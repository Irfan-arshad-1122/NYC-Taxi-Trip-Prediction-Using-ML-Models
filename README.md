# NYC Taxi Trip Duration Prediction
This project aims to predict the duration of taxi trips in New York City using machine learning algorithms. The dataset used for this project is the NYC Taxi Trip Duration dataset, sourced from Kaggle, which contains historical data about taxi trips including features such as pickup and drop-off locations, timestamps, and other relevant information.

## Project Overview
The project involves the following steps:

## Data Retrieval and Preparation:

The NYC Taxi Trip Duration dataset was downloaded from Kaggle using the Kaggle API.
The dataset was unzipped, and the required files (train.csv, test.csv, sample_submission.csv) were extracted for analysis.
## Data Exploration and Preprocessing (EDA):

Exploratory Data Analysis (EDA) was performed to understand the structure and characteristics of the dataset.
Data preprocessing techniques were applied to clean the data and prepare it for modeling.
## Model Building:

Three machine learning algorithms were employed for prediction: Random Forest, Decision Tree, and Linear Regression.
Each model was trained on the preprocessed data to learn the relationship between the input features and the target variable (trip duration).
## Evaluation:

The performance of each model was evaluated using appropriate metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
## File Structure
data/: Contains the dataset files (train.csv, test.csv, sample_submission.csv) used for training and testing the models.

notebooks/:
EDA.ipynb & Model Implementation.ipynb: Jupyter Notebook containing the implementation of machine learning models and EDA.

README.md: This file providing an overview of the project.
## Dependencies
The project requires the following dependencies:

Python 3.x

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Kaggle API (for dataset download)

## Usage
To reproduce the results or further explore the project:

Clone the repository to your local machine.

Install the required dependencies using pip install -r requirements.txt.

Open the Jupyter Notebook EDA.ipynb and Model Implementation.ipynb in Google Colab or any other Jupyter environment.

Execute the cells in the notebook sequentially to download the dataset, perform data preprocessing, train machine learning 

models, and evaluate their performance.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
