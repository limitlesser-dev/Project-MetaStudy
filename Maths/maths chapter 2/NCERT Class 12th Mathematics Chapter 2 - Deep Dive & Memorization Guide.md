# 📚 NCERT Class 12th Mathematics: Chapter 2 - Deep Dive & Memorization Guide

## 🤔 Why Radians Instead of Degrees?

You've hit upon a very important point that bridges your foundational understanding to higher mathematics! While degrees are intuitive for visualizing angles in geometry, **radians become the preferred unit for angles in calculus and advanced mathematics for several powerful reasons:**

1.  **Calculus Simplification:**
    *   When you study calculus (differentiation and integration), formulas involving trigonometric functions are much simpler when angles are expressed in radians.
    *   For example, the derivative of $\sin x$ is $\cos x$, i.e., $\frac{d}{dx}(\sin x) = \cos x$. This elegant formula **only holds true if $x$ is in radians**.
    *   If $x$ were in degrees, the formula would be $\frac{d}{dx}(\sin x^\circ) = \frac{\pi}{180}\cos x^\circ$, introducing an extra, often cumbersome, constant factor.
    *   This applies to many other calculus formulas involving trigonometric functions, making radians the "natural" unit for these operations.

2.  **Unitless Nature:**
    *   A radian is defined as the ratio of arc length ($s$) to the radius ($r$) of a circle ($\theta = \frac{s}{r}$). Since both arc length and radius are lengths, their ratio is a pure number with no units.
    *   This dimensionless quality makes radians incredibly useful in physics and engineering, where equations often need to maintain dimensional consistency.

3.  **Connection to Real Numbers:**
    *   In a more advanced mathematical sense, angles measured in radians can be directly treated as real numbers, allowing for seamless integration with other functions of real numbers. This direct correspondence is less straightforward with degrees.

**In summary:** While degrees are good for everyday understanding and basic geometry, radians are the workhorse of higher mathematics because they simplify formulas, particularly in calculus, and integrate more naturally with the broader system of real numbers.

---

## 🧠 What to Memorize for Chapter 2? (Your Cheat Sheet!)

Here's a concise list of everything you should commit to memory for this chapter. Organize these in your Obsidian notes for quick reference!

### 1. **Fundamental Trigonometric Values (Essential Prerequisite!)**

You MUST know these values for basic angles in both degrees and radians. This is the bedrock.

| Angle ($\theta$) | $\sin \theta$ | $\cos \theta$ | $\tan \theta$ |
| :--------------- | :------------ | :------------ | :------------ |
| $0^\circ$ (0 rad) | 0             | 1             | 0             |
| $30^\circ$ ($\frac{\pi}{6}$ rad) | $\frac{1}{2}$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{3}}$ |
| $45^\circ$ ($\frac{\pi}{4}$ rad) | $\frac{1}{\sqrt{2}}$ | $\frac{1}{\sqrt{2}}$ | 1             |
| $60^\circ$ ($\frac{\pi}{3}$ rad) | $\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$ | $\sqrt{3}$ |
| $90^\circ$ ($\frac{\pi}{2}$ rad) | 1             | 0             | Undefined     |

*(Also know their reciprocals: $\csc \theta = \frac{1}{\sin \theta}$, $\sec \theta = \frac{1}{\cos \theta}$, $\cot \theta = \frac{1}{\tan \theta}$)*

### 2. **Domain and Range (Principal Value Branch) of Inverse Trigonometric Functions**

This is CRITICAL for finding principal values correctly.

| Inverse Function | Domain           | Range (Principal Value Branch) |
| :--------------- | :--------------- | :----------------------------- |
| $y = \sin^{-1} x$ | $[-1, 1]$        | $[-\frac{\pi}{2}, \frac{\pi}{2}]$   |
| $y = \cos^{-1} x$ | $[-1, 1]$        | $[0, \pi]$                     |
| $y = \tan^{-1} x$ | $\mathbb{R}$     | $(-\frac{\pi}{2}, \frac{\pi}{2})$   |
| $y = \csc^{-1} x$ | $(-\infty, -1] \cup [1, \infty)$ | $[-\frac{\pi}{2}, \frac{\pi}{2}] - \{0\}$ |
| $y = \sec^{-1} x$ | $(-\infty, -1] \cup [1, \infty)$ | $[0, \pi] - \{\frac{\pi}{2}\}$     |
| $y = \cot^{-1} x$ | $\mathbb{R}$     | $(0, \pi)$                     |

### 3. **Properties of Inverse Trigonometric Functions**

#### a) Inverse Identity Properties (with conditions!)

*   $\sin^{-1} (\sin x) = x$, if $x \in [-\frac{\pi}{2}, \frac{\pi}{2}]$
*   $\cos^{-1} (\cos x) = x$, if $x \in [0, \pi]$
*   $\tan^{-1} (\tan x) = x$, if $x \in (-\frac{\pi}{2}, \frac{\pi}{2})$
    *(Similarly for $\csc^{-1}, \sec^{-1}, \cot^{-1}$)*

*   $\sin (\sin^{-1} x) = x$, if $x \in [-1, 1]$
*   $\cos (\cos^{-1} x) = x$, if $x \in [-1, 1]$
*   $\tan (\tan^{-1} x) = x$, if $x \in \mathbb{R}$
    *(Similarly for $\csc, \sec, \cot$)*

#### b) Negative Arguments Properties

*   $\sin^{-1} (-x) = -\sin^{-1} x$
*   $\tan^{-1} (-x) = -\tan^{-1} x$
*   $\csc^{-1} (-x) = -\csc^{-1} x$
*   $\cos^{-1} (-x) = \pi - \cos^{-1} x$
*   $\sec^{-1} (-x) = \pi - \sec^{-1} x$
*   $\cot^{-1} (-x) = \pi - \cot^{-1} x$

#### c) Reciprocal Identities

*   $\sin^{-1} x = \csc^{-1} \left(\frac{1}{x}\right)$
*   $\cos^{-1} x = \sec^{-1} \left(\frac{1}{x}\right)$
*   $\tan^{-1} x = \cot^{-1} \left(\frac{1}{x}\right)$, for $x > 0$

#### d) Complementary Angle Properties

*   $\sin^{-1} x + \cos^{-1} x = \frac{\pi}{2}$
*   $\tan^{-1} x + \cot^{-1} x = \frac{\pi}{2}$
*   $\csc^{-1} x + \sec^{-1} x = \frac{\pi}{2}$

#### e) Sum/Difference & Double Angle Formulas (especially for $\tan^{-1}$)

*   $\tan^{-1} x + \tan^{-1} y = \tan^{-1} \left(\frac{x+y}{1-xy}\right)$, if $xy < 1$
*   $\tan^{-1} x - \tan^{-1} y = \tan^{-1} \left(\frac{x-y}{1+xy}\right)$, if $xy > -1$
*   $2\tan^{-1} x = \tan^{-1} \left(\frac{2x}{1-x^2}\right)$, if $|x| < 1$
*   $2\tan^{-1} x = \sin^{-1} \left(\frac{2x}{1+x^2}\right)$, if $|x| \le 1$
*   $2\tan^{-1} x = \cos^{-1} \left(\frac{1-x^2}{1+x^2}\right)$, if $x \ge 0$

### 4. **Key Trigonometric Identities for Proofs (Important!)**

These are not inverse function properties, but standard trig identities crucial for solving problems like Question 1 and 2 from Exercise 2.2.

*   $\sin 2\theta = 2\sin\theta\cos\theta$
*   $\cos 2\theta = \cos^2\theta - \sin^2\theta = 2\cos^2\theta - 1 = 1 - 2\sin^2\theta$
*   $\tan 2\theta = \frac{2\tan\theta}{1-\tan^2\theta}$
*   $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$
*   $\cos 3\theta = 4\cos^3\theta - 3\cos\theta$

---

## 💡 How to "Think" About Using $\sin 30^\circ$ or $\cos 30^\circ$ (or their radian equivalents)?

This comes down to two main scenarios:

### Scenario 1: Finding Principal Values (like in Exercise 2.1)

When you see something like $\sin^{-1}\left(\frac{1}{2}\right)$ or $\cos^{-1}\left(-\frac{\sqrt{3}}{2}\right)$, you need to find an angle.

**Your thought process should be:**

1.  **Identify the Function and Value:** "I have $\sin^{-1}$ of $\frac{1}{2}$."
2.  **Recall the Principal Value Range:** "The output angle for $\sin^{-1}$ must be between $-\frac{\pi}{2}$ and $\frac{\pi}{2}$ (or $-90^\circ$ and $90^\circ$)."
3.  **Basic Trig Knowledge (Your Memorized Table):** "Which angle, in my memorized table, has a sine of $\frac{1}{2}$?"
    *   *Aha!* $\sin(\frac{\pi}{6}) = \frac{1}{2}$ (or $\sin 30^\circ = \frac{1}{2}$).
4.  **Check the Range:** "Is $\frac{\pi}{6}$ (or $30^\circ$) within the principal value range $[-\frac{\pi}{2}, \frac{\pi}{2}]$?"
    *   *Yes, it is!* So, the answer is $\frac{\pi}{6}$.

**What if it's negative?** (e.g., $\sin^{-1}\left(-\frac{1}{2}\right)$)

1.  **Identify Function and Value:** "I have $\sin^{-1}$ of $-\frac{1}{2}$."
2.  **Recall Principal Value Range:** "The output angle for $\sin^{-1}$ must be between $-\frac{\pi}{2}$ and $\frac{\pi}{2}$."
3.  **Basic Trig Knowledge:** "Which angle has a sine of positive $\frac{1}{2}$? That's $\frac{\pi}{6}$."
4.  **Apply Negative Argument Property/Quadrant Knowledge:** "Since the input is negative, and $\sin^{-1}(-x) = -\sin^{-1}x$, then $\sin^{-1}\left(-\frac{1}{2}\right) = -\sin^{-1}\left(\frac{1}{2}\right) = -\frac{\pi}{6}$."
    *   Alternatively, you can think: "In which quadrant is sine negative, and the angle still falls within $[-\frac{\pi}{2}, \frac{\pi}{2}]$? That's the fourth quadrant. So, if $\sin(\frac{\pi}{6})=\frac{1}{2}$, then $\sin(-\frac{\pi}{6})=-\frac{1}{2}$."
5.  **Check the Range:** "Is $-\frac{\pi}{6}$ within $[-\frac{\pi}{2}, \frac{\pi}{2}]$?" *Yes!*

The trick is to first find the positive angle, then adjust for the negative sign using the properties or quadrant rules, and finally, verify it's within the required principal value branch.

### Scenario 2: Simplifying Expressions (like in Exercise 2.2)

When you see complex expressions, especially those you need to prove or simplify, you're looking for patterns that match the trigonometric identities you've memorized.

**Your thought process should be:**

1.  **Look for Algebraic Patterns:** "I see $3x - 4x^3$ inside an inverse sine function: $\sin^{-1}(3x - 4x^3)$."
2.  **Connect to Trigonometric Identities:** "Does $3x - 4x^3$ remind me of any sine or cosine identity?"
    *   *Bingo!* It looks exactly like $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$.
3.  **Make the Substitution:** "If I let $x = \sin\theta$, then $3x - 4x^3$ becomes $3\sin\theta - 4\sin^3\theta$, which simplifies to $\sin 3\theta$."
4.  **Substitute into the Inverse Function:** "So, $\sin^{-1}(3x - 4x^3)$ becomes $\sin^{-1}(\sin 3\theta)$."
5.  **Apply Inverse Property (with domain check):** "I know $\sin^{-1}(\sin A) = A$, *provided* $A$ is in $[-\frac{\pi}{2}, \frac{\pi}{2}]$. My $A$ is $3\theta$. I need to make sure $3\theta$ is in that range based on the given domain for $x$."
    *   If $x \in [-\frac{1}{2}, \frac{1}{2}]$, then $\sin\theta \in [-\frac{1}{2}, \frac{1}{2}]$. This means $\theta \in [-\frac{\pi}{6}, \frac{\pi}{6}]$.
    *   Therefore, $3\theta \in [-\frac{\pi}{2}, \frac{\pi}{2}]$. The condition is satisfied!
6.  **Final Simplification:** "So, $\sin^{-1}(\sin 3\theta) = 3\theta$. And since $\theta = \sin^{-1}x$, the expression simplifies to $3\sin^{-1}x$."

This systematic approach of recognizing patterns, making substitutions, using identities, and checking conditions will guide you through most problems in this chapter.

Keep practicing, and these connections will become second nature! You're doing great by asking these foundational questions. Good luck with your exam!