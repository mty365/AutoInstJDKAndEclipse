 # AutoInstJDKAndEclipse
Windows平台自动安装JDK、Eclipse、Tomcat、Navicat、VC运行库、MySQL脚本

专为Java初学者设计，让Java开发的学习环境安装更简单。 



本软件使用到的组件版本（如组件已有64位版本，那么本软件也会使用64位的软件包）： 

JDK：8 

Eclipse：Eclipse IDE for Enterprise Java and Web Developers 2021-09

Tomcat：8.5.76 

Navicat：12 Premium 

VC运行库：包含2005-2019所有常用版本 

MySQL：8.0.22 

注：Tomcat、Navicat、MySQL为基于官方版本制作的定制包，如果您使用官方站下载的软件包，会出现报错（如指定的路径无法访问），其他软件包是官方原版。  



使用方法:  

1. 下载最新版本软件压缩包到电脑，并解压全部文件;  如果您想下载JDK和Eclipse其他版本的官方包，可以按（2）（3）步骤操作。 

   软件包下载地址：

   https://pan.baidu.com/s/1jje8_PhkA4DApHFjsdpgyA?pwd=6f83

   提取码:6f83

2. 下载JDK8 x64到刚才解压的文件夹（install.exe所在目录），并更名为jdk-8-windows-x64.exe;  

3. 下载Eclipse IDE for Java Developers压缩包到刚才解压的工具文件夹，并更名为eclipse.zip;  

4. 移动（1）步骤中software目录下的所有软件包到脚本解压目录，并替换（2）（3）步骤中另外下载的软件包（如果下载了） 

5. 运行install.exe，关注运行提示，耐心等待安装即可 

   注意：在初始化MySQL步骤时会有一个“Enter Password”提示，遇到直接回车即可继续执行。  

JDK8下载地址:  https://www.oracle.com/java/technologies/downloads/#java8-windows  

Eclipse下载地址:  https://www.eclipse.org/downloads/packages/  

也可以点击直链:  https://mirrors.neusoft.edu.cn/eclipse/technology/epp/downloads/release/2021-09/R/eclipse-java-2021-09-R-win32-x86_64.zip  

如果您喜欢该项目，希望您可以支持一下作者哦（微信赞赏码小额支持），感谢！同样，欢迎大家为该项目Star。

![赞赏码](https://github.com/mty365/LogDumpForWindows/blob/master/images/support.png)



2.0版本更新日志：

2.0新版本，不仅可以自动部署JDK和Eclipse，我们还扩充了它的能力，现在还能自动部署Tomcat、Navicat、VC运行库、MySQL啦～ 

同时： 

优化 JDK安装目录为当前系统所在分区下Java目录 

优化 目录名称格式，不再使用短目录名称格式

优化 软件包解压路径规则
