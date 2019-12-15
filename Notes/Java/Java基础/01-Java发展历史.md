##一 Java发展历史
####1 Java语言简介
Java语言是一种通用、并发、基于类且面向对象的语言。Java是一种高级语言，编译器将Java源码编译成字节码（bytecode），再由Java虚拟机（JVM）内嵌的解释器将字节码转换成最终的机器码。

Java语言最显著特性有两方面，一个是Write once，run anywhere（一次编写，到处运行），实现了跨平台的能力，在不同操作系统都可运行，不需要重新编码代码；第二是垃圾收集（GC，Garbage Collection），Java通过垃圾收集器实现自动分配和回收内存，大多数情况下，对于程序员不需要自己去实现内存的管理。

Java语言规范（The Java Language Specification）对于Java的语法、词汇、类型和程序结构等都做出了明确的规范要求。Java虚拟机规范（The Java Virtual Machine Specification）对于Java虚拟机的实现提供了规范标准，各个厂家的虚拟机在具体实现时会有所差别。Java语言规范是由JCP（Java Community Process）发展和更新，通过提交JSR（Java Specification Requests），通过特定程序，该更新进入到下一个版本中。目前，更新后的Java语言规范也可以在oracle官网（https://www.oracle.com/technetwork/java/index.html）查看。

Java分为三个体系：
    1.JavaSE（J2SE）（Java 2 Platform Standard Edition，java平台标准版）；
    2.JavaEE（J2EE）（Java 2 Platform Enterprise Edition，java平台企业版）；
    3.JavaME（J2ME）（Java 2 Platform Micro Edition，java平台微型版）。
####2 Java发展历史
1995年5月23日，Java语言诞生，由Sun Microsystems公司于1995年5月推出的Java面向对象程序设计语言和Java平台的总称。由James Gosling和同事们共同研发，并在1995年正式推出。

1996年1月，第一个JDK-JDK1.0诞生。

1996年4月，10个最主要的操作系统供应商申明将在其产品中嵌入JAVA技术。

1996年9月，约8.3万个网页应用了JAVA技术来制作。

1997年2月18日，JDK1.1发布。

1997年4月2日，JavaOne会议召开，参与者逾一万人，创当时全球同类会议规模之纪录。

1997年9月，JavaDeveloperConnection社区成员超过十万。

1998年2月，JDK1.1被下载超过2,000,000次。

1998年12月8日，JAVA2企业平台J2EE发布。

1999年6月，SUN公司发布Java的三个版本：标准版（JavaSE,以前是J2SE）、企业版（JavaEE以前是J2EE）和微型版（JavaME，以前是J2ME）。

2000年5月8日，JDK1.3发布。

2000年5月29日，JDK1.4发布。

2001年6月5日，NOKIA宣布，到2003年将出售1亿部支持Java的手机。

2001年9月24日，J2EE1.3发布。

2002年2月26日，J2SE1.4发布，自此Java的计算能力有了大幅提升。

2004年9月30日18:00PM，J2SE1.5发布，成为Java语言发展史上的又一里程碑。为了表示该版本的重要性，J2SE1.5更名为Java SE 5.0。

2005年6月，JavaOne大会召开，SUN公司公开Java SE 6。此时，Java的各种版本已经更名，以取消其中的数字"2"：J2EE更名为Java EE，J2SE更名为Java SE，J2ME更名为Java ME。

2006年12月，SUN公司发布JRE6.0。

2009年04月20日，甲骨文74亿美元收购Sun，取得Java的版权。

2010年11月，由于甲骨文对于Java社区的不友善，因此Apache扬言将退出JCP。

2011年7月28日，甲骨文发布 Java7.0 的正式版。

2014年3月18日，Oracle公司发表 Java SE 8。

2017年9月21日，Oracle公司发表 Java SE 9。

2018年3月21日，Oracle公司发表 Java SE 10。

2018年9月25日，Java SE 11 发布。

2019年3月20日，Java SE 12 发布。

####3 Java开发环境
	1.安装JDK
下载JDK到oracle官网地址下载，根据不同操作系统选择不同JDK，直接安装即可。如下地址：https://www.oracle.com/technetwork/java/javase/downloads/index.html。

    2. 环境变量配置
需要配置的环境变量如下三个：
    JAVA_HOME为实际JDK安装路径；
    CLASSPATH为.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar; 
    PATH为%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;
    
    3.集成开发环境（IDE）
开发环境选择Eclipse、JetBrains的IDEA、Notepad++等，各有优劣，适合就好，建议用IDEA。
