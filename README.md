# NI Project
本程序旨在于帮助各大码农/程序员快速为自己的个人程序接入网络接口，以实现本地程序与网络数据比较。你也可以为内部局域网开发一套同步程序。
早期项目，此项目已经废弃！...但是你依然可以参考

## 使用NI Project你需要准备的：
（1 一个可以转存信息的网站（邮箱也可以，只要是能传递信息的就可以）

（2 你未完成的程序代码

（3 一个经过加密狗破解的易语言

## 本程序的原理
你可以完全放心使用本程序，因为除了获取数据以外，数据交流全部在本地文件库进行。这意味着如果你需要添加此Project，只需要为你的程序添加读文件就可以了。

## 使用时注意事项
### 你可以拿这个程序爬虫，但请先详细阅读各大网站的robot文件
如果你使用此程序违反了网站的爬虫规则，请后果自负。
### 本程序大部分使用易语言写，但是不会影响你正在写的代码。
这个程序实际上是一个读网络系统，因此不会对你的软件产生影响。

## 本程序教程
### 1.1-定义你的链接
你可以直接导入你的空白文本web页面链接，让接口直接在<head><p></p></head>之间获取文本。输入网址时注意带有http://或https://
### 1.2-读页面中的自定义元素
选择内容web页面，输入查找头和查找尾，让接口自动查找文本。
### 1.3-读邮箱页面
这一部分依托于邮箱功能实现，需要你准备一个测试用邮箱和一个读文件邮箱。（如果不需要测试，正常情况下只需要一个读文件邮箱）此功能的实现依托于网易邮箱。因为网易邮箱新号接收过多邮件不会被封号。读文件邮箱不需要发送邮件功能。

（1 选择Email页面，输入读文件邮箱的账户和密码，使接口连接到网易邮箱服务器。同时输入你想要的读邮件间隔时长。（建议1min为间隔）

（2 使用测试用邮箱，给读文件邮箱发一个邮箱，内容随意。

（3 检查Congifs目录的printfs.fm文件，查看[text]配置项，检查测试用邮箱发送的邮件是否和配置项内容一致。

如果内容一致，说明最基本配置环境已经完成。
### 1.4-链接读文件规则
之前说过的printfs.fm文件并不是最终输出结果，而是中间文件。请打开Programs目录中的Transcription.e源代码，并将其放在易语言中跑一下。

简单来说，Transcription.e可以帮助你自定义的提取字符串中需要的信息，也就是修改读文件规则。

关于Transcription.e的配置文件如何读写，会在下一此更新中讲解，应为现在只做到了这么多功能。

## 程序日志==TEST LOGS
20221112 开始开发项目并完成readme [FishMoy]

20221113 基本写完1.4之前的内容 [FishMoy]

#NI Project
The purpose of this program is to help major coders/programmers quickly connect their personal programs to network interfaces, in order to compare local programs with network data. You can also develop a synchronization program for the internal LAN.
##What you need to prepare to use NI Project:
(1. A website that can transfer information (email can also be used, as long as it can transmit information)
(2) Your unfinished program code
(3) An easy language that has been cracked by a encryption dog
##The principle of this program
You can use this program with complete confidence, as all data exchange takes place in the local file library, except for obtaining data. This means that if you need to add this Project, you just need to add a read file for your program.
##Precautions during use
###You can use this program to crawl, but please read the robot files of various websites in detail first
If you use this program to violate the website's crawling rules, please bear the consequences.
###Most of this program is written in Easy Language, but it will not affect the code you are writing.
This program is actually a network reading system, so it will not have any impact on your software.
##This program tutorial
###1.1- Define Your Link
You can directly import your blank text web page link, allowing the interface to directly retrieve text between<head><p></p></head>. When entering a website address, be sure to include http://or https://
###1.2- Custom elements in reading pages
Select the content web page, enter the search header and search tail, and have the interface automatically search for text.
###1.3- Read email page
This part relies on the implementation of the email function, and you need to prepare a testing email and a file reading email. If no testing is required, under normal circumstances only one file reading email is needed. The implementation of this function relies on NetEase email. Because the new NetEase email account will not be banned if it receives too many emails. The email function is not required for reading files.
(1) Select the email page, enter the account and password for the file reading email, and connect the interface to the NetEase email server. At the same time, enter the desired interval time for reading emails. (It is recommended to use a 1-minute interval)
(2) Use a testing email and send an email to the file reading email with free content.
(3) Check the printfs.fm file in the Congifs directory, check the [text] configuration item, and check if the email sent by the test email matches the content of the configuration item.
If the content is consistent, it indicates that the basic configuration environment has been completed.
###1.4- Link Reading File Rules
The printfs.fm file mentioned earlier is not the final output result, but an intermediate file. Please open the Transcription. e source code in the Programs directory and run it in Easy Language.
Simply put, Transcription. e can help you customize the extraction of required information from strings, that is, modify file reading rules.
How to read and write the configuration file of Transcription. e will be explained in the next update, as it only achieves so many functions now.
##Program log==TEST LOGS
Starting project development and completing readme [FishMoy] on November 12, 2022
20221113 basically completed the content before 1.4 [FishMoy]
