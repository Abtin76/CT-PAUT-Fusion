### *Comparison and Integration of X-ray Computed Tomography and Phased Array Ultrasonic Testing for Enhanced Imaging Quality*

Welcome to the official repository for my Master’s Thesis. This project presents a novel approach to fusing X-ray CT and PAUT modalities to enhance image quality, defect detectability, and material evaluation in non-destructive testing (NDT).

---

## 🎯 Objectives

- Simulate **X-ray CT** using **aRTist**
- Simulate **Phased Array Ultrasonic Testing (PAUT)** using **Salvus**
- Reconstruct 3D images using **ASTRA toolbox** (CT) and **SAFT technique** (PAUT)
- Perform **volume registration and resampling** for alignment
- Apply image fusion techniques:
  - ✅ Maximum Fusion  
  - ✅ Weighted Fusion  
  - ✅ PCA Fusion  
  - ✅ Wavelet Fusion  
  - ✅ Multimodal Fusion with Denoising  
  - ✅ Laplacian Pyramid Fusion
- Implement a **hybrid reconstruction** algorithm using **SIRT**, integrating PAUT into CT reconstruction
- Evaluate image quality improvements through fusion and hybrid strategies

---

## 🛠 Tools & Technologies

| Tool           | Purpose                               |
|----------------|---------------------------------------|
| aRTist         | X-ray CT simulation                   |
| Salvus         | PAUT simulation                       |
| Astra Toolbox  | CT reconstruction                     |
| SAFT           | PAUT image reconstruction             |
| SIRT           | Iterative CT hybrid reconstruction    |
| Python         | Processing, visualization             |

> 📌 *Python libraries used:* NumPy, SciPy, Matplotlib, OpenCV, ASTRA, SimpleITK, PIL custom implementations for fusion methods

---


