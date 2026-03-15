# Marketing Prompts for Founders

## Project Overview
Marketing toolkit for solo technical SaaS founders. Claude Code skills, commands, and knowledge files that turn marketing theory into guided, artifact-producing workflows.

## Structure
- `knowledge/` — 19 canonical marketing knowledge files (deduplicated from 300+ sources)
- `.claude/skills/marketing.md` — core skill loaded by all `/marketing:*` commands
- `.claude/commands/marketing/` — 25 interactive commands + journey orchestrator

## Key Principles
- Every command produces ARTIFACTS, not lectures
- Questions are asked ONE AT A TIME
- Knowledge files are REFERENCE for the AI, not dumped on the user
- All advice is customized to the founder's product, stage, and constraints
- Commands end with: Summary → Next action → Next command

## Adding New Commands
Follow the pattern in `.claude/commands/marketing/journey.md`:
1. Start with frontmatter (name, description)
2. "Invoke the `marketing` skill."
3. Reference knowledge with "Read `knowledge/XX-filename.md`"
4. Ask context questions one at a time
5. Walk through phases, generating artifacts at each step
6. End with next steps

## Adding Knowledge
Follow the template in existing files:
- Overview → Frameworks → Playbook → Templates → Benchmarks → Tools → Anti-Patterns → Sources
- Keep under 400 lines
- Deduplicate ruthlessly
- Only actionable content, no fluff
