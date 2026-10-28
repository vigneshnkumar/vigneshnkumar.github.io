# vigneshnkumar.github.io

Personal landing page for Vignesh Kumar, live at **https://vigneshnkumar.github.io**.

Plain HTML + CSS with no build step and no dependencies. GitHub Pages serves it straight from `master`.

## Updating

| What | Where |
| --- | --- |
| Headline, pitch, links | `index.html`, `HERO` section |
| Impact numbers | `index.html`, `IMPACT` section (copy an `<article class="stat">`) |
| Skills / certs | `index.html`, `TOOLBOX` section |
| New job | `index.html`, `EXPERIENCE` section (copy an `<li>` to the top) |
| Resume | Replace `resume.pdf` (keep the same filename) |
| Photo | Replace `assets/vignesh.jpg` (square, ~480px) |
| Colors | `assets/style.css`, `--accent` at the top |

Preview locally: `python -m http.server` then open http://localhost:8000.
