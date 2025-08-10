# Maggie
Image compression project of a picture of my dog, Maggie, using Truncated Singular Value Decomposition and Total Variance Denoising.

# Image Compression and Denoising with SVD and Total Variation Denoising

This project demonstrates image compression using Truncated Singular Value Decomposition (TSVD) and image enhancement using Total Variation Denoising (TVD) in Python. The workflow includes loading an image, compressing it with SVD, visualizing the effect of truncation, and denoising the compressed image.

## Features

- **Image Loading and Grayscale Conversion:**  
  Loads an image and converts it to grayscale for processing.

- **Singular Value Decomposition (SVD):**  
  Decomposes the image matrix and visualizes the singular values and their cumulative information.

- **Image Compression:**  
  Reconstructs the image using a limited number of singular values, showing the trade-off between compression and quality.

- **Storage Calculation:**  
  Calculates and displays the storage required for each compressed image as a percentage of the original.

- **Total Variation Denoising:**  
  Applies TV denoising to the compressed image to enhance quality while maintaining compression.

