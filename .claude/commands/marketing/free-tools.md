---
name: marketing:free-tools
description: Build a free tool or side project to drive traffic and signups
---

Invoke the `marketing` skill.

## Your Role

You help solo founders build free tools that drive traffic, awareness, and conversions to their main product. Free tools only work when they're standalone, single-purpose, and solve a real pain point your target customer faces. You'll brainstorm ideas, validate demand, and design the conversion funnel.

## Step 1: Understand Your Product & Access

Ask the founder ONE question at a time:

> **What does your main product do?** (One sentence)

Then:

> **What are your top 3-5 keywords?** (What problem do you solve? Example: "API authentication", "database migration", "email deliverability")

Then:

> **What data or APIs do you have access to?** (Example: Stripe data, GitHub data, user behavior logs, public APIs you can leverage)

## Step 2: Brainstorm 5 Free Tool Ideas

Read `knowledge/17-free-tool-marketing.md` for tool types and examples.

Create 5 tool ideas solving problems your ICP faces. Each idea should:
- Be standalone (works without signing up for main product)
- Solve one specific problem
- Be completable in 1-2 days
- Have 10K-100K monthly search volume

**Example Framework** (for SaaS that helps with "API authentication"):

| Idea | Problem | Type | Search Volume | Build Effort |
|------|---------|------|---|---|
| JWT Decoder | "How do I decode a JWT token?" | Utility | 8K/mo | 2 hours |
| API Rate Limit Calculator | "How many requests per second?" | Calculator | 5K/mo | 4 hours |
| OAuth Flow Diagram | "Which OAuth flow for my use case?" | Interactive | 3K/mo | 6 hours |
| CORS Error Debugger | "Why is my CORS failing?" | Debugger | 12K/mo | 8 hours |
| API Key Generator | "Generate secure API keys instantly" | Generator | 6K/mo | 1 hour |

Ask: **"Which of these problems do you hear from potential customers most often?"**

## Step 3: Validate Demand Before Building

Read `knowledge/17-free-tool-marketing.md` section on demand validation.

Don't build yet. Validate:

1. **Search volume**: Use Google Ads Keyword Planner (free tier)
   - Target: 10K-100K monthly searches
   - Green light if > 5K searches

2. **Customer pain**: Do your existing users mention this problem?
   - Review support tickets for the keyword
   - Ask in customer calls: "How do you currently solve [problem]?"

3. **Conversion path**: Can you naturally point tool users to main product?
   - Tool solves problem → customer realizes they need full solution → easy upgrade path
   - Example: JWT decoder → user sees they need full auth platform → ✓

Ask: **"Based on search volume and customer feedback, which tool should we build first?"**

## Step 4: Design Zero-Friction Tool

Create a tool spec:

**Core Principles:**
- No signup required (public, anyone can use)
- Pre-populated with dummy data (instant value)
- Single input field (simplest UI possible)
- Instant results (no waiting)
- One-click copy/download

**Example Specs:**

**Tool: JWT Decoder**
```
Input: Paste JWT token
Process: Decode and display payload
Output:
  - Header (JSON)
  - Payload (JSON)
  - Signature valid? Yes/No
  - One-click Copy button
```

**Tool: CORS Error Debugger**
```
Input: Paste error message
Process: Parse error, suggest fixes
Output:
  - What went wrong (plain English)
  - 3 suggested fixes (code + explanation)
  - Link to MDN docs
```

**Tool: API Rate Limit Calculator**
```
Input:
  - API calls per second (number)
  - Cost per request ($)
  - Billing period (dropdown)
Process: Auto-calculate monthly spend
Output:
  - Monthly cost
  - Cost per day / hour / minute
  - Optimize suggestion
```

## Step 5: Design Conversion Funnel

Read `knowledge/17-free-tool-marketing.md` section on conversion strategy.

Create a 3-step funnel:

**Step 1: Tool Page**
- Logo + brand at top
- Tool itself (no scrolling required)
- Watermark: "[Your Company] - Powered by [Main Product]"

**Step 2: Contextual CTA**
- After tool completes: "Powered by [Main Product]"
- Link: "See how [Main Product] handles [problem] at scale"
- Frame: "This tool solved [problem]. [Main Product] solves 10 related problems."

**Example CTAs:**
- JWT Decoder → "See how [Product] secures APIs at scale"
- CORS Debugger → "Automate CORS handling with [Product]"
- Rate Limit Calc → "Scale APIs without rate limit headaches"

**Step 3: Landing Page**
- Tool users click CTA → landed on landing page
- Landing page frames tool as proof-of-concept
- CTA: "Try [Main Product] free for 14 days"

## Step 6: Plan Build & Launch

Ask: **"When can you dedicate 1 day to build this tool?"**

Create a timeline:

**Day 1: Build**
- Use no-code tool (Calconic, Bubble, or simple HTML/JS)
- Deploy to `/tools/[name]`
- Add watermark with link to main product
- Test on mobile (must work on phones)

**Days 2-7: SEO Prep**
- Write 1 FAQ section on tool page
- Add JSON-LD structured data
- Internal links from main site to tool
- Check with Google Rich Results Test

**Week 2: Launch**
- Product Hunt (if appropriate)
- Hacker News "Show HN"
- Reddit (r/InternetIsBeautiful, relevant subreddits)
- Twitter / personal network
- Dev.to, Hashnode articles linking to tool

**Weeks 3-12: Monitor & Iterate**
- Track traffic + conversion rate to main product
- Fix UI/UX based on user feedback
- Add second tool if first converts well

## Step 7: Set Realistic Expectations

Read `knowledge/17-free-tool-marketing.md` section on metrics that matter.

Tell the founder:

- **Traffic**: 500 visitors in 90 days is realistic baseline
- **Conversions**: 0.1-0.5% of visitors sign up for main product
- **Timeline**: SEO kicks in after 90+ days; viral potential in 24h-2 weeks
- **ROI**: Not about direct revenue; it's about awareness + SEO authority
- **Viral loop**: Pre-populate with examples, add watermark, make shareable

**Measurement:**
- Track: conversion rate tool → main product signup
- Ignore: Raw traffic numbers (vanity)
- Goal: Lower CAC + faster awareness, not direct sales

## Rules

- Build standalone (must work without main product)
- Single-purpose (one problem, not multi-feature)
- Zero friction (no signup, no scrolling, instant results)
- Validate demand before engineering (10K-100K monthly searches)
- Design conversion path (tool → awareness → main product)

---

## Summary

You've designed a free tool strategy with:
- 5 brainstormed tool ideas (ranked by search volume + effort)
- Demand validation plan (before engineering)
- Zero-friction tool spec (no signup, instant results)
- 3-step conversion funnel (tool → CTA → landing page)
- Build + launch timeline (1 day build, 2-week launch, 90-day measurement)
- Realistic metrics (500 visitors, 0.1-0.5% conversion)

## Next Action

**This week**: Validate top 2 tool ideas. Check search volume in Google Keyword Planner. Ask 3 customers if they face this problem. Pick one and build it within 5 days.

## Next Command

→ `/marketing:seo` — Once your tool is live, double down on SEO with long-tail keyword targeting, internal linking, and FAQ schema to drive sustained organic traffic and authority.
