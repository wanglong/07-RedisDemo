# RedisDemo

## 第7章的Demo下载及更多资料
+ RedisDemo下载地址：https://github.com/das2017/RedisDemo
+ RedisDesktopManage下载地址：https://redisdesktop.com/
+ Redis官网：https://redis.io/
+ ServiceStack.Redis客户端：https://github.com/ServiceStack/ServiceStack.Redis
+ Redis命令大全：http://www.redis.cn/commands.html

## 内容简介
本书结合作者近几年的工作经验，总结了一套可直接落地、基于开源、成本低、可快速搭建的中小研发团队架构实践方法。本书共5篇22章，开篇是本书的导读；架构篇是设计思想的提升，包括企业总体架构、应用架构设计、统一应用分层等；框架篇主讲中间件和工具的使用，包括消息队列、缓存、Job、集中式日志、应用监控和微服务等；公共应用篇是技术与业务的结合，包括单点登录和企业支付网关；进阶篇是从架构到管理，包括技改案例、技术与业务的匹配与融合等。从架构、框架、公共应用，到案例实战和技术管理，本书将大公司的工程理念压缩应用到中小研发团队，使小团队也能构建大网站。

## 全书目录
### 第一篇 开篇——照着做，你也能成为架构师
#### 第1章 中小研发团队架构实践，附案例和代码
　　一、框架篇——工欲善其事，必先利其器<br />
　　二、架构篇——思想提升<br />
　　三、公共应用篇——业务与技术的结合<br />
　　四、进阶篇——从架构到管理<br />
　　五、案例参考和Demo下载<br />
### 第二篇 架构篇——思想提升
#### 第2章 企业总体架构规划
　　一、企业商务模型<br />
　　二、架构现状<br />
　　　　2.1 功能架构<br />
　　　　2.2 应用架构<br />
　　　　2.3 数据设计<br />
　　　　2.4 物理架构<br />
　　三、领域模型<br />
　　四、架构规划<br />
　　　　4.1 顶层架构规划<br />
　　　　4.2 网站功能规划<br />
　　　　4.3 应用规划<br />
　　　　4.4 SOA规划<br />
　　　　4.5 分层架构<br />
　　　　4.6 数据库规划<br />
　　　　4.7 物理规划<br />
　　　　4.8 其它<br />
　　五、架构实施<br />
　　六、案例参考<br />
#### 第3章 单个项目架构设计
　　一、初识架构设计<br />
　　二、应用架构设计案例<br />
　　　　2.1 功能清单<br />
　　　　2.2 用例图与用例活动图<br />
　　　　2.3 领域图<br />
　　　　2.4 接口设计<br />
　　　　2.5 分层设计<br />
　　　　2.6 代码实现<br />
　　　　2.7 其它设计项<br />
　　　　2.8 演化<br />
　　三、更多知识探讨<br />
　　　　3.1 设计表述探讨<br />
　　　　3.2 关于UML<br />
　　　　3.3 关于设计模式<br />
　　　　3.4 关于设计原则SOLID<br />
　　　　3.5 关于DDD<br />
　　　　3.6 设计不足与过度设计<br />
　　　　3.7 架构设计是艺术<br />
　　四、互联网公司的架构设计要怎么落地<br />
　　　　4.1 要不要做架构设计<br />
　　　　4.2 MVP与架构设计<br />
　　　　4.3 互联网公司是怎么做的<br />
　　　　4.4 应用架构要怎么落地<br />
　　五、你给技术打个分<br />
　　六、案例参考<br />
#### 第4章 统一公司应用分层<br />
　　一、为什么要统一应用分层<br />
　　二、统一应用逻辑架构<br />
　　三、分层规范实践<br />
　　　　3.1 项目命名规范<br />
　　　　3.2 业务逻辑层规范<br />
　　　　3.3 数据操作层规范<br />
　　　　3.4 实体层规范<br />
　　　　3.5 数据库连接配置规范<br />
　　　　3.6 配置文件规范<br />
　　　　3.7 静态资源文件规范<br />
　　四、互动问答<br />
　　五、Demo下载<br />
#### 第5章 生产环境诊断工具WinDbg
　　一、诊断工具简介<br />
　　二、诊断工具下载<br />
　　三、获取异常进程的Dump文件<br />
　　四、WinDbg使用方法<br />
　　五、一个真实案例<br />
　　六、Demo下载及更多资料<br />
### 第三篇 框架篇——工欲善其事，必先利其器
#### 第6章 RabbitMQ快速入门及应用
　　一、为什么要用消息队列RabbitMQ<br />
　　二、RabbitMQ简介<br />
　　三、RabbitMQ工作原理<br />
　　四、RabbitMQ基本用法<br />
　　五、Demo下载及更多资料<br />
#### 第7章 Redis快速入门及应用
　　一、Redis简介<br />
　　二、Redis数据结构<br />
　　三、Redis重要特性<br />
　　四、使用方法<br />
　　五、其它<br />
　　　　5.1 Redis Key命名规范<br />
　　　　5.2 常见问题<br />
　　六、Demo下载及更多资料<br />
#### 第8章 任务调度Job
　　一、Job简介<br />
　　二、WinJob<br />
　　三、HttpJob<br />
　　　　3.1 HttpJob的服务端实现<br />
　　　　3.2 HttpJob集中式管理平台<br />
　　　　3.3 HttpJob的优势与约束<br />
　　四、Cron表达式<br />
　　五、Demo下载及更多资料<br />
#### 第9章 度量工具Metrics
　　一、Metrics简介<br />
　　二、埋点Metrics.NET的方法<br />
　　　　2.1 Meter<br />
　　　　2.2 Histogram<br />
　　三、Grafana配置<br />
　　　　3.1 仪表盘设置<br />
　　　　3.2 面板Panel设置<br />
　　　　3.3 模板Templating设置<br />
　　　　3.4 设置TimeRange<br />
　　　　3.5 告警设置<br />
　　四、其它说明<br />
　　五、Metrics的使用价值<br />
　　六、Demo下载及更多资料<br />
#### 第10章 集中式日志ELK
　　一、集中式日志<br />
　　　　1.1 ELK简介<br />
　　　　1.2 ELK的架构<br />
　　二、配置方法<br />
　　　　2.1 Elasticsearch<br />
　　　　2.2 Logstash<br />
　　　　2.3 Kibana<br />
　　　　2.4 Filebeat<br />
　　三、使用方法<br />
　　　　3.1 Log4Net本地日志<br />
　　　　3.2 日志查询<br />
　　四、Demo下载及更多资料<br />
#### 第11章 微服务MSA
　　一、MSA简介<br />
　　　　1.1 MSA是什么<br />
　　　　1.2 MSA框架简介<br />
　　　　1.3 MSA框架实现架构<br />
　　二、MSA框架的使用<br />
　　三、微服务治理<br />
　　四、微服务网关API Gateway<br />
　　　　4.1 API Gateway的简介<br />
　　　　4.2 API Gateway的优点<br />
　　　　4.3 API Gateway的架构<br />
　　　　4.4 API Gateway的功能<br />
　　　　4.5 API Gateway的使用<br />
　　五、Demo下载及更多资料<br />
#### 第12章 搜索引擎Solr
　　一、Solr简介<br />
　　1.1 为什么要用搜索引擎<br />
　　1.2 Solr是什么<br />
　　二、Solr怎样工作<br />
　　　　2.1 Web管理UI<br />
　　　　2.2 Solr服务端的安装与配置<br />
　　　　2.3 增加SolrUpdateTime字段和触发器<br />
　　　　2.4 SolrNet<br />
　　　　2.5 使用Job同步数据到Solr<br />
　　　　2.6 准实时数据导入、删除以及查询<br />
　　三、Solr的特性<br />
　　四、Demo下载及更多资料<br />
#### 第13章 分布式协调器ZooKeeper
　　一、ZooKeeper是什么<br />
　　二、ZooKeeper工作原理简介<br />
　　　　2.1 ZooKeeper架构<br />
　　　　2.2 ZooKeeper数据模型<br />
　　　　2.3 Watcher：ZNode数据变化通知<br />
　　三、ZooKeeper的典型应用场景<br />
　　　　3.1 配置服务：ConfigServiceDemo<br />
　　　　3.2 Master选举：MasterElectionDemo<br />
　　四、Demo下载及更多资料<br />
#### 第14章 小工具合集
　　一、ORM工具<br />
　　　　1.1 Dapper.NET简介<br />
　　　　1.2 为什么选择使用Dapper.NET<br />
　　　　1.3 如何使用Dapper.NET<br />
　　二、对象映射工具<br />
　　　　2.1 为什么需要使用对象映射工具<br />
　　　　2.2 EmitMapper和AutoMapper简介<br />
　　　　2.3 EmitMapper的使用方法<br />
　　　　2.4 AutoMapper的使用方法<br />
　　　　2.5 EmitMapper和AutoMapper的优缺点<br />
　　三、IoC工具<br />
　　　　3.1 Autofac简介<br />
　　　　3.2 背景<br />
　　　　3.3 依赖倒置原则<br />
　　　　3.4 IoC<br />
　　　　3.5 依赖注入<br />
　　　　3.6 优点<br />
　　四、DLL包管理工具<br />
　　　　4.1 NuGet简介<br />
　　　　4.2 为什么要用NuGet<br />
　　　　4.3 使用方法<br />
　　五、Demo下载和更多资料<br />
#### 第15章 一键发布和测试之持续集成工具Jenkins
　　一、Jenkins简介<br />
　　二、Jenkins插件与相关工具<br />
　　三、Jenkins关键配置<br />
　　　　3.1 邮件配置<br />
　　　　3.2 角色及权限管理<br />
　　　　3.3 部署到集群<br />
　　　　3.4 接口自动化测试SoapUI<br />
　　　　3.5 界面自动化测试UFT<br />
　　　　3.6 回滚操作Rollback<br />
　　　　3.7 暂未解决的问题<br />
　　四、Jenkins的使用价值<br />
　　五、更多资料<br />
#### 第四篇 公共应用篇——业务与技术的结合
#### 第16章 单点登录SSO
　　一、单点登录简介<br />
　　二、SSO技术实现<br />
　　　　2.1 SSO服务端功能<br />
　　　　2.2 SSO客户端功能<br />
　　　　2.3 用户单点登录流程<br />
　　　　2.4 用户访问和单点注销<br />
　　　　2.5 应用接入与集成<br />
　　三、JWT规范<br />
　　四、更多资料<br />
#### 第17章 企业支付网关
　　一、企业支付网关介绍<br />
　　二、统一支付服务<br />
　　　　2.1 统一支付接口<br />
　　　　2.2 统一支付架构<br />
　　　　2.3 业务核心代码<br />
　　　　2.4 接口封装情况<br />
　　三、统一支付通知<br />
　　四、Demo下载<br />
### 第五篇 进阶篇——从架构到管理
#### 第18章 技改之路：从单体应用到微服务
　　一、系统背景<br />
　　　　1.1 技术规模<br />
　　　　1.2 单体应用<br />
　　　　1.3 主要问题<br />
　　二、前期工作<br />
　　　　2.1 架构部组建<br />
　　　　2.2 总体规划<br />
　　　　2.3 中间件构建<br />
　　三、技改实施<br />
　　　　3.1 数据库改造<br />
　　　　3.2 服务改造<br />
　　　　3.3 应用架构改造<br />
　　　　3.4 组织架构微调<br />
　　四、经验总结<br />
　　	4.1 过程总结<br />
　　	4.2 经验感悟<br />
　　	4.3 通盘无妙招<br />
　　五、互动问答<br />
#### 第19章 机票垂直搜索引擎之性能优化
　　一、行业背景与垂直搜索<br />
　　二、主要问题与解决方案<br />
　　三、静态数据与任务打底<br />
　　四、缓存策略与数据一致<br />
　　六、实时查询与三段超时<br />
　　五、政策匹配与算法优化<br />
　　七、小结<br />
#### 第20章 上云
　　一、为什么要上云？<br />
　　二、内部虚拟化和外部云化<br />
　　三、云选型<br />
　　四、上云八条<br />
　　五、成功上云<br />
　　六、上云总结<br />
#### 第21章 技术与业务的匹配与融合
　　一、技术与业务的抱怨<br />
　　二、问题出在哪里<br />
　　三、理解源于彼此的了解<br />
　　四、如何去匹配与融合<br />
　　五、什么在驱动公司发展<br />
#### 第22章 研发团队文化是怎么长出来的
　　一、神秘的文化<br />
　　二、遇到的问题<br />
　　三、解决办法<br />
　　　　3.1 部门共治<br />
　　　　3.2 搭平台，立作风<br />
　　　　3.3 搞氛围，激活团队<br />
　　　　3.4 更多管理工具<br />
　　四、总结与提升<br />
　　五、「长」出来的团队文化<br />

## 新书链接：
+ 京东链接：https://item.jd.com/40103964120.html
+ 当当链接：http://product.dangdang.com/1436599215.html
+ 天猫店铺：https://detail.tmall.com/item.htm?spm=a1z10.3-b.w4011-16861154605.39.46be1b8bGWSsmz&id=585204361262&rn=12e44ccc5bb398b74fdd72e49e2af64e&abbucket=9
