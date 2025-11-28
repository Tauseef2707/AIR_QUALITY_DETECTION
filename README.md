# AIR_QUALITY_DETECTION
Air Quality Detection Using Machine Learning & Meteorological Data
Mini Project – Machine Learning | B.Tech AIML
📌 Project Overview

This project predicts PM2.5 concentration in the air using machine learning.
We use air pollution features from a dataset (Kaggle/AQI dataset) such as:

PM10

NO2

CO

SO2

The trained model uses these inputs to predict PM2.5 (µg/m³), which is one of the major indicators of air quality.

The model can be used in real time — if someone enters four pollutant values, the system will instantly predict PM2.5.

🧠 Objective

To analyze pollutant data and preprocess it

To train a machine learning model for PM2.5 prediction

To create a simple user-input system for real-time prediction

To display performance using evaluation metrics

To help understand how pollution factors affect air quality

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib / Seaborn

Google Colab

Joblib (for saving model & scaler)

📂 Project Files
File	Description
main.py	Final executable prediction script
AirQuality.ipynb	Colab notebook with step-wise code
dataset.csv	Dataset used for training
model.pkl	Trained Random Forest model
scaler.pkl	StandardScaler fitted on training data
README.md	Project documentation
🔢 Features Used

Model trained using four main pollutants:

PM10
NO2
CO
SO2


These inputs are used to predict:

➡️ PM2.5 (µg/m³)
A major indicator of air pollution and respiratory risk.

📊 Machine Learning Model

Algorithm used:

Random Forest Regressor

Why Random Forest?

Handles non-linear data

Works well with environmental datasets

High accuracy and robustness

📈 Evaluation Metrics

Mean Squared Error (MSE)

R² Score

Actual vs Predicted Plot

Graphs help visualize model accuracy.

🧪 How to Use
🟢 1. Run main.py
python3 main.py

🟢 2. Enter the four pollutant values

Example:

Enter PM10: 80
Enter NO2: 25
Enter CO: 1.2
Enter SO2: 12

🟢 3. Get Prediction

Example output:

Predicted PM2.5: 60.40 µg/m³

📥 Dataset Source

Kaggle Air Quality Dataset
(You may change the link based on the dataset you uploaded.)

🙌 Team / Contribution

Student Name: Tauseef Hussain
Course: B.Tech – AI & ML
Mini Project Guide: Your Faculty Name

📜 License

This project is for educational and academic purposes only.
