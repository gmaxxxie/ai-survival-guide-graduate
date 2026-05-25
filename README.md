# AI生存手册 · 毕业生篇

> 你的AI时代生存指南 — 理工科 / 文科商科 双版本

![GitHub stars](https://img.shields.io/github/stars/gmaxxxie/ai-survival-guide-graduate)
![GitHub forks](https://img.shields.io/github/forks/gmaxxxie/ai-survival-guide-graduate)

## 两个版本，怎么选？

```
main 分支（理工科版）
适合：计算机、电子、机械、数学、物理等理工背景
核心框架：Awakening → Skill Tree → Project Real Launch → Resume/Interview → Day-one → First Month → Day60-100 → Knowledge System → Career Ladder → AI+You → Startup Era → Soft Skills → Summary

arts 分支（文科/商科版）
适合：中文、历史、哲学、外语、新闻传播、法学、教育学、市场营销、商科、艺术设计等非技术背景
核心框架：文字感知力 + 叙事能力 + 社会洞察 + 作品集 + AI翻译官 + 感知力职场
```

**共同核心判断**：AI是模式识别器，不是思考主体。你的判断力才是核心资产。

---

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/gmaxxxie/ai-survival-guide-graduate.git
cd ai-survival-guide-graduate

# 切换到你的版本
git checkout main      # 理工科版
# 或
git checkout arts      # 文科/商科版

# 安装技能（以 Claude 为例）
python3 scripts/install_skills.py ~/.claude/skills

# 开始对话
# 理工科版 → /ai-survival-guide-entry
# 文科版   → /ai-survival-guide-arts-entry
```

---

## 课程结构

### 理工科版（main分支）

```
Phase 0: 觉醒与框架
├── 01 错位认知（Awakening Misalignment）
└── 02 能力树（Skill Tree Priority）

Phase 1: 项目实战
└── 01 真实项目发布（Project Real Launch）

Phase 2: 求职工具
├── 01 简历 ATS（Resume ATS Master）
├── 02 AI模拟面试（AI Interview Practice）
└── 03 工具清单（Job Tools Arsenal）

Phase 3: 入职生存
├── 01 第一天（Day One Survival）
├── 02 第一個月（First Month Delivery）
└── 03 第60-100天（Day60-100 Accountability）

Phase 4: 个人AI系统
├── 01 知识库（Personal AI Knowledge System）
└── 02 能力阶梯（Career Ladder）

Phase 5: AI与你
└── 01 AI协作者（AI+You Combo）

Phase 6: 创业与软技能
├── 01 AI创业（Startup AI Era）
└── 02 职场软技能（Workplace Soft Skills）

Phase 7: 总结
└── 01 全书总结（Summary & Recap）
```

### 文科/商科版（arts分支）

```
Phase 0: 觉醒与框架
├── 01 错位认知（文字+X体系 vs 理工科技能树）
└── 02 能力树（三叶草模型 + 文字感知力）

Phase 1: 项目实战
└── 01 作品集思维（追问耐受度 + 四维评估）

Phase 2: 求职工具
├── 01 AI简历（翻译官而非作家）
├── 02 AI面试（BEI + 内容创意）
└── 03 工具清单（内容人武器库）

Phase 3: 入职生存
├── 01 第一天（内容全量阅读）
├── 02 第一個月（内容闭环交付）
└── 03 第60-100天（成果档案）

Phase 4: 个人AI系统
├── 01 知识库（判断力为核心）
└── 02 能力阶梯（执行者→策略者→创作者）

Phase 5: AI与你
└── 01 AI协作者（人机分工判断标准）

Phase 6: 创业与软技能
├── 01 AI创业（自媒体/内容服务/数字产品）
└── 02 职场软技能（感知力+向上沟通+会议贡献）

Phase 7: 总结
└── 01 全书总结（文科AI生存路线图）
```

---

## 课程特色

**AI导师带路**：每一课都是一个AI角色提示词，激活后AI以特定导师身份与你对话，不是给你答案，而是引导你自己思考。

**学前+学后测**：每课配套quiz.json，学前测判断你的认知起点，学后测验证学习效果。

**真实场景**：不教概念，教你在真实场景里怎么做——投简历、面试、入职第一天、90天成果汇报。

---

## 推荐学习路径

```
Day 1-3:  通读 Phase 0（觉醒 + 能力树）
Day 4-7:  完成 Phase 1-2（项目 + 求职工具）
Week 2:   完成 Phase 3（入职生存）
Week 3-4: 完成 Phase 4-5（个人AI系统 + AI协作者）
Week 5+:  Phase 6-7（创业/软技能 + 总结）
```

---

## 配套资源

- `scripts/install_skills.py` — 注入技能到你的AI助手
- `phases/*/outputs/skill-*.md` — 每课的AI导师提示词
- `phases/*/quiz.json` — 每课的学前/学后测题目
