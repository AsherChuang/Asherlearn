## Lesson 1 向量
1. 理解向量是什么：
	a. 物理角度
	b. 计算机角度
	c. 数学角度
2. 理解向量加法
3. Scaling and Scalars 向量与标量相乘

## Lesson 2 线性组合、张成空间与基
1. 理解Basis vector：想象一下如果选择不同的Basis vector会发生什么变化
2. 理解Linear combination of $\vec{v}$ and $\vec{w}$
	Like: a$\vec{v}$  + b$\vec{w}$ 
3. What does the span of two 3d vectors look like?
	a. 想象一下，两个不同面的向量在三维空间里面改变不同标量创造的平面
	b. 想象一下如果加入了第三个向量，如果第三个向量在平面外是什么情况，在平面内是什么情况
4. 根据 (3) 去理解 Linearly dependent and Linearly independent 线性相关与无关
### 思考
 The basis of a vector space is a set of linearly independent vectors that span the full space. 向量空间的一组基是张成该空间的一个线性无关向量集。

## Lesson 3 矩阵与线性变换
1. 理解线性变化 linear-transformation 类似于function
	a. Lines remain lines
	b. Origin remains fixed
2. 思考如何用数值描述线性变换（基的视角）
3. 2 x 2 matrix
	![[3Blue1Brown-Lesson3.png]]
	明白这个图片是怎么推导的：
	$$\vec{v} =\begin{pmatrix}a \\c\\ \end{pmatrix}$$
	一共两组基，$\vec{v}$为其中一组变换后的，假设另外一个变换后的基为$\vec{w}$，然后
	$$\vec{p}=\begin{pmatrix}x \\ y \end{pmatrix}$$
	$\vec{p}$ 为原来的向量，经过线性变换以后，得到了变换后的向量。x就是在第一组基上走的步数，y就是在第二组基上走的步数，和之前的矩阵加法原理相似。通过这种方式，我们学会了矩阵乘法为什么是这样计算的。