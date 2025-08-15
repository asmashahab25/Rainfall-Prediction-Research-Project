# Rainfall-Prediction-Research-Project
A machine learning project that predicts rainfall based on historical weather data. This project explores data preprocessing, feature engineering, and model training using supervised learning techniques. Built for academic exploration and real-world application in climate analytics.

-Authors: Asma Shahab, Ananya Singhal
-Institution: Indira Gandhi Delhi Technical University for Women, Delhi

Features
- Predicts rainfall occurrence and intensity
- Supports CSV-based weather datasets
- Implements multiple ML models (Logistic Regression, SVM, XGBoost)
- Visualizes trends and performance metrics
- Modular codebase for easy experimentation

Tech Stack
- Languages: Python
- Libraries: Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn
- Tools: Jupyter Notebook / Google Colab, GitHub

Model Overview

LogisticRegression() : 
Training Accuracy :  0.8893967324057472
Validation Accuracy :  0.8966666666666667

XGBClassifier() : 
Training Accuracy :  0.9903285270573975
Validation Accuracy :  0.8408333333333333

SVC(probability=True) : 
Training Accuracy :  0.9026413474407211
Validation Accuracy :  0.8858333333333333

Observation

From the above accuracies, we can say that Logistic Regression and support vector classifier are satisfactory as the gap between the training and the validation accuracy is low.

How to Run 

- Clone the repository
git clone https://github.com/asmashahab25/Rainfall-Prediction.git
cd Rainfall-Prediction

- Install dependencies
pip install -r requirements.txt

- Run the notebook

- Open notebooks/Rainfall_Prediction.ipynb in Jupyter or Colab.

Dataset
- Source: [GeeksforGeeks]
- Format: CSV with features like temperature, humidity, wind speed, pressure, etc.
- Description: The dataset contains historical weather data including temperature, humidity, wind speed, and rainfall indicators. It is used to train and evaluate machine learning models for rainfall prediction.


Future Improvements
- Integrate deep learning models (LSTM for time series)
- Deploy as a web app using Streamlit or Flask
- Add real-time weather API integration

Repository Contents

 - Rainfall Prediction Dataset
 - Visual Studio Code
 - A detailed document explaining the code
 - Readme.md
  



