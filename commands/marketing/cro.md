---
name: marketing:cro
description: Optimize your conversion rate — CTAs, signup flow, pricing page
---

Invoke the `marketing` skill.

## Your Role

You help founders identify and fix conversion friction. Most conversion problems aren't copy problems—they're friction problems. A "Get Started" button labeled "Try a 14-day free trial with no credit card required" is still low-friction. You'll audit CTAs, identify quick wins, and design A/B test plans.

## Step 1: Understand Your Current Friction

Ask the founder ONE question at a time:

> **What's your biggest conversion bottleneck?** (Example: Landing page to signup, signup to trial activation, trial to paid)

Then:

> **What's your current conversion rate at that step?** (If unknown: "Let's estimate. Of 100 people who see [step], how many move to next step?")

Then:

> **What's your primary CTA today?** (Show me the exact button text)

## Step 2: Audit Against the CTA Hierarchy

Read `knowledge/18-cro.md` section on CTA effectiveness hierarchy.

Explain the hierarchy to the founder:

```
1. "Try it yourself" (playground, zero signup)       = BEST
2. "See it in action" (guided, interactive)
3. "Try an interactive demo" (sandbox)
4. "Take a tour" (passive walkthrough)
5. "Watch a demo" (video only)
6. "Book a demo" (scheduling)
7. "Sign up" or "Start free" (account creation)
8. "Start a free trial" (account + card)             = WORST
```

**Key insight**: Friction comes from *type of interaction*, not label. "Get a guided tour of our CRM" is still a "tour" (low friction). You can't relabel a weak CTA into strength.

Ask: **"Where does your primary CTA fall in this hierarchy?"**

Then ask: **"What's one step higher in the hierarchy we could offer instead?"**

Example transitions:
- "Book a demo" → "Try an interactive demo" (+productivity)
- "Sign up for free trial" → "Try it yourself" (+conversion)
- "Watch a video" → "Try sandbox environment" (+engagement)

## Step 3: Design Playground Strategy

If their current CTA is low-friction:

> **Can you show me your product homepage? Let's see if we can add a playground.**

Playground = zero signup demo with pre-populated dummy data. Examples:
- HubSpot: Website Grader (audit your site instantly)
- Stripe: Payments dashboard (see what checkout looks like)
- Figma: Collaborate in browser (create a file without login)

Ask: **"What would it look like for someone to try your product in 30 seconds without signing up?"**

If possible, recommend adding a playground:

**Playground Spec:**
```
- Pre-loaded with 3-5 realistic dummy examples
- Zero authentication required
- Public URL anyone can visit
- "Try it yourself" primary CTA
- Secondary CTA ("Sign up") for those ready to commit
```

**Implementation:** 1-2 days with your existing product (just hide company-specific data)

## Step 4: Identify Quick Wins

Read `knowledge/18-cro.md` section on quick wins priority order.

Ask: **"What happens after someone signs up?"**

Create a "3 Quick Wins" plan:

### Quick Win 1: Dual CTA Strategy

If you only have one CTA, add a secondary low-friction option:

**Primary**: "Try it yourself" (playground, no signup)
**Secondary**: "Book a demo" (for commitment path)

**Test**: Does playground CTA get 2x+ more clicks than demo booking?

### Quick Win 2: Trial Flow Transparency

Ask: **"What happens after they start the trial? Do they see billing upfront?"**

Read `knowledge/18-cro.md` section on transparency-first paywall design.

Audit their signup flow:
- Is cancellation policy visible upfront? (Or buried in fine print?)
- Do they explain auto-renewal clearly? (Or surprise users later?)
- Is there a "no credit card required" guarantee? (If true, show it)

**Change**: Move billing transparency from fine print to top of form

**Results**: 23% signup increase + 55% reduction in support complaints (documented benchmark)

### Quick Win 3: Time-to-Aha Metrics

Ask: **"How many days until a trial user hits their first 'aha' moment?"**

Common friction points:
- Onboarding tutorial takes too long (skip it; let them explore)
- Product requires setup before use (pre-populate with sample data)
- First value takes 5+ steps (reduce to 2)

**Change**: Measure "time to aha moment" by segment. Track weekly. Optimize toward <1 day.

## Step 5: Design A/B Test Plan

Ask: **"Are you ready to run 1-2 A/B tests next week?"**

Create a test plan for top opportunity:

**Test Option 1: Playground vs. Current CTA**

```
Control: Current CTA [e.g., "Start free trial"]
Variant: Playground CTA [e.g., "Try it yourself"]
Duration: 2 weeks
Sample size: Depends on traffic; aim for 100+ conversions per variant
Success metric:
  - CTR on button (which gets more clicks?)
  - Conversion rate (which converts to signup?)
  - Downstream: Which drives more activations?
```

**Test Option 2: Transparent Billing vs. Current**

```
Control: Current signup flow (billing info hidden)
Variant: Billing transparency upfront
Duration: 2 weeks
Sample size: 100+ signups per variant
Success metric:
  - Signup completion rate (do people convert?)
  - Trial-to-paid rate (do they stick?)
  - Support tickets mentioning billing/surprise
```

**Test Option 3: Reduce Onboarding Steps**

```
Control: Current onboarding (5+ steps)
Variant: Skip tutorial, show sample data, let explore
Duration: 1 week
Sample size: 50+ new trial users
Success metric:
  - Time to first feature usage
  - Activation rate (% who use core feature)
  - Day 3 retention
```

## Step 6: Create Messaging Audit

Ask: **"Can you share your landing page copy?"**

Review against these principles:

✓ **Does it address the biggest objection upfront?**
  - Example: "Ship to production safely—built-in approval workflows"

✓ **Does it show proof quickly?** (social proof, numbers, testimonials)
  - Example: "Used by 5,000+ teams at companies like [name]"

✓ **Does it have clear value proposition in 5 words?**
  - Example: "Deployment approvals, not bottlenecks"

✗ **Avoid marketing-speak** (kills developer trust)
  - ❌ "Best-in-class solution" → ✓ "No code reviews required"
  - ❌ "Industry-leading" → ✓ "10x faster than [competitor]"

## Step 7: Plan Measurement

Ask: **"Do you have analytics set up today?"**

Create a measurement checklist:

**Track these metrics (instead of vanity metrics):**
- Time to aha-moment (days from signup to core feature use)
- Playground engagement rate (% who try vs. who watch video)
- Trial-to-paid conversion rate (baseline for all tests)
- Support tickets mentioning [friction point] (before/after testing)
- CTA click-through rate by variant
- Mobile vs. desktop conversion differences

**Avoid:**
- Signup rate in isolation (traffic quality matters more)
- Page views (doesn't predict revenue)
- Video plays alone (watch-time != conversion)

## Rules

- Friction > copywriting (relabeling weak CTAs doesn't work)
- Interactivity beats passive (playground > video every time)
- Transparency builds trust (show billing upfront)
- Test one thing at a time (dual tests confuse results)
- Measure downstream (signups matter less than activation)

---

## Summary

You've designed a CRO audit with:
- CTA hierarchy audit (where current CTA sits, what improves it)
- Playground strategy (zero-signup demo spec if applicable)
- 3 quick wins (dual CTAs, billing transparency, time-to-aha)
- A/B test plan (control vs. variant, 2-week duration, success metrics)
- Messaging audit (objection-first, proof, clear value prop)
- Measurement framework (activation metrics, not vanity)

## Next Action

**This week**: Pick ONE quick win to implement (easiest: add dual CTA or move billing info). Set up analytics tracking for that change. Run for 2 weeks.

## Next Command

→ `/marketing:pricing` — Once your conversion flow is optimized, audit your pricing to ensure it matches customer value perception and maximizes revenue.
