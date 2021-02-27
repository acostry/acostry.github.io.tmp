# 基本信息

 - 朱修磊/男/1985 
 - 联系方式：13581649539,  <zhuxiulei@gmail.com>  
 - 硕士研究生/北京理工大学/计算机科学与技术/2008-2010
 - 本科/安徽理工大学/计算机科学与技术/2004-2008
 - 工作年限：11年 (截止到2021)  
 - 工作地点：北京  
 - Github：[https://github.com/xiuleiyy](https://github.com/xiuleiyy)  
 - 技术博客：[https://blog.csdn.net/acostry](http://blog.csdn.net/acostry)   
 - 英文简历：[https://github.com/xiuleiyy/xiuleiyy.github.io/blob/master/EN.md](EN.md)    
 
---

# 工作经历

## IBM CDL - 中国开发实验室（ 2009年9月 ~ 至今 ）

### Cloud Availability Manager(AVM) / Emergency Response Manager(ERM) 

2019年12月至今：Senior Cloud Availability Manager (Sr. AVM),  AP Leader  
2017年3月到2019年11月：Cloud Availability Manager (AVM),  AP Leader

做为 AVM，主要职责是促进和优化 IBM 云基础设施、系统和服务的稳定性和可用性，具体内容包括：通过执行不断优化的事件恢复流程，来解决云平台上出现的重大的影响客户的事件（CIE-Customer Impacting Events）；管理和协调事件恢复流程以驱动云平台上的故障恢复；向高层管理人员和外部客户提供清晰完整的事件恢复过程与状态更新；协调多个团队的资源来进行故障恢复，促进弥合团队之间的合作，并推动事故期间的快速恢复；在必要时逐步升级事件级别，以获取恢复故障所需要的更多资源和专家；记录故障的恢复过程以及其中需要改进的地方；与问题负责人一起完成和追踪事件的根本原因分析(RCA-Root Cause Analysis)；识别并确定问题负责人需要改进的领域；利用工具和技术知识确保云服务的设计和交付达到其可用性目标；提供云环境的整体运行状况，并提出改进云服务的建议；专注于个人/团队的目标和专业效率的提升。

做为自动化工具的开发 Leader，负责这些工具的日常开发和运维，包括：
 - AVM Online Service：一个在线的服务网站，用来为所有 IBM 云服务团队提供 AVM 的服务信息（例如：事件管理、问题管理以及相关事件的报表分析等等）。
 - Slack Bots：用来优化 IT 服务管理的自动化工具，使用 Node.js 构建并运行在 Kubernetes 平台上。这些 Bots 可以用来帮助相关团队进行事件管理/问题管理/升级管理，通过与多个后台 IT 系统（ServiceNow/Pagerduty/Other Internal Systems ...）集成来实实现 IT 服务管理流程中的自动化。
 - Notification Generator：一个用来帮助 AVM 团队自动生成外部客户通告的在线工具。
 
### 开源项目贡献者 - Open Horizon (2020年7月 ~ 至今)

做为开源项目 [Open Horizon](https://github.com/open-horizon) 的主要[贡献者](https://github.com/open-horizon/open-horizon.github.io/graphs/contributors)，为这个开源项目初始构建了[网站](https://open-horizon.github.io/)，并进行持续的改进与优化。同时，领导并负责为中国用户构建(撰写、翻译)中文文档的工作。

### 布道云平台/云技术（2013年初 ~ 2017年2月）

2013年初到2017年2月，一直都在从事 IBM 云平台和云技术的布道和推广工作，旨在国内传播云技术以及构建云相关生态系统。首先，通过直接面对国内的云开发者，了解第一手的需求和国内的云技术发展现状，并将这些信息反馈给公司内部产品部门，基于此可以更好的指导和开发适合国内企业和个人的云产品和解决方案。其次，传播云技术的过程，也是个人不断学习新技术和提高业务能力的过程，不仅掌握了云技术，同时也了解了云技术在实际企业中的应用。

在布道中，主要通过如下几种方式：1. 在技术网站/博客/社交媒体等发表文章(例如：[文章列表](#技术文章)，[微信公众号](#learningbluemix-微信公众号)，[博客](#基本信息)等)。2. 参加公司内外部举行的技术峰会，进行交流和学习(例如：[演讲和讲义](#演讲和讲义)，PyConHK2016-主题演讲，第七届中国云计算大会-Bluemix Lab，2013 Qcon 北京峰会-Bluemix Lab, 每年度 IBM 大中华区技术峰会-Bluemix Workshop等)。3.为多家公司和企业介绍 IBM 云产品和云技术(例如：CCTV/清源云顶/KaiKeBa/21v/Taiji Smart-T等) 4. 举办并参加线上/线下的技术交流，骇客马拉松以及开发者见面会(例如：[IBM Bluemix开发者锦标赛评委](http://2015bmix.csdn.net/)，IBM 大中华区 Bluemix 冠军编程大赛，北京大学骇客马拉松，武汉大学-Bluemix校园行，Bluemix 开发者吐槽会等)。

### 云平台自动化测试（2013年1月 ~ 2017年2月）

2013年1月到2017年2月，主要的工作职责是 IBM 云平台(公有云/专有云/私有云)的质量保证。工作的形式主要是测试开发，完善并自动化测试用例，构建整套的自动化测试流程，并搭建适用于整个云平台的 Pipeline(开发环境 --> 测试环境 --> 生产环境)，确保所有的组件和服务在部署到生产系统之前经过严格的测试和检验，整个过程全部自动化，以满足云计算时代的更新上线频率，尽可能的减少人为失误。

日常工作主要包括：自动化测试用例的设计与开发(Java/Junit/Maven/Jmeter)，内容涉及10+个云平台组件和服务的验收测试(AT)和系统集成测试(SIT); 搭建自动化测试框架(Jenkins/RTC/Docker)，每天定时执行所有的自动化测试用例，并将测试结果发送给用例的所有者，如有必要，进行问题诊断；为了构建云平台的 Pipeline, 基于已有的测试用例，搭建并持续运维全新的自动化测试框架(Jenkins/Git/Docker+Docker Registry/IBM UrbanCode Deploy/Shell)，每当发现有新的版本的组件和服务时，自动或定时的触发自动化测试流程，按照预定的顺序在不同的环境执行相关测试用例，如果测试全部通过，则将该组件和服务标位生产可用(Production Ready), 相反，则通知开发团队进行bug修复；日常的工作内容还包括对测试云环境的运维和问题修复，保证其可用性和稳定性；在中后期，做为项目lead，带领团队不断优化测试用例，并持续改进自动化测试框架，和国外团队一起，高效完成云平台质量保证的工作。

在这个项目中，最困难的部分就是从传统的软件测试向云平台自动化测试的转变，很多传统的方法都不再适用于现代云平台的自动化测试。通过拥抱新的技术，工具和开源框架，践行DevOps方法论，将持续集成(CI)和持续交付(CD)用在自动化的测试和开发中，构建更优化的测试用例和全新的测试框架。借鉴业内领先的测试方法和理论，将精华部分引入到自己的测试过程中，提高测试工作的效率，优化测试流程。

### WebShpere 系统测试 （2009年9月 ~ 2012年12月）

2009年9月到2012年12月，主要的工作职责是 Websphere Application Server(WAS) 系列中间件产品的质量保证(主要包括系统集成测试和系统验证性测试)。团队主要负责从终端用户的角度出发，开发端到端的测试用例并执行，同时也为国内 WAS 中间件客户提供线下支持。

工作内容主要有：WAS V6/V7 版本在新版本系统操作系统上的验证性测试，WAS V7 OSGi/V8/V8.5 版本的系统测试，除了要执行测试用例外，还需要根据新功能开发新的测试用例；对国内 WAS 中间件客户进行客户支持(例如：华胜天成/广发银行/华为/中国电信/中国建设银行/中国工商银行/中国人民银行/用友等)

### 荣誉和奖项

 - [IBM Invention Plateau](https://xiuleiyy.github.io/certificate/Plateau.jpeg) ($1,200)
 - [IBM Technical Rock Star for Cloud Platform](https://xiuleiyy.github.io/certificate/TRS_Annual.pdf) ($13,000)
 - Solutions Excellence Award ($250)
 - [Social Business Impact Award](https://xiuleiyy.github.io/certificate/SocialBusinessImpactAward.jpg) ($1,000)
 - [IBM developerWorks Accredited Author](https://xiuleiyy.github.io/certificate/IBM%20developerWorks%20Accredited%20Author.jpg) (Professional Author 和 [Contributing Author](https://xiuleiyy.github.io/certificate/IBMdeveloperWorksContributingAuthor.pdf))
 - Manager’s Choose Award (多个)

### 认证
ITIL® Foundation Certificate in IT Service Management  2019-05-19
[IBM Cloud Certified on different areas](https://www.youracclaim.com/users/acostry/badges)

---

# 专利和作品

## 专利

 - CN920150218US1 - LOCAL CONSUMPTION OF REMOTE SERVICES: 本专利是关于如何在本地开发时让应用程序可以直接使用部署在云端的各种服务。
 - CN920150241US1 - DEBUGGING CLOUD APPLICATIONS: 本专利提出了一种更轻量级，更简便的方法在本地远程调试运行在云端的应用程序。

## 技术文章 

- [使用 IBM Bluemix 开发和部署 Python 应用](https://www.ibm.com/developerworks/cn/cloud/library/cl-cn-bluemix-python-application/)
- [如何使用 IBM Bluemix 开发下一代云应用](http://www.ibm.com/developerworks/cn/cloud/library/1512_zhuxl_bluemixapp/) 
- [初探 IBM Bluemix 带您领略平台云](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1406_zhuxl_bluemix/1406_zhuxl_bluemix.html)
- [详解 IBM Bluemix端到端开发体验](http://blog.csdn.net/acostry/article/details/42107551)
- [Protect your resources with the Bluemix App User Registry Add-on](http://www.ibm.com/developerworks/cloud/library/cl-oauthregistry-app/index.html)
- [使用 Bluemix App User Registry Add-on 保护资源](http://www.ibm.com/developerworks/cn/cloud/library/cl-oauthregistry-app/index.html)
- [如何在 WebSphere Application Server V8 中部署和管理 OSGi 应用](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1204_zhuxl_osgi/1204_zhuxl_osgi.html)
- [新一代轻量级应用服务器：WebSphere Liberty Profile Server 介绍](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1207_zhuxl_liberty/1207_zhuxl_liberty.html)
- [使用 WebSphere Liberty Profile Server 和 Eclipse 开发 OSGi 应用](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1208_zhuxl_libertyosgi/1208_zhuxl_libertyosgi.html)
- [使用 IBM Packaging Utility 定制 WebSphere Application Server 软件存储库](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1208_zhuxl_utilty/1208_zhuxl_utilty.html)
- [使用 Rational Development 工具和 WebSphere Application Server V8.5 开发基于 EJB 的 OSGi 应用](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1211_zhuxl_osgi/1211_zhuxl_osgi.html)
- [企业级 OSGi 带来的好处](http://www.ibm.com/developerworks/cn/websphere/techjournal/1112_zhuxl_osgi/1112_zhuxl_osgi.html)
- [如何在 AIX shared-system WPAR 中共享 WAS 安装文件](http://www.ibm.com/developerworks/cn/aix/library/1111_zhuxl_aixsharedwpar_was/)
- [WebSphere Edge Load Balancer 在IBM System z上的安装、配置和使用](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1110_zhuxl_welb/1110_zhuxl_welb.html)
- [如何在WebSphere Application Server V8中实现OSGi动态服务功能](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1109_zhuxl_osgi/1109_zhuxl_osgi.html?ca=drs-)
- [WebSphere 中池资源调优 - 线程池、连接池和 ORB](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1106_zhuxl_websphereenhancement/1106_zhuxl_websphereenhancement.html)
- [WebSphere Application Server V7 OSGi新特性介绍](http://www.ibm.com/developerworks/cn/websphere/library/techarticles/1104_suipf_ogsioverview/1104_suipf_ogsioverview.html)
- [WebSphere Edge Load Balancer 在 IBM AIX 7.1 上的安装、配置和使用](http://www.ibm.com/developerworks/cn/aix/library/1102_zhuxl_wesonaix/)
- 更多文章可以查阅个人微信公众号(ID: IBMBluemix)以及技术博客！

## 演讲和讲义

  - PyCon 2016 香港大会主题演讲: [Keynote talk: Developing Python Applications on Cloud](http://pycon.hk/2016/program/developing-python-applications-on-cloud/)    [录像回放](http://v.youku.com/v_show/id_XMzM1ODU4OTE3Mg==.html?spm=a2h3j.8428770.3416059.1)(从 00:59:00 开始-英文版)    [讲义](https://xiuleiyy.github.io/resources/PyconHK2016-Bluemix.pdf)
  - 视频：[IBM Bluemix - Why? What? AND How? (中文版)](https://v.qq.com/x/page/p0193fp5d1z.html)
  - IBM 全球技术峰会 IMPACT2013: [A China BP Embraces Liberty in PowerLinux Virtualization Solution](https://xiuleiyy.github.io/resources/TAW-1822%20TeamSun%20Liberty%20V3.pdf) 
  - 公司内部及外部客户分享：1 - [IBM Bluemix Workshop](https://xiuleiyy.github.io/resources/IBM_Bluemix_WorkShop_V2.pdf),   2 - [WebSphere Application Server Liberty Profile](https://xiuleiyy.github.io/resources/WASV85_Jam_Liberty_Overview.pdf),   3 - [Modular & Dynamic OSGi Applications in WebSphere Application Server](https://xiuleiyy.github.io/resources/WASV8_Jam_OSGi.pdf)
  - 2012 年广发银行 WebSphere Workshop(现场翻译): [Introducing IBM WebSphere Application Server v8.5 - The Future Is Now](https://xiuleiyy.github.io/resources/AI%20Workshop%20CGB%20China%20Aug%202012%20client.pdf)
  - 2011 年北京理工大学共建系(软件学院): [我眼中的 IBM](https://xiuleiyy.github.io/resources/我眼里的IBM_XiuLei.pdf) 
  - 2010 年大连理工大学软件学院 授课 [IBM WebSphere Application Server On Windows V7管理培训(WA370)](http://www.avtechcn.com/course/was370/)
---

# 社团(区)工作

## China Cloud Computing Community
分别在 2015 年和 2016 年担任 IBM 大中华区的内部社团 C4(China Cloud Computing Community) 的主席。C4 的宗旨是“传播云技术，践行云理念，推进云计算成为公司转型的动力！” 在任职期间，带领团队组织并参与多次关于云计算的内外部分享(包括主题演讲，动手实验室，骇客马拉松等等)；成功举办了大中华区第一次 “IBM 云平台 Bluemix 冠军编程大赛” ；并参与公司大学合作部的项目，在大学进行关于 IBM 云平台和云计算的主题演讲以及相关课程验收。

## LearningBluemix 微信公众号
[LearningBluemix](https://xiuleiyy.github.io/certificate/learningbluemix.jpg) (微信号：IBMBluemix)是我的个人微信公众号，主要关注 IBM Cloud (曾用名：IBM Bluemix）及相关云平台和云技术，当前订阅用户数：1000+。该公众号大部分为原创文章，内容涉及 IBM 云平台，Cloud Foundry, Kubernetes 以及 Docker等云技术，旨在推广相关云产品和云技术在企业级领域的应用。

---

# 其他

  - 为 IBM 公有云平台 Bluemix 骇客马拉松拍摄宣传短片: [Bluemix 短跑节——开发者锦标赛：够胆你就来](https://v.qq.com/x/page/u01531ihc0l.html)
  - 为 IBM Bluemix 市场推广短片的脚本进行审查和更正: 1 - [IBM Bluemix 快到让你没有时间享受工作](http://v.youku.com/v_show/id_XOTIwMzAzMzI4.html),  2 - [IBM Bluemix 做你最想做的程序](http://v.youku.com/v_show/id_XOTIwMzE2NDA4.html), 3 - [IBM Bluemix 帮你整合全球资源尽在“不言中”](http://v.youku.com/v_show/id_XOTIwMzE3MTAw.html)

---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。  

