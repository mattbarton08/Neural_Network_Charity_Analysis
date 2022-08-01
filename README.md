# Neural Network Charity Analysis

## Overview of the analysis:

The purpose of this analysis was to create a binary classifier to predict whether a charity organization will be successful if given funding by Alphabet Soup.

## Results:

### Data Preprocessing
The target variable was whether the organization used the funding effectively. 

The feature variables were application type, affiliation, classifcation, use case, organization type, status, income amlount, special considerations, and the ask amount.

The EIN and name columns were neither targets nor features and were dropped from the data set before creating the model.

### Compiling, Training, and Evaluating the Model
My best performing model had three layers with 20, 10, and 8 neurons. I chose these after a kit if trial and error, as adding layers and neurons resulted in less accuracy.<br>

![neural_screenshit](https://i.imgur.com/U8Sqepl.png)

I was able to get better performance but not up to 75%. To increase performance, I added layers, neurons, and changed the activation funtion. I tried lots of different combinations of layers and neurons.

## Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
The machine learning model was able to predict fairly well whether a charity used money effectively. Another possible model that could be effective would be a random forest model, since the variable we are targeting can be measured with linear regression.
