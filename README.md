# Unofficial KCL LaTeX PhD Thesis Template

An unofficial LaTeX template for King's College London PhD thesis submissions.

This template is designed to be clear, minimal, and easily extendable while remaining compliant with typical KCL formatting expectations.

## License

This template is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License.

You are free to use, modify, and distribute this template with appropriate attribution.

## Overview

This template is adapted and consolidated from several publicly available thesis templates, including:

- [Bo Gao](https://www.overleaf.com/latex/templates/phd-thesis-template-for-kings-college-london/ftmpffzrydpq)
- [Andre Miede (Classic Thesis)](https://www.overleaf.com/latex/templates/classic-thesis-style-v4-dot-2-by-andre-miede/dwgtvykzvdtk)
- [Clara Eleonore Pavillet](https://www.overleaf.com/latex/templates/thesis-template-oxfordpav/fhwkjvtwpdzt)

It provides a modular structure suitable for large thesis projects.

## Project Structure

- `report.tex` — Main thesis entry point
- `packages.tex` — Centralised package configuration
- `KCL_Thesis_Template.pdf` — Example compiled output
- `FrontMatter/` — Declaration, abstract, acknowledgements, etc.
- `Chapters/` — Individual thesis chapters (modular structure)
- `Appendices/` — Supplementary materials
- `references.bib` — Main bibliography
- `personal.bib` — Personal publications list

## How to Compile

This template is configured for `pdflatex`.

Typical compilation sequence:

pdflatex report.tex
bibtex report
pdflatex report.tex
pdflatex report.tex

Alternatively, use:

latexmk -pdf report.tex


## Tested With

- Overleaf (January 2025)
- TeXShop 5.47 (macOS Sequoia 15.2)
- `latexmk` / `pdflatexmk`


## Author

Created and maintained by Humphrey Curtis.

With helpful suggestions from:
- Yazz Warsame  
- Benjamin Krarup  
- Alexandre Nevsky  

## Disclaimer

Users should verify formatting requirements against official KCL university submission guidelines.