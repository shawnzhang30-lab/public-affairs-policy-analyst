# Public Affairs Policy Analyst

> **公共事务政策分析作品集｜Political Science PhD Candidate**  
> 将政治学中的制度分析、比较研究与议题研究能力，转化为企业可直接使用的政策判断、业务影响分析和公共沟通材料。

## About this portfolio

我是一名政治学博士生，主要研究比较政治与政治理论。这个项目面向内容平台公共事务岗位，重点展示我如何处理一项真实的政策或社会议题：

**识别政策变化 → 判断制度与执行机制 → 分析业务影响 → 梳理利益相关方 → 评估议题走向 → 形成策略建议与沟通材料**

我希望展示的并非“能够搜集多少政策信息”，而是能否从复杂信息中抓住真正影响企业的制度变化，解释政策为什么会影响业务，并把研究判断转化为管理层、业务团队和外部沟通可以直接使用的内容。

## What I can contribute

- **政策与议题判断**：区分正式规则、征求意见稿、执法案例、政策信号与社会热点，判断信息的制度分量和后续演化空间。
- **制度分析**：识别主管机构、权限来源、决策程序和执行机制，回答“谁能决定、如何决定、怎样落地”。
- **业务影响分析**：把政策要求继续转译到产品、内容治理、创作者生态、用户体验、商业化和品牌信任等具体业务环节。
- **利益相关方分析**：梳理监管机构、行业、媒体、专家、用户、创作者和社会组织的不同诉求及影响方式。
- **比较研究**：在不同制度与地区之间识别真正可比的政策机制，判断其他市场经验能否被借鉴。
- **公共沟通**：把复杂研究压缩为管理层摘要、政策简报、议题材料、Q&A 和 talking points，并保持事实、判断与建议之间的边界。

---

## Featured Case

### AIGC 内容标识规则如何转化为内容平台治理议题

这是一篇基于公开资料完成的真实政策案例，以《人工智能生成合成内容标识办法》、GB 45438—2025 以及小红书公开 AI 治理规则为材料。

案例没有停留在法规摘要，而是继续追踪：

**监管目标如何进入平台治理 → 平台规则如何影响内容分发与创作者行为 → 治理机制如何进一步影响用户对内容真实性与社区信任的判断**

案例包含：

- 政策与平台治理时间线
- 监管权限与制度结构
- 平台业务影响链
- Stakeholder map
- 创作者与用户侧影响
- 关键不确定性与议题判断
- 公共事务行动建议
- 管理层一页式结论
- 对外沟通 Q&A

👉 **[直接查看案例：AIGC 内容标识规则如何转化为内容平台治理议题](examples/xiaohongshu-aigc-public-affairs-case.md)**

---

## Public Affairs Workflow

```text
Policy / Issue Signal
        ↓
Fact & Source Verification
        ↓
Institutional Analysis
        ↓
Business Impact Mechanism
        ↓
Stakeholder Mapping
        ↓
Risk / Opportunity Judgment
        ↓
Strategic Recommendation
        ↓
Internal Brief / External Communication
```

这套流程强调三个原则：

1. **先判断制度状态，再判断风险。**  
   一项政策是正式生效、征求意见、监管表态还是社会议题，其对企业的约束程度并不相同。

2. **先解释影响机制，再谈影响大小。**  
   “政策可能影响业务”没有足够的信息价值，需要继续回答影响经过哪个制度和业务环节发生。

3. **研究最终要服务于行动与表达。**  
   公共事务分析需要进一步转化为可执行的观察重点、沟通对象、行动建议和对外表达。

---

## Agent Skill

除了案例分析，我将上述工作方法整理成了一个可复用的 **Public Affairs Policy Analyst Agent Skill**。

它可以用于：

- 新政策 / 新规快速扫描
- 征求意见稿影响分析
- 社会热点与公司业务交汇分析
- Stakeholder mapping
- 一页式政策简报
- 深度议题研究
- 管理层摘要
- 外部 Q&A / talking points

核心 Skill：

👉 [`skills/public-affairs-policy-analyst/SKILL.md`](skills/public-affairs-policy-analyst/SKILL.md)

分析框架：

👉 [`skills/public-affairs-policy-analyst/references/analysis-framework.md`](skills/public-affairs-policy-analyst/references/analysis-framework.md)

输出模板：

👉 [`skills/public-affairs-policy-analyst/references/output-templates.md`](skills/public-affairs-policy-analyst/references/output-templates.md)

信息源标准：

👉 [`skills/public-affairs-policy-analyst/references/source-standard.md`](skills/public-affairs-policy-analyst/references/source-standard.md)

---

## More Examples

### Hypothetical Platform Policy Brief

用虚构政策场景演示如何把监管变化转换为平台业务影响、情景判断和行动建议。

👉 [`examples/hypothetical-platform-policy-brief.md`](examples/hypothetical-platform-policy-brief.md)

### Hypothetical Public Communication Package

用虚构场景展示如何从政策分析进一步形成 communication objective、core message、supporting points、敏感议题与 Q&A。

👉 [`examples/hypothetical-public-communication.md`](examples/hypothetical-public-communication.md)

---

## Repository Structure

```text
public-affairs-policy-analyst/
├── README.md
├── LICENSE
├── examples/
│   ├── hypothetical-platform-policy-brief.md
│   ├── hypothetical-public-communication.md
│   └── xiaohongshu-aigc-public-affairs-case.md
└── skills/
    └── public-affairs-policy-analyst/
        ├── SKILL.md
        ├── agents/
        │   └── openai.yaml
        └── references/
            ├── analysis-framework.md
            ├── output-templates.md
            └── source-standard.md
```

`examples/` 同时包含虚构情景演示与基于公开资料完成的真实政策案例；`references/` 保存分析框架、信息源标准与输出模板；`SKILL.md` 将整套公共事务分析方法组织为可复用工作流。

## Example Prompt

```text
使用 $public-affairs-policy-analyst 分析这项新政策。

请先确认政策状态与主管机构，再分析它通过什么机制影响平台业务，
识别关键利益相关方，区分已确认事实、判断与不确定事项，
最后给出一页式管理层简报和公共事务行动建议。
```

## Portfolio Note

本项目中的真实案例仅使用公开政策文件、公开标准信息和公开平台公告，不涉及任何企业内部资料。虚构案例仅用于展示分析方法。

## License

MIT
