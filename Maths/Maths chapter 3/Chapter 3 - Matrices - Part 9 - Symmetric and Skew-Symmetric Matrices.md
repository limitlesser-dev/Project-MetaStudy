# Chapter 3: Matrices - Part 9: Symmetric and Skew-Symmetric Matrices

Building on our understanding of the [[Transpose of a Matrix]], we can now define two important classes of matrices: Symmetric and Skew-Symmetric matrices. These types have unique properties and significant applications, especially in areas like physics and engineering.

---

## 1. Symmetric Matrix

> [!DEFINITION] Symmetric Matrix
> A **square matrix** $A$ is said to be a **symmetric matrix** if it is equal to its transpose.
> That is, $A = A^T$.
>
> If $A = [a_{ij}]$, then for a symmetric matrix, $a_{ij} = a_{ji}$ for all possible values of $i$ and $j$. This means the element in row $i$, column $j$ is the same as the element in row $j$, column $i$.

### 1.1 How to Identify a Symmetric Matrix

Visually, if you reflect the matrix across its main diagonal (the elements $a_{11}, a_{22}, a_{33}, \dots$), the elements should remain unchanged.

> [!EXAMPLE] Identifying a Symmetric Matrix
> Let $A = \begin{bmatrix} 2 & 3 & 5 \\ 3 & 7 & 1 \\ 5 & 1 & 9 \end{bmatrix}$
>
> **Step 1: Check if it's a square matrix.**
> Yes, it's a $3 \times 3$ matrix.
>
> **Step 2: Find its transpose, $A^T$.**
> $A^T = \begin{bmatrix} 2 & 3 & 5 \\ 3 & 7 & 1 \\ 5 & 1 & 9 \end{bmatrix}$ (by interchanging rows and columns)
>
> **Step 3: Compare A and $A^T$.**
> Since $A = A^T$, the matrix A is a **Symmetric Matrix**.
>
> Notice $a_{12}=3$ and $a_{21}=3$. Also $a_{13}=5$ and $a_{31}=5$, and $a_{23}=1$ and $a_{32}=1$. The elements symmetric about the main diagonal are equal.

---
## 2. Skew-Symmetric Matrix

> [!DEFINITION] Skew-Symmetric Matrix
> A **square matrix** $A$ is said to be a **skew-symmetric matrix** if it is equal to the negative of its transpose.
> That is, $A = -A^T$.
>
> If $A = [a_{ij}]$, then for a skew-symmetric matrix, $a_{ij} = -a_{ji}$ for all possible values of $i$ and $j$.

### 2.1 Special Property of Diagonal Elements in Skew-Symmetric Matrices

If $a_{ij} = -a_{ji}$, consider the diagonal elements where $i=j$.
So, $a_{ii} = -a_{ii}$.
This implies $2a_{ii} = 0$, which means $a_{ii} = 0$.
> [!IMPORTANT] All diagonal elements of a skew-symmetric matrix **must be zero**.

### 2.2 How to Identify a Skew-Symmetric Matrix

Visually, reflecting across the main diagonal results in the negative of the original elements, and all diagonal elements are zero.

> [!EXAMPLE] Identifying a Skew-Symmetric Matrix
> Let $B = \begin{bmatrix} 0 & 3 & -5 \\ -3 & 0 & 1 \\ 5 & -1 & 0 \end{bmatrix}$
>
> **Step 1: Check if it's a square matrix.**
> Yes, it's a $3 \times 3$ matrix.
>
> **Step 2: Check diagonal elements.**
> All diagonal elements are 0. (A good first check, but not sufficient by itself).
>
> **Step 3: Find its transpose, $B^T$.**
> $B^T = \begin{bmatrix} 0 & -3 & 5 \\ 3 & 0 & -1 \\ -5 & 1 & 0 \end{bmatrix}$ (by interchanging rows and columns)
>
> **Step 4: Find $-B^T$.**
> $-B^T = -1 \times \begin{bmatrix} 0 & -3 & 5 \\ 3 & 0 & -1 \\ -5 & 1 & 0 \end{bmatrix} = \begin{bmatrix} 0 & 3 & -5 \\ -3 & 0 & 1 \\ 5 & -1 & 0 \end{bmatrix}$
>
> **Step 5: Compare B and $-B^T$.**
> Since $B = -B^T$, the matrix B is a **Skew-Symmetric Matrix**.
>
> Notice $b_{12}=3$ and $b_{21}=-3$ ($b_{12} = -b_{21}$).
> Also $b_{13}=-5$ and $b_{31}=5$ ($b_{13} = -b_{31}$).
> And $b_{23}=1$ and $b_{32}=-1$ ($b_{23} = -b_{32}$).

---

## 3. Theorem: Sum of Symmetric and Skew-Symmetric Matrices

> [!THEORY] Any square matrix can be expressed as the sum of a symmetric and a skew-symmetric matrix.
> This is a crucial theorem and a common type of problem in NCERT.
>
> Let $A$ be any square matrix. We want to express $A$ as $P + Q$, where $P$ is symmetric and $Q$ is skew-symmetric.
>
> Consider the following constructions:
> *   $P = \frac{1}{2}(A + A^T)$
> *   $Q = \frac{1}{2}(A - A^T)$
>
> Let's prove their properties:
>
> **Proof that P is Symmetric:**
> We need to show $P^T = P$.
> $P^T = \left(\frac{1}{2}(A + A^T)\right)^T$
> $P^T = \frac{1}{2}(A + A^T)^T$ (Property: $(kA)^T = kA^T$)
> $P^T = \frac{1}{2}(A^T + (A^T)^T)$ (Property: $(A+B)^T = A^T+B^T$)
> $P^T = \frac{1}{2}(A^T + A)$ (Property: $(A^T)^T = A$)
> $P^T = \frac{1}{2}(A + A^T)$ (Matrix addition is commutative: $A^T+A = A+A^T$)
> $P^T = P$
> Hence, $P$ is a symmetric matrix.

> [!PROOF] Proof that Q is Skew-Symmetric:
> We need to show $Q^T = -Q$.
> $Q^T = \left(\frac{1}{2}(A - A^T)\right)^T$
> $Q^T = \frac{1}{2}(A - A^T)^T$
> $Q^T = \frac{1}{2}(A^T - (A^T)^T)$
> $Q^T = \frac{1}{2}(A^T - A)$
> $Q^T = -\frac{1}{2}(A - A^T)$ (Factor out -1)
> $Q^T = -Q$
> Hence, $Q$ is a skew-symmetric matrix.

> [!CHECK] Check that $A = P+Q$:
> $P + Q = \frac{1}{2}(A + A^T) + \frac{1}{2}(A - A^T)$
> $P + Q = \frac{1}{2}A + \frac{1}{2}A^T + \frac{1}{2}A - \frac{1}{2}A^T$
> $P + Q = \frac{1}{2}A + \frac{1}{2}A$
> $P + Q = A$
>
> This theorem provides a powerful method to decompose any square matrix into its symmetric and skew-symmetric components.

---

> [!EXAMPLE] Expressing a Matrix as Sum of Symmetric and Skew-Symmetric
> Express the matrix $A = \begin{bmatrix} 3 & 5 \\ 1 & -1 \end{bmatrix}$ as the sum of a symmetric and a skew-symmetric matrix.
>
> **Step 1: Find $A^T$.**
> $A^T = \begin{bmatrix} 3 & 1 \\ 5 & -1 \end{bmatrix}$
>
> **Step 2: Calculate $P = \frac{1}{2}(A + A^T)$.**
> $A + A^T = \begin{bmatrix} 3 & 5 \\ 1 & -1 \end{bmatrix} + \begin{bmatrix} 3 & 1 \\ 5 & -1 \end{bmatrix} = \begin{bmatrix} 3+3 & 5+1 \\ 1+5 & -1+(-1) \end{bmatrix} = \begin{bmatrix} 6 & 6 \\ 6 & -2 \end{bmatrix}$
> $P = \frac{1}{2} \begin{bmatrix} 6 & 6 \\ 6 & -2 \end{bmatrix} = \begin{bmatrix} 3 & 3 \\ 3 & -1 \end{bmatrix}$
> (Check: $P^T = \begin{bmatrix} 3 & 3 \\ 3 & -1 \end{bmatrix} = P$, so $P$ is symmetric. Correct!)
>
> **Step 3: Calculate $Q = \frac{1}{2}(A - A^T)$.**
> $A - A^T = \begin{bmatrix} 3 & 5 \\ 1 & -1 \end{bmatrix} - \begin{bmatrix} 3 & 1 \\ 5 & -1 \end{bmatrix} = \begin{bmatrix} 3-3 & 5-1 \\ 1-5 & -1-(-1) \end{bmatrix} = \begin{bmatrix} 0 & 4 \\ -4 & 0 \end{bmatrix}$
> $Q = \frac{1}{2} \begin{bmatrix} 0 & 4 \\ -4 & 0 \end{bmatrix} = \begin{bmatrix} 0 & 2 \\ -2 & 0 \end{bmatrix}$
> (Check: $Q^T = \begin{bmatrix} 0 & -2 \\ 2 & 0 \end{bmatrix}$. Also, $-Q = \begin{bmatrix} 0 & -2 \\ 2 & 0 \end{bmatrix}$. Since $Q^T = -Q$, $Q$ is skew-symmetric. Correct!)
>
> **Step 4: Verify $A = P + Q$.**
> $P + Q = \begin{bmatrix} 3 & 3 \\ 3 & -1 \end{bmatrix} + \begin{bmatrix} 0 & 2 \\ -2 & 0 \end{bmatrix} = \begin{bmatrix} 3+0 & 3+2 \\ 3+(-2) & -1+0 \end{bmatrix} = \begin{bmatrix} 3 & 5 \\ 1 & -1 \end{bmatrix}$
> This is equal to the original matrix $A$. The decomposition is successful!

---

> [!SUMMARY] Symmetric and Skew-Symmetric Matrices
> *   **Symmetric:** $A = A^T$ (elements $a_{ij} = a_{ji}$)
> *   **Skew-Symmetric:** $A = -A^T$ (elements $a_{ij} = -a_{ji}$, and all diagonal elements are 0)
> *   **Decomposition:** Any square matrix $A$ can be written as $A = P + Q$, where $P = \frac{1}{2}(A + A^T)$ (symmetric) and $Q = \frac{1}{2}(A - A^T)$ (skew-symmetric).

---

We are just one major topic away from the end of the core NCERT Chapter 3: **Elementary Operations** (or transformations) and finding the **Inverse of a Matrix by Elementary Operations**. Sometimes, the inverse is also taught using the Adjoint method which is usually covered in Chapter 4 (Determinants). For now, let's stick to Elementary Operations if you're aiming to complete Chapter 3.

Are you ready for Elementary Operations? This involves a bit of systematic thinking!