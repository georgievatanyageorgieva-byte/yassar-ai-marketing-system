---
name: challenge-emails
description: >
  Writes all email sequences for a challenge campaign.
  Six sequence types: registered participants, not-registered (cold),
  VIP onboarding, bump offer buyers, scarcity (last chance),
  and daily reminders during the challenge.
  Reads brand-dna.md and challenge-concept.md.
---

# Challenge Email Sequences

You write emails that people actually open and act on — not because they're clever, but because they arrive at the right moment with the right message.

---

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → voice, avatar, proof, transformation story.
Load `challenge-concept.md` → challenge name, dates, daily arc, VIP offer, bump offer, scarcity.

If either file is missing → name which file is missing and stop.

Extract and confirm:
- Challenge name + start date
- Number of days
- Daily session time
- VIP price + what VIP includes
- Order bump name + price (if exists)
- Scarcity mechanism (real seats limit / date cutoff)
- Viber/Facebook group links

---

## STEP 2 — PICK SEQUENCE

Ask:
> "Кой тип имейли искаш да генерирам?
>
> [A] Записали се — welcome, дневни имейли, offer close (7-10 имейла)
> [B] Не записали се — промо последователност за студена аудитория (4-8 имейла)
> [C] VIP — потвърждение + ексклузивно съдържание (5-7 имейла)
> [D] Bump offer — имейли за купилите order bump (3-5 имейла)
> [E] Scarcity — последен шанс имейли (2 имейла)
> [F] Ежедневни reminders — по 1 имейл на ден по време на challenge-а (1 на ден × [N] дни)
>
> Или напиши 'всички' за пълния пакет."

---

## SEQUENCE A — REGISTERED (7-10 emails)

Participants who signed up for the free challenge.

**Email 1 — Welcome (sent immediately after registration)**
- Subject: 3 hook options (confirm + excite + one action)
- Body: Registration confirmed → what to expect each day → how to prepare → community link (Viber/Facebook) → one action to take right now
- CTA: Join the Viber/Facebook group
- Tone: Warm, energetic, zero fluff

**Email 2 — Day before challenge starts**
- Subject: "Утре започваме — ето какво да направиш сега"
- Body: Recap of what's coming → one preparation action → what Day 1 holds → build anticipation
- CTA: Join the group (again, for those who missed it)

**Emails 3-[N+1] — Daily challenge emails (one per day, sent morning of each day)**
Each email:
- Subject: Curiosity hook about that day's content
- Body: Day title + key insight teaser (not the full content — make them show up) + session link/time + one reflection question
- CTA: "Виж го на живо в [TIME]" or group link
- Length: Under 150 words — short and punchy

**Email [N+2] — Final day + offer bridge**
- Subject: Curiosity about what comes next (NOT "Последен шанс")
- Body: Recap of transformation → acknowledge the work they've done → natural bridge to the offer (what's the logical next step?) → soft pitch → CTA (sales call / application link)
- Tone: Mentor, not salesperson

**Email [N+3] — Post-challenge follow-up (24h after final day)**
For those who didn't take the offer during the challenge:
- Subject: "Предизвикателството свърши, но трансформацията не трябва"
- Body: Acknowledge what they learned → what's still missing (without the program) → direct offer → deadline
- CTA: Sales call link / application

---

## SEQUENCE B — NOT REGISTERED (4-8 emails, 10-14 days before challenge)

Cold audience who hasn't signed up yet.

**Email 1 — Awareness (10-14 days before)**
- Subject: Pain hook — their problem, specific
- Body: "Ако [PAIN SITUATION]... имам нещо за теб." → Challenge announcement → what they'll get in [N] days → free registration link
- CTA: Register (free)

**Email 2 — Social proof (7-10 days before)**
- Subject: Result-focused — specific numbers or timeframe
- Body: Short case study or your own result → "Ето защо правя това предизвикателство" → link
- CTA: Register (free)

**Email 3 — Belief shift (5-7 days before)**
- Subject: Counterintuitive claim or common mistake
- Body: Address the #1 reason they haven't signed up → myth-bust it → reframe → "Ето защо трябва да дойдеш"
- CTA: Register (free)

**Email 4 — Urgency (2-3 days before)**
- Subject: Real scarcity — spots filling / days remaining
- Body: "[N] места останали" or "[X] дни до старта" → what they'll miss if they don't join → fast registration
- CTA: Register NOW (free)

**Emails 5-8 — Optional angles:**
- Email 5: Story angle (your personal story connecting to the challenge topic)
- Email 6: FAQ (answers the top 3 "but..." objections)
- Email 7: Direct angle ("Кажи ми ако не искаш повече имейли — иначе се виждаме на [DATE]")
- Email 8: Last call (day before — 5 sentences max)

---

## SEQUENCE C — VIP (5-7 emails)

People who purchased VIP access.

**Email 1 — VIP confirmation (card payment — sent immediately)**
- Subject: "✅ Добре дошъл в VIP — ето следващата ти стъпка"
- Body: Payment confirmed → full VIP benefits list → what to expect each day → VIP Viber group link → what to prepare
- CTA: Join VIP Viber group immediately

**Email 2 — VIP confirmation (bank transfer — sent immediately)**
- Subject: "Поръчката е получена — изчакваме превода"
- Body: Order received → bank transfer details (IBAN, reference, amount, 48h deadline) → what they're getting → FREE Viber group in the meantime → "Веднага след потвърждение ще получиш VIP достъп"
- CTA: Join free group + complete the transfer

**Email 3 — VIP Day before (exclusive prep)**
- Subject: "Само за VIP: ето как да се подготвиш за утре"
- Body: Tomorrow's VIP-exclusive session time → what to prepare → what to bring/have ready → "Ако имаш въпроси преди старта, отговори на този имейл"
- CTA: VIP Viber group

**Emails 4-5 — VIP-exclusive during challenge**
Each day (or every 2 days): deeper insight from that day + bonus material + 1:1 prep instructions
- Subject: "VIP само: [Day N] бонус материал"
- Body: Exclusive insight tied to that day's content → bonus resource or exercise → reminder of VIP session time/link
- CTA: VIP Viber / direct reply

**Email 6-7 (optional) — Post-challenge VIP follow-up**
After challenge ends: what's the next step in working together? Soft pitch for main offer with VIP-specific framing ("Ти вече знаеш системата — следващата стъпка е да я приложиш с мен лично").

---

## SEQUENCE D — BUMP OFFER (3-5 emails)

People who purchased the order bump during checkout (the €3-€8 micro-product).

**Email 1 — Bump confirmation (sent immediately)**
- Subject: "Ето твоят [BUMP NAME] — изтегли го сега"
- Body: Confirmation → download link or access instructions → one quick win they can get from it → reminder of VIP upgrade (if they didn't take VIP)
- CTA: Download / access link

**Email 2 — Day 2: How to use it**
- Subject: "Как да получиш максимума от [BUMP NAME]"
- Body: The #1 mistake people make with this resource → how to actually use it → connect it to what they're learning in the challenge
- CTA: Quick action they can take today

**Email 3 — Midpoint: Check-in**
- Subject: "[NAME], как вървят нещата?"
- Body: Reference the bump material → ask how it's going → bridge to VIP or main offer if they haven't taken it
- CTA: Reply with update OR upgrade to VIP

**Emails 4-5 (optional) — Post-challenge: upgrade path**
- Email 4: "Готов ли си за следващото ниво?" — soft pitch for VIP or main offer
- Email 5: Final offer with deadline

---

## SEQUENCE E — SCARCITY (2 emails)

Last-chance emails sent at the end of the challenge (or during final day).

**Email 1 — 24h warning (sent Day N, morning)**
- Subject: "[N] часа остават — след това [CONSEQUENCE]"
- Body: The challenge ends tonight → what happens to the offer after → why waiting costs them → what they get if they act now
- CTA: Register for offer / sales call link
- **Scarcity must be REAL** — only use if seats actually fill, price actually increases, or deadline is hard

**Email 2 — Final call (sent Day N, 2-3h before close)**
- Subject: "Затваряме в [TIME] — последен шанс"
- Body: 5 sentences max. The door closes. Here's the link. Here's what they get. P.S.: "Ако имаш въпрос — отговори СЕГА и ще ти отговоря лично."
- CTA: Offer link — single, bold, clear
- Length: Under 150 words. No stories. No fluff.

**RULE:** Never fabricate scarcity. If there's no real limit, don't send these emails.

---

## SEQUENCE F — DAILY REMINDERS (1 email per day × challenge duration)

Reminder emails sent 1-2 hours before each day's live session.

**Format for each reminder:**

```
REMINDER — ДЕН [N]: [DAY TITLE]

Subject options:
A) "Днес в [TIME]: [KEY TOPIC/TEASE]"
B) "[DAY TITLE] — започваме в [TIME]"
C) "[HOOK QUESTION] — отговорът е днес в [TIME]"

Body:
- 3-5 sentences max
- What they'll get TODAY (specific, not generic)
- Time + platform (Zoom/Viber/Facebook Live)
- One reason NOT to miss it (consequence or exclusive element)

CTA: [SESSION LINK]
```

Build one reminder per day (N = number of challenge days).
Each reminder should reference THAT day's topic (use `challenge-days.md` or `challenge-concept.md` daily arc).

**Note:** If `challenge-days.md` doesn't exist yet, generate placeholder reminders and note "Update with exact day topic when challenge-days.md is complete."

---

## EMAIL RULES (all sequences)

- Subject lines: 3 options per email (curiosity / benefit / direct)
- No emojis in subject lines (spam risk)
- Facebook posts and email body: emojis OK
- Every email has ONE CTA
- CTA is always a link (Calendly / registration / group / download) — never "write to me on Messenger"
- Keep under 300 words per email (except Sequence A Email [N+2] offer bridge: up to 450 words)
- Bulgarian only
- Write in the coach's voice (from brand-dna.md) — not corporate, not generic

---

## OUTPUT

Save each sequence as a separate file:
- `challenge-emails-a-registered.md`
- `challenge-emails-b-not-registered.md`
- `challenge-emails-c-vip.md`
- `challenge-emails-d-bump.md`
- `challenge-emails-e-scarcity.md`
- `challenge-emails-f-reminders.md`

---

## STEP 3 — DELIVERY

After generating the requested sequence(s):

> "Имейлите са готови. Следваща стъпка:
> [A] `/challenge-days` — структура на дневното съдържание (нужна за F reminders)
> [B] `/challenge-script` — offer close скрипт за финалния ден
> [C] `/quality-check` — провери имейлите преди изпращане
> [D] Готово"
