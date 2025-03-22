# House Price Prediction using Machine Learning Model

## Overview
This project predicts house prices using a **Random Forest Regressor** model trained on key features. It includes: 
- **Data Preprocessing & Training:** Prepares the dataset, trains a model, and saves it.
- **Web Application:** A **Flask-based web app** to predict house prices based on user inputs

## 🚀 Future Updates  
- **Model Improvement:** Tune hyperparameters, try XGBoost/LightGBM.  
- **Deployment:** Host on Render, Heroku, or AWS with Docker support.  
- **Better UI:** Use Streamlit for an interactive interface.  
- **Data Visualization:** Add charts for feature analysis.  
- **Database Integration:** Store predictions in SQLite/Firebase.  
- **Mobile App:** Convert to a Flutter or React Native app. 


## Installation & Setup 
### 1. Clone the Repository
```sh 
git clone https://github.com/Abhi01x/HousePricePrediction--Machine-Learning-Model.git
cd HousePricePrediction--Machine-Learning-Model

2. Install Dependencies 
Make sure you have Python installed, then install the required libraries:

pip install pandas numpy scikit-learn joblib flask


3. Dataset
The dataset (train.csv) contains housing features. Key features used:

OverallQual - Overall material and finish quality

GrLivArea - Above-ground living area 

GarageCars - Number of garages 

TotalBsmtSF - Total basement square footage

SalePrice - Target variable (house price)

Training the Model 
Run the following command to train and save the model:

python train_model.py

This will:

Load the dataset

Preprocess data (handle missing values)

Train a Random Forest Regressor

Save the model as house_price_model.pkl or you can use index.html 

Running the Web App
Start the Flask web application:
python app.py
Then, open http://127.0.0.1:5000/ in your browser to input house features and predict prices.


