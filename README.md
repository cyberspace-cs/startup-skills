# Startup Skills — 创业课程知识沉淀与技能库

> 从 472 条课程笔记中沉淀出的可执行创业 Skills，覆盖调研、设计、商业、工程四大核心领域。

## 🎯 这个仓库是什么

这不是课程笔记的堆砌，而是一套**从知识到行动**的转化体系：

```
原始课程笔记 → 结构化知识卡片 → 可复用分析框架 → 可执行 Skill
```

每个 Skill 都有明确的**触发场景、输入、执行步骤、输出模板和真实案例**，可以直接在创业实战中使用。

## 📚 课程体系（10 大主题 / 472 条目）

| 优先级 | 主题 | 条目数 | 对创业的价值 | 目录 |
|--------|------|--------|-------------|------|
| ★★★★★ | 调研与产品方法论 | 23 | 问题定义、用户调研、验证设计 | `01-research-product-methodology/` |
| ★★★★★ | 设计思维与实践 | 113 | 双钻模型、假设识别、原型、迭代 | `02-design-thinking/` |
| ★★★★★ | 商业与创业 | 59 | 商业模式、创业闭环、市场与团队 | `03-business-startup/` |
| ★★★★★ | 工程技术 | 114 | 技术可行性、产品开发、系统工程、供应链 | `04-engineering-tech/` |
| ★★★★★ | 项目辩论赛 / 第一性原理 / 在孵团队辅导 | 分布 | 真实提问、反驳和评审逻辑 | `05-debate-first-principles/` |
| ★★★★☆ | 嘉宾讲座与行业洞察 | 82 | 行业、政策、出海、合规、商业环境 | `06-guest-lectures-insights/` |
| ★★★☆☆ | 学院与新生指南 | 28 | 课程流程、团队形成、学院运行 | `07-academy-guide/` |
| ★★★☆☆ CMF 课程 | 43 | 硬件、消费品、材料、设计 | `08-cmf-course/` |
| ★★☆☆☆ | 众筹出海盛会 | 7 | 出海、众筹、商业化验证 | `09-crowdfunding-overseas/` |
| ★★☆☆☆ | 用户实拍 | 2 | 真实使用场景、产品观察 | `10-user-field-notes/` |

## 🏗️ Skill 标准结构

每个 Skill 遵循统一结构，确保可复用、可组合：

```
skill-name/
├── SKILL.md              # 主文档：触发条件、输入、步骤、输出
├── framework.md          # 核心框架/模型详解（带图示）
├── checklist.md          # 执行检查清单（打印可用）
├── templates/            # 可直接填写的模板
│   └── xxx-template.md
└── examples/             # 真实案例与输出样例
    └── case-xxx.md
```

## 📖 沉淀方法论

### 四层转化模型

| 层级 | 内容 | 产出 | 存放位置 |
|------|------|------|----------|
| L1 原始笔记 | 课程逐字稿/PPT/截图 | Markdown 笔记 | `notes-raw/` |
| L2 结构化知识 | 核心概念、模型、框架 | 知识卡片 | 各主题 `knowledge-cards/` |
| L3 可复用框架 | 决策模型、分析模板、检查清单 | 方法论文档 | 各 Skill `framework.md` + `checklist.md` |
| L4 可执行 Skill | 带输入输出、步骤、示例的工作流 | Skill 包 | 各 Skill 完整目录 |

### 沉淀原则

1. **从"知道"到"做到"** —— 每个 Skill 必须有明确的输入、输出和执行步骤
2. **场景驱动** —— 按创业者真实遇到的场景组织，而非按课程章节
3. **可组合** —— 小颗粒度 Skill，可以组合成完整工作流
4. **带示例** —— 每个 Skill 配真实案例和输出样例
5. **可验证** —— 每个框架都有适用边界和反例

## 🚀 如何使用

### 方式一：直接调用 Skill

在 AI 对话中描述你的场景，匹配对应 Skill：

> "我要做一个新市场的调研，用 market-terrain-analysis 这个 Skill"

### 方式二：按阶段组合使用

| 创业阶段 | 推荐 Skill 组合 |
|----------|----------------|
| 机会发现 | 反共识机会识别 + 市场地形分析 + 第一性原理拆解 |
| 用户调研 | 用户访谈框架 + 需求验证矩阵 + 痛点优先级排序 |
| 产品设计 | 双钻设计流程 + 假设识别与验证 + 快速原型 |
| 商业模式 | 商业模式画布 + 单位经济模型 + 寡头市场策略 |
| 技术评估 | 技术可行性分析 + 供应链评估 + 工程里程碑 |
| 融资路演 | 项目辩论评审 + 投资人视角自检 + 路演材料框架 |

## 📝 贡献指南

### 新增一个 Skill 的步骤

1. 在对应主题目录下创建 `skill-name/` 文件夹
2. 复制 `templates/SKILL_TEMPLATE.md` 为 `SKILL.md` 并填写
3. 补充 `framework.md`（核心框架）和 `checklist.md`（检查清单）
4. 在 `templates/` 下放可填写模板
5. 在 `examples/` 下放至少 1 个真实案例
6. 更新对应主题目录的 `README.md`

### 笔记沉淀流程

1. 原始笔记放入 `notes-raw/`，按主题分类
2. 提炼核心概念，写入对应主题的 `knowledge-cards/`
3. 识别可复用的框架/模型，升级为 Skill
4. 在实战中验证 Skill，补充案例和边界

## 📂 目录索引

- [01-research-product-methodology/](./01-research-product-methodology/) — 调研与产品方法论
- [02-design-thinking/](./02-design-thinking/) — 设计思维与实践
- [03-business-startup/](./03-business-startup/) — 商业与创业
- [04-engineering-tech/](./04-engineering-tech/) — 工程技术
- [05-debate-first-principles/](./05-debate-first-principles/) — 项目辩论/第一性原理
- [06-guest-lectures-insights/](./06-guest-lectures-insights/) — 嘉宾讲座与行业洞察
- [07-academy-guide/](./07-academy-guide/) — 学院与新生指南
- [08-cmf-course/](./08-cmf-course/) — CMF 课程
- [09-crowdfunding-overseas/](./09-crowdfunding-overseas/) — 众筹出海
- [10-user-field-notes/](./10-user-field-notes/) — 用户实拍
- [templates/](./templates/) — 通用模板
- [notes-raw/](./notes-raw/) — 原始课程笔记

---

*持续沉淀中，欢迎在实战中验证并反馈。*
