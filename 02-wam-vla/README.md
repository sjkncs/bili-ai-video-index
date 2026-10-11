# WAM 与 VLA 论文解读

> 来源：B 站 UP 主 **HyperHorizon**（mid 11470647）合集「WAM 与 VLA 论文解读」
> 快照：**2026-10-11**，共 **66** 集。结构化数据：[items.json](items.json)

## 数据来源 · 计算方法 · 口径限制

**数据来源**：B 站 x/polymer/web-space/seasons_archives_list 取分集列表；逐条调 x/web-interface/view 取 **desc（简介）** 字段——论文完整标题、会议、arXiv 链接、中文摘要全部来自简介。

**计算方法**：简介格式为 【论文分享】<论文全名> (<会议或 arXiv 年份>) — <中文摘要>。会议取标题块末尾括号（**支持嵌套括号**，如 SE(3)、ACM Multimedia (MM '26) 2026）；arXiv 号从 rxiv.org/abs/... 提取，另从 doi.org/10.48550/arXiv.xxxx 回捞。

**口径限制**
- B 站**视频标题**有 80 字符上限，本表的 paper 列取自**简介**而非标题，因此是完整的；原始标题仍可在 [items.json](items.json) 的 vid_title 字段回溯。
- 简介未给出会议或 arXiv 号的条目**保持为空，不做推测**。
- 只索引元数据，不含视频、字幕或论文全文；顺序为投稿顺序，iews 仅为弱热度信号。

## 全部 66 集

| # | paper | venue | category | arXiv | length | B站 |
|---:|---|---|---|---|---:|---|
| 1 | Decoupled Early Exits for Task-Dependent Compute Allocation in Flow-Matching VLAs | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.29382](https://arxiv.org/abs/2609.29382) | 15:13 | [看](https://www.bilibili.com/video/BV1upp46QEZQ) |
| 2 | DreamWAM: Beyond RGB Future Prediction for World Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.04996](https://arxiv.org/abs/2608.04996) | 13:12 | [看](https://www.bilibili.com/video/BV1GJuh6PEY6) |
| 3 | Zero-WAM: In-Context World-Action Modeling from Human Videos for Open-Ended Task Generalization | arXiv 2026 | WAM 与 VLA 论文解读 | - | 16:13 | [看](https://www.bilibili.com/video/BV1Yitw6eEin) |
| 4 | InternW0-\Delta: A World Action Model Bridging Predictive Dynamics and Actions with 20K+ Hours of Open Data | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.31394](https://arxiv.org/abs/2609.31394) | 17:18 | [看](https://www.bilibili.com/video/BV1Wqp46GEMc) |
| 5 | A Pragmatic VLA Foundation Model | arXiv 2026 | WAM 与 VLA 论文解读 | [2601.18692](https://arxiv.org/abs/2601.18692) | 16:23 | [看](https://www.bilibili.com/video/BV1NitN6wEyT) |
| 6 | Bridge3D: Enabling Vision-Language-Action Models to See and Act in 3D | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.24525](https://arxiv.org/abs/2609.24525) | 15:34 | [看](https://www.bilibili.com/video/BV1Fchy6gE22) |
| 7 | OpenWAM: An Open, Modular Exploration Towards Systematic World-Action Model Pretraining | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.07398](https://arxiv.org/abs/2609.07398) | 14:17 | [看](https://www.bilibili.com/video/BV1ewe16MEmo) |
| 8 | UniWAM: Unified World-Action Model | arXiv 2026 | WAM 与 VLA 论文解读 | [2610.02054](https://arxiv.org/abs/2610.02054) | 15:33 | [看](https://www.bilibili.com/video/BV1Zzp36REBH) |
| 9 | DiffWAM: A Fast and Efficient Navigation World Action Model | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.39763](https://arxiv.org/abs/2609.39763) | 16:37 | [看](https://www.bilibili.com/video/BV121pG6zEGw) |
| 10 | 3DWay: Generalizing Robot Manipulation via 3D Consistent Waypoints | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.08224](https://arxiv.org/abs/2609.08224) | 17:37 | [看](https://www.bilibili.com/video/BV1iZYK6YEqH) |
| 11 | AffordDrive3D: Affordance-Aware World-Action Modeling with Spatial Understanding | arXiv 2026 | WAM 与 VLA 论文解读 | [2610.11060](https://arxiv.org/abs/2610.11060) | 14:25 | [看](https://www.bilibili.com/video/BV1g6pv6VEHP) |
| 12 | Reflex: Enabling Fast and Predictive Vision-Language-Action Models for Reaction-Critical Manipulation | arXiv:2608.14379v1 2026 | WAM 与 VLA 论文解读 | [2608.14379](https://arxiv.org/abs/2608.14379) | 18:07 | [看](https://www.bilibili.com/video/BV1vW8g6aEq4) |
| 13 | Next Forcing: Causal World Modeling with Multi-Chunk Prediction | arXiv 2026 | WAM 与 VLA 论文解读 | [2606.11187](https://arxiv.org/abs/2606.11187) | 14:23 | [看](https://www.bilibili.com/video/BV13ktP6MEG6) |
| 14 | GaussianWAM: Distilling Geometry and Semantics from 3D Gaussian Fields into World-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.24714](https://arxiv.org/abs/2608.24714) | 15:25 | [看](https://www.bilibili.com/video/BV1HphF6jEPW) |
| 15 | PhysWAM: Physically Consistent World Action Model for Autonomous Driving | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.37970](https://arxiv.org/abs/2609.37970) | 15:39 | [看](https://www.bilibili.com/video/BV1fjpg6DEgf) |
| 16 | DeltaWAM: Delta World Action Models for Bimanual Manipulation | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.28811](https://arxiv.org/abs/2609.28811) | 15:15 | [看](https://www.bilibili.com/video/BV1anhy6xEhZ) |
| 17 | ForeAct3D: Policy-Grounded Future World Modeling for VLA Policies | arXiv 2026 | WAM 与 VLA 论文解读 | [2610.04607](https://arxiv.org/abs/2610.04607) | 15:29 | [看](https://www.bilibili.com/video/BV1tJp36BEgT) |
| 18 | Dynin-Robotics: Omnimodal Unified Diffusion Vision-Language-Action Model | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.13053](https://arxiv.org/abs/2609.13053) | 15:13 | [看](https://www.bilibili.com/video/BV13fe76xE6c) |
| 19 | VideoVLA: Video Generators Can Be Generalizable Robot Manipulators | NeurIPS 2025 | WAM 与 VLA 论文解读 | - | 10:31 | [看](https://www.bilibili.com/video/BV1r9ux6eEqv) |
| 20 | From Foundation to Application: Improving VLA Models in Practice | arXiv 2026 | WAM 与 VLA 论文解读 | [2607.06403](https://arxiv.org/abs/2607.06403) | 16:49 | [看](https://www.bilibili.com/video/BV1rCtN6xELX) |
| 21 | Flex-: A Multi-Stream World-Action Model with Compute Flexibility | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.10860](https://arxiv.org/abs/2608.10860) | 15:21 | [看](https://www.bilibili.com/video/BV1bg4R6uEF8) |
| 22 | GeoScaffold: Learning Compact Geometric Latents via Reconstruction for Efficient Vision-Language Navigation | arXiv 2026 | WAM 与 VLA 论文解读 | [2610.02697](https://arxiv.org/abs/2610.02697) | 15:24 | [看](https://www.bilibili.com/video/BV1uop36VEdb) |
| 23 | Beyond Data Scaling: Representation-Centric Continued Pre-training for Vision-Language-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.27550](https://arxiv.org/abs/2608.27550) | 16:41 | [看](https://www.bilibili.com/video/BV1nYtg6BE54) |
| 24 | DA-WAM: Decision-Aligned Future Latents for Driving World Models | arXiv 2026 | WAM 与 VLA 论文解读 | - | 14:32 | [看](https://www.bilibili.com/video/BV1Xq8q6qEyz) |
| 25 | HABILIS Brain 0: Geometry-Change Supervision for Vision-Language-Action and Residual Flow Recovery | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.25558](https://arxiv.org/abs/2609.25558) | 16:01 | [看](https://www.bilibili.com/video/BV1XFhm6iE24) |
| 26 | 4D-WAM: Infusing Spatiotemporal Awareness into World Action Models through Trajectory Fields | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.08023](https://arxiv.org/abs/2608.08023) | 7:19 | [看](https://www.bilibili.com/video/BV1R9g56ZERG) |
| 27 | V-Link: Recovering Lost Visual Representations in Action DiT for Vision-Language-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | - | 14:58 | [看](https://www.bilibili.com/video/BV1Wjtw67Ewb) |
| 28 | UniMPA: A Unified Memory-Prediction-Action Model via Action-Grounded Transition Modeling | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.11875](https://arxiv.org/abs/2609.11875) | 16:39 | [看](https://www.bilibili.com/video/BV14TYd6QEeQ) |
| 29 | One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.26058](https://arxiv.org/abs/2608.26058) | 16:10 | [看](https://www.bilibili.com/video/BV1ka4f6zEu1) |
| 30 | Breaking the Vision-Action Shortcut: Latent Interface Training for Generalizable Robotics Foundation Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.12641](https://arxiv.org/abs/2609.12641) | 14:37 | [看](https://www.bilibili.com/video/BV1DBeE6ZEYZ) |
| 31 | VGGTWorld-VLA: Intent-Conditioned 3D World Evolution for Autonomous Driving | arXiv 2026 | WAM 与 VLA 论文解读 | [2610.11161](https://arxiv.org/abs/2610.11161) | 14:59 | [看](https://www.bilibili.com/video/BV16Fpi6bEHR) |
| 32 | GeomVLA: Unifying Scene, Motion, and Action in 3D | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.13812](https://arxiv.org/abs/2609.13812) | 15:47 | [看](https://www.bilibili.com/video/BV1wNec6bEvY) |
| 33 | Evolve Vision-Language-Action Model into an Agent with On-the-fly Tool-use | arXiv:2608.14047v1 2026 | WAM 与 VLA 论文解读 | [2608.14047](https://arxiv.org/abs/2608.14047) | 15:42 | [看](https://www.bilibili.com/video/BV1wZ8j6YERR) |
| 34 | Continuous Actions from Discrete Minds: Latent-Aligned Planning for End-to-End Autonomous Driving | arXiv 2026 | WAM 与 VLA 论文解读 | - | 14:44 | [看](https://www.bilibili.com/video/BV1vgbE6JEnQ) |
| 35 | CSWAM: Better Causal Semantic Representations for Out-of-Distribution Generalization in World Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.18462](https://arxiv.org/abs/2609.18462) | 14:45 | [看](https://www.bilibili.com/video/BV1tDeC6oEJP) |
| 36 | TemporalFlow-VLA: Learning Physically Grounded Execution History for Long-Horizon Robot Manipulation | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.26821](https://arxiv.org/abs/2608.26821) | 16:12 | [看](https://www.bilibili.com/video/BV1HStn6qEqM) |
| 37 | FOCAL-VLA: Subtask-Guided Geometry Distillation and Implicit World Modeling for Vision-Language-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.21228](https://arxiv.org/abs/2609.21228) | 16:09 | [看](https://www.bilibili.com/video/BV1yuhn61EpW) |
| 38 | StrataVLA: Hierarchical and Efficient 3D Geometric Grounding for Vision-Language-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.26071](https://arxiv.org/abs/2609.26071) | 23:03 | [看](https://www.bilibili.com/video/BV1Xwhm6NEFv) |
| 39 | GigaBrain-0.7: Scaling Embodied Foundation Models to Emergent Capabilities with a Three-System Architecture | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.15875](https://arxiv.org/abs/2608.15875) | 15:32 | [看](https://www.bilibili.com/video/BV1Dx876VExv) |
| 40 | See like a Robot: Robot-Centric Pointmaps for Vision-Language-Action Models | arXiv:2607.11498v1 2026 | WAM 与 VLA 论文解读 | - | 5:23 | [看](https://www.bilibili.com/video/BV1PiuJ6XEna) |
| 41 | MVG-WAM: Multiple View Geometry-Aware World-Action Modeling for Robotic Manipulation | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.37793](https://arxiv.org/abs/2609.37793) | 13:26 | [看](https://www.bilibili.com/video/BV1FLpg6pECf) |
| 42 | Spatially Aware World Action Model via Geometric Latent Diffusion | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.02531](https://arxiv.org/abs/2609.02531) | 15:37 | [看](https://www.bilibili.com/video/BV1Z1tv6iEWU) |
| 43 | PointWAM: 3D World Action Modeling for Dexterous Robotic Manipulation | arXiv 2026 | WAM 与 VLA 论文解读 | [2610.02840](https://arxiv.org/abs/2610.02840) | 15:24 | [看](https://www.bilibili.com/video/BV1uop36VEoC) |
| 44 | Towards Zero-Shot Transfer Across Embodiments For Driving VLAs | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.02341](https://arxiv.org/abs/2609.02341) | 15:12 | [看](https://www.bilibili.com/video/BV1JAtv6KEsE) |
| 45 | Temporal Forcing: 4D Representation Alignment for Vision-Language-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.30643](https://arxiv.org/abs/2608.30643) | 14:26 | [看](https://www.bilibili.com/video/BV1JEtn6fEPu) |
| 46 | GS-VLA: Plug-and-Play Viewpoint Canonicalization for Frozen VLA Policies via Gaussian Splatting | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.19066](https://arxiv.org/abs/2608.19066) | 15:16 | [看](https://www.bilibili.com/video/BV1Re8q6zEqy) |
| 47 | Qwen-RobotManip Technical Report: Alignment Unlocks Scale for Robotic Manipulation Foundation Models | arXiv 2026 | WAM 与 VLA 论文解读 | - | 13:38 | [看](https://www.bilibili.com/video/BV1EMgj6MEFj) |
| 48 | RAF-VLA: Representation Alignment with the Future for End-to-End Autonomous Driving | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.17728](https://arxiv.org/abs/2609.17728) | 14:52 | [看](https://www.bilibili.com/video/BV1umeC6fEH9) |
| 49 | World Action Models are Zero-shot Policies | arXiv 2026 | WAM 与 VLA 论文解读 | [2602.15922](https://arxiv.org/abs/2602.15922) | 7:51 | [看](https://www.bilibili.com/video/BV1BXuH6UEPk) |
| 50 | SG-WAM: Text-Grounded and Spatial-aware Semantic Guidance for World-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.08839](https://arxiv.org/abs/2608.08839) | 17:33 | [看](https://www.bilibili.com/video/BV1UcgV6LEr3) |
| 51 | ActiveScale: Scaling Active Perception for Robots across Model, Data, and Hardware | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.18514](https://arxiv.org/abs/2609.18514) | 16:38 | [看](https://www.bilibili.com/video/BV1TXeC6xEq9) |
| 52 | From visual foresight to executable navigation | arXiv 2026 | WAM 与 VLA 论文解读 | - | 23:47 | [看](https://www.bilibili.com/video/BV1nQuA6qEC8) |
| 53 | 4DGS-WAM: Bridging Past and Future with an Object-Centric World Action Model based on 4D Gaussian Splatting | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.25956](https://arxiv.org/abs/2608.25956) | 15:00 | [看](https://www.bilibili.com/video/BV1tH4f67EfQ) |
| 54 | XGenAct: Geometry-Enhanced World Action Models through Cross-Task Generation | arXiv 2026 | WAM 与 VLA 论文解读 | [2610.03516](https://arxiv.org/abs/2610.03516) | 14:42 | [看](https://www.bilibili.com/video/BV1aQp362Efe) |
| 55 | Modality-Autoregressive World-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.17524](https://arxiv.org/abs/2609.17524) | 14:41 | [看](https://www.bilibili.com/video/BV1U4eM6xEC1) |
| 56 | DIDO: Distilling Interaction-Centric Dynamics into One-Step Denoising for World Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.15570](https://arxiv.org/abs/2609.15570) | 14:43 | [看](https://www.bilibili.com/video/BV1LEec6UEhs) |
| 57 | Imagine the Future, Internalize the Gist: Efficient VLA Reasoning via Internalized Spatiotemporal Imagination | arXiv 2026 | WAM 与 VLA 论文解读 | [2610.02626](https://arxiv.org/abs/2610.02626) | 14:44 | [看](https://www.bilibili.com/video/BV1hZp36kELr) |
| 58 | GeoWAM: Visual Geometry World Action Models for Autonomous Driving | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.23486](https://arxiv.org/abs/2608.23486) | 15:42 | [看](https://www.bilibili.com/video/BV17Y8X6xEWg) |
| 59 | GIF: Agentic Generation of Interactive and Functional Object Compositions for Robot Learning | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.05927](https://arxiv.org/abs/2609.05927) | 15:49 | [看](https://www.bilibili.com/video/BV1wPYK66EUj) |
| 60 | GaussianDream++: Efficient 3D Gaussian World Modeling for Robotic Manipulation | arXiv 2026 | WAM 与 VLA 论文解读 | - | 19:08 | [看](https://www.bilibili.com/video/BV16v4f6qE4r) |
| 61 | GALA: Geometry-Aware Latent Action Modeling for Vision-Language-Action Model Pretraining across Embodiments | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.21948](https://arxiv.org/abs/2609.21948) | 15:52 | [看](https://www.bilibili.com/video/BV1umhp6tEH9) |
| 62 | A Collaborative Multi-Modality Interaction for VLA-based End-to-End Autonomous Driving | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.20890](https://arxiv.org/abs/2608.20890) | 16:00 | [看](https://www.bilibili.com/video/BV1hshG6YEav) |
| 63 | GaussVLA: Geometry-Aware Spatial Reasoning for Vision-Language-Action Model | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.24959](https://arxiv.org/abs/2608.24959) | 17:57 | [看](https://www.bilibili.com/video/BV1SE4f6EE4t) |
| 64 | GlanceWAM: Sparse Test-Time Imagination for World-Action Models | arXiv 2026 | WAM 与 VLA 论文解读 | [2608.23927](https://arxiv.org/abs/2608.23927) | 15:04 | [看](https://www.bilibili.com/video/BV13khF6YEzp) |
| 65 | World Model for Robot Learning: A Comprehensive Survey | IJRR 2026 | WAM 与 VLA 论文解读 | [2605.00080](https://arxiv.org/abs/2605.00080) | 14:20 | [看](https://www.bilibili.com/video/BV1P88w6xET5) |
| 66 | ZimaBlue: Evolving Generalizable World Action Models through Scalable Video Pre-training | arXiv 2026 | WAM 与 VLA 论文解读 | [2609.00188](https://arxiv.org/abs/2609.00188) | 15:36 | [看](https://www.bilibili.com/video/BV1GLtZ6xEqM) |

## 逐条（含中文摘要）

- **Decoupled Early Exits for Task-Dependent Compute Allocation in Flow-Matching VLAs**　arXiv 2026 · [arXiv:2609.29382](https://arxiv.org/abs/2609.29382) · [B站](https://www.bilibili.com/video/BV1upp46QEZQ)
  - 用轻量 Exit Transformer 和 KV Cache synthesis，把 VLM 深度、动作专家深度、去噪步数变成可联合选择的计算预算。
- **DreamWAM: Beyond RGB Future Prediction for World Action Models**　arXiv 2026 · [arXiv:2608.04996](https://arxiv.org/abs/2608.04996) · [项目页](https://github.com/hustvl/DreamWAM) · [B站](https://www.bilibili.com/video/BV1GJuh6PEY6)
  - DreamWAM 将未来预测从 RGB 像素扩展为外观、运动、几何和语义四种互补状态，并在训练时以结构化监督增强 WAM 的鲁棒动作表示，部署时仍保持 RGB-only。
- **Zero-WAM: In-Context World-Action Modeling from Human Videos for Open-Ended Task Generalization**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV1Yitw6eEin)
  - 用可规模化生成的人类视频任务指令，加上任务均衡的机器人视频动作预训练，使因果世界动作模型能够零样本执行未见任务。
- **InternW0-\Delta: A World Action Model Bridging Predictive Dynamics and Actions with 20K+ Hours of Open Data**　arXiv 2026 · [arXiv:2609.31394](https://arxiv.org/abs/2609.31394) · [B站](https://www.bilibili.com/video/BV1Wqp46GEMc)
  - 用训练期未来监督和几何运动先验，把视频预测表征转化为无需未来视频 rollout 的动作条件。
- **A Pragmatic VLA Foundation Model**　arXiv 2026 · [arXiv:2601.18692](https://arxiv.org/abs/2601.18692) · [项目页](https://github.com/Robbyant/lingbot-vla) · [B站](https://www.bilibili.com/video/BV1NitN6wEyT)
  - 以大规模真实双臂数据为基础，将 VLM、动作专家、深度空间监督和高吞吐训练整合为可跨平台迁移的 VLA 基础模型。
- **Bridge3D: Enabling Vision-Language-Action Models to See and Act in 3D**　arXiv 2026 · [arXiv:2609.24525](https://arxiv.org/abs/2609.24525) · [项目页](https://hustvl.github.io/Bridge3D/) · [B站](https://www.bilibili.com/video/BV1Fchy6gE22)
  - 用冻结的三维视觉基础模型提供隐式空间先验，再用三维语义点场对动作去噪施加显式几何约束。
- **OpenWAM: An Open, Modular Exploration Towards Systematic World-Action Model Pretraining**　arXiv 2026 · [arXiv:2609.07398](https://arxiv.org/abs/2609.07398) · [B站](https://www.bilibili.com/video/BV1ewe16MEmo)
  - 以模块化基础设施支撑受控研究，提炼世界先验、世界—动作协同和跨域预训练的设计原则，并构建 OpenWAM-。
- **UniWAM: Unified World-Action Model**　arXiv 2026 · [arXiv:2610.02054](https://arxiv.org/abs/2610.02054) · [B站](https://www.bilibili.com/video/BV1Zzp36REBH)
  - 用互补数据和互补监督，把语义理解、未来视觉建模与动作生成统一为一个可泛化的机器人模型。
- **DiffWAM: A Fast and Efficient Navigation World Action Model**　arXiv 2026 · [arXiv:2609.39763](https://arxiv.org/abs/2609.39763) · [B站](https://www.bilibili.com/video/BV121pG6zEGw)
  - 用冻结视频模型的多层预测特征和首帧几何，直接解码连续相机轨迹；训练时蒸馏完整视频 roll-out，部署时跳过未来视频生成。
- **3DWay: Generalizing Robot Manipulation via 3D Consistent Waypoints**　arXiv 2026 · [arXiv:2609.08224](https://arxiv.org/abs/2609.08224) · [B站](https://www.bilibili.com/video/BV1iZYK6YEqH)
  - 多视角一致的二维路径点经过三角化后成为显式三维轨迹，可直接执行，也可作为 VLA 的空间先验。
- **AffordDrive3D: Affordance-Aware World-Action Modeling with Spatial Understanding**　arXiv 2026 · [arXiv:2610.11060](https://arxiv.org/abs/2610.11060) · [B站](https://www.bilibili.com/video/BV1g6pv6VEHP)
  - 用共享 VLM 同时预测未来 RGB、深度、可行驶区域、碰撞关键区域和自车轨迹，把世界状态建模对齐到驾驶规划。
- **Reflex: Enabling Fast and Predictive Vision-Language-Action Models for Reaction-Critical Manipulation**　arXiv:2608.14379v1 2026 · [arXiv:2608.14379](https://arxiv.org/abs/2608.14379) · [项目页](https://refl) · [B站](https://www.bilibili.com/video/BV1vW8g6aEq4)
  - 用 ReflexBench 评测延迟敏感的动态操作，并以 ReflexVLA 将未来预测、多帧时序融合与推理加速结合起来。
- **Next Forcing: Causal World Modeling with Multi-Chunk Prediction**　arXiv 2026 · [arXiv:2606.11187](https://arxiv.org/abs/2606.11187) · [项目页](https://github.com/robbyant-research/next-forcing) · [B站](https://www.bilibili.com/video/BV13ktP6MEG6)
  - 用轻量 MCP 模块同时预测多个未来视频块，把局部去噪目标变成密集的长程时间监督。
- **GaussianWAM: Distilling Geometry and Semantics from 3D Gaussian Fields into World-Action Models**　arXiv 2026 · [arXiv:2608.24714](https://arxiv.org/abs/2608.24714) · [B站](https://www.bilibili.com/video/BV1HphF6jEPW)
  - 用共享的三维高斯空间载体，把冻结教师提供的几何与视觉语义监督蒸馏进 WAM 表征，而推理时不增加额外模块。
- **PhysWAM: Physically Consistent World Action Model for Autonomous Driving**　arXiv 2026 · [arXiv:2609.37970](https://arxiv.org/abs/2609.37970) · [B站](https://www.bilibili.com/video/BV1fjpg6DEgf)
  - 用度量空间中的点投影误差，让生成深度与生成自车运动共同对齐到 LiDAR 场景。
- **DeltaWAM: Delta World Action Models for Bimanual Manipulation**　arXiv 2026 · [arXiv:2609.28811](https://arxiv.org/abs/2609.28811) · [B站](https://www.bilibili.com/video/BV1anhy6xEhZ)
  - 用稠密 anchor 保留场景语义，用稀疏 visual delta 描述变化，并通过 SDM 增量更新上下文。
- **ForeAct3D: Policy-Grounded Future World Modeling for VLA Policies**　arXiv 2026 · [arXiv:2610.04607](https://arxiv.org/abs/2610.04607) · [B站](https://www.bilibili.com/video/BV1tJp36BEgT)
  - 用动作条件化的语义三维未来状态，监督VLA策略学习物理上更一致、与计划动作相匹配的场景演化。
- **Dynin-Robotics: Omnimodal Unified Diffusion Vision-Language-Action Model**　arXiv 2026 · [arXiv:2609.13053](https://arxiv.org/abs/2609.13053) · [B站](https://www.bilibili.com/video/BV13fe76xE6c)
  - 用共享的 masked-diffusion 轨迹接口，同时学习动作、动作条件的下一状态、终止目标状态和轨迹到指令的重建，并在推理时组合这些预测。
- **VideoVLA: Video Generators Can Be Generalizable Robot Manipulators**　NeurIPS 2025 · [B站](https://www.bilibili.com/video/BV1r9ux6eEqv)
  - VideoVLA 将预训练视频生成器改造成统一的 Video-Action DiT，同时预测机器人动作与未来视觉结果，以提升开放世界操作泛化。
- **From Foundation to Application: Improving VLA Models in Practice**　arXiv 2026 · [arXiv:2607.06403](https://arxiv.org/abs/2607.06403) · [项目页](https://github.com/Robbyant/lingbot-vla-v2) · [B站](https://www.bilibili.com/video/BV1rCtN6xELX)
  - 以大规模异构数据、全身动作空间和预测性动态建模，缩小 VLA 基础能力与真实机器人应用之间的差距。
- **Flex-: A Multi-Stream World-Action Model with Compute Flexibility**　arXiv 2026 · [arXiv:2608.10860](https://arxiv.org/abs/2608.10860) · [项目页](https://flex-pi.github.io/) · [B站](https://www.bilibili.com/video/BV1bg4R6uEF8)
  - 用冻结的视频 VAE 编码 RGB 与 pointmap，再与 DINO 语义共同预测未来视觉流和动作；同一检查点可在动作独占与完整联合生成之间切换。
- **GeoScaffold: Learning Compact Geometric Latents via Reconstruction for Efficient Vision-Language Navigation**　arXiv 2026 · [arXiv:2610.02697](https://arxiv.org/abs/2610.02697) · [B站](https://www.bilibili.com/video/BV1uop36VEdb)
  - 用训练期的深度、连接性和可通行性重建，学习可被动作策略读取的紧凑几何潜变量。
- **Beyond Data Scaling: Representation-Centric Continued Pre-training for Vision-Language-Action Models**　arXiv 2026 · [arXiv:2608.27550](https://arxiv.org/abs/2608.27550) · [项目页](https://starvla.github.io/VLAct) · [B站](https://www.bilibili.com/video/BV1nYtg6BE54)
  - VLAct 把持续预训练目标从单一动作拟合转向可迁移表示学习：保护 VLM 先验、使用多动作头共同监督，并在 embodiment 之间共享物理上可比的动作语义。
- **DA-WAM: Decision-Aligned Future Latents for Driving World Models**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV1Xq8q6qEyz)
  - 对每条候选轨迹预测它自己的未来，再用对应未来潜变量共同决定轨迹分数。
- **HABILIS Brain 0: Geometry-Change Supervision for Vision-Language-Action and Residual Flow Recovery**　arXiv 2026 · [arXiv:2609.25558](https://arxiv.org/abs/2609.25558) · [B站](https://www.bilibili.com/video/BV1XFhm6iE24)
  - 用多视角未来–当前几何变化训练 VLA 表征，再用几何条件残差流恢复冻结策略。
- **4D-WAM: Infusing Spatiotemporal Awareness into World Action Models through Trajectory Fields**　arXiv 2026 · [arXiv:2608.08023](https://arxiv.org/abs/2608.08023) · [项目页](https://github.com/lishanyqy/4DWAM) · [B站](https://www.bilibili.com/video/BV1R9g56ZERG)
  - 用冻结的 4D 轨迹教师监督 WAM 的中间特征：运动对齐负责局部连续性，目的地对齐负责长时程目标。
- **V-Link: Recovering Lost Visual Representations in Action DiT for Vision-Language-Action Models**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV1Wjtw67Ewb)
  - V-Link 在 VLM 内学习 Spatial Query 与 Semantic Query，并通过不对称路径注入 Action DiT，以恢复动作专家可访问的几何与语义表征。
- **UniMPA: A Unified Memory-Prediction-Action Model via Action-Grounded Transition Modeling**　arXiv 2026 · [arXiv:2609.11875](https://arxiv.org/abs/2609.11875) · [项目页](https://JiuTian-VL.github.io/UniMPA-page/) · [B站](https://www.bilibili.com/video/BV14TYd6QEeQ)
  - 用动作落地的状态转移连接未来意图、可执行经验与场景自适应动作生成。
- **One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation**　arXiv 2026 · [arXiv:2608.26058](https://arxiv.org/abs/2608.26058) · [项目页](https://public-bots) · [B站](https://www.bilibili.com/video/BV1ka4f6zEu1)
  - 用相机可观测的锚点运动统一机器人与人手示范，再用具身几何把共享预测转换为目标机器人的原生控制。
- **Breaking the Vision-Action Shortcut: Latent Interface Training for Generalizable Robotics Foundation Models**　arXiv 2026 · [arXiv:2609.12641](https://arxiv.org/abs/2609.12641) · [项目页](https://magiclab-nus.github.io/LIT) · [B站](https://www.bilibili.com/video/BV1DBeE6ZEYZ)
  - LIT 先在没有图像的条件下学习带空间终点的动作先验，再用姿态监督的潜在接口引入视觉，从结构上限制视觉信息进入动作专家的方式。
- **VGGTWorld-VLA: Intent-Conditioned 3D World Evolution for Autonomous Driving**　arXiv 2026 · [arXiv:2610.11161](https://arxiv.org/abs/2610.11161) · [B站](https://www.bilibili.com/video/BV16Fpi6bEHR)
  - 用动作与驾驶语义条件化 VGGT 几何世界演化，使同一历史场景能够产生与意图一致的未来三维预测。
- **GeomVLA: Unifying Scene, Motion, and Action in 3D**　arXiv 2026 · [arXiv:2609.13812](https://arxiv.org/abs/2609.13812) · [B站](https://www.bilibili.com/video/BV1wNec6bEvY)
  - 在机器人中心的度量三维空间中，把语义场景、潜在未来运动和动作生成统一起来。
- **Evolve Vision-Language-Action Model into an Agent with On-the-fly Tool-use**　arXiv:2608.14047v1 2026 · [arXiv:2608.14047](https://arxiv.org/abs/2608.14047) · [B站](https://www.bilibili.com/video/BV1wZ8j6YERR)
  - ART 将 VLA 的连续动作生成与即时工具调用结合：先增强观测，再完成精细动作，并降低新场景对大规模动作数据的依赖。
- **Continuous Actions from Discrete Minds: Latent-Aligned Planning for End-to-End Autonomous Driving**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV1vgbE6JEnQ)
  - 用残差 VQ-VAE 学到运动学先验，用连续潜变量驱动冻结解码器，在一次前向传播中生成平滑轨迹。
- **CSWAM: Better Causal Semantic Representations for Out-of-Distribution Generalization in World Action Models**　arXiv 2026 · [arXiv:2609.18462](https://arxiv.org/abs/2609.18462) · [B站](https://www.bilibili.com/video/BV1tDeC6oEJP)
  - 用历史条件下的因果语义预测补足外观表示，让 action-only WAM 更能适应未见视觉环境。
- **TemporalFlow-VLA: Learning Physically Grounded Execution History for Long-Horizon Robot Manipulation**　arXiv 2026 · [arXiv:2608.26821](https://arxiv.org/abs/2608.26821) · [B站](https://www.bilibili.com/video/BV1HStn6qEqM)
  - 用训练期的机器人表面时序流监督两个紧凑查询，使 VLA 能利用有物理含义且有正确顺序的执行历史。
- **FOCAL-VLA: Subtask-Guided Geometry Distillation and Implicit World Modeling for Vision-Language-Action Models**　arXiv 2026 · [arXiv:2609.21228](https://arxiv.org/abs/2609.21228) · [项目页](https://zhiyuan-gao.github.io/FOCAL-VLA/) · [B站](https://www.bilibili.com/video/BV1yuhn61EpW)
  - 用当前子任务涉及的实体筛选几何与未来运动监督，并让两类潜表示共同条件化动作生成。
- **StrataVLA: Hierarchical and Efficient 3D Geometric Grounding for Vision-Language-Action Models**　arXiv 2026 · [arXiv:2609.26071](https://arxiv.org/abs/2609.26071) · [B站](https://www.bilibili.com/video/BV1Xwhm6NEFv)
  - 用冻结的三维几何专家产生共享记忆，在视觉语言骨干的浅、中、深层用稀疏适配器按需检索，并用路由与 LRU 缓存控制推理开销。
- **GigaBrain-0.7: Scaling Embodied Foundation Models to Emergent Capabilities with a Three-System Architecture**　arXiv 2026 · [arXiv:2608.15875](https://arxiv.org/abs/2608.15875) · [项目页](https://gigaai.cc/blog/gig) · [B站](https://www.bilibili.com/video/BV1Dx876VExv)
  - GigaBrain-0.7 将异构具身数据、理解规划、未来预测、动作控制和经验强化组织为一个三系统学习闭环。
- **See like a Robot: Robot-Centric Pointmaps for Vision-Language-Action Models**　arXiv:2607.11498v1 2026 · [B站](https://www.bilibili.com/video/BV1PiuJ6XEna)
  - 把每个像素的 3D 坐标提前变换到机器人坐标系，再以保持图像网格的 pointmap 注入预训练 VLA。
- **MVG-WAM: Multiple View Geometry-Aware World-Action Modeling for Robotic Manipulation**　arXiv 2026 · [arXiv:2609.37793](https://arxiv.org/abs/2609.37793) · [B站](https://www.bilibili.com/video/BV1FLpg6pECf)
  - 用标定几何把多相机观测连接起来，再以视角相关的几何状态增强视频—动作扩散模型。
- **Spatially Aware World Action Model via Geometric Latent Diffusion**　arXiv 2026 · [arXiv:2609.02531](https://arxiv.org/abs/2609.02531) · [B站](https://www.bilibili.com/video/BV1Z1tv6iEWU)
  - 用非线性深度归一化把几何信息编码成可被冻结视频 VAE 接受的潜变量帧，并与动作、RGB 未来状态联合扩散预测。
- **PointWAM: 3D World Action Modeling for Dexterous Robotic Manipulation**　arXiv 2026 · [arXiv:2610.02840](https://arxiv.org/abs/2610.02840) · [B站](https://www.bilibili.com/video/BV1uop36VEoC)
  - 在共享三维点轨迹空间中联合预测场景和手的运动，再将手轨迹重定向为机器人动作。
- **Towards Zero-Shot Transfer Across Embodiments For Driving VLAs**　arXiv 2026 · [arXiv:2609.02341](https://arxiv.org/abs/2609.02341) · [B站](https://www.bilibili.com/video/BV1JAtv6KEsE)
  - 用低容量 BEV 辅助任务把多视角图像中的地面物体布局写入 VLA 图像表征，从而改善有限相机 embodiment 下的零样本迁移。
- **Temporal Forcing: 4D Representation Alignment for Vision-Language-Action Models**　arXiv 2026 · [arXiv:2608.30643](https://arxiv.org/abs/2608.30643) · [B站](https://www.bilibili.com/video/BV1JEtn6fEPu)
  - 用历史路径压缩过去观测，并以预训练 4D 几何特征监督历史潜变量，使 VLA 能识别不可见的状态转移与任务进度。
- **GS-VLA: Plug-and-Play Viewpoint Canonicalization for Frozen VLA Policies via Gaussian Splatting**　arXiv 2026 · [arXiv:2608.19066](https://arxiv.org/abs/2608.19066) · [B站](https://www.bilibili.com/video/BV1Re8q6zEqy)
  - 用约 4M 参数的三维高斯 canonicalizer，把相机视角变化转化为冻结 VLA 前的观测空间修复；策略本身无需重新训练。
- **Qwen-RobotManip Technical Report: Alignment Unlocks Scale for Robotic Manipulation Foundation Models**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV1EMgj6MEFj)
  - 通过统一 representation、motion 与 behavior alignment，把异构机器人数据变成可以规模化吸收的训练信号，并用 OOD 泛化而不是单纯 IID 分数检验 foundation model 的真实能力。
- **RAF-VLA: Representation Alignment with the Future for End-to-End Autonomous Driving**　arXiv 2026 · [arXiv:2609.17728](https://arxiv.org/abs/2609.17728) · [B站](https://www.bilibili.com/video/BV1umeC6fEH9)
  - 用未来帧的表征对齐策略隐藏状态，以较低训练与推理代价获得规划相关表示。
- **World Action Models are Zero-shot Policies**　arXiv 2026 · [arXiv:2602.15922](https://arxiv.org/abs/2602.15922) · [项目页](https://dreamzero0.github.io) · [B站](https://www.bilibili.com/video/BV1BXuH6UEPk)
  - DreamZero 把未来视频预测和动作生成绑在一起，让机器人从异质、非重复数据中学习，并把视频中的物理先验迁移到新任务、新环境和新机器人。
- **SG-WAM: Text-Grounded and Spatial-aware Semantic Guidance for World-Action Models**　arXiv 2026 · [arXiv:2608.08839](https://arxiv.org/abs/2608.08839) · [项目页](https://livfour.github.io/SG-WAM/) · [B站](https://www.bilibili.com/video/BV1UcgV6LEr3)
  - 用 VLM 先预测“该操作谁、往哪里动”的未来语义，再用这份语义蓝图同时约束未来视频与机器人动作。
- **ActiveScale: Scaling Active Perception for Robots across Model, Data, and Hardware**　arXiv 2026 · [arXiv:2609.18514](https://arxiv.org/abs/2609.18514) · [项目页](https://active-scale.github.io) · [B站](https://www.bilibili.com/video/BV1TXeC6xEq9)
  - 用姿态约束的时间视觉、超过 1000 小时的人机数据和 AMP 平台，让机器人主动看清再完成操作。
- **From visual foresight to executable navigation**　arXiv 2026 · [项目页](https://dachii-azm.github.io/navwam/) · [B站](https://www.bilibili.com/video/BV1nQuA6qEC8)
  - NavWAM 把未来视觉、目标进展价值和动作块放进同一个 latent canvas，让 navigation world model 从“预测未来再规划”变成可以直接执行动作的闭环策略。
- **4DGS-WAM: Bridging Past and Future with an Object-Centric World Action Model based on 4D Gaussian Splatting**　arXiv 2026 · [arXiv:2608.25956](https://arxiv.org/abs/2608.25956) · [B站](https://www.bilibili.com/video/BV1tH4f67EfQ)
  - 用可渲染的 4D Gaussian 状态保存已观察背景，只对动态物体的 Gaussian 进行动作条件下的未来变换。
- **XGenAct: Geometry-Enhanced World Action Models through Cross-Task Generation**　arXiv 2026 · [arXiv:2610.03516](https://arxiv.org/abs/2610.03516) · [B站](https://www.bilibili.com/video/BV1aQp362Efe)
  - 用一个共享的视频扩散模型，在多种感知空间与动作空间之间进行跨任务生成，从而让结构化空间监督反过来改善机器人控制。
- **Modality-Autoregressive World-Action Models**　arXiv 2026 · [arXiv:2609.17524](https://arxiv.org/abs/2609.17524) · [B站](https://www.bilibili.com/video/BV1U4eM6xEC1)
  - 以点轨迹、DINO 特征和深度等结构化未来作为逐步生成的上下文，最后预测动作。
- **DIDO: Distilling Interaction-Centric Dynamics into One-Step Denoising for World Action Models**　arXiv 2026 · [arXiv:2609.15570](https://arxiv.org/abs/2609.15570) · [B站](https://www.bilibili.com/video/BV1LEec6UEhs)
  - 用交互轨迹、视觉对齐和动态区域精炼，把四步世界模型的操控相关信息压缩到一次去噪中。
- **Imagine the Future, Internalize the Gist: Efficient VLA Reasoning via Internalized Spatiotemporal Imagination**　arXiv 2026 · [arXiv:2610.02626](https://arxiv.org/abs/2610.02626) · [B站](https://www.bilibili.com/video/BV1hZp36kELr)
  - 在视觉潜空间预测任务相关的未来变化，并将完整推理压缩为 Scene Gist Token，以较低延迟保留行为指导。
- **GeoWAM: Visual Geometry World Action Models for Autonomous Driving**　arXiv 2026 · [arXiv:2608.23486](https://arxiv.org/abs/2608.23486) · [B站](https://www.bilibili.com/video/BV17Y8X6xEWg)
  - 用未来几何预测学习场景动态，再用几何动态条件化轨迹规划。
- **GIF: Agentic Generation of Interactive and Functional Object Compositions for Robot Learning**　arXiv 2026 · [arXiv:2609.05927](https://arxiv.org/abs/2609.05927) · [B站](https://www.bilibili.com/video/BV1wPYK66EUj)
  - 从语言或图像提示生成可分离的三维物体，并恢复满足接触、无碰撞且经重力稳定的相对位姿。
- **GaussianDream++: Efficient 3D Gaussian World Modeling for Robotic Manipulation**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV16v4f6qE4r)
  - 用 16 个 World State Tokens 与 4 个 World Prediction Tokens，把训练期的当前/未来 Gaussian supervision 内化为 PaliGemma 的策略表示；部署时只保留 token 和动作路径。
- **GALA: Geometry-Aware Latent Action Modeling for Vision-Language-Action Model Pretraining across Embodiments**　arXiv 2026 · [arXiv:2609.21948](https://arxiv.org/abs/2609.21948) · [B站](https://www.bilibili.com/video/BV1umhp6tEH9)
  - 用三维末端几何补足图像潜在动作的细粒度信息，并通过统一表示提升跨本体 VLA 预训练。
- **A Collaborative Multi-Modality Interaction for VLA-based End-to-End Autonomous Driving**　arXiv 2026 · [arXiv:2608.20890](https://arxiv.org/abs/2608.20890) · [B站](https://www.bilibili.com/video/BV1hshG6YEav)
  - 以最优传输和分布一致性建立多模态交互，再用多轨迹生成与感知风险代价优化驾驶动作。
- **GaussVLA: Geometry-Aware Spatial Reasoning for Vision-Language-Action Model**　arXiv 2026 · [arXiv:2608.24959](https://arxiv.org/abs/2608.24959) · [B站](https://www.bilibili.com/video/BV1SE4f6EE4t)
  - 用三维高斯 token 表示几何，用非自回归空间推理 token 对齐动作生成，并以轻量 Mamba 主干完成语言条件机器人操控。
- **GlanceWAM: Sparse Test-Time Imagination for World-Action Models**　arXiv 2026 · [arXiv:2608.23927](https://arxiv.org/abs/2608.23927) · [B站](https://www.bilibili.com/video/BV13khF6YEzp)
  - 用异步、稀疏的远期视觉预见指导快速动作解码，把视频想象从控制关键路径移开。
- **World Model for Robot Learning: A Comprehensive Survey**　IJRR 2026 · [arXiv:2605.00080](https://arxiv.org/abs/2605.00080) · [项目页](https://ntumars.github.io/wm-robot-survey/) · [B站](https://www.bilibili.com/video/BV1P88w6xET5)
  - 这是一篇以机器人学习为中心的综述：把世界模型统一看作支撑预测、规划、仿真、评估与数据生成的可行动预测结构。
- **ZimaBlue: Evolving Generalizable World Action Models through Scalable Video Pre-training**　arXiv 2026 · [arXiv:2609.00188](https://arxiv.org/abs/2609.00188) · [B站](https://www.bilibili.com/video/BV1GLtZ6xEqM)
  - 以无动作标注的具身视频学习世界动力学，以跨形态机器人轨迹完成动作对齐，再以 Slow–Fast 推理实现快速闭环控制。