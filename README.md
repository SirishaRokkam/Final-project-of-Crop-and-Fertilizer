# Week-2
 ### Crop and Fertilizerand Recommendation Prediction System 🌱
Overview
This project aims to assist farmers by recommending the best crops based on soil and weather conditions and suggesting suitable fertilizers to enhance productivity. Using machine learning models, we analyze key factors such as nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, pH, and rainfall to provide accurate predictions.

### Table of Contents
Features

Dataset

Technologies Used

Installation

Step-by-Step Process


Usage

Results

Future Enhancements

Contributors



## Features
✅ Predicts the best crop based on soil and climate conditions.
✅ Suggests the most suitable fertilizer for better yield.
✅ Data-driven recommendations using machine learning.
✅ Web-based UI for easy interaction (if deployed).

## Dataset
Crop Recommendation Dataset (Crop_recommendation.csv)
Contains soil nutrients, temperature, humidity, pH, and rainfall data.
Fertilizer Prediction Dataset (Fertilizer Prediction.csv)
Includes soil nutrient levels and recommended fertilizers.


## Technologies Used
🔹 Python
🔹 Pandas, NumPy (Data Processing)
🔹 Matplotlib, Seaborn (Data Visualization)

## Installation
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/crop-fertilizer-prediction.git
cd crop-fertilizer-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Step-by-Step Process
1. Data Collection & Preprocessing
Loaded crop recommendation and fertilizer prediction datasets.
Cleaned data by handling missing values and duplicates.
Performed exploratory data analysis (EDA) to identify key trends.
2. Feature Engineering & Selection
Selected important features: (N, P, K, temperature, humidity, pH, rainfall).
Normalized data for better model performance.
3. Model Selection & Training
Used Random Forest, Decision Trees, SVM, and KNN for crop recommendation.
Implemented Logistic Regression, Naïve Bayes for fertilizer prediction.
Trained models on cleaned data and optimized hyperparameters.
4. Model Evaluation
Evaluated models using accuracy, precision, recall, and F1-score.
Compared different models and selected the best one for deployment.
5. Deployment (Optional)
Built a simple web interface using Flask/Django.
Created an input form where users can enter soil/weather conditions.
Displayed crop and fertilizer recommendations.
Usage
To predict the best crop:

python
Copy
Edit
python crop_prediction.py
To predict fertilizer recommendations:

python
Copy
Edit
python fertilizer_prediction.py
Results
Achieved high accuracy for crop recommendation and fertilizer prediction.
Provided real-time insights for farmers.
Future Enhancements 🚀
Integrate a real-time weather API.
Add GIS-based soil mapping for more accurate predictions.
Improve UI with React.js or Streamlit.
Contributors
👤 SIRISHA ROKKAM –

