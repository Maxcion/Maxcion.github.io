---
layout: post_layout
title: 使用Github Pages搭建个人博客
time: 2019年02月27日 星期三
location: 长春
pulished: true
excerpt_separator: "```"
---

注册 [github](https://github.com) 已有三年之久，但是三年来未曾使用过



参考自：

Cyzus：[傻瓜都可以利用github pages建博客](http://cyzus.github.io/2015/06/21/github-build-blog/)

TTyb：[建站教程](http://www.tybai.com/gitblogfirst/_%E5%BB%BA%E7%AB%99%E6%95%99%E7%A8%8B.html)

感谢[Cyzus](http://cyzus.github.io/)和[TTyb](http://www.tybai.com/)！



## 1.注册github账号

打开[github](https://github.com/)网站进行注册

<img src="/assets/img/blogs/2019-02-27/1-1.JPG" />

然后登录



## 2.建立仓库

登录后点后上角去创建一个存储库

<img src="/assets/img/blogs/2019-02-27/2-1.jpg" />

填写基本信息

<img src="/assets/img/blogs/2019-02-27/2-2.jpg" />

Tips:

Repository name的格式为 你的用户名.github.io

默认Public

初始化README



## 3.设置仓库

在仓库页面进入Settings

<img src="/assets/img/blogs/2019-02-27/3-1.jpg" />

下拉鼠标看到GitHub Pages

此时默认开启成功

<img src="/assets/img/blogs/2019-02-27/3-2.jpg" />



## 4.配置本地环境

由于不太擅长使用DOS命令，因此我使用的是Github的一个图形界面

[Github客户端](https://desktop.github.com/)

安装完成，登录账号

关联存储库，clone到本地

然后就可以上传文件了



## 5.选择一个主题

下载一个jekyll主题到本地

[http://jekyllthemes.org/](http://jekyllthemes.org/)

解压，提取文件到你的clone到本地的库中

此时客户端中有许多Changes

简单描述Update，点击Commit to master递交，此时本地的状态已经记录

点击Fetch origin进行push

<img src="/assets/img/blogs/2019-02-27/5-1.jpg" />

此时就已经更新完成了



## 6.编写博客

使用Markdown来写个人博客

新的博客需要将.md文档放置于_posts文件夹

使用Github客户端即可上传