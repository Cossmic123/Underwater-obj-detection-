## Underwater-obj-detection-

An implementation of image enhancement techniques for underwater object detection using MATLAB.
This repository contains a collection of MATLAB scripts and a Graphical User Interface (GUI) designed to enhance the quality of underwater images and serve as a preliminary step for underwater object detection tasks.

##  underwater-image-enhancement-matlab The Challenge

Underwater images are often plagued by quality degradation issues that make them challenging for both human analysis and computer vision algorithms. These problems include:
* **Color Distortion:** Water absorbs longer wavelengths of light (like reds and oranges) more than shorter wavelengths (blues and greens), resulting in a dominant blue/green color cast.
* **Low Contrast & Haze:** Light is scattered by particles and sediment in the water, which reduces contrast and creates a hazy, foggy appearance.
* **Poor Illumination:** The deeper the water, the less natural light is available, leading to dark and poorly lit images.

These issues make it difficult to identify and classify objects accurately. This project aims to mitigate these problems through various image processing techniques.

## Project Goal

The primary goal of this project is to implement and test several core image enhancement algorithms to restore and improve the visual quality of underwater photographs. By correcting color, improving contrast, and reducing noise, we can produce clearer images that are more suitable for subsequent tasks like object detection and classification.

## Key Features

This project implements the following image processing techniques:

* **Gamma Correction:** Adjusts the luminance of an image to correct for poor lighting conditions and enhance overall brightness.
* **Histogram Equalization:** Improves image contrast by redistributing the intensity values of the pixels across the entire dynamic range.
* **Frequency Domain Filtering (DCT):** Utilizes the Discrete Cosine Transform (DCT) for advanced filtering operations, potentially for noise reduction or feature enhancement.
* **Interactive GUI:** A user-friendly interface (`Filters.fig`) allows for easy application and visualization of different filters and enhancement techniques on sample images.
