# ItemPreserver 插件使用指南

## 简介
ItemPreserver 是一个为 Terraria 游戏服务器设计的 TShock 插件，由 "肝帝熙恩" 开发。该插件允许服务器管理员指定某些物品在使用时不会消耗，即保持其堆叠数量不变。这对于管理服务器上的资源和提供特殊物品非常有用。

## 安装
1. 确保你的 Terraria 服务器已经安装了 TShock。
2. 下载 ItemPreserver 插件的最新版本。
3. 将插件文件解压到 TShock 的 "ServerPlugins" 文件夹中。
4. 重启服务器以加载插件。

## 配置
- 插件的配置文件位于 `TShock SavePath` 下的 `不消耗物品列表.json`。
- 使用 JSON 格式定义不消耗的物品列表和冷却时间。
- 物品列表是一个整数数组，每个整数代表一个物品的 ID。
- 冷却时间是一个整数，表示玩家在再次使用特定物品前需要等待的秒数。
- 权限：`itempreserver.use`，有该权限的玩家不被影响

## 使用
- 服务器管理员可以通过编辑配置文件来添加或移除不消耗的物品。
- 玩家在游戏中使用这些物品时，它们的堆叠数量不会减少。
- 如果玩家在冷却时间内尝试再次使用物品，将会收到错误消息提示。

## 注意事项
- 请谨慎修改冷却时间，以免影响游戏平衡。
- 确保服务器的 TShock 版本与插件兼容。
- 在进行任何配置更改后，重启服务器以确保更改生效。


## 支持与反馈
如果您在使用过程中遇到问题或有任何建议，欢迎在官方论坛或社区中提出issues或pr。
- GitHub 仓库：https://github.com/THEXN/ItemPreserver
- 感谢Tshock群诸多大佬帮助
- 本人不接受任何形式的赞助，如果可以就多关照我的服务器吧哈哈哈哈哈哈
- 如果你实在钱多没地方用，那就捐给去韩红基金会！：https://www.hhax.org/
- PS：捐款人可以填：我是泰批 或者 爱莉希雅(或者你随意)
