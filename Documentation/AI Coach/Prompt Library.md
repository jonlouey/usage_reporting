
Thirty-three curated AI Coach prompts organized by what you're trying to do — from prepping a 1:1 to managing your book of customers.

Thirty-three curated prompts for the [AI Coach](https://learn.lumopath.ai/ai-coach/ai-coach), organized by what you're trying to do. These prompts are also available directly in the app — open the AI Coach from any dashboard and browse the library there. This page is for reference and browsing when you're not in the app.

## Before you start[](https://learn.lumopath.ai/ai-coach/prompt-library#before-you-start)

**Role-based visibility.** Some prompts are tailored to specific roles. Individual contributors see prompts focused on their own work and customers. Managers also see prompts for coaching reports, team management, and resourcing decisions. Each prompt below is labeled with its **Audience**.

**Variables** — Some prompts include variables (like a person's name or a KPI). When you select a prompt in the app, you'll be prompted to fill these in automatically.

**Filters matter.** Every prompt operates within the filters you have set on the dashboard. Set your team, time range, and any other relevant filters _before_ opening the AI Coach. For more on this, see [How to Use the AI Coach](https://learn.lumopath.ai/ai-coach/how-to-use).

**Create your own.** If none of these fit, you can create and save your own prompts at **Settings → AI Coach Prompts**. See [Saved Prompts](https://learn.lumopath.ai/ai-coach/saved-prompts).

**Time range matters.** Most prompts work with whatever range you select. Two prompts (Prompts 9 and 14) compare the first half of your selected range to the second half — these work best with 8 or more weeks selected.

**Iterate.** If a prompt's output isn't quite right, ask a follow-up. The Coach keeps your filter context across the conversation; you don't need to repeat yourself.

---

## Managing Individuals[](https://learn.lumopath.ai/ai-coach/prompt-library#managing-individuals)

### 1. Prep for your next 1:1[](https://learn.lumopath.ai/ai-coach/prompt-library#id-1.-prep-for-your-next-1-1)

**Audience:** Managers only

**Variables:** `{{Name}}`, `{{Goals}}`

Copy

```
Prepare a 1:1 brief for {{Name}}. Their goals are "{{Goals}}".

Cover: (1) How their capacity trended over the selected period — improving,
stable, or worsening — and what's driving it (activity breakdown by type).
(2) Notable account activity — new escalations, contact gaps opening up,
wins, or resolved issues. Include any at-risk accounts due to churn signals
or unrealized upside, and any accounts consuming disproportionate time
relative to their revenue. (3) How their activity patterns compare to
peers in the same role. (4) One specific thing to coach on — tied to their
goals where relevant — and one specific thing to recognize. Make the
coaching point actionable — not "improve time management" but "their
internal meeting time is 40% above peer average; ask about the recurring
Thursday sync."
```

**When to use it.** The core 1:1 prep prompt. Pulls capacity trends, account activity, peer comparison, and goal alignment into a single brief you can read in 90 seconds before walking into the meeting.

---

### 2. Compare top vs. bottom performer activity[](https://learn.lumopath.ai/ai-coach/prompt-library#id-2.-compare-top-vs.-bottom-performer-activity)

**Audience:** Managers only

**Variables:** `{{Employee/Squad A}}`, `{{KPI}}`, `{{Employee/Squad B}}`

Copy

```
{{Employee/Squad A}} is a top performer as measured by {{KPI}}.

{{Employee/Squad B}} is a lower performer.

What are key differences in activity between these two that I could use
to coach the lower performers?
```

**When to use it.** When you want behavioral coaching insights, not theoretical advice. Uses your top performer as the benchmark and surfaces specific differences — meeting cadence, email patterns, ticket handling — you can translate into coaching actions.

---

### 3. Break down an employee's time[](https://learn.lumopath.ai/ai-coach/prompt-library#id-3.-break-down-an-employees-time)

**Audience:** Managers only

**Variables:** `{{Name}}`

Copy

```
Break down where {{Name}} is spending their time during the selected
period compared to peers in the same role. Split by: customer meetings,
internal meetings, email, Slack, support tickets, and project work. Flag
anything that looks disproportionate — either vs. their own week-by-week
trend or vs. peers. If one account or one activity type is consuming an
outsized share, call it out specifically — e.g., "Account X is taking
8 hours/week, mostly from an open support escalation."
```

**When to use it.** When someone is struggling and you need to know _why_ before the conversation. "Your capacity is high" isn't actionable coaching; "You're spending 8 hours a week on Meridian Corp because of an unresolved escalation" is.

---

### 4. Get a coaching recommendation for an employee[](https://learn.lumopath.ai/ai-coach/prompt-library#id-4.-get-a-coaching-recommendation-for-an-employee)

**Audience:** Managers only

**Variables:** `{{Name}}`

Copy

```
Based on {{Name}}'s data during the selected period — capacity trend,
account health, activity patterns, and peer comparison — what's the
single highest-leverage coaching focus for my next 1:1? Be specific
and actionable. Frame it as a behavior change or a decision, not a
metric to improve. For example: "Suggest they delegate tier-1 ticket
follow-ups on their 3 largest accounts to free up 5 hours/week" or
"They're spending 6 hours/week in internal meetings that don't involve
their accounts — ask which ones they can drop." Include the data that
supports the recommendation.
```

**When to use it.** When you want the Coach to act as a coaching advisor, not just a data summarizer. Returns one concrete, data-backed next step you can bring into the 1:1.

---

### 5. Track coaching progress for an employee[](https://learn.lumopath.ai/ai-coach/prompt-library#id-5.-track-coaching-progress-for-an-employee)

**Audience:** Managers only

**Variables:** `{{Name}}`, `{{Date}}`, `{{Topic}}`

Copy

```
On {{Date}}, I coached {{Name}} on {{Topic}}. Based on their data since
that date through the selected period, has anything changed? Show me the
specific metrics related to that coaching focus — before vs. now — and
whether the trend is moving in the right direction. If they improved,
give me something specific to recognize. If they haven't, tell me what's
still getting in the way so I can adjust my approach in the next 1:1.
```

**When to use it.** Creates continuity between 1:1s. Without this, coaching resets every week — you raise an issue, the rep nods, next week everyone starts fresh. This closes the loop with data: did the coaching land?

---

## Managing Teams[](https://learn.lumopath.ai/ai-coach/prompt-library#managing-teams)

### 6. Who should I recognize this week?[](https://learn.lumopath.ai/ai-coach/prompt-library#id-6.-who-should-i-recognize-this-week)

**Audience:** Managers only

Copy

```
Who on my team performed well during the selected period? Look for:
high-quality customer engagement (consistent outreach cadence, quick
responses, resolved escalations), accounts that moved from at-risk to
healthy, someone whose activity patterns stand out positively vs. peers,
or someone who's been quietly consistent while others get attention for
problems. For each person, give me a specific, referenceable data point
I can bring up in the 1:1 — something concrete like "you resolved 3
escalations this week and your accounts have zero open tickets" rather
than "good job."
```

**When to use it.** When you realize you've defaulted to coaching on problems and haven't recognized anyone in a while. Surfaces positive signals with specific data points so the recognition feels genuine.

---

### 7. Prepare for your next team meeting[](https://learn.lumopath.ai/ai-coach/prompt-library#id-7.-prepare-for-your-next-team-meeting)

**Audience:** Managers only

**Variables:** `{{Goals}}`

Copy

```
My team's goals are "{{Goals}}".

For my next team meeting, provide a report with the following topics.
Include reasoning and specific examples for each.

1. Key wins worth calling out to recognize what they are doing well?
2. Key areas where I may be able to help them better accomplish their goals?
3. Key clients that may warrant more attention due to churn risk or unrealized upside?
4. Key clients that may be taking too much time from them vs their revenue?
5. Repeatable activities we may want to automate, offload or increase efficiency?
```

**When to use it.** Before a recurring team meeting where you need a broad agenda covering wins, blockers, and customer health. Different from the 1:1 prep prompt because the audience is the whole team.

---

### 8. Summarize my team's capacity[](https://learn.lumopath.ai/ai-coach/prompt-library#id-8.-summarize-my-teams-capacity)

**Audience:** Managers only

Copy

```
Summarize my team's capacity over the selected period. Include the
overall trend (improving, stable, or worsening), how many people are
overloaded vs. have room, and whether the current level looks like a
sustained pattern or a recent shift. Call out anything unusual — like
one person driving the team average up, or a spike that started in a
specific week.
```

**When to use it.** The narrative starting point for any capacity conversation. Synthesizes trend, distribution, and anomalies into something you can act on or paste into a leadership update. Works with any range — 4 weeks for a quick check, 12 weeks for a quarterly view.

---

### 9. What's driving my team's workload?[](https://learn.lumopath.ai/ai-coach/prompt-library#id-9.-whats-driving-my-teams-workload)

**Audience:** Managers only

Copy

```
Break down what's driving my team's capacity. Split by activity type:
customer meetings, internal meetings, email, Slack, support tickets,
and project work. Compare the second half of the selected period to
the first half — which categories grew the most? Is the increase coming
from more customer volume, more internal overhead, or specific accounts
consuming disproportionate time? Name the top 3 drivers.
```

**When to use it.** Knowing capacity is at 110% isn't actionable. Knowing that internal meetings grew 30% or that 3 accounts added 15 hours/week of support tickets tells you _where to cut_ vs. _where to hire_. Best with 8–12 weeks selected.

---

### 10. Maximize time on a key activity[](https://learn.lumopath.ai/ai-coach/prompt-library#id-10.-maximize-time-on-a-key-activity)

**Audience:** ICs and managers

**Variables:** `{{Activity}}`

Copy

```
I want to maximize time spent on "{{Activity}}".

Based on the activity in the selected period, what is getting in the
way that can be automated, offloaded, or eliminated?

Provide reasoning and examples.
```

**When to use it.** When you have a clear high-value activity (customer-facing time, expansion conversations, strategic planning) and want to find what's competing for that time. Replace `{{Activity}}` with the specific work you want protected. Managers can run this for a team; ICs can run this for themselves.

---

### 11. Reduce time on a low-value activity[](https://learn.lumopath.ai/ai-coach/prompt-library#id-11.-reduce-time-on-a-low-value-activity)

**Audience:** ICs and managers

**Variables:** `{{Activity}}`

Copy

```
I want to minimize time spent on "{{Activity}}".

Based on the activity in the selected period, what are the main themes
in the time spent on "{{Activity}}" that could be reduced, automated,
offloaded, or eliminated?

Provide reasoning and examples.
```

**When to use it.** The mirror image of Prompt 10. When you've identified a category that's eating too much time (admin work, internal meetings, low-value customer touchpoints, a specific segment) and want concrete ideas for reducing it.

---

### 12. Rebalance workload across my team[](https://learn.lumopath.ai/ai-coach/prompt-library#id-12.-rebalance-workload-across-my-team)

**Audience:** Managers only

Copy

```
Looking at my team's individual capacity scores and current account
assignments during the selected period, are there rebalancing opportunities
that would relieve pressure without adding headcount? Who's consistently
overloaded and what could they hand off? Who has room and what type of
work could they absorb? Consider account complexity, segment, and relevant
experience — not just who has the lowest capacity number. Suggest 2–3
specific moves.
```

**When to use it.** Before deciding you need more headcount, check whether the issue is distribution. Returns specific, named rebalancing suggestions instead of a generic "look for capacity gaps."

---

### 13. Compare team health across my org[](https://learn.lumopath.ai/ai-coach/prompt-library#id-13.-compare-team-health-across-my-org)

**Audience:** Managers only

Copy

```
Compare all teams or segments within my org during the selected period.
For each team, show: overall capacity %, number of people at burnout
risk, the 2-3 KPIs that matter most at the org level, and the number
of accounts showing underservice signals (contact gaps, declining
engagement, rising tickets). Rank teams by overall health — worst
first. For the bottom-ranked team, briefly explain what's driving the
strain: is it headcount relative to account load, specific individuals
pulling the average, or a workload spike? If any team looks significantly
healthier than the others, flag it as a potential source of rebalancing.
```

**When to use it.** Before a quarterly review or resource allocation conversation. Produces the side-by-side cross-team view in one shot — which teams are healthy, which are strained, and where there's room to move resources. Built for VPs, Directors, and Heads of CS operating at the org altitude.

---

### 14. Diagnose a systemic issue across my org[](https://learn.lumopath.ai/ai-coach/prompt-library#id-14.-diagnose-a-systemic-issue-across-my-org)

**Audience:** Managers only

Copy

```
Something seems off across my org. Help me diagnose whether this is a
workload problem, a people problem, or a process problem.

Workload: Split the selected period in half. Did ticket volume or
customer-facing hours increase across the org? Is the growth concentrated
in one segment or spread everywhere?

People: Did we lose coverage — through attrition, reorgs, or new hires
still ramping? Are specific teams absorbing extra accounts without
added headcount? Is one person's burnout cascading to their team?

Process: Did internal meeting time, Slack volume, or non-customer-facing
work increase org-wide? Is there a new initiative, reporting cadence,
or cross-functional demand that's consuming time across all teams?

Tell me which of the three is the primary driver, what the evidence is,
and what action it points to — hiring, rebalancing, or cutting process
overhead. If it's a combination, rank them.
```

**When to use it.** When org-wide capacity is trending up or KPIs are trending down and you need to know _why_ at a structural level before you can act. The three-bucket framing prevents the default assumption that more headcount is the answer — sometimes the real problem is a new weekly sync consuming six hours per person across all teams. Best with 8+ weeks selected.

---

### 15. Which manager's team needs the most attention?[](https://learn.lumopath.ai/ai-coach/prompt-library#id-15.-which-managers-team-needs-the-most-attention)

**Audience:** Managers only

Copy

```
Evaluate each manager's team within my org based on the selected period.
For each, assess: current team capacity level, number of people in
overutilized territory, number of accounts showing underservice signals,
and overall account health. Rank the teams from most concerning to
healthiest. For the top 2-3 most concerning teams, help me distinguish:
is this a resourcing problem the manager can't control (too many
accounts, not enough people, absorbing a departing teammate's book) or
is it a management problem I should coach on (uneven account distribution
within the team, not addressing a struggling IC, not using available
tools like digests or triggers)? Be specific — cite the data that points
to one vs. the other.
```

**When to use it.** When you're a leader of leaders deciding which manager needs the most support. The critical distinction this surfaces is _resourcing vs. management_ — a manager whose team is struggling because they absorbed 30 accounts from a departed colleague needs headcount, not coaching. A manager whose team has reasonable workload but uneven distribution needs the opposite. Prevents you from applying the wrong intervention.

---

## Managing Up & Cross-Functionally[](https://learn.lumopath.ai/ai-coach/prompt-library#managing-up-and-cross-functionally)

### 16. Prepare a team QBR or leadership update[](https://learn.lumopath.ai/ai-coach/prompt-library#id-16.-prepare-a-team-qbr-or-leadership-update)

**Audience:** Managers only

**Variables:** `{{Goals}}`

Copy

```
My team's goals are "{{Goals}}".

Create a document with the following topics that I can share directly
with my leadership team. Include reasoning and specific examples for each.

1. Key wins.
2. Key issues getting in our way of success
   - 2a. How could my team solve these issues internally?
   - 2b. How could we use cross-functional support to solve these issues?
3. Potential next steps.
```

**When to use it.** When you need a structured leadership-ready summary you can paste into a deck or email. Returns the kind of QBR-style output a VP can read in two minutes. Different from Prompt 30 (Prep for a QBR / Business Review with This Customer) — this one is a team update going up to your leadership; that one is a customer-facing business review.

---

### 17. Build a data-backed headcount case[](https://learn.lumopath.ai/ai-coach/prompt-library#id-17.-build-a-data-backed-headcount-case)

**Audience:** Managers only

Copy

```
Based on my team's capacity, account load, and workload data in the
selected period, build the case for whether we need additional headcount.
Quantify the gap: how many hours per week is the team collectively over a
healthy capacity threshold? How many accounts show signs of underservice —
contact gaps over 14 days, declining engagement, or rising unresolved
tickets? If the team has been trending worse over the selected period,
note the trajectory. Give me specific numbers I can put in a headcount request.
```

**When to use it.** When you've already worked through whether the issue is staffing, allocation, or behavior (see workflow [M1](https://learn.lumopath.ai/workflows/managers/m1-capacity-hiring)) and concluded the answer is genuinely staffing — this is the prompt that turns that conclusion into the quantified evidence for a hiring conversation. Use after the diagnostic, not as a shortcut around it.

---

### 18. Model a what-if scenario[](https://learn.lumopath.ai/ai-coach/prompt-library#id-18.-model-a-what-if-scenario)

**Audience:** Managers only

**Variables:** `{{Scenario}}`

Copy

```
Model what happens to my team's capacity and account coverage under this
scenario: {{Scenario}}. Based on current capacity levels and per-person
workload during the selected period, project how the change would affect:
overall team capacity, the number of people pushed into overutilized
territory, and the number of accounts likely to become underserved. Flag
specific people who would be most impacted. If the scenario creates an
unsustainable state, estimate how many additional people would be needed
to maintain healthy capacity levels.
```

**When to use it.** When you're trying to make the case for hiring forward, not after the fact. "If we close 10 new logos next quarter without hiring, 4 people go above 120% and 18 accounts lose coverage" is a more compelling pitch than "we're stretched."

---

### 19. Which accounts are being neglected?[](https://learn.lumopath.ai/ai-coach/prompt-library#id-19.-which-accounts-are-being-neglected)

**Audience:** Managers only

Copy

```
Based on my team's activity data during the selected period, which
accounts show signs of being underserved? Look for: contact gaps over
14 days, declining engagement trends, rising unresolved tickets, and
accounts where the assigned CSM's capacity score suggests they don't
have bandwidth to cover their book properly. For each flagged account,
show the ARR, how long the underservice pattern has been happening, and
what specifically is being missed. Rank by business risk — a neglected
$300K renewal account is a different problem than a stable $30K one.
```

**When to use it.** The customer-impact side of the capacity argument. "The team is at 112%" is an internal metric. "14 accounts totaling $2.1M ARR haven't been contacted in 3+ weeks because the team is stretched" is a business risk leadership will understand.

---

### 20. Identify at-risk customers[](https://learn.lumopath.ai/ai-coach/prompt-library#id-20.-identify-at-risk-customers)

**Audience:** ICs and managers

Copy

```
Which customers in view have shown risk of churn during the selected
period? Look for: declining engagement (drop in meeting cadence, response
rates, or login activity), contact gaps over 14 days, rising or unresolved
support tickets, key contacts disengaging or leaving, escalations sitting
open, and any sentiment shifts in conversations. For each at-risk account,
give me: (1) the specific signals driving the risk, (2) how long the
pattern has been developing, (3) the ARR or strategic weight of the
account, and (4) one concrete recommendation — a save play, an internal
escalation, an outreach to a different contact, or a check-in cadence
change. Rank by business risk and call out anything where the renewal
window is within 90 days.
```

**When to use it.** Broad churn risk surfacing — engagement decline, champion departure, sentiment shifts, support volume changes. Different from Prompt 19 (which specifically surfaces accounts suffering from team capacity issues); this surfaces churn risk from any signal. ICs run this on their own book; managers run it across their team's book.

---

## Managing Yourself[](https://learn.lumopath.ai/ai-coach/prompt-library#managing-yourself)

Prompts for your own week-to-week work — weekly planning, 1:1 prep with your manager, time allocation, self-coaching, and career growth. Available on your own employee page.

### 21. Weekly priority reset[](https://learn.lumopath.ai/ai-coach/prompt-library#id-21.-weekly-priority-reset)

**Audience:** ICs and managers

Copy

```
Help me reset my priorities for the week ahead. Based on my activity
during the selected period: (1) Where did my time actually go — by
activity type and by account — and how does that compare to where I
intended to focus? (2) What's piled up that I should clear early in
the week — accounts I haven't touched in over a week, support tickets
aging without resolution, escalations sitting open, contact gaps
widening on key accounts? (3) Which 2–3 accounts deserve proactive
outreach this week based on declining engagement, recent escalations,
or upcoming milestones? (4) What's one recurring drain on my time
that I can plan around or push back on this week? End with a focused
priority list for the week — not a to-do dump.
```

**When to use it.** Start of the week or after a stretch of reactive work. Pulls together where your time actually went, what's piled up, and which accounts deserve outreach this week. Replaces the "I'll figure it out as I go" approach with a focused priority list. Also available on your customer-list view when you want to plan the week from your book of accounts.

---

### 22. Weekly 1:1 prep[](https://learn.lumopath.ai/ai-coach/prompt-library#id-22.-weekly-1-1-prep)

**Audience:** ICs only

**Variables:** `{{Manager Name}}`

Copy

```
I'm preparing for my 1:1 with {{Manager Name}}. Help me prepare a memo
I can bring to the meeting or share as a pre-read. Cover:

1. Key themes from my work during the selected period — what stood out,
   what shifted, what stayed consistent.
2. Wins and progress worth calling out: three things a strong manager
   should notice or appreciate about how I'm showing up. Ground each
   one in an actual pattern from my work, not generic praise.
3. Client-focused issues, challenges, or milestones worth flagging.
4. Any cost-to-serve trends or alerts on my accounts that should be
   on the radar.
5. Areas where I'd benefit from support, guidance, or unblocking from
   {{Manager Name}} — and how to ask for that support clearly and
   constructively.

Format as a memo with talking points and key asks I can use to drive
the conversation.
```

**When to use it.** Before your regular 1:1 with your manager. Drafts a memo-style brief you can use as your own talking points or share as a pre-read. Anchors the conversation in actual patterns from your work rather than vibes, and surfaces specific asks rather than generic "I'm doing fine."

---

### 23. Self-coaching insights[](https://learn.lumopath.ai/ai-coach/prompt-library#id-23.-self-coaching-insights)

**Audience:** ICs only

Copy

```
Based on my activity during the selected period, what's the single
highest-leverage thing I could work on improving? Look at my time
allocation, account engagement patterns, response times, and how my
activity compares to peers in the same role. Frame it as a behavior
change or a decision I could make this month — not a metric to chase.
For example: "Block two hours every Tuesday for proactive outreach to
your three largest accounts; right now they only get reactive contact"
or "Your support ticket response time has been climbing for three
weeks — consider a daily triage window instead of context-switching."
Include the data that points to this being the right focus and one
signal I can watch to know it's working.
```

**When to use it.** When you want a candid read on where you have the most room to improve, grounded in your activity data and peer comparison. Returns one behavior-change recommendation, not a list of metrics to chase. Pair with Prompt 26 (Follow Up on My Own Commitments) over the following weeks to track whether it's working.

---

### 24. Leadership & special projects[](https://learn.lumopath.ai/ai-coach/prompt-library#id-24.-leadership-and-special-projects)

**Audience:** ICs only

Copy

```
I'm thinking about how to grow my impact beyond day-to-day customer
work. Based on my activity during the selected period, help me identify:

1. Patterns in my work that suggest I'm well positioned to lead or
   contribute to a broader initiative.
2. Types of special projects, internal initiatives, or ownership areas
   that would naturally align with my strengths.
3. One concrete example of a project I could realistically propose or
   spearhead.

Frame this in a way that helps me build leadership skills and progress
in my career.
```

**When to use it.** When you're thinking about how to grow your impact beyond your day-to-day book. Surfaces patterns in your work that signal where you could naturally take on more — without you having to invent a project from scratch.

---

### 25. Where is my time going?[](https://learn.lumopath.ai/ai-coach/prompt-library#id-25.-where-is-my-time-going)

**Audience:** ICs and managers

Copy

```
Break down where my time is going during the selected period. Split
by: customer meetings, internal meetings, email, Slack, support
tickets, and project work. Flag anything that looks disproportionate
— either vs. my own week-by-week trend or vs. peers in the same role.
If one account or one activity type is consuming an outsized share
of my time, call it out specifically — e.g., "Account X is taking
8 hours/week, mostly from an open support escalation." End with one
observation about where my time and my stated priorities may be
drifting apart.
```

**When to use it.** When you suspect your time is drifting away from your priorities but can't pinpoint where. Breaks down your activity by type, flags disproportionate spend, and ends with a note on where time and priorities may be misaligned.

---

### 26. Follow up on my own commitments[](https://learn.lumopath.ai/ai-coach/prompt-library#id-26.-follow-up-on-my-own-commitments)

**Audience:** ICs and managers

**Variables:** `{{Date}}`, `{{Topic}}`

Copy

```
In my last 1:1 (on {{Date}}), I committed to {{Topic}}. Based on my
activity and data since that date through the selected period, has
anything actually changed? Show me the specific metrics related to
that commitment — before vs. now — and whether the trend is moving
in the right direction. If I'm making progress, give me one specific
data point I can share in my next 1:1 to demonstrate it. If I'm not,
tell me what's still getting in the way so I can adjust my approach.
```

**When to use it.** After you've made a commitment to your manager — to change a behavior, focus on something specific, or improve in some way — and want to check whether the data shows it's actually moving. Use a few weeks after the commitment date to give the change time to land.

---

## Managing My Book[](https://learn.lumopath.ai/ai-coach/prompt-library#managing-my-book)

Portfolio-level prompts for your book of customers. Available on your customer list view.

### 27. Which of my accounts need attention this week?[](https://learn.lumopath.ai/ai-coach/prompt-library#id-27.-which-of-my-accounts-need-attention-this-week)

**Audience:** ICs and managers

Copy

```
Looking at my book of accounts and the activity during the selected
period, which 3–5 should be at the top of my list this week? Consider:
contact gaps over 14 days, declining engagement trends, rising or
unresolved tickets, recent escalations, upcoming renewal or contract
milestones, and recent expansion or upsell signals. For each account,
give me: (1) why it's on the list, (2) the specific data point that
flagged it, and (3) one concrete next step — a meeting to schedule,
a check-in to send, or an internal conversation to have. Rank by
urgency and call out anything time-sensitive (e.g., renewal within
60 days, an escalation aging out, a key contact going quiet).
```

**When to use it.** For your weekly book-of-business reset. Surfaces the 3–5 accounts most worth your time this week with the data point that flagged each one and a concrete next step. Distinct from prompts that surface long-term underservice or churn risk — this is tactical, what to do this week.

---

## Customer Conversations[](https://learn.lumopath.ai/ai-coach/prompt-library#customer-conversations)

Prompts to prep for a specific customer interaction — meeting prep, account briefs, QBR prep, escalation prep, renewal prep, and expansion plays. Available on individual customer pages.

### 28. Prep for an upcoming meeting with this customer[](https://learn.lumopath.ai/ai-coach/prompt-library#id-28.-prep-for-an-upcoming-meeting-with-this-customer)

**Audience:** ICs and managers

Copy

```
I have an upcoming meeting with this customer. Help me prepare. Cover:
(1) Recent activity and engagement patterns over the selected period
— who on their side has been engaged, who's gone quiet, and any
noticeable shifts. (2) Open issues, escalations, or unresolved questions
I should be ready to address. (3) Wins or progress worth acknowledging.
(4) Strategic context — upcoming renewal, recent expansion, contract
milestones, or known risks. (5) Three suggested talking points and two
questions worth asking. Be specific — reference actual interactions,
tickets, or meeting outcomes, not generic advice.
```

**When to use it.** Before any meaningful customer meeting. Pulls recent engagement, open issues, wins, strategic context, and suggested talking points into a single brief. Saves you the scramble of clicking through Salesforce, Slack channels, and ticket history.

---

### 29. Brief me on this customer's health and recent activity[](https://learn.lumopath.ai/ai-coach/prompt-library#id-29.-brief-me-on-this-customers-health-and-recent-activity)

**Audience:** ICs and managers

Copy

```
Give me a tight brief on this customer's health and what's happened
during the selected period. Cover: overall account health (improving,
stable, or worsening) with the specific signals driving that read;
the most important interactions — meetings, email exchanges, tickets,
escalations — and what came of them; key contacts and how their
engagement has shifted; any open issues or risks; and any recent
wins. Keep it concise — the kind of summary I'd want before walking
into an exec sync or after coming back from a week away.
```

**When to use it.** When you're walking into an exec sync, coming back from a week off, or picking up an account from a teammate. Gives you a tight situational read in under a minute — health trend, key interactions, who's engaged, what's open.

---

### 30. Prep for a QBR / business review with this customer[](https://learn.lumopath.ai/ai-coach/prompt-library#id-30.-prep-for-a-qbr-business-review-with-this-customer)

**Audience:** ICs and managers

Copy

```
I'm preparing for a QBR or business review with this customer. Help
me build a structured prep doc covering: (1) Value delivered during
the selected period — usage trends, outcomes tied to their stated
goals, milestones achieved, issues resolved. (2) Open issues or
concerns that should be addressed in the meeting. (3) Strategic
opportunities — product areas they're underutilizing, expansion or
upsell signals worth surfacing. (4) Questions to ask their team about
goals, priorities, or org changes for the next period. (5) Anticipated
objections or sensitive topics and how to navigate them. Include
specific data points I can put on slides — utilization, response
times, support resolution, escalation history, etc.
```

**When to use it.** Before a customer QBR or business review. Structures the prep doc: value delivered, open issues, strategic opportunities, questions to ask, anticipated objections. Includes specific data points you can put directly on slides. Different from Prompt 16 (Prepare a Team QBR or Leadership Update) — that one is a team update going up to your leadership; this one is customer-facing.

---

### 31. Identify expansion opportunities on this customer[](https://learn.lumopath.ai/ai-coach/prompt-library#id-31.-identify-expansion-opportunities-on-this-customer)

**Audience:** ICs and managers

Copy

```
Based on this customer's activity and engagement during the selected
period, where are the strongest expansion or upsell opportunities?
Look for: heavy usage of a feature they're nearing limits on, interest
in product areas they don't yet have, new stakeholders engaging from
adjacent teams, pain points where a higher tier or add-on would solve
a problem, and growth signals like hiring, new initiatives, or
expanded scope coming up in conversations. For each opportunity, give
me: the signal that points to it, who I should talk to, and one
concrete next step to surface it.
```

**When to use it.** When you suspect there's growth potential on an account but haven't dug in. Surfaces usage signals, adjacent-team engagement, pain points that could be solved by a higher tier, and growth signals from their team. Useful before a renewal conversation or expansion play.

---

### 32. Prep for a difficult conversation with this customer[](https://learn.lumopath.ai/ai-coach/prompt-library#id-32.-prep-for-a-difficult-conversation-with-this-customer)

**Audience:** ICs and managers

Copy

```
I'm preparing for a difficult conversation with this customer — an
active escalation, a contract dispute, or a renewal at risk. Help me
prepare. Cover: (1) History of the issue during the selected period
— when it started, what's been done, what's still open, and how their
team has engaged or disengaged. (2) Specific data points that support
our side — usage, response times, support resolution, milestones
delivered. (3) Anticipated objections and the data to address each
one. (4) Sensitive topics or relationships that need careful navigation.
(5) Three options for resolution I could propose, ranked by what's
likely to land. Be direct — this isn't a routine meeting.
```

**When to use it.** For escalations, contract disputes, renewals at risk, or any meaningful customer conversation where the stakes are high and you need to walk in with a clear point of view. Returns history, supporting data, anticipated objections, and resolution options ranked by likelihood of landing.

---

### 33. Prep for this customer's renewal[](https://learn.lumopath.ai/ai-coach/prompt-library#id-33.-prep-for-this-customers-renewal)

**Audience:** ICs and managers

Copy

```
This customer's renewal is approaching. Help me build a renewal prep
doc covering: (1) Value delivered during the selected period —
outcomes tied to their stated goals, milestones achieved, ROI signals.
(2) Usage trends and product engagement — are they sticky and growing,
flat, or declining? (3) Risk signals — declining contacts, open
escalations, disengaged stakeholders, support volume changes. (4)
Expansion or upsell opportunities to raise alongside the renewal.
(5) Anticipated negotiation points and the data to support our
position. (6) Three potential renewal outcomes (renewal as-is,
expansion, churn risk) and what would drive each. Be specific — I
need to walk in with a clear point of view.
```

**When to use it.** 30–90 days before a renewal where you want to walk in with a structured plan. Covers value delivered, usage trends, risk signals, expansion opportunities, and likely negotiation points. Different from Prompt 30 (QBR / business review prep) — this one is specifically renewal-focused.