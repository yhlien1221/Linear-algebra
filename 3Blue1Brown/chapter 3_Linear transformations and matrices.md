# Linear transformations and matrices
## Linear transformations
* a function that takes an input and gives an output
* input a vector and then get a new vector with new position
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_1.png)<br/>
* input vectors
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_2.png)<br/>
* output vectors
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_3.png)<br/>
* input vectors (only consider points)
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_4.png)<br/>
* output vectors (only consider points)
## Two features of linear transformation
<br>After transformation<br/>
1. All lines are lines
2. Origin won't be changed
## Describe linear transformation numerically
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_5.png)<br/>
* we can use v vector to describe "????"
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_6.png)<br/>
<br>----------------------------------------------------------<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_7.png)<br/>
* Transformed v vector is equal to -1*transformed i vector plus 2 times transformed j vetor.
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_8.png)<br/>
* i from [1,0] to [1,-2]
* j from [0,1] to [3,0]
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_9.png)<br/>
* calulated transformed v vector
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_10.png)<br/>
* any point on the flat can be put into this transformation to get a new position.
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_11.png)<br/>
* There is a 2*2 Matrix. First row represents new i and second row is new j. Now we have vector [5,7], then we can do linear transformation by this vector and matrix. The meaning of this linear transformation is that we use new i,j as new base and keep the same scalars.
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_12.png)<br/>
* Formula for this concept that we mentioned in the last graph.
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_13.png)<br/>
* Tranformed vector will be on the same line of original vetor if there was linear dependent between original vector and tranformed vector. 


<!-- ref
https://www.jianshu.com/p/75cfb1f3c7ed
https://harshityadav95.medium.com/notes-essence-of-linear-algebra-7d5388b2a940
https://zhuanlan.zhihu.com/p/59137639
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_14.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_15.png)<br/>
<br>![image](https://github.com/yhlien1221/Linear-algebra/blob/main/3Blue1Brown/pic/3_16.png)<br/>
-->