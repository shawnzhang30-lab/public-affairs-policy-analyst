# Public Affairs Policy Analyst

> An Agent Skill for policy intelligence, business-impact analysis, stakeholder mapping, and public communication.

这个项目把政治学研究能力转化为一套可复用的公共事务工作流：面对政策、监管和社会议题变化，先判断事实与制度状态，再分析其影响业务的具体机制，识别关键利益相关方与争议结构，最后形成可供内部决策或外部沟通使用的材料。

## Why this project

公共事务工作并不止于“搜集政策信息”。真正有价值的分析，需要回答几个连续的问题：

**发生了什么 → 谁拥有决定权 → 政策如何落地 → 为什么影响业务 → 谁会推动或阻碍 → 风险如何演化 → 公司应如何行动和表达**

本 Skill 将这条分析链条固化为可重复使用的流程，同时保留政治学训练中对制度、权力、利益、公共价值与政治语境的敏感度。

## What it demonstrates

- **政策敏感度**：区分正式规则、征求意见稿、执法案例、政策信号与社会议题，避免把不同强度的信息混在一起。
- **制度分析能力**：识别主管机构、权限来源、决策程序、执行机制与地方差异，判断“谁能决定、如何决定、怎样执行”。
- **业务转译能力**：不止描述政策内容，继续追踪其对产品、运营、商业化、内容治理、用户关系和品牌信任的影响路径。
- **议题研究能力**：把碎片化信息整理为清晰的问题结构，区分事实、判断、预测与建议。
- **利益相关方分析**：识别机构、行业、媒体、专家、用户与社会组织的不同诉求、影响力与潜在行动。
- **比较政治视角**：在有必要时比较不同地区或制度环境下的政策逻辑，同时避免机械类比。
- **公共沟通能力**：把复杂研究压缩为一页简报、管理层摘要、Q&A、talking points 和议题沟通材料。


## Featured real-world case

### AIGC 内容标识规则如何转化为内容平台治理议题

仓库新增了一篇基于公开资料的真实政策案例，以《人工智能生成合成内容标识办法》、GB 45438—2025 以及小红书 2026 年公开 AI 治理规则为材料，展示如何完成：

**政策识别 → 制度结构判断 → 平台业务影响分析 → Stakeholder mapping → 风险与机会判断 → 管理层简报 → 对外沟通**

这个案例特别关注一个公共事务岗位经常面对的问题：法规文本给出的只是治理起点，企业真正需要判断的是监管目标如何进入产品、内容治理、创作者生态和用户信任。

👉 [`examples/xiaohongshu-aigc-public-affairs-case.md`](examples/xiaohongshu-aigc-public-affairs-case.md)

## Repository structure

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

`SKILL.md` 遵循 Agent Skills 的目录与元数据约定；`references/` 保存分析方法与模板，避免把所有内容塞进主 Skill；`examples/` 用虚构案例展示最终产出，不对应任何现实公司的内部情况。

## Example prompts

```text
Use $public-affairs-policy-analyst to analyze this newly released policy.
Separate confirmed facts from interpretation, explain the business impact mechanism,
map key stakeholders, and give me a one-page public affairs brief.
```

```text
使用 $public-affairs-policy-analyst 分析这个社会热点与内容平台业务的交汇点。
重点判断议题会不会转化为监管、舆论或行业治理压力，并给出沟通建议。
```

```text
使用 $public-affairs-policy-analyst 对这份征求意见稿做政策影响分析。
不要复述条文，重点回答：哪些变化真正影响业务、影响通过什么机制发生、
哪些问题目前仍不确定、下一步应该持续观察什么。
```

## Design principles

1. **Facts before judgment** — 先建立事实底座，再给判断。
2. **Mechanism before impact** — 不用“影响较大”代替分析，必须写出影响路径。
3. **Institution before speculation** — 先判断权限、程序与执行机制，再讨论趋势。
4. **Audience before communication** — 沟通内容取决于对象、目标和风险，不追求一套话术覆盖所有场景。
5. **Uncertainty is information** — 明确未知事项、反向信号与判断置信度。
6. **Public affairs is not legal review** — 涉及法律义务时，应明确哪些内容需要专业法律意见。

## Portfolio note

这个项目更适合作为公共事务岗位的“工作样本”而非单纯技术 Demo。它希望展示的是：如何把政治学中的制度分析、比较研究、概念辨析和论证能力，转换成企业能够直接使用的政策判断与公共沟通产品。

## License

MIT
