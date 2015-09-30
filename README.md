# SimpleMemo
已上架应用“易便签”的源代码，如果发现bug和可优化之处，请一定告诉我：likumb@outlook.com

**下载易便签:** https://itunes.apple.com/cn/app/yi-bian-qian/id1029807896?mt=8

## 主要功能特点
- **swift2.0编写** 
- **CoreData存储数据**
- **适配Apple Watch**
- **同步便签到印象笔记**
- **分享extension**
- **支持3D Touch**
- **适配 Watch OS2**

## 代码注意点：

- 无法直接运行源代码，需要在AppDelegate的`private func setEverNoteKey()`方法中设置印象笔记的key
- app和extension之间的数据共享用到app groups，该功能需要开发者账号
