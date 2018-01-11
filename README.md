# California-House-Price
Predicting the california housing price using the Estimator API of Tensorflow.

For this project, data is collected from http://www.liaad.up.pt/~ltorgo/Regression/DataSets.html.

In this project, Data is scaled first using the MinMaxScaler from sklearn. Then using the Estimator API, I have created the Linear and Dense neural network models for predicting the prices of the house. Average loss metric is used to identify if the model is overfitting the data. Finally, error is calculated to identify the best model for predicting the house price.
