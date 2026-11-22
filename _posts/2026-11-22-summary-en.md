---
layout: default
title: "Horizon Summary: 2026-11-22 (EN)"
date: 2026-11-22
lang: en
---

> From 23 items, 9 important content pieces were selected

---

**Technology News**
1. [Riemann Hypothesis Proof Formally Verified in Lean](#item-tech-news-1) ⭐️ 10.0/10
2. [Reflecting on Architectural Lessons and Design Challenges for Rust GUIs](#item-tech-news-2) ⭐️ 8.0/10
3. [Tesla Rolls Out FSD v15 Internationally](#item-tech-news-3) ⭐️ 7.0/10
4. [Debugging a Monitor USB Hub That Throttled Ethernet Download Speeds](#item-tech-news-4) ⭐️ 6.0/10
5. [China&\#x27;s National Data Bureau to Establish Token Metering and Quality Standards](#item-tech-news-5) ⭐️ 6.0/10
6. [Google Gemini Separates Chat History from Model Training Data Settings](#item-tech-news-6) ⭐️ 6.0/10
7. [Financial Times Reports Alleged Nvidia Chip Smuggling Network Involving Cambodia&\#x27;s Prince Group](#item-tech-news-7) ⭐️ 6.0/10

**Financial News**
1. [China Objects to US Telecom Number Restrictions](#item-finance-news-1) ⭐️ 7.0/10
2. [Huawei Leads Domestic Smartphone Market in First Three Quarters of 2026](#item-finance-news-2) ⭐️ 6.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Riemann Hypothesis Proof Formally Verified in Lean](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/) ⭐️ 10.0/10

On November 20, 2026, Levent Alpöge published a formal verification of a proof for the Riemann Hypothesis consisting of approximately 17 million lines of Lean code. On November 21, the Lean FRO and Mathlib Initiative jointly announced that the theorem and its proof were verified as correct. The community confirmed that the proposition matches Mathlib&\#x27;s RiemannHypothesis definition, the codebase compiles without errors, and multiple independent proof checkers validated its validity.

telegram · zaihuapd · Nov 21, 16:48

**「Background」** The Riemann Hypothesis is a famous unproven mathematical conjecture concerning the zeros of the Riemann zeta function, with profound implications for number theory. The Lean theorem prover is an interactive proof assistant used to check mathematical proofs with machine-checked rigor.

**「Impact」** Mathematicians and developers working with formal verification can utilize the newly validated Mathlib-compatible codebase as a benchmark for large-scale mechanized mathematics and automated reasoning.

**「Community Discussion」** Commenters debated the reliability of independent proof checkers and the role of AI models like Claude in formalizing massive amounts of modern mathematics, while crediting human expertise for guiding the process.

**Tags**: `#mathematics`, `#formal verification`, `#lean`, `#riemann hypothesis`

---

<a id="item-tech-news-2"></a>
### [Reflecting on Architectural Lessons and Design Challenges for Rust GUIs](https://linebender.org/blog/next-100-guis/) ⭐️ 8.0/10

Raph Levien reflects on the extensive design challenges and architectural lessons learned from developing numerous Rust GUI frameworks. The analysis addresses recurring hurdles in building high-performance, responsive graphical interfaces within the Rust ecosystem.

hackernews · raphlinus · Nov 21, 21:17 · [Discussion](https://news.ycombinator.com/item?id=50593737)

**「Background」** This analysis follows up on an earlier essay published roughly 4.5 years ago titled &quot;Advice for the next dozen Rust GUIs,&quot; reflecting on years of subsequent ecosystem development and dozens of newly announced toolkits.

**「Community Discussion」** Commenters discussed alternative frameworks like Slint and inquired about UI libraries inspired by Unreal Engine&\#x27;s Slate architecture. Others highlighted newer projects like Native Shell while noting the immense difficulty and slow pace of implementing foundational GUI details like text selection and wrapping from scratch in Rust.

<details><summary>References</summary>
<ul>
<li><a href="https://linebender.org/blog/next-100-guis/">Advice for the next 100 Rust GUIs - Linebender</a></li>

</ul>
</details>

**Tags**: `#Rust`, `#GUI`, `#Software Architecture`, `#Open Source`

---

<a id="item-tech-news-3"></a>
### [Tesla Rolls Out FSD v15 Internationally](https://x.com/Tesla/status/2124222447855743019) ⭐️ 7.0/10

Tesla has begun rolling out FSD v15 internationally, introducing a 25x improvement in handling safety-critical scenarios. The update features a new &quot;Tesla Reality View&quot; visualization interface that overlays camera feeds and driving paths on the infotainment screen with multiple view options. It also brings navigation enhancements, softer turn signal chimes, and optimized driving comfort for potholes, road debris, school zones, and severe weather.

telegram · zaihuapd · Nov 22, 00:03

**「Background」** Tesla&\#x27;s Full Self-Driving \(FSD\) software is an advanced driver-assistance system that receives regular over-the-air updates to improve its neural network-based autonomous driving capabilities and visualization interfaces.

**「Impact」** Drivers receiving the FSD v15 update will experience altered visual feedback via the new overlay interface alongside adjusted navigation cues and smoother handling in complex road and weather conditions.

**Tags**: `#artificial intelligence`, `#autonomous driving`, `#tesla`, `#machine learning`, `#computer systems`

---

<a id="item-tech-news-4"></a>
### [Debugging a Monitor USB Hub That Throttled Ethernet Download Speeds](https://blog.tymscar.com/posts/studiodisplayethernet/) ⭐️ 6.0/10

A developer discovered that routing an Ethernet connection through a monitor&\#x27;s built-in USB hub throttled download speeds by 75% due to high acknowledgment latency. The added latency prevented the laptop from acknowledging packets quickly enough, causing the Ethernet adapter&\#x27;s buffer to fill and drop packets. Replacing the adapter with one that required less frequent acknowledgments ultimately resolved the throughput degradation.

hackernews · soheilpro · Nov 21, 10:36 · [Discussion](https://news.ycombinator.com/item?id=50587875)

**「Background」** Monitors and docking stations with integrated USB hubs often include Ethernet adapters, routing network traffic through the USB controller alongside display and peripheral data.

**「Impact」** Developers and users routing high-speed wired internet through monitors or certain USB-C docks may experience severe TCP throughput drops, which can be mitigated by changing adapters or adjusting flow control settings.

**「Community Discussion」** Commenters noted that the issue stems primarily from the USB network switch and packet acknowledgment behavior rather than the monitor itself, with others reporting similar unresolved struggles using Thunderbolt docks.

**Tags**: `#networking`, `#hardware`, `#troubleshooting`, `#usb`

---

<a id="item-tech-news-5"></a>
### [China&\#x27;s National Data Bureau to Establish Token Metering and Quality Standards](https://www.cls.cn/detail/2540805) ⭐️ 6.0/10

China&\#x27;s National Data Bureau announced plans to develop standardized frameworks for token metering, billing, and quality evaluation. Speaking at the 2026 World Computing Conference in Changsha on November 20, 2026, Bureau Director Liu Liehong stated that these measures aim to prevent low-quality and redundant construction as token production services evolve to integrate computing power, models, and data.

telegram · zaihuapd · Nov 21, 10:19

**「Background」** Tokens serve as the fundamental unit of processing and billing for modern large language models, connecting underlying computing infrastructure to end-user applications. As artificial intelligence adoption grows, managing the economic and operational aspects of token consumption has become a key focus for industry resource allocation.

**「Impact」** AI service providers and computing infrastructure operators in China will need to align with future national standards for token billing and quality evaluation once formalized, affecting commercial pricing models and service delivery compliance.

**Tags**: `#artificial intelligence`, `#data governance`, `#standards`, `#ai economics`

---

<a id="item-tech-news-6"></a>
### [Google Gemini Separates Chat History from Model Training Data Settings](https://blog.google/innovation-and-ai/products/gemini-app/updated-controls/) ⭐️ 6.0/10

Google is updating Gemini app settings over the coming weeks to decouple chat history retention from model training data collection. Users will be given two distinct controls to separately manage how long their history is saved and whether their conversations and attachments are used to train generative AI models. When the change rolls out, the new settings will initially reflect the state of the previous single toggle.

telegram · zaihuapd · Nov 22, 01:24

**「Background」** Previously, Gemini applications used a single &\#x27;Gemini Apps Activity&\#x27; setting that bundled chat history preservation and model training together, meaning users had to disable history if they wanted to opt out of contributing their data to training.

**「Impact」** Gemini users who previously kept their history disabled solely to prevent data collection can now maintain their chat archives while opting out of model training.

**Tags**: `#Google Gemini`, `#Artificial Intelligence`, `#Privacy`, `#Machine Learning`

---

<a id="item-tech-news-7"></a>
### [Financial Times Reports Alleged Nvidia Chip Smuggling Network Involving Cambodia&\#x27;s Prince Group](https://www.ft.com/content/f3ad8a81-3890-4a8a-8853-ff0a94b08ba9?syn-25a6b1a6=1) ⭐️ 6.0/10

According to the Financial Times, individuals linked to Cambodia&\#x27;s Prince Group—including designated figure Hu Xiaowei—are allegedly involved in smuggling restricted Nvidia chips into China. Trade data cited in the report shows that a Malaysia-based subsidiary of Megaspeed declared approximately $4.6 billion in imported goods between December 2024 and December 2025, with a portion of the chips reportedly entering the Chinese black market through shell companies, private networks, and private jets. The Prince Group has denied the allegations, stating that the claims regarding illicit networks, private jet smuggling, and Hu&\#x27;s employment lack factual basis.

telegram · zaihuapd · Nov 22, 04:34

**「Background」** The United States has implemented strict export controls and trade restrictions on high-end Nvidia artificial intelligence hardware to prevent advanced computing technologies from reaching Chinese markets.

**「Impact」** The allegations expose potential vulnerabilities and illicit logistics routes in regional supply chains, which may prompt increased regulatory scrutiny and tighter enforcement of export controls on high-performance semiconductors passing through Southeast Asian intermediaries.

**Tags**: `#Nvidia`, `#Hardware`, `#Supply Chain`, `#Geopolitics`, `#Artificial Intelligence`

---

## Financial News

<a id="item-finance-news-1"></a>
### [China Objects to US Telecom Number Restrictions](https://www.bloomberg.com/news/articles/2026-11-22/china-objects-to-us-curbs-on-telecoms-access-to-phone-numbers) ⭐️ 7.0/10

On November 22, 2026, China&\#x27;s Ministry of Commerce urged the United States to rescind a Federal Communications Commission \(FCC\) restriction implemented on November 19, 2026, that blocks major Chinese telecommunications operators from accessing US phone number resources.

telegram · zaihuapd · Nov 22, 06:44

**「Background」** The US Federal Communications Commission \(FCC\) is an independent US government agency that regulates interstate and international communications, and it introduced new national security certifications to restrict entities on its Covered List from accessing US networks.

**Tags**: `#Telecommunications`, `#US-China Relations`, `#Regulatory Policy`, `#National Security`

---

<a id="item-finance-news-2"></a>
### [Huawei Leads Domestic Smartphone Market in First Three Quarters of 2026](https://weibo.com/1642634100/RsyNmsLgF) ⭐️ 6.0/10

Data published by blogger @RD 观测 on November 22, 2026, shows that Huawei led the domestic smartphone market with a 20.25% share in terms of sales volume for the first three quarters of 2026, up 3.92 percentage points from 16.33% in the same period last year, while the overall market declined by approximately 9.2%.

telegram · zaihuapd · Nov 22, 08:22

**「Background」** During the same period, Apple was the only other major brand to achieve positive growth, rising to 17.44% from 14.21% last year, while competitors such as OPPO, vivo,小米, and Honor experienced year-over-year declines.

**「Impact」** The market concentration has intensified as major brands Huawei and Apple capture nearly 37.7% of the total domestic sales volume, squeezing the combined share of smaller brands down to 4.30%.

**Tags**: `#smartphone market`, `#Huawei`, `#Apple`, `#market share`, `#consumer electronics`

---