## 简介

>《Java 小白进阶之路》是我花了将近一年时间完成的一份 Java 零基础学习教程！**目前共完成 240+ 篇，共计 60w 字，全部是我手敲的，百分百的原汁原味，通俗易懂，略微夹带一点点思维的乐趣。**
>
>[点击下载]()

<div align="center">
    <h5 style="background: azure; font-size: .85em;color: #000000;"> 扫码回复【Java】可下载我整理的 200+ 本高清电子书</h6>
    <h5 style="background: azure; font-size: .85em;color: #000000;"> 包括：入门、工具、框架、数据库、并发编程、底层、性能优化、设计模式、操作系统、计算机网络、数据结构与算法、面试、大数据、架构等等 </h6>
    <h5 style="background: azure; font-size: .85em;color: #000000;"> 如果你愿意支持我，可以给项目点个star，我会很感激！</h6>
    ![图片没显示的时候，微信搜索”沉默王二“也可以找得到](https://github.com/itwanger/JavaExplore/blob/main/itwanger.jpg)
</div>

<p align="center">
    这也许是东半球最好的零基础学习 Java 项目！
</p>

## 使用指南

1、因为本教程完全免费，但却被一些不良商家拿去卖钱，<b> 所以我需要你先帮我点一个 star </b>，助力原创，防止更多人上当受骗，也顺便支持我一下。

2、如果你想直接下载《Java 小白进阶之路》 PDF，[点击这里就行]()

3、如果你只想加我的个人微信: 二维码送上。

<div align="center">
    ![图片没显示的时候，微信搜索”qing_gee“也可以找得到](https://github.com/itwanger/JavaExplore/blob/main/qing_gee.jpeg)
</div>

## 导读

假如有那么残酷的一天，我不小心喝错了一瓶药，一下子抹掉了我这十多年的编程经验，把我变成了一只小白。我想自学 Java，并且想要找到一份工作，我预计需要 6 个月的时间，前提条件是每天都处于高效率的学习状态当中，并且每天的学习时间至少在 12 个小时以上。

即便是这样，我敢肯定，找到的工作肯定不会太好，勉强能够维持生活吧，毕竟是零基础入门啊。

如果想更进一步，真正成为一名不可或缺的高级 Java 工程师，时间需要更久，两年、三年、五年，直到秃的那天。

想着想着，我就觉得有必要为那一天做点准备，以备不时之需。

### 01、第一个阶段，环境和工具准备

- 准备一台电脑，要能连网
- 下载、安装 JDK，配置 Java 开发环境
- 下载、配置 [Maven](https://mp.weixin.qq.com/s/wSsm4zWHw9dxUO_PfEh1Dg)
- 下载、安装 IntelliJ IDEA
- 准备一个 GitHub 仓库（或者码云），管理 Java 源代码

Java 是一门计算机编程语言，学它的话，连台电脑都没有，学个屁。我有个亲戚家的孩子想学编程，就只看书，家里连台电脑都不配，说什么“先打好理论基础，再实操”，我真的是有点醉。

有了电脑，还得联网，自学的过程中肯定会遇到很多问题，遇到问题的时候先问搜索引擎，推荐谷歌和必应；实在没有答案的话，也可以来找我，申请加入技术交流群，问问群里面的大佬们。

既然要学 Java，JDK 是必须要先安装的，否则 Java 程序就没法编译和执行。

Maven 也是需要提前安装和配置的，因为后面进阶的话，需要一些练手项目，它们通常都需要 Maven 来加载第三方类库。

使用集成开发环境 IntelliJ IDEA 来敲 Java 代码吧，比 Eclipse 更流行。千万不要使用记事本编写源代码了，对于小白来说，时间是宝贵的，记事本只适合大牛们用来装逼，不适合小白用来编程（入门），纯浪费时间。

有了 IDEA，后面学习源码的话，就会方便很多，包括反编译字节码。

如果英语功底不太好的话，建议安装这两款 IDEA 插件：[chinese 和 translation](https://mp.weixin.qq.com/s/16zfRI6dD03awPPfelHvCg)。

如果注重编码规范的话，建议安装这两款 IDEA 插件：[Alibaba 和 SonarLint](https://mp.weixin.qq.com/s/ZKHe9yy7Ss-wn3Tq5YHehg)。

为什么还需要 GitHub 仓库或者码云仓库呢？它们可以用来在线云同步源代码，防止版本丢失。学到最后，还可以形成一套自己的工具库，轮子就有了，上班的时候工作效率就会高很多，能直接用的代码再也不用重新写了。

### 02、第二个阶段，Java 基础入门

 1）基本数据类型

- 8 种基本数据类型（boolean、char、byte、short、int、long、float、double）
- 整形中 byte、short、int、long 的取值范围
- 单精度和双精度
- [为什么不能使用“==”比较浮点数](https://mp.weixin.qq.com/s/NcMTCXtmiByMHVZ6eqFxSg)
- [基本类型和包装类型的区别](https://mp.weixin.qq.com/s/IoXT2D8eAG8UWK4j2Gem4A)
- 自动拆箱与装箱
- Integer 的缓存机制


2）操作符

- 算术运算符
- 逻辑运算符
- 比较运算符

3）流程控制语句

- 条件分支（if/else/else if、三元运算符、[switch](https://mp.weixin.qq.com/s/1BDDLDSKDGwQAfIFMyySdg)）
- 循环或者遍历（for、while、do-while）
- break 和 continue

4）包

- 创建包
- 导入包
- 包全名

5）main 方法详解

-  public 关键字
- [static 关键字](https://mp.weixin.qq.com/s/24EdEt3UyP7aKZStvvuDgQ)
- void 关键字
- main 方法
- 字符串数组参数（`String[] args`）

6）[数组](https://mp.weixin.qq.com/s/QpxUq90PEla7JZIA-kuV_w)

- 什么是数组？
- 访问数组
- 遍历数组
- [打印数组](https://mp.weixin.qq.com/s/udUi8ee8lA412aqpqFBcmw)
- [可变参数](https://mp.weixin.qq.com/s/xzEWgVZdTHSONToZYyLYIg)
- [数组排序](https://mp.weixin.qq.com/s/aPGwRxEe6bOXglNMy3dIyQ)
- 数组转成 Stream
- 数组转成 List
- [数组搜索](https://mp.weixin.qq.com/s/DBvgghP5cN6KlPnILaqjmQ)
- [ java.util.Arrays](https://mp.weixin.qq.com/s/-s0MdIvmxjeLmzBUHj4BNQ)
- [数组越界](https://mp.weixin.qq.com/s/TRyVTQqMGmqs4lmHtsgRuw)

7）注释

- 单行注释
- 多行注释
- 文档注释
- [注释真的不会被执行吗？](https://mp.weixin.qq.com/s/7jwu_Db8wfqK7CrX2xA83Q)
- [优秀的程序员真的不写注释吗](https://mp.weixin.qq.com/s/t4edQHFY0SHTpfvZ9AYVUA)

8）字符串

- 双引号字符串和 new 字符串对象
- [字符串为什么是不可变的？](https://mp.weixin.qq.com/s/XV69p7yGrUY5dHjBJztNAA)
- String、StringBuilder 和 StringBuffer  之间的区别
- 字符串拼接的几种方式
- 字符串常量池
- 关于 intern
- [字符串比较（== 和 equals）](https://mp.weixin.qq.com/s/WyrRCUlelzOxyfVBrxAGUg)
- [字符串拆分](https://mp.weixin.qq.com/s/P0HOlgREXqUWIDKgKxr-MA)
- [字符串操作小技巧](https://mp.weixin.qq.com/s/INnMP8hWakIO63i6kVoghg)
- [字符串转整形](https://mp.weixin.qq.com/s/SQlBZ3a7j0_fdASzMjaIFg)
- [生成 UUID](https://mp.weixin.qq.com/s/SQlBZ3a7j0_fdASzMjaIFg)
- [字符串可以引用传递吗？](https://mp.weixin.qq.com/s/Iq6C56_H6CThR5w6v_sQ7Q)
- [字符串长度](https://mp.weixin.qq.com/s/nLZwlQf35cuYkeHb6-BUhg)
- [关于 substring](https://mp.weixin.qq.com/s/rLakWBPuWqYG8QT6ACetGQ)

### 03、第三个阶段，Java 核心技术

1）面向对象

- [面向对象和面向过程](https://mp.weixin.qq.com/s/Ii366rkaslLTZ_Qo59B_vQ)
- [封装](https://mp.weixin.qq.com/s/lH6LXdUd2RdAhcCBv82yuw)
- [继承](https://mp.weixin.qq.com/s/q-dMxOXxT8N3W6ftmNWkWQ)
- 多态
- [接口](https://mp.weixin.qq.com/s/06d5Fk_ho4yafR83mfbWag)
- [抽象类](https://mp.weixin.qq.com/s/yES5bPg6wbCYuBciZhPYaQ)
- [重写和重载](https://mp.weixin.qq.com/s/b_q8qsMK00Ei3bellStrEA)
- 构造方法
- 局部变量、成员变量、静态变量、常量
- [值传递还是引用传递](https://mp.weixin.qq.com/s/v0mXk7cQzUFq_y2xArMTPA)
- [final 关键字](https://mp.weixin.qq.com/s/_Xhgk1su7drlsBfUPCC1xg)
- [this 关键字](https://mp.weixin.qq.com/s/MIX4srqeg7STzphhR6Gp5g)
- super 关键字
- [不可变对象](https://mp.weixin.qq.com/s/wbdV9rV60AwWiiTEBYPP7g)
- [equals() 和 hashCode()](https://mp.weixin.qq.com/s/Mtdd4sPRmR_lOPjadHBk1Q)
- [打印 Java 对象](https://mp.weixin.qq.com/s/d7j-EbhYqCnp5F63WI1lIA)
- [NullPointerException](https://mp.weixin.qq.com/s/PBqR_uj6dd4xKEX8SUWIYQ)

2）常用工具类

- 字符串相关的工具类
- 日期时间相关的工具类
- [枚举](https://mp.weixin.qq.com/s/5QrbbHwo6snBA6gIKPIjPQ)
- [随机数](https://mp.weixin.qq.com/s/f5zdOt1lFzpZQXQuXVlpCg)
- 正则表达式
- Apache-commons 工具库
- Guava 工具库

3）集合框架

- [ArrayList](https://mp.weixin.qq.com/s/9of-ZgM3FGMkg3g4t7Mq4w)
- [LinkedList](https://mp.weixin.qq.com/s/Gr1kXieJoQol2WuFuHWQaA)
- [ArrayList 和 LinkedList  之间的区别](https://mp.weixin.qq.com/s/fwoeeGHRM0KTJBrDXNzm0Q)
- [不可变 List](https://mp.weixin.qq.com/s/E6mVdSzPN4TXrDaDiCy7ng)
- [CopyOnWriteArrayList](https://mp.weixin.qq.com/s/Z_ZM9D7sNftF3YCEgotJNQ)
- [HashMap](https://mp.weixin.qq.com/s/VLf3bNKB_s2CImsVItxuRw)
- [LinkedHashMap](https://mp.weixin.qq.com/s/yI6mMIjddKnAOjOfwzjlXw)
- [TreeMap](https://mp.weixin.qq.com/s/e6LnmWs5g9SVbpOHysLOrg)
- [ConcurrentHashMap](https://mp.weixin.qq.com/s/WqYmB9G1TDPHL1YP4r6B9g)
- [fail-fast](https://mp.weixin.qq.com/s/TWG9OIOMEdbtKrE_abVe5w)


4）[反射机制](https://mp.weixin.qq.com/s/abaq2Gpt4KNyupNvf2Scfg)

- 什么是反射？
- 反射有什么用？
- Class 类

5）[异常处理](https://mp.weixin.qq.com/s/TQ8GYbDC5Cci7dXYeadzUA)

- 为什么需要异常处理机制？
- Error 和 Exception
- try-catch-finally
- [try-with-resource](https://mp.weixin.qq.com/s/fbTzH5B7mSr5v0tQ8mV2wA)
- 自定义异常
- 尽量捕获原始异常
- 不要打印堆栈后再抛出异常
- 不要用异常处理机制代替判断
- 不要过早捕获异常

6）[注解](https://mp.weixin.qq.com/s/TUMrwWitgb4mXmloiOKvAg)

- 注解是什么？
- 注解的生命周期
- 注解装饰的目标
- 自定义注解
- 使用注解

7）IO 流

- 字符流、字节流
- 输入流、输出流
- 同步、异步
- 阻塞、非阻塞
- BIO、NIO 和 AIO
- [NIO 2.0](https://mp.weixin.qq.com/s/8FS2eReMbzLL6DsU8yWEMg)

8）[序列化](https://mp.weixin.qq.com/s/rEpGT1Tc3t3EDbA4Ir8ELQ)

- 什么是序列化和反序列化
- Java 如何实现序列化和反序列化
- Serializbale 和 Externalizable
- serialVersionUID

9）[泛型](https://mp.weixin.qq.com/s/_uX0BTv7pVB8OzZTix1zbw)

- 什么是泛型？
- 类型擦除
- 泛型带来的问题
- 泛型中 K T V E 这些特殊字幕的含义
- 通配符
-  上下界限定符 extends 和 super
- [不要在集合中使用 Java 原始类型](https://mp.weixin.qq.com/s/ztYEmcdQ00c3L5nqgb2meg)

10）单元测试

- Junit
- TestNG

11）编码方式

- ASCII
- Unicode
- UTF-8
- GBK、GB2312
- 如何解决乱码问题

12）并发编程

- 什么是并发
- 什么是并行
- 什么是线程
- 什么是进程
- 线程的状态
- 线程的优先级
- 创建线程
- 创建线程池
- 什么是线程安全
- 多级缓存和一致性问题
- CPU 时间片和原子性问题
- 指令重排和有序性问题
- 线程安全和内存模型
- happens-before
- 可重入锁
- 阻塞锁
- 乐观锁
- 悲观锁
- 分布式锁
- CAS
- ABA
- 偏向锁
- 轻量级锁
- 重量级锁
- 自旋锁
- 什么是死锁
- 如果避免死锁
- [synchronized](https://mp.weixin.qq.com/s/yQx6GqWLnVOfSXqLRLD9Pw)
- volatile
- ThreadLocal
- Executors
- CountDownLatch
- Thread
- Runnable
- Callable
- ReentrantLock
- ReentrantReadWriteLock
- Atomic 相关类

13）Java 8 新特性

- [Lambda 表达式](https://mp.weixin.qq.com/s/ozr0jYHIc12WSTmmd_vEjw)
- [Stream流](https://mp.weixin.qq.com/s/7hNUjjmqKcHDtymsfG_Gtw)
- [Optional](https://mp.weixin.qq.com/s/PqK0KNVHyoEtZDtp5odocA)

14）源码阅读

- String
- Integer
- ArrayList
- LinkedList
- CopyOnWriteArrayList
- HashMap
- TreeMap
- LinkedHashMap
- ConcurrentHashMap
- CopyOnWriteArrayList

### 04、第四个阶段，Java 进阶升级

1）JVM

- Java 内存结构
- 堆
- 栈
- 垃圾回收
- JVM 参数调优
- Java 对象模型
- HotSpot
- [类加载机制](https://mp.weixin.qq.com/s/rA5aTVPKXWVesD1d69y4gg)
- 编译和反编译
- 反编译工具
- JIT
- 虚拟机性能监控和故障处理工具（jps、jstack、jmap、jstat、jconsole、javap）

2）性能优化

- 使用单例
- 使用线程池
- 减少上下文切换
- 减小锁粒度
- 数据压缩
- Stream 并行流
- GC 调优
- JVM 内存分配调优
- btrace

3）设计模式

- 设计模式的六大原则
- 创建型设计模式（单例、抽象工厂、建造者、工厂、原型）
- 结构型设计模式（适配器、桥接、装饰、组合、外观、享元、代理）
- 行为型设计模式（模板方法、命令、迭代器、观察者、中介者、备忘录、解释器、状态、策略、责任链、访问者）
- 单例的七种写法

4）数据结构和算法

- 简单的数据结构（栈、队列、链表、数组、哈希表）
- 树（二叉树、字典树、平衡树、排序树、B 树、B+ 树、R 树、红黑树、多路树）
- 堆
- 图（拓扑、有向图、无向图）
- 稳定的排序算法（冒泡排序、插入排序、鸡尾酒排序、桶排序、计数排序、归并排序、原地归并排序、二叉排序树排序、鸽巢排序、基数排序、侏儒排序、图书馆排序、块排序）
- 不稳定的排序算法（选择排序、希尔排序、梳排序、堆排序、平滑排序、快速排序、内省排序、耐心排序、Clover 排序）
- 时间复杂度
- 空间复杂度
- 贪心算法
- KMP 算法

5）操作系统

- Linux 常用命令（find、top、tar、move、grep、tail、netstat、curl、wget、ping、ssh）
- 服务器性能指标（qps、CPU 利用率）
- 进程同步
- 分段和分页
- 虚拟内存和主存

6）网络安全

- CSRF
- XSS
- SQL 注入
- 加密和解密（对称加密、非对称加密）
- MD5、SHA1、DES、RSA
- DDOS 攻击
- HTTP 和 HTTPS
- SSL
- TLS
- TCP 和 UDP
- Cookie、Session
- CDN
- DNS

7）数据库

- MySql
- 索引
- 存储过程
- 分库分表
- binlog
- 读写分离
- 数据库缓存（[Redis](https://mp.weixin.qq.com/s/NPJkMy5RppyFk9QhzHxhrw)、[MongoDB](https://mp.weixin.qq.com/s/qz0sNOFeS0GTW-H9cdnbJg)）
- 数据库中间件（MyCat）
- 数据库连接池（Durid）

8）大数据

- 搜索（[Elasticsearch](https://mp.weixin.qq.com/s/ZjsZxle7m_dfmVwVkq2ayg) 、Solr）
- 流式计算（Storm、Spark、Flink）
- Hadoop

9）服务器

- Tomcat
- jetty
- Nginx

10）框架

- Spring
- MyBatis
- Spring MVC
- Spring Boot
- Spring Security
- Spring Cloud
- Netty
- Dubbo

11）消息队列

- [RabbitMQ](https://mp.weixin.qq.com/s/CoK1PoGQ-ulQuj1Rejgccg)
- Kafka

12）容器

- Docker
- K8s


### 05、第五个阶段，活着最重要

技术是没有终点的，也是学不完的，最重要的是活着、不秃。

零基础入门的时候看书还是看视频，我觉得成年人，何必做选择题呢，两个都要。喜欢看书就看书，喜欢看视频就看视频。

最重要的是在自学的过程中，一定不要眼高手低，要实战，把学到的技术投入到项目当中，解决问题，之后进一步锤炼自己的技术。

开源的项目我推荐 GitHub 上的 mall 和 vhr，前者是电商系统，后者是微人事，都用的最前言的技术，并且文档很全面，不怕晕头转向。

自学最怕的就是缺乏自驱力，一定要自律，杜绝“三天打鱼两天晒网”，到最后白忙活一场。

高度自律的同时，要保持耐心，不抛弃不放弃，切勿自怨自艾，每天给自己一点点鼓励，学习的劲头就会很足，不容易犯困。

技术学到手后，找工作的时候一定要好好准备一份简历，不要无头苍蝇一样去海投简历，容易“竹篮打水一场空”。可以参考下面的链接，好好的准备一下简历，毕竟是找工作的敲门砖。

[入职阿里后，才知道原来简历这么写](https://mp.weixin.qq.com/s/QFraobvuGnVJRCi4tA-CNQ)

拿到面试邀请后，在面试的过程中一定要大大方方，尽力把自己学到的知识舒适地表达出来，不要因为是自学就不够自信，给面试官一个好的印象，面试成功的几率就会大很多，加油吧，骚年！
