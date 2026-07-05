# 拼好码：Code Assembly

> 能复用时不重造，能编排时不发明。

Claude Code 用方法论 skill。每次编码任务开始时使用 `/code-assembly` 加载本 skill。

## 7 步工作流

```
需求 → 拆能力 → 搜①官方 → 搜②社区 → 搜③平台 → 评估 → 选组合 → 定边界 → 写胶水 → 验证
```

每步没通过就回到上一步重新搜，不硬推进。

## 配套文件

| 文件 | 用途 |
|------|------|
| `SKILL.md` | 完整方法论 |
| `references/requirement-template.md` | 需求模板 |
| `references/decision-record-template.md` | 决策记录模板 |
| `references/evaluation-matrix.md` | 评估矩阵 |
| `references/search-templates.md` | 搜索命令模板 |

## 核心规则

1. 搜索不可跳过
2. 评估不可省略
3. 记录不可偷懒
4. 回滚路径必须有
5. 验证才等于完成
