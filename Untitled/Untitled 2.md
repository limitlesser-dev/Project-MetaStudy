# Chapter 3: Matrices - Detailed Answer Sheet

---

## 1. Definition, Order & Types of Matrices - Solutions

### Question 1.1
Consider the matrix $M = \begin{bmatrix} 2 & 0 & -1 \\ \sqrt{3} & 5 & 7 \\ -4 & 1/2 & 9 \end{bmatrix}$.
1.  What is the order of matrix $M$?
2.  Identify the elements $m_{23}$ and $m_{31}$.
3.  If a matrix has 13 elements, what are the possible orders it can have?

> [!SOLUTION] Answer 1.1
> 1.  Matrix $M$ has 3 rows and 3 columns.
>     The order of matrix $M$ is **$3 \times 3$**.
> 2.  $m_{23}$ refers to the element in the 2nd row and 3rd column. So, $m_{23} = 7$.
>     $m_{31}$ refers to the element in the 3rd row and 1st column. So, $m_{31} = -4$.
> 3.  If a matrix has 13 elements, its order (rows $\times$ columns) must multiply to 13. Since 13 is a prime number, its only integer factors are 1 and 13.
>     The possible orders are: **$1 \times 13$** and **$13 \times 1$**.

### Question 1.2
Classify each of the following matrices by its type (e.g., Row, Column, Square, Diagonal, Scalar, Identity, Zero).
1.  $A = \begin{bmatrix} 0 & 0 \\ 0 & 0 \end{bmatrix}$
2.  $B = \begin{bmatrix} -1 & 4 & 7 \end{bmatrix}$
3.  $C = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}$
4.  $D = \begin{bmatrix} 5 & 0 \\ 0 & 5 \end{bmatrix}$
5.  $E = \begin{bmatrix} 9 \\ 2 \\ 0 \end{bmatrix}$

> [!SOLUTION] Answer 1.2
> 1.  $A = \begin{bmatrix} 0 & 0 \\ 0 & 0 \end{bmatrix}$: This is a **Zero Matrix** (all elements are zero) and also a **Square Matrix** (2 rows, 2 columns). More specifically, it's a square zero matrix.
> 2.  $B = \begin{bmatrix} -1 & 4 & 7 \end{bmatrix}$: This matrix has only one row. It is a **Row Matrix**.
> 3.  $C = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}$: This is a square matrix with 1s on the main diagonal and 0s elsewhere. It is an **Identity Matrix**. (It is also a Scalar Matrix and a Diagonal Matrix, but Identity is the most specific classification).
> 4.  $D = \begin{bmatrix} 5 & 0 \\ 0 & 5 \end{bmatrix}$: This is a square matrix with zeros off the main diagonal and all diagonal elements being the same non-zero scalar (5). It is a **Scalar Matrix**. (It is also a Diagonal Matrix and a Square Matrix).
> 5.  $E = \begin{bmatrix} 9 \\ 2 \\ 0 \end{bmatrix}$: This matrix has only one column. It is a **Column Matrix**.

---

## 2. Equality of Matrices - Solutions

### Question 2.1
Find the values of $x, y, z,$ and $w$ if:
$\begin{bmatrix} x+y & 2x \\ x-y & z+w \end{bmatrix} = \begin{bmatrix} 8 & 6 \\ 2 & 10 \end{bmatrix}$

> [!SOLUTION] Answer 2.1
> By the definition of equality of matrices, corresponding elements must be equal:
> 1.  $x+y = 8$ (Eq 1)
> 2.  $2x = 6$ (Eq 2)
> 3.  $x-y = 2$ (Eq 3)
> 4.  $z+w = 10$ (Eq 4)
>
> From (Eq 2):
> $2x = 6 \implies x = 3$
>
> Substitute $x=3$ into (Eq 1):
> $3+y = 8 \implies y = 8-3 \implies y = 5$
>
> (Verify with Eq 3: $x-y = 3-5 = -2$. This does not match 2. This implies there's an inconsistency in the question setup if these were meant to be independent equations derived from one source. However, in such problems, you usually take the specific equations as given.)
>
> **Self-Correction:** My apologies, I made a mistake in setting up the question for $x-y$ and $2x$. In NCERT problems, these systems are always consistent. Let's assume the question *meant* the following:
>
> $\begin{bmatrix} x+y & 2x \\ x-y & z+w \end{bmatrix} = \begin{bmatrix} 8 & 6 \\ -2 & 10 \end{bmatrix}$
>
> If this were the case:
> $x+y = 8$
> $2x = 6 \implies x=3$
> $x-y = -2$
> $z+w = 10$
>
> From $x=3$ and $x+y=8 \implies 3+y=8 \implies y=5$.
> Check with $x-y=-2 \implies 3-5=-2$. This works!
>
> Now, we need more information to solve for $z$ and $w$ individually unless the question intended only for one possible combination (e.g., $z=5, w=5$).
>
> **Assuming a consistent problem (like NCERT would provide), where $x-y=2$ was actually $x-y=-2$, then:**
> $x=3$, $y=5$.
> $z+w = 10$. (We cannot find unique values for $z$ and $w$ with only one equation).
>
> Let's provide a revised, fully solvable version common in NCERT:
> **Revised Question 2.1:**
> Find the values of $x, y, z, a, b, c$ if:
> $\begin{bmatrix} x+y & 2x+z \\ x-y & 2z+a \\ 3b & c-1 \end{bmatrix} = \begin{bmatrix} 8 & 12 \\ 2 & 10 \\ -6 & 2 \end{bmatrix}$
>
> **Revised Solution 2.1:**
> 5.  $x+y=8$
> 6.  $2x+z=12$
> 7.  $x-y=2$
> 8.  $2z+a=10$
> 9.  $3b=-6$
> 10.  $c-1=2$
>
> From (3) $x-y=2$ and (1) $x+y=8$:
> Add (1) + (3): $(x+y) + (x-y) = 8+2 \implies 2x = 10 \implies \mathbf{x=5}$
> Substitute $x=5$ into (1): $5+y=8 \implies \mathbf{y=3}$
>
> From (2) $2x+z=12$:
> Substitute $x=5$: $2(5)+z=12 \implies 10+z=12 \implies \mathbf{z=2}$
>
> From (4) $2z+a=10$:
> Substitute $z=2$: $2(2)+a=10 \implies 4+a=10 \implies \mathbf{a=6}$
>
> From (5) $3b=-6$:
> $\mathbf{b=-2}$
>
> From (6) $c-1=2$:
> $\mathbf{c=3}$
>
> So, $x=5, y=3, z=2, a=6, b=-2, c=3$.

### Question 2.2
For what values of $a, b, c$ are the following matrices equal?
$P = \begin{bmatrix} a+2 & 4 \\ 3b & c-1 \end{bmatrix}$ and $Q = \begin{bmatrix} 3 & 4 \\ -6 & 2 \end{bmatrix}$

> [!SOLUTION] Answer 2.2
> By definition of equality:
> 1.  $a+2 = 3$
> 2.  $4 = 4$ (This is consistent)
> 3.  $3b = -6$
> 4.  $c-1 = 2$
>
> From (1): $a+2 = 3 \implies \mathbf{a = 1}$
> From (3): $3b = -6 \implies \mathbf{b = -2}$
> From (4): $c-1 = 2 \implies \mathbf{c = 3}$

---

## 3. Matrix Addition & Subtraction - Solutions

### Question 3.1
If $A = \begin{bmatrix} 2 & 3 \\ 4 & 5 \end{bmatrix}$ and $B = \begin{bmatrix} 0 & -1 \\ 2 & 7 \end{bmatrix}$, find:
1.  $A+B$
2.  $A-B$

> [!SOLUTION] Answer 3.1
> Both matrices are of order $2 \times 2$, so addition and subtraction are defined.
>
> 1.  $A+B = \begin{bmatrix} 2 & 3 \\ 4 & 5 \end{bmatrix} + \begin{bmatrix} 0 & -1 \\ 2 & 7 \end{bmatrix} = \begin{bmatrix} 2+0 & 3+(-1) \\ 4+2 & 5+7 \end{bmatrix} = \mathbf{\begin{bmatrix} 2 & 2 \\ 6 & 12 \end{bmatrix}}$
> 2.  $A-B = \begin{bmatrix} 2 & 3 \\ 4 & 5 \end{bmatrix} - \begin{bmatrix} 0 & -1 \\ 2 & 7 \end{bmatrix} = \begin{bmatrix} 2-0 & 3-(-1) \\ 4-2 & 5-7 \end{bmatrix} = \mathbf{\begin{bmatrix} 2 & 4 \\ 2 & -2 \end{bmatrix}}$

### Question 3.2
Given $X = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{bmatrix}$ and $Y = \begin{bmatrix} -1 & 0 & 1 \\ -2 & -3 & -4 \end{bmatrix}$.
1.  Find $X+Y$.
2.  Can you find $X- \begin{bmatrix} 1 \\ 2 \end{bmatrix}$? Explain why or why not.

> [!SOLUTION] Answer 3.2
> 1.  Both $X$ and $Y$ are $2 \times 3$ matrices, so addition is defined.
>     $X+Y = \begin{bmatrix} 1+(-1) & 2+0 & 3+1 \\ 4+(-2) & 5+(-3) & 6+(-4) \end{bmatrix} = \mathbf{\begin{bmatrix} 0 & 2 & 4 \\ 2 & 2 & 2 \end{bmatrix}}$
> 2.  The matrix $X$ is of order $2 \times 3$. The matrix $\begin{bmatrix} 1 \\ 2 \end{bmatrix}$ is of order $2 \times 1$.
>     Since the orders of the two matrices are different, **subtraction is not defined**. Matrices can only be added or subtracted if they have the exact same dimensions.

---

## 4. Scalar Multiplication - Solutions

### Question 4.1
If $A = \begin{bmatrix} -2 & 3 \\ 5 & 0 \end{bmatrix}$, find $3A$ and $-A$.

> [!SOLUTION] Answer 4.1
> For scalar multiplication, multiply every element of the matrix by the scalar.
> 1.  $3A = 3 \times \begin{bmatrix} -2 & 3 \\ 5 & 0 \end{bmatrix} = \begin{bmatrix} 3 \times (-2) & 3 \times 3 \\ 3 \times 5 & 3 \times 0 \end{bmatrix} = \mathbf{\begin{bmatrix} -6 & 9 \\ 15 & 0 \end{bmatrix}}$
> 2.  $-A = (-1) \times A = (-1) \times \begin{bmatrix} -2 & 3 \\ 5 & 0 \end{bmatrix} = \begin{bmatrix} (-1) \times (-2) & (-1) \times 3 \\ (-1) \times 5 & (-1) \times 0 \end{bmatrix} = \mathbf{\begin{bmatrix} 2 & -3 \\ -5 & 0 \end{bmatrix}}$

### Question 4.2
Given $B = \begin{bmatrix} 1 & 2 & 3 \\ 0 & 1/2 & -1 \end{bmatrix}$, calculate $\frac{1}{2}B$.

> [!SOLUTION] Answer 4.2
> $\frac{1}{2}B = \frac{1}{2} \times \begin{bmatrix} 1 & 2 & 3 \\ 0 & 1/2 & -1 \end{bmatrix} = \begin{bmatrix} \frac{1}{2} \times 1 & \frac{1}{2} \times 2 & \frac{1}{2} \times 3 \\ \frac{1}{2} \times 0 & \frac{1}{2} \times \frac{1}{2} & \frac{1}{2} \times (-1) \end{bmatrix} = \mathbf{\begin{bmatrix} 1/2 & 1 & 3/2 \\ 0 & 1/4 & -1/2 \end{bmatrix}}$

---

## 5. Matrix Multiplication - Solutions

### Question 5.1
If $A = \begin{bmatrix} 2 & 1 \\ 3 & 2 \end{bmatrix}$ and $B = \begin{bmatrix} 1 & 0 \\ 1 & 1 \end{bmatrix}$, find:
1.  $AB$
2.  $BA$
(Observe your results for commutativity!)

> [!SOLUTION] Answer 5.1
> Both A and B are $2 \times 2$ matrices. So, both $AB$ and $BA$ are defined and will be $2 \times 2$.
>
> 1.  **$AB$**:
>     $AB = \begin{bmatrix} 2 & 1 \\ 3 & 2 \end{bmatrix} \begin{bmatrix} 1 & 0 \\ 1 & 1 \end{bmatrix}$
>     $c_{11} = (2 \times 1) + (1 \times 1) = 2 + 1 = 3$
>     $c_{12} = (2 \times 0) + (1 \times 1) = 0 + 1 = 1$
>     $c_{21} = (3 \times 1) + (2 \times 1) = 3 + 2 = 5$
>     $c_{22} = (3 \times 0) + (2 \times 1) = 0 + 2 = 2$
>     $\mathbf{AB = \begin{bmatrix} 3 & 1 \\ 5 & 2 \end{bmatrix}}$
>
> 2.  **$BA$**:
>     $BA = \begin{bmatrix} 1 & 0 \\ 1 & 1 \end{bmatrix} \begin{bmatrix} 2 & 1 \\ 3 & 2 \end{bmatrix}$
>     $c_{11} = (1 \times 2) + (0 \times 3) = 2 + 0 = 2$
>     $c_{12} = (1 \times 1) + (0 \times 2) = 1 + 0 = 1$
>     $c_{21} = (1 \times 2) + (1 \times 3) = 2 + 3 = 5$
>     $c_{22} = (1 \times 1) + (1 \times 2) = 1 + 2 = 3$
>     $\mathbf{BA = \begin{bmatrix} 2 & 1 \\ 5 & 3 \end{bmatrix}}$
>
> **Observation:** Since $AB = \begin{bmatrix} 3 & 1 \\ 5 & 2 \end{bmatrix} \ne BA = \begin{bmatrix} 2 & 1 \\ 5 & 3 \end{bmatrix}$, this demonstrates that **matrix multiplication is generally not commutative ($AB \ne BA$)**.

### Question 5.2
If $X = \begin{bmatrix} 1 & -2 & 3 \end{bmatrix}$ and $Y = \begin{bmatrix} 2 \\ 4 \\ -1 \end{bmatrix}$, find:
1.  $XY$
2.  $YX$

> [!SOLUTION] Answer 5.2
> 1.  **$XY$**:
>     $X$ is $1 \times 3$. $Y$ is $3 \times 1$.
>     Columns of X (3) = Rows of Y (3). So $XY$ is defined.
>     Order of $XY$ will be $1 \times 1$.
>     $XY = \begin{bmatrix} 1 & -2 & 3 \end{bmatrix} \begin{bmatrix} 2 \\ 4 \\ -1 \end{bmatrix}$
>     $c_{11} = (1 \times 2) + (-2 \times 4) + (3 \times -1) = 2 - 8 - 3 = -9$
>     $\mathbf{XY = \begin{bmatrix} -9 \end{bmatrix}}$
>
> 2.  **$YX$**:
>     $Y$ is $3 \times 1$. $X$ is $1 \times 3$.
>     Columns of Y (1) = Rows of X (1). So $YX$ is defined.
>     Order of $YX$ will be $3 \times 3$.
>     $YX = \begin{bmatrix} 2 \\ 4 \\ -1 \end{bmatrix} \begin{bmatrix} 1 & -2 & 3 \end{bmatrix}$
>     $p_{11} = 2 \times 1 = 2$
>     $p_{12} = 2 \times (-2) = -4$
>     $p_{13} = 2 \times 3 = 6$
>     $p_{21} = 4 \times 1 = 4$
>     $p_{22} = 4 \times (-2) = -8$
>     $p_{23} = 4 \times 3 = 12$
>     $p_{31} = -1 \times 1 = -1$
>     $p_{32} = -1 \times (-2) = 2$
>     $p_{33} = -1 \times 3 = -3$
>     $\mathbf{YX = \begin{bmatrix} 2 & -4 & 6 \\ 4 & -8 & 12 \\ -1 & 2 & -3 \end{bmatrix}}$

---

## 6. Transpose of a Matrix - Solutions

### Question 6.1
Find the transpose of the following matrices:
1.  $A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \\ 5 & 6 \end{bmatrix}$
2.  $B = \begin{bmatrix} 7 & 8 & 9 \\ 10 & 11 & 12 \\ 13 & 14 & 15 \end{bmatrix}$

> [!SOLUTION] Answer 6.1
> 1.  $A$ is a $3 \times 2$ matrix. Its transpose $A^T$ will be $2 \times 3$.
>     $\mathbf{A^T = \begin{bmatrix} 1 & 3 & 5 \\ 2 & 4 & 6 \end{bmatrix}}$
> 2.  $B$ is a $3 \times 3$ matrix. Its transpose $B^T$ will also be $3 \times 3$.
>     $\mathbf{B^T = \begin{bmatrix} 7 & 10 & 13 \\ 8 & 11 & 14 \\ 9 & 12 & 15 \end{bmatrix}}$

### Question 6.2
Given $C = \begin{bmatrix} 1 & 2 \\ 0 & 3 \end{bmatrix}$ and $D = \begin{bmatrix} -1 & 0 \\ 4 & 5 \end{bmatrix}$, verify that $(CD)^T = D^T C^T$.

> [!SOLUTION] Answer 6.2
> **Step 1: Calculate $CD$.**
> $CD = \begin{bmatrix} 1 & 2 \\ 0 & 3 \end{bmatrix} \begin{bmatrix} -1 & 0 \\ 4 & 5 \end{bmatrix} = \begin{bmatrix} (1)(-1)+(2)(4) & (1)(0)+(2)(5) \\ (0)(-1)+(3)(4) & (0)(0)+(3)(5) \end{bmatrix}$
> $CD = \begin{bmatrix} -1+8 & 0+10 \\ 0+12 & 0+15 \end{bmatrix} = \begin{bmatrix} 7 & 10 \\ 12 & 15 \end{bmatrix}$
>
> **Step 2: Calculate $(CD)^T$.**
> $(CD)^T = \mathbf{\begin{bmatrix} 7 & 12 \\ 10 & 15 \end{bmatrix}}$
>
> **Step 3: Calculate $C^T$ and $D^T$.**
> $C^T = \begin{bmatrix} 1 & 0 \\ 2 & 3 \end{bmatrix}$
> $D^T = \begin{bmatrix} -1 & 4 \\ 0 & 5 \end{bmatrix}$
>
> **Step 4: Calculate $D^T C^T$.**
> $D^T C^T = \begin{bmatrix} -1 & 4 \\ 0 & 5 \end{bmatrix} \begin{bmatrix} 1 & 0 \\ 2 & 3 \end{bmatrix} = \begin{bmatrix} (-1)(1)+(4)(2) & (-1)(0)+(4)(3) \\ (0)(1)+(5)(2) & (0)(0)+(5)(3) \end{bmatrix}$
> $D^T C^T = \begin{bmatrix} -1+8 & 0+12 \\ 0+10 & 0+15 \end{bmatrix} = \mathbf{\begin{bmatrix} 7 & 12 \\ 10 & 15 \end{bmatrix}}$
>
> **Conclusion:** Since $(CD)^T = \begin{bmatrix} 7 & 12 \\ 10 & 15 \end{bmatrix}$ and $D^T C^T = \begin{bmatrix} 7 & 12 \\ 10 & 15 \end{bmatrix}$, we have verified that **$(CD)^T = D^T C^T$**.

---

## 7. Symmetric & Skew-Symmetric Matrices - Solutions

### Question 7.1
Check if the following matrices are symmetric, skew-symmetric, or neither:
1.  $P = \begin{bmatrix} 1 & -2 & 3 \\ -2 & 4 & 0 \\ 3 & 0 & 5 \end{bmatrix}$
2.  $Q = \begin{bmatrix} 0 & 1 & -2 \\ -1 & 0 & 3 \\ 2 & -3 & 0 \end{bmatrix}$
3.  $R = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$

> [!SOLUTION] Answer 7.1
> 1.  **For P:**
>     $P^T = \begin{bmatrix} 1 & -2 & 3 \\ -2 & 4 & 0 \\ 3 & 0 & 5 \end{bmatrix}$
>     Since $P^T = P$, $P$ is a **Symmetric Matrix**.
> 2.  **For Q:**
>     First, check diagonals: All are 0. (Good sign for skew-symmetric)
>     $Q^T = \begin{bmatrix} 0 & -1 & 2 \\ 1 & 0 & -3 \\ -2 & 3 & 0 \end{bmatrix}$
>     $-Q^T = \begin{bmatrix} 0 & 1 & -2 \\ -1 & 0 & 3 \\ 2 & -3 & 0 \end{bmatrix}$
>     Since $Q = -Q^T$, $Q$ is a **Skew-Symmetric Matrix**.
> 3.  **For R:**
>     $R^T = \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix}$
>     Since $R \ne R^T$, $R$ is not symmetric.
>     $-R^T = \begin{bmatrix} -1 & -3 \\ -2 & -4 \end{bmatrix}$
>     Since $R \ne -R^T$, $R$ is not skew-symmetric.
>     Therefore, $R$ is **neither symmetric nor skew-symmetric**.

### Question 7.2
Express the matrix $A = \begin{bmatrix} 4 & -2 \\ 1 & 0 \end{bmatrix}$ as the sum of a symmetric and a skew-symmetric matrix.

> [!SOLUTION] Answer 7.2
> We use the formulas: $P = \frac{1}{2}(A + A^T)$ and $Q = \frac{1}{2}(A - A^T)$.
>
> **Step 1: Find $A^T$.**
> $A^T = \begin{bmatrix} 4 & 1 \\ -2 & 0 \end{bmatrix}$
>
> **Step 2: Calculate $P = \frac{1}{2}(A + A^T)$.**
> $A + A^T = \begin{bmatrix} 4 & -2 \\ 1 & 0 \end{bmatrix} + \begin{bmatrix} 4 & 1 \\ -2 & 0 \end{bmatrix} = \begin{bmatrix} 4+4 & -2+1 \\ 1+(-2) & 0+0 \end{bmatrix} = \begin{bmatrix} 8 & -1 \\ -1 & 0 \end{bmatrix}$
> $P = \frac{1}{2} \begin{bmatrix} 8 & -1 \\ -1 & 0 \end{bmatrix} = \mathbf{\begin{bmatrix} 4 & -1/2 \\ -1/2 & 0 \end{bmatrix}}$
> (Check: $P^T = P$, so $P$ is symmetric)
>
> **Step 3: Calculate $Q = \frac{1}{2}(A - A^T)$.**
> $A - A^T = \begin{bmatrix} 4 & -2 \\ 1 & 0 \end{bmatrix} - \begin{bmatrix} 4 & 1 \\ -2 & 0 \end{bmatrix} = \begin{bmatrix} 4-4 & -2-1 \\ 1-(-2) & 0-0 \end{bmatrix} = \begin{bmatrix} 0 & -3 \\ 3 & 0 \end{bmatrix}$
> $Q = \frac{1}{2} \begin{bmatrix} 0 & -3 \\ 3 & 0 \end{bmatrix} = \mathbf{\begin{bmatrix} 0 & -3/2 \\ 3/2 & 0 \end{bmatrix}}$
> (Check: $Q^T = \begin{bmatrix} 0 & 3/2 \\ -3/2 & 0 \end{bmatrix} = -Q$, so $Q$ is skew-symmetric, and diagonals are 0)
>
> **Step 4: Express $A = P + Q$.**
> $\begin{bmatrix} 4 & -2 \\ 1 & 0 \end{bmatrix} = \begin{bmatrix} 4 & -1/2 \\ -1/2 & 0 \end{bmatrix} + \begin{bmatrix} 0 & -3/2 \\ 3/2 & 0 \end{bmatrix}$
> Check sum: $\begin{bmatrix} 4+0 & -1/2 - 3/2 \\ -1/2 + 3/2 & 0+0 \end{bmatrix} = \begin{bmatrix} 4 & -4/2 \\ 2/2 & 0 \end{bmatrix} = \begin{bmatrix} 4 & -2 \\ 1 & 0 \end{bmatrix}$. This matches A.

---

## 8. Elementary Operations / Inverse by Elementary Operations - Solutions

### Question 8.1
Perform the following elementary row operations on matrix $A = \begin{bmatrix} 1 & 3 & 5 \\ 2 & 0 & 4 \\ -1 & 1 & 6 \end{bmatrix}$:
1.  $R_1 \leftrightarrow R_3$
2.  $R_2 \rightarrow \frac{1}{2}R_2$
3.  $R_3 \rightarrow R_3 + R_1$ (using the original $A$)

> [!SOLUTION] Answer 8.1
> Given $A = \begin{bmatrix} 1 & 3 & 5 \\ 2 & 0 & 4 \\ -1 & 1 & 6 \end{bmatrix}$
>
> 1.  **$R_1 \leftrightarrow R_3$**:
>     Swap Row 1 and Row 3.
>     $A \sim \mathbf{\begin{bmatrix} -1 & 1 & 6 \\ 2 & 0 & 4 \\ 1 & 3 & 5 \end{bmatrix}}$
>
> 2.  **$R_2 \rightarrow \frac{1}{2}R_2$**:
>     Multiply every element in Row 2 by $\frac{1}{2}$.
>     $A \sim \begin{bmatrix} 1 & 3 & 5 \\ 2 \times \frac{1}{2} & 0 \times \frac{1}{2} & 4 \times \frac{1}{2} \\ -1 & 1 & 6 \end{bmatrix} = \mathbf{\begin{bmatrix} 1 & 3 & 5 \\ 1 & 0 & 2 \\ -1 & 1 & 6 \end{bmatrix}}$
>
> 3.  **$R_3 \rightarrow R_3 + R_1$ (using the original $A$)**:
>     Add Row 1 to Row 3. The result replaces Row 3. Row 1 remains unchanged.
>     $A \sim \begin{bmatrix} 1 & 3 & 5 \\ 2 & 0 & 4 \\ -1+1 & 1+3 & 6+5 \end{bmatrix} = \mathbf{\begin{bmatrix} 1 & 3 & 5 \\ 2 & 0 & 4 \\ 0 & 4 & 11 \end{bmatrix}}$

### Question 8.2
Find the inverse of the matrix $A = \begin{bmatrix} 2 & 1 \\ 1 & 1 \end{bmatrix}$ using elementary row operations.

> [!SOLUTION] Answer 8.2
> **Goal:** Transform $A = IA$ into $I = A^{-1}A$.
>
> Start with:
> $\begin{bmatrix} 2 & 1 \\ 1 & 1 \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} A$
>
> **Step 1: Make $a_{11}$ equal to 1.** (Swap $R_1$ and $R_2$ to get a 1 in the top-left).
> $R_1 \leftrightarrow R_2$:
> $\begin{bmatrix} 1 & 1 \\ 2 & 1 \end{bmatrix} = \begin{bmatrix} 0 & 1 \\ 1 & 0 \end{bmatrix} A$
>
> **Step 2: Make $a_{21}$ equal to 0.**
> $R_2 \rightarrow R_2 - 2R_1$:
> Left side: $\begin{bmatrix} 1 & 1 \\ 2 - 2(1) & 1 - 2(1) \end{bmatrix} = \begin{bmatrix} 1 & 1 \\ 0 & -1 \end{bmatrix}$
> Right side: $\begin{bmatrix} 0 & 1 \\ 1 - 2(0) & 0 - 2(1) \end{bmatrix} = \begin{bmatrix} 0 & 1 \\ 1 & -2 \end{bmatrix}$
> So: $\begin{bmatrix} 1 & 1 \\ 0 & -1 \end{bmatrix} = \begin{bmatrix} 0 & 1 \\ 1 & -2 \end{bmatrix} A$
>
> **Step 3: Make $a_{22}$ equal to 1.**
> $R_2 \rightarrow -1R_2$:
> Left side: $\begin{bmatrix} 1 & 1 \\ 0 \times (-1) & -1 \times (-1) \end{bmatrix} = \begin{bmatrix} 1 & 1 \\ 0 & 1 \end{bmatrix}$
> Right side: $\begin{bmatrix} 0 & 1 \\ 1 \times (-1) & -2 \times (-1) \end{bmatrix} = \begin{bmatrix} 0 & 1 \\ -1 & 2 \end{bmatrix}$
> So: $\begin{bmatrix} 1 & 1 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 0 & 1 \\ -1 & 2 \end{bmatrix} A$
>
> **Step 4: Make $a_{12}$ equal to 0.**
> $R_1 \rightarrow R_1 - R_2$:
> Left side: $\begin{bmatrix} 1 - 0 & 1 - 1 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}$
> Right side: $\begin{bmatrix} 0 - (-1) & 1 - 2 \\ -1 & 2 \end{bmatrix} = \begin{bmatrix} 1 & -1 \\ -1 & 2 \end{bmatrix}$
> So: $\begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 1 & -1 \\ -1 & 2 \end{bmatrix} A$
>
> **Result:** The left side is now the identity matrix $I$. The right side is $A^{-1}$.
> Therefore, the inverse of $A$ is $\mathbf{A^{-1} = \begin{bmatrix} 1 & -1 \\ -1 & 2 \end{bmatrix}}$.
>
> **Verification (Optional but recommended):**
> $A A^{-1} = \begin{bmatrix} 2 & 1 \\ 1 & 1 \end{bmatrix} \begin{bmatrix} 1 & -1 \\ -1 & 2 \end{bmatrix} = \begin{bmatrix} (2)(1)+(1)(-1) & (2)(-1)+(1)(2) \\ (1)(1)+(1)(-1) & (1)(-1)+(1)(2) \end{bmatrix}$
> $= \begin{bmatrix} 2-1 & -2+2 \\ 1-1 & -1+2 \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = I$. The inverse is correct!

---

I hope these detailed solutions help you solidify your understanding of Chapter 3. Keep practicing, and you'll master matrices in no time!