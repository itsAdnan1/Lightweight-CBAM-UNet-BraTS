# 🧠 Brain Tumor MRI Segmentation Using Lightweight CBAM U-Net

PyTorch implementation of a lightweight attention-based U-Net for multi-class brain tumor MRI segmentation using a curated subset of the BraTS 2021 dataset.

---

## ✨ Highlights

- ⚡ Lightweight architecture with only **487,234 trainable parameters (~0.487M)**
- 🎯 Integrated **CBAM attention mechanism**
- 🧪 Custom **Dice + BCE hybrid loss**
- 🚀 Fast inference time (~12 ms/image)
- 📊 Competitive segmentation performance:

| Region | Dice Score |
|--------|------------|
| Whole Tumor (WT) | **93.3%** |
| Tumor Core (TC) | **91.0%** |
| Enhancing Tumor (ET) | **86.3%** |

---

## 🛠️ Features

- Informative 2D axial slice selection
- Volumetric Z-score normalization
- Lightweight CBAM U-Net architecture
- 5-Fold Cross-Validation
- Quantitative & qualitative evaluation

---

## 📂 Implementation

The project is provided as a Jupyter Notebook:

```bash
CBAM_UNet_BraTS.ipynb
