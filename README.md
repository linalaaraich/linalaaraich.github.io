# linalaaraich.github.io

Personal portfolio of **Lina Laaraich** — SRE & DevOps Engineer.
Live at **https://linalaaraich.github.io**

A single self-contained `index.html` (terminal-themed, bilingual FR/EN, light/dark) that
hydrates client-side with React + Babel from unpkg. No build step.

## Structure
- `index.html` — the whole site (markup, styles, fonts and runtime are all embedded).
- `assets/cv/` — downloadable CV PDFs linked from the contact section.
- `.nojekyll` — serve the files verbatim (no Jekyll processing).

## Featured project
The site leads with the **AI-Powered Observability Platform with LLM Root-Cause Analysis**
(final-year project at CIRES Technologies, Digital Factory — Tanger Med): a unified
metrics/logs/traces observability platform with an LLM-driven RCA engine, shipped to
production in June 2026. Median diagnosis latency cut from ~5 min to 38 s.

## Editing content
All text lives in `index.html`:
- English copy is written directly in the markup (elements carry a `data-i18n="key"`).
- French copy lives in the `fr = { ... }` dictionary inside the inline
  `<script type="text/x-dc">`.
To change a string, edit the English text in the markup **and** its matching key in `fr`.

## Credit
Design by Lina Laaraich. CIRES project integration and deployment scaffolding added 2026.
