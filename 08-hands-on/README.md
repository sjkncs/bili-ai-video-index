# AIGC 上手实战

> 来源：B 站 **机器之心**（mid 73414544）
> 快照：**2026-10-11**，共 **18** 集。结构化数据：[items.json](items.json)

## 数据来源 · 计算方法 · 口径限制

**数据来源**：B 站 x/polymer/web-space/seasons_archives_list 取分集列表；逐条调 x/web-interface/view 取 **desc（简介）** 字段。

**计算方法**：机器之心的简介**没有统一格式**（不像论文解读那样有 【论文分享】 模板），所以：
- speaker / ffiliation **只从简介中的「嘉宾介绍」段落提取**，且仅当开头形如 姓名，单位… 或 姓名 单位… 时才采纳；
- 提取结果会做**有效性校验**（含「的/与/和」、以「教授/老师」结尾、含「嘉宾/主持」等一律判为不合格，整段退回到 ffiliation，speaker 留空）；
- **标题格式不参与拆解**——机器之心的标题风格混杂（机构+姓名：题目、题目 | 智者访谈、纯题目），按标题硬拆会产生错误数据，因此不做。

**口径限制**
- 本目录**不声称完整的讲者名单**：只有 104/188 条的简介含「嘉宾介绍」段落，其余保持为空。圆桌类条目的「嘉宾介绍」常含多人，本表只取段落原文，**未拆分到个人**。
- ull_title 对机器之心的条目**为空**（它不是论文解读，没有论文全名）。
- 只做目录索引，不含视频、字幕或讲义。

## 全部 18 集

| # | 讲者 | 单位/身份 | 题目 | 时长 | B站 |
|---:|---|---|---|---:|---|
| 1 | - | - | 【AIGC体验派】第6期：奇幻成像，高美感文生图背后的技术链路（下） | 15:16 | [看](https://www.bilibili.com/video/BV1c1421t7k8) |
| 2 | - | - | Stable Diffusion 应用场景入门：加速！电商美术设计 | 61:40 | [看](https://www.bilibili.com/video/BV1yy411z7vq) |
| 3 | 刘晨晨 | 火山引擎直播洞察产品负责人 | 【AIGC体验派】第4期：主打个性化体验，留住用户全靠AIGC？（上） | 12:09 | [看](https://www.bilibili.com/video/BV1DJ4m1T7dH) |
| 4 | - | - | 【AIGC体验派】第3期：体验增强，如何用AIGC提升营销互动率（上） | 20:03 | [看](https://www.bilibili.com/video/BV1Xm421G7eQ) |
| 5 | - | - | Stable Diffusion 在2D、3D、Video 中的应用 | 53:07 | [看](https://www.bilibili.com/video/BV1xS411N7F9) |
| 6 | 梁正 | 火山引擎销售助手产品负责人 | 【AIGC体验派】第4期：主打个性化体验，留住用户全靠AIGC？（下） | 25:07 | [看](https://www.bilibili.com/video/BV16S421R7GH) |
| 7 | - | - | 【AIGC体验派】第5期：创意为王安全为先，AIGC的双线作战（下） | 12:06 | [看](https://www.bilibili.com/video/BV1fJ4m1T7YX) |
| 8 | - | - | 【AIGC体验派】第3期：体验增强，如何用AIGC提升营销互动率（中） | 17:09 | [看](https://www.bilibili.com/video/BV1CT421k73y) |
| 9 | - | - | 文生图大模型评测：快手可图与SD3 | 71:16 | [看](https://www.bilibili.com/video/BV1dW421R7xB) |
| 10 | 吴佳硕 | 火山引擎智能创作云运营负责人  刘一鸣 NVIDIA 解决方案架构师 | 【AIGC体验派】第2期：极速面客如何用AIGC提升营销视频创作效率?（下） | 10:01 | [看](https://www.bilibili.com/video/BV1Wi421e7ox) |
| 11 | - | - | Stable Diffusion 3 究竟好不好？全面大测评 | 60:59 | [看](https://www.bilibili.com/video/BV1aS411A7Zk) |
| 12 | - | - | 【AIGC体验派】第6期：奇幻成像，高美感文生图背后的技术链路（上） | 13:14 | [看](https://www.bilibili.com/video/BV1zS411w7F7) |
| 13 | - | - | 【AIGC体验派】第5期：创意为王安全为先，AIGC的双线作战（上） | 17:07 | [看](https://www.bilibili.com/video/BV15S411w7Pe) |
| 14 | - | - | 【AIGC体验派】第3期：体验增强，如何用AIGC提升营销互动率（下） | 12:02 | [看](https://www.bilibili.com/video/BV1C1421b73m) |
| 15 | 吴佳硕 | 火山引擎智能创作云运营负责人  刘一鸣 NVIDIA 解决方案架构师 | 【AIGC体验派】第2期：极速面客如何用AIGC提升营销视频创作效率?（上） | 23:50 | [看](https://www.bilibili.com/video/BV1C4421S78W) |
| 16 | - | - | 非设计师玩转AI生图：用Stable Diffusion快速搞定工作 | 61:19 | [看](https://www.bilibili.com/video/BV12T421k7Pr) |
| 17 | 班丽婵 | CMO Club（首席营销官俱乐部）创始人&CEO，社群营销、B2B营销专家，前蓝色光标事业部总经理，曾担任《市场圈》、… | 【AIGC体验派】第一期：从有趣到有用，AIGC如何促进营销增长 | 25:54 | [看](https://www.bilibili.com/video/BV166421Z7rE) |
| 18 | - | - | Stable Diffusion 应用场景入门：从粘土人到动漫游戏世界 | 59:57 | [看](https://www.bilibili.com/video/BV1ym421V7kv) |

## 逐条

- **【AIGC体验派】第6期：奇幻成像，高美感文生图背后的技术链路（下）**
  - [B站](https://www.bilibili.com/video/BV1c1421t7k8)
- **Stable Diffusion 应用场景入门：加速！电商美术设计**
  - [B站](https://www.bilibili.com/video/BV1yy411z7vq)
- **【AIGC体验派】第4期：主打个性化体验，留住用户全靠AIGC？（上）**
  - 讲者 **刘晨晨** · 火山引擎直播洞察产品负责人 · [B站](https://www.bilibili.com/video/BV1DJ4m1T7dH)
  - 嘉宾介绍：刘晨晨 火山引擎直播洞察产品负责人
- **【AIGC体验派】第3期：体验增强，如何用AIGC提升营销互动率（上）**
  - [B站](https://www.bilibili.com/video/BV1Xm421G7eQ)
- **Stable Diffusion 在2D、3D、Video 中的应用**
  - [B站](https://www.bilibili.com/video/BV1xS411N7F9)
- **【AIGC体验派】第4期：主打个性化体验，留住用户全靠AIGC？（下）**
  - 讲者 **梁正** · 火山引擎销售助手产品负责人 · [B站](https://www.bilibili.com/video/BV16S421R7GH)
  - 嘉宾介绍：梁正 火山引擎销售助手产品负责人
- **【AIGC体验派】第5期：创意为王安全为先，AIGC的双线作战（下）**
  - [B站](https://www.bilibili.com/video/BV1fJ4m1T7YX)
- **【AIGC体验派】第3期：体验增强，如何用AIGC提升营销互动率（中）**
  - [B站](https://www.bilibili.com/video/BV1CT421k73y)
- **文生图大模型评测：快手可图与SD3**
  - [B站](https://www.bilibili.com/video/BV1dW421R7xB)
- **【AIGC体验派】第2期：极速面客如何用AIGC提升营销视频创作效率?（下）**
  - 讲者 **吴佳硕** · 火山引擎智能创作云运营负责人  刘一鸣 NVIDIA 解决方案架构师 · [B站](https://www.bilibili.com/video/BV1Wi421e7ox)
  - 嘉宾介绍：吴佳硕 火山引擎智能创作云运营负责人  刘一鸣 NVIDIA 解决方案架构师
- **Stable Diffusion 3 究竟好不好？全面大测评**
  - [B站](https://www.bilibili.com/video/BV1aS411A7Zk)
- **【AIGC体验派】第6期：奇幻成像，高美感文生图背后的技术链路（上）**
  - [B站](https://www.bilibili.com/video/BV1zS411w7F7)
- **【AIGC体验派】第5期：创意为王安全为先，AIGC的双线作战（上）**
  - [B站](https://www.bilibili.com/video/BV15S411w7Pe)
- **【AIGC体验派】第3期：体验增强，如何用AIGC提升营销互动率（下）**
  - [B站](https://www.bilibili.com/video/BV1C1421b73m)
- **【AIGC体验派】第2期：极速面客如何用AIGC提升营销视频创作效率?（上）**
  - 讲者 **吴佳硕** · 火山引擎智能创作云运营负责人  刘一鸣 NVIDIA 解决方案架构师 · [B站](https://www.bilibili.com/video/BV1C4421S78W)
  - 嘉宾介绍：吴佳硕 火山引擎智能创作云运营负责人  刘一鸣 NVIDIA 解决方案架构师
- **非设计师玩转AI生图：用Stable Diffusion快速搞定工作**
  - [B站](https://www.bilibili.com/video/BV12T421k7Pr)
- **【AIGC体验派】第一期：从有趣到有用，AIGC如何促进营销增长**
  - 讲者 **班丽婵** · CMO Club（首席营销官俱乐部）创始人&CEO，社群营销、B2B营销专家，前蓝色光标事业部总经理，曾担任《市场圈》、《广告主》、《联想》杂志主编，就职于联想集团品牌推广部、中国企业联合会、中国数码集团。作为营销行业知名的影响力人物，在营销界拥有20年丰富经验。2016年，她率先创办中国首席营销官CMO Club平台，为上万家企业市场营销部专业赋能成长。同时，还兼任数十家知名企业营销的顾问，及海尔创客实验室创新创业导师。 骆怡航，火山引擎AI解决方案负责人，负责火山引擎AI应用产品规划、落地与商业合作，曾参与字节跳动AI中台的规划与建设。清华大学自动化系博士毕业，从事云计算及AI领域的技术研究与商业落地十余年，并任北京市AI创新应用先导区副理事长，长江商学院聘用AI课程讲师。 · [B站](https://www.bilibili.com/video/BV166421Z7rE)
  - 嘉宾介绍：班丽婵，CMO Club（首席营销官俱乐部）创始人&CEO，社群营销、B2B营销专家，前蓝色光标事业部总经理，曾担任《市场圈》、《广告主》、《联想》杂志主编，就职于联想集团品牌推广部、中国企业联合会、中国数码集团。作为营销行业知名的影响力人物，在营销界拥有20年丰富经验。2016年，她率先创办中国首席营销官CMO Club平台，为上万家企业市场营销部专业赋能成长。同时，还兼任数十家知名企业营销的顾问，及海尔创客实验室创新创业导师。 骆怡航，火山引擎AI解决方案负责人，负责火山引擎AI应用产品规划、落地与商业合作，曾参与字节跳动AI中台的规划与建设。清华大学自动化系博士毕业，从事云计算及AI领域的技术研究与商业落地十余年，并任北京市AI创新应用先导区副理事长，长江商学院聘用AI课程讲师。
- **Stable Diffusion 应用场景入门：从粘土人到动漫游戏世界**
  - [B站](https://www.bilibili.com/video/BV1ym421V7kv)