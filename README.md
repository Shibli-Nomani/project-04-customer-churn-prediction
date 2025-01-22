# 🏢 Customer Churn Prediction with Supervised Machine Learning Models (Classification)
![customer-churn](https://github.com/user-attachments/assets/4056cd9c-6079-4cac-96e3-ccdd3fcf3b92)


# 👇 Kaggle Link :
https://www.kaggle.com/code/shiblinomani/mri-of-brain-tumor-classification-using-vgg19#%F0%9F%98%B2-MODEL-PREDICTION-WITH-VALIDATION(UNSEEN-DATA)

# 😉 About Dataset
[https://www.kaggle.com/datasets/iashiqul/mri-image-based-brain-tumor-classification](https://www.kaggle.com/datasets/shubh0799/churn-modelling/data)

# ㊗️ Models
- 📈 Logistic Regression
- 🌐 Naive Bayes (GaussianNB)
- 🌳 Decision Tree Classifier
- 🌲 Random Forest Classifier
- 🤝 K-Neighbors Classifier
- 🧠 Support Vector Classifier
- 🚀 XGBOOST

# 🎢 Summary 
The **Random Forest Classifier** showed better results compared to other models in terms of testing and training accuracy. We addressed class imbalance in the training data using SMOTE, resulting in balanced categories (1: 5972, 0: 5972), while the test data remained imbalanced (0: 1991, 1: 509). The training accuracy reached **100%**, while the test accuracy was **82%** accuracy_score due to the imbalance in the test data. The feature set shapes were X_train: (11944, 10) and X_test: (2500, 10). To optimize the Random Forest Classifier, we applied RandomSearchCV and GridSearchCV, with GridSearchCV achieving better test accuracy.

## Authors

- [@LinkedIn Khan MD Shibli Nomani](https://www.linkedin.com/in/khan-md-shibli-nomani-45445612b/)
