# NeuralNet
This program is an implementation of a neural network with a single hidden layer (option to change number of hidden nodes).
Input is the MNIST digit recognizer dataset (handwritten digits 0-9).

Flow of program:

  Forward propogate:

    input goes through input_to_hidden_weight_matrix,


    hidden_layer activations go through hid_to_output_matrix--second weight matrix.

  Back propogate:

    update output layer, 


    update output to hidden weights, 


    update hidden activation layer,


    update input to hidden weights.


To Run File:
- Install Jupyter Notebook: If you haven't installed Jupyter Notebook on your computer, you can do so by following the instructions on their website: https://jupyter.org/install
- Open Jupyter Notebook: Once you have installed Jupyter Notebook, open it by typing jupyter notebook in your terminal or command prompt.
- Navigate to the directory containing the .ipynb file: In Jupyter Notebook, navigate to the directory where the .ipynb file is located.
- Open the .ipynb file: Click on the .ipynb file to open it in Jupyter Notebook.
- Run the code: You can run the code in the .ipynb file by clicking on the "Run" button or by pressing "Shift + Enter" on your keyboard. You can also run all the code in the notebook by clicking on "Cell" in the menu bar, then "Run All."

