

---

# Supervised Data Mining - Classification

## Overview

This project focuses on implementing and comparing two supervised learning algorithms for classification tasks: **Decision Tree** and **Naive Bayes**. The algorithms are tested on the **Wisconsin Breast Cancer Database** to evaluate their performance and determine the more accurate classifier.

## Dataset

- **Name**: Wisconsin Breast Cancer Database
- **Source**: [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

The dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, describing the characteristics of the cell nuclei present in the image. The goal is to predict whether the breast cancer is benign or malignant.

## Algorithms Implemented

1. **Decision Tree**
   - A tree-like model used for classification, where each internal node represents a test on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label.

2. **Naive Bayes**
   - A probabilistic classifier based on applying Bayes' theorem with strong (naive) independence assumptions between the features.

## Results

- **Decision Tree**: Achieved an average accuracy rate of **93.41%**.
- **Naive Bayes**: Achieved an average accuracy rate of **91.95%**.

### Conclusion

The results indicate that the **Decision Tree Classifier** outperforms the **Naive Bayes Classifier** in terms of accuracy on the Wisconsin Breast Cancer dataset, making it a more suitable choice for this particular dataset.

## Dependencies

- Python 3.x
- scikit-learn
- pandas
- numpy

---
