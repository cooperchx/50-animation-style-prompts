# 50 种 AI 动画美学 · Animation Style Prompts

**简体中文** | [English](README.en.md)

说出动画风格，直接获得提示词；描述用途和视觉偏好，获得风格推荐及提示词。每种风格包含画面参考和中英文通用美学提示词。**来源：网络。**

## 一条命令安装

需要 Node.js / npm 和支持 Agent Skills 的 AI 助手。安装到全局，供工具发现与调用：

```bash
npx skills add cooperchx/50-animation-style-prompts --skill animation-style-prompts -g -y
```

也可以把 [skills/animation-style-prompts](skills/animation-style-prompts) 整个文件夹放入你的助手支持的 skills 目录。

## 直接调用

```text
$animation-style-prompts 给我黏土动画风格的提示词。
$animation-style-prompts 用皮克斯风写一个机器人园丁的动画提示词。
$animation-style-prompts 我要做温暖治愈的儿童短片，推荐风格并给提示词。
$animation-style-prompts 推荐一种复古、单色、纸张质感的动画风格。
```

安装后也可直接用自然语言表达需求。是否自动触发由助手的技能加载机制决定；使用 `$animation-style-prompts` 可以显式调用。

## 使用方式

- **指定风格**：按中文、英文或常见别名匹配，直接输出可复制的中英文提示词和负面词。
- **描述需求**：推荐最多 3 个有区别的风格，简述适合原因，并提供提示词。
- **提供题材**：保留用户给出的内容，将风格模板套入该题材；没有题材时只提供美学模板。

提示词保留材质、线条、比例、色板、光影和动画质感，不绑定参考图中的人物、地点或故事。画面参考用于理解视觉特征；实际生成效果取决于使用的模型和参数。此 Skill 输出文本，不需要 API Key，不自动生成图片或视频。

## 50 种风格与画面参考

点击风格名称查看中英文提示词。

| 编号 | 画面参考 | 风格 |
| --- | --- | --- |
| 01 | <img src="skills/animation-style-prompts/assets/01.jpeg" alt="Paper-Craft Illustration（纸艺插画）" width="200"> | [Paper-Craft Illustration（纸艺插画）](skills/animation-style-prompts/references/styles/01.md) |
| 02 | <img src="skills/animation-style-prompts/assets/02.jpeg" alt="Vietnamese folk-art inspired style（越南民间艺术）" width="200"> | [Vietnamese folk-art inspired style（越南民间艺术）](skills/animation-style-prompts/references/styles/02.md) |
| 03 | <img src="skills/animation-style-prompts/assets/03.jpeg" alt="手绘低多边形风（Painterly Low-Poly Style）" width="200"> | [手绘低多边形风（Painterly Low-Poly Style）](skills/animation-style-prompts/references/styles/03.md) |
| 04 | <img src="skills/animation-style-prompts/assets/04.jpeg" alt="Chinese Mythical Fantasy Animation（中国神话奇幻动画）" width="200"> | [Chinese Mythical Fantasy Animation（中国神话奇幻动画）](skills/animation-style-prompts/references/styles/04.md) |
| 05 | <img src="skills/animation-style-prompts/assets/05.jpeg" alt="Minimalist Cozy Slice-of-Life Illustration（极简温馨日常插画）" width="200"> | [Minimalist Cozy Slice-of-Life Illustration（极简温馨日常插画）](skills/animation-style-prompts/references/styles/05.md) |
| 06 | <img src="skills/animation-style-prompts/assets/06.jpeg" alt="Whimsical storybook illustration（奇趣绘本插画）" width="200"> | [Whimsical storybook illustration（奇趣绘本插画）](skills/animation-style-prompts/references/styles/06.md) |
| 07 | <img src="skills/animation-style-prompts/assets/07.jpeg" alt="Stylized Japanese anime concept art（风格化日式动漫概念艺术）" width="200"> | [Stylized Japanese anime concept art（风格化日式动漫概念艺术）](skills/animation-style-prompts/references/styles/07.md) |
| 08 | <img src="skills/animation-style-prompts/assets/08.jpeg" alt="Retro Editorial Cartoon / Mid-Century Storybook Illustration（复古社论漫画 / 世纪中期绘本）" width="200"> | [Retro Editorial Cartoon / Mid-Century Storybook Illustration（复古社论漫画 / 世纪中期绘本）](skills/animation-style-prompts/references/styles/08.md) |
| 09 | <img src="skills/animation-style-prompts/assets/09.jpeg" alt="水粉手绘绘本动画风（Hand-Painted Gouache Storybook Animation）" width="200"> | [水粉手绘绘本动画风（Hand-Painted Gouache Storybook Animation）](skills/animation-style-prompts/references/styles/09.md) |
| 10 | <img src="skills/animation-style-prompts/assets/10.jpeg" alt="吉卜力动画风格·温暖冒险（Studio Ghibli Animation Style — Warm Adventure）" width="200"> | [吉卜力动画风格·温暖冒险（Studio Ghibli Animation Style — Warm Adventure）](skills/animation-style-prompts/references/styles/10.md) |
| 11 | <img src="skills/animation-style-prompts/assets/11.jpeg" alt="Modern Ukiyo-e Illustration（现代浮世绘）" width="200"> | [Modern Ukiyo-e Illustration（现代浮世绘）](skills/animation-style-prompts/references/styles/11.md) |
| 12 | <img src="skills/animation-style-prompts/assets/12.jpeg" alt="Painterly Cinematic Concept Art（绘画感电影概念艺术）" width="200"> | [Painterly Cinematic Concept Art（绘画感电影概念艺术）](skills/animation-style-prompts/references/styles/12.md) |
| 13 | <img src="skills/animation-style-prompts/assets/13.jpeg" alt="Stylized Arabian Folk Art / Modernist Storybook（阿拉伯民间艺术 / 现代主义绘本）" width="200"> | [Stylized Arabian Folk Art / Modernist Storybook（阿拉伯民间艺术 / 现代主义绘本）](skills/animation-style-prompts/references/styles/13.md) |
| 14 | <img src="skills/animation-style-prompts/assets/14.jpeg" alt="Dark Medieval Fantasy（黑暗中世纪奇幻）" width="200"> | [Dark Medieval Fantasy（黑暗中世纪奇幻）](skills/animation-style-prompts/references/styles/14.md) |
| 15 | <img src="skills/animation-style-prompts/assets/15.jpeg" alt="绘画感 3D 奇幻动画风（Painterly 3D Fantasy Animation Style）" width="200"> | [绘画感 3D 奇幻动画风（Painterly 3D Fantasy Animation Style）](skills/animation-style-prompts/references/styles/15.md) |
| 16 | <img src="skills/animation-style-prompts/assets/16.jpeg" alt="平面印刷插画风（Graphic Print Illustration Style）" width="200"> | [平面印刷插画风（Graphic Print Illustration Style）](skills/animation-style-prompts/references/styles/16.md) |
| 17 | <img src="skills/animation-style-prompts/assets/17.jpeg" alt="Art Nouveau Manga Fusion（新艺术运动 × 漫画融合）" width="200"> | [Art Nouveau Manga Fusion（新艺术运动 × 漫画融合）](skills/animation-style-prompts/references/styles/17.md) |
| 18 | <img src="skills/animation-style-prompts/assets/18.jpeg" alt="Franco-Belgian comics（法比漫画）" width="200"> | [Franco-Belgian comics（法比漫画）](skills/animation-style-prompts/references/styles/18.md) |
| 19 | <img src="skills/animation-style-prompts/assets/19.jpeg" alt="蓝铅笔动画草稿风（Blue-Pencil Animation Sketch Style）" width="200"> | [蓝铅笔动画草稿风（Blue-Pencil Animation Sketch Style）](skills/animation-style-prompts/references/styles/19.md) |
| 20 | <img src="skills/animation-style-prompts/assets/20.jpeg" alt="Gothic Monolith（哥特巨石风）" width="200"> | [Gothic Monolith（哥特巨石风）](skills/animation-style-prompts/references/styles/20.md) |
| 21 | <img src="skills/animation-style-prompts/assets/21.jpeg" alt="Painterly Low-Poly Comic Art（绘画感低多边形漫画）" width="200"> | [Painterly Low-Poly Comic Art（绘画感低多边形漫画）](skills/animation-style-prompts/references/styles/21.md) |
| 22 | <img src="skills/animation-style-prompts/assets/22.jpeg" alt="吉卜力动画风格（Studio Ghibli Animation Style）" width="200"> | [吉卜力动画风格（Studio Ghibli Animation Style）](skills/animation-style-prompts/references/styles/22.md) |
| 23 | <img src="skills/animation-style-prompts/assets/23.jpeg" alt="Handmade Needle-Felt Fantasy（手工羊毛毡奇幻）" width="200"> | [Handmade Needle-Felt Fantasy（手工羊毛毡奇幻）](skills/animation-style-prompts/references/styles/23.md) |
| 24 | <img src="skills/animation-style-prompts/assets/24.jpeg" alt="1990s American superhero cartoon（90 年代美式超英动画）" width="200"> | [1990s American superhero cartoon（90 年代美式超英动画）](skills/animation-style-prompts/references/styles/24.md) |
| 25 | <img src="skills/animation-style-prompts/assets/25.jpeg" alt="朋克科幻漫画风（Punk Sci-Fi Comic Style）" width="200"> | [朋克科幻漫画风（Punk Sci-Fi Comic Style）](skills/animation-style-prompts/references/styles/25.md) |
| 26 | <img src="skills/animation-style-prompts/assets/26.jpeg" alt="墨线水彩奇幻风（Ink-and-Watercolor Fantasy Style）" width="200"> | [墨线水彩奇幻风（Ink-and-Watercolor Fantasy Style）](skills/animation-style-prompts/references/styles/26.md) |
| 27 | <img src="skills/animation-style-prompts/assets/27.jpeg" alt="Architectural Expressionism（建筑表现主义，现代德国表现主义）" width="200"> | [Architectural Expressionism（建筑表现主义，现代德国表现主义）](skills/animation-style-prompts/references/styles/27.md) |
| 28 | <img src="skills/animation-style-prompts/assets/28.jpeg" alt="夸张水粉绘本风（Caricatured Gouache Storybook Style）" width="200"> | [夸张水粉绘本风（Caricatured Gouache Storybook Style）](skills/animation-style-prompts/references/styles/28.md) |
| 29 | <img src="skills/animation-style-prompts/assets/29.jpeg" alt="90s anime style（90 年代动漫）" width="200"> | [90s anime style（90 年代动漫）](skills/animation-style-prompts/references/styles/29.md) |
| 30 | <img src="skills/animation-style-prompts/assets/30.jpeg" alt="Stylized 3D Animated Feature Film（风格化 3D 动画长片）" width="200"> | [Stylized 3D Animated Feature Film（风格化 3D 动画长片）](skills/animation-style-prompts/references/styles/30.md) |
| 31 | <img src="skills/animation-style-prompts/assets/31.jpeg" alt="Digital Oil Painting（数字油画）" width="200"> | [Digital Oil Painting（数字油画）](skills/animation-style-prompts/references/styles/31.md) |
| 32 | <img src="skills/animation-style-prompts/assets/32.jpeg" alt="复古几何插画风（Mid-Century Geometric Illustration Style）" width="200"> | [复古几何插画风（Mid-Century Geometric Illustration Style）](skills/animation-style-prompts/references/styles/32.md) |
| 33 | <img src="skills/animation-style-prompts/assets/33.jpeg" alt="Classic European fairy tale illustration（经典欧洲童话插画）" width="200"> | [Classic European fairy tale illustration（经典欧洲童话插画）](skills/animation-style-prompts/references/styles/33.md) |
| 34 | <img src="skills/animation-style-prompts/assets/34.jpeg" alt="武士杰克式几何动作动画风（Samurai Jack-Inspired Graphic Action Animation）" width="200"> | [武士杰克式几何动作动画风（Samurai Jack-Inspired Graphic Action Animation）](skills/animation-style-prompts/references/styles/34.md) |
| 35 | <img src="skills/animation-style-prompts/assets/35.jpeg" alt="混合媒介：3D 玩具 × 纸艺（3D Vinyl Toy × Papercraft）" width="200"> | [混合媒介：3D 玩具 × 纸艺（3D Vinyl Toy × Papercraft）](skills/animation-style-prompts/references/styles/35.md) |
| 36 | <img src="skills/animation-style-prompts/assets/36.jpeg" alt="Whimsical Watercolor Storybook（奇趣水彩绘本）" width="200"> | [Whimsical Watercolor Storybook（奇趣水彩绘本）](skills/animation-style-prompts/references/styles/36.md) |
| 37 | <img src="skills/animation-style-prompts/assets/37.jpeg" alt="LEGO（乐高积木）" width="200"> | [LEGO（乐高积木）](skills/animation-style-prompts/references/styles/37.md) |
| 38 | <img src="skills/animation-style-prompts/assets/38.jpeg" alt="哑光石雕 3D 绘本风（Matte Stone-Carved 3D Storybook Style）" width="200"> | [哑光石雕 3D 绘本风（Matte Stone-Carved 3D Storybook Style）](skills/animation-style-prompts/references/styles/38.md) |
| 39 | <img src="skills/animation-style-prompts/assets/39.jpeg" alt="北欧民间绘本风（Scandinavian Folk Storybook Style）" width="200"> | [北欧民间绘本风（Scandinavian Folk Storybook Style）](skills/animation-style-prompts/references/styles/39.md) |
| 40 | <img src="skills/animation-style-prompts/assets/40.jpeg" alt="怪趣手绘速写风（Quirky Hand-Drawn Sketch Style）" width="200"> | [怪趣手绘速写风（Quirky Hand-Drawn Sketch Style）](skills/animation-style-prompts/references/styles/40.md) |
| 41 | <img src="skills/animation-style-prompts/assets/41.jpeg" alt="Stylized Military Concept Art（风格化军事概念艺术）" width="200"> | [Stylized Military Concept Art（风格化军事概念艺术）](skills/animation-style-prompts/references/styles/41.md) |
| 42 | <img src="skills/animation-style-prompts/assets/42.jpeg" alt="蒂姆·伯顿式黑白哥特风（Tim Burton-Inspired Gothic Ink Style）" width="200"> | [蒂姆·伯顿式黑白哥特风（Tim Burton-Inspired Gothic Ink Style）](skills/animation-style-prompts/references/styles/42.md) |
| 43 | <img src="skills/animation-style-prompts/assets/43.jpeg" alt="Pixar style（皮克斯风）" width="200"> | [Pixar style（皮克斯风）](skills/animation-style-prompts/references/styles/43.md) |
| 44 | <img src="skills/animation-style-prompts/assets/44.jpeg" alt="Ligne claire（清线派）" width="200"> | [Ligne claire（清线派）](skills/animation-style-prompts/references/styles/44.md) |
| 45 | <img src="skills/animation-style-prompts/assets/45.jpeg" alt="Kids' drawing style（儿童涂鸦画风）" width="200"> | [Kids' drawing style（儿童涂鸦画风）](skills/animation-style-prompts/references/styles/45.md) |
| 46 | <img src="skills/animation-style-prompts/assets/46.jpeg" alt="蓝灰钢笔排线风（Blue-Gray Pen-and-Ink Hatching Style）" width="200"> | [蓝灰钢笔排线风（Blue-Gray Pen-and-Ink Hatching Style）](skills/animation-style-prompts/references/styles/46.md) |
| 47 | <img src="skills/animation-style-prompts/assets/47.jpeg" alt="绘画感动漫风（Painterly Anime Style）" width="200"> | [绘画感动漫风（Painterly Anime Style）](skills/animation-style-prompts/references/styles/47.md) |
| 48 | <img src="skills/animation-style-prompts/assets/48.jpeg" alt="卡通沙龙绘本动画风（Cartoon Saloon Storybook Animation Style）" width="200"> | [卡通沙龙绘本动画风（Cartoon Saloon Storybook Animation Style）](skills/animation-style-prompts/references/styles/48.md) |
| 49 | <img src="skills/animation-style-prompts/assets/49.jpeg" alt="暗调复古电影动漫风（Moody Retro Cinematic Anime Style）" width="200"> | [暗调复古电影动漫风（Moody Retro Cinematic Anime Style）](skills/animation-style-prompts/references/styles/49.md) |
| 50 | <img src="skills/animation-style-prompts/assets/50.jpeg" alt="Claymation Art（黏土动画）" width="200"> | [Claymation Art（黏土动画）](skills/animation-style-prompts/references/styles/50.md) |
