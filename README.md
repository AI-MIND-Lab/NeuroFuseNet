# Enhancing Generalization in Brain Tumor Diagnosis with Interpretable Squeeze-and-Excitation Enhanced ResNet-101

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.1.0-red?logo=pytorch)
![TorchVision](https://img.shields.io/badge/TorchVision-0.16.0-orange?logo=pytorch)
![OpenCV](https://img.shields.io/badge/OpenCV-4.8.1-green?logo=opencv)
![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.2-yellow?logo=matplotlib)

**Status:** Submitted to Scientific Reports  


## Overview

This repository contains the implementation and code for the paper titled *"Enhancing Generalization in Brain Tumor Diagnosis with Interpretable Squeeze-and-Excitation Enhanced ResNet-101"*. The work focuses on improving brain tumor classification using deep learning techniques, with an emphasis on interpretability and cross-dataset generalization.

Brain tumor diagnosis is critical for timely medical intervention, but models often struggle with generalization across diverse datasets. Our approach leverages a Squeeze-and-Excitation enhanced ResNet-101 architecture to achieve high accuracy while providing interpretable localization via Grad-CAM.

## Key Contributions

1. **Large-Scale Dataset Training:** Trained on a combined dataset of 7,023 images from Sartaj, Figshare, and BR35H datasets, achieving decent accuracy on brain tumor classification tasks.
2. **Interpretability with Grad-CAM:** Utilized Gradient-weighted Class Activation Mapping (Grad-CAM) to localize tumor regions, enhancing model explainability for clinical applications.
3. **Cross-Dataset Evaluation:** Evaluated the model on two independent datasets, including one region-specific dataset, demonstrating robust generalization and good performance.
4. **Superior Performance:** Surpassed reviewed literature in terms of accuracy and generalization, setting a new benchmark for brain tumor diagnosis models.

## Requirements

- **Python Version:** 3.10
- **PyTorch Version:** 2.1.0
- **TorchVision Version:** 0.16.0
- **OpenCV Version:** 4.8.1
- **NumPy Version:** 1.26.4
- **Matplotlib Version:** 3.7.2
