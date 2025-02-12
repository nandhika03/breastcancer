# Breast Cancer Diagnosis Using Machine Learning

## Overview
This project applies machine learning techniques to classify breast cancer cases using a publicly available dataset. We implemented **Logistic Regression** and **Random Forest** classifiers to distinguish between malignant and benign cases.

## Dataset
We used the **Breast Cancer Wisconsin Dataset**, which contains features extracted from cell nuclei present in digitized images of fine needle aspirate (FNA) samples of breast masses.

## Methodology
1. **Machine Learning Models:**  
   - **Logistic Regression**  
   - **Random Forest Classifier**  
2. **Cross-Validation:** We applied **K-Fold Cross-Validation** to evaluate model performance.  
3. **Hyperparameter Tuning:** We optimized model parameters for improved accuracy.  
4. **Performance Evaluation:** We analyzed the results using metrics such as **confusion matrix**, **accuracy**, **precision**, **recall**, and **F1-score**.

## Results
Both models achieved high accuracy, with **Random Forest** performing slightly better due to its ability to handle complex feature interactions. The confusion matrix helped assess misclassification rates.

## Repository Contents
- `breast_cancer_classification.ipynb` – Code for data preprocessing, training, and evaluation.  
- `data/` – The dataset used for training and testing.  
- `README.md` – This file explaining the project.

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/breast-cancer-ml.git
