# NTU MAE MSc Dissertation Template (LaTeX)

LaTeX template for an MSc dissertation at the School of Mechanical and Aerospace
Engineering, NTU. All content is placeholder text; only the formatting is kept.

## Using it on Overleaf

1. New Project -> Upload Project -> upload the zip.
2. Menu -> Settings -> Compiler -> **XeLaTeX** (pdfLaTeX will not compile: the title page uses Arial via fontspec).
3. Recompile.

## What to edit

| File | Content |
|------|---------|
| `Title/titlepage.tex` | Title, name, programme, year |
| `PDFpage/statement.pdf` | Upload your signed Statement of Originality with this name; it replaces the placeholder page |
| `Front/Abstract.tex`, `Front/Acknowledgement.tex` | Abstract, acknowledgement |
| `Chapter1/` ... `Chapter6/` | Chapters (Chapters 2 and 3 contain examples of figures, tables, equations, lists and code) |
| `Figures/PDF/` | Figure files |
| `Ref/references.bib` | References (BibTeX, `unsrt` style: numbered in order of citation) |
| `main.tex` | Preamble and chapter order; optional Acronyms / Symbols / Appendix are commented out |

## Format

A4, 3 cm margins, 11 pt Times, 1.5 line spacing, no paragraph indent. Table of contents
unnumbered, front matter in roman numerals, main text in arabic numerals.

This is an unofficial template. Check the current school submission guidelines before submitting.
