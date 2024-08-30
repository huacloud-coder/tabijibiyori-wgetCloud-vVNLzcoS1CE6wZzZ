
上篇文章很多小伙伴留言也讲到自己被公司裁员，还有的细心的小伙伴**说去年九月就被裁了，在看一下文章的发布时间，绷不住了。**先和大家说一下，我已经找到工作，因为最近工作一直都很忙，加上自己也比较懒，所以就拖了很久才写的。之前没说就是为了方便写后面的文章。也是通过本文分享一下自己找工作的方法，希望可以给大家一点帮助。


开始找工作，基本都是 `Boss不回、前程堪忧`。因为现在的行情就是不太好，公司的需求减少，大量的公司裁员。**在职的时候和大多数程序员一样，每天按部就班的工作，偶尔吐槽公司，也不敢离职找工作。等到被裁的时候，心里一片茫然**。


开始的一个月，就两三个面试。而且基本都是一面就挂了。基本的都是准备不足，但是一个月后，半个月的时候我就拿了 4 个offer，这里面也有运气和自己的策略问题。


# 面临的问题


* 八股文不会，或者背了就忘。
* 简历准备不够，只是写简单项目经历
* boss 不回就投递少。
* 外包填了几个信息没信之后，就很少回。


# 解决方案


被裁之后本来心气就低，特别又遇到现在这种行情，基本公司都是已读不回或者外包要填写各种各样的信息，填完就没消息了，就很容易气馁。


## 脸皮要厚


首先就要海投，不管什么公司，只要差不多符合要求的公司就投递，boss 不回就多投，一天最低要投递几十份简历。先要找到机会去面试，有机会面试，找到面试的感觉，根据面试的反馈做调整，聊天沟通几千家，投递一百多的简历，才有几次面试。


![](https://img2024.cnblogs.com/blog/2448954/202408/2448954-20240830112020036-337949079.png)


当时找工作的时候，外包的回复比较多，不过都是要求填写各种信息，还会问各种问。然后问完了就消息了。我后面从一个 HR 朋友才知道，原来外包的 HR 都是按照招的人数拿提成，他们有一个表格，填完表格之后，就直接交给用人部门，一个岗位招十个人，他可能聊了几百的候选人，这种情况下没有下文也正常。


针对外包 HR,聊了几次之后，基本都知道他们要什么信息，都会把新增存在聊天记录里面。下次要这些信息的时候就方便很多。


## 背八股文


大部分面试的都会问到八股文。


* 比较常见的八股文可以看看 `https://cyc2018.xyz/`
* 图解网络、操作系统、计算机组成 [小林coding](https://github.com)


### 图表加深记忆


如果光背八股文，没有给成套的体系的话，基本的都是背了就忘。我的记忆性不是很好，会辅助一下图表理解八股文，比如 HashMap 的数据结构，使用图表和流程就可以快速的理解和掌握，


比如 HashMap 结构：


![](https://files.mdnice.com/user/29864/9329125b-4a58-4ec8-8c8b-0c4e02bd9a6f.png)


先通过图表结构，大概了解他的结构，在通过一些流程图获取数据添加到流程：


![](https://files.mdnice.com/user/29864/7fe36669-1898-4f2d-9d6f-8633a28a4480.png)


通过上面的的方法，写了几篇关于 HashMap 的文章：


* [详解HashMap源码解析（上）](https://github.com)
* [详解HashMap源码解析（下）](https://github.com):[樱花宇宙官网](https://yzygzn.com)
* [详解ConCurrentHashMap源码（jdk1\.8）](https://github.com)


### 知识成体系


很多知识点会有很多的关联性。比如 HashMap 适用于并发度不高的情况，而如果想要保证线程安全就需要使用 ConCurrentHashMap，再看看 add 和 get 方法是如何线程线程安全，一环扣一环。


不同的知识点，底层都是有关联性，比如 ArrayList 和 Redis 的简单字符串的扩容，当数据不够的时候，都会扩大自己的 1\.5，这样的都是为了减少扩容的次数。


带着问题或者解决的难点去看八股文，比如 MQ 基本都会问消息的**可靠性**和**不可重复**，MQ 主要就是做一个消息的传递，在正常情况下，消息都能正常消费一次，但是如果服务器重启了，或者接收的服务重启，这都可能导致消息不可靠，带着问题，最好本地搭建服务，模拟消息丢失的情况，进而解决这个问题。**把这个问题解决的思路和过程改成自己在工作中解决了这种问题，再加一点自己的思考，这样比纯背题加分很多。**


## 准备简历


简历主要展示两个技能：


* 项目经验
* 技术技能


### 项目经验


项目包含几个点：


* 项目背景


让面试官和 hr 知道解决了什么问题，hr 会通过项目来匹配相同的经历的面试者。简单点就是说，这个项目解决了那些问题，整个项目是如何运的。


项目背景或者需求一般都是产品最了解，程序员大部分时间都用在如何实现功能上，用在需求的理解比较少。了解项目又会技术就给面试官印象比较深，面试通过的概率也比较高。


* 你参与的角色，负责模块


参与的模块，负责那些代码，不要简单写自己做了xx模块，而是从一整个项目出发，解决那些问题。比如一个数据分析系统。这是修改前项目职责：


* 订单商品维度销量统计
* 订单炼厂维度销售统计
* 订单客户统计
* 订单新客户统计


流水账记录实现的功能，没有了解到具体的需求和目标。好的技术是要先了解需求、技术设计、功能实现、配合同事完成任务对接。


下面是优化后的项目职责：


* 和业务团队收集需求，明确数据分析的需求和指标。
* 设计并实现数据统计和多维度分析统计。
* 主要统计每天或每周的订单、商品、供应商、业务员、新客户等销售数据。
* 配合前端提供图形化展示，帮助业务团队快速洞察问题。



> 相对一个只会干活的程序员，一个会思考需求的来源、项目解决的难点和痛点、设计技术实现方案以及高效的沟通的优秀程序员肯定的更受青睐，而且修改后的项目职责也相对更加的专业和规范。


### 技术技能


先看一下技术技能对比，这是修改前的技能：


![](https://img2024.cnblogs.com/blog/2448954/202408/2448954-20240830112102659-677846578.png)


修改前技能问题：


* 前后端都熟悉，没有突出的技能，现在很多公司都是前后端分离，没有突出的技能，面试那关估计就被刷掉。
* 技能比较简单，工作5,6年就不适用简单的技能了。
* 技术技能需要关联到相关的业务技能和沟通技能。


修改上面的问题，这是优化后的技能：


![](https://img2024.cnblogs.com/blog/2448954/202408/2448954-20240830112114739-1114103612.png)


技能除了介绍技术之外，更重要的要介绍自己的工作经验，主要涉及的业务方向。此外博客也是一个很好的展示技能。


# 准备完毕，开始面试


一共面试了 6 家，其中拿到了 4 个 offer，因为是去年面试的，过程只记了一个大概。


# 某喜到家


这是第一家面试的公司，是一家 o2o的公司，面试架构组职位。主要问了一些项目，如何实现，几个八股文，微服务的有什么缺点，分布式事务的替换方案。面试出奇的顺利，有的问题不太熟悉的，面试官也会给点提示。一下午技术面试过了两轮，hr面试也过了两轮。然后就回去等通知。


过了一天之后，通知我面试通过了。但是他们的上班时间是上午9点半到中午12点，中午休息2个小时。下午两点到六点，晚上休息半个个小时，六点半点到8点，而且还是大小周。给出的薪资相对之前基本是没涨（虽然工资涨了，工作时间也增加了），还是先拿个offer保底，再继续找工作。



> 这么长的工作时间，应该也很难招到人。工资也卡的比较死。这种情况自然面试也比较容易就通过了。


# 银行外包


面试过了一天，来了一个珠海外包的电话面试，主要问了一些八股文：


* SpringBoot自动装配原理
* 线程池线程数量设置，拒绝策略
* JMM


然后介绍自己的项目经历，自己负责的模块，如何实现对应的技术模块。印象比较的深一个点，是自己写博客地址，就问了下是不是自己写的，说看了还是写的挺不错的。而且还说：**我最近几天面试了十多个人，你是唯一一个让我感觉挺满意，背八股文不是应付任务一样的背，还会结合一些实际的工作常见使用。做项目也有自己的想法，而且还会把自己的心得、总结写成博客。**当时就感觉自己写了这么久的博客有人表扬还是很开心的。


二面时候，也是问了一个技术的问题，面试也过了。给的薪资还可以，比上面的 o2o 的工资好一点。但是毕竟外包还是工作比较累，还是拿个offer，再继续找工作。


# 某外贸公司


这是一家跨境电商的公司，主营的是电子烟，想要做一个独立站，跨境销售产品。面试形式是笔试 \+ 面试。比如主要写了一些八股文：


* CPU飙升到 100% 如何处理
* MQ 消息可靠性如何保证
* Mysql 事务隔离级别，以及各自的问题
* HashMap、ConCurrentHashMap、Hashtable 的区别


面试主要问项目经验和一些八股文,对 HashMap 的细节一直问的比较细节。后面人事总监面试也过了，第二天回复面试也通过了。给的薪资比前面都高，基本上对这个工资是比较满意，也准备拿了 offer 就准备上班了。


# 半路杀出个珠宝公司


本来就准备下周就去新的公司报道了，在 boss 上又来了一个面试，反正也没啥事，多面试几次也没事。前面几次面试基本上都是问 **项目 \+ 八股文**，都问出经验了，一面主要是问项目经验，自己的负责的模块用哪些技术实现。最后就问了一下如何实现点赞功能，要看到每天点赞的人数、每个人点赞的数量，这么统计的话，就不能使用 Redis 统计了,只能使用关系型数据库,比如 Mysql 实现。


一面过了，就来到了技术总监的面试，主要讲项目，还叫我在画板上画下流程图，面试也通过了，之后就是 HR 谈薪资。薪资和之前的外贸公司差不多，但是这个公司包吃住，相当于涨了三千的工资。


# 最后选择


最后就在外贸公司和珠宝公司选择，两个公司都是大小周，（后面面试的公司基本都是大小周）无论是薪资还是福利方面，珠宝公司都更好，而且相对来说珠宝行业也比较稳定点，所以最后就选择了珠宝公司。


# 总结


断断续续终于写完几篇失业日记，最开始失业的不适应、迷茫，后面找工作的屡屡碰壁，一次又一次的失败。简历一遍一遍的修改，疯狂打招呼，疯狂投简历。那个时候也不知道什么时候能找到工作，开始找工作的 10 月份的时候感觉过年都可能找不到工作，没想到 11 月份，半个月就拿了 4 个 offer，就像《阿甘正传》的那句台词一样：


**Life was like a box of chocolate. You never know what you're gonna get**


