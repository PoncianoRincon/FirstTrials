# Proyects
Used for showing coding examples of what I´ve done at work.  
The first project presented is:  
## Absenteeism  
This is from an HR experiment to try to predict the numer of hours a person will be absent and use it for work force management.  
Te code is contained in the folder: "Absenteeism_business_case" and is divided in the following files:  
* 01_Absenteeism_business_case.ipynb - This is the start of the process, where the following tasks take place:  
  * Data load and copy to avoid altering original source.  
  * Variable type check to see if any changes need to be made (like converting a string to a number).  
  * Check basic descriptive statistics.  
  * Delete columns that are not useful for modeling process.  
  * Grouping of variables that are useful for modeling but have too many categories.  
  * Dummy variable creation.  
  * Saving of new data created to file that will be used for modeling.  
* 02_Absenteeism_business_case_model.ipynb - This is where the modeling takes place under the following tasks:  
  * Data load.  
  * Create target variable for the model to predict.  
  * Drop variables that will not be used for modeling.  
  * Divide data into independent and target variables.  
  * Data standardization to avoid extreme values skew.  
  * Data split into training and testing groups for model development.  
  * Modeling using Logistic Regression algorithm (other models were used but are omitted due to contract restrictions).  
  * Model accuracy test calculating predictions on test data.  
  * Model algorithm extraction for implementation.  
  * Model results explanation for implementation.  
  * Model and scaler saved to pickle files for distribution.  
* 03_Absenteeism_module.ipynb - This file takes code from the previous files to create a single file that can be distributed and used by someone else to take data and make predictions without having to undergo the coding process.  
* 04_Absenteeism_module_predictions.ipynb - This is an example of how to use the module created in the previous steps.  
* Absenteeism-data.csv - Original data used for model development.  
* Absenteeism_module.py - Module created for distribution and implementation of the Logistic Regression model.  
* Absenteeism_new_data.csv - Data to demonstrate module use.  
* Absenteeism_predictions.csv - Data from predictions made using the model.  
* Absenteeism_preprocess.csv - Data created from the cleaning process in the first step.  
* model - pickle file with Logistic Regression model developed.  
* scaler - pickle file with custom scaler function used in model development.  
## Mental Health Prediction Using Machine Learning  
This is a work in progress that tries to classify someone needing treatment for mental health reasons. Different models are used like Logistic Regression, Lasso, Ridge, Elastic Net, Random Forests and Decision Trees.  
The files contained are:  
* Mental Health Prediction Using Machine Learning.ipynb - Where all the data loading, cleaning, and modeling takes place.  
* survey.csv - Raw data.  
* survey_clean.csv - Clean data used for training the models.  
