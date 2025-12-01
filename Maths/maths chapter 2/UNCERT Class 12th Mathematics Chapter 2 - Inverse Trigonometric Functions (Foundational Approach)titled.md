# 📚 NCERT Class 12th Mathematics: Chapter 2 - Inverse Trigonometric Functions (Foundational Approach)

## 🙏 Greetings, My Dear Student!

I understand this is your very first chapter in mathematics, and that's perfectly fine! We're going to build your understanding from the ground up. Inverse Trigonometric Functions might seem daunting at first, but with a solid grasp of the basics, you'll find them quite logical and manageable.

Let's begin our journey!

---

## 🎯 A Quick Look Back: What is Trigonometry?

Before we talk about *Inverse* Trigonometric Functions, let's briefly recall what **Trigonometry** is all about.

Trigonometry is the study of relationships between the sides and angles of triangles. Specifically, it deals with **right-angled triangles**.

You might remember the **six basic trigonometric ratios** (or functions):

*   **Sine (sin)**
*   **Cosine (cos)**
*   **Tangent (tan)**
*   **Cosecant (csc)** - reciprocal of sin
*   **Secant (sec)** - reciprocal of cos
*   **Cotangent (cot)** - reciprocal of tan

These ratios relate an angle in a right-angled triangle to the lengths of its sides. For example, for an angle $\theta$:

*   $\sin \theta = \frac{\text{Opposite Side}}{\text{Hypotenuse}}$
*   $\cos \theta = \frac{\text{Adjacent Side}}{\text{Hypotenuse}}$
*   $\tan \theta = \frac{\text{Opposite Side}}{\text{Adjacent Side}}$

### What is an Angle? (A Quick Reminder)

Angles can be measured in **degrees** ($^\circ$) or **radians**. In higher mathematics, **radians** are predominantly used because they simplify many formulas.

*   A full circle is $360^\circ$ or $2\pi$ radians.
*   $180^\circ = \pi$ radians
*   $90^\circ = \frac{\pi}{2}$ radians
*   $30^\circ = \frac{\pi}{6}$ radians
*   $45^\circ = \frac{\pi}{4}$ radians
*   $60^\circ = \frac{\pi}{3}$ radians

---

## 💡 Chapter Overview: Inverse Trigonometric Functions

Now, imagine you know the *ratio* (the value of sin, cos, or tan), but you want to find the *angle* that produced that ratio. That's precisely what **Inverse Trigonometric Functions** do!

They are the "undoing" or "reverse" operations of the basic trigonometric functions.

*   If $\sin \theta = x$, then $\theta = \sin^{-1} x$ (read as "sine inverse of x" or "arcsin x")
*   If $\cos \theta = x$, then $\theta = \cos^{-1} x$ (read as "cosine inverse of x" or "arccos x")
*   If $\tan \theta = x$, then $\theta = \tan^{-1} x$ (read as "tangent inverse of x" or "arctan x")

**Important Note:** The $"-1"$ here is *not* an exponent meaning $\frac{1}{\sin x}$. It's a special notation for the inverse function.

### The Challenge: Uniqueness

A crucial concept in mathematics is that for a function to have a unique inverse, it must pass the **horizontal line test** (meaning it maps each input to a unique output, and each output comes from a unique input).

Our standard trigonometric functions (like $\sin x$) are **periodic**, meaning their values repeat. For example, $\sin 0 = 0$, $\sin \pi = 0$, $\sin 2\pi = 0$, and so on. If we ask "what angle has a sine of 0?", there are infinitely many answers!

To get a *unique* answer for inverse trigonometric functions, we have to **restrict the domain** of the original trigonometric functions. This restricted domain is called the **Principal Value Branch**. This ensures that for every valid input, there's only one specific output angle that our inverse function will give.

---

## 💡 Concept 1: Definitions, Domain, Range, and Principal Value Branches

Let's look at the domains (what values of $x$ are allowed) and ranges (what angles $y$ the inverse function will give back) for each inverse trigonometric function. The range is particularly important as it represents the **Principal Value Branch**.

| Inverse Trigonometric Function | Domain (Allowed $x$ values) | Range (Principal Value Branch - Output Angle $y$) |
| :----------------------------- | :-------------------------- | :------------------------------------------------ |
| $y = \sin^{-1} x$              | $[-1, 1]$                   | $[-\frac{\pi}{2}, \frac{\pi}{2}]$ (or $[-90^\circ, 90^\circ]$) |
| $y = \cos^{-1} x$              | $[-1, 1]$                   | $[0, \pi]$ (or $[0^\circ, 180^\circ]$)        |
| $y = \tan^{-1} x$              | $(-\infty, \infty)$ or $\mathbb{R}$ | $(-\frac{\pi}{2}, \frac{\pi}{2})$ (or $(-90^\circ, 90^\circ]$) |
| $y = \csc^{-1} x$              | $(-\infty, -1] \cup [1, \infty)$ | $[-\frac{\pi}{2}, \frac{\pi}{2}] - \{0\}$         |
| $y = \sec^{-1} x$              | $(-\infty, -1] \cup [1, \infty)$ | $[0, \pi] - \{\frac{\pi}{2}\}$                  |
| $y = \cot^{-1} x$              | $(-\infty, \infty)$ or $\mathbb{R}$ | $(0, \pi)$                                        |

**Key Takeaway:** When you are asked to find the "principal value" of an inverse trigonometric function, you must find the angle that falls within its specific "Range (Principal Value Branch)".

---

### 📝 Exercise 2.1 - Practice Finding Principal Values

Let's use some questions from Exercise 2.1 to understand how to find these principal values. [4]

#### **Question 1: Find the principal value of $\sin^{-1} \left(-\frac{1}{2}\right)$**

**Thinking Process:**
1.  **What are we looking for?** An angle, let's call it $y$, such that $\sin y = -\frac{1}{2}$.
2.  **Where should this angle be?** The principal value branch for $\sin^{-1} x$ is $[-\frac{\pi}{2}, \frac{\pi}{2}]$ (or $[-90^\circ, 90^\circ]$).
3.  **Basic $\sin$ value:** We know that $\sin \left(\frac{\pi}{6}\right) = \frac{1}{2}$ (or $\sin 30^\circ = \frac{1}{2}$).
4.  **Handling the negative:** Since $\sin y$ is negative, and we need an angle in $[-\frac{\pi}{2}, \frac{\pi}{2}]$, we recall that $\sin(-A) = -\sin A$.
5.  So, if $\sin \left(\frac{\pi}{6}\right) = \frac{1}{2}$, then $\sin \left(-\frac{\pi}{6}\right) = -\frac{1}{2}$.
6.  **Check the range:** Is $-\frac{\pi}{6}$ (or $-30^\circ$) within $[-\frac{\pi}{2}, \frac{\pi}{2}]$? Yes, it is!

**Solution:**
Let $y = \sin^{-1} \left(-\frac{1}{2}\right)$.
This means $\sin y = -\frac{1}{2}$.
We know that the range of the principal value branch for $\sin^{-1}$ is $[-\frac{\pi}{2}, \frac{\pi}{2}]$.
We also know that $\sin \left(\frac{\pi}{6}\right) = \frac{1}{2}$.
Since $\sin(-A) = -\sin A$, we can write $\sin y = -\sin \left(\frac{\pi}{6}\right) = \sin \left(-\frac{\pi}{6}\right)$.
As $-\frac{\pi}{6}$ lies in the interval $[-\frac{\pi}{2}, \frac{\pi}{2}]$, it is the principal value.
Therefore, the principal value of $\sin^{-1} \left(-\frac{1}{2}\right)$ is $\boxed{-\frac{\pi}{6}}$.

---

#### **Question 2: Find the principal value of $\cos^{-1} \left(\frac{\sqrt{3}}{2}\right)$**

**Thinking Process:**
1.  **What are we looking for?** An angle, $y$, such that $\cos y = \frac{\sqrt{3}}{2}$.
2.  **Where should this angle be?** The principal value branch for $\cos^{-1} x$ is $[0, \pi]$ (or $[0^\circ, 180^\circ]$).
3.  **Basic $\cos$ value:** We know that $\cos \left(\frac{\pi}{6}\right) = \frac{\sqrt{3}}{2}$ (or $\cos 30^\circ = \frac{\sqrt{3}}{2}$).
4.  **Check the range:** Is $\frac{\pi}{6}$ (or $30^\circ$) within $[0, \pi]$? Yes, it is!

**Solution:**
Let $y = \cos^{-1} \left(\frac{\sqrt{3}}{2}\right)$.
This means $\cos y = \frac{\sqrt{3}}{2}$.
We know that the range of the principal value branch for $\cos^{-1}$ is $[0, \pi]$.
We also know that $\cos \left(\frac{\pi}{6}\right) = \frac{\sqrt{3}}{2}$.
Since $\frac{\pi}{6}$ lies in the interval $[0, \pi]$, it is the principal value.
Therefore, the principal value of $\cos^{-1} \left(\frac{\sqrt{3}}{2}\right)$ is $\boxed{\frac{\pi}{6}}$.

---

#### **Question 3: Find the principal value of $\tan^{-1} (-\sqrt{3})$**

**Thinking Process:**
1.  **What are we looking for?** An angle, $y$, such that $\tan y = -\sqrt{3}$.
2.  **Where should this angle be?** The principal value branch for $\tan^{-1} x$ is $(-\frac{\pi}{2}, \frac{\pi}{2})$ (or $(-90^\circ, 90^\circ]$). Notice the open brackets, meaning $-\frac{\pi}{2}$ and $\frac{\pi}{2}$ are not included.
3.  **Basic $\tan$ value:** We know that $\tan \left(\frac{\pi}{3}\right) = \sqrt{3}$ (or $\tan 60^\circ = \sqrt{3}$).
4.  **Handling the negative:** Since $\tan y$ is negative, and we need an angle in $(-\frac{\pi}{2}, \frac{\pi}{2})$, we recall that $\tan(-A) = -\tan A$.
5.  So, if $\tan \left(\frac{\pi}{3}\right) = \sqrt{3}$, then $\tan \left(-\frac{\pi}{3}\right) = -\sqrt{3}$.
6.  **Check the range:** Is $-\frac{\pi}{3}$ (or $-60^\circ$) within $(-\frac{\pi}{2}, \frac{\pi}{2})$? Yes, it is!

**Solution:**
Let $y = \tan^{-1} (-\sqrt{3})$.
This means $\tan y = -\sqrt{3}$.
We know that the range of the principal value branch for $\tan^{-1}$ is $(-\frac{\pi}{2}, \frac{\pi}{2})$.
We also know that $\tan \left(\frac{\pi}{3}\right) = \sqrt{3}$.
Since $\tan(-A) = -\tan A$, we can write $\tan y = -\tan \left(\frac{\pi}{3}\right) = \tan \left(-\frac{\pi}{3}\right)$.
As $-\frac{\pi}{3}$ lies in the interval $(-\frac{\pi}{2}, \frac{\pi}{2})$, it is the principal value.
Therefore, the principal value of $\tan^{-1} (-\sqrt{3})$ is $\boxed{-\frac{\pi}{3}}$.

---

## 💡 Concept 2: Properties of Inverse Trigonometric Functions

These properties are like shortcuts or rules that help us simplify expressions and solve more complex problems involving inverse trigonometric functions. It's important to understand and memorize them!

### Property Set 1: Inverse Identity Properties

These show how an inverse function "undoes" its corresponding trigonometric function (and vice versa), but *only* within their specific principal value ranges.

1.  $\sin^{-1} (\sin x) = x$, **if $x$ is in the range $[-\frac{\pi}{2}, \frac{\pi}{2}]$**
2.  $\cos^{-1} (\cos x) = x$, **if $x$ is in the range $[0, \pi]$**
3.  $\tan^{-1} (\tan x) = x$, **if $x$ is in the range $(-\frac{\pi}{2}, \frac{\pi}{2})$**
    (Similar properties exist for $\csc^{-1}$, $\sec^{-1}$, $\cot^{-1}$)

And for the other way around:
1.  $\sin (\sin^{-1} x) = x$, **if $x$ is in the domain $[-1, 1]$**
2.  $\cos (\cos^{-1} x) = x$, **if $x$ is in the domain $[-1, 1]$**
3.  $\tan (\tan^{-1} x) = x$, **if $x$ is in the domain $\mathbb{R}$ (all real numbers)**
    (Similar properties exist for $\csc^{-1}$, $\sec^{-1}$, $\cot^{-1}$)

### Property Set 2: Negative Arguments (How to handle negative inputs)

1.  $\sin^{-1} (-x) = -\sin^{-1} x$, for $x \in [-1, 1]$
2.  $\tan^{-1} (-x) = -\tan^{-1} x$, for $x \in \mathbb{R}$
3.  $\csc^{-1} (-x) = -\csc^{-1} x$, for $|x| \ge 1$
4.  $\cos^{-1} (-x) = \pi - \cos^{-1} x$, for $x \in [-1, 1]$
5.  $\sec^{-1} (-x) = \pi - \sec^{-1} x$, for $|x| \ge 1$
6.  $\cot^{-1} (-x) = \pi - \cot^{-1} x$, for $x \in \mathbb{R}$

*Notice how $\cos^{-1}$, $\sec^{-1}$, and $\cot^{-1}$ behave differently with negative inputs compared to $\sin^{-1}$, $\tan^{-1}$, $\csc^{-1}$. This is related to their principal value branches.*

### Property Set 3: Reciprocal Identities (Converting between functions)

1.  $\sin^{-1} x = \csc^{-1} \left(\frac{1}{x}\right)$, if $x \in (0, 1]$ or $[-1, 0)$
2.  $\cos^{-1} x = \sec^{-1} \left(\frac{1}{x}\right)$, if $x \in (0, 1]$ or $[-1, 0)$
3.  $\tan^{-1} x = \cot^{-1} \left(\frac{1}{x}\right)$, if $x > 0$
    *(For $x < 0$, it's slightly more complex, but for typical problems, the $x>0$ case is most common. You can usually convert between $\tan^{-1}$ and $\cot^{-1}$ by using triangles if needed.)*

### Property Set 4: Complementary Angle Properties (Sums that equal $\frac{\pi}{2}$)

1.  $\sin^{-1} x + \cos^{-1} x = \frac{\pi}{2}$, if $x \in [-1, 1]$
2.  $\tan^{-1} x + \cot^{-1} x = \frac{\pi}{2}$, if $x \in \mathbb{R}$
3.  $\csc^{-1} x + \sec^{-1} x = \frac{\pi}{2}$, if $|x| \ge 1$

### Property Set 5: Sum/Difference Formulas (For combining $\tan^{-1}$ terms)

These are very useful for simplifying expressions.

1.  $\tan^{-1} x + \tan^{-1} y = \tan^{-1} \left(\frac{x+y}{1-xy}\right)$, if $xy < 1$
2.  $\tan^{-1} x - \tan^{-1} y = \tan^{-1} \left(\frac{x-y}{1+xy}\right)$, if $xy > -1$
3.  $2\tan^{-1} x = \tan^{-1} \left(\frac{2x}{1-x^2}\right)$, if $|x| < 1$
4.  $2\tan^{-1} x = \sin^{-1} \left(\frac{2x}{1+x^2}\right)$, if $|x| \le 1$
5.  $2\tan^{-1} x = \cos^{-1} \left(\frac{1-x^2}{1+x^2}\right)$, if $x \ge 0$

---

### 📝 Exercise 2.2 - Using Properties to Solve Problems

Let's look at some problems that require applying these properties. These might seem more complex, but we'll break them down. [4]

#### **Question 1: Prove $3 \sin^{-1} x = \sin^{-1} (3x - 4x^3)$, for $x \in [-\frac{1}{2}, \frac{1}{2}]$**

**Thinking Process:**
This problem looks like it's related to a familiar trigonometric identity for $\sin(3\theta)$.
1.  **Strategy:** When you see expressions like $3x - 4x^3$, immediately think of $\sin 3\theta$ or $\cos 3\theta$. Here, $3x - 4x^3$ resembles $3\sin\theta - 4\sin^3\theta$.
2.  **Substitution:** Let $x = \sin \theta$. This means $\theta = \sin^{-1} x$.
3.  **Check Domain:** The given domain for $x$ is $[-\frac{1}{2}, \frac{1}{2}]$. If $x = \sin \theta$, then for this range of $x$, $\theta$ must be in $[-\frac{\pi}{6}, \frac{\pi}{6}]$. (Because $\sin(-\frac{\pi}{6}) = -\frac{1}{2}$ and $\sin(\frac{\pi}{6}) = \frac{1}{2}$).
4.  **Simplify RHS:** Substitute $x = \sin\theta$ into the Right Hand Side (RHS) of the equation.
5.  **Use identity:** Use the identity $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$.
6.  **Apply inverse property:** Use the property $\sin^{-1}(\sin A) = A$, but *only if A is in the correct range*. Here, $A = 3\theta$. We need to ensure $3\theta$ is in $[-\frac{\pi}{2}, \frac{\pi}{2}]$. Since $\theta \in [-\frac{\pi}{6}, \frac{\pi}{6}]$, then $3\theta \in [-3 \times \frac{\pi}{6}, 3 \times \frac{\pi}{6}] = [-\frac{\pi}{2}, \frac{\pi}{2}]$. This condition is met!
7.  **Substitute back:** Replace $\theta$ with $\sin^{-1} x$.

**Solution:**
Let $x = \sin \theta$.
Then, from the definition of inverse sine, $\theta = \sin^{-1} x$.
The given domain for $x$ is $[-\frac{1}{2}, \frac{1}{2}]$.
This implies that $\theta$ lies in the interval $[-\frac{\pi}{6}, \frac{\pi}{6}]$, because $\sin(-\frac{\pi}{6}) = -\frac{1}{2}$ and $\sin(\frac{\pi}{6}) = \frac{1}{2}$.

Now, let's work with the Right Hand Side (RHS):
RHS = $\sin^{-1} (3x - 4x^3)$
Substitute $x = \sin \theta$:
RHS = $\sin^{-1} (3\sin \theta - 4\sin^3 \theta)$

We recall the trigonometric identity: $\sin 3\theta = 3\sin \theta - 4\sin^3 \theta$.
So, RHS = $\sin^{-1} (\sin 3\theta)$

Since $\theta \in [-\frac{\pi}{6}, \frac{\pi}{6}]$, multiplying by 3 gives us $3\theta \in [-\frac{3\pi}{6}, \frac{3\pi}{6}]$, which simplifies to $3\theta \in [-\frac{\pi}{2}, \frac{\pi}{2}]$.
This is exactly the principal value branch for $\sin^{-1} x$.
Therefore, we can apply the property $\sin^{-1}(\sin A) = A$:
RHS = $3\theta$

Now, substitute back $\theta = \sin^{-1} x$:
RHS = $3\sin^{-1} x$
This is the Left Hand Side (LHS).
Hence, $3 \sin^{-1} x = \sin^{-1} (3x - 4x^3)$ is proved.

---

#### **Question 2: Prove $3 \cos^{-1} x = \cos^{-1} (4x^3 - 3x)$, for $x \in [\frac{1}{2}, 1]$**

**Thinking Process:**
This is very similar to the previous question, but now it resembles the $\cos 3\theta$ identity.
1.  **Strategy:** See $4x^3 - 3x$, think of $\cos 3\theta$.
2.  **Substitution:** Let $x = \cos \theta$. Then $\theta = \cos^{-1} x$.
3.  **Check Domain:** For $x \in [\frac{1}{2}, 1]$, what is $\theta$? We know $\cos(\frac{\pi}{3}) = \frac{1}{2}$ and $\cos(0) = 1$. The principal branch of $\cos^{-1} x$ is $[0, \pi]$. So, if $x \in [\frac{1}{2}, 1]$, then $\theta \in [0, \frac{\pi}{3}]$.
4.  **Simplify RHS:** Substitute $x = \cos\theta$.
5.  **Use identity:** Use $\cos 3\theta = 4\cos^3 \theta - 3\cos \theta$.
6.  **Apply inverse property:** Ensure $3\theta$ is in $[0, \pi]$. Since $\theta \in [0, \frac{\pi}{3}]$, then $3\theta \in [0, \pi]$. Condition met!
7.  **Substitute back:** Replace $\theta$ with $\cos^{-1} x$.

**Solution:**
Let $x = \cos \theta$.
Then, $\theta = \cos^{-1} x$.
The given domain for $x$ is $[\frac{1}{2}, 1]$.
This implies that $\theta$ lies in the interval $[0, \frac{\pi}{3}]$, because $\cos(\frac{\pi}{3}) = \frac{1}{2}$ and $\cos(0) = 1$, and the principal value branch for $\cos^{-1}$ is $[0, \pi]$.

Now, consider the Right Hand Side (RHS):
RHS = $\cos^{-1} (4x^3 - 3x)$
Substitute $x = \cos \theta$:
RHS = $\cos^{-1} (4\cos^3 \theta - 3\cos \theta)$

We recall the trigonometric identity: $\cos 3\theta = 4\cos^3 \theta - 3\cos \theta$.
So, RHS = $\cos^{-1} (\cos 3\theta)$

Since $\theta \in [0, \frac{\pi}{3}]$, multiplying by 3 gives us $3\theta \in [0, \pi]$.
This is the principal value branch for $\cos^{-1} x$.
Therefore, we can apply the property $\cos^{-1}(\cos A) = A$:
RHS = $3\theta$

Now, substitute back $\theta = \cos^{-1} x$:
RHS = $3\cos^{-1} x$
This is the Left Hand Side (LHS).
Hence, $3 \cos^{-1} x = \cos^{-1} (4x^3 - 3x)$ is proved.

---

#### **Question 3: Write $\tan^{-1} \left(\frac{2x}{1-x^2}\right)$ in the simplest form, assuming $|x|<1$.**

**Thinking Process:**
This expression should immediately remind you of one of the $2\tan^{-1} x$ formulas (from Property Set 5).

**Solution:**
We recognize this expression as a direct application of one of the **$2\tan^{-1} x$ properties**.
Specifically, we know that:
$2\tan^{-1} x = \tan^{-1} \left(\frac{2x}{1-x^2}\right)$, provided that $|x| < 1$.

The problem states $|x| < 1$, so the condition is met.
Therefore, the simplest form of $\tan^{-1} \left(\frac{2x}{1-x^2}\right)$ is $\boxed{2\tan^{-1} x}$.

---

#### **Question 4: Evaluate $\tan^{-1} \frac{1}{2} + \tan^{-1} \frac{2}{11}$**

**Thinking Process:**
This is a sum of two $\tan^{-1}$ terms, so we'll use the $\tan^{-1} x + \tan^{-1} y$ formula (from Property Set 5).
1.  **Identify $x$ and $y$**: Here, $x = \frac{1}{2}$ and $y = \frac{2}{11}$.
2.  **Check condition**: The formula requires $xy < 1$. Let's check: $\frac{1}{2} \times \frac{2}{11} = \frac{2}{22} = \frac{1}{11}$. Since $\frac{1}{11} < 1$, the condition is satisfied.
3.  **Apply formula**: Substitute $x$ and $y$ into the formula.
4.  **Simplify**: Perform the arithmetic inside the $\tan^{-1}$.

**Solution:**
We use the property for the sum of two inverse tangents:
$\tan^{-1} x + \tan^{-1} y = \tan^{-1} \left(\frac{x+y}{1-xy}\right)$, provided that $xy < 1$.

Here, $x = \frac{1}{2}$ and $y = \frac{2}{11}$.
First, check the condition $xy < 1$:
$xy = \left(\frac{1}{2}\right) \times \left(\frac{2}{11}\right) = \frac{2}{22} = \frac{1}{11}$.
Since $\frac{1}{11} < 1$, the property applies.

Now, substitute the values into the formula:
$\tan^{-1} \frac{1}{2} + \tan^{-1} \frac{2}{11} = \tan^{-1} \left(\frac{\frac{1}{2} + \frac{2}{11}}{1 - \frac{1}{2} \times \frac{2}{11}}\right)$

Let's simplify the numerator:
$\frac{1}{2} + \frac{2}{11} = \frac{1 \times 11}{2 \times 11} + \frac{2 \times 2}{11 \times 2} = \frac{11}{22} + \frac{4}{22} = \frac{11+4}{22} = \frac{15}{22}$

Now simplify the denominator:
$1 - \frac{1}{2} \times \frac{2}{11} = 1 - \frac{2}{22} = 1 - \frac{1}{11} = \frac{11}{11} - \frac{1}{11} = \frac{11-1}{11} = \frac{10}{11}$

Substitute these back into the $\tan^{-1}$ expression:
$= \tan^{-1} \left(\frac{\frac{15}{22}}{\frac{10}{11}}\right)$

To divide fractions, we multiply by the reciprocal of the denominator:
$= \tan^{-1} \left(\frac{15}{22} \times \frac{11}{10}\right)$
$= \tan^{-1} \left(\frac{15 \times 11}{22 \times 10}\right)$
We can simplify by canceling common factors: $11$ divides $22$ twice, and $5$ divides $15$ thrice and $10$ twice.
$= \tan^{-1} \left(\frac{3 \times 1}{2 \times 2}\right)$
$= \tan^{-1} \left(\frac{3}{4}\right)$

Therefore, $\tan^{-1} \frac{1}{2} + \tan^{-1} \frac{2}{11} = \boxed{\tan^{-1} \frac{3}{4}}$.

---

## 🚀 Study Tips for Tomorrow's Exam:

Since this is your first chapter in maths, a strong foundation is key!

1.  **Master the Basics of Trigonometry:** Ensure you're comfortable with $\sin, \cos, \tan$ for common angles ($0, 30^\circ, 45^\circ, 60^\circ, 90^\circ$ and their radian equivalents). If you're shaky, quickly review a basic trigonometry table or chart.
2.  **Understand Principal Value Branches:** This is the most common area where students make mistakes. Always ensure your final answer for an inverse function (the angle) falls within its correct principal value branch.
3.  **Memorize All Properties:** The properties are your toolkit for solving problems. Write them down, say them aloud, and use flashcards if it helps.
4.  **Practice, Practice, Practice:** Work through *all* the examples and exercises from your NCERT textbook. Don't skip any! Start with Exercise 2.1, then move to 2.2, and definitely tackle the Miscellaneous Exercise.
5.  **Pay Attention to Domain and Range:** These are not just theoretical; they are critical for correctly applying properties and finding valid solutions, especially with the "inverse identity properties" where conditions like $x \in [-\frac{\pi}{2}, \frac{\pi}{2}]$ are vital.
6.  **Don't Fear the Proofs:** Questions that ask you to "prove" something (like Questions 1 and 2 in Exercise 2.2) are excellent for understanding how the properties work. They often involve a clever substitution.

You've got this! Start with understanding, then move to memorization, and finally, practice. Stay calm, read the questions carefully, and apply what we've learned.

Good luck with your exam tomorrow! I'm confident you'll do great!