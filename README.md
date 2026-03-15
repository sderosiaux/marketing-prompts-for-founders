# Marketing Prompts for Founders

A complete marketing system for solo technical founders, built as Claude Code skills and commands. Sourced from 300+ curated resources, deduplicated and distilled into actionable playbooks.

Based on [Marketing-for-Founders](https://github.com/EdoStra/Marketing-for-Founders) by EdoStra.

## What This Is

19 knowledge files, 20 interactive commands, and a journey orchestrator that tells you exactly what marketing to do next based on where you are.

**Not a reading list.** Every command asks about YOUR product, walks you through a methodology, and generates real artifacts — emails, landing page copy, SEO strategies, launch plans — customized to your situation.

## Quick Start

### 1. Clone this repo

```bash
git clone https://github.com/YOUR_USERNAME/marketing-prompts-for-founders.git
```

### 2. Start your journey

Open the repo in Claude Code — commands and skills are auto-discovered from `.claude/`.

```
/marketing:journey
```

It asks where you are and tells you what to do next.

## Commands

| Command | What It Does |
|---|---|
| `/marketing:journey` | Figure out what to do next based on your stage |
| `/marketing:validate` | Validate your idea in 7 days |
| `/marketing:research` | User interviews, surveys, PMF measurement |
| `/marketing:icp` | Define your Ideal Customer Profile + positioning |
| `/marketing:landing-page` | Generate landing page copy section by section |
| `/marketing:pricing` | Set pricing strategy, tiers, and pricing page |
| `/marketing:launch` | Plan launch across Product Hunt, HN, directories |
| `/marketing:seo` | SEO strategy — keywords, content plan, structure |
| `/marketing:llm-seo` | Get recommended by ChatGPT and AI search |
| `/marketing:social` | Social media strategy — pick platform, create content |
| `/marketing:reddit` | Reddit marketing without getting banned |
| `/marketing:outreach` | Cold email system — leads, templates, sequences |
| `/marketing:email` | Email marketing — onboarding, lifecycle, retention |
| `/marketing:content` | Content marketing — strategy, topics, distribution |
| `/marketing:ads` | Paid ads — platform, budget, campaign structure |
| `/marketing:influencer` | Find and partner with influencers |
| `/marketing:affiliates` | Set up affiliate and referral programs |
| `/marketing:free-tools` | Build free tools to drive traffic |
| `/marketing:cro` | Conversion rate optimization |
| `/marketing:growth` | Misc growth tactics for your stage |

## How It Works

```
You (solo founder)
    │
    ▼
/marketing:journey ──→ "You're at stage D, do these 2 things"
    │
    ▼
/marketing:outreach ──→ asks about your product
    │                    walks you through ICP → triggers → emails
    │                    generates 3 cold email templates
    │                    designs outreach sequence
    │
    ▼
Real artifacts you can use today
```

Each command:
1. **Asks** 3-5 questions about your specific product
2. **Walks** you through the methodology step by step
3. **Generates** customized artifacts (copy, emails, plans)
4. **Points** you to what to do next

## Knowledge Base

19 deduplicated knowledge files covering every marketing channel. Synthesized from 300+ articles, newsletters, and guides. Each file contains:

- Frameworks with concrete steps
- Ready-to-use templates
- Real benchmarks and metrics
- Tools with cost info
- Anti-patterns (what NOT to do)

See `knowledge/_INDEX.md` for the full map.

## Project Structure

```
marketing-prompts-for-founders/
├── README.md
├── CLAUDE.md                      # Claude Code project instructions
├── .claude/
│   ├── commands/
│   │   └── marketing/
│   │       ├── journey.md         # Stage orchestrator (start here)
│   │       ├── validate.md
│   │       ├── ...
│   │       └── growth.md
│   └── skills/
│       └── marketing.md           # Core skill loaded by all commands
├── knowledge/                     # Canonical marketing knowledge (19 files)
│   ├── _INDEX.md                  # Quick reference map
│   ├── 01-idea-validation.md
│   ├── ...
│   └── 19-growth-tactics.md
├── raw/                           # Raw extractions (18 files, for reference)
└── docs/
    └── plans/                     # Design documents
```

## Credits

- Source material: [Marketing-for-Founders](https://github.com/EdoStra/Marketing-for-Founders) by [@e_stradella](https://x.com/e_stradella)
- Key sources include: PostHog, Lenny's Newsletter, MR Unlocked, Growth Unhinged, GTM Strategist, MarkePear, and many more (see individual knowledge files for full attribution)

## License

MIT
