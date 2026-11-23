---
layout: default
title: "Horizon Summary: 2026-11-23 (EN)"
date: 2026-11-23
lang: en
---

> From 27 items, 13 important content pieces were selected

---

**Technology News**
1. [Exploring the Correlation Between Model Perplexity and Machine Learning Intelligence](#item-tech-news-1) ⭐️ 8.0/10
2. [Examining the Evolution and Optimization Goals of Silicon Valley](#item-tech-news-2) ⭐️ 7.0/10
3. [Google Creates Simulated Internet &\#x27;Mirror Dimension&\#x27; to Test Chrome AI Agents](#item-tech-news-3) ⭐️ 7.0/10
4. [Progress tracking and community debate surround the Lean formalization of Alessandro Masullo&\#x27;s manuscript](#item-tech-news-4) ⭐️ 6.0/10
5. [Phison Announces 488 TB Pascari Space SSD Series for Orbital Data Centers](#item-tech-news-5) ⭐️ 6.0/10
6. [Moore Threads Product Manager Claims Lushan GPU Will Feature 64GB VRAM](#item-tech-news-6) ⭐️ 6.0/10
7. [Windows Server 2028 Will Drop Default 32-Bit App Support](#item-tech-news-7) ⭐️ 6.0/10

**Technology Blog**
1. [When in Doubt, Flail About](#item-tech-blog-1) ⭐️ 7.0/10

**Financial News**
1. [US Tech Sell-Off Triggers Asian Market Defenses](#item-finance-news-1) ⭐️ 8.0/10
2. [Super El Niño threatens global food security as aid funding falls](#item-finance-news-2) ⭐️ 8.0/10
3. [China Objects to US Telecom Restrictions](#item-finance-news-3) ⭐️ 7.0/10
4. [Simplexity Robotics Raises 100 Million USD](#item-finance-news-4) ⭐️ 7.0/10
5. [Huawei Leads Domestic Smartphone Market in First Three Quarters](#item-finance-news-5) ⭐️ 6.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Exploring the Correlation Between Model Perplexity and Machine Learning Intelligence](https://openai.com/index/perplexity-and-intelligence/) ⭐️ 8.0/10

An analysis explores the relationship between language model perplexity and intelligence, examining how prediction and compression rates correlate with progress in machine learning. Commenters noted that perplexity measures a model&\#x27;s surprise when predicting the next token over a sequence, ranging from one to the size of the vocabulary. Discussion also highlighted Microsoft&\#x27;s commitment to sharing pre-training progress on a common held-out evaluation set, reporting a log-perplexity of 0.819 for the MAI-2 Base model.

hackernews · acossta · Nov 22, 17:06 · [Discussion](https://news.ycombinator.com/item?id=50601525)

**「Perplexity Fundamentals」** Perplexity measures how well a language model predicts the next token on average, where lower values indicate better prediction accuracy and a greater degree of data compression.

**「Impact」** Researchers and developers gain a simple, clear metric for tracking base model pre-training progress and comparing intelligence scaling across different organizations.

**「Community Discussion」** Commenters expressed surprise that cross-entropy loss and perplexity remain such clear indicators of progress despite the rise of reinforcement learning and increasingly complex benchmarks.

<details><summary>References</summary>
<ul>
<li>Perplexity and Intelligence | OpenAI</li>

</ul>
</details>

**Tags**: `#artificial intelligence`, `#machine learning`, `#language models`, `#research`

---

<a id="item-tech-news-2"></a>
### [Examining the Evolution and Optimization Goals of Silicon Valley](https://www.oreilly.com/radar/what-happened-to-silicon-valley/) ⭐️ 7.0/10

An O&\#x27;Reilly Radar analysis examines the current state of Silicon Valley, arguing that capitalism functions as an optimization engine that should be redesigned around human flourishing rather than pure corporate profit and shareholder value. The piece applies mechanism design and reverse game theory to question the fundamental rules governing modern technology companies.

hackernews · greenyouse · Nov 22, 19:20 · [Discussion](https://news.ycombinator.com/item?id=50602947)

**「Context」** Tim O&\#x27;Reilly reflects on more than 40 years in and around Silicon Valley, tracing how the technology industry&\#x27;s focus shifted from customer-centered innovation and collective intelligence to extraction driven by shareholder capitalism.

**「Community Discussion」** Commenters debated the core optimization targets of corporations, noting that Milton Friedman&\#x27;s focus on shareholder profit often lacks a defined time frame. Others highlighted how the zero-interest-rate policy \(ZIRP\) era fueled unchecked tech growth, with companies now pivoting to AI and cutting core competencies as interest rates rise.

<details><summary>References</summary>
<ul>
<li>What Happened to Silicon Valley? - O&#x27;Reilly</li>
<li>What happened to Silicon Valley, and can AI help it return to creating more value than it ... - Facebook</li>

</ul>
</details>

**Tags**: `#Silicon Valley`, `#Tech Industry`, `#Mechanism Design`, `#Capitalism`, `#Analysis`

---

<a id="item-tech-news-3"></a>
### [Google Creates Simulated Internet &\#x27;Mirror Dimension&\#x27; to Test Chrome AI Agents](https://www.landian.news/archives/128701.html) ⭐️ 7.0/10

Google has developed a simulated internet environment named Mirror Dimension to safely test Chrome AI agents on tasks such as website navigation, searching, logging in, and purchasing. The isolated environment contains thousands of mock websites, running over 1,000 test cases per engineer daily to focus on defending against malicious web attacks like prompt injections.

telegram · zaihuapd · Nov 23, 01:30

**「Background」** Browser-based AI agents can autonomously execute multi-step workflows by interacting with web elements and parsing page content. However, this autonomy exposes them to security risks like indirect prompt injection, where malicious instructions hidden within web pages manipulate the agent into performing unintended actions.

**「Impact」** Developers and organizations building browser automation agents gain a dedicated framework to stress-test AI security against prompt injections without risking live systems or exposing real user accounts.

**Tags**: `#Artificial Intelligence`, `#Cybersecurity`, `#Browser Automation`, `#Google Chrome`

---

<a id="item-tech-news-4"></a>
### [Progress tracking and community debate surround the Lean formalization of Alessandro Masullo&\#x27;s manuscript](https://claude.ai/artifact/CtQyX8qfYAF822bgHJHHE3) ⭐️ 6.0/10

A progress map and repository are tracking the ongoing Lean theorem prover formalization of Alessandro Masullo&\#x27;s mathematical manuscript. Contributors note that hundreds of issues have been logged and addressed in an errata list, while external commentators and mathematicians emphasize that formalization progress does not guarantee the underlying mathematical validity of the proof.

hackernews · Qision · Nov 22, 23:12 · [Discussion](https://news.ycombinator.com/item?id=50605045)

**「Background」** Lean is an interactive theorem prover used to formally verify mathematical proofs down to foundational axioms with machine-checked rigor. Mathematical formalization projects often break complex or contested manuscripts down into modular components and issue trackers to identify logical gaps.

**「Impact」** Mathematicians and developers contributing to or following the repository are encouraged to direct AI agent tokens toward resolving remaining formalization issues, though experts caution that a single unaddressed logical flaw can invalidate the entire proof.

**「Community Discussion」** Commenters debate the credibility of the manuscript, noting that prominent professors have distanced themselves or stated the document requires major revisions, and caution that tracking progress bars do not substitute for a complete, sound mathematical proof.

**Tags**: `#Lean`, `#Formal Verification`, `#Mathematics`, `#Software Engineering`, `#Theorem Proving`

---

<a id="item-tech-news-5"></a>
### [Phison Announces 488 TB Pascari Space SSD Series for Orbital Data Centers](https://videocardz.com/newz/phison-announces-488tb-of-ssd-storage-for-space-data-centers-pricing-expected-to-be-astronomical) ⭐️ 6.0/10

Phison has announced the Pascari Space SSD series, featuring up to 488 TB of total capacity for upcoming orbital data centers. The hardware is confirmed for Lonestar Data Holdings&\#x27; StarVault-001 mission, scheduled to launch in the first half of 2027 with an available low-Earth orbit capacity of approximately 370 TB. The product lineup includes Flight Critical, Main Storage, and Orbital Data Center tiers with individual models offering up to 128 TB, utilizing pSLC configurations that Phison claims increase write endurance by up to 60 times.

telegram · zaihuapd · Nov 22, 10:31

**「Background」** Orbital data centers are an emerging approach to space-based computing that require specialized storage hardware capable of withstanding launch vibrations, extreme thermal variations, and cosmic radiation while operating reliably in low-Earth orbit.

**「Impact」** Aerospace organizations and commercial space-data providers can utilize these high-capacity drives to support localized data processing and storage in orbit, though the hardware pricing is anticipated to be extremely high.

**Tags**: `#Hardware`, `#Storage`, `#Space Technology`, `#SSD`

---

<a id="item-tech-news-6"></a>
### [Moore Threads Product Manager Claims Lushan GPU Will Feature 64GB VRAM](https://www.tomshardware.com/pc-components/gpus/moore-threads-next-lushan-gaming-gpu-could-pack-a-record-64gb-of-vram-doubles-the-rtx-5090s-32gb-lofty-claims-of-15x-gaming-and-50x-ray-tracing-over-mtt-s80) ⭐️ 6.0/10

A Moore Threads product manager stated that the upcoming next-generation Lushan gaming GPU may feature 64 GB of VRAM, doubling the 32 GB capacity of the RTX 5090. The unofficial claims also target performance multipliers of 15x in AAA gaming, 50x in ray tracing, and 64x in AI compute compared to the older MTT S80. Official product details are expected to be announced by CEO Zhang Jianzhong at MDC 2026 in Beijing on December 29–30.

telegram · zaihuapd · Nov 22, 15:11

**「Background」** Moore Threads previously released the MTT S80, a domestic consumer graphics card that established the company&\#x27;s initial architecture baseline before setting ambitious generational improvement targets at MDC 2025.

**Tags**: `#GPU`, `#Hardware`, `#Moore Threads`, `#VRAM`, `#Artificial Intelligence`

---

<a id="item-tech-news-7"></a>
### [Windows Server 2028 Will Drop Default 32-Bit App Support](https://www.windowslatest.com/2026/11/23/32-bit-apps-days-are-numbered-as-microsoft-strips-support-bit-by-bit-starting-with-windows-server-2028-but-windows-11-is-safe-for-now/) ⭐️ 6.0/10

Microsoft announced at Ignite 2026 that Windows Server 2028, scheduled for release in autumn 2027 alongside Windows 11 27H2, will no longer include the WoW64 subsystem by default, preventing out-of-the-box execution of 32-bit applications. Administrators can manually reinstall WoW64 via Features on Demand \(FoD\) using PowerShell or DISM on Server Core. Microsoft stated this change aims to reduce the operating system attack surface and block 32-bit malware, while Windows 11 retains WoW64 support for now.

telegram · zaihuapd · Nov 23, 03:03

**「Background」** The WoW64 \(Windows on Windows 64-bit\) subsystem is the compatibility layer that has historically allowed 32-bit x86 applications to run on 64-bit versions of the Windows operating system.

**「Impact」** Enterprise IT administrators managing legacy 32-bit software on Windows Server 2028 will need to explicitly reinstall the WoW64 feature during deployment to maintain application compatibility.

**Tags**: `#Windows Server`, `#Operating Systems`, `#Security`, `#Microsoft`, `#Enterprise IT`

---

## Technology Blog

<a id="item-tech-blog-1"></a>
### [When in Doubt, Flail About](https://seangoedecke.com/when-in-doubt-flail-about/) ⭐️ 7.0/10

rss · Sean Goedecke · Nov 23, 00:00

**「Background」** When facing high uncertainty without clear guidance, engineers often default to cautious, exhaustive up-front planning that ultimately proves insufficient for complex systems.

**「Solution」** The author argues that the most effective strategy is to deliberately &quot;flail about&quot; by trying many low-commitment approaches while listening closely to feedback and ruthlessly dropping failing ideas. Because most initial plans will inevitably fall short, generating multiple alternatives prevents over-investment and allows engineers to make direct contact with reality. This pragmatic mindset applies across three distinct domains: product development, where rapid margin-testing can uncover hidden traction like GitHub&\#x27;s continuous AI seed; messy engineering systems, where speculative changes outperform exhaustive upfront analysis; and organizational friction, where trying various interventions helps untangle unarticulated team problems.

**「Takeaway」** Embracing the uncomfortable feeling of flailing is a core psychological barrier engineers must push through to discover effective solutions under uncertainty. By maintaining strict feedback loops and discarding what fails, this experimental approach turns confusion into productive discovery.

**Tags**: `#software engineering`, `#problem solving`, `#product management`, `#engineering leadership`, `#experimental design`

---

## Financial News

<a id="item-finance-news-1"></a>
### [US Tech Sell-Off Triggers Asian Market Defenses](https://news.bjd.com.cn/2026/11/22/12039852.shtml) ⭐️ 8.0/10

Following a steep drop in US technology stocks where the Nasdaq plunged 5.28% and the Philadelphia Semiconductor Index fell nearly 11% on Friday, financial authorities in China, South Korea, and Taiwan introduced emergency stabilization measures and trading restrictions.

telegram · zaihuapd · Nov 22, 13:24

**「Background」** Regulators frequently intervene with trading curbs, margin adjustments, and repurchase rules during sharp market downturns to curb panic selling and restore liquidity.

**「Impact」** Investors and traders across Asian stock markets face tighter short-selling bans, higher margin requirements, and altered trading rules as regional authorities attempt to contain spillover from US tech losses.

**Tags**: `#Stock Market`, `#Monetary Policy`, `#Technology Sector`, `#Regulatory Action`, `#Market Disruption`

---

<a id="item-finance-news-2"></a>
### [Super El Niño threatens global food security as aid funding falls](https://www.wired.com/story/how-this-years-super-el-nino-will-worsen-global-hunger/) ⭐️ 8.0/10

A record-breaking super El Niño could push an additional 49 million people into acute food insecurity by the end of 2027 for a total of 274 million, according to World Food Programme projections, while global aid funding has dropped 30% from its 2022 peak.

telegram · zaihuapd · Nov 22, 14:09

**「Background」** El Niño is a recurring climate pattern characterized by warmer-than-average ocean temperatures in the central and eastern tropical Pacific, which disrupts global weather and agricultural yields.

**「Impact」** Vulnerable populations in drought-affected regions face severe hunger as humanitarian organizations scale back food distribution due to shrinking budgets.

**Tags**: `#El Niño`, `#Food Security`, `#Climate Change`, `#Global Economy`

---

<a id="item-finance-news-3"></a>
### [China Objects to US Telecom Restrictions](https://www.bloomberg.com/news/articles/2026-11-22/china-objects-to-us-curbs-on-telecoms-access-to-phone-numbers) ⭐️ 7.0/10

On November 22, 2026, China&\#x27;s Ministry of Commerce urged the US to revoke restrictions that prevent Chinese telecom operators from accessing US phone numbers, warning that the policy pushes both nations toward technological decoupling.

telegram · zaihuapd · Nov 22, 06:44

**「Background」** The US Federal Communications Commission \(FCC\) voted on November 19, 2026, to tighten security requirements and add national security certifications to block certain entities from accessing US telecommunications networks.

**「Impact」** Chinese telecom operators and internet voice service providers face direct barriers to entering the US market and accessing necessary network resources.

**Tags**: `#Telecommunications`, `#US-China Relations`, `#Regulatory Policy`, `#FCC`

---

<a id="item-finance-news-4"></a>
### [Simplexity Robotics Raises 100 Million USD](https://www.bloomberg.com/news/articles/2026-11-22/ant-group-bets-on-simplexity-to-thrive-in-china-s-humanoid-race) ⭐️ 7.0/10

Chinese embodied artificial intelligence startup Simplexity Robotics raised 100 million USD in a pre-A funding round led by Ant Group, resulting in a post-money valuation of 1.6 billion USD according to Chairman and Co-founder Wang Kai.

telegram · zaihuapd · Nov 23, 02:02

**「Company Background」** Founded in Hangzhou in July 2025 by former Li Auto team members, the company previously reported reaching a valuation of over 1 billion USD in March following five earlier funding rounds.

**Tags**: `#venture capital`, `#embodied AI`, `#robotics`, `#Ant Group`, `#funding`

---

<a id="item-finance-news-5"></a>
### [Huawei Leads Domestic Smartphone Market in First Three Quarters](https://weibo.com/1642634100/RsyNmsLgF) ⭐️ 6.0/10

Data published by blogger @RD 观测 shows that Huawei ranked first with a 20.25% share of the domestic smartphone market in the first three quarters of 2026, up from 16.33% in the same period last year.

telegram · zaihuapd · Nov 22, 08:22

**「Background」** During the same period, overall domestic smartphone sales volume declined by about 9.2%, while market concentration increased as only Huawei and Apple achieved positive year-over-year share growth.

**Tags**: `#smartphone market`, `#market share`, `#Huawei`, `#Apple`, `#consumer electronics`

---