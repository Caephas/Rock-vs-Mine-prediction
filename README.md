# Rock vs Mine Prediction

This project uses Machine Learning to distinguish between Rock and Mine

## Dependencies
This project is written in Python and uses the following libraries:
- numpy
- pandas
- sklearn

## Data Collection and Processing
The data for this project comes from a .csv file. It is loaded into a pandas dataframe and then split into features (X) and target variable (Y). The 60th column in the dataset is the target variable.

## Training and Testing Data
The data is split into a training set and a test set, with 90% of the data used for training and 10% reserved for testing. The 'stratify' parameter ensures that the train and test data sets have the same proportions of class labels as the input dataset.

## Model Training
The model used in this project is a Logistic Regression model from Scikit-learn. The model is trained using the training data.

## Model Evaluation
The model's performance is evaluated by comparing its predictions on the training data and test data to the actual values. The metric used for evaluation is accuracy.

## Predictive System
After training and evaluating the model, it's used for predictions. The input to the predictive system is a 1D array, which is reshaped to a 2D array because the model's predict function requires a 2D array as input.

## Usage
To use this project, run the script in a Python environment, and ensure the .csv file with the data is in the correct directory.

## Conclusion
This project demonstrates a simple machine learning workflow: from loading and preprocessing data, splitting it into train and test sets, training a model, evaluating the model, and finally using the model to make predictions. The Logistic Regression model shows high accuracy in distinguishing between rock and mine.
