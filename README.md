# Brain Tumor MRI Segmentation Using Lightweight CBAM U-Net

This repository contains the PyTorch implementation of the **Lightweight CBAM U-Net** for multi-class brain tumor segmentation, utilizing the BraTS 2021 dataset.

## Highlights
* **Lightweight Architecture:** Less than 0.5 million parameters.
* **Attention Mechanism:** Integrated Convolutional Block Attention Module (CBAM) for precise feature extraction.
* **Hybrid Loss:** Utilizes a custom `DiceBCELoss` to effectively combat extreme medical image class imbalance.
* **State-of-the-Art (SOTA) Performance:** * Whole Tumor (WT): **93.3%**
  * Tumor Core (TC): **91.0%**
  * Enhancing Tumor (ET): **86.3%**

## Usage
The code is provided as a Jupyter Notebook (`CBAM_UNet_BraTS.ipynb`) and was trained using Kaggle's GPU environment. It includes the full pipeline: data filtering, Z-score normalization, architecture definition, 5-fold cross-validation training, and qualitative visual evaluation.
