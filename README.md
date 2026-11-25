# fekry-plugins

design skills for AI agents, by [fekry aiad](https://fekryaiad.com).

i'm a product designer who got tired of agents shipping the same templated ai-looking interfaces. so i wrote my taste down. this repo is how i hand it to any agent i work with, and now to you.

## what's inside

one plugin, one skill: **fekry-design-core**.

my design philosophy, five style modes, motion language, and the implementation craft underneath, packaged so any agent can apply them. use it as-is if you like how i think, or fork it and swap in your own taste. honestly the best use of this repo is as a template for writing your own design skill.

every section leads with the judgment call, then the defaults that hold it up: type craft and measure, semantic color tokens, motion timing and interruption, accessibility as structure rather than a final pass, and UI copy rules. taste picks the direction. craft is what survives real content, real devices, and real users.

the five modes:

- utility/product: dashboards, saas, fintech. clarity or nothing
- editorial/personal: portfolios and manifestos. dark canvas, serif headlines, one loud accent
- health clarity: evidence-first health products. zero pinkwashing
- arabic luxury/community: dark, layered, gold in controlled doses. RTL native from the first pixel
- glass/experimental: blur and refraction, but the layout underneath stays honest

plus conflict resolution rules for when a product sits between two modes, so the agent doesn't guess.

## it asks before it designs

open brief? the agent asks you two to four questions, in one message, each with a suggested answer so "go with yours" works. the job, the feel, the limits, and the one thing people should remember. then it plays the brief back in five lines and starts.

small edits, reviews, and clear briefs skip the interview. and your answers beat my taste. they don't beat accessibility.

## pairs well with

two skills by other people that i use all the time. optional, installed separately. mine decides if you need one and passes it your brief so you don't get interviewed twice.

- [stageshow](https://github.com/benjitaylor/skills) by benji taylor: believable product UI, still or animated, for heroes and feature cards
- [hairline](https://github.com/lucasmarkes/hairline) by lucas marques: isometric line figures that answer the pointer, from an idea or your own svg

```bash
npx skills add benjitaylor/skills --skill stageshow
npx skills add lucasmarkes/hairline
```

## install

### claude code

```
/plugin marketplace add MohamedFekryyy/fekry-plugins
/plugin install fekry-design@fekry-plugins
```

heads up: installed plugins stay pinned to the commit you installed. to get my updates automatically, flip one toggle: `/plugin` > marketplaces > fekry-plugins > enable auto-update. new commits then land on your next session start.

### codex or any other agent

the skills are plain SKILL.md, spec-compliant agent skills. no claude-only fields. skip the marketplace and copy the folders:

```bash
git clone https://github.com/MohamedFekryyy/fekry-plugins
cp -r fekry-plugins/plugins/fekry-design/skills/* ~/.codex/skills/
```

or drop them in `~/.agents/skills/` to cover gemini cli and friends in one go.

## the short version of the philosophy

design is not decoration. every element earns its place or gets cut. context beats hype. build fast, edit slowly. one memorable move beats five generic ones. if a phrase sounds cool but says nothing, delete it. same rule applies to UI.

## renamed

`match-fekry-design-core` is now `fekry-design-core`. if you copied the folder by hand, delete the old one first so you don't end up with both.

## license

take it, fork it, make it yours. attribution appreciated, not required.
