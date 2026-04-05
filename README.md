# Image-compression-using-PCA
Implemented image compression using PCA by reducing dimensionality and reconstructing images while retaining up to 99% variance.
📷 Image Compression using PCA (Principal Component Analysis)
📌 Project Overview

This project demonstrates image compression using Principal Component Analysis (PCA).
The main goal is to reduce the size of an image while retaining most of the important visual information by reducing the number of principal components.

PCA reduces the dimensionality of image data and reconstructs the image using fewer components, thereby achieving compression.

📌Concept Used

Principal Component Analysis (PCA) is a dimensionality reduction technique that:

Converts correlated variables into a set of uncorrelated variables (principal components)
Retains maximum variance (information) with fewer components
Used here for image compression

📂 Project Workflow
1.Load the image
2.Check if the image is grayscale or RGB
3.Split RGB channels
4.Apply PCA on each channel
5.Calculate cumulative explained variance
6.Choose number of components for:
95% variance
98% variance
99% variance
7.Reconstruct the compressed image
8.Display compressed images


📌Results

| Variance Retained | Number of Components |
| ----------------- | -------------------- |
| 95%               | 41                   |
| 98%               | 63                   |
| 99%               | 80                   |

The reconstructed images show that even with fewer components, the image quality remains visually similar to the original image.
