# ipclient_gxnu
----------前言-----------

本人即将于明年毕业，研究三年基本上属于“不务正业”的状态。

今天用某杀毒软件居然扫出广西师大出校控制器有毒，于是“怒”决定把研究过的出校控制器的协议进行开源，造福各位师弟师妹。
不仅包括校园网的协议，还有的宽带的协议，学校的宿舍宽带其实没什么特殊，只是先发一组数据包给服务器202.193.160.123，然后服务器再决定开放联通还是移动的pppoe服务器给你使用。所以如果能够自己发包，就可以用Linux上网，甚至宿舍用树莓派开debian,架个vpn，拨好号，配置好路由表，全校宽带走起。由于本人的的“不务正业”，写出了QT和Python的两个版本，QT的好处是界面好看，Python的好处是代码短，两个都能跨所有平台，Python用在服务器上更方便一点。

还有会有人问为什么要开源呢？

这些协议只是学校的私有的协议，也就桂林这一带的高校才用，逆向了也没什么商业利益，纯粹兴趣和个人需要，所以就开源啦，就是辣么任性，哈哈哈～～

--------2016.8.11-----------

1、先建一个库，整理一下，有空放一些架设vpn的细节，可以联系邮箱xzpmail@gmail.com（我不喜欢扣扣聊天）

2、上传./ipclient_python/ipclient.py 校园网出校控制器Python实现，童鞋么可以在Linux,OS X,Windows下上网了，开源的用了更放心～～

--------2016.8.12-------------

1、上传ipclient的c版本源码(osx/linux通用,windows需要装Mingw，没试过)

2、上传ipclient的c版本的osx的编译后二进制包

3、上传ipclient_qt的源码

4、上传ipclient_qt的windows版本的二进制包

5、上传ipclient的linux命令行版本，

 /binary/ipclient_cli_x64_linux........64位linux的命令行版本

 /binary/ipclient_cli_linux........32位linux的命令行版本

 /binary/ipclient_cli_x64_osx........64位osx的命令行版本

6、上传原理文档，在/doc/原理文档.pdf里面，这才是最关键的哈哈哈～～
