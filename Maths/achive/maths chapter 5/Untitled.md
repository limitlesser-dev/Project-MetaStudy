# 📚 NCERT Class 12 Mathematics: Chapter 5 - Continuity and Differentiability

## 🙏 Introduction: Welcome, Future Mathematician!

Hello! As your math teacher, I'm here to guide you through Chapter 5: Continuity and Differentiability. This chapter is a cornerstone of calculus, building upon your understanding of limits and derivatives from Class 11. Mastering these concepts is crucial not just for your upcoming exam, but for higher mathematics and various scientific and engineering fields. We will explore each topic with clear explanations and solve problems directly from your NCERT textbook exercises. Let's get started!

---

## 🔗 1. Continuity

Continuity, in simple terms, means that you can draw the graph of a function without lifting your pen from the paper. There are no breaks, jumps, or holes in the graph.

### 📝 Definition of Continuity

A function $f(x)$ is said to be **continuous at a point** $x=c$ if:
1.  $f(c)$ is defined.
2.  $\lim_{x \to c^-} f(x)$ exists (Left-Hand Limit, LHL).
3.  $\lim_{x \to c^+} f(x)$ exists (Right-Hand Limit, RHL).
4.  The LHL, RHL, and $f(c)$ are all equal.

Mathematically, a function $f$ is continuous at $x=c$ if:
$$ \lim_{x \to c^-} f(x) = \lim_{x \to c^+} f(x) = f(c) $$

If a function is continuous at every point in its domain, it is said to be a **continuous function**.

### ➕➖✖️➗ Algebra of Continuous Functions

If $f$ and $g$ are two continuous functions at $x=c$, then:
*   $f+g$ is continuous at $x=c$.
*   $f-g$ is continuous at $x=c$.
*   $f \cdot g$ is continuous at $x=c$.
*   $f/g$ is continuous at $x=c$, provided $g(c) \neq 0$.

### 🎯 Exercise 5.1 Questions (Selected) [1]

Let's tackle some problems to solidify your understanding of continuity.

#### Question 1. Prove that the function $f(x) = 5x - 3$ is continuous at $x = 0$, at $x = -3$ and at $x = 5$. [1]

**_Explanation:_** This is a simple polynomial function. Polynomials are continuous everywhere. We will demonstrate this for a specific point.

**_Solution:_**
To prove continuity at $x=c$, we need to show that $\lim_{x \to c} f(x) = f(c)$.

**At $x = 0$:**
1.  $f(0) = 5(0) - 3 = -3$.
2.  $\lim_{x \to 0} f(x) = \lim_{x \to 0} (5x - 3) = 5(0) - 3 = -3$.
Since $\lim_{x \to 0} f(x) = f(0)$, the function is continuous at $x=0$.

**At $x = -3$:**
1.  $f(-3) = 5(-3) - 3 = -15 - 3 = -18$.
2.  $\lim_{x \to -3} f(x) = \lim_{x \to -3} (5x - 3) = 5(-3) - 3 = -18$.
Since $\lim_{x \to -3} f(x) = f(-3)$, the function is continuous at $x=-3$.

**At $x = 5$:**
1.  $f(5) = 5(5) - 3 = 25 - 3 = 22$.
2.  $\lim_{x \to 5} f(x) = \lim_{x \to 5} (5x - 3) = 5(5) - 3 = 22$.
Since $\lim_{x \to 5} f(x) = f(5)$, the function is continuous at $x=5$.

---

#### Question 5. Is the function $f$ defined by $f(x) = \begin{cases} x, & \text{if } x \le 1 \\ 5, & \text{if } x > 1 \end{cases}$ continuous at $x = 0$? At $x = 1$? At $x = 2$? [1]

**_Explanation:_** This is a piecewise function. We need to check continuity at the points where the definition of the function changes (critical points) and also at points within the defined intervals.

**_Solution:_**

**At $x = 0$:**
Since $0 \le 1$, $f(x) = x$.
1.  $f(0) = 0$.
2.  $\lim_{x \to 0} f(x) = \lim_{x \to 0} x = 0$.
Since $\lim_{x \to 0} f(x) = f(0)$, the function is continuous at $x=0$.

**At $x = 1$ (Critical Point):**
We need to check LHL, RHL, and $f(1)$.
1.  $f(1) = 1$ (since $x \le 1$, we use $f(x) = x$).
2.  LHL: $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} x = 1$.
3.  RHL: $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} 5 = 5$.
Since LHL $\neq$ RHL ($1 \neq 5$), the limit $\lim_{x \to 1} f(x)$ does not exist.
Therefore, the function is **not continuous** at $x=1$. It has a jump discontinuity.

**At $x = 2$:**
Since $2 > 1$, $f(x) = 5$.
1.  $f(2) = 5$.
2.  $\lim_{x \to 2} f(x) = \lim_{x \to 2} 5 = 5$.
Since $\lim_{x \to 2} f(x) = f(2)$, the function is continuous at $x=2$.

---

#### Question 17. Find the relationship between $a$ and $b$ so that the function $f$ defined by $f(x) = \begin{cases} ax + 1, & \text{if } x \le 3 \\ bx + 3, & \text{if } x > 3 \end{cases}$ is continuous at $x = 3$. [1]

**_Explanation:_** For a piecewise function to be continuous at a critical point, the LHL, RHL, and the function value at that point must all be equal.

**_Solution:_**
For $f(x)$ to be continuous at $x=3$, we must have:
$\lim_{x \to 3^-} f(x) = \lim_{x \to 3^+} f(x) = f(3)$.

1.  $f(3) = a(3) + 1 = 3a + 1$ (using $f(x) = ax+1$ for $x \le 3$).
2.  LHL: $\lim_{x \to 3^-} f(x) = \lim_{x \to 3^-} (ax + 1) = a(3) + 1 = 3a + 1$.
3.  RHL: $\lim_{x \to 3^+} f(x) = \lim_{x \to 3^+} (bx + 3) = b(3) + 3 = 3b + 3$.

For continuity at $x=3$, LHL = RHL = $f(3)$:
$3a + 1 = 3b + 3$
$3a - 3b = 3 - 1$
$3a - 3b = 2$
This is the required relationship between $a$ and $b$ for the function to be continuous at $x=3$.

---

## 📈 2. Differentiability

Differentiability is about the smoothness of a function's graph. A function is differentiable at a point if it has a well-defined tangent line at that point. Geometrically, this means there are no sharp corners, cusps, or vertical tangent lines.

### 📝 Definition of Differentiability

A function $f(x)$ is differentiable at a point $x=c$ if the derivative $f'(c)$ exists.
The derivative is defined as:
$$ f'(c) = \lim_{h \to 0} \frac{f(c+h) - f(c)}{h} $$
For this limit to exist, the Left-Hand Derivative (LHD) and the Right-Hand Derivative (RHD) must be equal.
*   LHD at $x=c$: $L f'(c) = \lim_{h \to 0^-} \frac{f(c+h) - f(c)}{h}$
*   RHD at $x=c$: $R f'(c) = \lim_{h \to 0^+} \frac{f(c+h) - f(c)}{h}$

If $L f'(c) = R f'(c)$, then $f(x)$ is differentiable at $x=c$.

### ↔️ Relationship between Continuity and Differentiability

An important theorem states:
**If a function is differentiable at a point, then it is necessarily continuous at that point.**
However, the converse is **not true**. A function can be continuous at a point but not differentiable at that point (e.g., functions with sharp corners like $|x|$ at $x=0$).

---

### ⛓️ 2.1. Derivatives of Composite Functions (Chain Rule)

The chain rule is used to differentiate composite functions. If $y = f(u)$ and $u = g(x)$, then $y = f(g(x))$.
The chain rule states:
$$ \frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} $$

#### 🎯 Exercise 5.2 Questions (Selected) [1]

#### Question 1. Differentiate the function with respect to $x$: $\sin(x^2 + 5)$ [1]

**_Explanation:_** This is a composite function where the outer function is $\sin(u)$ and the inner function is $u = x^2+5$.

**_Solution:_**
Let $y = \sin(x^2 + 5)$.
Let $u = x^2 + 5$. Then $y = \sin u$.
Now, differentiate $y$ with respect to $u$:
$\frac{dy}{du} = \frac{d}{du}(\sin u) = \cos u$

And differentiate $u$ with respect to $x$:
$\frac{du}{dx} = \frac{d}{dx}(x^2 + 5) = 2x$

Using the chain rule, $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$:
$\frac{dy}{dx} = (\cos u) \cdot (2x)$
Substitute back $u = x^2 + 5$:
$\frac{dy}{dx} = 2x \cos(x^2 + 5)$

---

### 👻 2.2. Derivatives of Implicit Functions

An implicit function is a function where $y$ is not explicitly expressed in terms of $x$ (e.g., $x^2 + y^2 = 25$). To differentiate implicit functions, we differentiate both sides of the equation with respect to $x$, treating $y$ as a function of $x$ and using the chain rule for terms involving $y$.

#### 🎯 Exercise 5.3 Questions (Selected) [1]

#### Question 1. Find $\frac{dy}{dx}$ in the following: $2x + 3y = \sin x$ [1]

**_Explanation:_** Here $y$ is implicitly defined. We differentiate term by term.

**_Solution:_**
Given $2x + 3y = \sin x$.
Differentiate both sides with respect to $x$:
$\frac{d}{dx}(2x) + \frac{d}{dx}(3y) = \frac{d}{dx}(\sin x)$

$2 \cdot \frac{d}{dx}(x) + 3 \cdot \frac{d}{dx}(y) = \cos x$
$2 \cdot 1 + 3 \cdot \frac{dy}{dx} = \cos x$
$2 + 3 \frac{dy}{dx} = \cos x$
$3 \frac{dy}{dx} = \cos x - 2$
$\frac{dy}{dx} = \frac{\cos x - 2}{3}$

---

### 🔄 2.3. Derivatives of Inverse Trigonometric Functions

You should be familiar with the derivatives of basic inverse trigonometric functions. Remember to use appropriate substitutions when dealing with composite inverse trigonometric functions to simplify differentiation.

For example:
*   $\frac{d}{dx}(\sin^{-1} x) = \frac{1}{\sqrt{1-x^2}}$
*   $\frac{d}{dx}(\cos^{-1} x) = -\frac{1}{\sqrt{1-x^2}}$
*   $\frac{d}{dx}(\tan^{-1} x) = \frac{1}{1+x^2}$

#### 🎯 Exercise 5.3 Questions (Selected) [1]

#### Question 9. Find $\frac{dy}{dx}$ in the following: $y = \sin^{-1} \left(\frac{2x}{1+x^2}\right)$ [1]

**_Explanation:_** This expression can be simplified by a trigonometric substitution before differentiation to avoid complex chain rule application. Notice the form $\frac{2x}{1+x^2}$. This resembles the formula for $\sin(2\theta)$ if we let $x = \tan \theta$.

**_Solution:_**
Given $y = \sin^{-1} \left(\frac{2x}{1+x^2}\right)$.
Let $x = \tan \theta$. Then $\theta = \tan^{-1} x$.
Substitute $x = \tan \theta$ into the expression:
$y = \sin^{-1} \left(\frac{2 \tan \theta}{1+\tan^2 \theta}\right)$
We know that $\frac{2 \tan \theta}{1+\tan^2 \theta} = \sin(2\theta)$.
So, $y = \sin^{-1}(\sin(2\theta))$
$y = 2\theta$
Now substitute $\theta = \tan^{-1} x$:
$y = 2 \tan^{-1} x$

Now differentiate with respect to $x$:
$\frac{dy}{dx} = \frac{d}{dx}(2 \tan^{-1} x)$
$\frac{dy}{dx} = 2 \cdot \frac{1}{1+x^2}$
$\frac{dy}{dx} = \frac{2}{1+x^2}$

---

### Exponential and Logarithmic Functions

The derivatives of exponential and logarithmic functions are fundamental:
*   $\frac{d}{dx}(e^x) = e^x$
*   $\frac{d}{dx}(a^x) = a^x \log a$
*   $\frac{d}{dx}(\log x) = \frac{1}{x}$
*   $\frac{d}{dx}(\log_a x) = \frac{1}{x \log a}$

#### 🎯 Exercise 5.4 Questions (Selected) [1]

#### Question 1. Differentiate the following w.r.t. $x$: $\frac{e^x}{\sin x}$ [1]

**_Explanation:_** This is a quotient of two functions, so we will use the quotient rule:
If $y = \frac{u}{v}$, then $\frac{dy}{dx} = \frac{v \frac{du}{dx} - u \frac{dv}{dx}}{v^2}$.

**_Solution:_**
Let $y = \frac{e^x}{\sin x}$.
Here, $u = e^x$ and $v = \sin x$.
$\frac{du}{dx} = \frac{d}{dx}(e^x) = e^x$
$\frac{dv}{dx} = \frac{d}{dx}(\sin x) = \cos x$

Applying the quotient rule:
$\frac{dy}{dx} = \frac{(\sin x) \cdot e^x - (e^x) \cdot (\cos x)}{(\sin x)^2}$
$\frac{dy}{dx} = \frac{e^x (\sin x - \cos x)}{\sin^2 x}$

---

### 📝 2.5. Logarithmic Differentiation

Logarithmic differentiation is a technique used when differentiating functions that are:
1.  A product or quotient of many functions.
2.  Of the form $[f(x)]^{g(x)}$ (function raised to the power of another function).
The process involves taking the natural logarithm on both sides of the equation before differentiating.

#### 🎯 Exercise 5.5 Questions (Selected) [1]

#### Question 1. Differentiate the function with respect to $x$: $\cos x \cdot \cos 2x \cdot \cos 3x$ [1]

**_Explanation:_** This is a product of three functions. While the product rule can be extended, logarithmic differentiation simplifies the process.

**_Solution:_**
Let $y = \cos x \cdot \cos 2x \cdot \cos 3x$.
Take natural logarithm on both sides:
$\log y = \log(\cos x \cdot \cos 2x \cdot \cos 3x)$
Using the logarithm property $\log(abc) = \log a + \log b + \log c$:
$\log y = \log(\cos x) + \log(\cos 2x) + \log(\cos 3x)$

Now differentiate both sides with respect to $x$:
$\frac{d}{dx}(\log y) = \frac{d}{dx}(\log(\cos x)) + \frac{d}{dx}(\log(\cos 2x)) + \frac{d}{dx}(\log(\cos 3x))$

Using the chain rule $\frac{d}{dx}(\log f(x)) = \frac{1}{f(x)} \cdot f'(x)$:
$\frac{1}{y} \frac{dy}{dx} = \frac{1}{\cos x} (-\sin x) + \frac{1}{\cos 2x} (-\sin 2x \cdot 2) + \frac{1}{\cos 3x} (-\sin 3x \cdot 3)$
$\frac{1}{y} \frac{dy}{dx} = -\tan x - 2\tan 2x - 3\tan 3x$
$\frac{dy}{dx} = y (-\tan x - 2\tan 2x - 3\tan 3x)$
Substitute back $y = \cos x \cdot \cos 2x \cdot \cos 3x$:
$\frac{dy}{dx} = -(\cos x \cdot \cos 2x \cdot \cos 3x)(\tan x + 2\tan 2x + 3\tan 3x)$

---

### ⚙️ 2.6. Derivatives of Functions in Parametric Forms

When $x$ and $y$ are both expressed as functions of a third variable (parameter, say $t$ or $\theta$), such as $x = f(t)$ and $y = g(t)$, these are parametric functions.
To find $\frac{dy}{dx}$, we use the formula:
$$ \frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{g'(t)}{f'(t)}, \quad \text{provided } \frac{dx}{dt} \neq 0 $$

#### 🎯 Exercise 5.6 Questions (Selected) [1]

#### Question 1. If $x$ and $y$ are connected parametrically by the equation, without eliminating the parameter, find $\frac{dy}{dx}$: $x = 2at^2$, $y = at^4$ [1]

**_Explanation:_** Here $t$ is the parameter. We will find $\frac{dx}{dt}$ and $\frac{dy}{dt}$ and then use the formula.

**_Solution:_**
Given $x = 2at^2$ and $y = at^4$.

Differentiate $x$ with respect to $t$:
$\frac{dx}{dt} = \frac{d}{dt}(2at^2) = 2a \cdot 2t = 4at$

Differentiate $y$ with respect to $t$:
$\frac{dy}{dt} = \frac{d}{dt}(at^4) = a \cdot 4t^3 = 4at^3$

Now, find $\frac{dy}{dx}$:
$\frac{dy}{dx} = \frac{dy/dt}{dx/dt} = \frac{4at^3}{4at}$
$\frac{dy}{dx} = t^2$

---

### 🥈 2.7. Second Order Derivatives

The second order derivative is simply the derivative of the first derivative.
If $y = f(x)$, then the first derivative is $\frac{dy}{dx} = f'(x)$.
The second derivative is denoted as $\frac{d^2y}{dx^2}$ or $f''(x)$, and it is calculated as:
$$ \frac{d^2y}{dx^2} = \frac{d}{dx} \left( \frac{dy}{dx} \right) $$

#### 🎯 Exercise 5.7 Questions (Selected) [1]

#### Question 1. Find the second order derivative of the function: $x^2 + 3x + 2$ [1]

**_Explanation:_** We will first find the first derivative, and then differentiate that result to get the second derivative.

**_Solution:_**
Let $y = x^2 + 3x + 2$.

First derivative:
$\frac{dy}{dx} = \frac{d}{dx}(x^2 + 3x + 2) = 2x + 3$

Second derivative:
$\frac{d^2y}{dx^2} = \frac{d}{dx}\left(\frac{dy}{dx}\right) = \frac{d}{dx}(2x + 3)$
$\frac{d^2y}{dx^2} = 2$

---

## 🏛️ 3. Rolle's Theorem and Mean Value Theorem (Lagrange's)

These theorems are crucial in calculus as they establish relationships between the value of a function and its derivative over an interval.

### 📜 Rolle's Theorem

If a function $f:[a, b] \to \mathbb{R}$ is such that:
1.  It is **continuous** on the closed interval $[a, b]$.
2.  It is **differentiable** on the open interval $(a, b)$.
3.  $f(a) = f(b)$.

Then there exists **at least one point** $c$ in the open interval $(a, b)$ such that $f'(c) = 0$.

Geometrically, this means if a continuous and differentiable curve starts and ends at the same height, there must be at least one point between the start and end where the tangent to the curve is horizontal (i.e., its slope is zero).

### 📜 Mean Value Theorem (Lagrange's)

If a function $f:[a, b] \to \mathbb{R}$ is such that:
1.  It is **continuous** on the closed interval $[a, b]$.
2.  It is **differentiable** on the open interval $(a, b)$.

Then there exists **at least one point** $c$ in the open interval $(a, b)$ such that:
$$ f'(c) = \frac{f(b) - f(a)}{b - a} $$

Geometrically, this means there is at least one point on the curve where the tangent line is parallel to the secant line connecting the endpoints $(a, f(a))$ and $(b, f(b))$. Rolle's Theorem is a special case of the Mean Value Theorem where $f(a) = f(b)$, which makes $\frac{f(b) - f(a)}{b - a} = 0$.

#### 🎯 Exercise 5.8 Questions (Selected) [1]

Let's look at an example from Exercise 5.8 to apply these theorems.

#### Question 2. Examine if Rolle's Theorem is applicable to any of the following functions. Can you say something about the converse of Rolle's Theorem? [1]
#### (i) $f(x) = [x]$ for $x \in [5, 9]$ [1]

**_Explanation:_** For Rolle's Theorem to apply, the function must satisfy three conditions: continuity, differentiability, and $f(a)=f(b)$. We need to check these for the greatest integer function.

**_Solution:_**
Given $f(x) = [x]$ for $x \in [5, 9]$.

1.  **Continuity on $[5, 9]$:** The greatest integer function $f(x) = [x]$ is discontinuous at every integer point. Since the interval $[5, 9]$ contains integers like $5, 6, 7, 8, 9$, the function is not continuous on $[5, 9]$.

2.  **Differentiability on $(5, 9)$:** Since the function is not continuous at integer points, it cannot be differentiable at those points. Thus, it is not differentiable on $(5, 9)$.

Since the first two conditions of Rolle's Theorem are not satisfied, **Rolle's Theorem is not applicable** to $f(x) = [x]$ on $[5, 9]$.

---

#### Question 3. If $f(x) = x^2 - 1$ for $x \in [1, 2]$, verify the Mean Value Theorem. [1]

**_Explanation:_** For Mean Value Theorem, we need to check continuity, differentiability, and then find a $c$ such that $f'(c) = \frac{f(b) - f(a)}{b - a}$.

**_Solution:_**
Given $f(x) = x^2 - 1$ for $x \in [1, 2]$. Here, $a=1$ and $b=2$.

1.  **Continuity on $[1, 2]$:** $f(x) = x^2 - 1$ is a polynomial function. Polynomial functions are continuous everywhere. Thus, $f(x)$ is continuous on $[1, 2]$.
2.  **Differentiability on $(1, 2)$:** $f(x) = x^2 - 1$ is a polynomial function. Polynomial functions are differentiable everywhere. Thus, $f(x)$ is differentiable on $(1, 2)$.

Since both conditions are satisfied, the Mean Value Theorem is applicable.
Now, we need to find $c \in (1, 2)$ such that $f'(c) = \frac{f(b) - f(a)}{b - a}$.

First, find $f'(x)$:
$f'(x) = \frac{d}{dx}(x^2 - 1) = 2x$.
So, $f'(c) = 2c$.

Next, calculate $\frac{f(b) - f(a)}{b - a}$:
$f(a) = f(1) = 1^2 - 1 = 0$.
$f(b) = f(2) = 2^2 - 1 = 4 - 1 = 3$.

$\frac{f(b) - f(a)}{b - a} = \frac{f(2) - f(1)}{2 - 1} = \frac{3 - 0}{1} = 3$.

Now, set $f'(c)$ equal to this value:
$2c = 3$
$c = \frac{3}{2}$

Since $c = \frac{3}{2} = 1.5$, and $1.5 \in (1, 2)$, the Mean Value Theorem is verified.

---

## 📝 Key Takeaways for Your Exam

*   **Continuity:** Check LHL, RHL, and $f(c)$. They must all be equal. Polynomial, exponential, sine, cosine functions are always continuous in their domain.
*   **Differentiability:** A function is differentiable if its graph is smooth (no sharp corners or breaks). Every differentiable function is continuous, but not vice-versa.
*   **Chain Rule:** Essential for composite functions. Differentiate from outside to inside.
*   **Implicit Differentiation:** Differentiate terms with $y$ with respect to $x$ using the chain rule (e.g., $\frac{d}{dx}(y^2) = 2y \frac{dy}{dx}$).
*   **Logarithmic Differentiation:** Use for complex products/quotients or functions of the form $[f(x)]^{g(x)}$.
*   **Parametric Differentiation:** $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$.
*   **Second Order Derivatives:** Differentiate the first derivative.
*   **Rolle's Theorem:** $f(a)=f(b)$ is a critical condition, along with continuity and differentiability. Look for $f'(c)=0$.
*   **Mean Value Theorem:** A generalization of Rolle's Theorem. Look for $f'(c) = \frac{f(b) - f(a)}{b - a}$.

---

I hope this comprehensive lesson helps you feel confident for your exam tomorrow! Remember to practice as many problems as possible. If you have any specific questions or need more examples, feel free to ask! Good luck! You've got this!