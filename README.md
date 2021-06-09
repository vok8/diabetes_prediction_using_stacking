# Diabetes Prediction using Stacking (Stacked Generalization)

- The architecture of a stacking model involves two or more base models, often referred to as level-0 models, and a meta-model that combines the predictions of the base models, referred to as a level-1 model.

- We have used the following models as level-0 models:
1. Gaussian Naive Bayes Classifier (With hyperparameter tuning) 
2. Random Forest Classifier (With hyperparameter tuning & 3-fold CV)
3. Decision Tree Classifier (With hyperparameter tuning & 3-fold CV)
4. SVM Classifier (With hyperparameter tuning & 3-fold CV)
5. ANN Model (With hyperparameter tuning & 3-fold CV)
6. Logisitic Regression (With hyperparameter tuning & 3-fold CV)

- We have used simple "Logistic Regression" Model (from python's 'scikit' module) as the level-1 model.

- We have achieved 76.2% test accuracy on "Our Model", which is better than all the 6 individual models.

## Contributors & Authors

Vinay Khilwani, Vasu Gondaliya, Shreya Patel, Jay Hemnani & Bhuvan Gandhi
