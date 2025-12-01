# Chapter 5: Continuity and Differentiability - NCERT Class 12 Mathematics (2025)

Welcome, future math whiz! Your exam is tomorrow, so let's make sure you ace Chapter 5. This chapter builds on your Class XI knowledge of differentiation and introduces some critical new concepts. We'll break it down, explain the core ideas, and practice with examples and exercise questions directly from your textbook.

---

## 5.1 Introduction

This chapter is all about two fundamental concepts in calculus: **Continuity** and **Differentiability**.
*   **Continuity** basically means you can draw the graph of a function without lifting your pen. No breaks, no jumps, no holes.
*   **Differentiability** means a function has a well-defined tangent line at every point. This is closely related to finding the instantaneous rate of change (derivative).

We'll also learn to differentiate more complex functions, including inverse trigonometric, exponential, and logarithmic functions, and explore different techniques like chain rule and logarithmic differentiation.

---

## 5.2 Continuity

### What is Continuity? (Informal and Formal Definition)

Informally, a function $f(x)$ is continuous at a point $c$ if its graph at that point can be drawn without lifting the pen. There are no sudden jumps or breaks.

**Mathematically (Definition 1, Page 2):**
A real function $f$ on a subset of real numbers is **continuous at a point $c$** in its domain if:
$$ \lim_{x \to c} f(x) = f(c) $$
This means three conditions must be met:
1.  $f(c)$ must be defined (the function exists at $x=c$).
2.  $\lim_{x \to c} f(x)$ must exist (the left-hand limit and right-hand limit are equal).
3.  The limit must be equal to the function's value at that point: $\lim_{x \to c^-} f(x) = \lim_{x \to c^+} f(x) = f(c)$.

If any of these conditions fail, the function is discontinuous at $c$, and $c$ is called a point of discontinuity.

**Example 1 (Page 3):** Check the continuity of $f(x) = 2x + 3$ at $x = 1$.
*   **Step 1: Find $f(1)$**
    $f(1) = 2(1) + 3 = 5$
*   **Step 2: Find $\lim_{x \to 1} f(x)$**
    $\lim_{x \to 1} (2x + 3) = 2(1) + 3 = 5$
*   **Step 3: Compare**
    Since $\lim_{x \to 1} f(x) = f(1)$, the function is continuous at $x = 1$. [1]

**Example of Discontinuity (Page 2):** Consider $f(x) = \begin{cases} 1, & \text{if } x \le 0 \\ 2, & \text{if } x > 0 \end{cases}$
*   Left-hand limit at $x=0$: $\lim_{x \to 0^-} f(x) = 1$
*   Right-hand limit at $x=0$: $\lim_{x \to 0^+} f(x) = 2$
*   Function value at $x=0$: $f(0) = 1$
Here, the left and right-hand limits are not equal, so $\lim_{x \to 0} f(x)$ does not exist. Thus, $f(x)$ is discontinuous at $x=0$. [1]

**A function is continuous** if it is continuous at every point in its domain (Definition 2, Page 4).

### Algebra of Continuous Functions (5.2.1)

**Theorem 1 (Page 10):** If $f$ and $g$ are continuous functions at a real number $c$, then:
1.  $f+g$ is continuous at $x=c$.
2.  $f-g$ is continuous at $x=c$.
3.  $f \cdot g$ is continuous at $x=c$.
4.  $f/g$ is continuous at $x=c$, provided $g(c) \ne 0$.

This theorem is very powerful! It tells us that sums, differences, products, and quotients of continuous functions are also continuous (as long as we don't divide by zero).

**Example 16 (Page 11):** Prove that every rational function is continuous.
A rational function is of the form $f(x) = p(x)/q(x)$, where $p(x)$ and $q(x)$ are polynomial functions and $q(x) \ne 0$.
We know that polynomial functions are continuous everywhere (Example 14, Page 9).
Since a rational function is a quotient of two continuous functions, by Theorem 1(4), it is continuous wherever $q(x) \ne 0$. [1]

**Example 17 (Page 11):** Discuss the continuity of sine function.
To show $\sin x$ is continuous at any point $c$:
$\lim_{x \to c} \sin x = \lim_{h \to 0} \sin(c+h) = \lim_{h \to 0} (\sin c \cos h + \cos c \sin h)$
$= \sin c \lim_{h \to 0} \cos h + \cos c \lim_{h \to 0} \sin h = \sin c (1) + \cos c (0) = \sin c = f(c)$.
Since $\lim_{x \to c} \sin x = \sin c$, the sine function is continuous at every real number. [1]
Similarly, cosine function is also continuous. From this, we can deduce the continuity of other trigonometric functions. For instance, $\tan x = \sin x / \cos x$ is continuous wherever $\cos x \ne 0$. [1]

### Continuity of Composite Functions

**Theorem 2 (Page 12):** If $g$ is continuous at $c$ and $f$ is continuous at $g(c)$, then the composite function $(f \circ g)(x) = f(g(x))$ is continuous at $c$.

**Example 19 (Page 12):** Show that $f(x) = \sin(x^2)$ is a continuous function.
Let $g(x) = x^2$ and $h(x) = \sin x$. Then $f(x) = h(g(x))$.
We know $g(x) = x^2$ (a polynomial) is continuous everywhere.
We know $h(x) = \sin x$ is continuous everywhere.
By Theorem 2, since $g$ is continuous and $h$ is continuous, $f(x) = \sin(x^2)$ is continuous. [1]

---

### Practice Exercise 5.1

Let's apply these concepts.

**Question 1 (Page 13):** Prove that $f(x) = 5x - 3$ is continuous at $x = 0$, at $x = -3$ and at $x = 5$.
*   **At $x = 0$**:
    *   $f(0) = 5(0) - 3 = -3$
    *   $\lim_{x \to 0} (5x - 3) = 5(0) - 3 = -3$
    *   Since $\lim_{x \to 0} f(x) = f(0)$, $f(x)$ is continuous at $x = 0$.
*   (You can follow the same steps for $x = -3$ and $x = 5$).

**Question 5 (Page 13):** Is the function $f$ defined by $f(x) = \begin{cases} x, & \text{if } x \le 1 \\ 5, & \text{if } x > 1 \end{cases}$ continuous at $x = 0$? At $x = 1$? At $x = 2$?

*   **At $x = 0$**: (Since $0 \le 1$, use $f(x)=x$)
    *   $f(0) = 0$
    *   $\lim_{x \to 0} x = 0$
    *   Continuous at $x = 0$.
*   **At $x = 1$**: (This is the critical point where the definition changes)
    *   $f(1) = 1$ (using $x \le 1$)
    *   Left-hand limit: $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} x = 1$
    *   Right-hand limit: $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} 5 = 5$
    *   Since $\lim_{x \to 1^-} f(x) \ne \lim_{x \to 1^+} f(x)$, the limit does not exist.
    *   Discontinuous at $x = 1$.
*   **At $x = 2$**: (Since $2 > 1$, use $f(x)=5$)
    *   $f(2) = 5$
    *   $\lim_{x \to 2} 5 = 5$
    *   Continuous at $x = 2$.

**Question 15 (Page 9 - related to definition):** Find all points of discontinuity of the greatest integer function defined by $f(x) = [x]$, where $[x]$ denotes the greatest integer less than or equal to $x$.
*   This function is discontinuous at every integer point. For any integer $c$:
    *   $f(c) = [c] = c$
    *   $\lim_{x \to c^-} [x] = c-1$ (e.g., if $c=3$, $[2.99]=2$)
    *   $\lim_{x \to c^+} [x] = c$ (e.g., if $c=3$, $[3.01]=3$)
*   Since $\lim_{x \to c^-} f(x) \ne \lim_{x \to c^+} f(x)$, the greatest integer function is discontinuous at all integer points. [1]

---

## 5.3 Differentiability

### What is Differentiability? (Definition)

A function $f(x)$ is **differentiable at a point $c$** if the derivative $f'(c)$ exists at that point.
The derivative $f'(c)$ is defined as:
$$ f'(c) = \lim_{h \to 0} \frac{f(c+h) - f(c)}{h} $$
For this limit to exist, the left-hand derivative (LHD) and right-hand derivative (RHD) must be equal:
$$ \text{LHD} = \lim_{h \to 0^-} \frac{f(c+h) - f(c)}{h} = \lim_{h \to 0^+} \frac{f(c+h) - f(c)}{h} = \text{RHD} $$

### Differentiability and Continuity

**Theorem 3 (Page 17):** If a function $f$ is differentiable at a point $c$, then it is also continuous at that point.
**Proof Idea:** The textbook shows that if $f'(c)$ exists, then $\lim_{x \to c} [f(x) - f(c)] = 0$, which implies $\lim_{x \to c} f(x) = f(c)$, hence continuity. [1]

**Important Remark (Page 17):** The converse is NOT true. A function can be continuous at a point but not differentiable at that point.
**Example:** $f(x) = |x|$ at $x=0$.
*   **Continuity at $x=0$**:
    *   $f(0) = |0| = 0$
    *   $\lim_{x \to 0^-} |x| = \lim_{x \to 0^-} (-x) = 0$
    *   $\lim_{x \to 0^+} |x| = \lim_{x \to 0^+} x = 0$
    *   Since limits equal $f(0)$, $f(x)=|x|$ is continuous at $x=0$.
*   **Differentiability at $x=0$**:
    *   LHD: $\lim_{h \to 0^-} \frac{|0+h| - |0|}{h} = \lim_{h \to 0^-} \frac{-h}{h} = -1$
    *   RHD: $\lim_{h \to 0^+} \frac{|0+h| - |0|}{h} = \lim_{h \to 0^+} \frac{h}{h} = 1$
    *   Since LHD $\ne$ RHD, $f(x)=|x|$ is not differentiable at $x=0$. [1]

### Chain Rule (Theorem 4, Page 18)

This is a crucial rule for differentiating composite functions. If $f = v \circ u$, meaning $f(x) = v(u(x))$, then:
$$ \frac{df}{dx} = \frac{dv}{du} \cdot \frac{du}{dx} $$
Or, if $t = u(x)$, then $f(x) = v(t)$, and $\frac{df}{dx} = \frac{dv}{dt} \cdot \frac{dt}{dx}$.

**Example 21 (Page 18):** Find the derivative of $f(x) = \sin(x^2)$.
Let $t = u(x) = x^2$. Then $f(x) = \sin(t)$.
$\frac{dt}{dx} = 2x$
$\frac{df}{dt} = \cos t$
Using the chain rule: $\frac{df}{dx} = \frac{df}{dt} \cdot \frac{dt}{dx} = (\cos t)(2x)$.
Substitute $t = x^2$ back: $\frac{df}{dx} = 2x \cos(x^2)$. [1]

---

### Practice Exercise 5.2

**Question 1 (Page 19):** Differentiate $\sin(x^2 + 5)$ with respect to $x$.
Let $y = \sin(u)$ where $u = x^2 + 5$.
$\frac{dy}{du} = \cos u$
$\frac{du}{dx} = 2x$
By chain rule, $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = (\cos u)(2x) = 2x \cos(x^2+5)$.

**Question 7 (Page 19):** Differentiate $2\sqrt{\cot(x^2)}$ with respect to $x$.
Let $y = 2\sqrt{u}$ where $u = \cot(v)$ and $v = x^2$.
$\frac{dy}{du} = 2 \cdot \frac{1}{2\sqrt{u}} = \frac{1}{\sqrt{u}}$
$\frac{du}{dv} = -\csc^2 v$
$\frac{dv}{dx} = 2x$
By chain rule, $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dv} \cdot \frac{dv}{dx} = \frac{1}{\sqrt{\cot(x^2)}} \cdot (-\csc^2(x^2)) \cdot (2x)$
$= \frac{-2x \csc^2(x^2)}{\sqrt{\cot(x^2)}}$.

---

## 5.3.2 Derivatives of Implicit Functions

An **implicit function** is a function where $y$ is not explicitly expressed in terms of $x$ (e.g., $x^2 + y^2 = 25$). To find $\frac{dy}{dx}$, we differentiate both sides of the equation with respect to $x$, treating $y$ as a function of $x$ and using the chain rule for terms involving $y$.

**Example 23 (Page 20):** Find $\frac{dy}{dx}$ if $y + \sin y = \cos x$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(y) + \frac{d}{dx}(\sin y) = \frac{d}{dx}(\cos x)$
$\frac{dy}{dx} + \cos y \frac{dy}{dx} = -\sin x$ (Remember $\frac{d}{dx}(\sin y) = \cos y \cdot \frac{dy}{dx}$ by chain rule)
Factor out $\frac{dy}{dx}$:
$\frac{dy}{dx}(1 + \cos y) = -\sin x$
$\frac{dy}{dx} = \frac{-\sin x}{1 + \cos y}$ [1]

---

### Practice Exercise 5.3

**Question 3 (Page 22):** Find $\frac{dy}{dx}$ for $ax + by^2 = \cos y$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(ax) + \frac{d}{dx}(by^2) = \frac{d}{dx}(\cos y)$
$a + b(2y)\frac{dy}{dx} = (-\sin y)\frac{dy}{dx}$
$a + 2by\frac{dy}{dx} = -\sin y\frac{dy}{dx}$
Rearrange to solve for $\frac{dy}{dx}$:
$a = -\sin y \frac{dy}{dx} - 2by \frac{dy}{dx}$
$a = \frac{dy}{dx}(-\sin y - 2by)$
$\frac{dy}{dx} = \frac{a}{-( \sin y + 2by )} = \frac{-a}{\sin y + 2by}$.

---

## 5.3.3 Derivatives of Inverse Trigonometric Functions

Inverse trigonometric functions are continuous. We use the chain rule to find their derivatives.

**Example 24 (Page 21):** Find the derivative of $f(x) = \sin^{-1} x$.
Let $y = \sin^{-1} x$. This means $x = \sin y$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(x) = \frac{d}{dx}(\sin y)$
$1 = \cos y \frac{dy}{dx}$
$\frac{dy}{dx} = \frac{1}{\cos y}$
Since $y = \sin^{-1} x$, and $-\frac{\pi}{2} \le y \le \frac{\pi}{2}$, $\cos y \ge 0$.
Also, $\cos^2 y + \sin^2 y = 1 \implies \cos y = \sqrt{1 - \sin^2 y}$.
Substitute $\sin y = x$: $\cos y = \sqrt{1 - x^2}$.
So, $\frac{dy}{dx} = \frac{1}{\sqrt{1 - x^2}}$. This is defined for $x \in (-1, 1)$. [1]

**Summary of Derivatives (Table, Page 21):**
| $f(x)$         | $f'(x)$                        | Domain of $f'(x)$ |
| :------------- | :----------------------------- | :---------------- |
| $\sin^{-1} x$  | $\frac{1}{\sqrt{1-x^2}}$       | $(-1, 1)$         |
| $\cos^{-1} x$  | $-\frac{1}{\sqrt{1-x^2}}$      | $(-1, 1)$         |
| $\tan^{-1} x$  | $\frac{1}{1+x^2}$              | $\mathbb{R}$      |
| $\cot^{-1} x$  | $-\frac{1}{1+x^2}$             | $\mathbb{R}$      |
| $\sec^{-1} x$  | $\frac{1}{|x|\sqrt{x^2-1}}$    | $|x| > 1$         |
| $\csc^{-1} x$  | $-\frac{1}{|x|\sqrt{x^2-1}}$   | $|x| > 1$         |

---

### Practice Exercise 5.3

**Question 9 (Page 22):** Find $\frac{dy}{dx}$ for $y = \sin^{-1}\left(\frac{2x}{1+x^2}\right)$.
This looks like a substitution problem. Recall the identity $2\tan\theta / (1+\tan^2\theta) = \sin(2\theta)$.
Let $x = \tan \theta$. Then $\theta = \tan^{-1} x$.
$y = \sin^{-1}\left(\frac{2\tan\theta}{1+\tan^2\theta}\right) = \sin^{-1}(\sin(2\theta))$
$y = 2\theta = 2\tan^{-1} x$.
Now differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(2\tan^{-1} x) = 2 \cdot \frac{1}{1+x^2} = \frac{2}{1+x^2}$.

---

## 5.4 Exponential and Logarithmic Functions

**Exponential Function (Definition 3, Page 23):** $y = f(x) = b^x$ where $b > 1$.
*   Domain: $\mathbb{R}$
*   Range: $(0, \infty)$
*   Always passes through $(0, 1)$ (since $b^0 = 1$).
*   Ever increasing.
*   Special base: $e \approx 2.718$. $y = e^x$ is the **natural exponential function**.

**Logarithmic Function (Definition 4, Page 24):** $y = \log_b a = x \iff b^x = a$.
*   Domain: $(0, \infty)$ (logarithm of non-positive numbers is undefined).
*   Range: $\mathbb{R}$
*   Always passes through $(1, 0)$ (since $\log_b 1 = 0$).
*   Ever increasing.
*   Special base: $e$. $y = \log_e x$ is the **natural logarithm**, denoted as $\ln x$. Your textbook uses $\log x$ to mean $\ln x$ in this chapter. [1]

**Properties of Logarithms (Page 25):**
*   Change of base: $\log_b p = \frac{\log_a p}{\log_a b}$
*   Product rule: $\log_b (pq) = \log_b p + \log_b q$
*   Quotient rule: $\log_b (p/q) = \log_b p - \log_b q$
*   Power rule: $\log_b (p^n) = n \log_b p$

**Example 25 (Page 26):** Is it true that $x = e^{\log x}$ for all real $x$?
No, it's only true for **positive** values of $x$, because $\log x$ is only defined for $x > 0$. [1]

### Derivatives of Exponential and Logarithmic Functions

**Theorem 5 (Page 26):**
1.  $\frac{d}{dx}(e^x) = e^x$
2.  $\frac{d}{dx}(\log x) = \frac{1}{x}$ (where $\log x$ means $\ln x$)

Using the chain rule, we can extend these:
*   $\frac{d}{dx}(e^{u(x)}) = e^{u(x)} \cdot u'(x)$
*   $\frac{d}{dx}(\log(u(x))) = \frac{1}{u(x)} \cdot u'(x)$

**Example 26(i) (Page 26):** Differentiate $e^{-x}$ w.r.t. $x$.
Let $y = e^u$ where $u = -x$.
$\frac{dy}{du} = e^u$
$\frac{du}{dx} = -1$
$\frac{dy}{dx} = e^u \cdot (-1) = -e^{-x}$. [1]

**Example 26(ii) (Page 26):** Differentiate $\sin(\log x)$ w.r.t. $x$.
Let $y = \sin u$ where $u = \log x$.
$\frac{dy}{du} = \cos u$
$\frac{du}{dx} = \frac{1}{x}$
$\frac{dy}{dx} = \cos u \cdot \frac{1}{x} = \frac{\cos(\log x)}{x}$. [1]

---

### Practice Exercise 5.4

**Question 1 (Page 27):** Differentiate $\sin(x^2+5)$ with respect to $x$. (This is the same as 5.2, Q1 - good for recall!)
This is $\frac{d}{dx} \sin(x^2+5) = \cos(x^2+5) \cdot \frac{d}{dx}(x^2+5) = \cos(x^2+5) \cdot 2x = 2x \cos(x^2+5)$.

**Question 5 (Page 27):** Differentiate $\log(\cos e^x)$ with respect to $x$.
Let $y = \log(u)$, where $u = \cos v$, and $v = e^x$.
$\frac{dy}{du} = \frac{1}{u}$
$\frac{du}{dv} = -\sin v$
$\frac{dv}{dx} = e^x$
$\frac{dy}{dx} = \frac{1}{\cos e^x} \cdot (-\sin e^x) \cdot e^x = -e^x \tan e^x$.

---

## 5.5 Logarithmic Differentiation

This technique is useful when differentiating functions of the form $f(x) = [u(x)]^{v(x)}$ or products/quotients of many functions. The idea is to take the natural logarithm of both sides first, use logarithm properties to simplify, and then differentiate implicitly. Remember, $f(x)$ and $u(x)$ must be positive for their logarithms to be defined. [1]

**General steps:**
1.  Let $y = f(x)$.
2.  Take $\log_e$ (or $\ln$) on both sides: $\ln y = \ln[f(x)]$.
3.  Use logarithm properties to simplify the right side.
4.  Differentiate both sides with respect to $x$, remembering that $\frac{d}{dx}(\ln y) = \frac{1}{y}\frac{dy}{dx}$.
5.  Solve for $\frac{dy}{dx}$.

**Example 29 (Page 29):** Differentiate $x^{\sin x}$ w.r.t. $x$ (for $x>0$).
Let $y = x^{\sin x}$.
Take $\ln$ on both sides: $\ln y = \ln(x^{\sin x}) = \sin x \cdot \ln x$.
Differentiate implicitly with respect to $x$:
$\frac{1}{y}\frac{dy}{dx} = \frac{d}{dx}(\sin x \cdot \ln x)$
Using the product rule on the right side:
$\frac{1}{y}\frac{dy}{dx} = (\cos x)(\ln x) + (\sin x)\left(\frac{1}{x}\right)$
$\frac{dy}{dx} = y \left[\cos x \ln x + \frac{\sin x}{x}\right]$
Substitute $y = x^{\sin x}$ back:
$\frac{dy}{dx} = x^{\sin x} \left[\cos x \ln x + \frac{\sin x}{x}\right]$. [1]

---

### Practice Exercise 5.5

**Question 3 (Page 31):** Differentiate $(\log x)^{\cos x}$ with respect to $x$.
Let $y = (\log x)^{\cos x}$.
Take $\ln$ on both sides: $\ln y = \ln((\log x)^{\cos x}) = \cos x \cdot \ln(\log x)$.
Differentiate implicitly with respect to $x$:
$\frac{1}{y}\frac{dy}{dx} = \frac{d}{dx}(\cos x \cdot \ln(\log x))$
Using the product rule:
$\frac{1}{y}\frac{dy}{dx} = (-\sin x)(\ln(\log x)) + (\cos x)\left(\frac{d}{dx}(\ln(\log x))\right)$
For $\frac{d}{dx}(\ln(\log x))$, use chain rule: $\frac{1}{\log x} \cdot \frac{d}{dx}(\log x) = \frac{1}{\log x} \cdot \frac{1}{x}$.
So, $\frac{1}{y}\frac{dy}{dx} = -\sin x \ln(\log x) + \cos x \left(\frac{1}{x \log x}\right)$
$\frac{dy}{dx} = (\log x)^{\cos x} \left[-\sin x \ln(\log x) + \frac{\cos x}{x \log x}\right]$.

---

## 5.6 Derivatives of Functions in Parametric Forms

Sometimes, $x$ and $y$ are both expressed as functions of a third variable, called a **parameter** (e.g., $t$ or $\theta$). For example, $x = f(t)$ and $y = g(t)$.
To find $\frac{dy}{dx}$, we use the chain rule:
$$ \frac{dy}{dx} = \frac{dy/dt}{dx/dt}, \quad \text{provided } \frac{dx}{dt} \ne 0 $$
You calculate $\frac{dy}{dt}$ and $\frac{dx}{dt}$ separately and then divide. [1]

**Example 32 (Page 32):** Find $\frac{dy}{dx}$ if $x = at^2$, $y = 2at$.
*   Find $\frac{dx}{dt}$:
    $\frac{dx}{dt} = \frac{d}{dt}(at^2) = 2at$
*   Find $\frac{dy}{dt}$:
    $\frac{dy}{dt} = \frac{d}{dt}(2at) = 2a$
*   Now, apply the formula:
    $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{2a}{2at} = \frac{1}{t}$. [1]

---

### Practice Exercise 5.6

**Question 1 (Page 34):** If $x = 2at^2$, $y = at^4$, find $\frac{dy}{dx}$.
*   $\frac{dx}{dt} = \frac{d}{dt}(2at^2) = 4at$
*   $\frac{dy}{dt} = \frac{d}{dt}(at^4) = 4at^3$
*   $\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{4at^3}{4at} = t^2$.

**Question 7 (Page 34):** If $x = \frac{\sin^3 t}{\sqrt{\cos 2t}}$, $y = \frac{\cos^3 t}{\sqrt{\cos 2t}}$, find $\frac{dy}{dx}$.
This one looks intimidating, but observe that $y/x = \cos^3 t / \sin^3 t = \cot^3 t$.
To find $\frac{dy}{dx}$, we will directly compute $\frac{dx}{dt}$ and $\frac{dy}{dt}$.

1.  **Calculate $\frac{dx}{dt}$**: Using the quotient rule $\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}$
    Let $u = \sin^3 t$ and $v = \sqrt{\cos 2t} = (\cos 2t)^{1/2}$.
    $u' = 3\sin^2 t \cos t$
    $v' = \frac{1}{2}(\cos 2t)^{-1/2} (-2\sin 2t) = -\frac{\sin 2t}{\sqrt{\cos 2t}}$
    $\frac{dx}{dt} = \frac{(3\sin^2 t \cos t)(\sqrt{\cos 2t}) - (\sin^3 t)\left(-\frac{\sin 2t}{\sqrt{\cos 2t}}\right)}{\cos 2t}$
    Multiply numerator and denominator by $\sqrt{\cos 2t}$:
    $\frac{dx}{dt} = \frac{3\sin^2 t \cos t \cos 2t + \sin^3 t \sin 2t}{(\cos 2t)^{3/2}}$

2.  **Calculate $\frac{dy}{dt}$**: Similarly for $y = \frac{\cos^3 t}{\sqrt{\cos 2t}}$.
    Let $u = \cos^3 t$ and $v = \sqrt{\cos 2t}$.
    $u' = 3\cos^2 t (-\sin t) = -3\cos^2 t \sin t$
    $v' = -\frac{\sin 2t}{\sqrt{\cos 2t}}$
    $\frac{dy}{dt} = \frac{(-3\cos^2 t \sin t)(\sqrt{\cos 2t}) - (\cos^3 t)\left(-\frac{\sin 2t}{\sqrt{\cos 2t}}\right)}{\cos 2t}$
    Multiply numerator and denominator by $\sqrt{\cos 2t}$:
    $\frac{dy}{dt} = \frac{-3\cos^2 t \sin t \cos 2t + \cos^3 t \sin 2t}{(\cos 2t)^{3/2}}$

3.  **Calculate $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$**:
    $\frac{dy}{dx} = \frac{\frac{-3\cos^2 t \sin t \cos 2t + \cos^3 t \sin 2t}{(\cos 2t)^{3/2}}}{\frac{3\sin^2 t \cos t \cos 2t + \sin^3 t \sin 2t}{(\cos 2t)^{3/2}}}$
    $\frac{dy}{dx} = \frac{-3\cos^2 t \sin t \cos 2t + \cos^3 t \sin 2t}{3\sin^2 t \cos t \cos 2t + \sin^3 t \sin 2t}$
    Factor out $\sin t \cos t$ from both numerator and denominator:
    $\frac{dy}{dx} = \frac{\sin t \cos t (-3\cos t \cos 2t + \cos^2 t (\frac{\sin 2t}{\sin t \cos t})\sin t \cos t)}{ \sin t \cos t (3\sin t \cos 2t + \sin^2 t (\frac{\sin 2t}{\sin t \cos t})\sin t \cos t)}$
    This factoring needs to be done carefully. Let's factor out $\sin t \cos t$ from each term first.
    Numerator: $\cos^2 t \sin t (-3\cos 2t + \cos t \frac{\sin 2t}{\sin t})$
    Denominator: $\sin^2 t \cos t (3\cos 2t + \sin t \frac{\sin 2t}{\cos t})$
    Use $\sin 2t = 2\sin t \cos t$.
    Numerator: $\cos^2 t \sin t (-3\cos 2t + \cos t (2\cos t)) = \cos^2 t \sin t (-3\cos 2t + 2\cos^2 t)$
    Denominator: $\sin^2 t \cos t (3\cos 2t + \sin t (2\sin t)) = \sin^2 t \cos t (3\cos 2t + 2\sin^2 t)$
    Now simplify common factors:
    $\frac{dy}{dx} = \frac{\cos t (-3\cos 2t + 2\cos^2 t)}{\sin t (3\cos 2t + 2\sin^2 t)} = \cot t \frac{-3\cos 2t + 2\cos^2 t}{3\cos 2t + 2\sin^2 t}$
    Now use the double angle identities: $\cos 2t = 2\cos^2 t - 1$ and $\cos 2t = 1 - 2\sin^2 t$.
    Numerator: $-3(2\cos^2 t - 1) + 2\cos^2 t = -6\cos^2 t + 3 + 2\cos^2 t = 3 - 4\cos^2 t$
    Denominator: $3(1 - 2\sin^2 t) + 2\sin^2 t = 3 - 6\sin^2 t + 2\sin^2 t = 3 - 4\sin^2 t$
    So, $\frac{dy}{dx} = \cot t \frac{3 - 4\cos^2 t}{3 - 4\sin^2 t}$.
    Recall the triple angle formulas: $\cos 3t = 4\cos^3 t - 3\cos t$ and $\sin 3t = 3\sin t - 4\sin^3 t$.
    Numerator: $-(4\cos^2 t - 3)\cos t = -\cos t (4\cos^2 t - 3)$.
    Denominator: $(3 - 4\sin^2 t)\sin t$.
    Let's go back to: $\frac{dy}{dx} = \frac{-3\cos t \cos 2t + 2\cos^3 t}{3\sin t \cos 2t + 2\sin^3 t}$
    Numerator: $2\cos^3 t - 3\cos t \cos 2t = 2\cos^3 t - 3\cos t (2\cos^2 t - 1) = 2\cos^3 t - 6\cos^3 t + 3\cos t = 3\cos t - 4\cos^3 t = - (4\cos^3 t - 3\cos t) = -\cos 3t$.
    Denominator: $3\sin t \cos 2t + 2\sin^3 t = 3\sin t (1 - 2\sin^2 t) + 2\sin^3 t = 3\sin t - 6\sin^3 t + 2\sin^3 t = 3\sin t - 4\sin^3 t = \sin 3t$.
    Therefore, $\frac{dy}{dx} = \frac{-\cos 3t}{\sin 3t} = -\cot 3t$.

---

## 5.7 Second Order Derivative

The **second order derivative** of $y=f(x)$ is the derivative of the first derivative $\frac{dy}{dx}$. It's denoted by $\frac{d^2 y}{dx^2}$ or $f''(x)$ or $y''$ or $y_2$. [1]
To find it, you first find $\frac{dy}{dx}$, and then differentiate that result with respect to $x$.

**Example 35 (Page 35):** Find $\frac{d^2 y}{dx^2}$ if $y = x^3 + \tan x$.
*   **First derivative**:
    $\frac{dy}{dx} = \frac{d}{dx}(x^3 + \tan x) = 3x^2 + \sec^2 x$
*   **Second derivative**:
    $\frac{d^2 y}{dx^2} = \frac{d}{dx}(3x^2 + \sec^2 x)$
    $= \frac{d}{dx}(3x^2) + \frac{d}{dx}(\sec^2 x)$
    $= 6x + 2\sec x \cdot (\frac{d}{dx}(\sec x))$
    $= 6x + 2\sec x \cdot (\sec x \tan x)$
    $= 6x + 2\sec^2 x \tan x$. [1]

---

### Practice Exercise 5.7

**Question 1 (Page 36):** Find the second order derivative of $x^2 + 3x + 2$.
Let $y = x^2 + 3x + 2$.
*   $\frac{dy}{dx} = \frac{d}{dx}(x^2 + 3x + 2) = 2x + 3$
*   $\frac{d^2 y}{dx^2} = \frac{d}{dx}(2x + 3) = 2$.

**Question 11 (Page 36):** If $y = 5\cos x - 3\sin x$, prove that $\frac{d^2 y}{dx^2} + y = 0$.
*   **First derivative**:
    $\frac{dy}{dx} = \frac{d}{dx}(5\cos x - 3\sin x) = -5\sin x - 3\cos x$
*   **Second derivative**:
    $\frac{d^2 y}{dx^2} = \frac{d}{dx}(-5\sin x - 3\cos x) = -5\cos x - 3(-\sin x) = -5\cos x + 3\sin x$
*   **Check the equation**:
    $\frac{d^2 y}{dx^2} + y = (-5\cos x + 3\sin x) + (5\cos x - 3\sin x)$
    $= -5\cos x + 3\sin x + 5\cos x - 3\sin x = 0$.
    Hence proved.

---

## Miscellaneous Examples and Summary

You've covered a lot! Here's a quick recap of the most important takeaways:

*   **Continuity:** Function exists, limit exists, and they are equal at a point. Algebra of continuous functions holds. Composites of continuous functions are continuous.
*   **Differentiability:** LHD = RHD. Differentiability implies continuity, but not vice-versa.
*   **Chain Rule:** $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$ (essential for composite functions).
*   **Implicit Differentiation:** Differentiate terms with $y$ using chain rule (e.g., $\frac{d}{dx}(y^2) = 2y \frac{dy}{dx}$).
*   **Inverse Trig Derivatives:** Memorize or be able to derive them (e.g., $\frac{d}{dx}(\sin^{-1} x) = \frac{1}{\sqrt{1-x^2}}$).
*   **Exponential and Logarithmic Derivatives:** $\frac{d}{dx}(e^x) = e^x$, $\frac{d}{dx}(\log x) = \frac{1}{x}$. Apply chain rule.
*   **Logarithmic Differentiation:** Use for functions of the form $u(x)^{v(x)}$ or complex products/quotients. Take $\ln$ first.
*   **Parametric Differentiation:** $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$.
*   **Second Order Derivatives:** $\frac{d^2 y}{dx^2} = \frac{d}{dx}\left(\frac{dy}{dx}\right)$.

### Final Exam Tip:

*   **Understand the definitions thoroughly.** Especially continuity and differentiability at a point.
*   **Practice with different types of functions.** Piecewise functions for continuity, absolute value for differentiability, etc.
*   **Know your differentiation formulas.** Trig, inverse trig, exponential, log.
*   **Master the chain rule.** It's used almost everywhere.
*   **Simplify your answers.** Often, trigonometric identities or algebraic manipulation can lead to much cleaner results.
*   **Be neat and show all your steps.** This helps avoid errors and allows for partial credit.

You've got this! Revise these points and practice a few more questions from the exercises. Good luck!