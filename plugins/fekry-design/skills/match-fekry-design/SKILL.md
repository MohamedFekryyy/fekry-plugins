---
name: match-fekry-design
description: Match Fekry Aiad's design philosophy, product taste, motion language, and implementation preferences. Use when designing, implementing, reviewing, or restyling interfaces that should feel like Fekry's own work across portfolio/editorial pages, SaaS and fintech tools, health-tech products, Arabic-first experiences, or glassmorphism-heavy experiments.
---

# Match Fekry Design

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

Use for dashboards, fintech, SaaS tools, admin panels, internal products, and workflow-heavy screens.

- Start from off-white or cool light surfaces like `#F1F0F4`, `#F7F7F7`, or `#F6F8FA`.
- Use crisp dark text like `#171717` or near-black.
- Choose one trust-building accent tied to the domain: navy `#08225A`, green `#176E44`, teal `#3D828E`, blue `#0099FF`, or lavender `#8787F4`.
- Keep cards, tables, charts, and summaries immediately legible.
- Favor medium-weight headings, tight hierarchy, subtle borders, and quiet hover states.
- Make the interface feel inevitable, not stripped-down for style points.

### 2. Editorial/Personal Mode

Use for portfolio pages, manifestos, narrative case studies, and personal-brand surfaces.

- Use a black or near-black canvas with white or warm-white type.
- Introduce one vivid accent, usually pink `#EC4899`, through highlights, links, glow strips, signatures, or hover cues.
- Pair a modern sans with `Instrument Serif` for headings and `Caveat` for notes or signatures.
- Add tactile atmosphere with paper/noise texture, postcard framing, soft border lines, masked media, or cinematic gradients.
- Let typography and writing lead. Keep composition poetic but controlled.
- Avoid random collage energy or “creative for creative’s sake” clutter.

### 3. Health Clarity Mode

Use for women’s health, medical guidance, wellbeing flows, family-oriented tools, and evidence-heavy onboarding.

- Reject fluffy wellness cliches unless explicitly requested.
- Prefer calm, evidence-first, non-patronizing interfaces.
- Use one of these proven directions:
- `Lena`: `#05272D`, `#3D828E`, `#47B8CC`, `#0099FF`, `#FCFDFF`
- `UHC`: `#8787F4`, `#99A0AE`, `#F6F8FA`, `#F0F0FE`
- `FertiScore`: `#F9F8F4`, `#C1F9CC`, `#1D2B24`
- Keep onboarding soft but confident. Favor readable cards, supportive prompts, and direct explanations.
- Let trust come from clarity and hierarchy, not from decorative softness.

### 4. Arabic Luxury/Community Mode

Use for Arabic-first communities, premium workshops, culturally specific brands, or event funnels.

- Default to `#1A170F` background, `#EAE8E6` foreground, and gold `#D4AF37`.
- Use a distinctive brand display face when available. `The Year of The Camel` is a strong precedent.
- Keep surfaces dark, layered, and refined rather than flashy.
- Use gold in controlled moments: progress, CTA, highlights, validation, or premium accents.
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

**3. Common conflict pairs:**

| Conflict | Base mode | Secondary mode allowed at |
|---|---|---|
| Health SaaS dashboard | Utility/Product | Onboarding, empty states, result reveals |
| Arabic fintech tool | Utility/Product | Marketing surface, login, premium upsell |
| Portfolio with case studies | Editorial/Personal | Case study detail screens (can shift to Utility feel) |
| Health app with heavy data | Health Clarity | Charts and data tables (pull in Utility density rules) |
| Experimental product demo | Glass/Experimental | Core content sections stay Utility underneath |
| Arabic health community | Arabic Luxury | Functional flows inside (shift to Health Clarity) |

**4. Never blend palettes across modes.**
If you use Lena's teal (`#3D828E`) as the primary, do not also pull in the editorial pink (`#EC4899`) as an accent. Pick one accent family and stay there.

**5. Typography can bridge. Palette cannot.**
`Instrument Serif` can appear in a Utility product for a hero headline or a celebratory moment. But the Utility surface colors stay intact. Typography is allowed to carry editorial warmth. Color is not.

**6. When genuinely unsure, ask:**
> *"Is the user here to complete a task or to feel something?"*
> Task → Utility base. Feeling → context-appropriate mode.

## Typography Rules

- Default to `Geist` or a modern sans for product UI.
- Use `Instrument Serif` for editorial headings and contrast moments.
- Use `Caveat` only for handwritten notes, signatures, annotations, or human fragments.
- Use `Marcellus` when the product needs a softer ceremonial or wellness tone.
- Use a custom local font for Arabic-first identity when the brand supports it.
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

- Use motion to reveal relationships and reduce cognitive load.
- Favor spring settings near `stiffness: 300-400`, `damping: 25-30`, `mass: 0.5-0.8`.
- Favor easing like `[0.22, 1, 0.36, 1]` or `[0.4, 0, 0.2, 1]`.
- Favor fade-plus-slide, staggered entrance, mild hover lift, gentle scale, parallax, or masked media.
- Keep most transitions in the `0.3s-0.8s` range.
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

## Product-Type Playbooks

### Fintech And SaaS

- Use the Utility/Product Default mode.
- Emphasize transparency, automation, and visual clarity.
- Use clean charts, trustworthy accents, and minimal decoration.

### Health And Wellness

- Use the Health Clarity mode.
- Remove anything that feels patronizing or cosmetically “feminine” without substance.
- Speak with confidence and evidence, not sentimentality.

### Portfolio And Thought Pieces

- Use the Editorial/Personal mode.
- Let the interface feel reflective, crafted, and slightly poetic without losing discipline.
- Use typographic contrast and tactile textures more than heavy UI chrome.

### Arabic Workshops And Premium Community Flows

- Use the Arabic Luxury/Community mode.
- Keep the experience culturally grounded, premium, and clear.
- Make RTL and typography feel native from the first pixel.

### Experimental Demos

- Use the Glass/Experimental mode.
- Keep the visual experiment anchored in a useful interaction.
- Preserve readability even when the effect is the point.

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

## Review Checklist

- Does every element earn its place?
- Would the interface still work if the “cool treatment” disappeared?
- Does motion clarify something real?
- Does the palette fit the product domain?
- Are there too many type voices?
- Does the interface feel authored instead of generic?
- Does the result reduce user effort?
- Does the design avoid hype, clutter, and false complexity?
- If the product is health-related, does it avoid pinkwashing and condescension?
- If the product is Arabic-first, does it feel natively RTL and culturally intentional?

## Source Anchors

Use these files as the strongest evidence for future refinement:

- `/Users/fekryaiad/fekryaiad.com/src/data/content.json`
  Extract Fekry’s core rules: `Design is not decoration`, `Context > hype`, `Build fast, edit slowly`, and the bias toward clarity, craft, and intent.
- `/Users/fekryaiad/fekryaiad.com/src/app/layout.tsx`
  Anchor the personal positioning: `Design Engineer / Tools, Systems, Interfaces` and `beautiful systems that work`.
- `/Users/fekryaiad/fekryaiad.com/src/styles/typography.ts`
  Anchor the restrained product hierarchy and the `920px` content rhythm.
- `/Users/fekryaiad/fekryaiad.com/src/components/GlassButton.tsx`
  Anchor the glassmorphism treatment: translucent surfaces, backdrop blur, disciplined shadow stack, and tactile physicality.
- `/Users/fekryaiad/fekryaiadsite/app/(app)/philosophy/page.tsx`
  Anchor the manifesto: utility, emotion, motion, typographic restraint, and human clarity.
- `/Users/fekryaiad/fekryaiadsite/app/(app)/components/Postcard.tsx`
  Anchor the editorial mode: black canvas, pink accent, `Instrument Serif`, `Caveat`, paper texture, and crafted emotional tone.
- `/Users/fekryaiad/fekryaiadsite/site-design.json`
  Anchor the personal-site palette, spacing, and typography system.
- `/Users/fekryaiad/fekryaiad.com/src/data/case-studies/lena-app.json`
  Anchor the anti-pinkwashing health position and evidence-first tone.
- `/Users/fekryaiad/smart-link/app/globals.css`
  Anchor Lena’s teal/navy trust palette.
- `/Users/fekryaiad/UHC/UHC/views/ChatScreen.swift`
  Anchor the clean healthcare palette with `#8787F4` on `#F6F8FA`.
- `/Users/fekryaiad/framer ai/fertiscore/src/routes/+page.svelte`
  Anchor the fertility-paper palette and calm green accent direction.
- `/Users/fekryaiad/Portfolio progression/Frame 30.png`
  Treat as screenshot evidence for FertiScore’s supportive, paper-toned, app-first health UI.
- `/Users/fekryaiad/rosseta/app/globals.css`
  Anchor the black/gold Arabic luxury system.
- `/Users/fekryaiad/rosseta/tailwind.config.ts`
  Anchor the exact Rosetta token scales, surface opacities, and rounded radius values.
- `/Users/fekryaiad/Downloads/R-2.png`
  Treat as screenshot evidence for dark Rosetta branding and premium black-base composition.
- `/Users/fekryaiad/liquid-glass-demo/app/page.jsx`
  Anchor the more advanced liquid-glass interaction language and physical highlight logic.

Treat the code files as primary evidence and the screenshots as secondary confirmation.
