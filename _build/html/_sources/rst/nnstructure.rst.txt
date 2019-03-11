=====================================
**Defining Neural Network Structure**
=====================================

Here we need to define 3 variables namely, 

   - n_x: the size of the input layer
   - n_h: the size of the hidden layer
   - n_y: the size of the output layer

**Hint: use shapes of X and Y to find n_x and n_y**

.. code-block:: python

   def layer_sizes(X, Y):
       """
       Arguments:
       X -- input dataset of shape (input size, number of examples)
       Y -- labels of shape (output size, number of examples)
       Returns:
       n_x -- the size of the input layer
       n_h -- the size of the hidden layer
       n_y -- the size of the output layer
       """

       return (n_x, n_h, n_y)


Expected Output
===============

n_x - 5
n_h - 4
n_y - 2


