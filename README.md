# 🖼️ Computer Vision Lab Series (OpenCV & Python)

This repository contains a collection of **Computer Vision lab experiments** implemented using **Python, OpenCV, NumPy, and Matplotlib**.  
Each notebook demonstrates fundamental image processing techniques such as **convolution, filtering, padding, noise reduction, edge detection, and histogram equalization** with clear visual results.

The main goal of this project is to **understand how low-level image processing operations work and how they affect images** step by step.

---

## 📁 Repository Structure

.
├── Computer Vision_01.ipynb
├── Computer Vision_02.ipynb
├── Computer Vision_03.ipynb
├── Computer Vision_04.ipynb
└── README.md



---

## 🧪 Experiments Covered

### ✅ 1. Image Loading & Preprocessing
- Load images using OpenCV  
- Convert between **BGR, RGB, and Grayscale**  
- Display images using Matplotlib  

---

### ✅ 2. Convolution Operations
- Apply **2D convolution** using custom kernels  
- Use:
  - Identity kernel  
  - Sharpening kernel  
  - Edge detection kernels  
- Apply convolution multiple times to observe cumulative effects  
- Analyze why some kernels (e.g., identity) do not change the image  

---

### ✅ 3. Image Padding Techniques
- Apply different padding methods:
  - **Constant padding**
  - **Reflect padding**
  - **Edge padding**
- Compare how padding changes image size and borders  

---

### ✅ 4. Noise & Blurring
- Add **Gaussian noise** to images  
- Reduce noise using:
  - Normal blur  
  - Gaussian blur with different **sigma values**  
- Observe the trade-off between smoothness and detail loss  

---

### ✅ 5. Edge Detection
- Apply:
  - **Laplacian filter** for edge detection  
  - **Vertical and Horizontal kernels** for directional edges  
- Perform repeated convolutions to strengthen edge responses  
- Compare vertical vs horizontal edge detection results  

---

### ✅ 6. Histogram Equalization
- Apply **Histogram Equalization** on grayscale images  
- Improve contrast in low-contrast images  
- Apply equalization multiple times and observe diminishing changes  

---

## 🛠️ Technologies Used

- Python 3  
- OpenCV (cv2)  
- NumPy  
- Matplotlib  
- Jupyter Notebook / Google Colab  

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
