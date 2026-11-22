---
layout: default
title: "Horizon Summary: 2026-11-22 (ZH)"
date: 2026-11-22
lang: zh
---

> 从 23 条内容中筛选出 9 条重要资讯。

---

**科技新闻**
1. [黎曼猜想证明通过 Lean 验证](#item-tech-news-1) ⭐️ 10.0/10
2. [Rust GUI 框架开发的架构经验与反思](#item-tech-news-2) ⭐️ 8.0/10
3. [特斯拉开始面向海外推送 FSD v15](#item-tech-news-3) ⭐️ 7.0/10
4. [显示器内置 USB 扩展坞导致下载速度锐减的故障排查](#item-tech-news-4) ⭐️ 6.0/10
5. [国家数据局：将健全词元计量计费与质量测评标准](#item-tech-news-5) ⭐️ 6.0/10
6. [Google Gemini 将支持单独关闭模型训练数据留存](#item-tech-news-6) ⭐️ 6.0/10
7. [英媒披露英伟达芯片走私网络：柬埔寨太子集团涉案人员被指参与对华走私](#item-tech-news-7) ⭐️ 6.0/10

**财经新闻**
1. [中国要求美国撤销电话号段接入限制](#item-finance-news-1) ⭐️ 7.0/10
2. [前三季度国内手机市场：华为份额居首](#item-finance-news-2) ⭐️ 6.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [黎曼猜想证明通过 Lean 验证](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/) ⭐️ 10.0/10

2026 年 11 月 20 日，Levent Alpöge 发布了黎曼猜想的 Lean 形式化证明，代码库规模约为 1700 万行。次日，Lean FRO 与 Mathlib Initiative 联合声明确认该命题与证明正确，社区验证其与 Mathlib 的 RiemannHypothesis 一致且代码可无错编译，多个独立证明检查器也证实了其有效性。

telegram · zaihuapd · 11月21日 16:48

**「背景」** Lean 是一个交互式定理证明器，常用于将复杂的数学定理转化为计算机可严格检验的形式化代码，以确保其逻辑严密性。

**「影响」** 这一进展标志着自动定理证明技术在处理极大规模现代数学前沿问题上取得重大突破，对数学基础与形式化研究具有深远影响。

**「社区讨论」** 评论指出，由于该证明经过了多种不同语言和实现的独立检查器验证，其因内核漏洞导致错误的概率极低；同时，讨论也提及了 AI 模型在其中发挥的大规模数学形式化辅助作用以及人类专家的核心贡献。

**标签**: `#mathematics`, `#formal verification`, `#lean`, `#riemann hypothesis`

---

<a id="item-tech-news-2"></a>
### [Rust GUI 框架开发的架构经验与反思](https://linebender.org/blog/next-100-guis/) ⭐️ 8.0/10

Rust 开发者 Raph Levien 在文章中回顾了构建多个 Rust GUI 框架的设计挑战与架构教训。文章探讨了在 Rust 生态中开发图形界面时所面临的底层技术和工程复杂度。

hackernews · raphlinus · 11月21日 21:17 · [社区讨论](https://news.ycombinator.com/item?id=50593737)

**「背景」** 本文是作者在 4.5 年前发表的《Advice for the next dozen Rust GUIs》一文的后续，期间 Rust GUI 生态中涌现出了大约 20 个新工具包。

**「社区讨论」** 评论者对文章未提及 Slint 框架感到意外，并讨论了虚幻引擎 Slate 架构对 Rust 的借鉴意义。此外，有开发者提到了新出现的 Native Shell 库，另有人分享了自己用 Rust 开发自定义 GUI 时在文本选择和光标定位等细节上进展缓慢的切身体会。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://linebender.org/blog/next-100-guis/">Advice for the next 100 Rust GUIs - Linebender</a></li>

</ul>
</details>

**标签**: `#Rust`, `#GUI`, `#Software Architecture`, `#Open Source`

---

<a id="item-tech-news-3"></a>
### [特斯拉开始面向海外推送 FSD v15](https://x.com/Tesla/status/2124222447855743019) ⭐️ 7.0/10

特斯拉已开始在海外推送 FSD v15 更新。新版本宣称将安全关键场景处理能力提升至 25 倍，引入了可在车机屏幕叠加摄像头画面与行驶规划的“Tesla Reality View”可视化界面，并支持全屏、地图、分屏及安静模式。此外，更新优化了导航信息叠加、转向灯提示音、复杂路况及恶劣天气下的驾驶体验。

telegram · zaihuapd · 11月22日 00:03

**「背景信息」** 特斯拉的 FSD（完全自动驾驶）系统此前经历了多个版本的迭代，持续针对城市及高速场景的神经网络架构、可视化界面以及驾乘舒适度进行更新。

**「影响与注意」** 已升级到 FSD v15 的海外用户将获得更直观的可视化界面和改进的导航与控速体验，但在实际道路行驶中仍需保持对车辆的监控。

**标签**: `#artificial intelligence`, `#autonomous driving`, `#tesla`, `#machine learning`, `#computer systems`

---

<a id="item-tech-news-4"></a>
### [显示器内置 USB 扩展坞导致下载速度锐减的故障排查](https://blog.tymscar.com/posts/studiodisplayethernet/) ⭐️ 6.0/10

一名开发者通过排查发现，经由显示器内置的 USB/以太网集线器路由网络连接会导致下载速度下降 75%。深入分析表明，由于走显示器集线器引入了额外的延迟，导致笔记本电脑无法及时确认数据包，进而引起网卡缓冲区填满并丢包。最终，更换对确认频率要求较低的其他适配器成功解决了该问题。

hackernews · soheilpro · 11月21日 10:36 · [社区讨论](https://news.ycombinator.com/item?id=50587875)

**「背景」** 在现代高带宽网络和 USB 外设的组合中，集成在显示器或扩展坞中的 USB 网卡可能由于额外的硬件延迟或背板限制，在处理高吞吐量 TCP 连接时引发确认延迟与丢包问题。

**「影响」** 使用集成以太网功能的显示器或部分雷电扩展坞的用户，若遭遇难以排查的网络吞吐量下降问题，可考虑排查 USB 拓扑及硬件引入的额外延迟对 TCP 确认机制的影响。

**「社区讨论」** 评论指出，该问题的本质在于硬件集线器带来的额外延迟影响了 TCP 数据包的确认频率，进而引发缓冲区丢包。多位用户表示曾在类似的外设或扩展坞组合中遇到过难以捉摸的同类故障。

**标签**: `#networking`, `#hardware`, `#troubleshooting`, `#usb`

---

<a id="item-tech-news-5"></a>
### [国家数据局：将健全词元计量计费与质量测评标准](https://www.cls.cn/detail/2540805) ⭐️ 6.0/10

国家数据局局长刘烈宏在 2026 世界计算大会上宣布，我国将进一步拓展词元服务应用场景，并健全词元计量计费、质量测评等标准规范。此举旨在规范词元生产服务，避免低质量重复建设，推动算力、模型和数据间的价值互联。

telegram · zaihuapd · 11月21日 10:19

**「背景」** 词元（Token）作为大语言模型处理文本的基本单元，正逐渐成为连接算力、模型与数据资源的核心计量单位和数智经济的价值锚点。

**标签**: `#artificial intelligence`, `#data governance`, `#standards`, `#ai economics`

---

<a id="item-tech-news-6"></a>
### [Google Gemini 将支持单独关闭模型训练数据留存](https://blog.google/innovation-and-ai/products/gemini-app/updated-controls/) ⭐️ 6.0/10

Google 宣布将在未来几周内更新 Gemini 应用的设置，将原有的“保留活动记录”拆分为两项独立控制项。新设置分别用于控制历史记录保存时长以及决定对话内容（包含文字与附件）是否用于训练生成式 AI 模型。变更后，用户可以在保留历史记录的同时，自主选择关闭模型训练授权。

telegram · zaihuapd · 11月22日 01:24

**「背景」** 此前，主流生成式 AI 助手通常将聊天历史记录的保存与用于模型训练的数据收集绑定在一起，用户若想保留历史记录就必须同意贡献训练数据。这种绑定方式引发了用户对隐私保护的持续关注。

**「影响」** 注重隐私的用户在更新后可以开启历史记录功能，同时避免其对话内容和附件被用于后续的生成式 AI 模型训练。

**标签**: `#Google Gemini`, `#Artificial Intelligence`, `#Privacy`, `#Machine Learning`

---

<a id="item-tech-news-7"></a>
### [英媒披露英伟达芯片走私网络：柬埔寨太子集团涉案人员被指参与对华走私](https://www.ft.com/content/f3ad8a81-3890-4a8a-8853-ff0a94b08ba9?syn-25a6b1a6=1) ⭐️ 6.0/10

英国《金融时报》报道称，被指为柬埔寨太子集团“二号人物”的胡小伟涉嫌参与将受限制的英伟达芯片走私至中国。据贸易数据显示，2024 年 12 月至 2025 年 12 月期间，Megaspeed 马来西亚子公司进口了申报价值约 46 亿美元的货物，部分芯片据称流入中国黑市。该网络被指利用空壳公司、私人飞机及地下融资渠道进行走私，而太子集团已对此予以否认，称相关指控缺乏事实依据。

telegram · zaihuapd · 11月22日 04:34

**「背景」** 美国政府对向中国出口高端人工智能芯片实施了严格的出口管制，旨在限制中国获取尖端计算硬件。这些贸易限制促使多方通过海外转运和空壳公司等灰色手段试图规避禁令。

**「影响」** 此事件凸显了现有芯片出口管制在跨境供应链和东南亚中转环节面临的合规与执法漏洞，可能促使监管机构进一步收紧对相关地区硬件贸易和物流的审查。

**标签**: `#Nvidia`, `#Hardware`, `#Supply Chain`, `#Geopolitics`, `#Artificial Intelligence`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [中国要求美国撤销电话号段接入限制](https://www.bloomberg.com/news/articles/2026-11-22/china-objects-to-us-curbs-on-telecoms-access-to-phone-numbers) ⭐️ 7.0/10

中国商务部于 11 月 22 日敦促美国撤销一项禁止中国三大电信运营商直接获取美国电话号码的措施，称其违反公平竞争原则并泛化国家安全概念。

telegram · zaihuapd · 11月22日 06:44

**「背景」** 美国联邦通信委员会（FCC）于 11 月 19 日投票通过新规，收紧互联网语音服务商的安全要求以阻止特定实体接入美国网络。

**「影响」** 中国商务部表示，相关举措正推动两国在电信与通信领域走向脱钩，中方将采取必要措施维护自身权益。

**标签**: `#Telecommunications`, `#US-China Relations`, `#Regulatory Policy`, `#National Security`

---

<a id="item-finance-news-2"></a>
### [前三季度国内手机市场：华为份额居首](https://weibo.com/1642634100/RsyNmsLgF) ⭐️ 6.0/10

根据博主 @RD 观测发布的数据，2026 年前三季度国内智能手机市场销量整体同比下跌 9.2%，其中华为以 20.25% 的实际份额居于首位，较去年同期提升 3.92 个百分点。

telegram · zaihuapd · 11月22日 08:22

**「背景」** 在此期间国内手机市场呈现头部集中趋势，仅华为与苹果两家头部品牌的市场份额实现同比正增长，其他主要品牌及中小品牌的份额均出现下滑。

**标签**: `#smartphone market`, `#Huawei`, `#Apple`, `#market share`, `#consumer electronics`

---