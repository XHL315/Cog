# 首页

当我们把目光伸向高版本的时，发现我们的魔改工具变的更多起来。先是原版自带的数据包，再是新起之秀 kudejs。老牌的 CraftTweaker 也不甘示弱，也进行了对高版本的进一步更新。然而和 1.13 原版、Forge 的极大改动一样，CraftTweaker 也进行了重写。最基本的合成添加：`recipes.addShaped` 也变成了 `craftingTable.addShaped` 。鉴于此，一份重写的教程也要出现。

一份很重要的事，1.15+ 的 CrT 支持热重载，使用 `/reload` 指令即可。

本篇教程使用的 MC 版本为 1.16.5，CrT 版本为 7.1.0.121。
