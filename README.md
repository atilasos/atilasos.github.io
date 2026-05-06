# atilasos.github.io

Personal site of Igor Almeida — ICT teacher in primary school, Funchal, Madeira.

Live: https://atilasos.github.io

## Structure

- `index.html`, `projetos.html`, `percurso.html`, `formacao.html`, `contacto.html` — pt-PT pages (default).
- `en/index.html`, `en/projects.html`, `en/journey.html`, `en/training.html`, `en/contact.html` — English mirror.
- `assets/css/style.css` — single shared stylesheet (dark theme).
- `assets/fonts/` — self-hosted Inter and JetBrains Mono (woff2).

## Editing

- All pages are static HTML. Edit directly. No build step.
- The header (with PT|EN toggle) is repeated in each file. When changing it, update all 10 pages.
- Each page declares `<link rel="alternate" hreflang="…">` to its sibling in the other language.

## Local preview

```bash
cd atilasos.github.io
python3 -m http.server 8000
# open http://localhost:8000/
```

## Deployment

Pushed to `main` → published by GitHub Pages at the repository's configured URL.

## Privacy

This repository does not include personal documents, full certificates, identifiable student data, tax/ID numbers, home addresses, or complete validation keys.
