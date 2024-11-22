# deep-learning-challenge

# Background

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

# Requirements

Preprocess the Data (30 points)
Create a dataframe containing the charity_data.csv data , and identify the target and feature variables in the dataset (2 points)
Drop the EIN and NAME columns (2 points)
Determine the number of unique values in each column (2 points)
For columns with more than 10 unique values, determine the number of data points for each unique value (4 points)
Create a new value called Other that contains rare categorical variables (5 points)
Create a feature array, X, and a target array, y by using the preprocessed data (5 points)
Split the preprocessed data into training and testing datasets (5 points)
Scale the data by using a StandardScaler that has been fitted to the training data (5 points)

Compile, Train and Evaluate the Model (20 points)
Create a neural network model with a defined number of input features and nodes for each layer (4 points)
Create hidden layers and an output layer with appropriate activation functions (4 points)
Check the structure of the model (2 points)
Compile and train the model (4 points)
Evaluate the model using the test data to determine the loss and accuracy (4 points)
Export your results to an HDF5 file named AlphabetSoupCharity.h5 (2 points)

Optimize the Model (20 points)
Repeat the preprocessing steps in a new Jupyter notebook (4 points)
Create a new neural network model, implementing at least 3 model optimization methods (15 points)
Save and export your results to an HDF5 file named AlphabetSoupCharity_Optimization.h5 (1 point)

Write a Report on the Neural Network Model (30 points)
Write an analysis that includes a title and multiple sections, labeled with headers and subheaders (4 points)
Format images in the report so that they display correction (2)
Explain the purpose of the analysis (4)
Answer all 6 questions in the results section (10)
Summarize the overall results of your model (4)
Describe how you could use a different model to solve the same problem, and explain why you would use that model (6)

# Documents

The Analysis for the deep machine learning model is listed as "Analysis_Report". There are two different notebooks, the first is labeled "AlphabetSoup_Charity" and second is labeled "AlphabetSoupCharity_Optimization". The first notebook is where the preprocessing and first model were explored. The second notebook contains the optimization adjustments. 
