# SUNNYCORE — Design Language Specification (Concrete Edition)

**Version:** 1.1  
**Goal:** An _instantly recognizable_ design movement: **extreme happiness + graphic punch**.  
**Recognition test:** If you screenshot any page/poster, it should scream **SUNNYCORE** even with the logo removed.

---

# 0) SUNNYCORE in 10 seconds (the recipe)

A SUNNYCORE composition must include **all** of these:

1. **Thick black outline** on key elements (3–5px)
2. **Ultra-saturated color blocks** (no muted palette)
3. **Sticker lift shadow** (specific shadow recipe below)
4. **Oversized headline font (Fredoka)**
5. **Confetti texture layer** (light but constant)
6. **Joy stamp** (CERTIFIED / APPROVED / GOOD VIBES)
7. **One burst shape** behind a primary element (CTA or headline)

If any of the above are missing → it becomes “nice happy brand,” not SUNNYCORE.

---

# 1) Color System (Concrete Palette + Rules)

## 1.1 Primary palette (SUNNYCORE Core)

These are intentionally loud and high-energy.

| Token            | Name           | Hex       | Use                                         |
| ---------------- | -------------- | --------- | ------------------------------------------- |
| `sun-yellow`     | Sun Yellow     | `#FFE600` | Primary energy, highlights, bursts          |
| `bubblegum-pink` | Bubblegum Pink | `#FF4FD8` | Friendly accents, stamps, playful panels    |
| `sky-cyan`       | Sky Cyan       | `#14D9FF` | Info sections, fresh UI blocks              |
| `mint-green`     | Mint Green     | `#4CFF88` | Success, positive confirmation, “go” states |
| `tangerine`      | Tangerine      | `#FF7A00` | CTA emphasis, urgency (positive urgency)    |

## 1.2 Secondary palette (Flavor + variation)

| Token         | Name        | Hex       | Use                               |
| ------------- | ----------- | --------- | --------------------------------- |
| `peach`       | Peach       | `#FFB199` | Soft warm background blocks       |
| `lavender`    | Lavender    | `#B79CFF` | Calm-but-happy secondary sections |
| `lemon-cream` | Lemon Cream | `#FFF7C2` | Background for text-heavy content |
| `soft-white`  | Soft White  | `#FFFDF5` | Default page background           |
| `cloud-gray`  | Cloud Gray  | `#F1F1F1` | Subtle separation blocks          |

## 1.3 Neutrals (readability + outline)

| Token      | Name          | Hex       | Use                     |
| ---------- | ------------- | --------- | ----------------------- |
| `ink`      | Ink Black     | `#111111` | Outlines, headline text |
| `charcoal` | Warm Charcoal | `#1E1E1E` | Body text               |
| `white`    | White         | `#FFFFFF` | Text on dark blocks     |

---

## 1.4 Color usage rules (non-negotiable)

### Rule A — The 70/20/10 layout rule

- **70%** soft-white / lemon-cream background space
- **20%** saturated blocks (primary palette)
- **10%** accents (stamps, outlines, confetti, small stickers)

### Rule B — Always use blocks, not subtle gradients

SUNNYCORE looks like **printed stickers + posters**, not modern glass gradients.

✅ OK: big rectangle of `#FFE600` behind a headline  
❌ Not OK: subtle gradient background or faded pastel wash

### Rule C — Outlines always use Ink

Outlines are **always** `#111111` (Ink).  
That consistency makes it instantly recognizable.

---

# 2) Typography (Concrete Font Stack + Scale)

SUNNYCORE uses a _toy-box headline font_ with a _clean readable body font_.

## 2.1 Font choices (pick these)

### Headline font (required)

- **Fredoka** (Google Font)  
  Fallback: `"Fredoka", "Baloo 2", system-ui, sans-serif`

### Body font (required)

- **Inter** (Google Font)  
  Fallback: `"Inter", system-ui, -apple-system, sans-serif`

### Optional number/stat font (if you want “scoreboard” energy)

- **Bungee** (Google Font) for big numeric callouts  
  Fallback: `"Bungee", "Fredoka", sans-serif`

---

## 2.2 Type scale (use exact sizes)

Use a _poster-like_ typographic hierarchy.

### Headlines (Fredoka)

- **H1 / Hero:** 64px (desktop), 40px (mobile) — weight 700
- **H2:** 40px (desktop), 28px (mobile) — weight 700
- **H3:** 28px (desktop), 22px (mobile) — weight 700
- **H4:** 22px (desktop), 18px (mobile) — weight 700

### Body (Inter)

- **Body L:** 18px — weight 500 — line-height 1.6
- **Body M:** 16px — weight 450–500 — line-height 1.6
- **Body S:** 14px — weight 450 — line-height 1.5

### Labels / UI microcopy

- **Button label:** 16px — Inter weight 700 — letter-spacing +0.5px
- **Badge label:** 13px — Inter weight 800 — letter-spacing +1px (ALL CAPS)

---

## 2.3 Typography rules (concrete)

### Rule A — Headlines must “hit” immediately

Headlines are **2–6 words max**.

- ✅ “TODAY IS A YES.”
- ✅ “MORE GOOD DAYS.”
- ❌ “Welcome to our initiative for increased well-being across teams”

### Rule B — Use uppercase strategically (not everywhere)

Only use ALL CAPS for:

- badges/stamps
- small punchy labels
- warnings-but-happy (“⚠️ TOO MUCH JOY INSIDE”)

---

# 3) Shapes + Presence (What it means concretely)

“Shapes have presence” means:

### ✅ Every primary element must have:

1. **Thick outline** (3–5px)
2. **Large corner radius** (see tokens below)
3. **Sticker-lift shadow** (see exact shadow values)
4. **Enough padding to feel chunky** (16–24px)

If an element looks “thin” or “flat,” it’s not SUNNYCORE.

---

## 3.1 Shape tokens (use these exact radii)

- `radius-pill`: **999px** (buttons, chips)
- `radius-card`: **28px** (cards, panels)
- `radius-input`: **18px** (forms)
- `radius-badge`: **999px** or **18px** (capsule or rounded rectangle)

---

## 3.2 Signature shapes (must appear)

At least **one** per page/poster:

- **Burst** (sunburst / comic explosion)
- **Stamp badge** (CERTIFIED / APPROVED)
- **Speech bubble** (callouts, helper copy)

### Burst shape spec (concrete)

- Size: 180–320px behind the CTA/headline
- Outline: 4px Ink
- Fill: usually `sun-yellow` or `tangerine`
- Position: behind element, offset slightly (top-left or bottom-right by 12–24px)

---

# 4) Sticker Lift (The “slightly floating” effect)

“Floating” in SUNNYCORE is not vague. It’s a **specific physical illusion**:

- a thick outline
- a shadow that looks like the object is lifted off paper
- optional slight rotation

## 4.1 Sticker shadow recipes (use these)

Pick **one** system-wide.

### Shadow A: Classic sticker lift (recommended)

- `box-shadow: 0px 10px 0px #111111;`
  This is super distinct: it looks like a _printed cutout_.

### Shadow B: Softer lift (less bold)

- `box-shadow: 0px 8px 0px rgba(17,17,17,0.65);`

### Shadow C: Double-lift (ultra sticker)

- `box-shadow: 0px 10px 0px #111111, 0px 18px 0px rgba(17,17,17,0.25);`

✅ SUNNYCORE typically uses **Shadow A** because it becomes recognizable instantly.

---

## 4.2 Outline thickness (exact)

- **Primary UI elements:** 4px Ink (`#111111`)
- **Secondary elements:** 3px Ink
- **Tertiary / subtle elements:** 2px Ink

Consistency matters more than variety.

---

## 4.3 Rotation rules (exact)

Use rotation rarely and subtly:

- Cards: **rotate(-1.5deg)** or **rotate(1.5deg)**
- Stamps: **rotate(-8deg)** for energy
- Never rotate text blocks in long reading sections

---

# 5) Component Specs (Concrete UI Recipes)

## 5.1 Buttons (The Joy Button)

A SUNNYCORE button must look like a toy button.

### Primary button spec

- Fill: `sun-yellow` or `tangerine`
- Border: `4px solid #111111`
- Radius: `999px`
- Padding: **16px 26px**
- Shadow: **Shadow A**
- Font: Inter 700, 16px, +0.5px letter spacing
- Optional icon: sparkle/star (left or right)

**Example labels**

- “LET’S GO ✨”
- “PRESS FOR JOY”
- “YES PLEASE”

### Hover motion (spec)

- Move up slightly: `translateY(-2px)`
- Shadow becomes slightly smaller: `0px 8px 0px #111111`
- Duration: 180ms ease-out

---

## 5.2 Cards (Sticker Cards)

### Sticker card spec

- Background: `soft-white` or any primary block color
- Border: `4px solid #111111`
- Radius: `28px`
- Padding: **20px**
- Shadow: Shadow A
- Title: Fredoka 22–28px
- Body: Inter 16px

### Card layout pattern

- Top-left: small icon bubble (48px)
- Top-right: badge stamp
- Bottom: 1 CTA link/button

---

## 5.3 Badges & Stamps (Signature element)

### Badge spec

- Background: `mint-green` or `bubblegum-pink`
- Border: `4px solid #111111`
- Radius: `999px`
- Padding: **8px 14px**
- Text: Inter 800, 13px, ALL CAPS, +1px letter spacing
- Shadow: optional small shadow `0px 5px 0px #111111`

**Examples**

- “CERTIFIED GOOD VIBES”
- “SUNNYCORE APPROVED”
- “MAXIMUM JOY”

---

## 5.4 Inputs & Forms

SUNNYCORE inputs must not look like “standard SaaS”.

### Input spec

- Height: **52px**
- Border: `3px solid #111111`
- Radius: `18px`
- Padding: `0 16px`
- Background: `#FFFFFF`
- Focus: outline becomes thicker + glow
  - Border: `4px solid #111111`
  - Extra: `box-shadow: 0px 0px 0px 6px rgba(20,217,255,0.35);`

Helper text example:

- “You’re doing great. Type anything 💛”

---

# 6) Confetti Layer (Concrete Pattern System)

This is a SYSTEM layer — it must appear subtly everywhere.

## 6.1 Confetti elements (allowed)

- dots
- stars
- sparkles
- hearts
- mini smiley faces (max 1 per cluster)

## 6.2 Confetti density rules

- On backgrounds: **8–12 confetti items per 500×500px**
- Opacity: **0.08–0.14**
- Sizes: **4px, 6px, 10px, 14px**
- Rotation: random between -25° and +25°
- Spacing: never evenly tiled (avoid wallpaper vibe)

## 6.3 Confetti color rules

Confetti can use:

- `bubblegum-pink`
- `sky-cyan`
- `mint-green`
- `lavender`
  But never more than **3 confetti colors per section**.

---

# 7) Layout Rules (Concrete)

SUNNYCORE is visually loud, but layout stays simple.

## 7.1 Spacing scale

Use only this scale:

- 8 / 16 / 24 / 40 / 64 / 96

## 7.2 Section structure templates

### Template A — “Hype Hero”

- Background: `soft-white` with confetti
- Headline block: `sun-yellow` rectangle behind text
- One burst behind CTA
- 1 stamp near headline

**Order**

1. H1 (Fredoka 64)
2. Subtext (Inter 18)
3. Primary button
4. Stamp badge (“CERTIFIED GOOD VIBES”)

### Template B — “Sticker Grid”

- 2–4 cards in a row
- At least 1 card rotated ±1.5°
- Each card includes a small badge

### Template C — “Big Message Banner”

A single loud horizontal block:

- Fill: bubblegum pink / cyan / mint
- Border: 4px Ink
- Text: H2, centered
- Confetti on corners only

---

# 8) Copywriting (Concrete rules + examples)

## 8.1 Tone rules

- Always kind
- Always forward-moving
- Zero guilt

## 8.2 Button copy (approved list)

- “LET’S GO ✨”
- “MAKE MY DAY”
- “SHOW ME SOMETHING GOOD”
- “YES PLEASE”
- “PRESS FOR JOY”
- “START THE HAPPY THING”

## 8.3 Errors (approved patterns)

Format:

> **Oops!** + reassurance + next step + emoji

Examples:

- “Oops! That didn’t work yet — try again 🌈”
- “Almost perfect. One small fix 💛”
- “We’re close! Give it one more go ✨”

## 8.4 Empty states

- “Nothing here yet — but it’s about to get awesome 🎉”
- “Your future wins will live here 🙂”

---

# 9) Accessibility & Readability (Concrete constraints)

SUNNYCORE is intense — so readability must be strict.

- Never place body text directly on neon without a backing shape
- Use Ink (`#111111`) for text on light backgrounds
- Use White text only on:
  - `bubblegum-pink`
  - `tangerine`
  - deep blocks (if you add any later)
- Minimum body size: **16px**
- Line height: **1.6**

---

# 10) SUNNYCORE Tokens (CSS-style)

Use this as the “source of truth”.

```css
:root {
  /* Colors */
  --sun-yellow: #ffe600;
  --bubblegum-pink: #ff4fd8;
  --sky-cyan: #14d9ff;
  --mint-green: #4cff88;
  --tangerine: #ff7a00;

  --peach: #ffb199;
  --lavender: #b79cff;
  --lemon-cream: #fff7c2;
  --soft-white: #fffdf5;
  --cloud-gray: #f1f1f1;

  --ink: #111111;
  --charcoal: #1e1e1e;
  --white: #ffffff;

  /* Radii */
  --radius-pill: 999px;
  --radius-card: 28px;
  --radius-input: 18px;

  /* Borders */
  --border-primary: 4px solid var(--ink);
  --border-secondary: 3px solid var(--ink);

  /* Shadows */
  --shadow-sticker: 0px 10px 0px var(--ink);
  --shadow-sticker-soft: 0px 8px 0px rgba(17, 17, 17, 0.65);
  --shadow-sticker-double:
    0px 10px 0px var(--ink), 0px 18px 0px rgba(17, 17, 17, 0.25);

  /* Spacing */
  --s-1: 8px;
  --s-2: 16px;
  --s-3: 24px;
  --s-4: 40px;
  --s-5: 64px;
  --s-6: 96px;
}
```
