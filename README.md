# 🌐 Internet English Skill

A daily English learning assistant built for Chinese internet professionals. Subscribe to your role channel and receive a personalized English digest every day — covering industry jargon, workplace scenarios, and the latest AI buzzwords.

---

## What It Does

Most business English courses teach generic phrases that don't match real tech company life. This skill is different — it's built around the actual language used inside Chinese internet companies (Meituan, ByteDance, Alibaba, Tencent, etc.), covering everything from product reviews to promotion panels.

**Every daily digest includes:**
- **3 role-specific terms** — drawn from your subscribed channel's vocabulary bank, with fresh example sentences each time
- **3 scenario expressions** — practical phrases for that day's featured workplace scene
- **2 AI buzzwords** — current terms from the AI/tech industry

---

## Role Channels

Subscribe to one or more channels based on your job:

| Channel | Role |
|---------|------|
| `pm` | Product Manager |
| `ops` | Operations (Growth / Events / User Ops) |
| `tech` | Engineering (Frontend / Backend / Algorithm) |
| `data` | Data (Analyst / Data Scientist) |
| `design` | UI/UX Designer |
| `mkt` | Marketing |
| `hr` | Human Resources |
| `finance` | Finance |
| `mgmt` | Management / Managing Up |
| `bd` | Business Development |
| `qa` | QA / Testing |
| `content` | Content Operations |
| `growth` | Growth Hacker |
| `legal` | Legal / Compliance |
| `supply` | Supply Chain / Procurement |
| `common` | General (works for everyone) |

---

## Workplace Scenarios Covered

The digest rotates through 8 core scenarios across the week:

| Day | Scene |
|-----|-------|
| Monday | ✉️ Business Email |
| Tuesday | 🎙️ Meeting Expressions |
| Wednesday | 🔼 Managing Up |
| Thursday | 📊 Performance Review / Appraisal |
| Friday | ☕ Small Talk |
| Weekend | 🔁 Review & Recap |

**Additional on-demand scenarios:**
- 🎖️ Promotion Panel — how to argue your case to a panel of evaluators
- 🌱 New Hire Icebreaker — first-week introductions and building relationships
- 💬 Giving & Receiving Feedback
- 🎯 Job Interview English

---

## How to Use

### Subscribe to a channel
Just tell the assistant your role:
```
I'm a product manager → subscribes to pm channel
I work in operations → subscribes to ops channel
I'm on the data team → subscribes to data channel
```

### Get today's digest
```
Send me today's digest
今天的日报
What should I learn today?
```

### Practice a specific scenario
```
Help me prepare for my promotion panel
I want to practice managing-up English
Teach me how to do small talk
```

### Quiz mode
```
Quiz me on what I've learned
出几道题考考我
```

### Set up daily auto-delivery
Tell the assistant: *"Send me the digest every morning at 9am"* — it will set up an automated daily push using your agent platform's scheduling feature.

---

## Content Design

**Vocabulary rotation** — Terms are drawn from role-specific banks with deduplication logic. High-frequency generic terms (DAU, MAU, GMV, ROI, etc.) appear at most once every two weeks so you're always learning something new.

**Spaced repetition** — Every 5–7 days, 2–3 previously seen terms reappear with new example sentences to reinforce memory.

**AI buzzwords** — Generated dynamically based on the current date, so the content stays relevant even without manual updates to the word bank.

**Scenario depth** — Key scenes like Promotion Panel and Performance Review include full example scripts, common evaluator questions, and the difference between a weak answer and a strong one.

---

## File Structure

```
internet-english/
├── SKILL.md                    # Skill definition (read by your AI agent)
├── README.md                   # This file
├── .gitignore
└── references/
    ├── daily-rules.md          # Digest generation rules
    ├── subscriptions.json      # User subscription state (local only, gitignored)
    ├── sent-log.json           # Term history for deduplication (local only, gitignored)
    ├── terms/                  # Role vocabulary banks
    │   ├── ai-trends.md        # AI & internet buzzwords
    │   ├── pm.md               # Product Manager
    │   ├── ops.md              # Operations
    │   ├── tech.md             # Engineering
    │   ├── data.md             # Data
    │   ├── design.md           # Design
    │   ├── mkt.md              # Marketing
    │   ├── hr.md               # HR
    │   ├── finance.md          # Finance
    │   ├── mgmt.md             # Management
    │   ├── bd.md               # Business Development
    │   ├── qa.md               # QA
    │   ├── content.md          # Content Ops
    │   ├── growth.md           # Growth
    │   ├── legal.md            # Legal
    │   ├── supply.md           # Supply Chain
    │   └── common.md           # General workplace terms
    └── scenes/                 # Scenario expression banks
        ├── email.md            # Business Email
        ├── meeting.md          # Meeting Expressions
        ├── presentation.md     # Performance Review
        ├── promotion.md        # Promotion Panel
        ├── new-hire-icebreak.md # New Hire Icebreaker
        ├── managing-up.md      # Managing Up
        ├── feedback.md         # Feedback
        ├── small-talk.md       # Small Talk
        ├── interview.md        # Job Interview
        └── review.md           # Weekly Review
```

---

## Requirements

- Any AI agent that supports loading skills via `SKILL.md` (e.g. CatDesk, Claude Code, Cursor, OpenClaw, etc.)
- No API keys required
- Works out of the box after installation

---

## Installation

Place the `internet-english/` folder inside your agent's skills directory and point it to `SKILL.md`. For example:

```
# CatDesk / CatPaw
~/.catpaw/skills/internet-english/

# Or any custom path your agent supports
/path/to/your/skills/internet-english/
```

---

*Built for Chinese internet professionals who want real workplace English — not textbook English, but the language actually used in standups, PRDs, OKR reviews, and promotion panels.*
