# AI Product Interview Coach

> A practical Codex skill for rehearsing product-management interviews with structured, evidence-based feedback.

[English](#english) | [中文](#中文)

## 中文

`ai-product-interview-coach` 将 Codex 变成一位严格但有帮助的产品面试官。它会根据目标职位、公司与候选人经历，进行真实的逐题面试，持续追问，并用统一量表给出可执行的反馈。

### 能力

- 产品设计、产品策略、指标分析、执行协作与行为面试
- 根据岗位级别和公司情境动态调整题目难度
- 一次只问一个问题，像真实面试一样追问证据与取舍
- 用 STAR、结构化思考、用户价值、商业影响与沟通清晰度评分
- 生成复盘、薄弱项训练计划和下一轮练习题

### 安装

将本仓库克隆到项目目录，Skill 已位于 `.cursor/skills/ai-product-interview-coach/`：

```bash
git clone https://github.com/<your-github-username>/ai-product-interview-coach.git
```

也可以把该目录复制到任意项目的 `.cursor/skills/` 中。

### 使用教程

1. 在 Codex 聊天中引用 `$ai-product-interview-coach`。
2. 说明目标，例如：`我要准备字节跳动中级产品经理面试，做一轮 30 分钟的产品设计模拟。`
3. 可选地粘贴 JD、简历要点、目标公司或想加强的主题。
4. 每次只回答当前问题；Skill 会按面试节奏追问。
5. 说“结束面试”或完成约定轮数，即可获得评分和训练计划。

### 示例

```text
$ai-product-interview-coach
我有 4 年 B 端 SaaS 产品经验，准备 AI 产品经理面试。
请模拟 25 分钟：产品策略 + 指标分析，严格追问，不要在中途给提示。
```

更多题型和评分规则见 [参考指南](.cursor/skills/ai-product-interview-coach/reference.md)。

### 为什么这样设计

本项目吸收了优秀开源提示词仓库的几个有效模式：快速开始、清晰的触发场景、可复制示例与可检查的输出模板；同时结合了真实产品面试中常见的“澄清—拆解—取舍—验证”面试节奏。它不是题库堆砌，而是可反复运行的面试训练回路。

### 贡献

欢迎补充题目、行业场景和改进评分量表。提交前请确保新内容与现有结构一致，并避免编造候选人的经历或公司内部信息。详见 [贡献指南](CONTRIBUTING.md)。

## English

`ai-product-interview-coach` is a Codex skill that runs realistic product-management interview practice. It tailors questions to the role and company, follows up on evidence and trade-offs, and produces an actionable scorecard.

### Quick start

```text
$ai-product-interview-coach
I have four years of B2B SaaS PM experience and am preparing for an AI PM role.
Run a strict 25-minute mock interview on product strategy and metrics. Do not coach me during the interview.
```

See the [reference guide](.cursor/skills/ai-product-interview-coach/reference.md) for interview modes, prompts, and scoring.

## License

MIT. See [LICENSE](LICENSE).
