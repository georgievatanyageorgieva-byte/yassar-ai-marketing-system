---
name: webinar-emails
description: >
  Writes all email sequences for a webinar campaign.
  Two sequences: pre-webinar (registrants) and post-webinar (attended/didn't attend).
  User picks which to generate. Reads brand-dna.md and webinar-concept.md.
---

# Webinar Email Sequences

You write emails that increase show-up rates and convert viewers into buyers — and re-engage those who missed the webinar.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → voice, avatar, proof, offer.
Load `webinar-concept.md` → topic, promise, date/time, offer details.
If missing → name which file and stop.

## STEP 2 — PICK SEQUENCE

> "Кой имейл тип искаш да генерирам?
> [A] Преди уебинара — за регистрирали се (4 имейла)
> [B] След уебинара — присъствали (3 имейла)
> [C] След уебинара — не присъствали (3 имейла)"

## SEQUENCE A — PRE-WEBINAR (4 emails)

**Email 1 — Confirmation (immediate)**
Subject: 3 hook options
Confirmed + what to prepare + what they'll leave with + calendar link

**Email 2 — 3 days before**
Subject: curiosity hook about the biggest insight
Tease the #1 thing they'll learn + why it matters specifically to them + link

**Email 3 — Day before**
Subject: "Утре [TIME] — ето как да се подготвиш"
Reminder + prep action + what to have ready + link

**Email 4 — Day of, 2 hours before**
Subject: "Започваме след 2 часа — [Hook from webinar topic]"
Last reminder + anticipation build + direct link

## SEQUENCE B — POST-WEBINAR, ATTENDED (3 emails)

**Email 1 — Same day, 2-3 hours after**
Subject: "Благодаря, че беше там — [key insight from today]"
Recap of biggest insight + the offer with deadline + Calendly CTA

**Email 2 — Day 2**
Subject: Addresses the #1 objection
Belief-shifting story or reframe + offer + deadline reminder

**Email 3 — Final day of offer**
Subject: "[NAME], последният ден"
Scarcity + recap of what they'll miss + final CTA

## SEQUENCE C — POST-WEBINAR, DIDN'T ATTEND (3 emails)

**Email 1 — Next morning**
Subject: "Пропусна [topic] — ето резюмето"
What was covered + key insight + offer if replay is available + Calendly link

**Email 2 — Day 3**
Subject: "[Result] без уебинара — ето как"
Alternative entry point to the same offer + no replay pressure

**Email 3 — Day 5**
Subject: Direct
One more chance to book a call. No elaborate story. Direct offer. Deadline.

## EMAIL RULES
- 3 subject line options per email
- No emojis in subject lines
- Max 300 words per email
- One CTA per email — always Calendly or registration link
- Bulgarian only

## OUTPUT
Save as `webinar-emails-[A/B/C].md`. Then suggest:
> "Имейлите са готови. Следваща стъпка:
> `/webinar-ads` — реклами за регистрации
> `/quality-check` — провери offer имейлите"
