<div align="center">

# awesome-jev-cn

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Updated](https://img.shields.io/badge/Updated-2026--09--21-38bdf8)]()
[![Lang](https://img.shields.io/badge/Lang-中文为主-ef4444)]()

**Jev 中文精选：TypeSafe AI「System One」决策模型一周实况，中文视角重整**

A curated list of Jev in Chinese — tutorials, KOL threads, Xiaohongshu, Bilibili, first tests.

*小红书 · B站 · X中文KOL · 上手教程 · 实测 · 争议*

灵感与英文骨架来源：[Promethe-us/awesome-jev](https://github.com/Promethe-us/awesome-jev)（MIT），本仓库为中文增强独立整理。

</div>

> ⚠️ **免责声明**：本仓库为社区整理，与 TypeSafe AI 官方无关。快照截至 **2026-09-21**（Jev 发布约 6 天，一切变化极快，以[官方博客](https://typesafe.ai/blog/introducing-system-one-models-and-jev)与[文档](https://docs.typesafe.ai)为准）。
> 💣 **防骗**：官方**没有**发行任何代币，任何 “$JEV / Jev币” 均与官方无关。

---

## 📑 目录

- [30秒了解 Jev](#-30秒了解-jev)
- [中文必看 Top 5](#-中文必看-top-5)
- [小红书精选](#-小红书精选)
- [B站 / 视频](#-b站--视频)
- [上手教程](#-上手教程)
- [GitHub 生态中文点评](#-github-生态中文点评)
- [论文与生态研究](#-论文与生态研究)
- [争议与冷思考](#-争议与冷思考)
- [FAQ](#-faq)
- [贡献](#-贡献)

---

## 🔥 30秒了解 Jev

> 一句话：Jev 是 TypeSafe AI 发布的 **“System One 模型”** —— 不聊天、不写代码、不生成文本。只做一件事：**吃结构化状态，吐带概率的类型化决策**（Choice / Score / Noul），给程序直接调用。

- 🏢 公司：TypeSafe AI，旧金山，stealth 2 年，2026-09-15 出关
- 👤 创始人：Diogo Almeida（前 OpenAI，ChatGPT / RLHF 共同创造者之一）
- 💰 融资：4000 万美元种子轮，DCVC 领投，估值约 2 亿美元
- ⚡ 官方数字：快 193.6×、便宜 444.6×（对比 GPT-6 Astra / Fable 5.1 均值），延迟 70ms–500ms
- 💸 定价：输入 $0.042 / 百万 tokens，输出免费
- 🚫 不能做：不生成自由文本、不读图、不会聊天
- 🌊 热度（2026-09-20快照）：官宣推文 7.3万赞、HN 1920分/504评论、GitHub 本周新建 jev 相关仓库 3200+

官方入口：[博客](https://typesafe.ai/blog/introducing-system-one-models-and-jev) · [文档](https://docs.typesafe.ai) · [Playground](https://console.typesafe.ai/playground) · [Discord](https://discord.gg/typesafe)

---

## 🇨🇳 中文必看 Top 5

按中文圈实际传播排序，链接均验证可访问：

| 日期 | 作者 | 内容一句话 | 热度 | 链接 |
|---|---|---|---|---|
| 09-18 | **森叔 @harrisonitsme** | 最火中文上手：waitlist 当天过 + `npx skills add` + 建 Key + 让 Codex 用 skill | 2522赞 | [原文](https://x.com/harrisonitsme/status/2100799749192569167) |
| 09-19 | **黄小木 @ai_xiaomu** | 长文《Jev 从0到1小白教程》，定调客服/审核/招聘 Agent 重构 | 848赞 | [原文](https://x.com/ai_xiaomu/status/2101135680168771979) |
| 09-17 | **SuSu_酥酥 @NFT_Chen** | 解读“一小时复刻特斯拉FSD”，把门槛砸穿 | 348赞 | [原文](https://x.com/nft_chen/status/2100466502545862725) |
| 09-19 | **SuSu_酥酥 @NFT_Chen** | 500条电商工单实测：Jev 83秒/$0.01 清完 vs DeepSeek V4.1 Flash 只做完173条/$0.06 | 164赞 | [原文](https://x.com/nft_chen/status/2101253568774697099) |
| 09-20 | **AI Will @FinanceYF5** | 50开地铁跑酷不到1美分；40秒拆724条广告仅$0.09 | 29/41赞 | [跑酷](https://x.com/financeyf5/status/2101502474691698971) · [广告](https://x.com/financeyf5/status/2101585391140905034) |

英文源头必看 2 条（方便对照）：
- Diogo Almeida 官宣 73115赞：[原文](https://x.com/CompleteSkeptic/status/2099925682726002904)
- jpschroeder 一小时复刻 FSD 4734赞：[原文](https://x.com/jpschroeder/status/2100347770867458384)

---

## 📕 小红书精选

> 小红书屏蔽搜索引擎，只能站内看。本区为本仓库重点，欢迎 PR 补充。

| 日期 | 作者 | 内容 | 链接 |
|---|---|---|---|
| 09-20 | @DeepSleep | 《GPT6太慢？试试Jev》图文：整理 awesome-jev，官方资源+社区实测+中文教程+争议，求 Star/PR，18赞/17收藏 | [笔记](https://www.xiaohongshu.com/explore/6aafe241000000001103375f?xsec_token=ABBYuHgvK74N6nwyt2XSUtiXIRfSD7DdEkRk9hEf7bpsE=&xsec_source=pc_feed) |
| 09-20 | @北京月薪5k | 《成了，用 cua 和 jev 实现电脑控制》视频：CUA+Jev 驱动电脑操作，比 codex computer use 便宜 | [笔记](https://www.xiaohongshu.com/explore/6aaf844a000000001103379c) |
| — | 待补充 | 站内搜「jev」「jev 模型」第一页教程类优先收录 | [站内搜索](https://www.xiaohongshu.com/search_result?keyword=jev) |

收录格式：日期 + 作者 + 一句话 + 赞藏数 + 链接，视频注明 🎬，图文注明 🖼️。

---

## 🎬 B站 / 视频

| 日期 | 标题方向 | 入口 |
|---|---|---|
| 09-19 | 《TypeSafe 发布 Jev：为何比 LLMs 快200倍》《Jev + Browser Use：最快的 AI 智能体》等测评合集 | [B站搜 Jev 模型](https://search.bilibili.com/all?keyword=Jev%20%E6%A8%A1%E5%9E%8B) |

> TODO：把具体 UP 主、播放量、试看结论补上，这是中文版拉开差距的关键。

---

## 🛠️ 上手教程

中文小白路径（综合森叔 + 黄小木 + 官方文档）：

1. 官网 [typesafe.ai](https://typesafe.ai) 申请 waitlist（反馈基本当天过）
2. [console.typesafe.ai/keys](https://console.typesafe.ai/keys) 建 API Key
3. 给 Agent 装技能：`npx skills add typesafe-ai/skills --skill typesafe-ai`
4. prompt 里说 `use the TypeSafe skill`，先跑 Choice / Score / Noul 三个原语
5. 先做分类/路由/审核类任务，别一上来做生成类

完整版见 [docs/INSTALLATION.md](docs/INSTALLATION.md)，项目雷达见 [docs/CATALOG.md](docs/CATALOG.md)。

最小 cURL（官方示例）：

```bash
curl -X POST https://api.typesafe.ai/v1/systemone \
  -H "Authorization: Bearer $TYPESAFE_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "state": "Hi, my Stripe integration keeps failing. Losing sales. ASAP!",
    "model": "jev-latest",
    "questions": {
      "department": { "type": "choice", "instructions": "Which team should handle this",
        "criteria": { "billing": "Payment issues", "technical": "Bugs", "sales": "Pricing" } },
      "is_urgent": { "type": "noul", "instructions": "Does this express urgency?" }
    }
  }'
```

---

## 💻 GitHub 生态中文点评

星数为 2026-09-20 快照，中文一句话点评为本仓库新增：

**官方必装**
- [typesafe-ai/skills](https://github.com/typesafe-ai/skills)（899★）：先装这个，其他都可以往后放
- [typesafe-ai/system-one-adapter-python](https://github.com/typesafe-ai/system-one-adapter-python)（184★）：没 Key 时用 LLM 模拟接口调通流程

**小白能跑的复刻**
- [jaredpalmer/kev](https://github.com/jaredpalmer/kev)（729★）：Qwen2.5-0.5B，MacBook 可训可跑
- [TianyuCodings/NanoJev](https://github.com/TianyuCodings/NanoJev)（1220★）：并行决策+端到端流水线，想看训练就看它
- [bespokelabsai/nimble](https://github.com/bespokelabsai/nimble)（809★）：开放配方，对比式数据策展值得学

**出圈应用**
- [browser-use/jev-ultrafast](https://github.com/browser-use/jev-ultrafast)（10422★）：Jev 驱动浏览器 Agent，动态动作空间
- [tamaratran/fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction)（4627★）：Claude Code 上下文压缩插件，开发者最该试
- [jarrodwatts/jev-trader](https://github.com/jarrodwatts/jev-trader)（1419★）：每区块一次交易决策，演示高速决策

更多见英文原版 + [docs/CATALOG.md](docs/CATALOG.md)。

---

## 📄 论文与生态研究

- [Jev in the Wild：Jev 应用生态的数据驱动综述与分析](https://arxiv.org/abs/2609.30216)（Ling 等，2026）：分析 2,170 个公开 GitHub Jev 项目，记录早期增长、应用领域及 Choice／Score／Noul 等决策用途的分布。

---

## ⚖️ 争议与冷思考

1. 先发权争议：Reddit/HN 有“我一年前就开源过同样架构”帖，Jev 无论文无法裁定
2. 基准自报：官方4工作流+自选基线，路由偏差存在
3. “永不幻觉”是定义级：schema 0%类型错 ≠ 答案对，选项>255 走两阶段会变慢
4. 定价可能补贴：“输出免费”官方自认可能是补贴
5. 无官方论文：一切数字出自博客文档，复刻能否复现400×便宜未知

---

## ❓ FAQ

**Jev 能写代码/聊天吗？** 不能，只返回 Choice/Score/Noul。

**和 LLM 是替代吗？** 互补：LLM 做 System 2 思考，Jev 做 System 1 高速执行。

**怎么申请？** 官网 waitlist → console 建 Key → 装 skill，详见 docs/INSTALLATION.md。

**开源吗？** 本体闭源，平替看 nimble / kev / NanoJev / jevlike。

**有币吗？** 没有，谨防 $JEV 仿冒。

---

## 🤝 贡献

欢迎 PR，尤其缺中文内容：

1. 与 Jev / System One 直接相关
2. 中文链接附日期+作者+一句话+赞藏数
3. 星数/热度注明快照日期
4. 小红书/B站/公众号优先收

---

## 📜 License

[MIT](LICENSE) © 2026 awesome-jev-cn contributors

<div align="center">

**“决策便宜400倍，智能总消耗会爆炸。杰文斯悖论，中文版同步追更。”**

⭐ 觉得有用点个 Star，中文实测持续更新！

</div>
