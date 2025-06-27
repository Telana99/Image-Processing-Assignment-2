# Image Processing Tasks – Gaussian Noise, Otsu Thresholding, and Region Growing

This project contains two basic image processing implementations using Python and `skimage`. It demonstrates image segmentation techniques through thresholding and region-based analysis.

## 🔍 Task 1: Gaussian Noise + Otsu’s Thresholding

### Objective:
Create a synthetic image with two distinct objects and apply Otsu’s thresholding after adding Gaussian noise.

### Method:
- Generate a 100x100 grayscale image with pixel values: 0 (background), 85 (object 1), and 170 (object 2).
- Add Gaussian noise (`var=0.01`).
- Apply Otsu’s algorithm to segment the image automatically.

## 🌱 Task 2: Region Growing Segmentation

### Objective:
Segment an object by starting from a seed point and growing the region based on pixel similarity.

### Method:
- Select a seed pixel inside one of the objects.
- Recursively include neighboring pixels if their values are within a defined threshold (`thresh=30`).
- Display the segmented region as an overlay on the noisy image.

## 📦 Requirements

Install the necessary Python packages:
```bash
pip install numpy matplotlib scikit-image
