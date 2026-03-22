# 🌦️ weatherOracle

**Consumer MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/weather/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "weatheroracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/weather/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `weather_current` | Current weather conditions for any city or coordinates. Returns temperature, fee |
| `weather_forecast` | 7-day (up to 14-day) daily weather forecast. Temperature range, precipitation, w |
| `weather_hourly` | 24-hour hourly weather breakdown. Temperature, precipitation probability, wind,  |
| `weather_alerts` | Severe weather alert check for next 3 days. Configurable thresholds for wind spe |
| `weather_air_quality` | European Air Quality Index (AQI) plus PM2.5, PM10, ozone, NO2, SO2 for any locat |
| `weather_marine` | Marine/ocean conditions: wave height, wave period, swell, ocean current velocity |
| `weather_astronomy` | Sunrise, sunset, daylight hours, sunshine hours, and UV index for 7 days. |
| `weather_history` | Historical weather data for any past date. Temperature range, precipitation, win |
| `weather_compare` | Compare current weather across 2-5 cities simultaneously. Returns side-by-side c |
| `health_check` | WeatherOracle server status and backend connectivity check. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

weatherOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/weather/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
