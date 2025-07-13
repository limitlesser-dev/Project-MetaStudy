Welcome back! We're diving into the most crucial matrix operation today: **Matrix Multiplication**. This is where many of the powerful applications of matrices come from, so let's understand it thoroughly.

---

## 4. Matrix Multiplication

Matrix multiplication is *not* element-wise multiplication. It's a fundamental operation with unique rules that combine rows and columns in a specific way.

### 4.1 Condition for Matrix Multiplication

> [!TIP] The MOST Important Rule for Matrix Multiplication!
> Two matrices, say $A$ and $B$, can be multiplied to form the product $AB$ **if and only if** the **number of columns in the first matrix ($A$) is equal to the number of rows in the second matrix ($B$)**.

Let's formalize this:
*   If matrix $A$ has order $m \times n$
*   And matrix $B$ has order $p \times q$

For the product $AB$ to be defined, $n$ **must be equal to** $p$.
That is: **`(columns of A) = (rows of B)`**

### 4.2 Order of the Resulting Product Matrix ($AB$)

If $A$ is $m \times n$ and $B$ is $n \times q$ (since $p=n$), then the product $AB$ will be of order **$m \times q$**.
Think of it like this:
$(m \times n)$ $\times$ $(n \times q)$ $\rightarrow$ $(m \times q)$
The "inner" dimensions ($n$) must match, and the "outer" dimensions ($m$ and $q$) determine the size of the result.

> [!EXAMPLE] Checking if multiplication is possible
> *   Can we multiply $A_{2 \times 3}$ by $B_{3 \times 4}$?
>     *   Columns of A (3) = Rows of B (3)? **YES!**
>     *   Resulting order: $2 \times 4$
> *   Can we multiply $C_{3 \times 2}$ by $D_{3 \times 2}$?
>     *   Columns of C (2) = Rows of D (3)? **NO!**
>     *   Multiplication $CD$ is **undefined**.
> *   Can we multiply $E_{2 \times 2}$ by $F_{2 \times 2}$?
>     *   Columns of E (2) = Rows of F (2)? **YES!**
>     *   Resulting order: $2 \times 2$

### 4.3 How to Multiply Matrices (The "Row by Column" Rule)

The element in the $i$-th row and $j$-th column of the product matrix $AB$ (let's call it $C$) is found by taking the **dot product** of the $i$-th row of matrix $A$ and the $j$-th column of matrix $B$.

Let $A = \begin{bmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{bmatrix}$ and $B = \begin{bmatrix} b_{11} & b_{12} \\ b_{21} & b_{22} \end{bmatrix}$.
The product $AB = C$ will be a $2 \times 2$ matrix: $C = \begin{bmatrix} c_{11} & c_{12} \\ c_{21} & c_{22} \end{bmatrix}$.

*   **To find $c_{11}$ (1st row, 1st column of C):**
    *   Take **1st row of A**: $[a_{11} \quad a_{12}]$
    *   Take **1st column of B**: $\begin{bmatrix} b_{11} \\ b_{21} \end{bmatrix}$
    *   Multiply corresponding elements and sum: $c_{11} = (a_{11} \times b_{11}) + (a_{12} \times b_{21})$

*   **To find $c_{12}$ (1st row, 2nd column of C):**
    *   Take **1st row of A**: $[a_{11} \quad a_{12}]$
    *   Take **2nd column of B**: $\begin{bmatrix} b_{12} \\ b_{22} \end{bmatrix}$
    *   Multiply corresponding elements and sum: $c_{12} = (a_{11} \times b_{12}) + (a_{12} \times b_{22})$

*   **To find $c_{21}$ (2nd row, 1st column of C):**
    *   Take **2nd row of A**: $[a_{21} \quad a_{22}]$
    *   Take **1st column of B**: $\begin{bmatrix} b_{11} \\ b_{21} \end{bmatrix}$
    *   Multiply corresponding elements and sum: $c_{21} = (a_{21} \times b_{11}) + (a_{22} \times b_{21})$

*   **To find $c_{22}$ (2nd row, 2nd column of C):**
    *   Take **2nd row of A**: $[a_{21} \quad a_{22}]$
    *   Take **2nd column of B**: $\begin{bmatrix} b_{12} \\ b_{22} \end{bmatrix}$
    *   Multiply corresponding elements and sum: $c_{22} = (a_{21} \times b_{12}) + (a_{22} \times b_{22})$

---

> [!EXAMPLE] Numerical Matrix Multiplication
> Let $A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$ and $B = \begin{bmatrix} 3 & 0 \\ 1 & 2 \end{bmatrix}$.
> Find $AB$.
>
> **Step 1: Check compatibility and resulting order.**
> *   $A$ is $2 \times 2$, $B$ is $2 \times 2$.
> *   Columns of A (2) = Rows of B (2). **YES!**
> *   Resulting order will be $2 \times 2$.
>
> **Step 2: Calculate each element of the product matrix $C = AB$.**
> $C = \begin{bmatrix} c_{11} & c_{12} \\ c_{21} & c_{22} \end{bmatrix}$
>
> *   $c_{11}$ (Row 1 of A $\times$ Column 1 of B):
>     $[1 \quad 2] \times \begin{bmatrix} 3 \\ 1 \end{bmatrix} = (1 \times 3) + (2 \times 1) = 3 + 2 = 5$
>
> *   $c_{12}$ (Row 1 of A $\times$ Column 2 of B):
>     $[1 \quad 2] \times \begin{bmatrix} 0 \\ 2 \end{bmatrix} = (1 \times 0) + (2 \times 2) = 0 + 4 = 4$
>
> *   $c_{21}$ (Row 2 of A $\times$ Column 1 of B):
>     $[3 \quad 4] \times \begin{bmatrix} 3 \\ 1 \end{bmatrix} = (3 \times 3) + (4 \times 1) = 9 + 4 = 13$
>
> *   $c_{22}$ (Row 2 of A $\times$ Column 2 of B):
>     $[3 \quad 4] \times \begin{bmatrix} 0 \\ 2 \end{bmatrix} = (3 \times 0) + (4 \times 2) = 0 + 8 = 8$
>
> **Step 3: Assemble the product matrix.**
> $AB = \begin{bmatrix} 5 & 4 \\ 13 & 8 \end{bmatrix}$

---

### 4.4 Important Note: Non-Commutativity of Matrix Multiplication

> [!WARNING] $AB \ne BA$ in general!
> In general, for matrices $A$ and $B$, $AB \ne BA$.
> *   Sometimes $BA$ might not even be defined (if dimensions don't match for $BA$).
> *   Even if both $AB$ and $BA$ are defined and have the same order (e.g., both A and B are square matrices of the same order), their products are usually different. This is a key distinction from multiplication of real numbers.

> [!EXAMPLE] Demonstrating Non-Commutativity
> Let's quickly check this for our previous example:
> $B = \begin{bmatrix} 3 & 0 \\ 1 & 2 \end{bmatrix}$ and $A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$. Find $BA$.
>
> $BA = \begin{bmatrix} c_{11} & c_{12} \\ c_{21} & c_{22} \end{bmatrix}$
> *   $c_{11}$ (Row 1 of B $\times$ Column 1 of A): $[3 \quad 0] \times \begin{bmatrix} 1 \\ 3 \end{bmatrix} = (3 \times 1) + (0 \times 3) = 3 + 0 = 3$
> *   $c_{12}$ (Row 1 of B $\times$ Column 2 of A): $[3 \quad 0] \times \begin{bmatrix} 2 \\ 4 \end{bmatrix} = (3 \times 2) + (0 \times 4) = 6 + 0 = 6$
> *   $c_{21}$ (Row 2 of B $\times$ Column 1 of A): $[1 \quad 2] \times \begin{bmatrix} 1 \\ 3 \end{bmatrix} = (1 \times 1) + (2 \times 3) = 1 + 6 = 7$
> *   $c_{22}$ (Row 2 of B $\times$ Column 2 of A): $[1 \quad 2] \times \begin{bmatrix} 2 \\ 4 \end{bmatrix} = (1 \times 2) + (2 \times 4) = 2 + 8 = 10$
>
> So, $BA = \begin{bmatrix} 3 & 6 \\ 7 & 10 \end{bmatrix}$
>
> Clearly, $AB = \begin{bmatrix} 5 & 4 \\ 13 & 8 \end{bmatrix}$ is **not equal to** $BA = \begin{bmatrix} 3 & 6 \\ 7 & 10 \end{bmatrix}$. This non-commutativity is a critical property!

---

> [!QUESTION] Quick Activity: Matrix Multiplication
> Given $X = \begin{bmatrix} 1 & 2 & 3 \end{bmatrix}$ (a $1 \times 3$ matrix) and $Y = \begin{bmatrix} 4 \\ 5 \\ 6 \end{bmatrix}$ (a $3 \times 1$ matrix)
>
> 1.  Is $XY$ defined? If yes, what is its order?
> 2.  Calculate $XY$.
> 3.  Is $YX$ defined? If yes, what is its order?
> 4.  Calculate $YX$.
>
> Take your time with this. Matrix multiplication requires careful, step-by-step calculation. Ask if any part of the "row by column" process is unclear! This is the core skill for this chapter.