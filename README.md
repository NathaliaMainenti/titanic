# Titanic Survival Prediction Project
This project implements machine learning models to predict passenger survival on the Titanic, achieving a top accuracy of 83.41% using K-Nearest Neighbors (KNN). The project compares multiple classification algorithms including Decision Trees, Logistic Regression, and SVM to determine the most effective approach for predicting survival outcomes based on passenger data. 


📊 Model Performance Results
The following models were trained and evaluated, with KNN performing the best among them.  
✅ KNN Accuracy: 83.41% ([[112 22] [ 15 74]])  
✅ Decision Tree Accuracy: 82.51% ([[119 15] [ 24 65]])  
✅ Logistic Regression Accuracy: 82.51% ([[116 18] [ 21 68]])  
✅ SVM Accuracy: 82.51% ([[119 15] [ 24 65]])  

🛠️ Methodology
Data Preprocessing: Handled missing values, encoded categorical variables, and scaled numerical features.
Model Training: Applied Decision Tree, Logistic Regression, SVM, and KNN.
Evaluation: Used accuracy and confusion matrices to compare model performance. 


🚀 Conclusion
The KNN model provided the highest accuracy at 83.41%. The confusion matrix shows that the models are generally robust but have room for improvement regarding false positives/negatives in the survival classification.
