# Predicting-Absenteeism-at-work

## Data Description
“Absenteeism at work” dataset was constructed with the sole purpose of predicting absent behaviour of the employees. Employees/workers are the backbone of any business. The unavailability of employee has direct drastic effects on the performance of the company. Employees on leave could cause a huge lose to company’s efficiency and profit. Its effects could be worst in case company don’t have alternatives for absent works. Absence of a worker from the job could because of a number of different factors. If we could predict the absent behaviour of the employees ahead, a huge lose to company’s efficiency and profit could be avoided.     

## Objective
The aim of the classification is to train a model that will predict the future absent behaviour of the employees with high accuracy.

## Neural Networks
Neural network is a famous, accurate and versatile classifier. We trained a NN and tested various settings to find the best results.
### Network Topology.
The architecture of the neural network is of vital importance. The network topology deals with the number of hidden layers, number of neutrons in the hidden layers, number of input units and number of output units in the output layer. We tested a range of topologies and their results are gievn in the results section below.
The neural network is implemented in the R programming language using the “neuralnet” package. 
### Implimentation
The data is loaded from the csv file and normalised. The data is split into 60% training and 40% testing data. The neural network is create with 20 input values and output one value, which is the predicted class attribute. It the best network topology is achieve through test and trial method. The performance of the network is measure by measuring the root mean square error. The network is tried for different topologies and the best one is selected and is shown below. 
[Neural Network](NN.png)

## Results
The different topologies of the network is tested that vary in number of hidden layer and number of neuron in them. The following table shows the network with different topologies and their respective root mean square errors. 
[Topology](results.png)

The best accuracy of the network is achieved with two hidden layers with 8 and 4 neurons respectively. The predicted values by model is plot by scatter plot. The straight line is the ideal line whereas the RMSE is the distance of predicted values from this line. 
[Plot](NN_result.png)
