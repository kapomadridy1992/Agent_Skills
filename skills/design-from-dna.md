---
name: design-from-dna
description: >-
  Creates new UI from selected Figma frame(s) by extracting design DNA, forming
  a creative thesis, then extending the system through strong layout exploration
  — authored, intentional work that avoids generic AI UI and predictable SaaS
  patterns. Use when generating new pages or directions that must feel like the
  same creative system as the source. Requires meaningful source frame(s); never
  modifies reference frames.
---

# Design from DNA (anti–UI slop)

Create new UI from selected Figma frame(s) by **learning existing design DNA first**, then extending it through layout exploration and creative direction.

The objective is **not** “good-looking UI.” The objective is work that feels:

- authored, intentional, contemporary, premium
- compositionally strong and specific to the selected design
- recognizably from the **same creative system**

Avoid generic AI UI, predictable SaaS patterns, surface decoration, and trend-driven styling.

## How to read this skill

- **Fact.** Figma structure conventions (frames, Auto Layout, variables/styles) and the user’s existing components when present.
- **Conflict.** “Best practice” landing templates vs. distinctive DNA from the source. Prefer a **distinctive decision supported by the source** over generic convention unless the source clearly uses that structure.
- **Practice.** Creative thesis, exploration modes, and slop detection — professional judgment, not automatic rules.

## Core principle

**Study first. Form a thesis. Design second.**

Before creating anything:

1. Read the selected frame(s).
2. Extract design DNA.
3. Identify what creates character.
4. Define a clear creative thesis for the new page.
5. Only then start designing.

Do **not** begin by assembling components, common landing-page patterns, or “what typically looks good.” Begin from the **selected design**.

---

## Step 1 — Read the selection

Inspect the complete selected Figma frame or frames. Read:

- Page structure, information hierarchy, section order
- Grid, columns, alignment, margins, spacing
- Typography, type scale, line lengths, text density
- Colors, image behavior, crops
- Components, borders, rules, surfaces, cards, icons, navigation
- Negative space, repetition, asymmetry, overlap, visual rhythm
- Interaction clues, editorial behaviors, layout exceptions

If multiple frames are selected: shared rules, intentional differences, recurring patterns, exceptions that create character.

Also inspect existing components, variables, styles, and variants when available.

**Never modify the selected reference frames.**

If no meaningful page/frame is selected, stop and ask the user to select source frame(s).

---

## Step 2 — Extract the design DNA

Summarize internally before designing.

### Layout DNA

Grid logic, content width, section proportions, spacing rhythm, alignment, full-width vs contained, symmetry vs asymmetry, density, whitespace, overlap, intentional grid breaks, vertical pacing.

### Typography DNA

Display and body roles, hierarchy, scale relationships, line-height, tracking, capitalization, labels, metadata, serif/sans relationships, alignment, oversized type, editorial treatments.

### Visual DNA

Dominant language, palette behavior, image treatment, materiality, borders, dividers, radius, shadows, gradients, masks, shapes, contrast, negative space, surface hierarchy.

### Component DNA

Recurring navigation, buttons, cards, section headers, labels, lists, image containers, tags, tabs, accordions, forms, CTAs, metadata patterns. Reuse existing components where appropriate.

### Composition DNA

How the designer creates focus, hierarchy, rhythm, contrast, tension, pacing, surprise, repetition, calm, density, section-to-section transitions. **Composition DNA matters more than copying component shells.**

---

## Step 3 — Design signature

Extract **5–10 specific signature behaviors** from the selected design (examples only — never add unsupported behaviors):

- Oversized typography as architecture
- Asymmetric columns, unusually large negative space
- Thin rules organizing content, editorial crops
- Restrained color with one accent
- Overlapping image and text planes
- Compressed metadata + oversized headlines
- Deliberate grid interruptions

---

## Step 4 — Creative tension

Determine what makes the selection interesting:

- Editorial or systematic? Restrained or expressive?
- Hierarchy from scale, spacing, density, color, or imagery?
- Where does the grid break? Where is tension? What is controlled vs unexpected?
- Which characteristic could be pushed further without losing identity?

Do **not** remove tension to make the interface more conventional.

---

## Step 5 — Concept thesis

Every direction starts with a **design thesis** — what the composition is trying to do. Examples (generate from actual DNA, do not copy blindly):

- **Typographic architecture** — Type organizes the page before containers.
- **Editorial compression** — Dense zones alternate with whitespace for rhythm.
- **Spatial narrative** — Scale, image placement, and transitions read as one story.

Never create a direction without a reason.

---

## Step 6 — Content handling

User-provided content, requirements, or docs are **source of truth.**

Do **not** invent claims, statistics, customers, testimonials, features, people, awards, or factual content.

If content is missing: lightweight placeholder copy only when needed to evaluate layout. Placeholders must be clearly replaceable, free of fake facts, and minimal on marketing fluff. Priority is **design**, not copywriting.

---

## Step 7 — Layout exploration

Do not repeat the exact composition of source frames. Preserve **principles**, not necessarily exact patterns.

When exploration is requested, produce **meaningfully different** strategies via hierarchy, scale, pacing, section structure, image placement, grid behavior, whitespace, density, typography, sequence, composition.

**Not meaningful:** variations that only change color, radius, card style, minor alignment/spacing, or image swap.

### Exploration modes (when multiple concepts requested)

| Mode | Intent |
| --- | --- |
| **01 — Native** | Natural extension; most structural behaviors preserved; immediately compatible with source. |
| **02 — Evolved** | Core DNA kept; push composition, hierarchy, rhythm, grid, visual relationships — newer but related. |
| **03 — Provocation** | Ambitious interpretation; may break secondary patterns while keeping core identity; push 1–2 defining traits — still same creative universe. |

No randomness for the sake of difference.

---

## Anti–UI slop rules

Do not automatically generate:

- Endless rounded cards, cards inside cards, unnecessary containers, excessive pills
- Generic bento grids, blue-purple SaaS gradients, random glassmorphism
- Repeated icon + title + paragraph blocks, centered everything
- Fake dashboards, arbitrary metrics, generic three-column features, testimonial walls
- Excessive shadows, meaningless decorative geometry, gradients “to look modern”
- Generic section labels, identical section spacing, predictable startup landing formulas

Especially avoid **Hero → Logo bar → 3 features → More cards → Testimonials → CTA** unless the selected design clearly supports it.

---

## Decision quality

Never decide something “because it looks good.” Every meaningful choice should improve at least one of: hierarchy, narrative, clarity, emphasis, rhythm, information organization, interaction, brand character, tension, surprise, memorability.

If an element only decorates without supporting composition, **remove it.**

---

## Design the page, not isolated sections

One composition strategy for the entire page. Before finalizing, ask: first/second read; where the page accelerates or breathes; density vs calm; dominant section; visual climax; grid changes; how sections lead into each other.

Avoid a collection of attractive sections with no relationship.

---

## Layout variety (when DNA supports it)

Consider asymmetric splits, editorial columns, oversized type, nested grids, staggered content, controlled overlaps, full-width moments, narrow reading columns, alternating density, offset imagery, modular systems, horizontal sequences, vertical narrative, deliberate empty space, scale shifts, grid interruptions — **only when they extend extracted DNA**, not as random injection.

---

## Typography as structure

Type may be navigation, hierarchy, structure, rhythm, separation, emphasis, composition. If source frames use strong typography, explore type replacing unnecessary boxes.

---

## Restraint

Premium ≠ more. Before adding: *Does the design need this?* Prefer fewer strong decisions, clear hierarchy, intentional whitespace, meaningful contrast, controlled repetition.

---

## Component usage

Before a new component: search the file, check variants, reuse or adapt when appropriate. Create new patterns when content or composition genuinely requires it. Do not force content into a component if it damages the design.

---

## Auto Layout and Figma quality

Build usable design work, not flattened art: frames, Auto Layout, logical nesting, components, variables, styles. Avoid unnecessary absolute positioning; use absolute only when intentional to composition.

---

## Creative director pass

After each direction, review:

- **Is there an idea?** One-sentence describable direction — if not, it may be only styling.
- **Authored composition?** Specific decisions vs generated look.
- **Enough contrast?** Large/small, dense/open, loud/quiet, image/type, structure/interruption.
- **Too safe?** Improve the most predictable section without breaking DNA.
- **Unnecessary devices?** Remove non-contributing decoration.
- **Memorable moment?** At least one clear identity beat.

---

## Slop detection

Redesign (do not merely polish) if you find: too many cards/containers, excessive rounding, repetitive layouts, uniform spacing, excessive centering, arbitrary gradients/icons, weak hierarchy, repeated feature patterns, same grid every section, decorative effects with no function, predictable page structure, no tension, everything equally important.

---

## Final DNA check

Compare output to source on: typography, grid, spacing, component, visual-language fidelity; composition quality; layout originality; creative-direction strength; **AI-slop risk**. If slop risk is high, run another design pass.

---

## Concept annotation

Beside each generated direction, add a concise annotation frame:

- **Concept** — short name
- **Thesis** — one or two sentences
- **Preserved** — key DNA behaviors kept
- **Pushed** — what was evolved or exaggerated
- **Why it works** — brief creative-director rationale for comparing concepts

---

## Final output

Create new frames **next to** the source. Name e.g. `[Page Name] — Native`, `[Page Name] — Evolved`, `[Page Name] — Provocation`, or concept names. Never overwrite source frame(s). Place annotation beside each concept.

---

## Final rule

Do not optimize toward generic “good UI” or AI-default modern websites.

**Understand the design. Find its principles. Form a point of view. Create a composition. Critique it. Refine it.**

When forced to choose between **generic best practice** and **a distinctive decision supported by source DNA**, prefer the distinctive decision.
