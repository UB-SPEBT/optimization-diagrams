# overall scheme
## How to compile in latex
### Standalone compilation to .svg file
```
latex overall-scheme.tex
dvisvgm --no-fonts overall-scheme.dvi
```
### Normal compilation to .pdf file
```
pdflatex overall-scheme.tex
```