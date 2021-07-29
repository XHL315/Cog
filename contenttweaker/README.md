# ContentTweaker

ContentTweaker 允许你使用 ZenCode 添加物品、方块等游戏内内容。在这里提一下游戏加载顺序的问题。CrT 脚本在游戏加载配方的时候才开始被加载（即进存档的时候），而我们只能在游戏初始化注册物品、方块时，就是你在看 mojang logo 的时候。所以为了做区分，你注册物品方块的脚本需要在第一行加上 `#loader contenttweaker` 指示这个脚本由 CoT 加载，在游戏初始化时就被加载。而物品方块的注册是不能热重载的。

tl;dr: CoT 脚本不能热重载，而且需要服务端和客户端有一样的脚本（CrT 脚本服务器会自动同步）