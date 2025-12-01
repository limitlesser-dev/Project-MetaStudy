# 📚 NCERT Class 12 Mathematics: Chapter 5 - Continuity and Differentiability (Exam Ready Guide)

## 🎯 Chapter Overview: What to Study?

In this chapter, we investigate the "behavior" of functions – whether they are smooth (differentiable), or if they have breaks/jumps/holes (continuous). We then explore advanced methods for finding derivatives and also learn about some important theorems.

---

## ✅ Concepts to Understand (You MUST understand these!)

These are the core ideas that you need to grasp deeply. Simply memorizing formulas won't be enough. The logic and geometric meaning behind these concepts should be clear.

### 1. Continuity
*   **Visual Meaning:** Imagine drawing the graph without lifting your pen. If you have to lift your pen, it's discontinuous.
*   **Why 3 Conditions?** Each condition has its own purpose:
    *   `f(c)` is defined: There shouldn't be a hole at that point.
    *   Limit `lim x->c f(x)` exists (LHL = RHL): There shouldn't be a jump or a break in the graph where parts don't meet.
    *   Limit value = Function value: Where you expect the function to be, its actual value should also be there (the hole is "filled").
*   **Types of Functions:** Polynomials, exponentials, `sin x`, `cos x` are always continuous (in their domains). `tan x`, `sec x`, `cot x`, `cosec x` are discontinuous where their denominators are zero (outside their domains).
*   **Algebra of Continuous Functions:** If two functions are continuous, then their sum, difference, product, and quotient (provided the denominator is not zero) are also continuous.

### 2. Differentiability
*   **Visual Meaning:** A function is differentiable at a point if its graph is "smooth" at that point – no sharp corners (like the tip of `|x|` at `x=0`), cusps, or vertical tangents.
*   **Relationship with Continuity:** **If a function is differentiable at a point, it is always continuous at that point.** (Smooth means no breaks).
    *   **Converse is FALSE:** A function can be continuous but not differentiable (e.g., `|x|` at `x=0` is continuous but has a sharp corner, so not differentiable).
*   **Geometric Meaning of Derivative:** The derivative `f'(x)` represents the **slope of the tangent line** to the curve `y = f(x)` at any point `x`. It also signifies the **instantaneous rate of change** of `y` with respect to `x`.

### 3. Chain Rule
*   **Concept:** For composite functions (function inside a function, like `f(g(x))`). Differentiate "outside-in".
*   **Logic:** Imagine nested dolls. You differentiate the outermost doll, then the next inner one, and so on, multiplying each result.

### 4. Implicit Differentiation
*   **Concept:** For functions where `y` is not explicitly written as `f(x)` (e.g., $x^2 + y^2 = 25$).
*   **Logic:** Differentiate both sides of the equation with respect to `x`. Whenever you differentiate a term involving `y`, remember to multiply by `dy/dx` (because `y` is a function of `x`, and you're applying the chain rule).

### 5. Logarithmic Differentiation
*   **Concept:** Used for differentiating complex functions involving:
    *   Products and quotients of many functions.
    *   Functions of the form `[f(x)]^(g(x))` (variable raised to the power of a variable, e.g., $x^x$).
*   **Logic:** Take natural logarithm on both sides to convert products/quotients into sums/differences and powers into multipliers, making differentiation easier. Then use implicit differentiation.

### 6. Parametric Differentiation
*   **Concept:** When `x` and `y` are both expressed in terms of a third variable (parameter, say `t` or `θ`).
*   **Logic:** Find `dx/dt` and `dy/dt` separately, then use the formula $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$.

### 7. Second Order Derivatives
*   **Concept:** Differentiating the first derivative.
*   **Logic:** If `dy/dx` is `f'(x)`, then the second derivative `d²y/dx²` is simply $\frac{d}{dx}(f'(x))$. It gives information about the concavity of the curve.

### 8. Rolle's Theorem & Mean Value Theorem (MVT)
*   **Concept:** These are fundamental theorems about functions and their derivatives over an interval. They guarantee the existence of a point `c` with a specific derivative value.
*   **Rolle's Logic:** If a continuous and differentiable function starts and ends at the same height ($f(a)=f(b)$), then there must be at least one point in between where the tangent is horizontal ($f'(c)=0$).
*   **MVT Logic:** If a function is continuous and differentiable over an interval, there must be at least one point `c` where the tangent line is parallel to the secant line connecting the endpoints. Rolle's Theorem is a special case of MVT.

---

## 🧠 Things to Memorize (Yeh Yaad Karna Hai!)

These are the formulas and rules you should commit to memory for quick application in exams.

### A. Basic Derivatives (from Class 11 & now)
1.  $\frac{d}{dx}(c) = 0$ (c is a constant)
2.  $\frac{d}{dx}(x^n) = nx^{n-1}$
3.  $\frac{d}{dx}(e^x) = e^x$
4.  $\frac{d}{dx}(a^x) = a^x \log a$ (where $a > 0$)
5.  $\frac{d}{dx}(\log x) = \frac{1}{x}$ (natural log / $\ln x$)
6.  $\frac{d}{dx}(\log_a x) = \frac{1}{x \log a}$

### B. Trigonometric Derivatives
1.  $\frac{d}{dx}(\sin x) = \cos x$
2.  $\frac{d}{dx}(\cos x) = -\sin x$
3.  $\frac{d}{dx}(\tan x) = \sec^2 x$
4.  $\frac{d}{dx}(\cot x) = -\csc^2 x$
5.  $\frac{d}{dx}(\sec x) = \sec x \tan x$
6.  $\frac{d}{dx}(\csc x) = -\csc x \cot x$

### C. Inverse Trigonometric Derivatives
1.  $\frac{d}{dx}(\sin^{-1} x) = \frac{1}{\sqrt{1-x^2}}$
2.  $\frac{d}{dx}(\cos^{-1} x) = -\frac{1}{\sqrt{1-x^2}}$
3.  $\frac{d}{dx}(\tan^{-1} x) = \frac{1}{1+x^2}$
4.  $\frac{d}{dx}(\cot^{-1} x) = -\frac{1}{1+x^2}$
5.  $\frac{d}{dx}(\sec^{-1} x) = \frac{1}{|x|\sqrt{x^2-1}}$
6.  $\frac{d}{dx}(\csc^{-1} x) = -\frac{1}{|x|\sqrt{x^2-1}}$

### D. Differentiation Rules
1.  **Chain Rule:** $\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)$
2.  **Product Rule:** $\frac{d}{dx}(u \cdot v) = u \frac{dv}{dx} + v \frac{du}{dx}$
3.  **Quotient Rule:** $\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v \frac{du}{dx} - u \frac{dv}{dx}}{v^2}$
4.  **Parametric Differentiation:** $\frac{dy}{dx} = \frac{dy/dt}{dx/dt}$

### E. Theorems' Conditions & Conclusions
1.  **Rolle's Theorem:**
    *   **Conditions:** `f` is continuous on `[a, b]`, `f` is differentiable on `(a, b)`, `f(a) = f(b)`.
    *   **Conclusion:** There exists `c ∈ (a, b)` such that `f'(c) = 0`.
2.  **Mean Value Theorem (MVT):**
    *   **Conditions:** `f` is continuous on `[a, b]`, `f` is differentiable on `(a, b)`.
    *   **Conclusion:** There exists `c ∈ (a, b)` such that $f'(c) = \frac{f(b) - f(a)}{b - a}$.

---

## 💡 Smart Exam Tips

*   **Practice Piecewise Functions:** These are common for continuity questions. Always check LHL, RHL, and `f(c)` at the critical points where the definition changes.
*   **Trigonometric Substitutions:** For inverse trig functions, often $x = \sin\theta$, $x = \cos\theta$, $x = \tan\theta$ can simplify the expression dramatically before differentiating.
*   **Logarithm Properties:** For logarithmic differentiation, remember $\log(ab) = \log a + \log b$, $\log(a/b) = \log a - \log b$, $\log(a^b) = b \log a$.
*   **Implicit Differentiation Caution:** Remember to multiply by `dy/dx` every time you differentiate a `y` term with respect to `x`.
*   **Theorem Verification:** For Rolle's and MVT, always state and verify the conditions *first* before finding `c`.

---

All the best for your exam tomorrow! You've got a solid guide here. Go through it, understand the concepts, memorize the formulas, and practice with your textbook questions. You will do great!