
# Neural-Network-Project

Deep learning project using Neural networks to predict Customer Loyalty

We are seeing how different attributes [like age, salary, tenure etc] have importance in predicting if a customer is likely to exit or not

All project related documents like architecture of model, accuracy of model can be visualised through pictures under the folder Project_Pictures in the repository



## Processes 

- ### Acquiring Data Set
We acquire the data set from kaggle

The data set is of a bank having various information about a customer

It can be found in the repository under the name **Data_Set.csv**

You can also visit the original data set by clicking [Here](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers) 

- ### Cleaning Data Set

First We have to address the problems in the data Set

#### Unwanted Columns

#### Gender (classification in text)

#### Geography
(Have to extrapolate Values in columns into its own seperate columns)

#### Scaling

We adress all these using python libraries (Pandas, NumPy)


- ### Constructing Model Architecture

We create a Sequential model using keras

- ### Training Model against data
We train our model were it decides weight and other parameters on fed data




## How the model Does. . .

![App Screenshot](https://github.com/FreakQnZ/Neural-Network-Project/blob/622db9d326aa63bcb7002f357933284f3439cc90/training_metrics.png)


## Main vs Weights

There are 2 jupyter notebooks

Main and weights.

Main is our original model while weights is a model we have constructed to draw inferences from

In our weights model a simple 12 input shape to a single neuron output with sigmoid activation is created

From this we can get to know the individual weights of each factor and make predictions on which factor has more precedence in calculating customer loyalty
## Results from Weights

![App Screenshot](https://github.com/FreakQnZ/Neural-Network-Project/blob/8e5eaa257b02c494f68d789bd74440755d1221c3/weights_info.png)


Exited is denoted by 1 and loyalty is denoted by 0.

So features whose value tend to be near 0.5 dont have tht much of an importance in predicting customer loyalty, and as the value deviates more towards 0 or 1, it favours the corresponding status of loyalty or exit