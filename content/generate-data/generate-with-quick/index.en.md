+++
title = "Generate with Quick"
weight = 41
+++

## Step 1: Open Amazon Quick Web

Sign into Amazon Quick. Start a new conversation.

## Step 2: Generate the dataset

Paste the following prompt, filling in your use case details from Module 1:

```text
I am building a demo for the following use case:

- Focus area: {your focus area}
- Personas: {list your 2-3 personas and what they care about}
- Central question: {your central question}
- Key metrics: {list your 4-5 metrics}
- Story arc:
  H1 (Overview): {what the ranking shows}
  H2 (Root cause): {what the drill-down reveals}
  H3 (Action): {what artifact to produce}
  H4 (Business case): {what dollar impact to calculate}

Generate a synthetic dataset as downloadable CSV files. Follow these rules:

1. RANK BELIEVABLY: Spread values so rankings look real. No round numbers.
   Example: four entities at 96.2, 93.1, 91.4, 87.3.

2. TRACEABLE CAUSE: Embed one clear root cause I can trace through the data.

3. TREND OVER TIME: Include at least 12 months or 26 weeks of time series
   so trends are visible in charts.

4. ONE DELIBERATE GAP: Do not include data for: {your unanswerable question}.

5. CROSS-FUNCTIONAL TENSION: Embed one conflict that spans two personas'
   domains.

For each CSV file, list the columns, the number of rows, and 3 example
questions someone could ask. Then generate the files.
```

## Step 3: Download the files

Quick will generate multiple CSV files. Download each one to a local folder.

Typical output:
- 3-6 CSV files covering your key metrics, time series, and entity details
- 50-1,500 rows per file depending on the metric

> **Tip:** If the data does not look right, tell Quick what to fix: "Make the gap between the top and bottom performer wider" or "Add a column for {cause category}." Iterate until the data supports your story.
