# Fish Species Classification & Dataset Analysis 🐟📸

This repository contains a PyTorch-based Deep Learning workflow designed for classifying fish species under varying background environments and lighting conditions. The pipeline includes data metadata analysis, subset visualization, dataset splitting, transfer learning with ResNet50, and evaluation metrics.

---

## 📌 Features
* **Metadata Analysis**: Exploratory Data Analysis (EDA) on dataset metadata (`filename`, `fish_type`, `background`, `lighting`).
* **Visual Data Quality Check**: Dynamic sample visualization across different fish species, background surfaces, and lighting settings.
* **Deep Learning Architecture**: Utilizes **ResNet50** fine-tuning with PyTorch.
* **GPU Acceleration**: Built-in CUDA support for faster training and inference.
* **Reproducible Setup**: Pre-configured paths for dataset structures and output directory handling.

---

## 📁 Dataset Structure

The dataset contains **1,536 images** categorized across **4 fish types**, **8 background types**, and **4 lighting conditions**.

```text
ML_Lab/
├── dataset/
│   ├── metadata.csv
│   ├── splits/
│   │   ├── train.csv
│   │   └── val.csv
│   └── raw/
│       ├── chikka/
│       ├── fara/
│       ├── guraila/
│       └── jati/
├── models/
│   └── resnet50_best.pth
└── outputs/
    └── plots/
