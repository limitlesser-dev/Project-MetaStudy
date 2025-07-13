# Chapter 3: Matrices - Part 8: Transpose of a Matrix

The transpose of a matrix is a fundamental concept that involves simply "flipping" the matrix over its diagonal. It's a straightforward operation with several useful properties.

---

## 1. Definition of Transpose of a Matrix

> [!INFO] Definition
> The **transpose** of a matrix $A$ is obtained by **interchanging its rows and columns**.
>
> If $A$ is an $m \times n$ matrix, its transpose, denoted by $A'$ or $A^T$, will be an $n \times m$ matrix.
>
> So, if $A = [a_{ij}]$, then its transpose $A^T = [a_{ji}]$. This means the element in the $i$-th row and $j$-th column of $A$ becomes the element in the $j$-th row and $i$-th column of $A^T$.

---

## 2. How to Find the Transpose

It's as simple as writing the first row of the original matrix as the first column of the transpose, the second row as the second column, and so on.

> [!EXAMPLE] Finding the Transpose
> Let $A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{bmatrix}$
>
> **Step 1: Identify the order of A.**
> A has 2 rows and 3 columns, so its order is $2 \times 3$.
>
> **Step 2: Determine the order of the transpose.**
> $A^T$ will have its rows and columns interchanged, so its order will be $3 \times 2$.
>
> **Step 3: Interchange rows and columns.**
> *   Row 1 of A: $\begin{bmatrix} 1 & 2 & 3 \end{bmatrix}$ becomes Column 1 of $A^T$.
> *   Row 2 of A: $\begin{bmatrix} 4 & 5 & 6 \end{bmatrix}$ becomes Column 2 of $A^T$.
>
> Therefore, $A^T = \begin{bmatrix} 1 & 4 \\ 2 & 5 \\ 3 & 6 \end{bmatrix}$.

> [!EXAMPLE] Another Example (Square Matrix)
> Let $B = \begin{bmatrix} 7 & 8 \\ 9 & 0 \end{bmatrix}$
>
> Order of B is $2 \times 2$. Order of $B^T$ will also be $2 \times 2$.
>
> $B^T = \begin{bmatrix} 7 & 9 \\ 8 & 0 \end{bmatrix}$.
> Notice how the diagonal elements ($a_{11}$ and $a_{22}$) remain in their original positions.

---

## 3. Properties of Transpose of Matrices

These properties are very important for solving problems and proofs related to matrices. Let A and B be matrices of suitable orders such that the operations are defined.

### 3.1 Transpose of Transpose
> [!NOTE] $(A^T)^T = A$
> Taking the transpose of a transpose of a matrix gives you back the original matrix.
>
> **Reasoning:** If you swap rows and columns twice, you return to the original arrangement.

### 3.2 Transpose of a Scalar Multiple
> [!NOTE] $(kA)^T = kA^T$, where $k$ is any scalar.
> The transpose of a matrix multiplied by a scalar is equal to the scalar multiplied by the transpose of the matrix.
>
> **Reasoning:** Each element is scaled by $k$ before or after swapping rows/columns, the result is the same.

### 3.3 Transpose of a Sum
> [!NOTE] $(A + B)^T = A^T + B^T$
> The transpose of the sum of two matrices is the sum of their transposes. This also holds true for subtraction: $(A - B)^T = A^T - B^T$.
>
> **Condition:** A and B must be of the same order.

### 3.4 Transpose of a Product (Reversal Law)
> [!WARNING] $(AB)^T = B^T A^T$
> This is a **very important property** and often a source of error if not remembered correctly. The transpose of the product of two matrices is the product of their transposes in **reverse order**.
>
> **Condition:** A and B must be compatible for multiplication (columns of A = rows of B).
>
> **Why the reversal?**
> Think about dimensions:
> If $A$ is $m \times n$ and $B$ is $n \times p$, then $AB$ is $m \times p$.
> So $(AB)^T$ is $p \times m$.
>
> Now consider $B^T A^T$:
> $B^T$ is $p \times n$.
> $A^T$ is $n \times m$.
> The product $B^T A^T$ is $p \times m$. The dimensions match!
>
> If you tried $A^T B^T$:
> $A^T$ is $n \times m$.
> $B^T$ is $p \times n$.
> For $A^T B^T$ to be defined, $m$ must equal $p$, which is not always true. Hence, the reversal.

---

> [!SUMMARY] Key Concepts of Transpose
> *   Swap rows and columns.
> *   $A_{m \times n} \rightarrow A^T_{n \times m}$.
> *   **Properties to Remember:** $(A^T)^T = A$, $(kA)^T = kA^T$, $(A+B)^T = A^T+B^T$, and most crucially, **$(AB)^T = B^T A^T$**.

---

