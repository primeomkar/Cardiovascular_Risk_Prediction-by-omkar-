# Cardiovascular_Risk_Prediction-by-omkar-
Project Summary -
Cardiovascular disease is a leading cause of death worldwide, and early prediction of cardiovascular risk can help in timely intervention and prevention of the disease. Machine learning techniques have shown promising results in predicting cardiovascular risk by analyzing various risk factors.

The goal of this project is to develop a machine learning model to predict the 10-year risk of cardiovascular disease in individuals using a dataset of demographic, clinical, and laboratory data.

The dataset used in this project is the Framingham Heart Study dataset, which is a widely used dataset for cardiovascular risk prediction. It contains data on 3,390 participants, who were followed up for ten years to track cardiovascular events. The dataset includes 17 variables such as age, sex, blood pressure, cholesterol levels, smoking status, and diabetes status.

The first step in this project is to perform data preprocessing, which includes handling missing values, encoding categorical variables, and scaling numerical variables. After preprocessing, the dataset is split into training and testing sets using a 70:20 ratio.

Various machine learning algorithms are applied to the training data, including logistic regression, KNN, XGBoost, SVC, and random forest, Naive Bayes Classifier. These algorithms are chosen as they have been shown to perform well in cardiovascular risk prediction. The algorithms are trained on the training data, and their performance is evaluated using the testing data.

The evaluation metrics used in this project include accuracy, precision, recall, and area under the receiver operating characteristic curve (AUC-ROC). These metrics help in assessing the performance of the machine learning model.

The results show that the XGBoost performs the best, with an accuracy of 0.89, precision of 0.92, recall of 0.85, and AUC-ROC of 0.89. This indicates that the model has a good overall performance in predicting cardiovascular risk.

Further analysis is performed to identify the most important features in the dataset. The feature importance plot shows that age, education, prevalentHyp,and cigarettes per day are the top important features in predicting cardiovascular risk. This information can help in identifying high-risk individuals and implementing preventive measures.

In conclusion, this project demonstrates the effectiveness of machine learning techniques in predicting cardiovascular risk using the Framingham Heart Study dataset. The developed machine learning model can be used by healthcare professionals to identify individuals at high risk of cardiovascular disease and take preventive measures to reduce the risk.
