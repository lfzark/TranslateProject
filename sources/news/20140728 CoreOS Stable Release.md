Translating by lfzark
CoreOS Stable Release
CoreOS稳定版发布
================================================================================
First off, [Happy SysAdmin Day][1]. We think we have a pretty good SysAdmin surprise in store for you today as we are announcing the CoreOS

首先，祝大家SysAdmin节快乐。随着今日CoreOS稳定版的发布，我们相信我们已经为SysAdmin节准备好了一个不错的惊喜。从今天起，用户可以在产品中

stable release channel. Starting today, you can begin running CoreOS in production. This version is the most tested, secure and reliable 

运行CoreOS了。这个版本是用户想要的最经考验，最安全，最可靠的CoresOS版本。这对我们来说，是一个重大的里程碑。自从2013年八月我们第一个alpha版本

version available for users wanting to run CoreOS. This is a huge milestone for us. Since our first alpha release in August 2013:

发布以来

- 191 releases have been tagged
- 191个发布版本
- Tested on hundreds of thousands of servers on the alpha and beta channels
- 在alpha和beta频道上测试了成千上万多服务器
- Supported on 10+ platforms, ranging from bare metal to being primary images on Rackspace and Google
- 支持10个以上平台，从裸机到Rackspace和Google云平台的主要镜像

It is a big day for us here at CoreOS, as we have been working hard to deliver the stable release. Of course, we couldn’t do this without the community so thank you for all of your support and contributions to the project.
对我们来说这是一个重要的日子，因为我们为了稳定版多发布付出了努力的工作。当然，如果没有社区的帮助，我们完成不了这些工作，感谢你们所有对项目的支持和贡献。
[CoreOS 367.1.0][2], our first version on the stable channel, includes the following:
[CoreOS 367.1.0][2], 我们在稳定channel上的第一个版本, 包括以下支持:

- Linux 3.15.2
- Linux 3.15.2
- Docker 1.0.1
- Docker 1.0.1
- Support on all major cloud providers, including Rackspace Cloud, Amazon EC2 (including HVM), and Google Compute Engine
- 所有主流多云服务商的支持, 包括 Rackspace Cloud, Amazon EC2 (包括 HVM), 和 Google Compute Engine
- Commercial support via [CoreOS Managed Linux][3]
- 通过 [CoreOS Managed Linux][3] 的商业支持 

This is a great opportunity to read about our [Update Philosophy][4] if you haven't already done so.
如果你还没有阅读我们的[Update Philosophy][4]，我相信这是一个不错的选择。

Please note: The stable release is not including etcd and fleet as stable, this release is only targeted at the base OS and Docker 1.0.
请注意：稳定发布版本由于稳定性不包括etcd和fleet ，此发布版
etcd/fleet stable support will be in subsequent releases.

For those of you who want to start running CoreOS in production be sure to review our quick [Switching Release Channels][5] guide. As you're booting new machines, be sure to base them off your desired channel from the beginning.

Finally, thanks to the community for your support. We can’t wait to hear your feedback. For those looking for additional support of running CoreOS in production, be sure to check out our [Managed Linux][6] offerings, as we have a full support team in place ready to answer any questions you may have.

Happy SysAdmin Day, and thank you for making the web awesome.

--------------------------------------------------------------------------------

via: https://coreos.com/blog/stable-release/

作者：Alex Polvi
译者：[译者ID](https://github.com/译者ID)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创翻译，[Linux中国](http://linux.cn/) 荣誉推出

[1]:http://sysadminday.com/
[2]:https://coreos.com/releases/#367.1.0
[3]:https://coreos.com/products/managed-linux/
[4]:https://coreos.com/using-coreos/updates/
[5]:https://coreos.com/docs/cluster-management/setup/switching-channels/
[6]:https://coreos.com/products/managed-linux/
