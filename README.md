# 大数据与人工智能

个人课程学习仓库，用于记录《大数据与人工智能》课程的学习笔记、代码与实验。

## 目录结构

```
bigdata-ai-course/
├── README.md          # 仓库说明
├── notes/             # 学习笔记（含 concepts/ 概念学习资料）
├── code/              # 代码示例与作业
├── experiments/       # 实验报告
├── learning-materials/ # 概念学习资料（HTML，由 Skill 生成）
└── .workbuddy/
    └── skills/
        └── concept-learning-generator/   # 「概念学习资料生成」Skill
```

## 概念学习资料生成 Skill

仓库内置一个 **concept-learning-generator** Skill：当对《大数据与人工智能》课程中的某个概念不理解时，可让 AI 生成一份结构化学习资料（是什么 → 为什么 → 生活类比 → 工作机制 → 代码示例 → 自测练习），输出到 `notes/concepts/` 目录。

使用方式：在支持加载仓库级 Skill 的工具中，直接对某个概念说"帮我把 XX 概念生成学习资料"即可自动触发。

## 环境

- Python 3.12
- Git
- VS Code

## 学习计划

- [ ] 大数据概述
- [ ] Hadoop 与 HDFS
- [ ] Spark 编程
- [ ] 机器学习基础
- [ ] 深度学习与神经网络

## 学习资料（learning-materials）

由仓库内置的 **concept-learning-generator** Skill 生成的结构化 HTML 学习资料，每份固定包含 6 个部分：一句话定义 → 核心直觉 → 生活类比 → 工作机制 → 代码示例 → 自测练习。

- [AI Agent（智能体）](learning-materials/agent.html)
- [大模型的上下文（Context）](learning-materials/llm-context.html)
- [Skill（技能）](learning-materials/skill.html)
- [Agent、上下文与 Skill 的关系](learning-materials/relationship.html)

## 作业说明

本次作业：使用仓库内置的 concept-learning-generator Skill，围绕《大数据与人工智能》课程中的核心概念生成结构化学习资料，输出为独立 HTML 文件并统一放入 `learning-materials/` 目录；完成后 `git add . && git commit && git push` 提交到本仓库（远程 `yc0715-nq/yingcuo`）。

> 提示：如需新增概念资料，直接对概念说"帮我把 XX 概念生成学习资料"即可触发 Skill。

## 人工核查

> 本仓库中的学习资料（`learning-materials/`）由 AI 辅助生成。提交前请同学自行核查：内容表述是否准确、代码示例是否可运行、结构是否完整。**AI 生成内容不代表最终答案，理解请以课程教材与教师讲解为准**；确认无误后再行提交。
>
> （若老师有指定的"人工核查"原文措辞，请以教师要求为准，可替换本段。）

