# Zeeg plugins for Claude Code

The Claude Code plugin marketplace for [Zeeg](https://zeeg.me), the AI-native scheduling platform with a built-in CRM and AI phone agents.

The `zeeg` plugin connects Claude Code to the Zeeg MCP server (`https://api.zeeg.me/mcp`) and adds skills for booking operations, CRM hygiene and tuning AI phone agents. See [plugins/zeeg](plugins/zeeg) for details.

## Install

```bash
claude plugin marketplace add Zeeg/claude-plugins
claude plugin install zeeg@zeeg-plugins
```

On first use Claude Code opens the Zeeg sign-in page in your browser. The connection acts with your own Zeeg permissions.

Documentation: https://developer.zeeg.me/mcp-server

## License

MIT, see [LICENSE](LICENSE).
