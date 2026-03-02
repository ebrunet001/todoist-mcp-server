# Todoist MCP Server

> Connect AI assistants to Todoist via MCP — 35 tools for task management, project organization, and AI-powered productivity features.

[![Run on Apify](https://img.shields.io/badge/Run%20on-Apify-blue)](https://apify.com/scrapmania/todoist-ai-assistant?fpr=ebrunet001)

## Features

- **35 MCP tools** across 6 categories:
  - **Tasks** (9 tools) — create, update, complete, reschedule, search
  - **Projects** (5 tools) — create, list, archive, organize
  - **Sections** (4 tools) — organize tasks within projects
  - **Labels** (4 tools) — tag and filter tasks
  - **Comments** (4 tools) — add context to tasks and projects
  - **AI Features** (9 tools) — smart prioritization, focus mode, daily digest, natural language processing
- **Natural language date parsing** in 4 languages: English, French, Spanish, German
- **Sub-500ms response time** after initial cold start
- **Secure** — your Todoist token is stored encrypted on Apify, never sent to AI models
- Works with **Claude Desktop, Claude Code, ChatGPT** and any MCP-compatible client

## Quick Start

Connect to the MCP server using the Streamable HTTP endpoint:

```
https://scrapmania--todoist-ai-assistant.apify.actor/mcp?token=YOUR_APIFY_TOKEN
```

### Setup (3 minutes)

1. Copy your [Todoist API token](https://todoist.com/app/settings/integrations/developer)
2. Go to the [Todoist MCP Server on Apify](https://apify.com/scrapmania/todoist-ai-assistant?fpr=ebrunet001), paste your token in the Input tab, and click **Save**
3. [Get your Apify API token](https://console.apify.com/account/integrations?fpr=ebrunet001) and add the Standby URL above as a custom MCP connector in your AI client

### Claude Desktop

Go to **Settings → MCP Servers → Add Custom Connector** and paste the URL above.

### Claude Code

Add the server URL to your MCP settings, then run `/permissions` and add `mcp__Todoist__*` to the Allow list.

## Example Prompts

Once connected, your AI assistant can handle prompts like:

- *"Add a task to call the dentist tomorrow at 2pm, high priority"*
- *"What's on my plate today? Prioritize by urgency"*
- *"Move all tasks from 'Inbox' to the 'Work' project"*
- *"Give me a daily digest of what I accomplished this week"*
- *"Ajoute une tâche pour demain matin : préparer la réunion"*
- *"Create a new project 'Q2 Planning' with sections for each team"*

## Security

- Your Todoist token is stored server-side on Apify's encrypted infrastructure
- The token is **never sent to AI models** — only used server-side for Todoist API calls
- The MCP server runs in Apify's secure sandbox with `limitedPermissions` enabled
- Your Apify token in the URL authenticates your MCP connection only

## Pricing

Pay-per-event — you only pay for the tools you actually use. The free tier gives you **$5 free credits every month**, enough for hundreds of tool calls.

## Links

- **Apify Store**: [Todoist MCP Server](https://apify.com/scrapmania/todoist-ai-assistant?fpr=ebrunet001)
- **Author**: [mrbridge on Apify](https://apify.com/mrbridge?fpr=ebrunet001)

## Related MCP Servers

- [ESPN MCP Server](https://apify.com/scrapmania/espn-mcp-server?fpr=ebrunet001) — Live scores, standings, and stats across 25+ sports leagues
- [League of Legends MCP Server](https://apify.com/scrapmania/lol-mcp-server?fpr=ebrunet001) — 13 tools for LoL player data, match history, and AI coaching
- [Teamfight Tactics MCP Server](https://apify.com/scrapmania/teamfight-tactics-mcp-server---ai-game-analysis?fpr=ebrunet001) — 10 tools for TFT compositions, augments, and AI coaching

---

*Built by [mrbridge](https://apify.com/mrbridge?fpr=ebrunet001)*
