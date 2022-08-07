# Latex Presentation with Beamer

## Example Build Command

```sh
pdflatex -synctex=1 -interaction=nonstopmode -file-line-error -recorder -shell-escpe main.tex
```

## Notes

- Pygments required for minted package and also latex command should executed
  with `-shell-escape` parameter.

## Useful Resources

- [Beamer user guide](https://texdoc.org/serve/beamer/0)
- [Overleaf Beamer](https://www.overleaf.com/learn/latex/Beamer)
