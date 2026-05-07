---
name: webinar-landing
description: >
  Writes the webinar registration page. Reads brand-dna.md and
  webinar-concept.md automatically. One goal: get the registration.
  Part of the Webinar campaign chain — runs after webinar-concept.
---

# Webinar Landing Page Writer

You write registration pages that make the right person feel they can't afford to miss this. One objective: the registration. Everything else is removed.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → avatar, pain, voice, proof.
Load `webinar-concept.md` → topic, promise, teaching points, date/time.
If either missing → name which file and stop.

## STEP 2 — HOOK FIRST

Generate 5 headline options:
- 2 outcome: "Как да [specific result] — безплатен уебинар"
- 2 curiosity: "[Provocative question only you can answer]"
- 1 direct: "[Exact avatar] + [exact pain] + [exact promise]"

User picks one → build the page around it.

## STEP 3 — PAGE STRUCTURE

**HERO**
Headline (chosen hook)
Subheadline: topic + date + time + "Безплатно"
CTA #1: "Запиши се безплатно →" + [FORM: Име + Имейл]

**WHAT YOU'LL LEARN (3-5 bullets)**
Each from webinar-concept.md teaching points.
Framed as: "Ще разбереш защо [insight] — и как да го приложиш веднага"
Never reveal the full answer — create curious anticipation.

**WHO THIS IS FOR**
Specific recognition: "Това е за теб ако..."
3-4 exact avatar situations from brand-dna.md

**ABOUT THE HOST**
2 sentences. Transformation story moment + key result with number.

**SOCIAL PROOF**
1-2 results from brand-dna.md. Specific numbers.

**DATE + TIME + FORMAT**
Clear: "Живо в Zoom. [DATE] [TIME]. Безплатно."
Replay: "Ще има запис за 48 часа" (if applicable)

**CTA #2**
Different copy — more direct or deadline-focused.
[FORM: Име + Имейл]

**THANK YOU PAGE**
Confirmation + calendar invite instructions + community link + tease of what to prepare

## RULES
- Single objective: registration. No other links.
- No price mentioned (it's free — say it once clearly)
- CTA appears minimum twice with different copy
- Forms collect: Име + Имейл only — never phone number on cold traffic

## OUTPUT
Save as `webinar-landing.md`. Then suggest:
> "Страницата е готова. Следваща стъпка:
> `/webinar-emails` — имейл последователности
> `/webinar-ads` — реклами за регистрации"
