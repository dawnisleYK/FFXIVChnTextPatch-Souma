# FFXIVChnTextPatch-Souma

本项目修改自 [FFXIVChnTextPatch-GP](https://github.com/GpointChen/FFXIVChnTextPatch-GP)

## 汉化步骤

### 傻瓜式

  1. 推荐 [开启高分辨率贴图](https://github.com/Souma-Sumire/FFXIVChnTextPatch-Souma/wiki/%E5%BC%80%E5%90%AF%E9%AB%98%E6%B8%85%E8%B4%B4%E5%9B%BE)，否则可能会导致 DirectX 崩溃（未实测）
  1. 下载最新的 [Release](https://github.com/Souma-Sumire/FFXIVChnTextPatch-Souma/releases/)
  1. 将压缩包中的文件覆盖到 `..\FINAL FANTASY XIV\game\sqpack\ffxiv\`

### 手动式

  1. 推荐 [开启高分辨率贴图](https://github.com/Souma-Sumire/FFXIVChnTextPatch-Souma/wiki/%E5%BC%80%E5%90%AF%E9%AB%98%E6%B8%85%E8%B4%B4%E5%9B%BE)，否则可能会导致 DirectX 崩溃（未实测）
  1. 克隆本仓库
  1. 在每次汉化开始前，请保证游戏文件是原版客户端文件。
  1. 运行 `FFXIVChnTextPatchGP.exe`
      - 游戏路径：选择你的游戏安装目录（应包含 boot 和 game 文件夹）
      - 档案语言：选择CSV
      - 原始语言：根据你的客户端选择日文或英文
      - 勾选替换字体和替换文本
      - 点击确认

## 常见问题解答（QA）

### 该版本与 GpointChen 的汉化补丁有什么不同？

| 项目 | FFXIVChnTextPatch-GP | FFXIVChnTextPatch-Souma |
| :---: | :---: | :---: |
| 显示语言 | 繁体中文、繁体机转简体中文 | 原生简体中文 |
| 汉化国服已有的文本 | √ | √ |
| 汉化新版本文本 | × | √ |
| Cactbot 正常运行 | × | √ |

### 使用汉化补丁是否安全？

本程序采用修改客户端文件的方式加载中文资源，使用本程序即表示你已了解此操作违反了官方规定，并确认愿意自行承担由此可能带来的一切后果。

### 可以使用旧版本的傻瓜包吗？

游戏版本更新后，应等待傻瓜包的新版本发布。

使用旧版本的傻瓜包会导致游戏崩溃、数据非法等问题。

### 聊天对话框是否安全？

在发送 `展示道具属性`、`<pos>`、`<flag>` 时，将会发送中文字符。

### 如何设置ACT解析插件？

例如你的客户端语言版本为英文，则你应该将 ACT 解析插件的语言设置为英文。

### 如何更换字体？

请参考 [Wiki](https://github.com/Souma-Sumire/FFXIVChnTextPatch-Souma/wiki/%E8%87%AA%E5%88%B6%E6%B8%B8%E6%88%8F%E5%AD%97%E4%BD%93) 内容。

### 如何汉化 UI 图片的部分？（例如切换场景、接取/完成任务时）

推荐搭配 [karaipsum/Simplified Chinese UI Replacement Mod](https://www.nexusmods.com/finalfantasy14/mods/2048) 为 UI 图片文字 进行汉化。

### 发现部分旧主线未翻译

主线部分的汉化全部为程序自动化执行，会根据每一句话的唯一 ID 去国服解包中寻找对应文本填入，因此若你在跑主线（国服已更新的）中发现部分台词未被翻译，这是由于国际服对这部分的台词 ID 进行了修改，导致无法对应到国服文本。这不是 bug，因此无需汇报。

### 故意未汉化的文本

为了正常使用 Cactbot，以下文本未被翻译：

- 敌人名称
- 倒计时相关的提示语句

### 其他问题

- 我并非你的保姆，因此提出过于愚蠢的问题将被无视
- 为了更好的解决你的问题，请先浏览：[提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/main/README-zh_CN.md) / [如何有效地报告 Bug](https://www.chiark.greenend.org.uk/~sgtatham/bugs-cn.html)
- 发起 Issues 或加入QQ群 `231937107` 寻求帮助

## 捐赠

![image](https://github.com/Souma-Sumire/FFXIVChnTextPatch-Souma/assets/33572696/33b547e0-f8d4-41ba-9d76-a813a8053daa)
