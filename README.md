# Latex Templates

Various Latex Templates

- [Beamer Presentation Template](beamer-presentation/main.tex)
- [Simple A4 Book Template](simple-a4/main.tex)
- [Cheatsheet Template](cheatsheet/main.tex)

## Notes

1. Changing output directory:

- Add `-output-directory=DIR` parameter to `pdflatex` command.

2. Mintex problem after output directory change:

- Use mintex with output directory options

```tex
\usepackage[outputdir=DIR]{minted}
```
