This README covers a series of Computer Vision laboratory tasks and projects, ranging from foundational image manipulation to advanced deep learning for medical diagnosis.

---

# 👁️ Computer Vision & Deep Learning Portfolio

This repository contains a comprehensive collection of Computer Vision projects and laboratory tasks, progressing from fundamental pixel manipulations to state-of-the-art deep learning architectures.

## 📚 Table of Contents

* [Fundamental Image Processing](https://www.google.com/search?q=%23fundamental-image-processing)
* [Filtering & Spatial Operations](https://www.google.com/search?q=%23filtering--spatial-operations)
* [Feature Detection & Gradients](https://www.google.com/search?q=%23feature-detection--gradients)
* [Deep Learning for Medical Diagnosis](https://www.google.com/search?q=%23deep-learning-for-medical-diagnosis)

---

## 🛠️ Project Breakdown

### 1. Fundamental Image Processing 🖼️

**File:** `Computer Vision_01.ipynb`

* **Focus:** Manual image creation and visualization using `NumPy` and `Matplotlib`.
* **Key Tasks:** * Generating grayscale images from raw arrays.
* Understanding coordinate systems and intensity values (0-255).
* Visualization of custom patterns using `plt.imshow`.



### 2. Filtering & Spatial Operations 🔍

**File:** `Computer Vision_02.ipynb`

* **Focus:** Implementation of 2D convolutions and kernel operations.
* **Key Tasks:**
* **Grayscale Transformation:** Converting BGR images to grayscale using OpenCV.
* **Manual Convolution:** Applying custom kernels (e.g., identity and simple shift kernels) to images using `cv2.filter2D`.
* **Multi-stage Filtering:** Analyzing the effect of sequential convolutions on image data.



### 3. Feature Detection & Gradients 📐

**File:** `Computer Vision_03.ipynb`

* **Focus:** Identifying structural elements within images using mathematical operators.
* **Key Tasks:**
* **Gradient Calculation:** Computing X/Y gradients and overall magnitude using Sobel operators.
* **Harris Corner Detection:** Implementing and tuning the Harris Corner algorithm to find interest points in complex images (like pizza or cake).
* **Visualization:** Overlaying detected corners on gradient magnitudes to evaluate detector performance.



### 4. Deep Learning for Medical Diagnosis 🩺

**File:** `Computer Vision_04.ipynb`

* **Focus:** Classification of skin cancer using the HAM10000 dataset.
* **Key Tasks:**
* **Architectural Comparison:** Training and evaluating **VGG16**, **ResNet50**, and **InceptionV3**.
* **Performance Analysis:** Comparing training vs. validation loss/accuracy across models.
* **Conclusion:** Determined that InceptionV3 performs best for this medical dataset due to its multi-scale convolutional blocks that capture both fine lesion textures and large structural patterns.



---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following libraries installed:

```bash
pip install numpy matplotlib opencv-python tensorflow keras

```

### Usage

1. Clone the repository.
2. Open any `.ipynb` file in Google Colab or Jupyter Notebook.
3. Update the `cv2.imread()` paths to point to your local images.
4. Run all cells to see the results and visualizations.

---

## 👤 Author

* **Name:** Md. Sybeen Abrar Prohor
