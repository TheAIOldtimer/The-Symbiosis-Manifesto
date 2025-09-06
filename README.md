# 🌱 The Symbiosis Manifesto

A living manifesto for **Symbiotic Intelligence** — not bigger models, but **better partnership** between humans and AI.

- **Philosophy:** Human × AI cooperation (symbiosis > replacement)  
- **Technical Direction:** HCR Architecture (Human-First, Context Assembly, Reasoning Orchestration, Resonance Loop, Private Memory, Guardrails)  
- **Personal Arc:** 1982 → 2025 → Future

📖 **Read the site:** <https://the-symbiosis-manifesto.netlify.app>  
🧭 **This repo:** Source for the manifesto site (HTML/CSS) + embedded HCR “white-paper” section.  
🔬 **Deeper technical work:** ZP-1 Protocol — <https://github.com/TheAIOldtimer/zp-1>

---

## Contents

- `/public/index.html` — Manifesto site (with expandable HCR white-paper sections)  
- `/public/manifesto.css` — Calm, accessible theme (mobile-first; dark/light aware)  
- `/public/og-symbiosis.png` — Social sharing image (optional)  
- `/public/favicon.ico` — Favicon (optional)  
- `LICENSE` — Code + text licenses

> Later we will extract a standalone white paper to `/whitepaper/hcr-architecture.md`.

---

## HCR Architecture (at a glance)

1. **Human-First Interface** — Calm UI, state-aware pacing, embedded boundaries  
2. **Context Assembly** — Retrieve only relevant encrypted memory slices  
3. **Reasoning Orchestration** — Small, composable passes (emotion, intent, plan, verify)  
4. **Resonance Loop (T/C/R)** — Live feedback on Trust, Clarity, Resonance  
5. **Private Memory** — Encrypted by default, human-readable recall  
6. **Agentic Guardrails** — Ask-before-act, audit trails, opt-in permissions

See the **HCR** section on the site for full details, implementation path, and a concrete **17×19** scaling case study.

---

## Contributing

We welcome thoughtful contributions:

1. **Fork** this repo  
2. Create a feature branch: `feat/your-change`  
3. Commit with clear messages  
4. Open a PR describing the change and why it improves clarity, trust, or resonance

For protocol-level ideas or research contributions, please also open an issue in **ZP-1**: <https://github.com/TheAIOldtimer/zp-1>

---

## Local preview

This is a static site (HTML/CSS only). Any static server works:

```bash
# from the repo root
cd public
python -m http.server 8080
# open http://localhost:8080
