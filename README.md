# Technical Documentation template for Latex

Yet another Latex template, but a specialized one!
This one is imspired by the KISS (keep it simple and stupid) principle and is focused on the minimum needed to create a complete technical documentation. It may be used for short general purpose documentations as well as a basis for a thesis document. It includes lists of figures, tables, abbreviations and a bibliography, math and units packages. The best way to include figures is providing them as `.eps` or `.pdf` vector graphics or as `.png` graphics.

This template is using the [KOMA script](https://komascript.de/) [(Documentation)](https://komascript.de/~mkohm/scrguien.pdf).

## Build configuration

This template is intended to be built with `pdflatex` and `biber`.
If Texmaker is used, change the `bib(la)tex` command to `biber %` in the configuration.

## Acronyms dictionary

The acronyms are implemented using the `acro` package [(Documentation)](http://mirror.easyname.at/ctan/macros/latex/contrib/acro/acro_en.pdf). This package offers multiple lists of abbreviations based on a classification.
The template already supplies as basic set of abbreviations for electronics and a suggested classification. However, the classification is currently not used and may be useful for larger documents.

Simple abbreviations are created by using `\ac{}` and the abbreviated item name from the acronyms file.
