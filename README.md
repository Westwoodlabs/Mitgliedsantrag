# Antrag auf Mitgliedschaft

Hier liegt der Westwoodlabs e.V. Mitgliedsantrag als LaTeX-Quelltext. Das PDF wird automatisch bei jedem Commit gebaut (siehe Build Artifacts). Wird der Commit zusätzlich getaggt, wird das PDF release und kann unter [Releases](https://github.com/Westwoodlabs/Mitgliedsantrag/releases) gefunden werden.

## Download

siehe [Releases](https://github.com/Westwoodlabs/Mitgliedsantrag/releases).

## Manuell Bauen

### Docker

`docker run -v "$(pwd):/workdir" danteev/texlive latexmk -pdf -latexoption=-file-line-error -latexoption=-interaction=nonstopmode -outdir=build 'Mitgliedsantrag_Westwoodlabs.tex'`

### Arch-Linux

Dependencies: `pacman -S texlive-most`
Bauen: `pdflatex 'Mitgliedsantrag_Westwoodlabs.tex'`
