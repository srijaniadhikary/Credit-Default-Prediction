**Objective**: To predict whether a customer will default in future based on an industrial scale data set provided by American Express (Kaggle Hackathon)
* Prepared and preprocessed large data (train size 16 GB, test size 34 GB approx.) with a low memory system.
* Divided the data based on variable types and performed segment wise feature engineering followed by 2 stage feature selection.
* Selected CatBoost, LightGBM and XGBoost as top 3 models based on AUC, Accuracy and Precision Using Pycaret.
* Observed 42% jump in performance as compared to the initial baseline model using CatBoost Classifier.
