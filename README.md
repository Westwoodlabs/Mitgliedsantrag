# Antrag auf Mitgliedschaft

## Bauen (Docker)

`docker run -v "$(pwd):/workdir" danteev/texlive latexmk -pdf -latexoption=-file-line-error -latexoption=-interaction=nonstopmode -outdir=build 'Mitgliedsantrag Westwoodlabs.tex'`

## Bauen (unter Arch-Linux)
Dependencies: `pacman -S texlive-most`
Bauen: `pdflatex 'Mitgliedsantrag Westwoodlabs.tex'`