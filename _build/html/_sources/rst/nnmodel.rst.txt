============
**NN Model**
============

The NN model should use previous functions in the right order.

.. code-block:: python
  
  def nn_model(X, Y, n_h, num_iterations = 10000, print_cost=False):
       """
       Arguments:
       X -- dataset of shape (2, number of examples)
       Y -- labels of shape (1, number of examples)
       n_h -- size of the hidden layer
       num_iterations -- Number of iterations in gradient descent loop
       print_cost -- if True, print the cost every 1000 iterations
       Returns:
       parameters -- parameters learnt by the model. They can then be used to predict
       """

       return parameters

Parameters initialized
======================

Initialize parameters, then retrieve W1, b1, W2, b2. Inputs: "n_x, n_h, n_y"

.. code-block:: python

   parameters = initialize_parameters(n_x, n_h, n_y)


Cost for every 1000 iterations

.. code-block:: python

   if print_cost and i % 1000 == 0:
       print ("Cost after iteration %i: %f" %(i, cost))


Expected output
===============

   - cost after iteration 0 - 0.692739

Then the value of W1, b1, W2, b2


