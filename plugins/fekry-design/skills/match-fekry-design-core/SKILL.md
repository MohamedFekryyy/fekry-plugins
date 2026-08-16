---
name: match-fekry-design-core
description: Portable version of Fekry Aiad's design philosophy and implementation craft, without his project-specific tokens, brand palettes, or source files. Covers style modes, typography, color tokens, motion, accessibility, and UI copy. Use when designing or reviewing an interface with Fekry's approach, or as a starting point for building your own design skill.
---

# Match Fekry Design (Core)

## Overview

Match Fekry by optimizing for utility first, then emotional precision. Build interfaces that earn their place, reduce the distance between user intent and outcome, and feel authored rather than trend-chased.

Taste decides what to build. Craft decides whether it survives contact with real users, real content, and real devices. This skill carries both: each section leads with the judgment call, then the implementation defaults that hold it up.

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
- Use the native element. A `<div>` wearing a click handler is a bug, not a style choice.
- Never let color be the only carrier of meaning.
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

### Voice

- Default to a modern sans for product UI.
- Use `Instrument Serif` for editorial headings and contrast moments.
- Use `Caveat` only for handwritten notes, signatures, annotations, or human fragments.
- Use a softer ceremonial serif when the product needs a wellness or ritual tone.
- Prefer medium weight and tracking-tight over loud ultra-bold UI.
- Let headers invite. Let body copy hold the room.

### Measure And Rhythm

- Cap the measure at 60-75 characters. At typical body sizes that lands near `700px`.
- Keep general content containers around `920px` when the layout benefits from focus and breathing room.
- Use `text-wrap: balance` on headings and `text-wrap: pretty` on short descriptions. Use neither in long-form text; both fight the reader over multiple paragraphs.

### Craft

- Ship `.woff2` on the web. Never `.ttf` or `.otf`.
- Apply `font-variant-numeric: tabular-nums` to every number that changes in place and to every table column: timers, counters, prices, metrics. Skip it when the face is already monospace. Numbers that jitter as they update read as broken, not alive.
- Set `-webkit-font-smoothing: antialiased` and `-moz-osx-font-smoothing: grayscale` once on the root. Never per component.
- Use `overflow-wrap: break-word` anywhere a long word, URL, or ID can escape its container. Use `white-space: nowrap` on labels, chips, and badges that must stay on one line.
- Store copy in its natural case and control presentation with `text-transform`. Never bake shouting into the content layer.
- Use real punctuation: curly quotes, en dash for ranges, em dash for asides, and the single ellipsis character.
- Set `text-underline-position: from-font` with `text-decoration-skip-ink: auto` so underlines clear descenders.
- When text truncates, keep the full value reachable through a tooltip, an expanded view, or a detail surface. Truncation is a display choice, never data loss.

## Color Rules

### Palette

- Choose palette by domain truth, not by trend.
- Treat accent color as a structural tool for emphasis, state, and trust.
- Use neutrals generously and let the accent do focused work.
- Prefer slightly warm or soft neutrals over sterile pure white when the product is human-centered.
- Preserve strong contrast even in atmospheric or textured compositions.
- Avoid purple-by-default unless the surrounding brand language already supports it.
- Give every step in the scale a job: page background, raised surface, hover, border, solid fill, body text. If no role claims a step, cut it.
- Author the dark palette on its own terms. A dark mode is not the light palette reversed.

### Tokens

- Separate primitives from tokens. The primitive is the raw value (`--blue-500`); the token is how that value is used (`--color-text-secondary`). Components reference tokens only.
- Name tokens for their role, never for their appearance or their first use. `--color-accent-solid`, not `--color-blue-button` or `--color-sidebar-gray`.
- Reserve `accent` for the brand color so `primary` never has to mean both the brand and the main body text.
- Never borrow a token from another role because the color happens to match. When that role changes, your element changes with it. Add a token for the new role instead.
- Measure contrast against the surface the element actually renders on, not the page background. Overlays, cards, and translucent panels each shift the baseline.
- Pick one theme-switching mechanism, `prefers-color-scheme` or a `.dark` class, and drive every token through it.
- Set gradient interpolation deliberately: `in oklab` for even brightness, `in oklch` for more vivid midtones, or omit it and accept the muted sRGB midpoint.

## Layout Rules

- Use generous negative space and obvious hierarchy.
- Favor simple modular sections over overloaded composites.
- Let spacing carry the grouping: the gap between groups is at least twice the gap inside one. `8px` within, `16px` or more between.
- Use thin borders or low-alpha separators instead of heavy chrome.
- Prefer rounded values like `6px`, `10px`, or `14px` on product surfaces.
- Match nested radii concentrically. The inner radius equals the outer radius minus the padding between them, so corners stay parallel instead of drifting.
- Use full pills for CTAs, chips, and inputs when the brand direction supports softness.
- Align optically, not geometrically. Trust the eye over the bounding box for icons, glyphs, and anything with uneven visual weight.
- Give images a `1px` outline offset by `-1px`, black at `8%` opacity in light mode and white at `8%` in dark, so a pale photo never bleeds into a pale surface.
- Never set fixed widths or heights on text containers. Content length changes; the box has to move with it.
- Use logical properties (`margin-inline-start`, `padding-inline-end`, `inset-inline`) by default, not left and right. This is what makes RTL a configuration instead of a rewrite.
- Use texture, background video, dither, or gradient only when text remains dominant and readable.
- Keep narrative sections clean enough to read as writing, not as marketing noise.

## Motion Rules

Before animating anything, answer two questions in order:

1. **How often will the user trigger this?** High-frequency interactions (repeated actions, list navigation, hover states in a long list, toggles the user hits constantly) get minimal or no animation. Save motion budget for moments the user sees occasionally: modals, reveals, onboarding, celebrations.
2. **What does this animation clarify?** Hierarchy, state, spatial relationship, or mood. If the honest answer is "it looks cool", cut it.

Then apply the values:

- Use motion to reveal relationships and reduce cognitive load.
- Micro-interactions (press feedback, hovers, toggles, small reveals): target `120-200ms`, hard cap `250ms`.
- Macro transitions (modals, drawers, page-level reveals, hero moments): `300-600ms`.
- Favor spring settings near `stiffness: 300-400`, `damping: 25-30`, `mass: 0.5-0.8`.
- Favor easing like `[0.22, 1, 0.36, 1]` or `[0.4, 0, 0.2, 1]`.
- Favor fade-plus-slide, staggered entrance, mild hover lift, gentle scale, parallax, or masked media.
- Stagger staged entrances by around `100ms`, grouped either by element or by cluster.
- Use infinite motion only for subtle glow, marquee, or ambient background behavior.
- If an animation does not clarify hierarchy, state, or mood, cut it.

### Craft

- Name the exact properties that transition. Never `transition: all`; it animates things you never chose and pays for them every frame.
- Use CSS transitions for anything the user can interrupt mid-flight. Use keyframes only for sequences that run once, start to finish.
- Give pressed buttons a scale between `0.95` and `0.98` with `transition: scale 200ms ease-out`. The press should feel acknowledged, not squashed.
- Cross-fade swapped icons: the entering icon runs scale `0.25` to `1`, opacity `0` to `1`, blur `4px` to `0`; the exiting icon reverses it.
- Apply `will-change` only to properties that genuinely change, and only `transform`, `opacity`, or `filter`.
- When an element drifts by a pixel or two mid-animation, especially in Safari on iOS, add `will-change: transform` to pin it to its own layer.
- Kill every transition while the theme swaps. A light-to-dark flip should be instant, not a slow bleed through every token on the page.

## Component Biases

### Buttons

- Prefer strong silhouettes: full-pill or softly rounded.
- Use medium or bold labels only when the action must feel decisive.
- Keep shadows subtle in product mode and more tactile in glass mode.
- Make the press state physical: subtle scale down, immediate release.

### Inputs And Forms

- Prefer transparent, bordered, or softly translucent shells over heavy filled blocks.
- Keep validation direct and human.
- Make forms feel easy, calm, and trustworthy.
- Build them against the form rules in Accessibility. A beautiful form that fights the keyboard, the password manager, or the paste buffer is a broken form.

### Cards

- Make cards useful first.
- Use shadow only to establish layer separation.
- Avoid decorative containers that do not improve comprehension.

### Status And Metadata

- Use dots, badges, chips, and tiny labels to communicate state quickly.
- Pair every state color with an icon, a label, or a shape. Color alone is not a state.
- Keep secondary metadata quiet but legible.

### Data UI

- Make charts and summaries readable at a glance.
- Use color-coding carefully and consistently.
- Set numeric columns in tabular figures and align them on the decimal.
- Prefer one-view comprehension over clever but fragmented composition.

## Accessibility Rules

Accessibility is structural, not a pass at the end. Atmospheric modes (editorial, glass, arabic luxury) never get an exemption. If the texture or blur wins over legibility, the treatment loses.

### Semantics And Focus

- Use the correct native element: `<button>` for actions, `<a>` for navigation. Reach for a `<div>` only when nothing native fits.
- Style `:focus-visible`. Never remove an outline without designing its replacement.
- Use only `tabindex="0"` and `tabindex="-1"`. Positive values break the natural tab order.
- Give icon-only controls a descriptive `aria-label`, and never put `aria-hidden="true"` on anything focusable.
- Write alt text by purpose, not appearance: `alt="Search"` on a search button, not `alt="magnifying glass"`. Decorative images get `alt=""`.
- Make the skip-to-content link the first focusable element, and add `scroll-margin-top` to anchored headings so they don't land under a sticky header.

### Forms And Inputs

- Give every input a real `<label>`, the right `type`, and the right `inputmode`.
- Never block paste. People paste passwords and one-time codes.
- Keep submit enabled until the request starts. Validate on submit: set `aria-invalid="true"`, point `aria-describedby` at the error, and move focus to the first invalid field. A disabled submit button hides the reason it's disabled.
- Never hang a tooltip off a `disabled` control; it never opens for keyboard or touch. Put the explanation in visible text beside it, or use `aria-disabled="true"` so the control stays focusable.

### Targets And Pointers

- Keep hit areas at `24x24px` minimum, `40x40px` on desktop where the layout allows, and `44x44px` on touch. Extended hit areas must never overlap.
- Set `pointer-events: none` on decorative layers such as glows, gradients, and noise, so they never swallow a click meant for a control.
- Gate hover effects behind `@media (hover: hover) and (pointer: fine)`. On touch, `:hover` sticks after a tap and reads as selected.

### Feedback And Status

- Use `role="status"` for routine updates and reserve `role="alert"` for urgent errors.
- Signal every status change with more than color: an icon, a label, or an underline.

### Motion And Direction

- Wrap positional and scale motion in `@media (prefers-reduced-motion: no-preference)`. Leave opacity and color transitions running: reduced means gentler, not zero, and those still carry meaning.
- In RTL contexts, mirror directional motion, directional icons, and reading order. Logical properties handle the spacing; direction of travel is still your call.

## Writing And Tone

### Voice

- Write directly and intelligently.
- Address the reader as "you", never "the user".
- Allow slight poetry only in editorial/personal contexts.
- Use language around clarity, crafted systems, intention, trust, and usefulness.
- Avoid inflated startup hype, vague futurism, and empty creative jargon.
- If a phrase sounds cool but says nothing, delete it.

### UI Copy

- Start button labels with a verb: "Save draft", "Delete project". Never "OK!" or a bare "Yes".
- Repeat the consequence in confirmation buttons: "Delete project" beside "Cancel", so the destructive choice is never the ambiguous one.
- Pick one word per flow and hold it at every step. "Continue" or "Next", never both.
- Name the destination in link text: "Read docs", never "Click here".
- Capitalize buttons, headings, and labels the same way everywhere. Sentence case is the safer default.
- Label toggles with the state they turn on: "Send read receipts", not "Disable read receipts".
- Orient the reader in empty states and offer one next action. "No results" is a dead end, not a message.

## Build Order

1. Choose the correct mode.
2. Define structure, hierarchy, and task flow.
3. Build with native elements, real labels, and logical properties from the first pass.
4. Set the type system and spacing rhythm.
5. Choose one domain-appropriate accent palette, then define the semantic tokens components will actually reference.
6. Add surface treatment, texture, or atmosphere.
7. Add motion only where it clarifies meaning or improves feel.
8. Run the craft pass: contrast on real surfaces, keyboard path, hit areas, reduced motion, dark mode, RTL, long and empty content.
9. Review for restraint. Cut anything that does not earn its place.

## Review Output Format

When reviewing a design or UI code against this skill, always output a single markdown table:

| What I'd change | Why | Which rule |
| --- | --- | --- |

One row per issue. "Which rule" points at the section of this skill the issue violates. Do not review as loose prose paragraphs or scattered before/after fragments; the table forces every critique to be specific, justified, and traceable.

## Review Checklist

- Does every element earn its place?
- Would the interface still work if the "cool treatment" disappeared?
- Does motion clarify something real, and can it be interrupted?
- Does the palette fit the product domain?
- Do components reference semantic tokens instead of raw primitives?
- Was the dark palette authored, or just inverted?
- Are there too many type voices?
- Does spacing make the grouping obvious without borders?
- Can the entire flow be completed by keyboard, and is focus always visible?
- Does any state depend on color alone?
- Does the copy use one word per concept across the whole flow?
- Does the layout survive long content, empty content, and a narrow viewport?
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
| `transition: all` | Name the exact properties that change |
| Same treatment on every surface | Apply atmosphere to specific layers, keep the rest quiet |
| Raw primitive used inside a component | Reference a semantic token named for its role |
| Token borrowed from a different role | Add a token for the new role |
| Dark mode built by inverting light mode | Author the dark palette on its own terms |
| Contrast checked against the page, not the actual surface | Re-measure against the surface the element renders on |
| Equal spacing inside and between groups | Double the gap between groups |
| Fixed height on a text container | Let the box grow with the content |
| Nested corners drifting out of parallel | Set the inner radius to the outer radius minus the padding |
| Numbers jittering as they update | Set `font-variant-numeric: tabular-nums` |
| `div` wired up as a button | Use the native element |
| `outline: none` with no replacement | Style `:focus-visible` |
| Icon-only button with no accessible name | Add a descriptive `aria-label` |
| Tooltip attached to a `disabled` control | Move the explanation into visible text, or use `aria-disabled` |
| Submit disabled until the form is "valid" | Keep it enabled, validate on submit, focus the first invalid field |
| State signalled by color alone | Add an icon, a label, or a shape |
| Decorative glow eating clicks | Set `pointer-events: none` on the decorative layer |
| "Click here" or bare "OK" labels | Verb-first labels naming the destination or the consequence |
| Health UI that decorates instead of informs | Rebuild around evidence, clarity, and confident tone |
| RTL as flipped-LTR afterthought | Design RTL natively: logical properties, mirrored motion, culturally intentional type |
| Glass effect dissolving the layout | Strengthen the structure underneath, then reapply the treatment to one layer |
