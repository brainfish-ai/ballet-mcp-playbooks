# Ballet MCP Playbooks

Agent workflows that call MCP servers such as Linear and Slack. One click into Ballet.

Built for developers building on the Model Context Protocol. Every template here imports into [Ballet](https://ballet.dev), the agent operations platform for building, running and observing deterministic workflows, with one click.

[![Validate](https://github.com/brainfish-ai/ballet-mcp-playbooks/actions/workflows/validate.yml/badge.svg)](https://github.com/brainfish-ai/ballet-mcp-playbooks/actions/workflows/validate.yml)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Templates

<!-- templates:start -->

### MCP

| Template | What it does | Trigger | Import |
|---|---|---|---|
| [Linear Weekly Digest via MCP](templates/mcp-linear-weekly-digest) | Read recent Linear issues and post a weekly digest to Slack, using the Linear and Slack MCP servers. | Manual run, or attach a weekly schedule in Studio | [Import](https://app.ballet.dev/import?repo=brainfish-ai/ballet-mcp-playbooks&path=templates/mcp-linear-weekly-digest&ref=main) |
| [Slack Thread to Linear Issue via MCP](templates/mcp-slack-thread-to-linear) | Turn a Slack thread into a well-formed Linear issue using the Slack and Linear MCP servers. | Manual run | [Import](https://app.ballet.dev/import?repo=brainfish-ai/ballet-mcp-playbooks&path=templates/mcp-slack-thread-to-linear&ref=main) |

<!-- templates:end -->

## How import works

1. Click **Import** next to a template.
2. Sign in or create a Ballet workspace. Ballet fetches the template from this repository, pinned to an exact commit.
3. Review the steps and code on the preview screen, then confirm.
4. Add the listed secrets and publish.

Imported playbooks always start unpublished with triggers off, and secrets are never part of a template.

## More templates

This repository is one focused slice of [brainfish-ai/ballet-templates](https://github.com/brainfish-ai/ballet-templates), which holds every Ballet template. Other collections:

- [ballet-support-playbooks](https://github.com/brainfish-ai/ballet-support-playbooks): Support triage, summaries and reply drafting for Zendesk, Freshdesk and more. One click into Ballet.
- [ballet-sales-playbooks](https://github.com/brainfish-ai/ballet-sales-playbooks): Lead enrichment, scoring and Slack alerts for Salesforce and web forms. One click into Ballet.
- [ballet-ops-playbooks](https://github.com/brainfish-ai/ballet-ops-playbooks): Signed webhooks, scheduled digests and issue triage with retries and observability. One click into Ballet.

## Contributing

This repository is generated from [brainfish-ai/ballet-templates](https://github.com/brainfish-ai/ballet-templates). Please open template pull requests there so every collection stays in sync. Issues are welcome here.

## License

[MIT](LICENSE)
