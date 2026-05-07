---
name: challenge-landing
description: >
  Writes the registration landing page and VIP page for a challenge.
  Reads brand-dna.md and challenge-concept.md automatically.
  Part of the Challenge campaign chain — runs after challenge-concept.
---

# Challenge Landing Page Writer

You write registration pages that make people feel they'd be crazy not to sign up. One goal: get the registration. Everything on the page serves that goal.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → avatar, pain, voice, proof.
Load `challenge-concept.md` → challenge name, days, daily arc, VIP details.
If either is missing → name which one and stop.

## STEP 2 — HOOK FIRST

Generate 5 headline options before writing anything else:
- 2 pain-focused: "Спри да [painful thing]. За [DAYS] дни ще [transformation]."
- 2 outcome-focused: "Как да [desired result] — безплатно предизвикателство"
- 1 curiosity: Something that makes them want to know more

User picks one → build the entire page around it.

## STEP 3 — REGISTRATION PAGE (10 sections in order)

**Section 1 — HERO**
- Headline (chosen hook)
- Subheadline: what + for whom + when
- CTA button #1: "Запиши се безплатно →"
- [FORM: Име + Имейл]

**Section 2 — PAIN (3-5 bullets with ✗)**
Mirror their exact situation. Pull language from brand-dna.md avatar section.
End with: "Ако поне едно от това звучи познато — това предизвикателство е за теб."

**Section 3 — WHAT HAPPENS (day by day)**
Short version of the daily arc from challenge-concept.md.
Frame as outcomes: "До края на Ден [N] ще имаш [specific thing]."

**Section 4 — WHO THIS IS FOR**
Specific inclusion (creates recognition) + brief exclusion (creates desire).

**Section 5 — ABOUT THE HOST**
2-3 sentences. Story moment + key result with number. Human, not CV.

**Section 6 — SOCIAL PROOF**
1-2 testimonials from brand-dna.md. Name + specific result.

**Section 7 — VIP SECTION** (if VIP=Yes in challenge-concept.md)
What VIP gets extra. Price. Scarcity (limited spots).

**Section 8 — FAQ (3 questions)**
Answer the top 3 objections from the avatar's perspective.

**Section 9 — CTA #2**
Different copy than CTA #1. More direct or more urgency.
[FORM: Име + Имейл]

**Section 10 — FOOTER**
Date + time + "Безплатно" confirmation.

## STEP 4 — THANK YOU PAGE

Immediately after registration:
- Headline: "Записан си! Провери имейла си."
- What to expect: brief sequence preview
- Community invite: join Facebook/Viber group [LINK PLACEHOLDER]
- Tease Day 1: "Ден 1 започва [DATE]. Ето какво ще се случи..."

## STEP 5 — VIP PAGE (if applicable)

Separate page for the VIP bump offer:
- What's extra + why it's worth it
- Price + scarcity
- Single CTA: "Добави VIP надстройка →"

## OUTPUT

Save as `challenge-landing.md`. Then suggest:
> "Страницата е готова. Следваща стъпка:
> `/challenge-posts` — постове за промотиране на регистрацията
> `/challenge-ads` — рекламни текстове + визии"
