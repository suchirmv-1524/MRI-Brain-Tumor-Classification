<h1 align="center">Brain Tumor Classification Using MRI Images</h1>

## About
This project aims to facilitate the early detection and classification of brain tumors using Magnetic Resonance Imaging (MRI) scans. The dataset consists of 7023 MRI images of human brains, which are classified into four classes: glioma, meningioma, no tumor, and pituitary.

## Methods
We employ Convolutional Neural Network (CNN) based models for detecting, classifying, and locating brain tumors in MRI scans. The dataset is utilized for multi-task classification, involving tumor detection, classification by grade and type, and identification of tumor location.

## Dataset Description
The dataset is a combination of three sources:
1. Figshare
2. SARTAJ dataset
3. Br35H
* Glioma Issue: It has been observed that the glioma class images in the SARTAJ dataset were not categorized correctly. To address this issue, images from the SARTAJ dataset were replaced with those from the figshare site.
* Image Sizes: Note that the sizes of the images in the dataset vary. Pre-processing steps include resizing images to a desired size after removing extra margins to enhance model accuracy.

## Usage
* Pre-processing: Ensure to preprocess images by resizing them to the desired size and removing extra margins.
* Model Training: Train CNN-based models for multi-task classification and tumor detection.
* Evaluation: Evaluate model performance on classification accuracy and tumor detection metrics.

