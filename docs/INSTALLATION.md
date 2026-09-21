# 上手指南（中文）

> 翻译整理自官方文档 + 森叔 / 黄小木中文教程，截至 2026-09-21。

## 1. 申请访问

1. 打开 https://typesafe.ai 申请 waitlist（社区反馈基本当天通过）
2. 登录 https://console.typesafe.ai/keys 创建 API Key
3. 先去 https://console.typesafe.ai/playground 免代码试一把，理解 Choice / Score / Noul

## 2. 安装 Agent Skill

```bash
npx skills add typesafe-ai/skills --skill typesafe-ai
```

然后在 Claude Code / Codex / Cursor 的 prompt 里写：

```
use the TypeSafe skill
```

## 3. 三个原语

- Choice：分类路由，如“这单给哪个团队？”返回选项+概率+confidence
- Score：打分，如“用户多沮丧？”返回等级+概率
- Noul：二值判断，如“是否紧急？”返回 yes 概率

## 4. 最小验证

```bash
export TYPESAFE_API_KEY=xxx
curl -X POST https://api.typesafe.ai/v1/systemone \
  -H "Authorization: Bearer $TYPESAFE_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "state": "用户：退款，快点！",
    "model": "jev-latest",
    "questions": {
      "is_urgent": { "type": "noul", "instructions": "是否紧急？" },
      "department": { "type": "choice", "instructions": "分给谁？",
        "criteria": { "billing": "账单", "technical": "技术", "sales": "销售" } }
    }
  }'
```

## 5. 中文建议起手任务

1. 客服工单分类（500条级别，先复现 SuSu 的对比）
2. 内容审核 / 越狱检测
3. 评论打分抽取
4. 别做：写代码、写文档、聊天、看图

## 6. 官方资源

- 博客：https://typesafe.ai/blog/introducing-system-one-models-and-jev
- 文档：https://docs.typesafe.ai（含 llms.txt）
- Evals：https://evals.typesafe.ai
- Python SDK：`pip install typesafe-sdk` → https://github.com/typesafe-ai/typesafe-sdk-python
