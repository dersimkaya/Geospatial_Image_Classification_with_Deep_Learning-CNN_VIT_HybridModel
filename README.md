# Geospatial Image Classification with Deep Learning  
## End‑to‑End Satellite Image Analysis using CNNs and Vision Transformers

This project provides an end‑to‑end experience in applying deep learning techniques to **geospatial image classification** using satellite data. It focuses on solving a domain‑specific challenge in remote sensing: **predicting agricultural vs. non‑agricultural land coverage** from high‑resolution imagery.

The work includes robust preprocessing pipelines, deep learning model development, evaluation with rigorous metrics, and experimentation with both **CNNs** and a **CNN–Vision Transformer (ViT) hybrid model**.

---

## Project Objectives

- Build a complete pipeline for satellite image classification.
- Develop preprocessing workflows for large geospatial datasets.
- Design and train two fundamentally different architectures:
  - A standard **Convolutional Neural Network (CNN)**
  - A **CNN–ViT hybrid model** for enhanced spatial feature extraction
- Apply augmentation and transfer learning to improve generalization.
- Evaluate models using:
  - Accuracy, Precision, Recall, F1 Score  
  - ROC‑AUC  
  - Confusion Matrix  
  - Classification Report  
- Compare model performance and analyze classification behavior.

---

## Dataset Overview

The dataset consists of:

- **6000 satellite images**
- **64×64 pixels**
- **Two classes**:
  - **Agricultural**
  - **Non‑Agricultural**

---

## Technologies

Python, TensorFlow / Keras, PyTorch, NumPy, Pandas, Matplotlib, Jupyter Notebook