# SpinGlass-GNN
In this work I implemented a Spin Glass model on a graph in order to perform two tasks: 
1. compare how a Graph Neural Network learn to predict the energy for a model with different number of connections;
2. compare the learning capability between a GNN and MLP (multlayer perceptron).

The project is organized as follow:
- task_1.ipynb: the notebook containing the functions to create the dataset, the GNN and to train it to predict the energy and the magnetization of the graphs;
- task_2.ipynb: the notebook containing the MLP model and his training;

- datasets: a directory to store all the dataset that has been created;
- n_nodes_10: a directory to store the various training, the models, the plots etc.. for the GNN

- MLP: a directory to store training, models etc. for the MLP

*Note*: all the files stored are encoded with a string with the following meaning:
"model_{n_nodes}_{n_dimensions}_{h}_{periodic}_{n_samples}_{hidden_channels_1}_{hidden_channels_2}_{hidden_channels_3}_{hidden_channels_4}_{hidden_linear}_{lr}_{weight_decay}_{dropout}_{epochs}"






