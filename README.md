# 🩺 Pneumonia Detection Using Chest X-Rays and Deep Learning

## Overview

This project focuses on the automated detection of pneumonia from chest X-ray images using Deep Learning and Computer Vision techniques. Multiple Convolutional Neural Network (CNN) architectures and preprocessing strategies were evaluated to improve classification performance and model robustness.

The objective is to assist medical diagnosis by accurately distinguishing between **Pneumonia** and **Normal** chest X-ray scans.

---

## Features

* Binary classification of Chest X-ray images
* Multiple CNN architectures evaluated
* Image preprocessing and enhancement using CLAHE
* Hyperparameter tuning and regularization techniques
* Model performance comparison across architectures
* Ensemble learning experiments
* Comprehensive evaluation using medical AI metrics

---

## Dataset

The project uses a publicly available Chest X-Ray dataset containing:

* Pneumonia Images
* Normal Images

Dataset Size:

* 5,800+ Chest X-Ray Images

Classes:

* Normal
* Pneumonia

---

## Deep Learning Architectures Explored

The project includes experiments with:

* Baseline CNN
* Improved CNN
* MobileNetV2
* EfficientNetB0
* DenseNet121
* ResNet50
* Xception
* Ensemble Models

---

## Image Preprocessing Techniques

To improve feature extraction and image quality:

* Image Resizing
* Normalization
* Data Augmentation
* Contrast Enhancement
* CLAHE (Contrast Limited Adaptive Histogram Equalization)
* Dataset Balancing

---

## Training Optimizations

The following techniques were applied to improve model performance:

* Hyperparameter Tuning
* Dropout Regularization
* Early Stopping
* Learning Rate Scheduling
* Model Checkpointing

---

## Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Results

| Metric   | Score |
| -------- | ----- |
| Accuracy | 97%   |
| F1-Score | 95.6% |

The final model demonstrated strong performance in distinguishing pneumonia cases from normal chest X-ray scans.

---

## Tech Stack

### Programming Language

* Python

### Deep Learning

* TensorFlow
* Keras

### Data Processing

* NumPy
* Pandas

### Visualization

* Matplotlib

### Computer Vision

* OpenCV

### Development Environment

* Jupyter Notebook
* VS Code

---

## Project Structure

```text
Pneumonia-Detection-Using-Chest-XRays-in-DL
│
├── Basse.ipynb
├── E1_BaselineCNN
├── E2_BaselineCNN
├── E3_BaselineCNN
├── ...
├── E30_Ensemble_Final
│
└── README.md
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/rawat9340/Pneumonia-Detection-Using-Chest-XRays-in-DL.git
```

### Install Dependencies

```bash
pip install tensorflow keras numpy pandas matplotlib opencv-python
```

### Launch Notebook

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

## Future Improvements

* Multi-class lung disease classification
* Explainable AI using Grad-CAM
* Web deployment using Flask/Streamlit
* Real-time inference system
* Clinical validation on larger datasets

---

## Author

**Arun Rawat**

* GitHub: https://github.com/rawat9340
* LinkedIn: https://www.linkedin.com/in/arun-rawat-545163213/

---

### Keywords

Deep Learning • Computer Vision • Medical Imaging • CNN • TensorFlow • Keras • Pneumonia Detection • Chest X-Ray Classification • Machine Learning • Healthcare AI
