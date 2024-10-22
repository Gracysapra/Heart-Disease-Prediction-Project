
# Heart Disease Prediction Project

## Overview
This project aims to develop a predictive model for heart disease using various machine learning algorithms. By leveraging patient data, the model assesses the likelihood of heart disease, providing a valuable tool for healthcare professionals to assist in early diagnosis and treatment.

## Dataset
The dataset utilized for this project consists of 1,025 records with 14 attributes, including:
- **Age**: Age of the patient
- **Sex**: Gender of the patient
- **Chest Pain Type (cp)**: Type of chest pain experienced
- **Resting Blood Pressure (trestbps)**: Blood pressure measurement
- **Cholesterol Level (chol)**: Serum cholesterol in mg/dl
- **Fasting Blood Sugar (fbs)**: Blood sugar level
- **Resting Electrocardiographic Results (restecg)**: Electrocardiographic results
- **Maximum Heart Rate Achieved (thalach)**: Maximum heart rate achieved during exercise
- **Exercise Induced Angina (exang)**: Indication of angina during exercise
- **Old Peak**: ST depression induced by exercise relative to rest
- **Slope**: Slope of the peak exercise ST segment
- **Number of Major Vessels (ca)**: Number of major vessels colored by fluoroscopy
- **Thalassemia (thal)**: Thalassemia status
- **Target**: Presence (1) or absence (0) of heart disease

## Machine Learning Models
The project implements several machine learning models to predict heart disease, including:
- **Logistic Regression**
- **Random Forest**
- **Decision Trees**
- **Support Vector Machines (SVM)**
- **XG Boost**
- **Feedforward Neural Networks (FNN)**
  

Each model is trained and evaluated based on accuracy, precision, recall, and F1 score. The results are presented using confusion matrices and classification reports to provide a comprehensive understanding of model performance.

## User Interface
To enhance user experience, the project incorporates **Gradio**, creating an interactive web interface where users can input patient data and receive immediate predictions. This feature allows healthcare professionals to utilize the tool effectively in clinical settings.

## Model Management
The project integrates **MLflow** for streamlined model management. MLflow is used for:
- Logging experiments and tracking model parameters
- Storing and versioning trained models
- Comparing model performance metrics over time

This facilitates the selection of the best-performing model for deployment and future reference.

## Conclusion
The heart disease prediction project combines advanced machine learning techniques with practical user interface design and effective model management strategies. By providing accurate predictive analytics, this tool aims to assist healthcare providers in making informed decisions, ultimately improving patient outcomes.

## Installation
To run the project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd heart-disease-prediction
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Gradio interface:
   ```bash
   python app.py
   ```

## Usage
Open a web browser and navigate to `http://localhost:7860` to access the Gradio interface. Input the necessary patient data to receive predictions regarding heart disease.
