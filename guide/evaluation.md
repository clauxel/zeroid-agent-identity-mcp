# Evaluation Guide

Use this page to evaluate whether ZeroID Agent Identity fits a real workflow.

## What To Test

- ZeroID
- ZeroID Agent Identity
- ZeroID Agent Identity documentation
- ZeroID Agent Identity remote MCP
- zeroidagent server card

## Expected Evidence

- Open ZeroID Agent Identity and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://zeroidagent.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call issue_agent_identity with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://zeroidagent.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=zeroidagent_public_docs&utm_content=evaluation_checkout
