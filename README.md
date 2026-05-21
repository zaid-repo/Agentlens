# AgentLens

AgentLens is a zero-install demo for debugging and red-teaming AI agents.

It shows how an agent handles a user goal, where it makes assumptions, which tool calls it would use, and how reliable the result looks before deployment.

## Why This Project Exists

Everyone is building AI agents. Fewer people are building tools to understand why agents fail.

AgentLens is a starter product idea for agent observability:

- Inspect agent plans and tool calls
- Detect missing information
- Flag unsafe or unverified actions
- Score reliability before an agent is trusted with real work

## Current Version

Version 1 is an interactive front-end prototype using plain HTML, CSS, and JavaScript. It includes:

- Agent goal input
- Sample scenario cards
- Simulated animated trace timeline
- Clickable step inspector
- Trace filters
- Risk-mode scoring
- Red-team checks
- Reliability scorecard
- Copyable audit summary
- Responsive dashboard UI

No installation is required.

## How To Run

Open `index.html` in a browser.

## Good Demo Tasks

Try these:

```text
Find the cheapest flight from Delhi to Mumbai tomorrow under Rs. 5000.
```

```text
Every Friday, collect invoices from Gmail, rename them, save them to Drive, and update a spreadsheet.
```

```text
Create a research brief on AI agents for small business automation with sources and confidence levels.
```

## Next Version Ideas

- Connect a real LLM
- Return structured JSON traces
- Add tool-call logging
- Add memory inspection
- Export audit reports
- Save runs locally
- Add real red-team test suites

## LinkedIn Post Hook

I built AgentLens, a debugging and red-team dashboard for AI agents.

Everyone is building agents. Very few people are building tools to understand why they fail.
