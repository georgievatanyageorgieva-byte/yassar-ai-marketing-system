---
name: ads
description: >
  Standalone ads skill. Writes scroll-stopping ad copy, Gemini visual prompts,
  and video scripts for ANY offer or promotion. Not tied to a specific campaign.
  Reads brand-dna.md. Three outputs in one skill. Always starts from the hook.
---

# Ads — Copy + Visuals + Video Scripts

Three outputs built around one hook: ad copy that stops the scroll, Gemini prompts for visuals, and video scripts for the camera.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → avatar, pain, voice, proof, offer.
If not found → ask for minimum context: who they are, who they help, what they're promoting.

## STEP 2 — CLARIFY THE PROMOTION

Ask ONE question: "Какво рекламираш? (безплатен лийд магнит, уебинар, предизвикателство, платена програма — и как се казва?)"

Then ask: "Кой е резултатът, който получават? (в 1-2 изречения)"

## STEP 3 — HOOK FIRST

Generate 8 hooks for this specific promotion:
- 2 pain hooks (they recognize themselves immediately)
- 2 curiosity hooks (they need to know more)
- 2 result hooks (someone got a specific outcome)
- 2 belief-shifting (challenge what they think they know)

User picks 3 → all three parts built around those hooks.

## PART A — AD COPY (6 variations)

**Short ads (3) — for feed, one per chosen hook:**
Hook → One-line promise → CTA
Max 5 lines. Punchy. Direct.

**Long ads (3) — for cold audience:**
Hook → Avatar pain in their language → What they get → Who it's for → CTA

**Belief-shifting bonus (1):**
Challenge the #1 reason they wouldn't click → reframe → offer

**Ad rules:**
- No emojis in first line
- CTA adapts to what's being promoted:
  - Free offer: "Вземи безплатно" / "Изтегли безплатно"
  - Webinar/challenge: "Регистрирай се безплатно" / "Запази място"
  - Paid offer: "Разгледай програмата" / "Кандидатствай сега"
- Never use "Click here" or "Learn more"
- Every ad must shift at least one belief

## PART B — GEMINI VISUAL PROMPTS (3)

**Prompt 1 — With photo (universal, warm)**
```
Create a clean square (1080x1080px) Facebook ad.
LAYOUT: Top 25%: bold hook text. Middle 45%: professional photo of [host — describe from brand-dna]. Bottom 30%: offer name + CTA button.
COLORS: [suggest 3 based on niche and brand-dna voice].
STYLE: Warm, professional, trustworthy. White background. High contrast text.
TEXT ELEMENTS: Hook line / Offer name / CTA button text.
```

**Prompt 2 — Offer visual (no photo)**
```
Create a square (1080x1080px) ad showcasing [the offer].
Show the offer as a tangible result — [book mockup / checklist / event banner / program card].
Include: offer name text overlay, benefit statement, minimal background.
COLORS: [brand colors from brand-dna].
STYLE: Clean, professional, high contrast.
```

**Prompt 3 — Text-only scroll-stopper**
```
Create a square (1080x1080px) ad with bold typography only.
Single hook line in very large font (60-80px), centered.
High contrast: dark background / white text OR white background / dark text.
No photos, no decorative elements — just the words hitting hard.
Font: Modern sans-serif, bold weight.
```

## PART C — VIDEO SCRIPTS (2)

**Script 1 — 30-45 seconds (Reels/Facebook feed)**
```
[0-3s] Say the hook directly to camera. No intro, no "Здравейте".
[3-12s] "Ако си [avatar situation]..." — mirror their problem exactly
[12-22s] "Направих/имам [offer name] — [what's inside in 1 sentence]"
[22-35s] "Линкът е в коментарите / Регистрирай се / [CTA specific to offer]"
```

**Script 2 — 60-90 seconds (Facebook video ad)**
```
[0-5s] Hook — say it, don't explain it
[5-20s] Their problem → why it's costing them → what they've tried that doesn't work
[20-50s] What the offer is → what's inside → [SHOW SCREEN/DOCUMENT/SLIDES if possible]
[50-65s] Who it's for (specific) + who it's NOT for
[65-80s] CTA + where to find the link
```

**Video rules:**
- Hook delivered in first 3 seconds — no greeting
- Works with sound OFF (include text overlay notes in brackets)
- [SHOW SCREEN] markers where to display the offer
- CTA: "Линкът е в коментарите" for Facebook (not "link in bio")
- Include B-roll suggestions in [BRACKETS] for what to show on screen

## OUTPUT

After all three parts, suggest:
> "Рекламите са готови. Следваща стъпка:
> `/quality-check` — провери hook-овете преди пускане
> `/cover-photo` — корица за Facebook групата
> `/lead-magnet-concept` → `/lead-magnet-ads` ако рекламираш лийд магнит"
