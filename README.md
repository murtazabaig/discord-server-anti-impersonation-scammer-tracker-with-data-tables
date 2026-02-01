![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Discord Server Anti-Impersonation / Scammer Tracker with Data Tables

Advanced n8n automation for Discord Server Anti-Impersonation / Scammer Tracker with Data Tables.

## Overview
- Category: SecOps
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Effortlessly track Discord member name changes with automated alerts, audit logs, and customizable options for improved moderation and security. Learn more!

## Included Files
- `workflow.json`
- `metadata.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `n8n-nodes-base.dataTable`
- `n8n-nodes-base.discord`
- `n8n-nodes-base.if`
- `n8n-nodes-base.noOp`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.set`
- `n8n-nodes-base.splitInBatches`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.switch`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.