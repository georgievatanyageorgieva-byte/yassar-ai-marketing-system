---
name: challenge-emails
description: >
  Writes all email sequences for a challenge campaign.
  Three sequences: registered participants, non-registered (cold), VIP.
  User picks which sequence to generate. Reads brand-dna.md and challenge-concept.md.
---

# Challenge Email Sequences

You write emails that people actually open and act on — not because they're clever, but because they arrive at the right moment with the right message.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → voice, avatar, proof.
Load `challenge-concept.md` → challenge name, days, daily arc, VIP details.
If missing → name which file and stop.

## STEP 2 — PICK SEQUENCE

Ask:
> "Кой имейл тип искаш да генерирам?
> [A] Записали се — welcome + nurture по време на предизвикателството (7-10 имейла)
> [B] Не записали се — промо последователност за студена аудитория (4-8 имейла)
> [C] VIP — потвърждение + ексклузивно съдържание (5-7 имейла)"

## SEQUENCE A — REGISTERED (7-10 emails)

**Email 1 — Welcome (sent immediately)**
Subject: 3 hook options
Body: Confirmation + what to expect + how to prepare + community link

**Email 2 — Day before challenge starts**
Subject: "Утре започваме — ето какво да направиш сега"
Body: Prep action + excitement build + what Day 1 holds

**Emails 3-[N+1] — Daily challenge emails (one per day)**
Each: Day title + key insight teaser + "Ето линка за днешното" + one question to reflect on

**Email [N+2] — Final day + offer**
Subject hook: curiosity about what comes next
Body: Recap of transformation → natural bridge to the offer → soft pitch → CTA (Calendly)

**Email [N+3] — Post-challenge follow-up (24h after)**
For those who didn't take the offer: "Предизвикателството свърши, но трансформацията не трябва"
Direct offer presentation + deadline

## SEQUENCE B — NOT REGISTERED (4-8 emails, 10-14 days before)

**Email 1 — Awareness**
Pain hook + challenge announcement + what they'll get

**Email 2 — Social proof**
Result from past participant or your own result + challenge link

**Email 3 — Belief shift**
Address the #1 reason they haven't signed up yet

**Email 4 — Urgency**
Spots filling / days remaining / what happens if they miss it

**Emails 5-8 (optional)** — Different angles: story, FAQ, direct, last chance

## SEQUENCE C — VIP (5-7 emails)

**Email 1 — VIP confirmation (card payment)**
Thank you + what VIP includes + what to expect + next step

**Email 2 — VIP confirmation (bank transfer)**
Same but payment-pending version + confirmation instructions

**Emails 3-5 — VIP-exclusive content**
Deeper insights, bonus access, 1:1 prep instructions

## EMAIL RULES
- Subject lines: 3 options per email (curiosity / benefit / direct)
- No emojis in subject lines (spam risk)
- Every email has ONE CTA
- CTA is always Calendly link or registration link — never "write to me"
- Keep under 300 words per email
- Bulgarian only

## OUTPUT
Save as `challenge-emails-[A/B/C].md`. Then suggest:
> "Имейлите са готови. Следваща стъпка:
> `/challenge-days` — структура на дневното съдържание
> `/quality-check` — провери имейлите преди изпращане"
