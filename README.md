# JJ's AI Writing Style Guide

Train AI to write like you — across newsletters, X posts, LinkedIn, and YouTube.

---

## Watch the Full Tutorial

[![Watch the Guide](https://img.youtube.com/vi/6LzUtXC8cKc/maxresdefault.jpg)](https://youtu.be/6LzUtXC8cKc?si=DYu44gzvWzA52C9q)

**[Watch: How to Build Your Own AI Writing Style Guide](https://youtu.be/6LzUtXC8cKc?si=DYu44gzvWzA52C9q)**

---

## Get the Files + Join the Community

**Want to copy this for yourself?** Comment "GUIDE" on the video and I'll send you all the project files!

| Resource | Link |
|----------|------|
| Join the Claude Code Community | [linkly.link/2ZOdx](https://linkly.link/2ZOdx) |
| AI Transformation for Your Business | [linkly.link/2ZOds](https://linkly.link/2ZOds) |
| Weekly AI News + Workflows Newsletter | [linkly.link/2ZOdi](https://linkly.link/2ZOdi) |

---

## What Is This?

This repo contains **AI writing skills** — structured markdown files that teach Claude Code (or any AI) how to write content in your voice and style.

Instead of re-explaining your preferences every time, you feed the AI:
1. **Successful examples** of content that performed well
2. **Skills** that define patterns, structure, and voice guidelines
3. **A hierarchy** so platform-specific rules override general rules

The result: AI that writes like you, consistently, across every platform.

---

## How It Works

### Skill Hierarchy

```
CLAUDE.md (Root)
    └── General copywriting rules for ALL content

/Newsletters/newsletter-writer-skill.md
    └── Overrides root for newsletters

/X/x-writer-skill.md
    └── Overrides root for X/Twitter

/Linkedin Successful Posts/linkedin-writer-skill.md
    └── Overrides root for LinkedIn

/Youtube posts/youtube-outline-skill.md
    └── Overrides root for YouTube
```

**Platform-specific skills take priority over the general skill when there are conflicts.**

---

## Repo Structure

```
JJ's Content Guide/
├── CLAUDE.md                          # Root skill (general copywriting)
├── README.md                          # You are here
│
├── Newsletters/
│   ├── newsletter-writer-skill.md     # Newsletter-specific skill
│   ├── Successful Posts/              # Examples that performed well
│   │   ├── 01-some-weird-stuff-is-happening-in-ai.md
│   │   ├── 02-im-done-with-no-code-heres-why.md
│   │   └── 03-elena-verna-creator-economy.md
│   └── New Posts/                     # Drafts
│       └── the-future-isnt-built-for-humans.md
│
├── X/
│   ├── x-writer-skill.md              # X/Twitter-specific skill
│   └── Successful Posts/              # Examples that performed well
│       ├── cj-hess-swarm-has-arrived.md
│       ├── viral-hook-10m-views-coding-app.md
│       ├── lovable-replace-saas-subscriptions.md
│       └── remotion-motion-graphics-guide.md
│
├── Linkedin Successful Posts/
│   ├── linkedin-writer-skill.md       # LinkedIn-specific skill
│   └── Successful Posts/              # Examples that performed well
│       ├── ai-agent-marketing-team-org-chart.md
│       ├── elena-verna-mom-and-pop-saas.md
│       ├── anton-lovable-smarter-update.md
│       └── alex-lieberman-hiring-100-people.md
│
└── Youtube posts/
    ├── youtube-outline-skill.md       # YouTube outline skill
    └── Successful Scripts/            # Example scripts/outlines
        ├── vibe-code-payments-mobile-app.md
        ├── riley-brown-claude-skills-general-agent.md
        └── greg-isenberg-alex-finn-proactive-ai-employee.md
```

---

## Skills Included

### General Copywriting (CLAUDE.md)
- Clarity over cleverness
- Benefits over features
- Specificity over vagueness
- Active voice, conversational tone

### Newsletter Skill
- Opening hooks that grab attention
- Personal stories + vulnerability
- Section structure (The Shift, What I Built, The Invitation)
- Emotional beats and CTAs
- Based on posts with 1,600+ views, 30% read rates

### X/Twitter Skill
- Short-form vs long-form patterns
- Hook formulas (pain point, contrarian, numbers, curiosity)
- Voice guidelines (lowercase casual, bold emphasis)
- Technical breakdown structure
- Based on posts with 10M+ views

### LinkedIn Skill
- B2B-focused, professional but human
- Post types: thought leadership, announcements, hiring, frameworks
- Hook patterns specific to LinkedIn
- Based on posts with 2,500+ likes, 33K+ comments

### YouTube Outline Skill
- Outline structure (not full scripts)
- Hook → Promise → Setup → Core → Conclusion
- 3 title options per outline
- 3 thumbnail concepts per outline

---

## How to Use

### With Claude Code

1. Clone this repo
2. Open the folder in your terminal
3. Run `claude`
4. Ask it to write content — it will automatically use the relevant skill

Example:
```
> Write a LinkedIn post announcing our new AI feature that helps users save 3 hours per week
```

Claude Code reads the LinkedIn skill and writes in that style.

### With Other AI Tools

Copy the skill files into your AI's context or system prompt. The skills are plain markdown — they work anywhere.

---

## Adding Your Own Content

### Adding Successful Examples

1. Create a new `.md` file in the appropriate `Successful Posts/` folder
2. Add frontmatter with metrics:
```yaml
---
Title: Your Post Title
Likes: 500
Comments: 50
Views: 10,000
---
```
3. Paste the full content below

### Creating New Skills

1. Create a `[platform]-writer-skill.md` in the platform folder
2. Follow the structure of existing skills:
   - Voice & tone guidelines
   - Structure patterns
   - What to avoid
   - Reference examples

---

## Credits

Built by [JJ Englert](https://twitter.com/JJEnglert)

Examples from:
- JJ Englert
- Elena Verna
- Alex Lieberman
- Anton (Lovable)
- CJ Hess
- Riley Brown
- Greg Isenberg
- Alex Finn

---

## License

Use this however you want. Build your own version. Make it better.

If you find it useful, join the community: [linkly.link/2ZOdx](https://linkly.link/2ZOdx)