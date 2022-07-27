***Features in a Dataset*** </br>
The dataset can be written in a table form where the number of rows- (i) in the superscript- will represent number of datasets and the number of columns- (j) in subscript - can be represented as number of features in it.
The concepts can be understood well with concept of basics of vectors and matrix.
The Parameters and Features can be represented in two ways:
a. With Vectorisation </br>
  w = np.array([1.0 , -2.1, -3.3])
  b = 2
  x = np.array([1, 2, 3])
b. Without Vectorisation </br>
  f = w[0] * x[0]  +  w[1] * x[1]  +  w[2] * x[2] + b

These can be the codes if the number of datasets are less, but what if they are thousands...? It would be very difficult to write all of them. Hence we use logic:

c. Without Vectorisation </br>
  f = 0
  for j in range (0,n):
    f = f + w[j] * x[j]
  f = f + b 
  
d. With Vectorisation </br>
  f = np.dot(w,x) + b
  
Vectorisation makes code easier to type and runs faster.</br>

In gradient descent:
e. Without vectorisation </br>
  f = 0
  for j in range (0,n):
  w[j] = w[j] - 0.1 * d[j]
  
f. With vectorisation:
  w = w - 0.1 * d
  

 
