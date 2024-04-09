# TidePredictionusingGRU
The objective is to evaluate the performance of various models for predicting tide time-series data at the BHP location. For this analysis, three different models were chosen to predict tide time-series data:

Model 1: Simple GRU

For the first model, a simple GRU (Gated Recurrent Unit) architecture was implemented. The GRU model is a type of recurrent neural network (RNN) that is well-suited for sequential data processing. In this configuration, a single layer of GRU units was utilized to predict the tide time-series data.

Model 2: GRU with Different Units and Layers

The second model involved experimenting with the architecture of the GRU model by varying the number of units and layers. This model aimed to investigate the impact of increasing the complexity of the network on prediction performance. Different configurations of GRU units and layers were tested to determine the optimal architecture for predicting tide data.

Model 3: GRU with Different Activation Function

In the third model, the activation function used within the GRU units was modified to explore its effect on prediction accuracy. The activation function plays a crucial role in controlling the output of neural network nodes. By testing different activation functions such as tanh, sigmoid, or ReLU (Rectified Linear Unit), the model sought to identify the most suitable activation function for the tide prediction task.

![image](https://github.com/dhrutijoshi11/TidePredictionusingGRU/assets/101862826/c97a9bc6-02f6-4825-8acd-bb1fe864643c)
Dataset:
The location is BHP.  The data for training is BHPtraining.csv, which holds 2017-2019 data and for testing BHPtest.csv which holds 2020 data.
![image](https://github.com/dhrutijoshi11/TidePredictionusingGRU/assets/101862826/9021b6ed-5f46-4b13-9e47-e1e7a0c55ec6)
