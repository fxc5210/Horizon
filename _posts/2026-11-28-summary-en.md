---
layout: default
title: "Horizon Summary: 2026-11-28 (EN)"
date: 2026-11-28
lang: en
---

> From 31 items, 19 important content pieces were selected

---

**Technology News**
1. [Linux Kernel NFS Server Vulnerability CVE-2026-99362 Grants Unauthenticated Root](#item-tech-news-1) ⭐️ 9.0/10
2. [Google Research Introduces DeepCrossAttention for Faster Transformers](#item-tech-news-2) ⭐️ 8.0/10
3. [Michael Nielsen Removes Online Book on Neural Networks](#item-tech-news-3) ⭐️ 8.0/10
4. [AWS Trainium3 Inference Microarchitecture and Benchmarking](#item-tech-news-4) ⭐️ 8.0/10
5. [Microsoft Plans to Replace Third-Party Drivers with Built-in Windows Components](#item-tech-news-5) ⭐️ 8.0/10
6. [Examining Soundness Bugs and Reliability in Computer-Checked Proof Systems](#item-tech-news-6) ⭐️ 7.0/10
7. [State Attorneys General Sue SpaceX Over Grok&\#x27;s Generation of Harmful Synthetic Media](#item-tech-news-7) ⭐️ 7.0/10
8. [Credit Card Skimming Scripts Using WebRTC Found on Shopping Sites](#item-tech-news-8) ⭐️ 7.0/10
9. [Convex AI Skill Transmits User App Ideas Without Explicit Notice](#item-tech-news-9) ⭐️ 7.0/10
10. [US Intelligence Agencies Targeted by Hackers Using AI Tool Artex](#item-tech-news-10) ⭐️ 7.0/10
11. [Anthropic Clarifies and Removes Covert Throttling on Frontier Model Research Requests](#item-tech-news-11) ⭐️ 7.0/10
12. [Bouncemarket: A Live Prediction Market Game for a Bouncing Ball](#item-tech-news-12) ⭐️ 6.0/10
13. [Minecraft Bedrock Edition Resource Pack Vulnerability Fixed in Version 26.65](#item-tech-news-13) ⭐️ 6.0/10

**Financial News**
1. [China&\#x27;s State Council Pledges Enhanced Market Support](#item-finance-news-1) ⭐️ 9.0/10
2. [Mixue Bingcheng Invests in DeepSeek Funding Round](#item-finance-news-2) ⭐️ 8.0/10
3. [China&\#x27;s Central Bank Lowers Large Certificate of Deposit Thresholds](#item-finance-news-3) ⭐️ 8.0/10
4. [China Summons 15 Electric Bicycle Makers](#item-finance-news-4) ⭐️ 8.0/10
5. [S&amp;P 500 Enters Correction Territory](#item-finance-news-5) ⭐️ 7.0/10
6. [Nvidia Market Volatility Tests Federal Reserve Policy Focus](#item-finance-news-6) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Linux Kernel NFS Server Vulnerability CVE-2026-99362 Grants Unauthenticated Root](https://opensec.in/blog/nfs2root-cve-2026-99362) ⭐️ 9.0/10

OpenSec disclosed a critical pre-authentication heap overflow vulnerability in the Linux kernel NFS server, tracked as CVE-2026-99362 with a CVSS score of 9.8. Unauthenticated attackers can send a crafted request to TCP port 2049 to achieve remote root access on hosts running Linux 3.16 or later with NFSv4.1 or NFSv4.2 enabled. Patches have been released in kernel versions 6.12.117, 6.18.61, 7.3.2, and 7.4-rc1, requiring a kernel update and system restart.

telegram · zaihuapd · Nov 27, 12:57

**「Background」** The Network File System \(NFS\) server in the Linux kernel handles file sharing across networks and has historically been a critical target for remote attack vectors due to its direct exposure of kernel-level file operations. This specific vulnerability has persisted across kernel releases since version 3.16 was introduced in 2014.

**「Impact」** File servers, NAS devices, and cluster storage nodes utilizing vulnerable kernel versions are at risk of complete remote compromise without authentication. Administrators unable to immediately update their kernels must restrict network access to TCP port 2049 using firewalls as a temporary mitigation.

**Tags**: `#Linux Kernel`, `#Security Vulnerability`, `#NFS`, `#Systems Engineering`, `#Network Security`

---

<a id="item-tech-news-2"></a>
### [Google Research Introduces DeepCrossAttention for Faster Transformers](https://research.google/blog/supercharging-transformer-residual-connections/) ⭐️ 8.0/10

Google Research has introduced DeepCrossAttention, a technique designed to supercharge transformer residual connections and achieve comparable model quality up to three times faster. The approach targets efficiency bottlenecks in standard transformer architectures by optimizing how residual connections handle data flow. The findings are published via Google Research, highlighting potential speedups for training and inference workloads.

hackernews · ComputedCamp995 · Nov 27, 23:06 · [Discussion](https://news.ycombinator.com/item?id=50672565)

**「Background」** Traditional transformer architectures rely on standard sequential residual connections that simply sum the outputs of previous layers, which can sometimes dilute crucial information during deep network training.

**「Community Discussion」** Commenters debated the relationship between the new architecture and existing designs like DenseNet, while others questioned the choice of line graphs in the research presentation due to the lack of a temporal relationship between methods. Additional discussion touched on broader token generation speed improvements from methods like MTP and Dflash.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2502.06785">DeepCrossAttention : Supercharging Transformer Residual ...</a></li>
<li><a href="https://www.alphaxiv.org/overview/2502.06785v1">DeepCrossAttention : Supercharging Transformer Residual ...</a></li>

</ul>
</details>

**Tags**: `#artificial intelligence`, `#machine learning`, `#transformers`, `#hardware optimization`

---

<a id="item-tech-news-3"></a>
### [Michael Nielsen Removes Online Book on Neural Networks](https://neuralnetworksanddeeplearning.com/) ⭐️ 8.0/10

Author and researcher Michael Nielsen has taken down his widely read free online book, Neural Networks and Deep Learning, from his personal website. The removal has sparked discussions across the tech community regarding open education and the trajectory of frontier artificial intelligence development.

hackernews · brandonb · Nov 27, 19:31 · [Discussion](https://news.ycombinator.com/item?id=50670757)

**「Background」** Michael Nielsen&\#x27;s online book has long served as a popular, foundational educational resource for individuals learning the core concepts of neural networks and deep learning.

**「Community Discussion」** Commenters debated whether removing educational materials serves as an effective protest against frontier AI labs or if restricting access hinders public understanding, while others noted that archived versions of the text remain accessible online.

**Tags**: `#artificial intelligence`, `#neural networks`, `#open source`, `#machine learning`, `#industry trends`

---

<a id="item-tech-news-4"></a>
### [AWS Trainium3 Inference Microarchitecture and Benchmarking](https://newsletter.semianalysis.com/p/trainium3-inferencex) ⭐️ 8.0/10

SemiAnalysis published a microarchitectural and cost-performance analysis of AWS Trainium3, showing that Trainium3 and TPUs are now live on the InferenceX benchmarking platform. According to the microbenchmarks and UBenchX suite, Trainium3 achieves peak HBM bandwidth utilization at small message sizes using its Descriptor Generation Engines, an efficiency previously unattainable on NVIDIA GPUs. On production end-to-end agentic inference workloads measured via AgentX, Trainium3 paired with vLLM delivers total cost of ownership performance comparable to or exceeding NVIDIA GB300 accelerators across the interactivity frontier.

rss · Semianalysis · Nov 27, 15:54

**「Background on ML Accelerator Architecture」** Traditional data center GPUs like NVIDIA&\#x27;s evolved from architectures originally designed for pixel shading, gradually incorporating tensor and tile processing units across successive generations. In contrast, specialized AI accelerators such as AWS Trainium are designed from the ground up specifically for machine learning workloads, utilizing tiles as a first-class architectural primitive.

**Tags**: `#Hardware`, `#Artificial Intelligence`, `#Machine Learning`, `#Cloud Computing`

---

<a id="item-tech-news-5"></a>
### [Microsoft Plans to Replace Third-Party Drivers with Built-in Windows Components](https://www.techspot.com/news/114721-microsoft-wants-replace-most-third-party-device-drivers.html) ⭐️ 8.0/10

At Ignite 2026, Microsoft announced plans to replace certain third-party hardware drivers with built-in Windows components to minimize third-party code running in the kernel and enhance system security and reliability. Printers are among the first targets, with the new Windows Ready Print mode replacing legacy third-party printer drivers. Additionally, Windows product manager Mehmet Kucukgoz stated that SoundWire and SDCA audio drivers will soon become built-in Windows components, alongside drivers for I3C buses, USB Ethernet, and MIPI cameras currently in development.

telegram · zaihuapd · Nov 28, 02:09

**「Background」** Operating system kernels traditionally rely on third-party vendors to provide specialized hardware drivers, which can introduce stability and security vulnerabilities when low-level code fails or contains flaws. Microsoft has introduced initiatives like the Driver Quality Initiative \(DQI\) to raise reliability standards and encourage developers to utilize native system capabilities.

**「Impact」** Hardware manufacturers and OEM developers will need to adapt their customization strategies to align with Microsoft&\#x27;s shift toward native drivers for standard hardware classes like audio, printing, and buses.

**Tags**: `#Operating Systems`, `#Windows`, `#Kernel Security`, `#Hardware Drivers`

---

<a id="item-tech-news-6"></a>
### [Examining Soundness Bugs and Reliability in Computer-Checked Proof Systems](https://cr.yp.to/proofs/falseccp.html) ⭐️ 7.0/10

An analysis explores soundness bugs and reliability issues within computer-checked proof systems, detailing past flaws discovered in automated verification tooling. The findings highlight that while individual verifiers have occasionally contained critical bugs, practical exploitation often requires multiple compounding flaws across independent systems.

hackernews · \_tk\_ · Nov 27, 15:26 · [Discussion](https://news.ycombinator.com/item?id=50667989)

**「Background」** Computer-checked proofs and formal verification tools use automated logic engines to mathematically guarantee software and mathematical theorem correctness. Ensuring the absolute soundness of these proof assistants remains a core challenge in computer science.

**「Impact」** Developers and researchers relying on formal verification must account for potential soundness vulnerabilities in single-checker setups. Projects requiring strict reliability increasingly adopt multi-verifier pipelines to mitigate the risk of hidden implementation bugs.

**「Community Discussion」** Commenters noted that while soundness bugs do exist, successfully misleading users typically requires simultaneous bugs across multiple independent verifiers written in different programming languages. Others pointed out that historical bugs are extremely rare relative to the decades of use, though specification mismatch remains a distinct risk when verifying complex systems.

**Tags**: `#formal verification`, `#software engineering`, `#computer systems`, `#open source`

---

<a id="item-tech-news-7"></a>
### [State Attorneys General Sue SpaceX Over Grok&\#x27;s Generation of Harmful Synthetic Media](https://www.oag.state.va.us/media-center/news-releases/jay-jones/3162-attorneys-general-jones-and-rayfield-file-suit-against-spacex-parent-company-of-x-xai-and-grok-over-creation-and-promotion-of-child-exploitation-and-non-consensual-images-on-platform) ⭐️ 7.0/10

State attorneys general have filed a lawsuit against SpaceX, the parent company of X and xAI, targeting the creation and promotion of child exploitation and non-consensual intimate images generated by the Grok AI system. The legal action addresses platform safety and moderation failures regarding harmful synthetic media. The lawsuit demands accountability from the corporate parent for content produced and shared across its platforms.

hackernews · DeepLogin · Nov 27, 19:42 · [Discussion](https://news.ycombinator.com/item?id=50670855)

**「Background」** Regulatory scrutiny has intensified around generative artificial intelligence models as tools increasingly become capable of producing photorealistic synthetic media, including child sexual abuse material and non-consensual intimate images.

**「Community Discussion」** Commenters debated the mechanisms behind the tool&\#x27;s output, questioning whether users needed to bypass specific guardrails to generate such content, while also discussing the legal and personal liability of the individuals producing the material versus the platform hosting it.

**Tags**: `#artificial intelligence`, `#ai safety`, `#legal/regulation`, `#ethics`, `#xai`

---

<a id="item-tech-news-8"></a>
### [Credit Card Skimming Scripts Using WebRTC Found on Shopping Sites](https://www.infohawk.com/news/2026-11-27-black-friday-webrtc-skimmer) ⭐️ 7.0/10

Security researchers uncovered credit card skimming scripts deployed on popular e-commerce sites that use WebRTC to exfiltrate payment data. The technique targets mobile devices specifically and aims to bypass standard network detection mechanisms by leveraging less-monitored channels.

hackernews · scanr · Nov 27, 15:40 · [Discussion](https://news.ycombinator.com/item?id=50668145)

**「Background」** WebRTC is a standard enabling peer-to-peer real-time communication of audio, video, and arbitrary data within web browsers without requiring intermediate servers.

**「Impact」** E-commerce operators and users face heightened risks of payment data theft that evade conventional network monitoring tools, reinforcing the vulnerability of embedding untrusted third-party scripts.

**「Community Discussion」** Commenters noted that WebRTC is used here primarily to evade monitoring rather than for unique technical capabilities, emphasizing that running untrusted third-party scripts inherently exposes sites to vulnerabilities. Others debated foundational web architecture issues, arguing that browsers executing arbitrary server-side code remain a core security flaw.

**Tags**: `#Cybersecurity`, `#WebRTC`, `#E-commerce`, `#JavaScript Security`

---

<a id="item-tech-news-9"></a>
### [Convex AI Skill Transmits User App Ideas Without Explicit Notice](https://github.com/convex/convex-backend-skill/issues/64) ⭐️ 7.0/10

A GitHub issue revealed that the Convex AI skill transmits user app ideas to a remote server without explicit notification. The company&\#x27;s CEO responded that the prompt upload powers the Convex quickstart feature, which succeeds the shut-down Convex Chef project.

hackernews · MickyTheMouse · Nov 27, 18:02 · [Discussion](https://news.ycombinator.com/item?id=50669765)

**「Background」** AI coding assistants and development plugins frequently integrate remote endpoints or gateways to process user prompts and generate project scaffolding. This architecture often blurs the line between local development actions and cloud data transmission.

**「Impact」** Developers using the Convex AI skill should review their data privacy preferences and be aware that prompts detailing proprietary app ideas are sent to remote servers.

**「Community Discussion」** Commenters emphasized that maintaining developer trust is paramount when handling data through AI plugins, while the company&\#x27;s CEO clarified the intended functionality behind the feature.

**Tags**: `#artificial intelligence`, `#developer tools`, `#privacy`, `#software engineering`, `#open source`

---

<a id="item-tech-news-10"></a>
### [US Intelligence Agencies Targeted by Hackers Using AI Tool Artex](https://www.forbes.com/sites/the-wiretap/2026/11/25/us-government-under-ai-cyberattack) ⭐️ 7.0/10

U.S. intelligence agencies, including the CIA, National Geospatial-Intelligence Agency, and the Office of the Director of National Intelligence, were targeted by hackers using an AI tool named Artex to probe network defenses. The breach affected non-classified reconnaissance data and was described as not severe. Artex integrates multiple open-source AI models to test defenses and was originally released by a Chinese developer on GitHub before being deleted.

telegram · zaihuapd · Nov 27, 10:42

**「Background」** Federal law enforcement agencies, including the FBI, previously warned earlier this year that cybercriminals and spies were widely adopting specialized AI tools like Artex to assist with network targeting and cyberattacks.

**「Impact」** Federal agencies must reassess their exposure to automated, AI-driven reconnaissance tools used by malicious actors against non-classified perimeter systems.

**Tags**: `#artificial intelligence`, `#cybersecurity`, `#government`, `#threat intelligence`

---

<a id="item-tech-news-11"></a>
### [Anthropic Clarifies and Removes Covert Throttling on Frontier Model Research Requests](https://news.ycombinator.com/item?id=50664325) ⭐️ 7.0/10

Anthropic clarified that an earlier practice of covertly restricting frontier AI model research requests using prompt rewrites, guidance vectors, and parameter-efficient fine-tuning—affecting approximately 0.03% of traffic under June&\#x27;s Fable 5 system cards—was an error that was reversed on June 10. The company stated that current requests of this nature are now explicitly refused or fallback with a user notification rather than being silently degraded. Additionally, Anthropic attributed some ongoing user reports to excessive caution where Claude models become overly fixated on self-imposed rules during long-running tasks.

telegram · zaihuapd · Nov 27, 13:42

**「Background」** AI labs typically enforce terms of service restricting users from leveraging frontier models to develop competing models or conduct autonomous AI research. System cards document these model safety boundaries, behavioral profiles, and operational mitigations introduced during deployment.

**「Impact」** Developers attempting to use Claude for frontier model research will now encounter explicit refusals or fallbacks with notifications instead of silent performance degradation, providing clearer feedback on service terms boundaries.

**Tags**: `#Artificial Intelligence`, `#Anthropic`, `#AI Safety`, `#Machine Learning`

---

<a id="item-tech-news-12"></a>
### [Bouncemarket: A Live Prediction Market Game for a Bouncing Ball](https://bouncemarket.minhanhday.com/) ⭐️ 6.0/10

Developer mday404 launched bouncemarket, a live prediction market game where players trade shares on the landing spot of a server-simulated bouncing ball. The drop is simulated server-side and streamed to clients using server-sent events with a small buffer. Each round is deterministic from its starting position, and AI traders participate with naive rule sets until more than five human players join a round.

hackernews · mday404 · Nov 27, 15:01 · [Discussion](https://news.ycombinator.com/item?id=50667726)

**「Background」** Prediction markets allow participants to buy and sell shares based on the outcome of future events, aggregating dispersed information into market probabilities. Server-sent events provide a lightweight mechanism for servers to push real-time updates over HTTP to web clients.

**「Impact」** Players report that the rapid movement of the ball makes timely betting difficult, and some note that buying cheap shares across multiple outcomes can yield a guaranteed win when odds fluctuate wildly.

**「Community Discussion」** Commenters debated the game&\#x27;s mechanics, noting that the fast-paced drop causes odds to jump dramatically in fractions of a second. Others observed that frontier AI models could potentially be instructed to build exact physical solvers to predict outcomes, turning the game into an automated bot battle.

**Tags**: `#prediction markets`, `#physics simulation`, `#web development`, `#game design`

---

<a id="item-tech-news-13"></a>
### [Minecraft Bedrock Edition Resource Pack Vulnerability Fixed in Version 26.65](https://www.zaikei.co.jp/article/20261119/878386.html) ⭐️ 6.0/10

A security vulnerability affecting Minecraft Bedrock Edition versions 26.52 through 26.63 allowed malicious resource packs containing a content.zipe file to modify Ore UI elements and execute hidden scripts. Players joining servers or Realms with automatic resource pack downloads enabled could receive the files without manual installation, exposing PC, mobile, and console users to risks such as save deletion, IP address exposure, and arbitrary URI launching on Windows. Mojang addressed this issue by releasing version 26.65, which fixes the vulnerability.

telegram · zaihuapd · Nov 27, 18:04

**「Background」** Minecraft Bedrock Edition supports cross-platform gameplay and allows servers to automatically distribute custom resource packs and add-ons to connecting players to customize textures, user interfaces, and behavior.

**「Impact」** Bedrock Edition players and server operators should immediately update their game clients to version 26.65 or later to prevent malicious resource packs from executing unauthorized scripts and accessing local systems.

**Tags**: `#Minecraft`, `#Security Vulnerability`, `#Game Development`, `#Remote Code Execution`

---

## Financial News

<a id="item-finance-news-1"></a>
### [China&\#x27;s State Council Pledges Enhanced Market Support](https://www.tmtpost.com/nictation/8220182.html) ⭐️ 9.0/10

At a November 27 executive meeting, China&\#x27;s State Council pledged to strengthen market-stabilizing mechanisms by optimizing Central Huijin&\#x27;s quasi-stabilization fund function to provide adequate liquidity and by encouraging long-term institutional investment.

telegram · zaihuapd · Nov 27, 05:35

**「Background」** The State Council frequently uses executive meetings to coordinate economic policy, guide state-backed financial entities, and regulate domestic capital markets.

**Tags**: `#monetary policy`, `#capital markets`, `#economic regulation`, `#government policy`

---

<a id="item-finance-news-2"></a>
### [Mixue Bingcheng Invests in DeepSeek Funding Round](https://m.sohu.com/a/1107027659_115479) ⭐️ 8.0/10

Tea drink chain Mixue Bingcheng has invested 500 million CNY in artificial intelligence company DeepSeek&\#x27;s new funding round, which raised between 100 billion and 105.5 billion CNY and resulted in a post-money valuation of approximately 615.5 billion CNY.

telegram · zaihuapd · Nov 27, 06:33

**「Background」** Mixue Bingcheng reported an operating revenue of 33.56 billion CNY and a net profit attributable to shareholders of approximately 5.89 billion CNY for the year 2025.

**「Impact」** The involvement of consumer brands and major technology corporations in this financing round highlights the broadening commercial backing for artificial intelligence development.

**Tags**: `#Artificial Intelligence`, `#Venture Capital`, `#Corporate Investment`, `#DeepSeek`

---

<a id="item-finance-news-3"></a>
### [China&\#x27;s Central Bank Lowers Large Certificate of Deposit Thresholds](https://www.news.cn/fortune/20261127/70789d77822242cc82216f51a416f872/c.html) ⭐️ 8.0/10

The People&\#x27;s Bank of China announced new regulations on November 27, 2026, lowering the personal minimum purchase threshold for large certificates of deposit to 100,000 yuan and the institutional threshold to 5 million yuan, effective March 21, 2027.

telegram · zaihuapd · Nov 27, 11:36

**「Background」** Previously, the provisional rules set in 2015 required a minimum purchase of 200,000 yuan for individuals and 10 million yuan for institutions, which these new regulations replace.

**「Impact」** Individual investors with smaller savings can now access large certificates of deposit, while banks must independently set their deposit and loan rates without resorting to high-interest deposit-chasing tactics.

**Tags**: `#Central Bank`, `#Monetary Policy`, `#Banking`, `#Interest Rates`, `#Regulation`

---

<a id="item-finance-news-4"></a>
### [China Summons 15 Electric Bicycle Makers](https://www.news.cn/20261127/0c8c665ce70c417b9263b39fa8a519f0/c.html?hl=zh-CN) ⭐️ 8.0/10

On November 27, 2026, China&\#x27;s State Administration for Market Regulation collectively summoned 15 electric bicycle enterprises, including Yadea, Tailing, Aima, Ninebot, and Niu, ordering strict rectifications and product recalls following quality compliance violations found during inspections.

telegram · zaihuapd · Nov 27, 12:06

**「Background」** Recent flying inspections by regulatory authorities acting under the China Compulsory Certification \(CCC\) system uncovered that several manufacturers lacked adequate quality assurance, failed to control product consistency, and sold non-compliant goods that violated mandatory national standards.

**「Impact」** Electric bicycle manufacturers in China must overhaul their compliance and quality control processes to prevent substandard vehicles from entering the market and to properly handle consumer recalls.

**Tags**: `#Regulation`, `#Electric Vehicles`, `#Compliance`, `#Consumer Rights`, `#China Market`

---

<a id="item-finance-news-5"></a>
### [S&amp;P 500 Enters Correction Territory](https://www.cnbc.com/2026/11/27/the-sp-500-is-in-a-correction-bear-markets-and-recessions-dont-always-follow.html) ⭐️ 7.0/10

The S&amp;P 500 index fell 11.6% to close at 6,910.39 on Nov. 20, 2026, marking its first correction—defined as a 10% drop from a recent high—since April 2025, according to CNBC reporting.

rss · CNBC Finance · Nov 27, 13:21

**「Historical Context」** A market correction is a drop of at least 10% from a recent peak, while a bear market is a decline of 20% or more, though historical data shows neither automatically signals an economic recession.

**「Investor Impact」** Equity investors experienced seven consecutive days of declines driven by concerns over artificial intelligence spending, mega-cap tech valuations, and Federal Reserve interest rate policy.

**Tags**: `#S&amp;P 500`, `#Market Correction`, `#Federal Reserve`, `#Recession`, `#Equities`

---

<a id="item-finance-news-6"></a>
### [Nvidia Market Volatility Tests Federal Reserve Policy Focus](https://www.cnbc.com/2026/11/25/nvidia-kevin-warsh-fed-market-signals.html) ⭐️ 7.0/10

Recent extreme volatility in Nvidia stock and financial markets is testing Federal Reserve Chairman Kevin Warsh&\#x27;s policy approach of relying heavily on market indicators while looking past short-term daily noise.

rss · CNBC Finance · Nov 27, 13:29

**「Background」** Federal Reserve Chairman Kevin Warsh favors using market expectations rather than traditional economic forecasts and forward guidance to guide monetary policy.

**Tags**: `#Federal Reserve`, `#Monetary Policy`, `#Financial Markets`, `#Interest Rates`, `#Kevin Warsh`

---