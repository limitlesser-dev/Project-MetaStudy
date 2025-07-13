# Chapter 3: Matrices - Part 10: Elementary Operations (Transformations) on a Matrix

Elementary operations are fundamental manipulations that can be performed on the rows or columns of a matrix. These operations are used for various purposes, most notably for finding the inverse of a matrix, solving systems of linear equations, and reducing a matrix to a simpler form.

---

## 1. What are Elementary Operations?

There are six elementary operations (or transformations) on a matrix: three related to rows and three related to columns.

> [!INFO] Important Note
> When using elementary operations to find the inverse of a matrix, you **must use either ONLY row operations OR ONLY column operations**. You cannot mix them in the same problem. For NCERT, typically **row operations** are preferred and more commonly used.

---

## 2. Types of Elementary Row Operations

Let $R_i$ denote the $i$-th row and $R_j$ denote the $j$-th row.

### 2.1 Interchange of any two rows
> [!NOTE] Notation: $R_i \leftrightarrow R_j$
> This operation means swapping the entire content of row $i$ with row $j$.
>
> **Example:**
> If $A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$
> Applying $R_1 \leftrightarrow R_2$:
> $A \sim \begin{bmatrix} 4 & 5 & 6 \\ 1 & 2 & 3 \\ 7 & 8 & 9 \end{bmatrix}$ (The symbol '$\sim$' means "is row equivalent to" or "is transformed to")

### 2.2 Multiplication of the elements of any row by a non-zero scalar
> [!NOTE] Notation: $R_i \rightarrow kR_i$ (where $k \ne 0$)
> This operation means multiplying every element in row $i$ by a non-zero constant $k$.
>
> **Example:**
> If $A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$
> Applying $R_2 \rightarrow 2R_2$:
> $A \sim \begin{bmatrix} 1 & 2 & 3 \\ 8 & 10 & 12 \\ 7 & 8 & 9 \end{bmatrix}$

### 2.3 Addition to the elements of any row, the corresponding elements of any other row multiplied by a non-zero scalar
> [!NOTE] Notation: $R_i \rightarrow R_i + kR_j$ (where $k \ne 0$)
> This is the most frequently used and powerful operation. It means adding $k$ times row $j$ to row $i$, and the result replaces row $i$. Row $j$ remains unchanged.
>
> **Example:**
> If $A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$
> Applying $R_2 \rightarrow R_2 - 4R_1$ (here $k = -4$):
> (New Row 2: (4 - 4*1), (5 - 4*2), (6 - 4*3))
> $A \sim \begin{bmatrix} 1 & 2 & 3 \\ 0 & -3 & -6 \\ 7 & 8 & 9 \end{bmatrix}$

---

## 3. Types of Elementary Column Operations

Similarly, let $C_i$ denote the $i$-th column and $C_j$ denote the $j$-th column.

### 3.1 Interchange of any two columns
> [!NOTE] Notation: $C_i \leftrightarrow C_j$

### 3.2 Multiplication of the elements of any column by a non-zero scalar
> [!NOTE] Notation: $C_i \rightarrow kC_i$ (where $k \ne 0$)

### 3.3 Addition to the elements of any column, the corresponding elements of any other column multiplied by a non-zero scalar
> [!NOTE] Notation: $C_i \rightarrow C_i + kC_j$ (where $k \ne 0$)

---

## 4. Inverse of a Matrix by Elementary Operations

> [!DEFINITION] Inverse of a Matrix
> If $A$ is a square matrix of order $n$, and if there exists another square matrix $B$ of the same order $n$, such that $AB = BA = I$ (where $I$ is the identity matrix of order $n$), then $B$ is called the **inverse** of $A$.
> The inverse of $A$ is denoted by $A^{-1}$.
>
> **Important:**
> *   Only **square matrices** can have an inverse.
> *   Not all square matrices have an inverse. If an inverse exists, the matrix is called **invertible** or **non-singular**. If no inverse exists, it's called a **singular matrix**. (You'll learn how to determine this using determinants in the next chapter).
> *   The inverse of a square matrix, if it exists, is **unique**.

### 4.1 Finding Inverse using Elementary Row Operations

The core idea is this:
Start with the matrix equation $A = IA$.
Apply a sequence of elementary row operations to $A$ (on the left side) to transform it into the identity matrix $I$.
Simultaneously, apply the *exact same sequence* of elementary row operations to the identity matrix $I$ (on the right side).
The matrix that $I$ transforms into will be $A^{-1}$.

> [!ALGORITHM] Steps to find $A^{-1}$ using Elementary Row Operations
> 1.  Write the given square matrix as $A = IA$.
> 2.  Apply a sequence of elementary row operations to matrix $A$ (on the left side) until it transforms into the Identity Matrix ($I$).
> 3.  Apply **the exact same sequence of row operations** to the Identity Matrix ($I$) on the right-hand side.
> 4.  Once the left side becomes $I$, the matrix on the right side (that was originally $I$) will be the inverse matrix $A^{-1}$.
>     So, $I = A^{-1}A$.
> 5.  If, during the process, you get a row (or column, if using column operations) of all zeros in the matrix $A$ on the left side, then the inverse of $A$ does not exist.

### 4.2 Example: Finding the Inverse of a 2x2 Matrix

Let's find the inverse of $A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$ using elementary row operations.

**Step 1: Write $A = IA$.**
$\begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} A$

**Goal:** Transform the left matrix $\begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$ into $\begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}$.

**Step 2: Make the element $a_{11}$ equal to 1.** (It's already 1, so no operation needed for this step.)

**Step 3: Make the element $a_{21}$ equal to 0.**
Apply $R_2 \rightarrow R_2 - 3R_1$ to both sides:
Left Side:
$\begin{bmatrix} 1 & 2 \\ 3 - 3(1) & 4 - 3(2) \end{bmatrix} = \begin{bmatrix} 1 & 2 \\ 0 & 4 - 6 \end{bmatrix} = \begin{bmatrix} 1 & 2 \\ 0 & -2 \end{bmatrix}$
Right Side:
$\begin{bmatrix} 1 & 0 \\ 0 - 3(1) & 1 - 3(0) \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ -3 & 1 \end{bmatrix}$
So, the equation becomes:
$\begin{bmatrix} 1 & 2 \\ 0 & -2 \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ -3 & 1 \end{bmatrix} A$

**Step 4: Make the element $a_{22}$ equal to 1.**
Apply $R_2 \rightarrow -\frac{1}{2}R_2$ to both sides:
Left Side:
$\begin{bmatrix} 1 & 2 \\ 0 \cdot (-\frac{1}{2}) & -2 \cdot (-\frac{1}{2}) \end{bmatrix} = \begin{bmatrix} 1 & 2 \\ 0 & 1 \end{bmatrix}$
Right Side:
$\begin{bmatrix} 1 & 0 \\ -3 \cdot (-\frac{1}{2}) & 1 \cdot (-\frac{1}{2}) \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ \frac{3}{2} & -\frac{1}{2} \end{bmatrix}$
So, the equation becomes:
$\begin{bmatrix} 1 & 2 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ \frac{3}{2} & -\frac{1}{2} \end{bmatrix} A$

**Step 5: Make the element $a_{12}$ equal to 0.**
Apply $R_1 \rightarrow R_1 - 2R_2$ to both sides:
Left Side:
$\begin{bmatrix} 1 - 2(0) & 2 - 2(1) \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}$
Right Side:
$\begin{bmatrix} 1 - 2(\frac{3}{2}) & 0 - 2(-\frac{1}{2}) \\ \frac{3}{2} & -\frac{1}{2} \end{bmatrix} = \begin{bmatrix} 1 - 3 & 0 + 1 \\ \frac{3}{2} & -\frac{1}{2} \end{bmatrix} = \begin{bmatrix} -2 & 1 \\ \frac{3}{2} & -\frac{1}{2} \end{bmatrix}$
So, the equation becomes:
$\begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} -2 & 1 \\ \frac{3}{2} & -\frac{1}{2} \end{bmatrix} A$

**Step 6: The left side is now $I$. The right side is $A^{-1}$.**
Therefore, $A^{-1} = \begin{bmatrix} -2 & 1 \\ \frac{3}{2} & -\frac{1}{2} \end{bmatrix}$.

---

> [!TIP] Verification
> You can always verify your inverse by multiplying $A \cdot A^{-1}$. The result should be $I$.
>
> $A \cdot A^{-1} = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} \begin{bmatrix} -2 & 1 \\ \frac{3}{2} & -\frac{1}{2} \end{bmatrix}$
> $= \begin{bmatrix} (1)(-2) + (2)(\frac{3}{2}) & (1)(1) + (2)(-\frac{1}{2}) \\ (3)(-2) + (4)(\frac{3}{2}) & (3)(1) + (4)(-\frac{1}{2}) \end{bmatrix}$
> $= \begin{bmatrix} -2 + 3 & 1 - 1 \\ -6 + 6 & 3 - 2 \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = I$. Correct!

---

> [!WARNING] Common Mistakes for Elementary Operations
> *   **Arithmetic errors:** This is the most common reason for getting wrong answers. Be very careful with signs and fractions.
> *   **Applying operation to only one side:** Remember to apply each operation to *both* the matrix $A$ on the left and the identity matrix $I$ on the right.
> *   **Mixing row and column operations:** Stick to one type throughout the problem.
> *   **Incorrect order of operations:** While there's flexibility, a common strategy is to first make the first column look like the identity column, then the second, and so on. (i.e., make $a_{11}=1$, then $a_{21}=0, a_{31}=0$, then $a_{22}=1$, then $a_{12}=0, a_{32}=0$, etc.).

---

This is pretty much the end of the theoretical concepts for NCERT Chapter 3: Matrices. You've gone through:

*   **Definition & Types**
*   **Equality**
*   **Operations** (Addition, Subtraction, Scalar Mult, Matrix Mult)
*   **Properties of Operations**
*   **Transpose**
*   **Symmetric & Skew-Symmetric Matrices**
*   **Elementary Operations & Finding Inverse**

Congratulations on covering so much material! The rest is practice, practice, practice. You now have the full conceptual toolkit for this chapter.

Do you have any questions about Elementary Operations or finding the inverse before we conclude this chapter?