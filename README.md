# NeuralNet
This program is an implementation of a neural network with a single hidden layer (option to change number of hidden nodes).
Input is the MNIST digit recognizer dataset (handwritten digits 0-9).

Flow of program:

forward propogate:

input goes through input_to_hidden_weight_matrix,
hidden_layer activations go through hid_to_output_matrix--second weight matrix.

back propogate:

update output layer, 
update output to hidden weights, 
update hidden activation layer,
update input to hidden weights,
