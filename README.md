# 🖼️ Image Classification using OpenCV and SVM

## 📌 Project Overview
This project implements a **simple image classification system** using **OpenCV** for image preprocessing and enhancement, and a **Support Vector Machine (SVM)** for classification.  
The goal is to understand how classical machine learning algorithms can be applied to image data after proper preprocessing.

The project is implemented in **Google Colab (.ipynb)** for easy execution and reproducibility.

---

## 📊 Dataset Used
**Handwritten Digits Dataset** from `sklearn.datasets`

- Total images: **1,797**
- Image type: **Grayscale**
- Image size: **8 × 8**
- Classes: **Digits 0–9**

This dataset is suitable for beginners and demonstrates image classification concepts effectively.

---

## 🧠 Implementation Details

### 1️⃣ Image Processing with OpenCV
The following preprocessing steps were applied:

- Resizing images to **32 × 32**
- Normalizing pixel values to range **[0, 1]**
- Flattening images into feature vectors

### Image Enhancement Techniques
To improve feature quality:
- **Brightness and contrast adjustment**
- **Gaussian Blur filtering**

Original and enhanced images are displayed side-by-side for comparison.

---

### 2️⃣ Model Development
- Algorithm used: **Support Vector Machine (SVM)**
- Kernel: **RBF (Radial Basis Function)**
- Train-Test split: **80% training / 20% testing**

The SVM model learns to classify digit images based on processed pixel features.

---

## 📈 Model Evaluation

### Metrics Used
- **Accuracy Score**
- **Confusion Matrix**

### Results
- The model achieves **high classification accuracy**
- The confusion matrix shows strong diagonal values, indicating correct predictions for most classes
- Sample test images are visualized with:
  - Predicted label
  - Actual label

---

## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## 🚀 How to Run
1. Open the `.ipynb` file in **Google Colab**
2. Run all cells sequentially
3. Observe preprocessing results, model performance, and visualizations

---

## 📌 Conclusion
This project demonstrates how traditional machine learning models can be combined with OpenCV image preprocessing to build an effective image classification system. It provides a strong foundation for understanding computer vision and classical ML workflows.
