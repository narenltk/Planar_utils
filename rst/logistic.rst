=======================
**Logistic Regression**
=======================

Logistic regression is a classification algorithm used to assign observations to a discrete set of classes. Unlike linear regression which outputs continuous number values, logistic regression transforms its output using the logistic sigmoid function to return a probability value which can then be mapped to two or more discrete classes.

The dataset is not linearly separable, so logistic regression doesn't perform well.

Types
=====

   - Binary (Pass / Fail)
   - Multi (Cats, Dogs, Sheep)
   - Ordinal (Low, Medium, High)


Sigmoid Activation
==================

The function maps any real value into another value between 0 and 1. In machine learning, we use sigmoid to map predictions to probabilities.

   - Math

.. math:: 

   S(Z) =  1 / ( 1 + (e^{-z}))

Graph
=====

.. image:: /img/sigmoid.png
   :height: 450px
   :width: 750px
   :scale: 50 %
   :align: left
