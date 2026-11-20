# Bogdan Sergeevichev

Backend and developer-tools engineer. I write Go, TypeScript and Kotlin, and I ship
systems that run every day instead of demos: an ERP that a real business uses for sales,
stock, cash shifts and fiscal receipts; a programming language with its own compiler and
LSP; terminal and web tools for working with AI coding agents.

Fourth-year Computer Engineering student at Antalya Bilim University (2023–2027).
Open to remote backend and tooling work.

## What I have built

| Project | What it is | Stack |
|---|---|---|
| [nit-gui](https://github.com/bongdo/nit-gui) | Web GUI for the OpenCode AI coding agent: sessions, streaming transcript, attachments, several agent servers behind one login | Go, React 19, TypeScript, SSE |
| [nit-android](https://github.com/bongdo/nit-android) | Native Android client for the same agent: SSE with reconnect, offline cache, encrypted session storage | Kotlin, Compose |
| [term-gui](https://github.com/bongdo/term-gui) + [termcore](https://github.com/bongdo/termcore) | Web terminal: one Go binary with an embedded SPA, one tmux shell per workspace, PTY engine extracted into a reusable module | Go, React, xterm.js, tmux |
| [strizh](https://github.com/bongdo/strizh) | Application language with a Go runtime: Hare-like syntax, sum types, structured parallelism — lexer, parser, semantic analysis, codegen, formatter, LSP | Go, Ink |
| [pero](https://github.com/bongdo/pero) | Modeless terminal code editor with LSP, mouse, tabs and AI assist | Go, Bubble Tea |
| [oracle-nix](https://github.com/bongdo/oracle-nix) | Reproducible NixOS image for Oracle Cloud A1 with Tailscale, Caddy and SearXNG | Nix |
| [telegram-tui](https://github.com/bongdo/telegram-tui) | Mouse-first Telegram client for the terminal | Go |
| [chinese-cards](https://github.com/bongdo/chinese-cards) | Offline-first flashcards with a Go sync server | Expo, Go |

## How I work

- One process, one binary where possible: SQLite instead of a cluster, systemd instead of
  an orchestrator, backups before migrations.
- Validation at every boundary: role checks in guards *and* database constraints, signed
  cookies shared between services, health checks before anything is published.
- Readable code over clever code. If a shortcut has a known limit, it is written down next
  to the shortcut.

## Toolbox

**Languages** Go, TypeScript/JavaScript, SQL, Kotlin, Python, Bash; some Zig, Nim, C3.
**Backend** net/http, PostgreSQL, SQLite, GORM, SSE, RBAC, HMAC/TOTP, FIFO costing.
**Frontend** React 19, Tailwind 4, Vite, CodeMirror 6, xterm.js.
**Mobile** Kotlin/Compose, Expo/React Native.
**Tooling** compilers, parsers, LSP, formatters, Bubble Tea, PTY, WebGL2.
**Infra** Linux, NixOS, systemd, nginx, Caddy, Docker, Tailscale.

## Contact

[bongdoq@gmail.com](mailto:bongdoq@gmail.com) · [t.me/bongdo](https://t.me/bongdo)
