# Hi, I'm JJ 🦊

📍 **Peru ↔ New Jersey** · 🧱 **Compounding, harness‑agnostic tooling for AI‑native devs**

The agent layer is commoditized, Claude, Codex, Cursor, and Gemini are racing each other. My time goes into the layer *above*: tooling and institutional knowledge that compound across model swaps, the kind you don't have to rebuild when you switch harnesses.

> *["Stop building another Claude. Build the harness around the one you already have."](https://juanjofuchs.github.io/ai-development/2026/03/31/stop-building-another-claude-learn-how-to-effectively-onboard-one-into-your-organization-instead.html)*

---

## 🛠️ What I'm building

<table>
<tr>
<td width="50%" valign="top">

**🔥 [ccburn](https://github.com/JuanjoFuchs/ccburn)** · ⭐ 89

<a href="https://github.com/JuanjoFuchs/ccburn"><img src="https://raw.githubusercontent.com/JuanjoFuchs/ccburn/main/docs/ccburn_070.png" alt="ccburn screenshot" width="100%"></a>

Real‑time burn‑up charts for Claude Code usage limits. Visual clarity for token burn, track usage against a budget pace line, instantly know if you're ahead or behind. Pace indicators (🧊/🔥/🚨), compact mode for status bars, JSON for automation.

```bash
npx ccburn
```

</td>
<td width="50%" valign="top">

**🖥️ [hwinfo-tui](https://github.com/JuanjoFuchs/hwinfo-tui)** · ⭐ 58

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

**⏰ [tempo-filler-mcp-server](https://github.com/TRANZACT/tempo-filler-mcp-server)** · ⭐ 5

<a href="https://github.com/TRANZACT/tempo-filler-mcp-server"><img src="https://raw.githubusercontent.com/TRANZACT/tempo-filler-mcp-server/main/docs/demo_get_worklogs.png" alt="Tempo Filler timesheet" width="100%"></a>

Tell Claude *"fill my October hours"* and the MCP server bulk‑creates the worklogs once you approve. Uses MCP Apps to render visual timesheet and calendar UIs inside Claude Desktop and VS Code.

```bash
npx @tranzact/tempo-filler-mcp-server
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

&nbsp;

</td>
</tr>
</table>

---

## ✍️ Latest from the blog

<!-- BLOG-POST-LIST:START -->
- [Launching atref: Don’t Install Skills, Mention Your Second-Brain Guides Into Any Agent](https://juanjofuchs.github.io/ai-development/2026/06/09/launching-atref-dont-install-skills-mention-your-second-brain-guides-into-any-agent.html)
- [Claude Just Gave You a Dry Promotion, and Will Keep Promoting You Until…](https://juanjofuchs.github.io/ai-development/2026/06/02/claude-just-gave-you-a-dry-promotion-and-will-keep-promoting-you-until.html)
- [14 Habits for Using Claude Code Without Wasting Tokens](https://juanjofuchs.github.io/ai-development/2026/05/26/14-habits-for-using-claude-code-without-wasting-tokens.html)
- [Who Builds the Next Senior Engineer When AI Removes the Junior Work?](https://juanjofuchs.github.io/ai-development/2026/05/19/who-builds-the-next-senior-engineer-when-ai-removes-the-junior-work.html)
- [Why I Built Yet Another Agent Mail Tool](https://juanjofuchs.github.io/ai/2026/05/12/why-i-built-yet-another-agent-mail-tool.html)
<!-- BLOG-POST-LIST:END -->

More at [juanjofuchs.github.io](https://juanjofuchs.github.io/), writing about AI‑native development, second‑brain workflows, and the tools above.

## 🤝 Connect

[![Blog](https://img.shields.io/badge/Blog-juanjofuchs.github.io-FF5722?style=flat-square&logo=jekyll&logoColor=white)](https://juanjofuchs.github.io/)
[![X](https://img.shields.io/badge/X-@JuanjoFuchs-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/JuanjoFuchs)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Juan_Jos%C3%A9_Fuchs-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanjofuchs)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JuanjoFuchs)
