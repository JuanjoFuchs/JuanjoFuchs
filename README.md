# Hi, I'm JJ 🦊

📍 **Peru ↔ New Jersey** · 🧱 **Compounding, harness‑agnostic tooling for AI‑native devs**

The agent layer is commoditized, Claude, Codex, Cursor, and Gemini are racing each other. My time goes into the layer *above*: tooling and institutional knowledge that compound across model swaps, the kind you don't have to rebuild when you switch harnesses.

> *["Stop building another Claude. Build the harness around the one you already have."](https://juanjofuchs.com/ai-development/2026/03/31/stop-building-another-claude-learn-how-to-effectively-onboard-one-into-your-organization-instead.html)*

---

## 🛠️ What I'm building

<table>
<tr>
<td width="50%" valign="top">

**🛰️ [command-bridge](https://github.com/JuanjoFuchs/command-bridge)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/command-bridge?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/command-bridge/stargazers)

<a href="https://github.com/JuanjoFuchs/command-bridge"><img src="https://raw.githubusercontent.com/JuanjoFuchs/command-bridge/main/docs/demo.gif" alt="Command Bridge demo: an agent explains its watch logic, pointing at each box of the diagram it drew on the shared canvas" width="100%"></a>

Meet a room of your coding agents by voice and watch them show you the work. Command Bridge is voice-tunnel grown up: the same local, self-describing CLI, now with a shared canvas the agents draw and point at while they explain, and a lane for each agent like participants on a call. Speech in and out on your own machine, no app, no account, no model in the tool. One `command-bridge describe` and your agent drives voice and canvas both.

```bash
curl -fsSL https://raw.githubusercontent.com/\
JuanjoFuchs/command-bridge/main/install.sh | bash
```

</td>
<td width="50%" valign="top">

**🎙️ [voice-tunnel](https://github.com/JuanjoFuchs/voice-tunnel)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/voice-tunnel?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/voice-tunnel/stargazers)

<a href="https://github.com/JuanjoFuchs/voice-tunnel"><img src="https://raw.githubusercontent.com/JuanjoFuchs/voice-tunnel/main/docs/demo.gif" alt="Shipping a release by voice from a phone" width="100%"></a>

Talk to your coding agent from your phone. One command opens a page any phone browser can load, no app and no App Store, and carries audio both ways. If your agent can run bash it can talk to you, and Claude Code, Codex and Grok drive it unchanged. Speech runs on your own CPU and nothing you say leaves the machine. Now frozen as a finished release; its shared-canvas successor is [command-bridge](https://github.com/JuanjoFuchs/command-bridge), to the left.

```bash
npm install -g @juanjofuchs/voice-tunnel
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔥 [ccburn](https://github.com/JuanjoFuchs/ccburn)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/ccburn?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/ccburn/stargazers)

<a href="https://github.com/JuanjoFuchs/ccburn"><img src="https://raw.githubusercontent.com/JuanjoFuchs/ccburn/main/docs/ccburn_070.png" alt="ccburn screenshot" width="100%"></a>

Real‑time burn‑up charts for Claude Code usage limits. Visual clarity for token burn, track usage against a budget pace line, instantly know if you're ahead or behind. Pace indicators (🧊/🔥/🚨), compact mode for status bars, JSON for automation.

```bash
npx ccburn
```

</td>
<td width="50%" valign="top">

**🖥️ [hwinfo-tui](https://github.com/JuanjoFuchs/hwinfo-tui)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/hwinfo-tui?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/hwinfo-tui/stargazers)

<a href="https://github.com/JuanjoFuchs/hwinfo-tui"><img src="https://raw.githubusercontent.com/JuanjoFuchs/hwinfo-tui/main/docs/demo.gif" alt="hwinfo-tui demo" width="100%"></a>

A TUI for plotting HWInfo64 sensors. HWInfo shows your CPU at 75°C right now but can't tell you if it just spiked or has been climbing for 10 minutes. This plots the values live to visually understand your sensors.

```bash
uvx hwinfo-tui
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📘 [claude-code-tips](https://github.com/JuanjoFuchs/claude-code-tips)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/claude-code-tips?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/claude-code-tips/stargazers)

<a href="https://github.com/JuanjoFuchs/claude-code-tips"><img src="https://raw.githubusercontent.com/JuanjoFuchs/claude-code-tips/main/assets/claude-code-tips-site.png" alt="Claude Code Engineering Tips" width="100%"></a>

14 habits to ship better code with less spend on Claude Code. Every tip cites Anthropic docs, something Boris Cherny said publicly, or a published field heuristic. The HTML site is for humans, the Markdown is for Claude — point it at the repo and it pulls what it needs.

> <a href="https://juanjofuchs.com/claude-code-tips/" target="_blank" rel="noopener">juanjofuchs.com/claude-code-tips</a>

</td>
<td width="50%" valign="top">

**🔖 [atref](https://github.com/JuanjoFuchs/atref)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/atref?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/atref/stargazers)

<a href="https://github.com/JuanjoFuchs/atref"><img src="https://raw.githubusercontent.com/JuanjoFuchs/atref/main/docs/demo.gif" alt="atref demo: summon the picker and insert a file reference at the caret" width="100%"></a>

Claude Code's `@` file picker — everywhere. Press a global chord in any text field (terminal, browser, Obsidian, IDE) and a fuzzy picker inserts an `@"<path>"` reference from your indexed folders. Git‑aware index, frecency, live file‑watcher, native acrylic UI. A Rust tray app that doubles as an agent‑drivable config CLI.

```powershell
winget install JuanjoFuchs.atref
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📊 [claudefana](https://github.com/JuanjoFuchs/claudefana)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/claudefana?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/claudefana/stargazers)

<a href="https://github.com/JuanjoFuchs/claudefana"><img src="https://raw.githubusercontent.com/JuanjoFuchs/claudefana/main/docs/screenshot.png" alt="claudefana dashboard" width="100%"></a>

Claude Code exports detailed OpenTelemetry data, cost per request, token breakdowns, tool calls, cache hits, edit decisions. All of it vanishes unless you wire up a backend. claudefana is that backend. 1 dashboard, 26 panels across 8 sections, cost per commit, cache hit ratio, lines per dollar, etc.

```bash
docker compose -f docker-compose.otel.yaml up -d
```

</td>
<td width="50%" valign="top">

**🏢 [claudefana-enterprise](https://github.com/JuanjoFuchs/claudefana-enterprise)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/claudefana-enterprise?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/claudefana-enterprise/stargazers)

<a href="https://github.com/JuanjoFuchs/claudefana-enterprise"><img src="https://raw.githubusercontent.com/JuanjoFuchs/claudefana-enterprise/main/docs/screenshot.png" alt="claudefana enterprise" width="100%"></a>

You deployed Claude Code to your engineering org, now you need to know if it's being adopted. Anthropic published a guide with 5 ROI questions, I built the dashboards that answer them. Two custom exporters pull org structure from Microsoft Graph and work data from Jira/Tempo. Three dashboards, 80+ panels.

```bash
docker compose -f docker-compose.enterprise.yaml up -d
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📬 [agent-mail-cli](https://github.com/JuanjoFuchs/agent-mail-cli)** · [![⭐](https://img.shields.io/github/stars/JuanjoFuchs/agent-mail-cli?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/JuanjoFuchs/agent-mail-cli/stargazers)

<a href="https://github.com/JuanjoFuchs/agent-mail-cli"><img src="https://raw.githubusercontent.com/JuanjoFuchs/agent-mail-cli/main/docs/agent-mail-hero.gif" alt="agent-mail-cli demo" width="100%"></a>

A CLI for coding agents to send mail to each other. One command for agents to learn it, no daemon, no MCP server, no harness setup. `send`, `read`, `ack`, `status`, that's the whole surface.

```bash
npx @juanjofuchs/agent-mail describe
```

</td>
<td width="50%" valign="top">

**⏰ [tempo-filler-mcp-server](https://github.com/TRANZACT/tempo-filler-mcp-server)** · [![⭐](https://img.shields.io/github/stars/TRANZACT/tempo-filler-mcp-server?style=flat-square&label=%E2%AD%90&labelColor=21262d&color=30363d)](https://github.com/TRANZACT/tempo-filler-mcp-server/stargazers)

<a href="https://github.com/TRANZACT/tempo-filler-mcp-server"><img src="https://raw.githubusercontent.com/TRANZACT/tempo-filler-mcp-server/main/docs/demo_get_worklogs.png" alt="Tempo Filler timesheet" width="100%"></a>

Tell Claude *"fill my October hours"* and the MCP server bulk‑creates the worklogs once you approve. Uses MCP Apps to render visual timesheet and calendar UIs inside Claude Desktop and VS Code.

```bash
npx @tranzact/tempo-filler-mcp-server
```

</td>
</tr>
</table>

---

## ✍️ Latest from the blog

<!-- BLOG-POST-LIST:START -->
- [Deixis: the agent points](https://juanjofuchs.com/blog/deixis)
- [What We Should Protect If AI Is the Next Great Filter](https://juanjofuchs.com/blog/optimistic-nihilism)
- [Bandwidth: Intent and Understanding Per Minute](https://juanjofuchs.com/blog/intent-per-minute)
- [Proof of Effort](https://juanjofuchs.com/blog/proof-of-effort)
- [Launching voice-tunnel: Talk to Your Coding Agent From Your Phone](https://juanjofuchs.com/ai/2026/08/11/launching-voice-tunnel-talk-to-your-coding-agent-from-your-phone.html)
<!-- BLOG-POST-LIST:END -->

More at [juanjofuchs.com](https://juanjofuchs.com/), writing about AI‑native development, second‑brain workflows, and the tools above.

## 🤝 Connect

[![Blog](https://img.shields.io/badge/Blog-juanjofuchs.com-FF5722?style=flat-square&logo=jekyll&logoColor=white)](https://juanjofuchs.com/)
[![X](https://img.shields.io/badge/X-@JuanjoFuchs-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/JuanjoFuchs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Juan_Jos%C3%A9_Fuchs-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanjofuchs)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JuanjoFuchs)
