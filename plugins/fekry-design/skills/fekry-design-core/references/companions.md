# Companion Skills

Two separate skills, made by other people, that go deeper than this one on a single job. They are optional. This skill decides *whether* one is needed and holds the result to the brief; the companion decides *how* it is built.

| Skill | Author | Use it for | Output |
| --- | --- | --- | --- |
| `stageshow` | Benji Taylor, [benjitaylor/skills](https://github.com/benjitaylor/skills) | Showing a product working: hero scene, feature card, bento grid, cursor walkthrough | React and plain CSS, still or animated |
| `hairline-create` | Lucas Marques, [lucasmarkes/hairline](https://github.com/lucasmarkes/hairline) | Giving an abstract idea a body: one isometric line figure that answers the pointer | One self-contained HTML file |
| `hairline-adopt` | same | The same, starting from an SVG icon, logo, or illustration | One self-contained HTML file |

## Which one

- The viewer needs to see **what the product does** → Stageshow.
- The viewer needs to grasp **an idea the product rests on** (layers, flow, sorting, signal) → Hairline.
- There is **real footage or a real screenshot** that tells it better → use that. Neither.
- The screen is the **working product** itself, not a page about it → neither, except a Hairline figure in a first-run or empty state.
- You cannot say what would be lost without it → neither.

By mode: Stageshow suits product pages in Utility and Health Clarity. Hairline suits Utility, Editorial, and Glass/Experimental, where one quiet object can carry a section. In Health Clarity, never let a figure stand in for evidence. In Arabic Luxury/Community, check that a monochrome line figure fits the surface before offering it.

One memorable move still holds. Pick one companion per view. If a long page needs both, give them separate sections and let one lead.

## Hand over the brief, don't re-interview

Pass the five-line brief from [interview.md](interview.md) plus the product's tokens (type, accent, radius, ground), then follow the companion's own workflow.

- **Stageshow:** Job becomes the story and payoff, Feel sets theme and fidelity, Not sets what to leave out. Real product language in the focal area. In RTL products, author the scene RTL: layout, cursor path, and mixed-direction text.
- **Hairline:** offer its two or three concepts as it asks; that is a real choice, not a repeat of the interview. Skip it only when the designer has already named the object and the gesture. Its own rules win inside the figure: one stroke color, no labels, no fills. The accent lives around it.

Both must hold on their own: a still frame that tells the story without motion, honored `prefers-reduced-motion`, and a text equivalent or `aria-hidden` when decorative. On touch, nothing essential may depend on hover.

Never present a faux screen as a real customer's data, or show a feature that does not exist as if it did.

## If it is not installed

Offer the command once, let the designer decide, and do not install it unasked:

```bash
npx skills add benjitaylor/skills --skill stageshow
npx skills add lucasmarkes/hairline
```

If they decline, build the move with what this skill has: typography, a cropped real screenshot, or a static SVG. Do not imitate a companion from memory.
