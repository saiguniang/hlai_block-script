## 📜 <img src="svg_files/tone_t.svg" style="height: 1.1em; vertical-align: middle;"><img src="svg_files/tone_un.svg" style="height: 1.1em; vertical-align: middle;"><img src="svg_files/tone_hl.svg" style="height: 1.1em; vertical-align: middle;"><img src="svg_files/tone_ai.svg" style="height: 1.1em; vertical-align: middle;"> 方块黎文（Hlai Block-Script）
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

尊敬的黎族同胞、语言学研究者及开源社区的朋友们，您好！欢迎来到本存储库！

### 📖 历史溯源：黎族话与《黎文方案》
首先，要向您说明：黎族话属汉藏语系壮侗语族黎语支。过去黎族没有本民族文字，均使用汉字。

为了弥补这一历史遗憾，1956 年 6 月，在党中央国务院的关怀下，中国社会科学院少数民族语言研究所、会同中央民族学院（现中央民族大学）、中南民族学院、广东省海南特别行政区民族事务委员会等单位，对海南 9 个市县的黎族 170 个点的语言进行了调查。

根据语音、词汇和语法的特点，专家将黎族话划分为哈、杞、润、美孚、赛五个方言。由于哈方言使用人口最多，而语言只有 3 个调值，语言易学，故最终以哈方言为基础方言，以乐东黎族自治县的抱由镇保定村（属哈方言罗活土语）的语音为标准音，设计了以拉丁字母为基础的《黎文方案》（草案）。

该方案于 1957 年 2 月，在原广东省海南黎族苗族自治州首府通什市（现五指山市）通过。在准确表达黎族话语音的前提下，字母的读音尽可能接近汉语拼音方案，为黎族文化的传承做出了不可磨灭的贡献。

### ✨ 本项目的诞生与愿景：回归东方美学
《黎文方案》的拉丁化拼写虽然极其科学，但在数字时代与现代汉字混排时，拉丁字母（A-Z）在视觉上容易产生文化疏离感与排版割裂感。

为了探索民族文字在「汉字文化圈」中的视觉边界，本项目诞生了。

本项目并非要替代官方拼音，而是为黎族话提供一套基于中国古典美学的「视觉外衣」：

我们考察了中国先秦时期的鸟虫篆与秦代小篆的线条特征，结合单音节方块字的结构逻辑，将黎族话的 33 个声母、99 个韵母及 5 个声调符号重新解构，设计出了这套「方块黎文」（Hlai Block-Script）。

它不仅保留了拼音系统的高效与科学，更让黎族话在与现代汉字混排时，能够实现字号等宽、基线对齐、气韵贯通，展现出中华民族「多元一体」的排版尊严。

本项目为民间的开源排版实验与视觉艺术创作，旨在为黎族话提供一种补充性能的古典美学表达方案。官方使用请以 1957 年《黎文方案》的拉丁化标准为准。

### 🛠️ 如何使用这套文字？
本存储库提供了极高的自由度，无论您是普通文化爱好者还是硬核开发者，都可以通过以下 4 种方式轻松使用「方块黎文」：

#### 1．网页与博客排版：Markdown／HTML 嵌入
如果您想在自己的 GitHub README、个人博客、或任何支持 Markdown／HTML 的地方排版这套文字，您可以直接通过 URL 调用本仓库的 SVG 图像。

**排版秘籍**：为确保字符等宽且与汉字完美对齐，请务必为`<img>`标签添加`style="height: 1.1em; vertical-align: middle;"`。

**代码示例**（以书写 ghoux 为例）：
```
<!-- 黎语：ghoux (我) -->
<img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_gh.svg" style="height: 1.1em; vertical-align: middle;" alt="gh"><img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_ou.svg" style="height: 1.1em; vertical-align: middle;" alt="ou"><img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_-x.svg" style="height: 1.1em; vertical-align: middle;" alt="-x">
```
👇 **实际渲染效果**：

<img src="svg_files/tone_gh.svg" style="height: 1.1em; vertical-align: middle;" alt="gh"><img src="svg_files/tone_ou.svg" style="height: 1.1em; vertical-align: middle;" alt="ou"><img src="svg_files/tone_-x.svg" style="height: 1.1em; vertical-align: middle;" alt="-x">

#### 2．跨语言排版：黎汉混写
作为深受汉字文化圈影响的语言，现代黎族话中包含了大量现代汉语借词。本系统极其推崇「无缝混排」的书写哲学，其基本逻辑异曲同工：
* **汉语借词**（如「三亚」「警察」「电脑」）：直接使用现代汉字，充当视觉锚点与核心表意符号。
* **黎族话固有词**（如「我」「去」「吃」）：使用方块黎文，充当表音与语法连接。
* **视觉法则**：汉字与方块黎文之间无需加空格，这种交替自然形成了完美的阅读节奏与断句红绿灯。

【绝美混排代码示例】

**假设我们要书写**：“我 (ghoux) 去过 (daas) 三亚”。
```
<!-- 黎族固有词：我 (ghoux) -->
<img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_gh.svg" style="height: 1.1em; vertical-align: middle;" alt="gh">
<img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_ou.svg" style="height: 1.1em; vertical-align: middle;" alt="ou">
<img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_-x.svg" style="height: 1.1em; vertical-align: middle;" alt="-x">

<!-- 黎族固有词：去/过 (daas) -->
<img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_d.svg" style="height: 1.1em; vertical-align: middle;" alt="d">
<img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_ae.svg" style="height: 1.1em; vertical-align: middle;" alt="ae">
<img src="https://raw.githubusercontent.com/hlai-li/hlai_block-script/refs/heads/main/svg_files/tone_-s.svg" style="height: 1.1em; vertical-align: middle;" alt="-s">

<!-- 汉语借词：三亚（无需空格，直接紧贴） -->
<span style="font-size: 1.1em; vertical-align: middle; font-family: sans-serif;">三亚</span>
```
👇 **实际渲染效果**：

<img src="svg_files/tone_gh.svg" style="height: 1.1em; vertical-align: middle;" alt="gh"><img src="svg_files/tone_ou.svg" style="height: 1.1em; vertical-align: middle;" alt="ou"><img src="svg_files/tone_-x.svg" style="height: 1.1em; vertical-align: middle;" alt="-x"><img src="svg_files/tone_d.svg" style="height: 1.1em; vertical-align: middle;" alt="d"><img src="svg_files/tone_ae.svg" style="height: 1.1em; vertical-align: middle;" alt="ae"><img src="svg_files/tone_-s.svg" style="height: 1.1em; vertical-align: middle;" alt="-s"><span style="font-size: 1.1em; vertical-align: middle; font-family: sans-serif;">三亚</span>

#### 3．视觉与文创设计：直接使用 SVG 零件
如果您是平面设计师、UI/UX 设计师或文创制作者（如绘制插画、设计潮牌海报等）：
* 1、下载本仓库的 svg_files 文件夹。
* 2、将这 123 个 .svg 文件导入至 Adobe Illustrator、Figma、Photoshop 或任何矢量设计软件中。
* 3、这些文件是 100% 纯矢量路径（无背景），支持无限放大、随意修改颜色与描边。
* 4、像拼积木一样，将它们排列组合即可生成具有中国风的视觉图腾。

#### 4．终极开发：封装为 .ttf 或 .otf 字库
如果您有意将这套文字系统，制作为可在操作系统全局使用的字体文件：
* 1、您可以使用 FontForge、Glyphs 等工具。
* 2、将本库的 123 个 SVG 文件批量导入。
* 3、分配编码：建议将其映射至 Unicode 的 PUA（私用区）编码，以防止与标准拉丁字母冲突。
* 4、设置连字：若您希望重现「方块堆叠」效果，可编写 OpenType 规则（例如：sub b h by bh_glyph;），从而实现键盘纯输入，即可自动合体的顶级效果。

#### 5．身份认同与人名规范
在现实社会与数字网络中，本系统强烈推荐参照「汉字文化圈」的双轨制姓名美学，以彰显黎族同胞独特的民族身份认同。

在官方证件及正式场合，请使用规范汉字（如：符樱），但在网络昵称、个人主页或签名中，建议添加你的黎族话昵称（如：[c][ai]）。这种「汉字+方块黎文」的组合极具视觉冲击力与私密性能。

#### 6．📜 关于借词排版的倡议
语言是活态的历史，而不是封闭的博物馆。

在长达千年的历史交融中，现代汉语（及海南闽语）早已成为黎族同胞日常表达不可或缺的一部分。因此，本「方块黎文」引擎强烈倡导「自然混排法则」：
* 1、**拒绝生造词**：对于黎语原生词库中不存在的现代事物（如「科学」「电脑」「警察」），**请直接使用现代规范汉字**。
* 2、**拒绝刻意外化**：不提倡为了追求「纯粹」而刻意生造冗长的黎语复合词，或刻意使用西方外来语替代已有的汉语借词。

让黎族的原生语法和古老词根，以绝美的「方块黎文」呈现；让现代文明的共有概念，以「汉字」呈现。这并非妥协，而是 100% 诚实地还原了，现代双语黎族同胞脑海中最真实的思维状态。

**真正的文化自信，是不畏惧融合，而是用自己的排版规则，去包容世界**。

### 📦 存储库内容
本仓库完全开源，包含以下核心元素：
* svg_files/：包含123个手工绘制的 SVG 矢量图形零件。它们是这套文字体系的基础，涵盖了黎族话所有的合法声韵调组合。

### 🛠️ 参与贡献
语言的生命力在于不断地使用与演化。本项目目前为 V1.0 版本，如果您是：
* 黎族文化学者：发现任何拼写规则或音素切分的遗漏；
* 前端／字体工程师：有意将本 SVG 库打包为标准的 .ttf／.otf 字体文件；
* UI／视觉设计师：对古风线条的曲率和对齐方式有更好的优化建议。

欢迎您将宝贵的意见留言在本项目的 Pull Requests 中。在此向每一位为中华民族文化保护贡献力量的朋友，致以最诚挚的谢意！
