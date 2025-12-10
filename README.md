# Enhancing Generalization in Brain Tumor Diagnosis with Interpretable Squeeze-and-Excitation Enhanced ResNet-101

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.1.0-red?logo=pytorch)
![TorchVision](https://img.shields.io/badge/TorchVision-0.16.0-orange?logo=pytorch)
![OpenCV](https://img.shields.io/badge/OpenCV-4.8.1-green?logo=opencv)
![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.2-yellow?logo=matplotlib)

![Status](status-badge.svg)

## Overview

This repository contains the implementation and code for the paper titled:

**_"Enhancing Generalization in Brain Tumor Diagnosis with Interpretable Squeeze-and-Excitation Enhanced ResNet-101"_**

The work focuses on improving brain tumor classification using deep learning techniques, with an emphasis on **interpretability** and **cross-dataset generalization**.

Brain tumor diagnosis is critical for timely medical intervention, but models often struggle with generalization across diverse datasets. Our approach leverages a **Squeeze-and-Excitation enhanced ResNet-101** architecture to achieve high accuracy while providing interpretable localization via **Grad-CAM**.

---

## ✨ Key Contributions

- 🏋️ **Large-Scale Dataset Training:** Trained on a combined dataset of **7,023 images** from Sartaj, Figshare, and BR35H datasets.  
- 🔍 **Interpretability with Grad-CAM:** Localizes tumor regions, enhancing model explainability for clinical use.  
- 🌐 **Cross-Dataset Evaluation:** Evaluated on two independent datasets, demonstrating robust generalization.  
- 🥇 **Superior Performance:** Surpassed previous literature in accuracy and generalization, setting a new benchmark.

---

## ⚡ Requirements & Training Platform

| Package / Platform    | Version / Details | Badge |
|----------------------|-----------------|-------|
| **Python**           | 3.10            | ![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) |
| **PyTorch**          | 2.1.0           | ![PyTorch](https://img.shields.io/badge/PyTorch-2.1.0-red?logo=pytorch) |
| **TorchVision**      | 0.16.0          | ![TorchVision](https://img.shields.io/badge/TorchVision-0.16.0-orange?logo=pytorch) |
| **OpenCV**           | 4.8.1           | ![OpenCV](https://img.shields.io/badge/OpenCV-4.8.1-green?logo=opencv) |
| **NumPy**            | 1.26.4          | ![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blue?logo=numpy) |
| **Matplotlib**       | 3.7.2           | ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.2-yellow?logo=matplotlib) |
| **Training Platform**| Kaggle Notebook | ![Kaggle](https://img.shields.io/badge/Kaggle-P100_GPU-blue?logo=kaggle) |
| **RAM**              | 29 GiB          | ![RAM](https://img.shields.io/badge/RAM-29GiB-lightgrey) |


## 🖼️ Workflow Diagram
<!-- Adjustable workflow diagram -->

![Workflow Diagram](workflow.png)


*Figure: Complete workflow of the brain tumor diagnosis pipeline, from dataset preprocessing to interpretable SE-ResNet-101 prediction and Grad-CAM visualization.*
