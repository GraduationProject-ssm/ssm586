# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm586连锁超市会员管理系统+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1t58veLEnL?p=182)


# 绪论
## 1.1研究背景与意义
### 1.1.1研究背景
近年来，第三产业发展非常迅速，诸如计算机服务、旅游、娱乐、体育等服务行业，对整个社会的经济建设起到了极大地促进作用，这一点是毋庸置疑的。现下，国家也出台了一些列的政策来支持和鼓励第三服务产业的发展与完善，用以带动社会经济的发展[1]。所以，整体来说，国家是比较提倡发展第三方服务行业的。纵观计算机领域的发展历程，从计算机的诞生到现在，已经有几百年的历史了，计算机应用技术目前也处于成熟阶段，并且许多相关的研究人员也在提出较新的技术，不断地发展和完善计算机领域。再到如今，计算机已经发展成为一个比较热门的行业了。在高校中，计算机、人工智能等专业热度非常高，许多学生在选择专业的时候，大都优先考虑计算机专业。在社会上，计算机类行业也成为了比较受欢迎的行业，从在浏览器中访问的网址，到手机上的各种应用程序，到大型的软件服务设备，基本上都离不开计算机技术支持，以及硬件的支撑。

如今，互联网几乎遍布于世界的各个角落，人工智能、大数据占据的越来越重要的社会地位，比如疫情期间，通过大数据技术进行筛查，确定哪些人员无接触史，哪些人员需要重点观察，由此可以在极短的时间内，以最快的速度对疫情进行防控。在这个大背景环境的推动下，本人通过学习Java语言、MySQL数据库、SSM框架等相关的计算机技术，打好坚实的技术基础，方便后期对系统进行研发。而后再通过对系统进行需求分析、可行性分析、总体功能设计等工作准备，确定系统的总体功能需求，方便接下来详细地系统功能模块进行设计和实现，最后成功的研发了一款基于SSM的连锁超市会员管理系统。本系统改善了传统的管理模式，将原先的手工记录和管理信息，改进为使用计算机存储和管理信息记录，极大地方便了工作人员对相关数据进行处理，为连锁超市节约了不少的人员费用和管理开销，并且能够在较短的时间内响应用户的需求，这种便捷的操作，对于用户来说可以节省了不少时间和精力，也省去了不少的麻烦，极大了方便了用户。
### 1.1.2研究意义
传统的连锁超市会员信息管理模式，主要是以人力为主进行管理和控制，由工作人员负责登记用户信息，再通过对照之前的信息记录，确定是否给用户提供相关的使用需求，以及如何提供能让用户满意的使用需求。这种管理模式已经适应不了时代的变化了，正在不断地走下坡路，并且逐步被信息化管理模式所取代。所谓的信息化管理模式，是现在主流的一种管理模式，其通过与计算机技术相结合的方式，对行业的整个工作模式和服务流程进行改进和完善。其主要通过使用计算机等设备，将工作服务流程电子化，并且进行存储记录，用以提高行业整体的服务水平。结合使用计算机技术，本人研发出一款基于SSM的连锁超市会员管理系统，采用电子化的方式对数据信息进行存储，便于工作人员对相关信息进行记录和管理，有利于提高连锁超市的工作运营效率以及工作人员的管理速度，以此更好的满足用户的相关需求，最终达到提升用户的使用感受的目的，由此可见设计和实现本系统具有重要的意义和价值。

2
![](/md/blog.002.png)	
## 1.2国内外研究现状
### 1.2.1国外研究现状
美国是最先发展计算机技术的众多国家之一，早在上个世纪，美国就快速的将计算机技术发展起来，并且将其运用在军事、医院、学校、社会服务等场所。日本、德国等国家紧随其后，不断地发展和完善计算机技术，侧重将医疗、社会服务等领域与计算机技术相结合[2]。而后随着社会的发展与进步，计算机技术逐渐趋于成熟。许多发达国家在探索将计算机技术应用于各行各业中时，从另一个角度来看，也在不断地推进连锁超市会员管理的信息化管理进程，使得商品管理也变得更加网络化、信息化了。有许多专家表示，可以结合使用图像处理软件、人工智能技术等相关工具，深度地分析连锁超市会员管理系统，主要从简化运行操作，加设功能模块，美化系统界面，保障数据安全等方面，更深层次地提升和优化系统，并且尽可能地在理想状态下做到实时的信息共享[3]。
### 1.2.2国内研究现状
国内的计算机技术的发展虽然晚于国外，尤其是美国、英国、德国等发达国家。但是我国的计算机技术发展势头非常迅猛，近些年，也逐渐走向成熟和完善的阶段。现在人们大多选择网上购物，也越来越离不开天猫、支付宝、微信等应用软件的使用[4]。许多行业结合使用了云计算、人工智能等先进的计算机技术，自主研发了信息化管理系统，使得系统越来越成熟，功能越来越完备。结合计算机技术，采用主流的B/S开发结构模式开发一款基于SSM的连锁超市会员管理系统。由此，工作人员不再被时空所限制，直接通过使用浏览器的方式对系统进行注册登录操作，支持随时随地对相关的连锁超市会员信息进行管理，便于及时为用户提供相关的连锁超市会员服务。并且所设计的系统基本上能够符合用户的客观使用需求，有利于充分协调连锁超市的人力、财力、物力等资源，不断提高连锁超市的服务水平和管理质量。
## 1.3研究内容与方法
### 1.3.1研究内容
本文首先介绍了连锁超市会员管理系统的研究背景与意义，其次介绍了功能模块的总体设计，接着介绍了各个功能模块的详细设计，最后介绍了系统的功能模块展示结果和测试结果。系统主要分为管理员角色和用户角色，具体的功能设计包括注册登录管理、个人中心管理、用户信息管理、商品信息管理、积分记录管理等模块。注册登录管理功能是之前没有使用过本系统的新用户，在使用系统前，需要通过注册步骤，登记详细的信息资料，而后再通过输入正确的账号和密码，成功登录系统后，即可通过一系列的操作来满足自己的相关需求。个人中心管理功能是管理相关的个人信息资料，个人根据现实情况的需要，有选择的对个人账户的相关信息进行一定的操作，比如选择更新或者删除操作。用户信息管理是管理相关的用户信息记录，对用户相关的信息进行管理，可以及时的更新相应的用户的基本资料。商品信息管理是管理相关的商品信息记录，查看详情情况，方便及时响应用户的服务请求。积分记录管理是管理相关的积分记录信息记录，方便相关人员及时查看并追踪积分记录信息，如果遇到异常的积分记录信息，可以及时对其进行处理，在较短的时间内解决问题，提高用户的使用体验。
### 1.3.2研究方法
本系统采用B/S结构，在idea平台上，通过使用Java语言设计系统相关的功能模块，MySQL数据库管理系统相关的数据信息，SSM框架设计系统功能架构，并且对其进行必要的管理和控制。系统设计的最关键的环节，则是需要通过Tomcat服务器将系统发布到浏览器上，以便相关用户的操作和使用。本系统的设计和实现是整个企业信息化管理的一大进步，促进了连锁超市的信息化建设，有利于简化相关人员工作流程，提高工作效率，提升工作幸福感。
## 1.4论文的组织结构
基于SSM的连锁超市会员管理系统的设计与实现的论文组织安排，大致可以被分为七个章节，具体的内容如下：

第一章为绪论，本章主要介绍了系统的背景、现状、方法等内容。根据研究背景与意义，介绍所要设计的系统的研究背景和理论依据，再通过国内外研究现状，了解当前相关的系统软件产品的实际研究情况，最后通过研究内容与方法，总体概括系统的整个开发流程和实现步骤，为系统提供可靠的理论依据和技术支持。

第二章为相关技术介绍，本系统通过在idea开发环境中，使用Java语言、MySQL数据库、SSM框架等关键技术，对系统基本功能进行设计和实现。其中，Java语言具有跨平台性，可移植性高，可以支持在不同的浏览器上运行本系统，MySQL数据库占用内存少，执行速度快，对于中小型系统的数据管理是非常好的选择。

第三章为系统分析，系统分析阶段主要是对系统进行需求和可行性分析，规划系统的功能设计，判断系统实现的可能性。根据需求分析，确认使用者对系统的基本功能需求，再通过在经济、操作、法律上进行可行性分析，分析系统研发的实际意义和使用价值，系统性能的稳定性和功能操作的便捷性，以及成功投入市场的可能性。

第四章为系统设计，系统设计阶段主要是对系统进行总体功能和数据库设计。通过介绍系统的总体功能设计，总体规划系统的功能模块，为系统的基本功能实现提供参考依据和设计思路。再通过介绍数据库设计，设计相关的数据二维表格存放和管理与系统有关的数据信息，便于相关人员管理与系统有关的数据信息，维护和更新数据信息的安全。

第五章为系统实现，系统实现阶段主要介绍了注册用户管理、商品信息管理、积分记录管理等功能模块。通过前面介绍的需求分析、总体功能设计、数据库设计等相关内容，对系统基本的功能模块进行设计与实现。系统实现过程也可以说为对系统的各个相关功能进行设计和实现的过程，在整个系统开发过程中，这一阶段是极为重要，直接关系到用户对系统的使用感受。

第六章为系统测试，系统测试阶段主要介绍了系统测试基本概念、测试用例、测试功能等相关内容。系统测试阶段主要任务是对系统进行功能测试，测试所设计的系统功能模块能否正常打开并使用，在系统运行过程中是否发生异常，如运行异常、数据异常、结果异常等，并且根据测试结果，给出相应的测试总结，由此得出相关结论，说明系统是否达到预期要求、设计目的。

第七章为总结与展望，对全文内容进行总结，并且对未来提出展望。总体来说，本系统的开发是比较理想的，未来的工作主要是针对于系统的功能和性能等方面，做一定的改进和完善，不断地优化系统的功能设计，美化系统的界面设计，简化系统的操作难度，使其能够满足更多用户的使用需求。
#
36
![](/md/blog.003.png)
# 2相关技术介绍
## 2.1 B/S结构
目前使用较多的开发结构模式大致可以包括C/S模式和B/S模式[5]。其中，C/S模式全称为客户端/服务器模式（Client/Server模式），B/S模式全称为浏览器/服务器模式（Browser/Server模式）。基于C/S模式下开发的系统，用户必须下载相应的客户端，即应用程序，才能操作和使用软件系统的相关功能模块。从使用者的角度来看，由于下载和安装客户端的步骤比较繁琐，期间还需要确保下载网速的稳定性，以及安装步骤的正确性，进而增加了用户放弃使用该系统的可能性，由此可见C/S模式具有很大的局限性。

由于C/S模式适用于小范围的局域网，并且具有一定的通信效率，所以在以前系统规模很小的时代，主要使用C/S模式对系统开发。随着时代地发展以及社会地进步，C/S模式也越来越满足不了开发者的设计需要，以及使用者的使用需求[6]。当下，C/S模式已经满足不了实际的系统程序设计要求，由此，B/S模式以C/S模式为基础而被提出，并且在近些年逐渐发展成为主流的开发结构模式。在B/S模式下开发的系统，不再需要用户下载和安装相应的应用程序，直接通过使用浏览器，输入正确的网站地址，以访问网站的形式实现系统的相关功能操作，这一特点对C/S模式下的开发设计做出了极大地改进，当然需要用户输入正确的账号和密码，才能成功的进入并使用系统。

## 2.2 Java语言
Java语言是由美国sun公司提出的一种面向对象的程序设计语言，它拥有着优秀的技术体系结构。目前在市场上，很大一部分的应用系统主要使用Java语言进行开发[7]。Java语言具有简单易懂，操作方便，健壮性强等优点，开发人员能够的在短时间内理解和掌握Java语言，并将其运用到具体的系统开发过程中学。Java语言所提供的垃圾回收机制，主要被用于解决系统的内存管理问题。此外，Java语言还将C语言中较难掌握的指针改进成容易被学习和掌握的引用，由此极大地简化了开发编程的难易程度，所以受到了很多开发人员的喜爱，大多数研发人员基本上首选使用Java语言开发系统。Java语言还具有跨平台性的特点，意味着它的可移植性非常高，这一特点有利于开发人员更新和维护相关代码，由它所开发的系统可以支持在不同的浏览器中打开。因为使用Java开发的系统兼容性较强，代码通用性较高，为了后期方便对系统进行完善和维护，所以本系统选择了使用Java语言进行设计和实现。

## 2.3 SSM框架
SSM框架主要由Spring、SpringMVC、MyBatis这三个框架所集成的，是现在比较流行的一种Java开发框架，能够适用于大中型的应用程序的设计和搭建。Spring是前几十年前兴起的一种轻量级的、开源的Java开发框架，使用它可以解决相关的系统对象创建和对象依赖问题，并且也可以将高耦合的系统分解为低耦合的多个功能模块，方便对系统模块进行明确的分工，对功能代码进行理解和修改，这就极大地减轻了设计人员的开发压力[8]。SpringMVC框架是基于Spring框架而被提出的，它以MVC三层架构为核心，对Spring的相关技术进行了整合，主要针对于Web端进行技术架构，通过对相关的请求处理进行细化处理，用来响应用户的使用请求。MyBatis框架是一种开源的Java持久层框架，它改进了手动设置参数和获取结果记录的方式，通过支持对数据库进行存储过程、高级映射等处理，使得数据库的操作更加定制化、透明化，因此降低了数据库访问的复杂性，提高了开发的工作效率。
## 2.4 MySQL数据库
MySQL数据库是目前使用较多的关系型数据库。因为其具有开源免费、占用内存少、安装简单、操作便捷、使用灵活等优点，所以经常被运用于中小型的系统开发中[9]。MySQL数据库可以支持多线程，在同一个时间内，能够同时响应多个用户的使用需求。MySQL数据库还自带了优化器，方便设计人员在 使用过程中，快速的查询相关的数据信息。除此之外，SQL server数据库也是当下较为主流的关系型数据库，它在数据安全、系统稳定等方面还是比有所保障，但是由于其收费使用、占用内存大、操作复杂、维护成本高，一般适用于中型及以上的系统开发中。MySQL数据库的内部代码中也很多的应用程序接口，便于其他编程语言与数据库进行连接和交互，由此编写的代码具有极高的通用性和维护性，并且MySQL数据库能够迅速的处理上千条数据记录，在系统故发生障时，能通过日志文件快速恢复。MySQL数据库与SQL server数据库相比较，综合考虑成本开销、占存大小、代码通用、数据维护、操作难易程度等方面，MySQL数据库占有很大的优势，数据库设计人员也比较喜欢使用MySQL数据库对系统数据进行管理。

#
# 3系统分析
## 3.1系统的需求分析
在软件设计开发的整个过程中，需求分析占用的时间是比较长的，也是比较耗费人力的阶段。需求分析是设计系统功能模块的总方向，系统开发工作基本上都是围绕着需求分析而进行开展的。通过需求分析阶段，可以确定系统的基本功能设计，以及在最后的系统验收阶段，通过对照需求分析报告，验证系统的功能设计是否合理，能否满足用户的基本需要，最终判断评定系统设计是否成功完成。本文主要通过问卷调查的方式，对基于SSM的连锁超市会员管理系统进行了需求分析[11]。根据调查结果显示，系统用户主要有两种类型，一种是以使用为主要目的的用户角色类型，另一种是以管理为主要目的的管理员角色类型。用户角色的主要功能需求包括商店信息查询、商品信息查询、积分记录管理等模块。管理员角色的主要功能需求包括注册用户管理、商品信息管理、积分记录管理等模块。其中，密码信息、商品信息、积分记录信息等都是非常重要的数据记录，在系统设计的过程中，需要进行一定的加密处理，确保数据安全性，切实的保护好用户的重要信息。
## 3.2系统的可行性分析
### 3.2.1经济可行性
对系统进行经济可行性分析，也可以被称为对系统进行经济可行性研究，它是从社会的经济发展出发，通过研究整个的系统可行性，对成本收益情况进行全面地、具体地分析，并且根据所分析的可行性报告，为相关的投资者提供最科学的决策理论和最优的投资方案。本系统的开发促进了连锁超市会员的信息化管理，管理人员可以直接通过在浏览器上发布连锁超市会员管理系统的网站地址，即可用户根据一定的需要，有选择的对系统相关功能进行操作。这种方式打破了时间和空间的限制，可以使得连锁超市在较短的时间内最大化地获取利润。并且本系统所使用的开发技术和相关工具，大部分是开源的、免费的，所以可以节约很大一笔开发成本。综合上述内容分析可知，本系统的实现在经济层面上是具备可行性的。
### 3.2.2技术可行性
本系统是基于Java语言而进行开发的，因为Java语言容易学习、使用简单、可移植性高、稳定性强等特点，所以许多研发人员首选Java语言设计系统功能，市场上很多应用程序是由Java语言进行开发实现的。并且Java语言还具有跨平台的优点，这意味着所设计的系统是与平台无关的，也就说明由Java语言开发的系统可以支持在不同的浏览器上运行和使用。本系统使用的是开源免费的MySQL数据库，相比于其他的数据库，MySQL数据库语法简单，数据库设计人员可以尽可能快的对其学习和掌握，所以一直是中小型系统最优的数据库选择。MySQL数据库还具有占用系统内存少、功能齐全、响应速度快等特点，能够在极短时间内处理上千条信息记录，所以能够保证系统可以高效地运行和工作。综合上述内容分析可知，系统的实现在技术层面上是具备可行性的。
### 3.2.3操作可行性
如今，人们的日常生活已经离不开互联网的使用，在一定程度上，行业的信息化建设促进着社会的发展。人们通过使用手机上的应用程序，比如，通过使用电子商务系统，可以实现网上购物、在线支付等功能；通过使用国家官方网站，可以查看最新消息，申报个人业务；通过使用医院管理系统，可以进行网上预约挂号，在线查看体检报告等操作。在这些应用的背景下，本系统使用的是B/S开发结构模式，网站界面以人性化的设计为主，具有美观友好、交互性好等优点，用户不需要掌握一定的编程技术，直接通过对系统进行简单的功能操作，即可满足自己的使用需求。本系统还设计了一些提示信息，便于用户更好的理解系统相关功能，较快的以正确的操作方式来使用系统。综合上述内容分析可知，系统的实现在操作层面上是具备可行性的。

#
# 4系统设计
## 4.1系统的总体功能设计
通过结合系统分析阶段的相关内容，对系统的整体功能设计进行规划。由此可知，本系统的使用者主要可以被分为管理员角色和用户角色两类。其中，管理员角色主要的功能需求有用户信息管理、商品信息管理、积分记录管理等模块，用户角色主要的功能需求有系统登录、查询商品信息、查询积分记录信息等模块。本系统的总体功能设计如图4-1所示。

连锁超市会员管理系统

用户信息管理

消费信息管理

商品信息管理

礼品信息管理

商店管理管理

用户信息修改

用户信息新增

商店管理添加 

商店管理删除

商店管理修改

礼品信息添加

礼品信息修改

礼品信息删除

消费信息添加

消费信息删改

消费信息删除

商品信息添加 

商品信息修改 

商品信息删除 

积分信息管理

积分信息修改

积分信息删除

积分信息添加


![](/md/blog.004.png)

图4-1系统的总体功能设计
## 4.2数据库设计
### 4.2.1概念设计
在数据库设计阶段，本系统通过使用开源的、小型的MySQL数据库对系统相关的数据信息进行管理和维护[12]。数据库设计大致可以被分为概念设计和逻辑设计两个阶段。概念设计阶段是逻辑设计阶段的重要依据，同样的，逻辑设计阶段也是概念设计阶段的实现目标。概念设计阶段主要通过使用实体-联系图（E-R图）的方式，将现实世界中用户对系统的实际需求，转换成设计人员能够理解的抽象的数据库概念模型。本人通过设计E-R图，详细的对系统中的实体以及实体之间的联系进行了表达。各实体信息的E-R图如图4-2、图4-3、图4-4、图4-5、图4-6、图4-7、图4-8、图4-9、图4-10所示，系统总体E-R图如图4-11所示。

![](/md/blog.005.png)

图4-2管理员信息E-R图

![](/md/blog.006.png)

图4-3用户信息E-R图

![](/md/blog.007.png)

图4-4员工信息E-R图

![](/md/blog.008.png)

图4-5商店信息E-R图

![](/md/blog.009.png)

图4-6商品信息E-R图

![](/md/blog.010.png)

图4-7礼品信息E-R图


![](/md/blog.011.png)

图4-8礼品兑换信息E-R图

![](/md/blog.012.png)

图4-9积分记录信息E-R图

![](/md/blog.013.png)

图4-10消费信息E-R图



![](/md/blog.014.png)

图4-11系统总体E-R图
### 4.2.2逻辑设计
逻辑设计阶段主要的工作是将概念设计中的E-R图，转换成方便系统进行存储和管理的二维表格形式[14]。这一阶段也可以被称为数据库的详细设计，其直接关系到系统功能模块的正常运行、数据信息的正常更新等。在设计过程中，需要充分考虑数据库的规范性和合理性，使得能够满足系统的功能和性能需求。本系统相关的数据表格设计内容如下所示。

表4-1 管理员信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

表4-2 用户信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|username|String|账户|是|
|3|password|String|密码|是|
|4|yonghu\_name|String|用户姓名|是|
|5|yonghu\_phone|String|用户手机号|是|
|6|yonghu\_id\_number|String|用户身份证号|是|
|7|yonghu\_photo|String|用户头像|是|
|8|sex\_types|Integer|性别|是|
|9|yonghu\_new\_jifen|BigDecimal|现积分|是|
|10|yonghu\_email|String|电子邮箱|是|
|11|create\_time|Date|创建时间|是|

表4-3 员工信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|shangdian\_id|Integer|商店|是|
|3|username|String|账户|是|
|4|password|String|密码|是|
|5|yuangong\_name|String|员工姓名|是|
|6|yuangong\_phone|String|员工手机号|是|
|7|yuangong\_photo|String|员工头像|是|
|8|sex\_types|Integer|性别|是|
|9|yuangong\_email|String|电子邮箱|是|
|10|create\_time|Date|创建时间|是|

表4-4 商店信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|shangdian\_name|String|商店名称|是|
|3|shangdian\_address|String|商店地址|是|
|4|shangdian\_content|String|商店介绍|是|
|5|create\_time|Date|创建时间|是|

表4-5 商品信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|shangdian\_id|Integer|商店|是|
|3|shangpin\_name|String|商品名称|是|
|4|shangpin\_danwei|String|单位|是|
|5|shangpin\_photo|String|商品照片|是|
|6|shangpin\_types|Integer|商品类型|是|
|7|<p>shangpin\_kucun\_</p><p>number</p>|Integer|商品库存|是|
|8|shangpin\_price|Integer|购买获得积分|是|
|9|shangpin\_old\_money|BigDecimal|商品原价|是|
|10|<p>shangpin\_new\_</p><p>money</p>|BigDecimal|现价|是|
|11|shangpin\_delete|Integer|逻辑删除|是|
|12|shangpin\_content|String|商品介绍|是|
|13|create\_time|Date|创建时间|是|

表4-6 礼品信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|lipin\_name|String|礼品名称|是|
|3|lipin\_danwei|String|单位|是|
|4|lipin\_photo|String|礼品照片|是|
|5|suoxu\_number|Integer|所需积分|是|
|6|lipin\_delete|Integer|逻辑删除|是|
|7|lipin\_content|String|礼品详细介绍|是|
|8|create\_time|Date|创建时间|是|

表4-7礼品兑换信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|yuangong\_id|Integer|员工|是|
|3|yonghu\_id|Integer|用户|是|
|4|lipin\_id|Integer|商品|是|
|5|lipinduihuan\_content|String|备注|是|
|6|insert\_time|Date|兑换时间|是|
|7|create\_time|Date|创建时间|是|

表4-8积分记录信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|yonghu\_id|Integer|用户|是|
|3|jifen\_types|Integer|积分类型|是|
|4|jifen\_number|Integer|数量|是|
|5|jifen\_content|String|详情|是|
|6|insert\_time|Date|添加时间|是|
|7|create\_time|Date|创建时间|是|

表4-9消费信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|id|Int|编号|否|
|2|xiaofei\_uuid\_number|String|消费流水号|是|
|3|yuangong\_id|Integer|员工|是|
|4|yonghu\_id|Integer|用户|是|
|5|shangpin\_id|Integer|商品|是|
|6|xiaofei\_number|Integer|消费数量|是|
|7|xiaofei\_content|String|备注|是|
|8|xiaofei\_time|Date|消费时间|是|
|9|insert\_time|Date|添加时间|是|
|10|create\_time|Date|创建时间|是|

#
# 5系统实现
## 5.1个人中心
通过设计的个人中心管理功能模块，管理用户可以对相关的个人信息进行管理，比如管理用户可以更新个人账号的密码信息，修改个人账号的用户名信息等，修改密码界面设计如图5-1所示，个人信息界面设计如图5-2所示。

![](/md/blog.015.png)

图5-1修改密码界面

![](/md/blog.016.png)

图5-2个人信息界面
## 5.2基础数据管理
通过设计的基础数据管理功能模块，管理用户可以对相关的商品类型信息进行管理，比如管理用户可以查看详细的商品类型名称信息，删除失效的商品类型信息记录等，基础数据管理界面设计如图5-3所示。

![](/md/blog.017.png)

图5-3基础数据管理界面
## 5.3礼品管理
通过设计的礼品管理功能模块，管理用户可以对相关的礼品、礼品兑换信息进行管理，比如管理用户可以查看详细的礼品所需积分信息，删除失效的礼品信息记录等，礼品管理界面设计如图5-4所示，礼品兑换管理界面设计如图5-5所示。

![](/md/blog.018.png)

图5-4礼品管理界面

![](/md/blog.019.png)

图5-5礼品兑换管理界面
## 5.4商店管理
通过设计的商店管理功能模块，管理用户可以对相关的商店信息进行管理，比如管理用户可以添加新商店信息记录，更新商店名称，删除失效的商店信息记录等，商店管理界面设计如图5-6所示。

![](/md/blog.020.png)

图5-6商店管理界面
## 5.5商品管理
通过设计的商品管理功能模块，管理用户可以对相关的商品、消费信息进行管理，比如管理用户可以查看商品现价，删除失效的商品信息记录等，商品管理界面设计如图5-7所示，消费管理界面设计如图5-8所示。

![](/md/blog.021.png)

图5-7商品管理界面

![](/md/blog.022.png)

图5-8消费管理界面
## 5.6积分记录管理
通过设计的积分记录管理功能模块，管理用户可以对相关的积分记录信息进行管理，比如管理用户可以查看积分记录类型，删除失效的积分信息记录等，积分记录管理界面设计如图5-9所示。

![](/md/blog.023.png)

图5-9积分记录管理界面
## 5.7用户管理
通过设计的用户管理功能模块，管理用户可以对相关的用户信息进行管理，比如管理用户可以查看用户头像信息，更新用户手机号码，删除已经注销的用户信息记录等，用户管理界面设计如图5-10所示。

![](/md/blog.024.png)

图5-10用户管理界面
## 5.8员工管理
通过设计的员工管理功能模块，管理用户可以对相关的员工信息进行管理，比如管理用户可以查看员工头像信息，更新员工手机号码，删除已经注销的员工信息记录等，员工管理界面设计如图5-11所示。

![](/md/blog.025.png)

图5-11员工管理界面


# 系










