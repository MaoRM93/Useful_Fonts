# Useful Fonts 常用字体

一个常用字体合集，主要给中文用户准备：思源黑体、思源宋体、微软雅黑、宋体、仿宋、楷体、方正系列，外加 Google Sans / Noto Sans 等英文字体。


## 目录结构

```
常用字体/
├── Windows 安装此文件夹/                              # Windows 用
├── macOS、iPadOS、iOS、HarmonyOS、Android 安装此文件夹/  # 苹果 / 鸿蒙 / 安卓用
├── SourceHanSansCN.zip                               # 思源黑体 简体
├── SourceHanSansTW.zip                               # 思源黑体 繁体
├── SourceHanSerifCN.zip                              # 思源宋体 简体
├── SourceHanSerifTW.zip                              # 思源宋体 繁体
├── Noto_Sans.zip
├── Google_Sans.zip
├── Google_Sans_Code.zip
└── Google Sans Text Regular.zip
```

## 怎么下载

### 方法一：整个仓库打包

1. 点页面右上角绿色的 **Code** 按钮；
2. 选 **Download ZIP**；
3. 下载完解压，得到 `Useful_Fonts-main` 文件夹，进去就是 `常用字体`。

> 仓库比较大（700MB 左右），下载慢很正常，耐心等。

### 方法二：只下你需要的某一个字体

1. 点进对应的文件夹（或 zip 文件）；
2. 点文件右侧的下载图标（Download raw file / Download）。

### 方法三： git

```bash
git clone https://github.com/MaoRM93/Useful_Fonts.git
```

## 怎么安装

### Windows

1. 打开 `Windows 安装此文件夹`；
2. 全选 → 右键 → **安装**（也可以双击每个文件 → 点「安装」）；
3. 是 zip 的，先右键解压，再装里面的 ttf / otf。

### macOS

1. 打开 `macOS、iPadOS、iOS、HarmonyOS、Android 安装此文件夹`；
2. 全选 → 双击 → 点 **安装字体**。

### iOS / iPadOS / Android / HarmonyOS

这些系统一般不能直接双击装 ttf，建议用第三方字体管理 App（iFont、AnyFont 之类）导入，或者把字体发给电脑装完再同步。

## 字体清单

| 字体 | 文件 | 用途 / 说明 |
| --- | --- | --- |
| 思源黑体 | `SourceHanSans*` | 无衬线，界面、正文通吃 |
| 思源宋体 | `SourceHanSerif*` | 衬线，适合长文阅读 |
| 微软雅黑 | `msyh*.ttc` | Windows 经典黑体 |
| 宋体 / 黑体 / 楷体 / 仿宋 | `simsun` / `simhei` / `simkai` / `simfang` | Windows 常用中文 |
| 等线 | `Deng*.ttf` | Win10+ 默认界面字体 |
| 方正系列 | 方正仿宋 / 小标宋 / 楷体 / 黑体 等 | 公文排版常用 |
| 阿里巴巴普惠体 | `AlibabaSans-Regular.otf` | 免费可商用 |
| Google Sans / Noto Sans | `*.zip` | 英文字体 |

## FAQ

**下载太慢 / 文件太大？**
仓库整体 700MB 上下，正常。网络差就只下单个文件，或者用 `git clone`（配合断点续传体验更好）。

**装完找不到字体？**
重启一下正在用的软件（Word、浏览器、设计工具），或者注销重登一次。

## License

字体版权归各自原作者所有，本项目只做整理分享。
