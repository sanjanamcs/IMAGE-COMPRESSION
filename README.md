# IMAGE-COMPRESSION

# Project Title: 

# Image Compression using Discrete Fourier Transform (DFT) and Inverse DFT (IDFT)

# Project Description:


## Introduction:

Image compression plays a crucial role in various applications, including storage, transmission, and efficient processing of digital images. This project aims to explore image compression techniques using the Discrete Fourier Transform (DFT) and its inverse (IDFT). DFT transforms images from the spatial domain to the frequency domain, allowing the selective removal or quantization of high-frequency components, thus achieving compression.

## Project Objectives:

- Implement a DFT and IDFT algorithm to transform images between the spatial and frequency domains.
- Analyze the frequency domain representation of images and understand the role of high and low-frequency components.
- Develop compression techniques using DFT, such as thresholding and quantization.
- Reconstruct the compressed image in the spatial domain using IDFT.
- Evaluate the quality and compression ratio of the resulting images.

## Methodology:

- Load an input image that serves as the source for compression.
- Apply DFT to convert the image to the frequency domain, creating a complex representation of amplitude and phase.
- Analyze the frequency domain image and identify high-frequency components.
- Apply compression techniques to reduce data size, such as setting small magnitude coefficients to zero (thresholding) or quantizing values.
- Reconstruct the compressed image by applying IDFT.
- Evaluate the quality of the compressed image using image quality metrics.

## Expected Results:


- The project will produce a compressed image with reduced data size compared to the original.
- Image quality will be evaluated, and the trade-off between compression ratio and image quality will be analyzed.
- You will gain a deeper understanding of the role of the DFT and IDFT in image processing and compression.

##  Tools and Technologies:

- Python (or a preferred programming language for image processing)
- Image processing libraries (e.g., OpenCV)
- Numerical libraries (e.g., NumPy)
- Evaluation metrics for image quality assessment (e.g., PSNR, SSIM)

## Conclusion:

- Image compression using DFT and IDFT offers insights into fundamental image processing techniques and allows for hands-on exploration of compression methods. The project will demonstrate how DFT-based compression can be used to achieve data reduction while understanding the trade-offs involved in image quality.
