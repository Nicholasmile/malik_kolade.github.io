# Malik Kolade — Quarto Portfolio

A personal portfolio for Malik Ishola Kolade, with a photograph, CV download, Bank Marketing case study, and research and experience summaries.

## Preview and build

```powershell
quarto preview
quarto render
```

Rendered pages are written to `_site/`. Edit the `.qmd` source pages and `styles.css`, rather than the generated HTML.

## Included materials

- `assets/malik-ishola.jpg`: supplied portrait, preserved unchanged.
- `assets/Malik_Kolade_CV.pdf`: supplied CV, preserved unchanged.
- `assets/bank-marketing.ipynb`: supplied notebook, preserved unchanged and offered as a download.
- Two charts extracted from the notebook’s saved outputs.

The notebook is a download resource and is not executed during site rendering. Obtain the CSV from UCI and install its Python dependencies before running it. The case-study metrics reflect saved outputs, rather than an independent rerun.

The project template remains available for editing but is excluded from rendering. Ongoing projects are labelled explicitly. LinkedIn is omitted until a verified URL is supplied.

## Before publication

See `PORTFOLIO_CHECKLIST.md`. The site has not been deployed by this update.

For GitHub Pages, initialise a repository, connect your intended remote, and use `quarto publish gh-pages` when ready. Choose the repository and hosting destination before publishing.
