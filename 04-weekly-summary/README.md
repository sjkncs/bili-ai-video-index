# 每周论文总结

> 来源：B 站 UP 主 **HyperHorizon**（mid 11470647）合集「每周论文总结」
> 快照：**2026-10-11**，共 **1** 集。结构化数据：[items.json](items.json)

## 数据来源 · 计算方法 · 口径限制

**数据来源**：B 站 x/polymer/web-space/seasons_archives_list 取分集列表；逐条调 x/web-interface/view 取 **desc（简介）** 字段——论文完整标题、会议、arXiv 链接、中文摘要全部来自简介。

**计算方法**：简介格式为 【论文分享】<论文全名> (<会议或 arXiv 年份>) — <中文摘要>。会议取标题块末尾括号（**支持嵌套括号**，如 SE(3)、ACM Multimedia (MM '26) 2026）；arXiv 号从 rxiv.org/abs/... 提取，另从 doi.org/10.48550/arXiv.xxxx 回捞。

**口径限制**
- B 站**视频标题**有 80 字符上限，本表的 paper 列取自**简介**而非标题，因此是完整的；原始标题仍可在 [items.json](items.json) 的 vid_title 字段回溯。
- 简介未给出会议或 arXiv 号的条目**保持为空，不做推测**。
- 只索引元数据，不含视频、字幕或论文全文；顺序为投稿顺序，iews 仅为弱热度信号。

## 全部 1 集

| # | paper | venue | category | arXiv | length | B站 |
|---:|---|---|---|---|---:|---|
| 1 | 【本周论文总结】2026.08.24–08.30｜WAM·VLA·世界模型·3DGS | - | 每周论文总结 | - | 22:03 | [看](https://www.bilibili.com/video/BV1pXtp6VEai) |

## 逐条（含中文摘要）

- **【本周论文总结】2026.08.24–08.30｜WAM·VLA·世界模型·3DGS**　[B站](https://www.bilibili.com/video/BV1pXtp6VEai)