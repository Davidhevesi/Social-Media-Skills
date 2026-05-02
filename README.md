# Social Media Skills for Claude Code

6 skills for business owners and entrepreneurs to build their social media presence using Claude Code. Run a discovery interview, generate post ideas, write hooks, build carousels, script videos, and repurpose everything — all inside your terminal.

---

## Skills

| Skill | Command | What it does |
|---|---|---|
| Social Strategy | `/social-strategy` | Discovery interview → positioning, pillars, platform focus |
| Content Ideas | `/content-ideas` | Generates weekly post ideas, themes, and angles |
| Hook Writing | `/hook-writing` | Writes scroll-stopping hooks for every platform |
| Carousel | `/carousel` | Builds slide-by-slide carousel posts with design notes |
| Short Form Video | `/short-form-video` | Scripts TikTok, Reels, and Shorts with B-roll shot list |
| Repurposing | `/repurposing` | Turns one piece of content into posts for every platform |

---

## How the Skills Chain Together

Run them in order for the best results:

```
/social-strategy → /content-ideas → /hook-writing → /carousel or /short-form-video → /repurposing
```

Each skill reads output files from previous skills automatically — no copy-pasting required.

---

## Output Files

Each skill saves its output to a file in your working directory:

| File | Created by |
|---|---|
| `SOCIAL-STRATEGY.md` | `/social-strategy` |
| `CONTENT-IDEAS.md` | `/content-ideas` |
| `HOOKS.md` | `/hook-writing` (appends — builds a swipe file) |
| `CAROUSELS.md` | `/carousel` (appends) |
| `VIDEO-SCRIPTS.md` | `/short-form-video` (appends) |
| `REPURPOSED.md` | `/repurposing` (appends) |

---

## Install

```bash
claude skills install ./social-strategy.md
claude skills install ./content-ideas.md
claude skills install ./hook-writing.md
claude skills install ./carousel.md
claude skills install ./short-form-video.md
claude skills install ./repurposing.md
```

---

## Skills

- [Social Strategy](./social-strategy.md)
- [Content Ideas](./content-ideas.md)
- [Hook Writing](./hook-writing.md)
- [Carousel](./carousel.md)
- [Short Form Video](./short-form-video.md)
- [Repurposing](./repurposing.md)
