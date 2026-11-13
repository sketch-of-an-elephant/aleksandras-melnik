# aleksandras-melnik

Personal site and CV of Aleksandras Melnik, served at https://sketch-of-an-elephant.github.io/aleksandras-melnik/

- `index.html`, `style.css`: the site.
- `cv/cv.tex`: the CV in LaTeX. On every push to `main`, GitHub Actions compiles it and publishes it at `/cv.pdf` together with the site.

To build the CV locally: `cd cv && pdflatex cv.tex`.
