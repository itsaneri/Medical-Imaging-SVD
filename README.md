# Medical-Imaging-SVD
Enhancing Medical Imaging with SVD: Noise Reduction, Compression, and Lung Segmentation Evaluation


This project explores **Singular Value Decomposition (SVD)** for **medical image denoising, compression, and preprocessing** to improve **lung segmentation** performance on chest X-rays.  

We evaluate how SVD helps reduce noise, compress images without losing key features, and enhance segmentation results using a **U-Net architecture**.

---

## 🚀 Features
- Add Gaussian noise to medical X-ray images (simulate real-world conditions).
- Apply **SVD-based denoising** (retain only top-k singular values).
- Perform **SVD compression** (reduce storage size while preserving features).
- Train and test a **U-Net** model for lung segmentation.
- Evaluate with metrics: **MSE, PSNR, SSIM, Dice, Jaccard**.

---
## 📊 Dataset
We use the **Chest X-Ray Lungs Segmentation** dataset from Kaggle.  
🔗 [Dataset Link](https://www.kaggle.com/datasets/iamtapendu/chest-x-ray-lungs-segmentation/data)  

Dataset contains:
- 704 chest X-ray images (grayscale).  
- 704 corresponding lung masks (binary).  
- Metadata (age, gender, TB label, etc.).  

⚠️ Dataset not included in this repo due to size. Please download it separately.

---

## 📈 Results
- **Noisy images** → poor segmentation (Dice ~56%).  
- **Denoised images** → improved segmentation (Dice ~76%).  
- **Compressed images** → best performance (Dice ~97%).  
- SVD compression produced **highest PSNR & SSIM, lowest MSE**.  
---

## 🤝 Contributors
- Ritik Raut  
- Amitesh Sahoo  
- Charani Sri Veerla  
- Asmita Pal  
- Aneri Soni  

---

