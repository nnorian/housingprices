Housing Price Prediction Project

This project aims to predict housing prices using a dataset with 13 key features that covers the entire machine learning pipeline from data cleaning to model training and evaluation along with data visualization

Project Structure

- Housing.csv: The raw dataset containing housing information, including features like area, bedrooms, bathrooms, the other features of the dataset
- cleaned_housing_data.csv: the cleaned version of the housing dataset
- cleaning_and_preparing.ipynb: contains the data cleaning and preparation steps
- model_training_n_evaluation.ipynb: contains the machine learning model training prediction and evaluation. The model used is linear regression
- visualisating_the_data.ipynb: visualizes the dataset and the relationships between different features and the target variable (price) to make the first predictions
  
1. Dataset Overview

The dataset contains various features that describe housing properties, including:

- `area`: The total area of the house.
-  number of bedrooms
-  number of bathrooms
-  number of stories (floors) in the house
-  is the house near the main road (yes/no)
-  is the house having a guest room (yes/no)
-  does the house has a basement (yes/no)
-  does the house has hot water heating (yes/no)
-  does the house has air conditioning (yes/no)
-  number of parking spaces
-  does the house  exist in a preferred area (yes/no)
-  furnishing status (furnished, semi-furnished, unfurnished)
-  target variable — the price of the house

2. Project Steps

1. data cleaning and preparation (to improve model accuracy)
- in cleaning_and_preparing.ipynb

2. Data visualization (to make initial assumptions)
- Performed in visualisating_the_data.ipynb

3. Model training and evaluation (using linear regression)
- Performed in model_training_n_evaluation.ipynb


  How to Run the Project

1 Clone the repository and download the project files
2 Install the required libraries (use requirements.txt)
3 Open the Jupyter notebook and run in the following order:
     1. cleaning_and_preparing.ipynb
     2. visualisating_the_data.ipynb
     3. model_training_n_evaluation.ipynb
