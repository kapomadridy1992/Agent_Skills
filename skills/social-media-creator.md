---
name: social-media-creator
description: >-
  Builds on-brand social media post, story, or ad frames (Instagram, LinkedIn,
  X/Twitter) using color tokens, type styles, and components — sized correctly
  per platform with safe margins. Can learn from reference posts: analyze layout,
  hierarchy, and composition, then apply structural patterns (never literal
  content) to new on-brand posts. Use when a social post or ad frame is needed,
  or when asked to study reference posts for layout inspiration. Tool-agnostic
  when a brand kit or design library is connected.
---

# Social media post creator

You compose **platform-correct, on-brand social frames** — not one-off decorations. Every layout should bind to tokens and components, respect safe margins, and read clearly at thumbnail scale.

## How to read this skill

- **Fact.** Documented platform dimensions and safe-zone guidance from the target network or the user’s brand system.
- **Conflict.** Platform specs vs. brand template vs. ad manager crop. Design to the stricter rule or ask which channel wins.
- **Practice.** Layout patterns, hierarchy habits, and pattern-library judgment below. Not a substitute for brand guidelines.

## When to invoke

Trigger when asked to:

- Build a social post, story, or ad frame for a platform (Instagram, LinkedIn, X/Twitter, etc.) using the connected brand or design system.
- Analyze, study, or “learn from” one or more reference posts to understand why their layout works, with or without building something from it right away.

## Inputs it expects

- **Target platform(s).** If not specified, ask before proceeding — do not guess.
- **Headline / message** the post needs to communicate.
- Any required **imagery, logo lockup, or CTA**.
- **Reference posts (optional):** screenshots or links whose layout/composition should inform the design. Not required — skip straight to compose steps if none are given.

### Platform dimensions (use unless told otherwise)

| Format | Size |
| --- | --- |
| Instagram post | 1080×1080 |
| Instagram story | 1080×1920 |
| LinkedIn post | 1200×627 |
| X/Twitter post | 1600×900 |

## Seed pattern library

Trained on a 32-post reference audit across corporate, agency, e-commerce, legal, food, and construction feeds. Check this set before deriving a layout brief from scratch — most reference posts you’ll be asked to build from are a variant of one of these eight:

1. **Single-object hero on flat field** — One subject isolated on a flat/gradient field, 35–60% negative space. Figure-ground contrast + focal-point isolation. Premium/conceptual brands (agencies, tech, luxury) where clutter undercuts a “considered” positioning.
2. **Bold stat/number callout** — An oversized number or percentage is the entire visual payload, plus a short supporting line and nothing else. Contrast hierarchy pushed to its extreme + curiosity gap. Authority-building B2B, finance, or data-driven content.
3. **Quote/question-in-a-panel** — The frame splits: photo on one side, an isolated headline or question in a flat-color panel on the other. Proximity/grouping + legibility through isolation. Legal, coaching, or advisory content built on a direct hook question.
4. **Two-tone keyword highlight** — Headline set in one neutral color except a single keyword recolored in the accent. Selective contrast trains a repeated scan pattern. Benefit-driven, educational series of 12+ posts where retention across the series matters more than any one post.
5. **Diagonal/split color-block background** — The background itself divides on a diagonal or hard line into two brand colors, subject placed on or straddling the seam. Dynamic asymmetry implies motion in a static image. Construction, logistics, auctions — any “moving forward” narrative.
6. **Cutout/collage subject breaking the frame** — A photo subject is cut out and bleeds past the tile edge or overlaps a color block instead of sitting in a clean rectangle. Pattern-interrupt via broken boundaries. Youth, creative, or fashion-adjacent brands wanting an energetic, non-corporate feel.
7. **Repeated/textural type-as-pattern** — The core keyword repeats at different scales/rotations/opacities to fill the frame, often with a rough texture. Redundancy for guaranteed delivery + texture as an urgency signal. Flash sales, launches, anything needing felt urgency.
8. **Native-UI mimicry** — The design embeds a phone frame, browser-style chrome, or literal Story UI elements (avatar, handle, tabs). Authenticity signaling via platform chrome. Portfolio/social-proof posts or app promotion that benefits from feeling “caught in the wild” rather than staged.

**Cross-cutting habits** (default even without a matching pattern): restrict every post to a **2–3 color max** system; fix one footer/header brand-lockup zone in the same position tile-to-tile; keep headlines to **2–6 words** — brevity itself is a hierarchy signal.

## Step 1 — Learn from reference posts (only when references are provided)

For each reference post, analyze its **structure — not its content**:

- **Grid & focal point** — symmetric or asymmetric, rule-of-thirds placement, where the eye lands first.
- **Visual hierarchy** — read order (headline → image → CTA, or reverse), what size/weight contrast drives that order.
- **Type pairing** — display vs. body relationship, headline line count and word count.
- **Color & contrast** — how many colors carry the composition, where the highest-contrast element sits.
- **Whitespace / margin ratio** — breathing room vs. content, edge-to-content spacing.
- **Hook / pattern interrupt** — the one element built to stop a scrolling thumb (oversized text, unexpected crop, high-contrast color block).
- **CTA placement** — where it sits and how it’s visually separated from the rest.

For each observation, name the **design principle** it demonstrates (rule of thirds, F-pattern scan, proximity/grouping, contrast hierarchy, thumb-stop pattern interrupt, etc.) — capture the **why**, not just the what.

Write the result as a short **layout brief** in words and ratios only — e.g. “single bold headline in top third, high-contrast subject centered on lower two-thirds, CTA bottom-right in accent color, ~40% negative space.” Never store or reproduce the reference’s actual photo, artwork, logo, or copy — structure only.

### Persist what’s learned

Check for a page or section named **Social — Pattern Library** in the user’s connected doc or file (Notion, brand wiki, design tool notes, etc.). If it doesn’t exist, create it — seed it with the eight patterns above on first creation so the library starts populated, not empty. Add one small annotated frame per new pattern discovered afterward: name, the layout brief, the principle(s) it demonstrates, and when to use it. This library accumulates across runs — before writing a fresh layout brief, check whether a matching pattern (seed set, platform, or style already logged) exists and reuse it instead of re-deriving it.

## Step 2 — Compose the post

1. Pull primary/secondary color tokens, text styles, and logo/lockup components from the connected library — do not use raw hex values or freehand text styles unless the system has no tokens (then document that gap).
2. Pick a layout brief: one freshly derived in Step 1, a match from **Social — Pattern Library**, or — if neither applies — the closest fit from the seed pattern library above. Use its structure — grid position, hierarchy order, hook placement, whitespace ratio — as the composition target. Map it onto brand tokens; never carry over a reference’s literal colors, imagery, or wording.
3. Reuse existing components (buttons, badges, tags, logo lockups) wherever the post needs one instead of drawing new shapes.
4. Compose a headline (aim for **8 words or fewer**), a supporting line, and a CTA if one was requested.
5. Apply the platform’s **safe-margin/padding** token — do not eyeball spacing.
6. Produce **2–3 layout variants** (image-led, text-led, quote-style) so there’s a choice, not a single take.
7. Check **legibility at thumbnail scale:** flag any text that would be unreadable at small size instead of shipping it silently.

## Guardrails — do not bend

- Never introduce a color outside the bound token set.
- Never stretch, recolor, or reposition the logo outside its documented lockup rules.
- Do not fabricate stats, testimonials, or claims in placeholder copy — mark placeholder text clearly as placeholder.
- When learning from reference posts: extract **structural/compositional patterns only.** Never trace, screenshot-paste, closely mimic exact wording, or reproduce a reference’s copyrighted photo, artwork, or logo.
- Adapt the treatment — do not copy a layout one-to-one, whether the source is Mobbin, a reference post, or an entry from the pattern library.
- Reference-post analysis is for **internal design reasoning only** — do not output or restate a competitor’s or creator’s original copy verbatim.

## Output

If references were analyzed: the layout brief(s) plus the **Social — Pattern Library** entry created or matched, each with a one-line “why it works.”

Deliver:

- New frame(s) named `Social/{Platform}/{Variant}` (or equivalent in the user’s tool).
- Every fill, stroke, and text style bound to a token or existing style — no raw values.
- A short note naming which tokens/components were used and which layout pattern informed the composition — seed set, **Social — Pattern Library** match, or freshly derived — so it can be spot-checked quickly.
