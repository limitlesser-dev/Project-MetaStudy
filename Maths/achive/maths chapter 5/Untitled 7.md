# 📚 NCERT Class 12 Mathematics: Chapter 5 - Continuity and Differentiability (Theorems Explained)

## 🏛️ Learning the Theorems: Rolle's Theorem and Mean Value Theorem

These two theorems are super important because they connect the values of a function to the values of its derivative over an interval. They might seem a bit abstract at first, but once you understand their geometric meaning, they become much clearer.

---

## 📜 1. Rolle's Theorem (Roll's Theorem)

Imagine a car journey. If you start at a certain altitude, drive for some time, and end up at the *exact same altitude* you started at, then at some point during your journey, you must have been driving perfectly horizontally (the slope of your path was zero).

### 📝 Formal Statement:

If a function $f: [a, b] \to \mathbb{R}$ is such that:
1.  It is **continuous** on the closed interval $[a, b]$.
2.  It is **differentiable** on the open interval $(a, b)$.
3.  $f(a) = f(b)$ (The function values at the endpoints are equal).

Then there exists **at least one point** $c$ in the open interval $(a, b)$ such that $f'(c) = 0$.

### 🚶 Explanation (Step-by-Step):

1.  **Continuous on $[a, b]$:** This means you can draw the function's graph from point `a` to point `b` without lifting your pen. No breaks, jumps, or holes in that interval, including the endpoints.
2.  **Differentiable on $(a, b)$:** This means the graph is smooth between `a` and `b`. No sharp corners or cusps in the middle of the journey. (Note: endpoints par differentiability check karne ki zaroorat nahi hai for the theorem).
3.  **$f(a) = f(b)$:** This is the special condition for Rolle's Theorem. It means the starting height and the ending height of your graph are the same.

**If all three of these conditions are met, then the theorem guarantees:**
There *must* be some point `c` (which is strictly between `a` and `b`, so `a < c < b`) where the derivative `f'(c)` is zero.
Remember, `f'(c) = 0` means the **slope of the tangent line at `c` is zero**, which implies the tangent line is horizontal.

### 🖼️ Geometric Interpretation:

*   Draw a continuous and smooth curve.
*   Mark two points `A(a, f(a))` and `B(b, f(b))` such that `f(a) = f(b)`.
*   Connect `A` and `B` with your smooth, continuous curve.
*   You'll see that to go from `A` to `B` (at the same height), the curve must either go up and then come down, or go down and then come up. At the peak (maximum) or valley (minimum) of that climb/descent, the tangent line will be perfectly horizontal. That's your point `c` where `f'(c) = 0`.
*   There can be more than one such point! The theorem says "at least one".

### 🎯 Exercise 5.8 Question (Selected) [1]

#### Question 2 (i). Examine if Rolle's Theorem is applicable to the function $f(x) = [x]$ for $x \in [5, 9]$. [1]
*(Recall: `[x]` is the greatest integer function, meaning it gives the greatest integer less than or equal to `x`. E.g., `[5.3] = 5`, `[5] = 5`)*

**_Explanation:_** To apply Rolle's Theorem, we *must* check all three conditions. If even one fails, the theorem is not applicable.

**_Solution:_**
Given $f(x) = [x]$ for $x \in [5, 9]$. Here, $a=5$ and $b=9$.

1.  **Continuity on $[5, 9]$:**
    The greatest integer function $f(x) = [x]$ is discontinuous at every integer point. For example, at $x=5.5$, it's $5$, at $x=5.9$, it's $5$, but just as $x$ crosses $6$ (e.g., $x=6.0001$), it jumps to $6$.
    Since the interval $[5, 9]$ contains integer points like $6, 7, 8$, the function is **not continuous** on $[5, 9]$.

2.  **Differentiability on $(5, 9)$:**
    A function cannot be differentiable where it is discontinuous. Since $f(x) = [x]$ is not continuous on $(5, 9)$ (due to integer points), it is also **not differentiable** on $(5, 9)$.
    *(Even if it were continuous, sharp "steps" make it non-differentiable at integers).*

Since the first two conditions for Rolle's Theorem are not satisfied, **Rolle's Theorem is not applicable** to $f(x) = [x]$ on $[5, 9]$.

**(Converse of Rolle's Theorem?):** The question also asks about the converse. The converse would be: "If $f'(c) = 0$ for some `c` in `(a, b)`, then `f(a) = f(b)` and `f` is continuous and differentiable." This is **not necessarily true**. For example, $f(x) = x^3$ has $f'(0)=0$, but if you take $x \in [-1, 1]$, $f(-1) \neq f(1)$. So, the converse is false.

---

## 📜 2. Mean Value Theorem (Lagrange's MVT)

Rolle's Theorem ka bada bhai hai MVT. Yeh thoda zyada general hai. Ismein zaroori nahi hai ki $f(a)$ aur $f(b)$ barabar hon.

Imagine karo tum Mumbai se Pune drive kar rahe ho. Agar tumhari average speed 60 km/hr thi, toh MVT kehta hai ki raste mein kahin na kahin (at least ek point par) tumhari instantaneous speed (uska derivative) bhi exactly 60 km/hr rahi hogi.

### 📝 Formal Statement:

If a function $f: [a, b] \to \mathbb{R}$ is such that:
1.  It is **continuous** on the closed interval $[a, b]$.
2.  It is **differentiable** on the open interval $(a, b)$.

Then there exists **at least one point** $c$ in the open interval $(a, b)$ such that:
$$ f'(c) = \frac{f(b) - f(a)}{b - a} $$

### 🚶 Explanation (Step-by-Step):

1.  **Continuous on $[a, b]$:** Same as Rolle's theorem. Graph should be unbroken from `a` to `b`.
2.  **Differentiable on $(a, b)$:** Same as Rolle's theorem. Graph should be smooth between `a` and `b`.

**If these two conditions are met, then the theorem guarantees:**
There *must* be some point `c` (`a < c < b`) where the derivative `f'(c)` is equal to the quantity $\frac{f(b) - f(a)}{b - a}$.

What is $\frac{f(b) - f(a)}{b - a}$?
This is the formula for the **slope of the secant line** joining the two endpoints `(a, f(a))` and `(b, f(b))`.
So, the theorem says: At some point `c`, the slope of the tangent line (`f'(c)`) is equal to the slope of the secant line. In simpler words, the tangent line at `c` is **parallel** to the secant line connecting the endpoints.

### 🖼️ Geometric Interpretation:

*   Draw a continuous and smooth curve.
*   Mark two points `A(a, f(a))` and `B(b, f(b))`. These points can be at different heights.
*   Draw a straight line (secant line) connecting `A` and `B`. Calculate its slope: $\frac{f(b) - f(a)}{b - a}$.
*   The MVT guarantees that somewhere on the curve *between* `A` and `B`, there will be at least one point `C(c, f(c))` where the tangent line to the curve is perfectly parallel to the secant line `AB`. The slope of this tangent line will be `f'(c)`.

### 🎯 Exercise 5.8 Question (Selected) [1]

#### Question 3. If $f(x) = x^2 - 1$ for $x \in [1, 2]$, verify the Mean Value Theorem. [1]

**_Explanation:_** To verify MVT, we first check the conditions. If they hold, we then find a `c` in the given interval that satisfies the theorem's conclusion.

**_Solution:_**
Given $f(x) = x^2 - 1$ for $x \in [1, 2]$. Here, $a=1$ and $b=2$.

1.  **Continuity on $[1, 2]$:**
    $f(x) = x^2 - 1$ is a polynomial function. All polynomial functions are continuous everywhere.
    Therefore, $f(x)$ is **continuous** on the closed interval $[1, 2]$. (Condition 1 satisfied).

2.  **Differentiability on $(1, 2)$:**
    $f(x) = x^2 - 1$ is a polynomial function. All polynomial functions are differentiable everywhere.
    Therefore, $f(x)$ is **differentiable** on the open interval $(1, 2)$. (Condition 2 satisfied).

Since both conditions are satisfied, the Mean Value Theorem is applicable.
Now, we need to find a value `c` in $(1, 2)$ such that $f'(c) = \frac{f(b) - f(a)}{b - a}$.

**Step 1: Find $f'(x)$ (the derivative of the function).**
$f'(x) = \frac{d}{dx}(x^2 - 1) = 2x - 0 = 2x$.
So, $f'(c) = 2c$.

**Step 2: Calculate the slope of the secant line $\frac{f(b) - f(a)}{b - a}$.**
*   $f(a) = f(1) = 1^2 - 1 = 0$.
*   $f(b) = f(2) = 2^2 - 1 = 4 - 1 = 3$.
*   $b - a = 2 - 1 = 1$.

So, $\frac{f(b) - f(a)}{b - a} = \frac{3 - 0}{1} = 3$.

**Step 3: Set $f'(c)$ equal to the slope of the secant line and solve for $c$.**
$2c = 3$
$c = \frac{3}{2}$

**Step 4: Check if $c$ is within the open interval $(a, b)$.**
Here, $c = \frac{3}{2} = 1.5$.
The interval is $(1, 2)$.
Since $1 < 1.5 < 2$, the value $c = 1.5$ lies within the open interval $(1, 2)$.

Thus, the Mean Value Theorem is **verified** for the given function and interval.

---

## 🔑 Key Takeaways for Theorems

*   **Conditions are Paramount:** For both theorems, *always* check continuity and differentiability first. If they fail, the theorem is not applicable.
*   **Rolle's Special Condition:** $f(a) = f(b)$ is the extra condition for Rolle's. This leads to $f'(c) = 0$.
*   **MVT Generalizes Rolle's:** If you set $f(a) = f(b)$ in MVT, then $\frac{f(b) - f(a)}{b - a} = \frac{0}{b-a} = 0$, which means $f'(c)=0$, making it Rolle's Theorem. So, Rolle's is a specific case of MVT.
*   **Geometric Meaning:** Visualize a horizontal tangent for Rolle's, and a tangent parallel to the secant line for MVT.
*   **"At least one point `c`":** Remember, the theorems guarantee *at least one* such point. There could be more!

---

I hope this detailed breakdown makes Rolle's and Mean Value Theorem much clearer for you. Go through the examples again, try drawing graphs for simple functions to visualize them, and then attempt more questions from your textbook. You've got this!