---
name: match-fekry-design-core
description: Portable version of Fekry Aiad's design philosophy without his project-specific tokens, brand palettes, or source files. Use when applying Fekry's design approach to your own projects, or as a starting point for building your own design skill.
---

# Match Fekry Design (Core)

## Overview

Match Fekry by optimizing for utility first, then emotional precision. Build interfaces that earn their place, reduce the distance between user intent and outcome, and feel authored rather than trend-chased.

## Start Here

- Identify the product context before choosing visuals. Do not flatten everything into one house style.
- Build the structural version first. Add atmosphere only after hierarchy, flows, and comprehension are already strong.
- Remove filler before adding flourish.
- Prefer one memorable move over five generic ones.

## Non-Negotiables

- Put function before ornament. Let beauty emerge from structure.
- Favor `context > hype`.
- Keep complexity transparent to the user.
- Use motion to explain, orient, reassure, or add trust. Do not animate for its own sake.
- Keep typography restrained. Use one main voice and one contrast voice; add a third only for intentional editorial or signature moments.
- Make every element earn its place.
- Avoid patronizing, over-cute, or pinkwashed health design.
- Default to clarity, craft, and real user value over trend mimicry.

## Pick A Style Mode

### 1. Utility/Product Default

Use for dashboards, SaaS tools, admin panels, fintech, and workflow-heavy screens.

- Start from off-white or cool light surfaces.
- Use crisp near-black text.
- Choose one trust-building accent tied to the domain.
- Keep cards, tables, charts, and summaries immediately legible.
- Favor medium-weight headings, tight hierarchy, subtle borders, and quiet hover states.
- Make the interface feel inevitable, not stripped-down for style points.

### 2. Editorial/Personal Mode

Use for portfolio pages, manifestos, narrative case studies, and personal-brand surfaces.

- Use a black or near-black canvas with white or warm-white type.
- Introduce one vivid accent through highlights, links, glow strips, or hover cues.
- Pair a modern sans with `Instrument Serif` for headings and `Caveat` for notes or signatures.
- Add tactile atmosphere with paper/noise texture, postcard framing, soft border lines, masked media, or cinematic gradients.
- Let typography and writing lead. Keep composition poetic but controlled.
- Avoid random collage energy or "creative for creative's sake" clutter.

### 3. Health Clarity Mode

Use for health products, medical guidance, wellbeing flows, family-oriented tools, and evidence-heavy onboarding.

- Reject fluffy wellness cliches unless explicitly requested.
- Prefer calm, evidence-first, non-patronizing interfaces.
- Build the palette from calm, trustworthy hues appropriate to the specific product.
- Keep onboarding soft but confident. Favor readable cards, supportive prompts, and direct explanations.
- Let trust come from clarity and hierarchy, not from decorative softness.

### 4. Arabic Luxury/Community Mode

Use for Arabic-first communities, premium workshops, culturally specific brands, or event funnels.

- Default to dark, warm, layered surfaces with a restrained metallic or premium accent.
- Use a distinctive brand display face when available.
- Keep surfaces dark, layered, and refined rather than flashy.
- Use the premium accent in controlled moments: progress, CTA, highlights, validation.
- Preserve RTL completely. Do not treat Arabic as a translated afterthought.
- Prefer fully rounded controls, subtle glow, and compact polished spacing.

### 5. Glass/Experimental Mode

Use for prototypes, floating controls, hero interactions, command palettes, status overlays, or future-facing demos.

- Use backdrop blur, translucent fills, internal highlights, and disciplined shadow stacks.
- Use plus-lighter or overlay blending only where it improves depth.
- Allow tilt, pointer-follow highlights, or refractive effects only if content stays legible.
- Keep the layout underneath strong and simple. Do not let the effect dissolve the interface into visual mush.
- Apply the treatment to specific layers, not the whole page.

## Mode Conflict Resolution

When a product sits between two modes, use this priority order. Do not blend freely.

**1. Function beats atmosphere.**
If the primary user job is task completion (dashboards, data entry, workflows), default to Utility/Product even if the domain is health or wellness. Apply Health Clarity only for onboarding, guidance, and emotional touchpoints within the same product.

**2. The heaviest user need wins the base mode.**
Identify where the user spends 80% of their time. That context sets the base mode. The secondary mode is allowed only at the edges: empty states, modals, celebratory moments, onboarding flows.

**3. Never blend palettes across modes.**
Whatever accent family the base mode establishes, do not pull in a second accent family from another mode. Pick one and stay there.

**4. Typography can bridge. Palette cannot.**
A contrast serif can appear in a Utility product for a hero headline or a celebratory moment. But the Utility surface colors stay intact. Typography is allowed to carry editorial warmth. Color is not.

**5. When genuinely unsure, ask:**
> *"Is the user here to complete a task or to feel something?"*
> Task → Utility base. Feeling → context-appropriate mode.

## Typography Rules

- Default to a modern sans for product UI.
- Use `Instrument Serif` for editorial headings and contrast moments.
- Use `Caveat` only for handwritten notes, signatures, annotations, or human fragments.
- Use a softer ceremonial serif when the product needs a wellness or ritual tone.
- Prefer medium weight and tracking-tight over loud ultra-bold UI.
- Keep long-form reading width around `700px`.
- Keep general content containers around `920px` when the layout benefits from focus and breathing room.
- Let headers invite. Let body copy hold the room.

## Color Rules

- Choose palette by domain truth, not by trend.
- Treat accent color as a structural tool for emphasis, state, and trust.
- Use neutrals generously and let the accent do focused work.
- Prefer slightly warm or soft neutrals over sterile pure white when the product is human-centered.
- Preserve strong contrast even in atmospheric or textured compositions.
- Avoid purple-by-default unless the surrounding brand language already supports it.

## Layout Rules

- Use generous negative space and obvious hierarchy.
- Favor simple modular sections over overloaded composites.
- Use thin borders or low-alpha separators instead of heavy chrome.
- Prefer rounded values like `6px`, `10px`, or `14px` on product surfaces.
- Use full pills for CTAs, chips, and inputs when the brand direction supports softness.
- Use texture, background video, dither, or gradient only when text remains dominant and readable.
- Keep narrative sections clean enough to read as writing, not as marketing noise.

## Motion Rules

Before animating anything, answer two questions in order:

1. **How often will the user trigger this?** High-frequency interactions (repeated actions, list navigation, toggles the user hits constantly) get minimal or no animation. Save motion budget for moments the user sees occasionally: modals, reveals, onboarding, celebrations.
2. **What does this animation clarify?** Hierarchy, state, spatial relationship, or mood. If the honest answer is "it looks cool", cut it.

Then apply the values:

- Use motion to reveal relationships and reduce cognitive load.
- Micro-interactions (press feedback, hovers, toggles, small reveals): target `120-200ms`, hard cap `250ms`.
- Macro transitions (modals, drawers, page-level reveals, hero moments): `300-600ms`.
- Favor spring settings near `stiffness: 300-400`, `damping: 25-30`, `mass: 0.5-0.8`.
- Favor easing like `[0.22, 1, 0.36, 1]` or `[0.4, 0, 0.2, 1]`.
- Favor fade-plus-slide, staggered entrance, mild hover lift, gentle scale, parallax, or masked media.
- Use infinite motion only for subtle glow, marquee, or ambient background behavior.
- If an animation does not clarify hierarchy, state, or mood, cut it.

## Component Biases

### Buttons

- Prefer strong silhouettes: full-pill or softly rounded.
- Use medium or bold labels only when the action must feel decisive.
- Keep shadows subtle in product mode and more tactile in glass mode.

### Inputs And Forms

- Prefer transparent, bordered, or softly translucent shells over heavy filled blocks.
- Keep validation direct and human.
- Make forms feel easy, calm, and trustworthy.

### Cards

- Make cards useful first.
- Use shadow only to establish layer separation.
- Avoid decorative containers that do not improve comprehension.

### Status And Metadata

- Use dots, badges, chips, and tiny labels to communicate state quickly.
- Keep secondary metadata quiet but legible.

### Data UI

- Make charts and summaries readable at a glance.
- Use color-coding carefully and consistently.
- Prefer one-view comprehension over clever but fragmented composition.

## Writing And Tone

- Write directly and intelligently.
- Allow slight poetry only in editorial/personal contexts.
- Use language around clarity, crafted systems, intention, trust, and usefulness.
- Avoid inflated startup hype, vague futurism, and empty creative jargon.
- If a phrase sounds cool but says nothing, delete it.

## Build Order

1. Choose the correct mode.
2. Define structure, hierarchy, and task flow.
3. Set the type system and spacing rhythm.
4. Choose one domain-appropriate accent palette.
5. Add surface treatment, texture, or atmosphere.
6. Add motion only where it clarifies meaning or improves feel.
7. Review for restraint. Cut anything that does not earn its place.

## Accessibility Rules

- Respect `prefers-reduced-motion`. Reduced means gentler, not zero: keep opacity and color transitions that aid comprehension, remove positional movement and scale.
- Gate hover effects behind `@media (hover: hover) and (pointer: fine)` so touch devices don't trigger false hover states.
- In RTL contexts, mirror directional motion, directional icons, and reading order. Use logical CSS properties (`margin-inline-start`, `padding-inline-end`) instead of left/right.
- Atmospheric modes (editorial, glass, arabic luxury) never get a pass on contrast. If the texture or blur wins over legibility, the treatment loses.

## Review Output Format

When reviewing a design or UI code against this skill, always output a single markdown table:

| What I'd change | Why | Which rule |
| --- | --- | --- |

One row per issue. "Which rule" points at the section of this skill the issue violates. Do not review as loose prose paragraphs or scattered before/after fragments; the table forces every critique to be specific, justified, and traceable.

## Review Checklist

- Does every element earn its place?
- Would the interface still work if the "cool treatment" disappeared?
- Does motion clarify something real?
- Does the palette fit the product domain?
- Are there too many type voices?
- Does the interface feel authored instead of generic?
- Does the result reduce user effort?
- Does the design avoid hype, clutter, and false complexity?
- If the product is health-related, does it avoid pinkwashing and condescension?
- If the product is Arabic-first, does it feel natively RTL and culturally intentional?

### Common Violations And Fixes

| Violation | Fix |
| --- | --- |
| Purple-by-default palette | Choose an accent from the product's domain truth |
| Two accent families mixed | Pick one accent family and stay there |
| Three or more type voices | Cut to one main voice plus one contrast voice |
| Decorative card containers | Remove the container or make it establish real layer separation |
| Animation without a purpose | Cut it, or tie it to hierarchy, state, or mood |
| Micro-interaction over `250ms` | Bring it into the `120-200ms` band |
| Same treatment on every surface | Apply atmosphere to specific layers, keep the rest quiet |
| Health UI that decorates instead of informs | Rebuild around evidence, clarity, and confident tone |
| RTL as flipped-LTR afterthought | Design RTL natively: mirrored motion, logical properties, culturally intentional type |
| Glass effect dissolving the layout | Strengthen the structure underneath, then reapply the treatment to one layer |
