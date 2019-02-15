# 联系方式
* 手机：15652803728
* Email：wangchao_96@163.com
* 微信号：W13755217682

# 个人信息
* 王超/男/1996
* 本科/江西农业大学软件学院
* 工作年限：2年
* 期望职位：JAVA
* 期望薪资：税前月薪15k
* 期望城市：北京

# 技能清单

* java基本功扎实，熟悉Java SE和Java EE技术，掌握JVM运作机制，了解常见算法和设计模式
* 熟练使用常用的MVC(SpringMvc/Struts2)、ORM框架(Mybatis/Hibernate)，熟悉常见的RPC（Dubbo）框架
* 熟悉分布式、缓存（Redis）、消息（RabbitMQ）等机制；
* 熟练使用MySQL,Oracle进行应用开发，熟悉数据库原理，对数据库事物、锁机制等原理有较深的了解
* 熟悉HTML/CSS/Javascript/Jquery及其周边常用框架
* 熟悉Linux系统，熟练使用Linux命令
* 熟练使用Svn/Git/Maven/Jenkins/SonarQube/ApiView/YAPI等版本管理、自动化部署工具


# 工作经历

## 卡友支付北京分公司 （2018 ~ 2019）

我认任职卡友支付北京分公司服务建设部门，
该部门后台系统主要由API模块、APP模块、运营后台模块、业务模块、第三方服务模块、公共服务模块以及数据模块组成。
后台的所有任务通过分布式任务系统进行任务管理。
整套系统部署在公司的私有服务器上，主要基于公司的Mysql集群和Redis集群做数据存储，使用RabbitMq集群做消息队列，
基于ZK集群搭建高可用系统，基于Dubbo框架做了整个系统的微服务化。

## 北京萌狮子科技有限公司 （2017 ~ 2018）

我认任职北京萌狮子科技有限公司公司研发部门，
主要负责App、运营后台产品需求分析与系统设计并对产品进行快速迭代开发，根据开发规范编写接口文档以及项目文档，
Nginx服务器运维，分析项目访问日志并生产可视化报告，分析原有项目瓶颈并对其进行重构。
前期后端项目为聚合项目，项目之间耦合较大，后期基于Dubbo框架做了整体系统的微服务化。


# 项目经历

### 逍遥推手App
* 项目介绍：信用卡办理、网络贷款、pos机办理推广平台；
基于SpringBoot，整合SpringMVC、MyBatis、Dubbo、Redis、RabbitMq的高可用服务；
* 工作描述：
项目搭建：整合SpringBoot简化配置，通过Maven实现多环境配置变量，整合Dubbo实现分布式服务以及集群容错；
微信公众号：微信Oauth2.0授权登录(redis缓存授权状态)，模版消息推送，自定义菜单；
权限模块：JWT实现登录控制，Intercepter+Annotation实现JWT校验；
订单模块：RabbitMq发放下单奖励（解耦、异步），支付宝支付，微信支付；
库存模块：RabbitMq推送集团ERP系统（解耦、异步）；

### 友刷App
* 项目介绍：pos机服务商业务拓展平台
* 工作描述：版本迭代、日常维护
机具采购：采购下单，采购单查询；
微信公众号：微信Oauth2.0授权登录；
账户模块：redis实现分布式并发控制，spring-task实现定时任务统计提现金额；
产品模块：首页展示产品以及产品排序缓存在redis避免重复查询；
支付模块：支付宝App支付，采用乐观锁实现并发控制（版本号+CAS）；

### 玩具超人App
* 项目介绍：玩具租赁电商平台
* 工作描述：
短信模块:多短信通道,线程池发送短信；
运力模块、库存模块:通过dubbo实现解耦以及熔断，提高主业务的稳定性；
优惠券模块：通过mq实现解耦以及异步，提高主业务系统的性能；
玩具列表模块：热门商品排序，通过重写比较器实现集合排序，使用redis缓存排序结果；
购物车模块：采用乐观锁实现并发控制（版本号+CAS）；
第三方授权模块：微信、京东、微博Oauth2.0授权登陆；

通过引入dubbo以及mq提高了系统在各种场景的性能以及稳定性;

### 玩具超人运营后台
* 项目介绍：基于SpringBoot,整合SpringMvc + shiro + mybatis 高可用性后台管理系统;
* 工作描述：
项目搭建：整合SpringBoot简化项目配置,通过Maven实现多环境配置变量;
日志分析模块：实现服务器日志按天分割，分析访问日志并生产可视化报告;
权限管理：shiro实现权限控制;
日志记录：登陆日志、操作日志、异常日志，Annotation+AOP实现日志解耦;
用户管理、角色管理、菜单管理：条件分页查询，POI导出Excle;

- - -

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
