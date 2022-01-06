# Axioms Probability

We first have to define a probability space, a probability space consists of two elements, S and P, where S is a sample space and P is a function that takes some event E, 
where E ⊆ S, and outputs some P(E) ∈ [0, 1] such that the function P satisifes the following two axioms:

* 1.) The probability of the Sample Space is 1, P(S) = 1
* 2.) The probability of the Union of disjoint sets is equal to to the sum of the probabilities of the sets

![equation](https://latex.codecogs.com/png.image?%5Cdpi%7B110%7D%20%5Cinline%20P(%5Cbigcup_%7Bi=1%7D%5E%7B%5Cinfty%7D%20E_%7Bi%7D)%20=%20%5Csum_%7Bi=1%7D%5E%7B%5Cinfty%7DP(E_%7Bi%7D))

From these axioms we can derive a few basic corollaries:

# Complement Rule

The first axiom gives us P(S) = 1, let A and A_c be two sets that are mutually exclusive and satisfy the property

A ⋃ A_c = S

This means P(A ⋃ A_c) = 1, which by axiom two is equivalent to



