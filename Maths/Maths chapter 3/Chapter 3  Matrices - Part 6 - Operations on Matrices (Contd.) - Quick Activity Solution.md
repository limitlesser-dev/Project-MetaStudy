# Chapter 3: Matrices - Part 6: Operations on Matrices (Contd.) - Quick Activity Solution

> [!SYNTHESIS] Your Progress So Far
> You correctly identified that $XY$ is defined and its order is $1 \times 1$.
> You also correctly identified that $YX$ is defined and its order is $3 \times 3$.
> That's fantastic! Understanding the pre-conditions and resultant order is half the battle won in matrix multiplication.

---

### Given Matrices:

*   $X = \begin{bmatrix} 1 & 2 & 3 \end{bmatrix}$ (Order: $1 \times 3$)
*   $Y = \begin{bmatrix} 4 \\ 5 \\ 6 \end{bmatrix}$ (Order: $3 \times 1$)

---

### 1. Calculating $XY$

#### 1.1 Is $XY$ Defined? What's its Order?
*   Columns of $X$ (3) = Rows of $Y$ (3)? **YES!**
*   The product $XY$ is defined.
*   Order of $XY$: (Rows of $X$) $\times$ (Columns of $Y$) $\rightarrow$ $1 \times 1$.

#### 1.2 Calculation of $XY$

Since $XY$ is a $1 \times 1$ matrix, it will have only one element, let's call it $c_{11}$.
To find $c_{11}$, we multiply the **1st row of $X$** by the **1st column of $Y$** and sum the products.

$c_{11} = (1 \times 4) + (2 \times 5) + (3 \times 6)$
$c_{11} = 4 + 10 + 18$
$c_{11} = 32$

So, $XY = \begin{bmatrix} 32 \end{bmatrix}$.

> [!NOTE] Your calculation for $c_{11}$ was $126$. Let's recheck your arithmetic for $1 \times 4 + 2 \times 5 + 3 \times 6$.
> $4 + 10 + 18 = 32$. It seems like a small arithmetic slip there. This is a common occurrence, so always double-check your sums!

---

### 2. Calculating $YX$

#### 2.1 Is $YX$ Defined? What's its Order?
*   Columns of $Y$ (1) = Rows of $X$ (1)? **YES!**
*   The product $YX$ is defined.
*   Order of $YX$: (Rows of $Y$) $\times$ (Columns of $X$) $\rightarrow$ $3 \times 3$.

#### 2.2 Calculation of $YX$

This is where it gets more involved, as we need to calculate 9 elements for the $3 \times 3$ result. Let's represent $YX$ as $P = \begin{bmatrix} p_{11} & p_{12} & p_{13} \\ p_{21} & p_{22} & p_{23} \\ p_{31} & p_{32} & p_{33} \end{bmatrix}$.

Remember the rule: $p_{ij}$ is the result of (Row $i$ of Y) $\times$ (Column $j$ of X).

Let's break it down:

*   **Row 1 of Y** is $\begin{bmatrix} 4 \end{bmatrix}$
*   **Row 2 of Y** is $\begin{bmatrix} 5 \end{bmatrix}$
*   **Row 3 of Y** is $\begin{bmatrix} 6 \end{bmatrix}$

*   **Column 1 of X** is $\begin{bmatrix} 1 \end{bmatrix}$
*   **Column 2 of X** is $\begin{bmatrix} 2 \end{bmatrix}$
*   **Column 3 of X** is $\begin{bmatrix} 3 \end{bmatrix}$

Now, let's calculate each element:

*   $p_{11}$: (Row 1 of Y) $\times$ (Column 1 of X) = $(4) \times (1) = 4$
*   $p_{12}$: (Row 1 of Y) $\times$ (Column 2 of X) = $(4) \times (2) = 8$
*   $p_{13}$: (Row 1 of Y) $\times$ (Column 3 of X) = $(4) \times (3) = 12$

*   $p_{21}$: (Row 2 of Y) $\times$ (Column 1 of X) = $(5) \times (1) = 5$
*   $p_{22}$: (Row 2 of Y) $\times$ (Column 2 of X) = $(5) \times (2) = 10$
*   $p_{23}$: (Row 2 of Y) $\times$ (Column 3 of X) = $(5) \times (3) = 15$

*   $p_{31}$: (Row 3 of Y) $\times$ (Column 1 of X) = $(6) \times (1) = 6$
*   $p_{32}$: (Row 3 of Y) $\times$ (Column 2 of X) = $(6) \times (2) = 12$
*   $p_{33}$: (Row 3 of Y) $\times$ (Column 3 of X) = $(6) \times (3) = 18$

Assembling the matrix $YX$:

$YX = \begin{bmatrix} 4 & 8 & 12 \\ 5 & 10 & 15 \\ 6 & 12 & 18 \end{bmatrix}$

---

> [!IMPORTANT] Takeaway from $XY$ vs $YX$
> Notice how dramatically different $XY$ (a $1 \times 1$ matrix) is from $YX$ (a $3 \times 3$ matrix). This strongly reinforces the idea that **matrix multiplication is NOT commutative** ($XY \ne YX$).

---

Now that we've grasped the core operations (addition, subtraction, scalar multiplication, and matrix multiplication), we're ready to look at their **properties**, then moving to the [[Transpose of a Matrix]] and related concepts.

Ready to continue our sprint through the chapter? We're making great progress!