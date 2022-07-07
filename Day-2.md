**Linear Regression:**
There are many ways of predicting values for given dataset, the simplest one is linear regression. This model is used when the dataset are in the form of $(x^i,y^i)$ scattered 
in the cartesian plot and job is to predict $y^i$, for a given $x^i$. The dataset can be simplified by drawing a line through the data which will predict our output given as 
$y = mx + c$

**Some terminologies:**
* Training example: $(x^i , y^i)$ i -> *represent row in a table of training set*
* input variable: $x$ *(feature)*
* output variable: $y$ *(target variable)*
* m : number of training example

$f(x) = wx + b$

* Where $f(x)$ is a linear function and results in predicted value when input value $x$ in entered with two parameters $w$ & $b$.
***
**Cost Function**
$J(w,b)= 1/2m\sum_{n = i} (f_{wb}(x^i) - y^i)^2$
