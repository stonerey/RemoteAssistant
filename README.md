# Hololens 远程视频通讯

*中文*｜ [**English**](README_en.md) 

## 介绍
RemoteMark是一款支持Hololens与Android,PC视频通讯并支持空间标注的软件，功能类似微软的[Remote Assist](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/remote-assist/ra-overview)
#### Video: https://youtu.be/fa6ECxv6nKk
#### PC与Hololens视频通讯截图
#### Remote Assistant SDK :https://github.com/stonerey/RemoteAssistantSDK
![Image text](Image/pc.jpg)
#### PC聊天截图
![Image text](Image/pc_chat.jpg)
##### Android与Hololens视频通讯截图
![Image text](Image/android.jpg)
#### Hololens 视频通讯截图
![Image text](Image/hls.jpg)
![Image text](Image/hls2.jpg)
## 运行条件

#### 1.运行服务器XRChatServer.exe，需要在本地电脑安装MySQL数据库，然后创建数据库：chatsql,密码：123456。port:3306。然后将tools文件夹下的account.dbf导入数据库中。数据表中UserAvatar填写你自己的用户头像地址。

![Image text](Image/sqlset.png)
![Image text](Image/SQL.png)
#### 2、先运行服务器然后再运行PC、Hololens客户端。
#### 3、Hololens 的运行文件较大 需要安装 git lfs:https://git-lfs.github.com。或者手动单独下载
![Image text](Image/hlsload.jpg)
## 其他说明
#### 1、如需正式版本请联系1053050442@qq.com
