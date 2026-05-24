---
layout: default
title: "Horizon Summary: 2026-05-24 (ZH)"
date: 2026-05-24
lang: zh
---

> 从 103 条内容中筛选出 26 条重要资讯

---

1. [从芯片照片中反汇编 80386 微码](#item-1) ⭐️ 9.0/10
2. [从第一性原理优化深度学习性能](#item-2) ⭐️ 9.0/10
3. [中国空间站将测试钙钛矿电池，为月球基地储能](#item-3) ⭐️ 8.0/10
4. [Anthropic 接近完成超 300 亿美元融资，估值或超 OpenAI](#item-4) ⭐️ 8.0/10
5. [国家数据局召开词元经济座谈会，阿里腾讯等参与](#item-5) ⭐️ 8.0/10
6. [OpenAI 详解低延迟语音 AI 的 WebRTC 架构](#item-6) ⭐️ 8.0/10
7. [在 Minecraft 中实现 Wayland 合成器](#item-7) ⭐️ 8.0/10
8. [C# 在 .NET 11 预览版 2 中引入联合类型](#item-8) ⭐️ 8.0/10
9. [深入解析 BerkeleyDB 架构](#item-9) ⭐️ 8.0/10
10. [AI 实验室从模型转向智能体](#item-10) ⭐️ 8.0/10
11. [深入探讨 HTML <dl>元素](#item-11) ⭐️ 7.0/10
12. [苹果在 WWDC 2026 前注册 genai.apple.com 子域名](#item-12) ⭐️ 7.0/10
13. [OpenAI 高薪招聘安全研究员，研究递归自我改进风险](#item-13) ⭐️ 7.0/10
14. [大众与众 06/07 今年将搭载地平线征程 6 智驾系统](#item-14) ⭐️ 7.0/10
15. [美光 CEO 警告内存短缺可能持续到 2026 年后](#item-15) ⭐️ 7.0/10
16. [中国 600 公斤推力级涡扇发动机首飞成功](#item-16) ⭐️ 7.0/10
17. [Grab 大规模工程支持的多智能体系统](#item-17) ⭐️ 7.0/10
18. [SpaceX 星舰 V3 首飞基本成功](#item-18) ⭐️ 7.0/10
19. [不要自己实现加密](#item-19) ⭐️ 7.0/10
20. [Jira 工作流被证明是图灵完备的](#item-20) ⭐️ 7.0/10
21. [R7RS Large 过程分册初稿发布](#item-21) ⭐️ 7.0/10
22. [sp.h：为 C 语言提出的新标准库](#item-22) ⭐️ 7.0/10
23. [仍与 C++不兼容的 C 语言构造](#item-23) ⭐️ 7.0/10
24. [苹果 MIE 安全机制首次被公开绕过](#item-24) ⭐️ 7.0/10
25. [SPy：一个带解释器和编译器的静态类型 Python 变体](#item-25) ⭐️ 7.0/10
26. [Go 语言中丢弃权限的技术指南](#item-26) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [从芯片照片中反汇编 80386 微码](https://www.reenigne.org/blog/80386-microcode-disassembled/) ⭐️ 9.0/10

Reenigne 利用高分辨率芯片照片成功反汇编了 Intel 80386 处理器的微码，揭示了此前未公开的内部控制逻辑。 这一突破使得 80386 的开源复制成为可能（如相关 z386 项目），并深入揭示了这款历史性 CPU 的设计，有利于复古计算和硬件教育。 微码是通过分析芯片照片中的 ROM 布局并追踪连接提取的，最终得到完整的二进制映像，可用于模拟处理器的行为。

hackernews · nand2mario · May 23, 12:11 · [社区讨论](https://news.ycombinator.com/item?id=48247004)

**背景**: 微码是 CPU 内部实现指令集架构的低级控制层。80386 于 1985 年发布，是英特尔首款 32 位 x86 处理器。从芯片照片中逆向工程其微码需要识别 ROM 单元并解码其位模式，这是一个结合显微术、图像处理和逻辑分析的艰苦过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.reenigne.org/blog/80386-microcode-disassembled/">80386 microcode disassembled « Reenigne blog</a></li>
<li><a href="https://news.ycombinator.com/item?id=48247004">80386 Microcode Disassembled | Hacker News</a></li>
<li><a href="https://www.altusintel.com/public-yyr4pw/?tt=1779562264">I386 Microcode Disassembly Results Published | Altus Intel</a></li>

</ul>
</details>

**社区讨论**: Hacker News 社区对逆向工程过程表现出浓厚兴趣，用户询问如何从芯片图像重建微码，并指出这种黑盒分析的难度和回报。同时提到了相关的 z386 开源 80386 项目讨论。

**标签**: `#reverse engineering`, `#microcode`, `#80386`, `#hardware`, `#retrocomputing`

---

<a id="item-2"></a>
## [从第一性原理优化深度学习性能](https://horace.io/brrr_intro.html) ⭐️ 9.0/10

Horace He 于 2022 年发表了一篇全面的技术博客，从第一性原理出发，通过理解硬件和软件栈来解释如何优化深度学习性能，内容涵盖 GPU 架构、内存层次结构和算子融合。该文章已成为机器学习系统领域的经典参考文献。 这篇深入分析帮助从业者超越黑盒优化，实现数量级的加速，满足了高效模型训练和推理日益增长的需求。同时，它也凸显了 NVIDIA 持续的硬件领先地位，这塑造了整个深度学习生态系统。 文章用一个简单例子（x.cos().cos()）说明 Python 开销、内存带宽和内核启动延迟如何主导性能，并展示算子融合可以将开销降低数百万倍。它解释了屋顶线模型、内存合并和张量核心利用率等概念。

hackernews · tosh · May 23, 11:50 · [社区讨论](https://news.ycombinator.com/item?id=48246889)

**背景**: 像 PyTorch 和 TensorFlow 这样的深度学习框架通过启动 GPU 内核来执行操作，但每次内核启动都会带来 Python 和 CUDA 运行时的开销。理解硬件-软件栈——包括 GPU 内存层次结构、线程束调度和张量核心——对于编写高效代码至关重要。屋顶线模型是一种可视化工具，用于识别内核是计算受限还是内存受限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.nvidia.com/gpugems/gpugems2/part-iv-general-purpose-computation-gpus-primer/chapter-35-gpu-program-optimization">Chapter 35. GPU Program Optimization | NVIDIA Developer</a></li>
<li><a href="https://dl.acm.org/doi/10.1145/3570638">Optimization Techniques for GPU Programming | ACM Computing Surveys</a></li>
<li><a href="https://www.digitalocean.com/community/tutorials/an-introduction-to-gpu-optimization">GPU Performance Optimization for Deep Learning | DigitalOcean</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞该文章是经典之作，并指出它清晰地解释了 NVIDIA 在 TFLOPs、带宽和互连方面的持续领先地位。一些人表示沮丧，认为性能优化建议在不同运行时和硬件之间不可移植，称当前状态为“巨大的混乱”。

**标签**: `#deep learning`, `#performance optimization`, `#GPU computing`, `#machine learning systems`, `#NVIDIA`

---

<a id="item-3"></a>
## [中国空间站将测试钙钛矿电池，为月球基地储能](https://www.ithome.com/0/954/472.htm) ⭐️ 8.0/10

中国空间站将首次开展钙钛矿电池动态服役实验，由神舟二十三号飞船携带上行，研究其在极端太空环境下的性能表现。 该实验将为未来低轨卫星、深空探测、月球基地和空间原位制造能源系统提供关键数据，推动高效、轻量化的空间光伏技术发展。 实验将测量在真实空间条件下（包括高能粒子辐射、原子氧、高低温交变）的转换效率衰减，以了解钙钛矿材料和器件的失效机制。

rss · IT HOME · May 24, 00:44

**背景**: 钙钛矿太阳能电池是第三代光伏技术，能直接将光能转化为电能，与储能电池不同。它们具有高效率、低成本和柔性等优点，但在太空中面临稳定性挑战。空间站为在动态轨道条件下测试这些电池提供了独特平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perovskite_solar_cell">Perovskite solar cell</a></li>
<li><a href="https://www.energy.gov/cmei/systems/perovskite-solar-cells">Perovskite Solar Cells | Department of Energy</a></li>
<li><a href="https://www.nature.com/articles/s44453-026-00030-3">Key technological challenges and systemic solutions for lunar base energy systems designed for long-term deployment needs | npj Space Exploration</a></li>

</ul>
</details>

**标签**: `#perovskite solar cells`, `#space station`, `#lunar base`, `#photovoltaics`, `#China space program`

---

<a id="item-4"></a>
## [Anthropic 接近完成超 300 亿美元融资，估值或超 OpenAI](https://www.ithome.com/0/954/452.htm) ⭐️ 8.0/10

据报道，Anthropic 即将完成一轮超过 300 亿美元的融资，公司估值有望突破 9000 亿美元，从而超越 OpenAI 成为全球估值最高的 AI 初创企业。该交易最快可能在下周宣布。 这轮融资将标志着 AI 初创企业格局的重大转变，Anthropic 在估值上超越 OpenAI，显示出投资者对其以 AI 安全为核心的方法充满信心。同时，这也凸显了 Anthropic 营收的快速增长——预计下月年化营收将突破 500 亿美元。 据报道，本轮融资规模已超过 Anthropic 最初设定的 300 亿美元目标，并在数周内迅速完成。公司年化营收从去年 7 月的 40 亿美元增长至预计的 500 亿美元，并可能很快迎来首个盈利季度。

rss · IT HOME · May 23, 15:12

**背景**: Anthropic 是一家成立于 2021 年的 AI 安全公司，由前 OpenAI 员工创立，以其 Claude 系列大语言模型而闻名。该公司将自己定位为比 OpenAI 更谨慎、更注重安全的替代选择。在竞争激烈的 AI 初创市场中，估值和融资轮次是衡量投资者信心的关键指标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anthropic">Anthropic - Wikipedia</a></li>
<li><a href="https://www.anthropic.com/">Home \ Anthropic</a></li>

</ul>
</details>

**标签**: `#Anthropic`, `#funding`, `#AI startups`, `#valuation`, `#OpenAI`

---

<a id="item-5"></a>
## [国家数据局召开词元经济座谈会，阿里腾讯等参与](https://www.ithome.com/0/954/441.htm) ⭐️ 8.0/10

2026 年 5 月 22 日，国家数据局召开词元经济座谈会，阿里云、腾讯、月之暗面等企业代表参会。国家数据局宣布将把推动词元经济发展纳入工作体系，以推进数据要素市场化配置改革。 这标志着官方将词元经济纳入政策重点，预示着数据资产化和 AI 驱动经济指标的转变。此举可能加速 AI 服务的商业化，并确立词元作为 AI 服务计费和结算的标准单位。 2026 年 3 月，国家数据局局长正式将 Token 翻译为“词元”。截至 2026 年 3 月，我国日均词元调用量从 2024 年初的 1000 亿次跃升至 140 万亿次，实现千倍增长。

rss · IT HOME · May 23, 13:38

**背景**: 词元经济是指以词元（Token）作为 AI 模型处理文本、代码、图像等信息的最小运算单元，并作为 AI 服务计量、结算和统计单位的经济体系。中国一直在推进数据要素市场化配置改革，并建设全国一体化算力网以支持 AI 发展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gov.cn/lianbo/bumen/202407/content_6964034.htm">坚持推进数据要素市场化配置改革——国家数据局介绍数据领域改革进展和...</a></li>
<li><a href="https://www.ndrc.gov.cn/xxgk/jd/jd/202508/t20250828_1400104.html">【激活数据要素市场化配置改革动能，筑牢“人工智能+”行动发展基石】-...</a></li>
<li><a href="https://www.gov.cn/zhengce/zhengceku/202401/content_6924596.htm">关于深入实施"东数西算"工程加快构建全国一体化算力网的实施意见_国务院部门文件_中国政府网</a></li>

</ul>
</details>

**标签**: `#token economy`, `#AI policy`, `#data governance`, `#China tech`, `#large language models`

---

<a id="item-6"></a>
## [OpenAI 详解低延迟语音 AI 的 WebRTC 架构](https://www.infoq.cn/article/HzTpYj4SIqzFOHybIO2q?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

OpenAI 发布了一篇详细文章，解释其如何重建 WebRTC 栈，以支持全球规模的低延迟语音 AI，用中继-收发器设计取代了传统的媒体终结模型。 该架构使 OpenAI 能够为 9 亿周活跃用户提供低延迟语音 AI，解决了扩展实时语音应用的关键挑战。这些见解对构建类似系统的工程师极具参考价值。 新的中继-收发器设计更适合 Kubernetes 和云负载均衡器，提升了可扩展性和对话中的轮换能力。OpenAI 的文章未披露具体的延迟数字，这引发了一些社区讨论。

rss · InfoQ 中文站 · May 23, 14:00

**背景**: WebRTC 是一个免费的开源项目，通过简单的 API 提供实时通信能力。OpenAI 的语音 AI（如 ChatGPT 中的高级语音模式）需要极低延迟以维持自然的对话流。传统的媒体终结模型在云原生环境中表现不佳，从而促使了架构重构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/delivering-low-latency-voice-ai-at-scale/">How OpenAI delivers low-latency voice AI at scale</a></li>
<li><a href="https://www.infoq.com/news/2026/05/openai-voice-ai-scale/">OpenAI Outlines WebRTC Architecture for Low-Latency Voice AI at...</a></li>
<li><a href="https://aitoolly.com/ai-news/article/2026-05-05-how-openai-scales-low-latency-voice-ai-for-900-million-weekly-users-via-webrtc-rearchitecture">OpenAI Scales Low-Latency Voice AI: WebRTC Rearchitecture</a></li>

</ul>
</details>

**社区讨论**: 一些社区成员注意到 OpenAI 的文章中缺少具体的延迟指标，质疑其声明的透明度。其他人则称赞架构细节以及转向中继-收发器模型作为扩展的实用解决方案。

**标签**: `#WebRTC`, `#voice AI`, `#low-latency`, `#OpenAI`, `#architecture`

---

<a id="item-7"></a>
## [在 Minecraft 中实现 Wayland 合成器](https://modrinth.com/project/9yAfrPwH) ⭐️ 8.0/10

一位开发者创建了一个完全作为 Minecraft 模组实现的 Wayland 合成器，使游戏能够作为 Wayland 客户端的显示服务器运行。 该项目展示了底层图形系统与流行游戏前所未有的集成，为在 Minecraft 中运行图形应用程序开辟了创意可能性，并展示了 Wayland 和 Minecraft 模组的灵活性。 该模组实现了 Wayland 协议，并在 Minecraft 内部充当合成窗口管理器，使外部 Wayland 应用程序能够在游戏世界中渲染。它可在 Modrinth 上获取，可能需要兼容的 Minecraft 版本和模组加载器。

rss · Lobsters · May 23, 14:07

**背景**: Wayland 是一种显示服务器协议，在 Linux 上取代了较旧的 X11 系统，合成器负责管理窗口渲染。Minecraft 模组允许玩家通过代码修改游戏，通常使用 Fabric 或 Forge 等模组加载器。该项目通过将 Wayland 合成器嵌入 Minecraft，将这两个世界融合在一起。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Wayland_(protocol)">Wayland (protocol) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Minecraft_modding">Minecraft modding - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Lobste.rs 上的讨论突出了该项目的创新性和技术上的令人印象深刻，一些评论者对性能和实际用例表示好奇。大家普遍欣赏其中涉及的创造性工程。

**标签**: `#Wayland`, `#Minecraft`, `#compositor`, `#modding`, `#graphics`

---

<a id="item-8"></a>
## [C# 在 .NET 11 预览版 2 中引入联合类型](https://andrewlock.net/exploring-the-dotnet-11-preview-2-dotnet-gets-union-types/) ⭐️ 8.0/10

微软在 .NET 11 预览版 2 中为 C# 引入了联合类型，使开发者能够表达属于封闭类型集合之一的值，并支持穷举模式匹配。 联合类型显著提升了类型安全性和代码表现力，通过在编译时检查所有可能情况来减少运行时错误，这是 C# 生态系统中期待已久的功能。 C# 中提议的联合类型是类型联合，而非可区分联合，但可以通过使用新类型声明作为 case 类型来表达可区分联合。该功能目前处于预览阶段，可能会有所变化。

rss · Lobsters · May 23, 21:28

**背景**: 联合类型允许变量持有多个指定类型之一，类似于 F# 或 Haskell 等函数式语言中的代数数据类型。此前，C# 开发者必须使用 OneOf 等库或自定义类层次结构来模拟此模式，但缺乏内置的穷举检查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/union">Union types - C# reference | Microsoft Learn</a></li>
<li><a href="https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/proposals/unions">Unions - C# feature specifications (preview) | Microsoft Learn</a></li>
<li><a href="https://blog.ndepend.com/csharp-unions/">C# 15 Unions - NDepend Blog</a></li>

</ul>
</details>

**社区讨论**: Lobsters 上的讨论显示出对该功能的兴奋，一些用户指出这使 C# 更接近函数式编程范式。其他人则对实现的复杂性和潜在性能影响表示谨慎。

**标签**: `#C#`, `#.NET`, `#union types`, `#language design`

---

<a id="item-9"></a>
## [深入解析 BerkeleyDB 架构](https://aosabook.org/en/v1/bdb.html) ⭐️ 8.0/10

这篇来自《开源应用架构》系列的文章详细分析了 BerkeleyDB 的设计，涵盖了其存储引擎、并发控制和事务子系统。 BerkeleyDB 是一种广泛使用的嵌入式数据库，了解其架构有助于开发者构建可靠、高性能的应用。这篇深度分析为系统程序员和数据库爱好者提供了宝贵的见解。 文章解释了 BerkeleyDB 如何从简单的键值存储（Data Store）演变为支持并发访问（Concurrent Data Store）和事务（Transactional Data Store）。它还介绍了确保 ACID 属性的锁定和日志机制。

rss · Lobsters · May 23, 20:38

**背景**: BerkeleyDB 是一个嵌入式数据库库，以字节数组形式存储任意键/值对。它用 C 语言编写，并提供多种语言的 API 绑定，被广泛应用于众多应用程序中，包括作为 MySQL 的 BDB 存储引擎。该架构文章是《开源应用架构》系列丛书的一部分，该系列剖析了著名的开源项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Berkeley_DB">Berkeley DB - Wikipedia</a></li>
<li><a href="https://web.stanford.edu/class/cs276a/projects/docs/berkeleydb/ref/txn/intro.html">Berkeley DB Reference Guide: Berkeley DB and transactions</a></li>
<li><a href="http://dev.cs.ovgu.de/db/mysql/BDB.html">The BDB (BerkeleyDB) Storage Engine</a></li>

</ul>
</details>

**社区讨论**: 在 Lobsters 上，评论者称赞文章清晰且深入，一些人指出 BerkeleyDB 的设计原则至今仍然适用。少数人讨论了 BerkeleyDB 与其他嵌入式数据库（如 SQLite）之间的权衡。

**标签**: `#database`, `#architecture`, `#BerkeleyDB`, `#systems`

---

<a id="item-10"></a>
## [AI 实验室从模型转向智能体](https://www.latent.space/p/ainews-all-model-labs-are-now-agent) ⭐️ 8.0/10

最近一篇文章指出，所有主要 AI 模型实验室正将重心转向构建智能体系统，标志着行业从纯模型开发向基于智能体的应用的重大转变。 这一转变表明 AI 行业正从基础模型转向能够自主行动的系统，可能释放自动化、科学发现和企业工作流的新能力。 文章综合了多位关键人物的言论，表明这是一个协调的趋势。Google Cloud 等实验室正在举办聚焦智能体工作流的活动，而 Latent Labs 等初创公司则推出了用于生物医学研究的 AI 智能体。

rss · Latent Space · May 23, 04:21

**背景**: AI 智能体是能够感知环境、处理数据并采取行动以实现目标的自主系统。与传统仅生成输出的 AI 模型不同，智能体可以执行多步骤任务、使用工具并适应反馈。从模型到智能体的转变代表了 AI 部署和变现方式的范式转移。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cloud.google.com/resources/ai-live-labs-2026">AI Live + Labs | Google Cloud</a></li>
<li><a href="https://www.genengnews.com/topics/artificial-intelligence/can-ai-agents-automate-scientific-discovery/">Can AI Agents Automate Scientific Discovery?</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#industry trends`, `#AI labs`, `#paradigm shift`

---

<a id="item-11"></a>
## [深入探讨 HTML <dl>元素](https://benmyers.dev/blog/on-the-dl/) ⭐️ 7.0/10

Ben Myers 的一篇文章探讨了 HTML <dl>元素的正确用法和细微差别，引发了关于语义 HTML 实用性的讨论。 这场讨论凸显了语义纯洁性与实际开发需求之间的持续张力，影响着开发者处理 HTML 结构和可访问性的方式。 <dl>元素历史上是定义列表，在 HTML5 中代表通用关联列表，但其有限的嵌套和样式灵活性常常让开发者感到沮丧。

hackernews · Lobsters · May 23, 13:03 · [社区讨论](https://news.ycombinator.com/item?id=48247325)

**背景**: 语义 HTML 使用元素传达超越表现的意义，有助于可访问性和 SEO。<dl>元素将术语(<dt>)与描述(<dd>)配对，但缺乏对分隔线或多层包装器等复杂结构的内置支持。

**社区讨论**: 评论揭示了分歧：一些人倡导语义正确性，而另一些人（如 kqp）认为语义 HTML 因其僵化而不实用。theodpHN 和 jimbosis 提供的历史背景显示了<dl>元素的悠久传统。

**标签**: `#HTML`, `#semantic HTML`, `#web development`, `#accessibility`, `#frontend`

---

<a id="item-12"></a>
## [苹果在 WWDC 2026 前注册 genai.apple.com 子域名](https://www.ithome.com/0/954/457.htm) ⭐️ 7.0/10

苹果注册了新的子域名 genai.apple.com，目前该域名尚未指向公开页面，表明苹果正在为 WWDC 2026 上的生成式 AI 发布做准备。 此举表明苹果正在加大生成式 AI 投入，很可能扩展 Apple Intelligence，推出独立 Siri 应用、自然语言语音控制及增强的无障碍功能等新特性，从而重塑 iOS、iPadOS 和 macOS 的用户交互方式。 该子域名由 MacRumors 的 Aaron Perris 发现，预计将用于托管生成式 AI 服务的专属网站。传闻中的功能包括独立 Siri 应用、iPhone 视频自动实时字幕，以及语音控制的自然语言指令。

rss · IT HOME · May 23, 22:40

**背景**: Apple Intelligence 是苹果在 WWDC 2024 上发布的生成式 AI 系统，集成于 iOS 18、iPadOS 18 和 macOS Sequoia 中，提供写作工具、图像生成、通知摘要及 ChatGPT 集成等功能。genai.apple.com 子域名表明苹果正在筹备更广泛的生成式 AI 平台或服务，可能超越当前 Apple Intelligence 的能力范围。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://9to5mac.com/2026/05/23/apple-new-gen-ai-subdomain-ahead-of-wwdc/">Apple registers new 'gen AI' subdomain ahead of next month's ...</a></li>
<li><a href="https://www.macrumors.com/2026/05/23/apple-gen-ai-subdomain/">Apple Preparing New 'Gen AI' Website Ahead of WWDC</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_Intelligence">Apple Intelligence</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Generative AI`, `#WWDC`, `#Apple Intelligence`, `#Siri`

---

<a id="item-13"></a>
## [OpenAI 高薪招聘安全研究员，研究递归自我改进风险](https://www.ithome.com/0/954/455.htm) ⭐️ 7.0/10

OpenAI 正在为其 Preparedness 安全团队招聘研究员，年薪最高达 44.5 万美元，研究 AI 递归自我改进带来的风险，包括数据投毒和模型可解释性。 此次招聘表明 OpenAI 在 AI 安全和对齐方面投入巨大，旨在应对 AI 系统自主改进可能超出人类控制的风险，这将对整个社会产生深远影响。 该职位重点研究防御数据投毒攻击、开发模型可解释性工具，以及追踪技术岗位的自动化进展。OpenAI 计划在 2025 年 9 月前部署自动化 AI 研究实习生，并在 2028 年 3 月前实现真正的自动化 AI 研究员。

rss · IT HOME · May 23, 15:49

**背景**: 递归自我改进（RSI）是指 AI 系统自我改进代码的过程，可能导致智能爆炸。数据投毒攻击通过破坏训练数据来操纵 AI 行为。模型可解释性旨在理解和解释 AI 的决策过程，对安全性至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recursive_self-improvement">Recursive self-improvement</a></li>
<li><a href="https://en.wikipedia.org/wiki/Data_poisoning_attack">Data poisoning attack</a></li>
<li><a href="https://www.ibm.com/think/topics/interpretability">What is AI interpretability? - IBM</a></li>

</ul>
</details>

**社区讨论**: 文章提到 Anthropic 的研究尝试用 AI 监督更强的 AI 模型，取得了有限但积极的结果。Anthropic 联合创始人杰克·克拉克估计，到 2028 年底 AI 研发完全自动化的概率约为 60%，反映了业界对时间线的争论。

**标签**: `#AI safety`, `#OpenAI`, `#recursive self-improvement`, `#alignment`, `#recruitment`

---

<a id="item-14"></a>
## [大众与众 06/07 今年将搭载地平线征程 6 智驾系统](https://www.ithome.com/0/954/453.htm) ⭐️ 7.0/10

大众汽车推出了与众 06 和 07 车型，这两款车是首批量产搭载地平线征程 6M 芯片的车型，配备了酷睿程开发的智能辅助驾驶系统，支持高速 NOA 和智能泊车。到 2026 年底，将推出基于更强大的征程 6H 芯片的城市 NOA 版本。 这标志着地平线征程 6 系列芯片首次在全球主流汽车制造商的车型上实现量产，是中国自动驾驶芯片的重要里程碑。到 2026 年实现城市 NOA 的清晰路线图，展示了 10-20 万元价位区间高级辅助驾驶的快速商业化。 征程 6M 芯片支持高速 NOA 和智能泊车，包括跨楼层记忆泊车，而即将推出的征程 6H 芯片将支持城市 NOA，具备 U 型路口掉头、窄路会车等功能。该智驾系统由大众 CARIAD 与地平线的合资公司酷睿程开发。

rss · IT HOME · May 23, 15:17

**背景**: 地平线是中国领先的自动驾驶 AI 芯片供应商，其征程 6 系列面向不同级别的智能驾驶。征程 6M 是一款面向 10-20 万元车型的高性价比芯片，而征程 6H 提供更高的 AI 算力（128-560 TOPS），适用于城市 NOA。酷睿程成立于 2024 年，旨在为大众在中国本土化开发智驾系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://xueqiu.com/7832829622/387352612">地平线的2026:两张牌，一大招! 第一张牌：征程6m，闷声发大财的"走量王" 这张牌的核心是 "无敌性价比" 。地平线的征程6m芯片恰好卡在 ...</a></li>
<li><a href="https://www.fromgeek.com/internet/50-682887.html">地平线发布征程6P和6H智驾芯片及L2城区辅助驾驶系统HSD_极客网</a></li>
<li><a href="https://chejiahao.autohome.com.cn/info/25280993">大众的AI，不只要“上车”，更要“入魂”_车家号_发现车生活_汽车之家</a></li>

</ul>
</details>

**标签**: `#autonomous driving`, `#Horizon Robotics`, `#Volkswagen`, `#NOA`, `#ADAS`

---

<a id="item-15"></a>
## [美光 CEO 警告内存短缺可能持续到 2026 年后](https://www.ithome.com/0/954/436.htm) ⭐️ 7.0/10

美光 CEO 桑杰·梅赫罗特拉警告称，全球存储芯片短缺可能持续到 2026 年之后，新产能要到 2028 年才能释放，因为 AI 需求远超供应扩张速度。 这表明内存芯片面临长期结构性短缺，可能推高 AI 硬件和消费电子产品的成本，并重塑内存行业向 AI 专用产品倾斜。 美光正在缩减消费级存储业务并停掉部分产品线，以将产能转向 AI 加速器所需的高带宽内存（HBM），并计划在 2026 年大幅提高资本支出。

rss · IT HOME · May 23, 13:10

**背景**: 内存芯片制造是资本密集型行业，建设周期长；新晶圆厂通常需要数年才能投产。高带宽内存（HBM）是一种基于 3D 堆叠技术的 DRAM，为 AI 和图形处理器提供高带宽，其需求随 AI 热潮激增。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-hans/高頻寬記憶體">高带宽内存- 维基百科，自由的百科全书</a></li>
<li><a href="https://news.qq.com/rain/a/20251204A022JB00">美光退出消费级存储业务：Crucial走到尽头_腾讯新闻</a></li>
<li><a href="https://wallstreetcn.com/articles/3760683">存储市场“雪上加霜”？美光将退出“消费级存储业务”，聚焦AI存储芯片 - ...</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#memory shortage`, `#AI hardware`, `#industry analysis`

---

<a id="item-16"></a>
## [中国 600 公斤推力级涡扇发动机首飞成功](https://www.ithome.com/0/954/429.htm) ⭐️ 7.0/10

2025 年 5 月 23 日，中国自主研制的 600 公斤推力级 F406 涡扇发动机在内蒙古上空配装先进气象无人机圆满完成首次飞行试验。 这一里程碑标志着中国首次实现中小推力高端涡扇发动机的自主可控与国产化应用，将提升 1.5 至 4 吨级无人机能力，并支撑低空经济发展。 F406 发动机具有 1.5 万米高空、0.8 马赫高速、长航时和高可靠性等特点；从设计到 2024 年 12 月点火成功仅用了不到 8 个月。

rss · IT HOME · May 23, 11:55

**背景**: 涡扇发动机是一种利用风扇产生推力的喷气发动机，广泛用于飞机。中国一直致力于减少无人机和通用航空对外国发动机的依赖。F406 由中国航发四川天府轻型动力科技有限公司研制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.defensemirror.com/news/38500/China_Unveils_600_Kilogram_Thrust_Engines_for_Heavy__Long_endurance_Drones">China Unveils 600-Kilogram Thrust Engines for Heavy, Long ...</a></li>
<li><a href="https://www.globaltimes.cn/page/202412/1325912.shtml">China’s domestically developed 600kg thrust-class high-end ...</a></li>
<li><a href="https://www.newsglobenow.com/new363605.html">AECC F406 Turbofan Completes First Flight in Inner Mongolia</a></li>

</ul>
</details>

**标签**: `#aerospace`, `#turbofan engine`, `#drone technology`, `#low-altitude economy`

---

<a id="item-17"></a>
## [Grab 大规模工程支持的多智能体系统](https://www.infoq.cn/article/7DfZeiQH0zm08P88xIw9?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

该案例研究展示了多智能体系统在实际工程中的实用架构，说明了如何通过自动化支持任务来回收大量工程带宽。它为面临类似可扩展性挑战的其他大型组织提供了可复制的模式。 该系统对调查工作采用中心辐射型拓扑，对增强工作采用独立的单智能体系统，智能体按风险概况而非技能进行划分。它支持 Grab 分析数据仓库中的 1000 多名用户和超过 15000 张表。

rss · InfoQ 中文站 · May 24, 08:00

**背景**: 多智能体系统 (MAS) 涉及多个 AI 智能体协作解决复杂任务，每个智能体专注于不同的子任务。在软件工程中，MAS 越来越多地用于自动化支持、代码审查和维护，尤其是在大型语言模型 (LLM) 的驱动下。Grab 的方法因其基于风险的智能体分离而引人注目，这与典型的基于技能的设计不同。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.com/news/2026/05/grab-multi-agent-support-system/">Designing a Multi-Agent System for Engineering Support at ...</a></li>
<li><a href="https://engineering.grab.com/from-firefighting-to-building">From firefighting to building: How AI agents restored our ...</a></li>
<li><a href="https://victorinollc.com/thinking/grab-multi-agent-risk-architecture">Grab Split Its Agents by Risk Profile, Not by Skill</a></li>

</ul>
</details>

**标签**: `#multi-agent systems`, `#software engineering`, `#AI`, `#case study`, `#Grab`

---

<a id="item-18"></a>
## [SpaceX 星舰 V3 首飞基本成功](https://arstechnica.com/space/2026/05/spacexs-starship-v3-still-a-work-in-progress-mostly-successful-on-first-flight/) ⭐️ 7.0/10

SpaceX 于 2026 年 5 月 21 日发射了首枚星舰 V3 进行亚轨道试飞，完成了大部分目标，但未进入近地轨道。 星舰 V3 是为 NASA 阿尔忒弥斯登月任务设计的重大升级，此次测试使 SpaceX 更接近完全轨道能力，可能彻底改变太空运输。 V3 型号具有重大设计变更，包括增加推进剂容量和升级发动机，但在尝试轨道飞行前仍需进一步测试。

rss · Ars Technica · May 23, 17:54

**背景**: 星舰是 SpaceX 的全可重复使用超重型运载火箭。之前的版本（V1 和 V2）已进行多次亚轨道测试。近地轨道（LEO）是海拔 160–2000 公里的范围，大多数卫星和国际空间站运行于此。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Low_Earth_orbit">Low Earth orbit</a></li>

</ul>
</details>

**标签**: `#SpaceX`, `#Starship`, `#aerospace`, `#engineering`, `#space exploration`

---

<a id="item-19"></a>
## [不要自己实现加密](https://susam.net/do-not-roll-your-own.html) ⭐️ 7.0/10

该文章重申了避免自行实现加密和其他安全关键组件的知名安全原则，建议使用成熟的库和标准。 这一原则对软件工程师至关重要，因为自定义安全代码常含有细微缺陷，可能导致漏洞，而成熟的库经过严格测试和审查。 文章包含指向 Lobsters 评论的链接，暗示可能有富有洞察力的社区讨论。它提醒开发者抵制实现自己安全解决方案的诱惑。

rss · Lobsters · May 23, 07:44

**背景**: 加密和安全关键组件以难以正确实现而闻名。即使是经验丰富的开发者也可能会犯下危及安全的错误。成熟的库如 OpenSSL、libsodium 和 NaCl 经过了广泛的同行评审，被广泛信任。

**标签**: `#security`, `#software engineering`, `#best practices`, `#cryptography`

---

<a id="item-20"></a>
## [Jira 工作流被证明是图灵完备的](https://seriot.ch/computation/jira.html) ⭐️ 7.0/10

一篇文章证明 Jira 的工作流系统是图灵完备的，意味着它可以模拟任何计算，只要复杂度足够。通过使用 Jira 的工作流转换和条件编码一个循环标签系统（一种已知的图灵完备自动机）来展示这一点。 这一发现揭示了 Jira 工作流可能被用于非预期的复杂计算，可能导致维护噩梦和安全风险。它也强调了理解软件工程中广泛使用的工具的理论极限的重要性。 该证明利用 Jira 的工作流条件和后置函数实现了一个循环标签系统，该系统是图灵完备的。作者指出，虽然理论上可行，但实际用于计算将极其繁琐且低效。

rss · Lobsters · May 23, 18:55

**背景**: 图灵完备是可计算性理论中的一个概念：如果一个系统可以模拟任何图灵机，那么它就是图灵完备的，意味着只要有足够的时间和内存，它可以执行任何计算。Jira 是一个流行的项目管理工具，它使用工作流来定义问题状态转换，通常带有条件和触发器。文章展示了这些工作流元素可以组合起来创建任意逻辑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Turing_completeness">Turing completeness - Wikipedia</a></li>
<li><a href="https://www.atlassian.com/software/jira/guides/workflows/overview">Introduction to Jira Workflows | Atlassian</a></li>

</ul>
</details>

**社区讨论**: Lobsters 上的讨论可能探讨了这一发现的实际意义和幽默之处，一些用户指出虽然技术上很有趣，但这是关于工作流复杂性的警示故事。其他人可能争论这是 bug 还是特性。

**标签**: `#Jira`, `#Turing-complete`, `#software engineering`, `#workflow`

---

<a id="item-21"></a>
## [R7RS Large 过程分册初稿发布](https://r7rs.org/large/fascicles/proc/) ⭐️ 7.0/10

Scheme 工作组 2 发布了 R7RS-Large 过程分册的初稿，该分册引入了在 lambda 等主体中混合定义和表达式的能力。 这一变化允许内部定义出现在表达式之后，简化了 Scheme 编程，使代码更加灵活和可读。这是最终确定 R7RS-Large 标准的重要一步。 该草案涵盖了块编程形式，如 lambda、let、if、or 和 set!。新功能允许定义与表达式混合，如示例所示，在 unless 表达式之后放置了一个 define。

rss · Lobsters · May 23, 20:11

**背景**: Scheme 是一种极简的 Lisp 方言，以其清晰的语义而闻名。R7RS 是 Scheme 标准的第七次修订，分为小型语言（R7RS-small）和大型语言（R7RS-large）以满足实际需求。过程分册是 R7RS-large 基础的一部分，规定了核心过程构造。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://codeberg.org/scheme/r7rs">scheme/r7rs: Central repository for development of the R7RS ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Scheme_(programming_language)">Scheme (programming language) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Scheme`, `#R7RS`, `#language design`, `#standardization`

---

<a id="item-22"></a>
## [sp.h：为 C 语言提出的新标准库](https://spader.zone/sp/) ⭐️ 7.0/10

一位开发者推出了 sp.h，这是一个用纯 C99 编写的 15000 行单头文件库，旨在作为 C 语言的现代标准库，提升安全性和易用性。 C 语言在系统编程中仍被广泛使用，但其标准库缺乏现代安全特性；sp.h 可以在不放弃 C 语言的前提下减少漏洞并提高开发效率。 该库是一个用 C99 编写的单头文件 (sp.h)，包含示例程序和扩展库，并在 GitHub 上提供。它旨在解决常见的 C 语言陷阱，如缓冲区溢出和内存管理问题。

rss · Lobsters · May 23, 05:31

**背景**: C 语言的标准库几十年来基本保持不变，缺乏现代语言提供的内置安全机制，这导致基于 C 的软件普遍存在安全漏洞。像 sp.h 这样的提议旨在在不破坏向后兼容性的前提下，为 C 语言增加安全性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://vuink.com/post/fcnqre-d-dmbar/sp">sp.h is the standard library that C deserves - vuink.com</a></li>

</ul>
</details>

**社区讨论**: Lobste.rs 上的讨论可能包括对 sp.h 可行性和完整性的辩论、与现有注重安全的 C 库的比较，以及对采用和维护的担忧。

**标签**: `#C`, `#standard library`, `#systems programming`, `#safety`

---

<a id="item-23"></a>
## [仍与 C++不兼容的 C 语言构造](https://lospino.so/blog/c-constructs-that-still-dont-work-in-cpp/) ⭐️ 7.0/10

一篇博文分析了仍与 C++不兼容的 C 语言构造，以及那些随时间推移已被修复的构造。 这很重要，因为 C 和 C++是广泛使用的语言，长期存在兼容性问题，影响着数百万处理混合代码库的开发者。 该文章可能涵盖特定构造，如变长数组、指定初始化器以及在 C 和 C++之间存在差异的隐式转换。

rss · Lobsters · May 23, 15:18

**背景**: C 和 C++是不同的语言，共享一个公共子集，但并非所有有效的 C 代码都能作为 C++编译。多年来，C++标准解决了一些不兼容问题，而其他问题由于基本设计差异而持续存在。

**社区讨论**: Lobsters 上的讨论可能包括开发者在实践中遇到这些问题的见解，一些人主张更好的兼容性，另一些人则捍卫 C++的设计选择。

**标签**: `#C`, `#C++`, `#compatibility`, `#language design`

---

<a id="item-24"></a>
## [苹果 MIE 安全机制首次被公开绕过](https://ironpeak.be/blog/bypassing-apple-mie/) ⭐️ 7.0/10

安全研究人员公开了首个绕过苹果内存完整性强制（MIE）的漏洞利用，该漏洞针对运行 macOS 26.4.1 的 M5 芯片，实现了内核内存破坏。 这一突破表明，即使是苹果最新的硬件级内存安全特性 MIE 也并非无懈可击，可能影响系统级防御，并推动进一步的安全研究。 该漏洞利用针对运行 macOS 26.4.1 的苹果 M5 芯片，由 Calif 的研究人员于 2026 年 5 月披露。这是首个公开的绕过 MIE 的内核内存破坏漏洞利用。

rss · Lobsters · May 24, 00:10

**背景**: 苹果的内存完整性强制（MIE）是一种始终开启的硬件与操作系统结合的内存安全防御机制，随 A19 和 M5 芯片引入。它结合了内存标记（EMTE）和安全内存分配器，旨在防止内存破坏攻击。该漏洞利用表明，即使如此先进的防护措施也可能被绕过。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ironpeak.be/blog/bypassing-apple-mie/">Pardon MIE ? - ironPeak Blog</a></li>
<li><a href="https://dasroot.net/posts/2026/05/first-public-macos-kernel-memory-corruption-exploit-on-apple-silicon-m5/">First Public macOS Kernel Memory Corruption Exploit on Apple Silicon M5 · Technical news about AI, coding and all</a></li>
<li><a href="https://www.scworld.com/brief/researchers-bypass-apples-m5-security-with-ai-powered-macos-exploit">Researchers bypass Apple’s M5 security with AI-powered macOS exploit | brief | SC Media</a></li>

</ul>
</details>

**社区讨论**: Lobste.rs 上的讨论可能包含专家对绕过技术细节和影响的评论，一些人表达了对硬件安全功能有效性的担忧。

**标签**: `#security`, `#Apple`, `#bypass`, `#MIE`, `#systems`

---

<a id="item-25"></a>
## [SPy：一个带解释器和编译器的静态类型 Python 变体](https://github.com/spylang/spy) ⭐️ 7.0/10

SPy 是一种新的编程语言，它同时作为静态类型 Python 变体的解释器和编译器，旨在提升性能和类型安全性。 该项目可能显著提升 Python 的性能和类型安全性，使其更适合大规模和性能关键型应用，同时保留 Python 的语法和动态特性。 SPy 被设计为可静态编译，同时保留 Python 的许多动态特性，并在 GitHub 上的 spylang/spy 仓库中可用。

rss · Lobsters · May 23, 05:51

**背景**: Python 是动态类型的，这提供了灵活性，但可能导致运行时错误和性能开销。像 C++或 Java 这样的语言使用的静态类型可以在编译时捕获类型错误并实现优化。SPy 旨在通过提供一种具有静态类型和编译功能的类 Python 语言来弥合这一差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/spylang/spy">GitHub - spylang/spy: SPy language · GitHub</a></li>
<li><a href="https://news.ycombinator.com/item?id=45761594">SPy: An interpreter and compiler for a fast statically typed variant of Python | Hacker News</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论强调作者专注于解释该语言的哲学，这可能有助于它感觉像一种具有独特优势的新语言。一些评论者指出，类似的想法以前也有人提出过，但 SPy 在性能方面的做法与众不同。

**标签**: `#Python`, `#compiler`, `#static typing`, `#programming languages`

---

<a id="item-26"></a>
## [Go 语言中丢弃权限的技术指南](https://log.0x21.biz/posts/go-privdrop/) ⭐️ 7.0/10

一篇关于在 Go 程序中正确丢弃权限的详细指南已发布，涵盖了系统调用和权限分离的最佳实践。 该指南帮助 Go 开发者避免常见陷阱，编写更安全的特权进程，这对于需要绑定低端口或访问敏感资源的服务至关重要。 该指南解释了如何在调用 setuid 之前手动设置 net.Listener，因为在丢弃权限后无法使用 http.ListenAndServe。它还涵盖了使用 setuid、setgid 和 chroot 等系统调用。

rss · Lobsters · May 23, 13:47

**背景**: 权限分离是一种安全技术，程序分为两个进程：执行敏感操作的特权父进程和处理不可信输入的非特权子进程。在 Go 中，正确丢弃权限需要谨慎处理文件描述符和系统调用，因为标准库的 HTTP 辅助函数假设拥有完整权限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://stackoverflow.com/questions/41248866/golang-dropping-privileges-v1-7">security - Golang dropping privileges (v1.7) - Stack Overflow Code sample</a></li>
<li><a href="https://codeberg.org/oxzi/go-privsep-showcase">oxzi/go-privsep-showcase: Dropping Privileges and Privilege ...</a></li>
<li><a href="https://github.com/sid77/drop">GitHub - sid77/drop: An easy way for dropping privileges in Go</a></li>

</ul>
</details>

**社区讨论**: Lobsters 上的讨论强调了该主题的重要性，并分享了 go-privsep-showcase 仓库等额外资源。一些评论者指出正确实现的复杂性以及 Go 需要更多内置支持。

**标签**: `#Go`, `#security`, `#privilege separation`, `#syscalls`

---