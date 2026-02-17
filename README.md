Problem 1: This algorithm calculates the sum of all distinct elements between two sets represented using arrays.
An element is considered distinct if it appears in only one of the two arrays and not in both.

The algorithm first reads the sizes of the two arrays and initializes them by storing their elements.
It then compares each element of the first array with the elements of the second array using a nested loop.
If an element from the first array is not found in the second array, it is added to the sum.

The same process is repeated in the opposite direction by checking elements of the second array against the first one.
Finally, the algorithm outputs the total sum of all elements that are present in either of the two arrays but not in both.


Problem 2: This algorithm determines whether pairs of vectors in ℝⁿ are orthogonal by computing their dot (scalar) product.

Each vector is represented using an array of real numbers.
A procedure (or function) named dot_product is defined to calculate the scalar product of two vectors by multiplying corresponding components and summing the results using a loop.

For each given pair of vectors, the algorithm initializes the vectors and calls the dot_product procedure (or function).
If the resulting dot product is equal to zero, the vectors are considered orthogonal; otherwise, they are not orthogonal.

The algorithm repeats this process for all given vector pairs and displays whether each pair is orthogonal or not.
