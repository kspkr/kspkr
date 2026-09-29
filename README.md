<!-- ───────────────────────────────────────────────────────────────
     kspkr · GitHub profile README
     Lives in the repo  github.com/kspkr/kspkr  (file: README.md)
     ─────────────────────────────────────────────────────────────── -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f1115,50:1f2530,100:e5a445&text=kspkr&fontColor=ffffff&fontSize=64&fontAlignY=38&desc=Developer%20tools%20that%20stay%20on%20your%20machine.&descAlignY=60&descSize=18&animation=fadeIn" width="100%" alt="kspkr" />

<a href="https://github.com/kspkr">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=E5A445&center=true&vCenter=true&width=640&height=48&lines=No+account.+No+cloud.+No+telemetry.;Go+engines+%C2%B7+React+interfaces+%C2%B7+Rust+shells;Free+forever%2C+MIT+licensed%2C+self-hosted;Open+source+tools+for+people+who+read+the+source" alt="No account. No cloud. No telemetry." />
</a>

<br />

[![TrafficKit](https://img.shields.io/badge/TrafficKit-HTTP%20debugging%20proxy-e5a445?style=for-the-badge&logo=go&logoColor=white&labelColor=1f2530)](https://github.com/kspkr/TrafficKit)
&nbsp;
[![QRForge](https://img.shields.io/badge/QRForge-QR%20code%20platform-e5a445?style=for-the-badge&logo=react&logoColor=white&labelColor=1f2530)](https://github.com/kspkr/QrForge)
&nbsp;
[![WireKit](https://img.shields.io/badge/WireKit-Go%20network%20primitives-e5a445?style=for-the-badge&logo=go&logoColor=white&labelColor=1f2530)](https://github.com/kspkr/wirekit)

<br />

</div>

## `GET /kspkr`

```http
HTTP/1.1 200 OK
Content-Type: application/json
X-Powered-By: Go, React, Rust
X-Telemetry: none
X-Account-Required: false
Cache-Control: no-cloud

{
  "handle":     "kspkr",
  "builds":     "local-first developer tools",
  "shipping":   ["TrafficKit", "QRForge", "WireKit"],
  "stack":      ["Go", "TypeScript / React", "Rust / Tauri", "Docker"],
  "principles": ["your data never leaves your machine",
                 "free means free, not freemium",
                 "if it needs an account, it is not a tool, it is a lease"],
  "status":     "building in public"
}
```

<br />

## What I ship

<table>
<tr>
<td width="50%" valign="top">

<div align="center">
<a href="https://github.com/kspkr/TrafficKit">
<img src="https://raw.githubusercontent.com/kspkr/TrafficKit/main/docs/images/logo.svg" width="56" alt="TrafficKit" /><br />
<h3>TrafficKit</h3>
</a>

**See every request your apps make. Decrypt HTTPS in one click. Let your AI read it too.**

<a href="https://github.com/kspkr/TrafficKit"><img src="https://raw.githubusercontent.com/kspkr/TrafficKit/main/docs/images/traffic.jpg" width="100%" alt="TrafficKit live traffic view" /></a>

![Go](https://img.shields.io/badge/Go-engine-00add8?style=flat-square&logo=go&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri_2-desktop-24c8db?style=flat-square&logo=tauri&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-ready-8b5cf6?style=flat-square)
![Platforms](https://img.shields.io/badge/Win_%7C_macOS_%7C_Linux-2b3137?style=flat-square)

</div>

A free HTTP/HTTPS debugging proxy with a fast desktop UI.

- One-click intercepted browsers and terminals, HTTPS included
- Live inspector for headers, bodies, timings and WebSocket frames
- Virtualized table that stays smooth at tens of thousands of requests
- Built-in [Model Context Protocol](https://modelcontextprotocol.io) server so Claude, Cursor and VS Code can read your traffic, with secrets redacted first
- Everything stays in memory on your machine

</td>
<td width="50%" valign="top">

<div align="center">
<a href="https://github.com/kspkr/QrForge">
<img src="https://raw.githubusercontent.com/kspkr/QrForge/main/assets/logo.svg" width="56" alt="QRForge" /><br />
<h3>QRForge</h3>
</a>

**Design in the browser. Self-host dynamic codes. Measure scans without tracking people.**

<a href="https://github.com/kspkr/QrForge"><img src="https://raw.githubusercontent.com/kspkr/QrForge/main/assets/screenshot-studio.jpg" width="100%" alt="QRForge Studio" /></a>

![React](https://img.shields.io/badge/React-studio-61dafb?style=flat-square&logo=react&logoColor=black)
![Go](https://img.shields.io/badge/Go-server-00add8?style=flat-square&logo=go&logoColor=white)
![npm](https://img.shields.io/npm/v/@qrforge/core?style=flat-square&label=%40qrforge%2Fcore&color=e5a445)
![Docker](https://img.shields.io/badge/Docker-compose_up-2496ed?style=flat-square&logo=docker&logoColor=white)

</div>

An open-source QR code platform covering the whole lifecycle.

- Browser designer with shapes, logos, frames and a scan-quality check
- Static codes render fully client-side, nothing is uploaded
- Dynamic codes from your own server: editable, expiring, password-protected
- Anonymous analytics: devices, countries, referrers, no third-party trackers
- Ships as `@qrforge/core`, `@qrforge/react`, a CLI and a REST SDK

[Try the live Studio →](https://kspkr.github.io/QrForge/)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

<div align="center">
<a href="https://github.com/kspkr/wirekit">
<img src="https://raw.githubusercontent.com/kspkr/wirekit/main/docs/images/logo.svg" width="56" alt="WireKit" /><br />
<h3>WireKit</h3>
</a>

**Go primitives for inspecting, parsing, and working with network data.**

![Go](https://img.shields.io/badge/Go-1.25%2B-00add8?style=flat-square&logo=go&logoColor=white)
![Std lib](https://img.shields.io/badge/dependencies-standard_library-2b3137?style=flat-square)
![Fuzzed](https://img.shields.io/badge/parsers-fuzzed-8b5cf6?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-e5a445?style=flat-square)

</div>

The protocol layer under TrafficKit, released as a library for anyone writing proxies, inspectors or protocol tests.

- HTTP messages with headers in wire order, cookies with RFC 6265 validation, bounded body capture
- WebSocket frames, message reassembly and close codes
- TLS connection and certificate summaries, plus a ClientHello parser with SNI, ALPN and JA3
- gzip, brotli and zstd decoding with limits, so a kilobyte cannot become a gigabyte
- Every parser fuzzed, every size bounded, nothing panics on hostile input

```go
req, _ := httpkit.ParseRequest(raw)
fmt.Println(req.Headers.Get("content-type"), req.Cookies(), req.Body.Size)
```

</td>
</tr>
</table>

<br />

## How I build

<table align="center">
<tr>
<td align="center" width="33%">
<h3>🖥️ Local-first</h3>
Software should work on a plane, in a basement, and after the company behind it disappears. Data stays where it was created.
</td>
<td align="center" width="33%">
<h3>🔓 Free, actually</h3>
MIT licensed. No paid tier, no usage caps, no "contact sales". If a feature exists, you have it.
</td>
<td align="center" width="33%">
<h3>🤖 AI-native, not AI-hostage</h3>
Tools expose their state over MCP so your assistant can help. Secrets are redacted before anything leaves the process.
</td>
</tr>
</table>

<br />

## Stack

<div align="center">

<a href="https://skillicons.dev">
<img src="https://skillicons.dev/icons?i=go,ts,js,react,rust,tauri,nodejs,vite,docker,html,css,git,github,githubactions&perline=7" alt="Go, TypeScript, JavaScript, React, Rust, Tauri, Node.js, Vite, Docker, HTML, CSS, Git, GitHub, GitHub Actions" />
</a>

<sub>Go for engines that must be fast and boring. React for interfaces. Rust + Tauri when it has to live on the desktop.</sub>

</div>

<br />

## Activity

<div align="center">

<a href="https://github.com/kspkr">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=kspkr&theme=github_dark" alt="GitHub stats" />
</a>
<a href="https://github.com/kspkr">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kspkr&theme=github_dark" alt="Languages across repositories" />
</a>

<a href="https://github.com/kspkr">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=kspkr&theme=github_dark" alt="Most committed languages" />
</a>
<a href="https://github.com/kspkr">
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=kspkr&theme=github_dark&utcOffset=0" alt="Commit times" />
</a>

<br /><br />

<a href="https://github.com/kspkr">
<img src="https://streak-stats.demolab.com?user=kspkr&theme=dark&hide_border=true&background=0f1115&ring=e5a445&fire=e5a445&currStreakLabel=e5a445&sideLabels=c9d1d9&dates=8b949e" alt="Contribution streak" />
</a>

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kspkr/kspkr/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/kspkr/kspkr/output/github-snake.svg" alt="Contribution snake" width="100%" />
</picture>

</div>

<br />

## Talk to me

<div align="center">

Found a bug, want a feature, or built something on top of one of these? Open an issue or a discussion. I read all of them.

[![Issues](https://img.shields.io/badge/Open_an_issue-TrafficKit-1f2530?style=for-the-badge&logo=github)](https://github.com/kspkr/TrafficKit/issues/new)
[![Issues](https://img.shields.io/badge/Open_an_issue-QRForge-1f2530?style=for-the-badge&logo=github)](https://github.com/kspkr/QrForge/issues/new)
[![Issues](https://img.shields.io/badge/Open_an_issue-WireKit-1f2530?style=for-the-badge&logo=github)](https://github.com/kspkr/wirekit/issues/new)

<br />

<sub>⭐ A star on any of these repos is the cheapest way to tell me to keep going.</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:e5a445,50:1f2530,100:0f1115" width="100%" alt="" />
