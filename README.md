# FFXIVChnTextPatch-Souma

本项目修改自 [FFXIVChnTextPatch-GP](https://github.com/GpointChen/FFXIVChnTextPatch-GP)

## 声明

使用汉化补丁是属于修改客户端的作弊行为，使用本汉化即表示你自愿承担一切后果。

我的日语是看番学的，英语是不太好的，并且完全不看剧情，所以请 **不要** 对翻译质量有什么期望。

我是一个人维护这个项目，难免会有错漏，所以请 **不要** 指望翻译的绝对正确性。

## 下载

从 [Release](https://github.com/Souma-Sumire/FFXIVChnTextPatch-Souma/releases/) 下载最新版本的汉化补丁

- 注意！当你展示道具 `<item>` 时，别人会如实看到你所展示的物品名称中文（以发送者的语言显示）
- 这些情况是安全的：`<t>` `<pos>` `<flag>` `<招募信息>` `<定型文>` `<系统情感动作>`（以接受者的语言显示）

### 推荐搭配

- 主线文本翻译：[Tataru Assistant](https://home.gamer.com.tw/artwork.php?sn=5323128)
- UI 标题图片翻译： [karaipsum/Simplified Chinese UI Replacement Mod](https://www.nexusmods.com/finalfantasy14/mods/2048)

## 常见问题

### 可以使用旧版本的 Release 吗？

**不可以！** 这是 **非常不安全** 的行为。

### 如何设置ACT解析插件语言？

与原客户端语言保持一致，例如英文或日文。

### 喊话任务的处理？

国服已有的内容会统一替换为E端文本，国服未更新的任务则以你的客户端原文为准。

### 任务文本有误？

因为任务量极大，我不可能逐个检查每个任务文本。

所以任务文本会直接照搬国服文本，若 7.0 存在技改，或旧主线任务文本更新，或职业任务文本变更（例如机工、武僧），请你自行尝试他 7.0 改成了什么技能，并且将这个情况反馈给我，否则你等多久也不会解决（我不是魔法师，不会平白无故的发现这些“错误”）

### 如何更换字体？

请参考 [Wiki](https://github.com/Souma-Sumire/FFXIVChnTextPatch-Souma/wiki/%E8%87%AA%E5%88%B6%E6%B8%B8%E6%88%8F%E5%AD%97%E4%BD%93) 内容

### 只安装中文字体，但是不汉化游戏内容

覆盖时只覆盖 `000000` 开头的3个文件

### 故意未汉化的文本

为了正常使用 Cactbot，以下文本未被翻译：

- 敌人名称
- 倒计时相关的提示语句
- 封锁区域的提示语句

### 与 Cactbot Radar 的兼容性问题

由于 LogMessage.csv#1350 被汉化，导致 Cactbot Radar 在切线后不会清空之前找到的怪物列表。考虑到使用 Radar 的人较少，不做兼容性修复（也就是不翻译这句话）。

如有 Radar 使用需求的可以将 Radar 链接替换为我修改过源码实现兼容的这个链接：`https://souma.diemoe.net/cactbot/ui/radar/radar.html`

### 与 Dalamud Plugins（卫月插件）的兼容性

若在汉化后，发现个别 Dalamud 插件功能无法使用，可尝试更换汉化方式，也许就会解决。

### 其他问题

- 我并非你的保姆，因此提出过于基础的问题将被无视
- 为了更好的解决你的问题，请先浏览：[提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/main/README-zh_CN.md) / [如何有效地报告 Bug](https://www.chiark.greenend.org.uk/~sgtatham/bugs-cn.html)
- 可以发起 Issues 或加入QQ群 `231937107` 寻求帮助

## 贡献和支持

如果这个项目对你有所帮助，欢迎打赏支持（微信）！

![image](https://github.com/Souma-Sumire/FFXIVChnTextPatch-Souma/assets/33572696/1fec3974-0b6d-43df-9afc-2d760c33f9b5)

若你觉得本汉化项目对你有帮助，欢迎给予 Star 以示鼓励！

[![Star History Chart](https://api.star-history.com/svg?repos=Souma-Sumire/FFXIVChnTextPatch-Souma&type=Timeline)](https://star-history.com/#Souma-Sumire/FFXIVChnTextPatch-Souma&Timeline)
