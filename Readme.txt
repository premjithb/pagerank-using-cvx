This is a simple implementation of pageranking algorithms using cvxpy, a python tool for convex optimization. 

Here, pagranking is considered as a convex optimization problem and used cvxpy to compute the page rank for each page in the 
network.

The pagerank for each page will be stored in the eigen vector corresponding to the highest eigen value (that is 1) of the 
link matrix (a stochastic matrix) after a number of iterations.

Author: Premjith B, Center for Computational Engineering and Networking (CEN), Amrita Vishwa Vidyapeetham, Coimbatore
