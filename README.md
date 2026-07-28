#  MCP Hub

<div align="center">

**The community driven discovery platform for Model Context Protocol servers.**

[![Live Site](https://img.shields.io/badge/Live%20Site-chuka--okafor.github.io/mcp--hub-FF4628?style=flat&logoColor=white)](https://chuka-okafor.github.io/mcp-hub)
[![Servers Indexed](https://img.shields.io/badge/Servers%20Indexed-25-B8C8D7?style=flat)](https://chuka-okafor.github.io/mcp-hub)
[![Built With](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-B8C8D7?style=flat)](https://github.com/Chuka-Okafor/mcp-hub)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-222?style=flat&logo=github)](https://chuka-okafor.github.io/mcp-hub)

[**→ Visit MCP Hub**](https://chuka-okafor.github.io/mcp-hub) · [Submit a Server](https://github.com/Chuka-Okafor/mcp-hub/issues/new) · [Report a Bug](https://github.com/Chuka-Okafor/mcp-hub/issues)

</div>

---

## What is this?

MCP (Model Context Protocol) is an open standard that lets Claude and other AI models connect to external tools. GitHub, databases, web search, Slack, file systems, and more. But finding the right MCP server for your use case is messy and scattered.

**MCP Hub** fixes that. It's a clean, searchable directory of MCP servers organized by category, with one click install commands and an AI powered recommendation engine.

---

## Features

-  **Live search** — filter 25+ servers instantly by name or description, no page reload
-  **Category filters** — Developer Tools, Web & Search, Databases, Productivity, AI & Research, Commerce
-  **Smart recommendation** — describe what you want to build, get matched to the right server
-  **One-click install** — copy the `npx` install command directly to your clipboard
-  **Community-maintained** — submit new servers via GitHub Issues
-  **Zero dependencies** — pure HTML, CSS, and JavaScript. No build step, no npm, no frameworks

---

## Servers Indexed

###  Developer Tools
| Server | Badge | Install |
|--------|-------|---------|
| GitHub | Official | `npx @modelcontextprotocol/server-github` |
| Filesystem | Official | `npx @modelcontextprotocol/server-filesystem` |
| Git | Official | `npx @modelcontextprotocol/server-git` |
| Sentry | Official | `npx @modelcontextprotocol/server-sentry` |
| Docker | Community | `npx mcp-server-docker` |
| Kubernetes | Community | `npx mcp-server-kubernetes` |

###  Web & Search
| Server | Badge | Install |
|--------|-------|---------|
| Brave Search | Official | `npx @modelcontextprotocol/server-brave-search` |
| Fetch | Official | `npx @modelcontextprotocol/server-fetch` |
| Puppeteer | Official | `npx @modelcontextprotocol/server-puppeteer` |
| Google Maps | Official | `npx @modelcontextprotocol/server-google-maps` |

###  Databases
| Server | Badge | Install |
|--------|-------|---------|
| PostgreSQL | Official | `npx @modelcontextprotocol/server-postgres` |
| SQLite | Official | `npx @modelcontextprotocol/server-sqlite` |
| MongoDB | Community | `npx mcp-server-mongodb` |
| Redis | Community | `npx mcp-server-redis` |
| Airtable | Community | `npx airtable-mcp-server` |

###  Productivity
| Server | Badge | Install |
|--------|-------|---------|
| Slack | Official | `npx @modelcontextprotocol/server-slack` |
| Google Drive | Official | `npx @modelcontextprotocol/server-gdrive` |
| Notion | Community | `npx @notionhq/notion-mcp-server` |
| Linear | Community | `npx mcp-linear` |
| Obsidian | Community | `npx mcp-obsidian` |

###  AI & Research
| Server | Badge | Install |
|--------|-------|---------|
| Memory | Official | `npx @modelcontextprotocol/server-memory` |
| Arxiv | Community | `npx arxiv-mcp-server` |
| EverArt | Official | `npx @modelcontextprotocol/server-everart` |
| AWS KB Retrieval | Official | `npx @modelcontextprotocol/server-aws-kb-retrieval` |

###  Commerce
| Server | Badge | Install |
|--------|-------|---------|
| Stripe | Popular | `npx @stripe/agent-toolkit` |

---

## Run Locally

```bash
# Clone the repo
git clone https://github.com/Chuka-Okafor/mcp-hub.git
cd mcp-hub

# Open in browser — that's it
open index.html
```

No build step. No npm install. No configuration. Just open the file.

---

## Submit a Server

Know an MCP server that isn't listed? Open an issue with this template:

```
**Server Name:**
**Description:**
**Category:** Developer / Web / Database / Productivity / AI / Commerce
**Install Command:** npx ...
**GitHub / Docs Link:**
**Badge:** Official / Community / Popular
```

→ [Open an Issue](https://github.com/Chuka-Okafor/mcp-hub/issues/new)

---

## Roadmap

- [ ] Add 50+ more MCP servers
- [ ] Search by install method (npx, pip, docker)
- [ ] "New this week" section with auto updates
-  *  Dark/light mode toggle
- [ ] Hausa and Swahili UI translations
- [ ] JSON API endpoint for programmatic access
- [ ] Server uptime/status indicators

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Icons | Simple Icons CDN |
| Fonts | Space Grotesk + Space Mono (Google Fonts) |
| Hosting | GitHub Pages |

---

## Built by

**Chuka Okafor** — CS Student, Imo State University, Nigeria 🇳🇬

Interested in AI Security, adversarial ML, and building tools that serve African developers and communities. Check out my other projects:

-  [African Language AI Safety Probe](https://github.com/Chuka-Okafor/African-language-safety-probe) — Research tool testing LLM safety filter parity across Yoruba, Igbo, and Nigerian Pidgin
-  [Robot Garden Simulation](https://github.com/Chuka-Okafor/Robot-garden-simulation) — Autonomous robot navigation with BFS pathfinding and adaptive control

---

*Data is community maintained.*
