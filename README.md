# Pesudo-Code-of-Sort-an-Array
Here , I am providing Pseudocode for 3 Elementary Sort Algorithms by using 
Selection Sort
Suppose A is an array of N values. We want to sort A in ascending order. That is, A[0] should be the smallest and A[N-1] should be the largest.

The idea of Selection Sort is that we repeatedly find the smallest element in the unsorted part of the array and swap it with the first element in the unsorted part of the array.

     For I = 0 to N-1 do:
       Smallsub = I
       For J = I + 1 to N-1 do:
         If A(J) < A(Smallsub)
           Smallsub = J
         End-If
       End-For
       Temp = A(I)
       A(I) = A(Smallsub)
       A(Smallsub) = Temp
     End-For
A refinement of the above pseudocode would be to avoid swapping an element with itself.

An alternate way to sort in ascending order is to find the largest value and swap with the last element in the unsorted part of the array.

Selection Sort does roughly N**2 / 2 comparisons and does N swaps.

