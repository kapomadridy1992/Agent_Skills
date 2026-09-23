---
name: social-media-creator
description: >-
  Builds on-brand social post, story, or ad frames (Instagram, LinkedIn,
  X/Twitter) using bound color tokens, type styles, and components — sized per
  platform with safe margins. Can analyze reference posts for layout and
  composition (structure only, never literal content) and apply those patterns
  to new frames. Use when a social post or ad is needed, or when studying
  reference posts for layout inspiration. Tool-agnostic when a brand kit or
  design library is connected (Canva Brand Kit, Figma variables/styles, etc.).
---

# Social media post creator

You compose **platform-correct, on-brand social frames** — not one-off decorations. Every layout should bind to tokens and components, respect safe margins, and read clearly at thumbnail scale.

## How to read this skill

- **Fact.** Documented platform dimensions and safe-zone guidance from the target network or the user’s brand system.
- **Conflict.** Platform specs vs. brand template vs. ad manager crop. Design to the stricter rule or ask which channel wins.
- **Practice.** Layout patterns, hierarchy habits, and pattern-library judgment below. Not a substitute for brand guidelines.

## When to use this skill

Trigger when asked to:

- Build a social post, story, or ad frame for Instagram, LinkedIn, X/Twitter, or similar using the connected brand or design system.
- Analyze or “learn from” reference posts to explain why a layout works — with or without building a new frame yet.

## Inputs (ask if missing)

| Input | Notes |
| --- | --- |
| Target platform(s) | **Do not guess.** Ask before proceeding. |
| Headline / message | What the post must communicate. |
| Imagery, logo lockup, CTA | As required by the brief. |
| Reference posts (optional) | Screenshots or links for **structural** inspiration only. Skip reference analysis if none are given. |

### Platform dimensions (default unless user overrides)

| Format | Size |
| --- | --- |
| Instagram post | 1080×1080 |
| Instagram story | 1080×1920 |
| LinkedIn post | 1200×627 |
| X/Twitter post | 1600×900 |

## Seed pattern library

Trained on a 32-post reference audit (corporate, agency, e-commerce, legal, food, construction). Before deriving a layout brief from scratch, check whether the ask matches one of these eight patterns:

1. **Single-object hero on flat field** — One subject on flat/gradient field, 35–60% negative space. Figure-ground contrast + focal isolation. Premium/conceptual brands (agency, tech, luxury).
2. **Bold stat/number callout** — Oversized number or percentage is the visual payload; short supporting line only. Extreme contrast hierarchy + curiosity gap. Authority B2B, finance, data-driven content.
3. **Quote/question-in-a-panel** — Frame splits: photo one side, headline or question in flat-color panel on the other. Proximity/grouping + legibility through isolation. Legal, coaching, advisory hooks.
4. **Two-tone keyword highlight** — Headline in neutral color except one keyword in accent. Selective contrast trains scan pattern. Benefit-driven educational series (12+ posts).
5. **Diagonal/split color-block background** — Background divides on diagonal or hard line into two brand colors; subject on or straddling the seam. Dynamic asymmetry. Construction, logistics, “moving forward” narratives.
6. **Cutout/collage subject breaking the frame** — Cut-out subject bleeds past tile edge or overlaps a color block. Pattern interrupt via broken boundaries. Youth, creative, fashion-adjacent energy.
7. **Repeated/textural type-as-pattern** — Core keyword repeats at different scales/rotations/opacities, often with texture. Redundancy + urgency signal. Flash sales, launches.
8. **Native-UI mimicry** — Phone frame, browser chrome, or Story UI chrome (avatar, handle, tabs). Authenticity via platform chrome. Portfolio/social proof, app promotion.

**Cross-cutting habits** (default even without a named pattern): 2–3 color max per post; fixed footer/header brand-lockup zone tile-to-tile; headlines **2–6 words** — brevity is hierarchy.

## Step 1 — Learn from reference posts (references only)

For each reference, analyze **structure, not content**:

- Grid and focal point — symmetry, rule of thirds, first landing point.
- Visual hierarchy — read order (headline → image → CTA or reverse), size/weight drivers.
- Type pairing — display vs. body, line count, word count.
- Color and contrast — how many colors carry the frame; highest-contrast element placement.
- Whitespace / margin ratio — edge-to-content spacing.
- Hook / pattern interrupt — thumb-stop element (oversized type, crop, color block).
- CTA placement — position and separation from the rest.

Name the **design principle** for each observation (rule of thirds, F-pattern, proximity, contrast hierarchy, pattern interrupt, etc.) — capture **why**, not only what.

Write a short **layout brief** in words and ratios only — e.g. “single bold headline in top third, high-contrast subject centered on lower two-thirds, CTA bottom-right in accent, ~40% negative space.” Never store or reproduce the reference’s photo, artwork, logo, or copy.

### Pattern library persistence

Look for a page or section named **Social — Pattern Library** in the user’s connected doc or file (Notion, brand wiki, etc.). If it does not exist, create it and seed the eight patterns above on first creation. For each new pattern discovered later, add one annotated entry: name, layout brief, principle(s), when to use it. Before writing a fresh brief, check for a matching seed, platform, or logged pattern and reuse instead of re-deriving.

## Step 2 — Compose the post

1. Pull primary/secondary color tokens, text styles, and logo/lockup components from the connected library — **no raw hex or freehand styles** unless the system has no tokens (then document that gap).
2. Pick a layout brief: from Step 1, **Social — Pattern Library**, or closest seed pattern. Map structure (grid, hierarchy, hook, whitespace) onto brand tokens; never carry reference colors, imagery, or wording.
3. Reuse existing components (buttons, badges, tags, logo lockups) instead of drawing new shapes when possible.
4. Compose headline (aim **8 words or fewer**), supporting line, and CTA if requested.
5. Apply the platform **safe-margin/padding** token — do not eyeball spacing.
6. Produce **2–3 layout variants** (image-led, text-led, quote-style) when useful.
7. Check **legibility at thumbnail scale**; flag unreadable text instead of shipping silently.

## Guardrails

- Never introduce colors outside the bound token set.
- Never stretch, recolor, or reposition the logo outside documented lockup rules.
- Do not fabricate stats, testimonials, or claims — mark placeholder copy clearly.
- Reference analysis: **structural/compositional patterns only.** No tracing, screenshot-paste, close mimic of wording, or reproduction of copyrighted photo, artwork, or logo.
- Adapt treatment — do not copy a layout one-to-one from Mobbin, a reference post, or the pattern library.
- Reference-post analysis is for **internal design reasoning** — do not output or restate a competitor’s or creator’s original copy verbatim.

## Output

When references were analyzed: layout brief(s) plus **Social — Pattern Library** entry created or matched, each with a one-line “why it works.”

Deliver:

- New frame(s) named `Social/{Platform}/{Variant}` (or equivalent in the user’s tool).
- Every fill, stroke, and text style bound to a token or existing style — no orphan raw values.
- Short note: tokens/components used and which layout pattern informed the work (seed, library match, or fresh derivation) for spot-checking.
