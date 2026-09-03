+++
title = "Flows"
weight = 54
+++

Flows are automated multi-step workflows. They chain together actions into a repeatable process.

## Step 1: Create a Flow

Design a Flow relevant to your use case:

| Focus area | Example Flow |
|------------|-------------|
| Supply chain | Weekly delivery alert: query the Space, flag entities below target, generate a summary |
| Sales | Daily pipeline digest: check account health, flag at-risk deals, draft an update |
| Operations | Shift briefing: pull latest metrics, rank by performance, generate a report |
| Finance | Monthly variance report: compare actuals to budget, flag overruns, summarize actions |

## Step 2: Build the Flow

1. Navigate to **Flows** in Amazon Quick
2. Click **Create Flow**
3. Describe it in plain language:

```text
Create a flow called "Weekly {Metric} Alert" that:
1. Queries the "{Space name}" Space for the latest {central metric}
2. Flags any {entity} below {target threshold}
3. For each flagged entity, identifies the top contributing factor
4. Generates a 1-page summary with the data, flags, and recommended actions
5. Saves the summary as a document
```

## Step 3: Test the Flow

Run it manually and verify:
- [ ] Queries the correct data
- [ ] Flags are accurate
- [ ] The generated summary is well-structured
- [ ] The output is shareable

## What makes this powerful

> "This runs on a schedule. The team gets an automated briefing without anyone lifting a finger. And because it pulls from the Space, the answers are always current."
