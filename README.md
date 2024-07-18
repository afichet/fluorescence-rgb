# Fluorescence RGB

This repository contains companion code for our CGF paper [*Non-Orthogonal
Reduction for Rendering Fluorescent Materials in Non-Spectral Engine*](https://arxiv.org/abs/2406.17360) -
[Alban Fichet](https://afichet.github.io/),
[Laurent Belcour](https://belcour.github.io/blog/),
[Pascal Barla](https://www.labri.fr/perso/barla/blog/).


The notebook `Reduce Matrix.ipynb` provides the code for reducing spectral
reradiation matrices along with comparison with the naive method.


# Data sources

- The reradiation matrices in `assets/fluo` come from *Evaluation of Bispectral Spectrophotometry for Accurate Colorimetry of Printing Materials* Sergio Gonzalez https://web.archive.org/web/20191018071813/https://www.rit.edu/cos/colorscience/re_sgonzalez.php
- The CIE XYZ 2006 2 degrees CMF in `assets/CMF/ciexyz06_2deg.csv` comes from the Colour & Vision Research Laboratory: http://www.cvrl.org/
- The illuminants in `assets/illuminant` were extracted from colour library https://www.colour-science.org/