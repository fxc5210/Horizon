---
layout: default
title: "Horizon Summary: 2026-11-23 (ZH)"
date: 2026-11-23
lang: zh
---

> 从 27 条内容中筛选出 13 条重要资讯。

---

**科技新闻**
1. [OpenAI 探讨模型困惑度与智能的关系](#item-tech-news-1) ⭐️ 8.0/10
2. [硅谷的现状与机制设计重构](#item-tech-news-2) ⭐️ 7.0/10
3. [谷歌搭建名为 Mirror Dimension 的模拟互联网用于测试 Chrome AI 代理](#item-tech-news-3) ⭐️ 7.0/10
4. [Alessandro Masullo 数学文稿的 Lean 形式化进展及社区讨论](#item-tech-news-4) ⭐️ 6.0/10
5. [Phison 发布面向轨道数据中心的 Pascari Space SSD 系列](#item-tech-news-5) ⭐️ 6.0/10
6. [摩尔线程产品经理透露下一代庐山 GPU 拟配 64 GB 显存](#item-tech-news-6) ⭐️ 6.0/10
7. [Windows Server 2028 默认移除 32 位应用支持](#item-tech-news-7) ⭐️ 6.0/10

**科技博客**
1. [在高度不确定性中摸索前行](#item-tech-blog-1) ⭐️ 7.0/10

**财经新闻**
1. [美股科技股大跌，亚洲多地出台股市稳定措施](#item-finance-news-1) ⭐️ 8.0/10
2. [超级厄尔尼诺海温破纪录与粮食援助危机](#item-finance-news-2) ⭐️ 8.0/10
3. [中国要求美国撤销电话号段接入限制](#item-finance-news-3) ⭐️ 7.0/10
4. [蚂蚁集团领投中国具身智能公司 1 亿美元融资](#item-finance-news-4) ⭐️ 7.0/10
5. [前三季度国内手机市场份额发布](#item-finance-news-5) ⭐️ 6.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [OpenAI 探讨模型困惑度与智能的关系](https://openai.com/index/perplexity-and-intelligence/) ⭐️ 8.0/10

OpenAI 发布了一篇探讨模型困惑度与智能之间关系的文章，分析了预测和压缩率如何与机器学习的进展相关联。该文引发了技术社区关于交叉熵损失、基础模型评估以及预测能力作为智能衡量标准的讨论。

hackernews · acossta · 11月22日 17:06 · [社区讨论](https://news.ycombinator.com/item?id=50601525)

**「困惑度与预测」** 困惑度用于衡量模型对序列中下一个词的平均预测能力，数值越低代表预测效果越好。

**「社区讨论」** 社区讨论指出，困惑度本质上衡量模型预测下一个 Token 时的惊讶程度，最佳情况为 1，最差情况等于词表大小。评论者认为，通过预测率来捕捉世界模型并衡量进展的理念既简单又直观，同时有评论提到微软等机构也开始在公共保留评估集上分享其基础模型的对数困惑度进展。

<details><summary>参考链接</summary>
<ul>
<li>Perplexity and Intelligence | OpenAI</li>

</ul>
</details>

**标签**: `#artificial intelligence`, `#machine learning`, `#language models`, `#research`

---

<a id="item-tech-news-2"></a>
### [硅谷的现状与机制设计重构](https://www.oreilly.com/radar/what-happened-to-silicon-valley/) ⭐️ 7.0/10

一篇发表于 O&\#x27;Reilly Radar 的文章探讨了硅谷的演变与现状，分析了资本主义作为优化引擎的目标。文章认为，应当将机制设计转向以人类福祉为核心，而非纯粹追求股东利益。

hackernews · greenyouse · 11月22日 19:20 · [社区讨论](https://news.ycombinator.com/item?id=50602947)

**「背景」** 蒂姆·奥赖利（Tim O&\#x27;Reilly）结合其在硅谷四十多年的经历，撰文探讨了硅谷从早期的客户中心创新与集体智慧愿景，逐步转向由股东资本主义驱动的价值提取模式的演变过程。

**「社区讨论」** 评论者赞同文章关于重新审视游戏规则和机制设计的核心观点，并指出应当思考人类集体优化的方向。另有讨论认为，零利率政策（ZIRP）时期刺激了科技公司的过度膨胀，而当前的利率环境和人工智能浪潮则促使企业重新评估其核心业务与支出。

<details><summary>参考链接</summary>
<ul>
<li>What Happened to Silicon Valley? - O&#x27;Reilly</li>
<li>What happened to Silicon Valley, and can AI help it return to creating more value than it ... - Facebook</li>

</ul>
</details>

**标签**: `#Silicon Valley`, `#Tech Industry`, `#Mechanism Design`, `#Capitalism`, `#Analysis`

---

<a id="item-tech-news-3"></a>
### [谷歌搭建名为 Mirror Dimension 的模拟互联网用于测试 Chrome AI 代理](https://www.landian.news/archives/128701.html) ⭐️ 7.0/10

谷歌为 Chrome 的 AI 代理搭建了一个名为 Mirror Dimension 的模拟互联网环境，用于在隔离状态下测试其浏览、登录、加购和完成任务等操作。该环境包含数千个模拟网站，每名工程师可进行单独隔离测试，每天运行超过 1000 个测试案例，重点防御恶意网页引发的提示词注入等网络攻击。

telegram · zaihuapd · 11月23日 01:30

**「背景」** 随着浏览器自动化和 AI 代理技术的普及，AI 代理在访问不受信任的网页时容易受到恶意提示词注入和自动化攻击的威胁。为了在不危及用户安全和数据隐私的前提下评估这些风险，行业内开始探索构建沙盒或隔离的模拟环境来进行安全测试。

**「影响」** 该隔离测试环境能够帮助谷歌在 Chrome AI 代理正式面向公众推出前，更有效地暴露并修复潜在的安全漏洞与提示词注入风险。

**标签**: `#Artificial Intelligence`, `#Cybersecurity`, `#Browser Automation`, `#Google Chrome`

---

<a id="item-tech-news-4"></a>
### [Alessandro Masullo 数学文稿的 Lean 形式化进展及社区讨论](https://claude.ai/artifact/CtQyX8qfYAF822bgHJHHE3) ⭐️ 6.0/10

社区正在追踪 Alessandro Masullo 数学文稿的 Lean 形式化验证进展，并评估其证明的有效性。贡献者指出，目前仓库中记录了数百个问题与修复，尚不能过早断定核心论证是否存在致命漏洞。同时，由于数学家和教授们的审阅与表态存在分歧，该文稿引发了广泛的审慎讨论。

hackernews · Qision · 11月22日 23:12 · [社区讨论](https://news.ycombinator.com/item?id=50605045)

**「背景」** Lean 是一种交互式定理证明器，常被数学家和计算机科学家用于以机器可读和严格验证的方式形式化复杂的数学证明。

**「影响」** 参与该项目的贡献者呼吁利用 AI 智能体协助处理形式化任务，这表明形式化验证工作正在借助自动化工具加速推进。

**「社区讨论」** 评论者提醒公众不要将形式化验证的进度条误读为证明正确的证据，因为只要存在一个漏洞就足以导致整个证明失效。此外，部分评论指出相关数学教授对该文稿的态度有所保留，并对其进行了严格审视。

**标签**: `#Lean`, `#Formal Verification`, `#Mathematics`, `#Software Engineering`, `#Theorem Proving`

---

<a id="item-tech-news-5"></a>
### [Phison 发布面向轨道数据中心的 Pascari Space SSD 系列](https://videocardz.com/newz/phison-announces-488tb-of-ssd-storage-for-space-data-centers-pricing-expected-to-be-astronomical) ⭐️ 6.0/10

Phison 推出了面向航天器、卫星和在轨数据中心的 Pascari Space SSD 系列产品，并确认该系列将被 Lonestar Data Holdings 用于计划于 2027 年上半年发射的 StarVault-001 轨道数据中心。该数据中心将搭载总容量达 488 TB 的 Phison SSD，进入低地球轨道后的可用容量约为 370 TB。该系列包含 Flight Critical、Main Storage 与 Orbital Data Center 三类型号，最高容量为 128 TB，部分型号采用 pSLC 技术可将写入寿命提高至多 60 倍，目前产品已上市。

telegram · zaihuapd · 11月22日 10:31

**「背景」** 随着商业航天和近地轨道任务的发展，太空环境中对高密度、高可靠性数据存储的需求日益增长，促使硬件厂商开发专门适应辐射和极端温度等空间条件的存储设备。

**「影响」** 参与轨道数据中心建设和航天硬件开发的机构和企业将能够利用这一高容量 SSD 系列在太空中存储和处理海量数据。

**标签**: `#Hardware`, `#Storage`, `#Space Technology`, `#SSD`

---

<a id="item-tech-news-6"></a>
### [摩尔线程产品经理透露下一代庐山 GPU 拟配 64 GB 显存](https://www.tomshardware.com/pc-components/gpus/moore-threads-next-lushan-gaming-gpu-could-pack-a-record-64gb-of-vram-doubles-the-rtx-5090s-32gb-lofty-claims-of-15x-gaming-and-50x-ray-tracing-over-mtt-s80) ⭐️ 6.0/10

摩尔线程 MTT S80 产品经理透露，下一代庐山游戏 GPU 的显存容量可能达到 64 GB，该表态尚未通过公司官方正式发布。官方此前披露的目标显示，庐山相比 S80 在 AAA 游戏性能上提升 15 倍、光追性能提升 50 倍、AI 算力提升 64 倍。摩尔线程计划于 2025 年 12 月 29 至 30 日在北京举办的 MDC 2026 上，由 CEO 张建中正式发布该旗舰产品。

telegram · zaihuapd · 11月22日 15:11

**「背景」** 摩尔线程此前曾推出 MTT S80 显卡，并在 MDC 2025 大会上公布了下一代庐山架构的初步性能规划目标。

**「影响」** 若 64 GB 显存规格最终落地，庐山 GPU 将在消费级显卡显存容量上达到新高，对高负载游戏和本地 AI 推理场景带来更大的显存冗余。

**标签**: `#GPU`, `#Hardware`, `#Moore Threads`, `#VRAM`, `#Artificial Intelligence`

---

<a id="item-tech-news-7"></a>
### [Windows Server 2028 默认移除 32 位应用支持](https://www.windowslatest.com/2026/11/23/32-bit-apps-days-are-numbered-as-microsoft-strips-support-bit-by-bit-starting-with-windows-server-2028-but-windows-11-is-safe-for-now/) ⭐️ 6.0/10

微软在 Ignite 2026 上宣布，计划于 2027 年秋季发布的 Windows Server 2028 将默认不再包含 WoW64 兼容子系统，导致系统开箱即无法运行 32 位应用。此举旨在减少攻击面并阻止 32 位恶意软件，但管理员仍可通过按需功能（FoD）手动将 WoW64 装回。目前 Windows 11 仍保留 WoW64 支持，微软尚未公布其移除计划。

telegram · zaihuapd · 11月23日 03:03

**「背景」** WoW64（Windows 32-on-Windows 64）是 Windows 操作系统中的一个子系统，长期以来一直负责在 64 位版本的 Windows 上运行 32 位应用程序。

**「影响」** 依赖 32 位软件的企业 IT 管理员在升级到 Windows Server 2028 时，必须通过 PowerShell 或 DISM 手动添加 FoD 功能来恢复兼容性，否则相关老旧应用将无法直接运行。

**标签**: `#Windows Server`, `#Operating Systems`, `#Security`, `#Microsoft`, `#Enterprise IT`

---

## 科技博客

<a id="item-tech-blog-1"></a>
### [在高度不确定性中摸索前行](https://seangoedecke.com/when-in-doubt-flail-about/) ⭐️ 7.0/10

rss · Sean Goedecke · 11月23日 00:00

**「背景」** 当工程师面对信息不明或缺乏指导的复杂情况时，本能的谨慎和超前规划往往力不从心。作者指出，等待全面理解常常行不通，我们需要一种主动应对高度不确定性的方法。

**「方案」** 作者主张采用一种被称为“胡乱折腾”的策略，即通过尝试多种低承诺方案并密切倾听反馈来打破僵局。由于缺乏信息，单个计划很可能失效，因此必须并行尝试多个选项，并对未获积极反馈的方案果断放弃。这种方法具体可应用于三个场景：在产品开发中通过边缘试错寻找产品契合点；在复杂的工程系统中通过投机性的小改动快速观测性能；以及在组织协作受阻时，通过提出多种设想来化解僵局。虽然这种实践从内部感受上像是不断失败和出丑，但只要保持对反馈的高度敏感，它就是一种极具价值的探索手段。

**「启示」** 在复杂环境中，伴随不适感的快速试错与敏锐反馈比盲目等待完美规划更为有效。克服心理阻碍并拥抱这种探索过程，是成为高效工程师的关键能力。

**标签**: `#software engineering`, `#problem solving`, `#product management`, `#engineering leadership`, `#experimental design`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [美股科技股大跌，亚洲多地出台股市稳定措施](https://news.bjd.com.cn/2026/11/22/12039852.shtml) ⭐️ 8.0/10

受美国人工智能科技股周五遭遇大规模抛售拖累，纳斯达克指数单日暴跌 5.28%，费城半导体指数重挫近 11%，中国内天、韩国和中国台湾地区随即宣布了下调融资保证金、放宽回购或限制卖空等一系列市场稳定措施。

telegram · zaihuapd · 11月22日 13:24

**「背景」** 近期美国科技股因市场抛售出现剧烈波动，引发了亚洲主要股票市场对跨市风险蔓延的防范。

**「影响」** 相关政策直接影响了亚洲市场的投资者交易规则，旨在抑制短期恐慌情绪并防范信用违约风险。

**标签**: `#Stock Market`, `#Monetary Policy`, `#Technology Sector`, `#Regulatory Action`, `#Market Disruption`

---

<a id="item-finance-news-2"></a>
### [超级厄尔尼诺海温破纪录与粮食援助危机](https://www.wired.com/story/how-this-years-super-el-nino-will-worsen-global-hunger/) ⭐️ 8.0/10

根据气候学家的数据，截至 10 月，今年超级厄尔尼诺现象中热带太平洋升温已达 3.5℃并打破此前约 2.75℃的纪录；世界粮食计划署预计，这可能在 2027 年底前将额外 4900 万人推入急性粮食不安全状态，同时全球援助资金较 2022 年峰值下降了 30%。

telegram · zaihuapd · 11月22日 14:09

**「背景」** 厄尔尼诺是一种自然气候现象，通过改变全球大气环流导致部分地区严重干旱或洪涝，进而对全球农业生产和粮食供应链造成冲击。

**标签**: `#El Niño`, `#Food Security`, `#Climate Change`, `#Global Economy`

---

<a id="item-finance-news-3"></a>
### [中国要求美国撤销电话号段接入限制](https://www.bloomberg.com/news/articles/2026-11-22/china-objects-to-us-curbs-on-telecoms-access-to-phone-numbers) ⭐️ 7.0/10

中国商务部于 11 月 22 日敦促美国撤销一项禁止中国三大电信运营商直接获取美国电话号码的限制措施，称该措施违反公平竞争并警告其正推动两国走向技术脱钩。

telegram · zaihuapd · 11月22日 06:44

**「背景」** 在此之前，美国联邦通信委员会（FCC）于 11 月 19 日投票通过新规，收紧了互联网语音服务商直接接入美国号码的安全要求，以阻止特定实体接入美国网络。

**「影响」** 相关限制措施直接影响中国三大国有电信运营商在美国市场的业务接入，并可能进一步加剧两国在通信与科技领域的经贸摩擦。

**标签**: `#Telecommunications`, `#US-China Relations`, `#Regulatory Policy`, `#FCC`

---

<a id="item-finance-news-4"></a>
### [蚂蚁集团领投中国具身智能公司 1 亿美元融资](https://www.bloomberg.com/news/articles/2026-11-22/ant-group-bets-on-simplexity-to-thrive-in-china-s-humanoid-race) ⭐️ 7.0/10

中国具身智能初创企业 Simplexity Robotics 完成了 1 亿美元的 pre-A 轮融资，由蚂蚁集团领投，使公司投后估值达到了 16 亿美元。

telegram · zaihuapd · 11月23日 02:02

**「背景」** 具身智能是指将人工智能技术集成到机器人等实体硬件中，使其能够感知并与物理世界进行交互。

**「影响」** 这笔资金将帮助 Simplexity Robotics 在中国的人形机器人市场中，与宇树和优必选等更成熟的厂商展开竞争。

**标签**: `#venture capital`, `#embodied AI`, `#robotics`, `#Ant Group`, `#funding`

---

<a id="item-finance-news-5"></a>
### [前三季度国内手机市场份额发布](https://weibo.com/1642634100/RsyNmsLgF) ⭐️ 6.0/10

博主 @RD 观测 发布的数据显示，2026 年前三季度国内手机市场销量整体下跌约 9.2%，其中华为以 20.25% 的市场份额居首，较去年同期的 16.33% 提升 3.92 个百分点。

telegram · zaihuapd · 11月22日 08:22

**「背景」** 同期国内手机市场头部集中趋势加剧，仅华为与苹果两家份额实现正增长，其余主要品牌的市场份额均同比下滑。

**标签**: `#smartphone market`, `#market share`, `#Huawei`, `#Apple`, `#consumer electronics`

---