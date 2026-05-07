# Yassar AI Marketing System

**Version:** 1.0.0 | **Author:** Yassar Markos | **Language:** Bulgarian

---

## What This Is

A complete AI-powered marketing toolkit built as installable Claude skills. Instead of one giant prompt, you get 23 focused skills organized into 3 campaign chains — each one doing exactly one job, starting from the hook.

**Two versions:**
- **Free** — Install skills in Claude Chat (Cowork). Run them one by one manually.
- **Paid (€39)** — Install in Claude Code. Skills can run in sequence and in parallel automatically.

---

## The One Rule: Brand DNA First

Before using any skill, you need your Brand DNA file. Everything else reads from it.

```
/brand-dna
```

This runs a guided intake (8 questions, one at a time) and saves `brand-dna.md` to your project folder. Every other skill picks this up automatically.

---

## How to Start

```
/start
```

The router loads your Brand DNA and shows you a menu. Pick what you want to build — it routes you to the right skill or campaign chain.

---

## The 3 Campaign Chains

### 🔴 Challenge Chain
For running a 3, 5, or 7-day challenge to attract leads and convert to your offer.

```
/challenge-concept     → Name, hook, [DAYS]-day arc, belief shifts per day
/challenge-landing     → Registration page + thank-you + VIP upsell page
/challenge-days        → Daily content structure (hook, teaching, action, community prompt)
/challenge-posts       → 5 Facebook posts to drive registrations
/challenge-emails      → 3 sequences: registered / not registered / VIP
/challenge-script      → Coming soon
```

**Start here:** `/challenge-concept` — saves `challenge-concept.md` which all other challenge skills read.

---

### 🔵 Webinar Chain
For a live or automated webinar that teaches and sells.

```
/webinar-concept       → Topic, hook, teaching points with belief shifts, offer moment
/webinar-script        → Full script: hook → rapport → teaching → transition → offer → Q&A
/webinar-landing       → Registration page + thank-you page
/webinar-emails        → 3 sequences: pre-webinar / attended / didn't attend
/webinar-ads           → Ad copy + Gemini visual prompts + video scripts
```

**Start here:** `/webinar-concept` — saves `webinar-concept.md` which all other webinar skills read.

---

### 🟢 Lead Magnet Chain
For a free resource that builds your email list and warms leads toward your offer.

```
/lead-magnet-concept   → Desire-first: what do they want badly enough to give their email?
/lead-magnet-content   → The actual resource (checklist, swipe file, mini-guide, template)
/lead-magnet-landing   → Opt-in page + thank-you page
/lead-magnet-posts     → 3-5 Facebook posts driving traffic to the opt-in page
/lead-magnet-emails    → 5-email nurture sequence (delivery → engagement → story → belief shift → invite)
/lead-magnet-ads       → Ad copy + Gemini visual prompts + video scripts
```

**Start here:** `/lead-magnet-concept` — saves `lead-magnet-concept.md` which all other lead magnet skills read.

---

## Standalone Tools

These work independently — no campaign chain required. They read `brand-dna.md` and ask what you need.

| Skill | What It Does |
|-------|-------------|
| `/ads` | Ad copy + Gemini visual prompts + video scripts for ANY promotion |
| `/cover-photo` | Generates a complete Gemini prompt for your Facebook GROUP cover (940x348px) |
| `/quality-check` | Frank Kern-style rating (0-10) with one fix at a time until 8+ |
| `/offer` | Diagnose or build your offer from scratch — 6 components |

---

## How Each Skill Works

Every content skill follows the same flow:

1. **Load Brand DNA** — reads `brand-dna.md` automatically
2. **Load campaign concept** — reads the relevant concept file (if in a chain)
3. **Hooks first** — generates 5-8 hooks before writing anything
4. **You pick** — choose 3 hooks to build around
5. **Full output** — complete content built around your chosen hooks

**Why hooks first?** Because the hook determines everything. A weak hook means no one reads the copy. A strong hook means even average copy converts.

---

## Installation

### Claude Chat (Free Version)
1. Copy the `skills/` folder to your computer
2. In Claude Chat, use the plugin/skill system to point to each SKILL.md file
3. Use skills one by one — type `/skill-name` to activate

### Claude Code (Paid Version — €39)
1. Copy the entire `yassar-ai-marketing-system/` folder to your project
2. Claude Code reads the `.claude-plugin/plugin.json` automatically
3. Type `/skill-name` in any conversation — skills are immediately available
4. Skills can run sequentially: finish one, start the next automatically
5. Campaign chains can run in parallel where skills don't depend on each other

---

## File Structure

```
yassar-ai-marketing-system/
├── .claude-plugin/
│   └── plugin.json              ← Package metadata (auto-loaded by Claude Code)
├── shared/
│   ├── brand-dna-template.md    ← Empty template (brand-dna skill fills this)
│   └── quality-rules.md         ← Rules all content skills follow
├── skills/
│   ├── start/                   ← Router — start here
│   ├── brand-dna/               ← Brand passport — run once
│   ├── offer/                   ← Offer diagnosis + build
│   ├── challenge-concept/
│   ├── challenge-landing/
│   ├── challenge-posts/
│   ├── challenge-emails/
│   ├── challenge-days/
│   ├── challenge-script/
│   ├── webinar-concept/
│   ├── webinar-script/
│   ├── webinar-landing/
│   ├── webinar-emails/
│   ├── webinar-ads/
│   ├── lead-magnet-concept/
│   ├── lead-magnet-content/
│   ├── lead-magnet-landing/
│   ├── lead-magnet-posts/
│   ├── lead-magnet-emails/
│   ├── lead-magnet-ads/
│   ├── ads/                     ← Standalone ads (any promotion)
│   ├── cover-photo/             ← Facebook group cover photo
│   └── quality-check/           ← Frank Kern quality gate
└── README.md
```

---

## The Content Rules (Applied in Every Skill)

- **Hook first, always** — no content without a hook selection
- **Bulgarian only** — all outputs in Bulgarian
- **No hashtags** in organic Facebook posts
- **No links in post body** — first comment only
- **No emojis in subject lines** — spam risk
- **One CTA per piece** — never multiple asks
- **Belief shifting** — every ad must challenge at least one limiting belief
- **"Безплатно" in every free offer ad** — explicit, not implied
- **Quality gate: 8/10 minimum** — use `/quality-check` before publishing

---

## The Recommended Order (First Time)

1. `/brand-dna` — your passport, run once
2. `/offer` — if you're not clear on your offer
3. Pick a campaign: `/challenge-concept`, `/webinar-concept`, or `/lead-magnet-concept`
4. Follow that chain to completion
5. `/quality-check` on anything before it goes live

---

## Support

Built by Yassar Markos for coaches and consultants who want a full marketing system without the guesswork.

Questions → yassarmarkoss@gmail.com
