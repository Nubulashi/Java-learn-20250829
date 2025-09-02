# Java学习记录

## Java架构师进阶之路
* Java初级工程师
	* 掌握Java核心技术
	* 累计代码编写量
	* 熟练使用应用框架开发
* Java中级工程师
    * 掌握Java核心技术
    * 了解大并发、大数据、大模型
    * 根据系统设计，独立完成对应模块功能开发
* Java高级工程师
	* 掌握Java核心技术+云原生
	* 熟悉大并发、大数据、大模型
	* 具有高并发、高性能系统的设计与开发能力
* 资深开发/架构师/技术专家
	* 掌握Java核心技术+云原生
	* 深入理解大并发、大数据、大模型
	* 丰富积累某个领域的经验，发现和解决技术问题并在业务中推广
	* 团队建设、管理能力，主导系统设计与保持产品技术竞争力
***
## Java核心技术
### 计算机基础
* 计算机操作基础
* 计算机组成原理
* 计算机网络
* 计算机编译原理
###  Java编程基础
#### JavaSE初阶
* 初识Java
* IDE集成开发工具-IDEA
* 数据类型
* 运算符
* 流程控制
* 方法的定义、调用、重载
* 数组
#### JavaSE中阶
* 面型对象
* 异常
* 常用类
* 集合
* IO流
* 多线程
* 网络编程
#### JavaSE进阶
* Junit 注解 枚举
* 反射
* Lambda表达式
* Stream
* jdk新特性
#### 初级项目
* 小鲨鱼记账系统
* 双色球彩票
* 披萨商店点餐系统
* 贪吃蛇小游戏 
###  JavaWeb技术 
* 前端之HTML
* 前端之CSS
* 前端之JS
* 前端之Ajax
* 前端之JQuery
* 前端之VUE3
* Servlet和JSP
* 过滤器监听器
* Java模块引擎之Freemarker
* ECMAScript6
### 数据库+常用工具
* MySQL基础应用
* Redis_高效NoSQL数据库
* Java连接数据库技术-JDBC
* 团队开发和版本控制工具-GIT
* Maven实战教程
* Linux基础命令
### Java开发框架
* Spring6
* SpringMVC
* MyBatis实战
* MyBatisPlus实战教程
* SpringDataJPA实战教程
* SpringBoot3
* RPC远程服务调用
* Spring Cloud Alibaba基础应用
* Admin&Sleuth&Zipkin
* Skywalking链路追踪
* Apollo配置中心
### 企业级项目
1. **合家云社区物业管理平台**
	* 本服务管理系统主要针对各大厦、小区、批发市场的物业管理部门，采用前后端分离技术和数据库技术为其提供全方位的物业管理。通过学习此项目，此项目会从整体架构设计，到具体业务需求分析，到实际落地开发，可以让没有项目经验的学员，通过此项目的学习和开发，来学习普通项目的开发流程，具体开发细节，以及积累项目经验。
	* 后端架构：SpringBoot+SpringMVC+MyBatisPlus+ElasticSearch+SpringSecurity
	* 前端架构：阿里 Ant Design+vue
2. **运营商短信云中台**
	* 系统整合 企业、短信平台、运营商网关 。由企业通过接口来发起短信发送；短信平台完成用户鉴权、扣费、等各种短信下发策略控制、流量控制等工作；通过运营商网关下发短信。客户可以登录管理平台查询、搜索统计自己下发的短信等功能，并根据业务对接不同类型短信下发。
	* 技术架构：SpringBoot + SpringBoot + SpringCloud Alibaba + Elastic-Job + Netty + Redis + Elasticsearch + RabbitMQ + Docker + Jenkins + SnowFlake + Harbor + Kubernetes
3. **医疗His系统微服务架构**
	* 在线医疗平台是以完整的基层医疗机构信息化解决方案为出发点，打造链接诊所、医生、患者、一站式互联网医疗服务系统，深度挖掘了基层医疗机构需求，解决其真正痛点，提供医疗前沿资源及信息共享等、全面提升医疗管理质量，可执行落地的综合性解决方案。由本次疫情的教训，后期国家定会加大医疗系统的投入，学完本项目之后可以对医疗体系有深入的认识，为以后扣开医疗系统公司的大门打下坚实的基础，也更加巩固了分布式相关的中件的实战用法，为高薪增添一份可靠的技术保障。
	* 后端技术架构： Spring Boot + Mybatis Plus +Shiro+ Spring Cloud Alibaba+ Redis+ Hutool + fastdfs + Swagger-ui + Mycat + Docker + ECS +nginx+linux
	* 前端技术架构： Vue + elementui+ sass + axios
### 核心架构源码
* 学习源码方法论
* Spring 底层源码
* SpringMVC源码
* Mybatis源码
* Springboot源码
* SpringSecurity源码
* SpringCloud/Alibaba源码
	* Nacos深入源码
	* Ribbon深入源码
	* Loadbalance深入源码
	* OpenFeign深入源码
	* Sentinel 深入源码实战
	* Gateway深入源码
	* seata深入源码
* Dubbo源码
### 中间件源码
* Netty源码
* RocketMQ源码
* Kafka源码
* Hotspot源码
* C语言深入剖析Redis6.x架构源码
* Zookeeper源码
* ELK源码  
### 案例设计
* 用户系统案例设计
* 网关系统设计
* 用户系统案例设计
* 电商订单系统设计
* 开放平台设计-API设计与管理
* 微信中用户管理、消息管理、消息传递的设计方案
* 微信共享位置和对讲机的设计方案
* 微信共享位置和对讲机的设计方案
* 超高并发百万用户在线直播弹幕系统方案
* 日活百亿级请求的大型电商平台红包系统
* DAU上亿系统的互关与点赞系统设计方案
* 类12306的百万并发互联网票务系统设计
* 解除核心系统单地域限制的异地多活方案
* 大型电商系统商品详情页秒杀系统设计专题
* 大型项目中台建设方案
### 架构设计
* DDD领域驱动设计
* 分流设计
* 服务并行与并发
* 缓存设计
* 存储设计
* 可靠性设计
* 应用保护设计
* 着眼未来云原生
* 海量数据处理
### 服务保障之DevOps
* 持续集成CI/CD Gitlab/Jenkins 
* JIRA/禅道
* Deploy: docker vagrant puppet chef ansible saltstack k8s Istio（2h）
* 镜像仓库:Harbor
* 监控：ELK Zabbix Prometheus Grafana
* 代码检测SonarCube
***
## Java与大并发
### 线程与高并发调优
* 颠覆认知的百万并发架构内幕
* Disruptor框架如何用单线程实现百万级QPS？
* 阿里双11订单系统的指令重排序灾难现场
* JDK19虚拟线程如何让锁机制作废
* 为什么线程池要用SynchronousQueue？
* 线程池参数设置错误引发P0级事故
* 高频交易系统1纳秒级写入的跳表优化
* 京东订单履约系统的异步编排CompletableFuture
### JVM性能调优
* 类加载之阿里双11的秒级启动优化
* JVM栈的幽灵问题：：什么让阿里云函数计算崩溃
* 为何G1选择混合模式，而ZGC使用“染色指针”
* 大厂垃圾收集器选型内幕
* 如何用Arthas在线诊断生产环境死锁？
* 基于机器学习的GC调优
* 百万并发JVM参数实战
### Tomcat性能调优
* 大厂生产级核心参数调优
* 压测脚本+监控三板斧
* Tomcat从内核到架构的全链路调优
### Nginx性能调优
* 负载均衡算法和权重
* 动静分离之5倍性能提升的秘籍
* Keepalived双主热备方案
* Redis+Lua分布式限流
* nginx多维度爬虫攻防战
### LVS负载均衡调优
* 字节跳动DR模式性能提升到200万QPS
* 百万并发DR模式配置模板
* TUN隧道技术——跨机房容灾的终极方案
* Keepalived脑裂检测方案
### 缓存中间件调优
* 阿里Redis支撑100万QPS的配置内幕
* 美团技术内幕之Caffeine多级缓存
* EhCache企业级实战
### 消息中间件调优
* RabbitMQ调优实战
* 字节跳动Kafka万亿级参数调优
* RocketMQ电商实战双11百万订单秒级削峰
* 腾讯云Pulsar万亿级配置
### 分布式调度调优
* Quartz-百万级任务调度优化
* Elastic Job-弹性分布式任务调度实战
* XXL Job-亿级任务调度架构设计
### 高效网络通讯框架调优
* Dubbo-百万TPS高并发架构优化
* RPC/GRPC-低延迟通信极致优化
* Restful API-高性能设计最佳实践
* Netty-千万级连接高吞吐实战
### 分布式解决方案与调优
* 分布式锁-Redisson高并发锁优化
* 分布式事务-Seata百万级TPS调优
* 分布式ID-雪花算法与美团Leaf优化
* 分布式幂等-金融级高可靠方案
* 分布式存储-分库分表+海量数据治理
* 注册中心-Nacos集群优化
* 配置中心-Nacos/Apollo万级配置
* 分布式会话-千万用户无状态架构
* 分布式任务-弹性调度与资源隔离
* 负载均衡-LVS+NGINX亿级流量调度
* 熔断降级-Sentinel百万QPS防护
* 限流隔离-高并发系统稳定性保障
### 大并发落地项目
1. **飞滴出行网约车项目**
	* 核心架构 SpringCloudAlibaba 高可用微服务设计
	* 从0到1手敲代码 表设计→业务逻辑→微服务联调
	* 专为转型者打造 传统软件→互联网微服务实战跃迁
	* 就业护航体系 项目简历编写+高频面试题破解
	* 技术栈全景 SpringBoot+SpringCloudAlibaba+Redis+JWT+Seata+RocketMQ
2. **亿级流量商城全链路实战**
	* 15大微服务模块 从需求分析到云端部署
	* 三高架构优化 搜索/网关/链路追踪方案对比
	* 企业级技术矩阵 SpringCloudAlibaba+ElasticSearch+RocketMQ+Docker
	* 全栈式教学 前端Vue+后端微服务+DevOps部署
3. **高并发游戏后端真实项目—英雄传说**
	* Netty千万级长连接 WebSocket+Protobuf极致优化
	* 7大游戏服务器核心技术 异步IO/反射动态编译/多线程并发控制
	* 架构灵魂四问 单线程VS多线程/数据库异步操作/并发处理/代码简化
	* 技术架构：Netty+WebSocket+Protobuf+多线程架构+Javassist
***
## Java与大数据
### 大数据存储
* Mycat+ShardingSphere双引擎方案
* Elasticsearch亿级数据毫秒检索
* MongoDB文档存储+Neo4j图数据库
* MinIO对象存储+HDFS分布式文件系统
* HBase列式存储+Hive数据仓库
### 大数据计算
* Hadoop MapReduce/Yarn调度体系
* Hadoop分布式资源调度框架Yarn
* Spark SQL/Streaming全栈方案
* Flink实时数仓与状态计算
* Lambda架构批流一体化实现
### 大数据落地项目
1. **电商日志分析和数据挖掘综合项目**
	* 核心架构 Lambda架构+Hadoop生态全链路实现
	* 数据智能 HiveSQL分析+机器学习模型训练
	* 技术矩阵 HDFS+Hive+HBase+Sqoop+Flume
	* 实战特色 从日志采集到商业决策的全流程开发
2. **实时交通监控平台项目**
	* 秒级响应 Flink实时处理道路违规行为
	* 可视化大屏 警力资源智能调度系统
	* 技术架构 Kafka+Flink+Redis+Druid实时数仓
	* 行业价值 提升城市交通管理效率300%
3. **基于Kappa架构的Flink实时数仓综合平台**
	* 架构革新 Kappa架构替代传统Lambda架构
	* 实时推荐 用户行为秒级分析+精准广告投放
	* 技术栈 Flink+ClickHouse+Phoenix实时OLAP
	* 业务突破 节假日故障预警响应速度提升10倍
4. **湖仓一体电商数据分析平台**
	* 架构融合 数据湖(Iceberg)+数据仓库一体化
	* 双流处理 FlinkCDC实现实时离线数据同步
	* 技术全景 Kafka+Iceberg+ClickHouse+SpringBoot
	* 商业价值 实现全渠道用户行为统一分析
5. **商品推荐系统综合项目**
	* 算法体系 SparkMLlib+TextRank多模型融合
	* 场景优化 解决电商信息过载核心痛点
	* 技术架构 Spark+Redis+TF-IDF特征工程
	* 效果提升 商品转化率提高45%
6. **音乐数据中心数仓综合平台**
	* 海量数据处理 日亿级用户行为分析
	* 技术架构：HDFS+Hive+Spark+SparkSQL+Kylin+Sqoop+ClouderaManager+SpringBoot+Superset+数据仓库模型设计
	* 技术生态 Hive+Sqoop+Superset可视化
	* 商业洞察 机器分布优化节省运维成本30%
***
## Java与大模型
### Java开发必知的AI知识
#### 什么是AI
* AI相关概念辨析
* AI发展史
#### AI发展与子领域
* 自然语言处理（NLP）
* 计算机视觉（CV）
* 语音技术
* 多模态与跨领域
* 决策规划决策与规划
* 推荐系统
* 知识图谱
* 机器人学（Robotics）
* 自动驾驶
#### 什么是大模型
* 大模型为什么叫大模型？
* 大模型为什么连小学数学题都能算错
* 大模型发展预测
* DeepSeek
* OpenAI
* 通义千问（Qwen）
* 盘古大模型
* 智谱AI
* 文心大模型
#### 大模型核心原理基础
* Transformer架构
* 推理与优化
* 预训练与微调范式
* 人类反馈强化学习
* GPT系列（自回归模型）
* BERT系列（自编码模型）
* 多模态模型
### SpringAI深度实践
#### Spring AI入门
* Spring AI概述
* 依赖管理与版本管理
* Spring AI示例
#### AI模型API
* AI模型-Chat
* AI模型-Text to Image
* AI模型-Audio Transcription
* AI模型-Text to Speech
* AI模型-Embedding
* 同步与流式API
* 模型特定功能
#### 向量存储API
* SQL-like元数据过滤API
* 14种向量数据库入门与配置
#### 自动配置
* Spring Boot自动配置
* AI模型和向量存储的启动器
#### ETL数据工程
* 数据与向量数据库
* 检索增强生成模式
#### SpringAI实战
* 法律咨询助手
* 童话故事编写
* 医疗知识问答平台
* 数据查询智能助手
* 技术手册生成助手
* 爆款标题生成助手
* 智能客服机器人
### Langchain4j全链路开发
#### LangChain4j简介
* 什么是LangChain4j
* LangChain4j的功能定位
#### LangChain4j的特点
* 与SpringAI分析对比
* Java生态集成
* 大语言模型与Java的双向调用
#### LangChain4j的核心功能
* 提示模板
* 聊天记忆管理
* 输出解析
* 代理（Agents）
* 检索增强生成（RAG）
#### LangChain4j实战
* 电商客服机器人
* 电商智能推荐助手
* 电商平台的智能客服系统
* 电商数据分析与报告生成
***
## Java与云原生
### 云服务演进（XaaS）
* IaaS：基础设施即服务（AWS EC2/Aliyun ECS）
* PaaS：平台即服务（K8s/OpenShift）
* SaaS：软件即服务（钉钉/企业微信）
* FaaS：函数即服务（AWS Lambda/Aliyun FC）
* BaaS：后端即服务（Firebase/MongoDB Atlas）
### 云原生核心架构
* Docker：容器化与镜像优化实战
* Kubernetes：亿级调度架构+核心源码解析
* Prometheus：万亿指标监控+自定义Exporter开发
* Istio：服务网格流量治理与熔断策略
### 云原生DevOps体系
* CI/CD：GitLab+Jenkins流水线优化
* KubeSphere：多云集群管理与可视化运维
* Terraform：基础设施即代码（IaC）自动化
### Serverless与混沌工程
* Serverless框架：Knative/OpenFaaS实战
* 混沌工程：大规模微服务故障注入与容灾演练
### 云平台建设方案
* 公有云：阿里云/华为云高可用架构
* 私有云：基于K8s的企业级云平台搭建