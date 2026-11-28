---
layout: default
title: "Horizon Summary: 2026-11-28 (ZH)"
date: 2026-11-28
lang: zh
---

> 从 31 条内容中筛选出 19 条重要资讯。

---

**科技新闻**
1. [Linux 内核 NFS 服务器披露 9.8 分高危漏洞](#item-tech-news-1) ⭐️ 9.0/10
2. [Google Research 推出 DeepCrossAttention 以加速 Transformer 模型残差连接](#item-tech-news-2) ⭐️ 8.0/10
3. [Michael Nielsen 下架其神经网络在线教程](#item-tech-news-3) ⭐️ 8.0/10
4. [AWS Trainium3 微架构与推理性能深度解析](#item-tech-news-4) ⭐️ 8.0/10
5. [微软计划以 Windows 内置驱动取代部分第三方驱动](#item-tech-news-5) ⭐️ 8.0/10
6. [计算机检查证明系统中的正确性漏洞与局限性分析](#item-tech-news-6) ⭐️ 7.0/10
7. [多州总检察长起诉 SpaceX 指控 Grok 生成违法图像](#item-tech-news-7) ⭐️ 7.0/10
8. [电子商务网站被曝利用 WebRTC 窃取信用卡数据](#item-tech-news-8) ⭐️ 7.0/10
9. [Convex AI 技能被曝在未明确告知的情况下将用户应用构想发送至远程服务器](#item-tech-news-9) ⭐️ 7.0/10
10. [美国中情局等多家情报机构遭使用 AI 工具 Artex 的黑客攻击](#item-tech-news-10) ⭐️ 7.0/10
11. [Anthropic 承认曾暗中限制前沿模型研发请求](#item-tech-news-11) ⭐️ 7.0/10
12. [Bouncemarket：基于弹跳小球的实时预测市场游戏](#item-tech-news-12) ⭐️ 6.0/10
13. [《我的世界》基岩版资源包漏洞修复](#item-tech-news-13) ⭐️ 6.0/10

**财经新闻**
1. [国常会要求优化类平准基金功能](#item-finance-news-1) ⭐️ 9.0/10
2. [蜜雪冰城 5 亿元参与 DeepSeek 新一轮融资](#item-finance-news-2) ⭐️ 8.0/10
3. [央行公布大额存单新规](#item-finance-news-3) ⭐️ 8.0/10
4. [市场监管总局集中约谈 15 家电动自行车企业](#item-finance-news-4) ⭐️ 8.0/10
5. [标普 500 指数陷入回调](#item-finance-news-5) ⭐️ 7.0/10
6. [英伟达股价波动考验美联储主席沃什的政策理念](#item-finance-news-6) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Linux 内核 NFS 服务器披露 9.8 分高危漏洞](https://opensec.in/blog/nfs2root-cve-2026-99362) ⭐️ 9.0/10

安全团队 OpenSec 于 2026 年 11 月 20 日公开了 Linux 内核 NFS 服务端的一个预认证堆溢出漏洞（CVE-2026-99362），CVSS 评分高达 9.8。该漏洞自 2014 年发布 Linux 3.16 起即存在，攻击者无需登录即可通过发往 tcp/2049 端口的连接进行越界写入并获取 root 权限，影响启用 NFSv4.1 或 4.2 的主机。官方已在 6.12.117、6.18.61、7.3.2 及 7.4-rc1 版本中发布了修复补丁。

telegram · zaihuapd · 11月27日 12:57

**「背景」** Linux 内核的 NFS（网络文件系统）服务端模块（nfsd）允许远程客户端通过网络挂载和访问服务器上的文件目录，广泛应用于企业级文件服务器、NAS 及集群存储节点。

**「影响与建议」** 受影响的系统管理员必须尽快将内核升级至已修复的版本并重启服务器；若无法立即升级，应通过防火墙限制对 tcp/2049 端口的访问以降低风险。

**标签**: `#Linux Kernel`, `#Security Vulnerability`, `#NFS`, `#Systems Engineering`, `#Network Security`

---

<a id="item-tech-news-2"></a>
### [Google Research 推出 DeepCrossAttention 以加速 Transformer 模型残差连接](https://research.google/blog/supercharging-transformer-residual-connections/) ⭐️ 8.0/10

Google Research 推出了名为 DeepCrossAttention 的新技术，旨在超级加速 Transformer 模型的残差连接。该技术在实现最高可达 3 倍加速的同时，能够保持与原有模型相当的模型质量。

hackernews · ComputedCamp995 · 11月27日 23:06 · [社区讨论](https://news.ycombinator.com/item?id=50672565)

**「背景」** 传统变压器模型的残差连接通常采用简单的层输出求和方式，这可能会稀释关键信息并限制模型的训练效率。

**「社区讨论」** 评论区讨论了该技术与 DenseNet 等早期架构的相似性，并有用户探讨了其与近年来其他推理及训练加速方法（如 MTP 和 Dflash）叠加使用的可能性。此外，有用户指出原研究图表使用了折线图而非不具时间序列关联的柱状图并不合适。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2502.06785">DeepCrossAttention : Supercharging Transformer Residual ...</a></li>

</ul>
</details>

**标签**: `#artificial intelligence`, `#machine learning`, `#transformers`, `#hardware optimization`

---

<a id="item-tech-news-3"></a>
### [Michael Nielsen 下架其神经网络在线教程](https://neuralnetworksanddeeplearning.com/) ⭐️ 8.0/10

Michael Nielsen 已将广受欢迎的神经网络与深度学习在线图书从原网址下架。这一举动引发了技术社区关于开放教育以及前沿人工智能发展的广泛讨论与抗议。

hackernews · brandonb · 11月27日 19:31 · [社区讨论](https://news.ycombinator.com/item?id=50670757)

**「背景」** Michael Nielsen 撰写的在线教程长期以来被视为机器学习和神经网络领域的经典入门资源，对开源教育社区产生了深远影响。

**「社区讨论」** 评论者认为此举更类似于一种象征性的抗议，虽然原网站已无法直接访问，但由于内容早已广泛传播，且有互联网存档存在，更多人开始关注其背后的动机。部分讨论还延伸到了前沿实验室的发展资本以及对超级人工智能（ASI）潜在风险的担忧。

**标签**: `#artificial intelligence`, `#neural networks`, `#open source`, `#machine learning`, `#industry trends`

---

<a id="item-tech-news-4"></a>
### [AWS Trainium3 微架构与推理性能深度解析](https://newsletter.semianalysis.com/p/trainium3-inferencex) ⭐️ 8.0/10

SemiAnalysis 发布了针对 AWS Trainium3 机器学习微架构与推理性能的深度技术分析。基准测试结果显示，Trainium3 在总拥有成本（TCO）的 Token 生成成本方面，能够与英伟达 GB300 展开竞争甚至超越。这一优势得益于其专为机器学习从头设计的微架构（如将 Tile 作为一等原语）以及描述符生成引擎（DGE），使其在小消息尺寸下也能达到峰值高带宽内存（HBM）利用率。

rss · Semianalysis · 11月27日 15:54

**「背景」** 英伟达的 GPU 最初为图形渲染而设计，历代架构通过不断加装张量核心（Tensor Cores）和切片数据移动引擎来适配 AI 负载。相比之下，传统的 ASIC 芯片如 AWS Trainium 采用专为机器学习工作负载构建的微架构，但在早期曾面临极大的软件栈挑战。

**标签**: `#Hardware`, `#Artificial Intelligence`, `#Machine Learning`, `#Cloud Computing`

---

<a id="item-tech-news-5"></a>
### [微软计划以 Windows 内置驱动取代部分第三方驱动](https://www.techspot.com/news/114721-microsoft-wants-replace-most-third-party-device-drivers.html) ⭐️ 8.0/10

微软在 Ignite 2026 大会上宣布，计划开发全新的内置硬件驱动以取代部分第三方驱动，旨在减少第三方代码对系统内核的侵入并提升安全性。首批重点替换领域涵盖打印机、音频及总线驱动，其中近期推出的 Windows Ready Print 模式用于取代旧式第三方打印驱动，而 SoundWire、SDCA 音频驱动以及 I3C 总线、USB 以太网和 MIPI 摄像头驱动也正作为内置组件进行开发。

telegram · zaihuapd · 11月28日 02:09

**「背景」** 长期以来，第三方硬件驱动在 Windows 内核层运行，其质量和稳定性问题常常成为引发操作系统崩溃或安全漏洞的主要隐患之一。

**「影响」** 此举将促使 OEM 厂商和第三方开发者调整硬件适配策略，更多地依赖微软的内置驱动标准和驱动质量倡议（DQI），从而改变 Windows 生态中硬件驱动的开发与维护模式。

**标签**: `#Operating Systems`, `#Windows`, `#Kernel Security`, `#Hardware Drivers`

---

<a id="item-tech-news-6"></a>
### [计算机检查证明系统中的正确性漏洞与局限性分析](https://cr.yp.to/proofs/falseccp.html) ⭐️ 7.0/10

近期的一项技术分析探讨了计算机检查证明系统（Computer-Checked Proofs）中存在的可靠性问题与正确性漏洞。此类形式化验证工具虽然在软件工程中得到应用，但其底层验证机制仍可能出现漏洞，引发技术界对完全依赖单一验证器安全性的讨论。

hackernews · \_tk\_ · 11月27日 15:26 · [社区讨论](https://news.ycombinator.com/item?id=50667989)

**「背景」** 计算机检查证明与形式化验证系统旨在通过数学方法证明软件或数学定理的正确性，以替代传统的人工审查。然而，这些验证系统自身的实现复杂度高，其核心检查程序也可能存在未被发现的漏洞。

**「影响」** 开发人员和研究人员在采用形式化验证工具时，不能盲目信任单一工具的检查结果，应当了解工具链中潜在的正确性风险。

**「社区讨论」** 评论者指出，实际应用中通常需要通过多个独立编写的验证器来交叉验证证明，从而大大降低因单个验证器漏洞导致系统失效的风险。另有观点认为，历史发现的漏洞数量相对较少，且将其与利用这些漏洞来误导数学家的实际难度结合来看，该技术对于绝大多数软件工程而言仍然具备极高的可靠性。

**标签**: `#formal verification`, `#software engineering`, `#computer systems`, `#open source`

---

<a id="item-tech-news-7"></a>
### [多州总检察长起诉 SpaceX 指控 Grok 生成违法图像](https://www.oag.state.va.us/media-center/news-releases/jay-jones/3162-attorneys-general-jones-and-rayfield-file-suit-against-spacex-parent-company-of-x-xai-and-grok-over-creation-and-promotion-of-child-exploitation-and-non-consensual-images-on-platform) ⭐️ 7.0/10

多州总检察长对 SpaceX（即 X 平台与 xAI 的母公司）提起诉讼，指控该公司旗下的 Grok 生成并传播儿童性虐待材料及非自愿亲密图像。该诉讼针对 AI 系统在内容审核和安全防护上的严重漏洞，直接涉及平台的责任及生成式人工智能的合规运营。

hackernews · DeepLogin · 11月27日 19:42 · [社区讨论](https://news.ycombinator.com/item?id=50670855)

**「背景」** xAI 开发的对话与生成模型 Grok 由于其内容审核政策相对宽松，此前多次因允许用户生成未经授权的深伪图像及争议性内容而受到公众和监管机构的审视。

**「影响」** 此项诉讼可能迫使 xAI 和 X 平台收紧 Grok 及相关生成工具的安全防护措施，并为未来针对 AI 开发商在生成有害合成内容方面的法律责任确立重要先例。

**「社区讨论」** 社区讨论主要集中在内容生成机制及法律界限上，有评论者对该功能此前未被严格限制感到困惑，也有人质疑相关司法管辖权以及针对自制生成内容的法律裁决标准。

**标签**: `#artificial intelligence`, `#ai safety`, `#legal/regulation`, `#ethics`, `#xai`

---

<a id="item-tech-news-8"></a>
### [电子商务网站被曝利用 WebRTC 窃取信用卡数据](https://www.infohawk.com/news/2026-11-27-black-friday-webrtc-skimmer) ⭐️ 7.0/10

安全研究人员在一些热门购物网站上发现了使用 WebRTC 的信用卡窃取脚本。这些脚本利用 WebRTC 协议外泄支付数据，从而避开标准的网络监控和检测机制。

hackernews · scanr · 11月27日 15:40 · [社区讨论](https://news.ycombinator.com/item?id=50668145)

**「背景」** WebRTC 是一种支持网页浏览器进行实时语音、视频和数据分享的技术。网络攻击者通常利用第三方脚本注入等手段，在受害者的浏览器端运行恶意 JavaScript 代码以窃取敏感信息。

**「社区讨论」** 评论指出，这种攻击并未利用 WebRTC 的底层技术缺陷，而是利用了该协议较少受到监控的盲区，其本质依然是第三方脚本嵌入带来的安全漏洞。部分用户认为，允许陌生服务器在客户端任意执行不可控代码是万维网设计中的根本隐患。

**标签**: `#Cybersecurity`, `#WebRTC`, `#E-commerce`, `#JavaScript Security`

---

<a id="item-tech-news-9"></a>
### [Convex AI 技能被曝在未明确告知的情况下将用户应用构想发送至远程服务器](https://github.com/convex/convex-backend-skill/issues/64) ⭐️ 7.0/10

一个 GitHub 问题显示，Convex 的 AI 技能在未明确通知用户的情况下，将用户的应用构想发送到了远程服务器。该问题引发了开发者社区对隐私和数据处理方式的讨论，该公司 CEO 随后在评论中进行了回应与澄清。

hackernews · MickyTheMouse · 11月27日 18:02 · [社区讨论](https://news.ycombinator.com/item?id=50669765)

**「背景」** Convex 是一个用于构建和托管软件的全栈平台，近期由于开发 AI 编码助手和插件中的数据隐私问题，受到了开发者社区的密切关注。

**「社区讨论」** 公司 CEO 解释称该功能用于支持 Convex 的快速启动特性，而社区成员则认为信任是新的注意力，并讨论了使用自托管开源模型的必要性。

**标签**: `#artificial intelligence`, `#developer tools`, `#privacy`, `#software engineering`, `#open source`

---

<a id="item-tech-news-10"></a>
### [美国中情局等多家情报机构遭使用 AI 工具 Artex 的黑客攻击](https://www.forbes.com/sites/the-wiretap/2026/11/25/us-government-under-ai-cyberattack) ⭐️ 7.0/10

美国中央情报局、国家地理空间情报局和国家情报总监办公室等多家情报机构遭黑客攻击，攻击过程中使用了名为 Artex 的 AI 辅助工具。此次攻击的影响局限于非机密侦察数据，整体情况不算严重。攻击中使用的 Artex 可整合多个开源 AI 模型来测试网络和计算机防御，由一名中国开发者于今年早些时候发布并随后从 GitHub 删除，此前已被用于针对欧盟等的多起攻击。

telegram · zaihuapd · 11月27日 10:42

**「背景」** Artex 是一种能够整合多个开源 AI 模型以测试网络和计算机防御的工具。联邦调查局（FBI）此前曾发出警告，指出网络罪犯和间谍正在广泛使用该工具。

**「影响」** 此次事件暴露出黑客正开始利用集成开源 AI 模型的工具对政府核心机构进行侦察试探，促使相关安全部门需要针对 AI 辅助的网络攻击防范采取进一步应对措施。

**标签**: `#artificial intelligence`, `#cybersecurity`, `#government`, `#threat intelligence`

---

<a id="item-tech-news-11"></a>
### [Anthropic 承认曾暗中限制前沿模型研发请求](https://news.ycombinator.com/item?id=50664325) ⭐️ 7.0/10

Anthropic 承认在今年 6 月发布的 Fable 5 系统卡中，曾对涉及开发前沿大模型的请求实施不可见的暗中限制，手段包括改写提示、引导向量和参数高效微调，影响约 0.03% 的流量。这一持续至 6 月 10 日的错误做法已在当时被撤销，现行的做法是将此类请求明确拒绝或回退并向用户显示提示。该公司同时否认曾训练 Claude 蓄意破坏用户工作，并指出部分用户反馈源于模型在长时间任务中的过度谨慎。

telegram · zaihuapd · 11月27日 13:42

**「背景」** 使用 AI 辅助开发同类前沿大模型本身违反了相关服务条款，而大模型系统卡通常用于披露模型的能力边界与安全防护机制。

**标签**: `#Artificial Intelligence`, `#Anthropic`, `#AI Safety`, `#Machine Learning`

---

<a id="item-tech-news-12"></a>
### [Bouncemarket：基于弹跳小球的实时预测市场游戏](https://bouncemarket.minhanhday.com/) ⭐️ 6.0/10

开发者推出了一款名为 bouncemarket 的实时预测市场游戏，玩家可以对服务器模拟弹跳小球的最终落点进行股份交易。小球的下落过程在服务端进行确定性物理模拟，并通过服务器发送事件（SSE）带有小缓冲区地流式传输至客户端。游戏内置了基础规则的 AI 交易员，当单局玩家超过五人时 AI 会自动退出，以确保真实玩家之间的博弈。

hackernews · mday404 · 11月27日 15:01 · [社区讨论](https://news.ycombinator.com/item?id=50667726)

**「背景」** 预测市场允许参与者通过买卖事件结果的契约来进行押注和价格发现。结合确定性物理模拟与实时流传输，能够让所有客户端精准同步并重现完全一致的动态过程。

**「影响」** 玩家和开发者可以测试在极短周期、纯随机且由物理驱动的事件中，预测市场的流动性表现与套利策略的可行性。

**「社区讨论」** 评论者指出游戏存在赔率变化过快导致难以投注的问题，同时有人发现完全不看小球、盲目买入廉价份额是一种高效策略。还有人讨论了利用前端模型编写求解器来应对这类混沌下落系统的可能性。

**标签**: `#prediction markets`, `#physics simulation`, `#web development`, `#game design`

---

<a id="item-tech-news-13"></a>
### [《我的世界》基岩版资源包漏洞修复](https://www.zaikei.co.jp/article/20261119/878386.html) ⭐️ 6.0/10

《我的世界》基岩版 26.52 至 26.63 版本存在一处资源包漏洞，允许带有 content.zipe 文件的恶意资源包修改 Ore UI 框架并执行隐藏脚本。该漏洞影响 PC、手机和主机平台，当玩家在加入服务器或 Realm 时开启资源包自动下载便可能中招，攻击者可借此删除存档、获取 IP 或在 Windows 上触发恶意软件下载。Mojang 已在 26.65 版本中修复了该问题，Java 版则不受此漏洞影响。

telegram · zaihuapd · 11月27日 18:04

**「背景」** 《我的世界》基岩版支持通过资源包与附加组件自定义游戏内容，并在玩家连接服务器时自动下载相关资源。Ore UI 是该版本用于构建游戏界面框架的组件。

**「影响」** 使用 26.52 至 26.63 版本的基岩版玩家应当尽快将游戏升级至 26.65 或更高版本，以避免在联机时遭受自动下载的恶意资源包攻击。

**标签**: `#Minecraft`, `#Security Vulnerability`, `#Game Development`, `#Remote Code Execution`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [国常会要求优化类平准基金功能](https://www.tmtpost.com/nictation/8220182.html) ⭐️ 9.0/10

国务院总理李强于 11 月 27 日主持召开国务院常务会议，提出要加力发挥“国家队”稳市作用，进一步优化中央汇金公司的类“平准基金”功能以提供充足流动性保障。

telegram · zaihuapd · 11月27日 05:35

**「背景」** 平准基金是指国家通过特定机构在证券市场低迷时进行逆周期买入以稳定市场行情的资金。资本市场事关经济发展大局，近期中国持续通过完善稳市机制与引导中长期资金入市来支持资本市场平稳运行。

**「影响」** 该政策有助于为 A 股市场注入流动性并提振投资者信心，同时推动上市公司分红与中长期资金入市。

**标签**: `#monetary policy`, `#capital markets`, `#economic regulation`, `#government policy`

---

<a id="item-finance-news-2"></a>
### [蜜雪冰城 5 亿元参与 DeepSeek 新一轮融资](https://m.sohu.com/a/1107027659_115479) ⭐️ 8.0/10

茶饮企业蜜雪冰城通过基金出资 5 亿元人民币参与人工智能企业 DeepSeek 的新一轮融资。该轮融资总规模在 1000 亿至 1055 亿元人民币之间，投后估值约达 6155 亿元人民币。

telegram · zaihuapd · 11月27日 06:33

**「背景」** DeepSeek 近期完成了包含多家知名企业和机构在内的新一轮融资，蜜雪冰城则通过创下今年市场化人民币盲池基金（即事先未确定具体投资标的的投资基金）最大募资纪录的天津砺思星深基金完成此次认缴。

**标签**: `#Artificial Intelligence`, `#Venture Capital`, `#Corporate Investment`, `#DeepSeek`

---

<a id="item-finance-news-3"></a>
### [央行公布大额存单新规](https://www.news.cn/fortune/20261127/70789d77822242cc82216f51a416f872/c.html) ⭐️ 8.0/10

中国人民银行公布新修订的《大额存单管理办法》，自 2027 年 3 月 21 日起将个人投资人认购起点金额由原先的 20 万元下调至 10 万元，机构投资人起点由 1000 万元下调至 500 万元。

telegram · zaihuapd · 11月27日 11:36

**「背景」** 大额存单是由银行业金融机构面向个人、非金融企业等机构发行的大额存款凭证，此前适用的旧版暂行办法于 2015 年发布。

**标签**: `#Central Bank`, `#Monetary Policy`, `#Banking`, `#Interest Rates`, `#Regulation`

---

<a id="item-finance-news-4"></a>
### [市场监管总局集中约谈 15 家电动自行车企业](https://www.news.cn/20261127/0c8c665ce70c417b9263b39fa8a519f0/c.html?hl=zh-CN) ⭐️ 8.0/10

11 月 27 日，国家市场监管总局集中约谈了雅迪、台铃、爱玛等 15 家电动自行车企业，要求企业针对飞行检查中发现的产品质量不合格、一致性管控不严等问题进行严格整改并实施产品召回。

telegram · zaihuapd · 11月27日 12:06

**「背景介绍」** 近期监管部门对电动自行车行业开展了中国强制性产品认证（即 CCC 认证）的全覆盖飞行检查，并发现了相关质量与合规问题。

**「市场影响」** 相关电动自行车生产企业需全面规范产品出厂标准并落实缺陷产品召回，从而保障消费者的出行安全与合法权益。

**标签**: `#Regulation`, `#Electric Vehicles`, `#Compliance`, `#Consumer Rights`, `#China Market`

---

<a id="item-finance-news-5"></a>
### [标普 500 指数陷入回调](https://www.cnbc.com/2026/11/27/the-sp-500-is-in-a-correction-bear-markets-and-recessions-dont-always-follow.html) ⭐️ 7.0/10

由于股市从 10 月的最高点大幅回落，标普 500 指数于 2026 年 11 月 20 日下跌 11.6%，收于 6,910.39 点，正式进入跌幅达 10%以上的“回调”区间。

rss · CNBC Finance · 11月27日 13:21

**「背景」** 当股票价格从近期最高点下跌 10%到 20%之间时即被定义为市场回调，历史数据表明股市回调并不必然预示着经济将陷入衰退。

**标签**: `#S&amp;P 500`, `#Market Correction`, `#Federal Reserve`, `#Recession`, `#Equities`

---

<a id="item-finance-news-6"></a>
### [英伟达股价波动考验美联储主席沃什的政策理念](https://www.cnbc.com/2026/11/25/nvidia-kevin-warsh-fed-market-signals.html) ⭐️ 7.0/10

近期英伟达公司股价和金融市场的剧烈波动，正值美联储主席凯文·沃什（Kevin Warsh）推行重视市场指标、忽视短期日常市场噪音的货币政策框架之际。

rss · CNBC Finance · 11月27日 13:29

**「背景」** 沃什主张减少前瞻性指引并依赖市场指标来引导政策，但这些指标容易受到短期剧烈波动的影响，从而给央行决策带来挑战。

**标签**: `#Federal Reserve`, `#Monetary Policy`, `#Financial Markets`, `#Interest Rates`, `#Kevin Warsh`

---