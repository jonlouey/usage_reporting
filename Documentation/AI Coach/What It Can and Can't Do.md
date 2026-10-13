
Honest expectation-setting for the AI Coach. What it's good at, what it isn't, and the things people sometimes expect it to do that it can't.

The AI Coach is powerful, but bounded. This page is the honest list of what to expect and what not to expect, so you don't waste time asking it questions it can't answer or, worse, trust answers it shouldn't give.

For the deeper conceptual layer — why these limits exist and how the Coach actually reasons — see [How the AI Coach Reasons](https://learn.lumopath.ai/how-lumopath-works/how-the-ai-coach-reasons).

## What it does well[](https://learn.lumopath.ai/ai-coach/what-it-can-and-cant-do#what-it-does-well)

Strength

Example

**Synthesizing patterns across many data points**

"Compare this team's activity patterns to other teams in the segment over the last quarter"

**Surfacing outliers and trends**

"Who on the team has had the steepest capacity increase in the last 6 weeks?"

**Producing structured summaries**

QBR-style reports, 1:1 prep briefs, leadership updates

**Comparing top vs. bottom performers**

"What's different about how Sarah engages with accounts vs. Daniel?"

**Modeling what-if scenarios**

"If we close 10 new logos next quarter without hiring, what does capacity look like?"

**Connecting effort to outcomes**

"Which accounts consume the most time relative to their ARR?"

**Iterating with follow-ups**

The Coach maintains context across questions; ask, refine, narrow

## What it can see[](https://learn.lumopath.ai/ai-coach/what-it-can-and-cant-do#what-it-can-see)

- **Activity metadata** from connected integrations — meetings (who, when, how long), emails (who, when, how often, response time), chats (volume, frequency), tickets, calls
    
- **AI-classified topics** of activity — what the work was about, at a category level
    
- **CRM data** — accounts, owners, ARR, segments, opportunities, renewal dates
    
- **Lumopath-derived metrics** — [Capacity](https://learn.lumopath.ai/how-lumopath-works/capacity), [KPIs](https://learn.lumopath.ai/how-lumopath-works/kpis), [Reactive vs Proactive splits](https://learn.lumopath.ai/how-lumopath-works/reactive-vs-proactive), engagement trends, after-hours patterns, time allocation
    
- **Org structure** — Teams, [Squads, Segments](https://learn.lumopath.ai/how-lumopath-works/squads-and-segments), reporting lines
    

## What it can't see[](https://learn.lumopath.ai/ai-coach/what-it-can-and-cant-do#what-it-cant-see)

This is the list of things people commonly expect the Coach to do but it currently can't. Knowing these saves frustration.

It can't...

Why

**Read Gmail or Microsoft 365 email body text**

For Gmail and M365, the Coach reasons over email metadata (who, when, response time) and AI-classified topics from subject lines. It can tell you that response times have lengthened by 60%; it can't quote the email body. **Exception:** if your admin has enabled [Email Bodies](https://learn.lumopath.ai/setup-and-administration/customization/crm-content-settings) in Settings → CRM, the Coach can access Salesforce EmailMessage body text for accounts with Salesforce-synced emails.

**Access Slack or Teams DMs**

Direct messages are never accessed. Channel content _is_ accessible and informs the Coach's analysis, but private DMs are off-limits entirely.

**See data from tools that aren't connected**

If your team works heavily in a tool Lumopath isn't integrated with, that work is invisible. Check what's connected under [Setup → Integrations](https://learn.lumopath.ai/setup-and-administration/integrations).

**See people or accounts outside your visibility scope**

The Coach respects your role and access settings. A manager asking about people they don't have visibility into will not get an answer. See [Data & Access Management](https://learn.lumopath.ai/trust-and-privacy/data-and-access).

**Predict the future as fact**

The Coach identifies patterns and risks based on what's happened. Treat its risk signals as flags worth investigating, not as forecasts.

**Reason across the limits of the time range you've selected**

If your filter is "last 30 days," the Coach can't tell you about year-over-year trends. Change the filter, then ask.

**Reason over data the dashboard filter has excluded**

This is the most common source of confusing answers. If you're filtered to internal time and you ask about external customer activity, the data isn't in its context window.

**What about meeting summaries?** The Coach can access meeting summaries when a supported source is configured in [Settings → CRM → Meeting Summaries](https://learn.lumopath.ai/setup-and-administration/customization/crm-content-settings). Supported recording tools include Gong, Fireflies, Clari, Chorus, and Avoma — each stores summaries in Salesforce, where Lumopath reads them.

## What it won't do (by design)[](https://learn.lumopath.ai/ai-coach/what-it-can-and-cant-do#what-it-wont-do-by-design)

A few things the Coach is intentionally constrained from doing:

- **Make hiring or firing recommendations.** It can build a data-backed case for headcount, but the decision is yours.
    
- **Replace your judgment about specific people.** It can show you what's happening; you bring the context about _why_. The Coach is a starting point for conversations, not a substitute for them.
    
- **Use your data to train models for other customers.** Lumopath does not use any customer's data to train models for any other customer. Feedback on the Coach (thumbs up/down) trains it for your organization specifically. See [Data & Access Management](https://learn.lumopath.ai/trust-and-privacy/data-and-access).
    

## What "improving" means[](https://learn.lumopath.ai/ai-coach/what-it-can-and-cant-do#what-improving-means)

The Coach gets better over time — but only for your organization. Concretely:

- **Thumbs-up signals** train it on the patterns of questions and answers your team finds valuable.
    
- **Thumbs-down signals** flag what didn't work. Notes attached to thumbs-down are especially high-signal.
    
- **More integrations** improve answer quality dramatically — the Coach can only reason over what's connected.
    
- **More usage** sharpens its responses to your team's specific phrasing and concerns.
    

If a Coach response is wrong, generic, or misframed, **always leave a thumbs-down with a brief note**. That's the single highest-leverage thing any user can do to make the Coach better for your team.

## Related[](https://learn.lumopath.ai/ai-coach/what-it-can-and-cant-do#related)

- [AI Coach Overview](https://learn.lumopath.ai/ai-coach/overview) — what the Coach is and when to reach for it
    
- [How to Use the AI Coach](https://learn.lumopath.ai/ai-coach/how-to-use) — hands-on procedural guide
    
- [Effective Prompting](https://learn.lumopath.ai/ai-coach/effective-prompting) — getting better answers
    
- [How the AI Coach Reasons](https://learn.lumopath.ai/how-lumopath-works/how-the-ai-coach-reasons) — the conceptual layer underneath