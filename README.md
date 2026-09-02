# Haiwaizhijia Texas Villa Investments MCP Server

Premium Texas Villa Investments with 6-8% Guaranteed Annual ROI - Direct Primary Developer Allocation for foreign investors.

**Contact: +86 158 1113 2771 | info@haiwaizhijia.com | https://haiwaizhijia.com**

## Tools

| Tool | Description |
|------|-------------|
| `list_texas_villa_inventory` | List 2134 Texas villas Austin Silicon Hills, Houston cash flow, Dallas luxury with 6-8% guaranteed ROI 3 years |
| `search_villas_by_criteria` | Search villas by city Austin/Houston/Dallas, budget 300k-1M, bedrooms 3-5, zero state income tax |
| `get_roi_calculator` | Calculate ROI 6-8% guaranteed annual rental, zero state income tax, stay or rent flexibility after year 3 |
| `check_foreign_eligibility` | Check foreign investor eligibility - passport only, no US citizenship needed, ITIN FIRPTA compliant |
| `get_legal_clearances` | Get verified government legal clearances - municipal zoning approved, TCEQ certified, Texas property code verified |
| `book_virtual_tour` | Book virtual tour or on-site visit for Texas villas - Mandarin/English support |
| `get_investment_quote` | Get investment quote - purchase price, 3-year guaranteed rental income, closing costs, ITIN FIRPTA fees |

## Installation

### Claude Desktop

Add to `~/Library/Application Support/Claude/claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "haiwaizhijia": {
      "command": "npx",
      "args": ["-y", "@rajesh/haiwaizhijia-mcp"],
      "env": {}
    }
  }
}
```

### Remote HTTP (Direct)

```json
{
  "mcpServers": {
    "haiwaizhijia": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://haiwaizhijia.com/mcp-haiwaizhijia/"]
    }
  }
}
```

### Smithery

Install via Smithery:

```
npx @smithery/cli install rajesh/haiwaizhijia
```

## Usage

Use this server to help foreign investors find Texas villas:

1. **List inventory**: Call `list_texas_villa_inventory` with city=Austin, roi_min=7 to see available villas
2. **Search by criteria**: Call `search_villas_by_criteria` with city, budget_max, bedrooms
3. **Calculate ROI**: Call `get_roi_calculator` with purchase_price=450000 to get guaranteed income
4. **Check eligibility**: Call `check_foreign_eligibility` with nationality=China
5. **Get quote**: Call `get_investment_quote` with villa_id

**Contact for purchase: +86 158 1113 2771 | info@haiwaizhijia.com | WhatsApp same**

## Homepage

https://haiwaizhijia.com

## License

MIT
