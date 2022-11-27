# A-guide-to-the-NAO-robot-relay-race
《机器人接力赛指南》，设备：NAO机器人

labmemzzf@qq.com

保留文章版权


## 关于WIN10无法使用自带的FTP功能的问题

在指南中有提到可以使用WIN10自带的文件管理器在地址栏输入`ftp://{IP}`访问到局域网内其他设备的资源，事实上你首先需要先手动开启WIN10的FTP功能才行，包括开启FTP服务、关闭部分防火墙功能、建立FTP账户等操作，在指南中没有提出这点，有所疏漏，现提供参考文章如下：

* [Win10搭建FTP服务器（局域网内访问）_feifei_Tang的博客-CSDN博客_ftp内网](https://blog.csdn.net/feifei_Tang/article/details/89336747)

* [Windows 10开启ftp服务 - pry_up - 博客园 (cnblogs.com)](https://www.cnblogs.com/ziyu-trip/p/7844162.html)

* [Win10开启FTP与配置（完整无错版）_zbored的博客-CSDN博客_win10打开ftp](https://blog.csdn.net/qq_34610293/article/details/79210539)

对于NAO机器人设备则无需设置，NAO机器人设备默认已关闭部分防火墙功能，允许使用FTP服务。
