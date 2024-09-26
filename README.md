# nerual-network

  this a simple guide for building nerual network

## description
we have two files neraul1 and neural2, neural1 simply predict numbers depend on an input and output
neural2 do this but in much complex way, i will use numpy as a library for this.

## variables definition
X: Input dataset matrix where each row is a training example
y: Output dataset matrix where each row is a training example
l0: First Layer of the Network, specified by the input data
l1: Second Layer of the Network, otherwise known as the hidden layer
synO: First layer of weights, Synapse 0, connecting l0 to l1.
*: Elementwise multiplication, so two vectors of equal size are multiplying corresponding values 1-to-1 to generate a final vector of identical size
-: 	Elementwise subtraction, so two vectors of equal size are subtracting corresponding values 1-to-1 to generate a final vector of identical size
x.dot(y): If x and y are vectors, this is a dot product. If both are matrices, it's a matrix-matrix multiplication. If only one is a matrix, then it's vector matrix multiplication.
