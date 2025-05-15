# INDIAN_HOUSE_PRICE_PREDICTION
This project uses machine learning to predict house prices based on important features such as location, area, number of bedrooms, and a custom-engineered luxury level. It includes a fully functional Streamlit web app where users can input house details and receive a price prediction instantly.
HOUSE PRICE PREDICTION USING MACHINE LEARNING
=============================================

Project Overview:
-----------------
This project implements a machine learning model to predict housing prices based on structured data including features such as location, area, number of bedrooms, and various amenities. It uses supervised learning algorithms to build a regression model capable of estimating the market price of a residential property.

The dataset is preprocessed, feature-engineered, and trained using scikit-learn regression models. The entire workflow includes data cleaning, exploratory data analysis (EDA), model training, evaluation, cross-validation, and model serialization for reuse.

Key Features:
-------------
- Cleaned and preprocessed real-estate dataset
- Feature engineering including:
    - Extraction of latitude/longitude from location
    - Creation of a composite 'Luxury' feature combining amenities
    - Encoding of categorical variables
    - Normalization of numerical features
- Multiple regression model training (Linear Regression, Gradient Boosting, Random Forest, etc.)
- Cross-validation using scikit-learn
- Error evaluation using:
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
    - R² Score
- Model persistence using Pickle (`model.pkl` and `preprocessor.pkl`)
- Jupyter notebook demonstrating full exploratory analysis and model logic

Directory Structure:
--------------------
house-price-prediction/
├── data
│   └── preprocessed_house_price_india.csv      
├── notebook
├── README.txt                 
└── .gitignore                

How to Use:
-----------
1. Clone the repository to your local system:
   git clone https://github.com/Proloy-mui/house-price-prediction.git

2. Navigate to the folder:
   cd house-price-prediction

3. Install the dependencies:
   pip install -r requirements.txt

4. Open the notebook:
   Run `jupyter notebook` and open `original_notebook.ipynb` to retrain, visualize, or test the model.


   

