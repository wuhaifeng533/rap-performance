# RAP ![](https://api.travis-ci.org/thx/RAP.svg)

### What is RAP?
RAP can help WEB engineers manage API document efficiently by supplying a GUI edit tool, it can generate mock data, validate real request by analyzing API structure, make API doc as a strong dependency with the development workflow. With structured API data, RAP can do more while we can do less.

RAP通过GUI工具帮助WEB工程师更高效的管理接口文档，同时通过分析接口结构自动生成Mock数据、校验真实接口的正确性，使接口文档成为开发流程中的强依赖。有了结构化的API数据，RAP可以做的更多，而我们可以避免更多重复劳动。

<img src="http://gtms04.alicdn.com/tps/i4/TB19tgUKVXXXXXAXXXXAhCB5VXX-1222-646.png" width="600" />


### Why we use RAP?
* Enterprise level application. More than 350+ corporations including Alibaba Group are using RAP to manage their important API Docs!
* Fast and efficient technical support, continuously update. Go to issues list to find out how lively the community is!
* Free and open source, all things are under control!

### 为什么我们信赖RAP？
* 企业级应用，包括阿里集团在内得350多个企业都在使用RAP管理重要的接口文档。
* 快速高效的技术支持，持续的更新，去Issues看一看就知道有多热闹。
* 免费、开源，一切尽在掌握中！

### 如何使用RAP
1. 直接访问由作者维护的[rap.taobao.org](http://rap.taobao.org/)
2. 自己部署一个RAP服务器，参考最新Release部分

### 快速上手 quick guide
* English: [Quick Guide Manual](https://github.com/thx/RAP/wiki/quick_guide) at first.
* 中文：[Video Tutorial 视频教程](http://thx.github.io/RAP/study.html)

### 分支说明
* master: 最新代码会在master，所以master是最新的，但是不保证稳定。且有一些公司自用的东西，所以提交记录可以参考，但不能直接使用master分支。
* release：是相对稳定的最新代码分支，也是RAP对外打包的分支
* 其它分支：根据开发需要，大的版本会以版本号为分支名，打一些临时分支。

### 最新Release
* [Release](https://github.com/thx/RAP/releases)
* [如何部署RAP服务器](https://github.com/thx/RAP/wiki/deploy_manual_cn)
* [如何使用RAP编辑文档](https://github.com/thx/RAP/wiki/user_manual_cn)

### 其它LINKS
* 我想大概了解RAP => [Official Site 官网](http://thx.github.io/RAP)
* 我想查找详细的文档资料 => [Wiki/Documents/Manual 文档/手册](http://github.com/thx/RAP/wiki)
* 我想快速了解什么是RAP => [视频介绍](http://vodcdn.video.taobao.com/player/ugc/tb_ugc_pieces_core_player_loader.swf?version=1.0.20150330&vid=11622279&uid=11051796&p=1&t=1&rid=&random=6666)
* 我想快速上手RAP使用方法 => [视频教程](http://thx.github.io/RAP/study.html)
* 我要反馈问题 => [Issues](http://github.com/thx/RAP/issues)

### Architect
* Framework: Hibernate5 + Spring4 + Struts2
* Store: MySQL5 + Redis3
* Front End: Velocity + jQuery + qUnit
* Deploy: Tomcat + Docker
* CI: Travis

###rap-performmance的改动点
在原有的rapv0.14.1beta版上增加上增加了性能基数项。
接口具有多种属性，其中一种属性是性能属性，一个接口在特定环境和特定压力下表现出的tps和响应值，保存这些数据使得系统性能数据有存档的地方，完善接口属性




