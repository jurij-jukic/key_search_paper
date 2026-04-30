# Multiresolution Learning Dynamics Paper

Public/arXiv paper source staging copy.

This repository is currently a structural copy of the paper source. The author
block and public code URL should be updated in a later public-release pass.

## Build

```bash
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

The generated `main.pdf` and BibTeX output `main.bbl` are tracked for public
release convenience. Transient LaTeX build files are ignored.
