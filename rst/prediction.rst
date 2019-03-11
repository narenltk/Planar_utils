==============
**Prediction**
==============

.. math::

   y_{prediction} = 1(activation > 0.5)

As an example, if we would like to set the entries of a matrix X to 0 and 1 based on a threshold we
need to:

.. math:: 

   X_{new} = (X > threshold)

.. code-block:: python

   def predict(parameters, X):
       """
       Using the learned parameters, predicts a class for each example in X
       Arguments:
       parameters -- python dictionary containing your parameters
       X -- input data of size (n_x, m)
       Returns 
       predictions -- vector of predictions of our model (red: 0 / blue: 1)
       """

       return predictions


Accuracy
========

.. code-block:: python

   predictions = predict(parameters, X)

Expected Output
===============

   - Cost after iteration 9000 0.218607
   - Accuracy 90 %

**Accuracy is really high compared to Logistic Regression. The model has learnt the leaf patterns of
the flower! Neural networks are able to learn even highly non-linear decision boundaries, unlike
logistic regression.**
