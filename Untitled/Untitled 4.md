# Chapter 3: Matrices - Revision Sheet

> [!TIP] How to Use This Sheet
> This sheet is a quick reference guide. It summarizes the core concepts of Matrices. For deeper understanding or specific examples, refer back to your detailed notes or NCERT textbook. Practice is crucial for mastery!

---

## 1. Matrix Basics: Definition, Order & Elements

*   **Definition:** A matrix is a rectangular array of numbers or functions (called **elements** or **entries**).
*   **Notation:** Denoted by capital letters (e.g., A, B) and elements by $a_{ij}$ (element in $i$-th row, $j$-th column).
*   **Order:** `m × n` (read "m by n"), where `m` is the number of rows and `n` is the number of columns.
    *   Total elements = $m \times n$.

### Types of Matrices
*   **Column Matrix:** Only one column ($m \times 1$).
*   **Row Matrix:** Only one row ($1 \times n$).
*   **Square Matrix:** Number of rows = number of columns ($m \times m$).
    *   **Main Diagonal:** Elements $a_{ii}$ (where row index = column index).
*   **Diagonal Matrix:** A square matrix where all **non-diagonal elements are zero**.
*   **Scalar Matrix:** A **diagonal matrix** where all **diagonal elements are equal**.
*   **Identity Matrix ($I_n$):** A **scalar matrix** where all **diagonal elements are 1**. (Acts like '1' in multiplication).
*   **Zero Matrix ($O$ or $0$):** All elements are zero. (Acts like '0' in addition).

---

## 2. Equality of Matrices

> [!NOTE] Two matrices A and B are equal if and only if:
> 1.  They have the **same order**.
> 2.  Their **corresponding elements are equal** ($a_{ij} = b_{ij}$ for all $i, j$).
*   Used to set up equations to find unknown values.

---

## 3. Operations on Matrices

### 3.1 Addition & Subtraction
*   **Condition:** Matrices must have the **same order**.
*   **Rule:** Add or subtract **corresponding elements**.
    *   If $A = [a_{ij}]$ and $B = [b_{ij}]$, then $A \pm B = [a_{ij} \pm b_{ij}]$.

### 3.2 Scalar Multiplication
*   **Condition:** None. Can multiply any matrix by any scalar.
*   **Rule:** Multiply **every element** of the matrix by the scalar.
    *   If $A = [a_{ij}]$ and $k$ is a scalar, then $kA = [ka_{ij}]$.

### 3.3 Matrix Multiplication ($AB$)
*   **Condition:** Number of **columns in the first matrix ($A$) must equal the number of rows in the second matrix ($B$)**.
    *   If $A_{m \times n}$ and $B_{p \times q}$, then $n=p$ for $AB$ to be defined.
*   **Order of Result:** If $A_{m \times n}$ and $B_{n \times q}$, then $AB$ will be an **$m \times q$** matrix.
*   **Rule (Row by Column):** The element $c_{ij}$ of $AB$ is the sum of the products of the corresponding elements of the $i$-th row of $A$ and the $j$-th column of $B$.
    *   $c_{ij} = (i \text{th row of } A) \cdot (j \text{th col of } B)$

---

## 4. Properties of Matrix Operations

### 4.1 Matrix Addition Properties
*   **Commutative:** $A+B = B+A$
*   **Associative:** $(A+B)+C = A+(B+C)$
*   **Additive Identity:** $A+O = O+A = A$ (where $O$ is the zero matrix of same order)
*   **Additive Inverse:** $A+(-A) = O$ (where $-A$ is obtained by multiplying $A$ by $-1$)

### 4.2 Scalar Multiplication Properties
*   **Distributive over Matrix Addition:** $k(A+B) = kA + kB$
*   **Distributive over Scalar Addition:** $(k+l)A = kA + lA$
*   **Associative:** $k(lA) = (kl)A$
*   **Identity:** $1 \cdot A = A$

### 4.3 Matrix Multiplication Properties
*   **Associative:** $(AB)C = A(BC)$ (Very Important!)
*   **Distributive (Left):** $A(B+C) = AB + AC$
*   **Distributive (Right):** $(A+B)C = AC + BC$
*   **Multiplicative Identity:** $AI = IA = A$ (where $I$ is the identity matrix of suitable order)
*   **Property of Zero Matrix:** $AO = OA = O$

> [!WARNING] Crucial Differences from Real Number Arithmetic:
> *   **Non-Commutative:** $AB \ne BA$ in general. (Order matters!)
> *   **Cancellation Law Not Always Valid:** If $AB = AC$, it does NOT necessarily imply $B=C$ (unless $A$ is invertible).
> *   **Zero Product:** If $AB = O$, it does NOT necessarily imply $A=O$ or $B=O$.

---

## 5. Transpose of a Matrix ($A^T$ or $A'$)

*   **Definition:** Obtained by **interchanging rows and columns**.
*   **Order Change:** If $A$ is $m \times n$, then $A^T$ is $n \times m$.
*   **Elements:** If $A = [a_{ij}]$, then $A^T = [a_{ji}]$.

### Properties of Transpose
*   $(A^T)^T = A$
*   $(kA)^T = kA^T$
*   $(A \pm B)^T = A^T \pm B^T$
*   **Reversal Law for Product:** $(AB)^T = B^T A^T$ (Extremely Important!)

---

## 6. Symmetric and Skew-Symmetric Matrices

> [!NOTE] These are special types of **square matrices**.

### 6.1 Symmetric Matrix
*   **Definition:** A square matrix $A$ is symmetric if **$A = A^T$**.
*   **Elements:** $a_{ij} = a_{ji}$ for all $i, j$. (Elements symmetric about the main diagonal are equal).

### 6.2 Skew-Symmetric Matrix
*   **Definition:** A square matrix $A$ is skew-symmetric if **$A = -A^T$**.
*   **Elements:** $a_{ij} = -a_{ji}$ for all $i, j$.
*   **Key Property:** All **diagonal elements are zero** ($a_{ii} = 0$).

### 6.3 Decomposition Theorem
*   **Theorem:** Any square matrix $A$ can be uniquely expressed as the sum of a **symmetric matrix** ($P$) and a **skew-symmetric matrix** ($Q$).
*   **Formulas:**
    *   $P = \frac{1}{2}(A + A^T)$ (always symmetric)
    *   $Q = \frac{1}{2}(A - A^T)$ (always skew-symmetric)
    *   And $A = P + Q$.

---

## 7. Elementary Operations & Inverse of a Matrix

### 7.1 Elementary Operations (Transformations)
*   Basic manipulations on rows or columns.
*   **Rule:** In inverse finding, use **ONLY row operations OR ONLY column operations** throughout.
*   **Row Operations:**
    1.  **$R_i \leftrightarrow R_j$** (Interchange two rows)
    2.  **$R_i \rightarrow kR_i$** ($k \ne 0$) (Multiply a row by a non-zero scalar)
    3.  **$R_i \rightarrow R_i + kR_j$** ($k \ne 0$) (Add a scalar multiple of one row to another)
*   (Analogous operations exist for columns: $C_i \leftrightarrow C_j$, $C_i \rightarrow kC_i$, $C_i \rightarrow C_i + kC_j$)

### 7.2 Inverse of a Matrix ($A^{-1}$)
*   **Definition:** For a **square matrix** $A$, if there exists a square matrix $B$ of the same order such that $AB = BA = I$, then $B$ is the inverse of $A$ ($B=A^{-1}$).
*   **Existence:** Only **non-singular** (determinant $\ne 0$) square matrices have an inverse.
*   **Uniqueness:** If an inverse exists, it is unique.

### 7.3 Finding Inverse using Elementary Row Operations
*   **Algorithm:**
    1.  Write the matrix equation: $A = IA$.
    2.  Apply a sequence of Elementary Row Operations to the left matrix $A$ to transform it into the Identity Matrix ($I$).
    3.  Apply the *exact same sequence* of Elementary Row Operations simultaneously to the right Identity Matrix ($I$).
    4.  When the left side becomes $I$, the right side will be $A^{-1}$. (i.e., $[A|I] \rightarrow [I|A^{-1}]$).
    5.  **Important:** If, during the process, you obtain a row (or column, if using column operations) of all zeros on the left side, then the inverse of $A$ does not exist.

---