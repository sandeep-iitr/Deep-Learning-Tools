# Fundamental Problem: Solve the system of linear equations.


## Different ways to look at this problem in Matrix form
- Row picture and column picture of the equations.
- Row picture is what we do in traditional matrix equations.
- In column picture, we are asking to find the linear combination of the columns (column vectors) to find the solution vector. 

---
 
 - Can we solve AX=B, for every B ?
 - Every B, means all the B in three dimensional space. 
 - The answer might depend on A. How could the answer become No.
 - When are we not able to produce the B. A can be considered as a vector with three columns. If any two columns of A lie in the same plane, then the answer is no. Because, any combination of two columns will still be in same plane, and we might not be able to solve the equation for all B.
 
 ---
 - In higher dimensional space, too the same logic works. The answer will depend on the vector columns of A. If all the columns vectors of A are independent, then they then fill out all the higher dimensional space. Else they are not able to fill the entire higher space. By filling we mean their some combination can fill it up. 
 
 ---
 - Different way to consider matrix multiplication. One way is to consider linear combinations of different vectors and then add them. This linear combination of columns is what is generally not used by us, and row by column multiplications is more common.
