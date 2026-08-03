# Quasar Spectrum Analysis

An observational astrophysics workflow in Python that downloads and parses 1D calibrated FITS spectroscopic data from astronomical archives (SDSS/DESI) to analyze quasar spectral features and the intergalactic medium.

## Overview
Quasars act as bright background light sources across cosmic distances. As their light travels toward Earth, it passes through intergalactic gas clouds composed of neutral hydrogen. Each cloud absorbs light at its specific redshifted wavelength, creating a dense array of absorption features known as the **Lyman-alpha ($\text{Ly}\alpha$) forest** blueward of the main emission peak.

## Features & Highlights
* **FITS Data Parsing:** Extracts 1D flux densities and logarithmic wavelength vectors directly from binary FITS table extensions using `astropy.io.fits`.
* **Wavelength Calibration:** Transforms logarithmic wavelength arrays into linear Angstroms for spectral plotting.
* **Spectral Analysis:** Identifies the redshifted $\text{Ly}\alpha$ emission line ($z \approx 4.5$) and maps line-of-sight neutral hydrogen absorption clouds.

## Tech Stack & Libraries
* **Python 3**
* **Astropy** (`astropy.io.fits`, `astropy.utils.data`)
* **Matplotlib**
* **NumPy**
