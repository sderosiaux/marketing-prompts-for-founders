# User Research

## Overview
User research reveals why customers buy, what makes them stick, and why they leave. Structured feedback loops across new, active, and churned users drive product roadmap priorities and messaging refinement. This playbook turns customer conversations into competitive advantage.

## Frameworks

### Three-Segment Lifecycle Feedback Loop
Structure research around customer lifecycle:
1. **New Users (0-30 days)**: Understand initial motivation and onboarding friction
2. **Active Users (ongoing)**: Identify what resonates and what causes friction
3. **Churned Users (post-churn)**: Learn why people leave without defensive bias

### The PMF Engine (Product-Market Fit)
1. **Survey metric**: "How would you feel if you could no longer use this?"
2. **Threshold**: 40%+ answering "very disappointed" = PMF achieved
3. **Analysis**: Build HXC (High-Expectation Customer) profile only from "very disappointed" cohort
4. **Roadmap split**: 50% deepening beloved features, 50% fixing friction for "somewhat disappointed" users
5. **Cadence**: Track continuously, analyze monthly, rebuild quarterly

### Jobs To Be Done (JTBD)
Understand the job customers hire your product to perform:
- Structure: "When [context], I want to [task], so that [outcome]"
- Customer journey: First Thought → Passively Looking → Actively Looking → Consideration → Purchase → Usage
- Four forces of switching: Habit anxiety (push), existing problems (pull), new option appeal (pull), can eliminate job entirely (competition redefined)
- Interviewee selection: Target longest-tenured customers, power users, recent purchasers (3-6 months)

### MaxDiff (Maximum Difference Scaling)
Force prioritization by asking binary trade-offs:
- Present attributes, ask respondents to pick most and least important
- Calculate difference scores (% selecting most minus % selecting least)
- Segment by LTV, industry, lifecycle stage, NPS to reveal hidden preference divergence
- Far superior to Likert scales which hide true priorities (4.73 vs 4.45 look similar but mean opposite things)

### Journey Mapping for Dev Tools
Map four critical moments:
1. **Signup Trigger**: Problem recognition, discovery, catalyst
2. **Signup Barrier**: Obstacles before signup
3. **Activation Trigger**: Moment of value realization
4. **Activation Barrier**: Setup/initial use friction

## Playbook

### New User Research (Do This First Week)
1. Send personal email invitation during days 2-4: "Thanks for signing up—I'm keen to learn your goals and how we can help. Free 30-min call this week?"
2. Alternative: Deploy single-question survey: "What made you sign up?" Organize responses by theme
3. Optional: Schedule 30-min calls with 5+ new users/month
4. Include small incentive ($5 voucher) to boost booking rate
5. Listen for problems they expected to solve and initial hesitations

### Active User Research (Ongoing Monthly)
1. Deploy NPS survey: "Would you recommend this to a friend?" (0-10 scale)
2. Deploy PMF survey: "How would you feel if you could no longer use this?" (very/somewhat/not disappointed)
3. Follow up with non-promoters (NPS 0-6) to understand friction
4. Quarterly: Conduct 5-10 journey mapping interviews per cohort (activators vs. non-activators)
5. Monthly: Gather and tag feature requests for pattern detection

### Journey Mapping Interview (30-40 min structure)
1. **Discovery anchor**: "When did you first hear about us?"
2. **Job identification**: "What problem does this solve?"
3. **Timeline**: "When did you sign up? [Get month/year]"
4. **Research behavior**: "Did you research competing solutions?"
5. **Hopes/concerns**: "What were you hoping this would accomplish? What hesitations did you have?"
6. **Stakeholders**: "Who else was involved in this decision?"
7. **Value moment**: "At what point did you realize value?"
8. **Reaching for the door** (15-20 min mark): "Is there anything else I should know?" (often surfaces critical insights)
9. Use Kanban board shared during call to visualize timeline

### Happy Customer Interview (20-30 min)
1. **Opening**: "I want to understand why you're happy so I can find more customers like you"
2. **Historical need**: "Go back in time—why did you need [what we do]?"
3. **Previous solutions**: "What were you using before?"
4. **Switching motivation**: "What made you switch to us?"
5. **Workflow context**: "Walk me through your day before vs. after using us"
6. **Feature deep-dive** (when they suggest features):
   - "Can you walk me through when you'd use this?"
   - "What do you currently use for this?"
   - "What other tools do you pay for? What do they handle?"
   - "How much time does this currently take?"
   - "Who else is involved?"
7. **Follow-up months later**: Reference their suggestion when building, or explain why you're not—shows you listened

### Churned Customer Interview (20-25 min, $25 gift card)
1. **Opening**: "This isn't a sales call. Nothing here will be used for sales. Can we talk about what happened?"
2. **Recent context**: "Walk me through what happened most recently" (listen extensively)
3. **Decision-making**: "Who made the decision to leave? Were there other factors beyond [stated reason]?"
4. **Original workflow**: "What were you doing before we came along? Why did your company need [what we do]?"
5. **Replacement**: "What are you switching to? How did you discover it? What was the deciding factor?"
6. **External influences**: "Did anyone outside your company influence the decision? New budget constraints?"
7. **Reaching for the door** (15-20 min): "Anything else I should understand?" then gracefully close
8. Never defend product or interrupt; focus entirely on their perspective
9. Send handwritten thank-you note after call

### Feature Request Deep-Dive (Turn Requests into Research)
When customer requests a feature, treat it as acute problem discovery:
1. **Email response** (keep to 2 questions max, send same day):
   - "Thanks for this! How would this fit into your broader process? How do you solve this currently?"
2. **Phone follow-up** (if high-value customer):
   - "Can you walk me through when you'd use this?" (context mapping)
   - "What made this need come about?" (origin)
   - "What do you currently use?" (current state)
   - "What other tools/steps have you tried?" (journey mapping)
   - "What are the steps involved?" (process breakdown)
   - "Can you show me what you do now?" (visual understanding)
   - "How much time does this take?" (impact assessment)
3. **Store**: Add to customer understanding repository with tags
4. **Pattern detection**: When 3+ customers mention same problem, prioritize development
5. **Circle back**: When you build it (months/years later), contact original requesters—signals competitive differentiation

### B2B Research Optimization (60 Accounts → 60 Seconds)
1. Identify 10-20 accounts with funding/hiring signals using CommonRoom or Clearbit
2. Use AI to write personalized call invites to these accounts
3. Deploy targeted survey (Tally) before expensive interviews to filter high-intent respondents
4. Segment survey results by: LTV, industry vertical, current lifecycle status, NPS/sentiment, role
5. Interview only high-intent respondents who complete survey

### Operational Workflow
1. **Weekly**: Review incoming feature requests and support tickets; tag by theme
2. **Bi-weekly**: Share research findings in Slack with word clouds showing emergent themes
3. **Monthly**: Track NPS/PMF scores; follow up with low-NPS users; analyze completed interviews for patterns
4. **Quarterly**: Rebuild PMF profile; allocate roadmap resources 50/50 (beloved vs. friction); update messaging based on HXC language
5. **Documentation**: Small team = Intercom tags per customer; larger team = interview transcripts in central repository

## Templates

### New User Call Invitation Email
```
Subject: Quick call about your goals with [Product]?

Hi [Name],

Thanks for signing up for [Product] this week—I really appreciate it.

I'm [Founder Name], one of the people building this, and I'm keen to learn about your goals and how we can help you get there.

Free 30 min call anytime this week? https://calendly.com/[your-link]

[Incentive option: "I'll also send you a $5 credit as a thank you"]

—[Your name]
```

### Feature Request Follow-Up Email
```
Subject: Re: [Feature request]

Thanks for this suggestion!

I'm curious—how would this fit into your broader process? And what do you currently use to solve this?

Would love to hop on a quick call if you have 15 min this week. [Calendly link]

—[Your name]
```

### Interview Invitation Email (Happy/Churned Customer)
```
Subject: Help me understand [your use case]

Hi [Name],

I've noticed you [completed this milestone / recently cancelled], and I'd love to understand your perspective.

I'm running a project to better understand how customers like you use [Product], and your experience would be invaluable. It's just 20-30 minutes, and as a thank you, I'll send you a [gift card / swag].

Recording is totally optional. Here's my calendar: [Calendly link]

Thanks,
[Your name]
```

### PMF Survey (4-Question Core)
```
1. How would you feel if you could no longer use [Product]?
   - Very disappointed
   - Somewhat disappointed
   - Not disappointed

2. Who benefits most from [Product]?
   [Open text]

3. What's the main benefit you've gotten from using [Product]?
   [Open text]

4. How could we improve [Product]?
   [Open text]
```

### Journey Mapping Interview Guide
```
Discovery: "When did you first hear about us?"
Job: "What problem does this solve for you?"
Timeline: "When did you sign up? [Get specific month/year]"
Research: "Did you research other solutions?"
Hopes: "What were you hoping this would accomplish?"
Concerns: "What concerns did you have?"
Stakeholders: "Who else was involved?"
Activation: "At what point did you realize value?"
[Around 15-20 min] "Is there anything else I should know?"
```

### Churned Customer Interview Guide
```
Opening: "This isn't a sales call. I want to understand what happened."
Recent: "Walk me through what happened most recently."
Decision: "Who decided to leave? Were there other factors?"
Before: "What were you using before us?"
Replacement: "What are you switching to? How did you find it?"
Pricing: "Did pricing play a role?"
External: "Did anyone outside your team influence this?"
[Around 15-20 min] "Anything else I should understand?"
```

## Benchmarks

| Metric | Target | Context |
|---|---|---|
| New user calls | 5+/month | Essential for activation friction discovery |
| Monthly survey responses | 50+ | Directional validity requires sample size |
| PMF threshold | 40% "very disappointed" | Industry standard (Sean Ellis analysis of ~100 startups) |
| Journey mapping cohort | 5-10 users | Minimum per segment (activators vs. non-activators) |
| Feature request pattern | 3+ mentions | Threshold before prioritizing roadmap item |
| PMF improvement case study | 22% → 58% in 3 quarters | Superhuman after segmenting by core benefit |
| Interview sample size | ~40 respondents | Directional validity for patterns |
| Interview duration | 30-40 min | Optimal for JTBD interviews; start with 30 min if nervous |
| Churn survey timing | Day 7 post-churn | Optimal recollection without staleness |

## Tools

| Tool | Use Case | Cost |
|---|---|---|
| Calendly | Interview scheduling with automatic reminders | Free tier |
| Tally | Lightweight survey deployment | Free tier |
| Amplitude | Analytics + session replay for qualitative behavior | Paid |
| CommonRoom | AI-powered account prioritization (B2B) | Paid |
| Mailshake | Automated outreach sequencing | Paid |
| Intercom | Customer tagging for small teams | Paid |

## Anti-Patterns

- **Skipping research due to time**: 60-second AI prioritization + surveys before interviews eliminates the "too time-consuming" excuse
- **Starting with interviews**: Begin with surveys to filter for high-intent respondents, then interview; 60-minute interviews blind are wasteful
- **Assuming churn reasons**: Always ask directly instead of guessing; get defensive instead of curious
- **Likert scales for prioritization**: 4.73 vs 4.45 average ratings look similar but hide true priorities; use MaxDiff (forced choice) instead
- **Broadcasting research questions**: Research 10-20 focused accounts (B2B) or batch interviews over weeks—broad simultaneous outreach kills pattern detection
- **Activating surveys mid-flow**: Trigger after meaningful events or at natural moments; never interrupt user experience
- **Pushing growth before PMF**: Growth before 40% "very disappointed" wastes acquisition spend on wrong customer segments
- **Ignoring feature requests**: Treat them as acute problem windows, not feature briefs; dig 5 levels deeper with "How/When/Why" questions
- **Never circling back**: Following up years later when features launch signals competitive differentiation through genuine attention

## Sources

- PostHog - Talk to Users — Three-segment lifecycle model, NPS/PMF/CES frameworks, incentive strategies, 40% PMF threshold
- Growth Roadmaps - Unlock Power User Feedback — Lifecycle segmentation, monthly NPS tracking, churn survey structure
- Growth Mates - No Time for Research — Signal-based targeting, AI account prioritization, survey-before-interviews strategy
- First Round Review - Superhuman's Product-Market Fit Engine — PMF calculation methodology, HXC profiling, quarterly rebuild cadence, Superhuman case study (22% → 58%)
- Demand Maven - MaxDiff Research Methodology — Forced-choice prioritization, segmentation analysis by LTV/industry/lifecycle
- Shili - Journey Mapping Interviews for Dev Tools — Four critical moments mapping, visual interview structure, question sequencing
- Valchanova - Customer Development & Jobs to Be Done — JTBD definition, customer journey timeline, four forces of switching, recent purchaser targeting (3-6 months)
- Forget the Funnel - JTBD Interview Questions — 25-question interview framework, email recruitment scripts
- Deploy Empathy - Customer Interview Scripts — New customer switch interviews (1-3 month window), happy customer deep-dive, churned customer philosophy, feature request exploration questions, thank-you follow-up tactics
