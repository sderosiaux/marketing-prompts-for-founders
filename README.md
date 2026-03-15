# Marketing Prompts for Founders

**Get your first customers this week.** Clone this repo, type one command, answer 3 questions about your product, and get a complete marketing playbook built for your situation — cold emails, landing page copy, launch plan, pricing strategy, whatever you need right now.

Built for solo technical founders who'd rather ship code than read marketing blogs.

Based on [Marketing-for-Founders](https://github.com/EdoStra/Marketing-for-Founders) by [@e_stradella](https://x.com/e_stradella) — 300+ curated resources, deduplicated and distilled into guided workflows that produce real artifacts.

## Prerequisites

This repo is built for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). You need Claude Code installed to use the slash commands.

**Don't have Claude Code?** See [Using Without Claude Code](#using-without-claude-code) below.

## Quick Start

```bash
git clone https://github.com/sderosiaux/marketing-prompts-for-founders.git
cd marketing-prompts-for-founders
```

Open in Claude Code and type:

```
/marketing:journey
```

It asks where you are and tells you exactly what to do next.

## What It Looks Like

Here's a real session — running `/marketing:landing-page` for a developer analytics tool:

```
You: /marketing:landing-page
     Product: DevDash — developer analytics showing code review bottlenecks.
     ICP: engineering managers at 20-100 person startups.
     Differentiator: PR-level bottlenecks, not just aggregate stats.

Claude: Knowledge loaded. Let's build your homepage copy section by section.

        ## Section 1: Hero

        Here are 5 headline options for DevDash:

        | # | Technique         | Headline                              |
        |---|-------------------|---------------------------------------|
        | 1 | Direct benefit    | See exactly where PRs get stuck       |
        | 2 | Problem-first     | Your code reviews are a bottleneck    |
        | 3 | Contrast          | Less guessing, more shipping          |
        | 4 | Specific proof    | Find PR bottlenecks in 30 seconds     |
        | 5 | Audience-first    | The dashboard EMs actually need       |

        My recommendation: #1 — "See exactly where PRs get stuck"

        Subheadline: Developer analytics that show PR-level bottlenecks,
        not just team averages.

        CTA button: Start finding bottlenecks →

        Before I continue — do you want to go with headline #1,
        or prefer a different one?
```

It then walks through 7 sections (hero, problem, solution, features, how it works, social proof, CTA), generating real copy for each. After you're done, it points you to `/marketing:review` to stress-test the copy from your customer's perspective.

## Commands

### Start here

| Command | What It Does |
|---|---|
| `/marketing:journey` | Diagnoses your stage, tells you what to do next |

### Foundation (do these first)

| Command | What It Does |
|---|---|
| `/marketing:validate` | Test if your idea is worth building — 7-day playbook |
| `/marketing:research` | User interviews, surveys, PMF measurement |
| `/marketing:icp` | Define who you're building for + positioning |
| `/marketing:landing-page` | Generate landing page copy section by section |
| `/marketing:pricing` | Set pricing strategy, tiers, and pricing page copy |

### Getting Users

| Command | What It Does |
|---|---|
| `/marketing:launch` | Plan launch across Product Hunt, HN, directories |
| `/marketing:outreach` | Cold email system — leads, templates, sequences |
| `/marketing:social` | Pick ONE platform, build profile + content plan |
| `/marketing:reddit` | Reddit marketing without getting banned |

### Scaling Growth

| Command | What It Does |
|---|---|
| `/marketing:seo` | Keyword strategy, content plan, page structure |
| `/marketing:llm-seo` | Get recommended by ChatGPT and AI search |
| `/marketing:content` | Content strategy, topics, distribution |
| `/marketing:ads` | Paid ads — platform, budget, campaign structure |
| `/marketing:email` | Onboarding sequences, lifecycle emails, retention |

### Review & Optimize

| Command | What It Does |
|---|---|
| `/marketing:review` | Role-play as your target customer to stress-test any artifact |
| `/marketing:audit` | Audit a live page for SEO, messaging, and conversion issues |
| `/marketing:write` | Write a blog post, Show HN post, Twitter thread, or LinkedIn post |
| `/marketing:cro` | Conversion rate optimization — CTAs, signup flow |
| `/marketing:metrics` | Define the 5 metrics that matter for your stage |
| `/marketing:competitors` | Competitive analysis — battle cards, positioning gaps |

### Advanced Channels

| Command | What It Does |
|---|---|
| `/marketing:influencer` | Find and partner with creators |
| `/marketing:affiliates` | Set up affiliate and referral programs |
| `/marketing:free-tools` | Build free tools that drive traffic |
| `/marketing:growth` | Stage-specific growth tactics and weekly plan |

## How It Works

Each command:
1. **Asks** 3-5 questions about your specific product
2. **Walks** you through the methodology step by step
3. **Generates** customized artifacts (copy, emails, plans, strategies)
4. **Points** you to what to do next

The knowledge base behind the commands contains frameworks, templates, benchmarks, and anti-patterns synthesized from 300+ articles. Claude reads them to inform its advice — you never see raw theory, only customized output.

Artifacts can be saved to `marketing-artifacts/` in your project so they persist between sessions.

## Using Without Claude Code

The `knowledge/` folder works standalone with any LLM. Here's how:

### With ChatGPT or any chat-based LLM

1. Pick the knowledge file for your need (see table below)
2. Copy the entire file content into a new conversation
3. Add this prompt:

```
You are a marketing advisor for solo SaaS founders. Use the knowledge
above to help me with my specific product. Ask me about my product,
who it's for, and where I am today. Then walk me through the frameworks
step by step, generating real artifacts (copy, emails, strategies)
customized to my situation. Ask one question at a time.
```

### With Cursor or AI-powered editors

1. Add the `knowledge/` folder to your project
2. Reference files in your prompts: `@knowledge/03-icp-positioning.md help me define my ICP`

### Most useful files to start with

| File | Best for | Lines |
|---|---|---|
| `03-icp-positioning.md` | Defining your target customer + positioning statement | 312 |
| `04-landing-pages-messaging.md` | Writing homepage copy that converts | ~300 |
| `11-cold-outreach.md` | Building a cold email system from scratch | 374 |
| `01-idea-validation.md` | Testing if your idea is worth building | ~250 |
| `08-llm-aeo.md` | Getting recommended by ChatGPT and AI search | ~200 |
| `_INDEX.md` | Quick reference map of all 19 files | 39 |

## Credits

- Source material: [Marketing-for-Founders](https://github.com/EdoStra/Marketing-for-Founders) by [@e_stradella](https://x.com/e_stradella)
- Key sources: PostHog, Lenny's Newsletter, MR Unlocked, Growth Unhinged, GTM Strategist, MarkePear, and many more (see individual knowledge files for full attribution)

## License

MIT
