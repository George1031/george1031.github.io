---
layout: post
slug: hr example
---
# python-pip源

_**因为国内访问pycharm下载库会有波动，有时候不稳定，导致无法安装第三方库
以推荐几个国内pip的源，帮助大家下载库**_

```
  阿里云 http://mirrors.aliyun.com/pypi/simple/
  中国科技大学 https://pypi.mirrors.ustc.edu.cn/simple/
  豆瓣(douban) http://pypi.douban.com/simple/
  清华大学 https://pypi.tuna.tsinghua.edu.cn/simple/
  中国科学技术大学 http://pypi.mirrors.ustc.edu.cn/simple/

```
#### 使用方式比较简单:
永久改源-只需要在pycharm-setting-python interpreter-+-manage repositories-添加新的源 <br/>
临时改源-在安装库后面加入-i 源地址
```
例：
pip install pillow -i https://pypi.mirrors.ustc.edu.cn/simple/
```

#### linux修改源
修改linux文件 ~/pip/pip.conf(如果没有文件自己创建)，内容如下：
```
[global]
index-url = https://pypi.mirrors.ustc.edu.cn/simple/
```
