# 世界模型论文解读

> 来源：B 站 UP 主 **HyperHorizon**（mid 11470647）合集「世界模型论文解读」
> 快照：**2026-10-11**，共 **83** 集。结构化数据：[items.json](items.json)

## 数据来源 · 计算方法 · 口径限制

**数据来源**：B 站 x/polymer/web-space/seasons_archives_list 取分集列表；逐条调 x/web-interface/view 取 **desc（简介）** 字段——论文完整标题、会议、arXiv 链接、中文摘要全部来自简介。

**计算方法**：简介格式为 【论文分享】<论文全名> (<会议或 arXiv 年份>) — <中文摘要>。会议取标题块末尾括号（**支持嵌套括号**，如 SE(3)、ACM Multimedia (MM '26) 2026）；arXiv 号从 rxiv.org/abs/... 提取，另从 doi.org/10.48550/arXiv.xxxx 回捞。

**口径限制**
- B 站**视频标题**有 80 字符上限，本表的 paper 列取自**简介**而非标题，因此是完整的；原始标题仍可在 [items.json](items.json) 的 vid_title 字段回溯。
- 简介未给出会议或 arXiv 号的条目**保持为空，不做推测**。
- 只索引元数据，不含视频、字幕或论文全文；顺序为投稿顺序，iews 仅为弱热度信号。

## 全部 83 集

| # | paper | venue | category | arXiv | length | B站 |
|---:|---|---|---|---|---:|---|
| 1 | Causal World Modeling for Robot Control | RSS 2026 | 世界模型论文解读 | [2601.21998](https://arxiv.org/abs/2601.21998) | 14:38 | [看](https://www.bilibili.com/video/BV1HNtN6pEaL) |
| 2 | GE-Sim 2.0: A Roadmap Towards Comprehensive Closed-loop Video World Simulators for Robotic Manipulation | arXiv 2026 | 世界模型论文解读 | [2605.27491](https://arxiv.org/abs/2605.27491) | 16:54 | [看](https://www.bilibili.com/video/BV1nC8B6pEzk) |
| 3 | Generative Physical AI in Vision: A Survey | arXiv 2025 | 世界模型论文解读 | [2501.10928](https://arxiv.org/abs/2501.10928) | 16:36 | [看](https://www.bilibili.com/video/BV1ZDgj6BEoo) |
| 4 | TesserAct: Learning 4D Embodied World Models | arXiv 2025 | 世界模型论文解读 | [2504.20995](https://arxiv.org/abs/2504.20995) | 17:24 | [看](https://www.bilibili.com/video/BV17LgE63EDG) |
| 5 | Geometry as Address: Routing Attention to Visual Memory for Long-Horizon Camera-Controlled Video Generation | arXiv 2026 | 世界模型论文解读 | [2609.34722](https://arxiv.org/abs/2609.34722) | 14:55 | [看](https://www.bilibili.com/video/BV1FRph6jEap) |
| 6 | Matrix-Game 2.0: An Open-Source, Real-Time, and Streaming Interactive World Model | arXiv 2025 | 世界模型论文解读 | [2508.13009](https://arxiv.org/abs/2508.13009) | 15:44 | [看](https://www.bilibili.com/video/BV1sqtU6JEWE) |
| 7 | Qwen-RobotWorld Technical Report: Unifying Embodied World Modeling through Language-Conditioned Video Generation | arXiv 2026 | 世界模型论文解读 | - | 13:43 | [看](https://www.bilibili.com/video/BV1Eugj6qEnS) |
| 8 | WALT: Learning World-Model-Aligned Latent Trajectories for Autonomous Driving | arXiv 2026 | 世界模型论文解读 | [2609.30436](https://arxiv.org/abs/2609.30436) | 14:25 | [看](https://www.bilibili.com/video/BV1Khp46jEHh) |
| 9 | WorldWeave: Growing Persistent Geometric Worlds for Video Generation | arXiv 2026 | 世界模型论文解读 | [2609.34221](https://arxiv.org/abs/2609.34221) | 16:04 | [看](https://www.bilibili.com/video/BV1MFpg6YEg3) |
| 10 | WNM-3D: A World Navigation Model with 3D Scene Conditioning for Closed-Loop VLN | arXiv 2026 | 世界模型论文解读 | [2608.07267](https://arxiv.org/abs/2608.07267) | 14:44 | [看](https://www.bilibili.com/video/BV1AWhP6wE4k) |
| 11 | OctWorld: Long-Range World-Consistent Video Generation with Octree-Based 3D Mapping | arXiv 2026 | 世界模型论文解读 | [2609.03919](https://arxiv.org/abs/2609.03919) | 17:11 | [看](https://www.bilibili.com/video/BV1j2bE6REdP) |
| 12 | Epona: Autoregressive Diffusion World Model for Autonomous Driving | ICCV 2025 | 世界模型论文解读 | [2506.24113](https://arxiv.org/abs/2506.24113) | 12:26 | [看](https://www.bilibili.com/video/BV19LuJ6KE9h) |
| 13 | Matrix-Game 3.0: Real-Time and Streaming Interactive World Model with Long-Horizon Memory | arXiv 2026 | 世界模型论文解读 | [2604.08995](https://arxiv.org/abs/2604.08995) | 16:05 | [看](https://www.bilibili.com/video/BV1YLtU6eEof) |
| 14 | GAE: Learning a Geometry-Native Latent Space for 3D-Consistent World Generation | arXiv 2026 | 世界模型论文解读 | [2609.24981](https://arxiv.org/abs/2609.24981) | 15:16 | [看](https://www.bilibili.com/video/BV1pZhC63Er9) |
| 15 | Echo-Memory: A Controlled Study of Memory in Action World Models | arXiv 2026 | 世界模型论文解读 | [2606.09803](https://arxiv.org/abs/2606.09803) | 14:17 | [看](https://www.bilibili.com/video/BV1u9hP6rEhB) |
| 16 | Code as Worlds: Agentic Discovery of Executable World Representations for Physical Reasoning | Technical Report 2026 | 世界模型论文解读 | - | 16:03 | [看](https://www.bilibili.com/video/BV13Btw6PEqM) |
| 17 | Evaluating Gemini Robotics Policies in a Veo World Simulator | arXiv 2025 | 世界模型论文解读 | [2512.10675](https://arxiv.org/abs/2512.10675) | 15:47 | [看](https://www.bilibili.com/video/BV17K8S67EyT) |
| 18 | Advancing Open-source World Models | arXiv 2026 | 世界模型论文解读 | [2601.20540](https://arxiv.org/abs/2601.20540) | 16:09 | [看](https://www.bilibili.com/video/BV11etN6aEST) |
| 19 | 4Director: Controlling Video World Models with Rigid 3D Geometry | arXiv 2026 | 世界模型论文解读 | [2610.02160](https://arxiv.org/abs/2610.02160) | 16:17 | [看](https://www.bilibili.com/video/BV1fBp36xEeF) |
| 20 | PointZero: 3D Point Track Completion for Learning Transferable 3D Dynamics | arXiv 2026 | 世界模型论文解读 | [2609.19142](https://arxiv.org/abs/2609.19142) | 14:59 | [看](https://www.bilibili.com/video/BV1EGey6kEB9) |
| 21 | WALL-SS: Scaling Long-horizon World Models via Next-Scale Autoregression | arXiv 2026 | 世界模型论文解读 | [2608.26239](https://arxiv.org/abs/2608.26239) | 15:34 | [看](https://www.bilibili.com/video/BV1JRtn6PEpv) |
| 22 | Matrix-Game 3.5: Enhancing Real-Time Streaming Interactive World Models with Patch Memory | arXiv 2026 | 世界模型论文解读 | [2608.29910](https://arxiv.org/abs/2608.29910) | 13:54 | [看](https://www.bilibili.com/video/BV1fbt76WEvq) |
| 23 | WoVoGen: World Volume-aware Diffusion for Controllable Multi-camera Driving Scene Generation | ECCV 2024 | 世界模型论文解读 | - | 16:42 | [看](https://www.bilibili.com/video/BV1vYgL6wErA) |
| 24 | Matrix-Game: Interactive World Foundation Model | arXiv 2025 | 世界模型论文解读 | - | 14:28 | [看](https://www.bilibili.com/video/BV1yBtU6UEqy) |
| 25 | VideoTok4D: A 4D-Aware Video Tokenizer for Compact World Representation | arXiv 2026 | 世界模型论文解读 | [2609.12874](https://arxiv.org/abs/2609.12874) | 14:46 | [看](https://www.bilibili.com/video/BV1qMeJ6MEC6) |
| 26 | Unfold The World: Factorize 4D Properties in Reinforcing Spatial Reasoning | arXiv 2026 | 世界模型论文解读 | [2609.03729](https://arxiv.org/abs/2609.03729) | 17:01 | [看](https://www.bilibili.com/video/BV1bnbE6kEMr) |
| 27 | GaussianDWM++: Language-Grounded 3D Gaussian Driving World Model for Unified Scene Understanding, Editing, and Multi-Modal Generation | IEEE TPAMI 2026 | 世界模型论文解读 | - | 17:31 | [看](https://www.bilibili.com/video/BV1e98L6jEPn) |
| 28 | Pelican-Sim 1.0: A General World Model Simulator for Embodied Intelligence | arXiv 2026 | 世界模型论文解读 | [2609.12036](https://arxiv.org/abs/2609.12036) | 15:15 | [看](https://www.bilibili.com/video/BV1C7eE6VELN) |
| 29 | Proxy2World: Learning to Generate Worlds From Lightweight Proxies without Seeing Them | arXiv 2026 | 世界模型论文解读 | [2609.35023](https://arxiv.org/abs/2609.35023) | 14:53 | [看](https://www.bilibili.com/video/BV1N6ph6dER7) |
| 30 | WorldGym: World Model as an Environment for Policy Evaluation | arXiv 2025 | 世界模型论文解读 | [2506.00613](https://arxiv.org/abs/2506.00613) | 15:35 | [看](https://www.bilibili.com/video/BV1jg8S6yEjN) |
| 31 | OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving | ECCV 2024 | 世界模型论文解读 | [2311.16038](https://arxiv.org/abs/2311.16038) | 17:45 | [看](https://www.bilibili.com/video/BV1irgJ6GEgv) |
| 32 | LeFlow: Generative Latent Flow Planning for World Models | arXiv 2026 | 世界模型论文解读 | [2608.24855](https://arxiv.org/abs/2608.24855) | 16:00 | [看](https://www.bilibili.com/video/BV13shA6kEjo) |
| 33 | Astronex-World 1.0: Real-Time Interactive World Model Foundation | arXiv 2026 | 世界模型论文解读 | [2609.20034](https://arxiv.org/abs/2609.20034) | 17:46 | [看](https://www.bilibili.com/video/BV1Ufe46jEeC) |
| 34 | Temporal Triplane Transformers as Occupancy World Models | arXiv 2025 | 世界模型论文解读 | [2503.07338](https://arxiv.org/abs/2503.07338) | 18:28 | [看](https://www.bilibili.com/video/BV1VJgE6BEf1) |
| 35 | Code World Model: Coding Agent as World Brain | arXiv 2026 | 世界模型论文解读 | - | 16:21 | [看](https://www.bilibili.com/video/BV1g1hw6uEkc) |
| 36 | Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | NeurIPS 2024 | 世界模型论文解读 | - | 15:59 | [看](https://www.bilibili.com/video/BV1BtgL6vEqS) |
| 37 | 面向实时交互式视频生成的 frame-wise autoregression | arXiv 2026 | 世界模型论文解读 | - | 12:53 | [看](https://www.bilibili.com/video/BV1PmM96JELX) |
| 38 | ConfAL-WM: Confidence-Guided Active Learning for Action-Conditioned World Models | arXiv 2026 | 世界模型论文解读 | [2608.25572](https://arxiv.org/abs/2608.25572) | 13:50 | [看](https://www.bilibili.com/video/BV1Pgtw6pEmT) |
| 39 | SpatialCrafter: Single Image World Modeling with Generative 3D Proxies | arXiv 2026 | 世界模型论文解读 | [2608.27073](https://arxiv.org/abs/2608.27073) | 15:28 | [看](https://www.bilibili.com/video/BV1Uqtn61Ebu) |
| 40 | CLAP: Cross-Embodiment Video World Models are Zero-Shot Physical Simulators | arXiv 2026 | 世界模型论文解读 | [2608.27406](https://arxiv.org/abs/2608.27406) | 16:50 | [看](https://www.bilibili.com/video/BV1P1tn63E6D) |
| 41 | World2Motion: Turning Video World Models into 3D Human Motion Generators | arXiv 2026 | 世界模型论文解读 | [2609.37004](https://arxiv.org/abs/2609.37004) | 15:38 | [看](https://www.bilibili.com/video/BV1oJpg6SEDX) |
| 42 | Programmable World Model | arXiv 2026 | 世界模型论文解读 | [2609.10540](https://arxiv.org/abs/2609.10540) | 15:51 | [看](https://www.bilibili.com/video/BV14GY56TEUg) |
| 43 | Honeycomb: Constant-Size Scene Memory Representation for Video World Models | arXiv 2026 | 世界模型论文解读 | [2609.37690](https://arxiv.org/abs/2609.37690) | 15:13 | [看](https://www.bilibili.com/video/BV1Agpg6dET8) |
| 44 | SPW-Nav: A Streaming Panoramic World Model for Language-Guided Navigation | arXiv 2026 | 世界模型论文解读 | [2610.08941](https://arxiv.org/abs/2610.08941) | 16:42 | [看](https://www.bilibili.com/video/BV1KVpt6mEJ9) |
| 45 | WorldSculpt: Generating Compositional Worlds from Grounded Videos | arXiv 2026 | 世界模型论文解读 | [2609.05416](https://arxiv.org/abs/2609.05416) | 15:18 | [看](https://www.bilibili.com/video/BV15Zb36NEL5) |
| 46 | Relationally Grounded Latent World Models for Autonomous Driving | arXiv 2026 | 世界模型论文解读 | [2609.24626](https://arxiv.org/abs/2609.24626) | 13:59 | [看](https://www.bilibili.com/video/BV1xQhC6LEq2) |
| 47 | RenderWorld: World Model with Self-Supervised 3D Label | - | 世界模型论文解读 | [2409.11356](https://arxiv.org/abs/2409.11356) | 15:49 | [看](https://www.bilibili.com/video/BV12jg76DEgn) |
| 48 | WorldAlign: Decoupled 4D Reward for World-Consistent Video Generation | arXiv 2026 | 世界模型论文解读 | [2610.12382](https://arxiv.org/abs/2610.12382) | 15:29 | [看](https://www.bilibili.com/video/BV1Adpv6wEp9) |
| 49 | WorldMAP: Bootstrapping Vision-Language Navigation Trajectory Prediction with Generative World Models | arXiv 2026 | 世界模型论文解读 | [2604.07957](https://arxiv.org/abs/2604.07957) | 20:32 | [看](https://www.bilibili.com/video/BV19igL6FEab) |
| 50 | DUET-DINO: Simultaneous Cross-View World Modeling for Latent Planning in Robot Manipulation | arXiv 2026 | 世界模型论文解读 | [2609.10506](https://arxiv.org/abs/2609.10506) | 15:07 | [看](https://www.bilibili.com/video/BV1seYV6AEKx) |
| 51 | DWMP: Leveraging Dual World Models for Humanoid Obstacle Traversal | arXiv 2026 | 世界模型论文解读 | [2609.12347](https://arxiv.org/abs/2609.12347) | 15:39 | [看](https://www.bilibili.com/video/BV1SreE6dEa2) |
| 52 | IntactWorld: Joint World Modeling with Intact Features | arXiv 2026 | 世界模型论文解读 | [2610.11174](https://arxiv.org/abs/2610.11174) | 15:26 | [看](https://www.bilibili.com/video/BV1EPpi6dEZF) |
| 53 | The Matrix: Infinite-Horizon World Generation with Real-Time Moving Control | arXiv 2024 | 世界模型论文解读 | [2412.03568](https://arxiv.org/abs/2412.03568) | 14:53 | [看](https://www.bilibili.com/video/BV1gutS6tEwn) |
| 54 | DepthWorld: 3D World Model for Robot Manipulation | arXiv 2026 | 世界模型论文解读 | [2610.08780](https://arxiv.org/abs/2610.08780) | 16:01 | [看](https://www.bilibili.com/video/BV1xsp36NEiA) |
| 55 | World Simulation with Video Foundation Models for Physical AI | arXiv 2025 | 世界模型论文解读 | [2511.00062](https://arxiv.org/abs/2511.00062) | 15:28 | [看](https://www.bilibili.com/video/BV1Eu8S6LE75) |
| 56 | AlayaVista: Streaming World Modeling from Panoramic States to Perspective Video | arXiv 2026 | 世界模型论文解读 | [2609.14462](https://arxiv.org/abs/2609.14462) | 15:45 | [看](https://www.bilibili.com/video/BV16Mec6xErX) |
| 57 | NeuIDO: Neural Intrinsic Dynamics Operator for Physics-Informed 4D World Models | arXiv 2026 | 世界模型论文解读 | [2609.24313](https://arxiv.org/abs/2609.24313) | 15:51 | [看](https://www.bilibili.com/video/BV1VEh26vEVg) |
| 58 | GeoWM: Efficient Direct World Modeling in Explicit Geometry | arXiv 2026 | 世界模型论文解读 | [2610.07381](https://arxiv.org/abs/2610.07381) | 14:12 | [看](https://www.bilibili.com/video/BV1Whp36cEHC) |
| 59 | STRIKE: Learning Visual State Transitions for Physical World Modeling | arXiv 2026 | 世界模型论文解读 | [2610.09514](https://arxiv.org/abs/2610.09514) | 15:03 | [看](https://www.bilibili.com/video/BV1Bmp46vE8R) |
| 60 | OccSora: 4D Occupancy Generation Models as World Simulators for Autonomous Driving | - | 世界模型论文解读 | - | 15:54 | [看](https://www.bilibili.com/video/BV1Y1gJ6zEcX) |
| 61 | Artemis: Geometry-Grounded Multi-Agent Driving World Models with Shared 3D State and Progressive Memory Update | arXiv 2026 | 世界模型论文解读 | [2610.07031](https://arxiv.org/abs/2610.07031) | 15:54 | [看](https://www.bilibili.com/video/BV1Whp36cEv7) |
| 62 | World in World: Explore the World with World Models | arXiv 2026 | 世界模型论文解读 | [2609.11548](https://arxiv.org/abs/2609.11548) | 14:41 | [看](https://www.bilibili.com/video/BV1zeYD6ZE6X) |
| 63 | WorldCrafter: Consistent Video World Model with Implicit 3D-aware Memory | arXiv 2026 | 世界模型论文解读 | [2609.24984](https://arxiv.org/abs/2609.24984) | 14:23 | [看](https://www.bilibili.com/video/BV1nfhC66EVP) |
| 64 | RoGSW4RLD: Feed-Forward 4D Gaussian Lifting for Robot World Model Rollouts | arXiv 2026 | 世界模型论文解读 | [2609.35311](https://arxiv.org/abs/2609.35311) | 15:51 | [看](https://www.bilibili.com/video/BV1Jjpg6QEp7) |
| 65 | 面向闭环自动驾驶仿真的实时生成式世界模型 | arXiv 2026 | 世界模型论文解读 | [2606.03159](https://arxiv.org/abs/2606.03159) | 15:07 | [看](https://www.bilibili.com/video/BV1LSu76KE69) |
| 66 | World Motion Models: Flexible Sequence Modeling of SE(3) Trajectories | arXiv 2026 | 世界模型论文解读 | [2610.01742](https://arxiv.org/abs/2610.01742) | 16:02 | [看](https://www.bilibili.com/video/BV17yp36HEPS) |
| 67 | USR-Drive: Unified Driving Scene Representation via Joint Denoising of 3D Gaussians and Boxes | arXiv 2026 | 世界模型论文解读 | [2608.19036](https://arxiv.org/abs/2608.19036) | 16:05 | [看](https://www.bilibili.com/video/BV1eB8T6sEjp) |
| 68 | Latent Spatial Memory for Video World Models | arXiv 2026 | 世界模型论文解读 | [2606.09828](https://arxiv.org/abs/2606.09828) | 12:54 | [看](https://www.bilibili.com/video/BV1vcuo63EGx) |
| 69 | Occupancy World Model for Robots | arXiv 2025 | 世界模型论文解读 | [2505.05512](https://arxiv.org/abs/2505.05512) | 16:03 | [看](https://www.bilibili.com/video/BV1aDgJ6KEjR) |
| 70 | Infinite Worlds with Versatile Interactions | arXiv 2026 | 世界模型论文解读 | [2607.07534](https://arxiv.org/abs/2607.07534) | 16:08 | [看](https://www.bilibili.com/video/BV16mtN6XEoX) |
| 71 | Latent-Foresight: End-to-End Learning Predictable Representations for Latent World Models | arXiv 2026 | 世界模型论文解读 | [2610.01942](https://arxiv.org/abs/2610.01942) | 14:38 | [看](https://www.bilibili.com/video/BV16ip36oE6t) |
| 72 | StrucPhysVideo: Learning Physical Dynamics from Structured Captions and Robot Actions | arXiv 2026 | 世界模型论文解读 | [2609.18430](https://arxiv.org/abs/2609.18430) | 14:44 | [看](https://www.bilibili.com/video/BV1Rney6TEvm) |
| 73 | H3-World: Turning Language Understanding into World Control | arXiv 2026 | 世界模型论文解读 | [2609.01560](https://arxiv.org/abs/2609.01560) | 15:34 | [看](https://www.bilibili.com/video/BV1aYtR6jE9R) |
| 74 | TourPhysics: Bringing Physics to World Models for Exploration and Manipulation from a Single Image | arXiv 2026 | 世界模型论文解读 | [2609.04911](https://arxiv.org/abs/2609.04911) | 16:10 | [看](https://www.bilibili.com/video/BV1nkb36VE9G) |
| 75 | Kepler4D: Controllable Future Video Generation via 4D Scene State Evolution | arXiv 2026 | 世界模型论文解读 | [2610.04152](https://arxiv.org/abs/2610.04152) | 15:26 | [看](https://www.bilibili.com/video/BV18Ep36uEYS) |
| 76 | ZYT-World: A Real-Time Controllable World Model for Closed-Loop Autonomous-Driving Simulation | arXiv 2026 | 世界模型论文解读 | [2609.21712](https://arxiv.org/abs/2609.21712) | 15:10 | [看](https://www.bilibili.com/video/BV14xhk65EUw) |
| 77 | TrAct: Bridging Robot Control and Visual Prediction with Visual Tracks | arXiv 2026 | 世界模型论文解读 | [2608.24101](https://arxiv.org/abs/2608.24101) | 15:51 | [看](https://www.bilibili.com/video/BV1D8hA6MEx8) |
| 78 | SolarWM: Open Data and Scalable Training for Long-Horizon Video World Models | arXiv 2026 | 世界模型论文解读 | [2609.02886](https://arxiv.org/abs/2609.02886) | 13:30 | [看](https://www.bilibili.com/video/BV1RVtv6tE45) |
| 79 | GeoVerse: World-Consistent Novel View Synthesis in Geometric Latent Space | arXiv 2026 | 世界模型论文解读 | [2609.35734](https://arxiv.org/abs/2609.35734) | 15:43 | [看](https://www.bilibili.com/video/BV1ENp46PEmg) |
| 80 | Hydra-0: Action Flow for Generalist World Modeling and Control | arXiv 2026 | 世界模型论文解读 | [2608.18077](https://arxiv.org/abs/2608.18077) | 17:13 | [看](https://www.bilibili.com/video/BV1fT8S61Ess) |
| 81 | Dream4ACT: A Shared Visual Action Interface for Multi-Embodiment Video-Action Modeling | arXiv 2026 | 世界模型论文解读 | [2609.40153](https://arxiv.org/abs/2609.40153) | 14:30 | [看](https://www.bilibili.com/video/BV1TKpG6TEw8) |
| 82 | Recursive Code World Models: Building Complex Worlds through Recursive Scene Programs | arXiv 2026 | 世界模型论文解读 | [2609.11499](https://arxiv.org/abs/2609.11499) | 15:19 | [看](https://www.bilibili.com/video/BV1XhY964EDe) |
| 83 | HelloWorld: Towards Practical Applications of Generative Driving World Models | arXiv 2026 | 世界模型论文解读 | [2609.28931](https://arxiv.org/abs/2609.28931) | 13:38 | [看](https://www.bilibili.com/video/BV1gshy6XENZ) |

## 逐条（含中文摘要）

- **Causal World Modeling for Robot Control**　RSS 2026 · [arXiv:2601.21998](https://arxiv.org/abs/2601.21998) · [项目页](https://github.com/Robbyant/lingbot-va) · [B站](https://www.bilibili.com/video/BV1HNtN6pEaL)
  - 用因果自回归视频—动作世界模型，把未来视觉状态预测、动作解码和闭环反馈统一起来。
- **GE-Sim 2.0: A Roadmap Towards Comprehensive Closed-loop Video World Simulators for Robotic Manipulation**　arXiv 2026 · [arXiv:2605.27491](https://arxiv.org/abs/2605.27491) · [B站](https://www.bilibili.com/video/BV1nC8B6pEzk)
  - \small 以动作条件多视角视频生成作为视觉基础，加入状态专家、World Judge 与加速推理，形成可评测、可学习的机器人操作闭环模拟器。
- **Generative Physical AI in Vision: A Survey**　arXiv 2025 · [arXiv:2501.10928](https://arxiv.org/abs/2501.10928) · [项目页](https://github.com/BestJunYu/Awesome-Physics-aware-Generation) · [B站](https://www.bilibili.com/video/BV1ZDgj6BEoo)
  - 用“显式模拟 / 隐式学习”统一整理视觉生成中的物理知识注入方式，并讨论评测缺口与未来路线。
- **TesserAct: Learning 4D Embodied World Models**　arXiv 2025 · [arXiv:2504.20995](https://arxiv.org/abs/2504.20995) · [项目页](https://TesserActWorld.github.io) · [B站](https://www.bilibili.com/video/BV17LgE63EDG)
  - 用 RGB、深度和法线视频作为轻量四维表示，再恢复时空一致的三维场景并服务机器人动作规划。
- **Geometry as Address: Routing Attention to Visual Memory for Long-Horizon Camera-Controlled Video Generation**　arXiv 2026 · [arXiv:2609.34722](https://arxiv.org/abs/2609.34722) · [B站](https://www.bilibili.com/video/BV1FRph6jEap)
  - 用每帧几何建立稀疏的视觉记忆地址，让 GCA 在去噪时直接读取相关历史 patch，并以 Invisible Octree 过滤遮挡错误。
- **Matrix-Game 2.0: An Open-Source, Real-Time, and Streaming Interactive World Model**　arXiv 2025 · [arXiv:2508.13009](https://arxiv.org/abs/2508.13009) · [B站](https://www.bilibili.com/video/BV1sqtU6JEWE)
  - 用大规模动作标注数据、动作注入和少步因果蒸馏，把交互式视频生成推进到长时段、流式、25 FPS。
- **Qwen-RobotWorld Technical Report: Unifying Embodied World Modeling through Language-Conditioned Video Generation**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV1Eugj6qEnS)
  - 用自然语言统一动作接口，把 manipulation、driving、navigation 与 human-to-robot transfer 放进同一个视频状态转移模型。
- **WALT: Learning World-Model-Aligned Latent Trajectories for Autonomous Driving**　arXiv 2026 · [arXiv:2609.30436](https://arxiv.org/abs/2609.30436) · [B站](https://www.bilibili.com/video/BV1Khp46jEHh)
  - 冻结驾驶世界模型，学习与其视觉表征对齐的紧凑轨迹 latent，用更低的规划计算量获得更好的 NAVSIM 规划分数。
- **WorldWeave: Growing Persistent Geometric Worlds for Video Generation**　arXiv 2026 · [arXiv:2609.34221](https://arxiv.org/abs/2609.34221) · [B站](https://www.bilibili.com/video/BV1MFpg6YEg3)
  - 用显式、可寻址的几何世界保存地形、区域、资产和接口，再用只读几何查询为视频生成提供深度条件。
- **WNM-3D: A World Navigation Model with 3D Scene Conditioning for Closed-Loop VLN**　arXiv 2026 · [arXiv:2608.07267](https://arxiv.org/abs/2608.07267) · [B站](https://www.bilibili.com/video/BV1AWhP6wE4k)
  - 从单目历史提取固定长度三维场景前缀，条件化联合生成未来视觉和导航动作，并用闭环数据逐阶段适配。
- **OctWorld: Long-Range World-Consistent Video Generation with Octree-Based 3D Mapping**　arXiv 2026 · [arXiv:2609.03919](https://arxiv.org/abs/2609.03919) · [B站](https://www.bilibili.com/video/BV1j2bE6REdP)
  - 用稀疏、空间自适应的八叉树 TSDF 记忆融合生成的 RGB-D 观察，支撑长程、可控且世界一致的视频扩散生成。
- **Epona: Autoregressive Diffusion World Model for Autonomous Driving**　ICCV 2025 · [arXiv:2506.24113](https://arxiv.org/abs/2506.24113) · [项目页](https://github.com/Kevin-thu/Epona) · [B站](https://www.bilibili.com/video/BV19LuJ6KE9h)
  - Epona 用连续 latent 中的自回归时序建模连接高保真下一帧生成与多步轨迹规划，并通过 Chain-of-Forward 训练把视频 rollout 延长到两分钟级。
- **Matrix-Game 3.0: Real-Time and Streaming Interactive World Model with Long-Horizon Memory**　arXiv 2026 · [arXiv:2604.08995](https://arxiv.org/abs/2604.08995) · [B站](https://www.bilibili.com/video/BV1YLtU6eEof)
  - 用误差感知训练、相机感知记忆、多段蒸馏和系统级加速，把交互视频生成推进到 720p 实时流式场景。
- **GAE: Learning a Geometry-Native Latent Space for 3D-Consistent World Generation**　arXiv 2026 · [arXiv:2609.24981](https://arxiv.org/abs/2609.24981) · [B站](https://www.bilibili.com/video/BV1pZhC63Er9)
  - 将冻结几何基础模型的多层特征压缩成一个同时可读出 RGB、深度、相机和点图的紧凑潜空间，再在这个空间中进行条件流匹配生成。
- **Echo-Memory: A Controlled Study of Memory in Action World Models**　arXiv 2026 · [arXiv:2606.09803](https://arxiv.org/abs/2606.09803) · [B站](https://www.bilibili.com/video/BV1u9hP6rEhB)
  - 在统一动作世界模型接口下，受控比较不同记忆表示，并用回放、闭环回访和开放域回访分离“跟随轨迹”与“记住世界”。
- **Code as Worlds: Agentic Discovery of Executable World Representations for Physical Reasoning**　Technical Report 2026 · [项目页](https://mirros-lab.github.io/code-as-world) · [B站](https://www.bilibili.com/video/BV13Btw6PEqM)
  - 用可执行代码表达物理组成、动态演化和视觉外观，再通过智能体循环从多模态证据中搜索可验证的世界假设，并为定量物理推理提供监督。
- **Evaluating Gemini Robotics Policies in a Veo World Simulator**　arXiv 2025 · [arXiv:2512.10675](https://arxiv.org/abs/2512.10675) · [B站](https://www.bilibili.com/video/BV17K8S67EyT)
  - 用可编辑、动作条件、多视角一致的视频世界，预测机器人策略在常规、OOD 与安全场景中的相对表现。
- **Advancing Open-source World Models**　arXiv 2026 · [arXiv:2601.20540](https://arxiv.org/abs/2601.20540) · [项目页](https://github.com/Robbyant/lingbot-world) · [B站](https://www.bilibili.com/video/BV11etN6aEST)
  - 以混合数据引擎和多阶段演化训练，把视频生成器变成具备动作控制、长时记忆和实时交互能力的世界模拟器。
- **4Director: Controlling Video World Models with Rigid 3D Geometry**　arXiv 2026 · [arXiv:2610.02160](https://arxiv.org/abs/2610.02160) · [B站](https://www.bilibili.com/video/BV1fBp36xEeF)
  - 用完整物体网格和逐帧刚性变换锁定三维运动，再由视频生成器补全外观与动态。
- **PointZero: 3D Point Track Completion for Learning Transferable 3D Dynamics**　arXiv 2026 · [arXiv:2609.19142](https://arxiv.org/abs/2609.19142) · [B站](https://www.bilibili.com/video/BV1EGey6kEB9)
  - 用单张 RGB-D 观测和一至三条稀疏完整轨迹，预测所有观测点的未来三维运动，并将这种无机器人预训练迁移到动力学建模与模仿学习。
- **WALL-SS: Scaling Long-horizon World Models via Next-Scale Autoregression**　arXiv 2026 · [arXiv:2608.26239](https://arxiv.org/abs/2608.26239) · [B站](https://www.bilibili.com/video/BV1JRtn6PEpv)
  - 用下一尺度自回归把动作条件视觉预测、受限长时记忆和视觉动力学对齐统一起来。
- **Matrix-Game 3.5: Enhancing Real-Time Streaming Interactive World Models with Patch Memory**　arXiv 2026 · [arXiv:2608.29910](https://arxiv.org/abs/2608.29910) · [B站](https://www.bilibili.com/video/BV1fbt76WEvq)
  - 用无新增主体参数的几何感知记忆、静态/动态解耦和两阶段实时蒸馏，把长时一致性与实时交互放进同一个因果生成系统。
- **WoVoGen: World Volume-aware Diffusion for Controllable Multi-camera Driving Scene Generation**　ECCV 2024 · [项目页](https://github.com/fudan-zvg/WoVoGen) · [B站](https://www.bilibili.com/video/BV1vYgL6wErA)
  - 先预测受车辆动作控制的 4D world volume，再以其约束多相机视频扩散生成，同时支持天气、物体与相机视角编辑。
- **Matrix-Game: Interactive World Foundation Model**　arXiv 2025 · [B站](https://www.bilibili.com/video/BV1yBtU6UEqy)
  - 从参考图像和逐帧动作生成可控、连贯并具有空间结构的游戏世界视频。
- **VideoTok4D: A 4D-Aware Video Tokenizer for Compact World Representation**　arXiv 2026 · [arXiv:2609.12874](https://arxiv.org/abs/2609.12874) · [B站](https://www.bilibili.com/video/BV1qMeJ6MEC6)
  - 用静态与动态 token 共同编码动态世界，并以相机条件渲染和 token-space diffusion 实现紧凑、可复用的 4D 表征。
- **Unfold The World: Factorize 4D Properties in Reinforcing Spatial Reasoning**　arXiv 2026 · [arXiv:2609.03729](https://arxiv.org/abs/2609.03729) · [B站](https://www.bilibili.com/video/BV1bnbE6kEMr)
  - FactoSR 将空间推理分解为 XY 平面对应、Z 深度次序与 T 时间可逆性，并以可验证奖励训练 VLM。
- **GaussianDWM++: Language-Grounded 3D Gaussian Driving World Model for Unified Scene Understanding, Editing, and Multi-Modal Generation**　IEEE TPAMI 2026 · [B站](https://www.bilibili.com/video/BV1e98L6jEPn)
  - Qwen foundation features 进入显式 3D Gaussian，再压缩为共享的语言兼容 world tokens。
- **Pelican-Sim 1.0: A General World Model Simulator for Embodied Intelligence**　arXiv 2026 · [arXiv:2609.12036](https://arxiv.org/abs/2609.12036) · [B站](https://www.bilibili.com/video/BV1C7eE6VELN)
  - 用统一的 28 维动作值、URDF 渲染动作视频和稀疏 MoE，构建跨机器人、跨场景的可控视觉模拟器。
- **Proxy2World: Learning to Generate Worlds From Lightweight Proxies without Seeing Them**　arXiv 2026 · [arXiv:2609.35023](https://arxiv.org/abs/2609.35023) · [B站](https://www.bilibili.com/video/BV1N6ph6dER7)
  - 用普通的有位姿 RGBD 视频学习一个共享世界模型，在采样时先遵循代理结构，再联合细化几何与外观。
- **WorldGym: World Model as an Environment for Policy Evaluation**　arXiv 2025 · [arXiv:2506.00613](https://arxiv.org/abs/2506.00613) · [B站](https://www.bilibili.com/video/BV1jg8S6yEjN)
  - 用动作条件视频世界模型承载策略闭环，用视觉语言模型从生成轨迹中给出任务奖励。
- **OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving**　ECCV 2024 · [arXiv:2311.16038](https://arxiv.org/abs/2311.16038) · [项目页](https://doi.org/10.1007/978-3-031-72624-8_4) · [B站](https://www.bilibili.com/video/BV1irgJ6GEgv)
  - 把驾驶场景压缩成离散 3D occupancy token，再以 GPT 式时空模型联合预测未来场景与自车轨迹。
- **LeFlow: Generative Latent Flow Planning for World Models**　arXiv 2026 · [arXiv:2608.24855](https://arxiv.org/abs/2608.24855) · [B站](https://www.bilibili.com/video/BV13shA6kEjo)
  - 在冻结的潜在世界模型上学习可复用的潜在轨迹先验，以批量生成和滚动重排序替代反复的在线动作优化。
- **Astronex-World 1.0: Real-Time Interactive World Model Foundation**　arXiv 2026 · [arXiv:2609.20034](https://arxiv.org/abs/2609.20034) · [项目页](https://world.astronex.com.cn) · [B站](https://www.bilibili.com/video/BV1Ufe46jEeC)
  - 用统一的文字、图像、相机和动作条件，把 5B 视频先验变成可实时流式交互的世界模型。
- **Temporal Triplane Transformers as Occupancy World Models**　arXiv 2025 · [arXiv:2503.07338](https://arxiv.org/abs/2503.07338) · [B站](https://www.bilibili.com/video/BV1VJgE6BEf1)
  - 用紧凑 triplane 表征和多尺度增量预测，同时提升 4D 占据预测、运动规划与实时性。
- **Code World Model: Coding Agent as World Brain**　arXiv 2026 · [项目页](https://buaacyw.github.io/cwm/) · [B站](https://www.bilibili.com/video/BV1g1hw6uEkc)
  - 用编码智能体和可执行代码维护世界，用 proxy 约束视频生成，从而把持久的规则演化与高保真的视觉实现结合起来。
- **Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability**　NeurIPS 2024 · [项目页](https://opendrivelab.com/Vista) · [B站](https://www.bilibili.com/video/BV1BtgL6vEqS)
  - Vista 以高分辨率视频扩散模型为基础，同时解决跨域泛化、长时一致性与多模态动作控制，并把生成不确定性转化为无需真值动作的奖励。
- **面向实时交互式视频生成的 frame-wise autoregression**　arXiv 2026 · [B站](https://www.bilibili.com/video/BV1PmM96JELX)
- **ConfAL-WM: Confidence-Guided Active Learning for Action-Conditioned World Models**　arXiv 2026 · [arXiv:2608.25572](https://arxiv.org/abs/2608.25572) · [项目页](https://ConfAL-WM.github.io) · [B站](https://www.bilibili.com/video/BV1Pgtw6pEmT)
  - 在 EVAC 上学习密集置信度，用它选择更有信息量的 RoboTwin2.0 数据，并加强高风险帧与局部 patch 的世界模型监督。
- **SpatialCrafter: Single Image World Modeling with Generative 3D Proxies**　arXiv 2026 · [arXiv:2608.27073](https://arxiv.org/abs/2608.27073) · [B站](https://www.bilibili.com/video/BV1Uqtn61Ebu)
  - 单张参考图先生成全局 3D Proxy，再把它渲染成粗 RGB-D 轨迹，并交给视频扩散模型补全外观与未观测区域。
- **CLAP: Cross-Embodiment Video World Models are Zero-Shot Physical Simulators**　arXiv 2026 · [arXiv:2608.27406](https://arxiv.org/abs/2608.27406) · [项目页](https://omni-clap.github.io) · [B站](https://www.bilibili.com/video/BV1P1tn63E6D)
  - 用跨具身视频数据学习通用物理先验，并以多种动作表示支持零样本机器人预测与规划。
- **World2Motion: Turning Video World Models into 3D Human Motion Generators**　arXiv 2026 · [arXiv:2609.37004](https://arxiv.org/abs/2609.37004) · [B站](https://www.bilibili.com/video/BV1oJpg6SEDX)
  - 用视频世界模型的环境先验，联合生成场景感知的三维人体运动与对应视频。
- **Programmable World Model**　arXiv 2026 · [arXiv:2609.10540](https://arxiv.org/abs/2609.10540) · [B站](https://www.bilibili.com/video/BV14GY56TEUg)
  - 用可执行状态和规则管理世界演化，再用带结构控制的生成式视频模型渲染可见观察。
- **Honeycomb: Constant-Size Scene Memory Representation for Video World Models**　arXiv 2026 · [arXiv:2609.37690](https://arxiv.org/abs/2609.37690) · [B站](https://www.bilibili.com/video/BV1Agpg6dET8)
  - 用六个固定大小的空间与时空特征平面，递归融合新视频块，并为后续视角生成提供可查询的场景记忆。
- **SPW-Nav: A Streaming Panoramic World Model for Language-Guided Navigation**　arXiv 2026 · [arXiv:2610.08941](https://arxiv.org/abs/2610.08941) · [项目页](https://alaya-lab.github.io/SPW-Nav) · [B站](https://www.bilibili.com/video/BV1KVpt6mEJ9)
  - 从单张全景图出发，理解连续语言指令，生成可切换指令的 2K、360 度、实时流式视频。
- **WorldSculpt: Generating Compositional Worlds from Grounded Videos**　arXiv 2026 · [arXiv:2609.05416](https://arxiv.org/abs/2609.05416) · [项目页](https://alaya-lab.github.io/WorldSculpt) · [B站](https://www.bilibili.com/video/BV15Zb36NEL5)
  - 把单物体三维生成先验接到对齐的多视角证据上，在不做场景级训练的前提下生成大规模组合式网格世界。
- **Relationally Grounded Latent World Models for Autonomous Driving**　arXiv 2026 · [arXiv:2609.24626](https://arxiv.org/abs/2609.24626) · [B站](https://www.bilibili.com/video/BV1xQhC6LEq2)
  - 用训练期场景图语义对齐视觉潜变量，使世界模型显式保留交互关系，并在不增加推理成本的情况下改善轨迹误差与碰撞率。
- **RenderWorld: World Model with Self-Supervised 3D Label**　[arXiv:2409.11356](https://arxiv.org/abs/2409.11356) · [B站](https://www.bilibili.com/video/BV12jg76DEgn)
- **WorldAlign: Decoupled 4D Reward for World-Consistent Video Generation**　arXiv 2026 · [arXiv:2610.12382](https://arxiv.org/abs/2610.12382) · [B站](https://www.bilibili.com/video/BV1Adpv6wEp9)
  - 语义分离动态主体与静态环境，再让几何先验和 VLM 先验各自评价它们。
- **WorldMAP: Bootstrapping Vision-Language Navigation Trajectory Prediction with Generative World Models**　arXiv 2026 · [arXiv:2604.07957](https://arxiv.org/abs/2604.07957) · [项目页](https://doi.org/10.48550/arXiv.2604.07957) · [B站](https://www.bilibili.com/video/BV19igL6FEab)
  - 用世界模型生成未来视角，再经语义空间记忆与显式规划构造轨迹监督，蒸馏出测试时轻量运行的导航学生模型。
- **DUET-DINO: Simultaneous Cross-View World Modeling for Latent Planning in Robot Manipulation**　arXiv 2026 · [arXiv:2609.10506](https://arxiv.org/abs/2609.10506) · [项目页](https://utn-air.github.io/DUET-DINO) · [B站](https://www.bilibili.com/video/BV1seYV6AEKx)
  - 用跨视角条件化的 DINOv3 潜在预测，联合优化侧视与腕视目标代价，从而支持完整七自由度的零样本操作规划。
- **DWMP: Leveraging Dual World Models for Humanoid Obstacle Traversal**　arXiv 2026 · [arXiv:2609.12347](https://arxiv.org/abs/2609.12347) · [B站](https://www.bilibili.com/video/BV1SreE6dEa2)
  - 用 Koopman 动力学世界模型处理本体感觉，用 RSSM 视觉世界模型压缩深度观测，再融合两者训练可部署的人形机器人障碍穿越策略。
- **IntactWorld: Joint World Modeling with Intact Features**　arXiv 2026 · [arXiv:2610.11174](https://arxiv.org/abs/2610.11174) · [B站](https://www.bilibili.com/video/BV1EPpi6dEZF)
  - 用不压缩的世界特征学习结构，再用紧凑 token 进行高效引导。
- **The Matrix: Infinite-Horizon World Generation with Real-Time Moving Control**　arXiv 2024 · [arXiv:2412.03568](https://arxiv.org/abs/2412.03568) · [B站](https://www.bilibili.com/video/BV1gutS6tEwn)
  - 用少量带控制信号的 AAA 游戏数据，加上大量无标注真实视频，训练能够无限延展、实时响应并跨场景泛化的 720p 世界模拟器。
- **DepthWorld: 3D World Model for Robot Manipulation**　arXiv 2026 · [arXiv:2610.08780](https://arxiv.org/abs/2610.08780) · [B站](https://www.bilibili.com/video/BV1xsp36NEiA)
  - 用机器人坐标系中的三维标定数据训练 RGB--深度联合世界模型，使多视角 rollout 更具几何一致性。
- **World Simulation with Video Foundation Models for Physical AI**　arXiv 2025 · [arXiv:2511.00062](https://arxiv.org/abs/2511.00062) · [B站](https://www.bilibili.com/video/BV1Eu8S6LE75)
  - \small 以大规模视频数据和流匹配为基础，把通用世界生成、可控世界转换与 Physical AI 应用连接起来。
- **AlayaVista: Streaming World Modeling from Panoramic States to Perspective Video**　arXiv 2026 · [arXiv:2609.14462](https://arxiv.org/abs/2609.14462) · [项目页](https://alaya-lab.github.io/AlayaVista) · [B站](https://www.bilibili.com/video/BV16Mec6xErX)
  - 用全景潜状态维护广域动态上下文，用视口渲染与局部细化生成当前用户需要的透视视频。
- **NeuIDO: Neural Intrinsic Dynamics Operator for Physics-Informed 4D World Models**　arXiv 2026 · [arXiv:2609.24313](https://arxiv.org/abs/2609.24313) · [B站](https://www.bilibili.com/video/BV1VEh26vEVg)
  - 从多场景视频学习统一的内在动力学表示，并将其用于物理一致的四维生成与快速泛化。
- **GeoWM: Efficient Direct World Modeling in Explicit Geometry**　arXiv 2026 · [arXiv:2610.07381](https://arxiv.org/abs/2610.07381) · [B站](https://www.bilibili.com/video/BV1Whp36cEHC)
  - 将冻结的几何基础模型、轻量相机运动预测器和 horizon-conditioned flow-matching transformer 组合起来，直接预测指定未来时刻的深度与三维几何。
- **STRIKE: Learning Visual State Transitions for Physical World Modeling**　arXiv 2026 · [arXiv:2610.09514](https://arxiv.org/abs/2610.09514) · [项目页](https://strike-applied.github.io/) · [B站](https://www.bilibili.com/video/BV1Bmp46vE8R)
  - 用事件和时间显式预测稀疏视觉状态，再把这些状态作为软条件交给视频动力学模型。
- **OccSora: 4D Occupancy Generation Models as World Simulators for Autonomous Driving**　[项目页](https://doi.org/10.1109/TIP) · [B站](https://www.bilibili.com/video/BV1Y1gJ6zEcX)
- **Artemis: Geometry-Grounded Multi-Agent Driving World Models with Shared 3D State and Progressive Memory Update**　arXiv 2026 · [arXiv:2610.07031](https://arxiv.org/abs/2610.07031) · [B站](https://www.bilibili.com/video/BV1Whp36cEv7)
  - 用显式共享三维世界状态约束多智能体视频生成，并通过几何记忆与姿态记忆维持长时域一致性。
- **World in World: Explore the World with World Models**　arXiv 2026 · [arXiv:2609.11548](https://arxiv.org/abs/2609.11548) · [B站](https://www.bilibili.com/video/BV1zeYD6ZE6X)
  - 以相机、时间和空间支持信息标注的视觉状态，统一接入冻结因果视频世界模型的原生 self-attention。
- **WorldCrafter: Consistent Video World Model with Implicit 3D-aware Memory**　arXiv 2026 · [arXiv:2609.24984](https://arxiv.org/abs/2609.24984) · [B站](https://www.bilibili.com/video/BV1nfhC66EVP)
  - 用目标相机查询的隐式 3D 感知记忆，帮助视频世界模型在长时域探索中重访一致、控制准确，并保持流式生成。
- **RoGSW4RLD: Feed-Forward 4D Gaussian Lifting for Robot World Model Rollouts**　arXiv 2026 · [arXiv:2609.35311](https://arxiv.org/abs/2609.35311) · [B站](https://www.bilibili.com/video/BV1Jjpg6QEp7)
  - 将同步的机器人多视角 rollout 直接提升为可按视角和时间查询的度量四维高斯场。
- **面向闭环自动驾驶仿真的实时生成式世界模型**　arXiv 2026 · [arXiv:2606.03159](https://arxiv.org/abs/2606.03159) · [项目页](https://github.com/nv-tlabs/omni-dreams) · [B站](https://www.bilibili.com/video/BV1LSu76KE69)
  - OmniDreams 把 Cosmos 视频扩散模型改造成可实时响应动作的闭环自动驾驶世界模型，并验证其仿真与策略迁移能力。
- **World Motion Models: Flexible Sequence Modeling of SE(3) Trajectories**　arXiv 2026 · [arXiv:2610.01742](https://arxiv.org/abs/2610.01742) · [B站](https://www.bilibili.com/video/BV17yp36HEPS)
- **USR-Drive: Unified Driving Scene Representation via Joint Denoising of 3D Gaussians and Boxes**　arXiv 2026 · [arXiv:2608.19036](https://arxiv.org/abs/2608.19036) · [B站](https://www.bilibili.com/video/BV1eB8T6sEjp)
  - USR-Drive 把密集、可渲染的 3D Gaussians 与稀疏的 3D 物体框作为共同场景状态，在同一个多模态扩散过程中相互约束、联合生成。
- **Latent Spatial Memory for Video World Models**　arXiv 2026 · [arXiv:2606.09828](https://arxiv.org/abs/2606.09828) · [项目页](https://aka) · [B站](https://www.bilibili.com/video/BV1vcuo63EGx)
  - Mirage 将世界模型的持久 3D memory 从 RGB point cloud 搬到 diffusion latent space，
- **Occupancy World Model for Robots**　arXiv 2025 · [arXiv:2505.05512](https://arxiv.org/abs/2505.05512) · [B站](https://www.bilibili.com/video/BV1aDgJ6KEjR)
  - RoboOccWorld 用联合时空感受野和下一步相机位姿引导的自回归 Transformer，预测室内机器人未来的细粒度 3D 语义占据。
- **Infinite Worlds with Versatile Interactions**　arXiv 2026 · [arXiv:2607.07534](https://arxiv.org/abs/2607.07534) · [项目页](https://github.com/Robbyant/lingbot-world-v2) · [B站](https://www.bilibili.com/video/BV16mtN6XEoX)
  - 以因果视频生成、少步蒸馏和智能体协同，构建可持续、可控制、可实时探索的开放世界。
- **Latent-Foresight: End-to-End Learning Predictable Representations for Latent World Models**　arXiv 2026 · [arXiv:2610.01942](https://arxiv.org/abs/2610.01942) · [B站](https://www.bilibili.com/video/BV16ip36oE6t)
  - 联合学习 VFM 特征 tokenizer 与 flow-based dynamics，让潜在表示同时可重建、可预测，并服务于未来场景理解。
- **StrucPhysVideo: Learning Physical Dynamics from Structured Captions and Robot Actions**　arXiv 2026 · [arXiv:2609.18430](https://arxiv.org/abs/2609.18430) · [B站](https://www.bilibili.com/video/BV1Rney6TEvm)
  - 用物理相关视频筛选与结构化标注提供监督，再以语言或机器人末端动作条件化视频世界模型，预测连续且可交互的场景演化。
- **H3-World: Turning Language Understanding into World Control**　arXiv 2026 · [arXiv:2609.01560](https://arxiv.org/abs/2609.01560) · [B站](https://www.bilibili.com/video/BV1aYtR6jE9R)
  - 用组合式语言动作和单出口时序路由，把 MiniMax-H3 的粗粒度语言控制转化为精细的角色与相机控制。
- **TourPhysics: Bringing Physics to World Models for Exploration and Manipulation from a Single Image**　arXiv 2026 · [arXiv:2609.04911](https://arxiv.org/abs/2609.04911) · [B站](https://www.bilibili.com/video/BV1nkb36VE9G)
  - 用模拟器负责状态与轨迹，用视频生成器负责外观，再用质量门和几何记忆把两者连接成持久的探索—操作循环。
- **Kepler4D: Controllable Future Video Generation via 4D Scene State Evolution**　arXiv 2026 · [arXiv:2610.04152](https://arxiv.org/abs/2610.04152) · [B站](https://www.bilibili.com/video/BV18Ep36uEYS)
  - 在共享的 4D 场景状态中显式演化物体轨迹，并将轨迹转为几何控制，以生成可控且保持场景一致性的未来视频。
- **ZYT-World: A Real-Time Controllable World Model for Closed-Loop Autonomous-Driving Simulation**　arXiv 2026 · [arXiv:2609.21712](https://arxiv.org/abs/2609.21712) · [B站](https://www.bilibili.com/video/BV14xhk65EUw)
  - 在真实生产相机接口下，同时实现可控、多视角一致、长时稳定和实时闭环生成。
- **TrAct: Bridging Robot Control and Visual Prediction with Visual Tracks**　arXiv 2026 · [arXiv:2608.24101](https://arxiv.org/abs/2608.24101) · [B站](https://www.bilibili.com/video/BV1D8hA6MEx8)
  - 用视觉轨迹作为共享接口，让世界模型预测候选动作的视觉后果，再由视觉语言评价器选择更可能完成任务的动作。
- **SolarWM: Open Data and Scalable Training for Long-Horizon Video World Models**　arXiv 2026 · [arXiv:2609.02886](https://arxiv.org/abs/2609.02886) · [B站](https://www.bilibili.com/video/BV1RVtv6tE45)
  - 用统一的数据契约、相机条件和三阶段训练，把异构视频生成器组织成可扩展的交互式世界模型家族。
- **GeoVerse: World-Consistent Novel View Synthesis in Geometric Latent Space**　arXiv 2026 · [arXiv:2609.35734](https://arxiv.org/abs/2609.35734) · [B站](https://www.bilibili.com/video/BV1ENp46PEmg)
  - 在 DA3 几何潜空间中注入 Wan2.2 VACE 外观特征，并用全局空间记忆约束多轮新视角生成。
- **Hydra-0: Action Flow for Generalist World Modeling and Control**　arXiv 2026 · [arXiv:2608.18077](https://arxiv.org/abs/2608.18077) · [B站](https://www.bilibili.com/video/BV1fT8S61Ess)
  - 用像素平面的 action flow 连接跨 embodiment 世界建模、策略评估与逆向机器人控制。
- **Dream4ACT: A Shared Visual Action Interface for Multi-Embodiment Video-Action Modeling**　arXiv 2026 · [arXiv:2609.40153](https://arxiv.org/abs/2609.40153) · [B站](https://www.bilibili.com/video/BV1TKpG6TEw8)
  - 用 URDF 渲染的固定多视图动作接口统一不同 embodiment，并通过无需训练的几何恢复得到关节动作。
- **Recursive Code World Models: Building Complex Worlds through Recursive Scene Programs**　arXiv 2026 · [arXiv:2609.11499](https://arxiv.org/abs/2609.11499) · [B站](https://www.bilibili.com/video/BV1XhY964EDe)
  - 让每个重要子世界都经历“建立整体—递归处理局部—回访整体”的完整视觉构造循环。
- **HelloWorld: Towards Practical Applications of Generative Driving World Models**　arXiv 2026 · [arXiv:2609.28931](https://arxiv.org/abs/2609.28931) · [B站](https://www.bilibili.com/video/BV1gshy6XENZ)
  - 将广泛视频先学习成 pose-conditioned causal prior，再逐级加入七视角、HD map、3D boxes、few-step inference 与条件 LiDAR。