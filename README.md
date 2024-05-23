# Predicting Heart Disease using Ensemble Technique

![image](https://github.com/Vanshika0301/Predicting_Heartdisease_using_Ensemble_Techniques/assets/146732449/cd694e03-5abf-4703-81de-a01b531695f0)

## Business Objective
This project aims to predict the presence of heart disease in patients based on various health-related features using ensemble techniques, specifically a Random Forest classifier. The dataset used is the "Heart Disease UCI" dataset, which contains information from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It includes 76 attributes, but all published experiments refer to using a subset of 14 of them. The target field indicates the presence of heart disease, with values 0 for no disease and 1 for disease.

## Features
- age: Age of the patient
- sex: Gender (1 = male, 0 = female)
- cp: Chest pain type
- trestbps: Resting blood pressure
- chol: Serum cholesterol
- fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise-induced angina (1 = yes, 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: Slope of the peak exercise ST segment
- ca: Number of major vessels (0-3) colored by fluoroscopy
- thal: Thalassemia

## Objective
The main objective of this project is to predict the presence of heart disease in patients based on the provided features using ensemble techniques, specifically a Random Forest classifier.

## Workflow
- Loading and Exploring the Data: Loading the dataset and exploring its structure and features.
- Data Preprocessing: Handling missing values and converting categorical variables to numerical using one-hot encoding.
- Splitting the Data: Splitting the dataset into training and testing sets.
- Building and Training the Random Forest Classifier: Creating and training a Random Forest classifier with 100 trees.
- Making Predictions and Evaluation: Making predictions on the test data and evaluating the model's performance using accuracy and classification report.
- Creating a Streamlit Web App: Developing a simple web app using Streamlit for users to interactively input features and get predictions from the trained model.

## Usage
- Clone this repository to your local machine using git clone https://github.com/Vanshika0301/Predicting_Heartdisease_using_Ensemble_Techniques.git
- Install the required dependencies using pip install -r requirements.txt
- Run the Streamlit app locally using streamlit run app.py
- Access the app through the URL provided (usually http://localhost:8501).

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Streamlit
