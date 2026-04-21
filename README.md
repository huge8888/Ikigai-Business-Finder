# 🎯 pd-ikigai — AI Business Idea Finder

> A Claude skill that acts as your personal business coach — guiding you from "I don't know what to sell" to a validated business idea with a niche, unfair advantage, offer, and pricing in 25–35 minutes.

**Shared by [@0xHUGE](https://x.com/0xHuge) — follow for more AI tools and frameworks like this.**

---

## What is this?

**pd-ikigai** is a skill file for [Claude](https://claude.ai) that turns AI into a structured business coaching session using the **Ikigai framework** — a Japanese concept for finding your reason for being.

## How to use

### Step 1 — Install the skill in Claude

1. Download `pd-ikigai.skill` from this repo
2. Open [Claude.ai](https://claude.ai)
3. Go to **Skills** settings and upload the `.skill` file

### Step 2 — Start the session

Type `/huge-ikigai` in any Claude conversation and the AI will guide you through the full process.

### Step 3 — Answer honestly

The more specific your answers, the better your result. Claude will push back if your answers are too vague — that's intentional.

---

## The 7-stage process

| Stage | What happens |
|-------|-------------|
| 1 — Ikigai Discovery | 4 questions to find what you love, what you're good at, what the world needs, and what you can be paid for |
| 2 — Niche Sharpening | Drill down 3 layers until your ideal client says "this is exactly for me" |
| 3 — Market Research | AI searches Reddit, X, LinkedIn, and YouTube to find real gaps in your market |
| 4 — Unfair Advantage | Identify the combination of experience and story that makes you impossible to copy |
| 5 — Validation Check | 4-point check: pain intensity, purchasing power, ease to find, market growth |
| 6 — Offer + Pricing | Build your offer stack and set a price anchored to outcome value (not hours) |
| 7 — Final Summary | One-page business plan + 3 action steps for this week |

---

## Files in this repo

```
huge-ikigai/
├── README.md          ← You are here
├── pd-ikigai.skill    ← Upload this to Claude
└── SKILL.md           ← Raw skill instructions (readable)
```

---

## Changelog

**v2 (latest)**
- Added diverse niche examples beyond B2B (content creators, e-commerce, local business, education)
- Added fallback for when market research returns thin results
- Pricing now supports multiple currencies (USD, THB, and others)
- Stage 7 now ends with 3 concrete next actions instead of generic advice
- Added stuck handler — AI unlocks you when you can't answer a question
- Added restart handler — change direction mid-session without starting over

**v1**
- Initial release

---

## About

Shared by **0xHUGE** — building and sharing AI tools for creators, entrepreneurs, and curious humans.

- 𝕏 Twitter: [@0xHUGE](https://x.com/0xHuge)

If this helped you find your business idea, give it a ⭐ and share it with someone who needs it.

---

## License

MIT — free to use, modify, and share. Attribution appreciated but not required.
