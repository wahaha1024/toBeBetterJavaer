
<p align="center">
  <a href="https://javabetter.cn">
    <img src="https://cdn.tobebetterjavaer.com/tobebetterjavaer/images/logo.png" width="200px" alt="二哥的Java进阶之路">
  </a>
</p>


# 面渣逆袭

>  **面试前必读系列**！包括 Java 基础、Java 集合框架、Java 并发编程、Java 虚拟机、Spring、Redis、MyBatis、MySQL、操作系统、计算机网络、RocketMQ、分布式 等等。

- [面渣逆袭（Java 基础篇八股文面试题）必看👍](docs/sidebar/sanfene/javase.md)
- [面渣逆袭（Java 集合框架篇八股文面试题）必看👍](docs/sidebar/sanfene/collection.md)
- [面渣逆袭（Java 并发编程篇八股文面试题）必看👍](docs/sidebar/sanfene/javathread.md)
- [面渣逆袭（Java 虚拟机篇八股文面试题）必看👍](docs/sidebar/sanfene/jvm.md)
- [面渣逆袭（Spring八股文面试题）必看👍](docs/sidebar/sanfene/spring.md)
- [面渣逆袭（MySQL八股文面试题）必看👍](docs/sidebar/sanfene/mysql.md)
- [面渣逆袭（Redis八股文面试题）必看👍](docs/sidebar/sanfene/redis.md)
- [面渣逆袭（MyBatis八股文面试题）必看👍](docs/sidebar/sanfene/mybatis.md)
- [面渣逆袭（操作系统八股文面试题）必看👍](docs/sidebar/sanfene/os.md)
- [面渣逆袭（计算机网络八股文面试题）必看👍](docs/sidebar/sanfene/network.md)
- [面渣逆袭（RocketMQ八股文面试题）必看👍](docs/sidebar/sanfene/rocketmq.md)
- [面渣逆袭（分布式面试题八股文）必看👍](docs/sidebar/sanfene/fenbushi.md)
- [面渣逆袭（微服务面试题八股文）必看👍](docs/sidebar/sanfene/weifuwu.md)

# Java基础

>  **Java基础非常重要**！包括基础语法、面向对象、集合框架、异常处理、Java IO、网络编程、NIO、并发编程和 JVM。

## Java概述及环境配置

- [Java简史、特性、前景](docs/overview/what-is-java.md)
- [Windows和macOS下安装JDK教程](docs/overview/jdk-install-config.md)
- [在macOS和Windows上安装Intellij IDEA](docs/overview/IDEA-install-config.md)
- [编写第一个程序Hello World](docs/overview/hello-world.md)

## Java基础语法

- [48个关键字及2个保留字全解析](docs/basic-extra-meal/48-keywords.md)
- [了解Java注释](docs/basic-grammar/javadoc.md)
- [基本数据类型与引用数据类型](docs/basic-grammar/basic-data-type.md)
- [自动类型转换与强制类型转换](docs/basic-grammar/type-cast.md)
- [Java基本数据类型缓存池剖析（IntegerCache）](docs/basic-extra-meal/int-cache.md)
- [Java运算符详解](docs/basic-grammar/operator.md)
- [Java流程控制语句详解](docs/basic-grammar/flow-control.md)

## 数组&字符串

- [掌握Java数组](docs/array/array.md)
- [掌握 Java二维数组](docs/array/double-array.md)
- [如何优雅地打印Java数组？](docs/array/print.md)
- [深入解读String类源码](docs/string/string-source.md)
- [为什么Java字符串是不可变的？](docs/string/immutable.md)
- [深入理解Java字符串常量池](docs/string/constant-pool.md)
- [详解 String.intern() 方法](docs/string/intern.md)
- [String、StringBuilder、StringBuffer](docs/string/builder-buffer.md)
- [Java中equals()与==的区别](docs/string/equals.md)
- [最优雅的Java字符串拼接是哪种方式？](docs/string/join.md)
- [如何在Java中拆分字符串？](docs/string/split.md)

## Java面向对象编程

- [类和对象](docs/oo/object-class.md)
- [Java中的包](docs/oo/package.md)
- [Java变量](docs/oo/var.md)
- [Java方法](docs/oo/method.md)
- [Java可变参数详解](docs/basic-extra-meal/varables.md)
- [手把手教你用 C语言实现 Java native 本地方法](docs/oo/native-method.md)
- [Java构造方法](docs/oo/construct.md)
- [Java访问权限修饰符](docs/oo/access-control.md)
- [Java代码初始化块](docs/oo/code-init.md)
- [Java抽象类](docs/oo/abstract.md)
- [Java接口](docs/oo/interface.md)
- [Java内部类](docs/oo/inner-class.md)
- [深入理解Java三大特性：封装、继承和多态](docs/oo/encapsulation-inheritance-polymorphism.md)
- [详解Java this与super关键字](docs/oo/this-super.md)
- [详解Java static 关键字](docs/oo/static.md)
- [详解Java final 关键字](docs/oo/final.md)
- [掌握Java instanceof关键字](docs/basic-extra-meal/instanceof.md)
- [聊聊Java中的不可变对象](docs/basic-extra-meal/immutable.md)
- [方法重写 Override 和方法重载 Overload 有什么区别？](docs/basic-extra-meal/override-overload.md)
- [深入理解Java中的注解](docs/basic-extra-meal/annotation.md)
- [Java枚举：小小enum，优雅而干净](docs/basic-extra-meal/enum.md)

## 集合框架（容器）

- [Java集合框架：List、Set、Map、队列——全面解析](docs/collection/gailan.md)
- [时间复杂度](docs/collection/time-complexity.md)
- [深入探讨 Java ArrayList](docs/collection/arraylist.md)
- [深入探讨 Java LinkedList](docs/collection/linkedlist.md)
- [ArrayList和LinkedList的区别](docs/collection/list-war-2.md)
- [Java 泛型深入解析](docs/basic-extra-meal/generic.md)
- [Java迭代器Iterator和Iterable有什么区别？](docs/collection/iterator-iterable.md)
- [为什么禁止在foreach里执行元素的删除操作？](docs/collection/fail-fast.md)
- [Java HashMap详解](docs/collection/hashmap.md)
- [Java LinkedHashMap详解](docs/collection/linkedhashmap.md)
- [Java TreeMap详解](docs/collection/treemap.md)
- [Java 双端队列 ArrayDeque详解](docs/collection/arraydeque.md)
- [Java 优先级队列PriorityQueue详解](docs/collection/PriorityQueue.md)
- [Java Comparable和Comparator的区别](docs/basic-extra-meal/comparable-omparator.md)

## Java IO

- [深入了解 Java IO](docs/io/shangtou.md)
- [Java File：IO 流的起点与终点](docs/io/file-path.md)
- [Java 字节流：Java IO 的基石](docs/io/stream.md)
- [Java 字符流：Reader和Writer的故事](docs/io/reader-writer.md)
- [Java 缓冲流：Java IO 的读写效率有了质的飞升](docs/io/buffer.md)
- [Java 转换流：Java 字节流和字符流的桥梁](docs/io/char-byte.md)
- [Java 打印流：PrintStream & PrintWriter](docs/io/print.md)
- [Java 序列流：Java 对象的序列化和反序列化](docs/io/serialize.md)
- [Java Serializable 接口：明明就一个空的接口嘛](docs/io/Serializbale.md)
- [深入探讨 Java transient 关键字](docs/io/transient.md)

## 异常处理

- [一文彻底搞懂Java异常处理，YYDS](docs/exception/gailan.md)
- [深入理解 Java 中的 try-with-resources](docs/exception/try-with-resources.md)
- [Java异常处理的20个最佳实践](docs/exception/shijian.md)
- [空指针NullPointerException的传说](docs/exception/npe.md)
- [try-catch 捕获异常真的会影响性能吗？](docs/exception/try-catch-xingneng.md)

## 常用工具类

- [Java Scanner：扫描控制台输入的工具类](docs/common-tool/scanner.md)
- [Java Arrays：专为数组而生的工具类](docs/common-tool/arrays.md)
- [Apache StringUtils：专为Java字符串而生的工具类](docs/common-tool/StringUtils.md)
- [Objects：专为操作Java对象而生的工具类](docs/common-tool/Objects.md)
- [Java Collections：专为集合而生的工具类](docs/common-tool/collections.md)
- [Hutool：国产良心工具包，让你的Java变得更甜](docs/common-tool/hutool.md)
- [Guava：Google开源的Java工具库，太强大了](docs/common-tool/guava.md)
- [其他常用Java工具类：IpUtil、MDC、ClassUtils、BeanUtils、ReflectionUtils](docs/common-tool/utils.md)

## Java新特性

- [Java 8 Stream流：掌握流式编程的精髓](docs/java8/stream.md)
- [Java 8 Optional最佳指南：解决空指针问题的优雅之选](docs/java8/optional.md)
- [深入浅出Java 8 Lambda表达式：探索函数式编程的魅力](docs/java8/Lambda.md)
- [Java 14 开箱，新特性Record、instanceof、switch香香香香](docs/java8/java14.md)

## Java网络编程

- [Java网络编程的基础：计算机网络](docs/socket/network-base.md)
- [Java Socket：飞鸽传书的网络套接字](docs/socket/socket.md)
- [牛逼，用Java Socket手撸了一个HTTP服务器](docs/socket/http.md)

## Java NIO

- [Java NIO 比传统 IO 强在哪里？](docs/nio/nio-better-io.md)
- [一文彻底解释清楚Java 中的NIO、BIO和AIO](docs/nio/BIONIOAIO.md)
- [详解Java NIO的Buffer缓冲区和Channel通道](docs/nio/buffer-channel.md)
- [聊聊 Java NIO中的Paths、Files](docs/nio/paths-files.md)
- [Java NIO 网络编程实践：从入门到精通](docs/nio/network-connect.md)
- [一文彻底理解Java IO模型](docs/nio/moxing.md)

## 重要知识点

- [Java命名规范：编写可读性强的代码](docs/basic-extra-meal/java-naming.md)
- [解决中文乱码：字符编码全攻略 - ASCII、Unicode、UTF-8、GB2312详解](docs/basic-extra-meal/java-unicode.md)
- [深入浅出Java拆箱与装箱](docs/basic-extra-meal/box.md)
- [深入理解Java浅拷贝与深拷贝](docs/basic-extra-meal/deep-copy.md)
- [Java hashCode方法解析](docs/basic-extra-meal/hashcode.md)
- [Java到底是值传递还是引用传递？](docs/basic-extra-meal/pass-by-value.md)
- [为什么无法实现真正的泛型？](docs/basic-extra-meal/true-generic.md)
- [Java 反射详解](docs/basic-extra-meal/fanshe.md)

## Java并发编程

- [并发编程小册简介](docs/thread/readme.md)
- [Java多线程入门](docs/thread/wangzhe-thread.md)
- [获取线程的执行结果](docs/thread/callable-future-futuretask.md)
- [Java线程的6种状态及切换](docs/thread/thread-state-and-method.md)
- [线程组和线程优先级](docs/thread/thread-group-and-thread-priority.md)
- [进程与线程的区别](docs/thread/why-need-thread.md)
- [多线程带来了哪些问题？](docs/thread/thread-bring-some-problem.md)
- [Java的内存模型（JMM）](docs/thread/jmm.md)
- [volatile关键字解析](docs/thread/volatile.md)
- [synchronized关键字解析](docs/thread/synchronized-1.md)
- [synchronized的四种锁状态](docs/thread/synchronized.md)
- [深入浅出偏向锁](docs/thread/pianxiangsuo.md)
- [CAS详解](docs/thread/cas.md)
- [AQS详解](docs/thread/aqs.md)
- [锁分类和 JUC](docs/thread/lock.md)
- [重入锁ReentrantLock](docs/thread/reentrantLock.md)
- [读写锁ReentrantReadWriteLock](docs/thread/ReentrantReadWriteLock.md)
- [等待通知条件Condition](docs/thread/condition.md)
- [线程阻塞唤醒类LockSupport](docs/thread/LockSupport.md)
- [Java的并发容器](docs/thread/map.md)
- [并发容器ConcurrentHashMap](docs/thread/ConcurrentHashMap.md)
- [非阻塞队列ConcurrentLinkedQueue](docs/thread/ConcurrentLinkedQueue.md)
- [阻塞队列BlockingQueue](docs/thread/BlockingQueue.md)
- [并发容器CopyOnWriteArrayList](docs/thread/CopyOnWriteArrayList.md)
- [本地变量ThreadLocal](docs/thread/ThreadLocal.md)
- [线程池](docs/thread/pool.md)
- [定时任务ScheduledThreadPoolExecutor](docs/thread/ScheduledThreadPoolExecutor.md)
- [原子操作类Atomic](docs/thread/atomic.md)
- [魔法类 Unsafe](docs/thread/Unsafe.md)
- [通信工具类](docs/thread/CountDownLatch.md)
- [Fork/Join](docs/thread/fork-join.md)
- [生产者-消费者模式](docs/thread/shengchanzhe-xiaofeizhe.md)


## Java虚拟机

- [JVM到底是什么？](docs/jvm/what-is-jvm.md)
- [JVM到底是如何运行Java代码的？](docs/jvm/how-run-java-code.md)
- [我竟然不再抗拒Java的类加载机制了](docs/jvm/class-load.md)
- [详解Java的类文件（class文件）结构](docs/jvm/class-file-jiegou.md)
- [从javap的角度轻松看懂字节码](docs/jvm/bytecode.md)
- [JVM字节码指令详解](docs/jvm/zijiema-zhiling.md)
- [虚拟机是如何执行字节码指令的？](docs/jvm/how-jvm-run-zijiema-zhiling.md)
- [HSDB（Hotspot Debugger）从入门到实战](docs/jvm/hsdb.md)
- [史上最通俗易懂的ASM教程](docs/jvm/asm.md)
- [自己编译JDK](docs/jvm/compile-jdk.md)
- [深入理解JVM的内存结构](docs/jvm/neicun-jiegou.md)
- [Java 创建的对象到底放在哪？](docs/jvm/whereis-the-object.md)
- [咱们从头到尾说一次Java垃圾回收](docs/jvm/gc.md)
- [图解Java的垃圾回收机制](docs/jvm/tujie-gc.md)
- [Java中9种常见的CMS GC问题分析与解决](docs/jvm/meituan-9-gc.md)
- [Java问题诊断和排查工具（查看JVM参数、内存使用情况及分析）](docs/jvm/problem-tools.md)
- [Java即时编译（JIT）器原理解析及实践](docs/jvm/jit.md)
- [一次内存溢出排查优化实战](docs/jvm/oom.md)
- [一次生产CPU 100% 排查优化实践](docs/jvm/cpu-percent-100.md)
- [JVM 核心知识点总结](docs/jvm/zongjie.md)


# Java进阶

>  - **到底能不能成为一名合格的 Java 程序员，从理论走向实战？Java进阶这部分内容就是一个分水岭**！
>  - 纸上得来终觉浅，须知此事要躬行。

## 开发/构建工具

> 工欲善其事必先利其器，这句话大家都耳熟能详了，熟练使用开发/构建工具可以让我们极大提升开发效率，解放生产力。

- [5分钟带你深入浅出搞懂Nginx](docs/nginx/nginx.md)

### IDEA

> 集成开发环境，Java 党主要就是 Intellij IDEA 了，号称史上最强大的 Java 开发工具，没有之一。

- [分享 4 个阅读源码必备的 IDEA 调试技巧](docs/ide/4-debug-skill.md)
- [分享 1 个可以在 IDEA 里下五子棋的插件](docs/ide/xechat.md)
- [分享 10 个可以一站式开发的 IDEA 神级插件](docs/ide/shenji-chajian-10.md)

### Maven

> Maven 是目前比较流行的一个项目构建工具，基于 pom 坐标来帮助我们管理第三方依赖，以及项目打包。

- [终于把项目构建神器Maven捋清楚了~](docs/maven/maven.md)

### Git

> Git 是一个分布式版本控制系统，缔造者是大名鼎鼎的林纳斯·托瓦茲 (Linus Torvalds)，Git 最初的目的是为了能更好的管理 Linux 内核源码。如今，Git 已经成为全球软件开发者的标配。如果说 Linux 项目促成了开源软件的成功并改写了软件行业的格局，那么 Git 则是改变了全世界开发者的工作方式和写作方式。

- [1小时彻底掌握Git，（可能是）史上最简单明了的 Git 教程](docs/git/git-qiyuan.md)

## Spring

- [Spring AOP扫盲](docs/springboot/aop-log.md)
- [Spring IoC扫盲](docs/springboot/ioc.md)


## SpringBoot

- [一分钟快速搭建Spring Boot项目](docs/springboot/initializr.md)
- [Spring Boot 整合 MySQL 和 Druid](docs/springboot/mysql-druid.md)
- [Spring Boot 整合 JPA](docs/springboot/jpa.md)
- [Spring Boot 整合 Thymeleaf 模板引擎](docs/springboot/thymeleaf.md)
- [Spring Boot 如何开启事务支持？](docs/springboot/transaction.md)
- [Spring Boot 中使用过滤器、拦截器、监听器](docs/springboot/Filter-Interceptor-Listener.md)
- [Spring Boot 整合 Redis 实现缓存](docs/redis/redis-springboot.md)
- [Spring Boot 整合 Logback 定制日志框架](docs/springboot/logback.md)
- [Spring Boot 整合 Swagger-UI 实现在线API文档](docs/springboot/swagger.md)
- [Spring Boot 整合 Knife4j，美化强化丑陋的Swagger](docs/gongju/knife4j.md)
- [Spring Boot 整合 Spring Task 实现定时任务](docs/springboot/springtask.md)
- [Spring Boot 整合 MyBatis-Plus AutoGenerator 生成编程喵项目骨架代码](docs/kaiyuan/auto-generator.md)
- [Spring Boot 整合Quartz实现编程喵定时发布文章](docs/springboot/quartz.md)
- [Spring Boot 整合 MyBatis](docs/springboot/mybatis.md)
- [一键部署 Spring Boot 到远程 Docker 容器](docs/springboot/docker.md)
- [如何在本地（macOS环境）跑起来编程喵（Spring Boot+Vue）项目源码？](docs/springboot/macos-codingmore-run.md)
- [如何在本地（Windows环境）跑起来编程喵（Spring Boot+Vue）项目源码？](docs/springboot/windows-codingmore-run.md)
- [编程喵🐱实战项目如何在云服务器上跑起来？](docs/springboot/linux-codingmore-run.md)
- [SpringBoot中处理校验逻辑的两种方式：Hibernate Validator+全局异常处理](docs/springboot/validator.md)


## Netty

- [超详细Netty入门，看这篇就够了！](docs/netty/rumen.md)


## 辅助工具

- [Chocolatey：一款GitHub星标8.2k+的Windows命令行软件管理器，好用到爆！](docs/gongju/choco.md)
- [Homebrew，GitHub 星标 32.5k+的 macOS 命令行软件管理神器，功能真心强大！](docs/gongju/brew.md)
- [Tabby：一款逼格更高的开源终端工具，GitHub 星标 21.4k](docs/gongju/tabby.md)
- [Warp：号称下一代终端神器，GitHub星标2.8k+，用完爱不释手](docs/gongju/warp.md)
- [WindTerm：新一代开源免费的终端工具，GitHub星标6.6k+，太酷了！](docs/gongju/windterm.md)
- [chiner：干掉 PowerDesigner，国人开源的数据库设计工具，界面漂亮，功能强大](docs/gongju/chiner.md)
- [DBeaver：干掉付费的 Navicat，操作所有数据库就靠它了！](docs/gongju/DBeaver.md)

## 开源轮子

- [Forest：一款极简的声明式HTTP调用API框架](docs/gongju/forest.md)
- [Junit：一个开源的Java单元测试框架](docs/gongju/junit.md)
- [fastjson：阿里巴巴开源的JSON解析库](docs/gongju/fastjson.md)
- [Gson：Google开源的JSON解析库](docs/gongju/gson.md)
- [Jackson：GitHub上star数最多的JSON解析库](docs/gongju/jackson.md)
- [Log4j：Java日志框架的鼻祖](docs/gongju/log4j.md)
- [Log4j 2：Apache维护的一款高性能日志记录工具](docs/gongju/log4j2.md)
- [Logback：Spring Boot内置的日志处理框架](docs/gongju/logback.md)
- [SLF4J：阿里巴巴强制使用的日志门面担当](docs/gongju/slf4j.md)


## 分布式

- [全文搜索引擎Elasticsearch入门教程](docs/elasticsearch/rumen.md)
- [可能是把ZooKeeper概念讲的最清楚的一篇文章](docs/zookeeper/jibenjieshao.md)
- [微服务网关：从对比到选型，由理论到实践](docs/microservice/api-wangguan.md)

## 消息队列

- [RabbitMQ入门教程（概念、应用场景、安装、使用）](docs/mq/rabbitmq-rumen.md)
- [怎么确保消息100%不丢失？](docs/mq/100-budiushi.md)
- [Kafka核心知识点大梳理](docs/mq/kafka.md)

# 数据库

>  - **简而言之，就是按照数据结构来组织、存储和管理数据的仓库**。几乎所有的 Java 后端开发都要学习数据库这块的知识，包括关系型数据库 MySQL，缓存中间件 Redis，非关系型数据库 MongoDB 等。

## MySQL

- [如何保障MySQL和Redis的数据一致性？](docs/mysql/redis-shuju-yizhixing.md)
- [从根上理解 MySQL 的事务](docs/mysql/lijie-shiwu.md)
- [浅入深出 MySQL 中事务的实现](docs/mysql/shiwu-shixian.md)

## Redis

- [Redis入门(适合新手)](docs/redis/rumen.md)
- [聊聊缓存雪崩、穿透、击穿](docs/redis/xuebeng-chuantou-jichuan.md)



## MongoDB

- [MongoDB最基础入门教程](docs/mongodb/rumen.md)


# 计算机基础

>  - **计算机基础包括操作系统、计算机网络、计算机组成原理、数据结构与算法等**。对于任何一名想要走得更远的 Java 后端开发来说，都是必须要花时间和精力去夯实的。
>  - 万丈高露平地起，勿在浮沙筑高台。

- [操作系统核心知识点大梳理](docs/cs/os.md)
- [计算机网络核心知识点大梳理](docs/cs/wangluo.md)


# 求职面试

>  - **学习了那么多 Java 知识，耗费了无数的脑细胞，熬掉了无数根秀发，为的是什么？当然是谋取一份心仪的 offer 了**。那八股文、面试题、城市选择、优质面经又怎能少得了呢？
>  - 千淘万漉虽辛苦，吹尽狂沙始到金。

## 面试题&八股文

- [34 道 Java 精选面试题👍](docs/interview/java-34.md)
- [13 道 Java HashMap 精选面试题👍](docs/interview/java-hashmap-13.md)
- [60 道 MySQL 精选面试题👍](docs/interview/mysql-60.md)
- [15 道 MySQL 索引精选面试题👍](docs/interview/mysql-suoyin-15.md)
- [12 道 Redis 精选面试题👍](docs/interview/redis-12.md)
- [40 道 Nginx 精选面试题👍](docs/interview/nginx-40.md)
- [17 道 Dubbo 精选面试题👍](docs/interview/dubbo-17.md)
- [40 道 Kafka 精选面试题👍](docs/interview/kafka-40.md)
- [Java 基础背诵版八股文必看🍉](docs/interview/java-basic-baguwen.md)
- [Java 并发编程背诵版八股文必看🍉](docs/interview/java-thread-baguwen.md)
- [Java 虚拟机背诵版八股文必看🍉](docs/interview/java-jvm-baguwen.md)
- [携程面试官👤：大文件上传时如何做到秒传？](docs/interview/mianshiguan-bigfile-miaochuan.md)
- [阿里面试官👤：为什么要分库分表？](docs/interview/mianshiguan-fenkufenbiao.md)
- [淘宝面试官👤：优惠券系统该如何设计？](docs/interview/mianshiguan-youhuiquan.md)


## 优质面经

- [硕士读者春招斩获深圳腾讯PCG和杭州阿里云 offer✌️](docs/mianjing/shanganaliyun.md)
- [本科读者小公司一年工作经验社招拿下阿里美团头条京东滴滴等 offer✌️](docs/mianjing/shezynmjfxhelmtttjddd.md)
- [非科班读者，用一年时间社招拿下阿里 Offer✌️](docs/mianjing/xuelybdzheloffer.md)
- [二本读者社招两年半10家公司28轮面试面经✌️](docs/mianjing/huanxgzl.md)
- [双非一本秋招收获腾讯ieg、百度、字节等6家大厂offer✌️](docs/mianjing/quzjlsspdx.md)
- [双非学弟收割阿里、字节、B站校招 offer，附大学四年硬核经验总结✌️](docs/mianjing/zheisnylzldhzd.md)
- [深漂 6 年了，回西安的一波面经总结✌️](docs/mianjing/chengxyspnhxagzl.md)


## 面试准备

- [面试常见词汇扫盲+大厂面试特点分享💪](docs/nice-article/weixin/miansmtgl.md)
- [有无实习/暑期实习 offer 如何准备秋招？💪](docs/nice-article/weixin/zijxjjdyfqzgl.md)
- [简历如何优化，简历如何投递，面试如何准备？💪](docs/nice-article/weixin/luoczbmsddyb.md)
- [校招时间节点、简历编写、笔试、HR面、实习等注意事项💪](docs/nice-article/weixin/youdxzhhmjzlycfx.md)

## 城市选择

- [武汉都有哪些值得加入的IT互联网公司？](docs/cityselect/wuhan.md)
- [北京都有哪些值得加入的IT互联网公司？](docs/cityselect/beijing.md)
- [广州都有哪些值得加入的IT互联网公司？](docs/cityselect/guangzhou.md)
- [深圳都有哪些值得加入的IT互联网公司？](docs/cityselect/shenzhen.md)
- [西安都有哪些值得加入的IT互联网公司？](docs/cityselect/xian.md)
- [青岛都有哪些值得加入的IT互联网公司？](docs/cityselect/qingdao.md)
- [郑州都有哪些值得加入的IT互联网公司？](docs/cityselect/zhengzhou.md)
- [苏州都有哪些值得加入的IT互联网公司？](docs/cityselect/suzhou.md)
- [南京都有哪些值得加入的IT互联网公司？](docs/cityselect/nanjing.md)
- [杭州都有哪些值得加入的IT互联网公司？](docs/cityselect/hangzhou.md)
- [成都都有哪些值得加入的IT互联网公司？](docs/cityselect/chengdu.md)
- [济南都有哪些值得加入的IT互联网公司？](docs/cityselect/jinan.md)


# 学习资源

>  - **不知道学什么？不知道该怎么学？找不到优质的学习资源**？这些问题在这里统统都可以找到答案。
>  - 我会把自己十多年的编程经验和学习资源毫不保留的分享出来。

## PDF下载

- [👏下载→超1000本计算机经典书籍分享](docs/pdf/java.md)
- [👏下载→2022年全网最全关于程序员学习和找工作的PDF资源](docs/pdf/programmer-111.md)
- [👏下载→深入浅出Java多线程PDF](docs/pdf/java-concurrent.md)
- [👏下载→GitHub星标115k+的Java教程](docs/pdf/github-java-jiaocheng-115-star.md)
- [👏下载→重学Java设计模式PDF](docs/pdf/shejimoshi.md)
- [👏下载→Java版LeetCode刷题笔记](docs/pdf/java-leetcode.md)
- [👏下载→阿里巴巴Java开发手册](docs/pdf/ali-java-shouce.md)
- [👏下载→阮一峰C语言入门教程](docs/pdf/yuanyifeng-c-language.md)
- [👏下载→BAT大佬的刷题笔记](docs/pdf/bat-shuati.md)
- [👏下载→给操作系统捋条线PDF](docs/pdf/os.md)
- [👏下载→豆瓣9.1分的Pro Git中文版](docs/pdf/progit.md)
- [👏下载→简历模板](docs/pdf/jianli.md)

## 学习建议

- [计算机专业该如何自学编程，看哪些书籍哪些视频哪些教程？](docs/xuexijianyi/LearnCS-ByYourself.md)
- [如何阅读《深入理解计算机系统》这本书？](docs/xuexijianyi/read-csapp.md)
- [电子信息工程最好的出路的是什么？](docs/xuexijianyi/electron-information-engineering.md)
- [如何填报计算机大类高考填志愿，计科、人工智能、软工、大数据、物联网、网络工程该怎么选？](docs/xuexijianyi/gaokao-zhiyuan-cs.md)
- [测试开发工程师必读经典书籍有哪些？](docs/xuexijianyi/test-programmer-read-books.md)
- [校招 Java 后端开发应该掌握到什么程度？](docs/xuexijianyi/xiaozhao-java-should-master.md)
- [大裁员下，程序员如何做“副业”？](docs/xuexijianyi/chengxuyuan-fuye.md)
- [如何在繁重的工作中持续成长？](docs/xuexijianyi/ruhzfzdgzzcxcz.md)
- [如何获得高并发的经验？](docs/xuexijianyi/gaobingfa-jingyan-hsmcomputer.md)
- [怎么跟 HR 谈薪资？](docs/xuexijianyi/hr-xinzi.md)
- [程序员 35 岁危机，如何破局？](docs/xuexijianyi/35-weiji.md)
- [不到 20 人的 IT 公司该去吗？](docs/xuexijianyi/20ren-it-quma.md)
- [本科生如何才能进入腾讯、阿里等一流的互联网公司？](docs/xuexijianyi/benkesheng-ali-tengxun.md)
- [计算机考研 408 统考该如何准备？](docs/xuexijianyi/408.md)

# 知识库搭建

> 从购买阿里云服务器+域名购买+域名备案+HTTP 升级到 HTTPS，全方面记录《二哥的Java进阶之路》知识库的诞生和改进过程，涉及到 docsify、Git、Linux 命令、GitHub 仓库等实用知识点。

- [购买云服务器](docs/szjy/buy-cloud-server.md)
- [安装宝塔面板](docs/szjy/install-baota-mianban.md)
- [购买域名&域名解析](docs/szjy/buy-domain.md)
- [备案域名](docs/szjy/record-domain.md)
- [给域名配置HTTPS证书](docs/szjy/https-domain.md)
- [使用docsify+Git+GitHub+码云+阿里云服务器搭建知识库网站](docs/szjy/tobebetterjavaer-wangzhan-shangxian.md)

本知识库使用 VuePress 搭建，并基于[VuePress Theme Hope](https://theme-hope.vuejs.press/zh/)主题，你可以把[仓库](https://github.com/itwanger/toBeBetterJavaer)拉到本地后直接通过 `npm run docs:dev` 跑起来。

>前提是你已经安装好 node.js 和 npm 环境。

![](https://cdn.tobebetterjavaer.com/stutymore/README-20230829162211.png)

点击链接就可以在本地看到运行后的效果了。

![](https://cdn.tobebetterjavaer.com/stutymore/README-20230829162301.png





