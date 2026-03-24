# 领科虾 (lingke-tutor)

> 领科教育 / WLSA 入学考试 AI 家教，一个可以替代真人一对一的备考助手

![Skill Version](https://img.shields.io/badge/version-1.0.0-blue)
![Platform WorkBuddy](https://img.shields.io/badge/Platform-CodeBuddy-orange)

## 简介

领科虾是一个基于 WorkBuddy (CodeBuddy) 的 AI 家教 skill，专门为准备领科教育（Linke Education）和 WLSA 入学考试的学生提供：

- 数学 / 英语 / 逻辑 考点精讲
- 历年题型解题技巧
- 英语作文批改（PEEL 结构）
- WLSA 英文模拟面试
- 个性化备考计划

## 适用人群

- 准备报考领科教育（上海校区）的学生
- 准备报考 WLSA 的学生
- 想了解国际学校入学考试风格的家长

## 安装方法

### 方式一：从文件安装（推荐）

1. 下载本仓库的 `lingke-tutor.zip` 文件
2. 打开 WorkBuddy (CodeBuddy)
3. 进入「技能市场」→「从文件安装」
4. 选择下载的 zip 文件

### 方式二：手动安装

```bash
# 解压到 CodeBuddy 的 skill 目录
unzip lingke-tutor.zip -d ~/.codebuddy/skills/

# 重启 CodeBuddy 使技能生效
```

## 使用方法

安装成功后，直接在 CodeBuddy 对话中输入以下内容即可激活：

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
└── references/
    ├── exam_overview.md        # 领科/WLSA 考试概览
    ├── math_strategies.md      # 数学解题策略
    └── english_strategies.md   # 英语备考策略
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
