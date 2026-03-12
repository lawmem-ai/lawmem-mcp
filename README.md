# LawMem — Legal Memory for AI Agents
**LawMem.ai** gives legal AI agents persistent, searchable memory via MCP. Store case notes, client context, research findings, and matter history — recalled semantically when relevant.

## Quickstart
Add to your MCP config:

```json
{
  "mcpServers": {
    "lawmem": {
      "type": "http",
      "url": "https://api.lawmem.ai/mcp/",
      "headers": {
        "Authorization": "Bearer YOUR_LAWMEM_API_KEY"
      }
    }
  }
}
```

Get your API key at [lawmem.ai/signup](https://lawmem.ai/signup.html) — free tier available.

## Tools
| Tool | Description |
|---|---|
| `memory_store` | Store a memory with text, namespace, and optional metadata |
| `memory_search` | Semantic search across stored memories |
| `memory_list` | List memories by namespace |
| `memory_delete` | Delete a memory by ID |

## Auth
Bearer token — get your API key at [lawmem.ai/signup](https://lawmem.ai/signup.html).

## Pricing
| Plan | Price | Calls/mo |
|---|---|---|
| Free | $0 | 1,000 lifetime |
| Pay-as-you-go | $0 | $0.005/call |
| Legal Starter | $199/mo | 50,000 |
| Legal Pro | $499/mo | 150,000 |

## Compatibility
Works with Claude Desktop, Claude Code, Cursor, Windsurf, and any MCP-compatible client.

## Privacy & Compliance
Namespace-isolated, audit-logged, GDPR-compliant. [Terms](https://lawmem.ai/terms.html) · [Privacy](https://lawmem.ai/privacy.html)
