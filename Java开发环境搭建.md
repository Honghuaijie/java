# java开发环境搭建

## 1.什么是JDK、JRE

- JDK（java Development Kit): 是java程序开发工具包，包含JRE和开发人员使用的工具
- JRE（Java Runtime Environment)：是java程序的运行时环境，包含JVM和运行时所需要的核心类库

![image-20230523143133454](C:\Users\Admin\AppData\Roaming\Typora\typora-user-images\image-20230523143133454.png)

小结：

JDK=JRE + 开发工具集（例如javac编译工具等）

JRE=JVM +JAVA SE标准类库



## 2.JDK版本选择

jdk下载地址

https://www.oracle.com/java/technologies/downloads/#jdk17-windows



### 3.配置PATH环境变量

什么是path环境变量？

答：window操作系统执行命令时，所要搜寻的路径

为什么要配置path？

答：希望在命令行使用java.exe等根据时，任意目录下都可以找到工具所在的目录