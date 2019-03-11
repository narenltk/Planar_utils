============
**Packages**
============

Let's first import all the packages that you will need during this assignment.

Numpy
=====

NumPy can be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.

.. code-block:: python
  
   import numpy as np

Sklearn
=======

Simple and efficient tools for data mining and data analysis. Built on NumPy, SciPy, and matplotlib.

.. code-block:: python

   import sklearn
   import sklearn.datasets
   import slkearn.linear_model
   
Matplotlib
==========

Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.

.. code-block:: python

   import matplotlib.pyplot as plt

Planar_utils
============

Python Utils is a collection of small Python functions and classes which make common patterns shorter and easier. It is by no means a complete collection but it has served me quite a bit in the past and I will keep extending it.

.. code-block:: python

   from planar_utils import plot_decision_boundary, sigmoid, load_planar_dataset, load_extra_datasets

testCases
=========

testCases provides some test examples to assess the correctness of your functions. This is another py file that's imported here.

.. code-block:: python

   from testCases import *


