# 论坛与圆桌

> 来源：B 站 **机器之心**（mid 73414544）
> 快照：**2026-10-11**，共 **37** 集。结构化数据：[items.json](items.json)

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

## 全部 37 集

| # | 讲者 | 单位/身份 | 题目 | 时长 | B站 |
|---:|---|---|---|---:|---|
| 1 | - | 苏   洋，灵心巧手联合创始人兼首席 AI 架构师 | 通往灵巧手的灵巧泛化之路 | 21:07 | [看](https://www.bilibili.com/video/BV1RsWuz8Ero) |
| 2 | - | - | 筑基石 启未来: VLA 模型开源工具箱与评测方案 | 26:02 | [看](https://www.bilibili.com/video/BV1FzygBkEds) |
| 3 | - | - | 云帆 AI 青年之声：范式转变中的机遇和挑战 | 28:48 | [看](https://www.bilibili.com/video/BV1QM4y1j71o) |
| 4 | - | - | 真机实际场景数据推动的渐进式具身智能路径 | 16:53 | [看](https://www.bilibili.com/video/BV1FzygBkEtx) |
| 5 | - | - | 从海量人类视频训练灵巧手 VLA 大模型 | 24:45 | [看](https://www.bilibili.com/video/BV1FzygBkE9u) |
| 6 | - | - | 可信联邦学习与开源生态 | 16:07 | [看](https://www.bilibili.com/video/BV1nz4y1J7J7) |
| 7 | 孙富春 | 清华大学计算机科学与技术系教授、博士生导师，清华大学人工智能研究院智能机器人中心主任 | 具身智能训练场与产业落地 | 40:02 | [看](https://www.bilibili.com/video/BV176piz3Eh3) |
| 8 | - | 秦 成：西门子Xcelerator 中国区总经理（兼主持人） 胡德波：开普勒人形机器人 CEO 孙兆治：Robopoet… | 我们的下一个“超级助手”：需求、场景与落地 | 45:24 | [看](https://www.bilibili.com/video/BV1tHWgzHEM3) |
| 9 | - | - | 大模型时代的 AI 原生研发模式 | 25:39 | [看](https://www.bilibili.com/video/BV1cM4y177y7) |
| 10 | 王广润 | 拓元智慧首席科学家、中山大学计算机学院副教授、博士生导师 | 拓元智慧王广润 / 基于新型大物理模型的具身智能 | 24:25 | [看](https://www.bilibili.com/video/BV1hNTvzHEZ2) |
| 11 | - | - | 圆桌对话：具身智能与 AI 终端创新未来图景 | 56:13 | [看](https://www.bilibili.com/video/BV1VRygBaEa3) |
| 12 | - | - | 大语言模型的原理、实现及应用 | 26:40 | [看](https://www.bilibili.com/video/BV1Cg4y1w7g1) |
| 13 | - | - | AI对齐失败数据库中文社区站点发布 | 7:49 | [看](https://www.bilibili.com/video/BV1aP411k7cC) |
| 14 | 赵哲伦 | 维他动力联合创始人 | 维他动力赵哲伦 / 智能机器人的十字路口 | 22:07 | [看](https://www.bilibili.com/video/BV1efTezxEW1) |
| 15 | - | - | 主持人开场 | 3:27 | [看](https://www.bilibili.com/video/BV15T411n7Qp) |
| 16 | 张直政 | 银河通用机器人联合创始人、大模型负责人 | 仿真合成数据驱动具身大模型实现产业智能化 | 20:51 | [看](https://www.bilibili.com/video/BV1tWWGzZEqV) |
| 17 | 赵明国 | 清华大学自动化系研究员 | 清华赵明国 / 基于脉冲神经网络的机械人类脑仿生控制 | 34:38 | [看](https://www.bilibili.com/video/BV125TvzLEk3) |
| 18 | - | - | 多模态通用生成模型的基本框架与最新进展 | 18:25 | [看](https://www.bilibili.com/video/BV1Z94y1q7Dr) |
| 19 | - | - | Challenges and Opportunities of Productionizing LLM to large scale applications | 13:41 | [看](https://www.bilibili.com/video/BV1Vk4y1N7WG) |
| 20 | - | - | 世界模型，开启物理世界通用智能新时代 | 23:46 | [看](https://www.bilibili.com/video/BV1piygByEKS) |
| 21 | - | - | 自然语言交互：大语言模型带来的交互方式变革 | 28:12 | [看](https://www.bilibili.com/video/BV19M4y1x7ng) |
| 22 | 位德浩 | 深圳星际光年科技有限公司 CEO | 星际光年位德浩 / 具身智能机器人设计革命：“乐高”式搭建灵巧手 | 11:29 | [看](https://www.bilibili.com/video/BV1rCTeziEEi) |
| 23 | - | - | 企业级生成式AI应用落地的一些思考 | 23:59 | [看](https://www.bilibili.com/video/BV1eV411N7pN) |
| 24 | - | 江 磊，国地共建人形机器人创新中心首席科学家 | 构建跨场景高效的“仿真-现实”数据飞轮 | 21:50 | [看](https://www.bilibili.com/video/BV1UBWuzDEUg) |
| 25 | 赵天成 | 联汇科技 CEO 兼首席科学家 | 联汇科技赵天成 / 视觉大模型 VLM 在具身智能中的应用 | 27:22 | [看](https://www.bilibili.com/video/BV1zSTezaEGz) |
| 26 | - | - | ROBO GALAXY：大模型时代的智能驾驶生产力工厂 | 18:49 | [看](https://www.bilibili.com/video/BV1zX4y1e7wa) |
| 27 | - | - | Colossal-AI：AI 大模型的挑战与系统优化 | 23:49 | [看](https://www.bilibili.com/video/BV1zX4y1e76e) |
| 28 | - | 主持人：闻菲 机器之心副主编 研讨嘉宾： 陈立梁：智元机器人具身算法专家 | 圆桌对话 / 具身智能的破晓：从前沿探索到产业落地与未来展望 | 48:22 | [看](https://www.bilibili.com/video/BV1oGTezoEva) |
| 29 | - | - | 生成式人工智能：从单模态迈向多模态 | 24:33 | [看](https://www.bilibili.com/video/BV15x4y1o7BB) |
| 30 | 金国强 | NVIDIA 资深解决方案架构师 | NVIDIA Physical AI 平台加速具身智能研发与落地 | 37:21 | [看](https://www.bilibili.com/video/BV1nqWgz3EP4) |
| 31 | - | - | 圆桌讨论与现场QA | 36:46 | [看](https://www.bilibili.com/video/BV1VX4y1m7DX) |
| 32 | - | - | 通往通用泛化的两条路（The Two Roads to Generalization） | 37:17 | [看](https://www.bilibili.com/video/BV1a3pizcExG) |
| 33 | - | - | 讯飞星火认知大模型的技术进展及应用创新 | 26:30 | [看](https://www.bilibili.com/video/BV1714y197A9) |
| 34 | 张伟男 | 哈尔滨工业大学计算机学院教授、博士生导师 哈尔滨工业大学计算学部主任助理，黑龙江省中文信息处理重点实验室副主任，国家重点… | 大模型时代自然语言处理中的可解释性问题 | 36:14 | [看](https://www.bilibili.com/video/BV1Po4y187Kp) |
| 35 | 许华哲 | 星海图首席科学家；清华大学交叉信息研究院助理教授，博导，清华大学具身智能实验室负责人 | 开启具身智能的下一站 | 16:15 | [看](https://www.bilibili.com/video/BV1ZrWgzBEie) |
| 36 | 张奇 | 复旦大学计算机科学技术学院教授、博士生导师 2009 年于复旦大学获得理学博士学位。研究领域为自然语言处理与信息检索。至… | GPT系列发展与鲁棒性研究 | 27:50 | [看](https://www.bilibili.com/video/BV1qh4y1p72o) |
| 37 | 李磊 | 加州大学圣巴巴拉分校助理教授 研究方向为机器学习、自然语言处理、数据挖掘。本科毕业于上海交通大学计算机系 ACM 班，博… | Trust worthy Pre-trained Language Models | 28:21 | [看](https://www.bilibili.com/video/BV1mL411Y7Gi) |

## 逐条

- **通往灵巧手的灵巧泛化之路**
  - 苏   洋，灵心巧手联合创始人兼首席 AI 架构师 · [B站](https://www.bilibili.com/video/BV1RsWuz8Ero)
  - 嘉宾介绍：苏   洋，灵心巧手联合创始人兼首席 AI 架构师
- **筑基石 启未来: VLA 模型开源工具箱与评测方案**
  - [B站](https://www.bilibili.com/video/BV1FzygBkEds)
- **云帆 AI 青年之声：范式转变中的机遇和挑战**
  - [B站](https://www.bilibili.com/video/BV1QM4y1j71o)
- **真机实际场景数据推动的渐进式具身智能路径**
  - [B站](https://www.bilibili.com/video/BV1FzygBkEtx)
- **从海量人类视频训练灵巧手 VLA 大模型**
  - [B站](https://www.bilibili.com/video/BV1FzygBkE9u)
- **可信联邦学习与开源生态**
  - [B站](https://www.bilibili.com/video/BV1nz4y1J7J7)
- **具身智能训练场与产业落地**
  - 讲者 **孙富春** · 清华大学计算机科学与技术系教授、博士生导师，清华大学人工智能研究院智能机器人中心主任 · [B站](https://www.bilibili.com/video/BV176piz3Eh3)
  - 嘉宾介绍：孙富春，清华大学计算机科学与技术系教授、博士生导师，清华大学人工智能研究院智能机器人中心主任
- **我们的下一个“超级助手”：需求、场景与落地**
  - 秦 成：西门子Xcelerator 中国区总经理（兼主持人） 胡德波：开普勒人形机器人 CEO 孙兆治：Robopoet 珞博智能创始人、首席执行官 · [B站](https://www.bilibili.com/video/BV1tHWgzHEM3)
  - 嘉宾介绍：秦 成：西门子Xcelerator 中国区总经理（兼主持人） 胡德波：开普勒人形机器人 CEO 孙兆治：Robopoet 珞博智能创始人、首席执行官
- **大模型时代的 AI 原生研发模式**
  - [B站](https://www.bilibili.com/video/BV1cM4y177y7)
- **拓元智慧王广润 | 基于新型大物理模型的具身智能**
  - 讲者 **王广润** · 拓元智慧首席科学家、中山大学计算机学院副教授、博士生导师 · [B站](https://www.bilibili.com/video/BV1hNTvzHEZ2)
  - 嘉宾介绍：王广润，拓元智慧首席科学家、中山大学计算机学院副教授、博士生导师
- **圆桌对话：具身智能与 AI 终端创新未来图景**
  - [B站](https://www.bilibili.com/video/BV1VRygBaEa3)
- **大语言模型的原理、实现及应用**
  - [B站](https://www.bilibili.com/video/BV1Cg4y1w7g1)
- **AI对齐失败数据库中文社区站点发布**
  - [B站](https://www.bilibili.com/video/BV1aP411k7cC)
- **维他动力赵哲伦 | 智能机器人的十字路口**
  - 讲者 **赵哲伦** · 维他动力联合创始人 · [B站](https://www.bilibili.com/video/BV1efTezxEW1)
  - 嘉宾介绍：赵哲伦，维他动力联合创始人
- **主持人开场**
  - [B站](https://www.bilibili.com/video/BV15T411n7Qp)
- **仿真合成数据驱动具身大模型实现产业智能化**
  - 讲者 **张直政** · 银河通用机器人联合创始人、大模型负责人 · [B站](https://www.bilibili.com/video/BV1tWWGzZEqV)
  - 嘉宾介绍：张直政，银河通用机器人联合创始人、大模型负责人
- **清华赵明国 | 基于脉冲神经网络的机械人类脑仿生控制**
  - 讲者 **赵明国** · 清华大学自动化系研究员 · [B站](https://www.bilibili.com/video/BV125TvzLEk3)
  - 嘉宾介绍：赵明国，清华大学自动化系研究员
- **多模态通用生成模型的基本框架与最新进展**
  - [B站](https://www.bilibili.com/video/BV1Z94y1q7Dr)
- **Challenges and Opportunities of Productionizing LLM to large scale applications**
  - [B站](https://www.bilibili.com/video/BV1Vk4y1N7WG)
- **世界模型，开启物理世界通用智能新时代**
  - [B站](https://www.bilibili.com/video/BV1piygByEKS)
- **自然语言交互：大语言模型带来的交互方式变革**
  - [B站](https://www.bilibili.com/video/BV19M4y1x7ng)
- **星际光年位德浩 | 具身智能机器人设计革命：“乐高”式搭建灵巧手**
  - 讲者 **位德浩** · 深圳星际光年科技有限公司 CEO · [B站](https://www.bilibili.com/video/BV1rCTeziEEi)
  - 嘉宾介绍：位德浩,深圳星际光年科技有限公司 CEO
- **企业级生成式AI应用落地的一些思考**
  - [B站](https://www.bilibili.com/video/BV1eV411N7pN)
- **构建跨场景高效的“仿真-现实”数据飞轮**
  - 江 磊，国地共建人形机器人创新中心首席科学家 · [B站](https://www.bilibili.com/video/BV1UBWuzDEUg)
  - 嘉宾介绍：江 磊，国地共建人形机器人创新中心首席科学家
- **联汇科技赵天成 | 视觉大模型 VLM 在具身智能中的应用**
  - 讲者 **赵天成** · 联汇科技 CEO 兼首席科学家 · [B站](https://www.bilibili.com/video/BV1zSTezaEGz)
  - 嘉宾介绍：赵天成，联汇科技 CEO 兼首席科学家
- **ROBO GALAXY：大模型时代的智能驾驶生产力工厂**
  - [B站](https://www.bilibili.com/video/BV1zX4y1e7wa)
- **Colossal-AI：AI 大模型的挑战与系统优化**
  - [B站](https://www.bilibili.com/video/BV1zX4y1e76e)
- **圆桌对话 | 具身智能的破晓：从前沿探索到产业落地与未来展望**
  - 主持人：闻菲 机器之心副主编 研讨嘉宾： 陈立梁：智元机器人具身算法专家 · [B站](https://www.bilibili.com/video/BV1oGTezoEva)
  - 嘉宾介绍：主持人：闻菲 机器之心副主编 研讨嘉宾： 陈立梁：智元机器人具身算法专家
- **生成式人工智能：从单模态迈向多模态**
  - [B站](https://www.bilibili.com/video/BV15x4y1o7BB)
- **NVIDIA Physical AI 平台加速具身智能研发与落地**
  - 讲者 **金国强** · NVIDIA 资深解决方案架构师 · [B站](https://www.bilibili.com/video/BV1nqWgz3EP4)
  - 嘉宾介绍：金国强， NVIDIA 资深解决方案架构师
- **圆桌讨论与现场QA**
  - [B站](https://www.bilibili.com/video/BV1VX4y1m7DX)
- **通往通用泛化的两条路（The Two Roads to Generalization）**
  - [B站](https://www.bilibili.com/video/BV1a3pizcExG)
- **讯飞星火认知大模型的技术进展及应用创新**
  - [B站](https://www.bilibili.com/video/BV1714y197A9)
- **大模型时代自然语言处理中的可解释性问题**
  - 讲者 **张伟男** · 哈尔滨工业大学计算机学院教授、博士生导师 哈尔滨工业大学计算学部主任助理，黑龙江省中文信息处理重点实验室副主任，国家重点研发计划项目负责人。研究兴趣包括自然语言处理及人机对话。在 ACL、SIGIR、AAAI、WWW、IJCAI、IEEE TKDE、ACM TOIS 等 CCF A 类国际会议及国际顶级期刊发表论文多篇，多次担任 ACL、EMNLP 领域主席。目前为中国中文信息学会青年工作委员会副主任，中国计算机学会（CCF）术语审定工作委员会执委、CCF 哈尔滨分部秘书长，中国人工智能学会教育工作委员会副秘书长，北京智源青源会会员。曾获黑龙江省科技进步一等奖、吴文俊人工智能科技进步二等奖及黑龙江省青年科技奖等。 · [B站](https://www.bilibili.com/video/BV1Po4y187Kp)
  - 嘉宾介绍：张伟男 哈尔滨工业大学计算机学院教授、博士生导师 哈尔滨工业大学计算学部主任助理，黑龙江省中文信息处理重点实验室副主任，国家重点研发计划项目负责人。研究兴趣包括自然语言处理及人机对话。在 ACL、SIGIR、AAAI、WWW、IJCAI、IEEE TKDE、ACM TOIS 等 CCF A 类国际会议及国际顶级期刊发表论文多篇，多次担任 ACL、EMNLP 领域主席。目前为中国中文信息学会青年工作委员会副主任，中国计算机学会（CCF）术语审定工作委员会执委、CCF 哈尔滨分部秘书长，中国人工智能学会教育工作委员会副秘书长，北京智源青源会会员。曾获黑龙江省科技进步一等奖、吴文俊人工智能科技进步二等奖及黑龙江省青年科技奖等。
- **开启具身智能的下一站**
  - 讲者 **许华哲** · 星海图首席科学家；清华大学交叉信息研究院助理教授，博导，清华大学具身智能实验室负责人 · [B站](https://www.bilibili.com/video/BV1ZrWgzBEie)
  - 嘉宾介绍：许华哲，星海图首席科学家；清华大学交叉信息研究院助理教授，博导，清华大学具身智能实验室负责人
- **GPT系列发展与鲁棒性研究**
  - 讲者 **张奇** · 复旦大学计算机科学技术学院教授、博士生导师 2009 年于复旦大学获得理学博士学位。研究领域为自然语言处理与信息检索。至今在 ACM/IEEE Transactions、IJCAI、AAAI、SIGIR、ACL、EMNLP 等自然语言处理和信息检索领域著名学术期刊和会议上发表论文 80 余篇。其中曾获 WSDM 2014 最佳论文推荐奖，COLING 2018 领域主席推荐奖（Area Chair Favorites）。承担 10 余项国家自然科学基金、国家 863 计划、国家科技支撑计划和国际合作项目。担任中国中文信息学会信息检索委员会常务委员、社会媒体处理专委会常务委员、青年工作委员会执行委员、计算语言学专委委员、语言与知识计算专委会委员、中国人工智能学会青年工作委员会常务委员、WSDM 2015 Local Chair、2019 年全国信息检索大会程序委员会联合主席。长期担任包括 ACL、EMNLP、SIGIR、IJCAI、AAAI、TKDE 等自然语言处理和人工智能领域重要国际刊物和会议的领域主席、程序委员会高级委员、程序委员会委员、审稿人等。2012 年获得上海市科技进步二等奖以及教育部科技进步二等奖、2015 年获得 ACM 上海新星提名奖、2016 年获得了钱伟长中文信息处理科学技术奖——汉王青年创新奖、2016 年获得 IBM Global Faculty Award 奖。 · [B站](https://www.bilibili.com/video/BV1qh4y1p72o)
  - 嘉宾介绍：张奇 复旦大学计算机科学技术学院教授、博士生导师 2009 年于复旦大学获得理学博士学位。研究领域为自然语言处理与信息检索。至今在 ACM/IEEE Transactions、IJCAI、AAAI、SIGIR、ACL、EMNLP 等自然语言处理和信息检索领域著名学术期刊和会议上发表论文 80 余篇。其中曾获 WSDM 2014 最佳论文推荐奖，COLING 2018 领域主席推荐奖（Area Chair Favorites）。承担 10 余项国家自然科学基金、国家 863 计划、国家科技支撑计划和国际合作项目。担任中国中文信息学会信息检索委员会常务委员、社会媒体处理专委会常务委员、青年工作委员会执行委员、计算语言学专委委员、语言与知识计算专委会委员、中国人工智能学会青年工作委员会常务委员、WSDM 2015 Local Chair、2019 年全国信息检索大会程序委员会联合主席。长期担任包括 ACL、EMNLP、SIGIR、IJCAI、AAAI、TKDE 等自然语言处理和人工智能领域重要国际刊物和会议的领域主席、程序委员会高级委员、程序委员会委员、审稿人等。2012 年获得上海市科技进步二等奖以及教育部科技进步二等奖、2015 年获得 ACM 上海新星提名奖、2016 年获得了钱伟长中文信息处理科学技术奖——汉王青年创新奖、2016 年获得 IBM Global Faculty Award 奖。
- **Trust worthy Pre-trained Language Models**
  - 讲者 **李磊** · 加州大学圣巴巴拉分校助理教授 研究方向为机器学习、自然语言处理、数据挖掘。本科毕业于上海交通大学计算机系 ACM 班，博士毕业于卡耐基梅隆大学计算机系。曾先后任加州大学伯克利分校博士后研究员、百度美国深度学习实验室少帅科学家、字节跳动人工智能实验室创始总监。曾获CCF 青竹奖、ACL 最佳论文奖、吴文俊人工智能二等奖，ACM SIGKDD 最佳博士论文Runner-up 奖。 · [B站](https://www.bilibili.com/video/BV1mL411Y7Gi)
  - 嘉宾介绍：李磊 加州大学圣巴巴拉分校助理教授 研究方向为机器学习、自然语言处理、数据挖掘。本科毕业于上海交通大学计算机系 ACM 班，博士毕业于卡耐基梅隆大学计算机系。曾先后任加州大学伯克利分校博士后研究员、百度美国深度学习实验室少帅科学家、字节跳动人工智能实验室创始总监。曾获CCF 青竹奖、ACL 最佳论文奖、吴文俊人工智能二等奖，ACM SIGKDD 最佳博士论文Runner-up 奖。