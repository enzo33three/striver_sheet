# striver_sheet

Striver SDE Sheet is a curated list of 590 coding problems designed to master Data Structures and Algorithms (DSA). It covers arrays, graphs, DP, recursion, and more, helping you crack top FAANG interviews efficiently. This sheet ensures structured practice for coding interviews and competitive programming. 🚀


# Table Of Content
- [Table Of Content](#table-of-content)
- [Array](#array)
  - [1 Set Matrix Zero](#1-set-matrix-zero)
  - [](#)



  <!-- - [](#) -->
 



# Array 
## [1 Set Matrix Zero]()

<h4>Logic :</h4>


> - mark starting of row and column to be zero for current i,j for example if
> - matrix[i][j] == 0 mark matrix[i][0] = 0 and matrix[0][j] = 0 now traverse
> - for specific row and column for mark the entire for and entire colum zero.
> - special case first element [0][0]; </br></br>
>   Time  -> O(N*N) + O(N) + O(N)   </br>
>   Space -> O(1)

[Code Link](./Arrays/01-set-matrix-zero.cpp)