# Chapter 3: Matrices - Part 12: Derivation of Symmetric and Skew-Symmetric Parts

> [!QUESTION] Why did we take $P = \frac{1}{2}(A + A^T)$ and $Q = \frac{1}{2}(A - A^T)$?

We want to show that *any* square matrix $A$ can be uniquely written as the sum of a symmetric matrix ($P$) and a skew-symmetric matrix ($Q$).

So, our goal is to find $P$ and $Q$ such that:
1.  $A = P + Q$
2.  $P$ is symmetric (meaning $P^T = P$)
3.  $Q$ is skew-symmetric (meaning $Q^T = -Q$)

---

### Step 1: Start with the fundamental assumption

Let's assume such $P$ and $Q$ exist.
We have our first equation:
$A = P + Q$  **(Equation 1)**

---

### Step 2: Take the transpose of Equation 1

Using the property of transpose of a sum ($(X+Y)^T = X^T + Y^T$):
$A^T = (P + Q)^T$
$A^T = P^T + Q^T$  **(Equation 2)**

---

### Step 3: Apply the definitions of Symmetric and Skew-Symmetric Matrices

Now, we use the properties that define $P$ as symmetric and $Q$ as skew-symmetric:
*   Since $P$ is symmetric, we know $P^T = P$.
*   Since $Q$ is skew-symmetric, we know $Q^T = -Q$.

Substitute these into **Equation 2**:
$A^T = P + (-Q)$
$A^T = P - Q$  **(Equation 3)**

---

### Step 4: Solve the system of linear equations for P and Q

Now we have a system of two matrix equations:

1.  $A = P + Q$
2.  $A^T = P - Q$

This is just like solving a system of two algebraic equations (e.g., $x = y+z$ and $a = y-z$).

#### To find P: Add Equation 1 and Equation 3
$(A) + (A^T) = (P + Q) + (P - Q)$
$A + A^T = P + Q + P - Q$
$A + A^T = 2P$

Divide by 2 (or multiply by $\frac{1}{2}$):
$P = \frac{1}{2}(A + A^T)$

#### To find Q: Subtract Equation 3 from Equation 1
$(A) - (A^T) = (P + Q) - (P - Q)$
$A - A^T = P + Q - P + Q$
$A - A^T = 2Q$

Divide by 2 (or multiply by $\frac{1}{2}$):
$Q = \frac{1}{2}(A - A^T)$

---

### Conclusion

So, the formulas for $P$ and $Q$ are not arbitrary. They are **derived directly from the definitions of symmetric and skew-symmetric matrices**, and the fundamental properties of matrix transpose.

This derivation proves that such a unique decomposition *always* exists for any square matrix $A$.

> [!INSIGHT] This derivation illustrates the power of using definitions and properties to arrive at new results. It's a common technique in mathematics!

Does that explanation clarify why those specific formulas are used? It's a neat piece of mathematical logic!