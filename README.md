# thesis-notes

Notes and code for my MA thesis in Statistics and Data Science at UC Berkeley, advised by Professor Steven Evans.

## Contents

- `2026-11-03-trs.qmd` — Spectral degeneracies of a topmost-to-random shuffle on balanced binary words. Renders to `2026-11-03-trs.html`.
- `index.qmd` — Landing page with links to the notes.
- `code/route1.py` — Trace check for the eigenvalue multiplicities, n = 1, ..., 9.
- `code/fig_eigenvalues.py`, `fig_graph4.py`, `fig_stirling.py`, `fig_partition.py`, `fig_mixing.py` — Standalone copies of the figure code.

## Live site

https://mattbix.github.io/thesis-notes/

## Build

Requires Quarto (https://quarto.org/) and Python with numpy, scipy, matplotlib, networkx.

    quarto render

This produces `index.html`, `2026-11-03-trs.html`, and `2026-11-03-trs_files/` in the repository root.

## Push to GitHub

    git init -b main
    git add .
    git commit -m "Initial commit: TRS spectrum note"
    git remote add origin https://github.com/mattbix/thesis-notes.git
    git push -u origin main

Then in the GitHub repository: Settings -> Pages -> Source: Deploy from a branch -> Branch: main, folder: / (root) -> Save.
