Author: Alexander Davis
Date: 02/19/2024

Purpose: The purpose of this project is to create a classification model to predict someone's credit score.


Scripts:
	- preprocessing.pynb: This notebook is for preprocessing the original data and performing tasks such as removing outliers, filling missing values, and correcting data errors. The output of this script is the credit_data_preprocessed file.
	- feature_engineering.pynb: This notebook is for preparing the preprocessed data for modeling. Includes feature creation and handling multicolinnearity. The output of this script is the model_inputs file.
	- model_selection.pynb: This notebook is for model creation and testing.


Data:
	- credit_data.csv: The original dataset.
	- credit_data_preprocessed.csv: The cleaned dataset after it goes through the preprocessing script.
	- model_inputs.csv: The refined dataset after it goes through the feature_engineering script.

Model:
	- the final model produced in the model_selection.pynb
	- stored as a .pkl file