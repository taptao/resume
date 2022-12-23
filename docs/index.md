 <center>
     <h1>陶明威 <img align="right" src="assets/head.png" width="80px"></h1>  
     <div>
         <span>
           <img src="assets/birth.png" width="18px">
             1996/4
         </span>
         ·
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             15623768970
         </span>      
   </div>
   <div>
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             543267868@qq.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/taptao">taptao</a>
         </span>
       	 ·
         <span>
             <img src="assets/resume.jpeg" width="18px">
             <a href="https://taptao.github.io/">resume</a>
         </span>
     </div>
 </center>



## <img src="assets/tools-solid.svg" width="30px"> 专业技能
- 熟练掌握 go 、java，熟悉使用python。
- 熟悉 Kubernetes / Docker
- 熟悉linux的虚拟化技术
- 熟悉使用 Mysql 进行开发，掌握 SQL 语句
- 熟悉使用基于 Spring boot 框架的 Java Web 编程

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历
- 奇安信科技集团有限公司    服务端研发  2019年08月 - 2022年11月  

  工作描述：  
  
  1) 参与主线版本功能的设计和开发
  1) 部署方案的设计与实现 
  1) 流量转发模块的开发和优化

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

**安全中台**		2022年9月 \- 2022年11月

```
项目描述：项目使用k8s部署，微服务架构和自研java框架实现安全中台能力。
责任描述：本人主要负责业务模块设计开发和maven插件设计开发。
（1) 设计并实现在级联或非级联场景下，集合工作流引擎，下发红头文件。并采用适配层方式隔离核心逻辑，用于适配多方产品。
（2) 插件开发，对接漏洞平台，实现编译期间检查是否存在不合规的jar包依赖，进行告警。
技术关键词：JAVA、k8s、工作流引擎、级联、maven插件
```

**云安全平台——服务器安全系统**		2021年11月 \- 2022年8月

```
项目描述：项目主要用于保障云服务器安全，为云服务器提供安全能力，如ips、ids、病毒查杀，以及提供资产信息的扫描功能。
责任描述：本人主要负责业务模块开发和流量转发驱动的维护和性能优化
（1) 业务层设计任务字段，通过任务调度服务下发核心层和数据展示。核心层向管理下发任务状态以及流速信息和熔断日志收集。
（2) 流量转发功能：性能优化。补充流速上报，熔断日志上报功能。
技术关键词：JAVA、redis、elasticsearch、mysql、任务调度、微服务、go性能问题排查。
```

**云安全平台——虚拟化安全系统**		2020年6月 \- 2022年8月

```项目描述：项目主要用于保障云服务器安全，为云服务器提供安全能力，如ips、ids、病毒查杀。整体分为server层和agent层。
项目描述：项目主要用于保障云服务器安全，为云服务器提供安全能力，如ips、ids、病毒查杀，以及提供资产信息的扫描功能。
责任描述：本人主要负责业务模块设计和开发和参与部署方案设计和开发。
（1) 安全日志处理。处理agent上报的日志信息，采用分区的方式增大并发量，处理后的日志也会不断地以不同的时间维度进行聚合。
（2) 升级回退。server端代码的升级回退，agent代码的升级回退。
（3) 双机集群HA设计和实现。通过keepalived机制实现IP的漂移。通过lsyncd机制实现文件和数据库的同步。
（4）通信模块开发。用于和server端进行通信（主要包含任务和策略的获取以及结果返回），以及和其他功能模块的交互。
（5）流量转发功能的模块化以及功能移植
技术关键词：JAVA、redis、sqlite、keepalived、lsycnd、go。
```

**云安全平台——流量分析系统**		2020年1月 \- 2021年5月

```
项目描述：项目主要用于分析以及转发云内产生的东西向和南北向的流量。通过有代理和无代理模式，覆盖私有云和公有云各种场景下的流量牵引和分析。
责任描述：本人业务模块设计和开发
（1）云平台同步。对接云平台的API，获取虚拟机、物理机、租户、集群等信息。目前对接过vsphere、阿里云和OpenStack及其衍生平台。
（2）优化流日志处理。将原有的Python进程处理改用flink处理。从kafka读取从agent上传的流日志，通过流量的五元组以及应用层信息不断聚合后，存入到postgresql中。后续定时根据聚合后的数据做更粗粒度的时间聚合。
（3）流量转发。开发用户态和内核态流量过滤和转发功能。
（4）限速熔断。可以自定义限速和熔断阈值，采用滑动窗口方式记录agent的CPU、MEM等信息，根据熔断阈值进行熔断决策。限速采用令牌桶的方式进行转发流速限速。
（5）流速统计。在vsphere场景，需要在安全虚拟机里面统计业务流速，采用pfring框架，采集流量信息，统计业务流速。
技术关键词：python、django、celery、rabbitMq、kafka、Redis、elasticsearch、云平台、go、linux tc、vlxan、gre、ovs、虚拟化网络。
```


## <img src="assets/trophy.jpeg" width="30px">奖项及作品
- 奇安信：优秀员工奖  2021/06  
  专利：《云内流量牵引方法及装置》、《流量监控方法及装置》  2022/03  

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历
- 硕士，华中科技大学，计算机科学与技术专业	2017年8月 - 2019年6月
- 学士，南昌航空大学，软件工程专业	2013年8月 - 2017年6月

