#IT校招面试名企题目汇总#
######整理：weiers  qhyuan1992@qq.com
---
历年计算机院学长找工作的问题汇总
##算法数据结构
>1.快排排序有几种方式，分别介绍其实现原理

>2.平衡二叉树

>3.STL中list、map对应的数据结构

>4.单向链表和双向链表的数据结构的实现

>5.Hashmap的value底层的存储结构

>6.哈希的主要原理

>7.怎样判断一个链表有环

>8.两个有序的单链表如何合并成一个有序的单链表

>9.一个特别大的数据，怎么计算给定范围的数组之和

>10.五子棋怎么判赢（检查当前落子点的一行，一列，左上右下和左下右上斜线是否有5个同样颜色的棋子）

>11.布龙过滤器，主要还是检查一个数据是否再海量数据中的方法（回答就是哈希，位图啥的）。

>12.俄罗斯方块游戏数据结构怎么设计，怎么表示形状，怎么判断消除

>13.搜索的时候输入一个字开始提示怎么实现的

>14.在我们使用淘点点时，怎么查找最近100家商户，数据量大；说出算法思想，要求效率高；

>15.100个数怎么选出三个最大的数

>16.找出一个字符串中第一个出现次数为一次的字符的下标

>17.int数组中保存了一个整数，如{1,2,3}，实现一个对数组加1的函数，不考虑{0,1,2,3}这种情况

>18.双向链表排序用什么排序算法比较好

>19.红黑树、平衡二叉树、B树的区别

>20.栈用数组怎么实现

>21.Map的实现原理（红黑树，红黑树能够实现快速查找的原理）

>22.STL容器有哪些，分别介绍其实现原理

>23.判断循环链表的方法

>24.1234576这个序列如果排序你会怎么做，为什么，如果是完全无序的会怎么做

>25.两个数进行交换，不额外使用变量，怎么做

>26.说出自己熟悉的排序算法以及每个算法的优缺点

>27.红黑树，B+，B-树，这个问题不会，我说我们讲二叉树最终应用到堆排序，然后让我讲堆排序实现以及优缺点、适用范围

>28.堆内存分配情况

>29.一个英文文章，含有各种单词和标点符号，从中找出A-Z都出现过至少一次的最小子串大小写不限，有点蒙了

>30.链表和数组分别适用于那些排序，为什么

>31.介绍一下数组，数组跟链表的区别，在数组和链表中查找一个特定值，数组和链表那个效率高？

>32.找数组中最大和最小元素，能否优化这个O（n）

>33.avl和红黑树的区别

>34.求二叉树的最大距离（即相距最远的两个叶子节点），写代码。

>35.求一个单链表的中间节点，要求安全检查，能直接运行的程序。

>36.字符串中第一个只出现一次的字符，如何优化算法使得遍历次数更少？

>37.两个栈实现一个队列，写代码。

>38.求二叉树的宽度，先简介思路再写代码。

##语言特性
###C++
>1.volatile

>2.用C实现面向对象(例如多态)

>3.C++多态、虚函数、重载多态是什么？虚函数实现原理

>4.Vector的底层是怎样的

>5.C++三大特性(继承、多态、封装)

>6.New和malloc都能创建新的对象，区别在哪？哪个效率高

>7.文件存储，文件删除了内存里面还有木有，能不能找回来

>8.函数变量存储在堆中还是栈中，什么时候分配什么时候回收

>9.接口、抽象类、集合

>10.构造函数和析构函数是否可以定义为虚函数（构造函数不能，析构函数尽可能定义成
虚函数）

>11.内部类的作用

>12.索引的作用、实现

>13.==和equals区别

>14.内部类、外部类；如何声明一个内部类，几种内部类的区别，有哪些map;list与set的
区别，有哪些list

>15.右值引用的概念

>16.Auto关键字

>17.C++的lambda函数实现原理，C++的函数对象是如何实现的

>18.C++11的几个智能指针分别怎么用

>19.Vector实现高效内存管理的原理

>20.头文件include“”和<>区别

>21.一个空类多大，一个空类的子类如果也是空，多大，为什么

>22.如果你定义一个string类，里面会有哪些函数

>23.堆栈的区别

>24.指针引用的区别

>25.static的用法

>26.申请内存和释放内存的函数是什么

>27.堆和栈的区别

>28.栈帧是什么？

>29.函数传参是怎么传的？如何入栈？根据类型大小的不同，系统是如何选择pushl还是pu
shb的？

>30.override和overload的区别。

>31.多线程的适用场景是什么？为啥要用多线程？

>32.static关键字作用（区分C语言和C++，两种语言下作用有所不同）。

###JAVA
>1.jvm问了类加载机制的流程，同一个类用不同加载器加载是否相同（当然不同），然后问了hashSet如何保证元素唯一性的？

>2.jvm内存管理、java内存泄露、异常

>3.finallyfinal使用

>4.hashmap的实现机制，hashmap和treemap区别

>5.hashcode和equals的区别

>6.java中集合如何排序

##系统实现（linux）
>1、linux命令、查cpu使用率

##网络
>1.HTTP、TCP协议、

>2.https的理解，http的各个方法的使用场景

>3.滑动窗口协议、滑动窗口的大小是怎么分配的

>4.httpcode404,200,302含义

>5.DNS解析过程

>6.Cookie简单介绍一下

>7.getpost区别

>8.7层TCP、IP协议分别在哪层

>9.TCP中time_wait作用

>10.TCP与UDP编程区别

>11.进程间通信的方式都有哪些

>12.两个文件，每个文件中有50亿URL，找出两个文件中相同的URL

>13.http错误码

>14.tcpsyn丢包，重连的时间

>15.tcp长连接和短连接的区别

>16.socket编程相关，如果服务器这边调用write写了100个字节的数据，客户端想要获得
这个数据，是直接用read系统调用，参数也是100吗？

>17.TCP/IP协议栈各个层次及分别的功能

>18.TCP长连接的保持消耗流量不，有什么优劣势

>19.HTTP各个状态码代表的含义

>20.写一个get请求包头

##操作系统
>1.进程wait的状态是怎么引起的

>2.死锁、怎么处理死锁、怎么预防死锁

>3.缓存处理的算法有哪些，讲一讲LRU算法

>4.缓存memrycache、缓存的作用

>5.同步机制synchronized、Lock

>6.线程、线程池使用

>7.守护线程和普通线程区别

>8.一个页面从输入URL到页面加载完的过程中都发生了什么事情

>9.进程与线程的区别

>10.UDP怎么模拟TCP可靠传输

>11.用户态和内核态的好处

>12.程序运行需要经过哪些过程

>13.多线程

>14.进程管理

>15.线程安全

>16.线程与进程的区别

>17.线程sleep和wait区别，线程同步机制（Synchronized，lock）

>18.inode节点，文件名是否存放在inode节点里，

>19.进程和线程的区别，chrome是多进程的还是多线程的（答案是多进程的），

>20.如何创建进程，如何创建守护进程

>21.套接字从write写入数据后，数据是如何发送到远端主机的

>22.x86计算机和网络字节序分别是什么

>23.举个会发生死锁的例子

>24.进程调度算法，有哪些算法比较难实现？

>25.linux下如何修改进程优先级？（nice命令的使用）。

>26.linux下性能监控命令uptime介绍，平均负载的具体含义是什么？建议看serverload概念。

>27.linux下如何调试程序？说到gdb，具体如何调试？如何查看core文件中的堆栈信息等（bt指令）。

##数据库
>1.mysql的底层存储的数据结构是啥

>2.数据库里面的索引

>3、有A,B用户，从A转100块钱到B用户，写出sql语句，需要注意的问题

>4、数据库事物

>5.数据库优化

>6.数据库插入数据时怎么判断是否重复操作

>7.索引、唯一索引

>8.什么是事物，隔离性的四个级别

>9.join语句和数据库移植问题

>10.mysql的表引擎

>11.事务的几个特性（含义+举例说明）。

>12.用MySQL语法建一个学生表，包括学生姓名、性别、年龄、班级信息。

>13.char()与varchar()的区分，什么情况下用char()？（两者区别很重要）

>14.建过索引吗？什么情况下需要建立索引？

>15.索引的作用？为什么能够提高查询速度？（索引的原理）

>16.索引有什么副作用吗？

>17.在sql语句中加上字符集的方法。

##大数据
>1.分布式系统怎么根据日志实现故障报警（检查日志文件单位时间正确的量和错误的量的变化，动态采样。）如何统计各分布式机器上的日志（根据日志，将某个模块的日志数量求和上报，发现故障直接连入该故障机器检查日志，有点类似namenode和datanode的关系）

>2.让自己设计一个类似map/reduce的分布式计算方法，能够实时计算大量数据

>3.聚类算法、分类算法

##设计模式
>1.用到的设计模式、再说一个设计模式

>2.画设计模式的类图(观察者模式)

>3、单例模式

##建模
>1、一个水果经营商每天去市场进水果和干果，拿到自己商店卖，每天盘点库存，期望得到收支平衡的数据。抽象建模，抽象出各个类的层次，说明其协作关系。说明组合方式和依赖方式的区别

##开放性问题
>1.两个文本文件，一个是过年发红包的1亿个qq用户的id信息，另外一个是5千万个会员的id信息，求出过年发红包的会员，也即两个的交集

>2.你家有头牛，你如何说服别人把你家牛卖个好价钱

>3、在服务器和客户端上有两个文件，均为10G，其中只有一个字节出错，如何用最快的方式同步这两个文件

##项目:
>我从项目的选题（为啥要做这个方向）、项目采用的技术、新颖的地方、最终达到的效果（由于我做的是某个算法的性能提高，那么我就会讲速度提高了多少？空间压缩了多少？）这几个方面详细介绍了自己的项目。