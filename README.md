# Fahad Bilal Saleem

**Software Engineer · Full-Stack & AI Systems** · Abu Dhabi, UAE

I've been shipping production websites since 2019, and since 2023 I've been the sole developer in every full-time role, owning code, releases, hosting, security and performance end to end. Since 2025 I've extended that into backend, infrastructure and AI engineering. Everything below I built and run myself.

Available immediately · open to relocation worldwide and remote roles.

---

## What I'm building

### Atlas — Personal AI operating system · private repo · [2-minute explainer](https://youtu.be/BMnlgIhvWiY)

A multi-agent AI system I built alone in Node.js, with no orchestration framework. It has run 24/7 on my own Oracle Cloud server since February 2026.

- **116 tools across 15 MCP servers**, a queen agent coordinating 9 workers, and 17 recurring autonomous workflows.
- **Routing:** a fast router model picks one of six routes; DeepSeek does the heavy reasoning, falling back to Groq and then local Gemma and Qwen.
- **Hybrid RAG:** pgvector similarity fused with PostgreSQL full-text search via Reciprocal Rank Fusion.
- **Safety:** five-tier tool authorisation, prompt-injection defence, credential scrubbing; risky actions wait for my approval on my phone.
- **ML:** a gradient-boosted model (R² 0.87, MAE 7.3 on a 0–100 scale) reproduces Atlas's job-fit scores instantly and at no cost. Retrained every Sunday; a new version replaces the old only if it's measurably better (1 promotion, 9 rejections since August).
- **Observability:** 1,000+ tests, every API call logged with its cost, Prometheus and Grafana across 33 gauges. Under $5 a month since May 2026.
- Voice and chat in English, Urdu and Punjabi.

### [Convolvger](https://github.com/fahadbilalsaleem/convolvger) — AI conversation archiver · [PyPI](https://pypi.org/project/convolvger/)

Turns public share links from eight AI providers (ChatGPT, Claude, Gemini, Grok, DeepSeek, Kimi, Qwen, Perplexity) into a canonical, schema-versioned archive with deterministic Markdown and JSON export, including a numbered Sources list for the pages an answer cites. Local-first: no LLM, no credentials, no telemetry. Every gap in what a provider served is recorded as a structured finding, never silently dropped, and `convolvger verify` checks an archive is complete and faithful. Nine releases, 0.1.0 to 0.7.0.

`Python 3.12+` `Pydantic` `Typer` `httpx` `pytest` `mypy --strict` `GitHub Actions`

### [Taphonomy](https://github.com/fahadbilalsaleem/taphonomy) — FAT32 evidence recovery in Rust

Recovers deleted and quick-format-orphaned files from FAT32 disk images. Read-only, SHA-256 hashing, and a named refusal wherever a recovery can't be supported. Checked against three NIST CFReDS images and The Sleuth Kit 4.12.1: every file it recovered matched NIST's documented sectors. 17 ADRs, 8 recorded experiments, 295 tests.

`Rust` `SHA-256` `FAT32` `GitHub Actions`

### [Orbital Viewer](https://github.com/fahadbilalsaleem/orbital-viewer) — Satellite tasking · [live demo](https://geo.fahadbilal.com)

A 3D globe with live SGP4 propagation over CelesTrak TLEs, real Copernicus Sentinel-2 imagery through the STAC API, and GiST-indexed PostGIS spatial matching across coverage, cloud cover and timing. Simulated elements are labelled as simulated.

`React 19` `TypeScript` `FastAPI` `PostgreSQL 16` `PostGIS` `MapLibre GL JS` `Docker`

### [Project Ephemeris](https://github.com/fahadbilalsaleem/project-ephemeris) — Satellite passes

Built in three days as a technical assessment: about 60 MB of orbital-track data processed with DuckDB Spatial behind a Node/Express/TypeScript API, visualised on MapLibre GL JS, containerised, with CI and Vitest.

### [Web Performance Monitor](https://github.com/fahadbilalsaleem/performance-monitor) — Core Web Vitals over time · [live demo](https://performance-monitor-beta.vercel.app)

Runs PageSpeed Insights audits on mobile and desktop and keeps every run, so LCP, INP, CLS, SEO and accessibility can be tracked over time. Filters, charts, CSV export, and per-user data kept separate with Supabase row-level security.

`Next.js` `Supabase` `PageSpeed Insights API` `Vercel`

---

## Stack

| | |
|---|---|
| **Professional** | PHP · JavaScript · MySQL · WordPress · WooCommerce · Shopify Liquid · Cloudflare · technical SEO · Core Web Vitals |
| **Independent** | TypeScript · Python · Rust · Node.js · FastAPI · PostgreSQL · PostGIS · pgvector · React 19 · Next.js · Docker · NGINX · Oracle Cloud · Prometheus · Grafana · GitHub Actions |
| **AI** | MCP · multi-agent orchestration · hybrid RAG · LLM routing and fallback · DeepSeek · Groq · Ollama · scikit-learn |

---

## Experience

**Full-Stack Developer** (promoted from Lead Web Developer) · International Vision Investments, Abu Dhabi · Oct 2024 – Apr 2026
The group's first in-house developer, sole engineer for 10+ production websites across its seven companies, including ivi.ae (custom PHP and MySQL), plus hosting, Cloudflare, performance and SEO for all of them.

Before that: sole developer at Vapes Bars (Shopify storefront and two B2B wholesale sites), a Shopify bookstore launch for Book Hero, and freelance work for clients in the US, UK and Pakistan since 2019.

---

**Portfolio** [fahadbilal.com](https://fahadbilal.com) · **LinkedIn** [in/fahadbilalsaleem](https://linkedin.com/in/fahadbilalsaleem) · **Email** contact@fahadbilal.com
