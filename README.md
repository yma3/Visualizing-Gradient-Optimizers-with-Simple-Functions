<<<<<<< HEAD
# Visualizing Gradient Optimizers with Simple Functions
![Gradient Optimizers](/images/gradientdescent.gif)
![Gradient Functions](/images/functions.gif)

## Purpose
This notebook shows how a series of gradient optimizers work and converge to the minima of a simple loss function, and how it can be used to train machine learning models. The purpose of this notebook is to educate as well as allow for users to experiment with their own functions, and ultimately gain some insight on the performance and the behavior of these optimizers.

## Using the notebook
The notebook contains information about each optimizer and builds each from scratch with simple mathematical operations. Running the entire notebook generates the plot shown in the screenshot above, which users can interact with to change the number of iteration steps, which optimizers to toggle, and change the angle on the 3D graph.

The notebook was built with the following packages:
1. numpy (1.18.5)
2. matplotlib (3.3.2)
3. plotly (4.8.2)
=======
# Visualizing-Gradient-Optimizers-with-Simple-Functions

Gradient descent is one of the fundamental principles in optimization that we use for machine learning. However, beginners looking to understand more about the field are met with graphs like this, \[insert image of parabola GD\], or contour plots like this \[contour plot here\]. Graphs like these give an initial intuition for what gradient descent is and what it does, but lack any further depth than an interesting picture. This is probably due to the highdimensionality of machine learning data requiring the ability to generalize these concepts. The goal of this notebook is to provide a more concrete example to build a stronger intuition on both how gradient optimizers work, and the behaviors of each.

### The notebook contains data generated from a linear function with noise. The goal of the optimization is to minimize the mean-squared error associated with a regression line drawn from two trainable parameters, the slope and intercept. Gradient descent, SGD, Minibatch GD, Momentum, RMSProp, and Adam are implemented and tested. A 3D plot of the cost surface and the paths the optimizers take at each epoch is plotted together. The notebook also contains details about each algorithm and implementation within each section.

## References
Insert refs here
>>>>>>> fe74d4b7ea2f187711b2209b65a5f307dec4a686
