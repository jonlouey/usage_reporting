Principles for getting useful answers out of the AI Coach. The difference between a question that lands and one that doesn't.

The AI Coach is a powerful tool, but the quality of the answer depends heavily on how you ask. This page is the short list of principles that consistently produce useful outputs. None of them are surprising — but applied together, they're the difference between "this is helpful" and "this is generic."

For curated prompts that already follow these principles, see the [Prompt Library](https://learn.lumopath.ai/ai-coach/prompt-library).

## The five principles[](https://learn.lumopath.ai/ai-coach/effective-prompting#the-five-principles)

### 1. Set your filters first[](https://learn.lumopath.ai/ai-coach/effective-prompting#id-1.-set-your-filters-first)

This is the single highest-leverage habit. The Coach can only reason over the data your filters expose. A great question with the wrong filters returns a useless answer.

- Set the **team or individual** before clicking Summarize.
    
- Set the **date range**. "This week" and "last quarter" are very different conversations.
    
- Set the **customer or segment** if your question is account-specific.
    

If you change your mind mid-conversation, change the filters and ask again. The next response will use the new scope.

### 2. Be specific about what you want returned[](https://learn.lumopath.ai/ai-coach/effective-prompting#id-2.-be-specific-about-what-you-want-returned)

Vague questions get vague answers. Concrete questions get concrete answers.

Vague

Specific

"How's the team doing?"

"Summarize the team's capacity over the last 8 weeks. What's driving the trend?"

"Is this person OK?"

"Compare Sarah's activity patterns to peers in the same role. Where is she different?"

"What should I do about Acme?"

"What signals suggest Acme is at risk, and what specifically has changed in the last 30 days?"

The Coach handles open-ended questions, but giving it a target — what you want covered, in what format, ranked how — produces something you can use directly.

### 3. Reference the data you want it to use[](https://learn.lumopath.ai/ai-coach/effective-prompting#id-3.-reference-the-data-you-want-it-to-use)

Tell the Coach what kinds of signals to consider. This keeps it grounded in real data instead of generalizing.

- Bad: "Why is this team struggling?"
    
- Good: "Based on capacity trends, account health, and activity patterns over the last 6 weeks, what's driving this team's strain?"
    

The Coach has access to a lot of data, but pointing it at specific dimensions tells it where to look first.

### 4. Iterate, don't restart[](https://learn.lumopath.ai/ai-coach/effective-prompting#id-4.-iterate-dont-restart)

The Coach maintains context across the conversation. If the first answer is close but not quite right, ask a follow-up — don't start over.

> **You:** "Summarize my team's capacity over the last 8 weeks."
> 
> **Coach:** _(returns summary)_
> 
> **You:** "Drill into the outliers. Why is Sarah the highest?"
> 
> **Coach:** _(zooms in on Sarah specifically)_
> 
> **You:** "What would change if we moved 2 of her accounts to Daniel?"
> 
> **Coach:** _(models the rebalance)_

Three short follow-ups produced something more useful than any single mega-prompt could have. Use the back-and-forth.

### 5. Anchor with examples when you can[](https://learn.lumopath.ai/ai-coach/effective-prompting#id-5.-anchor-with-examples-when-you-can)

If you're asking the Coach to do something subjective — coaching recommendations, recognition, talking points — give it an example of the kind of output you want.

> "Suggest a coaching focus for Daniel. Make it specific and actionable — not 'improve time management' but something like 'his internal meeting time is 40% above peer average, ask about the recurring Thursday sync.'"

The example sets the bar. Without it, the Coach defaults to safe, generic recommendations.

## Common antipatterns[](https://learn.lumopath.ai/ai-coach/effective-prompting#common-antipatterns)

### The "magic word" question[](https://learn.lumopath.ai/ai-coach/effective-prompting#the-magic-word-question)

Asking the Coach to do something it can't do, hoping it figures out what you meant.

> "Read the last email from Acme and tell me if they're frustrated."

The Coach can reason over engagement _patterns_ and metadata — but it doesn't read individual email content. A better question: "Based on response time, sentiment signals, and engagement trends, is Acme showing signs of disengagement?"

For more on what the Coach can and can't see, see [What It Can and Can't Do](https://learn.lumopath.ai/ai-coach/what-it-can-and-cant-do).

### The "boil the ocean" question[](https://learn.lumopath.ai/ai-coach/effective-prompting#the-boil-the-ocean-question)

Asking such a broad question that the Coach has to summarize at the top level and can't surface specifics.

> "Tell me everything about my team."

Better: pick a lens. Capacity, KPIs, account coverage, individual outliers. Ask one question with one focus, then iterate.

### The "filterless" question[](https://learn.lumopath.ai/ai-coach/effective-prompting#the-filterless-question)

Asking a question that requires data your current filters have excluded.

> _(Filter: this customer's account view)_
> 
> _(Question: "Compare my team's performance to other teams in the org.")_

The Coach can only see the customer in the filter. It will either return nothing useful or give you a hedged, generic answer. The fix is to change the filter scope before asking.

### The "infinite specificity" question[](https://learn.lumopath.ai/ai-coach/effective-prompting#the-infinite-specificity-question)

Cramming so many requirements into one prompt that the Coach hedges everything.

> "Summarize my team's capacity, but also tell me about each customer, and also rank by ARR, and also compare to last quarter, and also recommend coaching for each person, and also..."

Pick one job per prompt. Use follow-ups for the next one.

## When you can't get a useful answer[](https://learn.lumopath.ai/ai-coach/effective-prompting#when-you-cant-get-a-useful-answer)

If you've tried specific filters, specific questions, and one or two follow-ups and still can't get there, work through these in order:

1. **Try a** [**Prompt Library**](https://learn.lumopath.ai/ai-coach/prompt-library) **prompt that's close to your question.** Library prompts have been tuned to produce specific outputs.
    
2. **Check that the data you need is connected.** A question that requires Slack data won't work if Slack isn't integrated. Check [Setup → Integrations](https://learn.lumopath.ai/setup-and-administration/integrations).
    
3. **Give the response a thumbs-down with a brief note.** This is how the Coach gets better for your organization specifically.
    
4. **If something looks like a real bug or hallucination**, flag it to [support@lumopath.ai](mailto:support@lumopath.ai) with the question and the response.