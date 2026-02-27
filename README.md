# Xquik Skill

An [AI agent skill](https://skills.sh) for building integrations with the [Xquik](https://xquik.com) X (Twitter) real-time data platform.

Works with **40+ AI coding agents** including Claude Code, OpenAI Codex, Cursor, GitHub Copilot, Gemini CLI, Windsurf, VS Code, Cline, Roo Code, Goose, Amp, Augment, Continue, OpenHands, Trae, OpenCode, and more.

## Installation

Install via the [skills CLI](https://skills.sh) (auto-detects your installed agents):

```bash
npx skills add Xquik-dev/x-twitter-scraper
```

### Manual Installation

<details>
<summary>Claude Code</summary>

```bash
git clone https://github.com/Xquik-dev/x-twitter-scraper.git .claude/skills/x-twitter-scraper
```
</details>

<details>
<summary>Codex / Cursor / Gemini CLI / GitHub Copilot</summary>

```bash
git clone https://github.com/Xquik-dev/x-twitter-scraper.git .agents/skills/x-twitter-scraper
```
</details>

<details>
<summary>Windsurf</summary>

```bash
git clone https://github.com/Xquik-dev/x-twitter-scraper.git .windsurf/skills/x-twitter-scraper
```
</details>

<details>
<summary>Cline</summary>

```bash
git clone https://github.com/Xquik-dev/x-twitter-scraper.git .agents/skills/x-twitter-scraper
```
</details>

<details>
<summary>Roo Code</summary>

```bash
git clone https://github.com/Xquik-dev/x-twitter-scraper.git .roo/skills/x-twitter-scraper
```
</details>

<details>
<summary>Continue</summary>

```bash
git clone https://github.com/Xquik-dev/x-twitter-scraper.git .continue/skills/x-twitter-scraper
```
</details>

<details>
<summary>Goose</summary>

```bash
git clone https://github.com/Xquik-dev/x-twitter-scraper.git .goose/skills/x-twitter-scraper
```
</details>

<details>
<summary>OpenCode</summary>

```bash
git clone https://github.com/Xquik-dev/x-twitter-scraper.git .agents/skills/x-twitter-scraper
```
</details>

## What This Skill Does

When installed, this skill gives your AI agent deep knowledge of the Xquik platform:

- **Write API integrations** using the Xquik REST API (monitors, events, webhooks, draws, extractions, lookups, trends)
- **Set up webhook handlers** with proper HMAC-SHA256 signature verification
- **Configure MCP connections** for 8 IDEs and AI agent platforms
- **Choose the right endpoint** for any X data task (search vs. lookup vs. extraction)
- **Handle errors and pagination** following Xquik conventions
- **Use all 19 extraction tools** with correct parameters
- **Run giveaway draws** with configurable filters

## Skill Structure

```
x-twitter-scraper/
├── SKILL.md                      # Main skill (auth, endpoints, patterns)
└── references/
    ├── api-endpoints.md          # All REST API endpoints
    ├── webhooks.md               # Webhook setup & verification
    ├── mcp-setup.md              # MCP configs for 8 platforms
    ├── extractions.md            # 19 extraction tool types
    └── types.md                  # TypeScript type definitions
```

## Coverage

| Area | Details |
|------|---------|
| REST API | All endpoints across 9 resource groups |
| Webhooks | HMAC verification in Node.js, Python, Go |
| MCP Server | Claude Desktop, Claude Code, ChatGPT, Codex CLI, Cursor, VS Code, Windsurf, OpenCode |
| Extractions | All 19 tool types with parameters |
| Draws | Full giveaway draw API with filters |
| Types | Complete TypeScript definitions |

## Links

- [Xquik Platform](https://xquik.com)
- [API Documentation](https://docs.xquik.com)
- [API Reference](https://docs.xquik.com/api-reference/overview)
- [MCP Server Guide](https://docs.xquik.com/mcp/overview)

## License

MIT
