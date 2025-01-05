# Handling Class Imbalance: Comparing Techniques

## Overview
This project explores and compares multiple techniques to address class imbalance in a dataset:
- **Undersampling**
- **Oversampling**
- **SMOTE (Synthetic Minority Oversampling Technique)**
- **SMOTE-K (SMOTE with K-means)**

The goal is to evaluate the impact of these methods on model performance and identify the best-performing approach.

## Features
- Implementation of various methods to handle class imbalance.
- Comparison of performance metrics across different techniques.
- Detailed analysis of F1 scores and overall accuracy improvements.

## Key Results
1. **Undersampling**: Limited improvement in minority class F1 score, with a drop in overall accuracy.
2. **Oversampling**: Moderate improvement in minority class F1 score, but prone to overfitting.
3. **SMOTE**:  
   - **Minority Class F1 Score**: Increased significantly from **0.57 to 0.81**.
   - **Overall Accuracy**: Improved from **0.78 to 0.80**.
4. **SMOTE-K**: Balanced performance but slightly lower F1 score compared to SMOTE.

### **Conclusion**
Among all methods, **SMOTE performs the best**, significantly enhancing the minority class F1 score and overall model accuracy.



