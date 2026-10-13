
Common digest issues and how to fix them. Not receiving a digest, missing data, recipients not getting it, content looking wrong.

If a digest isn't behaving the way you expect, work through these in order. Most issues fall into one of four buckets: not receiving the email, recipients having issues, missing or wrong data, or the analysis itself looking off.

For general data issues that aren't specific to digests, see [Data Quality Gotchas](https://learn.lumopath.ai/how-lumopath-works/data-quality-gotchas).

## Not receiving a digest[](https://learn.lumopath.ai/digests/troubleshooting#not-receiving-a-digest)

You set up a digest, the schedule has passed, but nothing is in your inbox.

### Step 1 — Check spam, promotions, and other folders[](https://learn.lumopath.ai/digests/troubleshooting#step-1-check-spam-promotions-and-other-folders)

The most common cause. Digest emails from `lumopath.ai` sometimes land in spam, promotions, or a custom inbox folder, especially the first few times.

**Fix:**

- Search your full mailbox (including spam) for "Lumopath" or the digest's name
    
- Mark any digests you find as "not spam" or move them to your inbox
    
- Add `lumopath.ai` to your safe senders list
    
- If you're on Gmail, drag the email from "Promotions" to "Primary" — Gmail learns from this
    

### Step 2 — Verify the digest is Active, not Paused[](https://learn.lumopath.ai/digests/troubleshooting#step-2-verify-the-digest-is-active-not-paused)

Open the [Digests listing page](https://learn.lumopath.ai/digests/troubleshooting) and check the digest's row. Look for the status badge:

- **Active** — should be sending on schedule
    
- **Paused** — won't send until resumed
    
- _(no badge or different label)_ — flag to support
    

**Fix:** If it's paused, click the action button to resume it. The next delivery will go out at the next scheduled time.

### Step 3 — Verify you're a recipient[](https://learn.lumopath.ai/digests/troubleshooting#step-3-verify-youre-a-recipient)

Click **Edit** on the digest and check the **Recipients** field. Is your email address in the list? It's surprisingly common to set up a digest, forget to add yourself as a recipient, and wonder why nothing arrives.

**Fix:** Add yourself to the recipients list, save, and click **Send Test** to verify.

### Step 4 — Check the schedule[](https://learn.lumopath.ai/digests/troubleshooting#step-4-check-the-schedule)

Edit the digest and verify the schedule:

- Is the **frequency** set correctly?
    
- Is the **day** the day you expect?
    
- Is the **time zone** set to match where you are?
    
- Has the next scheduled time actually passed yet?
    

A digest scheduled for "Monday at 9:00 AM ET" doesn't fire on Sunday. If you enable or create a digest after its scheduled time has already passed on the due day, it may still be delivered later that same day. Otherwise, the next delivery happens at the next scheduled date and time.

**Fix:** Adjust the schedule, or click **Send Test** if you want a copy right now.

### Step 5 — Send a test[](https://learn.lumopath.ai/digests/troubleshooting#step-5-send-a-test)

Click **Send Test** on the digest's row. This emails you a fresh copy immediately, regardless of the schedule.

- **If the test arrives** — the digest is correctly configured. The issue was either the schedule, an Active/Paused state, or email delivery to the recipient list. Re-verify the schedule and recipient address.
    
- **If the test does not arrive** — there's likely an email delivery issue at your end. Check spam, then flag to [support@lumopath.ai](mailto:support@lumopath.ai).
    

## A recipient isn't receiving deliveries[](https://learn.lumopath.ai/digests/troubleshooting#a-recipient-isnt-receiving-deliveries)

You're getting the digest but a colleague who should be on the recipient list isn't.

### Step 1 — Verify they're in the recipient list[](https://learn.lumopath.ai/digests/troubleshooting#step-1-verify-theyre-in-the-recipient-list)

Edit the digest and check the **Recipients** field. Confirm the colleague's email address is spelled correctly. A typo (e.g., a missing letter or a `.con` instead of `.com`) is the single most common cause.

### Step 2 — Have them check spam and promotions[](https://learn.lumopath.ai/digests/troubleshooting#step-2-have-them-check-spam-and-promotions)

Same as above, but on their side. Have them search their full mailbox for "Lumopath" and the digest name.

### Step 3 — Check whether their organization blocks external email[](https://learn.lumopath.ai/digests/troubleshooting#step-3-check-whether-their-organization-blocks-external-email)

In some organizations, IT filters block emails from external domains by default. If you're an external partner sending a digest into another organization, it may not reach the recipient at all.

**Fix:** Have the recipient ask their IT to allow `lumopath.ai`, or send the digest to a different address (e.g., a personal email that isn't subject to the same filtering).

### Step 4 — Send a test from your account[](https://learn.lumopath.ai/digests/troubleshooting#step-4-send-a-test-from-your-account)

Click **Send Test** on the digest. The test goes only to you. If you receive it normally, the issue is specific to that recipient — usually a typo, spam filter, or organizational email rule.

## The digest arrives but data looks wrong[](https://learn.lumopath.ai/digests/troubleshooting#the-digest-arrives-but-data-looks-wrong)

The digest is being delivered, but the content is wrong — wrong people, wrong accounts, wrong metrics, or numbers that don't match what you see in the dashboard.

### Step 1 — Check the data scope in the configuration[](https://learn.lumopath.ai/digests/troubleshooting#step-1-check-the-data-scope-in-the-configuration)

Edit the digest and review:

- **Team Members to Coach** (or equivalent) — are the right people listed?
    
- **Metrics to Analyze** — are the right [KPIs](https://learn.lumopath.ai/how-lumopath-works/kpis) selected?
    
- **Teams (Data Source)** — is the right team or [Squad](https://learn.lumopath.ai/how-lumopath-works/squads-and-segments) being pulled from?
    
- **Lookback period** — is it the time window you expect?
    

**Fix:** Adjust whatever's wrong, save, and click **Send Test** to verify.

### Step 2 — Check the underlying integrations[](https://learn.lumopath.ai/digests/troubleshooting#step-2-check-the-underlying-integrations)

If specific data is missing — e.g., the digest doesn't reflect Slack activity, or ticketing data isn't showing up — the issue is usually that the relevant integration isn't connected.

Go to **Settings → Integrations** and verify that all the tools the digest depends on show "Connected" with a recent sync date.

For more on integration-related data issues, see [Data Quality Gotchas](https://learn.lumopath.ai/how-lumopath-works/data-quality-gotchas).

### Step 3 — Compare against the dashboard[](https://learn.lumopath.ai/digests/troubleshooting#step-3-compare-against-the-dashboard)

Open [Team Overview](https://learn.lumopath.ai/feature-reference/team-overview) (or whichever dashboard the digest pulls from), set the same filters and time range as the digest's data scope, and compare what you see there to what the digest contains.

- **If the dashboard matches the digest** — both are correct, your expectation was off
    
- **If the dashboard matches your expectation but the digest doesn't** — the digest's configuration is set wrong; edit it to match the dashboard filters
    
- **If the dashboard doesn't match either** — there's a data issue at the source. See [Data Quality Gotchas](https://learn.lumopath.ai/how-lumopath-works/data-quality-gotchas), then escalate if needed
    

### Step 4 — Send a test against the current data[](https://learn.lumopath.ai/digests/troubleshooting#step-4-send-a-test-against-the-current-data)

Click **Send Test** to generate a fresh copy. This rules out the possibility that you're looking at an old delivery — the test always uses the latest data.

## The analysis itself looks off[](https://learn.lumopath.ai/digests/troubleshooting#the-analysis-itself-looks-off)

The data scope is right, the integrations are connected, but the AI-generated analysis is generic, vague, or seems to be missing the obvious thing.

### Step 1 — Check the number of KPIs[](https://learn.lumopath.ai/digests/troubleshooting#step-1-check-the-number-of-kpis)

The most common cause of weak coaching analysis is too many KPIs in a single digest. The Coach gives sharper output when focused on 3–5 well-chosen metrics rather than 8+ generic ones.

**Fix:** Edit the digest, drop to your top 3–5 KPIs, send a test, and compare.

### Step 2 — Check the team/data source[](https://learn.lumopath.ai/digests/troubleshooting#step-2-check-the-team-data-source)

For a Weekly Coaching Plan, peer comparisons rely on the **Teams (Data Source)** field. If the data source is mismatched (e.g., comparing CSMs to a team that includes managers), comparisons will be off.

**Fix:** Adjust the data source to a comparable group of roles.

### Step 3 — Check that integrations cover the work that matters[](https://learn.lumopath.ai/digests/troubleshooting#step-3-check-that-integrations-cover-the-work-that-matters)

If a digest covering a chat-heavy team doesn't have Slack connected, the Coach is reasoning over a small fraction of the team's actual work — and the analysis will reflect that.

**Fix:** Connect the missing integrations under **Settings → Integrations**, wait for the next sync, and re-test.

### Step 4 — Send feedback in the digest itself[](https://learn.lumopath.ai/digests/troubleshooting#step-4-send-feedback-in-the-digest-itself)

Some digest emails include feedback links or thumbs-up / thumbs-down controls (similar to the [AI Coach](https://learn.lumopath.ai/ai-coach/how-to-use) inline feedback). Use these — they train the Coach for your organization specifically.

### Step 5 — Flag to support[](https://learn.lumopath.ai/digests/troubleshooting#step-5-flag-to-support)

If the analysis is consistently wrong in ways the above don't fix — for example, the Coach is hallucinating accounts, attributing activity to the wrong person, or producing recommendations that don't match the data — send the digest, the configuration, and a description of what's wrong to [support@lumopath.ai](mailto:support@lumopath.ai).

## When to escalate[](https://learn.lumopath.ai/digests/troubleshooting#when-to-escalate)

Escalate to [support@lumopath.ai](mailto:support@lumopath.ai) if:

- Test deliveries aren't arriving even after the spam/folder check
    
- A recipient consistently can't receive the digest after troubleshooting at their end
    
- Data is wrong in a way that doesn't match the dashboard either (suggests an underlying data issue)
    
- The Coach is generating clearly hallucinated content (wrong account names, fabricated employees, contradictory facts)
    

When you escalate, include:

- The digest's name
    
- Which delivery (the test, the most recent scheduled, etc.)
    
- A specific example of what's wrong
    
- What you expected
    
- A screenshot of the email if possible