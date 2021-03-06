## JVM&GC

### 1. Java 类加载过程？

### 2. 描述一下 JVM 加载 class 文件的原理机制？

### 3. Java 内存分配？

### 4. Java 堆的结构是什么样子的？什么是堆中的永久代（Perm Gen space）？

### 5. GC 是什么？为什么要有 GC？

### 6. 简述 Java 垃圾回收机制。

### 7. 如何判断一个对象是否存货？（或者 GC 对象的判定方法）

### 8. 垃圾回收的优点和原理。并考虑 2 种回收机制。

### 9. 垃圾回收器的基本原理是什么？垃圾回收器可以马上回收内存吗？有什么办法主动通知虚拟机进行垃圾回收？

### 10. Java 中会存在内存泄露吗？请简单描述。

### 11. 深拷贝和浅拷贝？

### 12. System.gc() 和 Runtime.gc() 会做什么事情？

### 13. finalize() 方法什么时候被调用？析构函数（finalization）的目的是什么？

### 14. 如果对象的引用被置为 null, 垃圾回收器是否会立即释放对象占用的内存？

### 15. 什么是分布式垃圾回收（DGC）？它是如何工作的？

### 16. 串行（serial）收集器和吞吐量（throughput）收集器的区别是什么？

### 17. 在 Java 中，对象什么时候可以被垃圾回收？

### 18. 简述 Java 内存分配与回收策略以及 Minor GC 和 Major GC。

### 19. JVM 的永久代中会发生垃圾回收吗？

### 20. Java 中垃圾手机的方法有哪些？

### 21. 什么是类加载器，类加载器有哪些？

### 22. 类加载器双亲委派模型机制？


## 算法&集合

### 1. List、Set、Map 的区别？

### 2. List 和 Map 的实现方式以及存储方式？

### 3. HashMap 的实现原理？

### 4. HashMap 的数据结构？

### 5. HashMap 的源码理解？

### 6. HashMap 如何 put 数据（从源码角度解读）

### 7. HashMap 手写实现？

### 8. ConcurrentHashMap 的实现原理？

### 9. ArrayMap 和 HashMap 的对比？

### 10. HashTable 实现原理？

### 11. TreeMap 具体实现？

### 12. HashMap 和 HashTable 的区别？

### 13. HashMap 和 HashSet 的区别？

### 14. HashSet 和 HashMap 怎么判断集合元素重复？

### 15. 集合 Set 实现 Hash 怎么防止碰撞？

### 16. ArrayList 和 LinkedList 的区别以及应用场景？

### 17. 数组和链表的区别？

### 18. 二叉树的深度优先遍历和广度优先遍历的具体实现？

### 19. 堆和树的区别？

### 20. 堆和栈在内存中的区别是什么？

### 21. 讲一下对数、B+ 树的理解？

### 22. 讲一下对图的理解？



## 设计模式&框架基础

### 1. 为什么需要代理模式？

### 2. 讲讲静态代理模式的优点及其瓶颈？

### 3. 对 Java 接口代理模式实现原理的理解？

### 4. 如何使用 Java 反射实现动态代理？

### 5. Java 接口代理模式的指定增强？

### 6. 谈谈对 CGLIB 类增强动态代理的实现？

### 7. 什么是 AOP？

### 8. point cut, advice, join point 是什么？

### 9. join point 和 point cut 的区别？

### 10. 怎么理解面向切面编程的切面？

### 11. 谈谈对 SpringAOP Weaving（织入）的理解？

### 12. 谈谈对 SpringAOP Introduction（引入）的理解？

### 13. 讲解 OOP 和 AOP 的简单对比？

### 14. 讲解 JDK 动态代理和 CGLIB 代理原理及区别？

### 15. 什么是 IOC？

### 16. 谈谈对控制反转设计思想的理解？

### 17. 怎么理解 Spring IOC 容器？

### 18. Spring 中有多少种 IOC 容器？

### 19. Spring IOC 怎么管理 Bean 之间的依赖关系，怎么避免循环依赖？

### 20. 说说对 Spring IOC 的单例模式和高级特性？

### 21. BeanFactory 和 FactoryBean 有什么区别，BeanFactory 和 ApplicationContext 又有什么不同？

### 22. Spring 在 Bean 创建过程中是如何解决循环依赖的？

### 23. 谈谈 Spring Bean 创建过程中的设计模式？

### 24. 为何能够直接使用 @Autowired 进行依赖注入？是如何工作的？

### 25. Spring 是如何通过 @Autowired 自动注入 Bean 属性和 Map、List 集合的？

### 26. @Required 是如何起到检查 XML 里面属性有没有被配置的？

### 27. Spring 框架是如何把标注 @Component 的 Bean 注入到容器？

### 28. @Configuration、@ComponentScan、@Import、@Bean 注解是如何工作的？

### 29. 使用 @PropertySource 引入配置文件，那么配置文件里面的配置是如何被注册到 Spring 环境里面的？

### 30. @Transactional 注解是否可以加在 private、protected 方法上？

### 31. 为什么抛出了异常，事务却没有回滚？

### 32. Spring 事务是如何保证线程安全的？


## 并发编程与锁

### 1. Synchronized 用过吗，其原理是什么？

### 2. 你刚才提到获取对象的锁，这个 "锁" 到底是什么？如何确定对象的锁？

### 3. 什么是可重入性，为什么说 Synchronized 是可重入锁？

### 4. JVM 对 Java 的原生锁做了哪些优化？

### 5. 为什么说 Synchronized 是非公平锁？

### 6. 什么是锁消除和锁粗化？

### 7. 为什么说 Synchronized 是一个悲观锁？乐观锁的实现的原理又是什么？

### 8. 乐观锁一定是好的吗？

### 9. 跟 Synchronized 相比，可重入锁 ReentrantLock 其实现有什么不同？

### 10. 请谈谈 AQS 框架是怎么回事？

### 11. 请尽可能详尽地对比下 Synchronized 和 ReentrantLock 的异同？

### 12. ReentrantLock 是如何实现可重入性的？

### 13. 除了 ReentrantLock，你还接触过 JUC 中哪些并发工具？

### 14. 请谈谈 ReadWriteLock 和 StampedLock。

### 15. 如何让 Java 的线程彼此同步？你了解过哪些同步器？分别介绍下。

### 16. CyclicBarrier 和 CountDownLatch 看起来很相似，请对比下呢？

### 17. Java 中的线程池是如何实现的？

### 18. 创建线程池的几个核心构造参数？

### 19. 线程池中的线程是怎么创建的？是一开始就随着线程池的启动创建好的吗？

### 20. 既然提到可以通过不同参数创建出不同的线程池，那么 Java 中默认实现好的线程池有哪些？请比较它们的异同。

### 21. 如何在 Java 线程池中提交线程？

### 22. 什么是 Java 的内存模型，Java 中各个线程是怎么彼此看到对方的变量的？

### 23. 请谈谈 volatile 有什么特点，为什么它能保证变量对所有线程的可见性？

### 24. 既然 volatile 能够保证线程间的变量可见性，是不是就意味着基于 volatile 变量的运算就是并发安全的？

### 25. 请对比下 volatile 和 Synchronized 的异同。

### 26. 请谈谈 ThreadLocal 是怎么解决并发安全的？

### 27. 很多人都说要慎用 TreadLocal，谈谈你的理解，使用 ThreadLocal 需要注意什么？


## Dubbo 专项

### 1. 简述一下你了解的 dubbo？

### 2. dubbo 主要解决了哪些 rpc 问题？

### 3. dubbo 有哪些功能？

### 4. dubbo 的核心组件有哪些？

### 5. dubbo 的主要应用场景？

### 6. 类与类依赖关系是什么？

### 7. dubbo 在项目之间的依赖划分？

### 8. 如何划分 dubbo 分布式服务？

### 9. dubbo 默认使用的是什么通信框架？还有别的选择吗？

### 10. dubbo 支持的协议有哪些？每种协议应用场景的优缺点是什么？

### 11. dubbo 推荐用的协议是什么？

### 12. dubbo 服务启动、调用、暴露消费的过程？

### 13. 讲讲 dubbo 的服务引用、服务拦截？

### 14. dubbo 的注册中心有哪些？默认的注册中心是什么？

### 15. 服务调用是阻塞的吗？

### 16. 服务提供者能实现失效提出是什么原理？

### 17. 如何解决服务调用链过长的问题？

### 18. 如何设计一个 dubbo 服务接口？

### 19. 如何完成 dubbo 服务只订阅及只注册模式？

### 20. dubbo 集群的负载均衡策略有哪些？

### 21. dubbo 的集群容错怎么做？

### 22. dubbo 的并发控制如何实现？

### 23. 简述 dubbo 的容错机制及高扩展性？

### 24. 讲讲 dubbo 直连、cmd 远程调试？

### 25. 基于 dubbo 的服务降级实现和灰度发布如何实现？

## 数据库【MySQL】

### 1. MySQL 有哪些存储引擎？都有什么区别？

### 2. float、decimal 存储金额的区别？

### 3. 什么是索引？

### 4. 对比一下 B+ 树索引和 Hash 索引？

### 5. MySQL 索引类型有？

### 6. 如何管理 MySQL 索引？

### 7. 对 Explain 参数及重要参数的理解？

### 8. 索引利弊是什么以及索引的分类？

### 9. 二叉树的转置是什么？

### 10. 聚簇索引和非聚簇索引的区别？

### 11. B+树 如何进行优化？索引遵循哪些原则？存储引擎会进行哪些自动优化？到底何时索引会失效？

### 12. 谈谈对 InnoDB 事务的理解？

### 13. 说说数据库事务特点及潜在问题？

### 14. 什么是 MySQL 隔离级别？

### 15. 有多少种事务失效的场景？如何解决？

### 16. 一致性非锁定读和一致性锁定读是什么？

### 17. InnoDB 如何解决幻读？

### 18. 讲讲 InnoDB 行锁？

### 19. 死锁及监控是什么？

### 20. 自增长与锁、锁的算法、锁问题、锁升级是什么？

### 21. 乐观锁的线程如何做失败补偿？

### 22. 高并发场景（领红包）如何防止死锁，保证数据一致性？

### 23. 谈谈 MySQL 的所并发？

### 24. 了解查询优化器模块吗？

### 25. 查询优化的基本思路是什么？

### 26. 说说 MySQL 读写分离、分库分表？

### 27. 浅谈索引优化？

### 28. JOIN 的原理是什么？

### 29 说说 SQL 优化的几点原则？

### 30. 说说 MySQL 几种存储引擎引用场景？

### 31. MySQL 常用优化方式有哪些？

### 32. MySQL 常用监控？

### 33. MySQL 瓶颈分析？


## 数据库【Redis】

### 1. Redis 有哪几种数据淘汰策略？

### 2. 什么 CAP 理论？

### 3. Redis 集群方案应该怎么做？都有哪些方案？

### 4. Redis 集群方案什么情况下会导致整个集群不可用？

### 5. MySQL 里有 2000W 数据，Redis 中只存 20W 的数据，如何保证 Redis 中的数据都是热点数据？

### 6. Redis 有哪些适合的场景？

### 7. Redis 支持的 Java 客户端都有哪些？官方推荐用哪个？

### 8. Redis 和 Redisson 有什么关系？

### 9. Redis 和 Redisson 对比有什么优缺点？

### 10. 说说 Redis 哈希槽的概念？

### 11. Redis 集群的主从复制模型是怎样的？

### 12. Redis 集群会有写操作丢失吗？为什么？

### 13. Redis 集群之间是如何复制的？

### 14. Redis 的管道有什么用？

### 15. 使用过 Redis 分布式锁吗？它是怎么实现的？

### 16. 简述 Redis 分布式锁的缺陷？

### 17. 讲讲对 Redisson 实现 Redis 分布式锁的底层原理的理解？

### 18. 加锁机制、锁互斥机制、watch dog 自动延期机制、可重入加锁机制、锁释放机制是什么？

### 19. Redis 的 setnx 命令是如何实现分布式锁的？

### 20. 说说对 setnx 的实现锁的原理的理解？

### 21. 如何避免死锁的出现？

### 22. 怎么理解 Redis 事务？

### 23. Redis 事务相关的命令有哪几个？

### 24. Redis key 的过期时间和永久有效分别怎么设置？

### 25. Redis 如何做内存优化？

### 26. Redis 回收进程如何工作的？

### 27. 使用过 Redis 做异步队列吗？是你怎么用的？有什么缺点？

### 28. 什么是缓存穿透？如何避免？什么是缓存雪崩？如何避免？

### 29. Redis 如何与 MySQL 数据库结合起来？

### 30. 应用通过 Redis 客户端进行读取并展示，是所有的数据都是这么做吗？

### 31. 在修改数据的时候修改到 Redis 吗？还是直接修改 MySQL？

### 32. 如果修改 Redis 中的数据，那什么时候同步到 MySQL，是被迫的，还是开发人员可控的？

### 33. 如果直接修改 MySQL 中数据，那 Redis 中数据会被同步吗？如何做到的？


## 数据库【NewSQL】




