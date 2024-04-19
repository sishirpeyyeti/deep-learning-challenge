# deep-learning-challenge
#The purpose of this analysis is to develop a deep learning model using TensorFlow and Keras to predict whether an organization funded by Alphabet Soup will be successful based on various features provided in the dataset. The analysis involves preprocessing the data, designing, compiling, training, and evaluating the neural network model, optimizing the model for better performance, and finally writing a report on the model's performance and suggesting potential improvements or alternative approaches.

Results:

Data Preprocessing:

Target Variable(s):

The target variable for our model is "IS_SUCCESSFUL," which indicates whether an organization funded by Alphabet Soup was successful (1) or not (0).
Feature Variable(s):

The features for our model include various columns from the dataset such as 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and others.
Variables to be Removed:

The 'EIN' and 'NAME' columns were removed from the input data during preprocessing as they do not provide useful information for predicting the success of an organization.
Compiling, Training, and Evaluating the Model:

Neurons, Layers, and Activation Functions:

The neural network model consists of two hidden layers with 80 and 30 neurons, respectively, along with ReLU activation functions. ReLU is chosen as it introduces non-linearity to the model and helps alleviate the vanishing gradient problem.
Achievement of Target Model Performance:

The model was able to achieve an accuracy of approximately 72.61% on the test dataset.
Steps Taken to Increase Model Performance:

During the optimization process, various methods were implemented such as adjusting the preprocessing steps, changing the number of neurons and layers, experimenting with different activation functions, and adjusting the number of epochs for training the model.
Summary:

In summary, the deep learning model developed for predicting the success of organizations funded by Alphabet Soup achieved an accuracy of around 72.61%, which falls short of the target performance threshold. While several optimization methods were attempted, further improvements are needed to enhance the model's performance. Unfortunately, I do not have the expertise or time to do so. 
