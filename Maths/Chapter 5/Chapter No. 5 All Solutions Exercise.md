Here are the step-by-step solutions to the exercise questions, formatted using Obsidian Markdown and LaTeX for mathematical expressions.

---

### **Chapter 5: Continuity and Differentiability**

---

#### **Exercise 5.1**

**1. Prove that the function $f(x) = 5x - 3$ is continuous at $x = 0$, at $x = -3$ and at $x = 5$.**

**Reasoning:**
A function $f(x)$ is continuous at a point $x=c$ if:
1. $f(c)$ is defined.
2. $\lim_{x \to c} f(x)$ exists.
3. $\lim_{x \to c} f(x) = f(c)$.
Since $f(x) = 5x - 3$ is a polynomial function, it is continuous everywhere. We will verify this for the given points.

**Step-by-step solution:**

*   **At $x = 0$:**
    1.  **Value of the function:** $f(0) = 5(0) - 3 = -3$.
    2.  **Limit of the function:** $\lim_{x \to 0} (5x - 3) = 5(0) - 3 = -3$.
    3.  **Comparison:** Since $\lim_{x \to 0} f(x) = f(0) = -3$, the function $f(x)$ is continuous at $x = 0$.

*   **At $x = -3$:**
    1.  **Value of the function:** $f(-3) = 5(-3) - 3 = -15 - 3 = -18$.
    2.  **Limit of the function:** $\lim_{x \to -3} (5x - 3) = 5(-3) - 3 = -15 - 3 = -18$.
    3.  **Comparison:** Since $\lim_{x \to -3} f(x) = f(-3) = -18$, the function $f(x)$ is continuous at $x = -3$.

*   **At $x = 5$:**
    1.  **Value of the function:** $f(5) = 5(5) - 3 = 25 - 3 = 22$.
    2.  **Limit of the function:** $\lim_{x \to 5} (5x - 3) = 5(5) - 3 = 25 - 3 = 22$.
    3.  **Comparison:** Since $\lim_{x \to 5} f(x) = f(5) = 22$, the function $f(x)$ is continuous at $x = 5$.

---

**2. Examine the continuity of the function $f(x) = 2x^2 - 1$ at $x = 3$.**

**Reasoning:**
Similar to question 1, $f(x) = 2x^2 - 1$ is a polynomial function, which is continuous everywhere. We will confirm its continuity at $x = 3$.

**Step-by-step solution:**

*   **At $x = 3$:**
    1.  **Value of the function:** $f(3) = 2(3)^2 - 1 = 2(9) - 1 = 18 - 1 = 17$.
    2.  **Limit of the function:** $\lim_{x \to 3} (2x^2 - 1) = 2(3)^2 - 1 = 2(9) - 1 = 18 - 1 = 17$.
    3.  **Comparison:** Since $\lim_{x \to 3} f(x) = f(3) = 17$, the function $f(x)$ is continuous at $x = 3$.

---

**3. Examine the following functions for continuity.**

**(a) $f(x) = x - 5$**

**Reasoning:**
This is a polynomial function, which is continuous for all real numbers.

**Step-by-step solution:**
For any real number $c$:
1.  $f(c) = c - 5$ is defined.
2.  $\lim_{x \to c} f(x) = \lim_{x \to c} (x - 5) = c - 5$.
3.  Since $\lim_{x \to c} f(x) = f(c)$, the function $f(x) = x - 5$ is continuous for all real numbers.

---

**(b) $f(x) = \frac{1}{x - 5}$, $x \neq 5$**

**Reasoning:**
This is a rational function. Rational functions are continuous everywhere in their domain. The domain is all real numbers except where the denominator is zero.

**Step-by-step solution:**
The function $f(x) = \frac{1}{x - 5}$ is defined for all real numbers $x \neq 5$.
For any $c \in \mathbb{R}$ such that $c \neq 5$:
1.  $f(c) = \frac{1}{c - 5}$ is defined.
2.  $\lim_{x \to c} f(x) = \lim_{x \to c} \frac{1}{x - 5} = \frac{1}{c - 5}$.
3.  Since $\lim_{x \to c} f(x) = f(c)$, the function $f(x)$ is continuous for all real numbers $x \neq 5$.
    At $x=5$, the function is undefined, so it is discontinuous at $x=5$.

---

**(c) $f(x) = \frac{x^2 - 25}{x + 5}$, $x \neq -5$**

**Reasoning:**
This is a rational function. We can simplify the expression first.

**Step-by-step solution:**
The function is defined for $x \neq -5$.
We can simplify $f(x)$:
$f(x) = \frac{(x - 5)(x + 5)}{x + 5}$
For $x \neq -5$, $f(x) = x - 5$.
For any $c \in \mathbb{R}$ such that $c \neq -5$:
1.  $f(c) = c - 5$ is defined.
2.  $\lim_{x \to c} f(x) = \lim_{x \to c} (x - 5) = c - 5$.
3.  Since $\lim_{x \to c} f(x) = f(c)$, the function $f(x)$ is continuous for all real numbers $x \neq -5$.
    At $x=-5$, the function is undefined, so it is discontinuous at $x=-5$.

---

**(d) $f(x) = |x - 5|$**

**Reasoning:**
The absolute value function is a composite of a polynomial function ($x-5$) and the absolute value function ($|u|$). Both are continuous functions. The composition of continuous functions is continuous.

**Step-by-step solution:**
We can write $f(x)$ as a piecewise function:
$f(x) = \begin{cases} -(x - 5) & \text{if } x < 5 \\ x - 5 & \text{if } x \geq 5 \end{cases}$

*   **For $x < 5$:** $f(x) = -(x - 5)$ is a polynomial, hence continuous.
*   **For $x > 5$:** $f(x) = x - 5$ is a polynomial, hence continuous.
*   **At $x = 5$:**
    1.  **Value of the function:** $f(5) = 5 - 5 = 0$.
    2.  **Left-hand limit:** $\lim_{x \to 5^-} f(x) = \lim_{x \to 5^-} -(x - 5) = -(5 - 5) = 0$.
    3.  **Right-hand limit:** $\lim_{x \to 5^+} f(x) = \lim_{x \to 5^+} (x - 5) = 5 - 5 = 0$.
    4.  **Comparison:** Since $\lim_{x \to 5^-} f(x) = \lim_{x \to 5^+} f(x) = 0$, the limit $\lim_{x \to 5} f(x) = 0$.
        Also, $\lim_{x \to 5} f(x) = f(5) = 0$.
    Therefore, $f(x) = |x - 5|$ is continuous at $x = 5$.

Combining these, $f(x) = |x - 5|$ is continuous for all real numbers.

---

**4. Prove that the function $f(x) = x^n$ is continuous at $x = n$, where $n$ is a positive integer.**

**Reasoning:**
The problem statement seems to have a slight typo. Usually, we prove continuity at any real number $c$ for the function $f(x) = x^n$. If it means proving continuity at a point $x=n$, then it's a specific case. Let's assume the question meant "Prove that the function $f(x) = x^n$ is continuous for all $x \in \mathbb{R}$". However, following the literal wording, we will prove continuity at $x=n$.

**Step-by-step solution:**
Let $c$ be a real number. For the function $f(x) = x^n$, where $n$ is a positive integer:
1.  **Value of the function at $x=c$**: $f(c) = c^n$ is defined for any real number $c$.
2.  **Limit of the function at $x=c$**: $\lim_{x \to c} f(x) = \lim_{x \to c} x^n = c^n$.
3.  **Comparison**: Since $\lim_{x \to c} f(x) = f(c)$, the function $f(x) = x^n$ is continuous at any real number $c$.

Therefore, the function $f(x) = x^n$ is continuous at $x = n$ (which is a specific real number $c$). More generally, it is continuous for all real numbers.

---

**5. Is the function $f$ defined by $f(x) = \begin{cases} x & \text{if } x \leq 1 \\ 5 & \text{if } x > 1 \end{cases}$ continuous at $x = 0$? At $x = 1$? At $x = 2$?**

**Reasoning:**
We need to check continuity at three specific points. The definition of the function changes at $x=1$, so that point will require checking left-hand and right-hand limits. For $x=0$ and $x=2$, the function is defined by a single rule around those points.

**Step-by-step solution:**

*   **At $x = 0$:**
    Since $0 \leq 1$, $f(x) = x$ for values around $x=0$.
    1.  **Value of the function:** $f(0) = 0$.
    2.  **Limit of the function:** $\lim_{x \to 0} f(x) = \lim_{x \to 0} x = 0$.
    3.  **Comparison:** Since $\lim_{x \to 0} f(x) = f(0) = 0$, the function is continuous at $x = 0$.

*   **At $x = 1$:**
    This is the point where the definition of the function changes.
    1.  **Value of the function:** $f(1) = 1$ (since $x \leq 1$).
    2.  **Left-hand limit:** $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} x = 1$.
    3.  **Right-hand limit:** $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} 5 = 5$.
    4.  **Comparison:** Since the left-hand limit ($1$) is not equal to the right-hand limit ($5$), $\lim_{x \to 1} f(x)$ does not exist.
    Therefore, the function is discontinuous at $x = 1$.

*   **At $x = 2$:**
    Since $2 > 1$, $f(x) = 5$ for values around $x=2$.
    1.  **Value of the function:** $f(2) = 5$.
    2.  **Limit of the function:** $\lim_{x \to 2} f(x) = \lim_{x \to 2} 5 = 5$.
    3.  **Comparison:** Since $\lim_{x \to 2} f(x) = f(2) = 5$, the function is continuous at $x = 2$.

---

**Find all points of discontinuity of $f$, where $f$ is defined by**

**6. $f(x) = \begin{cases} 2x + 3 & \text{if } x \leq 2 \\ 2x - 3 & \text{if } x > 2 \end{cases}$**

**Reasoning:**
The function is defined by polynomials in the intervals $x<2$ and $x>2$, so it is continuous in these open intervals. We only need to check for continuity at the point where the definition changes, which is $x=2$.

**Step-by-step solution:**

*   **Continuity for $x < 2$:**
    For any $c < 2$, $f(x) = 2x + 3$, which is a polynomial and thus continuous.

*   **Continuity for $x > 2$:**
    For any $c > 2$, $f(x) = 2x - 3$, which is a polynomial and thus continuous.

*   **Continuity at $x = 2$:**
    1.  **Value of the function:** $f(2) = 2(2) + 3 = 4 + 3 = 7$ (since $x \leq 2$).
    2.  **Left-hand limit:** $\lim_{x \to 2^-} f(x) = \lim_{x \to 2^-} (2x + 3) = 2(2) + 3 = 7$.
    3.  **Right-hand limit:** $\lim_{x \to 2^+} f(x) = \lim_{x \to 2^+} (2x - 3) = 2(2) - 3 = 4 - 3 = 1$.
    4.  **Comparison:** Since the left-hand limit ($7$) is not equal to the right-hand limit ($1$), $\lim_{x \to 2} f(x)$ does not exist.

Therefore, the function $f(x)$ is discontinuous at $x = 2$. There are no other points of discontinuity.

---

**7. $f(x) = \begin{cases} |x| + 3 & \text{if } x \leq -3 \\ -2x & \text{if } -3 < x < 3 \\ 6x + 2 & \text{if } x \geq 3 \end{cases}$**

**Reasoning:**
The function is defined by polynomial or absolute value functions in open intervals, so it is continuous within those intervals. We need to check for continuity at the points where the definition changes, which are $x=-3$ and $x=3$.

**Step-by-step solution:**

*   **Continuity for $x < -3$:**
    For $x < -3$, $f(x) = |x| + 3 = -x + 3$ (since $x$ is negative). This is a polynomial, thus continuous.

*   **Continuity for $-3 < x < 3$:**
    For $-3 < x < 3$, $f(x) = -2x$, which is a polynomial and thus continuous.

*   **Continuity for $x > 3$:**
    For $x > 3$, $f(x) = 6x + 2$, which is a polynomial and thus continuous.

*   **Continuity at $x = -3$:**
    1.  **Value of the function:** $f(-3) = |-3| + 3 = 3 + 3 = 6$ (since $x \leq -3$).
    2.  **Left-hand limit:** $\lim_{x \to -3^-} f(x) = \lim_{x \to -3^-} (|x| + 3) = \lim_{x \to -3^-} (-x + 3) = -(-3) + 3 = 3 + 3 = 6$.
    3.  **Right-hand limit:** $\lim_{x \to -3^+} f(x) = \lim_{x \to -3^+} (-2x) = -2(-3) = 6$.
    4.  **Comparison:** Since $\lim_{x \to -3^-} f(x) = \lim_{x \to -3^+} f(x) = 6$, the limit $\lim_{x \to -3} f(x) = 6$.
        Also, $\lim_{x \to -3} f(x) = f(-3) = 6$.
    Therefore, the function is continuous at $x = -3$.

*   **Continuity at $x = 3$:**
    1.  **Value of the function:** $f(3) = 6(3) + 2 = 18 + 2 = 20$ (since $x \geq 3$).
    2.  **Left-hand limit:** $\lim_{x \to 3^-} f(x) = \lim_{x \to 3^-} (-2x) = -2(3) = -6$.
    3.  **Right-hand limit:** $\lim_{x \to 3^+} f(x) = \lim_{x \to 3^+} (6x + 2) = 6(3) + 2 = 18 + 2 = 20$.
    4.  **Comparison:** Since the left-hand limit ($-6$) is not equal to the right-hand limit ($20$), $\lim_{x \to 3} f(x)$ does not exist.

Therefore, the function $f(x)$ is discontinuous at $x = 3$.

---

**8. $f(x) = \begin{cases} \frac{|x|}{x} & \text{if } x \neq 0 \\ 0 & \text{if } x = 0 \end{cases}$**

**Reasoning:**
The function is defined piecewise. The crucial point to check is where the definition changes, $x=0$. The term $\frac{|x|}{x}$ needs to be evaluated using left and right limits.

**Step-by-step solution:**
First, let's rewrite $\frac{|x|}{x}$:
If $x > 0$, $|x| = x$, so $\frac{|x|}{x} = \frac{x}{x} = 1$.
If $x < 0$, $|x| = -x$, so $\frac{|x|}{x} = \frac{-x}{x} = -1$.
So, the function can be written as:
$f(x) = \begin{cases} -1 & \text{if } x < 0 \\ 0 & \text{if } x = 0 \\ 1 & \text{if } x > 0 \end{cases}$

*   **Continuity for $x < 0$:**
    For any $c < 0$, $f(x) = -1$, which is a constant function and thus continuous.

*   **Continuity for $x > 0$:**
    For any $c > 0$, $f(x) = 1$, which is a constant function and thus continuous.

*   **Continuity at $x = 0$:**
    1.  **Value of the function:** $f(0) = 0$.
    2.  **Left-hand limit:** $\lim_{x \to 0^-} f(x) = \lim_{x \to 0^-} (-1) = -1$.
    3.  **Right-hand limit:** $\lim_{x \to 0^+} f(x) = \lim_{x \to 0^+} (1) = 1$.
    4.  **Comparison:** Since the left-hand limit ($-1$) is not equal to the right-hand limit ($1$), $\lim_{x \to 0} f(x)$ does not exist.

Therefore, the function $f(x)$ is discontinuous at $x = 0$.

---

**9. $f(x) = \begin{cases} \frac{x}{|x|} & \text{if } x < 0 \\ -1 & \text{if } x \geq 0 \end{cases}$**

**Reasoning:**
Similar to question 8, we need to analyze $\frac{x}{|x|}$ and then check continuity at $x=0$.

**Step-by-step solution:**
First, let's rewrite $\frac{x}{|x|}$ for $x < 0$:
If $x < 0$, $|x| = -x$, so $\frac{x}{|x|} = \frac{x}{-x} = -1$.
So, the function can be written as:
$f(x) = \begin{cases} -1 & \text{if } x < 0 \\ -1 & \text{if } x \geq 0 \end{cases}$
This means $f(x) = -1$ for all real numbers $x$.

*   **Continuity for all real numbers:**
    For any real number $c$:
    1.  **Value of the function:** $f(c) = -1$.
    2.  **Limit of the function:** $\lim_{x \to c} f(x) = \lim_{x \to c} (-1) = -1$.
    3.  **Comparison:** Since $\lim_{x \to c} f(x) = f(c) = -1$, the function $f(x)$ is continuous for all real numbers.

Therefore, there are no points of discontinuity.

---

**10. $f(x) = \begin{cases} x + 1 & \text{if } x \leq 1 \\ x^2 + 1 & \text{if } x > 1 \end{cases}$**

**Reasoning:**
The function is defined by polynomials in the intervals $x<1$ and $x>1$. We need to check continuity at $x=1$.

**Step-by-step solution:**

*   **Continuity for $x < 1$:**
    For any $c < 1$, $f(x) = x + 1$, which is a polynomial and thus continuous.

*   **Continuity for $x > 1$:**
    For any $c > 1$, $f(x) = x^2 + 1$, which is a polynomial and thus continuous.

*   **Continuity at $x = 1$:**
    1.  **Value of the function:** $f(1) = 1 + 1 = 2$ (since $x \leq 1$).
    2.  **Left-hand limit:** $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (x + 1) = 1 + 1 = 2$.
    3.  **Right-hand limit:** $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (x^2 + 1) = 1^2 + 1 = 1 + 1 = 2$.
    4.  **Comparison:** Since $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^+} f(x) = 2$, the limit $\lim_{x \to 1} f(x) = 2$.
        Also, $\lim_{x \to 1} f(x) = f(1) = 2$.
    Therefore, the function is continuous at $x = 1$.

Combining these, the function $f(x)$ is continuous for all real numbers. There are no points of discontinuity.

---

**11. $f(x) = \begin{cases} x^{10} - 1 & \text{if } x \leq 1 \\ x^2 & \text{if } x > 1 \end{cases}$**

**Reasoning:**
The function is defined by polynomials in the intervals $x<1$ and $x>1$. We need to check continuity at $x=1$.

**Step-by-step solution:**

*   **Continuity for $x < 1$:**
    For any $c < 1$, $f(x) = x^{10} - 1$, which is a polynomial and thus continuous.

*   **Continuity for $x > 1$:**
    For any $c > 1$, $f(x) = x^2$, which is a polynomial and thus continuous.

*   **Continuity at $x = 1$:**
    1.  **Value of the function:** $f(1) = 1^{10} - 1 = 1 - 1 = 0$ (since $x \leq 1$).
    2.  **Left-hand limit:** $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (x^{10} - 1) = 1^{10} - 1 = 0$.
    3.  **Right-hand limit:** $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (x^2) = 1^2 = 1$.
    4.  **Comparison:** Since the left-hand limit ($0$) is not equal to the right-hand limit ($1$), $\lim_{x \to 1} f(x)$ does not exist.

Therefore, the function $f(x)$ is discontinuous at $x = 1$.

---

**12. Is the function $f$ defined by $f(x) = \begin{cases} x^{10} - 1 & \text{if } x \leq 1 \\ x^2 & \text{if } x > 1 \end{cases}$ (Same as 11, question likely meant something else for 12, referring to an example given earlier in the document: $f(x) = \begin{cases} x+5 & \text{if } x \leq 1 \\ x-5 & \text{if } x > 1 \end{cases}$ from Example 13 or similar structure for continuity checks.)**

Let's assume the question is asking to examine the continuity for $f(x) = \begin{cases} x+5 & \text{if } x \leq 1 \\ x-5 & \text{if } x > 1 \end{cases}$ as it fits the exercise pattern of piecewise functions. If it's a direct repeat of question 11, the answer is the same as 11. Assuming it's a new question from the text's context, I'll solve for the likely intended function.

**Assumption: $f(x) = \begin{cases} x+5 & \text{if } x \leq 1 \\ x-5 & \text{if } x > 1 \end{cases}$**

**Reasoning:**
The function is defined by polynomials in the intervals $x<1$ and $x>1$. We need to check continuity at $x=1$.

**Step-by-step solution:**

*   **Continuity for $x < 1$:**
    For any $c < 1$, $f(x) = x + 5$, which is a polynomial and thus continuous.

*   **Continuity for $x > 1$:**
    For any $c > 1$, $f(x) = x - 5$, which is a polynomial and thus continuous.

*   **Continuity at $x = 1$:**
    1.  **Value of the function:** $f(1) = 1 + 5 = 6$ (since $x \leq 1$).
    2.  **Left-hand limit:** $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (x + 5) = 1 + 5 = 6$.
    3.  **Right-hand limit:** $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (x - 5) = 1 - 5 = -4$.
    4.  **Comparison:** Since the left-hand limit ($6$) is not equal to the right-hand limit ($-4$), $\lim_{x \to 1} f(x)$ does not exist.

Therefore, the function $f(x)$ is discontinuous at $x = 1$.

*(If Question 12 was indeed a repeat of Question 11, then the answer to Question 11 applies.)*

---

**13. Is the function defined by $f(x) = \begin{cases} x+5 & \text{if } x \leq 1 \\ x-5 & \text{if } x > 1 \end{cases}$ a continuous function?**

**Reasoning:**
This is the same function as assumed for question 12. We need to check continuity at the point where the definition changes, $x=1$.

**Step-by-step solution:**

*   **At $x=1$:**
    1.  **Value of the function:** $f(1) = 1 + 5 = 6$ (since $x \leq 1$).
    2.  **Left-hand limit:** $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (x + 5) = 1 + 5 = 6$.
    3.  **Right-hand limit:** $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (x - 5) = 1 - 5 = -4$.
    4.  **Comparison:** Since the left-hand limit ($6$) is not equal to the right-hand limit ($-4$), $\lim_{x \to 1} f(x)$ does not exist.

Since the limit at $x=1$ does not exist, the function is discontinuous at $x=1$. Therefore, $f(x)$ is **not a continuous function** (meaning it's not continuous over its entire domain). It is continuous everywhere except at $x=1$.

---

**Discuss the continuity of the function $f$, where $f$ is defined by**

**14. $f(x) = \begin{cases} 3 & \text{if } 0 \leq x \leq 1 \\ 4 & \text{if } 1 < x < 3 \\ 5 & \text{if } 3 \leq x \leq 10 \end{cases}$**

**Reasoning:**
This function is piecewise constant. Constant functions are continuous within their defined intervals. We need to check for continuity at the points where the definition changes, which are $x=1$ and $x=3$.

**Step-by-step solution:**

*   **Continuity for $0 \leq x < 1$:**
    $f(x) = 3$, a constant, continuous.

*   **Continuity for $1 < x < 3$:**
    $f(x) = 4$, a constant, continuous.

*   **Continuity for $3 < x \leq 10$:**
    $f(x) = 5$, a constant, continuous.

*   **Continuity at $x = 1$:**
    1.  **Value of the function:** $f(1) = 3$ (since $0 \leq x \leq 1$).
    2.  **Left-hand limit:** $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} 3 = 3$.
    3.  **Right-hand limit:** $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} 4 = 4$.
    4.  **Comparison:** Since the left-hand limit ($3$) is not equal to the right-hand limit ($4$), $\lim_{x \to 1} f(x)$ does not exist.
    Therefore, the function is discontinuous at $x = 1$.

*   **Continuity at $x = 3$:**
    1.  **Value of the function:** $f(3) = 5$ (since $3 \leq x \leq 10$).
    2.  **Left-hand limit:** $\lim_{x \to 3^-} f(x) = \lim_{x \to 3^-} 4 = 4$.
    3.  **Right-hand limit:** $\lim_{x \to 3^+} f(x) = \lim_{x \to 3^+} 5 = 5$.
    4.  **Comparison:** Since the left-hand limit ($4$) is not equal to the right-hand limit ($5$), $\lim_{x \to 3} f(x)$ does not exist.
    Therefore, the function is discontinuous at $x = 3$.

The points of discontinuity are $x = 1$ and $x = 3$.

---

**15. $f(x) = \begin{cases} 2x & \text{if } x < 0 \\ 0 & \text{if } 0 \leq x \leq 1 \\ 4x & \text{if } x > 1 \end{cases}$**

**Reasoning:**
The function is defined by polynomials/constants in the given intervals. We need to check for continuity at the points where the definition changes, which are $x=0$ and $x=1$.

**Step-by-step solution:**

*   **Continuity for $x < 0$:**
    $f(x) = 2x$, a polynomial, continuous.

*   **Continuity for $0 < x < 1$:**
    $f(x) = 0$, a constant, continuous.

*   **Continuity for $x > 1$:**
    $f(x) = 4x$, a polynomial, continuous.

*   **Continuity at $x = 0$:**
    1.  **Value of the function:** $f(0) = 0$ (since $0 \leq x \leq 1$).
    2.  **Left-hand limit:** $\lim_{x \to 0^-} f(x) = \lim_{x \to 0^-} (2x) = 2(0) = 0$.
    3.  **Right-hand limit:** $\lim_{x \to 0^+} f(x) = \lim_{x \to 0^+} 0 = 0$.
    4.  **Comparison:** Since $\lim_{x \to 0^-} f(x) = \lim_{x \to 0^+} f(x) = 0$, the limit $\lim_{x \to 0} f(x) = 0$.
        Also, $\lim_{x \to 0} f(x) = f(0) = 0$.
    Therefore, the function is continuous at $x = 0$.

*   **Continuity at $x = 1$:**
    1.  **Value of the function:** $f(1) = 0$ (since $0 \leq x \leq 1$).
    2.  **Left-hand limit:** $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} 0 = 0$.
    3.  **Right-hand limit:** $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (4x) = 4(1) = 4$.
    4.  **Comparison:** Since the left-hand limit ($0$) is not equal to the right-hand limit ($4$), $\lim_{x \to 1} f(x)$ does not exist.
    Therefore, the function is discontinuous at $x = 1$.

The only point of discontinuity is $x = 1$.

---

**16. $f(x) = \begin{cases} -2 & \text{if } x \leq -1 \\ 2x & \text{if } -1 < x < 1 \\ 2 & \text{if } x > 1 \end{cases}$**

**Reasoning:**
The function is defined by constants or polynomials in the given intervals. We need to check for continuity at the points where the definition changes, which are $x=-1$ and $x=1$.

**Step-by-step solution:**

*   **Continuity for $x < -1$:**
    $f(x) = -2$, a constant, continuous.

*   **Continuity for $-1 < x < 1$:**
    $f(x) = 2x$, a polynomial, continuous.

*   **Continuity for $x > 1$:**
    $f(x) = 2$, a constant, continuous.

*   **Continuity at $x = -1$:**
    1.  **Value of the function:** $f(-1) = -2$ (since $x \leq -1$).
    2.  **Left-hand limit:** $\lim_{x \to -1^-} f(x) = \lim_{x \to -1^-} (-2) = -2$.
    3.  **Right-hand limit:** $\lim_{x \to -1^+} f(x) = \lim_{x \to -1^+} (2x) = 2(-1) = -2$.
    4.  **Comparison:** Since $\lim_{x \to -1^-} f(x) = \lim_{x \to -1^+} f(x) = -2$, the limit $\lim_{x \to -1} f(x) = -2$.
        Also, $\lim_{x \to -1} f(x) = f(-1) = -2$.
    Therefore, the function is continuous at $x = -1$.

*   **Continuity at $x = 1$:**
    1.  **Value of the function:** $f(1)$ is not defined by $x \leq -1$ or $x > 1$. The interval is $-1 < x < 1$. The problem statement has $x > 1$ for the last case. If $x=1$ falls into the $2x$ category ($x \leq 1$), then $f(1)=2(1)=2$. If $x=1$ is not included in any piece, then the function is undefined at $x=1$. Assuming standard piecewise notation where the strict inequality implies it's not included, let's re-evaluate.
    However, the third case is $x > 1$. This means the domain of the function is $(-\infty, \infty)$ but at $x=1$ it is not explicitly stated. Typically, one of the inequalities would be inclusive. Let's assume the question meant $x \geq 1$ for the third piece, or the middle piece includes $x=1$. Let's assume the question text implies:
    $f(x) = \begin{cases} -2 & \text{if } x \leq -1 \\ 2x & \text{if } -1 < x \leq 1 \\ 2 & \text{if } x > 1 \end{cases}$ (This is a common way to write these functions for continuity checks.)

    Let's re-solve with this assumption (which makes sense from the context).
    2.  **Value of the function (assuming $x \leq 1$ for $2x$):** $f(1) = 2(1) = 2$.
    3.  **Left-hand limit:** $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (2x) = 2(1) = 2$.
    4.  **Right-hand limit:** $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} 2 = 2$.
    5.  **Comparison:** Since $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^+} f(x) = 2$, the limit $\lim_{x \to 1} f(x) = 2$.
        Also, $\lim_{x \to 1} f(x) = f(1) = 2$.
    Therefore, the function is continuous at $x = 1$.

Under this reasonable interpretation, the function is continuous for all real numbers. There are no points of discontinuity.

*(If the problem meant strictly $x > 1$ for the last piece and strictly $x < 1$ for the middle, leaving $x=1$ undefined, then $x=1$ would be a point of discontinuity due to $f(1)$ being undefined.)*

---

**17. Find the relationship between $a$ and $b$ so that the function $f$ defined by $f(x) = \begin{cases} ax + 1 & \text{if } x \leq 3 \\ bx + 3 & \text{if } x > 3 \end{cases}$ is continuous at $x = 3$.**

**Reasoning:**
For the function to be continuous at $x=3$, the value of the function, the left-hand limit, and the right-hand limit must all be equal at $x=3$.

**Step-by-step solution:**

*   **Continuity at $x = 3$:**
    1.  **Value of the function:** $f(3) = a(3) + 1 = 3a + 1$ (since $x \leq 3$).
    2.  **Left-hand limit:** $\lim_{x \to 3^-} f(x) = \lim_{x \to 3^-} (ax + 1) = a(3) + 1 = 3a + 1$.
    3.  **Right-hand limit:** $\lim_{x \to 3^+} f(x) = \lim_{x \to 3^+} (bx + 3) = b(3) + 3 = 3b + 3$.

For continuity at $x=3$, we must have:
Left-hand limit = Right-hand limit = Value of the function
$3a + 1 = 3b + 3$
Now, we solve for the relationship between $a$ and $b$:
$3a - 3b = 3 - 1$
$3a - 3b = 2$
$a - b = \frac{2}{3}$

The relationship between $a$ and $b$ for $f(x)$ to be continuous at $x=3$ is $a - b = \frac{2}{3}$.

---

**18. For what value of $\lambda$ is the function defined by $f(x) = \begin{cases} \lambda(x^2 - 2x) & \text{if } x \leq 0 \\ 4x + 1 & \text{if } x > 0 \end{cases}$ continuous at $x = 0$? What about continuity at $x = 1$?**

**Reasoning:**
First, we find the value of $\lambda$ that makes the function continuous at $x=0$ by equating the limits and function value. Then, we examine the continuity at $x=1$ using the determined $\lambda$.

**Step-by-step solution:**

*   **Continuity at $x = 0$:**
    1.  **Value of the function:** $f(0) = \lambda(0^2 - 2(0)) = \lambda(0) = 0$ (since $x \leq 0$).
    2.  **Left-hand limit:** $\lim_{x \to 0^-} f(x) = \lim_{x \to 0^-} \lambda(x^2 - 2x) = \lambda(0^2 - 2(0)) = 0$.
    3.  **Right-hand limit:** $\lim_{x \to 0^+} f(x) = \lim_{x \to 0^+} (4x + 1) = 4(0) + 1 = 1$.

For continuity at $x=0$, all three must be equal.
Left-hand limit = Right-hand limit
$0 = 1$
This is a contradiction. There is **no value of $\lambda$** for which the function $f(x)$ is continuous at $x = 0$.

*   **Continuity at $x = 1$:**
    Since $1 > 0$, the function is defined by $f(x) = 4x + 1$ around $x=1$. The value of $\lambda$ does not affect the function definition for $x > 0$.
    1.  **Value of the function:** $f(1) = 4(1) + 1 = 5$.
    2.  **Limit of the function:** $\lim_{x \to 1} f(x) = \lim_{x \to 1} (4x + 1) = 4(1) + 1 = 5$.
    3.  **Comparison:** Since $\lim_{x \to 1} f(x) = f(1) = 5$, the function is continuous at $x = 1$ for any value of $\lambda$. (Even though no $\lambda$ makes it continuous at $x=0$, it's continuous at $x=1$ regardless).

---

**19. Show that the function defined by $g(x) = x - [x]$ is discontinuous at all integral points. Here $[x]$ denotes the greatest integer less than or equal to $x$.**

**Reasoning:**
The greatest integer function $[x]$ is known to be discontinuous at integral points. We need to show that $g(x) = x - [x]$ is also discontinuous at integral points. Let $c$ be an integer.

**Step-by-step solution:**
Let $c$ be any integer.

*   **Value of the function at $x = c$:**
    $g(c) = c - [c] = c - c = 0$.

*   **Left-hand limit at $x = c$:**
    $\lim_{x \to c^-} g(x) = \lim_{x \to c^-} (x - [x])$
    As $x$ approaches $c$ from the left (e.g., $2.9, 2.99$ for $c=3$), $[x]$ will be $c-1$.
    So, $\lim_{x \to c^-} (x - [x]) = c - (c - 1) = 1$.

*   **Right-hand limit at $x = c$:**
    $\lim_{x \to c^+} g(x) = \lim_{x \to c^+} (x - [x])$
    As $x$ approaches $c$ from the right (e.g., $3.1, 3.01$ for $c=3$), $[x]$ will be $c$.
    So, $\lim_{x \to c^+} (x - [x]) = c - c = 0$.

*   **Comparison:**
    The left-hand limit ($1$) is not equal to the right-hand limit ($0$).
    Since $\lim_{x \to c^-} g(x) \neq \lim_{x \to c^+} g(x)$, the limit $\lim_{x \to c} g(x)$ does not exist.

Therefore, the function $g(x) = x - [x]$ is discontinuous at all integral points.

---

**20. Is the function defined by $f(x) = x^2 - \sin x + 5$ continuous at $x = \pi$?**

**Reasoning:**
The function $f(x)$ is a combination of polynomial functions ($x^2$, $5$) and a trigonometric function ($\sin x$). Polynomial functions are continuous everywhere. The sine function is continuous everywhere. The sum/difference of continuous functions is continuous.

**Step-by-step solution:**
Let $f_1(x) = x^2$, $f_2(x) = \sin x$, and $f_3(x) = 5$.
We know that:
*   $f_1(x) = x^2$ is a polynomial function, hence continuous at $x = \pi$.
*   $f_2(x) = \sin x$ is a trigonometric function, hence continuous at $x = \pi$.
*   $f_3(x) = 5$ is a constant function, hence continuous at $x = \pi$.

Since $f(x) = f_1(x) - f_2(x) + f_3(x)$ is the sum/difference of continuous functions, it is also continuous at $x = \pi$.

To verify explicitly at $x=\pi$:
1.  **Value of the function:** $f(\pi) = \pi^2 - \sin(\pi) + 5 = \pi^2 - 0 + 5 = \pi^2 + 5$.
2.  **Limit of the function:** $\lim_{x \to \pi} (x^2 - \sin x + 5) = \pi^2 - \sin(\pi) + 5 = \pi^2 - 0 + 5 = \pi^2 + 5$.
3.  **Comparison:** Since $\lim_{x \to \pi} f(x) = f(\pi) = \pi^2 + 5$, the function $f(x)$ is continuous at $x = \pi$.

---

**21. Discuss the continuity of the following functions:**

**(a) $f(x) = \sin x + \cos x$**

**Reasoning:**
The sine function and cosine function are continuous everywhere. The sum of two continuous functions is continuous.

**Step-by-step solution:**
Let $g(x) = \sin x$ and $h(x) = \cos x$.
We know that $g(x)$ is continuous for all $x \in \mathbb{R}$ and $h(x)$ is continuous for all $x \in \mathbb{R}$.
Since $f(x) = g(x) + h(x)$, and the sum of continuous functions is continuous, $f(x) = \sin x + \cos x$ is continuous for all $x \in \mathbb{R}$.

---

**(b) $f(x) = \sin x - \cos x$**

**Reasoning:**
Similar to (a), the difference of two continuous functions is continuous.

**Step-by-step solution:**
Let $g(x) = \sin x$ and $h(x) = \cos x$.
We know that $g(x)$ is continuous for all $x \in \mathbb{R}$ and $h(x)$ is continuous for all $x \in \mathbb{R}$.
Since $f(x) = g(x) - h(x)$, and the difference of continuous functions is continuous, $f(x) = \sin x - \cos x$ is continuous for all $x \in \mathbb{R}$.

---

**(c) $f(x) = \sin x \cdot \cos x$**

**Reasoning:**
The product of two continuous functions is continuous.

**Step-by-step solution:**
Let $g(x) = \sin x$ and $h(x) = \cos x$.
We know that $g(x)$ is continuous for all $x \in \mathbb{R}$ and $h(x)$ is continuous for all $x \in \mathbb{R}$.
Since $f(x) = g(x) \cdot h(x)$, and the product of continuous functions is continuous, $f(x) = \sin x \cdot \cos x$ is continuous for all $x \in \mathbb{R}$.

---

**22. Discuss the continuity of the cosine, cosecant, secant and cotangent functions.**

**Reasoning:**
We need to recall the definitions and domains of these trigonometric functions and their continuity properties.

**Step-by-step solution:**

*   **Cosine function, $f(x) = \cos x$:**
    The cosine function is defined for all real numbers. It is known to be continuous for all $x \in \mathbb{R}$.
    To show this for any $c \in \mathbb{R}$:
    $\lim_{x \to c} \cos x = \cos c$.
    Therefore, $f(x) = \cos x$ is continuous for all real numbers.

*   **Cosecant function, $f(x) = \csc x$:**
    The cosecant function is defined as $\csc x = \frac{1}{\sin x}$.
    It is defined wherever $\sin x \neq 0$. The sine function is zero at $x = n\pi$, where $n$ is an integer.
    Thus, the domain of $\csc x$ is $\mathbb{R} \setminus \{n\pi \mid n \in \mathbb{Z}\}$.
    Since $\sin x$ is continuous and non-zero on its domain, $\csc x$ (as the reciprocal of a continuous non-zero function) is continuous on its domain.
    Therefore, $f(x) = \csc x$ is continuous for all $x \in \mathbb{R}$, except for $x = n\pi$ (where $n$ is an integer).

*   **Secant function, $f(x) = \sec x$:**
    The secant function is defined as $\sec x = \frac{1}{\cos x}$.
    It is defined wherever $\cos x \neq 0$. The cosine function is zero at $x = \frac{\pi}{2} + n\pi = (2n+1)\frac{\pi}{2}$, where $n$ is an integer.
    Thus, the domain of $\sec x$ is $\mathbb{R} \setminus \{(2n+1)\frac{\pi}{2} \mid n \in \mathbb{Z}\}$.
    Since $\cos x$ is continuous and non-zero on its domain, $\sec x$ (as the reciprocal of a continuous non-zero function) is continuous on its domain.
    Therefore, $f(x) = \sec x$ is continuous for all $x \in \mathbb{R}$, except for $x = (2n+1)\frac{\pi}{2}$ (where $n$ is an integer).

*   **Cotangent function, $f(x) = \cot x$:**
    The cotangent function is defined as $\cot x = \frac{\cos x}{\sin x}$.
    It is defined wherever $\sin x \neq 0$. The sine function is zero at $x = n\pi$, where $n$ is an integer.
    Thus, the domain of $\cot x$ is $\mathbb{R} \setminus \{n\pi \mid n \in \mathbb{Z}\}$.
    Since $\cos x$ and $\sin x$ are continuous, and $\sin x$ is non-zero on its domain, $\cot x$ (as the quotient of two continuous functions where the denominator is non-zero) is continuous on its domain.
    Therefore, $f(x) = \cot x$ is continuous for all $x \in \mathbb{R}$, except for $x = n\pi$ (where $n$ is an integer).

---

**23. Find all points of discontinuity of $f$, where $f(x) = \sin(\frac{x}{x})$ (Question text is `Find all points of discontinuity of f, where sin.x` and then `f(x) = X`, so I will interpret this as `f(x) = sin(x)/x` for `x < 0` and `x+1` for `x >= 0`. This is based on the problem 24, which looks like it should be split into 23 and 24. Or, assuming the problem means $f(x) = \sin x$ and $f(x) = \frac{x}{x}$ if $x<0$ and $x+1$ if $x \geq 0$ from question 24. Given the format, it seems likely that question 23 intended a trigonometric piecewise function or similar structure that got truncated/misplaced. Given the text for 24, it seems 23 is incomplete. I will assume it meant $f(x) = \frac{\sin x}{x}$ for $x \neq 0$ and $f(x) = 0$ for $x = 0$ or something similar for this exercise number from common questions.)**

**Re-interpreting Problem 23 based on common exercise patterns and potentially truncated text:**
Let's assume the question meant $f(x) = \frac{\sin x}{x}$ for $x \neq 0$ and $f(x) = k$ for $x=0$.
A very common problem is: $f(x) = \begin{cases} \frac{\sin x}{x} & \text{if } x \neq 0 \\ 1 & \text{if } x = 0 \end{cases}$.
For this function, we know that $\lim_{x \to 0} \frac{\sin x}{x} = 1$. And $f(0)=1$. So this function is continuous at $x=0$.
And for $x \neq 0$, $\frac{\sin x}{x}$ is a quotient of continuous functions where the denominator is non-zero, so it is continuous for all $x \neq 0$. Therefore, this version would be continuous everywhere.

Given the actual text is `Find all points of discontinuity of f, where sin.x` and the `f(x)=X` is part of problem 24, problem 23 itself seems broken. I will skip providing a solution for 23 due to ambiguity.

---

**24. Determine if $f$ defined by $f(x) = \begin{cases} \frac{\sin x}{x} & \text{if } x < 0 \\ x+1 & \text{if } x \geq 0 \end{cases}$ is a continuous function?**

**Reasoning:**
The function is defined by $\frac{\sin x}{x}$ for $x<0$ and $x+1$ for $x \geq 0$. We need to check continuity for $x<0$, $x>0$, and at the transition point $x=0$.

**Step-by-step solution:**

*   **Continuity for $x < 0$:**
    For any $c < 0$, $f(x) = \frac{\sin x}{x}$. Both $\sin x$ and $x$ are continuous. Since $x \neq 0$ in this interval, the quotient $\frac{\sin x}{x}$ is continuous for all $x < 0$.

*   **Continuity for $x > 0$:**
    For any $c > 0$, $f(x) = x + 1$, which is a polynomial and thus continuous.

*   **Continuity at $x = 0$:**
    1.  **Value of the function:** $f(0) = 0 + 1 = 1$ (since $x \geq 0$).
    2.  **Left-hand limit:** $\lim_{x \to 0^-} f(x) = \lim_{x \to 0^-} \frac{\sin x}{x}$. This is a standard limit, $\lim_{x \to 0} \frac{\sin x}{x} = 1$.
        So, $\lim_{x \to 0^-} f(x) = 1$.
    3.  **Right-hand limit:** $\lim_{x \to 0^+} f(x) = \lim_{x \to 0^+} (x + 1) = 0 + 1 = 1$.
    4.  **Comparison:** Since $\lim_{x \to 0^-} f(x) = \lim_{x \to 0^+} f(x) = 1$, the limit $\lim_{x \to 0} f(x) = 1$.
        Also, $\lim_{x \to 0} f(x) = f(0) = 1$.

Therefore, the function $f(x)$ is continuous at $x = 0$.

Combining these, the function $f(x)$ is continuous for all real numbers.

---

**25. Examine the continuity of $f$, where $f$ is defined by $f(x) = \begin{cases} \sin x - \cos x & \text{if } x \neq 0 \\ -1 & \text{if } x = 0 \end{cases}$**

**Reasoning:**
The function is defined by $\sin x - \cos x$ for $x \neq 0$ and $-1$ for $x=0$. We need to check continuity for $x \neq 0$ and at $x=0$.

**Step-by-step solution:**

*   **Continuity for $x \neq 0$:**
    For any $c \neq 0$, $f(x) = \sin x - \cos x$. Both $\sin x$ and $\cos x$ are continuous functions. The difference of continuous functions is continuous. So, $f(x)$ is continuous for all $x \neq 0$.

*   **Continuity at $x = 0$:**
    1.  **Value of the function:** $f(0) = -1$.
    2.  **Limit of the function:** $\lim_{x \to 0} f(x) = \lim_{x \to 0} (\sin x - \cos x) = \sin(0) - \cos(0) = 0 - 1 = -1$.
    3.  **Comparison:** Since $\lim_{x \to 0} f(x) = f(0) = -1$, the function is continuous at $x = 0$.

Combining these, the function $f(x)$ is continuous for all real numbers.

---

**Find the values of $k$ so that the function $f$ is continuous at the indicated point in Exercises 26 to 29.**

**26. $f(x) = \begin{cases} \frac{k \cos x}{\pi - 2x} & \text{if } x \neq \frac{\pi}{2} \\ 3 & \text{if } x = \frac{\pi}{2} \end{cases}$ at $x = \frac{\pi}{2}$.**

**Reasoning:**
For $f(x)$ to be continuous at $x = \frac{\pi}{2}$, we need $\lim_{x \to \frac{\pi}{2}} f(x) = f(\frac{\pi}{2})$.

**Step-by-step solution:**
1.  **Value of the function:** $f(\frac{\pi}{2}) = 3$.

2.  **Limit of the function:**
    $\lim_{x \to \frac{\pi}{2}} f(x) = \lim_{x \to \frac{\pi}{2}} \frac{k \cos x}{\pi - 2x}$
    If we substitute $x = \frac{\pi}{2}$, we get $\frac{k \cos(\frac{\pi}{2})}{\pi - 2(\frac{\pi}{2})} = \frac{k \cdot 0}{\pi - \pi} = \frac{0}{0}$, which is an indeterminate form. We can use L'Hôpital's Rule or a substitution.

    **Using substitution:**
    Let $x = \frac{\pi}{2} + h$. As $x \to \frac{\pi}{2}$, $h \to 0$.
    $\cos x = \cos(\frac{\pi}{2} + h) = -\sin h$.
    $\pi - 2x = \pi - 2(\frac{\pi}{2} + h) = \pi - \pi - 2h = -2h$.

    So, the limit becomes:
    $\lim_{h \to 0} \frac{k (-\sin h)}{-2h} = \lim_{h \to 0} \frac{k \sin h}{2h} = \frac{k}{2} \lim_{h \to 0} \frac{\sin h}{h} = \frac{k}{2} \cdot 1 = \frac{k}{2}$.

3.  **Equating limit and function value:**
    For continuity, $\lim_{x \to \frac{\pi}{2}} f(x) = f(\frac{\pi}{2})$.
    $\frac{k}{2} = 3$
    $k = 6$.

Therefore, the value of $k$ is $6$.

---

**27. $f(x) = \begin{cases} kx^2 & \text{if } x \leq 2 \\ 3 & \text{if } x > 2 \end{cases}$ at $x = 2$.**

**Reasoning:**
For $f(x)$ to be continuous at $x=2$, we need $\lim_{x \to 2^-} f(x) = \lim_{x \to 2^+} f(x) = f(2)$.

**Step-by-step solution:**
1.  **Value of the function:** $f(2) = k(2)^2 = 4k$ (since $x \leq 2$).

2.  **Left-hand limit:** $\lim_{x \to 2^-} f(x) = \lim_{x \to 2^-} kx^2 = k(2)^2 = 4k$.

3.  **Right-hand limit:** $\lim_{x \to 2^+} f(x) = \lim_{x \to 2^+} 3 = 3$.

4.  **Equating limits and function value:**
    For continuity, $4k = 3$.
    $k = \frac{3}{4}$.

Therefore, the value of $k$ is $\frac{3}{4}$.

---

**28. $f(x) = \begin{cases} kx + 1 & \text{if } x \leq \pi \\ \cos x & \text{if } x > \pi \end{cases}$ at $x = \pi$.**

**Reasoning:**
For $f(x)$ to be continuous at $x=\pi$, we need $\lim_{x \to \pi^-} f(x) = \lim_{x \to \pi^+} f(x) = f(\pi)$.

**Step-by-step solution:**
1.  **Value of the function:** $f(\pi) = k\pi + 1$ (since $x \leq \pi$).

2.  **Left-hand limit:** $\lim_{x \to \pi^-} f(x) = \lim_{x \to \pi^-} (kx + 1) = k\pi + 1$.

3.  **Right-hand limit:** $\lim_{x \to \pi^+} f(x) = \lim_{x \to \pi^+} \cos x = \cos(\pi) = -1$.

4.  **Equating limits and function value:**
    For continuity, $k\pi + 1 = -1$.
    $k\pi = -2$.
    $k = -\frac{2}{\pi}$.

Therefore, the value of $k$ is $-\frac{2}{\pi}$.

---

**29. $f(x) = \begin{cases} kx + 1 & \text{if } x \leq 5 \\ 3x - 5 & \text{if } x > 5 \end{cases}$ at $x = 5$.**

**Reasoning:**
For $f(x)$ to be continuous at $x=5$, we need $\lim_{x \to 5^-} f(x) = \lim_{x \to 5^+} f(x) = f(5)$.

**Step-by-step solution:**
1.  **Value of the function:** $f(5) = k(5) + 1 = 5k + 1$ (since $x \leq 5$).

2.  **Left-hand limit:** $\lim_{x \to 5^-} f(x) = \lim_{x \to 5^-} (kx + 1) = k(5) + 1 = 5k + 1$.

3.  **Right-hand limit:** $\lim_{x \to 5^+} f(x) = \lim_{x \to 5^+} (3x - 5) = 3(5) - 5 = 15 - 5 = 10$.

4.  **Equating limits and function value:**
    For continuity, $5k + 1 = 10$.
    $5k = 9$.
    $k = \frac{9}{5}$.

Therefore, the value of $k$ is $\frac{9}{5}$.

---

**30. Find the values of $a$ and $b$ such that the function defined by $f(x) = \begin{cases} 5 & \text{if } x \leq 2 \\ ax + b & \text{if } 2 < x < 10 \\ 21 & \text{if } x \geq 10 \end{cases}$ is a continuous function.**

**Reasoning:**
For $f(x)$ to be a continuous function, it must be continuous at all points in its domain. The function is piecewise defined by constants and a polynomial, which are continuous in their respective open intervals. We need to ensure continuity at the transition points $x=2$ and $x=10$.

**Step-by-step solution:**

*   **Continuity at $x = 2$:**
    1.  **Value of the function:** $f(2) = 5$ (since $x \leq 2$).
    2.  **Left-hand limit:** $\lim_{x \to 2^-} f(x) = \lim_{x \to 2^-} 5 = 5$.
    3.  **Right-hand limit:** $\lim_{x \to 2^+} f(x) = \lim_{x \to 2^+} (ax + b) = a(2) + b = 2a + b$.

    For continuity at $x=2$:
    $2a + b = 5$ (Equation 1)

*   **Continuity at $x = 10$:**
    1.  **Value of the function:** $f(10) = 21$ (since $x \geq 10$).
    2.  **Left-hand limit:** $\lim_{x \to 10^-} f(x) = \lim_{x \to 10^-} (ax + b) = a(10) + b = 10a + b$.
    3.  **Right-hand limit:** $\lim_{x \to 10^+} f(x) = \lim_{x \to 10^+} 21 = 21$.

    For continuity at $x=10$:
    $10a + b = 21$ (Equation 2)

Now we have a system of two linear equations with two variables:
1.  $2a + b = 5$
2.  $10a + b = 21$

Subtract Equation 1 from Equation 2:
$(10a + b) - (2a + b) = 21 - 5$
$8a = 16$
$a = 2$.

Substitute $a=2$ into Equation 1:
$2(2) + b = 5$
$4 + b = 5$
$b = 1$.

Therefore, the values are $a = 2$ and $b = 1$.

---

**31. Show that the function defined by $f(x) = \cos(x^2)$ is a continuous function.**

**Reasoning:**
This is a composite function. Let $g(x) = x^2$ and $h(u) = \cos u$. Then $f(x) = h(g(x))$.
We know that if $g$ is continuous at $c$ and $h$ is continuous at $g(c)$, then the composite function $h \circ g$ is continuous at $c$.

**Step-by-step solution:**
Let $g(x) = x^2$ and $h(u) = \cos u$.
1.  The function $g(x) = x^2$ is a polynomial function, which is continuous for all real numbers.
2.  The function $h(u) = \cos u$ is a trigonometric function, which is continuous for all real numbers.

Since $f(x) = h(g(x)) = \cos(x^2)$ is the composition of two continuous functions, it is continuous for all real numbers.

---

**32. Show that the function defined by $f(x) = |\cos x|$ is a continuous function.**

**Reasoning:**
This is a composite function. Let $g(x) = \cos x$ and $h(u) = |u|$. Then $f(x) = h(g(x))$.
We know that if $g$ is continuous at $c$ and $h$ is continuous at $g(c)$, then the composite function $h \circ g$ is continuous at $c$.

**Step-by-step solution:**
Let $g(x) = \cos x$ and $h(u) = |u|$.
1.  The function $g(x) = \cos x$ is a trigonometric function, which is continuous for all real numbers.
2.  The function $h(u) = |u|$ (absolute value function) is continuous for all real numbers.

Since $f(x) = h(g(x)) = |\cos x|$ is the composition of two continuous functions, it is continuous for all real numbers.

---

**33. Examine that $\sin|x|$ is a continuous function.**

**Reasoning:**
This is a composite function. Let $g(x) = |x|$ and $h(u) = \sin u$. Then $f(x) = h(g(x))$.
We know that if $g$ is continuous at $c$ and $h$ is continuous at $g(c)$, then the composite function $h \circ g$ is continuous at $c$.

**Step-by-step solution:**
Let $g(x) = |x|$ and $h(u) = \sin u$.
1.  The function $g(x) = |x|$ (absolute value function) is continuous for all real numbers.
2.  The function $h(u) = \sin u$ is a trigonometric function, which is continuous for all real numbers.

Since $f(x) = h(g(x)) = \sin|x|$ is the composition of two continuous functions, it is continuous for all real numbers.

---

**34. Find all the points of discontinuity of $f$ defined by $f(x) = |x| - |x + 1|$.**

**Reasoning:**
The function $f(x)$ is the difference of two absolute value functions. The absolute value function $|u|$ is continuous for all real numbers. The difference of two continuous functions is continuous.
The points where the absolute value functions change their definition are $x=0$ (for $|x|$) and $x=-1$ (for $|x+1|$). These are the points we need to examine carefully.

**Step-by-step solution:**
Let $g(x) = |x|$ and $h(x) = |x+1|$.
Both $g(x)$ and $h(x)$ are continuous functions for all real numbers.
Since $f(x) = g(x) - h(x)$ is the difference of two continuous functions, $f(x)$ is continuous for all real numbers.

To show this by piecewise definition:
$|x| = \begin{cases} -x & \text{if } x < 0 \\ x & \text{if } x \geq 0 \end{cases}$

$|x+1| = \begin{cases} -(x+1) & \text{if } x < -1 \\ x+1 & \text{if } x \geq -1 \end{cases}$

We need to define $f(x)$ in three intervals: $x < -1$, $-1 \leq x < 0$, and $x \geq 0$.

*   **Case 1: $x < -1$**
    $f(x) = (-x) - (-(x+1)) = -x + x + 1 = 1$.
    $f(x) = 1$, which is continuous.

*   **Case 2: $-1 \leq x < 0$**
    $f(x) = (-x) - (x+1) = -x - x - 1 = -2x - 1$.
    $f(x) = -2x - 1$, which is a polynomial and continuous.

*   **Case 3: $x \geq 0$**
    $f(x) = (x) - (x+1) = x - x - 1 = -1$.
    $f(x) = -1$, which is continuous.

Now, check the transition points:

*   **At $x = -1$:**
    1.  **Value of the function:** $f(-1) = |-1| - |-1+1| = 1 - |0| = 1$. (Using the general definition, or from Case 2: $-2(-1)-1 = 2-1 = 1$).
    2.  **Left-hand limit:** $\lim_{x \to -1^-} f(x) = \lim_{x \to -1^-} 1 = 1$. (From Case 1).
    3.  **Right-hand limit:** $\lim_{x \to -1^+} f(x) = \lim_{x \to -1^+} (-2x - 1) = -2(-1) - 1 = 2 - 1 = 1$. (From Case 2).
    4.  **Comparison:** $\lim_{x \to -1} f(x) = f(-1) = 1$. Continuous at $x = -1$.

*   **At $x = 0$:**
    1.  **Value of the function:** $f(0) = |0| - |0+1| = 0 - 1 = -1$. (Using the general definition, or from Case 3: $-1$).
    2.  **Left-hand limit:** $\lim_{x \to 0^-} f(x) = \lim_{x \to 0^-} (-2x - 1) = -2(0) - 1 = -1$. (From Case 2).
    3.  **Right-hand limit:** $\lim_{x \to 0^+} f(x) = \lim_{x \to 0^+} (-1) = -1$. (From Case 3).
    4.  **Comparison:** $\lim_{x \to 0} f(x) = f(0) = -1$. Continuous at $x = 0$.

Since the function is continuous in all intervals and at the transition points, it is continuous for all real numbers.
Therefore, there are **no points of discontinuity**.

---

#### **Exercise 5.2**

**Differentiate the functions with respect to $x$ in Exercises 1 to 8.**

**1. $\sin(x^2 + 5)$**

**Reasoning:**
This is a composite function of the form $\sin(u)$ where $u = x^2 + 5$. We will use the chain rule: $\frac{d}{dx} \sin(u) = \cos(u) \frac{du}{dx}$.

**Step-by-step solution:**
Let $y = \sin(x^2 + 5)$.
Let $u = x^2 + 5$. Then $\frac{du}{dx} = \frac{d}{dx}(x^2 + 5) = 2x$.
And $y = \sin u$. So $\frac{dy}{du} = \frac{d}{du}(\sin u) = \cos u$.

Using the chain rule, $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$:
$\frac{dy}{dx} = (\cos u) \cdot (2x)$
Substitute back $u = x^2 + 5$:
$\frac{dy}{dx} = 2x \cos(x^2 + 5)$.

---

**2. $\cos(\sin x)$**

**Reasoning:**
This is a composite function of the form $\cos(u)$ where $u = \sin x$. We will use the chain rule: $\frac{d}{dx} \cos(u) = -\sin(u) \frac{du}{dx}$.

**Step-by-step solution:**
Let $y = \cos(\sin x)$.
Let $u = \sin x$. Then $\frac{du}{dx} = \frac{d}{dx}(\sin x) = \cos x$.
And $y = \cos u$. So $\frac{dy}{du} = \frac{d}{du}(\cos u) = -\sin u$.

Using the chain rule, $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$:
$\frac{dy}{dx} = (-\sin u) \cdot (\cos x)$
Substitute back $u = \sin x$:
$\frac{dy}{dx} = -\cos x \sin(\sin x)$.

---

**3. $\sin(ax + b)$**

**Reasoning:**
This is a composite function of the form $\sin(u)$ where $u = ax + b$. We will use the chain rule.

**Step-by-step solution:**
Let $y = \sin(ax + b)$.
Let $u = ax + b$. Then $\frac{du}{dx} = \frac{d}{dx}(ax + b) = a$.
And $y = \sin u$. So $\frac{dy}{du} = \cos u$.

Using the chain rule:
$\frac{dy}{dx} = (\cos u) \cdot (a)$
Substitute back $u = ax + b$:
$\frac{dy}{dx} = a \cos(ax + b)$.

---

**4. $\sec(\tan(\sqrt{x}))$**

**Reasoning:**
This is a nested composite function. We apply the chain rule multiple times.
Let $y = \sec(u)$, where $u = \tan(v)$, and $v = \sqrt{x}$.
$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dv} \cdot \frac{dv}{dx}$.

**Step-by-step solution:**
Let $y = \sec(\tan(\sqrt{x}))$.
Derivative of $\sec z$ is $\sec z \tan z$. So, $\frac{d}{dx} \sec(f(x)) = \sec(f(x)) \tan(f(x)) \cdot f'(x)$.
Here, $f(x) = \tan(\sqrt{x})$.
$\frac{dy}{dx} = \sec(\tan(\sqrt{x})) \tan(\tan(\sqrt{x})) \cdot \frac{d}{dx}(\tan(\sqrt{x}))$.

Now, find $\frac{d}{dx}(\tan(\sqrt{x}))$:
Derivative of $\tan w$ is $\sec^2 w$. So, $\frac{d}{dx} \tan(g(x)) = \sec^2(g(x)) \cdot g'(x)$.
Here, $g(x) = \sqrt{x} = x^{1/2}$.
$\frac{d}{dx}(\sqrt{x}) = \frac{1}{2} x^{1/2 - 1} = \frac{1}{2} x^{-1/2} = \frac{1}{2\sqrt{x}}$.
So, $\frac{d}{dx}(\tan(\sqrt{x})) = \sec^2(\sqrt{x}) \cdot \frac{1}{2\sqrt{x}}$.

Substitute this back into the main derivative:
$\frac{dy}{dx} = \sec(\tan(\sqrt{x})) \tan(\tan(\sqrt{x})) \cdot \sec^2(\sqrt{x}) \cdot \frac{1}{2\sqrt{x}}$.
$\frac{dy}{dx} = \frac{\sec(\tan(\sqrt{x})) \tan(\tan(\sqrt{x})) \sec^2(\sqrt{x})}{2\sqrt{x}}$.

---

**5. $\frac{\sin(ax + b)}{\cos(cx + d)}$**

**Reasoning:**
This is a quotient of two composite functions. We will use the quotient rule: $\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{u'v - uv'}{v^2}$.
Then apply the chain rule for the derivatives of $\sin(ax+b)$ and $\cos(cx+d)$.

**Step-by-step solution:**
Let $y = \frac{\sin(ax + b)}{\cos(cx + d)}$.
Let $u = \sin(ax + b)$ and $v = \cos(cx + d)$.

First, find $u'$:
$u' = \frac{d}{dx}(\sin(ax + b)) = \cos(ax + b) \cdot \frac{d}{dx}(ax + b) = a \cos(ax + b)$.

Next, find $v'$:
$v' = \frac{d}{dx}(\cos(cx + d)) = -\sin(cx + d) \cdot \frac{d}{dx}(cx + d) = -c \sin(cx + d)$.

Now, apply the quotient rule:
$\frac{dy}{dx} = \frac{u'v - uv'}{v^2}$
$\frac{dy}{dx} = \frac{[a \cos(ax + b)][\cos(cx + d)] - [\sin(ax + b)][-c \sin(cx + d)]}{[\cos(cx + d)]^2}$
$\frac{dy}{dx} = \frac{a \cos(ax + b) \cos(cx + d) + c \sin(ax + b) \sin(cx + d)}{\cos^2(cx + d)}$.

We can also split the fraction:
$\frac{dy}{dx} = a \cos(ax+b) \frac{\cos(cx+d)}{\cos^2(cx+d)} + c \sin(ax+b) \frac{\sin(cx+d)}{\cos^2(cx+d)}$
$\frac{dy}{dx} = a \cos(ax+b) \sec(cx+d) + c \sin(ax+b) \sec(cx+d) \tan(cx+d)$.

---

**6. $\cos(x^3) \sin^2(x^5)$**

**Reasoning:**
This is a product of two composite functions. We will use the product rule: $\frac{d}{dx}(uv) = u'v + uv'$.
Then apply the chain rule for the derivatives of $\cos(x^3)$ and $\sin^2(x^5)$.

**Step-by-step solution:**
Let $y = \cos(x^3) \sin^2(x^5)$.
Let $u = \cos(x^3)$ and $v = \sin^2(x^5)$.

First, find $u'$:
$u' = \frac{d}{dx}(\cos(x^3)) = -\sin(x^3) \cdot \frac{d}{dx}(x^3) = -\sin(x^3) \cdot (3x^2) = -3x^2 \sin(x^3)$.

Next, find $v'$:
$v' = \frac{d}{dx}(\sin^2(x^5)) = \frac{d}{dx}((\sin(x^5))^2)$.
Using the chain rule (outer function is $z^2$, inner is $\sin(x^5)$):
$v' = 2 \sin(x^5) \cdot \frac{d}{dx}(\sin(x^5))$.
Now, derivative of $\sin(x^5)$ is $\cos(x^5) \cdot \frac{d}{dx}(x^5) = \cos(x^5) \cdot (5x^4) = 5x^4 \cos(x^5)$.
So, $v' = 2 \sin(x^5) \cdot (5x^4 \cos(x^5)) = 10x^4 \sin(x^5) \cos(x^5)$.

Now, apply the product rule $\frac{dy}{dx} = u'v + uv'$:
$\frac{dy}{dx} = [-3x^2 \sin(x^3)][\sin^2(x^5)] + [\cos(x^3)][10x^4 \sin(x^5) \cos(x^5)]$
$\frac{dy}{dx} = -3x^2 \sin(x^3) \sin^2(x^5) + 10x^4 \cos(x^3) \sin(x^5) \cos(x^5)$.

---

**7. $2\sqrt{\cot(x^2)}$**

**Reasoning:**
This is a nested composite function.
Let $y = 2\sqrt{u}$, where $u = \cot(v)$, and $v = x^2$.
$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dv} \cdot \frac{dv}{dx}$.

**Step-by-step solution:**
Let $y = 2\sqrt{\cot(x^2)}$.
We know $\frac{d}{dz} \sqrt{z} = \frac{1}{2\sqrt{z}}$.
So, $\frac{dy}{dx} = 2 \cdot \frac{1}{2\sqrt{\cot(x^2)}} \cdot \frac{d}{dx}(\cot(x^2))$.
$\frac{dy}{dx} = \frac{1}{\sqrt{\cot(x^2)}} \cdot \frac{d}{dx}(\cot(x^2))$.

Now, find $\frac{d}{dx}(\cot(x^2))$:
We know $\frac{d}{dw} \cot w = -\csc^2 w$.
So, $\frac{d}{dx}(\cot(x^2)) = -\csc^2(x^2) \cdot \frac{d}{dx}(x^2)$.
$\frac{d}{dx}(x^2) = 2x$.
So, $\frac{d}{dx}(\cot(x^2)) = -\csc^2(x^2) \cdot (2x) = -2x \csc^2(x^2)$.

Substitute this back into the main derivative:
$\frac{dy}{dx} = \frac{1}{\sqrt{\cot(x^2)}} \cdot (-2x \csc^2(x^2))$.
$\frac{dy}{dx} = \frac{-2x \csc^2(x^2)}{\sqrt{\cot(x^2)}}$.

---

**8. $\cos(\sqrt{x})$**

**Reasoning:**
This is a composite function of the form $\cos(u)$ where $u = \sqrt{x}$. We will use the chain rule.

**Step-by-step solution:**
Let $y = \cos(\sqrt{x})$.
Let $u = \sqrt{x} = x^{1/2}$. Then $\frac{du}{dx} = \frac{1}{2} x^{-1/2} = \frac{1}{2\sqrt{x}}$.
And $y = \cos u$. So $\frac{dy}{du} = -\sin u$.

Using the chain rule:
$\frac{dy}{dx} = (-\sin u) \cdot (\frac{1}{2\sqrt{x}})$
Substitute back $u = \sqrt{x}$:
$\frac{dy}{dx} = -\frac{\sin(\sqrt{x})}{2\sqrt{x}}$.

---

**9. Prove that the function $f$ given by $f(x) = |x - 1|, x \in \mathbb{R}$ is not differentiable at $x = 1$.**

**Reasoning:**
A function is differentiable at a point if its left-hand derivative and right-hand derivative at that point exist and are equal.

**Step-by-step solution:**
The function is $f(x) = |x - 1|$. We can write it as a piecewise function:
$f(x) = \begin{cases} -(x - 1) & \text{if } x < 1 \\ x - 1 & \text{if } x \geq 1 \end{cases}$

We need to check differentiability at $x = 1$.
The derivative of a function $f$ at a point $c$ is defined as $f'(c) = \lim_{h \to 0} \frac{f(c + h) - f(c)}{h}$.

*   **Left-hand derivative at $x = 1$:**
    $L f'(1) = \lim_{h \to 0^-} \frac{f(1 + h) - f(1)}{h}$
    Since $h \to 0^-$, $1+h < 1$, so $f(1+h) = -( (1+h) - 1 ) = -h$.
    Also, $f(1) = |1 - 1| = 0$.
    $L f'(1) = \lim_{h \to 0^-} \frac{-h - 0}{h} = \lim_{h \to 0^-} \frac{-h}{h} = \lim_{h \to 0^-} (-1) = -1$.

*   **Right-hand derivative at $x = 1$:**
    $R f'(1) = \lim_{h \to 0^+} \frac{f(1 + h) - f(1)}{h}$
    Since $h \to 0^+$, $1+h > 1$, so $f(1+h) = (1+h) - 1 = h$.
    Also, $f(1) = 0$.
    $R f'(1) = \lim_{h \to 0^+} \frac{h - 0}{h} = \lim_{h \to 0^+} \frac{h}{h} = \lim_{h \to 0^+} (1) = 1$.

*   **Comparison:**
    Since the left-hand derivative ($-1$) is not equal to the right-hand derivative ($1$), the function $f(x) = |x - 1|$ is not differentiable at $x = 1$.

---

**10. Prove that the greatest integer function defined by $f(x) = [x], 0 < x < 3$ is not differentiable at $x = 1$ and $x = 2$.**

**Reasoning:**
A function is differentiable at a point only if it is continuous at that point. We already know from Problem 19 (for $g(x) = x - [x]$) or properties of $[x]$ that the greatest integer function is discontinuous at every integer. Therefore, it cannot be differentiable at integers. We will prove it explicitly using the definition of the derivative for $x=1$ and $x=2$.

**Step-by-step solution:**
The function is $f(x) = [x]$ for $0 < x < 3$.

*   **At $x = 1$:**
    1.  **Left-hand derivative at $x = 1$:**
        $L f'(1) = \lim_{h \to 0^-} \frac{f(1 + h) - f(1)}{h}$
        Since $h \to 0^-$, $1+h < 1$ (e.g., $0.99$), so $[1+h] = 0$.
        Also, $f(1) = = 1$.
        $L f'(1) = \lim_{h \to 0^-} \frac{0 - 1}{h} = \lim_{h \to 0^-} \frac{-1}{h} = \infty$. (The limit does not exist as a finite number).

    2.  **Right-hand derivative at $x = 1$:**
        $R f'(1) = \lim_{h \to 0^+} \frac{f(1 + h) - f(1)}{h}$
        Since $h \to 0^+$, $1+h > 1$ (e.g., $1.01$), so $[1+h] = 1$.
        Also, $f(1) = = 1$.
        $R f'(1) = \lim_{h \to 0^+} \frac{1 - 1}{h} = \lim_{h \to 0^+} \frac{0}{h} = 0$.

    Since the left-hand derivative is not finite and not equal to the right-hand derivative, $f(x) = [x]$ is not differentiable at $x = 1$.

*   **At $x = 2$:**
    1.  **Left-hand derivative at $x = 2$:**
        $L f'(2) = \lim_{h \to 0^-} \frac{f(2 + h) - f(2)}{h}$
        Since $h \to 0^-$, $2+h < 2$ (e.g., $1.99$), so $[2+h] = 1$.
        Also, $f(2) = = 2$.
        $L f'(2) = \lim_{h \to 0^-} \frac{1 - 2}{h} = \lim_{h \to 0^-} \frac{-1}{h} = \infty$. (The limit does not exist as a finite number).

    2.  **Right-hand derivative at $x = 2$:**
        $R f'(2) = \lim_{h \to 0^+} \frac{f(2 + h) - f(2)}{h}$
        Since $h \to 0^+$, $2+h > 2$ (e.g., $2.01$), so $[2+h] = 2$.
        Also, $f(2) = = 2$.
        $R f'(2) = \lim_{h \to 0^+} \frac{2 - 2}{h} = \lim_{h \to 0^+} \frac{0}{h} = 0$.

    Since the left-hand derivative is not finite and not equal to the right-hand derivative, $f(x) = [x]$ is not differentiable at $x = 2$.

---

#### **Exercise 5.3**

**Find $\frac{dy}{dx}$ in the following:**

**1. $2x + 3y = \sin x$**

**Reasoning:**
This is an implicit differentiation problem. We differentiate both sides of the equation with respect to $x$, treating $y$ as a function of $x$ and applying the chain rule where necessary.

**Step-by-step solution:**
Given equation: $2x + 3y = \sin x$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(2x) + \frac{d}{dx}(3y) = \frac{d}{dx}(\sin x)$
$2 + 3\frac{dy}{dx} = \cos x$
Now, solve for $\frac{dy}{dx}$:
$3\frac{dy}{dx} = \cos x - 2$
$\frac{dy}{dx} = \frac{\cos x - 2}{3}$.

---

**2. $2x + 3y = \sin y$**

**Reasoning:**
This is an implicit differentiation problem. We differentiate both sides with respect to $x$, treating $y$ as a function of $x$ and applying the chain rule.

**Step-by-step solution:**
Given equation: $2x + 3y = \sin y$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(2x) + \frac{d}{dx}(3y) = \frac{d}{dx}(\sin y)$
$2 + 3\frac{dy}{dx} = \cos y \cdot \frac{dy}{dx}$
Now, gather terms with $\frac{dy}{dx}$ on one side:
$2 = \cos y \frac{dy}{dx} - 3\frac{dy}{dx}$
$2 = \frac{dy}{dx}(\cos y - 3)$
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = \frac{2}{\cos y - 3}$.

---

**3. $ax + by^2 = \cos y$**

**Reasoning:**
This is an implicit differentiation problem. We differentiate both sides with respect to $x$, treating $y$ as a function of $x$ and applying the chain rule.

**Step-by-step solution:**
Given equation: $ax + by^2 = \cos y$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(ax) + \frac{d}{dx}(by^2) = \frac{d}{dx}(\cos y)$
$a + b \cdot 2y \frac{dy}{dx} = -\sin y \cdot \frac{dy}{dx}$
$a + 2by \frac{dy}{dx} = -\sin y \frac{dy}{dx}$
Gather terms with $\frac{dy}{dx}$:
$a = -\sin y \frac{dy}{dx} - 2by \frac{dy}{dx}$
$a = -\frac{dy}{dx}(\sin y + 2by)$
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = -\frac{a}{\sin y + 2by}$.

---

**4. $xy + y^2 = \tan x + y$**

**Reasoning:**
This is an implicit differentiation problem. We need to apply the product rule for $xy$ and the chain rule for $y^2$ and $y$.

**Step-by-step solution:**
Given equation: $xy + y^2 = \tan x + y$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(xy) + \frac{d}{dx}(y^2) = \frac{d}{dx}(\tan x) + \frac{d}{dx}(y)$

For $\frac{d}{dx}(xy)$, use the product rule: $1 \cdot y + x \cdot \frac{dy}{dx} = y + x\frac{dy}{dx}$.
For $\frac{d}{dx}(y^2)$, use the chain rule: $2y \frac{dy}{dx}$.
For $\frac{d}{dx}(\tan x)$, it is $\sec^2 x$.
For $\frac{d}{dx}(y)$, it is $\frac{dy}{dx}$.

Substitute these into the differentiated equation:
$y + x\frac{dy}{dx} + 2y\frac{dy}{dx} = \sec^2 x + \frac{dy}{dx}$
Gather terms with $\frac{dy}{dx}$:
$x\frac{dy}{dx} + 2y\frac{dy}{dx} - \frac{dy}{dx} = \sec^2 x - y$
$\frac{dy}{dx}(x + 2y - 1) = \sec^2 x - y$
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = \frac{\sec^2 x - y}{x + 2y - 1}$.

---

**5. $x^2 + xy + y^2 = 100$**

**Reasoning:**
This is an implicit differentiation problem. We need to apply the product rule for $xy$ and the chain rule for $y^2$.

**Step-by-step solution:**
Given equation: $x^2 + xy + y^2 = 100$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(x^2) + \frac{d}{dx}(xy) + \frac{d}{dx}(y^2) = \frac{d}{dx}(100)$

For $\frac{d}{dx}(x^2)$, it is $2x$.
For $\frac{d}{dx}(xy)$, use the product rule: $1 \cdot y + x \cdot \frac{dy}{dx} = y + x\frac{dy}{dx}$.
For $\frac{d}{dx}(y^2)$, use the chain rule: $2y \frac{dy}{dx}$.
For $\frac{d}{dx}(100)$, it is $0$.

Substitute these into the differentiated equation:
$2x + y + x\frac{dy}{dx} + 2y\frac{dy}{dx} = 0$
Gather terms with $\frac{dy}{dx}$:
$x\frac{dy}{dx} + 2y\frac{dy}{dx} = -2x - y$
$\frac{dy}{dx}(x + 2y) = -(2x + y)$
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = -\frac{2x + y}{x + 2y}$.

---

**6. $x^3 + x^2y + xy^2 + y^3 = 81$**

**Reasoning:**
This is an implicit differentiation problem. We need to apply the product rule for $x^2y$ and $xy^2$, and the chain rule for terms involving $y$.

**Step-by-step solution:**
Given equation: $x^3 + x^2y + xy^2 + y^3 = 81$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(x^3) + \frac{d}{dx}(x^2y) + \frac{d}{dx}(xy^2) + \frac{d}{dx}(y^3) = \frac{d}{dx}(81)$

For $\frac{d}{dx}(x^3)$, it is $3x^2$.
For $\frac{d}{dx}(x^2y)$, use the product rule: $2x \cdot y + x^2 \cdot \frac{dy}{dx} = 2xy + x^2\frac{dy}{dx}$.
For $\frac{d}{dx}(xy^2)$, use the product rule: $1 \cdot y^2 + x \cdot (2y \frac{dy}{dx}) = y^2 + 2xy\frac{dy}{dx}$.
For $\frac{d}{dx}(y^3)$, use the chain rule: $3y^2 \frac{dy}{dx}$.
For $\frac{d}{dx}(81)$, it is $0$.

Substitute these into the differentiated equation:
$3x^2 + (2xy + x^2\frac{dy}{dx}) + (y^2 + 2xy\frac{dy}{dx}) + 3y^2\frac{dy}{dx} = 0$
$3x^2 + 2xy + y^2 + x^2\frac{dy}{dx} + 2xy\frac{dy}{dx} + 3y^2\frac{dy}{dx} = 0$
Gather terms with $\frac{dy}{dx}$:
$(x^2 + 2xy + 3y^2)\frac{dy}{dx} = -(3x^2 + 2xy + y^2)$
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = -\frac{3x^2 + 2xy + y^2}{x^2 + 2xy + 3y^2}$.

---

**7. $\sin^2 y + \cos xy = k$**

**Reasoning:**
This is an implicit differentiation problem. We need to apply the chain rule for $\sin^2 y$ and $\cos xy$, and the product rule for $xy$.

**Step-by-step solution:**
Given equation: $\sin^2 y + \cos xy = k$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(\sin^2 y) + \frac{d}{dx}(\cos xy) = \frac{d}{dx}(k)$

For $\frac{d}{dx}(\sin^2 y)$, use the chain rule: $2 \sin y \cdot \frac{d}{dx}(\sin y) = 2 \sin y \cdot \cos y \cdot \frac{dy}{dx}$. This is also $\sin(2y)\frac{dy}{dx}$.
For $\frac{d}{dx}(\cos xy)$, use the chain rule and product rule: $-\sin(xy) \cdot \frac{d}{dx}(xy) = -\sin(xy) \cdot (1 \cdot y + x \cdot \frac{dy}{dx}) = -y\sin(xy) - x\sin(xy)\frac{dy}{dx}$.
For $\frac{d}{dx}(k)$, it is $0$.

Substitute these into the differentiated equation:
$2 \sin y \cos y \frac{dy}{dx} - y\sin(xy) - x\sin(xy)\frac{dy}{dx} = 0$
$\sin(2y)\frac{dy}{dx} - x\sin(xy)\frac{dy}{dx} = y\sin(xy)$
Gather terms with $\frac{dy}{dx}$:
$\frac{dy}{dx}(\sin(2y) - x\sin(xy)) = y\sin(xy)$
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = \frac{y\sin(xy)}{\sin(2y) - x\sin(xy)}$.

---

**8. $\sin^2 x + \cos^2 y = 1$**

**Reasoning:**
This is an implicit differentiation problem. We need to apply the chain rule for $\sin^2 x$ and $\cos^2 y$.

**Step-by-step solution:**
Given equation: $\sin^2 x + \cos^2 y = 1$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(\sin^2 x) + \frac{d}{dx}(\cos^2 y) = \frac{d}{dx}(1)$

For $\frac{d}{dx}(\sin^2 x)$, use the chain rule: $2 \sin x \cdot \frac{d}{dx}(\sin x) = 2 \sin x \cos x = \sin(2x)$.
For $\frac{d}{dx}(\cos^2 y)$, use the chain rule: $2 \cos y \cdot \frac{d}{dx}(\cos y) = 2 \cos y \cdot (-\sin y \cdot \frac{dy}{dx}) = -2 \sin y \cos y \frac{dy}{dx} = -\sin(2y)\frac{dy}{dx}$.
For $\frac{d}{dx}(1)$, it is $0$.

Substitute these into the differentiated equation:
$\sin(2x) - \sin(2y)\frac{dy}{dx} = 0$
$\sin(2x) = \sin(2y)\frac{dy}{dx}$
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = \frac{\sin(2x)}{\sin(2y)}$.

---

**Find $\frac{dy}{dx}$ for the functions in Exercises 9 to 15.**

**9. $y = \sin^{-1}\left(\frac{2x}{1 + x^2}\right)$**

**Reasoning:**
This is an inverse trigonometric function. We can differentiate directly using the chain rule, or use a trigonometric substitution to simplify the expression first. The substitution $x = \tan \theta$ is helpful here.

**Step-by-step solution (using substitution):**
Let $x = \tan \theta$. Then $\theta = \tan^{-1} x$.
Substitute $x = \tan \theta$ into the expression:
$y = \sin^{-1}\left(\frac{2 \tan \theta}{1 + \tan^2 \theta}\right)$
We know the identity $\frac{2 \tan \theta}{1 + \tan^2 \theta} = \sin(2\theta)$.
So, $y = \sin^{-1}(\sin(2\theta))$.
For $\sin^{-1}(\sin u)$, it is equal to $u$ if $u \in [-\frac{\pi}{2}, \frac{\pi}{2}]$.
Here, $u = 2\theta$. Since $x \in \mathbb{R}$, $\theta \in (-\frac{\pi}{2}, \frac{\pi}{2})$. So $2\theta \in (-\pi, \pi)$.
If $2\theta \in [-\frac{\pi}{2}, \frac{\pi}{2}]$, then $y = 2\theta = 2 \tan^{-1} x$.
$\frac{dy}{dx} = \frac{d}{dx}(2 \tan^{-1} x) = 2 \cdot \frac{1}{1 + x^2}$.

*Note on domain restriction:* The identity $\sin^{-1}(\sin u) = u$ holds for $u \in [-\frac{\pi}{2}, \frac{\pi}{2}]$. If $x = \tan \theta$, then $-\frac{\pi}{2} < \theta < \frac{\pi}{2}$, which means $-\pi < 2\theta < \pi$.
If $2\theta$ is outside $[-\frac{\pi}{2}, \frac{\pi}{2}]$, e.g., in $(\frac{\pi}{2}, \pi)$, then $\sin(2\theta) = \sin(\pi - 2\theta)$, and $\pi - 2\theta \in (0, \frac{\pi}{2})$. So $y = \pi - 2\theta$.
If $2\theta$ is in $(-\pi, -\frac{\pi}{2})$, then $\sin(2\theta) = \sin(-\pi - 2\theta)$, and $-\pi - 2\theta \in (0, \frac{\pi}{2})$. So $y = -\pi - 2\theta$.
However, in typical introductory calculus problems, it's often assumed that the principal value is taken where the simplification is direct. The derivative $\frac{2}{1+x^2}$ is valid for all $x$.

**Step-by-step solution (direct differentiation using chain rule):**
We know $\frac{d}{du} \sin^{-1} u = \frac{1}{\sqrt{1 - u^2}}$.
Let $y = \sin^{-1}\left(\frac{2x}{1 + x^2}\right)$.
$\frac{dy}{dx} = \frac{1}{\sqrt{1 - \left(\frac{2x}{1 + x^2}\right)^2}} \cdot \frac{d}{dx}\left(\frac{2x}{1 + x^2}\right)$.

First, simplify the square root term:
$\sqrt{1 - \frac{4x^2}{(1 + x^2)^2}} = \sqrt{\frac{(1 + x^2)^2 - 4x^2}{(1 + x^2)^2}} = \sqrt{\frac{1 + 2x^2 + x^4 - 4x^2}{(1 + x^2)^2}} = \sqrt{\frac{1 - 2x^2 + x^4}{(1 + x^2)^2}} = \sqrt{\frac{(1 - x^2)^2}{(1 + x^2)^2}} = \frac{|1 - x^2|}{1 + x^2}$.

Next, find $\frac{d}{dx}\left(\frac{2x}{1 + x^2}\right)$ using the quotient rule:
$\frac{d}{dx}\left(\frac{2x}{1 + x^2}\right) = \frac{2(1 + x^2) - 2x(2x)}{(1 + x^2)^2} = \frac{2 + 2x^2 - 4x^2}{(1 + x^2)^2} = \frac{2 - 2x^2}{(1 + x^2)^2} = \frac{2(1 - x^2)}{(1 + x^2)^2}$.

Now, combine these:
$\frac{dy}{dx} = \frac{1}{\frac{|1 - x^2|}{1 + x^2}} \cdot \frac{2(1 - x^2)}{(1 + x^2)^2} = \frac{1 + x^2}{|1 - x^2|} \cdot \frac{2(1 - x^2)}{(1 + x^2)^2}$.
$\frac{dy}{dx} = \frac{2(1 - x^2)}{|1 - x^2|(1 + x^2)}$.

If $1 - x^2 > 0$, i.e., $-1 < x < 1$, then $|1 - x^2| = 1 - x^2$.
$\frac{dy}{dx} = \frac{2(1 - x^2)}{(1 - x^2)(1 + x^2)} = \frac{2}{1 + x^2}$.

If $1 - x^2 < 0$, i.e., $x < -1$ or $x > 1$, then $|1 - x^2| = -(1 - x^2) = x^2 - 1$.
$\frac{dy}{dx} = \frac{2(1 - x^2)}{-(1 - x^2)(1 + x^2)} = -\frac{2}{1 + x^2}$.

This shows that the derivative depends on the interval. The substitution method implicitly assumes the principal branch where the simplification is direct. Given the context of these problems, the simplest form is usually expected. The question "Find dy/dx" usually implies a generic derivative where domain issues are not explicitly considered unless stated. So, $\frac{2}{1+x^2}$ is the common answer.

---

**10. $y = \tan^{-1}\left(\frac{3x - x^3}{1 - 3x^2}\right)$, $-\frac{1}{\sqrt{3}} < x < \frac{1}{\sqrt{3}}$**

**Reasoning:**
This is an inverse trigonometric function. The range for $x$ suggests a trigonometric substitution using $\tan \theta$. The expression $\frac{3 \tan \theta - \tan^3 \theta}{1 - 3 \tan^2 \theta}$ is the formula for $\tan(3\theta)$.

**Step-by-step solution:**
Let $x = \tan \theta$. Then $\theta = \tan^{-1} x$.
The given range $-\frac{1}{\sqrt{3}} < x < \frac{1}{\sqrt{3}}$ means $-\frac{\pi}{6} < \theta < \frac{\pi}{6}$.
This implies $-\frac{\pi}{2} < 3\theta < \frac{\pi}{2}$.
Substitute $x = \tan \theta$ into the expression:
$y = \tan^{-1}\left(\frac{3 \tan \theta - \tan^3 \theta}{1 - 3 \tan^2 \theta}\right)$
We know the identity $\frac{3 \tan \theta - \tan^3 \theta}{1 - 3 \tan^2 \theta} = \tan(3\theta)$.
So, $y = \tan^{-1}(\tan(3\theta))$.
Since $3\theta \in (-\frac{\pi}{2}, \frac{\pi}{2})$, we have $y = 3\theta$.
Substitute back $\theta = \tan^{-1} x$:
$y = 3 \tan^{-1} x$.
Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(3 \tan^{-1} x) = 3 \cdot \frac{1}{1 + x^2} = \frac{3}{1 + x^2}$.

---

**11. $y = \cos^{-1}\left(\frac{1 - x^2}{1 + x^2}\right)$, $0 < x < 1$**

**Reasoning:**
This is an inverse trigonometric function. The expression suggests a trigonometric substitution using $\tan \theta$. The identity $\frac{1 - \tan^2 \theta}{1 + \tan^2 \theta} = \cos(2\theta)$ is useful.

**Step-by-step solution:**
Let $x = \tan \theta$. Then $\theta = \tan^{-1} x$.
The given range $0 < x < 1$ means $0 < \theta < \frac{\pi}{4}$.
This implies $0 < 2\theta < \frac{\pi}{2}$. In this range, $\cos^{-1}(\cos(2\theta)) = 2\theta$.
Substitute $x = \tan \theta$ into the expression:
$y = \cos^{-1}\left(\frac{1 - \tan^2 \theta}{1 + \tan^2 \theta}\right)$
We know the identity $\frac{1 - \tan^2 \theta}{1 + \tan^2 \theta} = \cos(2\theta)$.
So, $y = \cos^{-1}(\cos(2\theta))$.
Since $2\theta \in (0, \frac{\pi}{2})$, we have $y = 2\theta$.
Substitute back $\theta = \tan^{-1} x$:
$y = 2 \tan^{-1} x$.
Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(2 \tan^{-1} x) = 2 \cdot \frac{1}{1 + x^2} = \frac{2}{1 + x^2}$.

---

**12. $y = \sin^{-1}\left(\frac{1 - x^2}{1 + x^2}\right)$, $0 < x < 1$**

**Reasoning:**
This is an inverse trigonometric function. The expression $\frac{1 - x^2}{1 + x^2}$ is familiar from the previous problem. We can use $x = \tan \theta$ again.

**Step-by-step solution:**
Let $x = \tan \theta$. Then $\theta = \tan^{-1} x$.
The given range $0 < x < 1$ means $0 < \theta < \frac{\pi}{4}$.
This implies $0 < 2\theta < \frac{\pi}{2}$.
Substitute $x = \tan \theta$ into the expression:
$y = \sin^{-1}\left(\frac{1 - \tan^2 \theta}{1 + \tan^2 \theta}\right)$
We know $\frac{1 - \tan^2 \theta}{1 + \tan^2 \theta} = \cos(2\theta)$.
So, $y = \sin^{-1}(\cos(2\theta))$.
We can rewrite $\cos(2\theta)$ as $\sin(\frac{\pi}{2} - 2\theta)$.
So, $y = \sin^{-1}(\sin(\frac{\pi}{2} - 2\theta))$.
Since $0 < 2\theta < \frac{\pi}{2}$, then $0 < \frac{\pi}{2} - 2\theta < \frac{\pi}{2}$. This means $\frac{\pi}{2} - 2\theta$ is in the principal value range for $\sin^{-1}$.
So, $y = \frac{\pi}{2} - 2\theta$.
Substitute back $\theta = \tan^{-1} x$:
$y = \frac{\pi}{2} - 2 \tan^{-1} x$.
Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(\frac{\pi}{2} - 2 \tan^{-1} x) = 0 - 2 \cdot \frac{1}{1 + x^2} = -\frac{2}{1 + x^2}$.

---

**13. $y = \cos^{-1}\left(\frac{2x}{1 + x^2}\right)$, $0 < x < 1$**

**Reasoning:**
This is an inverse trigonometric function. The expression $\frac{2x}{1 + x^2}$ suggests a trigonometric substitution using $\tan \theta$. The identity $\frac{2 \tan \theta}{1 + \tan^2 \theta} = \sin(2\theta)$ is useful.

**Step-by-step solution:**
Let $x = \tan \theta$. Then $\theta = \tan^{-1} x$.
The given range $0 < x < 1$ means $0 < \theta < \frac{\pi}{4}$.
This implies $0 < 2\theta < \frac{\pi}{2}$.
Substitute $x = \tan \theta$ into the expression:
$y = \cos^{-1}\left(\frac{2 \tan \theta}{1 + \tan^2 \theta}\right)$
We know $\frac{2 \tan \theta}{1 + \tan^2 \theta} = \sin(2\theta)$.
So, $y = \cos^{-1}(\sin(2\theta))$.
We can rewrite $\sin(2\theta)$ as $\cos(\frac{\pi}{2} - 2\theta)$.
So, $y = \cos^{-1}(\cos(\frac{\pi}{2} - 2\theta))$.
Since $0 < 2\theta < \frac{\pi}{2}$, then $0 < \frac{\pi}{2} - 2\theta < \frac{\pi}{2}$. This means $\frac{\pi}{2} - 2\theta$ is in the principal value range for $\cos^{-1}$.
So, $y = \frac{\pi}{2} - 2\theta$.
Substitute back $\theta = \tan^{-1} x$:
$y = \frac{\pi}{2} - 2 \tan^{-1} x$.
Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(\frac{\pi}{2} - 2 \tan^{-1} x) = 0 - 2 \cdot \frac{1}{1 + x^2} = -\frac{2}{1 + x^2}$.

---

**14. $y = \sin^{-1}(2x\sqrt{1 - x^2})$, $-\frac{1}{\sqrt{2}} < x < \frac{1}{\sqrt{2}}$**

**Reasoning:**
This is an inverse trigonometric function. The term $\sqrt{1 - x^2}$ suggests a substitution $x = \sin \theta$ or $x = \cos \theta$. Let's use $x = \sin \theta$.

**Step-by-step solution:**
Let $x = \sin \theta$. Then $\theta = \sin^{-1} x$.
The given range $-\frac{1}{\sqrt{2}} < x < \frac{1}{\sqrt{2}}$ means $-\frac{\pi}{4} < \theta < \frac{\pi}{4}$.
This implies $-\frac{\pi}{2} < 2\theta < \frac{\pi}{2}$. In this range, $\sin^{-1}(\sin(2\theta)) = 2\theta$.
Substitute $x = \sin \theta$ into the expression:
$y = \sin^{-1}(2 \sin \theta \sqrt{1 - \sin^2 \theta})$
Since $\sqrt{1 - \sin^2 \theta} = \sqrt{\cos^2 \theta} = |\cos \theta|$.
For $-\frac{\pi}{4} < \theta < \frac{\pi}{4}$, $\cos \theta > 0$, so $|\cos \theta| = \cos \theta$.
$y = \sin^{-1}(2 \sin \theta \cos \theta)$
We know the identity $2 \sin \theta \cos \theta = \sin(2\theta)$.
So, $y = \sin^{-1}(\sin(2\theta))$.
Since $2\theta \in (-\frac{\pi}{2}, \frac{\pi}{2})$, we have $y = 2\theta$.
Substitute back $\theta = \sin^{-1} x$:
$y = 2 \sin^{-1} x$.
Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(2 \sin^{-1} x) = 2 \cdot \frac{1}{\sqrt{1 - x^2}} = \frac{2}{\sqrt{1 - x^2}}$.

---

**15. $y = \sec^{-1}\left(\frac{1}{2x^2 - 1}\right)$, $0 < x < \frac{1}{\sqrt{2}}$**

**Reasoning:**
This is an inverse trigonometric function. The expression $2x^2 - 1$ suggests a substitution $x = \cos \theta$. The identity $2\cos^2 \theta - 1 = \cos(2\theta)$ is useful.
Also, $\sec^{-1} u = \cos^{-1}(\frac{1}{u})$.

**Step-by-step solution:**
We can rewrite $y$ using the identity $\sec^{-1} A = \cos^{-1}(\frac{1}{A})$:
$y = \cos^{-1}\left(\frac{1}{\frac{1}{2x^2 - 1}}\right) = \cos^{-1}(2x^2 - 1)$.

Now, let $x = \cos \theta$. Then $\theta = \cos^{-1} x$.
The given range $0 < x < \frac{1}{\sqrt{2}}$ means $\frac{\pi}{4} < \theta < \frac{\pi}{2}$.
This implies $\frac{\pi}{2} < 2\theta < \pi$.
Substitute $x = \cos \theta$ into the expression:
$y = \cos^{-1}(2 \cos^2 \theta - 1)$
We know the identity $2 \cos^2 \theta - 1 = \cos(2\theta)$.
So, $y = \cos^{-1}(\cos(2\theta))$.
Since $2\theta \in (\frac{\pi}{2}, \pi)$, we know that $\cos^{-1}(\cos u) = u$ is not directly applicable.
For $u \in (\frac{\pi}{2}, \pi)$, $\cos^{-1}(\cos u) = 2\pi - u$ is incorrect. It should be $\cos^{-1}(\cos u) = u$ if $u \in [0, \pi]$.
Ah, the range for $x$ is $0 < x < \frac{1}{\sqrt{2}}$. This means $x$ is positive.
Let's check the range of $2x^2 - 1$.
If $x \to 0^+$, $2x^2 - 1 \to -1$.
If $x \to \frac{1}{\sqrt{2}}^-$, $2x^2 - 1 \to 2(\frac{1}{2}) - 1 = 0$.
So $2x^2 - 1 \in (-1, 0)$.
This means $y = \cos^{-1}(2x^2 - 1)$ implies $y \in (\frac{\pi}{2}, \pi)$.

Let's stick with $x = \cos \theta$.
Range $0 < x < \frac{1}{\sqrt{2}}$ means $\frac{\pi}{4} < \theta < \frac{\pi}{2}$.
Then $2\theta$ is in $(\frac{\pi}{2}, \pi)$.
For $u \in [0, \pi]$, $\cos^{-1}(\cos u) = u$. So $y = 2\theta$.
This is correct.

Substitute back $\theta = \cos^{-1} x$:
$y = 2 \cos^{-1} x$.
Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(2 \cos^{-1} x) = 2 \cdot \frac{-1}{\sqrt{1 - x^2}} = -\frac{2}{\sqrt{1 - x^2}}$.

---

#### **Exercise 5.4**

**Differentiate the following w.r.t. $x$:**

**1. $\frac{e^x}{\sin x}$**

**Reasoning:**
This is a quotient of two functions. We use the quotient rule: $\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{u'v - uv'}{v^2}$.

**Step-by-step solution:**
Let $y = \frac{e^x}{\sin x}$.
Let $u = e^x \Rightarrow u' = e^x$.
Let $v = \sin x \Rightarrow v' = \cos x$.

Using the quotient rule:
$\frac{dy}{dx} = \frac{u'v - uv'}{v^2} = \frac{e^x \sin x - e^x \cos x}{\sin^2 x}$
$\frac{dy}{dx} = \frac{e^x(\sin x - \cos x)}{\sin^2 x}$.

---

**2. $e^{\sin^{-1} x}$**

**Reasoning:**
This is a composite function of the form $e^u$ where $u = \sin^{-1} x$. We use the chain rule: $\frac{d}{dx} e^u = e^u \frac{du}{dx}$.

**Step-by-step solution:**
Let $y = e^{\sin^{-1} x}$.
Let $u = \sin^{-1} x$. Then $\frac{du}{dx} = \frac{1}{\sqrt{1 - x^2}}$.
And $y = e^u$. So $\frac{dy}{du} = e^u$.

Using the chain rule:
$\frac{dy}{dx} = e^u \cdot \frac{du}{dx} = e^{\sin^{-1} x} \cdot \frac{1}{\sqrt{1 - x^2}}$
$\frac{dy}{dx} = \frac{e^{\sin^{-1} x}}{\sqrt{1 - x^2}}$.

---

**3. $e^{x^3}$**

**Reasoning:**
This is a composite function of the form $e^u$ where $u = x^3$. We use the chain rule.

**Step-by-step solution:**
Let $y = e^{x^3}$.
Let $u = x^3$. Then $\frac{du}{dx} = 3x^2$.
And $y = e^u$. So $\frac{dy}{du} = e^u$.

Using the chain rule:
$\frac{dy}{dx} = e^u \cdot \frac{du}{dx} = e^{x^3} \cdot (3x^2)$
$\frac{dy}{dx} = 3x^2 e^{x^3}$.

---

**4. $\sin(\tan^{-1} e^{-x})$**

**Reasoning:**
This is a nested composite function. We apply the chain rule multiple times.
$y = \sin(u)$, where $u = \tan^{-1}(v)$, and $v = e^{-x}$.
$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dv} \cdot \frac{dv}{dx}$.

**Step-by-step solution:**
Let $y = \sin(\tan^{-1} e^{-x})$.

1.  Derivative of the outermost function $\sin(A)$:
    $\frac{d}{dx}(\sin A) = \cos A \cdot \frac{dA}{dx}$.
    So, $\frac{dy}{dx} = \cos(\tan^{-1} e^{-x}) \cdot \frac{d}{dx}(\tan^{-1} e^{-x})$.

2.  Derivative of the next function $\tan^{-1}(B)$:
    $\frac{d}{dx}(\tan^{-1} B) = \frac{1}{1 + B^2} \cdot \frac{dB}{dx}$.
    So, $\frac{d}{dx}(\tan^{-1} e^{-x}) = \frac{1}{1 + (e^{-x})^2} \cdot \frac{d}{dx}(e^{-x}) = \frac{1}{1 + e^{-2x}} \cdot \frac{d}{dx}(e^{-x})$.

3.  Derivative of the innermost function $e^{-x}$:
    $\frac{d}{dx}(e^{-x}) = e^{-x} \cdot \frac{d}{dx}(-x) = e^{-x} \cdot (-1) = -e^{-x}$.

Combine all parts:
$\frac{dy}{dx} = \cos(\tan^{-1} e^{-x}) \cdot \frac{1}{1 + e^{-2x}} \cdot (-e^{-x})$
$\frac{dy}{dx} = -\frac{e^{-x} \cos(\tan^{-1} e^{-x})}{1 + e^{-2x}}$.

---

**5. $\log(\cos e^x)$**

**Reasoning:**
This is a nested composite function.
$y = \log(u)$, where $u = \cos(v)$, and $v = e^x$.
$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dv} \cdot \frac{dv}{dx}$.

**Step-by-step solution:**
Let $y = \log(\cos e^x)$.

1.  Derivative of the outermost function $\log(A)$:
    $\frac{d}{dx}(\log A) = \frac{1}{A} \cdot \frac{dA}{dx}$.
    So, $\frac{dy}{dx} = \frac{1}{\cos e^x} \cdot \frac{d}{dx}(\cos e^x)$.

2.  Derivative of the next function $\cos(B)$:
    $\frac{d}{dx}(\cos B) = -\sin B \cdot \frac{dB}{dx}$.
    So, $\frac{d}{dx}(\cos e^x) = -\sin e^x \cdot \frac{d}{dx}(e^x)$.

3.  Derivative of the innermost function $e^x$:
    $\frac{d}{dx}(e^x) = e^x$.

Combine all parts:
$\frac{dy}{dx} = \frac{1}{\cos e^x} \cdot (-\sin e^x) \cdot (e^x)$
$\frac{dy}{dx} = -e^x \frac{\sin e^x}{\cos e^x}$
$\frac{dy}{dx} = -e^x \tan(e^x)$.

---

**6. $e^x + e^{x^2} + \dots + e^{x^5}$**

**Reasoning:**
This is a sum of functions. We differentiate each term separately. Each term is of the form $e^{u}$ where $u$ is a power of $x$. We use the chain rule for each term.

**Step-by-step solution:**
Let $y = e^x + e^{x^2} + e^{x^3} + e^{x^4} + e^{x^5}$.
$\frac{dy}{dx} = \frac{d}{dx}(e^x) + \frac{d}{dx}(e^{x^2}) + \frac{d}{dx}(e^{x^3}) + \frac{d}{dx}(e^{x^4}) + \frac{d}{dx}(e^{x^5})$.

*   $\frac{d}{dx}(e^x) = e^x$.
*   $\frac{d}{dx}(e^{x^2}) = e^{x^2} \cdot \frac{d}{dx}(x^2) = e^{x^2} \cdot 2x = 2x e^{x^2}$.
*   $\frac{d}{dx}(e^{x^3}) = e^{x^3} \cdot \frac{d}{dx}(x^3) = e^{x^3} \cdot 3x^2 = 3x^2 e^{x^3}$.
*   $\frac{d}{dx}(e^{x^4}) = e^{x^4} \cdot \frac{d}{dx}(x^4) = e^{x^4} \cdot 4x^3 = 4x^3 e^{x^4}$.
*   $\frac{d}{dx}(e^{x^5}) = e^{x^5} \cdot \frac{d}{dx}(x^5) = e^{x^5} \cdot 5x^4 = 5x^4 e^{x^5}$.

Summing these derivatives:
$\frac{dy}{dx} = e^x + 2x e^{x^2} + 3x^2 e^{x^3} + 4x^3 e^{x^4} + 5x^4 e^{x^5}$.

---

**7. $\sqrt{e^{\sqrt{x}}}$, $x > 0$**

**Reasoning:**
This is a nested composite function.
$y = \sqrt{u}$, where $u = e^v$, and $v = \sqrt{x}$.
$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dv} \cdot \frac{dv}{dx}$.

**Step-by-step solution:**
Let $y = \sqrt{e^{\sqrt{x}}} = (e^{\sqrt{x}})^{1/2}$.

1.  Derivative of the outermost function $A^{1/2}$:
    $\frac{d}{dx}(A^{1/2}) = \frac{1}{2} A^{-1/2} \cdot \frac{dA}{dx} = \frac{1}{2\sqrt{A}} \cdot \frac{dA}{dx}$.
    So, $\frac{dy}{dx} = \frac{1}{2\sqrt{e^{\sqrt{x}}}} \cdot \frac{d}{dx}(e^{\sqrt{x}})$.

2.  Derivative of the next function $e^B$:
    $\frac{d}{dx}(e^B) = e^B \cdot \frac{dB}{dx}$.
    So, $\frac{d}{dx}(e^{\sqrt{x}}) = e^{\sqrt{x}} \cdot \frac{d}{dx}(\sqrt{x})$.

3.  Derivative of the innermost function $\sqrt{x}$:
    $\frac{d}{dx}(\sqrt{x}) = \frac{d}{dx}(x^{1/2}) = \frac{1}{2}x^{-1/2} = \frac{1}{2\sqrt{x}}$.

Combine all parts:
$\frac{dy}{dx} = \frac{1}{2\sqrt{e^{\sqrt{x}}}} \cdot e^{\sqrt{x}} \cdot \frac{1}{2\sqrt{x}}$
$\frac{dy}{dx} = \frac{e^{\sqrt{x}}}{4\sqrt{x}\sqrt{e^{\sqrt{x}}}}$
$\frac{dy}{dx} = \frac{\sqrt{e^{\sqrt{x}}}}{4\sqrt{x}}$.

---

**8. $\log(\log x)$, $x > 1$**

**Reasoning:**
This is a composite function of the form $\log(u)$ where $u = \log x$. We use the chain rule. The condition $x > 1$ ensures that $\log x > 0$, so $\log(\log x)$ is defined.

**Step-by-step solution:**
Let $y = \log(\log x)$.
Let $u = \log x$. Then $\frac{du}{dx} = \frac{1}{x}$.
And $y = \log u$. So $\frac{dy}{du} = \frac{1}{u}$.

Using the chain rule:
$\frac{dy}{dx} = \frac{1}{u} \cdot \frac{du}{dx} = \frac{1}{\log x} \cdot \frac{1}{x}$
$\frac{dy}{dx} = \frac{1}{x \log x}$.

---

**9. $\cos(\log x + e^x)$**

**Reasoning:**
This is a composite function of the form $\cos(u)$ where $u = \log x + e^x$. We use the chain rule.

**Step-by-step solution:**
Let $y = \cos(\log x + e^x)$.
Let $u = \log x + e^x$. Then $\frac{du}{dx} = \frac{d}{dx}(\log x) + \frac{d}{dx}(e^x) = \frac{1}{x} + e^x$.
And $y = \cos u$. So $\frac{dy}{du} = -\sin u$.

Using the chain rule:
$\frac{dy}{dx} = -\sin u \cdot \frac{du}{dx} = -\sin(\log x + e^x) \cdot \left(\frac{1}{x} + e^x\right)$
$\frac{dy}{dx} = -\left(\frac{1}{x} + e^x\right) \sin(\log x + e^x)$.

---

**10. $\cos(\log x + e^x)$, $x > 0$ (This appears to be a repeat of problem 9. Assuming it's meant to be $e^x \cos x$ or some other similar looking function that was truncated from the image)**

The problem 9 and 10 in the OCR appear to be identical: `cos(log x + e^x)`. I will solve it for the problem 9.

---

#### **Exercise 5.5**

**Differentiate the functions given in Exercises 1 to 11 w.r.t. $x$.**

**1. $\cos x \cdot \cos 2x \cdot \cos 3x$**

**Reasoning:**
This is a product of three functions. We can use the product rule for three functions: $\frac{d}{dx}(uvw) = u'vw + uv'w + uvw'$. Alternatively, use logarithmic differentiation, which is often simpler for products of many terms.

**Step-by-step solution (using logarithmic differentiation):**
Let $y = \cos x \cdot \cos 2x \cdot \cos 3x$.
Take the natural logarithm of both sides:
$\log y = \log(\cos x \cdot \cos 2x \cdot \cos 3x)$
Using logarithm properties:
$\log y = \log(\cos x) + \log(\cos 2x) + \log(\cos 3x)$.

Now, differentiate both sides with respect to $x$:
$\frac{1}{y} \frac{dy}{dx} = \frac{d}{dx}(\log(\cos x)) + \frac{d}{dx}(\log(\cos 2x)) + \frac{d}{dx}(\log(\cos 3x))$.

*   $\frac{d}{dx}(\log(\cos x)) = \frac{1}{\cos x} \cdot (-\sin x) = -\tan x$.
*   $\frac{d}{dx}(\log(\cos 2x)) = \frac{1}{\cos 2x} \cdot (-\sin 2x) \cdot 2 = -2 \tan 2x$.
*   $\frac{d}{dx}(\log(\cos 3x)) = \frac{1}{\cos 3x} \cdot (-\sin 3x) \cdot 3 = -3 \tan 3x$.

Substitute these back:
$\frac{1}{y} \frac{dy}{dx} = -\tan x - 2 \tan 2x - 3 \tan 3x$.

Finally, multiply by $y$:
$\frac{dy}{dx} = y (-\tan x - 2 \tan 2x - 3 \tan 3x)$
$\frac{dy}{dx} = \cos x \cos 2x \cos 3x (-\tan x - 2 \tan 2x - 3 \tan 3x)$.

---

**2. $\sqrt{\frac{(x - 1)(x - 2)}{(x - 3)(x - 4)(x - 5)}}$**

**Reasoning:**
This involves a complicated product and quotient inside a square root. Logarithmic differentiation is ideal here.

**Step-by-step solution:**
Let $y = \sqrt{\frac{(x - 1)(x - 2)}{(x - 3)(x - 4)(x - 5)}} = \left(\frac{(x - 1)(x - 2)}{(x - 3)(x - 4)(x - 5)}\right)^{1/2}$.
Take the natural logarithm of both sides:
$\log y = \frac{1}{2} \log\left(\frac{(x - 1)(x - 2)}{(x - 3)(x - 4)(x - 5)}\right)$.
Using logarithm properties:
$\log y = \frac{1}{2} [\log(x - 1) + \log(x - 2) - \log(x - 3) - \log(x - 4) - \log(x - 5)]$.

Now, differentiate both sides with respect to $x$:
$\frac{1}{y} \frac{dy}{dx} = \frac{1}{2} \left[\frac{d}{dx}(\log(x - 1)) + \frac{d}{dx}(\log(x - 2)) - \frac{d}{dx}(\log(x - 3)) - \frac{d}{dx}(\log(x - 4)) - \frac{d}{dx}(\log(x - 5))\right]$.

*   $\frac{d}{dx}(\log(x - 1)) = \frac{1}{x - 1}$.
*   $\frac{d}{dx}(\log(x - 2)) = \frac{1}{x - 2}$.
*   $\frac{d}{dx}(\log(x - 3)) = \frac{1}{x - 3}$.
*   $\frac{d}{dx}(\log(x - 4)) = \frac{1}{x - 4}$.
*   $\frac{d}{dx}(\log(x - 5)) = \frac{1}{x - 5}$.

Substitute these back:
$\frac{1}{y} \frac{dy}{dx} = \frac{1}{2} \left[\frac{1}{x - 1} + \frac{1}{x - 2} - \frac{1}{x - 3} - \frac{1}{x - 4} - \frac{1}{x - 5}\right]$.

Finally, multiply by $y$:
$\frac{dy}{dx} = \sqrt{\frac{(x - 1)(x - 2)}{(x - 3)(x - 4)(x - 5)}} \cdot \frac{1}{2} \left[\frac{1}{x - 1} + \frac{1}{x - 2} - \frac{1}{x - 3} - \frac{1}{x - 4} - \frac{1}{x - 5}\right]$.

---

**3. $(\log x)^{\cos x}$**

**Reasoning:**
This is a function of the form $f(x)^{g(x)}$. Logarithmic differentiation is required.

**Step-by-step solution:**
Let $y = (\log x)^{\cos x}$.
Take the natural logarithm of both sides:
$\log y = \log((\log x)^{\cos x})$.
Using logarithm properties:
$\log y = \cos x \cdot \log(\log x)$.

Now, differentiate both sides with respect to $x$. Use the product rule for the right side.
$\frac{1}{y} \frac{dy}{dx} = \frac{d}{dx}(\cos x) \cdot \log(\log x) + \cos x \cdot \frac{d}{dx}(\log(\log x))$.

*   $\frac{d}{dx}(\cos x) = -\sin x$.
*   $\frac{d}{dx}(\log(\log x)) = \frac{1}{\log x} \cdot \frac{1}{x}$ (from Exercise 5.4, problem 8).

Substitute these back:
$\frac{1}{y} \frac{dy}{dx} = (-\sin x) \log(\log x) + \cos x \cdot \frac{1}{x \log x}$.

Finally, multiply by $y$:
$\frac{dy}{dx} = (\log x)^{\cos x} \left[-\sin x \log(\log x) + \frac{\cos x}{x \log x}\right]$.

---

**4. $x^x - 2^{\sin x}$**

**Reasoning:**
This is a difference of two functions, each of which requires logarithmic differentiation or specific rules. For $x^x$, logarithmic differentiation is needed. For $2^{\sin x}$, we can use the rule $\frac{d}{dx}(a^u) = a^u \log a \frac{du}{dx}$.

**Step-by-step solution:**
Let $y = x^x - 2^{\sin x}$.
Let $u = x^x$ and $v = 2^{\sin x}$. So $y = u - v$.
Then $\frac{dy}{dx} = \frac{du}{dx} - \frac{dv}{dx}$.

**Find $\frac{du}{dx}$ for $u = x^x$:**
Take $\log$ on both sides: $\log u = \log(x^x) = x \log x$.
Differentiate with respect to $x$:
$\frac{1}{u} \frac{du}{dx} = \frac{d}{dx}(x) \cdot \log x + x \cdot \frac{d}{dx}(\log x)$ (using product rule)
$\frac{1}{u} \frac{du}{dx} = 1 \cdot \log x + x \cdot \frac{1}{x} = \log x + 1$.
$\frac{du}{dx} = u(\log x + 1) = x^x(1 + \log x)$.

**Find $\frac{dv}{dx}$ for $v = 2^{\sin x}$:**
Using the rule $\frac{d}{dx}(a^f(x)) = a^{f(x)} \log a \cdot f'(x)$.
Here $a=2$ and $f(x) = \sin x$, so $f'(x) = \cos x$.
$\frac{dv}{dx} = 2^{\sin x} \log 2 \cdot \cos x$.

**Combine $\frac{du}{dx}$ and $\frac{dv}{dx}$:**
$\frac{dy}{dx} = x^x(1 + \log x) - 2^{\sin x} \cos x \log 2$.

---

**5. $(x + 3)^2 \cdot (x + 4)^3 \cdot (x + 5)^4$**

**Reasoning:**
This is a product of three functions raised to powers. Logarithmic differentiation simplifies this greatly.

**Step-by-step solution:**
Let $y = (x + 3)^2 (x + 4)^3 (x + 5)^4$.
Take the natural logarithm of both sides:
$\log y = \log[(x + 3)^2 (x + 4)^3 (x + 5)^4]$.
Using logarithm properties:
$\log y = 2 \log(x + 3) + 3 \log(x + 4) + 4 \log(x + 5)$.

Now, differentiate both sides with respect to $x$:
$\frac{1}{y} \frac{dy}{dx} = 2 \cdot \frac{1}{x + 3} + 3 \cdot \frac{1}{x + 4} + 4 \cdot \frac{1}{x + 5}$.

Finally, multiply by $y$:
$\frac{dy}{dx} = (x + 3)^2 (x + 4)^3 (x + 5)^4 \left[\frac{2}{x + 3} + \frac{3}{x + 4} + \frac{4}{x + 5}\right]$.

---

**6. $\left(x + \frac{1}{x}\right)^x + x^{\left(1 + \frac{1}{x}\right)}$**

**Reasoning:**
This is a sum of two functions, each of the form $f(x)^{g(x)}$. Logarithmic differentiation is required for each term.

**Step-by-step solution:**
Let $y = \left(x + \frac{1}{x}\right)^x + x^{\left(1 + \frac{1}{x}\right)}$.
Let $u = \left(x + \frac{1}{x}\right)^x$ and $v = x^{\left(1 + \frac{1}{x}\right)}$. So $y = u + v$.
Then $\frac{dy}{dx} = \frac{du}{dx} + \frac{dv}{dx}$.

**Find $\frac{du}{dx}$ for $u = \left(x + \frac{1}{x}\right)^x$:**
Take $\log$ on both sides: $\log u = x \log\left(x + \frac{1}{x}\right)$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{u} \frac{du}{dx} = 1 \cdot \log\left(x + \frac{1}{x}\right) + x \cdot \frac{d}{dx}\left(\log\left(x + \frac{1}{x}\right)\right)$.
$\frac{d}{dx}\left(\log\left(x + \frac{1}{x}\right)\right) = \frac{1}{x + \frac{1}{x}} \cdot \frac{d}{dx}\left(x + \frac{1}{x}\right) = \frac{1}{\frac{x^2 + 1}{x}} \cdot \left(1 - \frac{1}{x^2}\right) = \frac{x}{x^2 + 1} \cdot \frac{x^2 - 1}{x^2} = \frac{x^2 - 1}{x(x^2 + 1)}$.

So, $\frac{1}{u} \frac{du}{dx} = \log\left(x + \frac{1}{x}\right) + x \cdot \frac{x^2 - 1}{x(x^2 + 1)} = \log\left(x + \frac{1}{x}\right) + \frac{x^2 - 1}{x^2 + 1}$.
$\frac{du}{dx} = \left(x + \frac{1}{x}\right)^x \left[\log\left(x + \frac{1}{x}\right) + \frac{x^2 - 1}{x^2 + 1}\right]$.

**Find $\frac{dv}{dx}$ for $v = x^{\left(1 + \frac{1}{x}\right)}$:**
Take $\log$ on both sides: $\log v = \left(1 + \frac{1}{x}\right) \log x$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{v} \frac{dv}{dx} = \frac{d}{dx}\left(1 + \frac{1}{x}\right) \cdot \log x + \left(1 + \frac{1}{x}\right) \cdot \frac{d}{dx}(\log x)$.
$\frac{d}{dx}\left(1 + \frac{1}{x}\right) = -\frac{1}{x^2}$.
$\frac{d}{dx}(\log x) = \frac{1}{x}$.

So, $\frac{1}{v} \frac{dv}{dx} = \left(-\frac{1}{x^2}\right) \log x + \left(1 + \frac{1}{x}\right) \frac{1}{x} = -\frac{\log x}{x^2} + \frac{1}{x} + \frac{1}{x^2} = \frac{x + 1 - \log x}{x^2}$.
$\frac{dv}{dx} = x^{\left(1 + \frac{1}{x}\right)} \left[\frac{x + 1 - \log x}{x^2}\right]$.

**Combine $\frac{du}{dx}$ and $\frac{dv}{dx}$:**
$\frac{dy}{dx} = \left(x + \frac{1}{x}\right)^x \left[\log\left(x + \frac{1}{x}\right) + \frac{x^2 - 1}{x^2 + 1}\right] + x^{\left(1 + \frac{1}{x}\right)} \left[\frac{x + 1 - \log x}{x^2}\right]$.

---

**7. $(\log x)^x + x^{\log x}$**

**Reasoning:**
This is a sum of two functions, each of the form $f(x)^{g(x)}$. Logarithmic differentiation is required for each term.

**Step-by-step solution:**
Let $y = (\log x)^x + x^{\log x}$.
Let $u = (\log x)^x$ and $v = x^{\log x}$. So $y = u + v$.
Then $\frac{dy}{dx} = \frac{du}{dx} + \frac{dv}{dx}$.

**Find $\frac{du}{dx}$ for $u = (\log x)^x$:**
Take $\log$ on both sides: $\log u = x \log(\log x)$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{u} \frac{du}{dx} = 1 \cdot \log(\log x) + x \cdot \frac{d}{dx}(\log(\log x))$.
$\frac{d}{dx}(\log(\log x)) = \frac{1}{x \log x}$ (from Exercise 5.4, problem 8).

So, $\frac{1}{u} \frac{du}{dx} = \log(\log x) + x \cdot \frac{1}{x \log x} = \log(\log x) + \frac{1}{\log x}$.
$\frac{du}{dx} = (\log x)^x \left[\log(\log x) + \frac{1}{\log x}\right]$.

**Find $\frac{dv}{dx}$ for $v = x^{\log x}$:**
Take $\log$ on both sides: $\log v = \log(x^{\log x}) = (\log x)(\log x) = (\log x)^2$.
Differentiate with respect to $x$ using the chain rule:
$\frac{1}{v} \frac{dv}{dx} = 2 (\log x) \cdot \frac{d}{dx}(\log x) = 2 \log x \cdot \frac{1}{x}$.
$\frac{dv}{dx} = v \cdot \frac{2 \log x}{x} = x^{\log x} \cdot \frac{2 \log x}{x}$.

**Combine $\frac{du}{dx}$ and $\frac{dv}{dx}$:**
$\frac{dy}{dx} = (\log x)^x \left[\log(\log x) + \frac{1}{\log x}\right] + x^{\log x} \left[\frac{2 \log x}{x}\right]$.

---

**8. $(\sin x)^x + \sin^{-1} \sqrt{x}$**

**Reasoning:**
This is a sum of two functions. For $(\sin x)^x$, logarithmic differentiation is required. For $\sin^{-1} \sqrt{x}$, we use the chain rule.

**Step-by-step solution:**
Let $y = (\sin x)^x + \sin^{-1} \sqrt{x}$.
Let $u = (\sin x)^x$ and $v = \sin^{-1} \sqrt{x}$. So $y = u + v$.
Then $\frac{dy}{dx} = \frac{du}{dx} + \frac{dv}{dx}$.

**Find $\frac{du}{dx}$ for $u = (\sin x)^x$:**
Take $\log$ on both sides: $\log u = x \log(\sin x)$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{u} \frac{du}{dx} = 1 \cdot \log(\sin x) + x \cdot \frac{d}{dx}(\log(\sin x))$.
$\frac{d}{dx}(\log(\sin x)) = \frac{1}{\sin x} \cdot \cos x = \cot x$.

So, $\frac{1}{u} \frac{du}{dx} = \log(\sin x) + x \cot x$.
$\frac{du}{dx} = (\sin x)^x [\log(\sin x) + x \cot x]$.

**Find $\frac{dv}{dx}$ for $v = \sin^{-1} \sqrt{x}$:**
Using the chain rule: $\frac{d}{dx} \sin^{-1} A = \frac{1}{\sqrt{1 - A^2}} \cdot \frac{dA}{dx}$.
Here $A = \sqrt{x} = x^{1/2}$. So $\frac{dA}{dx} = \frac{1}{2}x^{-1/2} = \frac{1}{2\sqrt{x}}$.
$\frac{dv}{dx} = \frac{1}{\sqrt{1 - (\sqrt{x})^2}} \cdot \frac{1}{2\sqrt{x}} = \frac{1}{\sqrt{1 - x}} \cdot \frac{1}{2\sqrt{x}} = \frac{1}{2\sqrt{x(1 - x)}}$.

**Combine $\frac{du}{dx}$ and $\frac{dv}{dx}$:**
$\frac{dy}{dx} = (\sin x)^x [\log(\sin x) + x \cot x] + \frac{1}{2\sqrt{x(1 - x)}}$.

---

**9. $x^{\sin x} + (\sin x)^{\cos x}$**

**Reasoning:**
This is a sum of two functions, each of the form $f(x)^{g(x)}$. Logarithmic differentiation is required for each term.

**Step-by-step solution:**
Let $y = x^{\sin x} + (\sin x)^{\cos x}$.
Let $u = x^{\sin x}$ and $v = (\sin x)^{\cos x}$. So $y = u + v$.
Then $\frac{dy}{dx} = \frac{du}{dx} + \frac{dv}{dx}$.

**Find $\frac{du}{dx}$ for $u = x^{\sin x}$:**
Take $\log$ on both sides: $\log u = \sin x \log x$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{u} \frac{du}{dx} = \frac{d}{dx}(\sin x) \cdot \log x + \sin x \cdot \frac{d}{dx}(\log x)$
$\frac{1}{u} \frac{du}{dx} = \cos x \log x + \sin x \cdot \frac{1}{x}$.
$\frac{du}{dx} = x^{\sin x} \left[\cos x \log x + \frac{\sin x}{x}\right]$.

**Find $\frac{dv}{dx}$ for $v = (\sin x)^{\cos x}$:**
Take $\log$ on both sides: $\log v = \cos x \log(\sin x)$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{v} \frac{dv}{dx} = \frac{d}{dx}(\cos x) \cdot \log(\sin x) + \cos x \cdot \frac{d}{dx}(\log(\sin x))$.
$\frac{d}{dx}(\cos x) = -\sin x$.
$\frac{d}{dx}(\log(\sin x)) = \frac{1}{\sin x} \cdot \cos x = \cot x$.

So, $\frac{1}{v} \frac{dv}{dx} = (-\sin x) \log(\sin x) + \cos x \cdot \cot x$.
$\frac{dv}{dx} = (\sin x)^{\cos x} [-\sin x \log(\sin x) + \cos x \cot x]$.

**Combine $\frac{du}{dx}$ and $\frac{dv}{dx}$:**
$\frac{dy}{dx} = x^{\sin x} \left[\cos x \log x + \frac{\sin x}{x}\right] + (\sin x)^{\cos x} [-\sin x \log(\sin x) + \cos x \cot x]$.

---

**10. $x^{\cos x} + \frac{x^2 + 1}{x^2 - 1}$**

**Reasoning:**
This is a sum of two functions. For $x^{\cos x}$, logarithmic differentiation is required. For $\frac{x^2 + 1}{x^2 - 1}$, we use the quotient rule.

**Step-by-step solution:**
Let $y = x^{\cos x} + \frac{x^2 + 1}{x^2 - 1}$.
Let $u = x^{\cos x}$ and $v = \frac{x^2 + 1}{x^2 - 1}$. So $y = u + v$.
Then $\frac{dy}{dx} = \frac{du}{dx} + \frac{dv}{dx}$.

**Find $\frac{du}{dx}$ for $u = x^{\cos x}$:**
Take $\log$ on both sides: $\log u = \cos x \log x$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{u} \frac{du}{dx} = \frac{d}{dx}(\cos x) \cdot \log x + \cos x \cdot \frac{d}{dx}(\log x)$
$\frac{1}{u} \frac{du}{dx} = (-\sin x) \log x + \cos x \cdot \frac{1}{x}$.
$\frac{du}{dx} = x^{\cos x} \left[-\sin x \log x + \frac{\cos x}{x}\right]$.

**Find $\frac{dv}{dx}$ for $v = \frac{x^2 + 1}{x^2 - 1}$:**
Using the quotient rule: $\frac{d}{dx}\left(\frac{A}{B}\right) = \frac{A'B - AB'}{B^2}$.
Here $A = x^2 + 1 \Rightarrow A' = 2x$.
And $B = x^2 - 1 \Rightarrow B' = 2x$.
$\frac{dv}{dx} = \frac{2x(x^2 - 1) - (x^2 + 1)(2x)}{(x^2 - 1)^2}$
$\frac{dv}{dx} = \frac{2x^3 - 2x - (2x^3 + 2x)}{(x^2 - 1)^2}$
$\frac{dv}{dx} = \frac{2x^3 - 2x - 2x^3 - 2x}{(x^2 - 1)^2} = \frac{-4x}{(x^2 - 1)^2}$.

**Combine $\frac{du}{dx}$ and $\frac{dv}{dx}$:**
$\frac{dy}{dx} = x^{\cos x} \left[-\sin x \log x + \frac{\cos x}{x}\right] - \frac{4x}{(x^2 - 1)^2}$.

---

**11. $(x \cos x)^x + (x \sin x)^{1/x}$**

**Reasoning:**
This is a sum of two functions, each of the form $f(x)^{g(x)}$. Logarithmic differentiation is required for each term.

**Step-by-step solution:**
Let $y = (x \cos x)^x + (x \sin x)^{1/x}$.
Let $u = (x \cos x)^x$ and $v = (x \sin x)^{1/x}$. So $y = u + v$.
Then $\frac{dy}{dx} = \frac{du}{dx} + \frac{dv}{dx}$.

**Find $\frac{du}{dx}$ for $u = (x \cos x)^x$:**
Take $\log$ on both sides: $\log u = x \log(x \cos x)$.
Using product rule for $\log(x \cos x) = \log x + \log(\cos x)$.
So, $\log u = x (\log x + \log(\cos x))$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{u} \frac{du}{dx} = 1 \cdot (\log x + \log(\cos x)) + x \cdot \frac{d}{dx}(\log x + \log(\cos x))$.
$\frac{d}{dx}(\log x + \log(\cos x)) = \frac{1}{x} + \frac{1}{\cos x} \cdot (-\sin x) = \frac{1}{x} - \tan x$.

So, $\frac{1}{u} \frac{du}{dx} = \log(x \cos x) + x \left(\frac{1}{x} - \tan x\right) = \log(x \cos x) + 1 - x \tan x$.
$\frac{du}{dx} = (x \cos x)^x [\log(x \cos x) + 1 - x \tan x]$.

**Find $\frac{dv}{dx}$ for $v = (x \sin x)^{1/x}$:**
Take $\log$ on both sides: $\log v = \frac{1}{x} \log(x \sin x)$.
Using product rule for $\log(x \sin x) = \log x + \log(\sin x)$.
So, $\log v = \frac{1}{x} (\log x + \log(\sin x))$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{v} \frac{dv}{dx} = \frac{d}{dx}\left(\frac{1}{x}\right) \cdot (\log x + \log(\sin x)) + \frac{1}{x} \cdot \frac{d}{dx}(\log x + \log(\sin x))$.
$\frac{d}{dx}\left(\frac{1}{x}\right) = -\frac{1}{x^2}$.
$\frac{d}{dx}(\log x + \log(\sin x)) = \frac{1}{x} + \frac{1}{\sin x} \cdot \cos x = \frac{1}{x} + \cot x$.

So, $\frac{1}{v} \frac{dv}{dx} = -\frac{1}{x^2} (\log x + \log(\sin x)) + \frac{1}{x} \left(\frac{1}{x} + \cot x\right)$.
$\frac{1}{v} \frac{dv}{dx} = -\frac{\log(x \sin x)}{x^2} + \frac{1}{x^2} + \frac{\cot x}{x} = \frac{1 - \log(x \sin x) + x \cot x}{x^2}$.
$\frac{dv}{dx} = (x \sin x)^{1/x} \left[\frac{1 + x \cot x - \log(x \sin x)}{x^2}\right]$.

**Combine $\frac{du}{dx}$ and $\frac{dv}{dx}$:**
$\frac{dy}{dx} = (x \cos x)^x [\log(x \cos x) + 1 - x \tan x] + (x \sin x)^{1/x} \left[\frac{1 + x \cot x - \log(x \sin x)}{x^2}\right]$.

---

**Find $\frac{dy}{dx}$ of the functions given in Exercises 12 to 15.**

**12. $x^y + y^x = 1$**

**Reasoning:**
This is an implicit differentiation problem involving terms of the form $f(x)^{g(x)}$. We use logarithmic differentiation for $x^y$ and $y^x$, and then differentiate the entire equation.

**Step-by-step solution:**
Let $u = x^y$ and $v = y^x$. Then the equation is $u + v = 1$.
Differentiating with respect to $x$: $\frac{du}{dx} + \frac{dv}{dx} = 0$.

**Find $\frac{du}{dx}$ for $u = x^y$:**
Take $\log$ on both sides: $\log u = y \log x$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{u} \frac{du}{dx} = \frac{dy}{dx} \log x + y \cdot \frac{1}{x}$.
$\frac{du}{dx} = x^y \left[\frac{dy}{dx} \log x + \frac{y}{x}\right]$.

**Find $\frac{dv}{dx}$ for $v = y^x$:**
Take $\log$ on both sides: $\log v = x \log y$.
Differentiate with respect to $x$ using the product rule:
$\frac{1}{v} \frac{dv}{dx} = 1 \cdot \log y + x \cdot \frac{1}{y} \frac{dy}{dx}$.
$\frac{dv}{dx} = y^x \left[\log y + \frac{x}{y} \frac{dy}{dx}\right]$.

**Substitute $\frac{du}{dx}$ and $\frac{dv}{dx}$ into $\frac{du}{dx} + \frac{dv}{dx} = 0$:**
$x^y \left[\frac{dy}{dx} \log x + \frac{y}{x}\right] + y^x \left[\log y + \frac{x}{y} \frac{dy}{dx}\right] = 0$
$x^y \log x \frac{dy}{dx} + x^y \frac{y}{x} + y^x \log y + y^x \frac{x}{y} \frac{dy}{dx} = 0$
Group terms with $\frac{dy}{dx}$:
$\left(x^y \log x + y^x \frac{x}{y}\right) \frac{dy}{dx} = -x^y \frac{y}{x} - y^x \log y$
$\left(x^y \log x + x y^{x-1}\right) \frac{dy}{dx} = -\left(y x^{y-1} + y^x \log y\right)$
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = -\frac{y x^{y-1} + y^x \log y}{x^y \log x + x y^{x-1}}$.

---

**13. $y^x = x^y$**

**Reasoning:**
This is an implicit differentiation problem involving terms of the form $f(x)^{g(x)}$. We use logarithmic differentiation.

**Step-by-step solution:**
Given equation: $y^x = x^y$.
Take the natural logarithm of both sides:
$\log(y^x) = \log(x^y)$
$x \log y = y \log x$.

Now, differentiate both sides with respect to $x$ using the product rule:
$\frac{d}{dx}(x \log y) = \frac{d}{dx}(y \log x)$
$1 \cdot \log y + x \cdot \frac{1}{y} \frac{dy}{dx} = \frac{dy}{dx} \cdot \log x + y \cdot \frac{1}{x}$
$\log y + \frac{x}{y} \frac{dy}{dx} = \log x \frac{dy}{dx} + \frac{y}{x}$.

Gather terms with $\frac{dy}{dx}$:
$\frac{x}{y} \frac{dy}{dx} - \log x \frac{dy}{dx} = \frac{y}{x} - \log y$
$\frac{dy}{dx}\left(\frac{x}{y} - \log x\right) = \frac{y}{x} - \log y$
$\frac{dy}{dx}\left(\frac{x - y \log x}{y}\right) = \frac{y - x \log y}{x}$.

Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = \frac{y(y - x \log y)}{x(x - y \log x)}$.

---

**14. $(\cos x)^y = (\cos y)^x$**

**Reasoning:**
This is an implicit differentiation problem involving terms of the form $f(x)^{g(x)}$. We use logarithmic differentiation.

**Step-by-step solution:**
Given equation: $(\cos x)^y = (\cos y)^x$.
Take the natural logarithm of both sides:
$\log((\cos x)^y) = \log((\cos y)^x)$
$y \log(\cos x) = x \log(\cos y)$.

Now, differentiate both sides with respect to $x$ using the product rule:
$\frac{d}{dx}(y \log(\cos x)) = \frac{d}{dx}(x \log(\cos y))$
$\frac{dy}{dx} \cdot \log(\cos x) + y \cdot \frac{1}{\cos x} (-\sin x) = 1 \cdot \log(\cos y) + x \cdot \frac{1}{\cos y} (-\sin y) \frac{dy}{dx}$
$\log(\cos x) \frac{dy}{dx} - y \tan x = \log(\cos y) - x \tan y \frac{dy}{dx}$.

Gather terms with $\frac{dy}{dx}$:
$\log(\cos x) \frac{dy}{dx} + x \tan y \frac{dy}{dx} = \log(\cos y) + y \tan x$
$\frac{dy}{dx}(\log(\cos x) + x \tan y) = \log(\cos y) + y \tan x$.
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = \frac{\log(\cos y) + y \tan x}{\log(\cos x) + x \tan y}$.

---

**15. $x y = e^{(x - y)}$**

**Reasoning:**
This is an implicit differentiation problem. We can take the natural logarithm of both sides to simplify the exponential term, or differentiate directly using the product rule for $xy$ and chain rule for $e^{(x-y)}$. Taking log will be cleaner.

**Step-by-step solution (using logarithmic differentiation):**
Given equation: $xy = e^{(x - y)}$.
Take the natural logarithm of both sides:
$\log(xy) = \log(e^{(x - y)})$
$\log x + \log y = x - y$.

Now, differentiate both sides with respect to $x$:
$\frac{d}{dx}(\log x) + \frac{d}{dx}(\log y) = \frac{d}{dx}(x) - \frac{d}{dx}(y)$
$\frac{1}{x} + \frac{1}{y} \frac{dy}{dx} = 1 - \frac{dy}{dx}$.

Gather terms with $\frac{dy}{dx}$:
$\frac{1}{y} \frac{dy}{dx} + \frac{dy}{dx} = 1 - \frac{1}{x}$
$\frac{dy}{dx}\left(\frac{1}{y} + 1\right) = \frac{x - 1}{x}$
$\frac{dy}{dx}\left(\frac{1 + y}{y}\right) = \frac{x - 1}{x}$.
Solve for $\frac{dy}{dx}$:
$\frac{dy}{dx} = \frac{y(x - 1)}{x(1 + y)}$.

---

**16. Find the derivative of the function given by $f(x) = (1 + x)(1 + x^2)(1 + x^4)(1 + x^8)$ and hence find $f'(1)$.**

**Reasoning:**
This is a product of multiple functions. Logarithmic differentiation is a good approach. Alternatively, one could multiply out the terms, but this would be tedious. Notice the pattern $(1+a)(1+a^2)$ - it's a part of $(1-a)(1+a)(1+a^2)... = (1-a^2)(1+a^2)...$ but here we have $(1+x)$ instead of $(1-x)$. This might hint at a different simplification.

**Step-by-step solution (using logarithmic differentiation):**
Let $y = (1 + x)(1 + x^2)(1 + x^4)(1 + x^8)$.
Take the natural logarithm of both sides:
$\log y = \log(1 + x) + \log(1 + x^2) + \log(1 + x^4) + \log(1 + x^8)$.

Differentiate both sides with respect to $x$:
$\frac{1}{y} \frac{dy}{dx} = \frac{1}{1 + x} \cdot 1 + \frac{1}{1 + x^2} \cdot 2x + \frac{1}{1 + x^4} \cdot 4x^3 + \frac{1}{1 + x^8} \cdot 8x^7$.

Multiply by $y$:
$\frac{dy}{dx} = (1 + x)(1 + x^2)(1 + x^4)(1 + x^8) \left[\frac{1}{1 + x} + \frac{2x}{1 + x^2} + \frac{4x^3}{1 + x^4} + \frac{8x^7}{1 + x^8}\right]$.

**Now, find $f'(1)$:**
Substitute $x = 1$ into the expression for $\frac{dy}{dx}$:
$f'(1) = (1 + 1)(1 + 1^2)(1 + 1^4)(1 + 1^8) \left[\frac{1}{1 + 1} + \frac{2(1)}{1 + 1^2} + \frac{4(1)^3}{1 + 1^4} + \frac{8(1)^7}{1 + 1^8}\right]$
$f'(1) = (2)(2)(2)(2) \left[\frac{1}{2} + \frac{2}{2} + \frac{4}{2} + \frac{8}{2}\right]$
$f'(1) = 16 \left[\frac{1}{2} + 1 + 2 + 4\right]$
$f'(1) = 16 \left[\frac{1}{2} + 7\right]$
$f'(1) = 16 \left[\frac{1 + 14}{2}\right]$
$f'(1) = 16 \left[\frac{15}{2}\right]$
$f'(1) = 8 \cdot 15 = 120$.

---

**17. Differentiate $(x^2 - 5x + 8)(x^3 + 7x + 9)$ in three ways mentioned below:**
**(i) by using product rule**
**(ii) by expanding the product to obtain a single polynomial.**
**(iii) by logarithmic differentiation.**
**Do they all give the same answer?**

**Reasoning:**
We will perform the differentiation using the three specified methods and compare the results. They should all yield the same answer.

**Step-by-step solution:**
Let $f(x) = (x^2 - 5x + 8)(x^3 + 7x + 9)$.

**(i) By using the product rule:**
Let $u = x^2 - 5x + 8$ and $v = x^3 + 7x + 9$.
Then $u' = \frac{d}{dx}(x^2 - 5x + 8) = 2x - 5$.
And $v' = \frac{d}{dx}(x^3 + 7x + 9) = 3x^2 + 7$.
Using the product rule, $f'(x) = u'v + uv'$:
$f'(x) = (2x - 5)(x^3 + 7x + 9) + (x^2 - 5x + 8)(3x^2 + 7)$.

Expand this expression:
$(2x - 5)(x^3 + 7x + 9) = 2x^4 + 14x^2 + 18x - 5x^3 - 35x - 45 = 2x^4 - 5x^3 + 14x^2 - 17x - 45$.
$(x^2 - 5x + 8)(3x^2 + 7) = 3x^4 + 7x^2 - 15x^3 - 35x + 24x^2 + 56 = 3x^4 - 15x^3 + 31x^2 - 35x + 56$.

Add the two expanded terms:
$f'(x) = (2x^4 - 5x^3 + 14x^2 - 17x - 45) + (3x^4 - 15x^3 + 31x^2 - 35x + 56)$
$f'(x) = 5x^4 - 20x^3 + 45x^2 - 52x + 11$.

**(ii) By expanding the product to obtain a single polynomial:**
$f(x) = (x^2 - 5x + 8)(x^3 + 7x + 9)$
$f(x) = x^2(x^3 + 7x + 9) - 5x(x^3 + 7x + 9) + 8(x^3 + 7x + 9)$
$f(x) = (x^5 + 7x^3 + 9x^2) - (5x^4 + 35x^2 + 45x) + (8x^3 + 56x + 72)$
$f(x) = x^5 - 5x^4 + (7x^3 + 8x^3) + (9x^2 - 35x^2) + (-45x + 56x) + 72$
$f(x) = x^5 - 5x^4 + 15x^3 - 26x^2 + 11x + 72$.

Now, differentiate this polynomial term by term:
$f'(x) = \frac{d}{dx}(x^5) - \frac{d}{dx}(5x^4) + \frac{d}{dx}(15x^3) - \frac{d}{dx}(26x^2) + \frac{d}{dx}(11x) + \frac{d}{dx}(72)$
$f'(x) = 5x^4 - 20x^3 + 45x^2 - 52x + 11$.

**(iii) By logarithmic differentiation:**
Let $y = (x^2 - 5x + 8)(x^3 + 7x + 9)$.
Take the natural logarithm of both sides:
$\log y = \log(x^2 - 5x + 8) + \log(x^3 + 7x + 9)$.

Differentiate both sides with respect to $x$:
$\frac{1}{y} \frac{dy}{dx} = \frac{d}{dx}(\log(x^2 - 5x + 8)) + \frac{d}{dx}(\log(x^3 + 7x + 9))$.
$\frac{d}{dx}(\log(x^2 - 5x + 8)) = \frac{2x - 5}{x^2 - 5x + 8}$.
$\frac{d}{dx}(\log(x^3 + 7x + 9)) = \frac{3x^2 + 7}{x^3 + 7x + 9}$.

So, $\frac{1}{y} \frac{dy}{dx} = \frac{2x - 5}{x^2 - 5x + 8} + \frac{3x^2 + 7}{x^3 + 7x + 9}$.
Multiply by $y$:
$\frac{dy}{dx} = (x^2 - 5x + 8)(x^3 + 7x + 9) \left[\frac{2x - 5}{x^2 - 5x + 8} + \frac{3x^2 + 7}{x^3 + 7x + 9}\right]$.
$\frac{dy}{dx} = (x^2 - 5x + 8)(x^3 + 7x + 9) \frac{2x - 5}{x^2 - 5x + 8} + (x^2 - 5x + 8)(x^3 + 7x + 9) \frac{3x^2 + 7}{x^3 + 7x + 9}$.
$\frac{dy}{dx} = (2x - 5)(x^3 + 7x + 9) + (x^2 - 5x + 8)(3x^2 + 7)$.

This expression is identical to the one obtained by the product rule in (i). Expanding it would again lead to $5x^4 - 20x^3 + 45x^2 - 52x + 11$.

**Comparison:**
Yes, all three methods yield the same answer: $f'(x) = 5x^4 - 20x^3 + 45x^2 - 52x + 11$.

---

**18. If $u, v$ and $w$ are functions of $x$, then show that $\frac{d}{dx}(u \cdot v \cdot w) = \frac{du}{dx} \cdot v \cdot w + u \cdot \frac{dv}{dx} \cdot w + u \cdot v \cdot \frac{dw}{dx}$ in two ways - first by repeated application of product rule, second by logarithmic differentiation.**

**Reasoning:**
We need to prove the product rule for three functions using two different methods.

**Step-by-step solution:**
Let $y = u \cdot v \cdot w$.

**First way: Repeated application of the product rule:**
Consider $y = (uv)w$. Let $A = uv$.
Using the product rule for $y = Aw$:
$\frac{dy}{dx} = \frac{dA}{dx} w + A \frac{dw}{dx}$.

Now, find $\frac{dA}{dx}$. Using the product rule for $A = uv$:
$\frac{dA}{dx} = \frac{du}{dx} v + u \frac{dv}{dx}$.

Substitute $\frac{dA}{dx}$ back into the expression for $\frac{dy}{dx}$:
$\frac{dy}{dx} = \left(\frac{du}{dx} v + u \frac{dv}{dx}\right) w + (uv) \frac{dw}{dx}$
$\frac{dy}{dx} = \frac{du}{dx} vw + u \frac{dv}{dx} w + uv \frac{dw}{dx}$.
This matches the desired formula.

**Second way: By logarithmic differentiation:**
Let $y = u \cdot v \cdot w$.
Take the natural logarithm of both sides:
$\log y = \log(u \cdot v \cdot w)$.
Using logarithm properties:
$\log y = \log u + \log v + \log w$.

Now, differentiate both sides with respect to $x$:
$\frac{1}{y} \frac{dy}{dx} = \frac{1}{u} \frac{du}{dx} + \frac{1}{v} \frac{dv}{dx} + \frac{1}{w} \frac{dw}{dx}$.

Multiply by $y$:
$\frac{dy}{dx} = y \left(\frac{1}{u} \frac{du}{dx} + \frac{1}{v} \frac{dv}{dx} + \frac{1}{w} \frac{dw}{dx}\right)$.
Substitute $y = uvw$:
$\frac{dy}{dx} = (uvw) \left(\frac{1}{u} \frac{du}{dx}\right) + (uvw) \left(\frac{1}{v} \frac{dv}{dx}\right) + (uvw) \left(\frac{1}{w} \frac{dw}{dx}\right)$
$\frac{dy}{dx} = v w \frac{du}{dx} + u w \frac{dv}{dx} + u v \frac{dw}{dx}$.
Rearranging the terms, we get:
$\frac{dy}{dx} = \frac{du}{dx} vw + u \frac{dv}{dx} w + uv \frac{dw}{dx}$.
This also matches the desired formula.

---

#### **Exercise 5.6**

**If $x$ and $y$ are connected parametrically by the equations given in Exercises 1 to 10, without eliminating the parameter, Find $\frac{dy}{dx}$.**

**1. $x = 2at^2, y = at^4$**

**Reasoning:**
For parametric equations, we find $\frac{dy}{dt}$ and $\frac{dx}{dt}$ and then use the formula $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$.

**Step-by-step solution:**
Given $x = 2at^2$ and $y = at^4$.

1.  Find $\frac{dx}{dt}$:
    $\frac{dx}{dt} = \frac{d}{dt}(2at^2) = 2a \cdot 2t = 4at$.

2.  Find $\frac{dy}{dt}$:
    $\frac{dy}{dt} = \frac{d}{dt}(at^4) = a \cdot 4t^3 = 4at^3$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{4at^3}{4at} = t^2$.

---

**2. $x = a \cos \theta, y = b \cos \theta$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{d\theta}$ and $\frac{dy}{d\theta}$ and then use $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta}$.

**Step-by-step solution:**
Given $x = a \cos \theta$ and $y = b \cos \theta$.

1.  Find $\frac{dx}{d\theta}$:
    $\frac{dx}{d\theta} = \frac{d}{d\theta}(a \cos \theta) = -a \sin \theta$.

2.  Find $\frac{dy}{d\theta}$:
    $\frac{dy}{d\theta} = \frac{d}{d\theta}(b \cos \theta) = -b \sin \theta$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta} = \frac{-b \sin \theta}{-a \sin \theta}$.
    Assuming $\sin \theta \neq 0$:
    $\frac{dy}{dx} = \frac{b}{a}$.

---

**3. $x = \sin t, y = \cos 2t$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{dt}$ and $\frac{dy}{dt}$ and then use $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$.

**Step-by-step solution:**
Given $x = \sin t$ and $y = \cos 2t$.

1.  Find $\frac{dx}{dt}$:
    $\frac{dx}{dt} = \frac{d}{dt}(\sin t) = \cos t$.

2.  Find $\frac{dy}{dt}$:
    $\frac{dy}{dt} = \frac{d}{dt}(\cos 2t) = -\sin 2t \cdot \frac{d}{dt}(2t) = -2 \sin 2t$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{-2 \sin 2t}{\cos t}$.
    Using the identity $\sin 2t = 2 \sin t \cos t$:
    $\frac{dy}{dx} = \frac{-2 (2 \sin t \cos t)}{\cos t}$.
    Assuming $\cos t \neq 0$:
    $\frac{dy}{dx} = -4 \sin t$.

---

**4. $x = 4t, y = \frac{4}{t}$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{dt}$ and $\frac{dy}{dt}$ and then use $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$.

**Step-by-step solution:**
Given $x = 4t$ and $y = \frac{4}{t}$.

1.  Find $\frac{dx}{dt}$:
    $\frac{dx}{dt} = \frac{d}{dt}(4t) = 4$.

2.  Find $\frac{dy}{dt}$:
    $\frac{dy}{dt} = \frac{d}{dt}(4t^{-1}) = 4(-1)t^{-2} = -\frac{4}{t^2}$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{-4/t^2}{4} = -\frac{1}{t^2}$.

---

**5. $x = \cos \theta - \cos 2\theta, y = \sin \theta - \sin 2\theta$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{d\theta}$ and $\frac{dy}{d\theta}$ and then use $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta}$.

**Step-by-step solution:**
Given $x = \cos \theta - \cos 2\theta$ and $y = \sin \theta - \sin 2\theta$.

1.  Find $\frac{dx}{d\theta}$:
    $\frac{dx}{d\theta} = \frac{d}{d\theta}(\cos \theta - \cos 2\theta) = -\sin \theta - (-\sin 2\theta \cdot 2) = -\sin \theta + 2 \sin 2\theta$.

2.  Find $\frac{dy}{d\theta}$:
    $\frac{dy}{d\theta} = \frac{d}{d\theta}(\sin \theta - \sin 2\theta) = \cos \theta - (\cos 2\theta \cdot 2) = \cos \theta - 2 \cos 2\theta$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta} = \frac{\cos \theta - 2 \cos 2\theta}{-\sin \theta + 2 \sin 2\theta}$.

---

**6. $x = a(\theta - \sin \theta), y = a(1 - \cos \theta)$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{d\theta}$ and $\frac{dy}{d\theta}$ and then use $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta}$.

**Step-by-step solution:**
Given $x = a(\theta - \sin \theta)$ and $y = a(1 - \cos \theta)$.

1.  Find $\frac{dx}{d\theta}$:
    $\frac{dx}{d\theta} = \frac{d}{d\theta}(a\theta - a\sin \theta) = a(1 - \cos \theta)$.

2.  Find $\frac{dy}{d\theta}$:
    $\frac{dy}{d\theta} = \frac{d}{d\theta}(a - a\cos \theta) = 0 - a(-\sin \theta) = a \sin \theta$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta} = \frac{a \sin \theta}{a(1 - \cos \theta)} = \frac{\sin \theta}{1 - \cos \theta}$.
    Using half-angle identities ($\sin \theta = 2 \sin(\frac{\theta}{2}) \cos(\frac{\theta}{2})$ and $1 - \cos \theta = 2 \sin^2(\frac{\theta}{2})$):
    $\frac{dy}{dx} = \frac{2 \sin(\frac{\theta}{2}) \cos(\frac{\theta}{2})}{2 \sin^2(\frac{\theta}{2})} = \frac{\cos(\frac{\theta}{2})}{\sin(\frac{\theta}{2})} = \cot\left(\frac{\theta}{2}\right)$.

---

**7. $x = \frac{\sin^3 t}{\sqrt{\cos 2t}}, y = \frac{\cos^3 t}{\sqrt{\cos 2t}}$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{dt}$ and $\frac{dy}{dt}$ and then use $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$. This problem involves the quotient rule and chain rule for each derivative with respect to $t$.

**Step-by-step solution:**
Given $x = \frac{\sin^3 t}{\sqrt{\cos 2t}}$ and $y = \frac{\cos^3 t}{\sqrt{\cos 2t}}$.
Notice that $y = x \frac{\cos^3 t}{\sin^3 t} = x \cot^3 t$. This might simplify finding $\frac{dy}{dx}$ if we can differentiate $y$ with respect to $x$ directly. However, the problem states "without eliminating the parameter", so we'll follow the standard approach.

Let $N_x = \sin^3 t$, $D = \sqrt{\cos 2t} = (\cos 2t)^{1/2}$.
Let $N_y = \cos^3 t$.

1.  Find $\frac{dN_x}{dt}$: $3 \sin^2 t \cos t$.
2.  Find $\frac{dN_y}{dt}$: $3 \cos^2 t (-\sin t) = -3 \cos^2 t \sin t$.
3.  Find $\frac{dD}{dt}$: $\frac{1}{2}(\cos 2t)^{-1/2} (-\sin 2t \cdot 2) = -\frac{\sin 2t}{\sqrt{\cos 2t}}$.

Now, apply the quotient rule for $\frac{dx}{dt} = \frac{N_x' D - N_x D'}{D^2}$:
$\frac{dx}{dt} = \frac{(3 \sin^2 t \cos t)\sqrt{\cos 2t} - (\sin^3 t)(-\frac{\sin 2t}{\sqrt{\cos 2t}})}{\cos 2t}$
Multiply numerator and denominator by $\sqrt{\cos 2t}$ to clear the fraction in the numerator:
$\frac{dx}{dt} = \frac{(3 \sin^2 t \cos t)\cos 2t + \sin^3 t \sin 2t}{(\cos 2t)^{3/2}}$.

Apply the quotient rule for $\frac{dy}{dt} = \frac{N_y' D - N_y D'}{D^2}$:
$\frac{dy}{dt} = \frac{(-3 \cos^2 t \sin t)\sqrt{\cos 2t} - (\cos^3 t)(-\frac{\sin 2t}{\sqrt{\cos 2t}})}{\cos 2t}$
Multiply numerator and denominator by $\sqrt{\cos 2t}$ to clear the fraction in the numerator:
$\frac{dy}{dt} = \frac{(-3 \cos^2 t \sin t)\cos 2t + \cos^3 t \sin 2t}{(\cos 2t)^{3/2}}$.

Now, find $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$:
$\frac{dy}{dx} = \frac{(-3 \cos^2 t \sin t)\cos 2t + \cos^3 t \sin 2t}{(3 \sin^2 t \cos t)\cos 2t + \sin^3 t \sin 2t}$.

Factor out common terms:
Numerator: $\cos^2 t \sin t (-3 \cos 2t + \cos t \frac{\sin 2t}{\sin t}) = \cos^2 t \sin t (-3 \cos 2t + \cos t (2 \cos t)) = \cos^2 t \sin t (-3 \cos 2t + 2 \cos^2 t)$.
Denominator: $\sin^2 t \cos t (3 \cos 2t + \sin t \frac{\sin 2t}{\cos t}) = \sin^2 t \cos t (3 \cos 2t + \sin t (2 \sin t)) = \sin^2 t \cos t (3 \cos 2t + 2 \sin^2 t)$.

This simplification is getting complicated. Let's try to simplify the fraction for $\frac{dy}{dx}$ before full expansion.
$\frac{dy}{dx} = \frac{\cos^2 t \sin t (-3 \cos 2t + \cos t (2 \cos t))}{\sin^2 t \cos t (3 \cos 2t + \sin t (2 \sin t))} = \frac{\cos t (-3 \cos 2t + 2 \cos^2 t)}{\sin t (3 \cos 2t + 2 \sin^2 t)}$.
We know $\cos 2t = 2\cos^2 t - 1$ and $\cos 2t = 1 - 2\sin^2 t$.

Numerator: $\cos t (-3(2\cos^2 t - 1) + 2\cos^2 t) = \cos t (-6\cos^2 t + 3 + 2\cos^2 t) = \cos t (3 - 4\cos^2 t)$.
Denominator: $\sin t (3(1 - 2\sin^2 t) + 2\sin^2 t) = \sin t (3 - 6\sin^2 t + 2\sin^2 t) = \sin t (3 - 4\sin^2 t)$.

So, $\frac{dy}{dx} = \frac{\cos t (3 - 4\cos^2 t)}{\sin t (3 - 4\sin^2 t)}$.
We know $\cos 3t = 4\cos^3 t - 3\cos t = -\cos t (3 - 4\cos^2 t)$.
And $\sin 3t = 3\sin t - 4\sin^3 t = \sin t (3 - 4\sin^2 t)$.
So, $\frac{dy}{dx} = \frac{-\cos 3t / \cos t}{\sin 3t / \sin t} = \frac{-\cos 3t \sin t}{\sin 3t \cos t} = -\cot 3t \tan t$.
This is a more simplified form.

---

**8. $x = a\left(\cos t + \log \tan \frac{t}{2}\right), y = a \sin t$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{dt}$ and $\frac{dy}{dt}$ and then use $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$.

**Step-by-step solution:**
Given $x = a\left(\cos t + \log \tan \frac{t}{2}\right)$ and $y = a \sin t$.

1.  Find $\frac{dx}{dt}$:
    $\frac{dx}{dt} = a \frac{d}{dt}\left(\cos t + \log \tan \frac{t}{2}\right)$
    $\frac{d}{dt}(\cos t) = -\sin t$.
    $\frac{d}{dt}\left(\log \tan \frac{t}{2}\right) = \frac{1}{\tan \frac{t}{2}} \cdot \sec^2 \frac{t}{2} \cdot \frac{1}{2}$ (using chain rule)
    $= \frac{\cos \frac{t}{2}}{\sin \frac{t}{2}} \cdot \frac{1}{\cos^2 \frac{t}{2}} \cdot \frac{1}{2} = \frac{1}{2 \sin \frac{t}{2} \cos \frac{t}{2}} = \frac{1}{\sin t}$.
    So, $\frac{dx}{dt} = a \left(-\sin t + \frac{1}{\sin t}\right) = a \left(\frac{-\sin^2 t + 1}{\sin t}\right) = a \frac{\cos^2 t}{\sin t}$.

2.  Find $\frac{dy}{dt}$:
    $\frac{dy}{dt} = \frac{d}{dt}(a \sin t) = a \cos t$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{a \cos t}{a \frac{\cos^2 t}{\sin t}}$.
    Assuming $\cos t \neq 0$:
    $\frac{dy}{dx} = \frac{\cos t \cdot \sin t}{\cos^2 t} = \frac{\sin t}{\cos t} = \tan t$.

---

**9. $x = a \sec \theta, y = b \tan \theta$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{d\theta}$ and $\frac{dy}{d\theta}$ and then use $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta}$.

**Step-by-step solution:**
Given $x = a \sec \theta$ and $y = b \tan \theta$.

1.  Find $\frac{dx}{d\theta}$:
    $\frac{dx}{d\theta} = \frac{d}{d\theta}(a \sec \theta) = a \sec \theta \tan \theta$.

2.  Find $\frac{dy}{d\theta}$:
    $\frac{dy}{d\theta} = \frac{d}{d\theta}(b \tan \theta) = b \sec^2 \theta$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta} = \frac{b \sec^2 \theta}{a \sec \theta \tan \theta}$.
    Assuming $\sec \theta \neq 0$:
    $\frac{dy}{dx} = \frac{b \sec \theta}{a \tan \theta} = \frac{b}{a} \cdot \frac{1/\cos \theta}{\sin \theta/\cos \theta} = \frac{b}{a} \cdot \frac{1}{\sin \theta} = \frac{b}{a} \csc \theta$.

---

**10. $x = a(\cos \theta + \theta \sin \theta), y = a(\sin \theta - \theta \cos \theta)$**

**Reasoning:**
Similar to problem 1, we find $\frac{dx}{d\theta}$ and $\frac{dy}{d\theta}$ and then use $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta}$. This involves the product rule for $\theta \sin \theta$ and $\theta \cos \theta$.

**Step-by-step solution:**
Given $x = a(\cos \theta + \theta \sin \theta)$ and $y = a(\sin \theta - \theta \cos \theta)$.

1.  Find $\frac{dx}{d\theta}$:
    $\frac{dx}{d\theta} = a \frac{d}{d\theta}(\cos \theta + \theta \sin \theta)$
    $\frac{d}{d\theta}(\cos \theta) = -\sin \theta$.
    $\frac{d}{d\theta}(\theta \sin \theta) = 1 \cdot \sin \theta + \theta \cdot \cos \theta = \sin \theta + \theta \cos \theta$ (product rule).
    So, $\frac{dx}{d\theta} = a (-\sin \theta + \sin \theta + \theta \cos \theta) = a(\theta \cos \theta)$.

2.  Find $\frac{dy}{d\theta}$:
    $\frac{dy}{d\theta} = a \frac{d}{d\theta}(\sin \theta - \theta \cos \theta)$
    $\frac{d}{d\theta}(\sin \theta) = \cos \theta$.
    $\frac{d}{d\theta}(\theta \cos \theta) = 1 \cdot \cos \theta + \theta \cdot (-\sin \theta) = \cos \theta - \theta \sin \theta$ (product rule).
    So, $\frac{dy}{d\theta} = a (\cos \theta - (\cos \theta - \theta \sin \theta)) = a (\cos \theta - \cos \theta + \theta \sin \theta) = a(\theta \sin \theta)$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/d\theta}{dx/d\theta} = \frac{a(\theta \sin \theta)}{a(\theta \cos \theta)}$.
    Assuming $a \theta \cos \theta \neq 0$:
    $\frac{dy}{dx} = \frac{\sin \theta}{\cos \theta} = \tan \theta$.

---

**11. If $x = \sqrt{a^{\sin^{-1} t}}, y = \sqrt{a^{\cos^{-1} t}}$, show that $\frac{dy}{dx} = -\frac{y}{x}$.**

**Reasoning:**
This involves parametric equations where $x$ and $y$ are functions of $t$. We can use logarithmic differentiation for $x$ and $y$ individually to simplify their derivatives, or notice a relationship between $x$ and $y$ first.

**Step-by-step solution (Method 1: Direct parametric differentiation):**
Given $x = a^{\frac{1}{2}\sin^{-1} t}$ and $y = a^{\frac{1}{2}\cos^{-1} t}$.

1.  Find $\frac{dx}{dt}$:
    $\frac{dx}{dt} = a^{\frac{1}{2}\sin^{-1} t} \log a \cdot \frac{d}{dt}\left(\frac{1}{2}\sin^{-1} t\right)$
    $\frac{dx}{dt} = a^{\frac{1}{2}\sin^{-1} t} \log a \cdot \frac{1}{2\sqrt{1 - t^2}} = x \log a \cdot \frac{1}{2\sqrt{1 - t^2}}$.

2.  Find $\frac{dy}{dt}$:
    $\frac{dy}{dt} = a^{\frac{1}{2}\cos^{-1} t} \log a \cdot \frac{d}{dt}\left(\frac{1}{2}\cos^{-1} t\right)$
    $\frac{dy}{dt} = a^{\frac{1}{2}\cos^{-1} t} \log a \cdot \frac{-1}{2\sqrt{1 - t^2}} = y \log a \cdot \frac{-1}{2\sqrt{1 - t^2}}$.

3.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{y \log a \cdot \frac{-1}{2\sqrt{1 - t^2}}}{x \log a \cdot \frac{1}{2\sqrt{1 - t^2}}}$.
    Assuming $\log a \neq 0$ and $2\sqrt{1-t^2} \neq 0$:
    $\frac{dy}{dx} = -\frac{y}{x}$.

**Step-by-step solution (Method 2: Finding a relationship between $x$ and $y$):**
Given $x = a^{\frac{1}{2}\sin^{-1} t}$ and $y = a^{\frac{1}{2}\cos^{-1} t}$.
Take the natural logarithm of both expressions:
$\log x = \frac{1}{2}\sin^{-1} t \log a$  (Equation 1)
$\log y = \frac{1}{2}\cos^{-1} t \log a$  (Equation 2)

Add Equation 1 and Equation 2:
$\log x + \log y = \frac{1}{2}(\sin^{-1} t + \cos^{-1} t) \log a$.
We know the identity $\sin^{-1} t + \cos^{-1} t = \frac{\pi}{2}$.
$\log x + \log y = \frac{1}{2} \cdot \frac{\pi}{2} \cdot \log a$
$\log(xy) = \frac{\pi}{4} \log a$.

Now, differentiate this implicit equation with respect to $x$:
$\frac{d}{dx}(\log x) + \frac{d}{dx}(\log y) = \frac{d}{dx}\left(\frac{\pi}{4} \log a\right)$
$\frac{1}{x} + \frac{1}{y} \frac{dy}{dx} = 0$ (since $\frac{\pi}{4} \log a$ is a constant).
$\frac{1}{y} \frac{dy}{dx} = -\frac{1}{x}$
$\frac{dy}{dx} = -\frac{y}{x}$.

Both methods yield the same result.

---

#### **Exercise 5.7**

**Find the second order derivatives of the functions given in Exercises 1 to 10.**

**1. $x^2 + 3x + 2$**

**Reasoning:**
To find the second order derivative, we first find the first derivative and then differentiate the first derivative.

**Step-by-step solution:**
Let $y = x^2 + 3x + 2$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(x^2 + 3x + 2) = 2x + 3$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}\left(\frac{dy}{dx}\right) = \frac{d}{dx}(2x + 3) = 2$.

---

**2. $x^{20}$**

**Reasoning:**
To find the second order derivative, we first find the first derivative and then differentiate the first derivative.

**Step-by-step solution:**
Let $y = x^{20}$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(x^{20}) = 20x^{19}$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(20x^{19}) = 20 \cdot 19x^{18} = 380x^{18}$.

---

**3. $x \cdot \cos x$**

**Reasoning:**
To find the second order derivative, we first find the first derivative using the product rule, and then differentiate the first derivative.

**Step-by-step solution:**
Let $y = x \cos x$.

1.  **First derivative $\frac{dy}{dx}$ (using product rule):**
    $\frac{dy}{dx} = \frac{d}{dx}(x) \cdot \cos x + x \cdot \frac{d}{dx}(\cos x)$
    $\frac{dy}{dx} = 1 \cdot \cos x + x \cdot (-\sin x) = \cos x - x \sin x$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(\cos x - x \sin x)$
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(\cos x) - \frac{d}{dx}(x \sin x)$.
    $\frac{d}{dx}(\cos x) = -\sin x$.
    $\frac{d}{dx}(x \sin x) = 1 \cdot \sin x + x \cdot \cos x = \sin x + x \cos x$ (product rule).
    So, $\frac{d^2y}{dx^2} = -\sin x - (\sin x + x \cos x)$
    $\frac{d^2y}{dx^2} = -\sin x - \sin x - x \cos x = -2 \sin x - x \cos x$.

---

**4. $\log x$**

**Reasoning:**
To find the second order derivative, we first find the first derivative and then differentiate the first derivative.

**Step-by-step solution:**
Let $y = \log x$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(\log x) = \frac{1}{x} = x^{-1}$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(x^{-1}) = -1 \cdot x^{-2} = -\frac{1}{x^2}$.

---

**5. $x^3 \log x$**

**Reasoning:**
To find the second order derivative, we first find the first derivative using the product rule, and then differentiate the first derivative (again using the product rule and sum/difference rules).

**Step-by-step solution:**
Let $y = x^3 \log x$.

1.  **First derivative $\frac{dy}{dx}$ (using product rule):**
    $\frac{dy}{dx} = \frac{d}{dx}(x^3) \cdot \log x + x^3 \cdot \frac{d}{dx}(\log x)$
    $\frac{dy}{dx} = 3x^2 \log x + x^3 \cdot \frac{1}{x} = 3x^2 \log x + x^2$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(3x^2 \log x + x^2)$
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(3x^2 \log x) + \frac{d}{dx}(x^2)$.
    For $\frac{d}{dx}(3x^2 \log x)$, use the product rule:
    $\frac{d}{dx}(3x^2) \cdot \log x + 3x^2 \cdot \frac{d}{dx}(\log x) = 6x \log x + 3x^2 \cdot \frac{1}{x} = 6x \log x + 3x$.
    For $\frac{d}{dx}(x^2)$, it is $2x$.
    So, $\frac{d^2y}{dx^2} = (6x \log x + 3x) + 2x = 6x \log x + 5x = x(6 \log x + 5)$.

---

**6. $e^x \sin 5x$**

**Reasoning:**
To find the second order derivative, we first find the first derivative using the product rule, and then differentiate the first derivative.

**Step-by-step solution:**
Let $y = e^x \sin 5x$.

1.  **First derivative $\frac{dy}{dx}$ (using product rule):**
    $\frac{dy}{dx} = \frac{d}{dx}(e^x) \cdot \sin 5x + e^x \cdot \frac{d}{dx}(\sin 5x)$
    $\frac{dy}{dx} = e^x \sin 5x + e^x (\cos 5x \cdot 5) = e^x \sin 5x + 5e^x \cos 5x$.
    $\frac{dy}{dx} = e^x (\sin 5x + 5 \cos 5x)$.

2.  **Second derivative $\frac{d^2y}{dx^2}$ (using product rule again):**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}[e^x (\sin 5x + 5 \cos 5x)]$
    Let $u = e^x$ and $v = \sin 5x + 5 \cos 5x$.
    $u' = e^x$.
    $v' = \frac{d}{dx}(\sin 5x) + \frac{d}{dx}(5 \cos 5x) = \cos 5x \cdot 5 + 5 (-\sin 5x \cdot 5) = 5 \cos 5x - 25 \sin 5x$.

    So, $\frac{d^2y}{dx^2} = u'v + uv'$
    $\frac{d^2y}{dx^2} = e^x (\sin 5x + 5 \cos 5x) + e^x (5 \cos 5x - 25 \sin 5x)$
    $\frac{d^2y}{dx^2} = e^x (\sin 5x + 5 \cos 5x + 5 \cos 5x - 25 \sin 5x)$
    $\frac{d^2y}{dx^2} = e^x (10 \cos 5x - 24 \sin 5x)$.

---

**7. $e^{6x} \cos 3x$**

**Reasoning:**
To find the second order derivative, we first find the first derivative using the product rule, and then differentiate the first derivative.

**Step-by-step solution:**
Let $y = e^{6x} \cos 3x$.

1.  **First derivative $\frac{dy}{dx}$ (using product rule):**
    $\frac{dy}{dx} = \frac{d}{dx}(e^{6x}) \cdot \cos 3x + e^{6x} \cdot \frac{d}{dx}(\cos 3x)$
    $\frac{dy}{dx} = (e^{6x} \cdot 6) \cos 3x + e^{6x} (-\sin 3x \cdot 3) = 6e^{6x} \cos 3x - 3e^{6x} \sin 3x$.
    $\frac{dy}{dx} = e^{6x} (6 \cos 3x - 3 \sin 3x)$.

2.  **Second derivative $\frac{d^2y}{dx^2}$ (using product rule again):**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}[e^{6x} (6 \cos 3x - 3 \sin 3x)]$
    Let $u = e^{6x}$ and $v = 6 \cos 3x - 3 \sin 3x$.
    $u' = 6e^{6x}$.
    $v' = \frac{d}{dx}(6 \cos 3x) - \frac{d}{dx}(3 \sin 3x) = 6(-\sin 3x \cdot 3) - 3(\cos 3x \cdot 3) = -18 \sin 3x - 9 \cos 3x$.

    So, $\frac{d^2y}{dx^2} = u'v + uv'$
    $\frac{d^2y}{dx^2} = 6e^{6x} (6 \cos 3x - 3 \sin 3x) + e^{6x} (-18 \sin 3x - 9 \cos 3x)$
    $\frac{d^2y}{dx^2} = e^{6x} [6(6 \cos 3x - 3 \sin 3x) + (-18 \sin 3x - 9 \cos 3x)]$
    $\frac{d^2y}{dx^2} = e^{6x} [36 \cos 3x - 18 \sin 3x - 18 \sin 3x - 9 \cos 3x]$
    $\frac{d^2y}{dx^2} = e^{6x} [27 \cos 3x - 36 \sin 3x]$.

---

**8. $\tan^{-1} x$**

**Reasoning:**
To find the second order derivative, we first find the first derivative and then differentiate the first derivative.

**Step-by-step solution:**
Let $y = \tan^{-1} x$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(\tan^{-1} x) = \frac{1}{1 + x^2} = (1 + x^2)^{-1}$.

2.  **Second derivative $\frac{d^2y}{dx^2}$ (using chain rule):**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}((1 + x^2)^{-1})$
    $\frac{d^2y}{dx^2} = -1 (1 + x^2)^{-2} \cdot \frac{d}{dx}(1 + x^2)$
    $\frac{d^2y}{dx^2} = -1 (1 + x^2)^{-2} \cdot (2x)$
    $\frac{d^2y}{dx^2} = -\frac{2x}{(1 + x^2)^2}$.

---

**9. $\log(\log x)$**

**Reasoning:**
To find the second order derivative, we first find the first derivative, and then differentiate the first derivative using the quotient rule or product rule with negative exponents.

**Step-by-step solution:**
Let $y = \log(\log x)$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{1}{\log x} \cdot \frac{d}{dx}(\log x) = \frac{1}{\log x} \cdot \frac{1}{x} = (x \log x)^{-1}$.

2.  **Second derivative $\frac{d^2y}{dx^2}$ (using chain rule for $(x \log x)^{-1}$ or quotient rule for $\frac{1}{x \log x}$):**
    Let's use the power/chain rule for $(x \log x)^{-1}$:
    $\frac{d^2y}{dx^2} = -1 (x \log x)^{-2} \cdot \frac{d}{dx}(x \log x)$.
    For $\frac{d}{dx}(x \log x)$, use the product rule: $1 \cdot \log x + x \cdot \frac{1}{x} = \log x + 1$.
    So, $\frac{d^2y}{dx^2} = -1 (x \log x)^{-2} (\log x + 1)$
    $\frac{d^2y}{dx^2} = -\frac{1 + \log x}{(x \log x)^2}$.

---

**10. $\sin(\log x)$**

**Reasoning:**
To find the second order derivative, we first find the first derivative using the chain rule, and then differentiate the first derivative using the quotient rule or product rule.

**Step-by-step solution:**
Let $y = \sin(\log x)$.

1.  **First derivative $\frac{dy}{dx}$ (using chain rule):**
    $\frac{dy}{dx} = \cos(\log x) \cdot \frac{d}{dx}(\log x) = \cos(\log x) \cdot \frac{1}{x} = \frac{\cos(\log x)}{x}$.

2.  **Second derivative $\frac{d^2y}{dx^2}$ (using quotient rule):**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}\left(\frac{\cos(\log x)}{x}\right)$.
    Let $u = \cos(\log x) \Rightarrow u' = -\sin(\log x) \cdot \frac{1}{x}$.
    Let $v = x \Rightarrow v' = 1$.
    $\frac{d^2y}{dx^2} = \frac{u'v - uv'}{v^2} = \frac{\left(-\sin(\log x) \cdot \frac{1}{x}\right) \cdot x - \cos(\log x) \cdot 1}{x^2}$
    $\frac{d^2y}{dx^2} = \frac{-\sin(\log x) - \cos(\log x)}{x^2} = -\frac{\sin(\log x) + \cos(\log x)}{x^2}$.

---

**11. If $y = 5 \cos x - 3 \sin x$, prove that $\frac{d^2y}{dx^2} + y = 0$.**

**Reasoning:**
We need to find the first and second derivatives of $y$, then substitute them into the given differential equation and show it holds true.

**Step-by-step solution:**
Given $y = 5 \cos x - 3 \sin x$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(5 \cos x - 3 \sin x)$
    $\frac{dy}{dx} = 5(-\sin x) - 3(\cos x) = -5 \sin x - 3 \cos x$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(-5 \sin x - 3 \cos x)$
    $\frac{d^2y}{dx^2} = -5(\cos x) - 3(-\sin x) = -5 \cos x + 3 \sin x$.

3.  **Substitute into the equation $\frac{d^2y}{dx^2} + y = 0$:**
    $(-5 \cos x + 3 \sin x) + (5 \cos x - 3 \sin x)$
    $= -5 \cos x + 3 \sin x + 5 \cos x - 3 \sin x$
    $= 0$.

Therefore, $\frac{d^2y}{dx^2} + y = 0$ is proven.

---

**12. If $y = \cos^{-1} x$, Find $\frac{d^2y}{dx^2}$ in terms of $y$ alone.**

**Reasoning:**
We need to find the first and second derivatives. The challenge is to express the second derivative in terms of $y$ only, which might require using inverse trigonometric relations.

**Step-by-step solution:**
Given $y = \cos^{-1} x$.
This implies $x = \cos y$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(\cos^{-1} x) = -\frac{1}{\sqrt{1 - x^2}}$.
    Since $x = \cos y$, then $\sqrt{1 - x^2} = \sqrt{1 - \cos^2 y} = \sqrt{\sin^2 y} = |\sin y|$.
    For $y = \cos^{-1} x$, the range of $y$ is $[0, \pi]$, in which $\sin y \geq 0$. So $|\sin y| = \sin y$.
    Thus, $\frac{dy}{dx} = -\frac{1}{\sin y} = -\csc y$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    We need to differentiate $\frac{dy}{dx} = -\csc y$ with respect to $x$.
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(-\csc y) = -\frac{d}{dy}(\csc y) \cdot \frac{dy}{dx}$.
    $\frac{d}{dy}(\csc y) = -\csc y \cot y$.
    So, $\frac{d^2y}{dx^2} = -(-\csc y \cot y) \cdot \frac{dy}{dx} = \csc y \cot y \cdot \frac{dy}{dx}$.
    Substitute $\frac{dy}{dx} = -\csc y$:
    $\frac{d^2y}{dx^2} = \csc y \cot y \cdot (-\csc y) = -\csc^2 y \cot y$.

This expression is in terms of $y$ alone.

---

**13. If $y = 3 \cos(\log x) + 4 \sin(\log x)$, show that $x^2 y_2 + xy_1 + y = 0$.**

**Reasoning:**
This is a verification problem involving first and second derivatives. We will find $y_1 = \frac{dy}{dx}$ and $y_2 = \frac{d^2y}{dx^2}$ and substitute them into the given differential equation.

**Step-by-step solution:**
Given $y = 3 \cos(\log x) + 4 \sin(\log x)$.

1.  **First derivative $y_1 = \frac{dy}{dx}$:**
    $y_1 = \frac{d}{dx}[3 \cos(\log x) + 4 \sin(\log x)]$
    $y_1 = 3 (-\sin(\log x) \cdot \frac{1}{x}) + 4 (\cos(\log x) \cdot \frac{1}{x})$
    $y_1 = -\frac{3 \sin(\log x)}{x} + \frac{4 \cos(\log x)}{x}$.
    Multiply by $x$: $xy_1 = -3 \sin(\log x) + 4 \cos(\log x)$. (Equation A)

2.  **Second derivative $y_2 = \frac{d^2y}{dx^2}$:**
    Differentiate Equation A with respect to $x$. Use the product rule for $xy_1$.
    $\frac{d}{dx}(xy_1) = \frac{d}{dx}(-3 \sin(\log x) + 4 \cos(\log x))$
    $1 \cdot y_1 + x \cdot y_2 = -3 (\cos(\log x) \cdot \frac{1}{x}) + 4 (-\sin(\log x) \cdot \frac{1}{x})$
    $y_1 + xy_2 = -\frac{3 \cos(\log x)}{x} - \frac{4 \sin(\log x)}{x}$.
    Multiply by $x$:
    $xy_1 + x^2 y_2 = -3 \cos(\log x) - 4 \sin(\log x)$.
    $xy_1 + x^2 y_2 = -[3 \cos(\log x) + 4 \sin(\log x)]$.
    Notice that the term in the square brackets is the original function $y$.
    $xy_1 + x^2 y_2 = -y$.

3.  **Rearrange to match the desired equation:**
    $x^2 y_2 + xy_1 + y = 0$.

Thus, the equation is proven.

---

**14. If $y = Ae^{mx} + Be^{nx}$, show that $\frac{d^2y}{dx^2} - (m + n)\frac{dy}{dx} + mny = 0$.**

**Reasoning:**
This is a verification problem involving first and second derivatives. We will find $\frac{dy}{dx}$ and $\frac{d^2y}{dx^2}$ and substitute them into the given differential equation.

**Step-by-step solution:**
Given $y = Ae^{mx} + Be^{nx}$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(Ae^{mx} + Be^{nx})$
    $\frac{dy}{dx} = A(e^{mx} \cdot m) + B(e^{nx} \cdot n) = Ame^{mx} + Bne^{nx}$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(Ame^{mx} + Bne^{nx})$
    $\frac{d^2y}{dx^2} = Am(e^{mx} \cdot m) + Bn(e^{nx} \cdot n) = Am^2e^{mx} + Bn^2e^{nx}$.

3.  **Substitute $\frac{d^2y}{dx^2}$, $\frac{dy}{dx}$, and $y$ into the differential equation:**
    $\frac{d^2y}{dx^2} - (m + n)\frac{dy}{dx} + mny = 0$.
    $(Am^2e^{mx} + Bn^2e^{nx}) - (m + n)(Ame^{mx} + Bne^{nx}) + mn(Ae^{mx} + Be^{nx})$
    $= Am^2e^{mx} + Bn^2e^{nx} - (Am^2e^{mx} + Bmne^{nx} + Anme^{mx} + Bn^2e^{nx}) + (mnae^{mx} + mnbe^{nx})$
    $= Am^2e^{mx} + Bn^2e^{nx} - Am^2e^{mx} - Bmne^{nx} - Amne^{mx} - Bn^2e^{nx} + Amne^{mx} + Bmne^{nx}$
    (Note: $mna = Amn$ and $mnb = Bmn$ by commutativity)
    Group terms by $e^{mx}$ and $e^{nx}$:
    $= e^{mx}(Am^2 - Am^2 - Amn + Amn) + e^{nx}(Bn^2 - Bmn - Bn^2 + Bmn)$
    $= e^{mx}(0) + e^{nx}(0)$
    $= 0$.

Thus, the equation is proven.

---

**15. If $y = 500e^{7x} + 600e^{-7x}$, show that $\frac{d^2y}{dx^2} = 49y$.**

**Reasoning:**
This is a verification problem involving the second derivative. We will find $\frac{d^2y}{dx^2}$ and substitute it into the given equation.

**Step-by-step solution:**
Given $y = 500e^{7x} + 600e^{-7x}$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(500e^{7x} + 600e^{-7x})$
    $\frac{dy}{dx} = 500(e^{7x} \cdot 7) + 600(e^{-7x} \cdot (-7))$
    $\frac{dy}{dx} = 3500e^{7x} - 4200e^{-7x}$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}(3500e^{7x} - 4200e^{-7x})$
    $\frac{d^2y}{dx^2} = 3500(e^{7x} \cdot 7) - 4200(e^{-7x} \cdot (-7))$
    $\frac{d^2y}{dx^2} = 24500e^{7x} + 29400e^{-7x}$.

3.  **Check if $\frac{d^2y}{dx^2} = 49y$:**
    From the expression for $y$:
    $49y = 49(500e^{7x} + 600e^{-7x})$
    $49y = 49 \cdot 500e^{7x} + 49 \cdot 600e^{-7x}$
    $49y = 24500e^{7x} + 29400e^{-7x}$.
    Comparing this with $\frac{d^2y}{dx^2}$, we see that they are equal.

Therefore, $\frac{d^2y}{dx^2} = 49y$ is proven.

---

**16. If $e^y(x + 1) = 1$, show that $\frac{d^2y}{dx^2} = \left(\frac{dy}{dx}\right)^2$.**

**Reasoning:**
This is an implicit differentiation problem. We need to find $\frac{dy}{dx}$ and $\frac{d^2y}{dx^2}$ and then verify the relationship. It's often easier to first solve for $y$ or $\frac{dy}{dx}$ explicitly if possible.

**Step-by-step solution:**
Given $e^y(x + 1) = 1$.
From this, $e^y = \frac{1}{x + 1}$.
Take the natural logarithm of both sides:
$\log(e^y) = \log\left(\frac{1}{x + 1}\right)$
$y = \log(1) - \log(x + 1)$
$y = -\log(x + 1)$.

1.  **First derivative $\frac{dy}{dx}$:**
    $\frac{dy}{dx} = \frac{d}{dx}(-\log(x + 1)) = -\frac{1}{x + 1}$.

2.  **Second derivative $\frac{d^2y}{dx^2}$:**
    $\frac{d^2y}{dx^2} = \frac{d}{dx}\left(-\frac{1}{x + 1}\right) = \frac{d}{dx}(-(x + 1)^{-1})$
    $\frac{d^2y}{dx^2} = -(-1)(x + 1)^{-2} \cdot \frac{d}{dx}(x + 1)$
    $\frac{d^2y}{dx^2} = (x + 1)^{-2} \cdot 1 = \frac{1}{(x + 1)^2}$.

3.  **Check if $\frac{d^2y}{dx^2} = \left(\frac{dy}{dx}\right)^2$:**
    We found $\frac{dy}{dx} = -\frac{1}{x + 1}$.
    So, $\left(\frac{dy}{dx}\right)^2 = \left(-\frac{1}{x + 1}\right)^2 = \frac{1}{(x + 1)^2}$.
    Comparing this with $\frac{d^2y}{dx^2}$, we see that they are equal.

Therefore, $\frac{d^2y}{dx^2} = \left(\frac{dy}{dx}\right)^2$ is proven.

---

**17. If $y = (\tan^{-1} x)^2$, show that $(x^2 + 1)^2 y_2 + 2x(x^2 + 1) y_1 = 2$.**

**Reasoning:**
This is a verification problem involving first and second derivatives. We will find $y_1$ and $y_2$ and substitute them into the given differential equation.

**Step-by-step solution:**
Given $y = (\tan^{-1} x)^2$.

1.  **First derivative $y_1 = \frac{dy}{dx}$:**
    $y_1 = \frac{d}{dx}((\tan^{-1} x)^2) = 2(\tan^{-1} x) \cdot \frac{d}{dx}(\tan^{-1} x)$
    $y_1 = 2(\tan^{-1} x) \cdot \frac{1}{1 + x^2}$.
    Multiply by $(1 + x^2)$:
    $(1 + x^2)y_1 = 2 \tan^{-1} x$. (Equation A)

2.  **Second derivative $y_2 = \frac{d^2y}{dx^2}$:**
    Differentiate Equation A with respect to $x$. Use the product rule for $(1 + x^2)y_1$.
    $\frac{d}{dx}((1 + x^2)y_1) = \frac{d}{dx}(2 \tan^{-1} x)$
    $2x \cdot y_1 + (1 + x^2) \cdot y_2 = 2 \cdot \frac{1}{1 + x^2}$.
    Multiply by $(1 + x^2)$:
    $2x(1 + x^2)y_1 + (1 + x^2)^2 y_2 = 2$.

This matches the desired equation.

Therefore, $(x^2 + 1)^2 y_2 + 2x(x^2 + 1) y_1 = 2$ is proven.

---

#### **Miscellaneous Examples (from Page 37)**

**Example 39. Differentiate w.r.t. x, the following function:**
**(i) $\sqrt{3x + 2} + \frac{1}{\sqrt{2x^2 + 4}}$**

**Reasoning:**
This is a sum of two functions. We differentiate each term separately using the chain rule.

**Step-by-step solution:**
Let $y = \sqrt{3x + 2} + \frac{1}{\sqrt{2x^2 + 4}} = (3x + 2)^{1/2} + (2x^2 + 4)^{-1/2}$.

1.  **Differentiate $(3x + 2)^{1/2}$:**
    $\frac{d}{dx}((3x + 2)^{1/2}) = \frac{1}{2}(3x + 2)^{-1/2} \cdot \frac{d}{dx}(3x + 2)$
    $= \frac{1}{2}(3x + 2)^{-1/2} \cdot 3 = \frac{3}{2\sqrt{3x + 2}}$.

2.  **Differentiate $(2x^2 + 4)^{-1/2}$:**
    $\frac{d}{dx}((2x^2 + 4)^{-1/2}) = -\frac{1}{2}(2x^2 + 4)^{-3/2} \cdot \frac{d}{dx}(2x^2 + 4)$
    $= -\frac{1}{2}(2x^2 + 4)^{-3/2} \cdot (4x)$
    $= -\frac{4x}{2(2x^2 + 4)^{3/2}} = -\frac{2x}{(2x^2 + 4)^{3/2}}$.

3.  **Combine the derivatives:**
    $\frac{dy}{dx} = \frac{3}{2\sqrt{3x + 2}} - \frac{2x}{(2x^2 + 4)^{3/2}}$.

---

#### **Miscellaneous Examples (from Page 38)**

**Example 40. Differentiate the following w.r.t. x.**

**(i) $\cos^{-1}(\sin x)$**

**Reasoning:**
This is a composite function. We use the chain rule. We can also simplify the expression first using trigonometric identities.

**Step-by-step solution (Method 1: Using trigonometric identity):**
Let $y = \cos^{-1}(\sin x)$.
We can rewrite $\sin x$ as $\cos(\frac{\pi}{2} - x)$.
So, $y = \cos^{-1}(\cos(\frac{\pi}{2} - x))$.
For the principal value of $\cos^{-1}$, if $\frac{\pi}{2} - x \in [0, \pi]$, then $y = \frac{\pi}{2} - x$.
This holds true for certain ranges of $x$. For example, if $x \in [-\frac{\pi}{2}, \frac{\pi}{2}]$, then $\frac{\pi}{2} - x \in [0, \pi]$.
In this case, $\frac{dy}{dx} = \frac{d}{dx}(\frac{\pi}{2} - x) = -1$.

**Step-by-step solution (Method 2: Direct chain rule):**
$\frac{d}{du}(\cos^{-1} u) = -\frac{1}{\sqrt{1 - u^2}}$.
Let $y = \cos^{-1}(\sin x)$.
$\frac{dy}{dx} = -\frac{1}{\sqrt{1 - \sin^2 x}} \cdot \frac{d}{dx}(\sin x)$
$\frac{dy}{dx} = -\frac{1}{\sqrt{\cos^2 x}} \cdot \cos x$
$\frac{dy}{dx} = -\frac{1}{|\cos x|} \cdot \cos x$.

This results in $-1$ if $\cos x > 0$ and $1$ if $\cos x < 0$.
The result from Method 1 ($ -1 $) is consistent for regions where $\cos x > 0$. For instance, for $x \in (-\frac{\pi}{2}, \frac{\pi}{2})$, $\cos x > 0$, and $\frac{\pi}{2} - x \in (0, \pi)$, so $y = \frac{\pi}{2} - x$ and $\frac{dy}{dx} = -1$.
The textbook example provides $-1$ as the answer, implicitly assuming the domain where $\cos x > 0$.

---

**(ii) $\tan^{-1}\left(\frac{\sin x}{1 + \cos x}\right)$**

**Reasoning:**
This is a composite function. The expression inside $\tan^{-1}$ can be simplified using half-angle trigonometric identities.

**Step-by-step solution:**
Let $y = \tan^{-1}\left(\frac{\sin x}{1 + \cos x}\right)$.
Using half-angle identities:
$\sin x = 2 \sin(\frac{x}{2}) \cos(\frac{x}{2})$.
$1 + \cos x = 2 \cos^2(\frac{x}{2})$.
Substitute these into the expression:
$y = \tan^{-1}\left(\frac{2 \sin(\frac{x}{2}) \cos(\frac{x}{2})}{2 \cos^2(\frac{x}{2})}\right)$
$y = \tan^{-1}\left(\frac{\sin(\frac{x}{2})}{\cos(\frac{x}{2})}\right)$
$y = \tan^{-1}\left(\tan(\frac{x}{2})\right)$.
Assuming $\frac{x}{2}$ is in the principal value range for $\tan^{-1}$ (i.e., $(-\frac{\pi}{2}, \frac{\pi}{2})$), then:
$y = \frac{x}{2}$.
Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}\left(\frac{x}{2}\right) = \frac{1}{2}$.

---

**(iii) $\sin^{-1}\left(\frac{2^{x+1}}{1 + 4^x}\right)$**

**Reasoning:**
This is a composite function. We need to simplify the expression inside $\sin^{-1}$ using properties of exponents and a trigonometric substitution.

**Step-by-step solution:**
Let $y = \sin^{-1}\left(\frac{2^{x+1}}{1 + 4^x}\right)$.
Rewrite the expression:
$2^{x+1} = 2^x \cdot 2^1 = 2 \cdot 2^x$.
$4^x = (2^2)^x = (2^x)^2$.
So, $y = \sin^{-1}\left(\frac{2 \cdot 2^x}{1 + (2^x)^2}\right)$.

Let $2^x = \tan \theta$. Then $\theta = \tan^{-1}(2^x)$.
The expression becomes:
$y = \sin^{-1}\left(\frac{2 \tan \theta}{1 + \tan^2 \theta}\right)$.
We know the identity $\frac{2 \tan \theta}{1 + \tan^2 \theta} = \sin(2\theta)$.
So, $y = \sin^{-1}(\sin(2\theta))$.
Assuming $2\theta$ is in the principal value range $[-\frac{\pi}{2}, \frac{\pi}{2}]$ for $\sin^{-1}$, then:
$y = 2\theta$.
Substitute back $\theta = \tan^{-1}(2^x)$:
$y = 2 \tan^{-1}(2^x)$.

Now, differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(2 \tan^{-1}(2^x))$.
Using the chain rule, $\frac{d}{du}(\tan^{-1} u) = \frac{1}{1 + u^2} \cdot \frac{du}{dx}$.
Here $u = 2^x$. So $\frac{du}{dx} = \frac{d}{dx}(2^x) = 2^x \log 2$.
$\frac{dy}{dx} = 2 \cdot \frac{1}{1 + (2^x)^2} \cdot (2^x \log 2)$
$\frac{dy}{dx} = \frac{2 \cdot 2^x \log 2}{1 + 4^x} = \frac{2^{x+1} \log 2}{1 + 4^x}$.

---

#### **Miscellaneous Examples (from Page 40)**

**Example 41. Find $f'(x)$ if $f(x) = (\sin x)^{\sin x}$ for all $0 < x < \pi$.**

**Reasoning:**
This is a function of the form $g(x)^{h(x)}$. Logarithmic differentiation is required.

**Step-by-step solution:**
Let $y = (\sin x)^{\sin x}$.
Take the natural logarithm of both sides:
$\log y = \log((\sin x)^{\sin x})$.
Using logarithm properties:
$\log y = \sin x \log(\sin x)$.

Now, differentiate both sides with respect to $x$ using the product rule:
$\frac{1}{y} \frac{dy}{dx} = \frac{d}{dx}(\sin x) \cdot \log(\sin x) + \sin x \cdot \frac{d}{dx}(\log(\sin x))$.
$\frac{d}{dx}(\sin x) = \cos x$.
$\frac{d}{dx}(\log(\sin x)) = \frac{1}{\sin x} \cdot \cos x = \cot x$.

So, $\frac{1}{y} \frac{dy}{dx} = \cos x \log(\sin x) + \sin x \cdot \cot x$.
$\frac{1}{y} \frac{dy}{dx} = \cos x \log(\sin x) + \sin x \cdot \frac{\cos x}{\sin x}$.
$\frac{1}{y} \frac{dy}{dx} = \cos x \log(\sin x) + \cos x$.
Factor out $\cos x$:
$\frac{1}{y} \frac{dy}{dx} = \cos x (1 + \log(\sin x))$.

Finally, multiply by $y$:
$\frac{dy}{dx} = (\sin x)^{\sin x} \cos x (1 + \log(\sin x))$.

---

**Example 42. For a positive constant $a$ find $\frac{dy}{dx}$, where $y = a^{t + \frac{1}{t}}$ and $x = \left(t + \frac{1}{t}\right)^a$.**

**Reasoning:**
This is a parametric differentiation problem. We need to find $\frac{dy}{dt}$ and $\frac{dx}{dt}$ and then use $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$.

**Step-by-step solution:**
Let $u = t + \frac{1}{t}$.
Then $x = u^a$ and $y = a^u$.

1.  Find $\frac{du}{dt}$:
    $\frac{du}{dt} = \frac{d}{dt}\left(t + t^{-1}\right) = 1 - t^{-2} = 1 - \frac{1}{t^2} = \frac{t^2 - 1}{t^2}$.

2.  Find $\frac{dx}{dt}$:
    $x = u^a$. So $\frac{dx}{du} = au^{a-1}$.
    Using the chain rule: $\frac{dx}{dt} = \frac{dx}{du} \cdot \frac{du}{dt} = au^{a-1} \cdot \frac{t^2 - 1}{t^2}$.
    Substitute $u = t + \frac{1}{t}$:
    $\frac{dx}{dt} = a\left(t + \frac{1}{t}\right)^{a-1} \left(\frac{t^2 - 1}{t^2}\right)$.

3.  Find $\frac{dy}{dt}$:
    $y = a^u$. So $\frac{dy}{du} = a^u \log a$.
    Using the chain rule: $\frac{dy}{dt} = \frac{dy}{du} \cdot \frac{du}{dt} = a^u \log a \cdot \frac{t^2 - 1}{t^2}$.
    Substitute $u = t + \frac{1}{t}$:
    $\frac{dy}{dt} = a^{\left(t + \frac{1}{t}\right)} \log a \left(\frac{t^2 - 1}{t^2}\right)$.

4.  Find $\frac{dy}{dx}$:
    $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{a^{\left(t + \frac{1}{t}\right)} \log a \left(\frac{t^2 - 1}{t^2}\right)}{a\left(t + \frac{1}{t}\right)^{a-1} \left(\frac{t^2 - 1}{t^2}\right)}$.
    Assuming $\frac{t^2 - 1}{t^2} \neq 0$ (i.e., $t \neq \pm 1$ and $t \neq 0$):
    $\frac{dy}{dx} = \frac{a^{\left(t + \frac{1}{t}\right)} \log a}{a\left(t + \frac{1}{t}\right)^{a-1}}$.

This can be further written using $y$ and $x$:
Recall $y = a^{\left(t + \frac{1}{t}\right)}$ and $x = \left(t + \frac{1}{t}\right)^a$.
$\frac{dy}{dx} = \frac{y \log a}{a \left(t + \frac{1}{t}\right)^{a-1}}$.
From $x = \left(t + \frac{1}{t}\right)^a$, we have $\left(t + \frac{1}{t}\right) = x^{1/a}$.
So, $\frac{dy}{dx} = \frac{y \log a}{a (x^{1/a})^{a-1}} = \frac{y \log a}{a x^{(a-1)/a}}$.

---

#### **Miscellaneous Examples (from Page 41)**

**Example 43. Differentiate $\sin^2 x$ w.r.t. $e^{\cos x}$.**

**Reasoning:**
This is differentiation of one function with respect to another function. If we want to find $\frac{du}{dv}$, where $u = f(x)$ and $v = g(x)$, we calculate $\frac{du}{dx}$ and $\frac{dv}{dx}$ and then use $\frac{du}{dv} = \frac{du/dx}{dv/dx}$.

**Step-by-step solution:**
Let $u = \sin^2 x$ and $v = e^{\cos x}$. We want to find $\frac{du}{dv}$.

1.  Find $\frac{du}{dx}$:
    $u = \sin^2 x = (\sin x)^2$.
    $\frac{du}{dx} = 2 \sin x \cdot \frac{d}{dx}(\sin x) = 2 \sin x \cos x = \sin(2x)$.

2.  Find $\frac{dv}{dx}$:
    $v = e^{\cos x}$.
    $\frac{dv}{dx} = e^{\cos x} \cdot \frac{d}{dx}(\cos x) = e^{\cos x} \cdot (-\sin x) = -\sin x e^{\cos x}$.

3.  Find $\frac{du}{dv}$:
    $\frac{du}{dv} = \frac{du/dx}{dv/dx} = \frac{\sin(2x)}{-\sin x e^{\cos x}}$.
    Using the identity $\sin(2x) = 2 \sin x \cos x$:
    $\frac{du}{dv} = \frac{2 \sin x \cos x}{-\sin x e^{\cos x}}$.
    Assuming $\sin x \neq 0$:
    $\frac{du}{dv} = \frac{2 \cos x}{-e^{\cos x}} = -2 \cos x e^{-\cos x}$.

---

This completes all exercises from the provided document.