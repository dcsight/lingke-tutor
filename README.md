# 领科虾 (lingke-tutor)

> 领科教育 / WLSA 入学考试 AI 家教，一个可以替代真人一对一的备考助手

![Skill Version](https://img.shields.io/badge/version-1.0.0-blue)
![Platform WorkBuddy](https://img.shields.io/badge/Platform-CodeBuddy-orange)

## 简介

领科虾是一个 AI 家教 skill，专门为准备领科教育（Linke Education）和 WLSA 入学考试的学生提供：

- 数学 / 英语 / 逻辑 考点精讲
- 历年题型解题技巧
- 英语作文批改（PEEL 结构）
- WLSA 英文模拟面试
- 个性化备考计划

## 适用人群

- 准备报考领科教育（上海校区）的学生
- 准备报考 WLSA 的学生
- 想了解国际学校入学考试风格的家长

## 安装方式

### 方式一：Claude Code 安装

1. 下载本仓库的 `lingke-tutor` 文件夹
2. 将文件夹复制到 Claude Code 的 skills 目录：
   ```bash
   cp -r lingke-tutor ~/.claude/skills/
   ```
3. 重启 Claude Code 即可使用

### 方式二：OpenClaw 安装

1. 在 OpenClaw 中打开 Skill 市场
2. 点击「从本地安装」
3. 选择 `lingke-tutor` 文件夹或打包的 `.skill` 文件
4. 安装完成后即可在对话中使用

## 使用方法

安装成功后，直接在对话中输入以下内容即可激活：

| 场景 | 示例指令 |
|------|----------|
| 数学解题 | "帮我做一道领科数学题" |
| 英语作文批改 | "帮我改一下这篇英语作文" |
| 模拟面试 | "来一场 WLSA 英文面试" |
| 备考规划 | "我要考领科，怎么准备" |
| 知识咨询 | "领科英语考什么题型" |

## 文件结构

```
lingke-tutor/
├── SKILL.md                    # Skill 主体定义
├── README.md                   # 项目说明
├── evals/
│   └── evals.json              # 评估测试用例集
└── references/
    ├── exam_overview.md        # 领科/WLSA 考试概览
    ├── math_strategies.md      # 数学解题策略
    ├── english_strategies.md   # 英语备考策略
    └── teaching_templates.md   # 教学模式详细模板
```

## 知识库内容

### 领科教育笔试

- 英语：阅读、语法、写作（议论文）
- 数学：代数、几何、函数、综合应用
- 逻辑：图形推理、数列规律

### WLSA 入学考试

- 英语：词汇、阅读、语法填空、写作
- 数学：AMC 风格选择 + 解答题
- 面试：英文即兴演讲、时事讨论

## 免责声明

本 skill 基于公开信息与通用学科知识构建，**不代表领科教育或 WLSA 官方机构**。具体考试时间、报名要求、真题授权等，请以各校官方通知为准。

## 贡献

欢迎提交 Issue 和 Pull Request！

---

Made with ❤️ for students preparing for international schools.
