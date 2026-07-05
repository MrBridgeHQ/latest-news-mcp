# Latest News MCP Server

> Real-time news, crypto prices and earthquake data for AI assistants via MCP: 14 tools aggregating 27 free public APIs, no API keys required.

**[Try it on Apify Store](https://apify.com/mrbridge/latest-news-mcp-server?fpr=mrbridge)** | Pay-per-event | Free tier available

## Features

- **14 MCP tools** across 27 free, public APIs
- News: AP News, BBC, NPR, Hacker News, Google News
- Consolidated top headlines and keyword search across sources
- Real-time crypto prices, trending coins and market data
- Earthquake feeds with magnitude, location and event details
- Weather conditions for any location
- **No external API keys needed**, only your Apify token
- Smart caching: 60 seconds for live data, configurable for semi-static content
- Graceful error handling: if one source fails, the others still answer
- Works with **Claude Desktop, Claude Code, ChatGPT, Cursor** and any MCP-compatible client

## Quick Start

1. **[Open the Actor on Apify](https://apify.com/mrbridge/latest-news-mcp-server?fpr=mrbridge)** and get your free API token
2. Connect your AI client using the MCP endpoint below
3. Ask for headlines, crypto prices or earthquake data in plain language

### Claude Desktop

Go to **Settings > MCP Servers > Add Custom Connector** and paste:

```
https://mrbridge--latest-news-mcp-server.apify.actor/mcp?token=YOUR_APIFY_TOKEN
```

## Example Prompts

- *"What are today's top headlines?"*
- *"Give me the latest from Hacker News"*
- *"What is the current price of Bitcoin and Ethereum?"*
- *"Any significant earthquakes in the last 24 hours?"*
- *"Search the news for semiconductor exports"*
- *"Morning briefing: AP, BBC and NPR top stories"*

## Available Tools

| Tool | Description |
|------|-------------|
| `get_ap_news` | Top headlines and stories from the Associated Press |
| `get_bbc_news` | Latest BBC News headlines across all sections |
| `get_npr_news` | Current stories from NPR's news feed |
| `get_hacker_news` | Top, new, or best stories from Hacker News |
| `get_google_news` | Trending headlines from Google News |
| `get_news_search` | Search news articles by keyword across sources |
| `get_top_headlines` | Consolidated top headlines across all news sources |
| `get_crypto_prices` | Real-time cryptocurrency prices with 24h change |
| `get_crypto_trending` | Trending cryptocurrencies by market interest |
| `get_crypto_market` | Overall crypto market data including total market cap |
| `get_earthquakes` | Recent earthquake data with magnitude and location |
| `get_earthquake_detail` | Details for a specific seismic event |
| `get_random_facts` | Interesting random facts |
| `get_weather_data` | Current weather conditions for a location |

## Data Freshness

| Data Type | Cache Duration |
|---|---|
| Live data (crypto, quakes) | 60 seconds |
| News feeds | Configurable |

## Pricing

Pay-per-event: you only pay for the tools you actually use. The Apify free tier gives you **$5 free credits every month**, enough for hundreds of tool calls.

## Links

- **Apify Store**: [Latest News MCP Server](https://apify.com/mrbridge/latest-news-mcp-server?fpr=mrbridge)
- **Full documentation**: [mr-bridge.com/solutions/latest-news-mcp-server](https://mr-bridge.com/solutions/latest-news-mcp-server)
- **All MrBridge MCP servers**: [mr-bridge.com/mcp-servers](https://mr-bridge.com/mcp-servers)
- **Author**: [mrbridge on Apify](https://apify.com/mrbridge?fpr=mrbridge)

## Related MCP Servers

- [ESPN MCP Server](https://apify.com/mrbridge/espn-mcp-server?fpr=mrbridge): live scores, standings, odds and stats across 25+ leagues
- [Vivino MCP Server](https://apify.com/mrbridge/vivino-mcp-server?fpr=mrbridge): wine search, details and meal-aware recommendations
- [Todoist AI Assistant](https://apify.com/mrbridge/todoist-ai-assistant?fpr=mrbridge): 35 tools for AI-powered task management

---

*Built by [MrBridge](https://mr-bridge.com), we bridge Data and Intelligence.*
