# Warm Paper

受 Claude 视觉风格启发的独立 Obsidian 主题，非官方作品。当前版本：**1.0.1**。

暖米色浅色模式与暖炭色深色模式，搭配陶土橙点缀、衬线正文和系统界面字体。无需插件，不加载在线字体或其他网络资源。

## 标题颜色

| 等级 | 颜色 |
| --- | --- |
| H1 | 陶土橙 |
| H2 | 赭金 |
| H3 | 苔绿 |
| H4 | 青绿 |
| H5 | 灰蓝 |
| H6 | 柔紫 |

浅色和深色模式分别配色，标题在主题主背景上的对比度均超过 4.5:1。

## 安装

1. 下载本仓库中的 `theme.css` 和 `manifest.json`。
2. 在 Obsidian 仓库中创建 `.obsidian/themes/Warm Paper/`，将两个文件放进去。
3. 打开「设置 → 外观 → 主题」，选择 **Warm Paper**。若未显示，重启 Obsidian。
4. 在外观设置中选择浅色、深色或跟随系统。

macOS Finder 中按 **Command + Shift + .** 可显示 `.obsidian` 隐藏文件夹。

## 字体与兼容性

正文优先使用本地 Iowan Old Style、Palatino 和宋体风格字体；界面和代码分别使用系统无衬线字体与等宽字体。字体可在 Obsidian 外观设置中覆盖，实际显示取决于设备已安装的字体。本主题不附带 Claude 专有字体。

主题使用 Obsidian 标准 CSS 变量，覆盖编辑与阅读视图的基础配色、标题、侧栏、标签页、代码、表格、引用和提示框。第三方插件自绘界面可能需要额外适配。

已检查元数据、CSS 括号配对、主要文本与标题对比度及安装包结构；尚未在真实 Obsidian 仓库或移动端中实测。

## 参考

[Obsidian 官方样式变量文档](https://docs.obsidian.md/Reference/CSS%20variables/About%20styling)
