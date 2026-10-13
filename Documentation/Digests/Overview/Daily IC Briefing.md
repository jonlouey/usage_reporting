A daily morning email that ranks an IC's accounts by urgency, combining priority KPI signals with AI-generated insights from across the data Lumopath collects. The IC equivalent of the Weekly Coaching

**The Daily IC Briefing is a daily morning email built for Individual Contributors managing customer accounts.** Each delivery ranks the IC's accounts by urgency, combining signals from [priority KPIs](https://learn.lumopath.ai/setup-and-administration/customization/priority-kpis) with AI-generated insights drawn from across all the data Lumopath collects. The IC opens it before their day starts and walks in already knowing which 3–5 accounts need attention today.

It is the IC equivalent of what the [Weekly Coaching Plan](https://learn.lumopath.ai/digests/digests/weekly-coaching-plan) is for managers and the [Executive / Leadership Digest](https://learn.lumopath.ai/digests/digests/executive-leadership-digest) is for senior leaders.

## Why this digest[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#why-this-digest)

ICs managing customer accounts face a time problem that's different from a manager's. A manager runs 1:1s on a weekly cadence and the Coaching Plan matches that rhythm. A leader reviews the org weekly and the Executive Digest matches theirs. But an IC's day is daily — they wake up, look at their inbox, and decide what to focus on. Without help, that decision is usually driven by whichever customer emailed most loudly the day before.

The Daily IC Briefing replaces "loudest inbox" with "what does the data say needs attention today?" By the time the IC opens their email at 7:30 AM, the AI has already:

- Ranked their accounts by urgency
    
- Surfaced what's going on with each one — contact gaps, ticket spikes, engagement drops, expansion signals
    
- Written a short specific insight per account drawing on meeting summaries, CRM changes, ticket patterns, Pendo usage, and other connected data
    
- Suggested a concrete next step for each one
    

The IC reads it in two minutes, picks the 3–5 accounts that need them today, and starts their day with data instead of guesswork.

## What it contains[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#what-it-contains)

Each delivery is structured as a scannable email, not a wall of AI text. The shape:

### Header[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#header)

A short greeting and a count of accounts needing attention, plus a summary bar showing the urgency breakdown for the day:

> Good morning, Sarah. 5 accounts need your attention today across your book of 47. **2 Urgent** · **2 Attention** · **1 Opportunity** · **42 On Track**

### Account cards (the main section)[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#account-cards-the-main-section)

Each flagged account gets a card with:

- **Account name + ARR + context** (e.g., "Renewal in 45 days")
    
- **Signal tags** showing what's driving the urgency. Priority KPI signals are prefixed with **★** so the IC can see at a glance which signals tie back to org priorities:
    
    - `★ No contact in 18 days` — a priority KPI signal
        
    - `★ Single-threaded` — another priority KPI
        
    - `3 tickets >48h` — a regular KPI signal
        
    - `Expansion signal detected` — an AI-detected qualitative signal
        
    
- **AI insight paragraph** — 2–3 sentences specific to the account, referencing actual data sources ("Jamie Torres went silent after the March QBR" not "engagement has declined")
    
- **Next step** — a concrete action recommendation
    
- **A "View [Account] in Lumopath" link** that deep-links to [Customer Details](https://learn.lumopath.ai/feature-reference/customer-details)
    

The cards are color-coded by urgency:

- **Red border** — Urgent: multiple bad signals or one severe signal (high ARR + overdue renewal + no contact)
    
- **Amber border** — Attention: one or two moderate signals
    
- **Blue border** — Opportunity: positive signals worth acting on (expansion, usage growth)
    

The email caps at roughly 5–7 detailed account cards. ICs with hundreds of accounts will have most of their book filtered out — the AI's job is to surface only the truly notable.

### Wins & positive signals[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#wins-and-positive-signals)

A compact list (max 3 entries) of accounts on a positive trajectory worth knowing about even though they don't need an action — usage growth, renewals trending well, accounts that recovered from a previous flag.

### Footer[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#footer)

- Count of "On Track" accounts (no action needed)
    
- A "View All Accounts in Lumopath" button linking to [Customer Prioritization](https://learn.lumopath.ai/feature-reference/customer-prioritization)
    
- Manage preferences and pause links
    

### How accounts are ranked[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#how-accounts-are-ranked)

Accounts are ranked by their [urgency label](https://learn.lumopath.ai/how-lumopath-works/urgency-score), determined by the [urgency rules](https://learn.lumopath.ai/setup-and-administration/customization/urgency-rules) your admin has configured. The highest-category rule that fires for an account sets its label (Urgent > Attention > Opportunity > On Track). Within the same label, the AI uses additional signals to order accounts:

1. **KPI signals** — how many KPIs are in a concerning state for this account, including any [priority KPIs](https://learn.lumopath.ai/setup-and-administration/customization/priority-kpis) (marked with ★)
    
2. **Qualitative data** — meeting summaries (from Gong, Fireflies, Clari, Chorus, Avoma, or other [configured sources](https://learn.lumopath.ai/setup-and-administration/customization/crm-content-settings)), email metadata, CRM changes, ticket patterns, Slack activity, Pendo usage data, and other connected sources
    

The IC doesn't see or need to understand the ranking logic. They just see accounts ordered by urgency. The AI insight per account explains _why_ that account is flagged in plain language.

## Who it's for[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#who-its-for)

The Daily IC Briefing is built for **ICs managing customer accounts**. Specifically:

- Customer Success Managers (CSMs)
    
- Account Managers (AMs)
    
- Anyone with a book of accounts and a daily rhythm of customer outreach
    

It is **not** designed for:

- Managers running 1:1s — they should use the [Weekly Coaching Plan](https://learn.lumopath.ai/digests/digests/weekly-coaching-plan) instead
    
- Senior leaders managing managers — they should use the [Executive / Leadership Digest](https://learn.lumopath.ai/digests/digests/executive-leadership-digest)
    

The loose role mapping for digests in Lumopath:

Role

Primary digest

Leader managing managers

[Executive / Leadership Digest](https://learn.lumopath.ai/digests/digests/executive-leadership-digest)

Manager running 1:1s

[Weekly Coaching Plan](https://learn.lumopath.ai/digests/digests/weekly-coaching-plan)

IC managing accounts

**Daily IC Briefing**

## Setup[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#setup)

The general digest creation flow is covered in [Setting Up a Digest](https://learn.lumopath.ai/digests/setting-up-a-digest). The Daily IC Briefing has the simplest setup of any digest type because the AI uses your priority KPIs and all available data automatically — there's no per-KPI selection step.

### Digest Name[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#digest-name)

Auto-populated as "Daily Briefing for [Your First Name]." Edit if you want something different.

### Accounts[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#accounts)

Defaults to **My Accounts** — pulled from CRM ownership. The default is what most ICs want.

You can modify the scope:

- **Add specific accounts** that you co-own or are involved with even if they're not formally assigned to you
    
- **Remove accounts** that show up under your name in CRM but that you don't actually manage
    
- **Switch to a custom list** — useful if you're temporarily covering for a colleague or focused on a specific cohort
    

### Schedule[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#schedule)

**The Daily IC Briefing is hardcoded to daily cadence** — the whole point is that it's a daily ritual.

What you can change:

- **Frequency** — Daily (weekdays only) is the default. Daily (every day, including weekends) is also an option.
    
- **Time of day** — typically 7:30 AM, configurable in 30-minute increments
    
- **Time zone** — anchor for delivery timing
    

The default and recommended schedule:

- **Daily (weekdays)**
    
- **7:30 AM** in your local time zone
    

This gets the briefing into your inbox before the start of the work day so you can read it over coffee.

### Recipients[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#recipients)

Defaults to your own email. You can add additional recipients — for example, your manager (so they have visibility into the same daily picture you're working from), or a colleague covering for you.

For the Slack channel email pro tip — useful if you want the briefing to post into a personal channel — see [Recipients & Schedule](https://learn.lumopath.ai/digests/recipients-and-schedule).

### Send a test[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#send-a-test)

Click **Send Test** to verify the configuration before saving. The test reflects today's data. Verify:

- Your accounts are the right ones (not someone else's, no missing accounts)
    
- The urgency ranking matches what you know about your book
    
- The narrative reads usefully (not generic)
    

If something looks off, edit the configuration before saving.

### Admin defaults[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#admin-defaults)

If you're an admin setting up the Daily IC Briefing for your team, you can create a default Briefing configuration that applies to all ICs. Individual ICs can then modify their own copy (change accounts, schedule, etc.). Contact your CSM or [support@lumopath.ai](mailto:support@lumopath.ai) to set up a default for your team.

## Using it well[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#using-it-well)

The Daily IC Briefing is built around a 5-minute morning ritual.

### The morning pattern[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#the-morning-pattern)

1. **Open the Briefing first thing in the morning** — before your inbox, not after. The whole point is to set the day's focus before the loudest emails do.
    
2. **Scan the urgency summary at the top** — how many accounts need attention today?
    
3. **Read each Urgent card** — these are the accounts where you need to take action today, not later this week.
    
4. **Read each Attention card** — these are the ones where you should plan a touchpoint today or tomorrow, but don't have to drop everything.
    
5. **Glance at the Opportunity cards** — these are positive signals you can act on if you have bandwidth (e.g., "Acme's usage spiked 40% this month — good time to pitch the upgrade").
    
6. **Skim Wins & Positive Signals** — accounts that are doing well. Don't act on these; just know they exist.
    
7. **Click "View All Accounts in Lumopath"** if you want the full table sorted by urgency. The same data lives in [Customer Prioritization](https://learn.lumopath.ai/feature-reference/customer-prioritization) with all of your accounts ranked, not just the top 5–7.
    

### The "deeper dive" pattern[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#the-deeper-dive-pattern)

For each account in the Briefing that you'll act on today, click through to its [Customer Details](https://learn.lumopath.ai/feature-reference/customer-details) page before reaching out. Customer Details shows:

- The full per-account [KPI cards](https://learn.lumopath.ai/feature-reference/customer-details) — including the priority KPIs with amber-bordered indicators
    
- The same AI insight from the Briefing, available inline as the **AI Insight box** above the existing tabs
    
- All the historical context (last contact, last meeting, open tickets, etc.) you'd want before sending an email or scheduling a call
    

The Briefing tells you _which_ accounts; Customer Details gives you _what to say_.

### What _not_ to do[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#what-not-to-do)

- **Don't try to act on every signal in every email.** The Briefing surfaces the top 5–7 most urgent. If you're behind, focus on Urgent first and accept that Attention items might wait until tomorrow.
    
- **Don't ignore the Opportunity cards.** Most ICs default to reactive mode and the positive signals get lost. Opportunities are where expansion conversations come from.
    
- **Don't replace the dashboard with the email.** The email is a daily nudge; the dashboard is the comprehensive view. Use both.
    

## Common pitfalls[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#common-pitfalls)

### "I have 80 accounts and the Briefing shows the same 5 every day"[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#i-have-80-accounts-and-the-briefing-shows-the-same-5-every-day)

Likely causes:

- **Those 5 actually are the most urgent** — chronic problems show up daily. The fix is to address them, not to ignore the Briefing.
    
- **Your priority KPIs are too narrow** — if your admin only marked one or two priority KPIs, the AI's ranking is less varied. Talk to your admin about broadening the [priority KPI set](https://learn.lumopath.ai/setup-and-administration/customization/priority-kpis).
    
- **You need to act on the chronic accounts** — if Acme has been Urgent for two weeks running, the answer is a difficult conversation with Acme, not turning off the digest.
    

### "I have 5 accounts and the Briefing tells me about all 5 every day"[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#i-have-5-accounts-and-the-briefing-tells-me-about-all-5-every-day)

For very small books (Enterprise CSMs, strategic AMs), the Briefing can feel less useful because you're already looking at every account regularly. In that case, the Briefing's value shifts from "what should I focus on?" (which you already know) to "what changed overnight?" — use it as the morning awareness check rather than the priority list.

### "The AI insight feels generic"[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#the-ai-insight-feels-generic)

Two usual causes:

- **Insufficient connected integrations** — the AI insight quality depends on how much data Lumopath sees. If only Email and Calendar are connected, the AI is reasoning over a small fraction of what's actually happening on the account. Check **Settings → Integrations**.
    
- **Not enough priority KPIs** — without priority KPI signals to anchor on, the AI defaults to broader patterns that can read as generic. Talk to your admin about marking the right KPIs as priority.
    

### "I'm not getting the email"[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#im-not-getting-the-email)

Same as any digest — check spam, verify recipients, verify the digest is Active. See [Troubleshooting](https://learn.lumopath.ai/digests/troubleshooting).

## What's connected to this digest elsewhere in Lumopath[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#whats-connected-to-this-digest-elsewhere-in-lumopath)

The Daily IC Briefing is part of a coordinated set of features that all work together. Knowing they exist helps explain why the Briefing references certain things:

- [**Priority KPI Settings**](https://learn.lumopath.ai/setup-and-administration/customization/priority-kpis) — Admins mark certain KPIs as "priority." Priority KPIs get visual ★ indicators in [Customer Prioritization](https://learn.lumopath.ai/feature-reference/customer-prioritization) and [Customer Details](https://learn.lumopath.ai/feature-reference/customer-details), and the AI Coach weighs them more heavily in its analysis.
    
- [**Customer Prioritization**](https://learn.lumopath.ai/feature-reference/customer-prioritization) — The full table view of your accounts, with the same urgency ranking the Briefing uses. Priority KPI columns show ★ in the header. This is the "view all accounts" page the Briefing's footer links to.
    
- [**Customer Details**](https://learn.lumopath.ai/feature-reference/customer-details) — The per-account view. Priority KPI cards are highlighted with an amber border, and the AI Insight box at the top shows the same insight that appeared in the Briefing for that account.
    

The flow is: you read the Briefing in the morning, click through to Customer Details for accounts you'll act on, and reference Customer Prioritization when you want the broader view. All three surface the same underlying signals.

## Related[](https://learn.lumopath.ai/digests/digests/daily-ic-briefing#related)

- [Setting Up a Digest](https://learn.lumopath.ai/digests/setting-up-a-digest) — the general creation flow
    
- [Reading a Digest](https://learn.lumopath.ai/digests/reading-a-digest) — the 90-second pattern for processing any digest
    
- [Recipients & Schedule](https://learn.lumopath.ai/digests/recipients-and-schedule) — including the Slack channel email pro tip
    
- [Weekly Coaching Plan](https://learn.lumopath.ai/digests/digests/weekly-coaching-plan) — the manager equivalent
    
- [Executive / Leadership Digest](https://learn.lumopath.ai/digests/digests/executive-leadership-digest) — the leader equivalent
    
- [IC1 — Which accounts should I focus on today?](https://learn.lumopath.ai/workflows/ics/ic1-daily-priorities) — the in-app workflow built around this digest
    
- [IC2 — How do I prepare for a customer meeting?](https://learn.lumopath.ai/workflows/ics/ic2-meeting-prep) — the workflow for digging into a specific account before reaching out