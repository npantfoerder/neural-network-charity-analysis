# Neural Networks and Deep Learning Models

## Overview of the Analysis
### Purpose
A hypothetical nonprofit foundation, Alphabet Soup, needs help analyzing the impact of their donations and vetting potential recipients by predicting which organizations are worth donating to and which are too high risk. I designed a deep learning neural network that evaluates all types of input data and produces a clear decision making result using the Python TensorFlow library.

## Results
### Data Preprocessing
- The IS_SUCCESSFUL column is considered the target for my model.
- The APPLICATION_TYPE,	AFFILIATION,	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	INCOME_AMT,	and ASK_AMT	columns are considered to be the features of my model.
- The EIN, NAME, STATUS, and SPECIAL_CONSIDERATION columns are neither targets nor features and should be removed from the input data. <br>
<kbd> <img src='https://github.com/npantfoerder/neural-network-charity-analysis/blob/master/Images/.png' width=700> </kbd> 
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I selected 80 neurons with a sigmoid function for my first layer, 30 nuerons with a ReLU function for the second, and 10 neurons with for the third, and a sigmoid function for the outer layer. I chose to change the activation function for the first layer because it increased the model's performance. 
- I only achieved an accuracy of 70% and was not able to achieve the target model performance.
- What steps did you take to try and increase model performance?
- I tried to increase the model performance by dropping more columns, creating more bins for rare occurances in columns, decreasing the number of values in some bins, using a differnet activation function, and adding/reducing the number of epochs. <br>
<kbd> <img src='https://github.com/npantfoerder/neural-network-charity-analysis/blob/master/Images/.png' width=700> </kbd>

## Summary
*Summarize the overall results of the deep learning model*
### Recommendation
A random forest model could solve this classification problem by

#### Resources
- Data Sources: charity_data.csv
- Software: Python 3.7.3, Anaconda 4.8.3, TensorFlow 2.3.1, Scikit-learn 0.23.1
