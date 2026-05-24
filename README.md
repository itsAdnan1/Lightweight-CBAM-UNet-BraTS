Brain Tumor MRI Segmentation Using Lightweight CBAM U-Net
This repository contains the PyTorch implementation of the Lightweight CBAM U-Net for multi-class brain tumor segmentation, utilizing a curated subset of the BraTS 2021 dataset.

Highlights
Lightweight Architecture: Highly efficient design with exactly 487,234 trainable parameters (approx. 0.487M).

Attention Mechanism: Integrated Convolutional Block Attention Module (CBAM) for precise channel and spatial feature extraction.

Hybrid Loss: Utilizes a custom DiceBCELoss to effectively combat extreme medical image class imbalance.

Competitive Performance:

Whole Tumor (WT): 93.3%

Tumor Core (TC): 91.0%

Enhancing Tumor (ET): 86.3%

Clinical Efficiency: Achieves an inference time of approximately 12 ms per image, demonstrating strong potential for real-time diagnostic assistance.

Usage
The code is provided as a Jupyter Notebook (CBAM_UNet_BraTS.ipynb) and was trained using an accelerated GPU environment. It includes the full pipeline:

Strict data filtering (selecting informative 2D axial slices, index 75).

Volumetric Z-score normalization.

Lightweight architecture definition with integrated CBAM blocks.

5-fold cross-validation training process.

Comprehensive quantitative and qualitative evaluation.
