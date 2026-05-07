---
name: cover-photo
description: >
  Generates a complete Gemini prompt for a Facebook GROUP cover photo.
  Outputs a ready-to-paste prompt. Reads brand-dna.md for colors and voice.
  Uses the proven cover photo framework (940x348px, 3-zone layout).
---

# Facebook Group Cover Photo Generator

You generate a complete, ready-to-paste Gemini prompt for a professional Facebook group cover photo. The user takes this prompt and pastes it directly into Gemini Image or ChatGPT to generate the image.

## STEP 1 — LOAD CONTEXT

Load `brand-dna.md` → name, niche, avatar, offer/lead magnet name, voice.
If not found → ask for minimum context: name, group name, what the group is for.

## STEP 2 — COLLECT SPECIFICS (one question at a time)

**Q1:** "Как се казва Facebook групата?"

**Q2:** "Кой е идеалният член на групата? (за кого е групата — в 1 изречение)"

**Q3:** "Имаш ли лийд магнит или безплатен ресурс, показан на корицата? Ако да — как се казва?"

**Q4:** "Какви са цветовете на бранда ти? (или предложи ти)"
If they don't know → suggest based on niche: "За коучинг/бизнес обикновено работи добре тъмно синьо + злато или тъмно зелено + бяло. Кое предпочиташ?"

**Q5:** "Опиши снимката ти, която ще бъде използвана: как изглеждаш, какво си облечен, какво е изражението. (Тя ще се постави в ляво без никакви промени.)"

## STEP 3 — GENERATE THE GEMINI PROMPT

Output a complete, ready-to-paste Gemini prompt using the proven 3-zone framework:

```
═══════════════════════════════════════════════
ГОТОВ ПРОМПТ ЗА GEMINI — КОПИРАЙ И ПОСТАВИ
═══════════════════════════════════════════════

You are an expert graphic designer. Create a professional Facebook group cover image with these EXACT specifications:

TECHNICAL: 940x348 pixels, high resolution, professional quality.

THREE-ZONE LAYOUT:

LEFT ZONE (0-280px):
- Expert's photo starting from the left edge
- Background completely removed (transparent cutout)
- Person visible from waist/chest up, head near top
- DO NOT modify the person in any way
- NO text or graphics overlapping the person

CENTER ZONE (280-650px):
- MAIN HEADLINE: "[GROUP NAME]"
  Font: Very large (48-60px), bold, [COLOR] on [BACKGROUND]
  Position: Upper third, approximately 50-70px from top
- SUB-HEADLINE: "За [AVATAR DESCRIPTION], които искат [DESIRED OUTCOME]"
  Font: Medium (18-24px), semi-transparent background bubble
  Position: Directly below headline
- EXPERT NAME: "[FULL NAME]" near bottom left

RIGHT ZONE (650-940px):
- 3D book/document mockup, slight angle (15-25 degrees)
- Size: approximately 220x280px
- Cover text on mockup:
  Line 1 (top): "БЕЗПЛАТНО"
  Line 2 (middle, large): "[LEAD MAGNET TITLE]"
  Line 3 (bottom): "[Short subtitle or benefit]"
- Subtle drop shadow for depth

COLOR PALETTE:
- Background: [MAIN COLOR]
- Headline text: [CONTRAST COLOR]
- Accent/buttons: [ACCENT COLOR]
- Book cover: White or light with [ACCENT] elements

STYLE: Professional, warm, trustworthy. Clean without being cold.
This is a COLOR photo — vibrant, not desaturated.
High contrast between text and background.
All text must be clearly readable on mobile.

DO NOT: Add filters, cartoonify, or distort the expert's photo.
DO: Make the book mockup look tangible and desirable.

═══════════════════════════════════════════════
```

After the prompt, add:
> "**Как да използваш:**
> 1. Копирай промпта горе
> 2. Отвори Gemini (gemini.google.com) или ChatGPT
> 3. Постави промпта + качи снимката си
> 4. Генерирай и изтегли
>
> **Ако резултатът не е идеален:** Кажи ми какво трябва да коригираме и ще обновя промпта."
