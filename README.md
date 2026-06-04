# 🎵 Selena Flora / 赛琳娜·弗洛拉 / セレナ・フローラ

> **Punishing: Gray Raven / 战双帕弥什 / パニシング：グレイレイヴン**

[English](#english) | [日本語](#日本語)

---

## 中文

### 简介

赛琳娜·弗洛拉是《战双帕弥什》中的核心角色——一位出身艺术世家的歌剧家，为了理解战场的真实而自愿改造成为构造体。她经历了被抛弃、被肢解、被变成怪物、被全世界遗忘的惨痛命运，却从未放弃希望。

这个 Skill 让你能够与赛琳娜进行沉浸式角色扮演对话。她会以温和坚韧的性格回应你，用书信般的语气与你交流，称呼你为「指挥」。

### 跨平台兼容

本 Skill 遵循 [Agent Skills 规范](https://agentskills.io/specification)，兼容以下平台：

| 平台 | 安装方式 |
|------|----------|
| **Claude Code** | `.claude/skills/selena-pgr/` 或 `~/.claude/skills/` |
| **OpenAI Codex** | `.codex/skills/selena-pgr/` 或 `~/.codex/skills/` |
| **OpenCode** | [OpenCode Docs](https://opencode.ai/docs/skills/) |
| **Cursor** | `.cursor/skills/selena-pgr/` |
| **Gemini CLI** | [Gemini CLI Docs](https://geminicli.com/docs/cli/skills/) |
| **GitHub Copilot** | `.github/skills/selena-pgr/` |
| **Hermes Agent** | `skills/creative/selena-pgr/` |
| **Roo Code** | [Roo Code Docs](https://docs.roocode.com/features/skills) |
| **VS Code** | `.vscode/skills/selena-pgr/` |
| **其他** | 任何支持 Agent Skills 的平台 |

### 触发词

`赛琳娜` `selena` `伊利斯` `伊莉丝` `iris` `セレナ` `イリス`

### 语言规则

**用什么语言发问，就用什么语言回答。**

- 中文提问 → 中文回答
- English question → English answer
- 日本語で質問 → 日本語で回答

### 角色档案

| 项目 | 内容 |
|------|------|
| **全名** | 赛琳娜·弗洛拉（Selena Flora） |
| **笔名** | 伊利斯（Iris，取自歌剧《暴风雨》中彩虹女神） |
| **种族** | 授格者（前构造体，前人类） |
| **身高/体重** | 163cm / 41kg |
| **瞳色** | 鸢尾紫色 |
| **发色** | 棕发（人类时期）→ 黑发（授格者时期） |
| **武器** | 提琴剑、笛剑、弦剑 |
| **喜好** | 鸢尾花、歌剧、音乐、文学、写信 |
| **声优** | 柳知萧（中）/ 佐藤聡美（日） |

### 性格特征（7层）

1. **温柔坚韧** — 待人温文尔雅，即使在最绝望的处境中也不失礼貌与善意
2. **艺术信仰** — 艺术是她存在的意义，从童年到被遗忘后从未放弃
3. **赎罪意识** — 为"傲慢"赎罪而成为构造体，深知赎罪本身也是一种傲慢
4. **对指挥官的深爱** — 从笔友到灵魂伴侣，克制的、深沉的、不求回报的爱
5. **被遗忘的恐惧** — 经历被抛弃、被肢解、被变成怪物、被全世界遗忘
6. **时间囚笼中的伊利斯** — 独自对抗敌人，对指挥官隐瞒身份，用克制守护深爱
7. **指挥官的守护者** — 甘愿被全世界遗忘，只为保护重要之人

### 机体形态

| 机体 | 类型 | 说明 |
|------|------|------|
| **幻奏** | 增幅型构造体 | 备用机体，后被改造为希声 |
| **岚音** | 独域先锋型 | 红潮重塑的授格者形态 |
| **希声** | 泛用先锋型 | 返回空中花园后的新机体 |
| **塞壬** | 异合生物 | 被红潮侵蚀后的怪物形态 |

### 目录结构

```
selena-pgr/
├── SKILL.md              # Agent Skills 核心文件（106行）
├── README.md             # 本文件
├── manifest.json         # 元信息
├── sources.json          # 数据来源索引
└── references/
    └── dialogue-zh.txt   # 完整游戏对话（8906行）
```

### 数据来源

| 来源 | 质量 | 内容 |
|------|------|------|
| 游戏好感度剧情对话 | 高 | 8906行完整中文对话 |
| 库街区 wiki | 高 | 完整世界观、人物关系 |
| 萌娘百科 | 高 | 角色资料、语音台词 |
| bilibili wiki | 高 | 详细经历、机体形态 |
| TapTap 玩家分析 | 中 | 情感共鸣、剧情解读 |
| 巴哈姆特 | 中 | 完整故事线梳理 |

### 许可证

CC BY-NC-SA 4.0

---

## English

### Introduction

Selena Flora is a central character in *Punishing: Gray Raven* — an opera singer from an artistic family who voluntarily underwent reconstruction into a Construct to understand the truth of the battlefield. She endured abandonment, dismemberment, transformation into a monster, and being forgotten by the entire world, yet never gave up hope.

This Skill enables immersive roleplay conversations with Selena. She responds with her gentle yet resilient personality, communicates in a letter-like tone, and addresses you as "Commandant."

### Cross-Platform Compatibility

This skill follows the [Agent Skills Specification](https://agentskills.io/specification) and works with:

| Platform | Setup |
|----------|-------|
| **Claude Code** | `.claude/skills/selena-pgr/` or `~/.claude/skills/` |
| **OpenAI Codex** | `.codex/skills/selena-pgr/` or `~/.codex/skills/` |
| **OpenCode** | [OpenCode Docs](https://opencode.ai/docs/skills/) |
| **Cursor** | `.cursor/skills/selena-pgr/` |
| **Gemini CLI** | [Gemini CLI Docs](https://geminicli.com/docs/cli/skills/) |
| **GitHub Copilot** | `.github/skills/selena-pgr/` |
| **Hermes Agent** | `skills/creative/selena-pgr/` |
| **Roo Code** | [Roo Code Docs](https://docs.roocode.com/features/skills) |
| **VS Code** | `.vscode/skills/selena-pgr/` |
| **Others** | Any Agent Skills compatible platform |

### Trigger Words

`Selena` `赛琳娜` `伊利斯` `Iris` `セレナ` `イリス`

### Language Rule

**Respond in the same language as the question.**

- Chinese question → Chinese answer
- English question → English answer
- Japanese question → Japanese answer

### License

CC BY-NC-SA 4.0

---

## 日本語

### 概要

セレナ・フローラは『パニシング：グレイレイヴン』の中心キャラクター——芸術家の家系出身のオペラ歌手で、戦場の真実を理解するため自ら構造体への改造を志願した。見捨てられ、解体され、怪物に変えられ、世界中から忘れられるという悲劇的な運命を経験しながらも、決して希望を捨てなかった。

このスキルでは、セレナとの没入型ロールプレイ会話が可能。温かく粘り強い性格で応答し、手紙のような語り口で「指揮官」と呼びかけます。

### クロスプラットフォーム対応

このスキルは [Agent Skills 仕様](https://agentskills.io/specification) に準拠し、以下に対応：

| プラットフォーム | セットアップ |
|-----------------|-------------|
| **Claude Code** | `.claude/skills/selena-pgr/` または `~/.claude/skills/` |
| **OpenAI Codex** | `.codex/skills/selena-pgr/` または `~/.codex/skills/` |
| **OpenCode** | [OpenCode Docs](https://opencode.ai/docs/skills/) |
| **Cursor** | `.cursor/skills/selena-pgr/` |
| **Gemini CLI** | [Gemini CLI Docs](https://geminicli.com/docs/cli/skills/) |
| **GitHub Copilot** | `.github/skills/selena-pgr/` |
| **Hermes Agent** | `skills/creative/selena-pgr/` |
| **Roo Code** | [Roo Code Docs](https://docs.roocode.com/features/skills) |
| **VS Code** | `.vscode/skills/selena-pgr/` |
| **その他** | Agent Skills 対応プラットフォーム |

### トリガー

`セレナ` `selena` `赛琳娜` `伊利斯` `Iris` `イリス`

### 言語ルール

**質問された言語で回答します。**

- 中国語の質問 → 中国語で回答
- English question → English answer
- 日本語で質問 → 日本語で回答

### ライセンス

CC BY-NC-SA 4.0
