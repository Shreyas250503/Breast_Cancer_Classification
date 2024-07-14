## **Breast Cancer Classification using PCA**

### **Overview** 
This project focuses on building a classification model to predict breast cancer using the Winscom dataset.
The dataset is processed using Principal Component Analysis (PCA) for dimensionality reduction.Various machine learning models are trained and evaluated, achieving an accuracy of over 99%.

### Introduction 
Breast cancer is one of the most common cancers among women worldwide. Early detection and accurate diagnosis are crucial for effective treatment. This project leverages machine learning techniques to classify breast cancer as benign or malignant.

### Dataset
The Winscom dataset is used for this project. It contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.

### Exploratory Data Analysis (EDA)
Thorough exploratory data analysis is performed to understand the distribution and relationships of features in the dataset. Various visualizations and statistical tests like the Anova Test are conducted to gain insights into the data.

### Principal Component Analysis (PCA)
PCA is used to reduce the dimensionality of the dataset while retaining the most significant features. This step helps in simplifying the model and improving computational efficiency.

### Model Training
The following machine learning models are trained using GridSearchCV for hyperparameter tuning:

+ Logistic Regression
+ K-Nearest Neighbors (KNN)
+ Linear Support Vector Machine (Linear SVM)
+ Gradient Boosting
+ Decision Tree
+ Random Forest

### Conclusion
The project demonstrates that using PCA and machine learning models can effectively classify breast cancer with high accuracy. The best model achieves an accuracy of over 99%, indicating its potential for real-world applications.




