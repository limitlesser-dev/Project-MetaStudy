# Solutions for EXERCISE 3.2

This document provides detailed solutions for EXERCISE 3.2, formatted for Obsidian Markdown, leveraging its math rendering capabilities.

---

## Question 1

Let $A = \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix}$, $B = \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix}$, $C = \begin{bmatrix} -2 & 5 \\ 3 & 4 \end{bmatrix}$.
Find each of the following:

**(i) $A + B$**
To add matrices, they must have the same order. Both $A$ and $B$ are $2 \times 2$ matrices. We add their corresponding elements:
$$
A + B = \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} + \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix} = \begin{bmatrix} 2+1 & 4+3 \\ 3+(-2) & 2+5 \end{bmatrix} = \begin{bmatrix} 3 & 7 \\ 1 & 7 \end{bmatrix}
$$

**(ii) $A - B$**
To subtract matrices, they must have the same order. Both $A$ and $B$ are $2 \times 2$ matrices. We subtract their corresponding elements:
$$
A - B = \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} - \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix} = \begin{bmatrix} 2-1 & 4-3 \\ 3-(-2) & 2-5 \end{bmatrix} = \begin{bmatrix} 1 & 1 \\ 5 & -3 \end{bmatrix}
$$

**(iii) $3A - C$**
First, we compute $3A$ by multiplying each element of $A$ by 3:
$$
3A = 3 \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} = \begin{bmatrix} 3 \times 2 & 3 \times 4 \\ 3 \times 3 & 3 \times 2 \end{bmatrix} = \begin{bmatrix} 6 & 12 \\ 9 & 6 \end{bmatrix}
$$
Now, we subtract $C$ from $3A$. Both matrices are $2 \times 2$:
$$
3A - C = \begin{bmatrix} 6 & 12 \\ 9 & 6 \end{bmatrix} - \begin{bmatrix} -2 & 5 \\ 3 & 4 \end{bmatrix} = \begin{bmatrix} 6-(-2) & 12-5 \\ 9-3 & 6-4 \end{bmatrix} = \begin{bmatrix} 8 & 7 \\ 6 & 2 \end{bmatrix}
$$

**(iv) $AB$**
To multiply matrices $A$ and $B$, the number of columns in $A$ must equal the number of rows in $B$. $A$ is $2 \times 2$ and $B$ is $2 \times 2$. The condition is met ($2=2$). The resulting matrix will be $2 \times 2$.
$$
AB = \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix} \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix}
$$
To find the element in the first row, first column of the product: (Row 1 of A) $\times$ (Column 1 of B)
$ (2)(1) + (4)(-2) = 2 - 8 = -6 $
To find the element in the first row, second column of the product: (Row 1 of A) $\times$ (Column 2 of B)
$ (2)(3) + (4)(5) = 6 + 20 = 26 $
To find the element in the second row, first column of the product: (Row 2 of A) $\times$ (Column 1 of B)
$ (3)(1) + (2)(-2) = 3 - 4 = -1 $
To find the element in the second row, second column of the product: (Row 2 of A) $\times$ (Column 2 of B)
$ (3)(3) + (2)(5) = 9 + 10 = 19 $
So,
$$
AB = \begin{bmatrix} -6 & 26 \\ -1 & 19 \end{bmatrix}
$$

**(v) $BA$**
To multiply matrices $B$ and $A$, the number of columns in $B$ must equal the number of rows in $A$. $B$ is $2 \times 2$ and $A$ is $2 \times 2$. The condition is met ($2=2$). The resulting matrix will be $2 \times 2$.
$$
BA = \begin{bmatrix} 1 & 3 \\ -2 & 5 \end{bmatrix} \begin{bmatrix} 2 & 4 \\ 3 & 2 \end{bmatrix}
$$
To find the element in the first row, first column of the product: (Row 1 of B) $\times$ (Column 1 of A)
$ (1)(2) + (3)(3) = 2 + 9 = 11 $
To find the element in the first row, second column of the product: (Row 1 of B) $\times$ (Column 2 of A)
$ (1)(4) + (3)(2) = 4 + 6 = 10 $
To find the element in the second row, first column of the product: (Row 2 of B) $\times$ (Column 1 of A)
$ (-2)(2) + (5)(3) = -4 + 15 = 11 $
To find the element in the second row, second column of the product: (Row 2 of B) $\times$ (Column 2 of A)
$ (-2)(4) + (5)(2) = -8 + 10 = 2 $
So,
$$
BA = \begin{bmatrix} 11 & 10 \\ 11 & 2 \end{bmatrix}
$$

---

## Question 2

Compute the following:

**(i)**
$$
\begin{bmatrix} a & b \\ -b & a \end{bmatrix} + \begin{bmatrix} a & b \\ b & a \end{bmatrix}
$$
Both matrices are $2 \times 2$, so addition is possible. Add corresponding elements:
$$
= \begin{bmatrix} a+a & b+b \\ -b+b & a+a \end{bmatrix} = \begin{bmatrix} 2a & 2b \\ 0 & 2a \end{bmatrix}
$$

**(ii)**
$$
\begin{bmatrix} a^2+b^2 & b^2+c^2 \\ a^2+c^2 & a^2+b^2 \end{bmatrix} + \begin{bmatrix} 2ab & -2ac \\ 2ac & -2ab \end{bmatrix}
$$
Both matrices are $2 \times 2$, so addition is possible. Add corresponding elements:
$$
= \begin{bmatrix} a^2+b^2+2ab & b^2+c^2-2ac \\ a^2+c^2+2ac & a^2+b^2-2ab \end{bmatrix}
$$
We can recognize some perfect squares and other terms:
$a^2+b^2+2ab = (a+b)^2$
$a^2+2ac+c^2 = (a+c)^2$
$b^2+c^2-2ac$ does not simplify further without more information or a typo.
$a^2+b^2-2ab = (a-b)^2$
So the sum is:
$$
= \begin{bmatrix} (a+b)^2 & b^2+c^2-2ac \\ (a+c)^2 & (a-b)^2 \end{bmatrix}
$$

**(iii)**
$$
\begin{bmatrix} \cos^2 x & \sin^2 x \\ \sin^2 x & \cos^2 x \end{bmatrix} + \begin{bmatrix} \sin^2 x & \cos^2 x \\ \cos^2 x & \sin^2 x \end{bmatrix}
$$
Both matrices are $2 \times 2$, so addition is possible. Add corresponding elements:
$$
= \begin{bmatrix} \cos^2 x + \sin^2 x & \sin^2 x + \cos^2 x \\ \sin^2 x + \cos^2 x & \cos^2 x + \sin^2 x \end{bmatrix}
$$
Using the fundamental trigonometric identity $\sin^2 \theta + \cos^2 \theta = 1$:
$$
= \begin{bmatrix} 1 & 1 \\ 1 & 1 \end{bmatrix}
$$

**(iv)**
$$
\begin{bmatrix} \cos^2 x & \sin^2 x \\ \sin^2 x & \cos^2 x \end{bmatrix} + \begin{bmatrix} \sin^2 x & \cos^2 x \\ \cos^2 x & \sin^2 x \end{bmatrix}
$$
This is identical to part (iii). Adding corresponding elements and using the identity $\sin^2 x + \cos^2 x = 1$:
$$
= \begin{bmatrix} 1 & 1 \\ 1 & 1 \end{bmatrix}
$$

---

## Question 3

Compute the indicated products.

**(i)**
$$
\begin{bmatrix} a & b \\ -b & a \end{bmatrix} \begin{bmatrix} a & b \\ -b & a \end{bmatrix}
$$
Both matrices are $2 \times 2$. The product is a $2 \times 2$ matrix.
$$
= \begin{bmatrix} (a)(a) + (b)(-b) & (a)(b) + (b)(a) \\ (-b)(a) + (a)(-b) & (-b)(b) + (a)(a) \end{bmatrix} = \begin{bmatrix} a^2 - b^2 & 2ab \\ -2ab & a^2 - b^2 \end{bmatrix}
$$

**(ii)**
$$
\begin{bmatrix} 1 & -2 \\ 2 & 3 \end{bmatrix} \begin{bmatrix} 1 & 2 \\ 3 & 1 \end{bmatrix}
$$
The first matrix is $2 \times 2$, the second is $2 \times 2$. The product is $2 \times 2$.
$$
= \begin{bmatrix} (1)(1)+(-2)(3) & (1)(2)+(-2)(1) \\ (2)(1)+(3)(3) & (2)(2)+(3)(1) \end{bmatrix} = \begin{bmatrix} 1-6 & 2-2 \\ 2+9 & 4+3 \end{bmatrix} = \begin{bmatrix} -5 & 0 \\ 11 & 7 \end{bmatrix}
$$

**(iii)**
$$
\begin{bmatrix} 2 & 3 \\ 3 & 2 \end{bmatrix} \begin{bmatrix} 1 & 2 \\ 3 & 1 \end{bmatrix}
$$
The first matrix is $2 \times 2$, the second is $2 \times 2$. The product is $2 \times 2$.
$$
= \begin{bmatrix} (2)(1)+(3)(3) & (2)(2)+(3)(1) \\ (3)(1)+(2)(3) & (3)(2)+(2)(1) \end{bmatrix} = \begin{bmatrix} 2+9 & 4+3 \\ 3+6 & 6+2 \end{bmatrix} = \begin{bmatrix} 11 & 7 \\ 9 & 8 \end{bmatrix}
$$

**(iv)**
$$
\begin{bmatrix} 3 & 4 \\ 4 & 5 \\ 6 & 3 \end{bmatrix} \begin{bmatrix} 1 & -3 \\ 0 & 2 \\ 4 & 5 \end{bmatrix}
$$
The first matrix has dimensions $3 \times 2$. The second matrix has dimensions $3 \times 2$.
For matrix multiplication $AB$, the number of columns in $A$ must equal the number of rows in $B$. Here, the number of columns in the first matrix is 2, and the number of rows in the second matrix is 3. Since $2 \neq 3$, this matrix multiplication is **not defined**.

**(v)**
$$
\begin{bmatrix} 2 & 1 \\ 3 & 2 \\ -1 & 1 \end{bmatrix} \begin{bmatrix} 1 & 0 & 1 \\ 0 & 1 & 0 \end{bmatrix}
$$
The first matrix has dimensions $3 \times 2$. The second matrix has dimensions $2 \times 3$. The condition for multiplication is met ($2=2$). The resulting matrix will have dimensions $3 \times 3$.
$$
= \begin{bmatrix} (2)(1)+(1)(0) & (2)(0)+(1)(1) & (2)(1)+(1)(0) \\ (3)(1)+(2)(0) & (3)(0)+(2)(1) & (3)(1)+(2)(0) \\ (-1)(1)+(1)(0) & (-1)(0)+(1)(1) & (-1)(1)+(1)(0) \end{bmatrix}
$$
$$
= \begin{bmatrix} 2+0 & 0+1 & 2+0 \\ 3+0 & 0+2 & 3+0 \\ -1+0 & 0+1 & -1+0 \end{bmatrix} = \begin{bmatrix} 2 & 1 & 2 \\ 3 & 2 & 3 \\ -1 & 1 & -1 \end{bmatrix}
$$

**(vi)**
$$
\begin{bmatrix} 3 & -1 & 3 \\ -1 & 0 & 2 \\ 3 & -1 & 3 \end{bmatrix} \begin{bmatrix} 2 & -3 \\ 1 & 0 \\ 3 & 1 \end{bmatrix}
$$
The first matrix is $3 \times 3$, the second is $3 \times 2$. The condition for multiplication is met ($3=3$). The resulting matrix will be $3 \times 2$.
$$
= \begin{bmatrix} (3)(2)+(-1)(1)+(3)(3) & (3)(-3)+(-1)(0)+(3)(1) \\ (-1)(2)+(0)(1)+(2)(3) & (-1)(-3)+(0)(0)+(2)(1) \\ (3)(2)+(-1)(1)+(3)(3) & (3)(-3)+(-1)(0)+(3)(1) \end{bmatrix}
$$
$$
= \begin{bmatrix} 6-1+9 & -9+0+3 \\ -2+0+6 & 3+0+2 \\ 6-1+9 & -9+0+3 \end{bmatrix} = \begin{bmatrix} 14 & -6 \\ 4 & 5 \\ 14 & -6 \end{bmatrix}
$$

# Solutions for EXERCISE 3.3 and 3.4, and Miscellaneous Exercises

This document provides detailed solutions for the remaining exercises, formatted for Obsidian Markdown.

---

## EXERCISE 3.3 (Continued from previous response)

**Q3. If $A' = \begin{bmatrix} 3 & 4 \\ 1 & 2 \\ -1 & 2 \end{bmatrix}$ and $B = \begin{bmatrix} 1 & 2 \\ 1 & 3 \\ 3 & 1 \end{bmatrix}$, then verify that:**
First, find $A$ from $A'$: $A = (A')' = \begin{bmatrix} 3 & 1 & -1 \\ 4 & 2 & 2 \end{bmatrix}$.
$A$ is a $2 \times 3$ matrix and $B$ is a $3 \times 2$ matrix.

**(i) $(A + B)' = A' + B'$**
For the property $(A+B)' = A'+B'$ to hold, $A$ and $B$ must be of the same order.
Here, $A$ is $2 \times 3$ and $B$ is $3 \times 2$. They are not of the same order.
Therefore, $A+B$ is not defined, and consequently $(A+B)'$ is not defined.
Also, $A'$ is $3 \times 2$ and $B'$ (transpose of $B$) is $2 \times 3$. Since $A'$ and $B'$ are not of the same order, $A'+B'$ is not defined.
Thus, the property cannot be verified with these specific matrices.

**(ii) $(A - B)' = A' - B'$**
Similarly, $A-B$ is not defined because $A$ and $B$ are not of the same order. Thus, $(A-B)'$ is not defined.
Also, $A'$ is $3 \times 2$ and $B'$ is $2 \times 3$. Thus $A' - B'$ is not defined.
This property also cannot be verified with these specific matrices.

**Note:** This question likely contains a typo, as the matrices are not of the same order, preventing the verification of these properties.

**Q4. If $A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$, $B = \begin{bmatrix} 4 & 2 & 5 \\ 1 & 3 & 2 \\ 2 & 0 & 3 \end{bmatrix}$ and $C = \begin{bmatrix} 1 & 2 & 3 \\ 0 & 3 & 2 \\ 4 & 5 & 6 \end{bmatrix}$, then compute $(A+B)$ and $(B-C)$. Also, verify that $A + (B - C) = (A + B) - C$.**

*   **Compute $A+B$**:
    $A$ and $B$ are both $3 \times 3$ matrices.
    $$
    A+B = \begin{bmatrix} 1+4 & 2+2 & 3+5 \\ 4+1 & 5+3 & 6+2 \\ 7+2 & 8+0 & 9+3 \end{bmatrix} = \begin{bmatrix} 5 & 4 & 8 \\ 5 & 8 & 8 \\ 9 & 8 & 12 \end{bmatrix}
    $$

*   **Compute $B-C$**:
    $B$ and $C$ are both $3 \times 3$ matrices.
    $$
    B-C = \begin{bmatrix} 4-1 & 2-2 & 5-3 \\ 1-0 & 3-3 & 2-2 \\ 2-4 & 0-5 & 3-6 \end{bmatrix} = \begin{bmatrix} 3 & 0 & 2 \\ 1 & 0 & 0 \\ -2 & -5 & -3 \end{bmatrix}
    $$

*   **Verify $A + (B - C) = (A + B) - C$** (Associative Property of Matrix Addition)

    **Calculate $A + (B - C)$:**
    $$
    A + (B - C) = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix} + \begin{bmatrix} 3 & 0 & 2 \\ 1 & 0 & 0 \\ -2 & -5 & -3 \end{bmatrix} = \begin{bmatrix} 1+3 & 2+0 & 3+2 \\ 4+1 & 5+0 & 6+0 \\ 7+(-2) & 8+(-5) & 9+(-3) \end{bmatrix} = \begin{bmatrix} 4 & 2 & 5 \\ 5 & 5 & 6 \\ 5 & 3 & 6 \end{bmatrix}
    $$

    **Calculate $(A + B) - C$:**
    $$
    (A + B) - C = \begin{bmatrix} 5 & 4 & 8 \\ 5 & 8 & 8 \\ 9 & 8 & 12 \end{bmatrix} - \begin{bmatrix} 1 & 2 & 3 \\ 0 & 3 & 2 \\ 4 & 5 & 6 \end{bmatrix} = \begin{bmatrix} 5-1 & 4-2 & 8-3 \\ 5-0 & 8-3 & 8-2 \\ 9-4 & 8-5 & 12-6 \end{bmatrix} = \begin{bmatrix} 4 & 2 & 5 \\ 5 & 5 & 6 \\ 5 & 3 & 6 \end{bmatrix}
    $$
    Since $A + (B - C) = (A + B) - C$, the equality is verified.

**Q5. If $A = \begin{bmatrix} 2 & 1 \\ 3 & 2 \\ 2 & 3 \end{bmatrix}$ and $B = \begin{bmatrix} 1 & 2 & 4 \\ 5 & 5 & 5 \\ 1 & 2 & 4 \end{bmatrix}$, then compute $3A - 5B$.**
$A$ is a $3 \times 2$ matrix, and $B$ is a $3 \times 3$ matrix.
Since the matrices $A$ and $B$ are not of the same order, the subtraction $3A - 5B$ is **not defined**.

**Q6. Simplify $\cos \theta \begin{bmatrix} \cos \theta & \sin \theta \\ -\sin \theta & \cos \theta \end{bmatrix} + \sin \theta \begin{bmatrix} \sin \theta & -\cos \theta \\ \cos \theta & \sin \theta \end{bmatrix}$.**
Perform scalar multiplication first:
$$
\begin{bmatrix} \cos^2 \theta & \cos \theta \sin \theta \\ -\cos \theta \sin \theta & \cos^2 \theta \end{bmatrix} + \begin{bmatrix} \sin^2 \theta & -\sin \theta \cos \theta \\ \sin \theta \cos \theta & \sin^2 \theta \end{bmatrix}
$$
Add the matrices:
$$
= \begin{bmatrix} \cos^2 \theta + \sin^2 \theta & \cos \theta \sin \theta - \sin \theta \cos \theta \\ -\cos \theta \sin \theta + \sin \theta \cos \theta & \cos^2 \theta + \sin^2 \theta \end{bmatrix}
$$
Using the identity $\sin^2 \theta + \cos^2 \theta = 1$:
$$
= \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}
$$

**Q7. Find X and Y, if**

**(i) $X + Y = \begin{bmatrix} 7 & 0 \\ 0 & 3 \end{bmatrix}$ and $X - Y = \begin{bmatrix} 3 & 0 \\ 0 & -1 \end{bmatrix}$**
Add the two equations: $(X+Y) + (X-Y) = \begin{bmatrix} 7 & 0 \\ 0 & 3 \end{bmatrix} + \begin{bmatrix} 3 & 0 \\ 0 & -1 \end{bmatrix} \implies 2X = \begin{bmatrix} 10 & 0 \\ 0 & 2 \end{bmatrix} \implies X = \begin{bmatrix} 5 & 0 \\ 0 & 1 \end{bmatrix}$.
Subtract the second equation from the first: $(X+Y) - (X-Y) = \begin{bmatrix} 7 & 0 \\ 0 & 3 \end{bmatrix} - \begin{bmatrix} 3 & 0 \\ 0 & -1 \end{bmatrix} \implies 2Y = \begin{bmatrix} 4 & 0 \\ 0 & 4 \end{bmatrix} \implies Y = \begin{bmatrix} 2 & 0 \\ 0 & 2 \end{bmatrix}$.

**(ii) $2X + 3Y = \begin{bmatrix} 2 & 3 \\ 4 & 0 \end{bmatrix}$ and $3X + 2Y = \begin{bmatrix} 2 & -1 \\ 5 & 6 \end{bmatrix}$**
Multiply the first equation by 2 and the second by 3:
$4X + 6Y = \begin{bmatrix} 4 & 6 \\ 8 & 0 \end{bmatrix}$
$9X + 6Y = \begin{bmatrix} 6 & -3 \\ 15 & 18 \end{bmatrix}$
Subtracting the first from the second: $5X = \begin{bmatrix} 2 & -9 \\ 7 & 18 \end{bmatrix} \implies X = \begin{bmatrix} \frac{2}{5} & -\frac{9}{5} \\ \frac{7}{5} & \frac{18}{5} \end{bmatrix}$.
Multiply the first equation by 3 and the second by 2:
$6X + 9Y = \begin{bmatrix} 6 & 9 \\ 12 & 0 \end{bmatrix}$
$6X + 4Y = \begin{bmatrix} 4 & -2 \\ 10 & 12 \end{bmatrix}$
Subtracting the second from the first: $5Y = \begin{bmatrix} 2 & 11 \\ 2 & -12 \end{bmatrix} \implies Y = \begin{bmatrix} \frac{2}{5} & \frac{11}{5} \\ \frac{2}{5} & -\frac{12}{5} \end{bmatrix}$.

**Q8. Find X, if $Y = \begin{bmatrix} 1 & 0 \\ 1 & 4 \end{bmatrix}$ and $2X + Y = \begin{bmatrix} 3 & 2 \\ 1 & 0 \end{bmatrix}$.**
$2X = \begin{bmatrix} 3 & 2 \\ 1 & 0 \end{bmatrix} - Y = \begin{bmatrix} 3 & 2 \\ 1 & 0 \end{bmatrix} - \begin{bmatrix} 1 & 0 \\ 1 & 4 \end{bmatrix} = \begin{bmatrix} 2 & 2 \\ 0 & -4 \end{bmatrix}$.
$X = \frac{1}{2} \begin{bmatrix} 2 & 2 \\ 0 & -4 \end{bmatrix} = \begin{bmatrix} 1 & 1 \\ 0 & -2 \end{bmatrix}$.

**Q9. Find x and y, if $2 \begin{bmatrix} 1 & 3 \\ 0 & x \end{bmatrix} + \begin{bmatrix} y & 0 \\ 1 & 4 \end{bmatrix} = \begin{bmatrix} 5 & 6 \\ 3 & 2 \end{bmatrix}$.**
$\begin{bmatrix} 2 & 6 \\ 0 & 2x \end{bmatrix} + \begin{bmatrix} y & 0 \\ 1 & 4 \end{bmatrix} = \begin{bmatrix} 5 & 6 \\ 3 & 2 \end{bmatrix}$
$\begin{bmatrix} 2+y & 6 \\ 1 & 2x+4 \end{bmatrix} = \begin{bmatrix} 5 & 6 \\ 3 & 2 \end{bmatrix}$
Equating elements: $2+y=5 \implies y=3$. $6=6$. $1=3$ (Contradiction). $2x+4=2$.
Since $1=3$ is a contradiction, there is **no solution** for $x$ and $y$.

**Q10. Solve the equation for $x, y, z$ and $t$, if $2 \begin{bmatrix} x & z \\ y & t \end{bmatrix} + 3 \begin{bmatrix} 1 & -1 \\ 0 & 2 \end{bmatrix} = 3 \begin{bmatrix} 3 & 5 \\ -2 & 4 \end{bmatrix}$.**
$\begin{bmatrix} 2x & 2z \\ 2y & 2t \end{bmatrix} + \begin{bmatrix} 3 & -3 \\ 0 & 6 \end{bmatrix} = \begin{bmatrix} 9 & 15 \\ -6 & 12 \end{bmatrix}$
$\begin{bmatrix} 2x+3 & 2z-3 \\ 2y & 2t+6 \end{bmatrix} = \begin{bmatrix} 9 & 15 \\ -6 & 12 \end{bmatrix}$
Equating elements:
$2x+3=9 \implies 2x=6 \implies x=3$.
$2z-3=15 \implies 2z=18 \implies z=9$.
$2y=-6 \implies y=-3$.
$2t+6=12 \implies 2t=6 \implies t=3$.
Solution: $x=3, y=-3, z=9, t=3$.

**Q11. If $X = \begin{bmatrix} x & y \\ z & w \end{bmatrix}$, $A = \begin{bmatrix} 1 & -1 \\ 0 & 2 \end{bmatrix}$, $B = \begin{bmatrix} 2 & 1 \\ 0 & -1 \end{bmatrix}$, find the values of $x, y, z$ and $w$ if $5A + 2X = 10B$.**
$5A = \begin{bmatrix} 5 & -5 \\ 0 & 10 \end{bmatrix}$, $10B = \begin{bmatrix} 20 & 10 \\ 0 & -10 \end{bmatrix}$.
$2X = 10B - 5A = \begin{bmatrix} 20 & 10 \\ 0 & -10 \end{bmatrix} - \begin{bmatrix} 5 & -5 \\ 0 & 10 \end{bmatrix} = \begin{bmatrix} 15 & 15 \\ 0 & -20 \end{bmatrix}$.
$X = \frac{1}{2} \begin{bmatrix} 15 & 15 \\ 0 & -20 \end{bmatrix} = \begin{bmatrix} \frac{15}{2} & \frac{15}{2} \\ 0 & -10 \end{bmatrix}$.
So, $x=\frac{15}{2}, y=\frac{15}{2}, z=0, w=-10$.

**Q12. Given $3 \begin{bmatrix} x & y \\ z & w \end{bmatrix} + 2 \begin{bmatrix} 1 & -1 \\ 0 & 2 \end{bmatrix} = \begin{bmatrix} 10 & 5 \\ 3 & 4 \end{bmatrix}$, find the values of $x, y, z$ and $w$.**
$\begin{bmatrix} 3x & 3y \\ 3z & 3w \end{bmatrix} + \begin{bmatrix} 2 & -2 \\ 0 & 4 \end{bmatrix} = \begin{bmatrix} 10 & 5 \\ 3 & 4 \end{bmatrix}$
$\begin{bmatrix} 3x+2 & 3y-2 \\ 3z & 3w+4 \end{bmatrix} = \begin{bmatrix} 10 & 5 \\ 3 & 4 \end{bmatrix}$
Equating elements:
$3x+2=10 \implies 3x=8 \implies x=\frac{8}{3}$.
$3y-2=5 \implies 3y=7 \implies y=\frac{7}{3}$.
$3z=3 \implies z=1$.
$3w+4=4 \implies 3w=0 \implies w=0$.
Solution: $x=\frac{8}{3}, y=\frac{7}{3}, z=1, w=0$.

---

## Miscellaneous Exercise on Chapter 3 (Continued)

**Q9. If $A = \begin{bmatrix} \alpha & \beta \\ \gamma & \alpha \end{bmatrix}$ is such that $A^2 = I$, then**
$A^2 = \begin{bmatrix} \alpha^2 + \beta\gamma & 2\alpha\beta \\ 2\alpha\gamma & \alpha^2 + \beta\gamma \end{bmatrix} = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}$.
From $\alpha^2 + \beta\gamma = 1$, we get $\alpha^2 + \beta\gamma - 1 = 0$, which is $1 - \alpha^2 - \beta\gamma = 0$.
**Answer:** (C) $1 - \alpha^2 - \beta\gamma = 0$.

**Q10. If the matrix $A$ is both symmetric and skew symmetric, then**
If $A$ is symmetric, $A'=A$. If $A$ is skew symmetric, $A'=-A$.
Thus $A=-A \implies 2A=0 \implies A=0$. The zero matrix.
**Answer:** (B) $A$ is a zero matrix.

**Q11. If $A$ is square matrix such that $A^2 = A$, then $(I + A)^3 - 7A$ is equal to**
$(I+A)^3 = I^3 + 3I^2A + 3IA^2 + A^3 = I + 3A + 3A^2 + A^3$.
Since $A^2=A$, we have $A^3 = A^2 \cdot A = A \cdot A = A^2 = A$.
So, $(I+A)^3 = I + 3A + 3A + A = I + 7A$.
Then $(I + A)^3 - 7A = (I + 7A) - 7A = I$.
**Answer:** (C) $I$.