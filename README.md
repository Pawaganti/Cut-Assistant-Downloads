# Cut Assistant｜下载与使用

Cut Assistant 是适用于 Windows 和 DaVinci Resolve Studio 的剪辑辅助插件。它将常用的时间线、片段、变换、变速、显示与颜色操作集中在可调整的面板中。

**此下载页当前提供 v1.0.32。**运行需要 DaVinci Resolve Studio 21.1 或更新版本。

![Cut Assistant 1.0.32 界面示意](docs/panel-1.0.32.png)

图片展示的是模拟状态下的面板布局。

## 下载与安装

请从[版本下载页](https://github.com/Pawaganti/Cut-Assistant-Downloads/releases/latest)选择一种方式：

| 方式 | 文件 | 安装步骤 |
| --- | --- | --- |
| 脚本安装 | `Cut-Assistant-1.0.32-Installer.zip` | 解压后运行 `安装.cmd`。 |
| 复制使用 | `Cut-Assistant-1.0.32-Portable.zip` | 解压后将整个 `Fusion` 文件夹复制到达芬奇的 `Support` 目录。 |

**注意：v1.0.32 的两个附件均为 ZIP；`Installer.zip` 使用安装脚本，不是 Windows 安装向导。**请勿同时使用两种方式。具体路径和首次使用步骤见[安装说明](docs/安装说明.md)。

安装后，在达芬奇的 **工作区 → 脚本 → Cut Assistant** 打开。下载页提供 `SHA256SUMS.txt`，可用于核对文件完整性。下载包不包含个人设置或工程素材。

## 使用提示

助手打开时读取一次当前状态，之后不会在后台持续轮询。如需立即核对面板数值与高亮，可在主面板空白处右键选择“刷新当前状态”。

随包提供的 PDF 手册中，个别自动刷新说明尚未同步；相关操作以本页的[安装说明](docs/安装说明.md)为准。
