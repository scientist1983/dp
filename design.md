# Design System — Open Jar / Design Pickle Express

Extracted from the prototype CSS. Intended to serve as a reference for future development and to align with the JarCOS UI design system.

---

## Typography

**Font family:** `DM Sans` (Google Fonts)  
Import: `https://fonts.googleapis.com/css2?family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600;9..40,700;9..40,800`  
Fallback: `system-ui, sans-serif`

| Role | Size | Weight | Color |
|------|------|--------|-------|
| Display / Hero | 42px | 800 | `#111` |
| Page title | 36px | 800 | `#111` |
| Dashboard title | 24px | 800 | `#111` |
| Section heading | 22px | 900 | `#111` |
| Modal title | 17px | 700 | `#111` |
| Card title | 15px | 700 | `#111` |
| Tab / nav label | 14px | 700 | `#111` |
| Card subtitle | 14px | 400 | `#999` |
| Body / bubble | 13px | 400 | `#111` |
| Body small | 12.5px | 400 | `#444` |
| Caption | 12px | 400 | `#AAA` |
| Label (caps) | 9–11px | 700 | `#BBB` (letter-spacing: .08–.12em, uppercase) |
| Micro | 7–8.5px | 700–800 | varies |

**Letter spacing:** `-0.6px` on display sizes, `.04–.12em` on uppercase labels  
**Line height:** `1.5` body, `1.6` bubbles/chat, `1.7` onboarding bubbles, `1.1` hero headlines

---

## Color Palette

### Brand — Green

| Token | Hex | Usage |
|-------|-----|-------|
| `brand-600` | `#0A7C4A` | Primary CTA, links, active states, avatars, progress bars |
| `brand-400` | `#14B870` | Gradient end, lighter accents, approved states |
| `brand-200` | `#52D6A2` | Gradient highlight (mascot, top of hero) |
| `brand-50` | `#EBF5EE` | Selected card bg, badge bg |
| `brand-25` | `#D4EDE0` | Hover on tinted buttons |
| `brand-hover-bg` | `#EBF5EE` | Hover tint on green-bordered elements |
| `brand-subtle` | `#F0FDF7` | Hover bg for asset cards |
| `brand-bg` | `#E6F3EC` | Badge background (locked) |

### Neutral — Dark (Ink)

| Token | Hex | Usage |
|-------|-----|-------|
| `ink-900` | `#111` | Primary text, dark buttons, sidenav bg |
| `ink-800` | `#222` | Sidenav hover |
| `ink-700` | `#2A2A2A` | Sidenav divider, dark borders |
| `ink-600` | `#333` | Secondary text, button hover |
| `ink-500` | `#444` | Option card text |
| `ink-400` | `#555` | Muted text, icon color |
| `ink-300` | `#666` | Tertiary text |
| `ink-250` | `#777` | Dashboard icons |
| `ink-200` | `#888` | Placeholder labels, badge text |
| `ink-150` | `#999` | Disabled / muted |

### Neutral — Light (Stone)

| Token | Hex | Usage |
|-------|-----|-------|
| `stone-300` | `#AAA` | Hint text, captions |
| `stone-200` | `#BBB` | Label text, badge |
| `stone-150` | `#C0BDB8` | Chat hint text |
| `stone-100` | `#C5C2BC` | Metadata dots |
| `stone-75` | `#CCC` | Input placeholder, typing dots |
| `stone-50` | `#D0CCC7` | Disabled send button |
| `stone-40` | `#D5D2CC` | Border muted, disabled bg |
| `stone-30` | `#DDD` | Scrollbar |

### Background / Surface

| Token | Hex | Usage |
|-------|-----|-------|
| `surface-100` | `#F0EDE8` | Icon button bg, pill bg, modal close |
| `surface-75` | `#F4F3F0` | App body bg, onboarding bg |
| `surface-60` | `#F5F4F0` | Sidebar hover, input bg, tile bg |
| `surface-50` | `#F7F5F1` | Right panel bg, brand scan header |
| `surface-40` | `#F8F7F4` | Type tile bg |
| `surface-25` | `#FAFAF8` | Chat footer bg, table row hover |
| `surface-10` | `#F9F9F9` | Upload drop zone |
| `white` | `#fff` | Cards, topbar, chat bubbles, inputs |

### Border

| Token | Hex | Usage |
|-------|-----|-------|
| `border-strong` | `#D5D2CC` | Input borders, muted dividers |
| `border-base` | `#E5E3DF` | Card borders, panel dividers |
| `border-soft` | `#EDEAE4` | Topbar, modal dividers |
| `border-subtle` | `#F0EDE8` | Inner section dividers |

### Blue — Accent

| Token | Hex | Usage |
|-------|-----|-------|
| `blue-600` | `#1D4ED8` | Blue button hover, "In Progress" text |
| `blue-500` | `#2563EB` | New request button, badge bg |
| `blue-400` | `#3B82F6` | AI FAB gradient end |
| `blue-100` | `#DBEAFE` | "In Progress" badge bg, role badge |

### Orange

| Token | Hex | Usage |
|-------|-----|-------|
| `orange-500` | `#F97316` | AI FAB gradient start |
| `orange-600` | `#E05A2B` | User avatar bg |

### Amber — Warning

| Token | Hex | Usage |
|-------|-----|-------|
| `amber-500` | `#F59E0B` | Gradient (type tile) |
| `amber-600` | `#D97706` | "Awaiting" badge text, stat warning |
| `amber-100` | `#FEF3C7` | "Awaiting" badge bg, warning card bg |
| `amber-200` | `#FDE68A` | Warning card border |

### Red — Destructive

| Token | Hex | Usage |
|-------|-----|-------|
| `red-500` | `#EF4444` | Reject button, error, invalid email |
| `red-50` | `#FFF5F5` | Rejected asset card bg |
| `red-25` | `#FFF0F0` | Invalid tag bg |

### Purple — Revision

| Token | Hex | Usage |
|-------|-----|-------|
| `purple-500` | `#6366F1` | Gradient start (social type tile) |
| `purple-400` | `#8B5CF6` | Gradient end |
| `purple-600` | `#7C3AED` | "Revision" badge text, team role badge |
| `purple-100` | `#EDE9FE` | "Revision" badge bg |

### Green — Approved (Emerald)

| Token | Hex | Usage |
|-------|-----|-------|
| `emerald-600` | `#059669` | "Approved" badge text |
| `emerald-100` | `#D1FAE5` | "Approved" badge bg |

---

## Status Badges

| Status | Background | Text |
|--------|-----------|------|
| In Progress | `#DBEAFE` | `#1D4ED8` |
| Awaiting | `#FEF3C7` | `#D97706` |
| Revision | `#EDE9FE` | `#7C3AED` |
| Approved | `#D1FAE5` | `#059669` |
| Locked | `#E6F3EC` | `#0A7C4A` |
| Building | `#EDEAE4` | `#888` |

---

## Gradients

| Name | Value | Usage |
|------|-------|-------|
| Brand (primary) | `linear-gradient(135deg, #0A7C4A, #14B870)` | Mascot, avatar, approve buttons |
| Brand (mascot full) | `linear-gradient(145deg, #0A7C4A 0%, #14B870 60%, #52D6A2 100%)` | Mascot illustration |
| AI FAB | `linear-gradient(135deg, #F97316, #3B82F6)` | AI floating action button |
| Indigo/Purple | `linear-gradient(135deg, #6366F1, #8B5CF6)` | Social media type tile |
| Amber/Red | `linear-gradient(135deg, #F59E0B, #EF4444)` | Email/digital type tile |
| Brand scan bar | `linear-gradient(90deg, #0A7C4A, #14B870)` | Brand scan progress bar |

---

## Border Radius

| Token | Value | Usage |
|-------|-------|-------|
| `radius-xs` | `3px` | Chat bubble tail radius |
| `radius-sm` | `6–7px` | Inner elements, checkboxes |
| `radius-md` | `8px` | Icon containers, thumbnails, swatches |
| `radius-lg` | `10px` | Option cards, step card footer buttons, dropdowns |
| `radius-xl` | `12px` | Cards, input bars, modals inner |
| `radius-2xl` | `14px` | Step cards, type popup tiles, brand scan |
| `radius-3xl` | `16px` | Modals, upload modal |
| `radius-4xl` | `18px` | Chat bubbles, ob-welcome bubble |
| `radius-mascot` | `24–32px` | Mascot / hero illustration |
| `radius-pill` | `9999px` | All pill-shaped buttons and badges |

---

## Elevation / Shadows

| Token | Value | Usage |
|-------|-------|-------|
| `shadow-xs` | `0 1px 3px rgba(0,0,0,.04)` | AI chat bubble |
| `shadow-sm` | `0 1px 6px rgba(0,0,0,.06)` | Welcome prompt card |
| `shadow-md` | `0 2px 8px rgba(0,0,0,.06)` | Request cards |
| `shadow-lg` | `0 4px 16px rgba(0,0,0,.1)` | Dropdowns, hover cards |
| `shadow-xl` | `0 8px 40px rgba(0,0,0,.12)` | Type popup |
| `shadow-2xl` | `0 16px 48px rgba(0,0,0,.18)` | Roles modal |
| `shadow-3xl` | `0 24px 72px rgba(0,0,0,.22)` | Full modal |
| `shadow-brand` | `0 12px 32px rgba(10,124,74,.22)` | Mascot glow |
| `shadow-brand-btn` | `0 4px 16px rgba(10,124,74,.3)` | Approve button hover |
| `shadow-fab` | `0 4px 20px rgba(59,130,246,0.35)` | AI FAB button |

---

## Spacing Scale

Base unit: `4px`

| Token | Value |
|-------|-------|
| `space-1` | `4px` |
| `space-2` | `8px` |
| `space-3` | `12px` |
| `space-4` | `16px` |
| `space-5` | `20px` |
| `space-6` | `24px` |
| `space-8` | `32px` |
| `space-10` | `40px` |
| `space-12` | `48px` |

Common intermediate values in use: `6px`, `9px`, `10px`, `11px`, `13px`, `14px`, `18px`, `22px`, `28px`.

---

## Component Dimensions

| Component | Value |
|-----------|-------|
| Sidenav width | `52px` |
| Topbar height | `52px` |
| Dashboard topbar height | `56px` |
| Agent tab bar height | `42px` |
| Progress bar height | `2px` |
| Right brief panel width | `296px` |
| Dashboard sidebar width | `180px` |
| Dashboard right panel width | `280px` |
| Step card max width | `min(500px, 95%)` |
| Step card max height | `min(680px, 82vh)` |
| Input bar min height | `42px` |
| Avatar (small) | `28×28px` |
| Avatar (medium) | `30–32px` |
| Icon buttons | `34–38px` |
| Send button | `38px` |
| AI FAB | `52×52px` |
| Sidenav logo | `34×34px` |
| Sidenav new button | `34×34px` |
| Mascot (welcome) | `220×220px` |
| Mascot (sidebar) | `150×150px` |

---

## Border Widths

| Usage | Value |
|-------|-------|
| Standard dividers & card borders | `0.5px solid` |
| Selected / active emphasis | `1.5px solid` |
| Asset fullscreen modal | `1px solid` |

---

## Animation

| Name | Definition | Usage |
|------|-----------|-------|
| `fadeUp` | `opacity 0→1, translateY 7px→0, 0.2s ease` | Chat messages, cards |
| `popUp` | `scale .96→1, translateY 8px→0, 0.3s cubic-bezier(.34,1.56,.64,1)` | Type popup, input bar |
| `db` (dot bounce) | `translateY 0→-4px, bg #ccc→#0A7C4A, 1.1s infinite` | Typing indicator dots |
| `brandScan` | `width 0→100%, 1.8s ease-in-out forwards` | Brand scanning progress bar |
| Transition standard | `0.15s` | Buttons, hover states |
| Transition slow | `0.4–0.5s ease` | Panel slide, progress bar fill |

---

## Layout Patterns

### App Shell
```
[sidenav 52px] [main flex:1]
  main: [topbar 52px] [agent-tabs 42px] [content flex:1]
    content: [chat pane] [right panel 296px]
```

### Dashboard
```
[db-topbar 56px]
[db-body flex:1]
  [db-sidebar 180px] [db-main flex:1 + gap 20px] [db-right 280px]
```

### Onboarding step card
Position: `align-self:flex-start`, `margin-left:37px` (offset for avatar width + gap)  
Structure: `[ob-sc-body flex:1 overflow:auto min-height:200px]` + `[ob-sc-footer]`

---

## Iconography

All icons are inline SVG.  
Standard icon size: `16–18px`  
Small icons: `14px`  
Large icons: `20–22px`

Style: Outline / stroke-based (`stroke-width: 1.5–2`)

---

## Key UI Patterns

### Chat bubbles
- AI: white bg, `0.5px solid #E5E3DF`, `border-bottom-left-radius:3px`, shadow-xs
- User: `#111` bg, white text, `border-bottom-right-radius:3px`
- Avatar size: `28×28px`, rounded full
- Max width: `90%`

### Pill buttons / badges
- `border-radius: 9999px`
- Variants: filled dark (`#111`), filled green (`#0A7C4A`), outlined (`#D5D2CC`), tinted brand (`#EBF5EE + #0A7C4A border`)

### Card hover effect
- `transform: translateY(-1px)`
- `box-shadow: 0 3px 12px rgba(0,0,0,.06–.07)`
- `border-color: #999`

### Selected / active state
- `border-color: #0A7C4A`
- `background: #EBF5EE`
- pointer-events disabled on single-select

### Scrollbars
- Width: `4px`
- Thumb: `#E5E3DF`, `border-radius: 2px`
- Track: transparent

---

## Figma File Reference

File: **JarCOS UI**  
URL: `https://www.figma.com/design/0v93xS3oDLra3a3uEJBwuP/JarCOS-UI`  
Access org: `llinnett@designpickle.com` (Design Pickle workspace)  
Node inspected: `30601-131418`
