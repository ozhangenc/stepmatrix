# stepmatrix
Let Gr(k; n): Grassmannian variety of k-linear subspaces on n dimensional projective space P^n together with the Plücker embedding.

Let 1=f_1 f_2 f_3 ... f_d be a list of strictly increasing integers starting from 1 where d = (k+1)x(n-k).

This Python script generates step matrices out of the sequence 1=f_1 f_2 f_3 ... f_d if it exists.

In fact, the existence of a step matrix ouf of the sequence 1=f_1 f_2 f_3 ... f_d is equievalent to the existence of an irreducible supernatural vector bundle on Gr(k; n) with the root sequence 1=f_1 f_2 f_3 ... f_d.

# Example
Write n for the dimension of projective space: 5
Write k for the dimension of subspaces: 1
Enter the root list : 1 2 4 5 7 9 10 12
[[ 1  2  7  9]
 [ 4  5 10 12]]
 
 Process finished with exit code 0
