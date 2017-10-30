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

父级路径    | 目录                    | 描述
---         |---                      |---
/opt/zimbra |                         | 由ZCS安装包创建
            | backup/                 | 备份目录，包含全备和增量备份数据
            | bin/                    | ZCS应用文件，包含附录A中的界面工具和命令行工具
            | cdpolicyd/              | Policy functions, throttling 
            | clamav/                 | Clam AV 病毒和反垃圾邮件引擎
            | conf/                   | 配置文件信息
            | contrib                 | 第三方脚本
            | convertd                | 转换服务
            | cyrus-sasl/             | SASL AUTH守护进程
            | data/                   | 包含LDAP, mailboxd, postfix, amavisd, clamav数据索引
            | db/                     | 数据存储
            | docs/                   | SOAP和技术相关文档说明
            | dspam/                  | DSPAM 反病毒系统
            | extensionsextra/        | 服务器不同类型的身份扩展验证
            | extensionsnetworkextra/ | 服务器不同网络版本扩展
            | httpd/                  | 包含Apache Web和拼写检查工具aspell
            | index/                  | 页面文件仓库
            | java/                   | java应用文件
            | jetty/                  | 包含mailboxd 应用实例，在webapps/zimbra/skins/里面里包含Zimbra UI 样式文件
            | lib/                    | 函数库文件
            | libexec/                | 内部使用的可执行文件
            | log/                    | ZCS服务器应用本地日志文件
            | logger                  | logger services的RRD和SQLite数据文件  
            | mysql/                  | MySQL 数据库文件
            | net-snmp/               | 用于收集统计信息
            | openldap/               | ZCS定制使用的openLDAP程序
            | postfix                 | ZCS定制使用的postfix程序
            | redolog/                | ZCS 当前事务日志
            | snmp/                   | SNMP监控文件
            | ssl/                    | 证书
            | store/                  | 消息仓库
            | zimbramon/              | 控制脚本和perl模块
            | zimlets/                | 包含Zimbra安装使用的Zimlet zip文件
            | zimletsdeployed/        | 包含Zimlets使用Zimbra web 客户端
            | zimletsnetwork/         | 包含网络模块安装使用的Zimlet zip文件
            | zmstat/                 | 以.csv存储的mailboxd 统计状态文件
