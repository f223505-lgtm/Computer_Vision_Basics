# Computer_Vision_Basics
all type of files related to Computer vision assignment 
# Computer Vision Assignment 01
## Introduction to Computer Vision

**Student Name:** Ali Hassan Irfan  
**Course:** Introduction to Computer Vision  
**Assignment:** Image Enhancement, Filtering & Edge Detection  

---

# 📌 Project Overview

This project implements fundamental computer vision algorithms from scratch using NumPy. 

The assignment covers:

- Histogram Equalization
- Contrast Stretching
- Gamma Correction
- 2D Convolution
- Gaussian Filtering
- Separable Gaussian Filtering
- Gradient Operators (Sobel, Prewitt, Roberts, Central Difference)
- Canny Edge Detection
- Edge Detection Comparison

OpenCV is only used for comparison purposes where required.

---

# ⚙️ How to Set Up the Environment

## 1️⃣ Install Python (if not installed)

Download Python 3.9+ from:
https://www.python.org

---

## 2️⃣ Create Virtual Environment (Recommended)

Activate:

Windows:

Mac/Linux:

---

## 3️⃣ Install Required Libraries

Run:


OR manually install:

---

# ▶️ How to Run the Project

## Option 1: Using Jupyter Notebook (Recommended)

Inside project folder:

---

## Option 2: VS Code

Open folder in VS Code  
Open notebook file  
Click **Run All**

---

# 🖼 Description of Test Images Used

The following test images were used in this assignment:

### 1️⃣ lena.png
- Standard grayscale test image
- Used for enhancement and filtering experiments

### 2️⃣ dark.jpg
- Underexposed image
- Used to test histogram equalization and gamma correction

### 3️⃣ low_contrast.jpg
- Low contrast image
- Used for contrast stretching comparison

### 4️⃣ cameraman.png
- Used for edge detection and filtering evaluation

All images are placed inside:

---

# 📊 Output Description

For each question:

- Output images are displayed after each section
- Histograms are plotted for enhancement tasks
- Execution time is measured for convolution
- Comparison with OpenCV is provided where required

---

# 🧠 Assumptions Made

1. All images are grayscale (single channel).
2. Pixel intensity range is assumed to be 0–255.
3. Input images are correctly placed inside the `test_images` folder.
4. OpenCV is used only for comparison (as allowed in assignment).
5. Default threshold values were selected experimentally for Canny.


