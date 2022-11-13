# NI Project
本程序旨在于帮助各大码农/程序员快速为自己的个人程序接入网络接口，以实现本地程序与网络数据比较。你也可以为内部局域网开发一套同步程序。

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
你可以直接导入你的空白文本web页面链接，让接口直接在<head><p></p></head>之间获取文本。
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
### 20221112
开始开发项目并完成readme [FishMoy]