#### 开源技术的集合：

 - Linux ，开源OS
 - Jetty ，web UI        
 - Postfix ，mail transfer agent (MTA)
 - MySQL，开源数据库
 - OpenLDAP， 开源的轻量级活动目录
 - Lucene， 搜索引擎
 - Autonomy, Inc. ，第三方软件可以把附件文件转为HTML
 - ClamAV, 反恶意软件病毒程序
 - SpamAssassin，反垃圾邮件程序
 - James/Sieve filtering, 邮件用的过滤器 
#### 使用的开放协议有：
 - SMTP
 - LMTP
 - SOAP
 - XML
 - IMAP
 - POP
#### 用倒的流行技术有：
- HTML5
- Javascript
- XML
- Java
#### 横向和纵向扩展：
- 每一个Zimbra mailbox都包含它自己的mailbox账号，关联的消息仓库和索引- Zimbra 支持增加系统资源的垂直扩展，也支持增加更多服务器的水平扩展
#### 方便的管理
- 用户和管理员可以通过web界面进行登录使用邮箱和进行管理

#### Zimbra Collaboration Server 架构
![image](https://res.cloudinary.com/liz/image/upload/v1509342159/ZCSArchitecture_phat37.jpg)

#### Zimbra 应用包



#### 文件目录
ZCS默认安装在/opt/zimbra


目录                                | 描述
---                                 |---
/opt/zimbra                         | 由ZCS安装包创建
/opt/zimbra/backup/                 | 备份目录，包含全备和增量备份数据
/opt/zimbra/bin/                    | ZCS应用文件，包含附录A中的界面工具和命令行工具
/opt/zimbra/cdpolicyd/              | Policy functions, throttling 
/opt/zimbra/clamav/                 | Clam AV 病毒和反垃圾邮件引擎
/opt/zimbra/conf/                   | 配置文件信息
/opt/zimbra/contrib                 | 第三方脚本
/opt/zimbra/convertd                | 转换服务
/opt/zimbra/cyrus-sasl/             | SASL AUTH守护进程
/opt/zimbra/data/                   | 包含LDAP, mailboxd, postfix, amavisd, clamav数据索引
/opt/zimbra/db/                     | 数据存储
/opt/zimbra/docs/                   | SOAP和技术相关文档说明
/opt/zimbra/dspam/                  | DSPAM 反病毒系统
/opt/zimbra/extensionsextra/        | 服务器不同类型的身份扩展验证
/opt/zimbra/extensionsnetworkextra/ | 服务器不同网络版本扩展
/opt/zimbra/httpd/                  | 包含Apache Web和拼写检查工具aspell
/opt/zimbra/index/                  | 页面文件仓库
/opt/zimbra/java/                   | java应用文件
/opt/zimbra/jetty/                  | 包含mailboxd 应用实例，在webapps/zimbra/skins/里面里包含Zimbra UI 样式文件
/opt/zimbra/lib/                    | 函数库文件
/opt/zimbra/libexec/                | 内部使用的可执行文件
/opt/zimbra/log/                    | ZCS服务器应用本地日志文件
/opt/zimbra/logger                  | logger services的RRD和SQLite数据文件  
/opt/zimbra/mysql/                  | MySQL 数据库文件
/opt/zimbra/net-snmp/               | 用于收集统计信息
/opt/zimbra/openldap/               | ZCS定制使用的openLDAP程序
/opt/zimbra/postfix                 | ZCS定制使用的postfix程序
/opt/zimbra/redolog/                | ZCS 当前事务日志
/opt/zimbra/snmp/                   | SNMP监控文件
/opt/zimbra/ssl/                    | 证书
/opt/zimbra/store/                  | 消息仓库
/opt/zimbra/zimbramon/              | 控制脚本和perl模块
/opt/zimbra/zimlets/                | 包含Zimbra安装使用的Zimlet zip文件
/opt/zimbra/zimletsdeployed/        | 包含Zimlets使用Zimbra web 客户端
/opt/zimbra/zimletsnetwork/         | 包含网络模块安装使用的Zimlet zip文件
/opt/zimbra/zmstat/                 | 以.csv存储的mailboxd 统计状态文件
