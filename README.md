# CO Line Fitting and Mass-Loss Estimation

This repository contains a Python-based Jupyter notebook that performs Gaussian fitting and physical analysis on molecular line spectra, specifically CO transitions (e.g., ¹²CO and ¹³CO). 
The code is designed to analyze observed spectral data, extract line parameters, and estimate physical properties such as column density, gas mass, and mass-loss rate.

## 📊 Features

- Fits Gaussian profiles to CO lines near their rest frequencies
- Calculates:
  - Peak flux density
  - Observed frequency and line width
  - Doppler velocity (v<sub>LSR</sub>)
  - Brightness temperature (T<sub>B</sub>)
  - Integrated intensity (∫T<sub>B</sub> dv)
  - Column density using a simplified LTE approximation
  - Gas mass and mass-loss rate assuming optically thin emission
