+++
title = "Topics"
weight = 62
+++

Topics are governed data domains with defined business terms, access controls, and data lineage. They ensure everyone gets the same answer to the same question.

## Step 1: Create a Topic

1. Navigate to **Topics** in Amazon Quick
2. Click **Create Topic**
3. Name it: "{Your Focus Area} Metrics"
4. Connect it to your dataset

## Step 2: Define business terms

For each key metric, define:

| Field | What to enter |
|-------|-------------|
| **Name** | The metric name |
| **Definition** | What it measures in plain language |
| **Calculation** | How it is computed |
| **Target** | The threshold or goal |

Ask Quick to help:

```text
For my dataset, suggest business term definitions I should configure
in a Topic. For each metric, give me the name, a plain-language
definition, the calculation, and a reasonable target.
```

## Step 3: Test the "same number" guarantee

Ask the same metric two different ways:

```text
What is our {metric} for {entity}?
```

Then rephrase:

```text
How are we performing on {alternative phrasing} at {entity}?
```

**Both should return the same number.** That consistency is the value of Topics.

## Step 4: Show data lineage

Click into the lineage view for any answer:
1. The answer (the number)
2. The source (which file, which columns)
3. The definition (how it is calculated)

## What makes this powerful

> "I asked the same question two ways and got the same answer. The metric is defined once, governed centrally, and every query traces back to the source. That is what trusted AI looks like."
