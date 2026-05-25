# AI Survival Guide for Graduates

> 理工科版本 / 文科商科版 双版本并行

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/gmaxxxie/ai-survival-guide-graduate)](https://github.com/gmaxxxie/ai-survival-guide-graduate/stargazers)

---

## 这是什么

这是一套面向理工科毕业生（材料/机械/电子/化工/生物医学等非CS专业）的AI时代就业指南。

**核心观点：** 高校AI课程更新周期3-5年，AI技术迭代6-12个月，约45%的毕业生面临结构性就业错位。这不是学生个人的问题，是课程体系跟不上的系统性问题。

**解决路径：** 专业是底座，AI是杠杆，两者缺一不可。

---

## 课程结构

```
phases/
├── 00-觉醒与框架/        ← 你在这里：认知校准 + 技能树优先级
├── 01-项目实战/          ← 怎么做一个有说服力的完整项目
├── 02-求职工具/          ← AI简历 + AI面试 + 工具清单
├── 03-入职生存/          ← 第一天/第一个月/第60-100天
├── 04-个人AI系统/        ← 知识库 + 能力阶梯
├── 05-AI与你/            ← AI作为协作者
├── 06-创业与软技能/      ← AI创业 + 职场软技能
└── 07-总结/
```

---

## 两个版本，怎么选？

| 版本 | 内容 | 路径 |
|------|------|------|
| 理工科版 | 计算机/电子/机械/数学/物理等 | `phases/`（主目录） |
| 文科/商科版 | 中文/新闻/商科/法律/艺术等 | `tracks/arts/phases/` |

```bash
# 理工科版
git checkout main
python3 scripts/install_skills.py ~/.claude/skills

# 文科/商科版
cd tracks/arts
python3 scripts/install_skills.py ~/.claude/skills
```

---

每个 lesson 包含：
- `outputs/skill-*.md` — AI导师角色提示词，注入你的AI助手
- `quiz.json` — 学前/学后测验题

---

## 快速开始

### 1. 克隆到本地

```bash
git clone https://github.com/gmaxxxie/ai-survival-guide-graduate.git
cd ai-survival-guide-graduate
```

### 2. 安装技能到你的AI助手

```bash
# Claude
python3 scripts/install_skills.py ~/.claude/skills

# 其他AI助手，请参考其官方技能安装方式
```

### 3. 开始对话

```
/awakening-misalignment   # Phase 00, Lesson 01: 认知错位诊断
/skill-tree-priority      # Phase 00, Lesson 02: 技能树优先级
```

---

## 课程哲学

**不是让你学更多技术，是让你把学过的技术锤炼成能交付成果的能力。**

理工科毕业生最大的优势是有专业底座。最大的误区是以为"学技术"可以替代"用技术解决问题"。

**AI不会取代师傅，但会用AI的毕业生，可以用AI替代师傅的一部分功能，让自己成长得更快。**

---

## 目标读者

- 理工科方向（材料/机械/电子/化工/生物医学等）应届毕业生
- 对AI时代的就业方向感到迷茫的学生
- 想在专业领域里建立差异化竞争力的求职者

---

## 配套资源

- [《毕业生AI生存指南》微信读书完整版](https://weread.qq.com/) — 书籍完整内容
- [AI学习追踪项目](https://github.com/your-repo) — 个人AI学习进度管理

---

## 贡献

欢迎提交 Issue 和 Pull Request！

---

## License

MIT License
