The general flow for creating any digest in Lumopath. Pick a type, configure the scope, set the schedule, choose recipients.

Setting up a digest takes about two minutes. The flow is the same regardless of which type you create — pick the type, configure what it covers, set the schedule, and choose who gets it. This page is the general walkthrough; for type-specific details, see the dedicated page for the type you're creating.

## Before you start[](https://learn.lumopath.ai/digests/setting-up-a-digest#before-you-start)

You'll need:

- **Access to a team you manage** (or visibility into one) — you can't create a digest for a team you don't have visibility into. See [Data & Access Management](https://learn.lumopath.ai/trust-and-privacy/data-and-access) if you're not sure what you have access to.
    
- **A clear answer to "what is this digest for"** — pick one job. Coaching prep, leadership update, customer health monitoring, or a custom report. Don't try to make one digest do all of them.
    

## The general flow[](https://learn.lumopath.ai/digests/setting-up-a-digest#the-general-flow)

### Open the Digests page[](https://learn.lumopath.ai/digests/setting-up-a-digest#open-the-digests-page)

In the left navigation, click **Digests**. You'll see the list of digests already created (yours, plus any you have visibility into). Click **Create Digest** in the top right.

### Pick the type[](https://learn.lumopath.ai/digests/setting-up-a-digest#pick-the-type)

A modal appears with the available digest types as cards. Pick the one that matches the job:

- [**Weekly Coaching Plan**](https://learn.lumopath.ai/digests/digests/weekly-coaching-plan) — per-employee analysis for managers running 1:1s
    
- [**Executive / Leadership Digest**](https://learn.lumopath.ai/digests/digests/executive-leadership-digest) — org-level "what's most important if I was OOO" summary for senior leaders
    
- [**Daily IC Briefing**](https://learn.lumopath.ai/digests/digests/daily-ic-briefing) — daily account priorities for ICs
    
- [**Custom Digest**](https://learn.lumopath.ai/digests/digests/custom-digest) — anything else
    

If you're not sure which fits, read the type descriptions on the cards or jump to the dedicated pages linked above.

### Name the digest[](https://learn.lumopath.ai/digests/setting-up-a-digest#name-the-digest)

Give the digest a name you'll recognize when you see it on the listing later. Names are private to the configuration — they don't show up in the email subject. Good names answer "what is this digest for?" — e.g., "Ori's CS Team Coaching Plan" or "Weekly Strategic Accounts Review."

### Configure the data scope[](https://learn.lumopath.ai/digests/setting-up-a-digest#configure-the-data-scope)

This is the part that varies by type. In all cases, you'll specify _what data the digest analyzes_:

- **For a Weekly Coaching Plan:** which team members to coach (up to 10 per digest), and which [KPIs](https://learn.lumopath.ai/how-lumopath-works/kpis) to analyze (up to 10, with 3 marked as "always visible").
    
- **For an Executive / Leadership Digest:** which teams, [Squads, or Segments](https://learn.lumopath.ai/how-lumopath-works/squads-and-segments) to summarize.
    
- **For a Custom Digest:** the specific data sources, KPIs, and customer or team scope you want included.
    
- **For a Daily IC Briefing:** which IC's accounts to cover. Account ranking is driven by [urgency rules](https://learn.lumopath.ai/setup-and-administration/customization/urgency-rules).
    

The dedicated type pages walk through each option in detail.

### Set the schedule[](https://learn.lumopath.ai/digests/setting-up-a-digest#set-the-schedule)

Choose when the digest goes out. **Frequency depends on the digest type:**

- **Weekly Coaching Plan and Executive / Leadership Digest** are hardcoded to weekly cadence. You pick the day and time, but you cannot change the frequency. If you need a more complex pattern (e.g., a separate digest per team member, each scheduled to arrive before that person's 1:1), create multiple digests — see "Need more granular scheduling?" below.
    
- **Daily IC Briefing** is hardcoded to daily cadence. You pick the time of day.
    
- **Custom Digests** support flexible scheduling — weekly, every weekday, monthly, etc. — depending on the use case.
    

For all types, you also configure:

- **Day and time** — within whatever frequency the type allows
    
- **Time zone** — anchor for delivery timing
    
- **Lookback** — how much history each delivery analyzes (e.g., "last 7 days")
    

The most common pattern for a Coaching Plan is **Monday at 9:00 AM in your local time zone, looking back at the previous 7 days** — it lines up with the start of most teams' work week.

For more on schedule options, see [Recipients & Schedule](https://learn.lumopath.ai/digests/recipients-and-schedule).

**Need more granular scheduling?** Because the Coaching Plan and Executive Digest are weekly-only, the way to get more frequency or more targeted timing is to create multiple digests. For example, if you have 5 direct reports and run their 1:1s on different days, you can create five Coaching Plans — one per person, each scheduled to arrive the morning before that person's 1:1.

### Add recipients[](https://learn.lumopath.ai/digests/setting-up-a-digest#add-recipients)

Add the email addresses that should receive each delivery. Recipients don't have to be Lumopath users — you can email a digest to anyone in your organization. Common patterns:

- **Just yourself** — for personal coaching prep or self-monitoring
    
- **You + your boss** — to give your manager visibility without an extra meeting
    
- **You + your team** — for shared context across the whole team
    
- **Senior leadership** — for executive digests routed to VPs or directors
    

Recipients see the digest as an email — they don't need to log in to Lumopath to read it.

**Pro tip — send a digest to a Slack channel.** Slack lets you generate a unique email address for any channel (Channel settings → Integrations → "Get email address for this channel"). Paste that address into the recipients field and your digest will post directly to Slack on its schedule. Great for team channels, leadership channels, or a dedicated #digest-room.

### Send a test (optional but recommended)[](https://learn.lumopath.ai/digests/setting-up-a-digest#send-a-test-optional-but-recommended)

Before you save, click **Send Test** to email yourself a sample of what the digest will look like. The test uses real data from your most recent period so you can verify:

- The right team or scope is selected
    
- The KPIs you picked are the ones you actually want
    
- The narrative output reads the way you expected
    
- The recipients list includes everyone it should
    

If something looks off, fix it before saving. It's much easier to adjust now than after the digest has been sending the wrong thing for two weeks.

### Save[](https://learn.lumopath.ai/digests/setting-up-a-digest#save)

Click save and the digest is live. It will send on the next scheduled delivery. You can verify it's set up correctly on the [Digests listing page](https://learn.lumopath.ai/digests/setting-up-a-digest) — the row will show its name, type, scope, recipients, and schedule, with an "Active" badge.

## After it's running[](https://learn.lumopath.ai/digests/setting-up-a-digest#after-its-running)

Once a digest is live, you can manage its lifecycle from the listing page:

- **Send Test** — Email yourself a fresh copy on demand (useful for debugging or showing a colleague)
    
- **Pause** — Stop deliveries without losing the configuration
    
- **Edit** — Change scope, schedule, or recipients
    
- **Delete** — Remove the digest entirely
    

For details, see [Pausing, Editing, Deleting](https://learn.lumopath.ai/digests/pausing-editing-deleting).

## Common pitfalls[](https://learn.lumopath.ai/digests/setting-up-a-digest#common-pitfalls)

### Don't set up too many digests at once[](https://learn.lumopath.ai/digests/setting-up-a-digest#dont-set-up-too-many-digests-at-once)

A common first-day instinct is to create five digests covering every possible angle. Resist it. Pick the one that maps to the most painful current question (usually a Weekly Coaching Plan), get a few weeks of value from it, and _then_ add more. Email fatigue is real and digest fatigue is real.

### Match the recipient list to the audience[](https://learn.lumopath.ai/digests/setting-up-a-digest#match-the-recipient-list-to-the-audience)

A coaching digest you read alone is fine. A coaching digest you send to your team without telling them you're doing it is awkward. Confirm with people before adding them as recipients to anything that includes their data.

### Test before you trust[](https://learn.lumopath.ai/digests/setting-up-a-digest#test-before-you-trust)

Always click Send Test before saving. The Coach is good but the data scope and KPI selection can be subtly wrong in ways you won't notice until the test arrives.