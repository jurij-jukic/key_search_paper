# Neural Network Training as Key Search Across Resolution Bands

Public preprint/arXiv source for the paper.

Repository: <https://github.com/jurij-jukic/key_search_paper>

The public code and experiment package is maintained separately at
<https://github.com/jurij-jukic/key_search_paper_code>.

## Build

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

The generated `main.pdf` and BibTeX output `main.bbl` are tracked for release
convenience. Transient LaTeX build files are ignored.

## Contents

- `main.tex`: paper source.
- `references.bib` and `main.bbl`: bibliography source and compiled bibliography.
- `neurips_2026.sty`: local style file needed for portable builds.
- `figures/`: figures included in the paper.
