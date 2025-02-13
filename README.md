# classify-individuals-income-level

# Income Dataset Analysis Using Classification Models and Clustering Techniques  

## Overview  
This project involves analyzing and processing the "Adult" dataset from the UCI repository, which contains demographic and economic information. The objective is to classify individuals based on their income level (>50K or <=50K) using various classification models, as well as apply clustering algorithms to uncover hidden patterns.  

## Workflow  
1. **Data Cleaning and Preprocessing:**  
   - Handling missing values.  
   - Encoding categorical variables into numerical values.  
   - Normalizing numerical values as needed.  

2. **Classification Models:**  
   - The following models were implemented:  
     - Logistic Regression  
     - Naive Bayes  
     - Decision Tree  
     - Random Forest  
     - AdaBoost  
     - XGBoost  

3. **Clustering:**  
   - Implemented clustering algorithms:  
     - DBSCAN Clustering  
     - K-means Clustering  

4. **Performance Evaluation:**  
   - Evaluated classification models using the following metrics:  
     - Accuracy  
     - Precision  
     - Recall  
     - F1-Score  

   - Assessed clustering algorithms based on detected patterns and visualizations.  

## Results  
- Classification models showed varying levels of accuracy, with XGBoost being the best-performing model.  
- Clustering algorithms provided valuable insights into data distribution patterns.  

## Requirements  
- Python 3.8+  
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost  
