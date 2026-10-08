# Agent Skills

> 个人沉淀的场景化 Skill 集合 —— 当你需要 Chatbot 在特定场景下给出**符合场景、符合要求**的产出时，直接取用对应的 Skill 即可。

[![Skills](https://img.shields.io/badge/skills-4-brightgreen)](#skills-列表)

## 简介

本仓库的所有 Skill 均为个人在实际使用中总结、打磨的原创产出。每个 Skill 针对一个具体场景，明确「谁使用、写给谁看」，用详细可执行的约束帮助 Chatbot 生成贴合需求的高质量内容。

## Skills 列表

| Skill | 说明 |
| ----- | ---- |
| [开发日志撰写 Skill](skills/开发日志撰写.md) | 非技术人员（运营/社区）撰写面向玩家的开发日志时使用的规范 |
| [GitHub 提交规范 Skill](skills/github提交规范.md) | 生成、改写或审查 git commit message 与 PR 标题时使用的规范 |
| [仓库结构管理 Skill](skills/仓库结构管理.md) | 规划、整理或重构仓库目录结构时使用的规范 |
| [自审迭代 Skill](skills/自审迭代.md) | skill 经过真实使用后，审查产出、归因并迭代 skill 本身的"使用-反馈-修改-再使用"规范 |

## 使用方式

1. 打开对应 Skill 文件，复制全部内容；
2. 在对话开始时粘贴给 Chatbot（或配置为系统提示词）；
3. 按 Skill 中定义的流程描述你的需求即可。

## 仓库结构

```text
agent-skills/
├── skills/                  # Skill 本体，每个文件一个场景
│   ├── 开发日志撰写.md
│   ├── github提交规范.md
│   ├── 仓库结构管理.md
│   └── 自审迭代.md
└── README.md
```

## Skill 编写规范

- 场景定位精准到「谁用」和「写给谁看」；
- 约束详细可执行：适用范围、前置确认、结构骨架、红线、禁用词、对照示例、自检清单；
- 反 AI 腔、反套话，产出要像人话、符合角色身份。
