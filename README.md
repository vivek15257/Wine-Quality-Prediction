Wine Quality Prediction using Linear Regression
This project demonstrates the use of Linear Regression to predict the quality of wine based on its chemical properties. The dataset used in this project is a wine quality dataset containing features like acidity, sugar, chlorides, alcohol content, etc.

Dataset
The dataset used is the WineQT.csv, which contains the following columns:

fixed acidity
volatile acidity
citric acid
residual sugar
chlorides
free sulfur dioxide
total sulfur dioxide
density
pH
sulphates
alcohol
quality (Target variable)
Id (Unique identifier)
Project Workflow
Data Loading and Preparation

The dataset is loaded using Pandas and split into features (X) and target (y).
Data is split into training and testing sets using train_test_split.
Model Training

A Linear Regression model from scikit-learn is trained on the training data.
Evaluation

The model is evaluated using:
Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.
R-squared (R²): Indicates how well the model explains the variability in the target variable.
Visualization

A scatter plot is created to compare the true quality vs predicted quality of wine.
Results
Mean Squared Error (MSE): 0.3824
R-squared (R²): 0.3128
The scatter plot below shows the relationship between true and predicted wine quality:


Installation and Setup
Clone the repository:
bash
Copy code
git clone <repository-url>
Navigate to the project directory:
bash
Copy code
cd wine-quality-prediction
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the script:
bash
Copy code
python wine_quality.py
Dependencies
Python 3.x
Pandas
scikit-learn
Matplotlib
Future Improvements
Experiment with other machine learning models (e.g., Decision Trees, Random Forests).
Perform feature engineering and scaling to improve model performance.
Include cross-validation to ensure robust model evaluation.
License
This project is licensed under the MIT License.

Acknowledgements
The dataset used in this project is publicly available and sourced from the UCI Machine Learning Repository.
