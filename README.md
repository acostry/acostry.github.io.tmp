# 联系方式

- 手机：13581649539
- Email：zhuxiulei@gmail.com
- 微信号：acostry

---

# 个人信息

 - 朱修磊/男/1985 
 - 硕士研究生/北京理工大学计算机科学与技术学院 
 - 工作年限：8+年
 - 个人微信公众号：[LearningBluemix](certificate/learningbluemix.jpg) (微信号：IBMBluemix, 介绍：关注 IBM Cloud (曾用名：IBM Bluemix）及相关云平台和云技术。当前订阅用户数：1000+) 
 - 技术博客：1 - [CSDN Blog](http://blog.csdn.net/acostry),   2 - [developWorks Blog](https://www.ibm.com/developerworks/community/blogs/acostry/?lang=en)
 - Github: [acostry](https://github.com/acostry)

---

# 工作经历

## IBM CDL - 中国开发实验室（ 2009年9月 ~ 至今 ）

### Cloud Availability Manager(AVM) / Emergency Response Manager(ERM) 

2017年3月至今，做为 AVM(刚开始叫ERM) 主要职责是维护和保证 IBM 云平台(公有云/专有云/私有云)的稳定性和可用性。当云平台上出现重大的影响客户的事件(CIE-Customer Impacting Events)时，第一时间确认并响应事件，协调一切资源，并领导各个相关团队尽一切努力快速解决问题，减少平均修复时间(MTTR-Mean Time to Repair)，并完成和追踪事件的根本原因分析(RCA-Root Cause Analysis)。

日常工作主要包括：在出现 CIE 之前，进行常规的警报监控，积极响应并处理来自各个相关团队的求助，尽可能在第一时间发现潜在的 CIE，并指导团队迅速处理；在 CIE 发生的时候，提供技术协助给运维及相关服务团队，参与解决问题，负责事件的外部用户通知以及内部的事件定期汇报，在必要的时候，与客户进行直接沟通，最大程度的去满足客户和快速响应来自各方面的请求；在 CIE 之后，一方面进行事件的根本原因分析，另一方面负责与受影响的服务团队进行对接，制定预防计划，防止相同事件再次发生。在 CIE 和 RCA 之外，我的主要时间用来进行团队内部的技术分享和学习，比如：创建并更新维护 AVM/ERM 运行手册(Runbook)，分享相关领域内技术，并不断深入学习云计算相关领域技术和产品。

在这个项目中，最困难的问题是如何高效的协调不同的团队来解决事件和进行事后的根本原因分析，我主要采用以下两个措施来应对：1. 提高自身领域内的技术能力，在事件发生时，提供切实有效的解决方案和关键建议。2. 不断提高软技能，提升自身领导力，在事件发生的紧急时刻，依然能够冷静的指导团队解决问题，在进行根本原因分析时，灵活采用各种有效的沟通方式，与相关团队一起制定切实有效的预防计划。通过持续的践行这两个措施，个人不但在技术上日益提高，而且还和各个服务团队建立起了良好的沟通渠道，这些都成为了高效完成工作的保障。

工作内容主要涉及的相关技术，产品和工具包括(但不限于)：IBM Cloud(Bluemix), IBM Container Service, Cloud Foundry, Docker, Kubernetes, Linux Shell, IBM Cloud Private, Go, Grafana, Pagerduty, ServiceNow, Slack等等。

### 云平台自动化测试

2013年初到2017年初，主要的工作职责是 IBM 云平台(公有云/专有云/私有云)的质量保证。工作的形式主要是测试开发，完善并自动化测试用例，构建整套的自动化测试流程，并搭建适用于整个云平台的 Pipeline(开发环境 --> 测试环境 --> 生产环境)，确保所有的组件和服务在部署到生产系统之前经过严格的测试和检验，整个过程全部自动化，以满足云计算时代的更新上线频率，尽可能的减少人为失误。

日常工作主要包括：自动化测试用例的设计与开发(Java/Junit/Maven/Jmeter)，内容涉及10+个云平台组件和服务的验收测试(AT)和系统集成测试(SIT); 搭建自动化测试框架(Jenkins/RTC/Docker)，每天定时执行所有的自动化测试用例，并将测试结果发送给用例的所有者，如有必要，进行问题诊断；为了构建云平台的 Pipeline, 基于已有的测试用例，搭建并持续运维全新的自动化测试框架(Jenkins/Git/Docker+Docker Registry/IBM UrbanCode Deploy/Shell)，每当发现有新的版本的组件和服务时，自动或定时的触发自动化测试流程，按照预定的顺序在不同的环境执行相关测试用例，如果测试全部通过，则将该组件和服务标位生产可用(Production Ready), 相反，则通知开发团队进行bug修复；日常的工作内容还包括对测试云环境的运维和问题修复，保证其可用性和稳定性；在中后期，我做为项目lead，带领团队不断优化测试用例，并持续改进自动化测试框架，和国外团队一起，高效完成云平台质量保证的工作。

在这个项目中，最困难的部分就是从传统的软件测试向云平台自动化测试的转变，很多传统的方法都不再适用于现代云平台的自动化测试。我的解决方法是：1. 拥抱新的技术，工具和开源框架，践行DevOps方法论，将持续集成(CI)和持续交付(CD)用在自动化的测试和开发中，构建更优化的测试用例和全新的测试框架。2. 借鉴业内领先的测试方法和理论，将精华部分引入到自己的测试过程中，提高测试工作的效率，优化测试流程。正是不断坚持这两种方法，使得团队可以圆满的完成云平台的自动化测试工作，在快速开发的迭代过程中，确保质量保证工作的高效性和可靠性。

### 云平台/云技术布道师

2013年初至今，一直都在从事 IBM 云平台和云技术的布道和推广工作，旨在国内传播云技术以及构建云相关生态系统。这些工作虽然繁琐，但是却很有价值：首先，可以直接面对国内的云开发者，了解第一手的需求和国内的云技术发展现状，并将这些信息反馈给公司内部开发部门，基于此可以更好的指导和开发适合国内企业和个人的云产品和解决方案。其次，在传播云技术的过程中，





我在此项目负责了哪些工作，分别在哪些地方做得出色/和别人不一样/成长快，这个项目中，我最困难的问题是什么，我采取了什么措施，最后结果如何。这个项目中，我最自豪的技术细节是什么，为什么，实施前和实施后的数据对比如何，同事和领导对此的反应如何。

---

# 专利和作品

## 发明专利
在 2016 年获得 [IBM Invention Plateau](certificate/Invention%20Plateau.jpg) 奖项

 - CN920150218US1 - LOCAL CONSUMPTION OF REMOTE SERVICES: 本专利是关于如何在本地开发时让应用程序可以直接使用部署在云端的各种服务。
 - CN920150241US1 - DEBUGGING CLOUD APPLICATIONS: 本专利提出了一种更轻量级，更简便的方法在本地远程调试运行在云端的应用程序。

## 技术文章
在 2015 年获得 [IBM developerWorks Accredited Author](certificate/IBM%20developerWorks%20Accredited%20Author.jpg) 称号 (Professional Author 和 [Contributing Author](certificate/IBMdeveloperWorksContributingAuthor.pdf))  

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

  - PyCon 2016 香港大会主题演讲: [Keynote talk: Developing Python Applications on Cloud](http://pycon.hk/2016/program/developing-python-applications-on-cloud/)    [录像回放](http://v.youku.com/v_show/id_XMzM1ODU4OTE3Mg==.html?spm=a2h3j.8428770.3416059.1)(从 00:59:00 开始)    [讲义](resources/PyconHK2016-Bluemix.pdf)
  - 视频：[IBM Bluemix - Why? What? AND How? (Chinese-中文版)](https://v.qq.com/x/page/p0193fp5d1z.html)
  - IBM 全球技术峰会 IMPACT2013: [A China BP Embraces Liberty in PowerLinux Virtualization Solution](resources/TAW-1822%20TeamSun%20Liberty%20V3.pdf) 
  - 公司内部及外部客户分享：1 - [IBM Bluemix Workshop](resources/IBM_Bluemix_WorkShop_V2.pdf),   2 - [WebSphere Application Server Liberty Profile](resources/WASV85_Jam_Liberty_Overview.pdf),   3 - [Modular & Dynamic OSGi Applications in WebSphere Application Server](resources/WASV8_Jam_OSGi.pdf)
  - 2012 年广发银行 WebSphere Workshop(负责翻译): [Introducing IBM WebSphere Application Server v8.5 - The Future Is Now](resources/AI%20Workshop%20CGB%20China%20Aug%202012%20client.pdf)
  - 2011 年北京理工大学共建系(软件学院): [我眼中的 IBM](resources/我眼里的IBM_XiuLei.pdf) 
  - 2010 年大连理工大学软件学院 授课 [IBM WebSphere Application Server On Windows V7管理培训(WA370)](http://www.avtechcn.com/course/was370/)

---

# 社团(区)工作

## China Cloud Computing Community
分别在 2015 年和 2016 年担任 IBM 大中华区的内部社团 C4(China Cloud Computing Community) 的主席。C4 的宗旨是“传播云技术，践行云理念，推进云计算成为公司转型的动力！” 在任职期间，带领团队组织并参与多次关于云计算的内外部分享(包括主题演讲，动手实验室，骇客马拉松等等)；成功举办了大中华区第一次 “IBM 云平台 Bluemix 冠军大赛” ；并参与公司大学合作部的项目，在大学进行关于 IBM 云平台和云计算的主题演讲以及相关课程验收。

## LearningBluemix 微信公众号
[LearningBluemix](certificate/learningbluemix.jpg) (微信号：IBMBluemix)是我的个人微信公众号，主要关注 IBM Cloud (曾用名：IBM Bluemix）及相关云平台和云技术，当前订阅用户数：1000+。该公众号大部分为原创文章，内容涉及 IBM 云平台，Cloud Foundry, Kubernetes 以及 Docker等云技术，旨在推广相关云产品和云技术在企业级领域的应用。

## Icap 中文社区
做为管理员以及主要的内容提供者，运营[Icap 中文社区](https://www.ibm.com/developerworks/community/groups/service/html/communitystart?communityUuid=84a69364-28a8-4f9e-ab63-4b22a408082b)。Icap 是 IBM Public Cloud(Bluemix) 的前身，是一个更加简便、快速的开发和管理云应用的平台，集合了 Mobile、WebSphere 以及 Cloud 的优势，将面向云的应用开发带入了一个新纪元！

---

# 其他

  - 为 IBM 公有云平台 Bluemix 骇客马拉松拍摄宣传短片: [Bluemix 短跑节——开发者锦标赛：够胆你就来](https://v.qq.com/x/page/u01531ihc0l.html)
  - 为 IBM Bluemix 市场推广短片的脚本进行审查和更正: 1 - [IBM Bluemix 快到让你没有时间享受工作](http://v.youku.com/v_show/id_XOTIwMzAzMzI4.html),  2 - [IBM Bluemix 做你最想做的程序](http://v.youku.com/v_show/id_XOTIwMzE2NDA4.html), 3 - [IBM Bluemix 帮你整合全球资源尽在“不言中”](http://v.youku.com/v_show/id_XOTIwMzE3MTAw.html)

---

# 技能清单
（我一般主张将技能清单写入到工作经历里边去。不过很难完整，所以有这么一段也不错）

以下均为我熟练使用的技能

- Web开发：PHP/Hack/Node
- Web框架：ThinkPHP/Yaf/Yii/Lavaral/LazyPHP
- 前端框架：Bootstrap/AngularJS/EmberJS/HTML5/Cocos2dJS/ionic
- 前端工具：Bower/Gulp/SaSS/LeSS/PhoneGap
- 数据库相关：MySQL/PgSQL/PDO/SQLite
- 版本管理、文档和自动化部署工具：Svn/Git/PHPDoc/Phing/Composer
- 单元测试：PHPUnit/SimpleTest/Qunit
- 云和开放平台：SAE/BAE/AWS/微博开放平台/微信应用开发

---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
