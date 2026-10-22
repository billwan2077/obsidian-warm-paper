Warm Paper 1.0.1

受 Claude 视觉语言启发的独立 Obsidian 主题，非官方作品。
暖纸色浅色模式、暖炭色深色模式、陶土橙点缀，适合长时间阅读与写作。
不加载外部字体、脚本或网络资源，也不需要额外插件。

安装
1. 打开你的 Obsidian 仓库目录。
2. 将整个 Warm Paper 文件夹放入仓库的 .obsidian/themes/ 目录。
   最终结构：.obsidian/themes/Warm Paper/theme.css 和 manifest.json。
3. 在 Obsidian「设置 → 外观 → 主题」中选择 Warm Paper。
4. 在外观的基础配色方案中选择浅色、深色或跟随系统。
   若未显示主题，重启 Obsidian。更新 manifest.json 后也应重启。

字体
正文优先使用 Iowan Old Style / Palatino，中文优先使用宋体风格字体；
缺少字体时自动使用系统回退字体，各平台效果会有差异。
界面使用系统无衬线字体，代码使用系统等宽字体。
可在「设置 → 外观」中自定义文本字体、界面字体、等宽字体及字号。
主题不包含 Claude 专有字体，也不保证与其网页逐像素一致。

覆盖范围
阅读视图、实时预览与源代码模式的基础配色和排版；
侧栏、标签页、表单、链接、标签、代码、表格、引用、任务和提示框。
第三方插件使用 Obsidian 标准变量时会继承配色，自绘界面可能需要适配。

验证范围
已检查文件结构、JSON 元数据、CSS 括号配对与主要文本颜色对比度。
尚未在真实 Obsidian 仓库中验证；建议安装后查看笔记、设置、搜索及移动端。

官方主题开发参考
https://docs.obsidian.md/Reference/CSS%20variables/About%20styling
https://github.com/obsidianmd/obsidian-sample-theme

1.0.1 更新
H1–H6 依次使用陶土橙、赭金、苔绿、青绿、灰蓝、柔紫。
浅色和深色分别配色，主要纸面背景上的标题对比度均达到 4.5:1。
通过标准标题颜色变量同时应用于阅读视图和编辑模式。
