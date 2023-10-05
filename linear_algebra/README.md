# Description:

We are given a sensitive data of an insurance company. 
It will be used to run a linear regression model on. 
However, the data must be protected before any work can be done on it.
This project deals with the problem of data protection

# Solution:

Multiplying the feature matrix by an invertible matrix will change the weights of the linear regression model, but not its predictions.
This means that the quality of the model will not change. 

The algorithm for protecting customer data can be described as follows:

1. creating a random square matrix with the dimension of the number of features
2. checking it for its inverse: if determinant is 0, then create a new matrix
3. multiplying the feature matrix by the generated matrix
4. checking for a significant difference between the resulting matrix and the original one: if it is close to zero, then create a new matrix
5. solving linear regression model

This algorithm will protect customer data, since without knowledge of the generated matrix it is difficult to derive the original data. 
Linear regression results will not change.
