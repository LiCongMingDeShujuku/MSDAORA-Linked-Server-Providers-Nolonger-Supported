![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# MSDAORA Linked服务器Providers, 不再支持
#### MSDAORA Linked Server Providers Nolonger Supported
**发布-日期: 2007年10月7日 (评论)**

![#](images/##############?raw=true "#")

## Contents

- [中文](#中文)
- [English](#English)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文
如果你运气不好想要尝试用在64位环境中熟悉的MSDAORA在SQL和Oracle之间设置链接服务器。
微软已确认他们在64位环境中不支持MSDAORA provider。

当你查看链接服务器下管理工作室的providers列表时，你会发现这一点。列表中没有任何Oracle provider 或者 Oracle variant。记住，这跟你如何安装和配置你的SQL服务器无关。他们只是不再提供而已。

你不得不使用Oracle驱动，在你安装Oracle客户端时会自动获得。一旦安装，你会看到ORAOLEDB.oracle管理工作室列出的provider。

假设你有一个64位的SQL 服务器，并且你正在尝试连接到32位的Oracle实例......这让事情变得更加困难。
传统观点认为，你需要为这两种数据源提供64位环境来让它运作。

不过，我曾读到过说：如果你同时拥有64位Oracle客户端，则可以将它进行设置安装在32位Oracle客户端旁边。

这些信息对某些人来说可能不是完全陌生的，但我觉得我还是需要提一下。

可能会在你创建链接服务器而无法调用ms时帮到忙。



## English
If you are trying to setup a linked server between SQL and Oracle using
the familiar MSDAORA in a 64bit environment your out of luck.

Microsoft has confirmed that they DO NOT support the MSDAORA provider
in in 64bit environments. you’ll notice this straight-away when looking over
the providers list from management studio under Linked Servers. any Oracle
provider or variant is missing from the list. remember that this has nothing
to do with how you installed and configured your SQL Server. it simply is
no longer offered.

You have to use the Oracle driver ( ORAOLEDB.oracle ) which you get automatically
when you install the Oracle client. once installed you’ll see the ORAOLEDB.oracle
provider listed in management studio.

Suppose you have a 64bit SQL Server, and you are trying to connect to a 32bit
Oracle instance… that just makes things more difficult.

The conventional wisdom is that you need to have 64bit environments for both data
sources to get it to work. I’ve read though; that the setup is possible if you have both the 64bit Oracle client installed along side the 32bit Oracle Client.
this information may not be entirely new for some; but thought I would mention
it regardless. Might save you call into ms over creating a linked server.




[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

