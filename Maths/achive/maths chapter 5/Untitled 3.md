# ❓ Clarifications and Further Explanations

Let's break down your questions one by one.

---

## 1. What do we call this `|x|`?

The symbol `|x|` is called the **absolute value function** (or modulus function).

### Definition:
The absolute value of a real number $x$, denoted as $|x|$, is the non-negative value of $x$ without regard to its sign.
Mathematically, it's defined as:
$$ |x| = \begin{cases} x, & \text{if } x \ge 0 \\ -x, & \text{if } x < 0 \end{cases} $$

### Example:
*   $|5| = 5$
*   $|-5| = 5$
*   $|0| = 0$

### Significance in Differentiability:
As mentioned in our lesson, the function $f(x) = |x|$ is continuous everywhere, but it is **not differentiable at $x=0$**. This is because its graph has a sharp corner (or cusp) at $x=0$.
*   The left-hand derivative at $x=0$ is $-1$.
*   The right-hand derivative at $x=0$ is $1$.
Since LHD $\neq$ RHD, the derivative does not exist at $x=0$.

---

## 2. What do we call `f'(c)`?

The notation `f'(c)` represents the **derivative of the function $f(x)$ evaluated at the point $x=c$**.

### Breakdown:
*   `f'(x)`: This is the **first derivative** of the function $f$ with respect to $x$. It gives us a new function that tells us the instantaneous rate of change (or the slope of the tangent line) of $f(x)$ at any given point $x$.
*   `c`: This is a specific constant value or a specific point in the domain of the function.
*   `f'(c)`: When we substitute `c` into the derivative function `f'(x)`, we get the specific numerical value of the slope of the tangent line to the graph of $f(x)$ at the exact point $x=c$. It tells us how fast the function $f(x)$ is changing precisely at $x=c$.

### Context:
*   In the **Mean Value Theorem**, $f'(c)$ is the slope of the tangent line that is parallel to the secant line connecting the endpoints of the interval.
*   In **Rolle's Theorem**, $f'(c) = 0$, meaning the tangent line at $x=c$ is horizontal.

---

## 3. How does `sin u` become `cos u` (when differentiated)?

This is a fundamental differentiation rule, and it comes directly from the **definition of the derivative using limits**.

### The Limit Definition of the Derivative:
The derivative of a function $f(x)$ is defined as:
$$ f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h} $$

### Deriving the Derivative of $\sin x$:
Let $f(x) = \sin x$.
Then $f(x+h) = \sin(x+h)$.

Substitute into the limit definition:
$$ \frac{d}{dx}(\sin x) = \lim_{h \to 0} \frac{\sin(x+h) - \sin x}{h} $$

Use the trigonometric identity: $\sin A - \sin B = 2 \cos \left(\frac{A+B}{2}\right) \sin \left(\frac{A-B}{2}\right)$
Here, $A = x+h$ and $B = x$.
$A+B = 2x+h \implies \frac{A+B}{2} = x + \frac{h}{2}$
$A-B = h \implies \frac{A-B}{2} = \frac{h}{2}$

So, $\sin(x+h) - \sin x = 2 \cos \left(x + \frac{h}{2}\right) \sin \left(\frac{h}{2}\right)$.

Substitute this back into the limit:
$$ \frac{d}{dx}(\sin x) = \lim_{h \to 0} \frac{2 \cos \left(x + \frac{h}{2}\right) \sin \left(\frac{h}{2}\right)}{h} $$
Rearrange the terms:
$$ \frac{d}{dx}(\sin x) = \lim_{h \to 0} \left[ \cos \left(x + \frac{h}{2}\right) \cdot \frac{\sin \left(\frac{h}{2}\right)}{\frac{h}{2}} \right] $$
Now, apply the limits:
*   As $h \to 0$, $\cos \left(x + \frac{h}{2}\right) \to \cos x$.
*   As $h \to 0$, we know that $\lim_{\theta \to 0} \frac{\sin \theta}{\theta} = 1$. Here, let $\theta = \frac{h}{2}$. So, $\lim_{h \to 0} \frac{\sin \left(\frac{h}{2}\right)}{\frac{h}{2}} = 1$.

Therefore:
$$ \frac{d}{dx}(\sin x) = \cos x \cdot 1 = \cos x $$

When we say `sin u` becomes `cos u`, we are referring to the application of this fundamental rule, often as part of the chain rule where $u$ is itself a function of $x$. For example, if $y = \sin(x^2+5)$, then $u = x^2+5$. When differentiating `sin u` with respect to $u$, it becomes `cos u`. Then, by the chain rule, we multiply by `du/dx`.

---

## 4. How to Differentiate or Derive?

"Differentiate" and "derive" are often used interchangeably in the context of finding the derivative, though "differentiate" is the more precise mathematical term. To **differentiate** a function means to find its derivative.

The process of differentiation involves several key rules and concepts:

### Fundamental Rules:
1.  **Power Rule:** $\frac{d}{dx}(x^n) = nx^{n-1}$ (e.g., $\frac{d}{dx}(x^3) = 3x^2$)
2.  **Constant Rule:** $\frac{d}{dx}(c) = 0$ (e.g., $\frac{d}{dx}(7) = 0$)
3.  **Constant Multiple Rule:** $\frac{d}{dx}(cf(x)) = c \frac{d}{dx}(f(x))$ (e.g., $\frac{d}{dx}(5x^2) = 5 \cdot 2x = 10x$)
4.  **Sum/Difference Rule:** $\frac{d}{dx}(f(x) \pm g(x)) = \frac{d}{dx}(f(x)) \pm \frac{d}{dx}(g(x))$
    (e.g., $\frac{d}{dx}(x^2 + 3x) = 2x + 3$)
5.  **Product Rule:** $\frac{d}{dx}(u \cdot v) = u \frac{dv}{dx} + v \frac{du}{dx}$
    (e.g., $\frac{d}{dx}(x \sin x) = x(\cos x) + (\sin x)(1)$)
6.  **Quotient Rule:** $\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \frac{du}{dx} - u \frac{dv}{dx}}{v^2}$
    (e.g., $\frac{d}{dx}\left(\frac{e^x}{\sin x}\right) = \frac{\sin x \cdot e^x - e^x \cdot \cos x}{\sin^2 x}$)
7.  **Chain Rule:** $\frac{d}{dx}(f(g(x))) = f'(g(x)) \cdot g'(x)$ or $\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$ for $y=f(u)$ and $u=g(x)$.
    (e.g., $\frac{d}{dx}(\sin(x^2)) = \cos(x^2) \cdot (2x)$)

### Steps for Differentiating:

1.  **Identify the type of function:** Is it a polynomial, trigonometric, exponential, logarithmic, inverse trigonometric, or a combination?
2.  **Look for composite functions:** If it's a function within a function (e.g., $\sin(x^2+5)$), you'll need the chain rule.
3.  **Look for products or quotients:** If functions are multiplied or divided, use the product or quotient rule.
4.  **Consider implicit functions:** If $y$ is not explicitly isolated (e.g., $x^2+y^2=1$), differentiate implicitly.
5.  **Consider logarithmic differentiation:** For functions like $x^x$ or complex products/quotients.
6.  **Break down complex functions:** Apply the rules step-by-step from the outermost operation to the innermost.

### Example Revisited: Differentiating $y = \sin(x^2 + 5)$

1.  **Identify:** This is a composite trigonometric function.
2.  **Outermost function:** $\sin(\text{something})$. Its derivative with respect to that 'something' is $\cos(\text{something})$.
3.  **Innermost function (the 'something'):** $u = x^2 + 5$.
4.  **Differentiate the outermost with respect to $u$**: $\frac{d}{du}(\sin u) = \cos u$.
5.  **Differentiate the innermost with respect to $x$**: $\frac{d}{dx}(x^2+5) = 2x$.
6.  **Apply Chain Rule**: Multiply the results: $\frac{dy}{dx} = \cos(x^2+5) \cdot 2x = 2x \cos(x^2+5)$.

Practice is key to mastering these rules. Keep working through problems, and you'll find the patterns and applications become second nature!