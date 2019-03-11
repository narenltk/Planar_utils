===============================
Initialise the model parameters
===============================

Instructions
============

- Make sure the parameters' sizes are right. Refer to the doc above.
- we need to initialize the weights matrices with random values.
   - Use: np.random.randn(a,b) * 0.01 to randomly initialize a matrix of shape (a,b).
- You will initialize the bias vectors as zeros.
   - Use: np.zeros((a,b)) to initialize a matrix of shape (a,b) with zeros.


.. code-block:: python

   def initialize_parameters(n_x, n_h, n_y):
       """
       Argument:
       n_x -- size of the input layer
       n_h -- size of the hidden layer
       n_y -- size of the output layer
       Returns:
       params -- python dictionary containing your parameters:
       W1 -- weight matrix of shape (n_h, n_x)
       b1 -- bias vector of shape (n_h, 1)
       W2 -- weight matrix of shape (n_y, n_h)
       b2 -- bias vector of shape (n_y, 1)
       """
       
       return parameters

Expected Output
===============

W1, b1, W2, b2 --> some values


