# ZeroID Agent Identity

ZeroID Agent Identity is a hosted remote MCP for ZeroID.

This repository is a public documentation project for ZeroID Agent Identity. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://zeroidagent.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=zeroidagent_public_docs&utm_content=readme_home
- Pricing: https://zeroidagent.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=zeroidagent_public_docs&utm_content=readme_pricing
- Checkout: https://zeroidagent.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=zeroidagent_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://zeroidagent.clauxel.com/mcp
- Server card: https://zeroidagent.clauxel.com/server-card.json
- Registry name: `com.clauxel.zeroidagent/zeroidagent-mcp`
- Tools: `issue_agent_identity`, `check_scope_lease`, `revoke_agent_identity`, `export_identity_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: issue_agent_identity
- MCP tool: check_scope_lease
- MCP tool: revoke_agent_identity
- MCP tool: export_identity_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
