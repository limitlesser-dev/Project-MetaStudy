# Solutions for EXERCISE 3.1

This document provides detailed solutions for EXERCISE 3.1, formatted for use in Obsidian Markdown, leveraging its math rendering capabilities.

## Question 1

Consider the matrix A:
$$
A = \begin{bmatrix}
2 & 5 & 19 & -7 \\
35 & -2 & 5 & 12 \\
\sqrt{3} & 1 & -5 & 17
\end{bmatrix}
$$

(i) **The order of the matrix:**
A matrix's order is defined by the number of its rows ($\text{m}$) by the number of its columns ($\text{n}$), expressed as $\text{m} \times \text{n}$.
In matrix A, we can count:
*   Number of rows = 3
*   Number of columns = 4
Therefore, the order of matrix A is $3 \times 4$.

(ii) **The number of elements:**
The total number of elements in a matrix of order $\text{m} \times \text{n}$ is $\text{m} \times \text{n}$.
For matrix A, the number of elements is $3 \times 4 = 12$.

(iii) **Write the elements $a_{13}, a_{21}, a_{33}, a_{24}, a_{23}$:**
An element $a_{ij}$ refers to the element located in the $i$-th row and $j$-th column.
*   $a_{13}$ (1st row, 3rd column): $19$
*   $a_{21}$ (2nd row, 1st column): $35$
*   $a_{33}$ (3rd row, 3rd column): $-5$
*   $a_{24}$ (2nd row, 4th column): $12$
*   $a_{23}$ (2nd row, 3rd column): $5$

## Question 2

**If a matrix has 24 elements, what are the possible orders it can have?**
If a matrix has $\text{N}$ elements, its possible orders are all ordered pairs $(\text{m}, \text{n})$ of natural numbers such that $\text{m} \times \text{n} = \text{N}$. For $\text{N} = 24$, we find all pairs of factors of 24:
*   $(1, 24)$
*   $(24, 1)$
*   $(2, 12)$
*   $(12, 2)$
*   $(3, 8)$
*   $(8, 3)$
*   $(4, 6)$
*   $(6, 4)$
Thus, the possible orders are $1 \times 24$, $24 \times 1$, $2 \times 12$, $12 \times 2$, $3 \times 8$, $8 \times 3$, $4 \times 6$, and $6 \times 4$.

**What, if it has 13 elements?**
For $\text{N} = 13$, since 13 is a prime number, its only pairs of factors are:
*   $(1, 13)$
*   $(13, 1)$
Thus, the possible orders are $1 \times 13$ and $13 \times 1$.

## Question 3

**If a matrix has 18 elements, what are the possible orders it can have?**
For $\text{N} = 18$, we find all pairs of factors of 18:
*   $(1, 18)$
*   $(18, 1)$
*   $(2, 9)$
*   $(9, 2)$
*   $(3, 6)$
*   $(6, 3)$
Thus, the possible orders are $1 \times 18$, $18 \times 1$, $2 \times 9$, $9 \times 2$, $3 \times 6$, and $6 \times 3$.

**What, if it has 5 elements?**
For $\text{N} = 5$, since 5 is a prime number, its only pairs of factors are:
*   $(1, 5)$
*   $(5, 1)$
Thus, the possible orders are $1 \times 5$ and $5 \times 1$.

## Question 4

Construct a $2 \times 2$ matrix, $A = [a_{ij}]$, whose elements are given by:
A $2 \times 2$ matrix has elements $a_{11}, a_{12}, a_{21}, a_{22}$.

(i) $a_{ij} = \frac{(i + j)^2}{2}$
*   $a_{11} = \frac{(1 + 1)^2}{2} = \frac{2^2}{2} = \frac{4}{2} = 2$
*   $a_{12} = \frac{(1 + 2)^2}{2} = \frac{3^2}{2} = \frac{9}{2}$
*   $a_{21} = \frac{(2 + 1)^2}{2} = \frac{3^2}{2} = \frac{9}{2}$
*   $a_{22} = \frac{(2 + 2)^2}{2} = \frac{4^2}{2} = \frac{16}{2} = 8$
The matrix is:
$$
A = \begin{bmatrix}
2 & \frac{9}{2} \\
\frac{9}{2} & 8
\end{bmatrix}
$$

(ii) $a_{ij} = \frac{i}{j}$
*   $a_{11} = \frac{1}{1} = 1$
*   $a_{12} = \frac{1}{2}$
*   $a_{21} = \frac{2}{1} = 2$
*   $a_{22} = \frac{2}{2} = 1$
The matrix is:
$$
A = \begin{bmatrix}
1 & \frac{1}{2} \\
2 & 1
\end{bmatrix}
$$

(iii) $a_{ij} = \frac{(i + 2j)^2}{2}$
*   $a_{11} = \frac{(1 + 2(1))^2}{2} = \frac{(1 + 2)^2}{2} = \frac{3^2}{2} = \frac{9}{2}$
*   $a_{12} = \frac{(1 + 2(2))^2}{2} = \frac{(1 + 4)^2}{2} = \frac{5^2}{2} = \frac{25}{2}$
*   $a_{21} = \frac{(2 + 2(1))^2}{2} = \frac{(2 + 2)^2}{2} = \frac{4^2}{2} = \frac{16}{2} = 8$
*   $a_{22} = \frac{(2 + 2(2))^2}{2} = \frac{(2 + 4)^2}{2} = \frac{6^2}{2} = \frac{36}{2} = 18$
The matrix is:
$$
A = \begin{bmatrix}
\frac{9}{2} & \frac{25}{2} \\
8 & 18
\end{bmatrix}
$$

## Question 5

Construct a $3 \times 4$ matrix, $A = [a_{ij}]$, whose elements are given by:
A $3 \times 4$ matrix has elements $a_{ij}$ where $i \in \{1, 2, 3\}$ and $j \in \{1, 2, 3, 4\}$.

(i) $a_{ij} = \frac{1}{2} | -3i + j |$
*   **For i = 1:**
    *   $a_{11} = \frac{1}{2} | -3(1) + 1 | = \frac{1}{2} | -2 | = \frac{1}{2}(2) = 1$
    *   $a_{12} = \frac{1}{2} | -3(1) + 2 | = \frac{1}{2} | -1 | = \frac{1}{2}(1) = \frac{1}{2}$
    *   $a_{13} = \frac{1}{2} | -3(1) + 3 | = \frac{1}{2} | 0 | = 0$
    *   $a_{14} = \frac{1}{2} | -3(1) + 4 | = \frac{1}{2} | 1 | = \frac{1}{2}$
*   **For i = 2:**
    *   $a_{21} = \frac{1}{2} | -3(2) + 1 | = \frac{1}{2} | -5 | = \frac{1}{2}(5) = \frac{5}{2}$
    *   $a_{22} = \frac{1}{2} | -3(2) + 2 | = \frac{1}{2} | -4 | = \frac{1}{2}(4) = 2$
    *   $a_{23} = \frac{1}{2} | -3(2) + 3 | = \frac{1}{2} | -3 | = \frac{1}{2}(3) = \frac{3}{2}$
    *   $a_{24} = \frac{1}{2} | -3(2) + 4 | = \frac{1}{2} | -2 | = \frac{1}{2}(2) = 1$
*   **For i = 3:**
    *   $a_{31} = \frac{1}{2} | -3(3) + 1 | = \frac{1}{2} | -8 | = \frac{1}{2}(8) = 4$
    *   $a_{32} = \frac{1}{2} | -3(3) + 2 | = \frac{1}{2} | -7 | = \frac{1}{2}(7) = \frac{7}{2}$
    *   $a_{33} = \frac{1}{2} | -3(3) + 3 | = \frac{1}{2} | -6 | = \frac{1}{2}(6) = 3$
    *   $a_{34} = \frac{1}{2} | -3(3) + 4 | = \frac{1}{2} | -5 | = \frac{1}{2}(5) = \frac{5}{2}$
The matrix is:
$$
A = \begin{bmatrix}
1 & \frac{1}{2} & 0 & \frac{1}{2} \\
\frac{5}{2} & 2 & \frac{3}{2} & 1 \\
4 & \frac{7}{2} & 3 & \frac{5}{2}
\end{bmatrix}
$$

(ii) $a_{ij} = 2i - j$
*   **For i = 1:**
    *   $a_{11} = 2(1) - 1 = 1$
    *   $a_{12} = 2(1) - 2 = 0$
    *   $a_{13} = 2(1) - 3 = -1$
    *   $a_{14} = 2(1) - 4 = -2$
*   **For i = 2:**
    *   $a_{21} = 2(2) - 1 = 3$
    *   $a_{22} = 2(2) - 2 = 2$
    *   $a_{23} = 2(2) - 3 = 1$
    *   $a_{24} = 2(2) - 4 = 0$
*   **For i = 3:**
    *   $a_{31} = 2(3) - 1 = 5$
    *   $a_{32} = 2(3) - 2 = 4$
    *   $a_{33} = 2(3) - 3 = 3$
    *   $a_{34} = 2(3) - 4 = 2$
The matrix is:
$$
A = \begin{bmatrix}
1 & 0 & -1 & -2 \\
3 & 2 & 1 & 0 \\
5 & 4 & 3 & 2
\end{bmatrix}
$$

## Question 6

Find the values of $x, y$ and $z$ from the following equations:

(i) The problem states two matrices `[ 4 3 x ; x 5 1 ]` and `[ y z 5 ; 1 5 8 ]`. Assuming the intent is for these matrices to be equal:
$$
\begin{bmatrix}
4 & 3 & x \\
x & 5 & 1
\end{bmatrix}
=
\begin{bmatrix}
y & z & 5 \\
1 & 5 & 8
\end{bmatrix}
$$
For two matrices to be equal, they must have the same order, and their corresponding elements must be equal.
From comparing the elements:
1.  $a_{11} = b_{11} \implies 4 = y \implies y = 4$
2.  $a_{12} = b_{12} \implies 3 = z \implies z = 3$
3.  $a_{13} = b_{13} \implies x = 5$
4.  $a_{21} = b_{21} \implies x = 1$
5.  $a_{22} = b_{22} \implies 5 = 5$ (Consistent)
6.  $a_{23} = b_{23} \implies 1 = 8$ (Inconsistent)

From equations (3) and (4), we have $x = 5$ and $x = 1$, which is a contradiction ($5 \neq 1$).
Also, equation (6) $1 = 8$ is a contradiction.
Therefore, there are no values of $x, y, z$ for which these two matrices can be equal. The problem statement as presented leads to an inconsistency.

(ii)
$$
\begin{bmatrix}
x + y & 2 \\
5 + z & xy
\end{bmatrix}
=
\begin{bmatrix}
6 & 2 \\
5 & 8
\end{bmatrix}
$$
Equating corresponding elements:
1.  $x + y = 6$
2.  $2 = 2$ (Consistent)
3.  $5 + z = 5$
4.  $xy = 8$

From (3): $5 + z = 5 \implies z = 0$.
From (1), we can express $y$ as $y = 6 - x$.
Substitute this into (4):
$x(6 - x) = 8$
$6x - x^2 = 8$
$x^2 - 6x + 8 = 0$
Factor the quadratic equation:
$(x - 2)(x - 4) = 0$
This gives two possible values for $x$: $x = 2$ or $x = 4$.

*   If $x = 2$, then $y = 6 - 2 = 4$.
*   If $x = 4$, then $y = 6 - 4 = 2$.

So, there are two sets of solutions:
*   $x = 2, y = 4, z = 0$
*   $x = 4, y = 2, z = 0$

(iii)
$$
\begin{bmatrix}
x + y + z \\
x + z \\
y + z
\end{bmatrix}
=
\begin{bmatrix}
9 \\
5 \\
7
\end{bmatrix}
$$
Equating corresponding elements:
1.  $x + y + z = 9$
2.  $x + z = 5$
3.  $y + z = 7$

Substitute (2) into (1):
$(x + z) + y = 9$
$5 + y = 9$
$y = 9 - 5 \implies y = 4$

Substitute the value of $y$ into (3):
$4 + z = 7$
$z = 7 - 4 \implies z = 3$

Substitute the value of $z$ into (2):
$x + 3 = 5$
$x = 5 - 3 \implies x = 2$

Therefore, the solution is: $x = 2, y = 4, z = 3$.

## Question 7

Find the value of $a, b, c$ and $d$ from the equation:
$$
\begin{bmatrix}
2a + b & a - 2b \\
5c - d & 4c + 3d
\end{bmatrix}
=
\begin{bmatrix}
4 & -3 \\
11 & 24
\end{bmatrix}
$$
Equating corresponding elements, we get a system of linear equations:
1.  $2a + b = 4$
2.  $a - 2b = -3$
3.  $5c - d = 11$
4.  $4c + 3d = 24$

**Solving for $a$ and $b$ (from equations 1 and 2):**
Multiply equation (1) by 2:
$(2a + b) \times 2 = 4 \times 2 \implies 4a + 2b = 8$ (Equation 5)
Add equation (2) and equation (5):
$(a - 2b) + (4a + 2b) = -3 + 8$
$5a = 5$
$a = 1$
Substitute $a = 1$ into equation (1):
$2(1) + b = 4$
$2 + b = 4$
$b = 4 - 2 \implies b = 2$

**Solving for $c$ and $d$ (from equations 3 and 4):**
Multiply equation (3) by 3:
$(5c - d) \times 3 = 11 \times 3 \implies 15c - 3d = 33$ (Equation 6)
Add equation (4) and equation (6):
$(4c + 3d) + (15c - 3d) = 24 + 33$
$19c = 57$
$c = \frac{57}{19} \implies c = 3$
Substitute $c = 3$ into equation (3):
$5(3) - d = 11$
$15 - d = 11$
$d = 15 - 11 \implies d = 4$

Therefore, the solution is: $a = 1, b = 2, c = 3, d = 4$.