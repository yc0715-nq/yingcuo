# 大数据与人工智能

个人课程学习仓库，用于记录《大数据与人工智能》课程的学习笔记、代码与实验。

## 目录结构

```
bigdata-ai-course/
├── README.md          # 仓库说明
├── notes/             # 学习笔记（含 concepts/ 概念学习资料）
├── code/              # 代码示例与作业
├── experiments/       # 实验报告
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
