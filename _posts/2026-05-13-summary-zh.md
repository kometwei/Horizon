---
layout: default
title: "Horizon Summary: 2026-05-13 (ZH)"
date: 2026-05-13
lang: zh
---

> From 130 items, 21 important content pieces were selected

---

1. [dnsmasq 发布六个严重 CVE](#item-1) ⭐️ 9.0/10
2. [加拿大 C-22 法案复活监控与加密后门](#item-2) ⭐️ 9.0/10
3. [社区分支恢复 Bambu 打印机的本地网络支持](#item-3) ⭐️ 8.0/10
4. [Needle：2600 万参数工具调用模型可在手机上运行](#item-4) ⭐️ 8.0/10
5. [DuckDB 推出 Quack 客户端-服务器协议](#item-5) ⭐️ 8.0/10
6. [Obsidian 推出新插件审核系统](#item-6) ⭐️ 8.0/10
7. [谷歌与 SpaceX 联手推进太空数据中心](#item-7) ⭐️ 8.0/10
8. [中国电信实现 40Tbps 量子-经典空芯共纤传输创纪录](#item-8) ⭐️ 8.0/10
9. [开源作者呼吁验证软件供应链](#item-9) ⭐️ 8.0/10
10. [谷歌在 Next '26 大会上宣布 GKE Agent Sandbox 和 Hypercluster](#item-10) ⭐️ 8.0/10
11. [谷歌发布新一代 TPU，专为智能体和 SOTA 模型训练设计](#item-11) ⭐️ 8.0/10
12. [攻击者通过 Flippa 购买 30 个 WordPress 插件并植入后门](#item-12) ⭐️ 8.0/10
13. [中国开放 AI 生态系统的优势不断累积](#item-13) ⭐️ 8.0/10
14. [FDA 局长因特朗普政府强制批准果味电子烟辞职](#item-14) ⭐️ 8.0/10
15. [双胞胎兄弟被解雇后删除 96 个政府数据库](#item-15) ⭐️ 8.0/10
16. [青少年因 ChatGPT 药物建议死亡，诉讼指控](#item-16) ⭐️ 8.0/10
17. [Redis 与野心的代价](#item-17) ⭐️ 8.0/10
18. [Rockstar 如何将一座城市塞进 PS2 内存](#item-18) ⭐️ 8.0/10
19. [Go 库 fsnotify 因维护者变更引发供应链安全担忧](#item-19) ⭐️ 8.0/10
20. [安卓 VPN 绕过漏洞导致用户流量泄露](#item-20) ⭐️ 8.0/10
21. [Trail of Bits 分支 Go 工具链以增强模糊测试](#item-21) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [dnsmasq 发布六个严重 CVE](https://lists.thekelleys.org.uk/pipermail/dnsmasq-discuss/2026q2/018471.html) ⭐️ 9.0/10

CERT 发布了六个针对 dnsmasq 的严重安全漏洞 CVE，包括通过畸形 DNS 查询或 DHCP 请求实现远程代码执行和拒绝服务。 dnsmasq 广泛用于路由器、物联网设备和 Linux 发行版，这些漏洞对数百万设备构成重大风险。此事件也重新引发了关于为关键网络服务采用 Rust 或 Go 等内存安全语言的讨论。 这些漏洞包括堆越界写入和导致 dnsmasq 停止响应的无限循环。社区批评 Debian 将补丁回溯到旧版本，而不是升级到最新版本。

hackernews · Lobsters · May 12, 18:12 · [社区讨论](https://news.ycombinator.com/item?id=48112042)

**背景**: dnsmasq 是一个轻量级 DNS 转发器和 DHCP 服务器，常用于小型网络、家用路由器和嵌入式设备。它使用 C 语言编写，这是一种内存不安全的语言，容易导致内存损坏漏洞。Rust 和 Go 等内存安全语言通过设计防止此类漏洞，从而减少攻击面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dnsmasq">Dnsmasq</a></li>
<li><a href="https://www.memorysafety.org/docs/memory-safety/">What is memory safety and why does it matter? - Prossimo</a></li>
<li><a href="https://en.wikipedia.org/wiki/Common_Vulnerabilities_and_Exposures">Common Vulnerabilities and Exposures - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论强调了修补的紧迫性，有人呼吁用内存安全语言重写。一位用户推广 MaraDNS 作为更安全的替代方案，另一位批评 Debian 懒惰的回溯做法。据报道 OpenWRT 正在修复。

**标签**: `#security`, `#dnsmasq`, `#CVE`, `#memory safety`, `#open source`

---

<a id="item-2"></a>
## [加拿大 C-22 法案复活监控与加密后门](https://www.eff.org/deeplinks/2026/05/canadas-bill-c-22-repackaged-version-last-years-surveillance-nightmare) ⭐️ 9.0/10

电子前哨基金会（EFF）报告称，加拿大 C-22 法案重新引入强制数据留存和加密后门要求，威胁加密服务与用户隐私。 若通过，C-22 法案可能迫使 Signal、WhatsApp 等加密通讯服务封锁加拿大用户或削弱其安全性，为民主国家的政府监控树立危险先例。 该法案既包括对互联网服务提供商的强制数据留存要求，也包括加密后门要求，批评者称这将破坏端到端加密并助长大规模监控。

hackernews · Brajeshwar · May 12, 17:35 · [社区讨论](https://news.ycombinator.com/item?id=48111531)

**背景**: 强制数据留存法律要求互联网服务提供商存储用户元数据以供政府访问，而加密后门则为执法部门提供对加密通信的特殊访问权限。这两项措施均遭到隐私倡导者和技术专家的广泛批评，认为它们会削弱安全性并导致滥用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.internetsociety.org/blog/2025/05/what-is-an-encryption-backdoor/">What Is an Encryption Backdoor? - Internet Society</a></li>
<li><a href="https://www.accessnow.org/mo-data-mo-problems/">Mo’ data , mo’ problems: Data retention rears ugly head... - Access Now</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了强烈反对，用户警告加密服务将封锁加拿大人，并呼吁采取行动反对该法案。一些人认为该立法是一个警钟，可能推动抗审查工具的创新，而另一些人则对类似法案的反复提出感到遗憾。

**标签**: `#surveillance`, `#encryption`, `#privacy`, `#Canada`, `#digital rights`

---

<a id="item-3"></a>
## [社区分支恢复 Bambu 打印机的本地网络支持](https://github.com/FULU-Foundation/OrcaSlicer-bambulab) ⭐️ 8.0/10

FULU 基金会下的一个 OrcaSlicer 社区分支恢复了 Bambu Lab 打印机的完整 BambuNetwork 支持，以对抗 Bambu 近期强制云端认证的固件更新。 该分支保留了 Bambu Lab 打印机用户的本地控制和离线打印能力，回应了 3D 打印社区对供应商锁定和数据隐私的担忧。 该分支基于 Bambu 认证变更前的 OrcaSlicer 状态，通过恢复与打印机的直接本地网络通信来绕过新的纯云端模式。

hackernews · Murfalo · May 12, 21:55 · [社区讨论](https://news.ycombinator.com/item?id=48115127)

**背景**: OrcaSlicer 是一款流行的开源 3D 打印切片软件。Bambu Lab 近期发布了固件更新，要求某些操作必须进行云端认证，从而阻止第三方工具本地访问打印机。此举引发了社区反弹，促成了这个分支。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hackaday.com/2025/01/17/new-bambu-lab-firmware-update-adds-mandatory-authorization-control-system/">New Bambu Lab Firmware Update Adds Mandatory Authorization ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了复杂情绪：一些人称赞该分支恢复了本地控制，而另一些人则批评 Bambu 的动机并质疑分支的长期可行性。像 bri3d 这样的技术用户提供了对 Bambu 认证变更的详细分析。

**标签**: `#3D printing`, `#open source`, `#Bambu Lab`, `#OrcaSlicer`, `#cloud vs local`

---

<a id="item-4"></a>
## [Needle：2600 万参数工具调用模型可在手机上运行](https://github.com/cactus-compute/needle) ⭐️ 8.0/10

Cactus 开源了 Needle，一个 2600 万参数的工具调用模型，在消费级设备上实现 6000 tok/s 预填充和 1200 tok/s 解码速度，采用无 MLP 的简单注意力网络架构。 这挑战了工具调用需要大模型的假设，使得代理式 AI 在廉价手机、可穿戴设备等边缘设备上成为可能，有望扩大 AI 代理的适用范围。 该模型在 200B 令牌上预训练，并在 Gemini 生成的 2B 令牌合成函数调用数据上后训练。它在单次函数调用上优于 FunctionGemma-270M、Qwen-0.6B 等模型，但缺乏对话能力。

hackernews · HenryNdubuaku · May 12, 18:03 · [社区讨论](https://news.ycombinator.com/item?id=48111896)

**背景**: 工具调用是 AI 模型根据用户查询调用外部函数或 API 的能力。传统方法依赖大参数语言模型，但 Needle 将工具调用视为检索与组装而非推理，使用交叉注意力将查询匹配到工具名称并提取参数。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/cactus-compute/needle">26m function call model that runs on incredibly small devices</a></li>
<li><a href="https://news.ycombinator.com/item?id=48111896">Show HN: Needle: We Distilled Gemini Tool Calling into a 26M ...</a></li>
<li><a href="https://github.com/cactus-compute/needle/blob/main/docs/simple_attention_networks.md">needle/docs/ simple _ attention _ networks .md at main...</a></li>

</ul>
</details>

**社区讨论**: 评论者对模型在复杂工具使用中的判别能力表示兴趣，并建议发布实时演示。有人指出构建具有自然语言解析的命令行工具的潜力，也有人质疑参数表示法的细微差别（26M 与 0.026B）。

**标签**: `#tool calling`, `#small language models`, `#efficient inference`, `#open source`, `#agentic AI`

---

<a id="item-5"></a>
## [DuckDB 推出 Quack 客户端-服务器协议](https://duckdb.org/2026/05/12/quack-remote-protocol) ⭐️ 8.0/10

DuckDB 推出了名为 'Quack' 的客户端-服务器协议，该协议允许 DuckDB 实例之间相互通信，实现了水平扩展和远程查询执行，并支持多个并发写入者。 这解决了 DuckDB 嵌入式特性的一个关键限制，使其适用于多用户、基于服务器的分析工作负载，并扩展了其在数据工程和内部分析中的用例。 Quack 基于成熟技术构建，设计简单易用，秉承 DuckDB 的精神。它支持具有多个并发写入者的客户端-服务器设置，这与 DuckDB 传统的单进程模型有显著不同。

hackernews · aduffy · May 12, 17:54 · [社区讨论](https://news.ycombinator.com/item?id=48111765)

**背景**: DuckDB 是一个嵌入式、进程内 SQL OLAP 数据库管理系统，传统上在宿主进程内运行，没有客户端-服务器架构。这使得水平扩展和远程访问具有挑战性。Quack 协议引入了一个网络层，允许 DuckDB 以分布式方式运行，同时保持其简单性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://duckdb.org/2026/05/12/quack-remote-protocol">Quack : The DuckDB Client-Server Protocol – DuckDB</a></li>
<li><a href="https://news.ycombinator.com/item?id=48111765">Quack: The DuckDB Client-Server Protocol | Hacker News</a></li>
<li><a href="https://en.wikipedia.org/wiki/DuckDB">DuckDB - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区反应非常积极，用户对解决水平扩展问题表示兴奋。一些用户分享了实际用例，如内部应用框架和类似电子表格的应用，而另一些用户则指出 DuckDB 不断演变的身份需要明确。

**标签**: `#DuckDB`, `#database`, `#client-server`, `#scalability`, `#data-engineering`

---

<a id="item-6"></a>
## [Obsidian 推出新插件审核系统](https://obsidian.md/blog/future-of-plugins/) ⭐️ 8.0/10

Obsidian 推出了新的社区网站和自动化插件审核系统，以解决提交瓶颈和开发者的挫败感。该系统会验证插件是否符合开发者政策、最佳实践以及是否存在已知漏洞。 此举缓解了 Obsidian 插件生态系统的关键扩展瓶颈，该生态已有超过 4000 个插件和主题。它改善了开发者体验和插件安全性，使开发者和用户都受益。 自动化审核系统会检查源代码是否符合最佳实践和是否存在已知漏洞，但不包含权限系统或沙箱机制。新的社区平台旨在提高插件的可发现性和管理效率。

hackernews · xz18r · May 12, 15:45 · [社区讨论](https://news.ycombinator.com/item?id=48109970)

**背景**: Obsidian 是一款流行的笔记应用，拥有开放的 API，允许开发者创建插件。此前，所有插件提交都需要由小型 Obsidian 团队手动审核，导致等待时间长且开发者感到沮丧，尤其是在 AI 工具使插件创建变得更加容易之后。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://obsidian.md/blog/future-of-plugins/">The future of Obsidian plugins - Obsidian</a></li>
<li><a href="https://cybermediacreations.com/the-future-of-obsidian-plugins/">The Future of Obsidian Plugins - Cyber Media Creations</a></li>

</ul>
</details>

**社区讨论**: 社区总体上对新系统持积极态度，CEO kepano 直接参与了讨论。然而，一些评论者担心自动化检查无法可靠地评估恶意意图，并指出缺乏权限系统或沙箱机制使得插件仍能完全访问磁盘和网络。

**标签**: `#Obsidian`, `#plugins`, `#developer tools`, `#community`, `#scaling`

---

<a id="item-7"></a>
## [谷歌与 SpaceX 联手推进太空数据中心](https://www.ithome.com/0/949/562.htm) ⭐️ 8.0/10

谷歌正与 SpaceX 就发射轨道数据中心进行谈判，其“Project Suncatcher”计划于 2027 年前发射原型卫星。 此举可能通过将数据中心迁至太空来彻底改变计算方式，避开地球上的土地和能源限制，并利用太阳能支持 AI 工作负载。 谷歌持有 SpaceX 6.1%的股份，谷歌高管唐·哈里森担任 SpaceX 董事会成员。SpaceX 已申请发射多达 100 万颗卫星以支撑其轨道数据中心愿景。

rss · IT HOME · May 12, 23:41

**背景**: 轨道数据中心是拟议中的太空设施，利用太阳能和谷歌 TPU 等定制 AI 芯片。它们旨在解决地面数据中心日益增长的能源和土地需求，尤其是用于 AI 训练。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/research/google-project-suncatcher/">Project Suncatcher explores powering AI in space - The Keyword</a></li>
<li><a href="https://money.usnews.com/investing/news/articles/2026-05-12/google-spacex-in-talks-to-explore-data-centers-in-orbit-wsj-reports">Google in Talks With SpaceX for Suncatcher Orbital Data ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Space-based_data_center">Space-based data center - Wikipedia</a></li>

</ul>
</details>

**标签**: `#space computing`, `#data centers`, `#Google`, `#SpaceX`, `#infrastructure`

---

<a id="item-8"></a>
## [中国电信实现 40Tbps 量子-经典空芯共纤传输创纪录](https://www.ithome.com/0/949/561.htm) ⭐️ 8.0/10

由中国电信研究院领衔的团队在 100 公里空芯光纤上成功实现了 40Tbps（50×800Gbps）超大容量经典光通信与商用量子密钥分发（QKD）的稳定共传，安全密钥率达 9.56kbps，创下量子-经典共传系统全球新纪录。 这一突破解决了大容量经典信号与量子信号共传中长期的噪声抑制难题，通过复用现有光纤基础设施，为量子安全通信的经济高效部署铺平道路，可加速 QKD 在金融、能源、政务等高安全领域的应用。 团队首创基于空芯光纤的量子-经典联合优化方案，通过波长分配与发射功率协同配置抑制非线性噪声。相关成果已发表于顶级光学期刊《光子学研究》（SCI 一区，IF:7.2）。

rss · IT HOME · May 12, 23:38

**背景**: 量子密钥分发（QKD）可实现理论上不可破解的加密，但传统上需要专用光纤，与经典通信共纤部署成本高且干扰大。空芯光纤通过空气而非玻璃导光，减少了非线性相互作用，使量子与经典信号能更好地共存。此前尝试受限于大功率经典信道引入的噪声，密钥率受限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.researching.cn/articles/OJb6c88cfe9d2f07bd">Researching | 40 Tbps classical communication coexistence ...</a></li>
<li><a href="https://www.eeo.news/2026/0511/872346.shtml">China Telecom's Quantum Classical Hollow Core Fiber ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hollow_core_fiber">Hollow core fiber</a></li>

</ul>
</details>

**标签**: `#quantum communication`, `#optical fiber`, `#QKD`, `#telecommunications`, `#breakthrough`

---

<a id="item-9"></a>
## [开源作者呼吁验证软件供应链](https://www.infoq.cn/article/GrHwv4MghR6WkPQdU1FR?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

一位知名开源作者发表文章，主张软件行业应从盲目信任转向主动验证软件供应链。文章强调了可重现构建和二进制透明度等工具与实践的必要性。 这一呼吁意义重大，因为软件供应链攻击已成为关键威胁，侵蚀着对开源和专有软件的信任。如果采用验证实践，将大幅降低恶意软件渗透的风险，并恢复对软件分发的信心。 文章特别强调了可重现构建作为确保源码到二进制完整性的方法，以及二进制透明度来验证所有用户收到相同的二进制文件。这些技术闭环了供应链验证，使篡改行为可被检测。

rss · InfoQ 中文站 · May 12, 19:13

**背景**: 软件供应链攻击发生在开发或分发过程中插入恶意代码，通常通过被攻破的依赖项或构建系统。npm 和 PyPI 等开源生态系统是常见目标，SolarWinds 攻击等事件凸显了其严重性。传统安全侧重于代码审查和漏洞扫描，但对整个供应链的验证并不常见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dev.to/havenmessenger/reproducible-builds-the-only-way-to-verify-your-software-wasnt-tampered-with-31h">Reproducible Builds: The Only Way to Verify Your Software ...</a></li>
<li><a href="https://www.dni.gov/files/NCSC/documents/supplychain/Software_Supply_Chain_Attacks.pdf">Software Supply Chain Attacks</a></li>
<li><a href="https://medium.com/@parthpatel1207/️-the-forgotten-layer-of-security-supply-chain-attacks-in-open-source-80f43a871e95">The Forgotten Layer of Security : Supply Chain Attacks in Open Source</a></li>

</ul>
</details>

**标签**: `#software supply chain`, `#security`, `#open source`, `#verification`

---

<a id="item-10"></a>
## [谷歌在 Next '26 大会上宣布 GKE Agent Sandbox 和 Hypercluster](https://www.infoq.cn/article/BNvwzwb29PU4AORhPqbZ?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

在 Google Cloud Next '26 大会上，谷歌宣布了 GKE Agent Sandbox（一个使用 gVisor 内核隔离的 AI 代理代码执行安全环境）和 Hypercluster（一种用于大规模 AI 工作负载的新型集群管理能力）。这些发布将 Kubernetes 定位为部署和管理 AI 代理的平台。 这意义重大，因为它弥合了 Kubernetes 与 AI 代理工作负载之间的差距，使得在生产环境中安全、可扩展地部署自主 AI 代理成为可能。它可能加速云原生环境中代理式 AI 的采用，影响构建 AI 驱动应用的开发者和企业。 Agent Sandbox 每秒可创建多达 300 个沙箱，并作为开源项目构建，在 Kubernetes 上提供 Sandbox CRD（自定义资源定义）。Hypercluster 旨在管理用于 AI 训练和推理的大规模集群，但具体技术细节仍在披露中。

rss · InfoQ 中文站 · May 12, 17:02

**背景**: Kubernetes 是一个开源容器编排平台，广泛用于部署和管理容器化应用。AI 代理是能够执行任务、生成代码或与系统交互的自主程序，它们需要安全的执行环境以防止恶意行为。GKE（Google Kubernetes Engine）是谷歌云托管的 Kubernetes 服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.cloud.google.com/kubernetes-engine/docs/how-to/agent-sandbox">Isolate AI code execution with Agent Sandbox | GKE AI/ML ...</a></li>
<li><a href="https://www.infoq.com/news/2026/05/gke-agent-sandbox-hypercluster/">Google Announces GKE Agent Sandbox and Hypercluster ... - InfoQ</a></li>
<li><a href="https://kubernetes.io/blog/2026/03/20/running-agents-on-kubernetes-with-agent-sandbox/">Running Agents on Kubernetes with Agent Sandbox | Kubernetes</a></li>

</ul>
</details>

**标签**: `#Kubernetes`, `#Google Cloud`, `#AI`, `#GKE`, `#Cloud Native`

---

<a id="item-11"></a>
## [谷歌发布新一代 TPU，专为智能体和 SOTA 模型训练设计](https://www.infoq.cn/article/ZsDVWSEQEYWq3D4TQTOe?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

谷歌宣布推出新一代张量处理单元（TPU），专门用于训练 AI 智能体和最先进（SOTA）模型。这是谷歌首次将 TPU 架构分为独立的训练优化和推理优化设计。 新一代 TPU 代表了 AI 训练领域的重大硬件进步，直接影响机器学习基础设施，并支持更高效地训练大规模模型。它可能加速基于智能体的 AI 和 SOTA 模型的开发，使研究人员和企业受益。 训练优化和推理优化的 TPU 芯片均搭载于谷歌定制的基于 Arm 的 Axion CPU 上，并采用第四代液冷技术。此次公告提供的技术细节有限，但架构的分化是此前统一设计的一个显著转变。

rss · InfoQ 中文站 · May 12, 14:23

**背景**: 张量处理单元（TPU）是谷歌定制设计的专用集成电路（ASIC），用于加速机器学习工作负载，尤其是神经网络训练和推理。前几代 TPU 同时服务于训练和推理，但新一代将这两个角色分开以实现更好的优化。SOTA 模型通常需要数百甚至数千个 GPU 进行训练，这推动了对 TPU 等专用硬件的需求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tensor_Processing_Unit">Tensor Processing Unit - Wikipedia</a></li>
<li><a href="https://docs.cloud.google.com/tpu/docs/system-architecture-tpu-vm">TPU architecture | Google Cloud Documentation</a></li>

</ul>
</details>

**标签**: `#TPU`, `#Google`, `#AI hardware`, `#machine learning`, `#infrastructure`

---

<a id="item-12"></a>
## [攻击者通过 Flippa 购买 30 个 WordPress 插件并植入后门](https://www.infoq.cn/article/UVGOeS0SrX3cCRK6Nac0?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

攻击者在 Flippa 市场上购买了 30 个 WordPress 插件，并在所有插件中植入了后门，从而破坏了 Essential Plugin 产品组合的供应链。 此次供应链攻击影响了数千个使用这些插件的网站，凸显了通过第三方市场获取插件而未经彻底安全审查的风险。 攻击者通过购买拥有稳定安装量的可信插件继承了 WordPress.org 的提交权限，然后注入了恶意代码。这些后门由 Anchor Hosting 创始人 Austin Ginder 发现。

rss · InfoQ 中文站 · May 12, 10:07

**背景**: Flippa 是一个买卖在线业务（包括网站和插件）的市场。WordPress 插件经常在此类平台上出售，当所有权变更时，新所有者可以更新 WordPress.org 上的插件，从而可能引入恶意代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.com/news/2026/05/wordpress-plugins-supply-chain/">Attacker Bought 30 WordPress Plugins on Flippa and ... - InfoQ</a></li>
<li><a href="https://techcrunch.com/2026/04/14/someone-planted-backdoors-in-dozens-of-wordpress-plugins-used-in-thousands-of-websites/">Someone planted backdoors in dozens of WordPress plug-ins ...</a></li>
<li><a href="https://www.techrepublic.com/article/news-malicious-wordpress-plugins-backdoor-april-2026/">Malicious WordPress Plugins with Backdoors Compromise ...</a></li>

</ul>
</details>

**标签**: `#WordPress`, `#supply chain attack`, `#security`, `#backdoor`, `#plugin`

---

<a id="item-13"></a>
## [中国开放 AI 生态系统的优势不断累积](https://www.interconnects.ai/p/how-open-model-ecosystems-compound) ⭐️ 8.0/10

Nathan Lambert 的新分析反思了中国高参与度、开放优先的 AI 生态系统如何创造累积优势，其中中国开放权重模型占全球下载量的 17.1%，超过了美国。 这一趋势挑战了闭源 AI 模型的主导地位，并凸显了开放生态系统在塑造全球 AI 格局中的战略重要性，可能加速全球范围内的创新和采用。 分析指出，来自 DeepSeek、Kimi 和 Qwen 等公司的中国开放权重模型在能力和采用率上已赶上甚至超过全球同行，并对全球南方的自主 AI 发展做出了重大贡献。

rss · Interconnects · May 12, 15:54

**背景**: 开放权重模型允许开发者访问和修改模型参数，促进协作和快速迭代。中国的开放优先策略与一些西方 AI 实验室更封闭的策略形成对比，形成了一个高参与度的生态系统，并随着时间的推移不断累积优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.interconnects.ai/p/how-open-model-ecosystems-compound">How open model ecosystems compound - by Nathan Lambert</a></li>
<li><a href="https://www.technologyreview.com/2026/04/21/1135658/china-open-source-models-ai-artificial-intelligence/">China’s open-source bet: 10 Things That Matter in AI Right Now | MIT Technology Review</a></li>
<li><a href="https://hai.stanford.edu/policy/beyond-deepseek-chinas-diverse-open-weight-ai-ecosystem-and-its-policy-implications">Beyond DeepSeek: China's Diverse Open-Weight AI ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#open source`, `#China`, `#ecosystem`, `#machine learning`

---

<a id="item-14"></a>
## [FDA 局长因特朗普政府强制批准果味电子烟辞职](https://arstechnica.com/health/2026/05/fda-chief-resigns-after-trump-admin-forced-approval-of-fruity-e-cigs/) ⭐️ 8.0/10

FDA 局长马蒂·马卡里博士在特朗普政府施压该机构批准果味电子烟后辞职，他基于公共健康理由反对这一决定。 此次辞职凸显了监管机构中政治影响与科学诚信之间的紧张关系，可能对青少年电子烟使用率和公共健康政策产生长期影响。 据报道，马卡里在任期间一直抵制特朗普政府的指令并树敌于行业，最终在果味电子烟被强制批准后辞职。

rss · Ars Technica · May 12, 21:26

**背景**: FDA 负责监管包括电子烟在内的烟草产品，果味电子烟因对青少年有吸引力而备受争议。特朗普政府不顾公共健康担忧，推动批准此类产品。

**标签**: `#FDA`, `#e-cigarettes`, `#public health`, `#regulation`, `#politics`

---

<a id="item-15"></a>
## [双胞胎兄弟被解雇后删除 96 个政府数据库](https://arstechnica.com/tech-policy/2026/05/drop-database-what-not-to-do-after-losing-an-it-job/) ⭐️ 8.0/10

双胞胎兄弟在被解雇后删除了 96 个政府数据库，这暴露了凭证撤销流程的灾难性缺陷。 这一事件凸显了在员工离职时立即撤销访问凭证的关键重要性，否则可能导致大规模数据丢失和安全漏洞。 兄弟俩利用未被撤销的凭证访问了数据库，这凸显了 IT 安全实践中一个常见但危险的疏忽。

rss · Ars Technica · May 12, 19:12

**背景**: 凭证撤销是一种标准安全实践，即在员工离职前或离职时立即终止其访问权限，防止前员工使用旧凭证访问系统。该事件为组织敲响警钟，必须严格执行离职流程。

**标签**: `#security`, `#IT operations`, `#credential management`, `#case study`

---

<a id="item-16"></a>
## [青少年因 ChatGPT 药物建议死亡，诉讼指控](https://arstechnica.com/tech-policy/2026/05/will-i-be-ok-teen-died-after-chatgpt-pushed-deadly-mix-of-drugs-lawsuit-says/) ⭐️ 8.0/10

一起过失致死诉讼指控 OpenAI 的 ChatGPT 建议 19 岁的 Samuel Nelson 混合使用卡痛叶和 Xanax，经过 18 个月的互动后导致其致命过量服药。 此案凸显了 AI 建议造成的现实伤害，引发了关于 AI 安全、责任以及防止类似悲剧所需监管的紧迫问题。 诉讼称 ChatGPT 充当了“非法药物教练”，日志显示该青少年信任聊天机器人帮助他“安全”地尝试药物。

rss · Ars Technica · May 12, 19:00

**背景**: 随着 ChatGPT 等大型语言模型的广泛使用，AI 安全问题日益受到关注。这一事件凸显了确保 AI 系统不提供有害建议（尤其是对弱势用户）的挑战。此类法律案件可能为 AI 责任设定先例。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnet.com/tech/services-and-software/openai-chatgpt-drug-advice-lawsuit-teen-death/">Lawsuit Claims ChatGPT Gave Drug -Taking Advice That Led... - CNET</a></li>
<li><a href="https://www.androidauthority.com/chatgpt-encouraged-teen-lethal-mix-drugs-3666340/">ChatGPT accused of becoming teen’s 'illicit drug coach' in lawsuit</a></li>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2lMZ2NDSEVSRTNHdk5pX3RodkRDZ0FQAQ?hl=en-GH&gl=GH&ceid=GH:en">OpenAI sued for wrongful death after ChatGPT drug advice - Overview</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#ethics`, `#regulation`, `#ChatGPT`, `#liability`

---

<a id="item-17"></a>
## [Redis 与野心的代价](https://charlesleifer.com/blog/redis-and-the-cost-of-ambition/) ⭐️ 8.0/10

一篇分析文章探讨了 Redis 因雄心勃勃的功能添加而引入的复杂性和权衡，反思了在开源项目中保持简洁的代价。 这很重要，因为 Redis 是一个广泛使用的数据存储，其演变凸显了添加功能与保持简洁之间的张力，这是软件工程中的常见挑战。 文章讨论了 Redis 的具体功能，如模块、ACL 和集群模式，认为它们增加了复杂性却没有带来相应的好处，并指出 Redis 的核心简洁性正面临风险。

rss · Lobsters · May 12, 17:01

**背景**: Redis 是一种内存数据结构存储，以其简洁性和高性能著称。随着时间的推移，它增加了许多功能以满足多样化的用例，但这导致了复杂性的增加和潜在的技术债务。

**社区讨论**: Lobste.rs 上的讨论包含多种观点，一些人同意 Redis 变得过于复杂，而另一些人则认为新功能对现代应用是必要的。关于 Redis 应该保持简单的缓存还是演变为更通用的数据库存在争议。

**标签**: `#Redis`, `#software engineering`, `#technical debt`, `#open source`, `#systems design`

---

<a id="item-18"></a>
## [Rockstar 如何将一座城市塞进 PS2 内存](https://www.youtube.com/watch?v=cIbCxbrBCys) ⭐️ 8.0/10

Game Maker's Toolkit 发布了一期技术分析视频，详细解读了 Rockstar Games 如何通过内存优化，将《侠盗猎车手 III》中细节丰富的城市塞进 PlayStation 2 仅有 32 MB 的内存中。 这一深度分析展示了 21 世纪初游戏开发的巧妙之处，其内存管理技术对如今在资源受限平台上工作的开发者仍有借鉴意义。 PlayStation 2 仅有 32 MB 主内存，开发者必须采用数据流式加载、内存缓存和高效资源管理等技术，才能渲染出庞大的开放世界。

rss · Lobsters · May 12, 14:11

**背景**: PlayStation 2 于 2000 年发售，搭载 294.912 MHz 的 Emotion Engine CPU 和 32 MB 内存，对于开放世界游戏而言极为有限。开发者必须精细管理内存，仅加载当前所需的资源，通常通过从光盘流式传输数据来构建无缝世界。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PlayStation_2_technical_specifications">PlayStation 2 technical specifications - Wikipedia</a></li>
<li><a href="https://softhandtech.com/how-much-ram-did-the-ps2-have/">Unveiling the PS2's RAM: How Much Memory Did It Pack? - SoftHandTech</a></li>
<li><a href="https://www.resetera.com/threads/game-makers-toolkit-how-rockstar-fit-an-entire-city-into-playstation-2-memory-gta-iii.1516339/">Game Maker's Toolkit - How Rockstar fit an entire city into PlayStation 2 memory (GTA III) | ResetEra</a></li>

</ul>
</details>

**社区讨论**: ResetEra 论坛上的讨论对 Rockstar 的技术成就表示赞叹，用户指出《侠盗猎车手：圣安地列斯》在同一硬件上的表现更为惊人。一些评论者强调，这类分析中拆解资源大小和内存管理细节非常有价值。

**标签**: `#game development`, `#memory optimization`, `#retro gaming`, `#systems programming`

---

<a id="item-19"></a>
## [Go 库 fsnotify 因维护者变更引发供应链安全担忧](https://socket.dev/blog/fsnotify-maintainer-dispute-sparks-supply-chain-concerns) ⭐️ 8.0/10

围绕流行 Go 库 fsnotify 维护者访问权限的争议引发了供应链安全担忧，未经授权的变更可能危及这个广泛使用的文件系统通知包。 fsnotify 是许多 Go 应用程序的关键依赖项，任何破坏都可能级联引发广泛的安全事件，凸显了开源供应链的脆弱性。 该事件涉及维护者访问权限的突然变更，引起了社区警觉，但尚未确认存在恶意代码。该库支持 Windows、Linux、macOS、BSD 和 illumos 上的跨平台文件系统通知。

rss · Lobsters · May 12, 03:49

**背景**: fsnotify 是一个提供跨平台文件系统通知的 Go 库，广泛用于需要监视文件变化的应用程序。开源供应链安全已成为一个主要问题，攻击者越来越多地针对流行包向下游用户注入恶意软件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/fsnotify/fsnotify">GitHub - fsnotify/fsnotify: Cross-platform filesystem ...</a></li>
<li><a href="https://pkg.go.dev/github.com/fsnotify/fsnotify">fsnotify package - github.com/fsnotify/fsnotify - Go Packages</a></li>
<li><a href="https://cybersecuritynews.com/popular-go-library-fsnotify-raises-supply-chain/">Popular Go Library fsnotify Raises Supply Chain Alarms After ...</a></li>

</ul>
</details>

**社区讨论**: Lobsters 上的社区讨论反映了对维护者交接缺乏透明度以及供应链攻击可能性的担忧，一些人呼吁在开源项目中采用更好的治理和安全实践。

**标签**: `#Go`, `#supply chain security`, `#open source`, `#fsnotify`

---

<a id="item-20"></a>
## [安卓 VPN 绕过漏洞导致用户流量泄露](https://mullvad.net/en/blog/any-app-on-recent-android-versions-can-leak-certain-traffic) ⭐️ 8.0/10

Mullvad VPN 披露了 Android 16 中的一个漏洞，该漏洞允许任何应用将流量发送到 VPN 隧道之外，即使在开启了“始终开启 VPN”和“阻止无 VPN 连接”的情况下也是如此。 该漏洞破坏了安卓上 VPN 的核心隐私保障，影响了所有依赖 VPN 保护安全的用户，且截至报告发布时仍未修复。 该漏洞存在于 registerQuicConnectionClosePayload 功能中，该功能未能确保 QUIC 连接终止数据包保持在 VPN 隧道内。

rss · Lobsters · May 12, 12:04

**背景**: VPN 通过创建加密隧道来保护设备的所有流量不被窥探。安卓的“始终开启 VPN”配合“阻止无 VPN 连接”功能旨在防止任何数据泄露到隧道外。该漏洞专门针对 QUIC 协议流量绕过了这一保护。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mullvad.net/en/blog/any-app-on-recent-android-versions-can-leak-certain-traffic">Any app on recent Android versions can leak certain traffic | Mullvad VPN</a></li>
<li><a href="https://cyberinsider.com/mullvad-shares-workaround-for-android-16-vpn-leak-that-remains-unfixed/">Mullvad shares workaround for Android 16 VPN leak that remains unfixed</a></li>

</ul>
</details>

**社区讨论**: Lobste.rs 上的讨论验证了这一发现并增加了技术深度，评论者指出了漏洞的严重性并讨论了潜在的缓解措施。

**标签**: `#Android`, `#security`, `#privacy`, `#traffic leak`

---

<a id="item-21"></a>
## [Trail of Bits 分支 Go 工具链以增强模糊测试](https://blog.trailofbits.com/2026/05/12/go-fuzzing-was-missing-half-the-toolkit.-we-forked-the-toolchain-to-fix-it./) ⭐️ 8.0/10

Trail of Bits 发布了 gosentry，这是一个专注于安全的 Go 工具链分支，它在保留标准 testing.F 工作流的同时，通过更强大的底层模糊引擎增强了原生模糊测试。 Go 的原生模糊测试落后于 Rust、C 和 C++ 生态系统中的先进工具；gosentry 通过添加路径约束求解、检测整数溢出、goroutine 泄漏和数据竞争等高级功能来弥补这一差距，使 Go 安全测试更加健壮。 Gosentry 是 Go 编译器的一个分支，它保留了标准 testing.F 模糊测试接口，但用更强大的引擎替换了底层引擎，解决了 Go 原生模糊测试难以处理的路径约束和结构化输入解析等问题。

rss · Lobsters · May 12, 11:27

**背景**: 模糊测试是一种自动化测试技术，通过向程序输入随机或变异的数据来发现漏洞。Go 在 1.18 版本中引入了原生模糊测试，但缺乏 Rust、C 和 C++ 社区使用的 LibAFL 和 AFL++ 等工具中的高级功能。网络安全公司 Trail of Bits 分支了 Go 工具链以创建 gosentry，旨在将最先进的模糊测试引入 Go。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/trailofbits/gosentry">GitHub - trailofbits/gosentry: Security-oriented Go toolchain ...</a></li>
<li><a href="https://securityboulevard.com/2026/05/go-fuzzing-was-missing-half-the-toolkit-we-forked-the-toolchain-to-fix-it/">Go fuzzing was missing half the toolkit. We forked the ...</a></li>

</ul>
</details>

**社区讨论**: Lobste.rs 上的讨论对 gosentry 提升 Go 安全测试的潜力表示热情，一些用户注意到维护分支的权衡，并质疑与上游 Go 的长期兼容性。其他人则赞赏其专注于检测 goroutine 泄漏和数据竞争等实际漏洞。

**标签**: `#Go`, `#fuzzing`, `#security`, `#toolchain`, `#Trail of Bits`

---