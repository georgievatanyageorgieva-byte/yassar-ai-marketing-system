---
name: lead-magnet-ads
description: >
  Writes ad copy, Gemini visual prompts, and video scripts for a lead magnet campaign.
  Three outputs in one skill. Reads brand-dna.md and lead-magnet-concept.md.
  Always starts from the hook. Part of Lead Magnet campaign chain.
---

# Lead Magnet Ads — Copy + Visuals + Video Scripts

Three outputs: ad copy that stops the scroll, Gemini prompts for visuals, and video scripts for the camera. All around the same hook.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → avatar, pain, voice, proof.
Load `lead-magnet-concept.md` → title, format, core promise.
If missing → name which file and stop.

## STEP 2 — HOOK FIRST

Generate 8 hooks:
- 2 pain hooks
- 2 curiosity hooks  
- 2 result hooks
- 2 belief-shifting (contrarian)

User picks 3 → all three parts built around those hooks.

## PART A — AD COPY (6 variations)

**Short ads (3) — for feed, one per chosen hook:**
Hook → One-line promise → "Безплатно — [CTA with link]"
Max 5 lines. Punchy. Direct.

**Long ads (3) — for cold audience:**
Hook → Avatar pain in their language → What's inside the lead magnet → Who it's for → "Безплатно: [LINK]"

**Belief-shifting bonus (1):**
Challenge the #1 reason they wouldn't download this → reframe → offer

**Ad rules:**
- "Безплатно" appears in every ad
- CTA: "Изтегли безплатно" or "Вземи безплатния [format]"
- No emojis in first line
- Never use "Click here" or "Learn more"

## PART B — GEMINI VISUAL PROMPTS (3)

**Prompt 1 — With photo (universal, warm)**
```
Create a clean square (1080x1080px) Facebook ad.
LAYOUT: Top 25%: bold hook text. Middle 45%: professional photo of [host - describe from brand-dna]. Bottom 30%: lead magnet mockup image + "БЕЗПЛАТНО" badge + CTA button.
COLORS: [suggest 3 based on niche].
STYLE: Warm, professional, trustworthy. White background. High contrast text.
TEXT ELEMENTS: Hook line / "Безплатно" / Lead magnet title / CTA button text.
```

**Prompt 2 — Lead magnet mockup (no photo)**
```
Create a square (1080x1080px) ad showing a [checklist/guide/template] mockup.
Show the resource as a physical document/screen. Make it look tangible and desirable.
Include: title text overlay, "БЕЗПЛАТНО" badge, minimal background.
COLORS: [brand colors from brand-dna].
```

**Prompt 3 — Text-only creative (scroll-stopper)**
Bold typography, single hook line, high contrast.
No images — just text that hits hard.

## PART C — VIDEO SCRIPTS (2)

**Script 1 — 30-45 seconds (Reels/Facebook)**
```
[0-3s] Say the hook directly to camera. No intro.
[3-12s] "Ако си [avatar situation]..." — mirror their problem
[12-22s] "Направих [format name] с [specific thing inside]"
[22-30s] "Безплатно — линкът е в коментарите/bio"
```

**Script 2 — 60-90 seconds (Facebook video ad)**
Hook → Their problem → What's inside the lead magnet (show it if possible) → Who it's for → CTA

**Video rules:**
- Hook delivered in first 3 seconds, no greeting
- Works with sound OFF (text on screen for key moments)
- Include [SHOW SCREEN/DOCUMENT] markers where to display the lead magnet
- CTA: "Линкът е в коментарите" not "link in bio" for Facebook

## OUTPUT
Save as `lead-magnet-ads.md`. Then suggest:
> "Рекламите са готови. Следваща стъпка:
> `/quality-check` — провери hook-овете преди пускане
> `/cover-photo` — корица за Facebook групата"
