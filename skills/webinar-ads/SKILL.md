---
name: webinar-ads
description: >
  Writes ad copy, Gemini visual prompts, and video scripts for a webinar campaign.
  Three outputs in one skill. Reads brand-dna.md and webinar-concept.md.
  Always starts from the hook. Adapted from adam-ad-optimisation and vex-viral-hooks.
---

# Webinar Ads — Copy + Visuals + Video Scripts

You create three things: ad copy that stops the scroll, Gemini prompts for the visuals, and video scripts for the camera. All built around the same hook.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → avatar, pain, proof, voice.
Load `webinar-concept.md` → topic, promise, date.
If missing → name which file and stop.

## STEP 2 — HOOK FIRST (always)

Generate 8 hook options before writing anything:
- 2 pain hooks
- 2 curiosity hooks
- 2 result hooks
- 2 belief-shifting hooks (contrarian angle)

User picks 3 → everything is built around those 3 hooks.

## PART A — AD COPY (6-8 text variations)

For each chosen hook, write 2 ad copy variations:

**VARIATION 1 — Short (3-5 lines)**
Hook → One-line promise → Date/time → CTA: "Запиши се безплатно [LINK]"

**VARIATION 2 — Long (8-12 lines)**
Hook → Pain description in their language → What they'll learn → Who it's for → Date → CTA

**Belief-shifting ads (2 additional):**
Open with a common belief in the niche → flip it → webinar as the proof → CTA

**Ad copy rules:**
- Never start with the webinar name
- No emojis in first line (kills reach on some placements)
- CTA is always "Запиши се безплатно" — never "Learn more" or "Click here"
- Include date and time in every ad

## PART B — VISUAL PROMPTS FOR GEMINI (3 prompts)

**Prompt 1 — Minimalist with photo (universal)**
Generate a complete Gemini/Midjourney prompt:
```
Create a clean square (1080x1080px) Facebook ad for a webinar.
LAYOUT: Top 20%: webinar title text. Middle 50%: professional photo of [host description from brand-dna].
Bottom 30%: date, time, "Безплатно", registration button.
COLOR PALETTE: [suggest 3 colors based on niche/topic].
STYLE: Minimalist, professional, warm. High contrast text. White or light background.
TEXT ON IMAGE: "[Webinar title]" / "[Date] [Time]" / "Запиши се безплатно"
```

**Prompt 2 — Bold text-focused (no photo)**
A creative ad built around the hook text, no face.

**Prompt 3 — Story/emotional (for Instagram Stories format)**
Vertical (1080x1920px), single emotion, single message.

## PART C — VIDEO SCRIPTS (2 scripts)

**Script 1 — Short (30-45 seconds, for Reels/TikTok/Facebook)**
```
[0-3s] HOOK: [Chosen hook — say it exactly]
[3-10s] PROBLEM: "Ако си [avatar situation]..."
[10-20s] PROMISE: "На [date] ще покажа как [specific result]"
[20-30s] CTA: "Линкът за регистрация е в коментарите/bio"
```

**Script 2 — Medium (60-90 seconds, for Facebook/YouTube)**
Hook → Pain story (their situation) → What the webinar covers → Who it's for → CTA with urgency

**Video script rules:**
- First 3 seconds must work without sound (text overlay on screen)
- Speak directly to camera — no reading from script
- Include [B-ROLL SUGGESTION] for any moment that can be visualized
- End with verbal CTA + point to link in comments

## OUTPUT
Save as `webinar-ads.md` with all three parts clearly labeled. Then suggest:
> "Рекламите са готови. Следваща стъпка:
> `/quality-check` — провери hook-овете преди пускане
> `/webinar-emails` — имейли за регистрираните"
