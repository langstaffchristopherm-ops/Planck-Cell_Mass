# Planck-Cell — Mass

This archive contains the LaTeX source for **“Planck-Cell — Mass”**, where mass is framed as temporal stiffness (\(m=\hbar\omega_0/c^2\)). It includes a minimal constructive dynamics, sector-specific mappings (Higgs/QCD/neutrinos), a falsifier template, and a notation table.

## Build
```bash
latexmk -pdf -interaction=nonstopmode main.tex
# or: pdflatex main && bibtex main && pdflatex main && pdflatex main
```
**Note:** For clickable DOIs in the bibliography, ensure the `doi` package is loaded (it is via `other_tex/format_macros.tex`) and that your TeX distribution includes `plainurl.bst` (from `urlbst`). In `main.tex` we use `\bibliographystyle{\DefaultBibStyle}` which falls back to `plain` if `plainurl` is unavailable.

https://doi.org/10.5281/zenodo.17209646