# Haiwaizhijia - Texas Real Estate MCP Server (Agent 5 Ready 100/100)

**Real estate dealer for Austin, Dallas, Houston in Texas USA**
Level 5 Agent-Native on [isitagentready.com](https://isitagentready.com) - AI agents can search, list, and book viewings automatically.

**MCP Endpoint:** `https://Haiwaizhijia.com/mcp-haiwaizhijia`
**Server Card:** `https://Haiwaizhijia.com/.well-known/mcp/server-card.json`
**AI Catalog (ARD):** `https://Haiwaizhijia.com/.well-known/ai-catalog.json`

## 🏠 What We Do

We are a Texas-focused real estate dealer covering:
- **Austin, TX** - Downtown, South Congress, Westlake, Cedar Park, Round Rock
- **Dallas, TX** - Downtown Dallas, Highland Park, Frisco, Plano, Irving
- **Houston, TX** - Galleria, The Heights, Sugar Land, Katy, Cypress

Specializing in residential, commercial, and investment properties for international buyers.

## 🛠️ MCP Tools for AI Agents

- `list_properties` - List all available properties in Austin, Dallas, Houston
- `search_properties` - Search by location (Austin/Dallas/Houston), price range, bedrooms, bathrooms, property type (house, condo, apartment, commercial, land), year built, sqft
- `get_property_details` - Full details: MLS ID, price, address, HOA, taxes, schools, walk score, 3D tour link
- `schedule_viewing` - Book in-person or virtual tour, with calendar integration
- `get_market_report` - Monthly market report for Austin, Dallas, Houston - median price, inventory, days on market

### Example Queries for AI Agents:
- "List 3-bed houses in Austin under $500k"
- "Search Dallas condos near downtown with 2 baths"
- "Get details for property at 123 Main St, Houston"
- "Schedule viewing for tomorrow at 2pm"
- "Get Austin market report for July 2026"

## 🤖 For AI Agents & LLMs

This MCP server is discoverable via:
- **MCP Server Card:** `/.well-known/mcp/server-card.json` (SEP-1649)
- **ARD Catalog:** `/.well-known/ai-catalog.json` (specVersion 1.0)
- **DNS TXT:** `_catalog._agents.Haiwaizhijia.com = "url=https://Haiwaizhijia.com/.well-known/ai-catalog.json"`

```json
{
  "mcpServers": {
    "haiwaizhijia-realestate": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-fetch"],
      "env": {
        "MCP_SERVER_URL": "https://Haiwaizhijia.com/mcp-haiwaizhijia"
      }
    }
  }
}
```

## 🌐 Agent Readiness - 100/100 Level 5

We publish:
- `/.well-known/mcp/server-card.json` - MCP discovery
- `/.well-known/ai-catalog.json` - ARD discovery
- `/llms.txt` and `/agents.md` for LLM context
- `robots.txt` with AI bot Allow rules
- Link headers RFC 8288

Check: https://isitagentready.com/Haiwaizhijia.com

## 📦 GitHub Repository

- **Repo:** `github.com/gaier/Haiwaizhijia-com-mcp`
- **Official Registry:** `registry.modelcontextprotocol.io`
- **Glama.ai:** `https://glama.ai/mcp/servers/@gaier/Haiwaizhijia-com-mcp`

This is one of 5 repos under same GitHub account `gaier-` (factory, trading, real estate).

## 📞 Contact

- **Company:** Haiwaizhijia
- **Texas Markets:** Austin, Dallas, Houston
- **China Office:** Floor 2, No.6 Hengxing Road, Guzhen, Zhongshan, Guangdong 528421
- **Phone / WhatsApp:** +86-15811132771
- **Website:** https://Haiwaizhijia.com

## 🏷️ Maintainer

`gaier-` - Same GitHub account for all 5 websites (factory + trading + real estate)
`glama.json`: `{"maintainers": ["gaier-"]}`
