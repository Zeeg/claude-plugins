# Zeeg plugin for Claude Code

Connects Claude Code to the Zeeg MCP server (`https://api.zeeg.me/mcp`) and adds three skills:

| Skill | What it does |
|---|---|
| `booking-operations` | Find times, book, reschedule, cancel and hand over meetings |
| `crm-hygiene` | Find and fix duplicate or incomplete CRM people and companies |
| `agent-tuning` | Review an AI phone agent's calls and suggest prompt changes |

On first use Claude Code opens the Zeeg sign-in and consent page in the browser. The connection acts with your Zeeg permissions and needs a paid plan or a trial. Disconnect it in Zeeg under Settings → Connected apps.

Each skill also names the matching `zeeg` CLI commands for terminal use.

## Try it from this checkout

```bash
claude --plugin-dir plugins/zeeg
```

Documentation: https://developer.zeeg.me/mcp-server
