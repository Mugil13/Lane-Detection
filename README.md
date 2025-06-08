# Lane-Detection

This repository contains two ipynb files each serving its own purpose. The lane detection problem is implemented as a part of my coursework for the course titled "Computer Vision".

---

## Description

This project explores lane detection for self-driving vehicles using:

1. **Traditional CV Techniques**  
   - Edge detection (Canny, Sobel, Scharr)
   - Thresholding & Morphology
   - Color-based masking (HSV/HLS)
   - Texture features (GLCM)
   - HOG (Histogram of Oriented Gradients)
   - Hough Line Transform

2. **Deep Learning (E-Net CNN Architecture)**  
   - Built using PyTorch
   - Custom dataset loader for TuSimple dataset
   - Encoder-decoder segmentation network
   - Feature visualization using Grad-CAM

---

## Dataset

Both notebooks use the TuSimple Lane Detection dataset.
Download it from Kaggle TuSimple Dataset.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Mugil13/Lane-Detection.git
cd Lane-Detection
pip install -r requirements.txt
```

## Visual Outputs

Both notebooks include inline visualizations such as:

1. Edge maps
2. Segmentation masks
3. HOG features
4. Activation maps & Grad-CAM overlays

## Author
Mugilkrishna D U

## License
MIT License. This project is licensed for academic and educational use.
