# yonsei-thesis
Used yonsei thesis format.

* Accompanied with [VSCode LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) configuration
* **XeLaTeX(!!)** is highly recomemended
* It has not been tested in `pdfLaTeX.`.

# Requirements
* [Tex Live 2023](https://www.tug.org/texlive/)

# Fonts
* Body(Serif) : [Noto Serif Korean](https://fonts.google.com/noto/specimen/Noto+Serif+KR)
* Math : [TeX Gyre Schola Math](https://ctan.org/pkg/tex-gyre-math-schola?lang=en)
* Mono : [Noto Sans Mono](https://fonts.google.com/noto/specimen/Noto+Sans+Mono)
* CJK : [Noto Serif Korean](https://fonts.google.com/noto/specimen/Noto+Serif+KR)

# Known Issue

* luaLaTeX partially works but not be guaranteed
    - Hangul support is limited in luaLaTeX
* **pdfLaTeX doesn't work** due to conflict between `kotex` and `siunitx`
    - If you disable `siunitx`, this document can be compiled with pdfLaTeX

# Reference
* [Georgia Tech - Thesis Template](https://github.com/manoj-c/GATechThesis)
