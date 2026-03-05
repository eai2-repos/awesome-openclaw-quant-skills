# Awesome OpenClaw Quant Skills

> 说明：你给的 8 个名称在官方源里未检索到精确同名。下面改为“**同类高星资源 + 可替代技能归类**”。

## A. 高星同类资源（网上可见）

> 这些是“技能集合仓库”（不是单个 skill），适合当发现入口。

| Repo | Stars（检索时） | 链接 | 说明 |
|---|---:|---|---|
| VoltAgent/awesome-openclaw-skills | 28k+ | https://github.com/VoltAgent/awesome-openclaw-skills | 最大的 OpenClaw skills 聚合清单（按分类整理）。 |
| clawdbot-ai/awesome-openclaw-skills-zh | 2k+ | https://github.com/clawdbot-ai/awesome-openclaw-skills-zh | 中文向技能聚合与分类。 |
| sundial-org/awesome-openclaw-skills | 300+ | https://github.com/sundial-org/awesome-openclaw-skills | 精选型 awesome 列表。 |

---

## B. 你的 8 个能力位 → 同类技能归类（可替代）

> 来源优先选 OpenClaw 官方 skills 仓库路径（`github.com/openclaw/skills/tree/main/...`）。

### 1) 行情/账户数据（对应 `market-data-fetch`）
- `plaid`：https://github.com/openclaw/skills/tree/main/skills/jverdi/plaid/SKILL.md  
  （金融账户/交易数据接口能力）
- `sharesight-skill`：https://github.com/openclaw/skills/tree/main/skills/lextoumbourou/sharesight-skill/SKILL.md  
  （组合持仓/投资跟踪）

### 2) 基本面/财务结构化（对应 `fundamentals-parser`）
- `sharesight-skill`（可用于投资组合财务视角）  
- `expense-tracker-pro`：https://github.com/openclaw/skills/tree/main/skills/jhillin8/expense-tracker-pro/SKILL.md  
  （财务数据结构化记录与统计）

### 3) 舆情/信号输入（对应 `news-sentiment-scan`）
- 可从高星 awesome 列表里的 Search/Research 分类筛选（入口）：  
  https://github.com/VoltAgent/awesome-openclaw-skills

### 4) 因子评分 / 事件冲击（对应 `factor-score-engine` / `event-impact-analyzer`）
- 当前更建议走“组合式实现”：行情数据 skill + 研究/分析类 skill + 自定义评分逻辑（本 repo 可继续补模板）。

### 5) 风控护栏（对应 `risk-guardrail`）
- `tax-professional`：https://github.com/openclaw/skills/tree/main/skills/scottfo/tax-professional/SKILL.md  
  （偏合规/税务约束，非交易风控）
- `api-credentials-hygiene`：https://github.com/openclaw/skills/tree/main/skills/kowl64/api-credentials-hygiene/SKILL.md  
  （偏安全护栏）

### 6) 组合建议（对应 `portfolio-suggestion`）
- `sharesight-skill`（投资组合管理与观察）

### 7) 报告生成（对应 `report-generator`）
- 可在 awesome 列表中优先查 `PDF & Documents` / `Data & Analytics` 分类：  
  https://github.com/VoltAgent/awesome-openclaw-skills

---

## C. 官方基准入口（用于后续继续扩展）

- OpenClaw Skills 规范：https://docs.openclaw.ai/tools/skills
- ClawHub 说明：https://docs.openclaw.ai/tools/clawhub
- 官方 skills 根目录：https://github.com/openclaw/openclaw/tree/main/skills

---

## D. 下一步建议（我可以继续代做）

如果你同意，我下一步直接给这个 repo 补一份：
1. `skills-map.md`：把“8 能力位”各补 5~10 个候选 skill（含链接、适用场景、替代关系）  
2. `quant-workflow-template.md`：给出可直接复制的量化工作流模板（数据→信号→评分→风控→报告）

## Disclaimer

For research/education only. Not investment advice.
