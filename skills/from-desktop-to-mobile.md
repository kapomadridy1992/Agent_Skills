---
name: from-desktop-to-mobile
description: >-
  Builds a mobile version of a selected desktop Figma frame that feels natively
  designed for mobile — not a shrunk desktop. Preserves brand, content, and visual
  language; transforms structure, sizing, and interaction patterns only. Outputs
  Mobile 390 frame(s), optional mobile menu state, and a transformation report.
  Use when adapting a desktop page or screen to a ~390px mobile width.
---

# From desktop to mobile

Create a **mobile version** of the selected desktop frame. It must feel **native to mobile**, not a scaled-down desktop. Preserve brand, content, and visual language exactly; change only structure, sizing, and interaction patterns.

## How to read this skill

- **Fact.** Baseline width 390px (iPhone 14/15 class), 44×44px minimum touch targets, and spacing/type rules below unless the user’s design system overrides with documented mobile tokens.
- **Conflict.** Desktop centering vs mobile readability; comparison tables vs stacked cards. Default to rules here and **report** tradeoffs (e.g. matrix dropped per plan).
- **Practice.** Section pattern choices (stack vs carousel, hamburger vs tab bar) — match product type and desktop structure.

## Canvas setup

- Target width: **390px** (iPhone 14/15 baseline). Use another width if the user specifies.
- Height: **auto** — grows with content. Never crop or hide content to fit arbitrary height.
- Name the new frame `[original name] — Mobile 390`.
- Place it **120px to the right** of the desktop frame.
- **Never modify** the original desktop frame.

---

## Step 1 — Read and map the desktop frame

Before creating anything:

1. Read the full node tree: sections, order, grids, components, text styles, spacing values.
2. Identify section types (hero, nav, feature grid, pricing, testimonials, gallery, footer, forms, tables, etc.).
3. Note spacing system (base unit, section paddings) and type scale — mobile values **derive from these**, not invented from scratch.
4. If the selection is not a frame, or is a single small component rather than a page/screen, tell the user and **stop**.

---

## Step 2 — Global transformation rules

### Layout

- Multi-column grids → **single column**. Order = desktop reading order (left→right, top→bottom).
- Content max-width: 390 − 2×20px side margins = **350px** content area. Side padding: 20px (or 16px if desktop uses a 4px base).
- Section vertical padding: reduce desktop by ~**40–50%** (e.g. 120→64, 96→56, 64→40). Keep rhythm proportional.
- Gaps between stacked items: **16–24px**, from desktop spacing scale.
- Use **vertical Auto Layout** for stacked sections so the frame stays editable.

### Typography

Scale headings ~**30–40%**; keep body nearly intact:

| Desktop (approx.) | Mobile (approx.) |
| --- | --- |
| 64–72 | 36–40 |
| 48–56 | 30–32 |
| 32–40 | 24–28 |
| 24 | 20 |
| Body 16–18 | Keep 16 (never below **15** for body) |
| Captions/labels | Keep; minimum **12** |

Line-height: headings **1.1–1.2**, body **1.5–1.6**.

**Do not shorten copy.** If a heading wraps to 4+ lines, **flag in the final report** rather than rewriting.

Long text blocks: **left-align** even if desktop centered; centered is fine for short heroes and section titles.

### Touch targets

- Every interactive element: minimum **44×44px** hit area.
- Primary CTAs in stacked sections: **full-width (350px)**, height **48–56px**. Secondary buttons may stay intrinsic width.
- Adjacent tap targets: minimum **8px** between.
- Links in body text: keep; ensure line-height gives tap room.

### Imagery

- Full-bleed may extend edge-to-edge (390px); contained images stay within 350px content area.
- Preserve aspect ratios; wide panoramic heroes (e.g. 21:9) → **4:3 or 1:1** crops focused on subject.
- Decorative backgrounds that crowd small screens: scale down or remove; **list every removal** in the final report.

---

## Step 3 — Section-specific patterns

### Navigation

- Desktop horizontal nav → top bar **64px**: logo left, hamburger right.
- Add separate frame `[name] — Mobile Menu`: opened state (full-screen or dropdown), links stacked, **56px** row height each.
- Prominent desktop CTA (“Get started”): keep in top bar next to hamburger if space allows; else first item in opened menu.
- App-like dashboard with 3–5 primary destinations → **bottom tab bar** (56px, icons + labels) instead of hamburger.

### Hero

- Stack: heading → subheading → CTA(s) → hero image (if image is the message, image may go first).
- Side-by-side CTAs → stack vertically, primary on top, **12px** gap.

### Feature grids (3–4 columns)

- Default: **stack** one column.
- **Horizontal swipe carousel** only for 4+ visually rich cards (galleries, logos, testimonials) — not default for simple feature lists.
- Card internal padding: reduce ~**25%** from desktop.

### Logo bars / social proof

- Wrap to 2 rows or single-row horizontal scroll. Logos max height **28–32px**.

### Pricing tables

- Stack plans vertically; **recommended plan first** (not middle as on desktop).
- Shared feature-comparison matrix → each plan card lists its own features; drop matrix and **note in report**.

### Data tables

- Wider than 350px: each row → **card** (label:value pairs), or horizontal scroll with first column pinned.
- Default: cards for ≤6 columns of simple data; scroll for dense numeric tables.

### Forms

- All fields full-width, stacked. Field height **48–56px**. Labels above fields — not placeholder-only labels.
- Multi-column rows (First | Last) → stacked unless both fields are short (ZIP | City may stay paired).

### Footer

- Columns stack; link groups as stacked lists or **accordions** if 4+ groups. Legal line and social icons last.

### Sticky elements

- Desktop sticky sidebar CTAs → **sticky bottom bar** on mobile (full-width button, 16px padding, above safe area).

---

## Step 4 — Content prioritization

Mobile users scroll; attention decays. **Without deleting content:**

- Keep desktop section order unless a section is purely decorative filler before the primary CTA — then it may move below the CTA; **report reordering**.
- Long FAQ lists → **accordions** (first item may be expanded).
- Long testimonial walls → **carousel**, one testimonial per view.

---

## Step 5 — Finalize and report

1. Verify: no horizontal overflow; body text ≥15px; touch targets ≥44px; Auto Layout on stacked sections.
2. Deliver: `— Mobile 390`, `— Mobile Menu`, plus any other state frames created.
3. Report in chat:
   - Sections transformed and pattern used for each
   - Anything removed, cropped, reordered, or converted (e.g. “comparison matrix → per-card feature lists”)
   - Flags for human review (headings 4+ lines, dense tables, ambiguous nav CTA placement)

---

## Guardrails

- Never invent new content, copy, or imagery — everything from the desktop frame.
- Never restyle: colors, fonts, radius, shadows stay identical to the desktop system.
- Use existing components and **mobile variants** from the library when they exist; detach or rebuild only when no variant fits — **report each case**.
- If desktop uses breakpoint-specific components (e.g. `nav/desktop`), check for `nav/mobile` (or equivalent) before building from scratch.
