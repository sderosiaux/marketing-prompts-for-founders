# USER RESEARCH: Interviews, Surveys, JTBD, PMF

## Source: PostHog - Talk to Users

### Key Frameworks
- **Three-Segment Lifecycle Feedback Model**: Structure user feedback collection across new users (understand initial motivation), active users (identify resonance/friction), and churned users (learn why people leave)

### Actionable Tactics
- **New User Outreach**: Send call invitation during first days: "Thanks for signing up for our product - it's much appreciated! I'm really keen to learn more about your goals and can we can help you get there. Free for a 30 min call this week?"
- **Alternative for New Users**: Send automated email with single question: "What made you sign up?" then organize responses via tagging/filtering
- **Active User Surveys**: Deploy three in-app survey types—NPS ("Would you recommend this to a friend?"), PMF test ("How would you feel if you could no longer use this?"), and CES (Customer Effort Score)
- **Call Incentives**: Include small reward (e.g., $5 voucher) to boost booking rates
- **Churned User Approach**: Send survey 7 days post-churn mixing open-ended, true/false, list, and rating questions for easier analysis
- **Implementation Workflow**: Create experiments based on findings, refine personas by rating changes 1-5 for persona alignment, improve messaging by identifying most-valued features, share findings company-wide every 2 weeks via Slack

### Metrics/Benchmarks
- Minimum 5 users/month on calls
- Target 50 survey responses/month
- PMF threshold: 40%+ "very disappointed" = Product-Market Fit achieved

### Anti-Patterns
- Don't interrupt user flow with in-app surveys; trigger only after meaningful events
- Avoid asking too many questions per call—focus on depth over breadth
- Don't assume you know why users churn without direct evidence

---

## Source: Growth Roadmaps - Unlock Power User Feedback

### Key Frameworks
- **Three-Segment Lifecycle Approach**: Segment feedback collection by new users, active users, and churned users
- **NPS Monthly Tracking**: Regular measurement with follow-up on low scorers
- **PMF Survey**: "How would you feel if you could no longer use this?"
- **CES Implementation**: Deploy to measure ease of use and problem resolution

### Actionable Tactics
- **Call Outreach for New Users**: "Thanks for signing up for our product - it's much appreciated! I'm really keen to learn more about your goals and can we can help you get there. Free for a 30 min call this week?"
- **New User Email Survey**: Single question "What made you sign up?" sent in first days
- **NPS Follow-up**: Track monthly and reach out to non-promoters
- **Incentive Strategy**: $5 voucher or similar reward to boost call booking rates
- **Churn Survey Timing**: Send 7 days post-churn with mixed question formats (open-ended, true/false, list, rating)
- **Company-Wide Sharing**: Update Slack every 2 weeks with key findings and learnings

### Templates
- New user call invitation email template provided
- Churn survey structure: mix of question types to improve analysis

### Metrics/Benchmarks
- 5+ users/month on calls
- 50 survey responses/month minimum
- 40%+ "very disappointed" on PMF question = PMF achieved

### Anti-Patterns
- Triggering surveys at wrong moments in user flow
- Asking excessive questions per call
- Making assumptions about churn without data

---

## Source: Growth Mates - No Time for Research (3 High-Speed Methods)

### Key Frameworks
- **Account Research Before User Research**: In B2B, prioritize account-level insights before end-user behavior
- **ICP Profile Building**: Market/industry vertical, geography, company size, business challenges/revenue impact, user/buyer roles, purchase timelines, technology stack (technographics)
- **Survey-First Approach**: "You don't need to start with interviews...Start with a survey" to identify high-intent users for follow-up

### Actionable Tactics
- **AI-Powered Account Prioritization**: Reduce research time from 60 minutes to 60 seconds using tools that surface funding signals, engagement trends, competitor mentions, and community activity
- **Signal-Based Targeting**: Focus on 10-20 accounts rather than hundreds; look for hiring/funding signals, product usage patterns, and website interaction behavior
- **Personalized Outreach**: Use AI to write tailored messages inviting prioritized accounts to calls or surveys
- **Survey Before Interviews**: Start with targeted surveys to collect qualitative data before conducting time-intensive interviews

### Templates
- Onboarding Experience Survey (12 questions)
- Power Users Survey (17 questions)
- Upgrade & Pricing Insights Survey (20 questions)

### Tools Mentioned
- CommonRoom (AI-powered account research)
- Tally (survey platform)
- Amplitude (analytics with session replay for qualitative insights)

### Metrics/Benchmarks
- Author conducted 100 interviews in one year as personal growth challenge

### Anti-Patterns
- Skipping research due to time constraints—sacrificing research activities believing it's too time-consuming
- Starting with interviews—beginning with 60-minute interviews without prior context wastes time
- Unfocused sampling—researching hundreds of accounts instead of strategically selected priority accounts

---

## Source: First Round Review - Superhuman's Product-Market Fit Engine

### Key Frameworks
- **Leading Indicator Metric for PMF**: Question—"How would you feel if you could no longer use this product?" / Benchmark: 40% responding "very disappointed" signals PMF
- **High-Expectation Customer (HXC) Profile**: Build vivid persona from "very disappointed" users' own language describing who benefits most; reveals discerning customer who drives word-of-mouth
- **Four-Step PMF Engine**:
  1. **Segment**: Isolate supporters by grouping survey responses; identify personas within "very disappointed" cohort to narrow market focus
  2. **Analyze Feedback**: Study why users love you vs. what holds others back; disregard feedback from non-disappointed users
  3. **Build Roadmap**: Allocate 50% resources doubling down on beloved features; 50% addressing friction for "somewhat disappointed" users
  4. **Repeat & Track**: Survey continuously (new users only), rebuild quarterly, make PMF score the primary OKR

### Actionable Tactics
- **Word Cloud Analysis**: Use word clouds from open-ended feedback to identify emergent themes
- **Segmentation by Core Benefit**: Segment "somewhat disappointed" users by whether your core benefit resonates—only act on feedback from those where it does
- **Cost/Impact Analysis**: Employ low-medium-high cost/impact analysis to stack-rank roadmap initiatives
- **Custom Tooling**: Build continuous surveying and weekly/monthly/quarterly tracking capabilities
- **Quarterly Rebuilding**: Reconstruct PMF and update roadmap every quarter based on new survey data

### Survey Template (4 Core Questions)
1. Disappointment level (very/somewhat/not)
2. Who benefits most from product?
3. Main benefit received?
4. How to improve?

### Metrics/Benchmarks
- **40% threshold**: Industry benchmark for PMF (per Sean Ellis analysis of ~100 startups)
- **Superhuman case study**: 22% → 33% (after segmenting) → 58% (within 3 quarters)
- Sample size: ~40 respondents minimum for directional validity

### Anti-Patterns
- Launching prematurely with "throw it out there" mentality before validating fit
- Acting on feedback from users who wouldn't miss the product
- Building feature parity with competitors instead of deepening core benefit
- Pushing premature growth before achieving measurable PMF score
- Ignoring that PMF may decline as user base expands beyond early adopters

---

## Source: Demand Maven - MaxDiff Research Methodology

### Key Frameworks
- **MaxDiff (Maximum Difference Scaling)**: Forces binary trade-offs; respondents select the *most* and *least* important attributes from a set, analysts subtract least-important responses from most-important to create clear ranking

### Actionable Tactics
- **Binary Comparison Method**: Present attributes in groups; ask respondents to identify one most and one least important rather than ranking all simultaneously
- **Segmentation Analysis**: Break MaxDiff results by customer LTV, industry vertical, current lifecycle status (trial/free/paying/churned), NPS/sentiment scores, role or persona
- **Interpretation**: Calculate difference scores across all responses to force prioritization for product roadmaps and marketing messaging

### Metrics/Benchmarks
- Difference scores (most important % minus least important %)
- Variation by segment (which audiences have divergent preferences?)
- Correlation with LTV or retention rates

### Anti-Patterns
- **Likert Scale False Comfort**: 1-5 rating systems create false comfort when applied to feature importance; averages of 4.73 vs. 4.45 look statistically similar but create illusion of clarity—"everything seems important and I'm not sure which way is up"
- Using non-comparative ranking that obscures true priorities

---

## Source: Shili - Journey Mapping Interviews for Dev Tools

### Key Frameworks
- **Four Key Moments to Map**:
  1. **Signup Trigger** - Problem recognition, discovery, decision catalyst
  2. **Signup Barrier** - Obstacles, concerns, hesitations before signup
  3. **Activation Trigger** - Moment of value realization, time-to-activation
  4. **Activation Barrier** - Friction points in setup/initial use

### Actionable Tactics
- **Visual Interview Structure**: Use Kanban/Trello board shared during call; timeline questioning with specific month/year anchors; zoom in/out capability to move between detail and overview
- **Question Sequencing**:
  1. Discovery: "When did you first hear about us?"
  2. Job identification: "What problem does this solve?"
  3. Timeline: "When did you sign up?"
  4. Research behavior: "Did you research solutions?"
  5. Value moment: "At what point did you realize value?"
  6. Stakeholders: "Who was involved in this process?"
- **Stack-rank pain points by user perception**

### Metrics/Benchmarks
- "5-10 users is a great start" for each cohort (activators vs. non-activators)
- Segment by persona when analyzing different buyer types

### Anti-Patterns
- High-level, abstract feedback without specific timeline anchors
- Confirmation bias by suggesting pain points first
- Insufficient data consistency across interviews
- Conflating different user personas in analysis

---

## Source: Valchanova - Customer Development & Jobs to Be Done

### Key Frameworks
- **JTBD Definition Model**: "When… I want to… So that I…" structure capturing context, task, and desired outcome
- **Customer Journey Timeline**: First Thought (seed planted) → Passively Looking → Actively Looking trigger event → Consideration & evaluation → Purchase moment → Consumption/usage
- **Four Forces of Switching**:
  - **Push Forces**: Habit and anxiety about change
  - **Pull Forces**: Problems with existing solution and appeal of new option
- **Competition Reimagined**: Three competitive levels—direct competitors (same solution method), secondary competitors (alternative approaches), indirect competitors (eliminate the Job entirely)

### Actionable Tactics
- **Interviewee Selection**: Target specific segments—longest-tenured customers, power users, high-value purchasers—rather than broad audiences; recent purchasers (3-6 months) retain fresher memories
- **Interview Duration & Setup**: Allocate 30-40 minutes per session; provide Calendly links for seamless booking; offer small incentives (gift cards, product samples); request permission to record
- **Question Strategy**: Avoid "Why" questions; use "What" and "How" instead; skip either-or framing; start with purchase moment (specific anchor point); work backward chronologically to First Thought
- **Batch Outreach & Iteration**: Don't ask broad audiences simultaneously; spread sessions over weeks for iterative refinement

### Tools Mentioned
- **Scheduling**: Calendly
- **Outreach Automation**: Mailshake

### Metrics/Benchmarks
- Case study: Messaging refinement from 4 personas to 2 JTBD resulted in 28% increase in trial signups and 10% decrease in bounce rate

### Templates
- Interview invitation email template (personalized approach with clear expectations, incentive, and easy booking link)

### Anti-Patterns
- Asking broad audiences simultaneously dilutes pattern recognition
- Using imprecise question framing

---

## Source: Forget the Funnel - JTBD Interview Questions & Email Script

### Key Frameworks
- **Jobs To Be Done Interview Methodology**: Structured approach focused on understanding the "job" customers hire products to do, rather than demographic characteristics

### Actionable Tactics
- Conduct interviews with 25 predetermined questions designed to elicit deeper customer motivations
- Use included email script to invite customers to participate in interviews
- Adapt B2B-focused questions for B2C contexts as needed
- Record and analyze responses to identify patterns in customer needs

### Templates
- "25 questions to conduct more effective Jobs To Be Done interviews with your customers"
- Email invitation script for recruiting interview participants
- Downloadable Google Doc template for implementation

### Application
- Framework specifically designed for B2B SaaS products but maintains flexibility for other business models
- Created by Georgiana Laudi and Claire Suellentrop (Forget The Funnel), marketing strategists

---

## Source: Deploy Empathy - Customer Interview Script (JTBD Switch Interview - New Customers)

### Key Frameworks
- **JTBD Switch Interview Target**: Customers who've used product for 1-3 months, capturing journey from problem awareness through product adoption

### Interview Structure
- **Opening Phase**: Confirm participant identity, introduce yourself, address questions, clarify incentives and recording permissions
- **Main Questions** (loosely ordered exploring):
  - How customer initially identified their need
  - Desired end outcomes
  - Previous manual workarounds attempted
  - Timeline for recognizing need for external solutions
  - Search and discovery process
  - Hopes for what product would accomplish
  - Initial concerns or hesitations
  - Consultation with others before deciding
  - Alternative options considered
  - Required stakeholder approvals

### Actionable Tactics
- **Critical Moment**: Approximately halfway through, ask "Is there anything else you think I should know?" (the "reaching for the door" question often surfaces valuable insights)
- **Flow Management**: Expect conversations to diverge naturally—this indicates engagement; gently redirect rather than forcing sequential answers
- **Thank-You Strategy**: For existing customers, physical swag (stickers, hats, socks) works better than gift cards; always include handwritten note
- **Documentation**: Choose system matching team size—from simple Intercom tags to transcripts for larger organizations

### Metrics/Benchmarks
- **Timing**: 15-60 minutes works; start with 30 minutes to reduce anxiety

---

## Source: Deploy Empathy - Customer Interview Script (Happy Customer)

### Key Frameworks
- **Happy Customer Interview Purpose**: Focus on satisfied, long-term customers to identify why they're happy and find more customers like them; counters loss aversion bias that over-focuses on upset customers

### Actionable Tactics
- **Recruitment Email Framing**: Emphasize founder involvement: "I'm also interested to hear any feature suggestions or tweaks you might have"—incentivizes participation
- **Main Interview Topics**:
  - Historical need: "Could you go back in time and tell me why you even needed something to do [what your service does]"
  - Previous solutions used
  - Motivation for switching
  - Workflow context (before/after using service)
  - Evolution since adoption
- **Feature Request Deep-Dive**: When customers suggest features, probe with usage scenario walkthroughs, current workarounds, associated costs, time investment, and "magic wand" question for unconstrained thinking
- **Meticulous Documentation**: Follow up months or years later to either request additional details when building feature or close the loop after launch

### Critical Success Factor
- "The follow-up that shows you listened?" signals competitive differentiation through genuine customer attention

---

## Source: Deploy Empathy - Customer Interview Script (Churned Customer)

### Key Frameworks
- **Churned Customer Interview Philosophy**: Don't aim to win back customer; instead use interviews to identify problematic use cases so you attract fewer misaligned customers and more ideal ones
- **Pizza Shop Analogy**: Rather than adding salad options to appease dissatisfied customers, double down on your core audience

### Interview Structure (20-25 Minutes)
- **Opening Questions**: Establish this isn't a sales call; clarify nothing discussed will be used for sales purposes; offer $25 Amazon gift card; request recording permission
- **Deal With Disappointment First**: "Can you walk me through what happened most recently?" (listen extensively); explore contributing factors beyond immediate trigger; identify decision-makers; ask about cancellation process
- **Why They Came to You**: Understand original workflow before product; learn why company performs this function; identify who championed initial adoption
- **What They'll Use Next**: Discover replacement solutions; learn discovery path for alternatives; identify external influences on tool selection; inquire about new pricing

### Actionable Tactics
- **Emotional Management**: Create space for own feelings of rejection before call so you can listen without defensiveness
- **Validation Over Defense**: Never interrupt or explain product intent; focus entirely on their perspective
- **Timing**: Ask "reaching for the door" question around 15-20 minutes to gracefully conclude
- **Follow-up**: Always send thank-you note afterward
- **Incentive**: $25 Amazon gift card works well for churn interviews; avoid branded swag

---

## Source: Deploy Empathy - Turning Feature Requests into Customer Research

### Key Frameworks
- **Reframe Feature Requests**: Treat them as "a welcome and crisp window into an acute problem for a customer"; customer articulates need as solution rather than problem—your role is to dig deeper

### Actionable Tactics
- **Phone Response Exploration Questions**:
  1. Context mapping: "Can you walk me through when you might use this?"
  2. Origin discovery: "What made this need come about?"
  3. Current state: "What do you currently use for this?"
  4. Competitive landscape: "Do you pay for other tools? What else do they handle?"
  5. Journey mapping: "What other tools/steps have you tried?"
  6. Process breakdown: "What are the different steps involved?"
  7. Visual understanding: "Can you show me what you do now?"
  8. Impact assessment: "How much time does this currently take?"
  9. Stakeholder identification: "Is anyone else involved?"

- **Email Response Template**: Keep concise (max 2 questions) to maintain response rates; use framing words that elicit big-picture thinking (context, background, broader goal/process, big picture)
  - Sample opener: "Thank you for this suggestion! How would this fit into your broader process? I'm curious how you currently solve this."

- **Post-Research Action Steps**:
  1. **Store learnings**: Add insights to customer understanding repository
  2. **Pattern tracking**: Tag customers by request theme; maintain running lists of related requests
  3. **Communication**: Tell customers you're saving idea with explicit "if/when we add it" framing
  4. **Momentum trigger**: When multiple customers reference same process, prioritize development
  5. **Circle back**: Reconnect with original requesters when features launch—even years later—to demonstrate you listened

### Philosophical Shift
- Transform groans into curiosity: "All people like to feel valued, appreciated, and helpful"
- Genuine appreciation for requests builds long-term trust regardless of implementation

---

## Synthesis: Cross-Source Patterns & Best Practices

### Research Structure by User Segment
Create a three-segment feedback loop:
1. **New Users (0-30 days)**: Single-question survey ("What made you sign up?") + optional 30-min calls with personal outreach
2. **Active Users (ongoing)**: Monthly NPS + PMF survey + quarterly journey mapping interviews (5-10 users per cohort)
3. **Churned Users (post-churn)**: Survey at 7-day mark + select interviews with $25 gift card incentive

### The PMF Engine (Most Actionable Framework)
1. **Survey metric**: "How would you feel if you could no longer use this?" Threshold: 40%+ "very disappointed"
2. **Segment ruthlessly**: Only analyze feedback from "very disappointed" users to identify HXC profile
3. **Roadmap allocation**: 50% deepening beloved features, 50% fixing friction for "somewhat disappointed" users who get the core benefit
4. **Quarterly rebuild**: Track metric continuously, analyze monthly, rebuild roadmap every quarter

### Interview Templates (Ready-to-Use)
- **New/Switch Customers (1-3 months)**: Explore problem discovery → research process → hopes → hesitations → alternatives considered → stakeholder involvement
- **Happy Customers**: Probe feature requests deeply with workaround mapping and impact assessment
- **Churned Customers**: Understand original workflow → why company needed it → what they're switching to (avoid win-back mentality)
- **General Tactic**: Start with purchase moment as anchor, work backward chronologically

### Signal-Based Targeting (Time Saver)
- For B2B: Research 10-20 accounts with funding/hiring signals before broad surveys
- Use CommonRoom (account intelligence), Tally (surveys), Amplitude (qualitative sessions)
- Reduce research time 60 minutes → 60 seconds with AI prioritization
- Survey before interviews to filter for high-intent respondents

### Reframe Feature Requests as Research Gold
- Every feature request reveals an acute problem
- Exploration questions: Use broad framing ("How would this fit your process?" vs. "Do you want this?")
- Store all patterns in system; act when 3+ customers mention same problem
- Always circle back when you build it—builds trust and future feedback

### Research Anti-Patterns to Avoid
- Don't assume reasons for churn/dissatisfaction—always ask
- Never push growth before PMF (40%+) is validated
- Avoid Likert scales for feature importance; use MaxDiff (forced choice) for clarity
- Don't start with broad audiences for interviews; batch and iterate to find patterns
- Never interrupt user flow with surveys; trigger post-activation or at natural moments

### Measurement Fundamentals
- **NPS**: Monthly tracking with low-scorer follow-up
- **PMF**: 40% "very disappointed" benchmark; Superhuman case study showed 22% → 58% in 3 quarters
- **Cost/Impact**: Stack-rank roadmap initiatives as low/medium/high before building
- **Cohort Specificity**: MaxDiff and segmentation reveal hidden preferences by industry/LTV—don't assume one-size-fits-all

### Team Operational Tactics
- **Incentives**: $5-25 gift cards work; physical swag (stickers, hats) beats branded items for existing customers; handwritten thank-you notes compound trust
- **Documentation**: Intercom tags for small teams, transcripts for larger teams
- **Company Communication**: Share findings every 2 weeks via Slack; use word clouds to show emergent themes
- **Tooling**: Build continuous survey infrastructure for weekly/monthly/quarterly tracking
