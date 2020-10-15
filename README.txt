How many neurons and layers did you select for your neural network model? Why?
For the input layer, I added the number of input features equal to the number of variables in the feature DataFrame.
In the hidden layers I added two hidden layers with only a few neurons in each layer. I added another Keras Dense class while defining our model for our second hidden layer. All of our hidden layers will use the relu activation function to identify nonlinear characteristics from the input values.
In the output layer, I used the same parameters from our basic neural network including the sigmoid activation function. 
The sigmoid activation function will help us predict whether or not an applicant will be successful if funded by Alphabet Soup.

Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
The model was able to correctly identify applicants who will be successful if funded by Alphabet Soup ~73% of the time. I was not able to optimize my model training to target a predictive accuracy higher than 75%.
However, the deep learning model was able to produce a fairly reliable classifier. 
I tried doubling the epochs from 100 to 200. When compared to the previous deep learning model, this model produced a similarily reliable classifier. 
This models accuracy was Accuracy: 0.7259474992752075, while the previous model was Accuracy: 0.7250145673751831.

If you were to implement a different model to solve this classification problem, which would you choose? Why?
I would us a Random forest classifier because random forest classifiers are a type of ensemble learning model that combines multiple smaller models into a more robust and accurate model. 
They use a number of weak learner algorithms and combine their output to make a final classification decision. Both output and feature selection of random forest models are easy to interpret, and they can easily handle outliers and nonlinear data.
