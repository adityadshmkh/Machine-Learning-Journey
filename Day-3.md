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
Where $\alpha$ is very small value. It is also known as learning rate (we called it as a step in our discussion).<br />
In the gradient descent the values of w & b can be updated as follows:<br />
$temp_w =$  w - $\alpha$ $\frac{\partial J}{\partial w}$<br />
$temp_b =$  b - $\alpha$ $\frac{\partial J}{\partial b}$<br />
$w = temp_w$<br />
$b = temp_b$<br />
This is known as changing the values of the w & b simultaneously. This is done so that we get the minimum value of the cost function.<br />
The learning rate is always positive, hence the value of alpha is always positive the derivative term i.e. the slope of the tangent to the curve of the graph discussed above can be positive or negative. When it is positive, hence making an acute angle, it will decrease the value of w & b as the derivative part is positive and the new value will be decreased. When it is negative, hence making an obtuse angle, it will increase the value of w & b as the derivative part is negative and the new value will be increased.<br />
The learning rate should not be too small, if being so would take alot of time to reach the local minimum and even may not reach. The learning rate cannot be more than desired as it will the never reach the global minimum and will stay distracted. The learning rate should be as small and significant so that it gives the desired lowest cost function.<br />
***
