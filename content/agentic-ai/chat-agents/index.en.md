+++
title = "Chat Agents"
weight = 52
+++

Chat Agents are persona-based AI assistants with custom instructions and data access. They show that one Quick environment serves many roles.

## Step 1: Create an agent for each persona

For each persona from Module 1, create a Chat Agent using this template:

```text
Create a Chat Agent called "{Role Title}" with these instructions:

You are an AI assistant for the {role title}.
Your job is to {2-3 specific responsibilities from Module 1}.
Always lead with {what matters most to this role}.
When {metric} is below {threshold}, flag it and recommend action.
Use the data in the "{Space name}" Space for all answers.
Keep responses under 200 words unless asked for detail.
Ground every recommendation in specific data points.
```

## Step 2: Test each agent

Ask each agent the same question:

```text
What is the biggest risk to our performance this quarter?
```

**Verify:** Each agent frames the answer differently based on their role, but all reference the same underlying data.

## Step 3: Test a cross-functional question

Ask one agent a question that spans another persona's domain:

```text
How does {decision from Persona A's area} affect {metric from Persona B's area}?
```

This cross-functional insight is the strongest moment. It shows Quick connecting dots across organizational silos.

## What makes this powerful

> "Same data, three perspectives. Each agent knows its role and answers accordingly. The operations lead sees risk. The planner sees a gap. The finance lead sees cost. All grounded in the same truth."
