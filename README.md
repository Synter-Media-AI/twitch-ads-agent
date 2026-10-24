# Twitch Ads MCP Starter Kit — Manage Twitch Ads with AI

> **This is a recipe repo.** The Synter MCP server itself lives at [Synter-Media-AI/mcp-server](https://github.com/Synter-Media-AI/mcp-server): 19 ad platforms, campaign creation on 14, one-click install in Cursor, Claude, ChatGPT, and VS Code. Issues, releases, and ⭐ go there.

[![MCP Compatible](https://img.shields.io/badge/MCP-compatible-blue)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform: Twitch Ads](https://img.shields.io/badge/Platform-Twitch%20Ads-9146FF)](https://twitchadvertising.tv)

**Reach live gamers on stream and VOD.** Open this repo in Amp, Cursor, or VS Code and manage Twitch Ads with AI — categories, live vs VOD, and gaming creatives — through Synter MCP.

---

## Why Twitch Ads + AI?

Twitch is live gaming culture: categories, streamers, raids, and VODs. Ads compete with that energy. Good campaigns target game categories (not “gamers 18-34” as a blob), respect stream context, and separate live from VOD.

An agent helps you pick categories, draft mid-roll vs overlay briefs, and compare Twitch with Discord Quests for acquisition.

**Best for:** games, gaming hardware, energy/snacks, game-adjacent apps, creator tools, live events.

---

## Gaming ad platforms compared

| Network | Format | Session | Best for |
|--------|--------|---------|----------|
| **Twitch Ads** | In-stream, overlay, VOD | Live watch + VOD | Reach during play/watch |
| **Discord Quests** | Branded quests / tasks | In-community completion | Play, install, or watch-to-earn style acquisition |

Companion: [discord-quests-agent](https://github.com/Synter-Media-AI/discord-quests-agent).

---

## Quick Start (30 Seconds)

### Amp / Cursor / VS Code (Copilot)

1. **Get a free API key** at [syntermedia.ai/developer](https://syntermedia.ai/developer)
2. **Set the key:**
   ```bash
   export SYNTER_API_KEY=syn_your_key_here
   ```
3. **Open this repo** in your editor
4. **Start chatting** — MCP tools are pre-configured in `.mcp.json`

### Claude Desktop

Copy `claude_desktop_config.json` to your Claude config directory and replace the API key:

- **macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows:** `%APPDATA%\\Claude\\claude_desktop_config.json`

---

## What You Can Do

| Capability | Example |
|-----------|---------|
| **Category targeting** | "Target Just Chatting, Valorant, and indie game categories" |
| **Live vs VOD** | "Split budget 70% live, 30% VOD for our new title" |
| **Creative briefs** | "Write a 15s mid-roll that does not kill raid energy" |
| **Compare** | "Twitch Ads vs Discord Quests for a Steam wishlist campaign" |
| **Performance** | "Pull Twitch Ads completion rate, CTR, and install assists" |
| **Delivery QA** | "Validate my Twitch campaign structure for delivery issues" |

Hosted **Synter MCP** (`@synterai/mcp-server` / https://mcp.syntermedia.ai). Connect at [syntermedia.ai/credentials](https://syntermedia.ai/credentials). Not a first-party Twitch Ads API client.

---

## Example Conversations

### 1. Launch week live

> **You:** Steam page goes live Friday. I want Twitch live inventory in our genre.
>
> **Agent:** I will map genre categories, avoid leftover placements from unrelated sports streams, and brief a 6s + 15s pair. Connect Twitch in Synter and I will create the campaign via MCP.

### 2. Twitch vs Discord Quests

> **You:** Should we run Quests instead of Twitch ads?
>
> **Agent:** Different jobs. Twitch buys attention in the stream. Discord Quests buy completed actions in a server. Run Twitch for awareness, Quests for play/install. I can open both recipe kits.

---

## FAQ

### Is there an MCP for Twitch Ads?
Yes — this recipe pre-configures Synter MCP for Twitch Ads in Amp, Cursor, VS Code, and Claude Desktop.

### Can I buy specific streamers here?
Use Synter to plan category and campaign structure. Talent/influencer deals stay in your creator workflow.

---

## Related Repos

- [carbon-ads-agent](https://github.com/Synter-Media-AI/carbon-ads-agent) — Carbon Ads / developer blog inventory
- [ethical-ads-agent](https://github.com/Synter-Media-AI/ethical-ads-agent) — EthicalAds privacy-first OSS inventory
- [brave-ads-agent](https://github.com/Synter-Media-AI/brave-ads-agent) — Brave Ads, search, and new-tab
- [twitch-ads-agent](https://github.com/Synter-Media-AI/twitch-ads-agent) — Twitch Ads for live gaming
- [discord-quests-agent](https://github.com/Synter-Media-AI/discord-quests-agent) — Discord Quests gamer acquisition
- [reddit-ads-agent](https://github.com/Synter-Media-AI/reddit-ads-agent) — Reddit community ads
- [google-ads-agent](https://github.com/Synter-Media-AI/google-ads-agent) — Search intent capture
- [meta-ads-agent](https://github.com/Synter-Media-AI/meta-ads-agent) — Facebook & Instagram reach
- [cross-platform-ads-agent](https://github.com/Synter-Media-AI/cross-platform-ads-agent) — Multi-channel management

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Synter](https://syntermedia.ai) · [Get API Key](https://syntermedia.ai/developer) · [Documentation](https://syntermedia.ai/docs)
