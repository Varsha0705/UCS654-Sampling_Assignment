# UCS654-Sampling_Assignment
Here’s the code for a complete `README.md` file to document your assignment solution clearly and professionally for GitHub:

---

```markdown
# Sampling Assignment - Machine Learning Models and Sampling Techniques

## **Overview**
This project demonstrates the application of five **sampling techniques** and evaluates their impact on the performance of five **machine learning models**. The assignment involves creating balanced datasets using various sampling techniques, applying these datasets to ML models, and comparing their accuracies.

---

## **Steps Completed**

### **1. Dataset**
The dataset used is `Creditcard_data.csv`, containing features for binary classification (`Class` column).

### **2. Sampling Techniques**
Five sampling techniques were applied to create balanced datasets:
1. **Sampling1**: Random Sampling
2. **Sampling2**: Systematic Sampling
3. **Sampling3**: Cluster Sampling
4. **Sampling4**: Stratified Sampling
5. **Sampling5**: Oversampling

Each sampling technique was applied to generate balanced datasets and ensure fair model evaluation.

---

### **3. Models**
Five machine learning models were used to evaluate each sampled dataset:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Support Vector Machine (SVM)**
5. **K-Nearest Neighbors (KNN)**

---

### **4. Accuracy Matrix**
The models were trained and evaluated on the five sampling techniques, and their accuracy was stored in the following matrix:

| Model | Sampling1 | Sampling2 | Sampling3 | Sampling4 | Sampling5 |
|-------|-----------|-----------|-----------|-----------|-----------|
| M1 (Logistic Regression) | 0.9836 | 0.8525 | 0.8852 | 0.9344 | 0.9180 |
| M2 (Decision Tree)        | 0.8689 | 0.9672 | 0.9508 | 0.9672 | 0.9508 |
| M3 (Random Forest)        | 0.9672 | 1.0000 | 0.9836 | 0.9836 | 0.9836 |
| M4 (SVM)                  | 0.7377 | 0.5902 | 0.7213 | 0.6721 | 0.6885 |
| M5 (KNN)                  | 0.7377 | 0.7213 | 0.7541 | 0.7377 | 0.6721 |


---
```
---

## **Code Files**

### **1. sampling_and_models.py**
Contains the main code to:
- Apply five sampling techniques to the dataset.
- Train and evaluate the models on sampled datasets.
- Output the accuracy matrix.

### **2. Generated Sampling Datasets**
- `sampling1.csv`
- `sampling2.csv`
- `sampling3.csv`
- `sampling4.csv`
- `sampling5.csv`

### **3. accuracy_matrix.csv**
Contains the results of the model evaluations (accuracy matrix).

---

## **Results**
- The accuracy matrix shows the performance of each model on each sampling technique.

---

## **Conclusion**
This project highlights the importance of sampling techniques in machine learning. The accuracy of models varies significantly depending on how the dataset is sampled. Proper sampling ensures balanced training and testing, leading to better performance and fair evaluation.

---
