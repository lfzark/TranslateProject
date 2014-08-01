Translating By lfzark

Use Pushbullet Indicator In Ubuntu To Send Files To Android Or iOS Devices
Pushbullet的使用, 一个ubuntu系统下向Android/iOS设备推送文件的Indicator小应用
================================================================================
![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/Pushbullet_Logog.jpg)

[Pushbullet][1] is an app available for iOS and Android devices that lets you send files, links, images from your desktop to your mobile device and vice versa. Pushbullet can be used in any OS by installing extensions in Firefox or Chrome.
[Pushbullet][1]是一款iOS和Android设备与桌面系统互相传输文件、链接、图片的APP应用,Pushbullet可以在任何装有Firefox或Chrome
浏览器的操作系统上安装使用。
If you are not fan of browser extensions and want to use something more of a desktop app for **Pushbullet in Ubuntu 14.04**, you can use **Pushbullet Indicator** developed by [Atareao][2]. Pushbullet Indicator is in development stage at the moment and doesn’t have all the functionality of the official Windows desktop app but it still has enough to get you started.
如果你不是浏览器扩展插件的粉丝，却依然想使用桌面应用**Pushbullet in Ubuntu 14.04**的话，你可以使用由 [Atareao][2]开发的**Pushbullet Indicator**.Pushbullet Indicator 小应用正在正在开发阶段，并不具备官方windows桌面版应用的所有功能，但是已经足够令大家入门使用了

### Install Pushbullet Indicator in Ubuntu 14.04 and Linux Mint 17 ###
### 在Ubuntu 14.04 和 Linux Mint 17 下安装Pushbullet Indicator小应用 ###

Open a terminal and use the following commands:
打开一个终端，并且使用以下命令
    sudo add-apt-repository ppa:atareao/atareao
    sudo apt-get update
    sudo apt-get install pushbullet-indicator

The above PPA won’t work on Ubuntu 13.10.
以上个人软件包不支持运行在Ubuntu 13.10.版本

### Using Pushbullet Indicator in Ubuntu 14.04 and Linux Mint 17 ###
### 在Ubuntu 14.04 和 Linux Mint 17 下使用Pushbullet Indicator小应用 ###

- Create an account on [Pushbullet][3].
- [Pushbullet][3]为创建一个账号
- Install the Pushbullet app on your Android or iOS device.
- 在Android/iOS设备上安装Pushbullet
- After installing Pushbullet Indicator in Ubuntu or Linux Mint, start it. On the first launch, it will give the option to connect to your Pushbullet account:
- 在Ubuntu 或者Linux Mint系统安装Pushbullet Indicator小应用以后，第一次启动时，会提供一些Pushbullet账号连接的选项。如图：


![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/Pushbullet_Indicator_start.png)

- Once connected, you should also name your device, from the device tab in the above picture. If you want Pushbullet to
- 当连接完成时，你也应该从下图设备标签中命名你的设备。如果你想Pushbullet在每次开机时自动启动，你可以在从preference设备中
- 点击打开Autostart按钮自动启动(显示在下图中)
- autostart at each boot, you can choose it do so by going in preference and turn on the Autostart button (shown in the picture above).
- Once you are done with this, you will see the Pushbullet indicator in Unity panel.
- 当你做完这一步，你会看见 Pushbullet indicator 小应用出现在Unity panel

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/Use_Pushbullet_indicator_Ubuntu.jpeg)

- To send something to your smartphone, click on the indicator and select the device (linked to your Pushbullet account). It’s as simple as that.
-点击indicator，选择设备（已经连接到你的Pushbullet）以发送数据到智能手机

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/Pushbullet_Indicator_In_Ubuntu.png)

- You’ll get a notification on the other device of receiving a file. You can access them all from the Pushbullet app.
- 
- Android devices can also get notifications for phone calls, text messages and other notifications.
- If you send a file from your mobile device to your desktop, you will be notified about it:

![](http://itsfoss.itsfoss.netdna-cdn.com/wp-content/uploads/2014/07/Pushbulet_Indicator_Notification.jpeg)

- The files are not automatically saved to a certain directory. To get the file sent from other device, go to Show last push from the indicator menu, it will show you the last push available. Click on it to download the file to a directory of your choice.

### Install Nautilus extension for Pushbullet: ###
### 为Pushbullet安装Nautilus扩展 ###
Alternatively, you can also install Nautilus extension for Pushbullet to send files directly from right click menu. Use the following command:

    sudo apt-get install nautilus-pushbullet

You’ll have to authenticate it again after restarting.

Do share your experience with Pushbullet Indicator in comment section. Ciao ![](http://itsfoss.itsfoss.netdna-cdn.com/wp-includes/images/smilies/icon_smile.gif)

--------------------------------------------------------------------------------

via: http://itsfoss.com/pushbullet-indicator-ubuntu/

作者：[Abhishek][a]
译者：[译者ID](https://github.com/译者ID)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创翻译，[Linux中国](http://linux.cn/) 荣誉推出

[a]:http://itsfoss.com/author/Abhishek/
[1]:https://www.pushbullet.com/
[2]:http://www.atareao.es/
[3]:https://www.pushbullet.com/
