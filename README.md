# deep-learning-challenge

# Report on the Neural Network

## Analysis Overview

The purpose of the analysis is to create a deep learning neural network model to predict whether or not the charities were successful when applying for the grant. The information that we used to train this model was from the charities data csv file as shown below.

![image](https://user-images.githubusercontent.com/114998403/230673333-6fab1109-5f45-4a67-8cb9-213a7a27c5ac.png)


## Results


### Data Preprocessing

The variabe the tos the target for this model is the IS_SUCCESSFUL variable as that is the variable that we are looking to predict using our model. The Faetures of the model are the remaining columns in the dataframe execpt for the IS_SUCCESSFUL variable as that is the target. I have also removed the EIN column as this is neither a target or a feature of this dataset.


![image](https://user-images.githubusercontent.com/114998403/230673531-fdd6d84b-12a3-4aee-86b6-a5062443d074.png)

### Compiling, Training, and Evaluating the Model


After optimising this model I have used 6 layers in the Neural network which consit of a total of 420 nodes. The model that I have used consists of the relu activation function before finally going to a sigmoid activation function as well are doing classification. I have used the relu function as this gave me the best results when comparing to the other activation functions and also because  it does not activate all the neurons at the same time.

![image](https://user-images.githubusercontent.com/114998403/230674018-bede3437-dfda-41df-b483-61d8e5cbc836.png)


My model has achieved over the target model performance achieving nearly 79% accuracy. In order to increase my model performance, I have reduce the amount of columns that were dropped, changed the classifaction bins to include more information, increased the amount of layers and nodes, change the activation functions and also reduced the number of epochs.

![image](https://user-images.githubusercontent.com/114998403/230674544-55831448-efa3-4337-a4cd-09891bf65abc.png)


## Summary

The overall result of my model were very positive a achieving well over the target performance. I would also recommend a logistic regression model to solve this classifcation problem. Logistic regression estimates the probability of an event occurrin, based on a given dataset of independent variables therefore would be suitable for this classification problem.


