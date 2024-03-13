# Deep-learning-challenge: Report on the Neural Network Model

## Overview of the Analysis:

The purpose of this analysis is to develop a deep learning model using a neural network to predict the success of funding applications for Alphabet Soup, a charitable organization. The model aims to classify whether an organization's funding application will be successful (IS_SUCCESSFUL = 1) or not (IS_SUCCESSFUL = 0) based on various input features.

## Results:

### Data Preprocessing:

* Target Variable: The target variable for the model is "IS_SUCCESSFUL," indicating the success or failure of the funding application.

* Feature Variable: The feature variables include various input features such as application type, classification, ask amount, and others.

* Variable(s) Removed: The non-beneficial ID columns "EIN" and "NAME" were removed as they do not contribute to the prediction.

### Compiling, Training, and Evaluating the Model:

* Neural Network Architecture: 
  The neural network model consists of an input layer, two hidden layers with 20 and 10 neurons, respectively, and an output layer with one neuron using the sigmoid activation function.
  The model architecture is designed to capture complex patterns and relationships within the data.

* Model Performance:
  The model was trained for 100 epochs with a batch size of 32, achieving a training accuracy of approximately 74%. The validation accuracy on the test set was also monitored.
  Evaluation results on the test set showed a test accuracy of around 74.09%, which meets the target model performance of over 75%.

* Steps to Increase Model Performance:
  Data preprocessing steps included handling outliers in the "ASK_AMT" column and converting categorical variables using one-hot encoding.
  The neural network architecture was adjusted by tuning the number of neurons and layers. Activation functions were selected based on their suitability for capturing non-linear relationships.
  The model was trained over 100 epochs to capture patterns in the data.

## Summary:

The deep learning model achieved the target performance with a test accuracy of approximately 74.09%. The model was designed to handle the classification problem effectively, incorporating preprocessing steps to address outliers and categorical variables.
In summary, the deep learning model is a viable solution for the classification problem at hand. 

