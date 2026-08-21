Source Sans 3 (Adobe's successor to Source Sans Pro), release [3.052R](https://github.com/adobe-fonts/source-sans/releases/tag/3.052R).

Only the four weights `resume.tex` uses are kept here: Regular, Bold, Italic, Bold Italic.

Licensed under the SIL Open Font License 1.1 — see `LICENSE.md`.

Compiling `resume.tex` requires `xelatex` or `lualatex` (via `fontspec`), not plain `pdflatex`. The GitHub Actions workflow (`.github/workflows/build.yml`) is configured to use `xelatex`.
