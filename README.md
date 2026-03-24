# Civic Intelligence Search Tool

> **Status:** Active

Open WebUI tool for cross-source search across all civic intelligence data and data freshness status.

Part of the [Change Agent Civic Intelligence Platform](https://github.com/unreliable-machine/civic-tools/blob/main/PLATFORM.md).

## Installation

1. Open your Open WebUI instance → **Admin Panel** → **Tools** → **+**
2. Paste the contents of `civic_search.py`
3. Save → configure Valves (gear icon)

## Valves

| Valve | Value |
|-------|-------|
| `GOVCON_API_URL` | `https://govcon-api-production.up.railway.app` |
| `GOVCON_API_KEY` | Your GOVCON API key |
| `TIMEOUT` | `30` |

## Methods

- `search_all`
- `data_status`

## Test

```
Search civic data for climate change
```

## Backend API

`govcon-api`

## Related

- [civic-tools](https://github.com/unreliable-machine/civic-tools) — umbrella repo with all 7 civic tools
- [civic-finance](https://github.com/unreliable-machine/civic-finance) — campaign finance microservice
- [civic-irs](https://github.com/unreliable-machine/civic-irs) — IRS 990 filings microservice
- [govcon-intelligence](https://github.com/unreliable-machine/govcon-intelligence) — procurement, grants, legislators, courts

## License

MIT
