 Excellent! Let's build on that real-world example of organizing data in rows and columns and formally define what a matrix is.

---

### **Chapter 3: Matrices - Part 2: Definition and Types of Matrices**

**1. What is a Matrix? - The Formal Definition**

Alright class, think of a matrix as a rectangular arrangement of numbers or functions. These numbers or functions are called the **elements** or **entries** of the matrix.

*   A matrix is usually denoted by capital letters like A, B, C, X, Y, etc.
*   The elements are enclosed within square brackets `[ ]` or sometimes parentheses `( )`.

**Definition:** A **matrix** is an ordered rectangular array of numbers or functions.

**Example:**
Let's take our shop sales data and represent it as a matrix:

`A = [ 100  120 ]`
`    [  80   90 ]`

Here, 100, 120, 80, and 90 are the elements of matrix A.

**Rows and Columns:**

*   **Rows** are the horizontal lines of elements. In our example, `[100 120]` is the first row, and `[80 90]` is the second row.
*   **Columns** are the vertical lines of elements. `[100]` and `[120]` form the first column and second column respectively.
    `[80]` `[90]`

**Order of a Matrix:**

The **order** of a matrix tells us its size. It's always expressed as **number of rows × number of columns**.

*   If a matrix has 'm' rows and 'n' columns, its order is **m × n** (read as "m by n").

In our example matrix A:
`A = [ 100  120 ]`
`    [  80   90 ]`

*   It has 2 rows.
*   It has 2 columns.

So, the order of matrix A is **2 × 2**.

**Can anyone tell me, if a matrix has 3 rows and 4 columns, what would its order be?** (Think about it!)

---

**2. Notation of Elements in a Matrix**

To refer to a specific element within a matrix, we use subscripts.
An element in the `i`-th row and `j`-th column of a matrix A is denoted by `a_ij`.

So, the general form of an `m × n` matrix A can be written as:

`A = [ a_11  a_12  ...  a_1n ]`
`    [ a_21  a_22  ...  a_2n ]`
`    [  .     .         .   ]`
`    [  .     .         .   ]`
`    [ a_m1  a_m2  ...  a_mn ]`

Or, more compactly, `A = [a_ij]_(m × n)`.

Let's look at our example again:
`A = [ 100  120 ]`
`    [  80   90 ]`

*   `a_11` (element in 1st row, 1st column) = 100
*   `a_12` (element in 1st row, 2nd column) = 120
*   `a_21` (element in 2nd row, 1st column) = 80
*   `a_22` (element in 2nd row, 2nd column) = 90

This notation is crucial for defining operations later on!

---

**3. Types of Matrices**

Now that we understand the basic structure, let's explore different types of matrices based on their order and the nature of their elements.

**a) Column Matrix:**
A matrix that has only **one column**.
*   Its order will be `m × 1`.

**Example:**
`A = [ 1 ]`
`    [ 2 ]`
`    [ 3 ]`
This is a 3 × 1 column matrix.

**b) Row Matrix:**
A matrix that has only **one row**.
*   Its order will be `1 × n`.

**Example:**
`B = [ 1  5  -2 ]`
This is a 1 × 3 row matrix.

**c) Square Matrix:**
A matrix in which the **number of rows is equal to the number of columns**.
*   Its order will be `m × m` (or simply said to be of order 'm').

**Example:**
`C = [ 1  2 ]`
`    [ 3  4 ]`
This is a 2 × 2 square matrix.

*   **Principal Diagonal / Main Diagonal:** In a square matrix, the elements `a_ij` where `i = j` (i.e., `a_11, a_22, a_33`, etc.) form the principal diagonal. In matrix C, 1 and 4 are diagonal elements.

**d) Diagonal Matrix:**
A **square matrix** in which all the **non-diagonal elements are zero**.
*   Only the elements on the principal diagonal can be non-zero.

**Example:**
`D = [ 5  0  0 ]`
`    [ 0  1  0 ]`
`    [ 0  0  9 ]`
This is a 3 × 3 diagonal matrix.

**e) Scalar Matrix:**
A **diagonal matrix** in which all the **diagonal elements are equal**.

**Example:**
`E = [ 7  0  0 ]`
`    [ 0  7  0 ]`
`    [ 0  0  7 ]`
This is a 3 × 3 scalar matrix. Notice how it's a special type of diagonal matrix.

**f) Identity Matrix (or Unit Matrix):**
A **scalar matrix** in which all the **diagonal elements are 1**.
*   It is denoted by `I_n`, where 'n' is the order of the matrix.

**Example:**
`I_2 = [ 1  0 ]` (2 × 2 identity matrix)
`      [ 0  1 ]`

`I_3 = [ 1  0  0 ]` (3 × 3 identity matrix)
`      [ 0  1  0 ]`
`      [ 0  0  1 ]`

The identity matrix plays a very important role, similar to the number '1' in scalar multiplication!

**g) Zero Matrix (or Null Matrix):**
A matrix in which **all the elements are zero**.
*   It is denoted by `O` or `0`. Its order is usually specified.

**Example:**
`O_(2 × 2) = [ 0  0 ]`
`            [ 0  0 ]`

`O_(3 × 1) = [ 0 ]`
`            [ 0 ]`
`            [ 0 ]`

---

**Quick Activity:**

Look at these matrices and tell me their order and what type they are:

1.  `P = [ 0  0  0 ]`
    `    [ 0  0  0 ]`

2.  `Q = [ 4 ]`
    `    [ 0 ]`
    `    [ 0 ]`

3.  `R = [ 1  2 ]`
    `    [ 2  1 ]`

(Take a moment to classify them!)

---

That covers the definition and basic types of matrices. Understanding these fundamental concepts is crucial before we move on to equality of matrices and then, the exciting part – matrix operations!

Any questions so far? Is anything unclear? Let's discuss before we move on.