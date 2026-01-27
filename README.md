# Masters Dissertation

![Languages used](https://img.shields.io/github/languages/count/isadfrn/masters-dissertation?style=flat-square)
![Repository size](https://img.shields.io/github/repo-size/isadfrn/masters-dissertation?style=flat-square)
![Last commit](https://img.shields.io/github/last-commit/isadfrn/masters-dissertation?style=flat-square)

## About

This repository contains the LaTeX source code and related files for my Master's dissertation.

## Project Structure

```
masters-dissertation/
├── 00_main.tex                    # Main LaTeX document
├── abntex2-options.bib            # Bibliography options (required by abntex2cite.sty)
├── chapters/                      # Document chapters
│   ├── 01_introducao.tex
│   ├── 02_cap2.tex
│   ├── 03_cap3.tex
│   ├── 04_cap4.tex
│   ├── 05_cap5.tex
│   └── 06_conclusao.tex
├── frontmatter/                   # Pre-textual elements
│   ├── resumo.tex                 # Abstract (Portuguese)
│   ├── abstract.tex               # Abstract (English)
│   ├── lista_figuras.tex         # List of figures
│   ├── lista_tabelas.tex          # List of tables
│   ├── lista_acronimos.tex        # List of acronyms
│   └── sumario.tex                # Table of contents
├── appendices/                    # Appendices (when needed)
│   └── 20_apendiceA.tex ... 26_apendiceG.tex
├── styles/                        # LaTeX styles and packages
│   ├── abntex2.cls                # Main document class
│   ├── abntex2cite.sty            # Citation package
│   ├── abntex2abrev.sty           # Abbreviation package
│   ├── acronimos-extendido.sty    # Extended acronym package
│   ├── univali_custom.sty         # UNIVALI custom style
│   ├── abntex2-alf.bst            # Bibliography style (alphabetical)
│   └── abntex2-num.bst            # Bibliography style (numerical)
├── bibliography/                  # Bibliography files
│   └── 11_referencias.bib
├── _template/                     # Unused template files
│   ├── agradecimentos.tex
│   ├── dedicatoria.tex
│   ├── epigrafe.tex
│   ├── ficha_catalografica.tex
│   ├── folha_de_aprovacao.tex
│   ├── lista_quadros.tex
│   ├── lista_siglas.tex
│   └── lista_simbolos.tex
├── figs/                          # Figures and images
└── scripts/                       # Scripts and notebooks
    └── graficos.ipynb             # Jupyter notebook for graph generation
```

## Run

To compile this document, use [Overleaf](https://www.overleaf.com/). Simply upload the project files to Overleaf and compile `00_main.tex`.

## Status

Maintaining

## License

[CCPL](./LICENSE)
