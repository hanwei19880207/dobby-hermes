# 质量域 Harness 工程架构规划 v0.1

> 飞书文档：https://www.feishu.cn/docx/VfgydOpqqoMApyxMWVhc4LaQnJg
> 架构图 HTML：`docs/architecture/quality-harness-architecture.html`
> 版本：v0.1 | 2026-06-07

## 核心结论

1. **Harness 架构**：Agent运行时层 + Harness核心（约束/环境/验证） + Skill Hub/知识底座 三层架构
2. **知识库规划**：消费者（消费D-End上游知识）+ 生产者（反哺资损案例/缺陷/测试经验）
3. **反哺路径**：采集→蒸馏→审核→入库→消费→校准 闭环
4. **阶段推进**：0-2月主测试Agent MVP → 2-4月 Skill扩展 → 4-6月全链路覆盖
