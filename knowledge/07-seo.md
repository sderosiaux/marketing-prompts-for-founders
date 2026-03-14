# SEO for SaaS

## Overview
SEO is a multi-year, high-leverage investment for bootstrapped SaaS. It works best when targeting high-intent keywords (bottom-of-funnel) from month one, building topical authority through interconnected content clusters, and creating defensible assets (programmatic pages, tools, or UGC) rather than competing on isolated blog posts.

## Frameworks

### 4 SEO Pillars
1. **SEO Approach**: Choose BoFU content, programmatic SEO, or use-case tools
2. **On-page**: Optimize titles, meta descriptions, headings, URLs, internal links
3. **Technical**: Site hierarchy, Core Web Vitals, HTTPS, XML sitemaps, robots.txt, canonical tags
4. **Off-page**: Backlinks and domain authority

### 11 High-Intent Keyword Categories
1. Tool-specific pain points
2. Pricing/cost-related searches
3. Competitor comparisons
4. Competitor-specific queries
5. Feature-specific searches
6. Integration keywords
7. Product category + audience targeting
8. Benefit-driven searches
9. Educational content (TOFU)
10. Location-based (if applicable)
11. Template-based queries

### APTK Framework
**Audience → Product → Topics → Keywords**
Structure content around audience segments and product alignment. Prioritize relevance over vanity metrics. Build topical authority through interconnected content clusters.

### TOFU/MOFU/BOFU Content Alignment
- **TOFU**: Problem awareness ("what is…", "benefits of…")
- **MOFU**: Solution-seeking ("how to…", frameworks, templates)
- **BOFU**: Product intent (comparisons, reviews, alternatives) ← **Start here**

### Query Syntax Formula (Programmatic SEO)
`Head term + modifier(s)` = scalable permutations. Examples:
- Rankings: "best/top 10 {X}"
- Templates: "{X} template"
- Data: "{job} salary in {country}"
- Integrations: "{X} + {Y} integration"
- Comparisons: "{X} vs. {Y}"
- How-to: "How to {X}"

## Playbook

### Phase 1: Foundation (Month 1-2)
**Validate demand before creating anything**
1. Use Answer The Public, Google Autocomplete, ChatGPT web search to confirm real search volume
2. Interview sales/CS teams on objections, triggers, customer pain points
3. Analyze G2 reviews for competitive gaps and shared pain points
4. Run 5-8 customer interviews validating content/tool concepts
5. Establish measurement baseline: organic traffic share, keywords ranking 4-10

**Choose your approach:**
- **Programmatic SEO**: If you have hundreds of permutations (locations, companies, jobs, etc.)
- **Use-Case Tools**: If you can build calculators, generators, quizzes, or databases
- **Content-Only**: If neither fits your business model

### Phase 2: Content (Month 2-6)
**Start BOFU, then expand**
1. Create content framework by analyzing top-ranking pages for target keywords
2. Document section structure (H1/H2/H3 hierarchy) and internal linking patterns
3. Build keyword clusters (pillar topic → subtopic → long-tail articles)
4. Develop content briefs addressing: pillar topic, target audience, core message, CTA
5. Publish bottom-of-funnel first: alternatives, comparisons, pricing pages, pain-point solutions
6. Acquire 3-5 initial backlinks: guest articles, HARO, directory submissions, co-marketing
7. Measure: conversion rate per page, organic traffic share, keyword rank positions

### Phase 3: Scale (Month 6+)
1. Double down on top-performing content clusters (highest traffic, best conversion rates)
2. Expand MOFU and TOFU content to build topical authority
3. Scale winning approaches (programmatic SEO across new markets/segments, new tool variations)
4. Build user-generated content channel if product supports it (galleries, templates, shared resources)
5. Acquire quality backlinks: leverage high-traffic pages for link stealing, co-marketing at scale
6. Monitor and maintain: update ranking pages quarterly, refresh competitor analysis, kill underperformers

## Keyword Research

**5-Step Process:**
1. Understand keyword formats (modifiers, intent signals) before tool selection
2. Generate topic clusters using APTK framework (Claude/Gemini with system prompt)
3. Validate with Google/Bing autocomplete and ChatGPT web search
4. Analyze top 3 competitors' site structure using Ahrefs for ranking patterns
5. Filter by lowest domain rating (DR 10-15) for exploitable gaps in Ahrefs/SEMrush

**Prioritization:**
- Filter for commercial intent (pricing, comparisons, reviews, alternatives)
- Target long-tail keywords with lower competition initially
- Validate search volume > 0 in multiple tools
- Estimate conversion potential (would a customer searching this term convert?)
- Prioritize keywords where top-ranking content has low authority (easy win)

**Anti-patterns:**
- Chasing high search volume without conversion intent
- Using LLMs as primary discovery tools (they can't validate real demand)
- Copying competitor keywords without understanding your unique audience journey
- Treating SEO separately from product/audience understanding

## Programmatic SEO

**When to use:**
- You have a dataset with 100+ permutations (locations, companies, job titles, etc.)
- Query patterns repeat with high search volume
- You can create unique/proprietary data differentiation
- You can commit to 3-month incubation period before judging success

**5-Step Implementation:**
1. **Define & validate**: Research via Ahrefs, MarketMuse, Voxel. Confirm hundreds+ permutations exist. Validate with 5-8 customer interviews.
2. **Template**: Create landing page with SEO metadata, clear navigation, CTAs, breadcrumbs, H1/H2/H3 hierarchy, social proof, rich content (images, charts, videos), internal links, FAQs with schema markup
3. **Data**: Set up Airtable database (one table per query syntax). Scrape via ScrapingBee, Simplescraper, or public APIs. Map data using DataFetcher.
4. **Content**: Enrich with ChatGPT/Jasper. Fact-check using Grammarly, Longshot, PepperContent. Generate images via Unsplash API or Placid. Sync to Webflow via WhaleSync.
5. **Optimize**: Use Alli AI for crawling, indexing, schema. A/B test headlines, descriptions, page speed. Deploy site-wide optimizations.

**Tech Stack:**
- Page building: Webflow (CMS collections)
- Data: Airtable
- Scraping: ScrapingBee, Simplescraper, ScrapeHero
- Mapping: DataFetcher
- Sync: WhaleSync
- AI content: ChatGPT, Jasper, CopyAI, WriteSonic, Byword
- Images: Unsplash API, Placid
- Fact-check: Grammarly, Longshot, PepperContent
- Optimization: Alli AI

**Benchmarks:**
- Minimum 100-300 permutations for ROI
- 3-month incubation before evaluating performance
- Expect to kill 50% of experiments
- Success requires placing "several bets" simultaneously

**Anti-patterns:**
- Shallow content without genuine customer value
- AI hallucinations without fact-checking
- Inconsistent design/navigation across thousands of pages
- Targeting trendy topics instead of evergreen entities
- Launching without search volume/competition analysis
- Single big bet instead of parallel experiments

## Use-Case Tools (Alternative to Programmatic)

**What works:**
- Calculators, ROI estimators, generators (naming, strategy), quizzes, databases, demo galleries
- Target "how to do X with [product]" intent
- Examples: Ramp (calculators by persona), Storylane (100+ demo-led pages), Shopify (name generator)

**Scaling approach:**
- Start soft-gating (free trial, gate results) for discovery
- Progress to hard-gating (email required upfront) as differentiation increases
- Requires ongoing maintenance and feature updates to maintain rankings

## Backlink Acquisition

**Ranked by effectiveness:**
1. Build genuinely useful products that naturally attract links (free tools, calculators)
2. Guest articles in authority publications (5-8 high-quality links > 50 low-quality)
3. Competitor backlink analysis ("link stealing") — identify who links to competitors, pitch yourself as superior
4. Co-marketing with complementary SaaS (webinars, research reports)
5. HARO (Help A Reporter Out) for journalist-sourced links
6. Directory submissions (limited authority boost, low friction)
7. Leverage existing audience (social media, newsletters)

**Avoid:**
- Low-quality paid backlinks
- Private blog networks
- Over-optimized anchor text
- Spammy URL submissions (Google penalties)

## User-Generated Content (Defensible Moat)

**Why it matters:**
Traditional company-generated content faces AI competition. Build moats through user-created content:
- Individual template landing pages (Canva, Notion, Figma)
- Shared galleries (Amplitude charts, Miro templates, Figma plugins)
- One-click publishing from product workflows (zero friction)

**Timeline & scale:**
- 1-2 years + thousands of pieces needed for measurable acquisition impact
- Balance financial, intrinsic, and extrinsic rewards
- Screen for proprietary data before publishing

**Anti-patterns:**
- Expecting hockey-stick growth from 10 templates
- Launching without understanding user demand signals
- Creating friction in contribution process
- Misaligned incentives

## On-Page SEO Essentials

- **Title tags**: 50-60 chars, primary keyword early, natural language
- **Meta descriptions**: 150-160 chars, include secondary keywords, write for humans
- **H1-H3 headings**: Primary keyword in H1, secondary in H2/H3, natural hierarchy
- **URLs**: Descriptive, keyword-inclusive, lowercase, hyphens not underscores
- **Internal linking**: Relevant anchor text, link to related articles, build content clusters
- **External links**: Link to 3-5 authority sources per article
- **Images**: Compress, lazy load, descriptive alt text with keywords
- **Mobile-first**: Responsive design, test on devices, optimize viewport

## Technical SEO Essentials

- **Site structure**: Main → Categories → Specific pages (clear hierarchy)
- **Core Web Vitals**: Mobile-first indexing, optimize for speed (Google Lighthouse target <3s)
- **HTTPS/SSL**: Non-negotiable security foundation
- **XML sitemaps**: Submit to Google Search Console
- **Robots.txt**: Configure crawl allowances
- **Canonical tags**: Prevent duplicate content issues
- **Structured data**: Schema markup for FAQs, reviews, products

## Templates

### Content Brief Template
- **Pillar topic**: Main subject
- **Target audience**: Specific persona
- **Intent**: TOFU/MOFU/BOFU classification
- **Core message**: Single value proposition
- **Sections**: H2 outline matching top 3 competitors
- **Primary keyword**: (1)
- **Secondary keywords**: (3-5)
- **CTA**: Clear next step
- **Internal links**: (3-5 related articles)

### Keyword Research Spreadsheet Columns
- Keyword
- Search volume
- Keyword difficulty (0-100)
- Commercial intent (TOFU/MOFU/BOFU)
- Conversion potential (high/medium/low)
- Current rank position (if publishing existing)
- Top 3 competitors' domains
- Target URL/article

### Programmatic SEO Dataset Structure (Airtable)
- Record ID
- Head term
- Modifier 1 (location, company, job, etc.)
- Modifier 2 (optional)
- Meta title
- Meta description
- H1
- Unique data points (3-5 fields)
- Image
- Internal link targets
- Status (draft/published/optimized)

## Benchmarks

| Metric | Target | Context |
|---|---|---|
| Keyword discovery | 50-100 initial keywords | Filter to 10-20 priority clusters |
| Domain Authority (DA) | 20+ | Required for ranking on competitive terms |
| Backlink quality | 5-8 from DA 30+ domains | Better than 50 from DA <10 |
| Time to first ranking | 2-4 months | For long-tail keywords in positions 8-12 |
| Conversion rate (organic) | 0.5%-2% | Depends on product, traffic quality |
| Bounce rate | <50% | Higher = content misaligned with user intent |
| Time-on-page | >2 min | Strong engagement signal for tools/utilities |
| Organic traffic share | 20%+ (Year 2) | Mature SEO channel in bootstrapped SaaS |
| Cost per acquisition (CPA) | 50-70% lower than paid | Long-term SEO advantage |

## Tools

| Tool | Use Case | Cost |
|---|---|---|
| **Google Search Console** | Query data, indexing, sitemaps | Free |
| **Google Keyword Planner** | Search volume estimates | Free |
| **Google Lighthouse** | Performance audits | Free |
| **Answer The Public** | Question discovery | Free tier or $99/mo |
| **Ahrefs** | Keyword research, backlinks, competitor analysis | $99+/mo |
| **SEMrush** | Keyword research, competitor analysis | $119+/mo |
| **Airtable** | Data management for pSEO | $20+/mo |
| **Webflow** | CMS for programmatic SEO at scale | $12+/mo |
| **ChatGPT Pro** | Content generation, topic clustering | $20/mo |
| **Cursor AI** | Code editor for pSEO setup | $20+/mo |
| **Alli AI** | Automated SEO optimization | Variable |
| **Longshot** | Fact-checking AI content | Variable |
| **ScrapingBee** | Ethical web scraping | $49+/mo |
| **DataFetcher** | Data mapping for pSEO | Variable |
| **WhaleSync** | Airtable ↔ Webflow sync | Variable |

## Anti-Patterns

- **Starting before PMF clarity**: Don't invest in SEO while product-market fit is unclear; content will miss the mark
- **Chasing volume over intent**: 100 high-intent visitors outperform 10,000 low-intent ones
- **Ignoring user intent**: Optimizing for keywords without understanding searcher needs wastes effort
- **Fire-and-forget content**: Initial ranking gains disappear without ongoing optimization and competitive monitoring
- **Insufficient validation**: Launching pSEO or tools without 5-8 customer interviews or demand verification
- **Poor UX at scale**: Inconsistent design/navigation across templated pages signals low quality to Google
- **Generic at scale**: Creating thousands of similar pages without unique data/insights fails to differentiate
- **Isolated blog posts**: Publishing without topical authority strategy misses clustering benefits
- **Premature paid ads**: Incompatible with bootstrapped constraints; organic compounds over time
- **Overemphasizing technical SEO**: Quality content > perfect technical setup
- **High-traffic pages without CTAs**: Wasted organic traffic with no conversion pathway

## When NOT to Pursue SEO

- Hyper-niche TAM with minimal search demand
- Target customers not actively searching (B2B enterprise deals)
- Cannot commit to 6+ months consistent content (SEO compounds; stops without ongoing effort)
- Need immediate revenue/cash flow (organic takes time)
- Building entirely new category (no existing demand to target)
- $9-$19/month price point without scale (unit economics don't support content investment)

## Timeline Expectations

| Period | What to Expect | Actions |
|---|---|---|
| Month 1-3 | No ranking changes | Validate, build framework, publish first content |
| Month 3-6 | Rank positions 8-12 for 5-10 keywords | Publish BoFU content, acquire initial backlinks |
| Month 6-12 | Keywords move to top 10, organic traffic appears | Scale winners, expand MOFU, measure conversion |
| Year 2+ | Topical authority compounds, 20%+ organic traffic | UGC/tools/scaling, link acquisition at scale |

Quick wins (brand-adjacent keywords) possible in 3 months. Expect material traffic from month 6-9+.

## Sources
- The SaaS SEO Guide (MrRunLocked)
- Getting Your First 1000 Customers (1millionarr)
- Use-Case-Led SEO (Hypergrowth Partners)
- User-Generated Content & SEO (Elena Verna)
- AI-Powered Programmatic SEO (Hypergrowth Partners)
- SEO Blueprint (dannypostma.com)
- Keyword Research for SEO and AEO (marketermilk.com)
- SEO Learning Resource (learningseo.io)
- Programmatic SEO Guide (withdaydream.com)
- App Store Listing Optimization (refined.so)
