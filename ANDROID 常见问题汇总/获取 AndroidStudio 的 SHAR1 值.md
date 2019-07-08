# 获取 Android Studio 的 SHAR1 值

这篇主要记录一下如何获取 Android Studio 的 SHAR1 值。总体分为如下三个步骤：

+ 1、打开AndroidStudio的Terminal。

<p align="left">
<img alt="打开 Terminal" src="https://github.com/Simplation/Simplation.WANG/blob/master/ANDROID%20%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E6%B1%87%E6%80%BB/source/image/open_Terminal.jpg?raw=true">
</p>

+ 2、输入keytool -list -keystore D:\Soft\JDK1.8\MyJks.jks   

**这里需要注意的是：必须是在你存放的JKS文件路径才可以。**

<p align="left">
<img alt="输入 keytool -list -keystore + jks路径" src="https://github.com/Simplation/Simplation.WANG/blob/master/ANDROID%20%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E6%B1%87%E6%80%BB/source/image/input_command.jpg?raw=true">
</p>

+ 3、输入口令，正确之后就可以看到Share1的值

<p align="left">
<img alt="获取到的 SHAR1 值" src="https://github.com/Simplation/Simplation.WANG/blob/master/ANDROID%20%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98%E6%B1%87%E6%80%BB/source/image/get_shar1.jpg?raw=true">
</p>
