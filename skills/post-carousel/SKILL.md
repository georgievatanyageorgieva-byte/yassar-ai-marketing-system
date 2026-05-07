---
name: post-carousel
description: >
  Transforms any long post into Instagram/Facebook carousel prompts for Gemini/DALL-E.
  Analyzes post into semantic blocks, maps to cards (3-10), generates one prompt per card.
  Confirms structure before creating. Content fidelity — never adds information not in the original post.
---

# Carousel Creator

Трансформираш дълъг пост в carousel от промпти за Gemini/ChatGPT/DALL-E.

**Принцип:** Запазваш ЦЕЛИЯ оригинален текст. Не добавяш информация. Не опростяваш.

---

## STEP 1 — GET THE POST

"Постави поста, който искаш да превърнеш в carousel."

Ако нямат пост: "Искаш ли да генерирам пост първо? (/post-belief / /post-social-proof / /post-offer)"

---

## STEP 2 — CLARIFY PLATFORM & COLORS

Задай едновременно:
- "Платформа: Instagram Feed или Facebook Feed? (default: Instagram)"
- "Цветова палитра? (постави HEX кодове или напиши 'предложи ти')"

Ако трябва да предложиш — предложи 4 цвята подходящи за нишата с обяснение.

---

## STEP 3 — ANALYZE & PROPOSE STRUCTURE

Прочети поста и раздели на **смислови блокове**:

```
СМИСЛОВИ БЛОКОВЕ:

БЛОК 1: [Тип — Hook/Теза/Аргумент/Пример/Стъпка/Заключение/CTA]
Оригинален текст: "[Точен текст]"
Плътност: [Лека (1-2 реда) / Средна (2-4 реда) / Плътна (4+ реда)]
→ Картиране: КАРТА [X]

[Повтори за всички блокове]
```

**Правила за картиране:**
- Лека плътност → комбинирай с друг блок в 1 карта
- Средна → 1 карта
- Плътна → 1-2 карти

**Брой карти:**
- Минимум: 3 (hook + съдържание + CTA)
- Оптимум: 5-8
- Максимум: 10 (Instagram лимит)

Представи структурата и **изчакай потвърждение:**
> "Одобряваш ли тази структура? Ако ДА → 'да'. Ако НЕ → кажи какво да коригирам."

---

## STEP 4 — CREATE PROMPTS ONE BY ONE

За всяка карта след потвърждение:

### КАРТА 1 — HOOK

```
Create a square (1:1 ratio, 1080x1080px) Instagram carousel card - CARD 1 of [X] (HOOK).

CARD ROLE: Hook - stop the scroll, create desire to swipe

LAYOUT:
Top section (30%): [Визуален елемент или акцент]
Middle section (50%): Main headline
Bottom section (20%): Card number + supporting element

TEXT ELEMENTS:

Headline:
- Text: "[Точен текст от блока — без съкращаване]"
- Size: Large (48-60px)
- Weight: Bold
- Color: [HEX]
- Position: Center
- Alignment: Left or Center
- Max lines: 3

Card number:
- Text: "1/[X]"
- Size: Small (14px)
- Color: [Muted HEX]
- Position: Bottom right

IMPORTANT: Display ALL text WITHOUT quotation marks in the final design.

STYLE: [Описание на визуалния стил — тъмен/светъл, минималистичен/bold]

COLORS:
Primary: [HEX]
Secondary: [HEX]
Accent: [HEX]
Text: [HEX]
Background: [HEX]

VISUAL ELEMENTS: [Описание на графични елементи ако има]

MOOD: Stopping the scroll — bold, clear, intriguing

SPECIAL NOTES:
- Must create desire to swipe
- All text from original post preserved
- No added information
- Mobile-readable (min 18px body text)

Image: 1080x1080px, Instagram Feed carousel, high quality
```

**Покажи ASCII визуализация:**
```
┌─────────────────────────────────┐
│                                 │
│  [HEADLINE LINE 1]              │
│  [HEADLINE LINE 2]              │
│                                 │
│  [Supporting text if any]       │
│                                 │
│                            1/X  │
└─────────────────────────────────┘
```

**СПРИ и изчакай:**
> "Одобряваш ли КАРТА 1 (Hook)? Да / Не + корекция"

---

### КАРТИ 2 до X-1 — DEVELOPMENT

```
Create a square (1:1 ratio, 1080x1080px) Instagram carousel card - CARD [X] of [Y] ([РОЛЯ]).

CARD ROLE: [Development/Context/Argument/Example/Step] - [описание]

LAYOUT:
[Адаптирана за ролята]

TEXT ELEMENTS:

Headline:
- Text: "[Точен текст от блока — ЦЕЛИЯТ текст]"
- Size: Medium-Large (32-40px)
- Weight: Bold
- Color: [HEX]

Body text:
- Text: "[Пълният текст от блока — НЕ съкращавай]"
- Size: Medium (18-22px)
- Weight: Regular
- Color: [HEX]
- Line height: 1.5
- Max lines: [Брой редове нужни за ЦЕЛИЯ текст]

Card number: "[X/Y]" - Bottom right - Small

IMPORTANT: 
- Display ALL text WITHOUT quotation marks
- Preserve ALL text from original block — no abbreviations
- Do NOT add information not in the original post

STYLE: [Consistent с Карта 1, controlled variation]

COLORS: [Същата палитра]

DESIGN CONSISTENCY:
- Same typography as Card 1
- Same color palette
- Same spacing rules
- Variation: [какво е различно за тази карта]

MOOD: [Consistent с общия тон]

Image: 1080x1080px, high quality
```

**ASCII визуализация + изчакай потвърждение след всяка карта.**

---

### ПОСЛЕДНА КАРТА — CTA

```
Create a square (1:1 ratio, 1080x1080px) Instagram carousel card - CARD [X] of [X] (FINAL - CTA).

CARD ROLE: CTA - convert attention into action

TEXT ELEMENTS:

CTA Headline:
- Text: "[Призив за действие]"
- Size: Large, bold
- Color: [Accent HEX]

CTA Action:
- Text: "[Конкретно действие — Save/Comment/DM/Link in bio]"
- Style: Button or prominent text
- Color: [Contrast HEX]
- Position: Center-bottom

Supporting text (optional):
- Text: "[Допълнителна мотивация]"
- Size: Small-Medium

Card number: "[X/X]" - Bottom right

CTA TYPES:
- Save: "Запази за по-късно"
- Comment: "Напиши в коментарите"
- DM: "Пиши ми в директни"
- External: "Линк в био"

MOOD: Clear, action-oriented, motivating

Image: 1080x1080px, high quality
```

---

## STEP 5 — FINAL SUMMARY

```
✅ CAROUSEL ЗАВЪРШЕН!

X карти:
КАРТА 1: Hook — [описание]
КАРТА 2: [Роля] — [описание]
...
КАРТА X: CTA — [описание]

ПРОВЕРКА:
✅ Platform: 1:1, 1080x1080px
✅ Content fidelity: Целият оригинален текст запазен
✅ No added information
✅ Visual consistency
✅ CTA card present

Промптите са готови за Gemini / ChatGPT / DALL-E / Midjourney
```

---

## CONTENT FIDELITY RULES (КРИТИЧНО ВАЖНО)

❌ НЕ добавяй факти, примери или твърдения извън оригиналния пост
❌ НЕ опростявай терминологията
❌ НЕ преформулирай по начин, който мени смисъла
❌ Ако липсва информация за карта → маркирай [MISSING INFO] и питай

✅ Използвай САМО информация от оригиналния пост
✅ Запазвай ЦЕЛИЯ текст — не съкращавай без одобрение
✅ Запазвай точни числа, имена, терминология

---

Пиши само на БЪЛГАРСКИ в комуникацията. Промптите за изображения са на АНГЛИЙСКИ.
