
Hands-on guide to using the AI Coach. Where the button lives, how filters define context, and how to ask follow-up questions.

This page is the procedural how-to. For the conceptual layer (what the Coach can and can't see, why filters matter), see [How the AI Coach Reasons](https://learn.lumopath.ai/how-lumopath-works/how-the-ai-coach-reasons). For curated prompts to copy-paste, see the [Prompt Library](https://learn.lumopath.ai/ai-coach/prompt-library).

## Find the AI Coach button[](https://learn.lumopath.ai/ai-coach/how-to-use#find-the-ai-coach-button)

The AI Coach lives behind a **Summarize** or **AI Coach** button that appears across most dashboards in Lumopath. Look for it on:

- [Team Overview](https://learn.lumopath.ai/feature-reference/team-overview)
    
- [Customer Details](https://learn.lumopath.ai/feature-reference/customer-details)
    
- [Cost to Serve](https://learn.lumopath.ai/feature-reference/cost-to-serve)
    
- Segment Details
    
- And other views — see [Where It Appears](https://learn.lumopath.ai/ai-coach/where-it-appears) for the full list
    

Clicking Summarize opens the Coach as a side panel against whatever you currently have on screen.

On [**Customer Prioritization**](https://learn.lumopath.ai/feature-reference/customer-prioritization), the Coach is also available as a **mini Coach** inside the insight drawer — click any account row to open the drawer, then type your question in the chat input at the bottom. This lets you ask quick follow-up questions about a specific account without navigating away from the table.

## Set your filters first[](https://learn.lumopath.ai/ai-coach/how-to-use#set-your-filters-first)

This is the single most important habit when using the Coach: **set your filters before you click Summarize.** The Coach only reasons over the data your filters expose. Two filter scopes shape every interaction.

### Dashboard-level filters (top of the page)[](https://learn.lumopath.ai/ai-coach/how-to-use#dashboard-level-filters-top-of-the-page)

These define the _who_ and _when_:

- Team, individuals, or [Squad](https://learn.lumopath.ai/how-lumopath-works/squads-and-segments)
    
- Date range
    
- Customer or [Segment](https://learn.lumopath.ai/how-lumopath-works/squads-and-segments)
    

### Summarize-window filters (inside the Coach panel)[](https://learn.lumopath.ai/ai-coach/how-to-use#summarize-window-filters-inside-the-coach-panel)

Once you open the Coach, additional filters narrow the scope further:

- **Work category** — proactive / [reactive](https://learn.lumopath.ai/how-lumopath-works/reactive-vs-proactive)
    
- **Work context** — internal / external
    
- **Tool** — email, calendar, ticketing, chat, etc.
    

### What this means in practice[](https://learn.lumopath.ai/ai-coach/how-to-use#what-this-means-in-practice)

If you're filtered to a single customer and you ask "how's my team doing this quarter?", the Coach will answer in the context of _that customer_, not your whole team. If you're filtered to internal time only and you ask about external customer activity, you'll get a blank or unhelpful answer because the data isn't in its context window.

The fix is always the same: **change your filters, then ask**. Or open the [Prompt Library](https://learn.lumopath.ai/ai-coach/prompt-library), where prompts note their filter requirements.

## Ask a question[](https://learn.lumopath.ai/ai-coach/how-to-use#ask-a-question)

You have two ways to give the Coach a question:

### Pick from the Prompt Library[](https://learn.lumopath.ai/ai-coach/how-to-use#pick-from-the-prompt-library)

Click Summarize and the Coach surfaces curated prompts you can run as-is. These are pre-loaded based on the dashboard you're on, plus the full [Prompt Library](https://learn.lumopath.ai/ai-coach/prompt-library) catalog. Most prompts have variables in `{{double curly braces}}` — replace them with your specifics before submitting.

### Type your own question[](https://learn.lumopath.ai/ai-coach/how-to-use#type-your-own-question)

Plain language works. The Coach handles full sentences, fragments, follow-ups, and clarifications. A few examples that work well:

> "Summarize this team's capacity over the selected period and tell me what's driving it."

> "Compare Sarah's activity to her peers — what's different?"

> "Are any of these accounts at risk of churn based on engagement patterns?"

Rules of thumb for writing your own:

- Be specific about what you want returned ("a 3-bullet summary," "ranked from most concerning")
    
- Reference the data you want it to use ("based on capacity trends and account health")
    
- If it gives you a vague answer, your question was probably vague — rephrase
    

For more on prompting principles, see [Effective Prompting](https://learn.lumopath.ai/ai-coach/effective-prompting).

## Iterate with follow-ups[](https://learn.lumopath.ai/ai-coach/how-to-use#iterate-with-follow-ups)

The Coach handles follow-up questions naturally. You don't have to repeat your filters — they stay set across the conversation.

> **You:** "Summarize my team's capacity over the last 8 weeks."
> 
> **Coach:** _(returns a summary covering trends, outliers, and drivers)_
> 
> **You:** "Drill into the outliers. Why is Sarah the highest?"
> 
> **Coach:** _(returns analysis of Sarah specifically, using the same filter context)_
> 
> **You:** "What would it look like if we moved 2 of her accounts to Daniel?"
> 
> **Coach:** _(models the rebalance based on current capacity and account load)_

If you want to change scope mid-conversation, change the filters and ask again. The Coach's next response will use the new scope.

## Give feedback[](https://learn.lumopath.ai/ai-coach/how-to-use#give-feedback)

Every Coach response has a thumbs-up and thumbs-down button. Use them.

The Coach is constantly improving — **but only for your organization**. Lumopath does not use your data to train models for other customers. Instead, the more your team uses the Coach and gives feedback, the better it gets at interpreting your specific context. Concretely:

- **Thumbs-up** signals that an answer was useful as-is. The Coach learns the patterns in the questions and answers your team finds valuable.
    
- **Thumbs-down** signals that something was wrong, missing, or misframed. If you can, leave a brief note explaining what didn't land — that's much higher-signal than the thumbs-down alone.
    

For more on data handling and what's stored, see [Data & Access Management](https://learn.lumopath.ai/trust-and-privacy/data-and-access).

## A few power-user tips[](https://learn.lumopath.ai/ai-coach/how-to-use#a-few-power-user-tips)

- **Connect every relevant tool first.** Coach quality depends on how much of your team's work is visible to Lumopath. More integrations = better answers.
    
- **Build a habit of weekly Summarize sessions.** Most managers find more value from a 5-minute check-in once a week than a long deep-dive once a month.
    
- **Pair with the dashboard, don't replace it.** Use the Coach to find what to look at, then click into the dashboard for specifics.
    
- **When in doubt, start with a Prompt Library prompt.** The library is faster than typing and the prompts have been tuned to produce specific outputs.
    

## When the Coach gives a bad answer[](https://learn.lumopath.ai/ai-coach/how-to-use#when-the-coach-gives-a-bad-answer)

If you ask a question and get a vague, generic, or wrong-feeling response, work through these in order:

1. **Check your filters.** Are they scoped to the data the question requires? This is the cause about 70% of the time.
    
2. **Rephrase with more specificity.** "How's the team doing?" → "What's driving the change in our team's capacity over the last 6 weeks, broken down by activity type?"
    
3. **Try a** [**Prompt Library**](https://learn.lumopath.ai/ai-coach/prompt-library) **version of what you're asking.** The library prompts have been tuned to produce useful output.
    
4. **Give it a thumbs-down with a note.** This is how the Coach gets better for your organization.
    
5. **If something looks like a real bug or hallucination**, flag it to [support@lumopath.ai](mailto:support@lumopath.ai) with the question and the response.