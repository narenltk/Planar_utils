===========
**Dataset**
===========

Let's get the dataset we will work on. The following code will load a "flower" 2-class dataset into variables X and Y.

.. code-block:: python

   X, Y = load_planar_dataset()

You can visualize the dataset with the help of matplotlib. The data will be like a "flower" with red and blue petals.

We need to build a model to fit this data.

First we need to make sense of the data which we have. We need to make use of Numpy

We have 

   - a numpy-array (matrix) X that contains your features (x1, x2)
   - a numpy-array (vector) Y that contains your labels (red:0, blue:1)

We need to make use of "Shape of the array".
