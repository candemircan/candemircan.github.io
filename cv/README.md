# Curriculum Vitae

LaTeX source of my CV. The rendered PDF is always **`Demircan_cv.pdf`**.

## Build

```sh
latexmk -pdf Demircan_cv.tex   # pdfLaTeX
```

(pdfLaTeX is required; XeLaTeX currently fails because the Cochineal/Cabin
font names are not resolvable system-wide on this machine.)

This folder lives in [candemircan.github.io](https://github.com/candemircan/candemircan.github.io)
(`cv/`) and is served at https://candemircan.github.io/cv/Demircan_cv.pdf.
