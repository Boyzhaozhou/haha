# E20 h5
将工作期间的H5代码进行整理

分为touch版和scroll版

touch版的只有项目demo，没有模板可供使用。

scroll版提供模板。

gulp 目录是配置好的gulp环境

使用npm install下载依赖包

针对常规页面的开发，可以一键使用。

在命令行进入项目目录 执行 gulp dev 即可进入开发模式

代码更新浏览器同步刷新，如需手机调试，在当前cmd查看下行ip地址的链接，手机访问即可。

ps:保证电脑和手机处于一个局域网，连接同一个无线网。

个别手机有访问不了的情况，可尝试电脑链接网线或者无线网，使用360wifi进行本电脑分发wifi，手机使用此wifi

1.npm install 下载依赖包

2.gulp dev 进入开发模式

3.gulp build 打包

4.在gulpfile.js文件里注释了一段upload的上线配置，打开注释 可以直接上传ftp文件目录，假设用ftp的话。