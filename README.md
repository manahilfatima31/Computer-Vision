# Computer Vision Lab Tasks
This repository contains a collection of computer vision lab tasks completed as part of a coursework or project. These tasks cover various computer vision concepts and techniques, demonstrating proficiency in image processing, object detection, and related fields.

## Lab 01: Image Processing Basics

### Grocery List
A simple Python program to manage a grocery list, allowing users to add, remove items, and display the current list.

### Student Record System
Implementation of a student record system using a Python dictionary, allowing operations like adding students, updating grades, and displaying records.

### Image Processing with OpenCV
- Load and display images
- Convert images to grayscale
- Resize images using OpenCV
- Drawing basic shapes on images
- Apply Gaussian blur, crop, and manipulate images
- Add text to images
- Apply binary thresholding and rotation
- Blend two images, convert to grayscale, and apply histogram equalization
- Perform bitwise operations on binary images
- Convert image pixel values to a Pandas DataFrame and apply masks

## Lab 02: Exploring Datasets and Preprocessing

### Dataset Exploration
Explore a dataset containing images of pets categorized into four classes: Angry, Sad, Happy, and Others. Display the number of samples in each class.

### Loading and Preprocessing Dataset
Load the pet emotions dataset, resize images, normalize pixel values, and split the dataset into training and testing sets.

### Exploratory Data Analysis (EDA)
Perform EDA on the pet emotions dataset, displaying the distribution of class labels using a bar plot.

### Data Visualization
Display sample images from each class of the pet emotions dataset along with their labels.

### Summary Statistics
Calculate summary statistics for each class (Angry, Sad, Happy, Others) to understand the distribution of emotions in the dataset.

## Dataset Task - Group Work
Collection and basic operations on the "Common Objects-Within University" dataset.

## Lab 03: Medical Image Enhancement and Fusion

### Enhancing and Analyzing Medical Image Quality
Tasks include loading and displaying X-ray images, contrast enhancement, color mapping, color balance, color filtering, logarithmic and power-law transformations.

### Enhancing Multi-Modal Medical Image Fusion
Tasks include loading X-ray and MRI images, histogram equalization, color mapping, multi-modal weighted fusion, logarithmic and power-law transformations, and comparative analysis.

### Real-Time Video Enhancement and Analysis
Capture live video, apply various image enhancement operations in real-time, and display the original and enhanced video frames.

## Lab 04: Image Filtering and Fourier Transformations

### Linear Filtering
Implement Gaussian blur, Sobel edge detection, image sharpening, mean filter for noise reduction.

### Non-Linear Filtering
Develop median filter, max filter (dilation), min filter (erosion), bilateral filter, and adaptive median filter.

### Fourier Transformations
Calculate 1D and 2D Fourier Transforms, implement high-pass filter, and perform image compression using Fourier Transformation.

### Hybrid Images
Create hybrid images from two input images with different spatial frequencies, experiment with filter combinations, and analyze trade-offs.

## Lab 05: Medical Image Analysis and Feature Detection

### Medical Image Analysis for Tumor Detection
Discuss the application of edge detection as a feature extraction technique for tumor detection and propose an additional feature extraction technique.

### Harris Corner Detection
Implement Harris Corner Detection algorithm, detect corners in an image, and experiment with different threshold values.

### Corner Detection in Real-time Video
Implement corner detection in real-time using the Harris or Shi-Tomasi method on video frames.

### Corner Detection for Image Stitching
Implement Harris or Shi-Tomasi Corner Detection for image stitching by detecting corners in multiple images.

### Feature Detection and Matching using ORB Detector
Use ORB (Oriented FAST and Rotated BRIEF) detector and descriptor for feature detection and matching between two images.

## Lab 06: Image Segmentation

### Thresholding-Based Segmentation
Perform thresholding-based segmentation on a medical X-ray image to isolate a bone fracture.

### Region Growing Intensity-Based Segmentation
Perform region growing-based segmentation on a microscopic image of cells to identify and separate a specific cell.

### Watershed Segmentation
Use watershed segmentation to separate and count individual coins in an image of overlapping coins.

### Cluster-Based Segmentation
Perform cluster-based segmentation on an image of colorful flowers to separate different types of flowers based on color.

## Lab 07: Advanced Computer Vision Applications

### Computer Screen Detection
Implement screen detection in a computer lab using the Hough Line Transformation to identify boundaries of computer screens.

### Asset Tracking Using SIFT
Implement asset tracking in a computer lab using the Scale-Invariant Feature Transform (SIFT) to recognize and identify individual computer systems and components.

### Anomaly Detection Using Wavelet Transformation
Develop a system for real-time anomaly detection in sensor data using the wavelet transformation.

### Object Recognition (Using Video)
Implement object recognition using the SIFT algorithm on a set of test images.

### Panoramic Image Stitching
Create a panoramic image by stitching multiple overlapping images together using the SIFT algorithm.

### Lane Detection
Implement lane detection for an autonomous vehicle project using the Hough Line Transformation.

### Coins Detection and Counting
Implement coin detection and counting using the Hough Circle Transformation.

### Smart Security System
Implement boundary detection in a security system to detect unauthorized objects in a predefined zone in a real-time video stream.

## Lab 08: Deep Learning for Computer Vision

### Gender Classification
Develop a CNN model for gender classification using a dataset of human faces labeled with gender information.

### Animal Facial Expression Recognition
Create a CNN-based model for recognizing facial expressions in images of animals.

### Age Estimation
Build a system that estimates the age of a person in a video using a CNN-based architecture.

### Hand Gesture Recognition
Implement a system for real-time hand gesture recognition using CNN models.

## Lab 09: Image Classification with Pre-trained Models

### Image Classification using EfficientNet and ResNet50
Perform image classification using pre-trained models, EfficientNet and ResNet50, on a chosen dataset.

## Lab 10: Object Detection with YOLO and R-CNN

### Lab 10-1: YOLO Object Detection
Use YOLO (You Only Look Once) to detect home assets using a live web camera.

### Lab 10-II: Object Detection Using R-CNN
Implement object detection using Regional Convolutional Neural Networks (R-CNN) on a dataset of your choice.

## Lab 11: Image Classification with Vision Transformers

### Vision Transformer-based Image Classification
Classify images using Vision Transformers on a dataset of your choice.
