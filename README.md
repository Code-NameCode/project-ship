# ZA_AI://TERMINAL

**South Africa's premier terminal-themed portal for local AI News, Draft National AI Policy updates, and the African LLM Leaderboard. Benchmarking Zulu, Xhosa, and Afrikaans language performance.**

---

## Table of Contents
- [About The Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [SEO & Compliance](#seo--compliance)
- [Contact](#contact)
- [License](#license)

## About The Project
`ZA_AI://TERMINAL` is a retro-terminal-styled web application built to serve as a centralized intelligence hub for the South African AI ecosystem. It analyzes artificial intelligence performance, local language accuracy (isiZulu, isiXhosa, Afrikaans, Sepedi), and policy changes within South Africa through an interactive, CRT-themed interface.

A clear README sets expectations and provides a roadmap for getting started [note: MD+HTML/Generated_blog_1780163952910.md § Why a README.md Matters]. This document follows professional documentation structures [note: MD+HTML/Generated_blog_1780163952910.md § Core Components of a High‑Quality README.md] to help contributors and users understand the project quickly.

## Features
- **News & Editorial Tab:** Coverage of the Draft National AI Policy (DCDT 2026), Justice Ministry bias warnings, Telkom R100M AI pledge, and UCT multilingual model releases.
- **Africa LLM Leaderboard:** Interactive benchmark table ranking Gemini 3.5 Flash, Claude 4.6 Opus, DeepSeek-V4-Pro, GPT-5.4, and local fine-tuned models across AfriMCQA, AfriMMLU, MasakhaNEWS, and AfriMedQA v2.
- **Console Shell (CLI):** Simulated terminal environment with command parsing (`help`, `news`, `benchmarks`, `subscribe`, `sponsors`, `clear`) and Web Audio API keystroke sounds.
- **ZA SEO Checklist:** Local compliance suite with real-time meta index checking and POPIA alignment status.
- **Theme Switcher:** Phosphor Green, Cyber Amber, Steel Cyan, and High-Contrast palettes with scanline CRT effects.
- **Live Stats:** SAST (South African Standard Time) clock, simulated JINX/CINX latency ping, and compliance badges.

## Tech Stack
- **Markup:** HTML5 (Single-file architecture)
- **Styling:** Tailwind CSS (CDN), Custom CSS (CRT/scanline effects)
- **Fonts:** Google Fonts – Inter & JetBrains Mono
- **Logic:** Vanilla JavaScript (Tab state machine, CLI interpreter, Web Audio synthesizer)
- **SEO:** JSON-LD Structured Data (`WebSite` & `TechArticle` schemas)

## Getting Started
This is a static, self-contained HTML project requiring no compilation.

### Prerequisites
- A modern web browser with JavaScript enabled
- Internet connectivity (for Tailwind CDN and Google Fonts loading)

### Installation
1. Download or clone the repository containing `za_ai_terminal_news_blog_benchmarks(3).html`.
2. Open the file directly in your browser, or serve it locally:
   ```bash
   python3 -m http.server 8000
   # Visit http://localhost:8000/za_ai_terminal_news_blog_benchmarks(3).html
   ```

## Usage
### Navigation
Use the top terminal navigation bar to switch views:
- `[1] NEWS & EDITORIAL` – Blog posts and policy updates
- `[2] AFRICA LLM BENCHMARKS` – Performance metrics table
- `[3] CONSOLE SHELL` – Interactive CLI
- `[4] ZA SEO CHECKLIST` – Local audit suite

### CLI Quick Reference
| Command | Action |
|---------|--------|
| `help` | List available shell scripts |
| `news` | Query latest SA AI news logs |
| `benchmarks` | Load Q2 2026 evaluation metrics |
| `subscribe <email>` | Register under POPIA compliance |
| `sponsors` | Show institutional partners |
| `clear` | Flush the terminal buffer |

## Project Structure
The application is delivered as a single portable HTML file:
```
za_ai_terminal_news_blog_benchmarks(3).html
├── <head>     : SEO meta, Open Graph, JSON-LD, Tailwind config, embedded styles
├── <body>     : Terminal UI (Header, Nav, Main Views, Aside Widgets, Footer)
└── <script>   : Audio synth, theme switching, CLI router, modal handlers
```

## SEO & Compliance
- **POPIA Aligned:** Cookie-free architecture, privacy-first newsletter capture [note: za_ai_terminal_news_blog_benchmarks(3).html § VIEW 4].
- **Localized Schema:** Embedded `PostalAddress` (Rosebank, Johannesburg) for geo-targeting.
- **Multilingual Ready:** Hreflang mappings for `en-ZA`, `zu-ZA`, and `xh-ZA`.

## Contact
Provide support channels or inquiries via:
- **Organization:** ZA AI Innovation Systems (ZA AI Terminal Division)
- **Location:** 160 Jan Smuts Avenue, Rosebank, Johannesburg, Gauteng, 2196, South Africa
- **Web:** [za-ai-terminal.co.za](https://za-ai-terminal.co.za/)
- **Issue Tracking:** Use the repository issue tracker for bugs or content updates [note: MD+HTML/Generated_blog_1780163952910.md § Contact]

## License
© 2026 ZA_AI TERMINAL INC. ALL RIGHTS RESERVED. IN COMPLIANCE WITH POPIA REGULATIONS.
