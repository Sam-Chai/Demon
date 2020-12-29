# Demon
基于Mixin的Bukkit->Forge桥梁

目前来看，大部分的ForgeBukkit服务端（Mohist、CatServer、ArcLight等）都无法准确地挂钩Forge与Bukkit。
于是就诞生了这款插件。

该插件使用Mixin技术，混淆Bukkit插件源码（目前支持CMI、Grief全系列、Res、WorldGuard、Essentials、LuckPerms），将Bukkit插件原本够不到的Mod实体、维度、破坏方式等，进行对接，使得Bukkit插件也可以像Sponge插件一样轻松控制ForgeMod

# 目前支持控制项目
- Mod生物实体
- Mod方块
- Mod维度
- Mod生物群系
- Mod附魔书、药水效果
- Mod对方块的Listener
- Mod对实体的Listener
- Mod金币与Vault的对接
- Mod权限节点与LuckPerms的对接

# 使用方法
- 将 Demon-ForgeHook 放入./mods文件夹内
- 将 Demon-BukkitHook 放入./plugins文件夹内
- 重启服务端
- 配置./config/demon.conf文件

