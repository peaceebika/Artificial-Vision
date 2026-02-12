# HW2 – Image Filtering, Edge Detection, and Pyramids using OpenCV

## Course Project: (OpenCV)

This repository contains my **HW2 implementation** using **OpenCV in Python**.  
The goal of this homework is to understand **image filtering**, **edge detection**, **common image transformations**, and **image pyramids**, and to see how they are implemented in OpenCV.

All experiments were performed using a **pepper image** as the input image.

---

## Objectives of the Homework

The main objectives of this assignment are:

- To understand **different image filters** and how they work
- To learn **when and why** each filter is used
- To explore **edge detection operators**
- To apply **common image transformations**
- To understand **Gaussian and Laplacian pyramids**
- To connect theory directly to **OpenCV functions**

---

## Tools and Libraries Used

- Python 3
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

---

## Image Used

A **red bell pepper image** was used for all experiments because:
- It has clear edges
- It contains smooth regions and sharp boundaries
- It is ideal for demonstrating filters and edge detection

---

## Filters Implemented

### 1. Gaussian Blur
```python
cv2.GaussianBlur()
```
### 2. Median Blur
```python
cv2.medianBlur()
```
## Edge Detection Operators

### 1. Sobel Operator
```python
cv2.Sobel()
```
### 2. Canny Edge Detector
```python
cv2.Canny()
```

## Image Pyramids

### 1. Gaussian Pyramid
```python
cv2.pyrDown()
cv2.pyrUp()
```
### Laplacian Pyramid
```python
cv2.subtract()
```

