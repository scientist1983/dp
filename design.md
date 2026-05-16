# Design System — JarCOS UI

Source: Figma Variables panel, file `JarCOS UI` (`0v93xS3oDLra3a3uEJBwuP`)

**Color modes:** JarCOS-Light · JarCOS-Dark  
**Density modes (Corner Radius & Size):** Standard · Expanded (+4) · Expanded (+8) · Condensed (-4)  
**Font mode:** Lato · Regular / Semi Bold

---

## Corner Radius

Values are in `px`. Token name = Standard value; modes adjust by ±4 or ±8.

| Token | Standard | Expanded (+4) | Expanded (+8) | Condensed (-4) |
|-------|---------|--------------|--------------|----------------|
| `radius/0` | 0 | 0 | 0 | 0 |
| `radius/4` | 4 | 8 | 12 | 0 |
| `radius/8` | 8 | 12 | 16 | 4 |
| `radius/12` | 12 | 16 | 20 | 8 |
| `radius/16` | 16 | 20 | 24 | 12 |
| `radius/20` | 20 | 24 | 28 | 16 |
| `radius/24` | 24 | 28 | 32 | 20 |
| `radius/28` | 28 | 32 | 36 | 24 |
| `radius/32` | 32 | 36 | 40 | 28 |
| `radius/40` | 40 | 44 | 48 | 36 |
| `radius/48` | 48 | 52 | 56 | 44 |
| `radius/56` | 56 | 58 | 62 | 52 |
| `radius/64` | 64 | 68 | 72 | 60 |
| `radius/72` | 72 | 76 | 80 | 68 |
| `radius/80` | 80 | 84 | 88 | 76 |

---

## Font

| Token | Lato mode |
|-------|-----------|
| `font` | `Lato` |
| `letter spacing` | `0` |

---

## Font Weight

| Token | Regular / Semi Bold mode |
|-------|--------------------------|
| `regular` | `400` |
| `bold` | `700` |

---

## Paragraph Spacing

Two modes: **Text** (no extra spacing) and **Paragraph** (adds bottom spacing).

| Token | Text | Paragraph |
|-------|------|-----------|
| `paragraph-spacing/8` | 0 | 8 |
| `paragraph-spacing/10` | 0 | 10 |
| `paragraph-spacing/12` | 0 | 12 |
| `paragraph-spacing/14` | 0 | 14 |
| `paragraph-spacing/18` | 0 | 18 |
| `paragraph-spacing/24` | 0 | 24 |
| `paragraph-spacing/36` | 0 | 36 |
| `paragraph-spacing/48` | 0 | 48 |

---

## Size (Type Scale)

Font size tokens in `px`. Four density modes match Corner Radius.

| Token | Standard | Expanded (+4) | Expanded (+8) | Condensed (-4) |
|-------|---------|--------------|--------------|----------------|
| `size/12` | 12 | 16 | 20 | 8 |
| `size/16` | 16 | 20 | 24 | 12 |
| `size/20` | 20 | 24 | 28 | 16 |
| `size/24` | 24 | 28 | 32 | 20 |
| `size/28` | 28 | 32 | 36 | 24 |
| `size/32` | 32 | 36 | 40 | 28 |
| `size/40` | 40 | 44 | 48 | 36 |
| `size/48` | 48 | 52 | 56 | 44 |
| `size/56` | 56 | 60 | 64 | 52 |
| `size/64` | 64 | 68 | 72 | 60 |
| `size/72` | 72 | 76 | 80 | 68 |
| `size/80` | 80 | 84 | 88 | 76 |

---

## Spacing

Layout spacing tokens in `px`. Same four density modes as Corner Radius and Size.

| Token | Standard | Expanded (+4) | Expanded (+8) | Condensed (-4) |
|-------|---------|--------------|--------------|----------------|
| `spacing/0` | 0 | 0 | 0 | 0 |
| `spacing/2` | 2 | 4 | 8 | 0 |
| `spacing/4` | 4 | 8 | 12 | 0 |
| `spacing/8` | 8 | 12 | 16 | 4 |
| `spacing/10` | 10 | 14 | 18 | 6 |
| `spacing/12` | 12 | 16 | 20 | 8 |
| `spacing/16` | 16 | 20 | 24 | 12 |
| `spacing/20` | 20 | 24 | 28 | 16 |
| `spacing/24` | 24 | 28 | 32 | 20 |
| `spacing/28` | 28 | 32 | 36 | 24 |
| `spacing/40` | 40 | 44 | 48 | 36 |
| `spacing/48` | 48 | 52 | 56 | 44 |
| `spacing/80` | 80 | 84 | 88 | 0 |

---

## Visibility

Boolean tokens used to show/hide elements. Two separate collections with identical structure.

| Collection | Token | True mode | False mode |
|-----------|-------|-----------|------------|
| Visibility 1 | `visibility 1` | `True` | `False` |
| Visibility 2 | `visibility 2` | `True` | `False` |

---

## Color Variables

Two modes: **JarCOS-Light** and **JarCOS-Dark**

---

## Color Variables

### Semantic Tokens

| Token | JarCOS-Light | JarCOS-Dark |
|-------|-------------|------------|
| `primary` | `Charcoal/100%` → `#0B0C0B` | `secondary/Volt/100` → `#D5FF02` |
| `logo` | `primary` → `#0B0C0B` | `secondary/Volt/100` → `#D5FF02` |

---

### White

| Token | JarCOS-Light | JarCOS-Dark |
|-------|-------------|------------|
| `white/100%` | `#FFFFFF` | `#0B0C0B` |
| `white/80%` | `#FFFFFF` · 80% | `#0B0C0B` · 80% |
| `white/40%` | `#FFFFFF` · 40% | `#0B0C0B` · 40% |
| `white/20%` | `#FFFFFF` · 20% | `#0B0C0B` · 20% |
| `white/10%` | `#FFFFFF` · 10% | `#0B0C0B` · 10% |
| `white/4%` | `#FFFFFF` · 4% | `#0B0C0B` · 4% |

---

### Charcoal

| Token | JarCOS-Light | JarCOS-Dark |
|-------|-------------|------------|
| `Charcoal/100%` | `#0B0C0B` | `#FFFFFF` |
| `Charcoal/80%` | `#0B0C0B` · 80% | `#FFFFFF` · 80% |
| `Charcoal/40%` | `#0B0C0B` · 40% | `#FFFFFF` · 40% |
| `Charcoal/20%` | `#0B0C0B` · 20% | `#FFFFFF` · 20% |
| `Charcoal/10%` | `#0B0C0B` · 10% | `#FFFFFF` · 15% |
| `Charcoal/4%` | `#0B0C0B` · 4% | `#FFFFFF` · 10% |

---

### Background

| Token | JarCOS-Light | JarCOS-Dark |
|-------|-------------|------------|
| `background/1` | `#FFFFFF` | `#0B0C0B` |
| `background/2` | `#F9F9FA` | `#FFFFFF` · 4% |
| `background/3` | `#FFFFFF` · 80% | `#000000` · 10% |
| `background/4` | `#EDEEFC` | `#090C34` |
| `background/5` | `#E6F1FD` | `#E6F1FD` |
| `background/6` | `#FFFFFF` · 90% | `#404040` · 90% |

---

### Secondary Palette

#### Volt
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Volt/100` | `#D5FF02` | `#D5FF02` |
| `secondary/Volt/10` | `#D5FF02` · 10% | `#D5FF02` · 10% |

#### Neon
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Neon/100` | `#5CD801` | `#5CD801` |
| `secondary/Neon/10` | `#5CD801` · 10% | `#5CD801` · 10% |

#### Yellow Rose
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Yellow Rose/100` | `#FFF200` | `#FFF200` |
| `secondary/Yellow Rose/10` | `#FFF200` · 10% | `#FFF200` · 10% |

#### Aqua
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Aqua/100` | `#00F6FF` | `#00F6FF` |
| `secondary/Aqua/10` | `#00F6FF` · 10% | `#00F6FF` · 10% |

#### Kleine Blue
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Kleine Blue/100` | `#2C3AFF` | `#A1A7FF` |
| `secondary/Kleine Blue/110` | `#2834E5` | `#2834E5` · 50% |
| `secondary/Kleine Blue/10` | `#2C3AFF` · 10% | `#2C3AFF` · 70% |

#### Fuchsia Pink
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Fuchsia Pink/100` | `#FF8FFF` | `#FF8FFF` |
| `secondary/Fuchsia Pink/10` | `#FF8FFF` · 10% | `#FF8FFF` · 10% |

#### Tangelo
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Tangelo/100` | `#F55200` | `#F55200` |
| `secondary/Tangelo/110` | `#B03B00` | `#B03B00` |
| `secondary/Tangelo/10` | `#F55200` · 10% | `#F55200` · 10% |

#### Dim Gray
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Dim Gray/100` | `#686868` | `#686868` |
| `secondary/Dim Gray/10` | `#686868` · 10% | `#686868` · 10% |

#### Silver Sand
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Silver Sand/100` | `#C4C4C4` | `#C4C4C4` |
| `secondary/Silver Sand/10` | `#C4C4C4` · 10% | `#C4C4C4` · 10% |

#### Orange
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Orange/100` | `#FFB55B` | `#FFB55B` |
| `secondary/Orange/110` | `#E5A352` | `#E5A352` |
| `secondary/Orange/10` | `#FFB55B` · 10% | `#FFB55B` · 10% |

#### Purple
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Purple/100` | `#B899EB` | `#B899EB` |
| `secondary/Purple/10` | `#B899EB` · 10% | `#B899EB` · 10% |

#### Green
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Green/100` | `#71DD8C` | `#71DD8C` |
| `secondary/Green/110` | `#66C77E` | `#66C77E` |
| `secondary/Green/10` | `#71DD8C` · 10% | `#71DD8C` · 10% |

#### Yellow
| Token | Light | Dark |
|-------|-------|------|
| `secondary/Yellow/100` | `#FFCC00` | `#FFCC00` |
| `secondary/Yellow/10` | `#FFCC00` · 10% | `#FFCC00` · 10% |

---

## Prototype Color Reference

The current prototype (`index.html`) uses Design Pickle brand colors rather than JarCOS tokens. This section maps what's currently in use so colors can be reconciled with the official system later.

### Brand Green (Design Pickle)
| Hex | Usage |
|-----|-------|
| `#0A7C4A` | Primary CTAs, links, active states, avatars, progress bars |
| `#14B870` | Gradient end, approved states |
| `#52D6A2` | Gradient highlight |
| `#EBF5EE` | Selected card background |
| `#E6F3EC` | Locked badge background |
| `#D4EDE0` | Hover on tinted buttons |
| `#F0FDF7` | Hover bg on asset cards |

### Neutral Scale
| Hex | Role |
|-----|------|
| `#111` | Primary text, dark buttons, sidenav |
| `#333` / `#444` / `#555` | Secondary text hierarchy |
| `#666` / `#777` / `#888` / `#999` | Tertiary / muted |
| `#AAA` / `#BBB` / `#CCC` | Placeholder, hints, labels |
| `#D5D2CC` | Muted borders |
| `#E5E3DF` | Card borders |
| `#EDEAE4` | Panel dividers |
| `#F0EDE8` | Inner dividers |
| `#F4F3F0` | App background |
| `#F5F4F0` | Surface level 1 |
| `#F7F5F1` | Surface level 2 |
| `#FAFAF8` | Table row hover, footer bg |

### Status Colors
| Status | Background | Text |
|--------|-----------|------|
| In Progress | `#DBEAFE` | `#1D4ED8` |
| Awaiting | `#FEF3C7` | `#D97706` |
| Revision | `#EDE9FE` | `#7C3AED` |
| Approved | `#D1FAE5` | `#059669` |
| Locked | `#E6F3EC` | `#0A7C4A` |

### Accent Colors
| Color | Hex | Usage |
|-------|-----|-------|
| Blue 500 | `#2563EB` | New request button |
| Blue 600 | `#1D4ED8` | Hover, in-progress text |
| Blue 400 | `#3B82F6` | AI FAB gradient |
| Orange | `#F97316` | AI FAB gradient start |
| Red | `#EF4444` | Reject / error / destructive |

---

## Typography

**Font family:** `DM Sans` (Google Fonts)  
Weights: 300, 400, 500, 600, 700, 800 — optical size `9..40`

| Role | Size | Weight |
|------|------|--------|
| Display | 42px | 800 |
| Hero | 36px | 800 |
| Dashboard title | 24px | 800 |
| Section heading | 22px | 900 |
| Modal title | 17px | 700 |
| Card title | 15px | 700 |
| Body / bubble | 13px | 400–600 |
| Caption | 12px | 400 |
| Label (caps) | 9–11px | 700 (letter-spacing .08–.12em, uppercase) |

---

## Border Radius

| Token | Value | Usage |
|-------|-------|-------|
| `radius-pill` | `9999px` | All pill buttons and badges |
| `radius-4xl` | `18px` | Chat bubbles |
| `radius-3xl` | `16px` | Modals |
| `radius-2xl` | `14px` | Step cards, tiles |
| `radius-xl` | `12px` | Cards, inputs |
| `radius-lg` | `10px` | Option cards, buttons |
| `radius-md` | `8px` | Icons, thumbnails, swatches |
| `radius-sm` | `6–7px` | Inner elements |
| `radius-xs` | `3px` | Bubble tail |

---

## Gradients (Prototype)

| Name | Value |
|------|-------|
| Brand | `linear-gradient(135deg, #0A7C4A, #14B870)` |
| Brand full | `linear-gradient(145deg, #0A7C4A 0%, #14B870 60%, #52D6A2 100%)` |
| AI FAB | `linear-gradient(135deg, #F97316, #3B82F6)` |
| Brand scan | `linear-gradient(90deg, #0A7C4A, #14B870)` |

---

## Figma File

| | |
|-|-|
| File name | JarCOS UI |
| File key | `0v93xS3oDLra3a3uEJBwuP` |
| Access | `llinnett@designpickle.com` (Design Pickle org) |
| URL | `https://www.figma.com/design/0v93xS3oDLra3a3uEJBwuP/JarCOS-UI` |
