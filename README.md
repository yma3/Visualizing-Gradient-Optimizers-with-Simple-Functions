# Visualizing Gradient Optimizers with Simple Functions

![Gradient Optimizers](/images/gradientdescent.gif)
![Gradient Functions](/images/functions.gif)

## Purpose
Gradient descent is one of the fundamental principles in optimization that we use for machine learning. However, beginners looking to understand more about the field are met with generic graphs, or contour plots that relate only in the abstract sense. Graphs like these give an initial intuition for what gradient descent is and what it does, but lack any further depth than an interesting picture. The high-dimensionality of most machine learning models make it difficult to visualize for beginners. The goal of this notebook is to provide a more concrete example to build a stronger intuition on both how gradient optimizers work, and the behaviors of each. Hopefully, users can gain further insights from this notebook.

## Using the notebook
Running the entire notebook generates the plots shown in the GIFs above, which users can interact with to change the number of iteration steps, which optimizers to toggle, and change the angle on the 3D graph.

The notebook contains data generated from a linear function with noise. The goal of the optimization is to minimize the mean-squared error associated with a regression line drawn from two trainable parameters, the slope and intercept. Gradient descent, SGD, Minibatch GD, Momentum, RMSProp, and Adam are implemented and tested. A 3D plot of the cost surface and the paths the optimizers take at each epoch is plotted together. The notebook also contains details about each algorithm and implementation within each section.

The notebook was built with the following packages:
1. numpy (1.18.5)
2. matplotlib (3.3.2)
3. plotly (4.8.2)
