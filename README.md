# Neural_Network_Charity_Analysis
## Overview of Project
In Neural network Analysis project we are applying the skills of preprocessing the data for the neural network model, compile, train, evaluate and then optimize the model. Pandas and Scikit-Learn’s standard scaler is used to preprocess the dataset in order to compile, train and evaluate the neural network model using TensorFlow.


## Analysis
Preprocessing included dropping the EIN and NAME column, unique values were determined for each column and then number of datapoints were determined for those unique values. Density plot was taken to determine the distribution.

![ images/density_plot]( images/density_plot.png)

![ images/density_plot1]( images/density_plot.png)

Categorical variables are encoded using one-hot encoding and variables are placed in dataframe

![images/preprocessing]( images/preprocessing.png)

![images/AphabetCharityanalysis]( images/AphabetCharityanalysis.png)

Model is optimized using increasing neurons and activation functions has been changed, noisy variables have been removed in all three attempts.

![ images/AlphabetSoupCharity_Optimization1]( images/AlphabetSoupCharity_Optimization1.png)

![ images/AlphabetSoupCharity_Optimization2]( images/AlphabetSoupCharity_Optimization1.png)

![ images/AlphabetSoupCharity_Optimization3]( images/AlphabetSoupCharity_Optimization1.png)



## Summary:
Maximum accuracy achieved through optimization was around 73%. More experimentation should be done on optimizing the model to achieve our target of 75% accuracy.
