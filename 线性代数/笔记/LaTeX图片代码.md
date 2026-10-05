# 图片代码

3x3行列式对角线法则

![对角线法则](./images/3x3dialaw.png)
$$
\begin{vmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{vmatrix} \ 
\begin{matrix}
a_{11} & a_{12} \\
a_{21} & a_{22} \\
a_{31} & a_{32}
\end{matrix}
$$

有0元素在对角线上的上三角行列式

![0上三角行列式](./images/0toptri.png)
$$
\begin{vmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,p} & \cdots & a_{1,n - 1} & a_{1,n} \\
0 & a_{2,2} & \cdots & a_{2,p} & \cdots & a_{2,n - 1} & a_{2,n} \\
\vdots & \vdots & \ddots & \vdots & \ddots & \vdots & \vdots \\
0 & 0 & \cdots & 0 & \cdots & a_{p,n - 1} & a_{p,n} \\
\vdots & \vdots & \ddots & \vdots & \ddots & \vdots & \vdots \\
0 & 0 & \cdots & 0 & \cdots & a_{n - 1,n - 1} & a_{n - 1,n} \\
0 & 0 & \cdots & 0 & \cdots & 0 & a_{n,n}
\end{vmatrix}
$$