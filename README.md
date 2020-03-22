# COVID-19-Infection-Predictor
it consist of a ML model which predicts the chances of being infected by corona virus to a person.

For probability prediction, I have used a deep neural network, which consists of a total of 4 layers.
Layer 1) 64 neurons, activation function : relu (Input Layer)
Layer 2) 32 neurons, activation function : relu (Hidden Layer)
Layer 3) 16 neurons, activation function : relu (Hidden Layer)
Later 4) 1 neuron (output layer)

I have used TensorFlow for creating my model on the Colaboratory platform.
Optimizer: RMSprop with Learning rate: 0.0005
Loss metrics: Mean Absolute Error(MAE)
Evaluation metrics: Mean Absolute Error(MAE), Mean Squared Error(MSE)

Model is trained for 1000 EPOCHS and validation split is 20%

I have converted categorical features to One Hot Encoding and then normalized whole data for better accuracy.

Data preprocessing:-
Given training and test data is stored in pandas dataframe.
I have converted categorical features to One Hot Encoding and then normalized whole data for better accuracy.
Some feature columns that are not much responsible for Infection probability are removed before putting data into the model.

People Id and their respective Infection Probability is stored is a CSV file and downloaded. 

all the required dataset and files are present in the repo.
