# 🐱🐶 Cats vs Dogs Classification using SVC

This repository contains a machine learning project that classifies images of cats and dogs using a Support Vector Classifier (SVC) model.

---

## 📌 Project Overview

This project aims to build an image classification model that can differentiate between images of cats and dogs. The **Support Vector Classifier (SVC)** is used as the machine learning algorithm due to its strong performance in classification tasks with well-separated classes.

The dataset contains labeled images of cats and dogs, which are preprocessed and split into training and testing sets before model training.

---

## 📂 Dataset

* **Source:** Commonly available Cats vs Dogs dataset from Kaggle.
* **Classes:**

  * `Cat`
  * `Dog`
* **Preprocessing Steps:**

  * Image resizing to a consistent dimension.
  * Grayscale conversion for simplified computation.
  * Flattening images into 1D arrays.
  * Normalization of pixel values.

---

## ⚙️ Model Details

* **Algorithm:** Support Vector Classifier (SVC)
* **Kernel:** Linear, Polynomial, RBF (tested)
* **Evaluation Metrics:** Accuracy score

---

## 📊 Results

* Model performance was evaluated on the testing dataset.
* Accuracy score achieved: **(65)**

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/cats-vs-dogs-svc.git
   cd cats-vs-dogs-svc
   ```
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Place your dataset inside the project folder.
4. Run the training script or Jupyter Notebook to train and evaluate the model.

---

## 📈 Future Improvements

* Experiment with deep learning models like CNNs for higher accuracy.
* Implement data augmentation to improve model generalization.
* Deploy the model as a web application for easy accessibility.

---

