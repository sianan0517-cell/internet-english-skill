<div align="center">

[中文](./README.md) · **English**

# 🌐 Internet Business English Skill

#### A daily English digest for Chinese tech professionals — subscribe to your role channel and get a tailored lesson every day

[![License](https://img.shields.io/badge/License-MIT-3B82F6?style=for-the-badge)](./LICENSE)
[![Channels](https://img.shields.io/badge/Channels-16-10B981?style=for-the-badge)](#-channels)
[![Scenes](https://img.shields.io/badge/Scenes-10-F59E0B?style=for-the-badge)](#-scene-coverage)

![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-Skill-10B981?style=flat-square&logo=openai&logoColor=white)
![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-8B5CF6?style=flat-square)
![CatDesk](https://img.shields.io/badge/CatDesk-Skill-EC4899?style=flat-square)

</div>

Most business English courses teach generic phrases stripped of real context. This Skill is different — content is drawn from authentic workplace scenarios at Chinese tech companies, covering everything from daily emails to promotion reviews.

**Each daily digest includes:**
- **3 role-specific terms** — randomly drawn from your subscribed channel's vocabulary, with fresh example sentences every time
- **3 scene expressions** — practical phrases for the day's featured scenario
- **2 AI buzzwords** — dynamically generated based on the current date to stay relevant

---

## 📋 Channels

<a id="-channels"></a>

Subscribe to one or more channels:

| Channel | Role |
|---------|------|
| `pm` | Product Manager |
| `ops` | Operations (Growth / Campaign / User Ops) |
| `tech` | Engineering (Frontend / Backend / Algorithm) |
| `data` | Data (Analyst / Data Science) |
| `design` | UI/UX Design |
| `mkt` | Marketing |
| `hr` | Human Resources |
| `finance` | Finance |
| `mgmt` | Management / Upward Communication |
| `bd` | Business Development / Partnerships |
| `qa` | Quality Assurance / Testing |
| `content` | Content Operations |
| `growth` | User Growth / Growth Hacking |
| `legal` | Legal / Compliance |
| `supply` | Supply Chain / Procurement |
| `common` | General (suitable for everyone) |

---

## 🗓️ Scene Coverage

<a id="-scene-coverage"></a>

The daily digest rotates through featured scenes by day of the week:

| Day | Scene |
|-----|-------|
| Monday | ✉️ Business Email |
| Tuesday | 🎙️ Meeting & Speaking Up |
| Wednesday | 🔼 Upward Communication |
| Thursday | 📊 Performance Review / Reporting |
| Friday | ☕ Small Talk |
| Weekend | 🔁 Review & Recap |

**On-demand practice scenes:**
- 🎖️ Promotion Review — how to make your case in front of a panel
- 🌱 New Hire Icebreaker — first-week introductions and relationship building
- 💬 Feedback & Criticism — diplomatic phrasing and constructive delivery
- 🎯 Interview English — self-introduction, STAR method, questions to ask

---

## 🚀 How to Use

**Subscribe to a channel** — just tell the Agent your role:
```
I'm a product manager  →  subscribe to pm channel
I work in operations   →  subscribe to ops channel
I'm on the data team   →  subscribe to data channel
```

**Get today's digest:**
```
today's digest / send daily report / what do I learn today
```

**Practice a specific scene:**
```
help me prepare for my promotion review in English
teach me small talk
I want to practice upward communication
```

**Quiz mode:**
```
quiz me / test me on what I've learned
```

**Set up automatic daily delivery:**
Tell the Agent "send me the digest every morning at 9 AM" and it will configure a scheduled task using your platform's automation capability.

---

## 📁 File Structure

```
internet-business-english/
├── SKILL.md                    # Skill definition (Agent reads this)
├── README.md                   # Chinese README
├── README.en.md                # English README (this file)
├── .gitignore
└── references/
    ├── daily-rules.md          # Digest generation rules
    ├── terms/                  # Role-specific vocabulary
    │   ├── ai-trends.md        # AI & internet buzzwords
    │   ├── pm.md / ops.md / tech.md / data.md ...
    └── scenes/                 # Scene expression libraries
        ├── email.md / meeting.md / presentation.md ...
```

> `subscriptions.json` and `sent-log.json` are local runtime data files, excluded via `.gitignore`.

---

## 📦 Installation

Place the `internet-business-english/` directory in your Agent's skills folder and point it at `SKILL.md`. For example:

```bash
# CatDesk / CatPaw
~/.catpaw/skills/internet-business-english/

# Or any path your Agent supports
/path/to/your/skills/internet-business-english/
```

---

## 🌟 Design Principles

**Vocabulary rotation** — high-frequency terms (DAU, MAU, GMV, ROI, etc.) appear at most once every two weeks, so every day brings something new.

**Spaced repetition** — every 5–7 days, 2–3 previously seen terms reappear with different example sentences to reinforce retention.

**Scene depth** — high-stakes scenarios like promotion reviews and performance presentations include full example scripts, with clear contrast between basic and advanced phrasing.

---

<div align="center">

[MIT License](./LICENSE) · Free to use, modify, and redistribute

</div>
