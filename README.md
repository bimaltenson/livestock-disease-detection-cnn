# CNN-Based Cow Disease Classification Using Deep Learning

## Project Overview

This project presents a deep learning approach for automatic livestock disease classification using Convolutional Neural Networks (CNN) and MobileNetV2. The objective is to classify cattle images into three disease categories and compare the performance of a custom CNN model with a transfer learning model (MobileNetV2).

## Dataset

**Dataset Name:**
Cows Disease Dataset

**Dataset Source:**
https://www.kaggle.com/datasets/bimaltenson/cows-disease-dataset

**Classes:**

* Healthy
* Foot-and-Mouth Disease
* Lumpy Skin Disease

**Dataset Statistics:**

* Total Images: **3,244**
* Training Images: **2,596**
* Validation Images: **648**
* Image Size: **224 × 224 pixels**

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Models Implemented

* Custom Convolutional Neural Network (CNN)
* MobileNetV2 (Transfer Learning)

---

## Results

| Model       | Training Accuracy | Validation Accuracy |
| ----------- | ----------------: | ------------------: |
| Custom CNN  |        **73.65%** |          **75.31%** |
| MobileNetV2 |        **91.99%** |          **57.87%** |

The experimental results show that the custom CNN model achieved better validation performance and generalized more effectively than the MobileNetV2 model on the cow disease dataset.

---

## Repository Contents

* CNN-Based Cow Disease Classification Notebook
* Dataset Information
* Training and Validation Curves
* Confusion Matrices
* Model Comparison
* Project Documentation

---

## How to Run

1. Clone this repository.
2. Download the dataset from the Kaggle link above.
3. Open the notebook in Kaggle or Jupyter Notebook.
4. Install the required Python libraries.
5. Run all notebook cells to train and evaluate the models.

---

## Author

**Bimal Tenson**

Machine Learning Course Project
