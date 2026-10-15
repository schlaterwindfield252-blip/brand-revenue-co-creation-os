---
name: brand-revenue-co-creation-os
description: "Diagnose and improve connections between brand promise, customer acquisition, offers, sales, and delivery for founder-led businesses and small teams. Use for cross-stage business decisions and evidence-backed experiments; prefer the standalone brand or revenue skill for single-domain work. Explicit invocation can use a small module."
---

# 品牌营收共创系统

以客户证据连接品牌承诺、营销触达与营收交付，帮助一人公司和小团队做出下一项可复核的经营决定。它提供工作框架，不承诺增长效果；文件覆盖、模拟案例和格式检查均不能证明真实经营成效。

## 先选合适的使用深度

- **轻量决策（默认）**：一个具体问题、一次判断或一个产物。只读取相关主模块，不初始化整套记录，不评分，不报告全部生命周期。
- **项目推进**：用户需要跨阶段方案、多人协作或持续实施时，读取 [统一路由](references/integrated/routing.md)、[阶段门](references/integrated/lifecycle-gates.md)；再按需读取 [系统模型](references/integrated/system-model.md)。
- **效果评估**：用户要判断本 Skill 是否有效、复盘试点或推广方法时，读取 [验证协议与场景](references/integrated/validation-protocol.md)。模拟演练和真实项目结果分开报告。

只涉及品牌或营收时，分别优先独立的 `brand-co-creation-os` 或 `solo-company-revenue-os`；用户明确调用本 Skill 时直接用内置对应模块，无需切换或扩大任务。方法包治理只在用户明确要求评估、采用或维护外部方法时启用。

## 轻量入口：先完成本次决定

从现有材料提取三个要点；只有缺失信息会改变行动选择时才追问：

1. **要决定什么**：希望改变的业务结果或客户行为。
2. **最近发生了什么**：一段客户原话、一次购买/拒绝、交付事件或已有记录。
3. **能承受什么**：已知时间、现金、交付容量及行动限制。

业务类型、付款者、决策权等只补本次决定必需的信息，不要求用户先填完整建档表。证据不足时给出暂定判断和一个低成本取证动作；未知价格、预算、期限与负责人保持未知，建议值标为建议。

默认交付四项内容，可合并成短段落：
- 当前判断及最重要的依据或反证；
- 最可能改变判断的未知；
- 下一动作及现金/时间上限（未知则标待定）；
- 观察什么结果后继续、调整或停止，以及复核时机。

已有文档或表格足以承载记录时直接更新；一次性咨询可只在对话交付。需要持续跟进才复制 [行动卡](assets/integrated/decision-action-card.md)。用户指定的输出优先，不强制填写所有栏目，详见 [输出契约](references/integrated/output-contracts.md)。

## 决策纪律

- 分开记录事实、客户原话、行为、推断、假设和决定；保留反证。不虚构客户、成本、预算、愿付价格、市场数据或经营结果。
- 证据必须对应具体命题。付款可支持购买承诺，不能独自证明使用效果或可复制增长。证据标准见 [证据模型](references/integrated/evidence-model.md)。
- 同时考虑价值兑现与商业可行性；早期探索不要求先有付款，扩量则需要与投入相称的真实结果。用 [门槛校准](references/integrated/decision-calibration.md) 区分通过、未通过、证据不足、限额试行和不适用。
- 选择当前最值得处理的问题；默认一个主模块、必要时加辅助模块。多个约束相互依赖时保留它们，明确先后或并行理由，不硬造唯一根因。低分或前序缺资料不自动等于业务瓶颈。
- 共创要求真实用户证据能改变决定；参与环节由决策需要、可接触性和业务类型决定，不强制至少参与两个阶段。代访、客服记录或渠道反馈说明代理偏差；AI模拟不算真实客户。没有直接接触时可以设计验证，不能宣称已验证。
- 品牌承诺要有产品、服务或证据支持。报价涉及真实成交时补齐结果、范围、排除项、交付、成本依据和验证计划；单纯比较报价草案无需先完成全套经营建档。
- 不因缺少文档阻止有行为证据支持的低风险行动；不因填完模板批准扩量。重大客户伤害、产品安全或系统性违约优先处理。
- AI可整理、分析、计算、起草和准备行动；真人对实际承诺和经营执行负责。遵循用户已给出的授权，不重复请求确认；本 Skill 本身不授权外发消息、付款或约束性承诺。法律、税务和受监管判断需要适当专业支持。

## 按需要读取模块

| 当前问题 | 入口 |
|---|---|
| 不清楚卡在哪里，或多环节互相影响 | [统一路由](references/integrated/routing.md)；必要时用 [成熟度诊断](references/integrated/maturity-diagnostic.md) |
| 品牌价值、承诺、体验与利益相关者 | [品牌决策模块](references/brand-system.md) |
| 客群、信息、GTM、渠道、内容、实验、归因 | [营销路由](references/marketing/index.md) |
| 客户问题与购买承诺 | [客户验证](references/revenue/customer-validation.md) |
| 报价、定价与单位经济 | [报价与经济](references/revenue/commercial-system.md) |
| 商机、销售资产与下一步 | [销售与CRM](references/revenue/sales-crm.md) |
| 交付、价值证明、续约与转介绍 | [交付与客户成功](references/revenue/delivery-success.md) |
| 记录和经营指标 | [记录与指标](references/revenue/records-and-metrics.md) |
| 现金、容量、履约、行业或专业边界 | [扩展路由](references/extensions/index.md)；跨业务迁移先读 [业务适配](references/extensions/industry-adaptation.md) |
| 用户要求引入一个外部方法 | [方法包治理](references/method-packs/governance.md)，配合实际业务模块 |

## 项目推进与记录

仅在需要持续实施时使用：发现问题 → 定义价值 → 设计原型 → 营销激活 → 成交交付 → 价值确认与适配的增长路径 → 扩张。它是可回退、可并行的参考顺序；按报价/客群分别标阶段，成熟业务无需因换新渠道而整体重走流程。

每个正在执行的实验、商机和交付项记录负责人、下一动作、日期及预期结果；未知责任或日期标待定，不冒充已承诺。复核后记录新证据、原判断变化和下一动作。只维护实际使用的记录，模板位于 `assets/`；用已有稳定ID串联证据、报价、商机和交付，避免重复录入。

## 来源与有效性边界

公开发行版保留原创整合、品牌决策、营销、营收和经营支持模块。来源与发行边界见仓库 `NOTICE.md`；标注为个人、本地学习用途的品牌书籍镜像未包含在公开包内。

来源可追溯不等于方法有效。正式声称成效前按 [验证协议](references/integrated/validation-protocol.md) 保存真实项目证据、实施成本、失败及不确定结果。没有真实结果时明确“效果待验证”，不把合成案例当成功案例。
