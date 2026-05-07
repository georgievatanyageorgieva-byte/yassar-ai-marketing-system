---
name: challenge-days
description: >
  Builds the detailed daily content structure for the challenge.
  What the coach teaches, delivers, and does each day.
  Reads challenge-concept.md for the arc. Output is the coach's daily guide.
---

# Challenge Daily Content Builder

You design what actually happens inside the challenge each day — the teaching, the activity, the energy, the transition to the next day. This is the coach's playbook.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → mechanism, voice, real results.
Load `challenge-concept.md` → daily arc, belief shifts per day, [DAYS].
If missing → name which file and stop.

## STEP 2 — ASK DELIVERY FORMAT

> "Jak ще доставяш предизвикателството?
> [A] Facebook Live / Zoom — живо всеки ден
> [B] Pre-recorded видео — записано предварително
> [C] Текстово съдържание — постове + PDF-и в група
> [D] Комбинация — кажи каква"

Format affects how daily content is structured.

## STEP 3 — BUILD EACH DAY

For each day, produce a complete daily guide:

---
**ДЕН [N]: [Day Title from challenge-concept.md]**

**Цел за деня:** [What shifts by end of day]

**Вярване преди:** "[Exact limiting belief from concept]"
**Вярване след:** "[New empowering belief]"

**OPENING HOOK (first 60 seconds):**
[Exactly what to say/show to grab attention immediately]

**MAIN TEACHING ([15-25 min]):**
- Key insight #1: [Specific idea + why it matters]
- Key insight #2: [Specific idea + example from their real client work]
- The mechanism moment: [Where you show your system/method in action]

**DAILY ACTION:**
> "Днешното предизвикателство: [Specific action completable in 30 min]"
Criteria for success: [How they know they did it right]

**COMMUNITY PROMPT:**
[Question to post in the group — drives engagement + algorithm]

**TRANSITION TO NEXT DAY:**
[Tease what's coming tomorrow — creates anticipation]

**For Day [DAYS] only — OFFER MOMENT:**
Natural bridge from the day's teaching to the offer:
[How the teaching leads directly to why they need the paid program]
Soft pitch → hard pitch → CTA → deadline

---

## RULES
- Every day must feel like a complete win on its own
- Day 1 delivers the fastest, most tangible insight (sets the tone)
- Day [DAYS] delivers the biggest insight — the offer is the obvious next step
- Never pitch on days 1 through [DAYS-1]
- Daily actions are specific and completable — not "reflect on your journey"

## OUTPUT
Save as `challenge-days.md`. Then suggest:
> "Дневното съдържание е готово. Следваща стъпка:
> `/challenge-emails` — имейли за участниците
> `/quality-check` — провери Day [DAYS] offer момента"
