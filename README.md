# Coordinate-Descent
## Implementation of Coordinate Descent

Coordinate descent algorithms have recently been in use due to its higher efficiency to solve optimization problems by successively minimizing along each coordinate or coordinate hyperplane. It is quite similar to gradient descent except for the fact that, instead of moving all the coordinates along the gradient direction, at each iteration, only selected coordinate(s) are changed by the coordinate descent. The selected coordinate could be a single coordinate or even a batch of coordinates (BCD - Batch Coordinate Descent).

# Files
## Code
* Coordinate-Descent-Fixed-Step-Size.ipynb ---> Fixed step-size (large value) for Coordinate Descent
* Backtracking-line-search.ipynb ---> Adaptive step-size using the backtracking line search approach
## Data
* wine.data ---> Wine data. Also, found in sklearn library
## Write-up
* Coordinate-Descent.pdf ---> Mathematical approach and explanation
