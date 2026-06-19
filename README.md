# stripe-billing-pro

Manage resources using stripe natively from your AI agent.

## Requirements

- **License key** — purchase from [MCP Marketplace](https://mcpmarketplace.com) to get your `MCP_LICENSE_KEY`
- Node.js 18+

## Installation

```json
{
  "mcpServers": {
    "stripe-billing-pro": {
      "command": "npx",
      "args": [
        "-y",
        "stripe-billing-pro"
      ],
      "env": {
        "MCP_LICENSE_KEY": "your-license-key-here"
      }
    }
  }
}
```

## Tools

| Tool | Description |
|------|-------------|
| `manage` | Run arbitrary commands using the stripe CLI. |

## Development

```bash
npm install
npm run build
npm test
```
