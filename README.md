

---

# Supervised Data Mining - Classification

## Overview

This project focuses on implementing and comparing two supervised learning algorithms for classification tasks: **Decision Tree** and **Naive Bayes**. The algorithms are tested on the **Wisconsin Breast Cancer Database** to evaluate their performance and determine the more accurate classifier.

## Results

- **Decision Tree**: Achieved an average accuracy rate of **93.41%**.
- **Naive Bayes**: Achieved an average accuracy rate of **91.95%**.
  
## Dataset

- **Name**: Wisconsin Breast Cancer Database  
- **Source**: [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)   

### Information About the Dataset

The dataset contains a total of **699 instances**. Each instance represents a case of breast cancer and is classified as either **Benign (2)** or **Malignant (4)**. Out of the 699 instances, **458** are classified as Benign and **241** are classified as Malignant. There are **16 instances** with missing data, which are marked as "**?**".

### Attribute Information

The dataset consists of 11 attributes, which include:

1. **Sample code number**: Unique ID for each instance  
2. **Clump Thickness**: Range 1 - 10  
3. **Uniformity of Cell Size**: Range 1 - 10  
4. **Uniformity of Cell Shape**: Range 1 - 10  
5. **Marginal Adhesion**: Range 1 - 10  
6. **Single Epithelial Cell Size**: Range 1 - 10  
7. **Bare Nuclei**: Range 1 - 10  
8. **Bland Chromatin**: Range 1 - 10  
9. **Normal Nucleoli**: Range 1 - 10  
10. **Mitoses**: Range 1 - 10  
11. **Class**: (2 for Benign, 4 for Malignant)  

These attributes describe various characteristics of cell nuclei present in digitized images of fine needle aspirates (FNA) of breast masses. The goal is to classify the breast cancer as either benign or malignant based on these attributes.

## Algorithms Implemented

1. **Decision Tree**
   - A tree-like model used for classification, where each internal node represents a test on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label.

2. **Naive Bayes**
   - A probabilistic classifier based on applying Bayes' theorem with strong (naive) independence assumptions between the features.


### Conclusion

The results indicate that the **Decision Tree Classifier** outperforms the **Naive Bayes Classifier** in terms of accuracy on the Wisconsin Breast Cancer dataset, making it a more suitable choice for this particular dataset.


## Dependencies

- Python 3.x
- scikit-learn
- pandas
- numpy


---

