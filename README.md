# 🚀 Image Segmentation & Thresholding - Assignment 2

This repository contains the solution for **Take Home Assignment 2** of the _Computer Vision and Image Processing (EC7212)_.

---

## ✨ Assignment Details

- **Name:** Perera G.A.L.S.
- **Reg No:** EG/2020/4111
- **Semester:** 07
- **Course:** EC7212 – Computer Vision and Image Processing
- **Assignment:** Take Home Assignment 2

---

## 🎯 Contents

### ✅ Question 1 – Otsu’s Thresholding
- A synthetic image with two objects (one circle, one rectangle) and three distinct pixel intensities (one for each object and one for the background) was generated using NumPy.
- Gaussian noise (mean = 0, standard deviation = 20) was added to the synthetic image.
- Otsu’s thresholding algorithm was applied using both OpenCV's built-in `cv2.THRESH_OTSU` method and `scikit-image`'s `filters.threshold_otsu`.
- Outputs: Original image, noisy image, and the thresholded binary images from both OpenCV and scikit-image.

### ✅ Question 2 – Region Growing Segmentation
- A grayscale image was loaded using OpenCV.
- Seed points were manually selected within the region of interest.
- A custom region growing algorithm was implemented to segment regions based on the similarity of pixel intensities to the initial seed pixel values.
- The final output is a binary mask showcasing the segmented region.

---

## 🛠️ Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib (for visualization)
- Scikit-image (`skimage`)

You can install the dependencies via:

```bash
pip install opencv-python numpy matplotlib scikit-image