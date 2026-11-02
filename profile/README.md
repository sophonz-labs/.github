<p align="center">
  <img src="observability.png" width="96" alt="sophonz observability" />&nbsp;&nbsp;
  <img src="terminal.png" width="96" alt="sophonz terminal" />
</p>

<h1 align="center">sophonz labs</h1>

<p align="center">Observability for mobile and web apps, and a terminal you can reach from anywhere.</p>

## What we build

<img src="observability.png" width="20" align="top" /> **sophonz observability** — an OpenTelemetry-based RUM/APM platform at [sophonz.com](https://sophonz.com).
Sessions, traces, logs and crashes from Android, iOS, web, React Native, Flutter and Python, stored in ClickHouse. The collector is a fork of
[opentelemetry-collector-contrib](https://github.com/sophonz-labs/opentelemetry-collector-contrib).

<img src="terminal.png" width="20" align="top" /> **sophonz terminal (`st`)** — your tmux sessions in a browser, a phone or a desktop app, over a control plane at
[link.sophonz.io](https://link.sophonz.io). A single Go binary, with native iOS and Android apps and a Rust/GPUI
desktop app. Install from [dl.sophonz.io](https://dl.sophonz.io) or the [Homebrew tap](https://github.com/sophonz-labs/homebrew-tap).

## Open source

| Repository | What it is |
|---|---|
| [stui](https://github.com/sophonz-labs/stui) | Terminal UI for tmux and the coding agents in it: agent state, orchestration and GitHub Actions |
| [tmui](https://github.com/sophonz-labs/tmui) | Terminal UI for tmux sessions, windows and panes |
| [tui-plugins](https://github.com/sophonz-labs/tui-plugins) | Plugins for tmui and stui: a CLI's output as a view, its commands on keys |
| [psmux](https://github.com/sophonz-labs/psmux) | tmux for Windows, in Rust: PowerShell, Windows Terminal, cmd.exe |
| [skills](https://github.com/sophonz-labs/skills) | Orchestration skills for Claude Code and Codex: one agent coordinates others in tmux through st |
| [homebrew-tap](https://github.com/sophonz-labs/homebrew-tap) | Homebrew formulae for sophonz tools |
| [opentelemetry-collector-contrib](https://github.com/sophonz-labs/opentelemetry-collector-contrib) | Our collector fork with the sophonz exporters and processors |
