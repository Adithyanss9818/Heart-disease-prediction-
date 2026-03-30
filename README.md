
# 🩺 Heart Disease Prediction Using Machine Learning

## 📌 Project Description

The main objective of this project is to develop a Machine Learning model using the Random Forest algorithm to predict the presence of heart disease based on various health and lifestyle parameters. The model uses features such as age, body mass index (BMI), heart rate, blood pressure, smoking habits, diabetic status, physical activity, and sleep patterns to identify whether a person is at risk of heart disease.

This project was chosen because heart disease is one of the leading causes of death worldwide, and early prediction can significantly reduce health risks. Machine Learning helps in analyzing large amounts of medical data efficiently and extracting meaningful patterns, making it a powerful tool in healthcare.

Predicting heart disease is important because many individuals are unaware of their health risks until it becomes critical. This model helps in early detection, allowing timely precautions such as lifestyle changes, monitoring, and medical treatment. It ultimately contributes to better healthcare and can help save lives.

The project addresses the problem of delayed or difficult diagnosis using traditional methods. Manual analysis may not always detect hidden patterns in data, whereas this system provides a fast and accurate data-driven solution. The Random Forest model improves prediction accuracy by combining multiple decision trees and reducing errors.

This system can be implemented in real-world applications such as hospitals, clinics, healthcare systems, and health monitoring applications. It can also be integrated into wearable devices for continuous health tracking. In the future, the model can be enhanced using larger datasets and advanced algorithms.

---

## ⚙️ Procedure for Heart Disease Prediction

- Collected a dataset containing health and lifestyle information  
- Analyzed the dataset to understand features and target variable  
- Performed data preprocessing:
  - Converted Yes/No values into 0/1  
  - Encoded gender  
  - Split blood pressure into systolic and diastolic  
- Selected important features such as age, BMI, heart rate, and lifestyle factors  
- Split the dataset into training (80%) and testing (20%)  
- Chose Random Forest algorithm for model building  
- Trained the model using training data  
- Predicted heart disease using test data  
- Evaluated the model using:
  - Accuracy  
  - Confusion Matrix  
  - Precision  
  - Recall  
  - F1-Score  

---

## 🤖 Model Explanation

This project uses the Random Forest algorithm to predict heart disease. The dataset was first analyzed and preprocessed by converting categorical values into numerical form and preparing the data for training. Important features influencing heart disease were selected to improve model performance.

The dataset was then divided into training and testing sets. The model was trained using the training data to learn patterns between health factors and heart disease. After training, it was used to predict outcomes on test data. The model’s performance was evaluated using standard classification metrics, showing good accuracy and reliability.

---

## 🌳 Why Random Forest?

- Provides high accuracy  
- Reduces overfitting  
- Handles both numerical and categorical data  
- Works well with complex medical datasets  
- Uses multiple decision trees for better prediction  

---

## ❌ Why Other Models Were Not Preferred

- **Logistic Regression**: Assumes linear relationships, not suitable for complex data  
- **Decision Tree**: Prone to overfitting  
- **K-Nearest Neighbors (KNN)**: Slow for large datasets  
- **Support Vector Machine (SVM)**: Complex and computationally expensive  

Random Forest overcomes these limitations and provides better performance, making it the best choice for this project.

---

## ✅ Conclusion

The Random Forest model successfully predicts heart disease with good accuracy. This project demonstrates how Machine Learning can be used in healthcare for early detection and risk prediction. It provides a reliable and efficient solution that can be applied in real-world medical systems.
