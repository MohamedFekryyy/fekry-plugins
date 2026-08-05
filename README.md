# fekry-plugins

design skills for AI agents, by [fekry aiad](https://fekryaiad.com).

i'm a product designer who got tired of agents shipping the same templated ai-looking interfaces. so i wrote my taste down. this repo is how i hand it to any agent i work with, and now to you.

## what's inside

one plugin, one skill: **match-fekry-design-core**.

my design philosophy, five style modes, motion language, and implementation rules, packaged so any agent can apply them. use it as-is if you like how i think, or fork it and swap in your own taste. honestly the best use of this repo is as a template for writing your own design skill.

the five modes:

- utility/product: dashboards, saas, fintech. clarity or nothing
- editorial/personal: portfolios and manifestos. dark canvas, serif headlines, one loud accent
- health clarity: evidence-first health products. zero pinkwashing
- arabic luxury/community: dark, layered, gold in controlled doses. RTL native from the first pixel
- glass/experimental: blur and refraction, but the layout underneath stays honest

plus conflict resolution rules for when a product sits between two modes, so the agent doesn't guess.

## install

### claude code

```
/plugin marketplace add MohamedFekryyy/fekry-plugins
/plugin install fekry-design@fekry-plugins
```

updates come with every commit. force a refresh with `/plugin marketplace update fekry-plugins`.

### codex or any other agent

the skills are plain SKILL.md, spec-compliant agent skills. no claude-only fields. skip the marketplace and copy the folders:

```bash
git clone https://github.com/MohamedFekryyy/fekry-plugins
cp -r fekry-plugins/plugins/fekry-design/skills/* ~/.codex/skills/
```

or drop them in `~/.agents/skills/` to cover gemini cli and friends in one go.

## the short version of the philosophy

design is not decoration. every element earns its place or gets cut. context beats hype. build fast, edit slowly. one memorable move beats five generic ones. if a phrase sounds cool but says nothing, delete it. same rule applies to UI.

## license

take it, fork it, make it yours. attribution appreciated, not required.
