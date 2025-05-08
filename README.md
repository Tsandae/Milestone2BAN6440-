# Milestone2BAN6440-
# Breast Cancer Diagnosis using Neural Networks

## Project Overview
This project focuses on developing a deep learning model to classify breast cancer tumors as **malignant (M)** or **benign (B)** using a publicly available dataset. The goal is to assist in early diagnosis and treatment planning by leveraging machine learning techniques.

---

## Dataset Used
- **Source**: Breast Cancer Dataset
- **Target**: Diagnosis (M = malignant, B = benign)

---

## Model Architecture
The final model architecture was selected through hyperparameter tuning, including:
- **Input layer**: 30 features
- **Hidden layers**: 
  - Model 1: [64, 32] neurons, Dropout 0.5
  - Model 2: [32, 16] neurons, Dropout 0.3
  - Model 3: [64, 32, 16] neurons, Dropout 0.3
- **Activation Function**: ReLU
- **Output Layer**: 1 neuron with sigmoid activation
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam

---

##  Model Training and Evaluation
- **Train-Test Split**: 80/20
- **Validation Split**: 10% from training data
- **Best Validation Accuracy**: **1.0000**
- **Test Accuracy**: Achieved nearly perfect classification on unseen data

---

## Requirements
- Python 3.12+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow / keras



