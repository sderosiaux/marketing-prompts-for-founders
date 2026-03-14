# Marketing Toolkit for Solo Founders — Design

## Context
Build an actionable marketing system for technical solo founders, sourced from 300+ curated links in [Marketing-for-Founders](https://github.com/EdoStra/Marketing-for-Founders). Open-source the result.

## Persona
Technical solo founder building SaaS/dev tools. Can code, automate, use AI. Needs marketing playbooks that produce artifacts, not lectures.

## Architecture: Hybrid (Stage + Channel)

### Journey Layer (stage-based orchestration)
`/marketing:journey` guides founders through stages:
1. Validate idea
2. Define ICP & positioning
3. Build landing page & pricing
4. Plan & execute launch
5. Grow (SEO, content, outreach, social)
6. Scale (ads, influencers, affiliates)

Each stage invokes the right channel skills with context.

### Channel Skills (domain expertise)
Each skill contains synthesized knowledge + guided workflow:
- Asks context questions about the founder's product
- Walks through the methodology step-by-step
- Generates artifacts (copy, emails, checklists, strategies)

### Output Format
Guided workflow with coached execution. Theory woven into action, not separate.

## Project Structure
```
marketing-prompts-for-founders/
├── docs/plans/                    # Design docs
├── raw/                           # Phase 1: raw extractions per category
├── knowledge/                     # Phase 2: deduplicated canonical knowledge
│   ├── _INDEX.md
│   ├── 01-idea-validation.md
│   ├── 02-user-research.md
│   ├── 03-icp-positioning.md
│   ├── 04-landing-pages-messaging.md
│   ├── 05-pricing.md
│   ├── 06-launch.md
│   ├── 07-seo.md
│   ├── 08-llm-aeo.md
│   ├── 09-social-media.md
│   ├── 10-reddit.md
│   ├── 11-cold-outreach.md
│   ├── 12-email-marketing.md
│   ├── 13-content-marketing.md
│   ├── 14-ads.md
│   ├── 15-influencer.md
│   ├── 16-affiliates-referrals.md
│   ├── 17-free-tool-marketing.md
│   ├── 18-cro.md
│   └── 19-growth-tactics.md
├── skills/
│   └── marketing.md               # Core marketing skill
├── commands/
│   └── marketing/
│       ├── journey.md              # Stage orchestrator
│       ├── validate-idea.md
│       ├── define-icp.md
│       ├── craft-positioning.md
│       ├── plan-launch.md
│       ├── launch.md
│       ├── cold-outreach.md
│       ├── seo.md
│       ├── llm-seo.md
│       ├── reddit.md
│       ├── email-flows.md
│       ├── content.md
│       ├── ads.md
│       ├── pricing.md
│       └── cro.md
├── README.md
└── CLAUDE.md
```

## Build Process

### Phase 1: Bulk Extraction
- Parse all 300+ URLs from source repo
- Launch parallel Haiku agents per category
- Each agent fetches URLs, extracts actionable intel
- Output: raw markdown per category in `raw/`

### Phase 2: Synthesize & Deduplicate
- Merge overlapping advice across categories
- Extract canonical frameworks, templates, checklists
- Resolve conflicts (different sources, different advice)
- Output: knowledge files in `knowledge/`

### Phase 3: Build Channel Skills + Commands
- One command per marketing channel
- Each command loads relevant knowledge files
- Guided workflow: questions → methodology → artifacts
- Output: skills and commands

### Phase 4: Build Journey Layer
- Stage orchestrator that sequences channel skills
- Context flows between stages
- Output: journey command

## Distribution
Self-contained repo. Users clone and symlink/copy into their `~/.claude/` tree.
