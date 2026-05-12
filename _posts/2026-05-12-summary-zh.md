---
layout: default
title: "Horizon Summary: 2026-05-12 (ZH)"
date: 2026-05-12
lang: zh
---

> From 152 items, 19 important content pieces were selected

---

1. [TanStack npm 供应链攻击事后分析](#item-1) ⭐️ 9.0/10
2. [加州大学洛杉矶分校发现首个修复脑损伤的中风康复药物](#item-2) ⭐️ 9.0/10
3. [两周内第二个严重 Linux 漏洞](#item-3) ⭐️ 9.0/10
4. [谷歌称犯罪黑客利用 AI 发现零日漏洞](#item-4) ⭐️ 8.0/10
5. [Thinking Machines 发布实时多模态交互模型](#item-5) ⭐️ 8.0/10
6. [GitLab 裁员并放弃 CREDIT 价值观，转向 AI](#item-6) ⭐️ 8.0/10
7. [中国强制短视频标注六类标签，含 AI 生成内容](#item-7) ⭐️ 8.0/10
8. [谷歌发布新一代 TPU，专为 AI 智能体和 SOTA 模型训练设计](#item-8) ⭐️ 8.0/10
9. [攻击者在 Flippa 购买 30 个 WordPress 插件并植入后门](#item-9) ⭐️ 8.0/10
10. [Figma 自研 Redis 代理实现六个九可用性](#item-10) ⭐️ 8.0/10
11. [James Shore：AI 编程代理必须降低维护成本](#item-11) ⭐️ 8.0/10
12. [你的 AI 使用正在摧毁我的大脑](#item-12) ⭐️ 8.0/10
13. [Shopify 的 River：在公开 Slack 频道中的 AI 编程代理](#item-13) ⭐️ 8.0/10
14. [数据中心消耗 3000 万加仑水未被察觉](#item-14) ⭐️ 8.0/10
15. [Starlink 在 IPO 前禁用 GPS 替代方案](#item-15) ⭐️ 8.0/10
16. [考克斯在最高法院的胜诉可能重塑版权责任](#item-16) ⭐️ 8.0/10
17. [Fsnotify 维护者争议引发供应链警报](#item-17) ⭐️ 8.0/10
18. [在 LLVM 中对抗 Hyrum 定律](#item-18) ⭐️ 8.0/10
19. [Kettle：可验证软件来源的可信构建系统](#item-19) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [TanStack npm 供应链攻击事后分析](https://tanstack.com/blog/npm-supply-chain-compromise-postmortem) ⭐️ 9.0/10

2026 年 5 月 11 日，攻击者通过向一个 fork 推送恶意提交，攻陷了 TanStack Router 的 npm 包，随后利用该提交在 npm 上发布了 42 个@tanstack/*包共 84 个恶意版本，并影响了 Mistral AI 的客户端包。 这一针对广泛使用的开源项目的真实供应链攻击，暴露了 npm 和 GitHub Actions CI/CD 管道中的关键漏洞，强调了采用可信发布和依赖锁定等更强安全实践的必要性。 攻击链包括 pull_request_target Pwn 请求、跨 fork-base 信任边界的 GitHub Actions 缓存投毒，以及从运行器内存中提取 OIDC 令牌，使攻击者能够发布具有有效 SLSA 来源的恶意版本。

hackernews · varunsharma07 · May 11, 21:08 · [社区讨论](https://news.ycombinator.com/item?id=48100706)

**背景**: 供应链攻击针对软件开发和分发过程，通常通过攻陷依赖项或构建管道实现。npm 包因其广泛使用以及通过 postinstall 脚本在安装期间执行任意代码的能力而特别脆弱。GitHub Actions 缓存投毒利用共享缓存存储跨仓库注入恶意工件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tanstack.com/blog/npm-supply-chain-compromise-postmortem">Postmortem: TanStack npm supply-chain compromise | TanStack Blog</a></li>
<li><a href="https://www.stepsecurity.io/blog/mini-shai-hulud-is-back-a-self-spreading-supply-chain-attack-hits-the-npm-ecosystem">TeamPCP's Mini Shai-Hulud Is Back: A Self-Spreading Supply Chain Attack Compromises TanStack npm Packages - StepSecurity</a></li>
<li><a href="https://socket.dev/blog/tanstack-npm-packages-compromised-mini-shai-hulud-supply-chain-attack">Tanstack npm Packages Compromised in Ongoing Mini Shai-Hulud...</a></li>

</ul>
</details>

**社区讨论**: 社区成员指出，有效载荷安装了一个死机开关，如果被盗令牌被撤销，将擦除用户的主目录。其他人认为，GitHub 的共享对象存储允许恶意 fork 提交与合法提交无法区分是一个根本性缺陷，而 postinstall 脚本仍然是一个危险的攻击向量。

**标签**: `#supply-chain security`, `#npm`, `#open-source`, `#postmortem`, `#CI/CD`

---

<a id="item-2"></a>
## [加州大学洛杉矶分校发现首个修复脑损伤的中风康复药物](https://stemcell.ucla.edu/news/ucla-discovers-first-stroke-rehabilitation-drug-repair-brain-damage) ⭐️ 9.0/10

加州大学洛杉矶分校的研究人员发现了一种药物，通过恢复幸存神经网络的连接性来修复中风后的脑损伤，但该药物无法逆转梗死核心的细胞死亡。 这是首个能够修复脑损伤的中风康复药物，有望改善全球数百万中风幸存者的康复效果，并为治疗其他神经系统疾病开辟新途径。 该药物针对的是幸存远端网络的连接中断和节律丧失，而非梗死核心的死亡细胞。该化合物已在 PubMed 研究（PMID: 39106304）中被确认。

hackernews · bookofjoe · May 11, 17:53 · [社区讨论](https://news.ycombinator.com/item?id=48098261)

**背景**: 中风是指大脑部分区域血流中断，导致梗死核心细胞死亡。然而，周围“挫伤”的细胞可能存活但失去连接，导致功能缺陷。目前的治疗侧重于急性干预，而非修复受损网络。

**社区讨论**: 评论者澄清该药物针对的是幸存网络而非死亡细胞，并指出与迷幻药重新打开大脑可塑性关键期的相似之处。有人询问是否适用于阿尔茨海默病。

**标签**: `#neuroscience`, `#stroke`, `#drug discovery`, `#brain repair`, `#medical breakthrough`

---

<a id="item-3"></a>
## [两周内第二个严重 Linux 漏洞](https://arstechnica.com/security/2026/05/linux-bitten-by-second-severe-vulnerability-in-as-many-weeks/) ⭐️ 9.0/10

两周内 Linux 中发现了第二个严重漏洞，生产补丁现已可用，需立即安装。 该漏洞对关键基础设施构成重大安全风险，系统管理员必须紧急修补以防止潜在利用。 该漏洞严重到需要立即修补，但简要内容中未提供具体技术细节。

rss · Ars Technica · May 11, 22:28

**背景**: Linux 是一个广泛使用的开源操作系统内核，驱动着服务器、嵌入式系统和许多其他设备。严重漏洞可能允许攻击者获得未授权访问或导致系统崩溃。补丁通常由 Linux 内核社区和下游发行版发布。

**标签**: `#Linux`, `#security`, `#vulnerability`, `#patch`

---

<a id="item-4"></a>
## [谷歌称犯罪黑客利用 AI 发现零日漏洞](https://www.nytimes.com/2026/05/11/us/politics/google-hackers-attack-ai.html) ⭐️ 8.0/10

谷歌威胁情报组报告称，一个犯罪黑客组织使用 AI 模型发现并武器化了一个零日漏洞，这是已知的首例真实世界 AI 辅助网络攻击。该攻击在被造成损害前已被阻止。 这一事件表明，恶意行为者现在正积极利用 AI 来发现和利用软件漏洞，降低了复杂网络攻击的门槛。它标志着网络安全进入新时代，防御者必须预见 AI 驱动的威胁。 该漏洞是一个零日漏洞，即在被利用时软件供应商尚不知情。谷歌高度确信 AI 模型在发现和武器化过程中都提供了帮助，但具体模型和方法尚未披露。

hackernews · donohoe · May 11, 13:20 · [社区讨论](https://news.ycombinator.com/item?id=48094641)

**背景**: 零日漏洞是指软件开发者未知的安全缺陷，攻击者可在补丁发布前利用它。AI 辅助漏洞发现是一个日益增长的研究领域，例如 Anthropic 的 Claude Opus 4.6 最近发现了数百个未知漏洞。此案是首次确认犯罪黑客在真实环境中将 AI 用于此类目的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bloomberg.com/news/articles/2026-05-11/hackers-used-ai-to-build-zero-day-attack-google-researchers-say">Google Researchers Detect First AI-Built Zero-Day Exploit in Cyberattack - Bloomberg</a></li>
<li><a href="https://www.engadget.com/2170002/google-announces-its-first-ever-discovery-of-a-zero-day-exploit-made-with-ai/">Google announces its first-ever discovery of a zero-day exploit made with AI - Engadget</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-day_exploit">Zero-day exploit</a></li>

</ul>
</details>

**社区讨论**: 评论者对谷歌如何确定 AI 参与表示怀疑，有人质疑这一叙事是否旨在为更严格的 AI 管控提供理由。其他人则认为这一结果不可避免，并呼吁像核材料一样加强 AI 治理。

**标签**: `#AI`, `#cybersecurity`, `#zero-day`, `#Google`, `#threat intelligence`

---

<a id="item-5"></a>
## [Thinking Machines 发布实时多模态交互模型](https://thinkingmachines.ai/blog/interaction-models/) ⭐️ 8.0/10

Thinking Machines 推出了一款实时多模态 Transformer，通过 200 毫秒的微轮次交错处理输入和输出，实现了自然的对话停顿和打断。该模型处理文本、图像和音频输入，并实时生成文本和音频输出。 这种交互模型代表了人机交互的重大进步，从基于回合的聊天转向更流畅的全双工对话。它可能实现更自然、更直观的 AI 助手，影响客户服务、教育和娱乐等应用。 该架构是一个联合训练文本、图像和音频模态的 Transformer，使用 200 毫秒的微轮次连续交错处理输入和生成输出。这使得 AI 即使在说话时也能对视觉和听觉输入做出反应，从而实现打断和停顿。

hackernews · smhx · May 11, 20:53 · [社区讨论](https://news.ycombinator.com/item?id=48100524)

**背景**: 传统的 AI 对话模型以回合制方式运行，用户说完后模型再回应，导致不自然的停顿且无法处理打断。多模态 Transformer 将多种输入类型（文本、图像、音频）整合到单一模型中，实现更丰富的理解。微轮次方法将对话分解为 200 毫秒的小段，实现类似人类对话的实时全双工交互。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://economictimes.indiatimes.com/magazines/panache/mira-muratis-thinking-machines-unveils-ai-models-designed-for-live-human-interaction/articleshow/131028457.cms?from=mdr">Mira Murati’s Thinking Machines unveils AI models designed for live human interaction - The Economic Times</a></li>
<li><a href="https://www.newsbytesapp.com/news/science/mira-murati-s-ai-start-up-unveils-model-built-for-real-time-interactions/story">Mira Murati's AI start-up unveils model built for real-time interactions</a></li>

</ul>
</details>

**社区讨论**: 社区对演示印象深刻，尤其是模型在停顿期间自然等待的能力。然而，一些评论者对经济模式表示怀疑，并指出使用 Gemma4 和 TTS 的本地解决方案已经存在。其他人认为演示场景有些刻意，并对实际商业应用提出质疑。

**标签**: `#AI`, `#multimodal`, `#real-time`, `#transformer`, `#interaction`

---

<a id="item-6"></a>
## [GitLab 裁员并放弃 CREDIT 价值观，转向 AI](https://about.gitlab.com/blog/gitlab-act-2/) ⭐️ 8.0/10

GitLab 宣布在部分地区裁员高达 30%，并终止其 CREDIT 价值观，作为名为“GitLab Act 2”的战略重组的一部分，旨在聚焦 AI 的“代理时代”。 这标志着一家主要 DevOps 公司的重大转变，表明即使是成熟企业也在积极重组以顺应 AI 趋势，可能影响数千名开发者和整个 DevOps 生态系统。 裁员在某些地区影响高达 30%的员工，CREDIT 价值观（协作、结果、效率、多样性、迭代、透明）将被一套与 AI 战略一致的新价值观取代。

hackernews · AnonGitLabEmpl · May 11, 20:51 · [社区讨论](https://news.ycombinator.com/item?id=48100500)

**背景**: GitLab 是一个领先的 DevOps 平台，提供覆盖整个软件开发生命周期的工具。其 CREDIT 价值观是其公司文化的核心部分，强调透明和效率。“代理时代”指的是能够自主决策和执行任务的 AI 代理的兴起。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://handbook.gitlab.com/handbook/values/">GitLab Values | The GitLab Handbook</a></li>
<li><a href="https://cybermediacreations.com/gitlab-announces-workforce-reduction-and-end-of-their-credit-values/">GitLab Announces Workforce Reduction and End of Their CREDIT ...</a></li>
<li><a href="https://time.com/7312641/agentic-ai-era-humans/">What the Agentic AI Era Means for Business—And for Humanity</a></li>

</ul>
</details>

**社区讨论**: 评论者表示怀疑，指出 GitLab 股价一年内腰斩，并质疑裁员如何与抓住“最大机遇”相符。一些人认为这是对投资者压力的回应，以强调 AI，而另一些人则怀疑 AI 能否解决 GitLab 长期存在的产品问题。

**标签**: `#GitLab`, `#layoffs`, `#AI strategy`, `#DevOps`, `#workforce reduction`

---

<a id="item-7"></a>
## [中国强制短视频标注六类标签，含 AI 生成内容](https://www.ithome.com/0/949/320.htm) ⭐️ 8.0/10

中央网信办规定，短视频平台必须要求发布者在发布前从六类“必选标签”中选择一项，包括“含有 AI 生成内容”和“含有虚构演绎内容”。该规定还要求平台在 2025 年底前对存量未标注视频进行清理整改。 该规定直接影响抖音、快手、哔哩哔哩等主要平台及数百万内容创作者，强制要求内容来源和真实性透明化。它回应了人们对 AI 生成和误导性视频日益增长的担忧，为数字生态中的内容标注树立了先例。 六类必选标签包括：“含有虚构演绎内容”、“含有 AI 生成内容”、“含有营销信息”、“内容为转载”、“内容为个人观点”和“无需标注”。其中“无需标注”仅用于真实生活记录类短视频，且不在页面呈现。平台须在 2025 年 5 月底前完成标注系统升级。

rss · IT HOME · May 12, 07:13

**背景**: 短视频已成为中国主流内容消费形式，但深度伪造、AI 生成片段和摆拍内容模糊了现实与虚构的界限。中央网信办此前已在 12 家平台开展试点。新规建立在现有 AI 内容标注要求（如 AI 生成内容水印强制规定）之上，旨在进一步提升透明度。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://www.news.cn/digital/20250902/d08b592223954340af8c02ac3d7161e1/c.html">AI生成内容强制“打标”，内容安全治理迈出关键一步-新华网</a></li>
<li><a href="https://www.qstheory.cn/20250327/f04b851f37724fe183515a16f91f366f/c.html">给AI生成内容加标识的治理启示 - 求是网</a></li>

</ul>
</details>

**标签**: `#regulation`, `#short video`, `#AI content`, `#content moderation`, `#China`

---

<a id="item-8"></a>
## [谷歌发布新一代 TPU，专为 AI 智能体和 SOTA 模型训练设计](https://www.infoq.cn/article/ZsDVWSEQEYWq3D4TQTOe?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

谷歌宣布推出新一代张量处理单元（TPU），专门针对 AI 智能体和最先进（SOTA）模型的训练进行了优化。这标志着针对现代 AI 工作负载不断变化的需求而量身定制的重大硬件进步。 这款新 TPU 对于加速 AI 研究和部署至关重要，尤其是在复杂的基于智能体的系统和前沿模型方面。它将实现更快的迭代和更高效的训练，直接惠及 AI/ML 工程师和研究人员。 该 TPU 利用脉动阵列架构实现高效的矩阵运算，这是神经网络训练的基础。它支持 TensorFlow、JAX 和 PyTorch 框架，确保与现有 AI 工作流的广泛兼容性。

rss · InfoQ 中文站 · May 12, 14:23

**背景**: 张量处理单元（TPU）是谷歌为神经网络机器学习开发的定制专用集成电路（ASIC），于 2015 年首次内部使用。它们旨在加速深度学习中常见的大规模矩阵运算，与通用 GPU 相比提供更高的性能和效率。新一代 TPU 专门针对训练 AI 智能体和 SOTA 模型日益增长的需求，这些模型需要巨大的计算资源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tensor_Processing_Unit">Tensor Processing Unit - Wikipedia</a></li>
<li><a href="https://docs.cloud.google.com/tpu/docs/system-architecture-tpu-vm">TPU architecture | Google Cloud Documentation</a></li>

</ul>
</details>

**标签**: `#TPU`, `#Google`, `#AI hardware`, `#machine learning`, `#training`

---

<a id="item-9"></a>
## [攻击者在 Flippa 购买 30 个 WordPress 插件并植入后门](https://www.infoq.cn/article/UVGOeS0SrX3cCRK6Nac0?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

攻击者在 Flippa 市场上购买了 30 个 WordPress 插件，并在所有插件中植入了后门，从而破坏了软件供应链。 此次供应链攻击可能影响使用这些插件的数千个网站，凸显了从未经审查的第三方市场获取代码的风险。 攻击者可能利用购买的插件分发恶意软件（如远程访问后门），该事件强调了在部署第三方插件前进行严格代码审查的必要性。

rss · InfoQ 中文站 · May 12, 10:07

**背景**: Flippa 是一个买卖在线业务（包括网站和插件）的市场。WordPress 插件是供应链攻击的常见目标，因为它们被广泛使用且安全审查往往不够严格。此前也曾发生过类似攻击，攻击者获取合法插件后注入恶意代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://flippa.com/">Flippa</a></li>

</ul>
</details>

**标签**: `#security`, `#supply chain attack`, `#WordPress`, `#malware`

---

<a id="item-10"></a>
## [Figma 自研 Redis 代理实现六个九可用性](https://www.infoq.cn/article/8Q9hEDB6cqe9qpW6mJh6?utm_source=rss&utm_medium=article) ⭐️ 8.0/10

Figma 开发了 FigCache，这是一个自研的 Redis 代理，通过用统一的无状态数据平面取代碎片化的缓存栈，实现了 99.9999%的可用性。 这展示了先进的分布式系统工程如何显著提升关键基础设施的可靠性，为大规模 Web 应用的缓存层可用性树立了新标杆。 FigCache 将前端层（负责连接管理和协议感知的命令解析）与后端层分离，实现了无状态操作和高弹性。

rss · InfoQ 中文站 · May 11, 21:24

**背景**: Redis 是一种流行的内存数据存储，常用于缓存。实现六个九（99.9999%）的可用性意味着每年停机时间不超过 32 秒，这需要复杂的故障转移和冗余机制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.infoq.com/news/2026/05/figma-redis-figcache/">Figma Builds In-House Redis Proxy to Hit Six Nines Uptime - InfoQ</a></li>
<li><a href="https://www.figma.com/blog/figmas-next-generation-data-caching-platform/">Figma's Next-Generation Data Caching Platform | Figma Blog</a></li>

</ul>
</details>

**标签**: `#Redis`, `#distributed systems`, `#availability`, `#infrastructure`, `#Figma`

---

<a id="item-11"></a>
## [James Shore：AI 编程代理必须降低维护成本](https://simonwillison.net/2026/May/11/james-shore/#atom-everything) ⭐️ 8.0/10

James Shore 认为，AI 编程代理必须按比例降低维护成本以匹配生产力提升，否则将产生不可持续的技术债务。 这一观点揭示了 AI 辅助编程中一个常被忽视的关键后果：代码生成速度提升但维护成本未相应降低，会导致技术债务呈指数级增长，威胁项目的长期可持续性。 Shore 使用了一个简单的数学模型：如果生产力翻倍但维护成本不变，总维护成本将翻倍；如果两者都翻倍，成本将变为四倍。他认为只有当维护成本按生产力提升的倒数比例下降时，等式才能平衡。

rss · Simon Willison · May 11, 19:48

**背景**: AI 编程代理是帮助开发者编写、调试和优化代码的工具。虽然它们能提升短期生产力，但往往优先考虑即时功能而非长期可维护性，从而导致技术债务。技术债务是指为快速但质量不高的代码进行返工的未来成本，当 AI 生成的代码缺乏适当结构或文档时，这种债务会不断累积。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tembo.io/blog/ai-technical-debt">AI Technical Debt : How AI - Generated Code Creates Hidden Costs...</a></li>
<li><a href="https://kodus.io/en/ai-generated-code-is-messing-with-your-technical-debt/">How AI - Generated Code is messing with your Technical Debt</a></li>

</ul>
</details>

**标签**: `#AI coding`, `#software maintenance`, `#productivity`, `#technical debt`, `#LLM`

---

<a id="item-12"></a>
## [你的 AI 使用正在摧毁我的大脑](https://simonwillison.net/2026/May/11/zombie-internet/#atom-everything) ⭐️ 8.0/10

Jason Koebler 在 404 Media 上发表了一篇愤怒但富有洞察力的文章，提出了“僵尸互联网”这一术语，用以描述 AI 生成内容对在线讨论和人类写作风格的普遍且令人精神疲惫的影响。 这篇文章凸显了科技界日益增长的担忧：AI 生成内容正在扭曲真正的人际互动，使互联网变得令人精神疲惫，为“死互联网”理论增添了细微差别。 Koebler 将僵尸互联网定义为人类与机器人对话、使用 AI 的人与非 AI 用户交流，以及为盈利而生成的 AI 垃圾内容（如自动化的 YouTube 频道和虚假的 Reddit 帖子）的混合体。文章强调了不断过滤 AI 垃圾内容所带来的精神负担。

rss · Simon Willison · May 11, 19:21

**背景**: “死互联网理论”是一种阴谋论，认为自 2016 年左右以来，大多数在线内容和互动是由机器人和算法而非人类生成的。随着生成式 AI 的兴起，这一理论重新受到关注，因为 AI 工具现在可以产生大量文本和图像，可能淹没人类创作的内容。Koebler 的“僵尸互联网”将其重新定义为一种更隐蔽的场景，即人类与 AI 纠缠在一起，使得区分真实与合成内容变得更加困难。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dead_Internet_theory">Dead Internet theory</a></li>

</ul>
</details>

**标签**: `#AI`, `#internet culture`, `#content quality`, `#AI ethics`

---

<a id="item-13"></a>
## [Shopify 的 River：在公开 Slack 频道中的 AI 编程代理](https://simonwillison.net/2026/May/11/learning-on-the-shop-floor/#atom-everything) ⭐️ 8.0/10

Shopify CEO Tobias Lütke 透露，其内部 AI 编程代理 River 完全在公开的 Slack 频道中运作，拒绝私信，使所有对话可搜索并对所有员工可见。 这种方法培养了一种透明、协作的学习文化——称为'Lehrwerkstatt'（教学工坊）——员工通过观察真实的编码工作来学习，可能改变团队整合 AI 工具的方式。 River 拒绝私信并坚持使用公开频道；Lütke 自己的频道#tobi_river 有超过 100 名关注者，他们进行互动、补充背景信息并通过观察学习。该设计模仿了 Midjourney 早期的公开 Discord 策略。

rss · Simon Willison · May 11, 15:46

**背景**: AI 编程代理是自主编写或辅助编写代码的工具。通常，这类代理与单个开发者私下交互。Shopify 的 River 打破了这种模式，在公开的 Slack 频道中运作，使每次互动都成为整个组织的学习机会。

**标签**: `#AI-assisted coding`, `#software engineering culture`, `#Shopify`, `#transparency`, `#learning`

---

<a id="item-14"></a>
## [数据中心消耗 3000 万加仑水未被察觉](https://arstechnica.com/tech-policy/2026/05/data-center-used-30-million-gallons-of-water-without-initially-paying/) ⭐️ 8.0/10

一个数据中心在数月内消耗了 3000 万加仑水而未支付费用，凸显了 AI 基础设施隐藏的环境成本。 这一事件凸显了 AI 数据中心的巨大水足迹，尤其是在缺水地区，引发了关于可持续性和监管的紧迫问题。 该数据中心的用水量数月未被察觉，表明监测和计费系统不足。AI 训练和推理需要大量冷却水，一次大型模型训练消耗的水量相当于一个小镇一天的用水量。

rss · Ars Technica · May 11, 20:37

**背景**: 数据中心需要大量水来冷却服务器，尤其是运行 AI 工作负载的数据中心。随着 AI 应用的普及，用水量预计将激增，到 2025 年 AI 数据中心预计将占全球电力和水资源的 4-6%。许多数据中心位于缺水地区，加剧了当地的水资源短缺。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Environmental_impact_of_artificial_intelligence">Environmental impact of artificial intelligence - Wikipedia</a></li>
<li><a href="https://zipdo.co/ai-water-usage-statistics/">AI water usage includes training , inference, and model projections.</a></li>
<li><a href="https://www.linkedin.com/pulse/hidden-cost-ai-draining-water-from-thirsty-himanshu-arya-ql3if">The Hidden Cost of AI : Draining Water from the Thirsty</a></li>

</ul>
</details>

**标签**: `#data centers`, `#AI`, `#environment`, `#water usage`, `#sustainability`

---

<a id="item-15"></a>
## [Starlink 在 IPO 前禁用 GPS 替代方案](https://arstechnica.com/gadgets/2026/05/starlink-blocks-access-to-its-gps-alternative-ahead-of-spacex-ipo/) ⭐️ 8.0/10

Starlink 在 SpaceX 计划 IPO 前关闭了其类似 GPS 的定位功能，该功能利用卫星信号提供定位服务。研究人员目前正在探索逆向工程或解锁该功能的方法。 此举凸显了替代导航系统的战略重要性，以及商业利益与开放研究之间的张力。如果研究人员成功，可能会使基于卫星的定位服务超越 GPS，实现更广泛的普及。 据报道，该功能通过软件更新被禁用，官方未发布有关底层机制的技术细节。研究人员正专注于分析信号模式，并利用软件定义无线电技术来复制定位能力。

rss · Ars Technica · May 11, 17:55

**背景**: GPS（全球定位系统）是一种广泛用于定位和授时的卫星导航系统。替代导航系统，例如利用 Starlink 低地球轨道卫星的系统，可以提供备份或增强能力。Starlink 的该功能被视为 GPS 的潜在竞争对手，尤其是在 GPS 信号较弱的区域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://prod-edam.honeywell.com/content/dam/honeywell-edam/aero/en-us/products/navigation-and-sensors/navigation-systems/alternative-navigation-systems/documents/hon-aero-alt-nav-sys-brochure.pdf?download=false">Alternative Navigation Systems</a></li>
<li><a href="https://actesolutions.se/en/article/positioning-navigation-and-timing-pnt-alternative-to-gps-navigation/">Positioning, Navigation and Timing | ACTE Solutions</a></li>

</ul>
</details>

**标签**: `#Starlink`, `#GPS`, `#satellite navigation`, `#SpaceX`, `#technology`

---

<a id="item-16"></a>
## [考克斯在最高法院的胜诉可能重塑版权责任](https://arstechnica.com/tech-policy/2026/05/sonys-failed-war-against-internet-piracy-may-doom-other-copyright-lawsuits/) ⭐️ 8.0/10

最高法院在索尼音乐娱乐公司诉考克斯通信公司的版权侵权案中裁定考克斯胜诉，可能限制互联网服务提供商对用户盗版行为的责任。 这一裁决可能开创先例，保护技术提供商免于为用户版权侵权承担责任，重塑互联网服务提供商和在线平台的法律环境。 该案涉及考克斯被指控未能终止重复侵权者，但法院认为，互联网服务提供商无需在法定安全港条款之外监控用户活动。

rss · Ars Technica · May 11, 11:00

**背景**: 根据《数字千年版权法》（DMCA），互联网服务提供商如果遵守特定要求（如终止重复侵权者），则可免于版权责任。索尼认为考克斯未能做到这一点，但最高法院支持考克斯，强调互联网服务提供商没有义务主动监控或审查用户内容。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://supreme.justia.com/cases/federal/us/607/24-171/case.pdf">24-171 Cox Communications , Inc. v . Sony Music Entertainment...</a></li>
<li><a href="https://www.loeb.com/en/insights/publications/2024/03/sony-music-entertainment-v-cox-communications-inc">Sony Music Entertainment v . Cox Communications , Inc.</a></li>
<li><a href="https://en.wikisource.org/wiki/Cox_Communications,_Inc._v._Sony_Music_Entertainment">Cox Communications , Inc. v . Sony Music Entertainment - Wikisource...</a></li>

</ul>
</details>

**标签**: `#copyright`, `#Supreme Court`, `#ISP liability`, `#tech policy`, `#piracy`

---

<a id="item-17"></a>
## [Fsnotify 维护者争议引发供应链警报](https://socket.dev/blog/fsnotify-maintainer-dispute-sparks-supply-chain-concerns) ⭐️ 8.0/10

据 Socket.dev 报道，流行的 Go 库 fsnotify 因维护者访问权限变更引发争议，从而引起供应链安全担忧。 Fsnotify 被广泛用于 Go 项目中的文件系统监控，因此任何妥协都可能影响众多下游应用，并凸显开源治理中的更广泛风险。 争议涉及维护者访问权限的变更，可能允许未经授权的代码修改，如果引入恶意代码，则可能导致供应链攻击。

rss · Lobsters · May 12, 03:49

**背景**: Fsnotify 是一个提供跨平台文件系统通知的 Go 库，被许多项目用于监视文件变化。开源供应链安全已成为关键问题，近期事件显示攻击者会投毒流行工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/fsnotify/fsnotify">fsnotify / fsnotify : Cross-platform filesystem notifications for Go . · GitHub</a></li>

</ul>
</details>

**社区讨论**: Lobsters 上的讨论（文章中有链接）可能涉及对维护者信任的担忧以及开源项目需要更好治理的需求，但未提供具体评论。

**标签**: `#Go`, `#supply chain security`, `#open source`, `#maintainer dispute`

---

<a id="item-18"></a>
## [在 LLVM 中对抗 Hyrum 定律](https://maskray.me/blog/2026-05-10-fighting-hyrums-law-in-llvm) ⭐️ 8.0/10

MaskRay 的一篇博客文章探讨了在 LLVM 中缓解 Hyrum 定律的策略，解决了意外行为依赖如何使编译器演进复杂化的问题。 这很重要，因为 Hyrum 定律是软件工程中的一个基本挑战，将其应用于 LLVM 这样的主要编译器基础设施，会影响系统编程人员的工具、优化和长期可维护性。 该文章可能讨论了 LLVM API 或行为中意外依赖的具体示例，并提出了减少对未记录或偶然特性依赖的技术。

rss · Lobsters · May 11, 18:30

**背景**: Hyrum 定律指出：“当一个 API 有足够多的用户时，你在契约中承诺什么并不重要：你系统的所有可观察行为都会被某些人依赖。”这意味着即使是未记录或偶然的行为也会成为事实上的契约，使得在不破坏用户的情况下更改 API 变得困难。LLVM 是一个广泛使用的编译器基础设施，提供用于代码生成、优化和分析的 API，因此容易受到该定律的影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hyrum's_Law">Hyrum's Law</a></li>
<li><a href="https://lawsofsoftwareengineering.com/laws/hyrums-law/">Hyrum's Law | Laws of Software Engineering</a></li>

</ul>
</details>

**社区讨论**: Lobste.rs 上的讨论可能包含编译器开发者和 LLVM 贡献者的见解，一些人同意问题的严重性，另一些人则分享他们在实践中遇到 Hyrum 定律的经历。

**标签**: `#LLVM`, `#compilers`, `#software engineering`, `#Hyrum's Law`, `#systems programming`

---

<a id="item-19"></a>
## [Kettle：可验证软件来源的可信构建系统](https://arxiv.org/pdf/2605.08363) ⭐️ 8.0/10

一篇新学术论文介绍了 Kettle 系统，该系统通过可信构建实现可验证的软件来源，填补了供应链安全中的关键空白。 这项研究意义重大，因为它提供了一种实用方法，确保软件工件能够与其构建过程进行加密关联，这对于抵御供应链攻击和满足合规要求至关重要。 Kettle 专注于可信构建，即构建系统生成包含构建环境、输入和输出元数据的签名声明（证明），从而实现下游验证。

rss · Lobsters · May 12, 03:38

**背景**: 软件来源记录了软件组件的来源和保管链。可信构建通过加密签名构建过程扩展了这一概念，使消费者能够验证二进制文件是否由特定源代码构建且未被篡改。随着 SolarWinds 漏洞等供应链攻击凸显对软件工件信任的需求，这一点变得越来越重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jfrog.com/learn/grc/software-provenance/">What Is Software Provenance? | Secure Supply Chain Practices - JFrog</a></li>
<li><a href="https://www.hashicorp.com/en/blog/software-provenance-why-visibility-into-your-software-supply-chain-matters">Software provenance: Why visibility into your software supply chain matters - HashiCorp</a></li>

</ul>
</details>

**社区讨论**: 未提供 Lobste.rs 上关于 Kettle 的讨论，因此无法获取社区观点。

**标签**: `#software supply chain`, `#security`, `#build systems`, `#provenance`, `#academic paper`

---