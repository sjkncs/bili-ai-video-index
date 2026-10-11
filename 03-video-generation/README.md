# 视频生成论文解读

> 来源：B 站 UP 主 **HyperHorizon**（mid 11470647）合集「视频生成论文解读」
> 快照：**2026-10-11**，共 **32** 集。结构化数据：[items.json](items.json)

## 数据来源 · 计算方法 · 口径限制

**数据来源**：B 站 x/polymer/web-space/seasons_archives_list 取分集列表；逐条调 x/web-interface/view 取 **desc（简介）** 字段——论文完整标题、会议、arXiv 链接、中文摘要全部来自简介。

**计算方法**：简介格式为 【论文分享】<论文全名> (<会议或 arXiv 年份>) — <中文摘要>。会议取标题块末尾括号（**支持嵌套括号**，如 SE(3)、ACM Multimedia (MM '26) 2026）；arXiv 号从 rxiv.org/abs/... 提取，另从 doi.org/10.48550/arXiv.xxxx 回捞。

**口径限制**
- B 站**视频标题**有 80 字符上限，本表的 paper 列取自**简介**而非标题，因此是完整的；原始标题仍可在 [items.json](items.json) 的 vid_title 字段回溯。
- 简介未给出会议或 arXiv 号的条目**保持为空，不做推测**。
- 只索引元数据，不含视频、字幕或论文全文；顺序为投稿顺序，iews 仅为弱热度信号。

## 全部 32 集

| # | paper | venue | category | arXiv | length | B站 |
|---:|---|---|---|---|---:|---|
| 1 | 【视频生成】Seedance 2.0:Advancing Video Generation for World Complexity | - | 视频生成论文解读 | [2604.14148](https://arxiv.org/abs/2604.14148) | 15:53 | [看](https://www.bilibili.com/video/BV1SWbC62EKp) |
| 2 | InstructVVT: Instruction-Driven Video Virtual Try-On without Auxiliary Spatial Priors | arXiv preprint 2026 | 视频生成论文解读 | [2608.14070](https://arxiv.org/abs/2608.14070) | 16:38 | [看](https://www.bilibili.com/video/BV1nV8g6uEne) |
| 3 | LeviTor: 3D Trajectory Oriented Image-to-Video Synthesis | CVPR 2025 | 视频生成论文解读 | [2412.15214](https://arxiv.org/abs/2412.15214) | 15:55 | [看](https://www.bilibili.com/video/BV17GtN6mE9i) |
| 4 | SCoPE: Sightline-Coordinate Positional Encoding for Video Diffusion Transformers | arXiv 2026 | 视频生成论文解读 | [2606.27345](https://arxiv.org/abs/2606.27345) | 18:43 | [看](https://www.bilibili.com/video/BV1JTgN6gEfk) |
| 5 | HOIMask: Towards Generative Masked Modeling for Human Object Interaction Generation | arXiv:2608.15141v1 2026 | 视频生成论文解读 | [2608.15141](https://arxiv.org/abs/2608.15141) | 16:53 | [看](https://www.bilibili.com/video/BV1K58E6rE4o) |
| 6 | PhysGen3D: Crafting a Miniature Interactive World from a Single Image | CVPR 2025 | 视频生成论文解读 | [2503.20746](https://arxiv.org/abs/2503.20746) | 15:52 | [看](https://www.bilibili.com/video/BV1o9gj6iEgk) |
| 7 | PhysStream: Streaming Physics-Grounded Video Generation with Structured Scene Memory and Fine-Grained Motion Control | arXiv 2026 | 视频生成论文解读 | [2609.17521](https://arxiv.org/abs/2609.17521) | 15:22 | [看](https://www.bilibili.com/video/BV14ueu6oEwJ) |
| 8 | Scaling Mixture-of-Experts Video Pretraining for Embodied Intelligence | arXiv 2026 | 视频生成论文解读 | [2607.07675](https://arxiv.org/abs/2607.07675) | 16:25 | [看](https://www.bilibili.com/video/BV1r2tN6WE2D) |
| 9 | MLLM-Guided Semantic Correction for Text-to-Video Generation | arXiv preprint 2026 | 视频生成论文解读 | [2608.16513](https://arxiv.org/abs/2608.16513) | 15:36 | [看](https://www.bilibili.com/video/BV14T8j6qEQD) |
| 10 | Video Generative Models as Geometry Learner | arXiv 2026 | 视频生成论文解读 | [2608.28549](https://arxiv.org/abs/2608.28549) | 15:35 | [看](https://www.bilibili.com/video/BV1FDtT68E6n) |
| 11 | Echo-Forcing: A Scene Memory Framework for Interactive Long Video Generation | arXiv 2026 | 视频生成论文解读 | [2605.16003](https://arxiv.org/abs/2605.16003) | 18:53 | [看](https://www.bilibili.com/video/BV1XyhP62EZK) |
| 12 | CamWorldQA: Perceptual Quality Assessment of Camera-Controlled World Video Generation | arXiv 2026 | 视频生成论文解读 | [2608.18710](https://arxiv.org/abs/2608.18710) | 17:12 | [看](https://www.bilibili.com/video/BV1bm8T6EEzH) |
| 13 | Generative Cinematographer: Composing Camera and Object Motion in 3D | arXiv 2026 | 视频生成论文解读 | [2610.02180](https://arxiv.org/abs/2610.02180) | 15:44 | [看](https://www.bilibili.com/video/BV1aRp36yECo) |
| 14 | LynnReal-Omni: Native multi-modal Video Generation for Agentic Visual Workflows | arXiv 2026 | 视频生成论文解读 | [2609.15863](https://arxiv.org/abs/2609.15863) | 15:44 | [看](https://www.bilibili.com/video/BV1pwec68Ee1) |
| 15 | Open-Sora 2.0: Training a Commercial-Level Video Generation Model in $200k | arXiv 2025 | 视频生成论文解读 | [2503.09642](https://arxiv.org/abs/2503.09642) | 16:31 | [看](https://www.bilibili.com/video/BV1QPg76fEA9) |
| 16 | MeRoPE: Metric Rotary Position Embedding for Camera-Controlled Video Generation | arXiv 2026 | 视频生成论文解读 | [2609.01252](https://arxiv.org/abs/2609.01252) | 16:11 | [看](https://www.bilibili.com/video/BV1VktB6KEjc) |
| 17 | VACE: All-in-One Video Creation and Editing | arXiv 2025 | 视频生成论文解读 | [2503.07598](https://arxiv.org/abs/2503.07598) | 13:30 | [看](https://www.bilibili.com/video/BV1pwud6QENS) |
| 18 | RealWonder: Real-Time Physical Action-Conditioned Video Generation | arXiv 2026 | 视频生成论文解读 | [2603.05449](https://arxiv.org/abs/2603.05449) | 15:26 | [看](https://www.bilibili.com/video/BV1Ss8S6PEAs) |
| 19 | Tether the Subject, Release the Scene: Query-Aware Memory Routing for Long-Horizon Autoregressive Video Generation | arXiv 2026 | 视频生成论文解读 | [2608.26902](https://arxiv.org/abs/2608.26902) | 14:26 | [看](https://www.bilibili.com/video/BV1zjtu6hEzD) |
| 20 | Video Generation Models are General-Purpose Vision Learners | ECCV 2026 | 视频生成论文解读 | [2607.09024](https://arxiv.org/abs/2607.09024) | 14:26 | [看](https://www.bilibili.com/video/BV1bE8p6WEa7) |
| 21 | SlotDiT: Object-Centric Representations for Diffusion Transformers | arXiv 2026 | 视频生成论文解读 | [2609.17414](https://arxiv.org/abs/2609.17414) | 14:43 | [看](https://www.bilibili.com/video/BV1fNeM66E58) |
| 22 | Echo-Infinity: Learning Evolving Memory for Real-Time Infinite Video Generation | arXiv 2026 | 视频生成论文解读 | - | 15:41 | [看](https://www.bilibili.com/video/BV1CNhN6AEqy) |
| 23 | Harnessing Intrinsic Subject-Aware Attention for Controllable Multi-Subject Video Generation | arXiv 2026 | 视频生成论文解读 | [2609.11507](https://arxiv.org/abs/2609.11507) | 14:07 | [看](https://www.bilibili.com/video/BV1isY96hEtz) |
| 24 | Physics-Aware Video Generation via Agentic Planning and Graph-Guided Optimization | arXiv 2026 | 视频生成论文解读 | [2609.13006](https://arxiv.org/abs/2609.13006) | 14:13 | [看](https://www.bilibili.com/video/BV1BNeJ6gEqT) |
| 25 | Spatiotemporally Decoupled Autoregressive Diffusion Model for Human Motion Generation | arXiv 2026 | 视频生成论文解读 | [2608.23279](https://arxiv.org/abs/2608.23279) | 16:24 | [看](https://www.bilibili.com/video/BV1o98S65EPY) |
| 26 | MSEditor: Toward Consistent Multi-Shot Video Editing | arXiv 2026 | 视频生成论文解读 | [2608.17559](https://arxiv.org/abs/2608.17559) | 14:40 | [看](https://www.bilibili.com/video/BV19ybZ6bEJL) |
| 27 | LiveVVT: High-Fidelity Video Virtual Try-On in Real Time | arXiv 2026 | 视频生成论文解读 | [2608.26714](https://arxiv.org/abs/2608.26714) | 15:59 | [看](https://www.bilibili.com/video/BV1zdtn6YE4Q) |
| 28 | Grounded-Exo2Ego: Structured Semantic Grounding for Robust Exocentric-to-Egocentric Video Generation | arXiv 2026 | 视频生成论文解读 | [2608.20534](https://arxiv.org/abs/2608.20534) | 14:25 | [看](https://www.bilibili.com/video/BV1ZyhM6AEyU) |
| 29 | ReCamMaster: Camera-Controlled Generative Rendering from A Single Video | - | 视频生成论文解读 | - | 17:00 | [看](https://www.bilibili.com/video/BV1Bag766Ew6) |
| 30 | Context-Matched Distillation: Teacher Causality for Autoregressive Video Distillation | arXiv 2026 | 视频生成论文解读 | [2608.13391](https://arxiv.org/abs/2608.13391) | 14:34 | [看](https://www.bilibili.com/video/BV1tD8T6jEJZ) |
| 31 | Beyond Text Conditioning: A Systematic Study of MLLM-DiT Fusion for Video Generation | arXiv 2026 | 视频生成论文解读 | [2608.14043](https://arxiv.org/abs/2608.14043) | 15:01 | [看](https://www.bilibili.com/video/BV1E58g6BE86) |
| 32 | JoyAI-Echo: Pushing the Frontier of Long Audio-Visual Generation | Technical Report 2026 | 视频生成论文解读 | - | 15:38 | [看](https://www.bilibili.com/video/BV1TP8v6pELF) |

## 逐条（含中文摘要）

- **【视频生成】Seedance 2.0:Advancing Video Generation for World Complexity**　[arXiv:2604.14148](https://arxiv.org/abs/2604.14148) · [项目页](https://seed.bytedance.com/seedance2_0) · [B站](https://www.bilibili.com/video/BV1SWbC62EKp)
- **InstructVVT: Instruction-Driven Video Virtual Try-On without Auxiliary Spatial Priors**　arXiv preprint 2026 · [arXiv:2608.14070](https://arxiv.org/abs/2608.14070) · [B站](https://www.bilibili.com/video/BV1nV8g6uEne)
  - 用源视频、参考服装和自然语言指令恢复试穿控制，再以 MLLM 奖励和 DiffusionNFT 对生成器进行偏好对齐。
- **LeviTor: 3D Trajectory Oriented Image-to-Video Synthesis**　CVPR 2025 · [arXiv:2412.15214](https://arxiv.org/abs/2412.15214) · [项目页](https://github.com/robbyant-research/LeviTor) · [B站](https://www.bilibili.com/video/BV17GtN6mE9i)
  - 用 K-means 聚类点、相对深度和实例信息构造三维轨迹控制，让图像到视频生成能够处理遮挡、远近变化和复杂运动。
- **SCoPE: Sightline-Coordinate Positional Encoding for Video Diffusion Transformers**　arXiv 2026 · [arXiv:2606.27345](https://arxiv.org/abs/2606.27345) · [项目页](https://visual-ai.github.io/sc) · [B站](https://www.bilibili.com/video/BV1JTgN6gEfk)
  - SCoPE 把每个 token 的 camera ray 作为第二坐标，以加性 Q/K 几何注入让视频扩散 Transformer 更准确地遵循相机轨迹。
- **HOIMask: Towards Generative Masked Modeling for Human Object Interaction Generation**　arXiv:2608.15141v1 2026 · [arXiv:2608.15141](https://arxiv.org/abs/2608.15141) · [B站](https://www.bilibili.com/video/BV1K58E6rE4o)
  - HOIMask 将人和物的运动与接触信号离散化为 2D token map，再用生成式掩码 Transformer 建模交互，并在推理时用接触/穿透损失优化 logits。
- **PhysGen3D: Crafting a Miniature Interactive World from a Single Image**　CVPR 2025 · [arXiv:2503.20746](https://arxiv.org/abs/2503.20746) · [项目页](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_PhysGen3D_Crafting) · [B站](https://www.bilibili.com/video/BV1o9gj6iEgk)
  - 从单图恢复以相机为中心的可交互 3D 场景，用显式物理模拟与 PBR 合成可控未来视频。
- **PhysStream: Streaming Physics-Grounded Video Generation with Structured Scene Memory and Fine-Grained Motion Control**　arXiv 2026 · [arXiv:2609.17521](https://arxiv.org/abs/2609.17521) · [B站](https://www.bilibili.com/video/BV14ueu6oEwJ)
  - 用来自生成历史的几何与对象记忆，配合稀疏的速度增量，让视频模型在多物体场景中边生成、边观察、边接受物理控制。
- **Scaling Mixture-of-Experts Video Pretraining for Embodied Intelligence**　arXiv 2026 · [arXiv:2607.07675](https://arxiv.org/abs/2607.07675) · [项目页](https://github.com/Robbyant/lingbot-video) · [B站](https://www.bilibili.com/video/BV1r2tN6WE2D)
  - 用稀疏混合专家扩大视频模型容量，用具身数据与物理奖励把生成能力推向可行动的世界建模。
- **MLLM-Guided Semantic Correction for Text-to-Video Generation**　arXiv preprint 2026 · [arXiv:2608.16513](https://arxiv.org/abs/2608.16513) · [B站](https://www.bilibili.com/video/BV14T8j6qEQD)
  - SASMA 在视频扩散采样中期引入 MLLM 反馈，以训练无关、可解释的方式纠正语义漂移。
- **Video Generative Models as Geometry Learner**　arXiv 2026 · [arXiv:2608.28549](https://arxiv.org/abs/2608.28549) · [项目页](https://happy-hsy.github.io/projects/GeoNeXt/) · [B站](https://www.bilibili.com/video/BV1FDtT68E6n)
  - 将预训练视频生成模型改造成联合深度与表面法线估计器，以较少的几何标注获得强跨域泛化。
- **Echo-Forcing: A Scene Memory Framework for Interactive Long Video Generation**　arXiv 2026 · [arXiv:2605.16003](https://arxiv.org/abs/2605.16003) · [B站](https://www.bilibili.com/video/BV1XyhP62EZK)
  - 将历史 KV 缓存拆成可保存、可召回、可衰减的场景记忆，在有界缓存内统一支持长时稳定生成与交互控制。
- **CamWorldQA: Perceptual Quality Assessment of Camera-Controlled World Video Generation**　arXiv 2026 · [arXiv:2608.18710](https://arxiv.org/abs/2608.18710) · [B站](https://www.bilibili.com/video/BV1bm8T6EEzH)
  - 论文建立 CamWorldQA 主观评测基准，并提出 CWQA，以空间、时间与光流信息联合预测相机控制生成视频的感知质量。
- **Generative Cinematographer: Composing Camera and Object Motion in 3D**　arXiv 2026 · [arXiv:2610.02180](https://arxiv.org/abs/2610.02180) · [B站](https://www.bilibili.com/video/BV1aRp36yECo)
  - 用共享世界坐标中的相机路径、局部三维运动句柄和三类 guidance maps，控制单图像视频生成。
- **LynnReal-Omni: Native multi-modal Video Generation for Agentic Visual Workflows**　arXiv 2026 · [arXiv:2609.15863](https://arxiv.org/abs/2609.15863) · [项目页](https://github.com/LynnReal-AI/LynnReal-Omni) · [B站](https://www.bilibili.com/video/BV1pwec68Ee1)
  - 用共享多模态扩散 Transformer 统一多种视觉条件、长视频续接与音视频生成，并通过 Flash 路径和轻量解码器降低实时推理成本。
- **Open-Sora 2.0: Training a Commercial-Level Video Generation Model in $200k**　arXiv 2025 · [arXiv:2503.09642](https://arxiv.org/abs/2503.09642) · [项目页](https://github.com/hpcaitech/Open-Sora) · [B站](https://www.bilibili.com/video/BV1QPg76fEA9)
  - 通过数据、模型、训练策略与基础设施协同优化，11B 视频生成模型把单次完整训练成本控制在约 20 万美元，同时取得接近主流商业模型的评测表现。
- **MeRoPE: Metric Rotary Position Embedding for Camera-Controlled Video Generation**　arXiv 2026 · [arXiv:2609.01252](https://arxiv.org/abs/2609.01252) · [B站](https://www.bilibili.com/video/BV1VktB6KEjc)
  - 用正交的射线旋转、度量平移 RoPE 和视差锚点，稳定地表达相机相对运动。
- **VACE: All-in-One Video Creation and Editing**　arXiv 2025 · [arXiv:2503.07598](https://arxiv.org/abs/2503.07598) · [项目页](https://alivilab.github.io/VACE-Page/) · [B站](https://www.bilibili.com/video/BV1pwud6QENS)
  - VACE 把文本、图像、视频和 mask 组织成统一的 Video Condition Unit，
- **RealWonder: Real-Time Physical Action-Conditioned Video Generation**　arXiv 2026 · [arXiv:2603.05449](https://arxiv.org/abs/2603.05449) · [项目页](https://liuwei283.github.io/RealWonder) · [B站](https://www.bilibili.com/video/BV1Ss8S6PEAs)
  - 用物理仿真把连续三维动作转换为光流和粗略 RGB 条件，再由四步因果视频生成器实时还原逼真的动作后果。
- **Tether the Subject, Release the Scene: Query-Aware Memory Routing for Long-Horizon Autoregressive Video Generation**　arXiv 2026 · [arXiv:2608.26902](https://arxiv.org/abs/2608.26902) · [B站](https://www.bilibili.com/video/BV1zjtu6hEzD)
  - 对冻结的视频生成器，在注意力归一化之前按查询角色、空间区域和记忆年龄路由历史信息。
- **Video Generation Models are General-Purpose Vision Learners**　ECCV 2026 · [arXiv:2607.09024](https://arxiv.org/abs/2607.09024) · [项目页](https://genception.github.io) · [B站](https://www.bilibili.com/video/BV1bE8p6WEa7)
  - 把大规模 text-to-video diffusion backbone 重新训练成由文本指令驱动的 feed-forward 通用视觉模型。
- **SlotDiT: Object-Centric Representations for Diffusion Transformers**　arXiv 2026 · [arXiv:2609.17414](https://arxiv.org/abs/2609.17414) · [B站](https://www.bilibili.com/video/BV1fNeM66E58)
  - 用 object-centric slots 替代密集潜变量，让 DiT 直接建模任务相关的对象动态。
- **Echo-Infinity: Learning Evolving Memory for Real-Time Infinite Video Generation**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV1CNhN6AEqy)
- **Harnessing Intrinsic Subject-Aware Attention for Controllable Multi-Subject Video Generation**　arXiv 2026 · [arXiv:2609.11507](https://arxiv.org/abs/2609.11507) · [B站](https://www.bilibili.com/video/BV1isY96hEtz)
  - DIAL 从 DiT 的内在空间主体定位中构造可控注意力引导，并用零额外标注成本的偏好优化抑制高噪声阶段的语义漂移。
- **Physics-Aware Video Generation via Agentic Planning and Graph-Guided Optimization**　arXiv 2026 · [arXiv:2609.13006](https://arxiv.org/abs/2609.13006) · [项目页](https://physplan.github.io/) · [B站](https://www.bilibili.com/video/BV1BNeJ6gEqT)
  - PhysPlan 用 VLM 规划物理状态，用对象级梯度路由和动态强度调度约束视频扩散采样。
- **Spatiotemporally Decoupled Autoregressive Diffusion Model for Human Motion Generation**　arXiv 2026 · [arXiv:2608.23279](https://arxiv.org/abs/2608.23279) · [B站](https://www.bilibili.com/video/BV1o98S65EPY)
  - 连续二维时空潜表示 + 时空掩码自回归扩散，兼顾生成质量与局部编辑。
- **MSEditor: Toward Consistent Multi-Shot Video Editing**　arXiv 2026 · [arXiv:2608.17559](https://arxiv.org/abs/2608.17559) · [B站](https://www.bilibili.com/video/BV19ybZ6bEJL)
  - MSEditor 将多视角监督、Supervisory Adapter、Cross-Shot Packing 与 Sparse Cross Attention 结合，在一次推理中保持多镜头编辑的身份、语义和时间一致性。
- **LiveVVT: High-Fidelity Video Virtual Try-On in Real Time**　arXiv 2026 · [arXiv:2608.26714](https://arxiv.org/abs/2608.26714) · [B站](https://www.bilibili.com/video/BV1zdtn6YE4Q)
  - 用固定滚动窗口和双重记忆，在有限前视下实现高保真、低延迟的长序列视频虚拟试衣。
- **Grounded-Exo2Ego: Structured Semantic Grounding for Robust Exocentric-to-Egocentric Video Generation**　arXiv 2026 · [arXiv:2608.20534](https://arxiv.org/abs/2608.20534) · [项目页](https://research.nvidia.com/labs/amri/pr) · [B站](https://www.bilibili.com/video/BV1ZyhM6AEyU)
  - 用空间几何与物体语义共同约束视频扩散模型，并从数据侧修复几何渲染与真实第一视角之间的错位。
- **ReCamMaster: Camera-Controlled Generative Rendering from A Single Video**　[B站](https://www.bilibili.com/video/BV1Bag766Ew6)
- **Context-Matched Distillation: Teacher Causality for Autoregressive Video Distillation**　arXiv 2026 · [arXiv:2608.13391](https://arxiv.org/abs/2608.13391) · [项目页](https://hmrishavbandy.github.io/) · [B站](https://www.bilibili.com/video/BV1tD8T6jEJZ)
  - 用因果教师、Prefix Scoring 与 Prefix Corruption，让蒸馏监督遵守学生生成目标时真正可见的历史和控制信息。
- **Beyond Text Conditioning: A Systematic Study of MLLM-DiT Fusion for Video Generation**　arXiv 2026 · [arXiv:2608.14043](https://arxiv.org/abs/2608.14043) · [B站](https://www.bilibili.com/video/BV1E58g6BE86)
  - 论文系统比较 MLLM 与 DiT 之间的中间表示、生成机制和融合方式，并以 BiVidGen 用语义视觉 token 引导视频扩散渲染。
- **JoyAI-Echo: Pushing the Frontier of Long Audio-Visual Generation**　Technical Report 2026 · [项目页](https://echo-team-joy-future-academy-jd.github.io/Echo-LongVideo-Page/) · [B站](https://www.bilibili.com/video/BV1TP8v6pELF)
  - 以紧凑的音视频记忆维持长程身份，用记忆感知后训练换取质量与速度，再用 Agent 和超分辨率完成可交互的高分辨率创作。