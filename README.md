###一、简介

SOHU-DBProxy是由 搜狐 数据库团队开发维护的一个基于MySQL协议的数据中间层项目。它在MySQL官方推出的MySQL-Proxy 0.8.3版本的基础上，
修改了大量bug，添加了很多功能特性。现在已经在sohu的公有云上使用，也在sohu视频和焦点业务线上使用
    
主要功能：

1 事物级的多路连接复用

2 负载均衡提高读性能，支持动态扩展

3 动态添加的SQL审核和过滤。能够统计的SQL长时间运行影响性能，并且阻止其运行 

4 用户连接限制

5 自动摘除宕机的DB

6 读写分离（当前版本没有，代码和测试已经完成，没有合并到当前版本）



###二、dbproxy详细说明

[1.二进制安装的包(支持redhat5/6)] (bin/)  

[2.快速了解dbproxy](doc/Getting_Started_with_DBProxy.pdf)

[3.安装](doc/dbproxy安装.pdf)

[4.命令参考手册](doc/dbproxy管理命令列表.pdf)

[5.测试报告](doc/dbproxy_测试报告.pdf)

[6.使用限制](doc/dbproxy使用限制.pdf)

[7.dbproxy的内部设计文档](doc/design_internal_doc)

###三、dbproxy的需求及Bug反馈方式

如果用户在实际的应用场景中有新的功能需求，或者在使用的过程中发现了bug，
欢迎用户发邮件至dba@sohu-inc.com，与我们取得联系，我们将及时回复。

