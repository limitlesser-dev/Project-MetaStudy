

> [!info]
> I’ll teach you like a coach for tomorrow’s exam. I’m assuming NCERT Class 12 Maths Chapter 5 = ==Continuity and Differentiability==.
> If your Chapter 5 is different in your book, tell me and I’ll switch immediately.
>
> Also: I can’t reproduce NCERT’s exact exercise questions here. Instead, I’ve created ==NCERT-style problems== that mirror the types and difficulty of Exercises 5.1–5.8 so you’ll be fully prepared.

---

# 🧭 Game Plan (Tonight + Exam Morning)

- 60–90 mins: Learn/refresh core concepts + formulas (this note’s Sections 1–2).
- 60–90 mins: Do the worked examples (Section 3) actively (don’t just read).
- 30 mins: Speed drill (Section 4).
- 10 mins: Pitfalls + checklist (Section 5).
- Morning: Re-do 5–6 quick problems from Speed Drill you found tricky.

---

# 1) Concept Map — What this chapter covers

- Continuity of functions at a point, on an interval; types of discontinuity (removable, jump, infinite).
- Differentiability vs continuity; left/right derivative.
- Algebra of continuous/differentiable functions.
- Chain rule, product/quotient rules; implicit, parametric, logarithmic differentiation.
- Derivatives of:
  - Polynomials/rationals; trig/inverse trig; exponential/log functions.
- Mean Value Theorem (MVT) and Rolle’s Theorem: conditions + verification.

> [!tip]
> In CBSE-style questions, continuity/differentiability at a point and Rolle/MVT verification are frequent, along with chain/implicit/log differentiation questions.

---

# 2) One-Page Formula Sheet (High Yield)

## Continuity at x = c
- f is continuous at c iff
  - lim_{x→c^-} f(x) = lim_{x→c^+} f(x) = f(c)
- Algebra: If f, g continuous at c then f±g, f·g, f/g (if g(c)≠0), and g∘f are continuous.
- Standard continuous functions on their domains: polynomials, rationals (where denom ≠ 0), sin x, cos x, tan x, e^x, a^x (a>0), ln x, log_a x, inverse trigs (on suitable domains).

## Differentiability
- f is differentiable at c if left and right derivatives exist and are equal:
  - f'(c) = lim_{h→0} (f(c+h) − f(c))/h
- ==Differentiable ⇒ Continuous== (but not conversely; e.g., f(x)=|x| is continuous at 0 but not differentiable at 0).

## Standard Limits to remember
- lim_{x→0} (sin x)/x = 1
- lim_{x→0} (tan x)/x = 1
- lim_{x→0} (1 − cos x)/x = 0 and (1 − cos x)/x^2 = 1/2
- lim_{x→0} (e^x − 1)/x = 1
- lim_{x→0} (a^x − 1)/x = ln a  (a>0, a≠1)
- lim_{x→0} (ln(1+x))/x = 1

## Derivative Rules
- (f ± g)' = f' ± g'
- (fg)' = f'g + fg'
- (f/g)' = (f'g − fg')/g^2
- Chain: (g∘f)'(x) = g'(f(x)) · f'(x)
- Implicit: Differentiate both sides wrt x; collect dy/dx terms.
- Parametric: If x = x(t), y = y(t), then dy/dx = (dy/dt)/(dx/dt), when dx/dt ≠ 0.
- Log differentiation: For y = [u(x)]^{v(x)}, use ln y = v ln u, then differentiate.

## Standard Derivatives
- d/dx (x^n) = n x^{n−1}
- d/dx (e^x) = e^x;  d/dx (a^x) = a^x ln a
- d/dx (ln x) = 1/x;  d/dx (log_a x) = 1/(x ln a)
- d/dx (sin x) = cos x;  d/dx (cos x) = −sin x;  d/dx (tan x) = sec^2 x
- d/dx (sec x) = sec x tan x;  d/dx (csc x) = −csc x cot x;  d/dx (cot x) = −csc^2 x
- d/dx (sin^{-1} x) = 1/√(1−x^2)
- d/dx (cos^{-1} x) = −1/√(1−x^2)
- d/dx (tan^{-1} x) = 1/(1+x^2)

## Rolle’s Theorem and MVT
- Rolle’s: If f is continuous on [a,b], differentiable on (a,b), and f(a) = f(b), then ∃ c∈(a,b) with f'(c)=0.
- Mean Value Theorem (Lagrange): If f is continuous on [a,b], differentiable on (a,b), then ∃ c∈(a,b) with
  - f'(c) = (f(b) − f(a)) / (b − a)

> [!warning]
> At points where function definition changes (piecewise, |x|, [x], sgn x), always check LHL, RHL, f(c) for continuity; and L-derivative vs R-derivative for differentiability.

---

# 3) Worked Examples (NCERT-style)

I’ve organized them to mirror the flow of Exercises. Practice by pausing and attempting before you look at the solution.

## A. Continuity (mirrors Ex 5.1)

### A1. Find k so that f is continuous at x=2:
f(x) = 
- (x^2 − 4)/(x − 2), x ≠ 2
- k, x = 2

Solution:
- For x ≠ 2, simplify: (x^2 − 4)/(x − 2) = (x−2)(x+2)/(x−2) = x+2
- lim_{x→2} f(x) = 4. For continuity we need k = f(2) = 4.
==Answer: k=4==

---

### A2. Check continuity of f(x) = ⌊x⌋ at x=2 (⌊x⌋ is greatest integer ≤ x).
- lim_{x→2^-} f(x) = 1
- lim_{x→2^+} f(x) = 2
- f(2) = 2
Since LHL ≠ RHL, not continuous at x=2. ==Jump discontinuity== at integers.

---

### A3. Find k so that f is continuous at x=0:
f(x) =
- (sin ax)/(bx), x ≠ 0
- k, x=0
(a,b ≠ 0)

Solution:
- lim_{x→0} (sin ax)/(bx) = (a/b) · lim_{x→0} (sin ax)/(ax) = a/b
For continuity, k = a/b. ==Answer: k = a/b==

---

### A4. Identify type of discontinuity of f(x) = tan x at x = π/2.
- lim_{x→(π/2)^-} tan x = +∞, lim_{x→(π/2)^+} tan x = −∞
==Infinite (essential) discontinuity==.

---

## B. Differentiability vs Continuity (mirrors Ex 5.2)

### B1. Show f(x)=|x| is continuous at 0 but not differentiable at 0.
- Continuity: lim_{x→0}|x| = 0 = f(0)
- Left derivative at 0: lim_{h→0^-} (|h| − 0)/h = (−h)/h = −1
- Right derivative at 0: lim_{h→0^+} (|h| − 0)/h = h/h = 1
Unequal ⇒ not differentiable at 0.

---

### B2. Points of non-differentiability of f(x)=⌊x⌋.
- f is constant on each (n, n+1) with derivative 0 there.
- At every integer, jump ⇒ not differentiable at integers.

---

### B3. For f(x)=x|x|, show differentiability at 0.
- For x≥0: f=x^2 ⇒ f' = 2x
- For x<0: f=−x^2 ⇒ f' = −2x
- f'(0^+) = 0, f'(0^−) = 0 ⇒ differentiable at 0 with f'(0)=0.

---

## C. Chain, Implicit, Log, Parametric (mirrors Ex 5.3–5.5)

### C1. Differentiate: y = sin^5(3x)
Let u = sin(3x). Then y = u^5 ⇒ dy/du = 5u^4, du/dx = 3cos(3x)
So y' = 5[sin(3x)]^4 · 3cos(3x) = 15 sin^4(3x) cos(3x)

---

### C2. Differentiate using logarithmic differentiation: y = x^x (x>0)
ln y = x ln x ⇒ (y'/y) = 1·ln x + x·(1/x) = ln x + 1 ⇒
==y' = x^x (ln x + 1)==

---

### C3. Implicit differentiation: x^2 + y^2 = 1
2x + 2y (dy/dx) = 0 ⇒ dy/dx = −x/y

---

### C4. Parametric differentiation: x = a cos t, y = a sin t
dy/dx = (dy/dt)/(dx/dt) = (a cos t)/(−a sin t) = −cot t

---

### C5. Differentiate: y = (sin x)^{cos x}, 0<sin x≤1
ln y = cos x · ln(sin x)
y'/y = (−sin x)·ln(sin x) + cos x · (cos x/sin x)
= −sin x ln(sin x) + (cos^2 x)/(sin x)
⇒ y' = (sin x)^{cos x} [ −sin x ln(sin x) + (cos^2 x)/(sin x) ]

---

## D. Exponential/Log/Inverse Trig (mirrors Ex 5.6–5.7)

### D1. Differentiate: y = a^x, a>0, a≠1
y' = a^x ln a

---

### D2. Differentiate: y = ln(√(1+x^2))
y = (1/2) ln(1+x^2) ⇒ y' = (1/2) · (2x/(1+x^2)) = x/(1+x^2)

---

### D3. Differentiate: y = sin^{-1} ( 2x/(1+x^2) ), for |x|<1
Use identity: put x=tan θ ⇒ 2x/(1+x^2) = sin 2θ ⇒ y = 2θ = 2 tan^{-1} x
So y' = 2/(1+x^2)  (valid for |x|<1)

---

### D4. Differentiate: y = tan^{-1} ( (1−x)/(1+x) ), x≠−1
Let u = (1−x)/(1+x). Using d/dx [tan^{-1} u] = u'/(1+u^2):
u' = [−(1+x) − (1−x)]/(1+x)^2 = [−1 − x − 1 + x]/(1+x)^2 = −2/(1+x)^2
1+u^2 = 1 + (1−x)^2/(1+x)^2 = [(1+x)^2 + (1−x)^2]/(1+x)^2 = [2(1+x^2)]/(1+x)^2
Therefore y' = [−2/(1+x)^2] / [2(1+x^2)/(1+x)^2] = −1/(1+x^2)

---

## E. Rolle’s Theorem and MVT (mirrors Ex 5.8)

### E1. Verify Rolle’s Theorem for f(x)=x^3−3x on [−√3, √3]. Find c.
- f is a polynomial ⇒ continuous on [−√3, √3], differentiable on (−√3, √3)
- f(−√3) = −3√3 + 3√3 = 0; f(√3)=3√3 − 3√3 = 0 ⇒ f(a)=f(b)
- f'(x) = 3x^2 − 3 ⇒ f'(c)=0 ⇒ c=±1 (both in interval)
Any c∈{−1, 1} works.

---

### E2. Verify MVT for f(x)=ln x on [1, e^2]. Find c satisfying MVT conclusion.
- Continuous on [1, e^2], differentiable on (1, e^2).
- Average slope: (f(b)−f(a))/(b−a) = (2 − 0)/(e^2 − 1) = 2/(e^2 − 1)
- f'(x)=1/x; set 1/c = 2/(e^2 − 1) ⇒ c = (e^2 − 1)/2

---

# 4) Speed Drill (Exam Practice)

Try these without looking. Answers at the end of this section.

1) Find k so that f is continuous at x=1:
f(x)=
- (x^2−1)/(x−1), x≠1
- k, x=1

2) Check continuity and differentiability at x=0:
f(x)=
- x sin(1/x), x≠0
- 0, x=0

3) Find a,b so that f is differentiable at x=0:
f(x)=
- a x + b |x|, x∈ℝ

4) Evaluate: d/dx [ (x^2+1)^{3/2} ]

5) Evaluate: d/dx [ ln( (1+sin x)/(1−sin x) ) ]

6) dy/dx if sin(y) + y = x

7) dy/dx for x = a cos t, y = a(1 − cos t)

8) Show all points of discontinuity of f(x) = {x} (fractional part)

9) Differentiate: y = (x^x)^{sin x}

10) Evaluate: d/dx [ tan^{-1} ( (2x)/(1−x^2) ) ] for |x|<1

11) Find k so that f is continuous at 0:
f(x)=
- (1 − cos kx)/x^2, x≠0
- 1/2, x=0

12) Show whether f(x) = e^{|x|} is differentiable at 0.

13) If f(x)=ln(1+x) and g(x)=e^x, check MVT for h(x)=f(x)+g(x) on [0,1] and find c.

14) Find dy/dx at x=0 for y = sin^{-1}(x)·cos^{-1}(x).

15) Find points where f(x)=|x−2| + |x+1| is not differentiable.

<details>
<summary>Answers (click to expand)</summary>

1) k = lim_{x→1} (x^2−1)/(x−1) = lim (x+1) = 2 ⇒ k=2

2) At 0: lim_{x→0} x sin(1/x) = 0 ⇒ continuous. f'(0) = lim_{h→0} (h sin(1/h))/h = lim sin(1/h) does not exist ⇒ not differentiable at 0.

3) Left derivative at 0: a − b; Right derivative: a + b. For differentiable: a−b = a+b ⇒ b=0. Any a; b=0.

4) Use chain rule: (3/2)(x^2+1)^{1/2}·2x = 3x√(x^2+1)

5) Use ln A − ln B and t-formula:
Let u = (1+sin x)/(1−sin x) ⇒ d/dx ln u = u'/u = (2 cos x)/(1−sin^2 x) = (2 cos x)/(cos^2 x) = 2 sec x

6) Differentiate implicitly: cos y · (dy/dx) + dy/dx = 1 ⇒ dy/dx = 1/(1+cos y)

7) dy/dx = (dy/dt)/(dx/dt) = (a sin t)/(−a sin t) = −1 (except where sin t=0; there slope undefined from param speed)

8) {x} has jump discontinuities at integers; continuous on (n, n+1)

9) y = (x^x)^{sin x} = e^{sin x · x ln x}
ln y = sin x · x ln x
y'/y = cos x · x ln x + sin x · (ln x + 1)
⇒ y' = (x^x)^{sin x} [ x ln x · cos x + sin x (ln x + 1) ], x>0

10) tan^{-1}(2x/(1−x^2)) = 2 tan^{-1} x for |x|<1 ⇒ derivative = 2/(1+x^2)

11) lim_{x→0} (1 − cos kx)/x^2 = (k^2/2) ⇒ set = 1/2 ⇒ k^2/2 = 1/2 ⇒ k = ±1

12) For x>0: f' = e^x; x<0: f' = −e^{−x} = −e^{|x|}
At 0: left derivative −1; right derivative 1 ⇒ not differentiable at 0 (but continuous).

13) h is continuous on [0,1], differentiable on (0,1). Average slope = (ln 2 + e − 1)/1. h'(x) = 1/(1+x) + e^x. Solve 1/(1+c) + e^c = ln 2 + e − 1 for c∈(0,1) (exists by IVT).

14) y = sin^{-1}(x)·cos^{-1}(x). At x=0: sin^{-1}(0)=0, cos^{-1}(0)=π/2.
y' = (cos^{-1} x)·(1/√(1−x^2)) + sin^{-1} x · (−1/√(1−x^2))
At x=0: y' = (π/2)·1 + 0 = π/2

15) Kinks where arguments of |·| change sign: x=−1 and x=2 ⇒ not differentiable at x=−1, 2.

</details>

---

# 5) Common Pitfalls + Quick Tips

- ==Don’t== assume continuity implies differentiability (|x| at 0).
- For piecewise functions at c:
  - Step 1: Find LHL, RHL, f(c) for continuity.
  - Step 2: Find left and right derivatives for differentiability.
- For limits like (1 − cos kx)/x^2 near 0, use standard: ≈ (k^2/2).
- For “find constants a, b”:
  - Continuity gives equation 1.
  - Differentiability gives equation 2 (matching left and right derivatives).
- Inverse trig compositions often simplify using identities:
  - sin(2θ) = 2 tan θ / (1 + tan^2 θ)
  - tan^{-1}(2x/(1−x^2)) = 2 tan^{-1} x (|x|<1)
- Rolle/MVT: Always check the hypotheses first:
  - Continuity on [a,b], differentiability on (a,b), and f(a)=f(b) for Rolle.

> [!tip]
> In proofs: “If differentiable ⇒ continuous”:
> If f is differentiable at c, then
> f(c+h) − f(c) = h·[f(c+h) − f(c)]/h → 0 as h→0 ⇒ lim_{x→c} f(x) = f(c).

---

# 6) Mini Checklist (Exam Morning)

- [ ] I can test continuity at a point using LHL=RHL=f(c).
- [ ] I can test differentiability with left/right derivatives.
- [ ] I know standard limits and when to apply them.
- [ ] I’m confident with chain/implicit/parametric/log differentiation.
- [ ] I can handle |x|, ⌊x⌋, {x} near integers and kinks.
- [ ] I can verify Rolle’s/MVT conditions and find c.

---

# 7) Extra Practice (Short NCERT-style set)

Try these if you have time; brief answers posted.

1) Find k so that f is differentiable at 0:
f(x) =
- kx, x≥0
- x^2, x<0

2) Evaluate: d/dx [ x^x · e^{x^2} ]

3) Evaluate: d/dx [ sin^{-1}(x) + cos^{-1}(x) ]

4) Check continuity of f(x) = (x − ⌊x⌋) at x=3.

5) Verify MVT for f(x) = x^2 on [−1, 2] and find c.

Answers:
1) Continuity: k·0 = 0 ⇒ ok. Derivatives at 0: right=k, left=0 ⇒ k=0.
2) Product rule: x^x(ln x + 1)·e^{x^2} + x^x · e^{x^2}·2x = x^x e^{x^2}[(ln x + 1) + 2x]
3) Derivative = 1/√(1−x^2) − 1/√(1−x^2) = 0
4) Fractional part is continuous at non-integers; at integer 3, left limit 1−, right limit 0 ⇒ discontinuous.
5) Avg slope = (4 − 1)/(2 − (−1)) = 3/3 = 1; f'(x)=2x ⇒ 2c=1 ⇒ c=1/2.

---

# Want me to drill you with rapid-fire questions on any subtopic (continuity at a point, piecewise, inverse trig derivatives, or MVT)? I can generate a focused quiz with instant feedback.
```