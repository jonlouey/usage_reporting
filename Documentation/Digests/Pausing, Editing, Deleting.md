Managing the lifecycle of a digest after it's created. The four actions on every row, what each does, and when to use them.

Every digest on the [Digests listing page](https://learn.lumopath.ai/digests/pausing-editing-deleting) has the same four lifecycle actions. This page explains what each does, when to use them, and what happens when you do.

## The four actions[](https://learn.lumopath.ai/digests/pausing-editing-deleting#the-four-actions)

Each digest row in the listing has these action buttons, in order:

1. **Send Test** — Email yourself a fresh copy on demand
    
2. **Pause** — Stop deliveries without losing the configuration
    
3. **Edit** — Change the digest's name, scope, schedule, or recipients
    
4. **Delete** — Remove the digest entirely
    

## Send Test[](https://learn.lumopath.ai/digests/pausing-editing-deleting#send-test)

Email yourself (only you, not the configured recipients) a fresh copy of the digest using the latest data. The test reflects the current configuration, so it's the best way to verify that what you've set up actually produces what you expected.

### When to use Send Test[](https://learn.lumopath.ai/digests/pausing-editing-deleting#when-to-use-send-test)

- **Before saving a new digest** — verify the configuration produces something useful
    
- **After editing a live digest** — confirm the changes do what you intended
    
- **When debugging a digest that seems wrong** — see what the digest is actually generating right now
    
- **To preview for a colleague** — generate a sample you can share without committing them as a permanent recipient
    

### What Send Test does and doesn't do[](https://learn.lumopath.ai/digests/pausing-editing-deleting#what-send-test-does-and-doesnt-do)

- **Sends only to you** — not to the configured recipients list
    
- **Uses real data** from the most recent applicable period
    
- **Doesn't affect the schedule** — the next regularly scheduled delivery still goes out as planned
    
- **Doesn't count against any rate limits**
    

A test is the safest way to interact with a digest. There's no consequence for sending one.

## Pause[](https://learn.lumopath.ai/digests/pausing-editing-deleting#pause)

Stop deliveries without losing the digest's configuration. The digest's row stays on the listing but won't send until you resume it.

### When to use Pause vs. Delete[](https://learn.lumopath.ai/digests/pausing-editing-deleting#when-to-use-pause-vs.-delete)

- **Use Pause when you want to stop deliveries temporarily** — vacation, a project that's wrapping up, a digest that's not currently relevant but might be again
    
- **Use Pause when you're testing changes** — pause, edit, send a test, verify, resume
    
- **Use Delete when you're sure you won't need the digest again**
    

Pausing is reversible. Deleting is not. When in doubt, pause.

### What pausing does[](https://learn.lumopath.ai/digests/pausing-editing-deleting#what-pausing-does)

- **Stops scheduled deliveries** immediately — the next scheduled send is skipped
    
- **Preserves the full configuration** — name, scope, KPIs, recipients, schedule, lookback
    
- **Marks the digest as Paused** on the listing — you'll see a paused indicator instead of an Active badge
    
- **Doesn't notify recipients** — paused digests just stop arriving; there's no automated message about why
    

### Resuming a paused digest[](https://learn.lumopath.ai/digests/pausing-editing-deleting#resuming-a-paused-digest)

Click the same button (which now reads "Resume" or similar) on a paused digest to resume scheduled deliveries. The next delivery happens at the next scheduled time per the existing schedule — pausing doesn't fire a make-up delivery.

## Edit[](https://learn.lumopath.ai/digests/pausing-editing-deleting#edit)

Change any part of the digest's configuration. The edit page shows the same fields you saw at creation — name, scope, KPIs, recipients, schedule, lookback — and you can change any of them.

### What can be edited[](https://learn.lumopath.ai/digests/pausing-editing-deleting#what-can-be-edited)

Everything. There are no fields locked after creation.

- **Name** — rename for clarity
    
- **Scope (team members, KPIs, data sources)** — narrow or expand what's analyzed
    
- **Recipients** — add or remove email addresses
    
- **Schedule** — change frequency, day, time, time zone
    
- **Lookback** — adjust the analysis window
    

### When changes take effect[](https://learn.lumopath.ai/digests/pausing-editing-deleting#when-changes-take-effect)

**On the next scheduled delivery, not retroactively.**

This means:

- If you add someone to the recipients list, they get the _next_ delivery and onward — they don't get a backfill of past deliveries
    
- If you change the team scope, the next delivery analyzes the new scope; past deliveries remain as they were
    
- If you change the schedule, the new schedule starts immediately (the next delivery happens at the next time matching the new schedule)
    
- If you change the lookback, the next delivery uses the new window
    

If you need to verify the change worked, click **Send Test** after saving the edit.

### When to edit vs. create a new digest[](https://learn.lumopath.ai/digests/pausing-editing-deleting#when-to-edit-vs.-create-a-new-digest)

Edit when:

- You're making a small tweak (adjusting recipients, swapping a KPI, changing the time)
    
- The digest's job is the same and you're just refining it
    

Create a new digest when:

- The job is fundamentally changing (e.g., switching from coaching focus to leadership reporting)
    
- You want both the old and new version (consider pausing the old one rather than deleting)
    
- You're changing the digest type entirely
    

When in doubt, create a new one. It's a 2-minute operation.

## Delete[](https://learn.lumopath.ai/digests/pausing-editing-deleting#delete)

Permanently remove the digest. The row disappears from the listing and the digest stops sending immediately.

### What deleting does[](https://learn.lumopath.ai/digests/pausing-editing-deleting#what-deleting-does)

- **Stops all future deliveries** immediately
    
- **Removes the digest from the listing**
    
- **Deletes the configuration** — name, scope, KPIs, recipients, schedule
    
- **Does not delete past deliveries** — emails recipients have already received remain in their inboxes
    

### What you can't get back[](https://learn.lumopath.ai/digests/pausing-editing-deleting#what-you-cant-get-back)

Deleting is permanent. There's no recovery, no archive, no undo. If you delete a digest and later realize you need it, you'll have to recreate it from scratch.

For this reason: **prefer Pause over Delete unless you're sure you'll never need the digest again.** A paused digest occupies almost no mental overhead — it sits on the listing as a paused row — and it can be resumed in two clicks.

### When to delete[](https://learn.lumopath.ai/digests/pausing-editing-deleting#when-to-delete)

- **Test digests you set up while learning the product** — the "Try this" digest you made on day one and never use
    
- **Digests for projects or initiatives that have completed** — and won't repeat
    
- **Duplicates** — if you accidentally created two of the same digest
    
- **Configurations that are completely wrong** — easier to delete and recreate than edit
    

## Common pitfalls[](https://learn.lumopath.ai/digests/pausing-editing-deleting#common-pitfalls)

### Deleting when you meant to pause[](https://learn.lumopath.ai/digests/pausing-editing-deleting#deleting-when-you-meant-to-pause)

The most common mistake. If you want to "stop this for now," use Pause. Delete is for "I'm sure I won't need this again."

### Forgetting that edits don't fire an immediate delivery[](https://learn.lumopath.ai/digests/pausing-editing-deleting#forgetting-that-edits-dont-fire-an-immediate-delivery)

If you edit a digest in the morning and want to verify the change immediately, click **Send Test** — don't wait for the next scheduled delivery.

### Editing the recipient list and forgetting to remove someone[](https://learn.lumopath.ai/digests/pausing-editing-deleting#editing-the-recipient-list-and-forgetting-to-remove-someone)

If you add a recipient by mistake, edit again to remove them. Past deliveries to them are already in their inbox; removing them only affects future deliveries.

### Confusing Send Test with a regular delivery[](https://learn.lumopath.ai/digests/pausing-editing-deleting#confusing-send-test-with-a-regular-delivery)

Send Test goes only to you, regardless of the recipient list. It's a personal preview. If you want to send a real delivery to the full recipient list outside the schedule, the workflow is to edit the schedule to fire sooner, then change it back — there's no "send to all recipients now" button.