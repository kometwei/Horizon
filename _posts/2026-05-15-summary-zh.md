---
layout: default
title: "Horizon Summary: 2026-05-15 (ZH)"
date: 2026-05-15
lang: zh
---

> 从 144 条内容中筛选出 39 条重要资讯

---

1. [首个公开的 Apple M5 macOS 内核漏洞利用](#item-1) ⭐️ 9.0/10
2. [Bun 从 Zig 重写为 Rust 已合并](#item-2) ⭐️ 9.0/10
3. [零日漏洞绕过 Windows 11 BitLocker 加密](#item-3) ⭐️ 9.0/10
4. [vLLM v0.21.0：重大变更、KV 卸载、推测解码](#item-4) ⭐️ 8.0/10
5. [从 2024 款 RAV4 混动版中移除调制解调器和 GPS](#item-5) ⭐️ 8.0/10
6. [Antirez 发布 DS4：面向 DeepSeek 4 的 LLM 推理运行时](#item-6) ⭐️ 8.0/10
7. [Codex 现已集成到 ChatGPT 移动应用](#item-7) ⭐️ 8.0/10
8. [RTX 5090 外接显卡在 M4 MacBook Air 上实现游戏与 LLM 突破](#item-8) ⭐️ 8.0/10
9. [新 Nginx 漏洞利用重写和设置指令](#item-9) ⭐️ 8.0/10
10. [arXiv 对虚假参考文献实施一年禁令](#item-10) ⭐️ 8.0/10
11. [硬盘固件破解：逆向工程与解密](#item-11) ⭐️ 8.0/10
12. [SpaceX 最快下周披露 IPO 招股书，目标募资超 7000 亿美元](#item-12) ⭐️ 8.0/10
13. [苹果基于 Intel 18A-P 开发 A/M 系列处理器以分散供应链](#item-13) ⭐️ 8.0/10
14. [Linux 页面缓存漏洞：Copy Fail 与 Dirty Frag](#item-14) ⭐️ 8.0/10
15. [安大略审计发现 AI 笔记生成器捏造治疗转诊](#item-15) ⭐️ 8.0/10
16. [IBM 发布开源多语言嵌入模型，支持 32K 上下文](#item-16) ⭐️ 8.0/10
17. [ssh-keysign-pwn：非特权用户可读取 root 拥有的文件](#item-17) ⭐️ 8.0/10
18. [Abridge：AI 原生医疗为临床医生节省 20 小时](#item-18) ⭐️ 8.0/10
19. [Ollama v0.24.0 集成 Codex 应用](#item-19) ⭐️ 7.0/10
20. [Amazonbot 终于遵守 robots.txt](#item-20) ⭐️ 7.0/10
21. [MIT 校长警告资金危机与人才管道问题](#item-21) ⭐️ 7.0/10
22. [黑客伪造苹果与雅虎 CDN 域名部署远程木马](#item-22) ⭐️ 7.0/10
23. [AMD EPYC 在 2026 年第一季度创下 46.2% 的服务器营收份额纪录](#item-23) ⭐️ 7.0/10
24. [TanStack 供应链攻击迫使 Mac 版 ChatGPT 更新](#item-24) ⭐️ 7.0/10
25. [AT&T、T-Mobile、Verizon 组建卫星合资企业消除信号盲区](#item-25) ⭐️ 7.0/10
26. [新 iPhone 盗窃骗局利用查找联系人号码钓鱼](#item-26) ⭐️ 7.0/10
27. [国内首枚高校主导的面对称可回收液体火箭成功垂直起降](#item-27) ⭐️ 7.0/10
28. [基于半监督评测的 UI 自动化生产实践](#item-28) ⭐️ 7.0/10
29. [AWS WorkSpaces 现允许 AI 智能体操作遗留桌面应用](#item-29) ⭐️ 7.0/10
30. [本地优先 AI 推理实现高性价比文档处理](#item-30) ⭐️ 7.0/10
31. [前 Qwen 负责人林俊旸创业，新 AI Lab 估值 136 亿元](#item-31) ⭐️ 7.0/10
32. [Netflix 推出模型生命周期图，助力企业级 MLOps](#item-32) ⭐️ 7.0/10
33. [谷歌 DORA 报告：工程基础决定 AI 投资回报](#item-33) ⭐️ 7.0/10
34. [能源供应商优先服务数据中心，弃置太浩湖居民](#item-34) ⭐️ 7.0/10
35. [浏览器对大型网站区别对待](#item-35) ⭐️ 7.0/10
36. [通行密钥能取代密码吗？](#item-36) ⭐️ 7.0/10
37. [C++26 引入 SIMD 库引发争议](#item-37) ⭐️ 7.0/10
38. [Mandy 将 ActivityPub 引入 Goblins](#item-38) ⭐️ 7.0/10
39. [前部署工程在技术变革中再度兴起](#item-39) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [首个公开的 Apple M5 macOS 内核漏洞利用](https://blog.calif.io/p/first-public-kernel-memory-corruption) ⭐️ 9.0/10

安全公司 Calif 在 Anthropic 的 Mythos Preview AI 帮助下，仅用五天就构建了一个针对 Apple M5 芯片的 macOS 内核内存破坏漏洞利用，绕过了苹果五年的软硬件安全努力。 这是首个公开的 Apple M5 芯片内核漏洞利用演示，表明即使像内存标记扩展（MTE）这样的先进硬件防御也可能被绕过，对苹果的安全声誉和整个行业具有重大影响。 该漏洞利用是在五天内使用 Anthropic 的 Claude Mythos AI 预览版开发的，该 AI 帮助识别漏洞并协助开发。一份 55 页的技术报告详细说明了发现。

hackernews · Lobsters · May 14, 18:25 · [社区讨论](https://news.ycombinator.com/item?id=48139219)

**背景**: Apple M5 芯片包含内存完整性强制（MIE）并依赖 ARM 的内存标记扩展（MTE）来防止内存破坏攻击。MTE 为内存分配分配随机标签，使攻击者更难破坏内存。该漏洞利用表明即使这些保护措施也可能被克服。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.calif.io/p/first-public-kernel-memory-corruption">First public macOS kernel memory corruption exploit on Apple M 5</a></li>
<li><a href="https://9to5mac.com/2026/05/14/calif-team-details-how-anthropic-mythos-helped-build-a-working-macos-exploit-in-five-days/">Anthropic Mythos helped Calif build a macOS exploit in five... - 9to5Mac</a></li>
<li><a href="https://decrypt.co/367925/apple-mac-m5-system-exploited-anthropic-claude-mythos-ai">Apple Mac M 5 System Exploited With Anthropic's Claude... - Decrypt</a></li>

</ul>
</details>

**社区讨论**: 评论者对漏洞利用的开发速度感到惊讶，并质疑它如何绕过 MTE。一些人推测该漏洞在苹果漏洞赏金计划中的潜在价值，而另一些人则讽刺地认为苹果可能是在编造漏洞来炒作 AI。

**标签**: `#macOS`, `#kernel exploit`, `#Apple M5`, `#security`, `#memory corruption`

---

<a id="item-2"></a>
## [Bun 从 Zig 重写为 Rust 已合并](https://github.com/oven-sh/bun/pull/30412) ⭐️ 9.0/10

Bun JavaScript 运行时已合并一个拉取请求，将其代码库从 Zig 重写为 Rust，新增超过 100 万行 Rust 代码，并删除了 4,024 行 Zig 代码。 这一重写标志着一个广泛使用的 JavaScript 运行时的重大架构转变，可能提升内存安全性和开发者生产力，同时引发了社区关于语言权衡和软件复杂性的讨论。 重写耗时约一周，并附有将 Zig 惯用法映射到 Rust 的详细说明。代码库现在包含超过 10,000 个 `unsafe` 块，分布在 736 个文件中，表明在性能关键区域需要手动管理安全性。

hackernews · Chaoses · May 14, 08:15 · [社区讨论](https://news.ycombinator.com/item?id=48132488)

**背景**: Bun 是一个快速的全能 JavaScript 运行时、打包器和包管理器，旨在作为 Node.js 的即插即用替代品。它最初使用 Zig 编写，Zig 是一种注重简洁性和性能的低级系统语言。Rust 是另一种以无垃圾回收的内存安全性而闻名的系统语言，因此成为性能关键型软件的热门选择。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：一些人赞扬详细的迁移指南和准备工作，而另一些人则对大量 `unsafe` 块以及 Bun 代码库日益增长的复杂性表示担忧，其规模已接近 Rust 编译器本身。Bun 的一位维护者指出，Rust 消除了许多内存错误，但无法防止所有问题，尤其是涉及 JavaScript 边界穿越的问题。

**标签**: `#Bun`, `#Rust`, `#JavaScript runtime`, `#rewrite`, `#software engineering`

---

<a id="item-3"></a>
## [零日漏洞绕过 Windows 11 BitLocker 加密](https://arstechnica.com/security/2026/05/zero-day-exploit-completely-defeats-default-windows-11-bitlocker-protections/) ⭐️ 9.0/10

一个名为 YellowKey 的零日漏洞已被公开，该漏洞通过物理访问完全绕过 Windows 11 系统的默认 BitLocker 加密，可在几分钟内完全访问加密驱动器。 该漏洞影响数百万依赖 BitLocker 进行数据保护的 Windows 11 用户和企业系统，因为它破坏了针对设备物理盗窃的主要防御手段。 该漏洞位于 Windows 恢复环境（WinRE）中，仅影响 Windows 11、Windows Server 2022 和 Windows Server 2025；微软已确认正在调查。

rss · Ars Technica · May 14, 18:32

**背景**: BitLocker 是 Windows 内置的全盘加密功能，用于保护丢失或被盗设备上的数据。YellowKey 漏洞利用 Windows 恢复环境中的缺陷，无需解密密钥即可绕过加密。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arstechnica.com/security/2026/05/zero-day-exploit-completely-defeats-default-windows-11-bitlocker-protections/">Zero-day exploit completely defeats default Windows 11 ...</a></li>
<li><a href="https://cybersecuritynews.com/windows-bitlocker-0-day-vulnerability/">Windows BitLocker 0-Day Vulnerability Enables Access to ...</a></li>
<li><a href="https://thehackernews.com/2026/05/windows-zero-days-expose-bitlocker.html">Windows Zero-Days Expose BitLocker Bypasses And CTFMON ...</a></li>

</ul>
</details>

**标签**: `#security`, `#zero-day`, `#Windows 11`, `#BitLocker`, `#exploit`

---

<a id="item-4"></a>
## [vLLM v0.21.0：重大变更、KV 卸载、推测解码](https://github.com/vllm-project/vllm/releases/tag/v0.21.0) ⭐️ 8.0/10

vLLM v0.21.0 引入了重大构建变更（需要 C++20 编译器、迁移至 transformers v5）、结合混合内存分配器（HMA）的 KV 卸载、支持推理模型思考预算的推测解码，以及面向 Blackwell GPU 的新 TOKENSPEED_MLA 注意力后端。 此版本显著提升了大型推理模型和混合架构的推理效率，同时重大变更确保了与现代 PyTorch 和 transformers 的兼容性。新的 Blackwell 后端为 DeepSeek-R1 和 Kimi-K25 等模型提供了更快的预填充和解码。 该版本包含来自 202 位贡献者的 367 次提交，弃用了 transformers v4，并要求 C++20。HMA 集成实现了对具有多种注意力类型的混合模型的高效 KV 缓存管理，推测解码现在尊重推理/思考预算。

github · khluu · May 14, 23:15

**背景**: vLLM 是一个高吞吐量、内存高效的 LLM 推理引擎。混合内存分配器（HMA）将具有相同注意力类型的层分组，以高效分配 KV 缓存块，这对于结合滑动窗口和全局注意力的混合模型至关重要。推测解码通过使用草稿模型生成候选令牌，然后由目标模型验证来加速推理；思考预算确保推理模型在生成答案前为思维链分配足够的令牌。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/vllm-project/vllm/issues/11382">[RFC]: Hybrid Memory Allocator · Issue #11382 · vllm-project/vllm</a></li>
<li><a href="https://docs.vllm.ai/en/latest/design/hybrid_kv_cache_manager/">Hybrid KV Cache Manager - vLLM</a></li>
<li><a href="https://fenado.ai/articles/lightseek-foundation-unveils-open-source-tokenspeed-llm-engine-with-vllm-integration-for-nvidia-blackwell">LightSeek Foundation Unveils Open-Source TokenSpeed LLM Engine with vLLM Integration for NVIDIA Blackwell | TokenSpeed, LLM inference engine, Fenado AI</a></li>

</ul>
</details>

**社区讨论**: 社区一直在积极讨论这些重大变更，一些用户对迁移到 transformers v5 和 C++20 的工作量表示担忧。然而，许多用户赞赏性能改进和新功能，特别是 HMA 集成和推测解码增强。

**标签**: `#vLLM`, `#LLM inference`, `#breaking changes`, `#GPU optimization`, `#speculative decoding`

---

<a id="item-5"></a>
## [从 2024 款 RAV4 混动版中移除调制解调器和 GPS](https://arkadiyt.com/2026/05/13/removing-the-modem-and-gps-from-my-rav4/) ⭐️ 8.0/10

一份详细指南说明了如何从 2024 款 RAV4 混动版中物理移除调制解调器和 GPS 天线以阻止遥测数据收集，并指出蓝牙连接仍会通过手机网络泄露数据。 这很重要，因为现代汽车会收集大量遥测数据，常与保险公司或第三方共享，而本指南让车主能够通过硬件改造重新获得隐私。 移除调制解调器会禁用丰田安全连接和远程服务，但通过 USB 使用 CarPlay 不会传输遥测数据，而蓝牙则会。移除 GPS 天线可能影响导航精度。

hackernews · arkadiyt · May 14, 17:08 · [社区讨论](https://news.ycombinator.com/item?id=48138136)

**背景**: 像 2024 款 RAV4 混动版这样的现代汽车配备了远程信息处理控制单元（TCU），包含蜂窝调制解调器和 GPS 接收器，以启用联网服务并收集驾驶数据。这些数据可用于车辆诊断、紧急服务，有时在车主同意的情况下与保险公司共享。物理移除 TCU 是一种极端的隐私保护措施，会禁用所有联网功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48138136">Removing the Modem and GPS from My 2024 RAV 4 Hybrid</a></li>
<li><a href="https://www.justanswer.com/car/qkdpr-2024-toyota-rav4-hybrid-telematics-control-module-location.html">2024 RAV 4 Hybrid : Telematics Module Guide & Tips</a></li>
<li><a href="https://www.toyota.com/connected-services/toyota-app/">Toyota App</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了替代方法，如拔掉保险丝（例如福特 Maverick），并指出丰田仅在车主同意的情况下才会与保险公司共享数据。有人对丰田拒绝修复 GPS 问题表示沮丧，而其他人则强调蓝牙网络共享仍可能泄露遥测数据。

**标签**: `#privacy`, `#automotive`, `#telematics`, `#hardware hacking`, `#data ownership`

---

<a id="item-6"></a>
## [Antirez 发布 DS4：面向 DeepSeek 4 的 LLM 推理运行时](https://antirez.com/news/165) ⭐️ 8.0/10

Antirez 宣布了 DS4，这是一个小型 LLM 推理运行时，专门针对配备 96GB 内存的 MacBook 优化以运行 DeepSeek 4，主要支持 Metal，并额外支持 NVIDIA CUDA 和 AMD ROCm 后端。 DS4 将接近 Claude 质量的本地 AI 推理带到高端消费硬件上，展示了强大的 LLM 可以在本地运行而无需依赖云端，这可能加速私有、离线 AI 助手的普及。 该项目基于 llama.cpp 和 GGML 构建，社区反馈指出 DS4 使用的 imatrix 量化优于 OpenRouter 上其他可用的量化方式，并且该模型表现出意外的自我意识，能够识别自己的服务器进程。

hackernews · caust1c · May 14, 22:29 · [社区讨论](https://news.ycombinator.com/item?id=48142108)

**背景**: LLM 推理运行时是加载并在本地硬件上执行大型语言模型的软件框架，支持离线使用和隐私保护。DeepSeek 4 是 DeepSeek 最近推出的开放权重模型系列，提供高性能并支持百万 token 上下文。DS4 是一个专注且精简的运行时，旨在让 DeepSeek 4 能够在具有足够统一内存的 Apple Silicon Mac 上运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cometapi.com/deepseek-v4-released-what-is-and-how-to-access/">Deepseek v4 released: What is and How to Access</a></li>
<li><a href="https://developer.nvidia.com/blog/build-with-deepseek-v4-using-nvidia-blackwell-and-gpu-accelerated-endpoints/">Build with DeepSeek V4 Using NVIDIA Blackwell and GPU ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 DS4 的性能表示兴奋，一位用户指出尽管速度较慢，但其质量接近 Claude。另一位用户质疑扩展趋势，想知道几年后这种智能是否能在 16GB 内存上运行。还有评论提到 antirez 的推文，称 GPT-5.5 在底层优化工作上比 Opus 更有帮助。

**标签**: `#LLM`, `#inference`, `#DeepSeek`, `#local AI`, `#antirez`

---

<a id="item-7"></a>
## [Codex 现已集成到 ChatGPT 移动应用](https://openai.com/index/work-with-codex-from-anywhere/) ⭐️ 8.0/10

OpenAI 已将其 AI 编程代理 Codex 集成到 ChatGPT 移动应用中，用户现在可以在 iOS 和 Android 设备上免费使用 AI 辅助编程。 这一集成使强大的 AI 编程辅助功能在移动设备上可用，降低了开发者在移动中编程的门槛，并可能扩大 AI 辅助开发的用户基础。 Codex 包含在 ChatGPT 的免费套餐中，但交互数据可能用于训练。移动应用支持通过侧边栏中的“Codex”功能远程控制桌面上运行的 Codex。

hackernews · OpenAI News · May 14, 20:06 · [社区讨论](https://news.ycombinator.com/item?id=48140529)

**背景**: Codex 是 OpenAI 推出的一套 AI 驱动的编程代理，可自动化软件工程任务。它可以通过 CLI 或桌面应用本地运行，现在也可以通过 ChatGPT 移动应用使用，使开发者能够将编程活动委托给 AI。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/OpenAI_Codex">OpenAI Codex</a></li>
<li><a href="https://github.com/openai/codex/releases">Releases · openai / codex</a></li>
<li><a href="https://github.com/openai/codex">GitHub - openai / codex : Lightweight coding agent that runs in your...</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 Codex 免费感到兴奋，有人指出它包含在免费套餐中。然而，一些用户报告称，由于屏幕尺寸和输入限制，移动端的使用效果不如桌面端；还有人对不同平台之间的设置差异感到困惑。

**标签**: `#OpenAI`, `#Codex`, `#AI coding assistant`, `#mobile app`, `#ChatGPT`

---

<a id="item-8"></a>
## [RTX 5090 外接显卡在 M4 MacBook Air 上实现游戏与 LLM 突破](https://scottjg.com/posts/2026-05-05-egpu-mac-gaming/) ⭐️ 8.0/10

一位开发者通过 Thunderbolt 5 成功将 Nvidia RTX 5090 外接显卡连接到 M4 MacBook Air，实现了可玩的游戏体验和显著更快的 LLM 推理速度，而 macOS 官方并不支持 Apple Silicon 上的外接显卡。 这一变通方案表明，外接显卡仍可为 Apple Silicon Mac 的游戏和 AI 等 GPU 密集型任务带来好处，挑战了苹果的官方立场，并为需要额外图形性能的 Mac 用户开辟了新的可能性。 该设置使用 Thunderbolt 5 外接盒，并需要自定义驱动或虚拟机 GPU 直通，因为 macOS 缺乏原生 Nvidia 驱动支持。基准测试显示，RTX 5090 外接显卡的 LLM 提示处理速度比 M4 内置 GPU 快达两倍。

hackernews · allenleee · May 14, 15:47 · [社区讨论](https://news.ycombinator.com/item?id=48137145)

**背景**: Apple Silicon Mac 使用统一内存，官方不支持外接显卡，而 Intel Mac 则支持。M4 MacBook Air 没有独立显卡，因此在游戏和 AI 工作负载方面能力较弱。该项目使用 Thunderbolt 5 外接显卡盒和软件变通方案来绕过这些限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://support.apple.com/en-us/102363">Use an external graphics processor with your Mac - Apple Support</a></li>
<li><a href="https://www.reddit.com/r/gpu/comments/1nzetms/3000_rtx_5090_external_gpu_gets_tested_native/">r/gpu on Reddit: $3,000 RTX 5090 external GPU gets tested, native benchmarks show it's slower than a 4090 on average</a></li>
<li><a href="https://www.theverge.com/pc-gaming/606006/nvidia-rtx-5090-egpu-gaming-handheld-oculink-test-pcie-minisforum-deg1">I plugged an Nvidia RTX 5090 into a gaming handheld | The Verge</a></li>

</ul>
</details>

**社区讨论**: 社区对这一技术成就印象深刻，许多人指出此前认为 Apple Silicon 无法使用外接显卡。一些评论者强调 LLM 推理改进是最实用的好处，而另一些人则对苹果不官方支持这一用例表示失望。

**标签**: `#eGPU`, `#Apple Silicon`, `#gaming`, `#LLM inference`, `#macOS`

---

<a id="item-9"></a>
## [新 Nginx 漏洞利用重写和设置指令](https://github.com/DepthFirstDisclosures/Nginx-Rift) ⭐️ 8.0/10

一个名为 Nginx-Rift 的新 Nginx 漏洞利用被公开，它针对 rewrite 和 set 指令，声称可以绕过 ASLR，但发布的验证代码要求 ASLR 被禁用。 该漏洞意义重大，因为 Nginx 是最广泛使用的 Web 服务器之一，且该利用针对常见的配置模式，在特定条件下可能允许远程代码执行。 该利用要求 rewrite 指令的替换字符串中包含问号，并且后续有一个 set 指令引用正则捕获组（例如 set $var $1）。F5 已为 1.31.0 和 1.30.1 版本发布补丁，并提供了使用命名捕获代替未命名捕获的缓解措施。

hackernews · hetsaraiya · May 14, 17:17 · [社区讨论](https://news.ycombinator.com/item?id=48138268)

**背景**: Nginx 是一种流行的开源 Web 服务器，使用 rewrite 和 set 等指令进行 URL 操作和变量赋值。ASLR（地址空间布局随机化）是一种安全技术，通过随机化内存地址来增加利用难度。该漏洞利用针对这些指令中处理正则捕获时的内存损坏漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nginx.org/en/docs/http/ngx_http_rewrite_module.html">Module ngx_http_rewrite_module - nginx</a></li>

</ul>
</details>

**社区讨论**: 社区正在积极讨论其严重性，一些安全专家认为，即使验证代码要求 ASLR 禁用，也应认真对待声称的 ASLR 绕过。其他人指出 ASLR 提供了有效保护，并且使用命名捕获的缓解措施很简单。

**标签**: `#nginx`, `#security`, `#exploit`, `#vulnerability`, `#web-server`

---

<a id="item-10"></a>
## [arXiv 对虚假参考文献实施一年禁令](https://twitter.com/tdietterich/status/2055000956144935055) ⭐️ 8.0/10

arXiv 推出新政策，对提交含有虚假参考文献的论文的作者实施一年禁令，并要求后续提交的论文必须先被知名同行评审场所接受，才能在 arXiv 上发布。 该政策直接应对了科学提交中日益严重的 AI 生成虚假参考文献问题，这一问题损害了研究诚信。它设立了明确的威慑，鼓励作者仔细核实引用，惠及整个科学界。 该禁令适用于含有虚假参考文献的提交，禁令结束后，作者必须让论文被知名场所接受后才能重新提交到 arXiv。据报道，该政策已计划但可能尚未生效，因为 arXiv 的政策页面上尚未明确列出。

hackernews · gjuggler · May 14, 20:39 · [社区讨论](https://news.ycombinator.com/item?id=48140922)

**背景**: 虚假参考文献是由 AI 语言模型生成的看似真实但实际虚构的引用，这是学术出版中日益严重的问题。arXiv 是一个免费的预印本存储库，广泛应用于物理学、数学、计算机科学及相关领域。新政策旨在维护提交内容的质量和可信度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://info.arxiv.org/help/submit_sword.html">SWORD/APP Deposit API User's Manual - arXiv info</a></li>
<li><a href="https://www.nature.com/articles/d41586-026-00969-z">Hallucinated citations are polluting the scientific ... - Nature</a></li>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC13051339/">Hallucinated citations produced by generative artificial ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论大多表示支持，用户称该政策“对科学非常有益”，并指出 arXiv 是一种特权而非权利。一些人表达了对实施的谨慎态度，例如在禁令前确保仔细审查，而另一些人则批评反对该政策的 LLM 爱好者。

**标签**: `#arXiv`, `#AI ethics`, `#scientific publishing`, `#hallucination`, `#policy`

---

<a id="item-11"></a>
## [硬盘固件破解：逆向工程与解密](https://icode4.coffee/?p=1465) ⭐️ 8.0/10

一篇关于逆向工程和破解硬盘固件的详细技术文章已发布，展示了绕过加密并从硬盘中提取解密固件的方法。 这项研究暴露了硬盘固件安全中的漏洞，可能使攻击者绕过硬件磁盘加密并访问敏感数据。它凸显了厂商需要加强固件保护和透明度的必要性。 文章涵盖了在各种 HDD 和 SSD 上转储、逆向工程和修改固件的方法。社区评论揭示，某些厂商的固件更新工具在上传前会解密固件，通过 seccomp 系统调用过滤即可轻松提取。

hackernews · Lobsters · May 14, 16:19 · [社区讨论](https://news.ycombinator.com/item?id=48137553)

**背景**: 硬盘固件控制驱动器的内部操作，包括加密和数据访问。研究人员此前已展示过 SSD 加密中的缺陷，通过修改固件或使用调试接口可以绕过密码保护。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://icode4.coffee/?p=1465">HDD Firmware Hacking Part 1 – I Code 4 Coffee</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/flaws-in-popular-ssd-drives-bypass-hardware-disk-encryption/">Flaws in Popular SSD Drives Bypass Hardware Disk Encryption</a></li>
<li><a href="https://github.com/chrivers/samsung-firmware-magic">GitHub - chrivers/samsung- firmware -magic: Tool for decrypting the...</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了实际攻击向量，例如使用 seccomp 从厂商更新程序中截获解密固件，并引用了关于三星 SSD 固件反编译的相关工作。一些评论者还指出 NSA 历史上对硬盘固件破解的兴趣。

**标签**: `#firmware hacking`, `#reverse engineering`, `#hard drive security`, `#embedded systems`

---

<a id="item-12"></a>
## [SpaceX 最快下周披露 IPO 招股书，目标募资超 7000 亿美元](https://www.ithome.com/0/950/664.htm) ⭐️ 8.0/10

SpaceX 计划最快于下周公开其 IPO 招股说明书，目标在 2026 年 6 月 8 日启动路演。此次发行预计募资 7000 亿至 7500 亿美元，有望成为史上最大规模的 IPO。 此次 IPO 的募资规模可能超过沙特阿美 2019 年纪录的两倍以上，标志着由 AI 和太空技术驱动的新一轮公开市场热潮。同时，在长期新股上市低迷后，投资者对 AI 相关项目的热情高涨。 SpaceX 于 2026 年 4 月秘密提交 IPO 申请，并于 2026 年 2 月与 xAI 合并，合并后实体估值达 1.25 万亿美元。公司顾问正在寻找独特的配售渠道，包括英国、日本和加拿大的零售持有者。

rss · IT HOME · May 14, 23:27

**背景**: IPO（首次公开募股）是私营公司首次向公众出售股票的过程。路演是 IPO 前向潜在投资者进行的一系列推介活动。SpaceX 由埃隆·马斯克创立，是一家以可重复使用火箭和星链卫星互联网闻名的领先航天公司。与马斯克的 AI 公司 xAI 合并后，SpaceX 获得了 AI 能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/05/14/spacex-ipo-prospectus-could-land-as-soon-as-next-week-sources-say.html">SpaceX IPO prospectus could land as soon as next week, sources say</a></li>
<li><a href="https://www.axios.com/2026/05/14/spacex-musk-sp-stocks">The SpaceX IPO is already upending the stock market</a></li>
<li><a href="https://thenextweb.com/news/spacex-ipo-s1-musk-voting-control">SpaceX’s public IPO filing confirms Musk and insiders retain dominant voting control</a></li>

</ul>
</details>

**标签**: `#SpaceX`, `#IPO`, `#finance`, `#technology`, `#investment`

---

<a id="item-13"></a>
## [苹果基于 Intel 18A-P 开发 A/M 系列处理器以分散供应链](https://www.ithome.com/0/950/655.htm) ⭐️ 8.0/10

苹果已启动基于 Intel 18A-P 工艺（采用 Foveros 封装）的低端或旧款 iPhone、iPad 及 Mac 处理器的开发项目，计划 2026 年小规模测试，2027 年量产。 此举标志着苹果通过培养英特尔作为第二供应商来减少对台积电依赖的战略努力，可能重塑半导体供应链并增强苹果的议价能力。 苹果同时在 Intel 18A-P 上启动三大产品线，涵盖 iPhone、iPad 和 Mac 芯片，投片比例与销售比重相似。英特尔 2027 年的良率目标为 50-60%，初期台积电仍将供应苹果 90%以上的芯片。

rss · IT HOME · May 14, 22:53

**背景**: Intel 18A-P 是 Intel 18A 工艺的优化版本，采用 RibbonFET 环绕栅极晶体管和 PowerVia 背面供电技术，以及 Foveros 3D 封装。苹果目前几乎完全依赖台积电生产先进芯片，但台积电的产能正日益向 AI 和 HPC 客户倾斜，促使苹果寻找替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.intel.com/content/www/us/en/foundry/library/intel-18a-platform-brief.html">Intel 18A Process Node</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/semiconductors/intel-ceo-recognizes-its-18a-node-for-external-customers-as-18a-p-gets-inbound-interest-company-cites-increasing-yields">Intel CEO embraces its 18A node for external customers as 18A ...</a></li>
<li><a href="https://semiwiki.com/wikis/industry-wikis/intel-18ap-process-technology-wiki/">Intel 18A (P) Process Technology Wiki - SemiWiki</a></li>

</ul>
</details>

**标签**: `#Apple`, `#Intel`, `#TSMC`, `#semiconductor`, `#supply chain`

---

<a id="item-14"></a>
## [Linux 页面缓存漏洞：Copy Fail 与 Dirty Frag](https://www.infoq.cn/article/1HucCJrazwgF7QNT232r?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

两个关键的 Linux 内核漏洞——Copy Fail（CVE-2026-31431）和 Dirty Frag（CVE-2026-43284 和 CVE-2026-43500）已被披露，影响所有主流发行版。Copy Fail 允许向页面缓存执行受控的 4 字节写入，而 Dirty Frag 则通过链式利用两个漏洞实现本地权限提升。 这些漏洞带来严重的数据损坏和权限提升风险，可能允许非特权用户获得 root 权限。它们影响几乎所有现代 Linux 发行版，因此成为系统管理员和云提供商高度优先的安全问题。 Copy Fail 利用 authencesn 加密模板中的逻辑错误，通过 AF_ALG 和 splice() 向任何可读文件的页面缓存写入 4 字节。Dirty Frag 则链式利用 xfrm-ESP 页面缓存写入漏洞（CVE-2026-43284）和 RxRPC 页面缓存写入漏洞（CVE-2026-43500）来获取 root 权限。

rss · InfoQ 中文站 · May 15, 09:37

**背景**: Linux 页面缓存是内核的一个组件，用于在内存中缓存文件数据以提高 I/O 性能。允许对页面缓存进行任意写入的漏洞可能导致数据损坏或权限提升，因为该缓存在进程间共享。Copy Fail 和 Dirty Frag 是此类漏洞的最新例子，由安全研究人员发现并于 2026 年 4 月至 5 月披露。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://xint.io/blog/copy-fail-linux-distributions">Copy Fail : 732 Bytes to Root on Every Major Linux Distribution. - Xint</a></li>
<li><a href="https://edera.dev/stories/dirty-frag-the-linux-kernel-exploit-that-turns-your-page-cache-against-you">Dirty Frag: The Linux Kernel Exploit That Turns Your Page ...</a></li>
<li><a href="https://thehackernews.com/2026/05/linux-kernel-dirty-frag-lpe-exploit.html">Linux Kernel Dirty Frag LPE Exploit Enables Root Access ...</a></li>

</ul>
</details>

**标签**: `#Linux`, `#security`, `#vulnerability`, `#page cache`, `#data corruption`

---

<a id="item-15"></a>
## [安大略审计发现 AI 笔记生成器捏造治疗转诊](https://arstechnica.com/health/2026/05/your-doctors-ai-notetaker-may-be-making-things-up-ontario-audit-finds/) ⭐️ 8.0/10

安大略省的一项审计显示，医疗领域使用的 AI 笔记生成器经常捏造治疗转诊和错误的处方，引发对其可靠性的严重担忧。 这很重要，因为临床文档中的 AI 错误可能直接影响患者安全，导致不当治疗或遗漏护理。这些发现可能促使更严格的监管审查，并在医疗领域谨慎采用 AI 工具。 审计发现，AI 笔记生成器经常捏造治疗转诊并开出错误药物。尽管这些系统被宣传为医生的省时工具，但幻觉仍然发生。

rss · Ars Technica · May 14, 17:28

**背景**: AI 笔记生成器利用语音识别和自然语言处理来转录和总结患者就诊情况。然而，它们容易产生“幻觉”——生成看似合理但虚假的信息——这是大型语言模型的一个已知问题。在医疗领域，此类错误可能产生严重后果。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arstechnica.com/health/2026/05/your-doctors-ai-notetaker-may-be-making-things-up-ontario-audit-finds/">Your doctor’s AI notetaker may be making things up... - Ars Technica</a></li>

</ul>
</details>

**标签**: `#AI`, `#healthcare`, `#audit`, `#hallucination`, `#patient safety`

---

<a id="item-16"></a>
## [IBM 发布开源多语言嵌入模型，支持 32K 上下文](https://huggingface.co/blog/ibm-granite/granite-embedding-multilingual-r2) ⭐️ 8.0/10

IBM 发布了 Granite Embedding Multilingual R2，这是一个采用 Apache 2.0 开源协议的多语言嵌入模型，支持 32K token 的上下文窗口，并在参数低于 1 亿的模型中取得了最佳的检索质量。 该发布提供了一个高质量、开源的多语言嵌入模型，可自由用于检索、搜索和相似度任务，惠及 NLP 社区并推动 AI 应用更易获取。 该模型提供 97M 和 311M 两种参数规模，其中 311M 版本基于类似 ModernBERT 的架构，包含 22 层和 768 维嵌入向量。在多语言信息检索、代码检索、长文档搜索和对话多轮任务中表现优异。

rss · Hugging Face Blog · May 14, 18:55

**背景**: 嵌入模型将文本转换为固定长度的向量表示，从而实现语义相似度搜索和检索。Apache 2.0 许可证允许自由使用、修改和分发，使该模型对研究和商业应用都具有吸引力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/ibm-granite/granite-embedding-97m-multilingual-r2">ibm- granite / granite - embedding -97m- multilingual - r 2 · Hugging Face</a></li>
<li><a href="https://arxiv.org/pdf/2605.13521">Granite Embedding Multilingual R 2 Models</a></li>
<li><a href="https://www.ibm.com/granite/docs/models/embedding">Granite Embedding - IBM Granite</a></li>

</ul>
</details>

**标签**: `#NLP`, `#embeddings`, `#open-source`, `#multilingual`, `#retrieval`

---

<a id="item-17"></a>
## [ssh-keysign-pwn：非特权用户可读取 root 拥有的文件](https://github.com/0xdeadbeefnetwork/ssh-keysign-pwn/) ⭐️ 8.0/10

一个名为 ssh-keysign-pwn 的新漏洞利用程序已被发布，它通过利用 OpenSSH 中 ssh-keysign 组件的漏洞，允许非特权用户在 Linux 系统上读取 root 拥有的文件。 该漏洞使得非特权用户能够提升权限至 root 级别访问文件，可能被用于窃取 SSH 主机密钥、密码或配置文件等敏感数据，影响截至目前的所有 Linux 内核版本。 该漏洞利用针对 ssh-keysign 二进制文件，该文件设置了 setuid root 权限，可被滥用以读取任意 root 拥有的文件。该漏洞编号为 CVE-2011-4327，影响 5.8p2 之前的 OpenSSH 版本，但由于遗留的配置错误，该漏洞利用在现代系统上似乎仍然有效。

rss · Lobsters · May 15, 01:14

**背景**: ssh-keysign 是 OpenSSH 用于基于主机认证的辅助程序，它被设置为 setuid root 以访问主机密钥。旧版本中的一个漏洞允许非特权用户通过传递精心构造的参数读取任意 root 拥有的文件。这个新的漏洞利用程序复活了该攻击方式，表明许多系统由于补丁不完整或配置问题仍然存在漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.phoronix.com/news/Linux-ssh-keysign-pwn">Linux's Latest Vulnerability Allows Reading Root-Owned Files By ...</a></li>
<li><a href="https://github.com/advisories/GHSA-9998-pmcc-vpg5">ssh-keysign.c in ssh-keysign in OpenSSH before 5.8p2 on... - GitHub</a></li>
<li><a href="https://my.f5.com/manage/s/article/K15557">K15557: OpenSSH vulnerability CVE-2011-4327 - MyF5 | Support</a></li>

</ul>
</details>

**标签**: `#security`, `#vulnerability`, `#ssh`, `#exploit`, `#privilege-escalation`

---

<a id="item-18"></a>
## [Abridge：AI 原生医疗为临床医生节省 20 小时](https://www.latent.space/p/abridge) ⭐️ 8.0/10

AI 原生医疗平台 Abridge 已处理超过 1 亿次医生就诊，通过自动化临床文档和几分钟内完成预先授权，每周为临床医生节省 10-20 小时。 这表明 AI 可以显著减轻医疗领域的行政负担，有望改善临床医生福祉、提高患者可及性并降低成本。 该平台利用生成式 AI 将患者与临床医生的对话转化为结构化临床记录，并近乎实时地处理预先授权请求，直接集成到现有工作流程中。

rss · Latent Space · May 14, 22:05

**背景**: Abridge 是一家初创公司，将大语言模型应用于医疗对话，旨在取代手动记录和行政任务。预先授权是常见的保险要求，常导致延误；自动化处理每个案例可节省数小时。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.abridge.com/">Generative AI for Clinical Conversations | Abridge</a></li>
<li><a href="https://www.beckershospitalreview.com/healthcare-information-technology/innovation/abridge-has-become-the-wiring-of-healthcare-how-health-systems-are-operationalizing-real-time-intelligence/">Abridge Has Become the ‘Wiring’ of Healthcare: How health ...</a></li>
<li><a href="https://aitoolly.com/ai-news/article/2026-05-15-ai-native-healthcare-how-abridge-is-transforming-100-million-doctor-visits-and-saving-clinicians-20">Abridge AI: Saving Clinicians 20 Hours in Healthcare | AIToolly</a></li>

</ul>
</details>

**标签**: `#AI`, `#Healthcare`, `#NLP`, `#Clinical Workflow`, `#Startup`

---

<a id="item-19"></a>
## [Ollama v0.24.0 集成 Codex 应用](https://github.com/ollama/ollama/releases/tag/v0.24.0) ⭐️ 7.0/10

Ollama v0.24.0 引入了对 Codex 应用的支持，这是一款桌面编程助手，允许用户使用任何本地或云端 Ollama 模型进行编码、浏览和代码审查。该版本还重新设计了 MLX 采样器，以提升 Apple Silicon 上的生成质量。 这一集成为开发者提供了一个强大的桌面环境，用于 AI 辅助编程，结合了本地 LLM 的灵活性与内置浏览器和审查模式。它降低了在实用编程工作流中使用开源模型的门槛，可能增加 Ollama 在开发者中的采用率。 Codex 应用可通过命令 'ollama launch codex-app' 启动，用户可使用 'ollama launch codex-app --restore' 恢复默认的 OpenAI 设置。推荐用于困难编程任务的模型包括 kimi-k2.6 和 glm-5.1，而本地模型如 nemotron-3-super、gemma4:31b 和 qwen3.6 则适合离线使用。

github · github-actions[bot] · May 14, 02:24

**背景**: Ollama 是一个在本地计算机上运行和管理大型语言模型的软件平台，提供命令行界面、REST API 和模型管理工具。Codex 应用最初由 OpenAI 推出，是一款 macOS 桌面应用，帮助开发者管理多个 AI 代理、并行运行任务以及协作完成长期编程项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ollama">Ollama - Wikipedia</a></li>
<li><a href="https://openai.com/index/introducing-the-codex-app/">Introducing the Codex app | OpenAI</a></li>

</ul>
</details>

**标签**: `#ollama`, `#codex`, `#llm`, `#coding-assistant`, `#release`

---

<a id="item-20"></a>
## [Amazonbot 终于遵守 robots.txt](https://xeiaso.net/notes/2026/amazonbot-respecting-robots-txt/) ⭐️ 7.0/10

亚马逊的 Alexa AI 网络爬虫 Amazonbot 现在终于遵守 robots.txt 规则，此前它曾忽略禁止路径并给网站所有者带来过多流量。 这一变化恢复了对自愿性 robots.txt 标准的信任——此前许多 AI 爬虫无视该标准——并帮助网站所有者控制不必要的爬虫流量，而无需采取激进的屏蔽措施。 用户报告 Amazonbot 一个月内从公共仓库消耗了高达 750 GiB 的流量，并且该爬虫还访问了天气网站上被禁止的 URL 前缀。一些网站所有者尽管托管在 AWS 上，仍不得不通过 WAF 规则屏蔽 Amazonbot。

hackernews · Lobsters · May 14, 20:22 · [社区讨论](https://news.ycombinator.com/item?id=48140730)

**背景**: robots.txt 是一个标准文件，用于告知网络爬虫可以访问网站的哪些部分，但遵守是自愿的。在 2020 年代，许多 AI 爬虫无视 robots.txt，导致服务器过载和隐私问题。Amazonbot 被亚马逊用于索引网页内容，以支持 Alexa 的 AI 驱动回答。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.amazon.com/amazonbot">About AmazonBot</a></li>
<li><a href="https://datadome.co/bots/amazonbot/">What is Amazonbot ? How to block it ?</a></li>
<li><a href="https://en.wikipedia.org/wiki/Robots.txt">Robots.txt</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了 Amazonbot 带来过多流量的经历，有人提到一个月内高达 750 GiB。一些人觉得在 AWS 基础设施上屏蔽 Amazonbot 颇具讽刺意味。还发现了一个新的用户代理 'Amazon-Quick-on-Behalf-of-$HEXID'，引发了关于未记录爬虫的疑问。

**标签**: `#robots.txt`, `#web scraping`, `#AI crawlers`, `#Amazon`, `#site reliability`

---

<a id="item-21"></a>
## [MIT 校长警告资金危机与人才管道问题](https://president.mit.edu/writing-speeches/video-transcript-message-president-kornbluth-about-funding-and-talent-pipeline) ⭐️ 7.0/10

MIT 校长 Sally Kornbluth 发布视频讲话，指出研究经费下降以及吸引和留住人才方面的挑战，凸显学术界的系统性问题。 这一讲话标志着美国研究型大学面临关键转折点，资金削减和博士毕业生的失望情绪威胁着科学创新的未来和人才管道。 视频文字稿提到未获资助的学生更不可能接受录取，社区评论指出 80%的近期博士毕业生因工作艰苦和薪酬低而考虑离开学术界。

hackernews · dmayo · May 14, 14:51 · [社区讨论](https://news.ycombinator.com/item?id=48136262)

**背景**: 美国研究型大学严重依赖联邦拨款来资助研究生和研究项目。资金减少加上成本上升和就业市场严峻，导致早期职业研究人员日益失望，可能削弱国家的科学劳动力。

**社区讨论**: 评论反映了对学术界的普遍失望，许多人指出博士毕业生正转向工业界。一些人认为系统已崩溃，需要重置；另一些人则指出博士进入工业界本身并非问题，但资助模式需要改革。

**标签**: `#academia`, `#research funding`, `#talent pipeline`, `#higher education`, `#science policy`

---

<a id="item-22"></a>
## [黑客伪造苹果与雅虎 CDN 域名部署远程木马](https://www.ithome.com/0/950/689.htm) ⭐️ 7.0/10

Darktrace 于 2025 年 5 月 14 日披露，黑客自 2025 年 9 月底起，利用伪造的苹果和雅虎 CDN 域名（如 yahoo-cdn.it.com、icloud-cdn.net），通过 DLL 侧载技术向亚太地区目标投放远程访问木马。 该攻击通过滥用受信任的 CDN 域名和合法 Windows 进程绕过传统安全过滤，对亚太地区的企业和开发者构成重大威胁。使用 FDMTP 等模块化后门表明这是一场复杂的长期间谍活动。 攻击链包括下载合法可执行文件，然后拉取恶意 DLL 和配置文件。被滥用的进程包括 dfsvc.exe、vshost.exe 以及配合 browser_host.dll 的搜狗拼音。载荷与升级版 FDMTP 后门相关，支持加密通信、插件加载、注册表和计划任务持久化。

rss · IT HOME · May 15, 00:56

**背景**: DLL 侧载是一种攻击技术，攻击者将恶意 DLL 放置在合法应用程序会加载的位置，从而在可信进程伪装下执行代码。CDN 域名欺骗是指创建模仿合法 CDN 基础设施的虚假域名以逃避检测。远程访问木马（RAT）使攻击者能够远程控制受感染系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://attack.mitre.org/techniques/T1574/001/">Hijack Execution Flow: DLL, Sub-technique T1574.001 ...</a></li>
<li><a href="https://www.crowdstrike.com/en-us/blog/dll-side-loading-how-to-combat-threat-actor-evasion-techniques/">DLL Side-Loading: How to Combat Threat Actor ... - CrowdStrike</a></li>
<li><a href="https://www.cloudflare.com/learning/ssl/what-is-domain-spoofing/">What Is Domain Spoofing? | Website and Email Spoofing</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#malware`, `#CDN`, `#DLL sideloading`, `#APT`

---

<a id="item-23"></a>
## [AMD EPYC 在 2026 年第一季度创下 46.2% 的服务器营收份额纪录](https://www.ithome.com/0/950/680.htm) ⭐️ 7.0/10

据 Mercury Research 数据，AMD EPYC 服务器处理器在 2026 年第一季度创下 46.2% 的营收份额纪录，主要得益于云端和企业市场的强劲采用。相比之下，EPYC 的出货量份额为 27.4%，表明其平均售价高于英特尔至强处理器。 这一里程碑凸显了 AMD 在高价值服务器 CPU 市场日益增长的竞争力，挑战了英特尔长期的主导地位。与英特尔（53.8%）的营收份额差距现已缩小至仅 7.6 个百分点，预示着数据中心经济格局可能发生转变。 AMD 在 2026 年第一季度的数据中心营收达到 58 亿美元，占公司总营收的 55.9%。增长主要由第四代 EPYC（Genoa）和第五代 EPYC（Turin）处理器驱动，搭载 EPYC 的云实例同比增长近 50%，总量超过 1600 个。

rss · IT HOME · May 15, 00:30

**背景**: Mercury Research 是一家信誉良好的市场研究机构，追踪 CPU 的营收和出货量市场份额。AMD 基于 Zen 架构的 EPYC 系列自 2017 年推出以来稳步增长，而英特尔的至强系列则面临延迟。服务器 CPU 市场还包括基于 Arm 的处理器，其在 2026 年第一季度的出货量份额为 17.7%。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tomshardware.com/news/amd-and-intel-cpu-market-share-report-recovery-looms-on-the-horizon">AMD and Intel CPU Market Share Report: Recovery on the ... The Server Recession Ends, And Both Intel And AMD Won Question - What will the CPU industry marketshare look like ... Mercury Market Size, Share & Growth Analysis Report, 2030 Mercury Testing Service Market Share | Industry Report 2035 Mercury Market Share - Market Research Future</a></li>
<li><a href="https://en.wikipedia.org/wiki/Epyc">Epyc - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/huggingface-amd-turin">Introducing the AMD 5th Gen EPYC™ CPU</a></li>

</ul>
</details>

**标签**: `#AMD`, `#EPYC`, `#server CPU`, `#market share`, `#data center`

---

<a id="item-24"></a>
## [TanStack 供应链攻击迫使 Mac 版 ChatGPT 更新](https://www.ithome.com/0/950/666.htm) ⭐️ 7.0/10

由于开源库 TanStack 遭遇供应链攻击，导致两名员工设备及签名证书被入侵，OpenAI 已要求所有 Mac 版 ChatGPT 桌面用户在 2026 年 6 月 12 日前完成强制更新。 此事件凸显了针对广泛使用的开源库的供应链攻击可能产生连锁风险，直接影响 ChatGPT 等主要 AI 产品的终端用户。Mac 用户必须立即行动以避免应用功能失效，而整个技术社区应重新评估依赖项安全性。 此次名为 Mini Shul-Hulud 的攻击于 2026 年 5 月 11 日入侵了 42 个 TanStack 包中的 84 个 npm 包制品。OpenAI 确认仅少量内部源代码仓库子集及部分凭证材料被盗，未发现用户数据被访问。

rss · IT HOME · May 14, 23:30

**背景**: TanStack 是一个流行的开源库生态系统，被许多开发者用于构建 Web 应用。供应链攻击是指攻击者通过入侵受信任的第三方组件来渗透下游用户。Mini Shul-Hulud 蠕虫利用 npm 生命周期脚本和 CI/CD 流水线自动传播。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://snyk.io/blog/tanstack-npm-packages-compromised/">TanStack npm Packages Hit by Mini Shai-Hulud | Snyk</a></li>
<li><a href="https://www.securityweek.com/tanstack-mistral-ai-uipath-hit-in-fresh-supply-chain-attack/">TanStack, Mistral AI, UiPath Hit in Fresh Supply Chain Attack</a></li>
<li><a href="https://thehackernews.com/2026/05/mini-shai-hulud-worm-compromises.html">Mini Shai-Hulud Worm Compromises TanStack, Mistral AI ...</a></li>

</ul>
</details>

**标签**: `#security`, `#supply chain attack`, `#OpenAI`, `#ChatGPT`, `#TanStack`

---

<a id="item-25"></a>
## [AT&T、T-Mobile、Verizon 组建卫星合资企业消除信号盲区](https://www.ithome.com/0/950/660.htm) ⭐️ 7.0/10

AT&T、T-Mobile 和 Verizon 宣布达成原则性协议，将组建一家合资企业，整合频谱资源并集成卫星直连设备（D2D）服务，旨在消除美国全境的无线信号盲区。这可能为 iPhone 及其他智能手机实现普遍的卫星连接能力。 美国三大运营商的这一合作可能通过在农村和偏远地区提供无缝的卫星备份连接来改变移动通信格局，减少覆盖盲区。这也标志着运营商采取战略举措，防止卫星服务提供商绕过传统运营商，同时可能加速 D2D 技术在消费者和物联网应用中的普及。 该合资企业将整合三家运营商的授权频谱，并提供给 Starlink 和 AST SpaceMobile 等卫星服务提供商。现有的运营商专属卫星协议将继续有效，每个合作伙伴也可独立开展各自的连接工作。该合资企业旨在支持直连设备（D2D）通信，使标准智能手机无需硬件修改即可直接连接卫星。

rss · IT HOME · May 14, 23:15

**背景**: 直连设备（D2D）卫星技术允许未经修改的智能手机直接与卫星通信，在没有蜂窝网络覆盖的区域提供连接。此前，T-Mobile 与 Starlink 合作，而 AT&T 和 Verizon 分别与 AST SpaceMobile 合作。通过组建合资企业，运营商旨在创建一个统一平台，简化卫星服务提供商的集成，并确保跨网络的一致用户体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://about.att.com/story/2026/new-joint-venture.html">AT&T, T-Mobile, and Verizon Plan to Launch New Joint Venture</a></li>
<li><a href="https://qz.com/att-tmobile-verizon-satellite-joint-venture-dead-zones-051426">AT&T, T-Mobile, Verizon form satellite joint venture - Quartz</a></li>
<li><a href="https://www.sdxcentral.com/news/att-t-mobile-us-verizon-eye-satellite-focused-spectrum-pooling-jv/">AT&T, T-Mobile US, Verizon eye satellite-focused spectrum-pooling JV</a></li>

</ul>
</details>

**标签**: `#satellite`, `#telecommunications`, `#iPhone`, `#5G`, `#connectivity`

---

<a id="item-26"></a>
## [新 iPhone 盗窃骗局利用查找联系人号码钓鱼](https://www.ithome.com/0/950/653.htm) ⭐️ 7.0/10

安全公司 Infoblox 发现了一种新型钓鱼攻击，盗贼利用苹果“查找”网络中丢失 iPhone 上留下的联系电话，发送伪造的苹果支持页面，诱骗机主泄露锁屏密码。 这种攻击通过利用人性弱点绕过了苹果的“查找”防盗保护，且解锁工具成本极低（不到 10 美元），为被盗 iPhone 创造了利润丰厚的黑市，可能助长盗窃动机。 钓鱼域名（如'applemaps-support[.]live'）每年新增超过 80 万个，攻击者还使用“FMI OFF”和“iCloud Webkit”等工具窃取 Apple 账户密码。对于旧款 iPhone，Telegram 群组出售基于越狱的解锁软件和 AI 驱动的语音通话社会工程学工具。

rss · IT HOME · May 14, 22:49

**背景**: 苹果的“查找”网络允许用户将丢失的 iPhone 标记为丢失，并在锁屏上显示联系电话。iOS 17.4 引入了“失窃设备保护”功能，在陌生位置对敏感操作增加安全延迟。然而，这种钓鱼攻击通过诱骗用户主动提供密码来绕过这些保护。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoblox.com/blog/threat-intelligence/lookalike-domains-expose-the-iphone-theft-economy/">Inside the Underground Market That Unlocks Stolen iPhones</a></li>
<li><a href="https://appleinsider.com/articles/26/05/14/thieves-are-unlocking-and-making-more-money-from-stolen-and-locked-iphones">How thieves are unlocking, and profiting from, stolen iPhones</a></li>
<li><a href="https://www.wired.com/story/your-iphone-gets-stolen-then-the-hacking-begins/">Your iPhone Gets Stolen. Then the Hacking Begins | WIRED</a></li>

</ul>
</details>

**标签**: `#iPhone security`, `#phishing`, `#Apple Find My`, `#cybercrime`, `#black market`

---

<a id="item-27"></a>
## [国内首枚高校主导的面对称可回收液体火箭成功垂直起降](https://www.ithome.com/0/950/648.htm) ⭐️ 7.0/10

中山大学成功完成了“逸仙-3 号”火箭的垂直起降飞行试验，这是国内首枚由高校主导研制的面对称可回收液体火箭，验证了二子级回收关键技术。 这一成就标志着中国可重复使用火箭技术的重要里程碑，尤其是难度高于一子级回收的二子级回收技术。同时，它也展示了产学研合作推动航天创新的潜力。 这枚高 4.5 米、直径 0.6 米、重约 1 吨的火箭完成了约 30 秒的飞行，实现了精确悬停和着陆。项目中有 10 名关键学生参与（5 名本科生、5 名研究生），并在大湾区域内实现了全产业链闭环。

rss · IT HOME · May 14, 15:48

**背景**: VTVL（垂直起飞、垂直着陆）是可重复使用火箭的核心技术，使火箭能够在发射后安全返回。虽然一子级回收已被 SpaceX 等公司实现，但二子级回收因速度和高度更高而更为复杂。本次试验聚焦于二子级回收，这是实现完全可重复使用运载火箭的关键。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zh.wikipedia.org/zh-cn/垂直起降_(火箭)">垂直起降 (火箭) - 维基百科，自由的百科全书</a></li>
<li><a href="https://baike.baidu.com/item/垂直起降火箭/20809213">垂直起降火箭 - 百度百科 朱雀三号可复用火箭十公里级垂直起降飞行试验任务圆满成功！ 国内首枚高校主导研制的面对称可回收液体火箭平台飞行试验成功，中大... 自研液体火箭关键技术验证！成功实现垂直起降与空中悬停【硬核可回收... 朱雀三号VTVL-1可重复使用垂直起降回收试验箭完成十公里级垂直起降返...</a></li>

</ul>
</details>

**标签**: `#reusable rocket`, `#VTVL`, `#university research`, `#aerospace`

---

<a id="item-28"></a>
## [基于半监督评测的 UI 自动化生产实践](https://www.infoq.cn/article/ybKCXkQgfxf4J9GCUuJl?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

蚂蚁集团工程师黄兆嵩在 QCon 2026 北京站提出了一种方法，通过半监督评测体系将 UI 生成接入自动化生产流水线。 该方法解决了 UI 迭代速度超过设计产能的瓶颈，能够实现更快、更个性化的用户体验，并简化开发流程。 半监督评测体系可能结合自动化指标和有限的人工反馈来评估生成的 UI，在保持质量的同时减少全面人工审查的需求。

rss · InfoQ 中文站 · May 14, 18:09

**背景**: 传统的 UI 自动化测试依赖 Selenium 或 Playwright 等工具验证 UI 行为，但自动生成 UI 并大规模评估仍具挑战。半监督学习利用少量标注数据指导大量未标注数据的评估，可应用于 UI 质量评估。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.cn/article/ybKCXkQgfxf4J9GCUuJl">把 UI 生成接进流水线：基于半监督评测体系的 UI 自动化生产实践 - In...</a></li>
<li><a href="https://news.qq.com/rain/a/20260512A063OX00">把 UI 生成接进流水线：基于半监督评测体系的 UI 自动化生产实践</a></li>
<li><a href="https://max.book118.com/html/2026/0510/5100243013013212.shtm">把UI生成接进流水线：基于半监督评测体系的UI自动化生产实践.pptx-原...</a></li>

</ul>
</details>

**标签**: `#UI automation`, `#semi-supervised learning`, `#software engineering`, `#AI/ML`

---

<a id="item-29"></a>
## [AWS WorkSpaces 现允许 AI 智能体操作遗留桌面应用](https://www.infoq.cn/article/ktRP5kz1fMkW5rmmMFoR?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

AWS 宣布 Amazon WorkSpaces 现在可以作为 AI 智能体的托管虚拟桌面（公开预览），智能体通过 IAM 认证，利用计算机视觉和键盘/鼠标输入来操作遗留桌面应用程序。 这一集成使组织能够自动化遗留桌面应用程序，而无需进行 API 现代化或应用重写，显著降低了企业环境中 AI 驱动自动化的成本和复杂性。 智能体通过唯一的预签名 URL 连接到 WorkSpace，通过截图（计算机视觉）进行交互，并可存储截图用于审计。该功能目前处于公开预览阶段，支持基于 IAM 的认证和 MCP（模型上下文协议）。

rss · InfoQ 中文站 · May 14, 14:29

**背景**: 遗留桌面应用程序通常缺乏现代 API，难以通过传统脚本或 AI 智能体进行自动化。AWS WorkSpaces 在云中提供虚拟桌面，这一新功能为 AI 智能体提供了自己的桌面环境，使其能够像人类一样通过屏幕观察和输入模拟来与这些应用程序交互。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/aws/modernize-your-workflows-amazon-workspaces-now-gives-ai-agents-their-own-desktop-preview/">Modernize your workflows: Amazon WorkSpaces now gives AI ...</a></li>
<li><a href="https://www.infoq.com/news/2026/05/aws-workspaces-ai-agents/">AWS WorkSpaces Now Lets AI Agents Operate Legacy Desktop ...</a></li>
<li><a href="https://stack-archive.com/blog/amazon-workspaces-ai-agents-legacy-desktop-2026/">Amazon WorkSpaces for AI Agents: Solving the Legacy Desktop ...</a></li>

</ul>
</details>

**标签**: `#AWS`, `#AI agents`, `#legacy applications`, `#cloud computing`

---

<a id="item-30"></a>
## [本地优先 AI 推理实现高性价比文档处理](https://www.infoq.cn/article/GKePaJNHaWHeoEfD7W0f?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

一种名为本地优先 AI 推理的新型云架构模式被提出，该模式在边缘设备本地完成 70-80%的文档提取，仅将复杂案例发送至云端 AI（如 Azure OpenAI）处理。 该模式在生产级工作负载中可将 API 成本降低高达 75%，处理时间缩短 55%，使企业能够更经济地使用 AI 文档处理技术。 该架构采用三层混合方法：本地确定性提取、云端 AI 处理边缘案例、以及人工审核低置信度结果。在 4700 份文档的测试中，延迟从 2-3 秒降至 300 毫秒以内，单次成本从 0.5 元降至 0.02 元。

rss · InfoQ 中文站 · May 14, 12:00

**背景**: 传统的云端文档处理将每份文档都发送至托管 AI 端点，效率低下且成本高昂。本地优先推理利用部署在用户本地或边缘设备上的轻量级模型，处理大多数结构化文档（如发票、工程图纸），无需将数据发送至云端。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.cn/article/GKePaJNHaWHeoEfD7W0f">本地优先 AI 推理：高性价比文档处理云架构模式 - InfoQ</a></li>
<li><a href="https://www.ailookout.cn/news/1132">本地优先 AI 推理：高性价比文档处理云架构模式 | AI 瞭望台 | AI 瞭...</a></li>
<li><a href="https://www.showapi.com/news/article/6a0573c04ddd79ab67103643">本地优先AI推理：重构文档处理的新范式-易源AI资讯 | 万维易源</a></li>

</ul>
</details>

**标签**: `#AI inference`, `#cloud architecture`, `#document processing`, `#edge computing`, `#cost optimization`

---

<a id="item-31"></a>
## [前 Qwen 负责人林俊旸创业，新 AI Lab 估值 136 亿元](https://www.infoq.cn/article/OpaYcpzKc45zmvxCNBlW?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

前阿里巴巴通义千问（Qwen）团队负责人林俊旸创立了一家新的人工智能实验室，估值达 136 亿元人民币（约 20 亿美元）。 这一高调举动表明中国 AI 领域人才流动和投资持续活跃，可能加剧 AI 实验室之间的竞争，并加速大语言模型的创新。 这家尚未公布名称的新公司已获得顶级投资者的重大融资。林俊旸曾是阿里云 Qwen 系列模型的核心贡献者。

rss · InfoQ 中文站 · May 14, 11:40

**背景**: Qwen（通义千问）是阿里云开发的一系列大语言模型，与 GPT-4 和 Llama 等模型竞争。林俊旸在离职创业前担任 Qwen 团队的首席研究员和核心维护者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>
<li><a href="https://grokipedia.com/page/Junyang_Lin">Junyang Lin</a></li>
<li><a href="https://eu.36kr.com/en/p/3807382930251523">Lin Junyang Launches Business: New Company Valued at Around ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#entrepreneurship`, `#Alibaba`, `#Qwen`, `#funding`

---

<a id="item-32"></a>
## [Netflix 推出模型生命周期图，助力企业级 MLOps](https://www.infoq.cn/article/omIEI3rqzgXWJOHiHMWU?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

Netflix 发布了一个模型生命周期图，该图标准化了企业环境中机器学习模型开发、部署和监控的各个阶段。 该图为 MLOps 团队提供了一个通用框架，有助于扩展机器学习运营并减少数据科学家与工程师之间的摩擦。 该图涵盖了从数据摄入、模型训练到部署、监控和再训练的各个阶段，并强调了迭代反馈循环。

rss · InfoQ 中文站 · May 14, 10:19

**背景**: MLOps（机器学习运营）是一套旨在可靠且高效地在生产环境中部署和维护机器学习模型的实践。随着组织扩展其机器学习工作，管理完整的生命周期变得复杂。Netflix 的图提供了一个视觉蓝图，用于协调团队和流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://netflixtechblog.com/democratizing-machine-learning-at-netflix-building-the-model-lifecycle-graph-5cc6d5828bb1">Democratizing Machine Learning at Netflix: Building the Model ...</a></li>
<li><a href="https://www.geeksforgeeks.org/machine-learning/mlops-components-machine-learning-life-cycle/">MLOps Components and Life Cycle - GeeksforGeeks</a></li>

</ul>
</details>

**标签**: `#MLOps`, `#Netflix`, `#machine learning`, `#model lifecycle`, `#enterprise`

---

<a id="item-33"></a>
## [谷歌 DORA 报告：工程基础决定 AI 投资回报](https://www.infoq.cn/article/IgGuKFh9qmKmFEIZeR4t?utm_source=rss&utm_medium=article) ⭐️ 7.0/10

谷歌 DORA 团队发布了一份题为《AI 辅助软件开发的 ROI》的新报告，强调扎实的工程基础是决定 AI 投资回报的首要因素。 该报告提供了数据驱动的证据，表明组织在期望从 AI 采用中获得显著回报之前，必须优先考虑工程基础（如部署频率和变更失败率），这将影响企业如何为 AI 转型分配资源。 该报告引入了“不稳定税”的概念，即糟糕的工程实践会侵蚀 AI 辅助开发的收益，并使用四个关键指标（部署频率、前置时间、变更失败率、恢复时间）来衡量绩效。

rss · InfoQ 中文站 · May 14, 09:23

**背景**: DORA（DevOps 研究与评估）是 Google Cloud 的一项长期研究项目，研究软件交付和运维绩效。其四个关键指标在 DevOps 社区中被广泛用于衡量团队效能。这份新报告将该框架扩展到评估 AI 工具对软件开发的影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dora.dev/">DORA | Get Better at Getting Better</a></li>
<li><a href="https://www.infoq.com/news/2026/05/dora-roi-ai-assisted-dev-report/">New DORA Report Claims Strong Engineering Foundations... - InfoQ</a></li>
<li><a href="https://cloud.google.com/blog/products/devops-sre/using-the-four-keys-to-measure-your-devops-performance">Use Four Keys metrics like change failure rate to... | Google Cloud Blog</a></li>

</ul>
</details>

**标签**: `#DORA`, `#AI ROI`, `#engineering fundamentals`, `#software engineering`, `#Google`

---

<a id="item-34"></a>
## [能源供应商优先服务数据中心，弃置太浩湖居民](https://arstechnica.com/ai/2026/05/energy-supplier-abandons-lake-tahoe-residents-to-serve-data-centers/) ⭐️ 7.0/10

太浩湖地区的能源供应商 NV Energy 通知公用事业公司，将把电力转用于内华达州的数据中心，导致近 49,000 名加州居民需在一年内另寻电源。 这一决定凸显了 AI 基础设施巨大的能源需求与当地社区需求之间日益加剧的矛盾，引发了关于能源公平和资源分配伦理的紧迫问题。 受影响的居民可能失去高达 75%的电力供应，NV Energy 声称需要将容量用于数据中心，而这些数据中心正越来越多地由 AI 工作负载驱动。

rss · Ars Technica · May 14, 19:17

**背景**: 数据中心，尤其是支持 AI 的数据中心，消耗大量电力。随着 AI 应用的普及，能源供应商面临优先保障这些设施的压力，有时会牺牲居民用户。太浩湖事件正是这种紧张关系的具体体现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arstechnica.com/ai/2026/05/energy-supplier-abandons-lake-tahoe-residents-to-serve-data-centers/">Energy supplier abandons Lake Tahoe residents to serve data ...</a></li>
<li><a href="https://fortune.com/2026/05/12/lake-tahoe-data-center-49000-residents-power-source/">Nearly 50,000 Lake Tahoe residents face power loss as utility ...</a></li>

</ul>
</details>

**标签**: `#energy`, `#data centers`, `#AI infrastructure`, `#policy`, `#ethics`

---

<a id="item-35"></a>
## [浏览器对大型网站区别对待](https://denodell.com/blog/browsers-treat-big-sites-differently) ⭐️ 7.0/10

浏览器对主要网站实施特殊处理，应用不同于小型网站的安全、性能和隐私策略。 这种区别对待可能为网络开发者创造不公平的竞争环境，并引发对小型网站公平性、安全性和隐私的担忧。 具体机制包括为 Google、Facebook 和 Amazon 等大型网站优化缓存、放宽安全检查以及提供特权 API 访问。

rss · Lobsters · May 14, 09:56

**背景**: Chrome、Firefox 和 Edge 等浏览器长期以来包含针对特定网站的兼容性处理，以确保与流行服务的兼容性。这些处理通常未记录在案，并可能影响内容安全策略、Cookie 处理和性能优化等功能的应用方式。

**社区讨论**: Lobste.rs 上的讨论指出，这种做法在浏览器工程师中已知，但很少公开披露。评论者争论这种特殊处理是兼容性所必需，还是构成了不公平的优势。

**标签**: `#browsers`, `#web security`, `#performance`, `#privacy`

---

<a id="item-36"></a>
## [通行密钥能取代密码吗？](https://kerkour.com/passkeys) ⭐️ 7.0/10

文章探讨了基于 WebAuthn 标准的通行密钥能否有效取代传统密码，强调了其在安全性和易用性方面的优势。 通行密钥提供抗钓鱼认证，无需用户记忆复杂密码，有望减少账户泄露并改善全网用户体验。 通行密钥使用公钥密码学，私钥存储在用户设备上且从不与服务器共享，从而抵御服务器端数据泄露。

rss · Lobsters · May 14, 14:37

**背景**: 密码长期以来是主要的认证方式，但存在钓鱼攻击、重复使用和弱密码等弱点。通行密钥由 FIDO 联盟和 W3C 通过 WebAuthn 标准化，旨在通过生物识别或设备 PIN 实现无密码登录，解决这些问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Passkeys_(authentication)">Passkeys (authentication)</a></li>
<li><a href="https://fidoalliance.org/passkeys/">FIDO Passkeys: Passwordless Authentication | FIDO Alliance</a></li>
<li><a href="https://www.consumerreports.org/electronics/digital-security/should-you-use-passkeys-instead-of-passwords-a1201817243/">Should You Use Passkeys Instead of Passwords? Top Stories Still Using Passwords? It's Time to Upgrade to Passkeys Now Passwords vs Passkeys - GeeksforGeeks Are 'passkeys' better than passwords? This security expert ... Passkeys Are the New Passwords. You Should Start Using Them ... Password vs Passkey: Key Differences & Security Comparison Passkey vs Password: Which Should I Use? - Keeper Security</a></li>

</ul>
</details>

**标签**: `#authentication`, `#security`, `#passkeys`, `#web development`

---

<a id="item-37"></a>
## [C++26 引入 SIMD 库引发争议](https://lucisqr.substack.com/p/c26-shipped-a-simd-library-nobody) ⭐️ 7.0/10

C++26 正式发布了 std::simd（P1928），这是一个可移植的 SIMD 抽象库，允许编写一次数据并行代码，然后针对不同的 SIMD 架构（如 AVX2）进行编译。 这一新增功能将 SIMD 编程标准化到 C++ 中，可能提升许多领域的性能，但标题暗示该库是在没有广泛社区需求的情况下添加的，引发了对其设计和必要性的质疑。 该库提供了数据并行类型和操作，以可移植的方式实现显式数据并行。然而，一些开发者认为现有的编译器内建函数或第三方库已经满足了 SIMD 需求，标准库可能没有显著优势。

rss · Lobsters · May 14, 15:22

**背景**: SIMD（单指令多数据）是一种并行计算技术，单条指令同时处理多个数据点，广泛应用于多媒体处理和科学计算等性能关键型应用。C++26 是 C++ 标准的下一个计划版本，预计在 2026 年左右最终确定。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://lucisqr.substack.com/p/c26-shipped-a-simd-library-nobody">C++26 Shipped a SIMD Library Nobody Asked For</a></li>
<li><a href="https://en.cppreference.com/cpp/numeric/simd">Data-parallel types (SIMD) (since C++26) - cppreference.com</a></li>
<li><a href="https://en.wikipedia.org/wiki/Single_instruction,_multiple_data">Single instruction, multiple data - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Lobste.rs 上的评论可能讨论了 std::simd 是受欢迎的补充还是不必要复杂化，一些人称赞其可移植性，另一些人则批评缺乏需求和潜在的性能陷阱。

**标签**: `#C++`, `#SIMD`, `#programming languages`, `#performance`

---

<a id="item-38"></a>
## [Mandy 将 ActivityPub 引入 Goblins](https://spritely.institute/news/mandy-activitypub-on-goblins.html) ⭐️ 7.0/10

Spritely 研究所宣布了 Mandy，这是在 Goblins 分布式编程环境上实现 ActivityPub 协议的一个项目，从而支持去中心化社交网络功能。 这一集成将广泛采用的 ActivityPub 标准引入了一个基于能力的安全分布式系统，有望用更健壮、更安全的社交应用扩展联邦宇宙。 Mandy 构建在 Goblins 之上，Goblins 遵循 actor 模型并提供对象能力安全机制，适合安全的分布式编程。该实现旨在支持 ActivityPub 的客户端到服务器和服务器到服务器协议。

rss · Lobsters · May 14, 14:14

**背景**: ActivityPub 是 W3C 制定的去中心化社交网络标准，被 Mastodon、PeerTube 等平台使用。Goblins 是 Spritely 研究所开发的分布式对象编程环境，专为安全、事务性的分布式计算而设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://spritely.institute/goblins/">Goblins: Distributed Programming — Spritely Institute</a></li>
<li><a href="https://en.wikipedia.org/wiki/ActivityPub">ActivityPub</a></li>
<li><a href="https://docs.racket-lang.org/goblins/intro.html">1 What is Goblins?</a></li>

</ul>
</details>

**社区讨论**: Lobsters 上的讨论突出了将 ActivityPub 与基于能力的安全机制相结合的关注，一些评论者指出这有可能带来更安全的联邦应用。其他人则讨论了在 Goblins 这样的新型运行时中实现 ActivityPub 的技术挑战。

**标签**: `#ActivityPub`, `#Goblins`, `#decentralization`, `#distributed systems`, `#social networking`

---

<a id="item-39"></a>
## [前部署工程在技术变革中再度兴起](https://newsletter.pragmaticengineer.com/p/the-pulse-forward-deployed-engineering) ⭐️ 7.0/10

《务实工程师》通讯报道了前部署工程（FDE）的复兴，同时技术岗位流失加剧，以及氛围编码与智能体工程的融合。 这一趋势标志着向客户嵌入式、AI 集成工程角色的转变，可能重新定义软件工程实践和职业发展路径。 前部署工程师直接在客户环境中构建和部署解决方案，而氛围编码利用 AI 根据提示生成代码，智能体工程则专注于自主 AI 智能体。

rss · The Pragmatic Engineer · May 14, 16:09

**背景**: 前部署工程（FDE）是一种工程师嵌入客户环境解决实际问题的模式。氛围编码由 Andrej Karpathy 提出，涉及 AI 辅助代码生成且审查较少。智能体工程设计能自主规划和执行任务的 AI 智能体。随着 AI 采用加速，这些概念正在融合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Forward_Deployed_Engineer">Forward Deployed Engineer - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding</a></li>
<li><a href="https://www.ibm.com/think/topics/agentic-engineering">What is agentic engineering? - IBM</a></li>

</ul>
</details>

**标签**: `#software engineering`, `#tech trends`, `#AI`, `#career`

---