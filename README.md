

# 🧠 Enhancing Generalization in Brain Tumor Diagnosis with Interpretable Squeeze-and-Excitation Enhanced ResNet-101
![Status](status-badge.svg)
### 👨‍💻 Authors & Affiliations

| Name | Affiliation | Email |
|------|------------|-------|
| Md. Ehsanul Haque | ![EWU](https://img.shields.io/badge/East_West_University_Dhaka_1212_Bangladesh-blue) | ![Email](https://img.shields.io/badge/2021--3--60--018@std.ewubd.edu-grey) |
| Md. Nurul Absur | ![CUNY](https://img.shields.io/badge/Department_of_Computer_Science_City_University_of_New_York_New_York_USA-red) | ![Email](https://img.shields.io/badge/mabsur@gradcenter.cuny.edu-grey) |
| Pegah Khosravi* | ![UCF1](https://img.shields.io/badge/Department_of_Clinical_Sciences_College_of_Medicine_University_of_Central_Florida_Orlando_FL_USA-orange) <br> ![UCF2](https://img.shields.io/badge/Institute_for_Artificial_Intelligence_Department_of_Computer_Science_University_of_Central_Florida_Orlando_FL_USA-orange) | ![Email](https://img.shields.io/badge/pegah.khosravi@ucf.edu-grey) |

\* **Corresponding Author**


\
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.1.0-red?logo=pytorch)
![TorchVision](https://img.shields.io/badge/TorchVision-0.16.0-orange?logo=pytorch)
![OpenCV](https://img.shields.io/badge/OpenCV-4.8.1-green?logo=opencv)
![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.2-yellow?logo=matplotlib)
![Open Access](https://img.shields.io/badge/Open_Access-Yes-brightgreen)




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
## 🗂️ Dataset Image Distribution Across all classes
## 🗂️ Class-wise Image Counts

| ![Tumor Class](https://img.shields.io/badge/Tumor_Class-blue) | ![Main Dataset](https://img.shields.io/badge/Main_Dataset-blue) | ![PMRAM Dataset](https://img.shields.io/badge/PMRAM_Cross_Testing-red) | ![Merged Dataset](https://img.shields.io/badge/Merged_Cross_Testing-green) |
|--------------------------------------------------------------|-----------------|-----------------|-----------------|
| ![Glioma](https://img.shields.io/badge/Glioma-blue)         | ![1621](https://img.shields.io/badge/1621-blue) | ![373](https://img.shields.io/badge/373-red)  | ![3538](https://img.shields.io/badge/3538-green) |
| ![Meningioma](https://img.shields.io/badge/Meningioma-blue) | ![1645](https://img.shields.io/badge/1645-blue) | ![363](https://img.shields.io/badge/363-red)  | ![3818](https://img.shields.io/badge/3818-green) |
| ![No Tumor](https://img.shields.io/badge/No_Tumor-blue)     | ![2000](https://img.shields.io/badge/2000-blue) | ![396](https://img.shields.io/badge/396-red)  | ![3175](https://img.shields.io/badge/3175-green) |
| ![Pituitary](https://img.shields.io/badge/Pituitary-blue)   | ![1757](https://img.shields.io/badge/1757-blue) | ![373](https://img.shields.io/badge/373-red)  | ![3755](https://img.shields.io/badge/3755-green) |

## 📂 Datasets & Sources

| Dataset | Source  |
|---------|-----------------|
| Main Experiment Dataset | [![Kaggle](https://img.shields.io/badge/Kaggle-Download-blue?logo=kaggle)](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) |
| PMRAM Dataset (Cross-Dataset Validation) | [![Mendeley](https://img.shields.io/badge/Mendeley-Download-red?logo=mendeley)](https://data.mendeley.com/datasets/m7w55sw88b/1) |
| Merged Dataset (Cross-Dataset Validation) | [![Kaggle](https://img.shields.io/badge/Kaggle-Download-blue?logo=kaggle)](https://www.kaggle.com/datasets/sohansakib75/brainucfcdv) |
| Components of Custom Merged Dataset: Pradeep Dataset | [![Kaggle](https://img.shields.io/badge/Kaggle-Download-blue?logo=kaggle)](https://www.kaggle.com/datasets/pradeep2665/brain-mri) |
| Components of Custom Merged Dataset: Masoud dataset | [![Kaggle](https://img.shields.io/badge/Kaggle-Download-blue?logo=kaggle)](https://www.kaggle.com/datasets/mohamedmetwalysherif/braintumordataset/data?select=Training) |

