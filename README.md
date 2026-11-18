# React Bits Effects — an AI skill for beautiful websites

A design playbook that teaches any AI assistant how to make a website beautiful with [React Bits](https://reactbits.dev) animated components — choosing effects that fit **what the website is**, instead of decorating at random.

## How to use it

Give [`SKILL.md`](./SKILL.md) to your AI (Claude, ChatGPT, Cursor, Copilot — any assistant that can read a skill/instructions file), then ask it to build or restyle your website. The AI will:

1. Read your site's type, mood and content shape first
2. Pick a core set of 3–5 effects that match (dashboard, portfolio, landing page, gallery, blog, e-commerce, event page…)
3. Place them by the placement map — one background, one heading treatment, one deck style
4. Follow the composition and safety rules — motion stays subtle, content is never hidden, everything still works on touch and reduced-motion

## What's inside SKILL.md

- **The core set** — 13 proven, versatile components with placement guidance (TiltedCard, SplitText, LetterGlitch, CursorGrid, BorderGlow, DepthText, TextType, ScrollReveal, CardSwap, Shredder, BranchedMenu, StickerPeel, FlipCard)
- **The complete free library index** — all **217 free** React Bits components with their exact install commands, grouped by category:
  - Text Animations · 33
  - Animations · 38
  - Components · 48
  - Micro · 34
  - Backgrounds · 64
- **Selection tables by website type**, a placement map, composition rules and non-negotiable implementation/safety rules

## Example command

Every component installs the same way:

```bash
npx shadcn@latest add @react-bits/TiltedCard-JS-CSS
```

## Free vs Pro

Everything in this skill is **free** — all 217 components on reactbits.dev. "React Bits Pro" is a separate paid library on a different site and is not included here.

## Credits

Components by [React Bits](https://reactbits.dev) (David Haz). This repo is a curated skill/index — it contains no React Bits source code, only component names, install commands and design guidance.
