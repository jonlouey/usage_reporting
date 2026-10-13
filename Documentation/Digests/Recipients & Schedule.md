How recipients work, schedule options, and what changes when you edit a live digest.

This page covers the configuration options that apply across all digest types — who receives the email, when it's delivered, and what time range each delivery analyzes.

## Recipients[](https://learn.lumopath.ai/digests/recipients-and-schedule#recipients)

Recipients are the email addresses that receive each delivery. Configure them when you create the digest, and update them at any time.

### Who can be a recipient[](https://learn.lumopath.ai/digests/recipients-and-schedule#who-can-be-a-recipient)

Anyone with a valid email address. Recipients **do not** need to be Lumopath users — you can email a digest to:

- Yourself
    
- Your manager or VP
    
- Members of your team
    
- A peer manager
    
- Internal stakeholders (RevOps, leadership, etc.)
    
- An internal mailing list
    
- **A Slack channel** (see the pro tip below)
    

**Pro tip — send a digest to a Slack channel.** Slack supports generating a unique email address for any channel. Anyone (or anything) that emails that address has the message posted directly into the Slack channel.

To set it up:

1. In Slack, open the channel you want to receive the digest
    
2. Click the channel name or settings menu, then go to **Integrations** (or **More** → **Integrations**)
    
3. Look for **"Get email address for this channel"** or **"Send emails to this channel"** (the exact label varies by Slack workspace settings)
    
4. Slack generates a long unique address that looks like `<random-id>@<workspace>.slack.com`. Copy it.
    
5. Back in Lumopath, paste that address into the recipients field for your digest
    

The digest will post to the Slack channel on its schedule, formatted as a normal Slack message with the digest content inline. Great for team channels, leadership channels, or a dedicated #digests channel where everyone can see what's arriving.

**Note:** This requires that your Slack workspace has channel-email integration enabled (it's enabled by default on most paid Slack workspaces, but some admins disable it). If you don't see the "Get email address" option in Slack, ask your Slack admin.

### How recipients see the digest[](https://learn.lumopath.ai/digests/recipients-and-schedule#how-recipients-see-the-digest)

Recipients receive the digest as a regular email — they don't need to log in to Lumopath to read it. The email contains the full digest content (the AI-generated analysis, the per-person sections, the metric summaries, etc.) inline.

If a recipient _is_ a Lumopath user with access to the underlying data, the email may also include links to relevant dashboards. If they're not, the email is self-contained and they read what's in the message.

### Privacy and visibility[](https://learn.lumopath.ai/digests/recipients-and-schedule#privacy-and-visibility)

A digest's contents reflect the data scope you configured at creation. Recipients see _whatever the configuration produces_ — there's no per-recipient filtering.

This matters for two reasons:

- **Coaching digests are candid.** A Weekly Coaching Plan contains direct coaching observations about each person on the team. Don't add a recipient who shouldn't see those observations. As a rule: if you wouldn't say it out loud in a meeting where the person was present, you probably shouldn't put them on a coaching digest that covers their teammates.
    
- **Account-level digests don't filter by ownership.** A digest covering "Strategic accounts" sends the same view to everyone on the recipient list, regardless of which accounts they personally own.
    

If you need different views for different audiences, create separate digests rather than trying to make one digest cover all recipients.

### Adding and removing recipients[](https://learn.lumopath.ai/digests/recipients-and-schedule#adding-and-removing-recipients)

Recipients can be added or removed at any time by editing the digest. See [Pausing, Editing, Deleting](https://learn.lumopath.ai/digests/pausing-editing-deleting). Changes take effect on the next delivery.

## Schedule[](https://learn.lumopath.ai/digests/recipients-and-schedule#schedule)

The schedule controls _when_ each delivery goes out and _what time range_ it analyzes.

### Frequency depends on the digest type[](https://learn.lumopath.ai/digests/recipients-and-schedule#frequency-depends-on-the-digest-type)

This is important to understand upfront: **frequency is not a free choice** for the role-specific digest types. Each type is hardcoded to a specific cadence.

Digest type

Frequency

What you can configure

**Weekly Coaching Plan**

Hardcoded weekly

Day of the week, time of day, time zone

**Executive / Leadership Digest**

Hardcoded weekly

Day of the week, time of day, time zone

**Daily IC Briefing**

Hardcoded daily

Time of day, time zone

**Custom Digest**

Flexible

Frequency (weekly, every weekday, monthly), day, time, time zone, lookback

### Why hardcoded frequencies[](https://learn.lumopath.ai/digests/recipients-and-schedule#why-hardcoded-frequencies)

The role-specific types are tuned around their job. The Coaching Plan is built around a weekly 1:1 cadence; weekly is what makes the AI analysis useful for that purpose. The Executive Digest is built around a leader's weekly review rhythm. Allowing arbitrary frequencies would dilute the analysis.

If you need a more frequent or more granular pattern, the answer is **create multiple digests**, not change the frequency. See "Need a digest more often than weekly?" below.

### Need a digest more often than weekly? Create multiple digests.[](https://learn.lumopath.ai/digests/recipients-and-schedule#need-a-digest-more-often-than-weekly-create-multiple-digests)

Because the Coaching Plan and Executive Digest are weekly-only, the way to get more frequency or more targeted timing is to create multiple digests of the same type, each with different scopes or schedules. Common patterns:

- **One Coaching Plan per direct report**, each scheduled to arrive the morning before that person's 1:1. If you have 5 reports running 1:1s on different days, that's 5 separate digests.
    
- **A weekly Executive Digest sent to you on Monday morning**, plus a **second one with the same scope sent to your VP on Friday afternoon**. Both reflect the same data; the timing serves different audiences.
    
- **A Coaching Plan covering your full team** for general awareness, plus **a tighter 3-person Coaching Plan** for the people you're actively focused on coaching this period.
    

There's no per-account limit on how many digests you can create. The constraint is your willingness to manage them.

### Day and time[](https://learn.lumopath.ai/digests/recipients-and-schedule#day-and-time)

Pick the day of the week (for weekly) or day of the month (for monthly), and the time of day. Common patterns:

- **Monday at 9:00 AM** in your local time zone — the most common Coaching Plan schedule, lining up with the start of the work week
    
- **Friday at 4:00 PM** — for end-of-week reviews
    
- **First Monday of the month** — for monthly Executive Digests
    
- **Every weekday at 9:00 AM** — for high-frequency Custom Digests covering daily activity
    

### Time zone[](https://learn.lumopath.ai/digests/recipients-and-schedule#time-zone)

Schedules are anchored to a time zone. Pick the time zone that matches the recipient audience — usually your own, but for digests sent to leadership in another region, match theirs.

If you have recipients in multiple time zones, the digest sends at one time and they receive it at their local equivalent. There's no per-recipient scheduling.

### Lookback period[](https://learn.lumopath.ai/digests/recipients-and-schedule#lookback-period)

Each delivery analyzes a time range — the "lookback period." For most weekly digests, this is the previous 7 days; for monthly digests, the previous 30 days.

The lookback should match the cadence:

- A weekly digest looking back 30 days will surface a lot of stale data
    
- A monthly digest looking back 7 days will miss most of the relevant context
    
- A daily digest looking back 7 days makes sense for "what happened in the last week" rolling reviews
    

The lookback can be customized — if your team's natural rhythm is to look at 14-day windows, configure that. The default settings are starting points, not requirements.

### Pausing the schedule[](https://learn.lumopath.ai/digests/recipients-and-schedule#pausing-the-schedule)

Pausing a digest is different from deleting it. A paused digest stops sending but keeps its configuration intact, so you can resume it later without rebuilding. See [Pausing, Editing, Deleting](https://learn.lumopath.ai/digests/pausing-editing-deleting).

## Editing a live digest[](https://learn.lumopath.ai/digests/recipients-and-schedule#editing-a-live-digest)

You can edit any part of a digest at any time — name, scope, KPIs, recipients, schedule, lookback. Changes take effect on the next delivery, not retroactively.

A few things to know:

- **Editing scope or KPIs** changes what the next delivery analyzes. If you remove someone from the team list, they won't appear in the next delivery (but they'll still have appeared in past deliveries).
    
- **Editing recipients** changes who gets the next delivery. Removing a recipient means they won't get future deliveries; they'll still have whatever past deliveries they already received.
    
- **Editing the schedule** doesn't fire an immediate delivery. The next scheduled time per the new schedule applies.
    
- **Editing the lookback** changes what data range the next delivery analyzes. Past deliveries are unaffected.
    

If you're making significant changes (e.g., switching from a coaching focus to a reporting focus, or completely changing the team), it's often cleaner to create a new digest and delete the old one rather than editing in place.

## Common pitfalls[](https://learn.lumopath.ai/digests/recipients-and-schedule#common-pitfalls)

### Time zone mismatch[](https://learn.lumopath.ai/digests/recipients-and-schedule#time-zone-mismatch)

A digest scheduled at 9:00 AM Eastern arriving for a recipient in Pacific time hits their inbox at 6:00 AM. Usually fine, but worth double-checking when you have international recipients.

### Recipient surprised to be on the list[](https://learn.lumopath.ai/digests/recipients-and-schedule#recipient-surprised-to-be-on-the-list)

If you add a colleague as a recipient without telling them, the next digest just shows up in their inbox unannounced. For coaching digests especially, give people a heads-up.

### Lookback not matching cadence[](https://learn.lumopath.ai/digests/recipients-and-schedule#lookback-not-matching-cadence)

A weekly digest with a 30-day lookback will tell you about things that already happened weeks ago. Adjust the lookback to match how often the digest runs.

### Forgetting to send a test after editing[](https://learn.lumopath.ai/digests/recipients-and-schedule#forgetting-to-send-a-test-after-editing)

If you make significant edits — adding KPIs, changing scope, switching teams — always click Send Test before saving. It's easy to introduce a configuration mistake that's invisible until the next scheduled delivery.