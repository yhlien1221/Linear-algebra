# Inverse matrices, column space and null space
## Linear equation
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_1.png)<br/>
- Coeffients, variables and constants
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_2.png)<br/>***
- Constant matrix A, vector and constant vector
<br><br/>
## The geometric meaning of Ax=v
- We need to find a solution for x which can be overlapped on v after linear transformation
- When the determinant of this transformation is not zero, it turns out that there will be one and only one vector that lands on v
## Inverse matrices
- Inverse transformation
- If a vector was transformed by A matrix, then A can be inversed by inverse A matrix.
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_3.png)<br/>
## For example, the inverse of 90 degree of anticlockwise is the 90 degree of counterclockwise.
- Inverse Transformation is the transformation required from V to go back to A (AInv A is Identity since it ends up doing nothing )
- Unless the the Determinant is Not ZERO the Determinant will Exist (if zero the area will be line and you cannot decompose back line back to area or volume through a single function)
- A Inverse X A is doing Nothing thus the Identity matrix
- Solution can Still exist if the Determinant is zero if the solution exist on the Same Line
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_4.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_5.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_6.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_7.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_8.png)<br/>
## Rank
- Rank is the number of dimensions in the output
- In 3D space, the input outputs a line after linear transformation, which is called **rank 1**.
- In 3D space, the input outputs a plane after linear transformation, which is called **rank 2**.
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_9.png)<br/>

## Column space
- This set of all possible outputs for your matrix after linear transformation, whether it's a line, a plane, 3d space, whatever, is called the column space of your matrix.

<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_10.png)<br/>
- The matrix tells where the base vectors lands
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_11.png)<br/>
- The span of those transformed basis vectors gives you all possible output.
- Span of Columns = Column Space
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_12.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_13.png)<br/>
- since linear transformations must keep the origin fixed in place
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_14.png)<br/>
- matrix of full rank, only origin will be in the same place after linear transformation.
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_15.png)<br/>
## Null space
- A linear transformation in 3D space, it squeeze 3D space on a line and there's a whole plane full of vectors that land on the origin.
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_16.png)<br/>
- The set of vectors that lands on the origin is called the null space or the kernel of the Matrix.
- The null space gives you all of the possible solutions to the equation
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_17.png)<br/>
- It can be judged by column space whether there is a solution in a equation
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/7_18.png)<br/>





<!-- ref
https://www.jianshu.com/p/75cfb1f3c7ed
https://harshityadav95.medium.com/notes-essence-of-linear-algebra-7d5388b2a940
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_14.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_15.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_16.png)<br/>
-->