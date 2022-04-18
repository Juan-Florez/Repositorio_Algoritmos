Goal:
The goal of this work is to compare and face brute force algorithms with greedy algorithms for the problem of find the roots of a polynom

Complexity:
Taking n as the size of the interval for find the answer the complexity of the brute force algorithm is O(n^2), complexity O(n) to evaluate the function in the interval and complexity O(n) to get the minimum value (O(n)*O(n) = O(n^2)).
For other size taking as a reference the time complexity of binary search trees we can get intuetively a complexity of O(log(n)) for the bisection algorithm, given that in some degree we are doing a binary search.

Execution time:
brute force = 524.3106138706 seconds
bisection algorithm = 0.0015826225 seconds
