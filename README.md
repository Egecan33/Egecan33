# Egecan Aktan

**AI agents · Data engineering · Operations research**

I build Python systems that connect language models, data workflows and mathematical optimization. At **Cravio**, I work on founding and technical development, with experience in FastAPI, RAG and agent workflows. My academic background includes an MSc in Industrial Engineering at **Özyeğin University**.

My toolkit includes **Python, FastAPI, Docker, Airflow, PostgreSQL and Gurobi**. I am interested in opportunities where reliable software and explicit decision models meet.

## Featured: USA Energy Market

<p>
  <a href="https://github.com/Egecan33/USA_Energy_Market"><img alt="USA Energy Market repository" src="https://img.shields.io/badge/repo-USA__Energy__Market-0E5C8A?style=for-the-badge&logo=github"></a>
  <a href="https://github.com/Egecan33/USA_Energy_Market/actions/workflows/ci.yml"><img alt="CI status" src="https://github.com/Egecan33/USA_Energy_Market/actions/workflows/ci.yml/badge.svg?branch=main"></a>
  <img alt="Python 3.12" src="https://img.shields.io/badge/Python-3.12-0E5C8A?style=flat-square">
  <img alt="Built with AI agents" src="https://img.shields.io/badge/built%20with-AI%20agents-4B5E64?style=flat-square">
</p>

**[USA Energy Market](https://github.com/Egecan33/USA_Energy_Market)** is a knowledge base and teaching system for US electricity and gas markets, built with AI coding agents under strict, test-enforced rules. It turns energy podcasts, papers and grid-operator documents into cited evidence and linked notes, then into bilingual lessons and calculators.

- **Pipeline:** RSS feeds, publisher transcripts and local speech-to-text (Parakeet on MLX) for 1,000+ episodes, plus open-access papers and reports.
- **Quote gate:** every mined claim, number and prediction must quote its source exactly, or it fails validation.
- **Teaching:** 71 lessons in English and Turkish, 13 calculators (LMP, capacity auctions, FTRs, spark spreads and more), and an Obsidian vault of 6,000+ notes.
- **Market data:** `usgrid`, an eptr2-style client over `gridstatus` for the seven US grid operators.

**What's next** ([full roadmap](https://github.com/Egecan33/USA_Energy_Market/blob/main/docs/roadmap.md)):

| When | Plan |
| --- | --- |
| Nov–Dec 2026 | PJM and FERC EQR data through PUDL, daily data snapshots, primary-source lesson audits, weekly podcast sync |
| Q1 2027 | Settlement rule tables, `usgrid` on PyPI, a battery arbitrage backtester, the dashboard on GitHub Pages |
| Q2 2027 | FTR and congestion analytics, a capacity auction model, live market panels in lessons |
| H2 2027 | Interconnection-queue and data-center tracker, forecast baselines, a podcast prediction scoreboard, a cited Q&A agent and MCP server |

## Forge: local deck builders for card games

Three free, open-source deck builders that share one design: a pure TypeScript engine, SQLite, card images on disk and a Next.js interface on localhost. No account and no AI at runtime; every score is computed from card text, rules and synced data, and is shown with its reasons. Each ships as a portable download for macOS and Windows.

| Tool | Game | What it does | Download |
| --- | --- | --- | --- |
| [Commander Forge](https://github.com/Egecan33/mtg-commander-deck-builder) | Magic: The Gathering (Commander) | Bracket-aware auto-build, 0–100 card scores per commander, deck rating, improve suggestions, printable proxies, a deck finder for your collection. | [![Latest release](https://img.shields.io/github/v/release/Egecan33/mtg-commander-deck-builder?style=flat-square&color=0E5C8A)](https://github.com/Egecan33/mtg-commander-deck-builder/releases/latest) |
| [Riftbound Forge](https://github.com/Egecan33/riftbound-deck-builder) | Riftbound | Auto-builds legal decks, scores every card, rates a list, finds synergies and win conditions, gives matchup and side-deck lines for 1v1, 2v2 and FFA. | [![Latest release](https://img.shields.io/github/v/release/Egecan33/riftbound-deck-builder?style=flat-square&color=0E5C8A)](https://github.com/Egecan33/riftbound-deck-builder/releases/latest) |
| [Snap Forge](https://github.com/Egecan33/marvel-snap-deck-builder) | Marvel Snap | Brews off-meta decks that still clear a power floor, with a deck rating, a separate novelty score against synced meta lists, energy curve and draw odds, and swap suggestions. | [![Latest release](https://img.shields.io/github/v/release/Egecan33/marvel-snap-deck-builder?style=flat-square&color=0E5C8A)](https://github.com/Egecan33/marvel-snap-deck-builder/releases/latest) |

These are unofficial fan projects built with AI coding agents in staged, test-gated workflows. Ratings are heuristic construction checks, not win-rate predictions; each repository states what is measured and what is not. Card data and images are downloaded to the user's machine and are not part of the repositories.

## Selected technical projects

| Project | What to explore |
| --- | --- |
| [Agent Lot Sizing](https://github.com/Egecan33/lot-sizing-agent) | SmolAgents and a local language model connected to deterministic Gurobi tools; separate capacitated and uncapacitated planning models. |
| [Multi-Item Perishable Lot Sizing](https://github.com/Egecan33/multi-item-perishable-lot-sizing) | Compact mixed-integer formulations and branch-and-price experiments for production capacity and shelf-life constraints. Research code with several model iterations. |
| [Coil Stacking with Q-Learning](https://github.com/Egecan33/coil-stacking-q-learning) | A custom stacking environment and tabular Q-learning experiment with support, blocking and urgency rules. An experimental policy, with validation work still ahead. |
| [Explainable Road-Repair Prioritization](https://github.com/Egecan33/explainable-road-repair-prioritization) | An Ataşehir prototype combining OSM roads, simulated damage/POIs, XGBoost and SHAP. Heuristic training targets and distance-unit validation remain research limitations. |

## Side projects

- [EPİAŞ Price Explorer](https://github.com/Egecan33/epias-market-price-dashboard) — a Streamlit date selector and table viewer built around the external `eptr2` electricity-market data client.
- [Mechabellum Build Assistant](https://github.com/Egecan33/mechabellum-build-assistant) — a fan tool for counter lookups, composition vulnerabilities and tier-aware suggestions using structured game data.
- [Galio's Den](https://github.com/Egecan33/galios-den) — a Java console dungeon game with randomized encounters, resource choices and boss fights.

I use side projects to turn an idea into an interface, work with imperfect data and explore game mechanics. Repository maturity varies; research prototypes should be read with their assumptions and limitations.

## Open-source context

[eptr2](https://github.com/Egecan33/eptr2) and [Catan-AI](https://github.com/Egecan33/Catan-AI) are **forks of upstream projects**. They are separate from the original projects above; these links do not imply authorship of the upstream code.

You can explore my work and contact me through [GitHub](https://github.com/Egecan33).
