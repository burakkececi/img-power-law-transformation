# 🤳 Power Law Transformation on Gray Scale Image

## 📝 Description

This work explores the application of Power Law Transformation on gray scale images. The Power Law Transformation is a method commonly used in image processing to enhance the contrast of an image by adjusting pixel intensities. This technique is particularly useful for improving the visibility of details in both bright and dark regions of an image.

**Table of Contents**
- [Introduction](#introduction) 
- [Understanding Power Law Transformation](#understanding-power-law-transformation)
- [Implementing Power Law Transformation in Python](#implementing-power-law-transformation-in-python) 

### Introduction

The Power Law Transformation is a mathematical technique that alters the intensity values of pixels in an image. It follows the formula:

T(r) = c * r^γ

where:
- T(r) is the transformed intensity,
- r is the original intensity,
- c is a constant,
- γ is the gamma parameter.

### Understanding Power Law Transformation

The transformation is a nonlinear process that adjusts pixel intensities to enhance image features. Higher values of \( \gamma \) (> 1) increase the contrast of bright regions, while lower values (< 1) enhance dark regions. Understanding the impact of \( \gamma \) is crucial in optimizing the transformation for specific image characteristics.

### Implementing Power Law Transformation in Python

To apply Power Law Transformation to gray scale images using Python, the following steps will be taken:

1. Read and load the gray scale image.
2. Normalize pixel intensities.
3. Apply the Power Law Transformation using the given formula.
4. Adjust parameters such as γ to observe the effects.
5. Visualize and compare the original and transformed images.

By implementing these steps, we aim to demonstrate the effectiveness of Power Law Transformation in enhancing the contrast of gray scale images and provide insights into parameter tuning for optimal results.

