# Chapter 3: Matrices - Flashcards

---

## 1. Definition, Order & Types of Matrices

What is a matrix?::A rectangular array (arrangement) of numbers or functions, called elements or entries.

How is the order of a matrix denoted, and what does it represent?::`m x n` (read as "m by n"), where 'm' is the number of rows and 'n' is the number of columns.

What is a square matrix?::A matrix where the number of rows (m) is equal to the number of columns (n), i.e., it's an `m x m` matrix.

What defines an Identity Matrix ($I$)?::A **square matrix** where all elements on the **main diagonal are 1** and all other (non-diagonal) elements are 0.
Example: $\begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}$

What defines a Zero Matrix ($O$)?::A matrix where **all its elements are zero**. Its order can be any `m x n`.

What is a Column Matrix?::A matrix that has only **one column**. (Order `m x 1`)

What is a Row Matrix?::A matrix that has only **one row**. (Order `1 x n`)

What is a Diagonal Matrix?::A **square matrix** in which all the **non-diagonal elements are zero**. (Diagonal elements can be non-zero).

What is a Scalar Matrix?::A **diagonal matrix** in which all the **diagonal elements are equal**. (It's a special type of diagonal matrix).

---

## 2. Equality of Matrices

What are the two conditions for two matrices A and B to be equal?::1. They must have the **same order**. 2. Their **corresponding elements** must be equal ($a_{ij} = b_{ij}$ for all i, j).

---

## 3. Matrix Addition & Subtraction

What is the condition for adding or subtracting two matrices?::They must have the **same order**.

How do you perform matrix addition ($A+B$) or subtraction ($A-B$)?::Add or subtract their **corresponding elements**.

---

## 4. Scalar Multiplication

How do you perform scalar multiplication of a matrix $A$ by a scalar $k$ ($kA$)?::Multiply **every single element** of the matrix $A$ by the scalar $k$.

---

## 5. Matrix Multiplication

What is the fundamental condition for multiplying matrix $A$ (order $m \times n$) by matrix $B$ (order $p \times q$) to get the product $AB$?::The number of **columns in the first matrix ($A$) must equal the number of rows in the second matrix ($B$)**. So, $n = p$.

What will be the order of the product matrix $AB$ if $A$ is $m \times n$ and $B$ is $n \times q$?::The order will be **$m \times q$** (rows of A by columns of B).

How do you find the element $c_{ij}$ (in the $i$-th row and $j$-th column) of the product matrix $C = AB$?::It is found by taking the **dot product** (sum of products of corresponding elements) of the **$i$-th row of matrix $A$** and the **$j$-th column of matrix $B$**.

True or False: Matrix multiplication is commutative ($AB = BA$).::False. In general, $AB \ne BA$.

---

## 6. Properties of Matrix Operations

Matrix addition is {{c1::commutative}} ($A+B = B+A$).

Matrix addition is {{c1::associative}} ($(A+B)+C = A+(B+C)$).

The Zero Matrix ($O$) is the additive {{c1::identity}} for matrices ($A+O = A$).

The matrix $-A$ is the additive {{c1::inverse}} of $A$ ($A+(-A) = O$).

Scalar multiplication distributes over matrix addition: $k(A+B) = $ {{c1::$kA + kB$}}.

Matrix multiplication is {{c1::associative}}, meaning $(AB)C = A(BC)$.

Matrix multiplication distributes over matrix addition: $A(B+C) = $ {{c1::$AB + AC$}} (Left Distributive Law) and $(A+B)C = $ {{c1::$AC + BC$}} (Right Distributive Law).

The Identity Matrix ($I$) is the multiplicative {{c1::identity}} for square matrices ($AI = IA = A$).

If $AB = O$ (zero matrix), does this always mean $A=O$ or $B=O$?::No. It's possible for two non-zero matrices to multiply to a zero matrix.

If $AB = AC$ and $A \ne O$, does this always imply $B=C$?::No. The **cancellation law does not generally hold** for matrix multiplication.

---

## 7. Transpose of a Matrix

How do you find the transpose of a matrix $A$? What are its common notations?::By **interchanging its rows and columns**. Notations: $A'$ or $A^T$.

If $A$ is an $m \times n$ matrix, what is the order of its transpose $A^T$?::$n \times m$.

What is the property for the transpose of a transpose?::$(A^T)^T = A$.

What is the property for the transpose of a scalar multiple?::$(kA)^T = kA^T$.

What is the property for the transpose of a sum?::$(A+B)^T = A^T + B^T$.

State the Reversal Law for the transpose of a product.::$(AB)^T = B^T A^T$.

---

## 8. Symmetric & Skew-Symmetric Matrices

What is a **Symmetric Matrix**?::A **square matrix** $A$ such that $A = A^T$. (This means $a_{ij} = a_{ji}$).

What is a **Skew-Symmetric Matrix**?::A **square matrix** $A$ such that $A = -A^T$. (This means $a_{ij} = -a_{ji}$).

What is a key property of the diagonal elements of a skew-symmetric matrix?::All diagonal elements **must be zero**.

How can any square matrix $A$ be uniquely expressed as the sum of a symmetric and a skew-symmetric matrix?::As $A = P + Q$, where $P = \frac{1}{2}(A + A^T)$ (the symmetric part) and $Q = \frac{1}{2}(A - A^T)$ (the skew-symmetric part).

---

## 9. Elementary Operations & Inverse of a Matrix

List the three types of **Elementary Row Operations** (with notation examples).::
1.  **Interchange of any two rows**: $R_i \leftrightarrow R_j$
2.  **Multiplication of the elements of any row by a non-zero scalar**: $R_i \rightarrow kR_i$ (where $k \ne 0$)
3.  **Addition to the elements of any row, the corresponding elements of any other row multiplied by a non-zero scalar**: $R_i \rightarrow R_i + kR_j$ (where $k \ne 0$)

What is the definition of the **inverse of a matrix** $A$?::If $A$ is a **square matrix**, its inverse is a square matrix $B$ (denoted $A^{-1}$) of the same order, such that $AB = BA = I$ (where $I$ is the identity matrix).

True or False: Every square matrix has an inverse.::False. Only **non-singular** square matrices have inverses.

What is the general algorithmic approach to finding the inverse of a matrix $A$ using elementary row operations?::
1.  Start with the augmented matrix $[A | I]$.
2.  Apply a sequence of elementary row operations to transform the left side ($A$) into the Identity Matrix ($I$).
3.  Apply the *exact same sequence* of operations to the right side ($I$).
4.  Once the left side becomes $I$, the right side will be $A^{-1}$. So, $[I | A^{-1}]$.

---