# Image Super-Resolution via Least Squares and Robust LOESS (RLOESS)

This project was completed as part of the *Introduction to Scientific Computing* course at National Taiwan Normal University (NTNU), and later presented at the **Taiwan Society for Industrial and Applied Mathematics (TWSIAM)** seminar.

## Overview
Our goal was to reconstruct high-resolution images from sparse or downsampled data using mathematical modeling.  
We first implemented a **quadratic least-squares (LS)** fitting model to approximate pixel intensity surfaces, then extended it using a **Robust Locally Estimated Scatterplot Smoothing (RLOESS)** filter to improve sharpness near edges.  
RLOESS was generalized from a 1D to a 2D local regression by redefining its kernel weighting function, reducing edge instability and noise.

## Results
- The proposed RLOESS-enhanced model achieved clearer structural recovery and a higher PSNR (~29 dB) compared to bicubic and pure LS interpolation.
- Presented results and methodology at the 2024 TWSIAM seminar in Taiwan.

## Repository Contents
- `Lu_ShaoChun_TWSIAM_Poster.pdf` — Poster presented at TWSIAM 2024.  
- `Lu_ShaoChun_SciComp_Report.pdf` — Full written report detailing methodology and numerical results.  
- `sample_input.png` — Example of low-resolution input image.  
- `sample_output_LS.png` — Super-resolved image using Least Squares model.  
- `sample_output_RLOESS.png` — Final output using Robust LOESS enhancement.

*(All figures shown are for educational purposes.)*
