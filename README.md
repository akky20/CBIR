# Content-Based Image Retrieval (CBIR) Project

## Overview

This project implements a Content-Based Image Retrieval (CBIR) system using machine learning techniques. The code is designed to work with the OfficeHomeDataset, and it includes:

- Dataset importing and overview
- Analysis of image statistics (size, aspect ratio, etc.)
- Image classification using different models (SVM, Random Forest, KNN)
- Image retrieval based on a query image
  
## What is CBIR?

CBIR is a technology that allows users to search for images by visual content rather than relying on keywords or metadata. It involves extracting features from images and using these features to compare and retrieve similar images. The goal is to bridge the semantic gap between high-level concepts humans use to describe images and the low-level features extracted from images.

## Dataset

The project utilizes the [OfficeHomeDataset](https://www.hemanthdv.org/office/OfficeHome-Dataset.html), a diverse dataset containing images from office and home environments. To use the code, download the dataset from the official website and place it in the 'Dataset/OfficeHomeDataset_10072016' directory.

## Features Used

The CBIR system employs a combination of color histograms and Histogram of Oriented Gradients (HOG) features for image representation. These features capture both color distribution and shape information, providing a rich representation for image matching.

- **Color Histograms:** Describes the distribution of color intensities in an image.
- **HOG Features:** Captures the local gradient information in an image, useful for shape analysis.

## Requirements

- I use Python 3.9
- Required Python packages: pandas, scikit-learn, opencv-python, numpy, scikit-image, matplotlib

Install the required packages using:

```bash
pip install pandas scikit-learn opencv-python numpy scikit-image matplotlib


