# CVL_Assignment01 - Image Enhancement

This repository contains the implementation of **Image Enhancement** techniques for the Advanced Computer Vision course.

The project applies several image enhancement methods to images with different conditions, including dark images, low-contrast images, blurred images, overexposed images, and images affected by salt-and-pepper noise.

## Methods

The enhancement techniques implemented in this project include:

- Gamma Transformation
- Log Transformation
- Contrast Stretching
- Laplacian Sharpening
- Median Filter
- Histogram Equalization

Most images are converted into grayscale and processed based on pixel intensity values in the range of 0–255.

## Evaluation

The results are evaluated using **PSNR (Peak Signal-to-Noise Ratio)** as an additional metric to measure how much the enhanced image changes compared to the original image.

## Files

- `CVL_Assignment01.ipynb` — main implementation notebook
- `dataset/` — images used for the image enhancement experiments
- `Laporan_CVL_Assignment01_Dennita.pdf` — assignment report containing the implementation analysis and results

## Summary

The experiment shows that different image problems require different enhancement methods:

- Gamma Transformation can enhance dark and overexposed images.
- Contrast Stretching and Histogram Equalization improve image contrast.
- Laplacian Sharpening enhances edges in blurred images.
- Median Filter reduces salt-and-pepper noise.

The enhancement method should be selected based on the characteristics and condition of the input image.

## Author

**Dennita Noor Febianty**
