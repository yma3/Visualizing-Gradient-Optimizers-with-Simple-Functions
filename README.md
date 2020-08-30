# Visualizing-Gradient-Optimizers-with-Simple-Functions

Gradient descent is one of the fundamental principles in optimization that we use for machine learning. However, beginners looking to understand more about the field are met with graphs like this, \[insert image of parabola GD\], or contour plots like this \[contour plot here\]. Graphs like these give an initial intuition for what gradient descent is and what it does, but lack any further depth than an interesting picture. This is probably due to the highdimensionality of machine learning data requiring the ability to generalize these concepts. The goal of this notebook is to provide a more concrete example to build a stronger intuition on both how gradient optimizers work, and the behaviors of each.

### The notebook contains data generated from a linear function with noise. The goal of the optimization is to minimize the mean-squared error associated with a regression line drawn from two trainable parameters, the slope and intercept. Gradient descent, SGD, Minibatch GD, Momentum, RMSProp, and Adam are implemented and tested. A 3D plot of the cost surface and the paths the optimizers take at each epoch is plotted together. The notebook also contains details about each algorithm and implementation within each section.

## References
Insert refs here
