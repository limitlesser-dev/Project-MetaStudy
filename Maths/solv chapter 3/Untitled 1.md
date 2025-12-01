# Solutions for Mathematics Exercises

This document provides solutions for the exercises from the provided text, formatted for Obsidian Markdown.

## EXERCISE 3.1

**Question 1 - 7 were solved previously. Continuing from Question 8.**

**Question 8:**
$A = [a_{ij}]_{m \times n}$ is a square matrix, if
(A) $m < n$
(B) $m > n$
(C) $m = n$
(D) None of these

**Explanation:**
By definition, a square matrix is a matrix where the number of rows ($m$) equals the number of columns ($n$).
Therefore, for $A = [a_{ij}]_{m \times n}$ to be a square matrix, $m$ must equal $n$.

**Answer:** (C) $m = n$

**Question 9:**
Which of the given values of $x$ and $y$ make the following pair of matrices equal:
$$
\begin{bmatrix}
3x + 7 & 5 \\
y + 1 & 2 - 3x
\end{bmatrix}
,
\begin{bmatrix}
0 & y - 2 \\
8 & 4
\end{bmatrix}
$$

For matrices to be equal, their corresponding elements must be equal.
1.  $3x + 7 = 0 \implies 3x = -7 \implies x = -\frac{7}{3}$
2.  $5 = y - 2 \implies y = 7$
3.  $y + 1 = 8 \implies y = 7$
4.  $2 - 3x = 4 \implies -3x = 2 \implies x = -\frac{2}{3}$

We have two conflicting values for $x$ ($-\frac{7}{3}$ and $-\frac{2}{3}$). Therefore, there are no values of $x$ and $y$ that can make these matrices equal.

**Answer:** (B) Not possible to find

**Question 10:**
The number of all possible matrices of order $3 \times 3$ with each entry 0 or 1 is:
(A) 27
(B) 18
(C) 81
(D) 512

**Explanation:**
A $3 \times 3$ matrix has $3 \times 3 = 9$ elements. Each element can be either 0 or 1 (2 choices).
The total number of possible matrices is $2^9$.
$2^9 = 512$.

**Answer:** (D) 512

**Question 11:**
If a matrix has 13 elements, what are the possible orders it can have?
For a matrix with 13 elements, the possible orders are pairs of factors of 13. Since 13 is prime, the factors are 1 and 13.
Possible orders: $1 \times 13$ and $13 \times 1$.

**Answer:** $1 \times 13$, $13 \times 1$.

**Question 12:**
Solve the equation for $x, y, z$ and $t$, if:
$$
2 \begin{bmatrix} x & y \\ z & w \end{bmatrix} + \begin{bmatrix} 3 & -4 \\ 1 & 2 \end{bmatrix} = \begin{bmatrix} 7 & 6 \\ 15 & 14 \end{bmatrix}
$$
**Solution:**
First, distribute the scalar 2:
$$
\begin{bmatrix} 2x & 2y \\ 2z & 2w \end{bmatrix} + \begin{bmatrix} 3 & -4 \\ 1 & 2 \end{bmatrix} = \begin{bmatrix} 7 & 6 \\ 15 & 14 \end{bmatrix}
$$
Perform matrix addition:
$$
\begin{bmatrix} 2x+3 & 2y-4 \\ 2z+1 & 2w+2 \end{bmatrix} = \begin{bmatrix} 7 & 6 \\ 15 & 14 \end{bmatrix}
$$
Equate corresponding elements:
1.  $2x + 3 = 7 \implies 2x = 4 \implies x = 2$
2.  $2y - 4 = 6 \implies 2y = 10 \implies y = 5$
3.  $2z + 1 = 15 \implies 2z = 14 \implies z = 7$
4.  $2w + 2 = 14 \implies 2w = 12 \implies w = 6$

**Answer:** $x = 2, y = 5, z = 7, w = 6$.

---

## EXERCISE 3.2

**Question 1:**
Let $A = \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix}$, $B = \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix}$, $C = \begin{bmatrix} -2 & 5 \\ 3 & 4 \end{bmatrix}$. Find each of the following:

(i) $A + B$
$$
A + B = \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} + \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix} = \begin{bmatrix} 2+1 & 4+3 \\ 3+(-2) & 2+5 \end{bmatrix} = \begin{bmatrix} 3 & 7 \\ 1 & 7 \end{bmatrix}
$$

(ii) $A - B$
$$
A - B = \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} - \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix} = \begin{bmatrix} 2-1 & 4-3 \\ 3-(-2) & 2-5 \end{bmatrix} = \begin{bmatrix} 1 & 1 \\ 5 & -3 \end{bmatrix}
$$

(iii) $3A - C$
First, $3A = 3 \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} = \begin{bmatrix} 6 & 12 \\ 9 & 6 \end{bmatrix}$.
$$
3A - C = \begin{bmatrix} 6 & 12 \\ 9 & 6 \end{bmatrix} - \begin{bmatrix} -2 & 5 \\ 3 & 4 \end{bmatrix} = \begin{bmatrix} 6-(-2) & 12-5 \\ 9-3 & 6-4 \end{bmatrix} = \begin{bmatrix} 8 & 7 \\ 6 & 2 \end{bmatrix}
$$

(iv) $AB$
$$
AB = \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix} = \begin{bmatrix} (2)(1)+(4)(-2) & (2)(3)+(4)(5) \\ (3)(1)+(2)(-2) & (3)(3)+(2)(5) \end{bmatrix} = \begin{bmatrix} 2-8 & 6+20 \\ 3-4 & 9+10 \end{bmatrix} = \begin{bmatrix} -6 & 26 \\ -1 & 19 \end{bmatrix}
$$

(v) $BA$
$$
BA = \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix} \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} = \begin{bmatrix} (1)(2)+(3)(3) & (1)(4)+(3)(2) \\ (-2)(2)+(5)(3) & (-2)(4)+(5)(2) \end{bmatrix} = \begin{bmatrix} 2+9 & 4+6 \\ -4+15 & -8+10 \end{bmatrix} = \begin{bmatrix} 11 & 10 \\ 11 & 2 \end{bmatrix}
$$

**Question 2:**
Compute the following:

(i)
$$
\begin{bmatrix} a & b \\ -b & a \end{bmatrix} + \begin{bmatrix} a & b \\ b & a \end{bmatrix} = \begin{bmatrix} a+a & b+b \\ -b+b & a+a \end{bmatrix} = \begin{bmatrix} 2a & 2b \\ 0 & 2a \end{bmatrix}
$$

(ii)
$$
\begin{bmatrix} a^2+b^2 & b^2+c^2 \\ a^2+c^2 & a^2+b^2 \end{bmatrix} + \begin{bmatrix} 2ab & -2ac \\ 2ac & -2ab \end{bmatrix} = \begin{bmatrix} a^2+b^2+2ab & b^2+c^2-2ac \\ a^2+c^2+2ac & a^2+b^2-2ab \end{bmatrix} = \begin{bmatrix} (a+b)^2 & b^2-2ac+c^2 \\ a^2+2ac+c^2 & (a-b)^2 \end{bmatrix}
$$
Note: The expected result might be simpler if there's a typo in the question or if the terms are meant to form perfect squares like $(a+b)^2$, $(a-b)^2$, etc. Assuming the provided expression is correct.

(iii)
$$
\begin{bmatrix} \cos^2 x & \sin^2 x \\ \sin^2 x & \cos^2 x \end{bmatrix} + \begin{bmatrix} \sin^2 x & \cos^2 x \\ \cos^2 x & \sin^2 x \end{bmatrix} = \begin{bmatrix} \cos^2 x + \sin^2 x & \sin^2 x + \cos^2 x \\ \sin^2 x + \cos^2 x & \cos^2 x + \sin^2 x \end{bmatrix}
$$
Using the identity $\sin^2 \theta + \cos^2 \theta = 1$:
$$
= \begin{bmatrix} 1 & 1 \\ 1 & 1 \end{bmatrix}
$$

(iv)
$$
\begin{bmatrix} \cos^2 x & \sin^2 x \\ \sin^2 x & \cos^2 x \end{bmatrix} + \begin{bmatrix} \sin^2 x & \cos^2 x \\ \cos^2 x & \sin^2 x \end{bmatrix} = \begin{bmatrix} \cos^2 x + \sin^2 x & \sin^2 x + \cos^2 x \\ \sin^2 x + \cos^2 x & \cos^2 x + \sin^2 x \end{bmatrix}
$$
Using the identity $\sin^2 \theta + \cos^2 \theta = 1$:
$$
= \begin{bmatrix} 1 & 1 \\ 1 & 1 \end{bmatrix}
$$
*(Note: This appears to be the same as (iii), likely a duplicate.)*

**Question 3:**
Compute the indicated products.

(i)
$$
\begin{bmatrix} a & b \\ -b & a \end{bmatrix} \begin{bmatrix} a & b \\ -b & a \end{bmatrix} = \begin{bmatrix} (a)(a) + (b)(-b) & (a)(b) + (b)(a) \\ (-b)(a) + (a)(-b) & (-b)(b) + (a)(a) \end{bmatrix} = \begin{bmatrix} a^2 - b^2 & 2ab \\ -2ab & a^2 - b^2 \end{bmatrix}
$$

(ii)
$$
\begin{bmatrix} 1 & -2 \\ 2 & 3 \end{bmatrix} \begin{bmatrix} 1 & 2 \\ 3 & 1 \end{bmatrix} = \begin{bmatrix} (1)(1)+(-2)(3) & (1)(2)+(-2)(1) \\ (2)(1)+(3)(3) & (2)(2)+(3)(1) \end{bmatrix} = \begin{bmatrix} 1-6 & 2-2 \\ 2+9 & 4+3 \end{bmatrix} = \begin{bmatrix} -5 & 0 \\ 11 & 7 \end{bmatrix}
$$

(iii)
$$
\begin{bmatrix} 2 & 3 \\ 3 & 2 \end{bmatrix} \begin{bmatrix} 1 & 2 \\ 3 & 1 \end{bmatrix} = \begin{bmatrix} (2)(1)+(3)(3) & (2)(2)+(3)(1) \\ (3)(1)+(2)(3) & (3)(2)+(2)(1) \end{bmatrix} = \begin{bmatrix} 2+9 & 4+3 \\ 3+6 & 6+2 \end{bmatrix} = \begin{bmatrix} 11 & 7 \\ 9 & 8 \end{bmatrix}
$$

(iv)
$$
\begin{bmatrix} 3 & 4 \\ 4 & 5 \\ 6 & 3 \end{bmatrix} \begin{bmatrix} 1 & -3 \\ 0 & 2 \\ 4 & 5 \end{bmatrix}
$$
This product is not defined because the number of columns in the first matrix (2) is not equal to the number of rows in the second matrix (3).

(v)
$$
\begin{bmatrix} 2 & 1 \\ 3 & 2 \\ -1 & 1 \end{bmatrix} \begin{bmatrix} 1 & 0 & 1 \\ 0 & 1 & 0 \end{bmatrix} = \begin{bmatrix} (2)(1)+(1)(0) & (2)(0)+(1)(1) & (2)(1)+(1)(0) \\ (3)(1)+(2)(0) & (3)(0)+(2)(1) & (3)(1)+(2)(0) \\ (-1)(1)+(1)(0) & (-1)(0)+(1)(1) & (-1)(1)+(1)(0) \end{bmatrix} = \begin{bmatrix} 2 & 1 & 2 \\ 3 & 2 & 3 \\ -1 & 1 & -1 \end{bmatrix}
$$

(vi)
$$
\begin{bmatrix} 3 & -1 & 3 \\ -1 & 0 & 2 \\ 3 & -1 & 3 \end{bmatrix} \begin{bmatrix} 2 & -3 \\ 1 & 0 \\ 3 & 1 \end{bmatrix} = \begin{bmatrix} (3)(2)+(-1)(1)+(3)(3) & (3)(-3)+(-1)(0)+(3)(1) \\ (-1)(2)+(0)(1)+(2)(3) & (-1)(-3)+(0)(0)+(2)(1) \\ (3)(2)+(-1)(1)+(3)(3) & (3)(-3)+(-1)(0)+(3)(1) \end{bmatrix} = \begin{bmatrix} 6-1+9 & -9+0+3 \\ -2+0+6 & 3+0+2 \\ 6-1+9 & -9+0+3 \end{bmatrix} = \begin{bmatrix} 14 & -6 \\ 4 & 5 \\ 14 & -6 \end{bmatrix}
$$

---

## EXERCISE 3.3

**Question 1:**
Find the transpose of each of the following matrices:

(i)
$$
\begin{bmatrix} 5 \\ 1 \\ 2 \\ -1 \end{bmatrix}
$$
Transpose: $\begin{bmatrix} 5 & 1 & 2 & -1 \end{bmatrix}$

(ii)
$$
\begin{bmatrix} 1 & -1 \\ 2 & 2 \end{bmatrix}
$$
Transpose: $\begin{bmatrix} 1 & 2 \\ -1 & 2 \end{bmatrix}$

(iii)
$$
\begin{bmatrix} -1 & 5 & 6 \\ \sqrt{3} & 5 & 6 \\ 2 & 3 & -1 \end{bmatrix}
$$
Transpose: $\begin{bmatrix} -1 & \sqrt{3} & 2 \\ 5 & 5 & 3 \\ 6 & 6 & -1 \end{bmatrix}$

**Question 2:**
If $A = \begin{bmatrix} -1 & 2 & 3 \\ 5 & 7 & 9 \\ -2 & 1 & 1 \end{bmatrix}$ and $B = \begin{bmatrix} -4 & 1 & -5 \\ 1 & 2 & 0 \\ 1 & 3 & 1 \end{bmatrix}$, then verify that:

(i) $(A + B)' = A' + B'$
First, find $A+B$:
$$
A+B = \begin{bmatrix} -1+(-4) & 2+1 & 3+(-5) \\ 5+1 & 7+2 & 9+0 \\ -2+1 & 1+3 & 1+1 \end{bmatrix} = \begin{bmatrix} -5 & 3 & -2 \\ 6 & 9 & 9 \\ -1 & 4 & 2 \end{bmatrix}
$$
Now find the transpose of $(A+B)$:
$(A+B)' = \begin{bmatrix} -5 & 6 & -1 \\ 3 & 9 & 4 \\ -2 & 9 & 2 \end{bmatrix}$

Next, find $A'$ and $B'$:
$A' = \begin{bmatrix} -1 & 5 & -2 \\ 2 & 7 & 1 \\ 3 & 9 & 1 \end{bmatrix}$, $B' = \begin{bmatrix} -4 & 1 & 1 \\ 1 & 2 & 3 \\ -5 & 0 & 1 \end{bmatrix}$

Now find $A' + B'$:
$$
A' + B' = \begin{bmatrix} -1+(-4) & 5+1 & -2+1 \\ 2+1 & 7+2 & 1+3 \\ 3+(-5) & 9+0 & 1+1 \end{bmatrix} = \begin{bmatrix} -5 & 6 & -1 \\ 3 & 9 & 4 \\ -2 & 9 & 2 \end{bmatrix}
$$
Since $(A + B)' = A' + B'$, the property is verified.

(ii) $(A - B)' = A' - B'$
First, find $A-B$:
$$
A-B = \begin{bmatrix} -1-(-4) & 2-1 & 3-(-5) \\ 5-1 & 7-2 & 9-0 \\ -2-1 & 1-3 & 1-1 \end{bmatrix} = \begin{bmatrix} 3 & 1 & 8 \\ 4 & 5 & 9 \\ -3 & -2 & 0 \end{bmatrix}
$$
Now find the transpose of $(A-B)$:
$(A-B)' = \begin{bmatrix} 3 & 4 & -3 \\ 1 & 5 & -2 \\ 8 & 9 & 0 \end{bmatrix}$

Next, find $A' - B'$:
$$
A' - B' = \begin{bmatrix} -1 & 5 & -2 \\ 2 & 7 & 1 \\ 3 & 9 & 1 \end{bmatrix} - \begin{bmatrix} -4 & 1 & 1 \\ 1 & 2 & 3 \\ -5 & 0 & 1 \end{bmatrix} = \begin{bmatrix} -1-(-4) & 5-1 & -2-1 \\ 2-1 & 7-2 & 1-3 \\ 3-(-5) & 9-0 & 1-1 \end{bmatrix} = \begin{bmatrix} 3 & 4 & -3 \\ 1 & 5 & -2 \\ 8 & 9 & 0 \end{bmatrix}
$$
Since $(A - B)' = A' - B'$, the property is verified.

**Question 3:**
If $A' = \begin{bmatrix} 3 & 4 \\ 1 & 2 \\ -1 & 2 \end{bmatrix}$ and $B = \begin{bmatrix} 1 & 2 \\ 1 & 3 \\ 3 & 1 \end{bmatrix}$, then verify that:

First, find $A$ from $A'$: $A = (A')' = \begin{bmatrix} 3 & 1 & -1 \\ 4 & 2 & 2 \end{bmatrix}$.

(i) $(A + B)' = A' + B'$
First, find $A+B$:
$$
A+B = \begin{bmatrix} 3 & 1 & -1 \\ 4 & 2 & 2 \end{bmatrix} + \begin{bmatrix} 1 & 2 & 1 \\ 1 & 3 & 3 \end{bmatrix} = \begin{bmatrix} 3+1 & 1+2 & -1+1 \\ 4+1 & 2+3 & 2+3 \end{bmatrix} = \begin{bmatrix} 4 & 3 & 0 \\ 5 & 5 & 5 \end{bmatrix}
$$
Now find the transpose of $(A+B)$:
$(A+B)' = \begin{bmatrix} 4 & 5 \\ 3 & 5 \\ 0 & 5 \end{bmatrix}$

Next, find $B'$:
$B' = \begin{bmatrix} 1 & 1 & 3 \\ 2 & 3 & 1 \end{bmatrix}$

Now find $A' + B'$:
$$
A' + B' = \begin{bmatrix} 3 & 4 \\ 1 & 2 \\ -1 & 2 \end{bmatrix} + \begin{bmatrix} 1 & 1 & 3 \\ 2 & 3 & 1 \end{bmatrix}
$$
This addition is not possible because $A'$ is $3 \times 2$ and $B'$ is $2 \times 3$. They are not of the same order.
Let's re-check the question and my interpretation. The question provides $A'$ and $B$.
To verify $(A+B)' = A'+B'$, we need $A, B$ of same order, then $(A+B)'$ is transpose of sum, and $A'+B'$ is sum of transposes.
$A$ is $2 \times 3$, $B$ is $3 \times 2$. They are not of the same order. So $A+B$ is not defined.
This implies there might be a typo in the question, or the property being verified is for matrices of the same order. Let's assume the question intends for $A$ and $B$ to be of the same order for the verification.

*If the question meant to ask for verification with $A$ and $B$ of the same order:*
Let's assume $A = \begin{bmatrix} 3 & 1 & -1 \\ 4 & 2 & 2 \end{bmatrix}$ and $B = \begin{bmatrix} 1 & 2 & 1 \\ 1 & 3 & 3 \end{bmatrix}$ (making them same order $2 \times 3$).
Then $A+B = \begin{bmatrix} 4 & 3 & 0 \\ 5 & 5 & 5 \end{bmatrix}$.
$(A+B)' = \begin{bmatrix} 4 & 5 \\ 3 & 5 \\ 0 & 5 \end{bmatrix}$.
$A' = \begin{bmatrix} 3 & 4 \\ 1 & 2 \\ -1 & 2 \end{bmatrix}$, $B' = \begin{bmatrix} 1 & 1 \\ 2 & 3 \\ 1 & 3 \end{bmatrix}$.
$A' + B' = \begin{bmatrix} 3+1 & 4+1 \\ 1+2 & 2+3 \\ -1+1 & 2+3 \end{bmatrix} = \begin{bmatrix} 4 & 5 \\ 3 & 5 \\ 0 & 5 \end{bmatrix}$.
In this case, $(A+B)' = A'+B'$ is verified.

(ii) $(A - B)' = A' - B'$
This also requires $A$ and $B$ to be of the same order. Given $A$ is $2 \times 3$ and $B$ is $3 \times 2$, $A-B$ is not defined.
*If we assume the same order $2 \times 3$ for $A$ and $B$ as above:*
$A-B = \begin{bmatrix} 3-1 & 1-2 & -1-1 \\ 4-1 & 2-3 & 2-3 \end{bmatrix} = \begin{bmatrix} 2 & -1 & -2 \\ 3 & -1 & -1 \end{bmatrix}$.
$(A-B)' = \begin{bmatrix} 2 & 3 \\ -1 & -1 \\ -2 & -1 \end{bmatrix}$.
$A' - B' = \begin{bmatrix} 3 & 4 \\ 1 & 2 \\ -1 & 2 \end{bmatrix} - \begin{bmatrix} 1 & 1 \\ 2 & 3 \\ 1 & 3 \end{bmatrix} = \begin{bmatrix} 3-1 & 4-1 \\ 1-2 & 2-3 \\ -1-1 & 2-3 \end{bmatrix} = \begin{bmatrix} 2 & 3 \\ -1 & -1 \\ -2 & -1 \end{bmatrix}$.
In this case, $(A-B)' = A'-B'$ is verified.

**Conclusion for Q3:** The question as stated leads to undefined operations ($A+B$, $A-B$) because $A$ and $B$ are not of the same order. However, if we assume $A$ and $B$ are meant to be of the same order (e.g., $A = \begin{bmatrix} 3 & 1 & -1 \\ 4 & 2 & 2 \end{bmatrix}$ and $B = \begin{bmatrix} 1 & 2 & 1 \\ 1 & 3 & 3 \end{bmatrix}$), the properties hold.

---

## EXERCISE 3.4

**Question 1:**
Matrices $A$ and $B$ will be inverse of each other only if
(A) $AB = BA$
(B) $AB = BA = 0$
(C) $AB = 0$, $BA = I$
(D) $AB = BA = I$

**Explanation:**
By definition, two matrices $A$ and $B$ are inverses of each other if their product in both orders is the identity matrix ($I$). That is, $AB = I$ and $BA = I$.

**Answer:** (D) $AB = BA = I$

---

## Miscellaneous Exercise on Chapter 3

**Question 1:**
If $A$ and $B$ are symmetric matrices, prove that $AB - BA$ is a skew symmetric matrix.

**Proof:**
Given that $A$ and $B$ are symmetric matrices, we have $A' = A$ and $B' = B$.
Let $C = AB - BA$.
We need to show that $C' = -C$.
$C' = (AB - BA)'$
Using the property $(X - Y)' = X' - Y'$:
$C' = (AB)' - (BA)'$
Using the property $(XY)' = Y'X'$:
$C' = B'A' - A'B'$
Since $A$ and $B$ are symmetric ($A'=A, B'=B$):
$C' = BA - AB$
We can factor out $-1$:
$C' = -(AB - BA)$
$C' = -C$
Thus, $AB - BA$ is a skew symmetric matrix.

**Question 2:**
Show that the matrix $B'AB$ is symmetric or skew symmetric according as $A$ is symmetric or skew symmetric.

**Case 1: $A$ is a symmetric matrix.**
If $A$ is symmetric, then $A' = A$.
Let $C = B'AB$. We need to check if $C' = C$ (symmetric) or $C' = -C$ (skew-symmetric).
$C' = (B'AB)'$
Using the property $(XYZ)' = Z'Y'X'$:
$C' = B'(A')'(B')'$
Using the property $(X')' = X$:
$C' = B'A'B$
Since $A$ is symmetric, $A' = A$.
$C' = B'AB$
$C' = C$
Therefore, if $A$ is symmetric, $B'AB$ is symmetric.

**Case 2: $A$ is a skew symmetric matrix.**
If $A$ is skew symmetric, then $A' = -A$.
Let $C = B'AB$.
$C' = (B'AB)'$
$C' = B'(A')'(B')'$
$C' = B'A'B$
Since $A$ is skew symmetric, $A' = -A$.
$C' = B'(-A)B$
$C' = -B'AB$
$C' = -C$
Therefore, if $A$ is skew symmetric, $B'AB$ is skew symmetric.

**Question 3:**
Find the values of $x, y, z$ if the matrix $A = \begin{bmatrix} 0 & 2y & z \\ x & y & -z \\ x & -y & z \end{bmatrix}$ satisfies $A'A = I$.

Given $A = \begin{bmatrix} 0 & 2y & z \\ x & y & -z \\ x & -y & z \end{bmatrix}$.
First, find $A'$:
$A' = \begin{bmatrix} 0 & x & x \\ 2y & y & -y \\ z & -z & z \end{bmatrix}$

Now compute $A'A$:
$$
A'A = \begin{bmatrix} 0 & x & x \\ 2y & y & -y \\ z & -z & z \end{bmatrix} \begin{bmatrix} 0 & 2y & z \\ x & y & -z \\ x & -y & z \end{bmatrix}
$$
$$
= \begin{bmatrix}
(0)(0)+(x)(x)+(x)(x) & (0)(2y)+(x)(y)+(x)(-y) & (0)(z)+(x)(-z)+(x)(z) \\
(2y)(0)+(y)(x)+(-y)(x) & (2y)(2y)+(y)(y)+(-y)(-y) & (2y)(z)+(y)(-z)+(-y)(z) \\
(z)(0)+(-z)(x)+(z)(x) & (z)(2y)+(-z)(y)+(z)(-y) & (z)(z)+(-z)(-z)+(z)(z)
\end{bmatrix}
$$
$$
= \begin{bmatrix}
0+x^2+x^2 & 0+xy-xy & 0-xz+xz \\
0+xy-xy & 4y^2+y^2+y^2 & 2yz-yz-yz \\
0-zx+zx & 2yz-yz-yz & z^2+z^2+z^2
\end{bmatrix}
$$
$$
= \begin{bmatrix}
2x^2 & 0 & 0 \\
0 & 6y^2 & 0 \\
0 & 0 & 3z^2
\end{bmatrix}
$$
We are given that $A'A = I$. The identity matrix of order 3 is $I = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}$.
Equating $A'A$ to $I$:
$$
\begin{bmatrix}
2x^2 & 0 & 0 \\
0 & 6y^2 & 0 \\
0 & 0 & 3z^2
\end{bmatrix} = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}
$$
Equating the corresponding elements:
1.  $2x^2 = 1 \implies x^2 = \frac{1}{2} \implies x = \pm \frac{1}{\sqrt{2}} = \pm \frac{\sqrt{2}}{2}$
2.  $6y^2 = 1 \implies y^2 = \frac{1}{6} \implies y = \pm \frac{1}{\sqrt{6}} = \pm \frac{\sqrt{6}}{6}$
3.  $3z^2 = 1 \implies z^2 = \frac{1}{3} \implies z = \pm \frac{1}{\sqrt{3}} = \pm \frac{\sqrt{3}}{3}$

**Answer:** $x = \pm \frac{\sqrt{2}}{2}$, $y = \pm \frac{\sqrt{6}}{6}$, $z = \pm \frac{\sqrt{3}}{3}$.

**Question 4:**
For what values of $x$:
$$
\begin{bmatrix} 1 & 2 & 1 \end{bmatrix} \begin{bmatrix} 2 & 0 & 2 \\ 1 & 0 & 1 \\ 0 & 2 & 0 \end{bmatrix} \begin{bmatrix} x \\ 0 \\ 2 \end{bmatrix} = 0
$$
**Solution:**
First, multiply the first two matrices:
$\begin{bmatrix} 1 & 2 & 1 \end{bmatrix} \begin{bmatrix} 2 & 0 & 2 \\ 1 & 0 & 1 \\ 0 & 2 & 0 \end{bmatrix} = \begin{bmatrix} (1)(2)+(2)(1)+(1)(0) & (1)(0)+(2)(0)+(1)(2) & (1)(2)+(2)(1)+(1)(0) \end{bmatrix}$
$= \begin{bmatrix} 2+2+0 & 0+0+2 & 2+2+0 \end{bmatrix} = \begin{bmatrix} 4 & 2 & 4 \end{bmatrix}$

Now, multiply this result by the third matrix:
$\begin{bmatrix} 4 & 2 & 4 \end{bmatrix} \begin{bmatrix} x \\ 0 \\ 2 \end{bmatrix} = (4)(x) + (2)(0) + (4)(2) = 4x + 0 + 8 = 4x + 8$

We are given that this product equals 0:
$4x + 8 = 0$
$4x = -8$
$x = -2$

**Answer:** $x = -2$.

**Question 5:**
If $A = \begin{bmatrix} 3 & 1 \\ -1 & 2 \end{bmatrix}$, show that $A^2 - 5A + 7I = 0$.

**Solution:**
First, calculate $A^2$:
$A^2 = A \cdot A = \begin{bmatrix} 3 & 1 \\ -1 & 2 \end{bmatrix} \begin{bmatrix} 3 & 1 \\ -1 & 2 \end{bmatrix} = \begin{bmatrix} (3)(3)+(1)(-1) & (3)(1)+(1)(2) \\ (-1)(3)+(2)(-1) & (-1)(1)+(2)(2) \end{bmatrix} = \begin{bmatrix} 9-1 & 3+2 \\ -3-2 & -1+4 \end{bmatrix} = \begin{bmatrix} 8 & 5 \\ -5 & 3 \end{bmatrix}$

Next, calculate $5A$:
$5A = 5 \begin{bmatrix} 3 & 1 \\ -1 & 2 \end{bmatrix} = \begin{bmatrix} 15 & 5 \\ -5 & 10 \end{bmatrix}$

Next, calculate $7I$. Since $A$ is a $2 \times 2$ matrix, $I$ is the $2 \times 2$ identity matrix:
$I = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}$
$7I = 7 \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 7 & 0 \\ 0 & 7 \end{bmatrix}$

Now, substitute these into the expression $A^2 - 5A + 7I$:
$A^2 - 5A + 7I = \begin{bmatrix} 8 & 5 \\ -5 & 3 \end{bmatrix} - \begin{bmatrix} 15 & 5 \\ -5 & 10 \end{bmatrix} + \begin{bmatrix} 7 & 0 \\ 0 & 7 \end{bmatrix}$
$= \begin{bmatrix} 8-15 & 5-5 \\ -5-(-5) & 3-10 \end{bmatrix} + \begin{bmatrix} 7 & 0 \\ 0 & 7 \end{bmatrix}$
$= \begin{bmatrix} -7 & 0 \\ 0 & -7 \end{bmatrix} + \begin{bmatrix} 7 & 0 \\ 0 & 7 \end{bmatrix}$
$= \begin{bmatrix} -7+7 & 0+0 \\ 0+0 & -7+7 \end{bmatrix} = \begin{bmatrix} 0 & 0 \\ 0 & 0 \end{bmatrix}$

Since the result is the zero matrix, $A^2 - 5A + 7I = 0$ is shown.

**Question 6:**
Find $x$, if $\begin{bmatrix} x & -5 & -1 \end{bmatrix} \begin{bmatrix} 0 & 2 & 1 \\ 4 & 0 & 3 \\ 1 & 4 & 0 \end{bmatrix} = 0$.

**Solution:**
Multiply the first two matrices:
$\begin{bmatrix} x & -5 & -1 \end{bmatrix} \begin{bmatrix} 0 & 2 & 1 \\ 4 & 0 & 3 \\ 1 & 4 & 0 \end{bmatrix}$
$= \begin{bmatrix} (x)(0)+(-5)(4)+(-1)(1) & (x)(2)+(-5)(0)+(-1)(4) & (x)(1)+(-5)(3)+(-1)(0) \end{bmatrix}$
$= \begin{bmatrix} 0-20-1 & 2x+0-4 & x-15+0 \end{bmatrix}$
$= \begin{bmatrix} -21 & 2x-4 & x-15 \end{bmatrix}$

We are given that this product equals the zero matrix (which in this case must be a $1 \times 3$ zero matrix: $\begin{bmatrix} 0 & 0 & 0 \end{bmatrix}$).
$\begin{bmatrix} -21 & 2x-4 & x-15 \end{bmatrix} = \begin{bmatrix} 0 & 0 & 0 \end{bmatrix}$

Equating corresponding elements:
1.  $-21 = 0$ (This is a contradiction, $-21 \neq 0$)
2.  $2x - 4 = 0$
3.  $x - 15 = 0$

Since the first equation $-21 = 0$ is a contradiction, there is no value of $x$ that can satisfy the given equation. This indicates a potential issue with the problem statement as presented.

**Answer:** No solution exists due to inconsistency.

**Question 7:**
A manufacturer produces three products $x, y, z$ which he sells in two markets. Annual sales are indicated below:

Market | Products
------- | --------
I | 10,000 (x) | 2,000 (y) | 18,000 (z)
II | 6,000 (x) | 20,000 (y) | 8,000 (z)

(a) If unit sale prices of $x, y$ and $z$ are ₹2.50, ₹1.50 and ₹1.00, respectively, find the total revenue in each market with the help of matrix algebra.

**Solution:**
Let the sales matrix be $S$ and the price matrix be $P$.
Sales Matrix $S$:
$$
S = \begin{bmatrix}
10000 & 2000 & 18000 \\
6000 & 20000 & 8000
\end{bmatrix} \quad \begin{array}{c}
\text{Market I} \\
\text{Market II}
\end{array}
$$
Price Matrix $P$ (as a column vector, since price is per unit):
$$
P = \begin{bmatrix} 2.50 \\ 1.50 \\ 1.00 \end{bmatrix} \quad \begin{array}{c}
x \\
y \\
z
\end{array}
$$
Total Revenue is obtained by multiplying $S \times P$:
$$
\text{Revenue} = S \times P = \begin{bmatrix}
10000 & 2000 & 18000 \\
6000 & 20000 & 8000
\end{bmatrix} \begin{bmatrix} 2.50 \\ 1.50 \\ 1.00 \end{bmatrix}
$$
$$
= \begin{bmatrix}
(10000)(2.50) + (2000)(1.50) + (18000)(1.00) \\
(6000)(2.50) + (20000)(1.50) + (8000)(1.00)
\end{bmatrix}
$$
$$
= \begin{bmatrix}
25000 + 3000 + 18000 \\
15000 + 30000 + 8000
\end{bmatrix}
$$
$$
= \begin{bmatrix}
46000 \\
53000
\end{bmatrix}
$$
**Total Revenue:**
*   Market I: ₹46,000
*   Market II: ₹53,000

(b) If the unit costs of the above three commodities are ₹2.00, ₹1.00 and 50 paise respectively. Find the gross profit.

**Solution:**
Unit Cost Matrix $C$ (as a column vector):
50 paise = ₹0.50
$$
C = \begin{bmatrix} 2.00 \\ 1.00 \\ 0.50 \end{bmatrix} \quad \begin{array}{c}
x \\
y \\
z
\end{array}
$$
Gross Profit per unit = Selling Price per unit - Cost Price per unit.
Profit per unit matrix $Pr$:
$$
Pr = P - C = \begin{bmatrix} 2.50 \\ 1.50 \\ 1.00 \end{bmatrix} - \begin{bmatrix} 2.00 \\ 1.00 \\ 0.50 \end{bmatrix} = \begin{bmatrix} 0.50 \\ 0.50 \\ 0.50 \end{bmatrix}
$$
Total Gross Profit = Sales Matrix $S$ $\times$ Profit per unit Matrix $Pr$:
$$
\text{Gross Profit} = S \times Pr = \begin{bmatrix}
10000 & 2000 & 18000 \\
6000 & 20000 & 8000
\end{bmatrix} \begin{bmatrix} 0.50 \\ 0.50 \\ 0.50 \end{bmatrix}
$$
$$
= \begin{bmatrix}
(10000)(0.50) + (2000)(0.50) + (18000)(0.50) \\
(6000)(0.50) + (20000)(0.50) + (8000)(0.50)
\end{bmatrix}
$$
$$
= \begin{bmatrix}
5000 + 1000 + 9000 \\
3000 + 10000 + 4000
\end{bmatrix}
$$
$$
= \begin{bmatrix}
15000 \\
17000
\end{bmatrix}
$$
**Gross Profit:**
*   Market I: ₹15,000
*   Market II: ₹17,000

**Question 8:**
Find the matrix $X$ so that $X \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix} = \begin{bmatrix} -7 & -8 & -9 \\ 2 & 4 & 6 \end{bmatrix}$.

Let $A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$ and $B = \begin{bmatrix} -7 & -8 & -9 \\ 2 & 4 & 6 \end{bmatrix}$. We want to find $X$ such that $XA = B$.
For this equation to hold, the order of $X$ must be such that when multiplied by $A$ (order $3 \times 3$), it results in $B$ (order $2 \times 3$).
Let $X$ be of order $m \times n$. Then $m \times n$ times $3 \times 3$ must give $2 \times 3$.
This implies $n=3$ (inner dimensions must match) and $m=2$ (outer dimension gives the result's row count).
So, $X$ must be of order $2 \times 3$. Let $X = \begin{bmatrix} a & b & c \\ d & e & f \end{bmatrix}$.

$$
\begin{bmatrix} a & b & c \\ d & e & f \end{bmatrix} \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix} = \begin{bmatrix} -7 & -8 & -9 \\ 2 & 4 & 6 \end{bmatrix}
$$
This gives two sets of linear equations:

**For the first row of B:**
1.  $a + 4b + 7c = -7$
2.  $2a + 5b + 8c = -8$
3.  $3a + 6b + 9c = -9$ (Divide by 3: $a + 2b + 3c = -3$)

**For the second row of B:**
4.  $d + 4e + 7f = 2$
5.  $2d + 5e + 8f = 4$
6.  $3d + 6e + 9f = 6$ (Divide by 3: $d + 2e + 3f = 2$)

Let's analyze the matrix $A$. The third row is obtained by $2 \times (\text{second row}) - (\text{first row})$:
$2 \times [4\ 5\ 6] - [1\ 2\ 3] = [8\ 10\ 12] - [1\ 2\ 3] = [7\ 8\ 9]$.
This means the rows of $A$ are linearly dependent. The rank of $A$ is less than 3.
Similarly, for the equations involving $d, e, f$:
$2 \times [4\ 5\ 6] - [1\ 2\ 3] = [7\ 8\ 9]$
$2 \times (\text{row 2}) - (\text{row 1})$ gives row 3.
The third equation for $d,e,f$ simplifies to $d+2e+3f=2$.

This system might have infinite solutions or no solution. Let's try to express some variables in terms of others.
From equation (3, simplified): $a = -3 - 2b - 3c$. Substitute this into (1) and (2).
Equation (1): $(-3 - 2b - 3c) + 4b + 7c = -7 \implies -3 + 2b + 4c = -7 \implies 2b + 4c = -4 \implies b + 2c = -2$.
So, $b = -2 - 2c$.
Then $a = -3 - 2(-2 - 2c) - 3c = -3 + 4 + 4c - 3c = 1 + c$.

Now let's check if these values satisfy equation (2):
$2a + 5b + 8c = 2(1+c) + 5(-2-2c) + 8c = 2 + 2c - 10 - 10c + 8c = (2-10) + (2c-10c+8c) = -8 + 0c = -8$.
This equation is satisfied for any value of $c$.
So, we can express $a$ and $b$ in terms of $c$:
$a = 1 + c$
$b = -2 - 2c$
$c = c$ (free variable)

Similarly for the second row:
From equation (6, simplified): $d = 2 - 2e - 3f$. Substitute this into (4) and (5).
Equation (4): $(2 - 2e - 3f) + 4e + 7f = 2 \implies 2 + 2e + 4f = 2 \implies 2e + 4f = 0 \implies e + 2f = 0$.
So, $e = -2f$.
Then $d = 2 - 2(-2f) - 3f = 2 + 4f - 3f = 2 + f$.

Now let's check if these values satisfy equation (5):
$2d + 5e + 8f = 2(2+f) + 5(-2f) + 8f = 4 + 2f - 10f + 8f = 4 + (2f-10f+8f) = 4 + 0f = 4$.
This equation is satisfied for any value of $f$.
So, we can express $d$ and $e$ in terms of $f$:
$d = 2 + f$
$e = -2f$
$f = f$ (free variable)

Let's choose a simple value for $c$ and $f$, say $c=0$ and $f=0$.
If $c=0$: $a=1, b=-2, c=0$.
If $f=0$: $d=2, e=0, f=0$.

Then $X = \begin{bmatrix} 1 & -2 & 0 \\ 2 & 0 & 0 \end{bmatrix}$.

Let's verify this $X$:
$\begin{bmatrix} 1 & -2 & 0 \\ 2 & 0 & 0 \end{bmatrix} \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix} = \begin{bmatrix} (1)(1)+(-2)(4)+(0)(7) & (1)(2)+(-2)(5)+(0)(8) & (1)(3)+(-2)(6)+(0)(9) \\ (2)(1)+(0)(4)+(0)(7) & (2)(2)+(0)(5)+(0)(8) & (2)(3)+(0)(6)+(0)(9) \end{bmatrix}$
$= \begin{bmatrix} 1-8+0 & 2-10+0 & 3-12+0 \\ 2+0+0 & 4+0+0 & 6+0+0 \end{bmatrix} = \begin{bmatrix} -7 & -8 & -9 \\ 2 & 4 & 6 \end{bmatrix}$.
This matches the right-hand side.
So, $X = \begin{bmatrix} 1 & -2 & 0 \\ 2 & 0 & 0 \end{bmatrix}$ is a solution.

Since there are free variables, there are infinitely many solutions. The question asks for "the" matrix X, which usually implies a unique solution. This suggests that perhaps there was a simpler intended answer or a constraint missed. However, based on the algebra, the matrix $X$ is not unique. Let's present the general form.
Let $c = k_1$ and $f = k_2$, where $k_1, k_2$ are arbitrary constants.
$a = 1 + k_1$
$b = -2 - 2k_1$
$c = k_1$
$d = 2 + k_2$
$e = -2k_2$
$f = k_2$

$X = \begin{bmatrix} 1+k_1 & -2-2k_1 & k_1 \\ 2+k_2 & -2k_2 & k_2 \end{bmatrix}$

If the problem expects a single answer, it might be assuming a minimal solution or a specific choice of constants. The simplest choice ($k_1=0, k_2=0$) gives $X = \begin{bmatrix} 1 & -2 & 0 \\ 2 & 0 & 0 \end{bmatrix}$.

**Answer:** $X = \begin{bmatrix} 1 & -2 & 0 \\ 2 & 0 & 0 \end{bmatrix}$ (or more generally, $X = \begin{bmatrix} 1+k_1 & -2-2k_1 & k_1 \\ 2+k_2 & -2k_2 & k_2 \end{bmatrix}$ for arbitrary constants $k_1, k_2$).