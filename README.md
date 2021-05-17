# Neural Network Charity Analysis

## Overview of the analysis: 
The purpose of this project is to use neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.
We use preprocessed the data for the neural network model, compiled it, trained and evaluated the model, and then optimized the model.
## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
The column IS_SUCCESSFUL is considered as the target for our deep learning neural network.
The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model
The columns EIN and NAME are identification information and have been removed from the input data

### Compiling, Training, and Evaluating the Model
Layer 1 had 80 neurons; layer 2 had 30 neurons; layer 3 has 10 neurons and the relu and sigmoud activation functions were used
The model was unble to run do to an error with the T10 category
I added another hidden layer to try increase accuracy

## Summary: 
The deep learning neural network model did not reach the target of 75% accuracy. 
Since it is a  binary classification situation, a supervised machine learning model could be used and then be evaluated its performance against our deep learning model.
