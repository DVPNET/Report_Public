[Behinder_v3.0] https://github.com/rebeyond/Behinder

###2021.4.8 v3.0 Beta 7 更新日志

修复：  
1.数据库查询内容显示不正常；  
2.关闭主界面后，虚拟终端后台线程继续请求；  
3.某些场景下中文路径显示乱码；  
4.优麒麟系统无法弹出窗口；  
5.备忘录不能自动保存；  
6.某些场景下提示数据库被锁定；  
7.目标https证书过期连接问题；  
8.Jar包体积缩小，Jar包执行不再区分操作系统平台，提供跨平台版本；  
9.去除了一些特征；  
10.其他一些问题；  

新增：  
1.反弹shell中增加CobaltStrike一键上线；  
2.新增Java内存马注入功能，支持多种Web容器，包括但不限于Tomact、jboss、weblogic；  
3.新增反向DMZ功能，可以将VPS或本地局域网监听端口映射进目标内网，在目标内网不出网的情况下，实现目标内网反向木马回连；  
4.反弹Shell支持一键穿透，在目标内网不能出网的情况下，可以实现将meterpreter、shell、CobaltStrike直接上线至本地、本地局域网主机、远程VPS。msfconsole、CobaltStrike Server不再需要部署在公网；  
5.新增Shell关键字搜索功能；  
6.新增shell批量存活检测功能；  
7.新增Shell多选删除；  
8.新增老版本数据库Shell批量导入；  
9.新增文件时间戳修改功能；  
10.文件管理UI细节优化；  
11.增加基于端口映射的的Socks代理；内网直接将Socks代理服务开到远程VPS；  
12.命令行优化，支持命令历史记录；  

补充：beta7版本客户端不再内置JavaFX库，请使用Java8运行；Java 11及以后的版本，需要下载JavaFX库；  
