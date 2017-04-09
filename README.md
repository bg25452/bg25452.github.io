# 某科学的程序员
致谢
====================================
+ 感谢[Less官网](http://lesscss.cn/)的样式，本Jekyll框架的样式都是基于Less官网的样式直接拷贝过来的。只是重构了JS，并且加入了Jekyll语法而已。
+ 感谢[Github](https://github.com/)提供的代码维护和发布平台
+ 感谢[Jekyll](https://jekyllrb.com/)团队做出如此优秀的产品
+ 感谢[Solar](https://github.com/mattvh/solar-theme-jekyll)的原作者[Matt Harzewski](http://www.webmaster-source.com/)
+ 感谢luoyan35714(https://github.com/luoyan35714/LessOrMore.git)提供了一个好的博客模版


使用
====================================

下载
------------------------------------

使用git从[某科学的程序员](https://github.com/bg25452/bg25452.github.io)主页下载项目

``` bash
git clone https://github.com/bg25452/bg25452.github.io
```

配置
------------------------------------

`某科学的程序员`项目需要配置的只有一个文件`_config.yml`，打开之后按照如下进行配置。

> 特别注意`baseurl`的配置。如果是`***.github.io`项目，不修改为空''的话，会导致JS,CSS等静态资源无法找到的错误

``` bash
name: 博客名称
email: 邮箱地址
author: 作者名
url: 个人网站
### baseurl修改为项目名，如果项目是'***.github.io'，则设置为空''
baseurl: ''
resume_site: 个人简历网站
github: github地址
github_username: github用户名称
FB:
  comments :
    provider : cloudtie
    cloudtie :
        short_name : cloudtie账户
```

如何写文章
------------------------------------

在`bg25452.github.io/_posts`目录下新建一个文件，可以创建文件夹并在文件夹中添加文件，方便维护。在新建文件中粘贴如下信息，并修改以下的`titile`,`date`,`categories`,`tag`的相关信息，添加`* content {:toc}`为目录相关信息，在进行正文书写前需要在目录和正文之间输入至少2行空行。然后按照正常的Markdown语法书写正文。

``` bash
---
layout: post
#标题配置
title:  标题
#时间配置
date:   2016-08-27 01:08:00 +0800
#大类配置
categories: document
#小类配置
tag: 教程
---

* content
{:toc}


我是正文。我是正文。我是正文。我是正文。我是正文。我是正文。
```

执行
------------------------------------

``` bash
jekyll server
```

效果
------------------------------------
打开浏览器并输入URL`http://localhost:4000/`,回车。


关于作者
====================================

为了工作努力学习的程序猿。更多个人信息和联系方式[机密]。

关于打赏
====================================

你可以为了我的工作打赏！以激励我做出更好的东西。

支付宝
----------------

<img src="/styles/images/zhifubao.PNG" alt="支付宝二维码付款给黑水" width="310" />

微信
----------------
<img src="/styles/images/weixin.png" alt="微信二维码付款给黑水" width="310" />
