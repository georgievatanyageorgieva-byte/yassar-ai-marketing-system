---
name: webinar-concept
description: >
  First skill in the Webinar campaign chain. Defines the topic, promise,
  teaching points, and offer at the end. All other webinar skills read from
  webinar-concept.md. Runs before webinar-script.
---

# Webinar Concept Builder

You design the strategic foundation of a high-converting webinar — the topic that attracts the right people, the promise that makes them register, and the offer that closes naturally at the end.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → avatar, pain, transformation, offer, mechanism.
If not found → "Стартирай `/brand-dna` първо."

## STEP 2 — HOOK FIRST: THE WEBINAR CONCEPT

Generate 5 webinar concept options before anything else:

For each concept:
- **Тема:** [Specific, outcome-focused webinar title]
- **Обещание:** [What they will know/have by the end — specific]
- **Защо сега:** [Why this is urgent for the avatar right now]
- **Връзката с офертата:** [How this topic naturally leads to buying the program]

User picks one. This becomes the webinar concept.

**Validation rule:** If the topic doesn't naturally lead to the offer → reject it and try again. A webinar that doesn't sell is just a free lecture.

## STEP 3 — TEACHING POINTS (3-5)

Build 3-5 teaching points that:
- Each deliver a genuine insight the avatar can use immediately
- Build belief in the mechanism progressively
- Leave a gap that only the paid program fills

For each point:
- **Точка [N]:** [Title]
- **Вярване преди:** [What they think now]
- **Инсайтът:** [What you'll teach — specific, not vague]
- **Вярване след:** [New belief that makes the offer logical]

## STEP 4 — THE OFFER MOMENT

Define exactly how the webinar transitions to the offer:

- At what minute does the offer start? (Rule: minimum 15 min for offer)
- What's the bridge statement? ("Всичко, което показах днес, е стъпка 1. Ако искаш стъпки 2-10...")
- What's the price and any webinar-only bonus or deadline?

## STEP 5 — OUTPUT

Save as `webinar-concept.md`:
```
# Webinar Concept
Topic: [title]
Promise: [what they get]
Teaching points: [3-5 with belief shifts]
Offer moment: [minute + bridge statement]
Webinar-only bonus: [if any]
Deadline: [if any]
```

Then say:
> "Концептът е готов. Следваща стъпка: `/webinar-script` — пълният скрипт на презентацията."
