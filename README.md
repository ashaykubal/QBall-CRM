# QBall CRM — AI-Native CRM Prototype

> **Live demo:** [ashaykubal.github.io/QBall-CRM](https://ashaykubal.github.io/QBall-CRM/)

QBall CRM is a design prototype for a sell-side financial services CRM built around a core conviction:

> **The role of AI in an AI-native CRM is not that of a chatbot.** The chat interface is essential, but secondary. Instead, AI is deeply embedded into user workflows — often enhancing and augmenting them with critical insights.

This prototype showcases three persona-specific surfaces inside an investment bank, each demonstrating how AI (the embedded agent **Qubie**) augments daily work rather than just answering questions.

---

## The three views

| View | Persona | Core workflow |
|------|---------|---------------|
| **Equity Research** | Sell-side equity research analyst | Contact engagement scoring, II vote campaigns, report distribution |
| **Sales & Trading** | Sell-side equity sales trader | Account coverage tiles, consumption analytics, revenue attribution |
| **Investment Banking** | M&A banker (VP / Associate) | Deal pipeline kanban, stage-gate AI assistance, pitch deck generation |

Switch views via the floating segmented control in the top-right of the prototype (this control sits outside the product UI — it exists only for navigation between the three demos).

---

## Qubie — the embedded AI agent

Qubie appears on **two interaction surfaces** that coexist throughout the product:

### Surface 1 — Command bar (AI-forward)
A persistent input at the bottom of every view (`⌘K` to focus). Expands into a chat-style panel for conversational, intent-driven interactions. Outputs are **actionable** — lists become interactive tiles, drafts become editable blocks with `Send` / `Edit in full view` actions.

### Surface 2 — Inline (embedded intelligence)
Qubie appears contextually within the structured UI — annotations on contact rows, nudge badges on account tiles, stage-gate offers when a deal card moves between columns, morning-brief summary cards at the top of boards. Not chat — **pre-computed insights and offers to act**.

Both surfaces converge on the same structured product UI. Surface 1 is user-initiated; Surface 2 is system-initiated.

---

## What's in this prototype

- ✅ Three full persona views (EQ Research, Sales & Trading, IB / M&A)
- ✅ Both Qubie surfaces wired across all views
- ✅ Vibrant (light) + Midnight (dark) theme support
- ✅ Realistic sample data + interaction patterns (drag-to-stage, audience assembly, pitch generation)
- 🚫 Not a working product — no backend, no real data, no auth

## Versions

| Version | Live URL | Notes |
|---------|----------|-------|
| **Latest** | [/](https://ashaykubal.github.io/QBall-CRM/) | Whatever's currently at repo root |
| v1 (2026-05) | [/v1/](https://ashaykubal.github.io/QBall-CRM/v1/) | Initial prototype |

---

## How it's built

- **Single self-contained HTML file** generated via [Claude Design](https://claude.ai/) — no build step, no backend, no dependencies. Just open in a browser (or serve via GitHub Pages).
- **QBall design system** — custom tokens, components, fonts (separate spec, not in this repo).
- **Specification** — full UX spec (Qubie surfaces, view layouts, stage gates, interaction summary) is the source of truth that drove the prototype.

---

## Status

Design prototype only. Not production code. Built to showcase the AI-native CRM concept for design reviews, stakeholder demos, and pattern conversations.

For questions or collaboration: [@ashaykubal](https://github.com/ashaykubal)
