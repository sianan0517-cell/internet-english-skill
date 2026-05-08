<div align="center">

**中文** · [English](./README.en.md)

# 🌐 互联网商务英语 Skill

#### 专为中国互联网人打造的每日英语助手，订阅岗位频道，每天推送定制化英语日报

[![License](https://img.shields.io/badge/License-MIT-3B82F6?style=for-the-badge)](./LICENSE)
[![Channels](https://img.shields.io/badge/Channels-16-10B981?style=for-the-badge)](#-频道列表)
[![Scenes](https://img.shields.io/badge/Scenes-10-F59E0B?style=for-the-badge)](#-场景覆盖)

![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-Skill-10B981?style=flat-square&logo=openai&logoColor=white)
![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-8B5CF6?style=flat-square)
![CatDesk](https://img.shields.io/badge/CatDesk-Skill-EC4899?style=flat-square)

</div>

大多数商务英语课教的是脱离场景的通用表达。这个 Skill 不一样——内容来自互联网大厂的真实职场语境，覆盖从日常邮件到晋升答辩的全场景。

**每期日报包含：**
- **3 个岗位术语** — 从订阅频道词库随机抽取，每次例句不同
- **3 个场景表达** — 当日主打场景的实用句式
- **2 个 AI 热词** — 结合当前日期动态生成，保持时效性

---

## 📋 频道列表

<a id="-频道列表"></a>

订阅一个或多个频道：

| 频道 | 岗位 |
|------|------|
| `pm` | 产品经理 |
| `ops` | 运营（增长 / 活动 / 用户运营） |
| `tech` | 技术研发（前端 / 后端 / 算法） |
| `data` | 数据（分析师 / 数据科学） |
| `design` | UI/UX 设计 |
| `mkt` | 市场营销 |
| `hr` | 人力资源 |
| `finance` | 财务 |
| `mgmt` | 管理层 / 向上沟通 |
| `bd` | 商务拓展 / 合作 |
| `qa` | 质量保障 / 测试 |
| `content` | 内容运营 |
| `growth` | 用户增长 / 增长黑客 |
| `legal` | 法务 / 合规 |
| `supply` | 供应链 / 采购 |
| `common` | 通用（所有人适用） |

---

## 🗓️ 场景覆盖

<a id="-场景覆盖"></a>

日报按星期轮换主打场景：

| 星期 | 场景 |
|------|------|
| 周一 | ✉️ 商务邮件 |
| 周二 | 🎙️ 会议发言 |
| 周三 | 🔼 向上沟通 |
| 周四 | 📊 述职汇报 |
| 周五 | ☕ Small Talk |
| 周末 | 🔁 复习总结 |

**随时可练的专项场景：**
- 🎖️ 晋升答辩 — 如何在评委面前证明自己值得晋升
- 🌱 新人破冰 — 入职第一周的自我介绍和建立关系
- 💬 反馈与批评 — 给负面反馈的委婉说法和建设性表达
- 🎯 面试英语 — 英文自我介绍、STAR 法、反问面试官

---

## 🚀 使用方式

**订阅频道** — 直接告诉 Agent 你的岗位：
```
我是产品经理  →  订阅 pm 频道
我做运营的    →  订阅 ops 频道
我在数据团队  →  订阅 data 频道
```

**获取今日日报：**
```
今天的日报 / 发日报 / 今天学什么
```

**练习特定场景：**
```
帮我准备晋升答辩英语
教我怎么 small talk
我要练向上沟通
```

**测验模式：**
```
出几道题考考我 / quiz me
```

**设置每日自动推送：**
告诉 Agent「每天早上 9 点推送日报」，它会用你所在平台的定时能力自动配置。

---

## 📁 文件结构

```
internet-business-english/
├── SKILL.md                    # Skill 定义文件（Agent 读取此文件）
├── README.md                   # 中文说明（本文件）
├── README.en.md                # English README
├── .gitignore
└── references/
    ├── daily-rules.md          # 日报生成规则
    ├── terms/                  # 岗位术语词库
    │   ├── ai-trends.md        # AI & 互联网热词
    │   ├── pm.md / ops.md / tech.md / data.md ...
    └── scenes/                 # 场景表达词库
        ├── email.md / meeting.md / presentation.md ...
```

> `subscriptions.json` 和 `sent-log.json` 是本地运行数据，已通过 `.gitignore` 排除。

---

## 📦 安装

将 `internet-business-english/` 目录放入你的 Agent skills 目录，指向 `SKILL.md` 即可。例如：

```bash
# CatDesk / CatPaw
~/.catpaw/skills/internet-business-english/

# 或任何你的 Agent 支持的路径
/path/to/your/skills/internet-business-english/
```

---

## 🌟 设计理念

**词库轮转** — 高频通用词（DAU、MAU、GMV、ROI 等）每两周最多出现一次，保证每天都在学新东西。

**间隔重复** — 每 5~7 天会重新出现 2~3 个之前推送过的术语，但例句不同，帮助巩固记忆。

**场景深度** — 晋升答辩、述职汇报等关键场景提供完整示例脚本，区分初级表达和高级表达。

---

<div align="center">

[MIT License](./LICENSE) · 自由使用 / 修改 / 再分发

</div>
