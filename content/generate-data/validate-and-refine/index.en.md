+++
title = "Validate and refine"
weight = 42
+++

## Step 1: Spot-check the data

Before building anything, verify the data supports your story:

```text
Look at the data you just generated. Answer these questions:
1. Which entity ranks lowest on the central metric?
2. What root cause can you trace from the data?
3. Is the time series trend visible and realistic?
4. Is the deliberate gap present?
```

## Step 2: Test the hero questions

Ask your four hero questions (H1-H4) against the data:

```text
Using the data you generated, answer: {your H1 question}
```

Repeat for H2, H3, and H4. Verify:
- [ ] H1 returns a clear ranking with no ties
- [ ] H2 identifies the root cause you embedded
- [ ] H3 produces a usable artifact (not just a paragraph)
- [ ] H4 calculates a credible dollar impact

## Step 3: Refine if needed

| Problem | Fix prompt |
|---------|-----------|
| Rankings too close | "Widen the spread. Make the worst performer clearly worse." |
| Root cause not traceable | "Make the root cause more explicit. Add a column for {cause}." |
| Time series is flat | "Add a clear declining trend for {entity} over the last {N} periods." |
| Numbers feel fake | "Add more variability. Real data has noise." |
| Missing a persona's view | "Add a file for {metric} that {persona} would care about." |

## Step 4: Generate a situation brief (optional)

For richer context in your Space:

```text
Write a 1-page situation brief that describes the organization,
the key people, current challenges, and business context for this
use case. Make it realistic but entirely fictional.
```

Download this alongside your CSV files.
