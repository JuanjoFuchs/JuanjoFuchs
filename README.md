# Hi, I'm JJ 🦊

📍 **Peru ↔ New Jersey** · 🧱 **Compounding, harness‑agnostic tooling for AI‑native devs**

The agent layer is commoditized, Claude, Codex, Cursor, and Gemini are racing each other. My time goes into the layer *above*: tooling and institutional knowledge that compound across model swaps, the kind you don't have to rebuild when you switch harnesses.

> *["Stop building another Claude. Build the harness around the one you already have."](https://juanjofuchs.github.io/ai-development/2026/03/31/stop-building-another-claude-learn-how-to-effectively-onboard-one-into-your-organization-instead.html)*

---

## 🛠️ What I'm building

<table>
<tr>
<td colspan="2" valign="top">

**🎙️ [voice-tunnel](https://github.com/JuanjoFuchs/voice-tunnel)**

<a href="https://github.com/JuanjoFuchs/voice-tunnel"><img src="https://raw.githubusercontent.com/JuanjoFuchs/voice-tunnel/main/docs/demo.gif" alt="Shipping a release by voice from a phone" align="left" width="200"></a>

Talk to your coding agent from your phone. One command opens a page any phone browser can load, no app and no App Store, and carries audio both ways. **If your agent can run bash, it can talk to you.** Claude Code, Codex and Grok each drive it unchanged, because the tool holds no model and makes no decisions, the agent that started it does the thinking.

Speech recognition (Parakeet TDT) and synthesis (Piper) both run on your CPU. No GPU, no speech API, no account, and nothing you say leaves the machine. Turns end when you *sound* finished rather than when a timer expires, and only your own voiceprint can interrupt a reply, so the room and the agent's own speech cannot.

Onboarding an agent is one call: `voice-tunnel describe` returns the whole contract as JSON, no MCP server and no docs to keep in sync. [Read the write‑up](https://juanjofuchs.github.io/ai/2026/08/11/launching-voice-tunnel-talk-to-your-coding-agent-from-your-phone.html).

```bash
npm install -g @juanjofuchs/voice-tunnel
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🔥 [ccburn](https://github.com/JuanjoFuchs/ccburn)** · ⭐ 90

<a href="https://github.com/JuanjoFuchs/ccburn"><img src="https://raw.githubusercontent.com/JuanjoFuchs/ccburn/main/docs/ccburn_070.png" alt="ccburn screenshot" width="100%"></a>

Real‑time burn‑up charts for Claude Code usage limits. Visual clarity for token burn, track usage against a budget pace line, instantly know if you're ahead or behind. Pace indicators (🧊/🔥/🚨), compact mode for status bars, JSON for automation.

```bash
npx ccburn
```

</td>
<td width="50%" valign="top">

**🖥️ [hwinfo-tui](https://github.com/JuanjoFuchs/hwinfo-tui)** · ⭐ 60

<a href="https://github.com/JuanjoFuchs/hwinfo-tui"><img src="https://raw.githubusercontent.com/JuanjoFuchs/hwinfo-tui/main/docs/demo.gif" alt="hwinfo-tui demo" width="100%"></a>

A TUI for plotting HWInfo64 sensors. HWInfo shows your CPU at 75°C right now but can't tell you if it just spiked or has been climbing for 10 minutes. This plots the values live to visually understand your sensors.

```bash
uvx hwinfo-tui
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📘 [claude-code-tips](https://github.com/JuanjoFuchs/claude-code-tips)**

<a href="https://github.com/JuanjoFuchs/claude-code-tips"><img src="https://raw.githubusercontent.com/JuanjoFuchs/claude-code-tips/main/assets/claude-code-tips-site.png" alt="Claude Code Engineering Tips" width="100%"></a>

14 habits to ship better code with less spend on Claude Code. Every tip cites Anthropic docs, something Boris Cherny said publicly, or a published field heuristic. The HTML site is for humans, the Markdown is for Claude — point it at the repo and it pulls what it needs.

> <a href="https://juanjofuchs.github.io/claude-code-tips/" target="_blank" rel="noopener">juanjofuchs.github.io/claude-code-tips</a>

</td>
<td width="50%" valign="top">

**🔖 [atref](https://github.com/JuanjoFuchs/atref)**

<a href="https://github.com/JuanjoFuchs/atref"><img src="https://raw.githubusercontent.com/JuanjoFuchs/atref/main/docs/demo.gif" alt="atref demo: summon the picker and insert a file reference at the caret" width="100%"></a>

Claude Code's `@` file picker — everywhere. Press a global chord in any text field (terminal, browser, Obsidian, IDE) and a fuzzy picker inserts an `@"<path>"` reference from your indexed folders. Git‑aware index, frecency, live file‑watcher, native acrylic UI. A Rust tray app that doubles as an agent‑drivable config CLI.

```powershell
winget install JuanjoFuchs.atref
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📊 [claudefana](https://github.com/JuanjoFuchs/claudefana)** · ⭐ 1

<a href="https://github.com/JuanjoFuchs/claudefana"><img src="https://raw.githubusercontent.com/JuanjoFuchs/claudefana/main/docs/screenshot.png" alt="claudefana dashboard" width="100%"></a>

Claude Code exports detailed OpenTelemetry data, cost per request, token breakdowns, tool calls, cache hits, edit decisions. All of it vanishes unless you wire up a backend. claudefana is that backend. 1 dashboard, 26 panels across 8 sections, cost per commit, cache hit ratio, lines per dollar, etc.

```bash
docker compose -f docker-compose.otel.yaml up -d
```

</td>
<td width="50%" valign="top">

**🏢 [claudefana-enterprise](https://github.com/JuanjoFuchs/claudefana-enterprise)**

<a href="https://github.com/JuanjoFuchs/claudefana-enterprise"><img src="https://raw.githubusercontent.com/JuanjoFuchs/claudefana-enterprise/main/docs/screenshot.png" alt="claudefana enterprise" width="100%"></a>

You deployed Claude Code to your engineering org, now you need to know if it's being adopted. Anthropic published a guide with 5 ROI questions, I built the dashboards that answer them. Two custom exporters pull org structure from Microsoft Graph and work data from Jira/Tempo. Three dashboards, 80+ panels.

```bash
docker compose -f docker-compose.enterprise.yaml up -d
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📬 [agent-mail-cli](https://github.com/JuanjoFuchs/agent-mail-cli)**

<a href="https://github.com/JuanjoFuchs/agent-mail-cli"><img src="https://raw.githubusercontent.com/JuanjoFuchs/agent-mail-cli/main/docs/agent-mail-hero.gif" alt="agent-mail-cli demo" width="100%"></a>

A CLI for coding agents to send mail to each other. One command for agents to learn it, no daemon, no MCP server, no harness setup. `send`, `read`, `ack`, `status`, that's the whole surface.

```bash
npx @juanjofuchs/agent-mail describe
```

</td>
<td width="50%" valign="top">

**⏰ [tempo-filler-mcp-server](https://github.com/TRANZACT/tempo-filler-mcp-server)** · ⭐ 5

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
- [Building Your Second Brain, Part 6: Git as Durable Memory](https://juanjofuchs.github.io/productivity/2026/08/04/building-your-second-brain-part-6-git-as-durable-memory.html)
- [GitHub Stars Are Not Evals](https://juanjofuchs.github.io/ai-development/2026/07/28/github-stars-are-not-evals.html)
- [The Vibe Coder Liberty Paradox: Who Maintains What AI Lets Anyone Ship?](https://juanjofuchs.github.io/ai-development/2026/07/21/the-vibe-coder-liberty-paradox-who-maintains-what-ai-lets-anyone-ship.html)
- [Building Your Second Brain, Part 5: The Capture Loop](https://juanjofuchs.github.io/productivity/2026/07/14/building-your-second-brain-part-5-the-capture-loop.html)
- [Taste Debt](https://juanjofuchs.github.io/ai-development/2026/07/07/taste-debt.html)
<!-- BLOG-POST-LIST:END -->

More at [juanjofuchs.github.io](https://juanjofuchs.github.io/), writing about AI‑native development, second‑brain workflows, and the tools above.

## 🤝 Connect

[![Blog](https://img.shields.io/badge/Blog-juanjofuchs.github.io-FF5722?style=flat-square&logo=jekyll&logoColor=white)](https://juanjofuchs.github.io/)
[![X](https://img.shields.io/badge/X-@JuanjoFuchs-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/JuanjoFuchs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Juan_Jos%C3%A9_Fuchs-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanjofuchs)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JuanjoFuchs)
