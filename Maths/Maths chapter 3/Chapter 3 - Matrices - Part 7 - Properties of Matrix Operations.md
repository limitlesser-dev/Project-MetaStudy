# Chapter 3: Matrices - Part 7: Properties of Matrix Operations

We've learned how to add, subtract, multiply by a scalar, and multiply matrices. Now, let's explore the rules or "properties" that these operations follow. Some are similar to real numbers, others are uniquely matrix-specific.

---

## 1. Properties of Matrix Addition

These properties hold true for any three matrices A, B, and C, provided they are of the same order (so that addition is defined).

### 1.1 Commutative Law
> [!NOTE] A + B = B + A
> Matrix addition is **commutative**. The order in which you add two matrices does not affect the result.
>
> **Example:**
> If $A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$ and $B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}$
> $A+B = \begin{bmatrix} 1+5 & 2+6 \\ 3+7 & 4+8 \end{bmatrix} = \begin{bmatrix} 6 & 8 \\ 10 & 12 \end{bmatrix}$
> $B+A = \begin{bmatrix} 5+1 & 6+2 \\ 7+3 & 8+4 \end{bmatrix} = \begin{bmatrix} 6 & 8 \\ 10 & 12 \end{bmatrix}$
> Clearly, $A+B = B+A$.

### 1.2 Associative Law
> [!NOTE] (A + B) + C = A + (B + C)
> Matrix addition is **associative**. When adding three or more matrices, the way you group them does not affect the result.
>
> You can verify this with an example.

### 1.3 Existence of Additive Identity
> [!INFO] A + O = O + A = A
> For any matrix A, there exists a **zero matrix (null matrix) O** of the same order such that when O is added to A, the result is A itself.
> The zero matrix acts like '0' in real number addition.
>
> **Example:**
> If $A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$ and $O = \begin{bmatrix} 0 & 0 \\ 0 & 0 \end{bmatrix}$
> $A+O = \begin{bmatrix} 1+0 & 2+0 \\ 3+0 & 4+0 \end{bmatrix} = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} = A$

### 1.4 Existence of Additive Inverse
> [!INFO] A + (-A) = O
> For every matrix A, there exists a matrix **-A** (which is obtained by multiplying A by the scalar -1) such that when -A is added to A, the result is the zero matrix O.
> -A is called the **additive inverse** of A.
>
> **Example:**
> If $A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$ then $-A = \begin{bmatrix} -1 & -2 \\ -3 & -4 \end{bmatrix}$
> $A+(-A) = \begin{bmatrix} 1+(-1) & 2+(-2) \\ 3+(-3) & 4+(-4) \end{bmatrix} = \begin{bmatrix} 0 & 0 \\ 0 & 0 \end{bmatrix} = O$

---

## 2. Properties of Scalar Multiplication

These properties involve multiplying matrices by scalar values ($k$ and $l$). Let A and B be matrices of the same order.

### 2.1 Distribution over Matrix Addition
> [!NOTE] $k(A + B) = kA + kB$
> Scalar multiplication is distributive over matrix addition.
>
> **Example:**
> If $A = \begin{bmatrix} 1 & 0 \\ 2 & 3 \end{bmatrix}$, $B = \begin{bmatrix} 4 & 1 \\ 0 & 5 \end{bmatrix}$, and $k=2$.
> $A+B = \begin{bmatrix} 5 & 1 \\ 2 & 8 \end{bmatrix}$
> $k(A+B) = 2 \begin{bmatrix} 5 & 1 \\ 2 & 8 \end{bmatrix} = \begin{bmatrix} 10 & 2 \\ 4 & 16 \end{bmatrix}$
>
> $kA = 2 \begin{bmatrix} 1 & 0 \\ 2 & 3 \end{bmatrix} = \begin{bmatrix} 2 & 0 \\ 4 & 6 \end{bmatrix}$
> $kB = 2 \begin{bmatrix} 4 & 1 \\ 0 & 5 \end{bmatrix} = \begin{bmatrix} 8 & 2 \\ 0 & 10 \end{bmatrix}$
> $kA+kB = \begin{bmatrix} 2+8 & 0+2 \\ 4+0 & 6+10 \end{bmatrix} = \begin{bmatrix} 10 & 2 \\ 4 & 16 \end{bmatrix}$
> Both sides match!

### 2.2 Distribution over Scalar Addition
> [!NOTE] $(k + l)A = kA + lA$
> A matrix distributes over the sum of two scalars.
>
> You can verify this.

### 2.3 Associativity of Scalar Multiplication
> [!NOTE] $k(lA) = (kl)A$
> When multiplying a matrix by multiple scalars, the order of scalar multiplication does not matter.
>
> You can verify this.

### 2.4 Multiplicative Identity for Scalar Multiplication
> [!INFO] $1 \cdot A = A$
> Multiplying a matrix by the scalar '1' leaves the matrix unchanged.

### 2.5 Scalar Multiplication by -1
> [!INFO] $(-1) \cdot A = -A$
> Multiplying a matrix by the scalar '-1' gives its additive inverse.

---

## 3. Properties of Matrix Multiplication

These properties apply to matrices A, B, and C, assuming their dimensions are compatible for the respective operations.

### 3.1 Associative Law
> [!SUCCESS] $(AB)C = A(BC)$
> Matrix multiplication is **associative**. This is extremely important! If you're multiplying three or more matrices, the grouping does not change the final product.
> This is why we can write $ABC$ without ambiguity.
>
> This property is often used in complex matrix computations.

### 3.2 Distributive Law
> [!SUCCESS] $A(B + C) = AB + AC$ (Left Distributive Law)
> [!SUCCESS] $(A + B)C = AC + BC$ (Right Distributive Law)
> Matrix multiplication distributes over matrix addition.
> **Important:** The order of multiplication matters here because of non-commutativity. $A(B+C)$ is not necessarily equal to $(B+C)A$.

### 3.3 Existence of Multiplicative Identity
> [!INFO] $AI = IA = A$
> For every square matrix A, there exists an **identity matrix I** (of the same order as A) such that when A is multiplied by I (from left or right), the result is A itself.
> The identity matrix acts like '1' in real number multiplication.
>
> **Example:**
> If $A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$ and $I = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}$
> $AI = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} (1 \cdot 1)+(2 \cdot 0) & (1 \cdot 0)+(2 \cdot 1) \\ (3 \cdot 1)+(4 \cdot 0) & (3 \cdot 0)+(4 \cdot 1) \end{bmatrix} = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} = A$
> You can also verify that $IA = A$.

### 3.4 Multiplicative Property of Zero Matrix
> [!NOTE] $AO = OA = O$
> The product of any matrix with a zero matrix (of compatible dimensions) is always a zero matrix.

### 3.5 Non-Commutativity (Re-emphasized)
> [!WARNING] $AB \ne BA$ in general.
> We've already discussed this. This is the most significant difference from real number multiplication. Always remember that the order of matrix multiplication matters!

### 3.6 Cancellation Law Does Not Generally Hold
> [!WARNING] If $AB = AC$, it does **not** necessarily imply $B = C$.
> If $A \ne O$, this would be true for real numbers. However, for matrices, it's possible for $AB = AC$ even if $B \ne C$ and $A \ne O$.
>
> **Example:**
> Let $A = \begin{bmatrix} 1 & 0 \\ 0 & 0 \end{bmatrix}$, $B = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$, $C = \begin{bmatrix} 1 & 2 \\ 5 & 6 \end{bmatrix}$
> $AB = \begin{bmatrix} 1 & 2 \\ 0 & 0 \end{bmatrix}$
> $AC = \begin{bmatrix} 1 & 2 \\ 0 & 0 \end{bmatrix}$
> Here, $AB = AC$, but clearly $B \ne C$. This is a major point of difference and a common pitfall.

### 3.7 If $AB = O$, it does not necessarily imply $A = O$ or $B = O$.
> [!WARNING] Products can be zero without any factor being zero.
> This is also unlike real numbers where if $xy=0$, then either $x=0$ or $y=0$. For matrices, it's possible for the product of two non-zero matrices to be a zero matrix.
>
> **Example:**
> Let $A = \begin{bmatrix} 1 & 1 \\ 2 & 2 \end{bmatrix}$, $B = \begin{bmatrix} -1 & 1 \\ 1 & -1 \end{bmatrix}$
> $AB = \begin{bmatrix} (1)(-1)+(1)(1) & (1)(1)+(1)(-1) \\ (2)(-1)+(2)(1) & (2)(1)+(2)(-1) \end{bmatrix} = \begin{bmatrix} -1+1 & 1-1 \\ -2+2 & 2-2 \end{bmatrix} = \begin{bmatrix} 0 & 0 \\ 0 & 0 \end{bmatrix} = O$
> Here, $A \ne O$ and $B \ne O$, but $AB = O$.

---

> [!SUMMARY] Key Takeaways from Properties
> *   **Addition:** Commutative and Associative, has Identity (Zero Matrix) and Inverse (-A).
> *   **Scalar Multiplication:** Distributes over matrix and scalar addition, Associative.
> *   **Matrix Multiplication:** **Associative** and **Distributive** (both left and right), has Identity (Identity Matrix).
> *   **Crucial Differences:** Matrix multiplication is **NOT commutative**, and the **cancellation law does NOT generally hold**. Also, a product can be zero without any factor being zero.

---

We've covered the definitions, types, equality, and all the main operations along with their properties. This is a huge chunk of the chapter!

Next, we'll move onto the [[Transpose of a Matrix]] and then explore [[Symmetric and Skew-Symmetric Matrices]]. These concepts build directly on our current understanding.

Are you ready to dive into the Transpose?