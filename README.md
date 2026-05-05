# Literature Review Template

These are quarto and rmarkdown templates for research literature review.
They are meant to make reading, taking notes and keep track of your studies easy.

## Getting Started

### Dependencies

* rmarkdown
* quarto
* curl

### Executing program

* use the scripts in `scripts/` to render the markdown files to pdf
```
./scripts/rmd2pdf lit-review-template.rmd
./scripts/qmd2pdf lit-review-template.qmd
```
* use `scripts/doi2bib` to generate the bibtex entry for a document given the doi
(this script simply prints the results, redirect it into your references and clean the key as needed)
```
./scripts/doi2bib '11.1038/ng.2982' >> references.bib
```
