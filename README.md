# 处理图像序列教程 HTML 网页版

## [点此打开](https://iavoe.github.io/img-sequence-enc-web-tutorial/HTML/index.html)

- 建立于[x264-x265-QAAC-ffprobe-Ultimatetutorial](https://github.com/iAvoe/x264-x265-QAAC-ffprobe-Ultimatetutorial)的 x264 教程 2024.45 版，并大幅改进了内容

### HTML 版特点

- [x] 基于 docx 版教程的手工移植，考量了每一处段落的实现
- [x] 支持如 [Dark Reader](https://darkreader.org) 的暗黑模式浏览器插件
- [x] 响应式网站设计 + 点击图片的排版变更系统：点击图片轮询三种大小和对应段落的排版格式（左右环绕↔上下环绕），调整浏览器窗口轮询横↔竖式排版
- [x] HTML 版教程会因显示方案变更而区别于 docx，但仍然会为减少维护难度而延用英文/半角标点符号。
- [x] 解决了诸多文书规范性和阅读排版的问题，包括一些无法简单修复（如标题 1 被大版块用完）的历史遗留问题
- [x] 解决了难以通过 git 的变更跟踪系统检查更改内容的版本管理问题，尤其影响协作检查和撰写
- [x] 大幅改良了内容，包括多平台自动排版适配，JavaScript 排版切换互动，CSS 响应式设计，语法去简练化（不再需要通过字数限制控制排版），错误纠正
- [x] 100% LaTex 公式（使用 MathJax 实现，支持复制为 MathML 以及 LaTex，见下）
- [x] 高速 CI/CD。摆脱传统 docx-PDF 版教程的网盘和 QQ 群等间接发布，间接下载，每次更新要重复下载的困难
- [x] 利用 Github 透明化的代码区别检查

### 字体系统

分为正文黑体，注解圆体和代码段字体共三套字体集。

- 正文黑体为首选[煮豆黑体 Zhudou Sans](https://github.com/Buernia/Zhudou-Sans)（中文）附件  
  - 辅以系统 Sans Serif（英文
- 注解圆体为 Windows 的幼圆（中英文）附件
- 代码段的字体为传统代码段的 SFMono-Regular，Menlo，Monaco，Consolas（英文）  
辅以[狮尾圆体 Light](https://github.com/max32002/swei-gothic/blob/master)（中文）附件
- 公式段的字体为 [KaTeX Math Regular](https://github.com/KaTeX/katex-fonts/blob/master)（英文）附件（适配安卓）  
  - 辅以 Cochin，Georgia，Times，Times New Roman，serif

### 内容范围

图像序列的科普，ffmpeg Image2，x264 直接编码为视频的用例，ffmpeg pipe 复杂文件名序列的用例，手动指定文件名顺序的用例，以及将视频转换为图像序列的用例

### 繁体中文支持

本教程由简体中文编写，设计上通过自行安装浏览器插件转换为繁体。转换效果不理想则请截图，并发送到本教程 Github 仓库中的 Issues，或 QQ 群里。

### 暗黑模式支持

设计上通过将图片的白色背景改为透明，并给剩下的内容添加白色描边实现。目前已验证了 [Dark Reader](https://darkreader.org) 的效果。转换效果不理想时请截图发送到本教程 Github 仓库中的 Issues，或 QQ 群里。

### 打印机支持

打开教程后，在标题栏中可以将当前内容切换到打印排版。并切换回一般排版。转换效果不理想时请截图发送到本教程 Github 仓库中的 Issues，或 QQ 群里。

### 打赏

<p align="center"><img src="bmc_qr.png"><br><img src="pp_tip_qr.png"></p>

——[Buy me a coffee 链接](https://buymeacoffee.com/iavoe)

——[PayPal 链接](https://www.paypal.com/qrcodes/managed/3e3e8b7f-27ed-4edc-a0fa-1b469e854a3c?utm_source=consapp)

<p align="center"><font size=1>——新纪录！这玩意现在年收入 20 人民币</font></p>

-----

联系方式：[Github：iAvoe]("https://github.com/iAvoe/iAvoe)，[QQ 群]("https://jq.qq.com/?_wv=1027&k=5YJFXyf")  
欢迎提交 pull-request 和 issues 指正