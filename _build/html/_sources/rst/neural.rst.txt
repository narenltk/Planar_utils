==================
**Neural Network**
==================

Neural networks, with their remarkable ability to derive meaning from complicated or imprecise data, can be used to extract patterns and detect trends that are too complex to be noticed by either humans or other computer techniques. A trained neural network can be thought of as an "expert" in the category of information it has been given to analyse. This expert can then be used to provide projections given new situations of interest and answer "what if" questions.


   * What are neurons in NN ?
     The Neuron is nothing more than a set of inputs, a set of weights and an activation function. The Neuron translates these inputs into a single output, which can then be picked up as a input for another layer of neurons later on. 

Logistic Regression didn't work well with "Flower Dataset". So now we are going to train NN with a single hidden layer.

Mathematically
==============

For one example,

.. math:: 

  z^{[1](i)} = W^{[1]}x^{(i)} + b^{[1]}

  a^{[1](i)} = tanh(z^{[i](i)}

  z^{[2](i)} = W^{[2]}a^{[i](i)} + b^{[2]}

  y`^{i} = a^{[2](i)} = sigma(z^{[2](i)})

Problem Statement
=================

According to this model the following are the parameters to be noted,

   - Hidden Layer is of Size 4 
   - Input Layer has 2 inputs
   - Output Layer has Activation Function as Sigmoid
   - Hidden Layer has Activation Function as tanh
