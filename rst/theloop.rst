============
**The Loop**
============

Instructions
============

- You can use the function sigmoid() . It is built-in (imported) in the notebook.
- You can use the function np.tanh() . It is part of the numpy library.
- Values needed in the backpropagation are stored in " cache ". The cache will be given as an input to the backpropagation function.

.. code-block:: python

   def forward_propagation(X, parameters):
       """
       Argument:
       X -- input data of size (n_x, m)
       parameters -- python dictionary containing your parameters (output of initial
       Returns:
       A2 -- The sigmoid output of the second activation
       cache -- a dictionary containing "Z1", "A1", "Z2" and "A2"
       """

       return A2, cache

Assert Variable
===============

.. code-block:: python

   assert(A2.shape == (1, X.shape[1]))

Formula
=======

.. math:: 


       J = (-1/m) sum_{i=0}^m (y^i log(a^{[2](i)}) + (1 - y^i) log(1 - a^{[2](i)})


Instructions
============

There are many ways to implement the cross-entropy loss, have a look at the example

.. code-block:: python

   logprobs = np.multiply(np.log(A2), Y)
   cost = - np.sum(logprobs)

**Note:-
You can use either np.multiply() and then np.sum() or directly np.dot())**

.. code-block:: python

   def compute_cost(A2, Y, parameters):
       """
       Computes the cross-entropy cost given in equation (13)
       Arguments:
       A2 -- The sigmoid output of the second activation, of shape (1, number of exam
       Y -- "true" labels vector of shape (1, number of examples)
       parameters -- python dictionary containing your parameters W1, b1, W2 and b2
       Returns:
       cost -- cross-entropy cost given equation (13)
       """

       return cost

m and cost Variable
===================

.. code-block:: python

   m = Y.shape[1]

   cost = np.squeeze(cost)



Expected Output
===============

   - cost 0.693058761..

Using the cache computed during forward propagation, you can now implement backward
propagation.

Using the cache computed during Forward Propogation, we need to implement Backward Propogation.

.. code-block:: python

  def backward_propagation(parameters, cache, X, Y):

       """
       Implement the backward propagation using the instructions above.
       Arguments:
       parameters -- python dictionary containing our parameters
       cache -- a dictionary containing "Z1", "A1", "Z2" and "A2".
       X -- input data of shape (2, number of examples)
       Y -- "true" labels vector of shape (1, number of examples)
       Returns:
       grads -- python dictionary containing your gradients with respect to different
       """

       return grads

Expected Output
===============

   This should throw up the values for dW1, db1, dW2, db2


