# 访谈与对话

> 来源：B 站 **机器之心**（mid 73414544）
> 快照：**2026-10-11**，共 **13** 集。结构化数据：[items.json](items.json)

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

## 全部 13 集

| # | 讲者 | 单位/身份 | 题目 | 时长 | B站 |
|---:|---|---|---|---:|---|
| 1 | - | - | Llama 对决 GPT：AI 开源拐点已至？/ 智者访谈 | 46:54 | [看](https://www.bilibili.com/video/BV13142187hw) |
| 2 | - | - | DeepSeek你得这样用，成本低、稳定还安全 | 3:35 | [看](https://www.bilibili.com/video/BV1C3QGYyE9E) |
| 3 | - | - | 清华赵明国：智能人形机器人≠智能+人形 / 智者访谈 | 43:34 | [看](https://www.bilibili.com/video/BV1miDpY5E2p) |
| 4 | - | - | 小米语音科学家：语音识别已经卷完了，AI的机会这里 / 智者访谈 | 27:07 | [看](https://www.bilibili.com/video/BV1aGw8ePE4Q) |
| 5 | - | - | 解码生物语言，开启大模型时代药物研发新范式 / 智者访谈 | 30:49 | [看](https://www.bilibili.com/video/BV16DmPY3ESB) |
| 6 | - | - | 图森未来陈默：自动驾驶无以为继，急转驶入AIGC游戏，已拿下金庸群侠传、三体IP / 智者访谈 | 30:31 | [看](https://www.bilibili.com/video/BV1wHk1YyEgq) |
| 7 | - | - | 清华翟季冬：DeepSeek 百倍算力效能背后的系统革命 / 智者访谈 | 31:50 | [看](https://www.bilibili.com/video/BV19scFeSEeo) |
| 8 | - | - | 上海交大卢策吾：具身智能与他的首个刮胡子机器人 / 智者访谈 | 60:16 | [看](https://www.bilibili.com/video/BV1xz421h7N8) |
| 9 | - | - | 硅谷正在疯狂押注 Self-Improve Agent | 2:55 | [看](https://www.bilibili.com/video/BV1V7Gb6qEcn) |
| 10 | - | - | 上海交大张拳石：思维链只是表象，DeepSeek凭什么更强 / 智者访谈 | 62:51 | [看](https://www.bilibili.com/video/BV1HfRgY1E3p) |
| 11 | - | - | 北大王立威：理论视角看大模型，为什么AI既聪明又愚蠢 / 智者访谈 | 58:39 | [看](https://www.bilibili.com/video/BV1bcp7e1Ed2) |
| 12 | - | - | 蚂蚁集团韦韬：数据密态化是大模型产业未来之路丨智者访谈 | 48:39 | [看](https://www.bilibili.com/video/BV1mw4m1a7qk) |
| 13 | - | - | 腾讯混元大模型负责人王迪：揭秘万亿 MoE 系统工程之道｜智者访谈 | 58:32 | [看](https://www.bilibili.com/video/BV1QuWae8Eoj) |

## 逐条

- **Llama 对决 GPT：AI 开源拐点已至？| 智者访谈**
  - [B站](https://www.bilibili.com/video/BV13142187hw)
- **DeepSeek你得这样用，成本低、稳定还安全**
  - [B站](https://www.bilibili.com/video/BV1C3QGYyE9E)
- **清华赵明国：智能人形机器人≠智能+人形 | 智者访谈**
  - [B站](https://www.bilibili.com/video/BV1miDpY5E2p)
- **小米语音科学家：语音识别已经卷完了，AI的机会这里 | 智者访谈**
  - [B站](https://www.bilibili.com/video/BV1aGw8ePE4Q)
- **解码生物语言，开启大模型时代药物研发新范式 | 智者访谈**
  - [B站](https://www.bilibili.com/video/BV16DmPY3ESB)
- **图森未来陈默：自动驾驶无以为继，急转驶入AIGC游戏，已拿下金庸群侠传、三体IP | 智者访谈**
  - [B站](https://www.bilibili.com/video/BV1wHk1YyEgq)
- **清华翟季冬：DeepSeek 百倍算力效能背后的系统革命 | 智者访谈**
  - [B站](https://www.bilibili.com/video/BV19scFeSEeo)
- **上海交大卢策吾：具身智能与他的首个刮胡子机器人 | 智者访谈**
  - [B站](https://www.bilibili.com/video/BV1xz421h7N8)
- **硅谷正在疯狂押注 Self-Improve Agent**
  - [B站](https://www.bilibili.com/video/BV1V7Gb6qEcn)
- **上海交大张拳石：思维链只是表象，DeepSeek凭什么更强 | 智者访谈**
  - [B站](https://www.bilibili.com/video/BV1HfRgY1E3p)
- **北大王立威：理论视角看大模型，为什么AI既聪明又愚蠢 | 智者访谈**
  - [B站](https://www.bilibili.com/video/BV1bcp7e1Ed2)
- **蚂蚁集团韦韬：数据密态化是大模型产业未来之路丨智者访谈**
  - [B站](https://www.bilibili.com/video/BV1mw4m1a7qk)
- **腾讯混元大模型负责人王迪：揭秘万亿 MoE 系统工程之道｜智者访谈**
  - [B站](https://www.bilibili.com/video/BV1QuWae8Eoj)