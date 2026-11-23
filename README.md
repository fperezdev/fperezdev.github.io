# fperezdev.github.io

Source of my portfolio — **[fperezdev.github.io](https://fperezdev.github.io/)** (English) ·
**[/es.html](https://fperezdev.github.io/es.html)** (español).

Static site, no build step, no dependencies: three files served straight by GitHub Pages.

```
index.html   English version
es.html      Spanish version
style.css    shared styles (warm paper, green accent, Montserrat + JetBrains Mono)
og.png       social share card (1200×630)
```

## What it says, and why

The page sells one thing: **a manual, repetitive process turned into an automation that holds up
in production**. Everything on it is verifiable:

- **AI Automation Suite** — four modules on n8n + an LLM for a dental clinic in Ñuñoa, each with
  its own golden set and a reproducible evaluation.
- **FlowWatch** — Go + Next.js pipeline alerting, 30/30 on its evaluation set and 400/400 events
  through a pod-kill test on k3s.
- The metrics table uses medians and per-operation cost measured with the mock model, because
  numbers without a reproducible command are decoration.

Claims I do not make: no invented clients, no "years of experience" beyond the five years of
full-stack work, no results that cannot be reproduced from a public repository.

## Editing

Edit the HTML/CSS directly and open the file in a browser — there is no toolchain. Keep both
languages in sync: `index.html` and `es.html` share structure and `style.css`.

The table collapses to stacked rows below 640 px (CSS only, via `data-label` attributes), and
animation is skipped entirely under `prefers-reduced-motion`.

## Elsewhere

- **Profile:** [github.com/fperezdev](https://github.com/fperezdev)
- **Suite:** [ai-automation-suite](https://github.com/fperezdev/ai-automation-suite) · [demo](https://ai.fperez.top/)
- **Workana:** [freelancer profile](https://www.workana.com/freelancer/bb457201c64a7fe99c5cc2c6f555dead)
- **LinkedIn:** [in/fperezlefiman](https://www.linkedin.com/in/fperezlefiman/)

<sub>© Francisco Pérez Lefiman · Santiago, Chile.</sub>
