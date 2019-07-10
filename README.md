# wopiHost
-----------------------------------
office online server 的 微软wopi协议项目.
如果office online server想要在线编辑，那么它一定要搭建

项目简介
----------------------------

原代码:ethendev

整理者:Rock-Ayl

开发环境所需：

windows 10 || MAC || windows 7

jdk1.8 

gradle 4、5

开发工具推荐：IEEA 2019

项目集成框架
-----------------------------------
spring 

fasterxml

搭建流程
------------------------------------
下载源码,用gradle管理,idea进行开发,设置jdk1.8

启动WopihostApplication的main

拼装office online server的路径并打开 具体我就不写流程了，该项目只是提供gradle管理的代码.

eg:

http://XXX.XXX.XXX.XXX/we/wordeditorframe.aspx?ui=zh-CN&rs=zh-CN&WOPISrc=http://XXX.XXX.XXX.XXX:8080/wopi/files/XXX.docx
