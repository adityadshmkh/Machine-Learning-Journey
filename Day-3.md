***
**Visualising Cost function graph**
***
The primary objective of plotting a cost function graph is to know where does the minima of the graph lies, i.e. What should be the values of w,b so that, our model best fits the given data and predicts the data most closely.
The cost function graph can be plotted in two ways:
1. Contour: In this method you can observe concentric ovels with two axes of w & b.
2. Surface view: This type of graph shows the w & b in two axes and the cost function on the third axes, which makes it visually easier to spot the minima(of cost function).

We cannot everytime make a graph and visualise a graph to find the values of w & b to find a best fit models, so for that we have different algorithms which do our job to find the values of w & b so that the model is best fit.
***
**Gradient Descent**
This algorithm is widely used in the field of Machine Learning. This type of method is when one takes steps towards minimising the cost with small steps. We can visualise this by imagining a cost function which has valleys and hills and moving towards the minimum step by step. The step taken towards the minima can also lead to different minima if the direction is changed a bit and our goal is to find global minima.<br />
$w = w -$ $\alpha$ $\frac{\partial J}{\partial w}$<br />
$b = b -$ $\alpha$ $\frac{\partial J}{\partial b}$<br />
