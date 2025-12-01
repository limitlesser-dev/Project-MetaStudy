This response provides a comprehensive copy book detailing the foundational concepts, definitions, essential formulas, and problem-solving strategies for NCERT Class 12th Mathematics, Chapter 2 (Inverse Trigonometric Functions), drawing exclusively from the provided sources.

---

## 📚 NCERT Class 12th Mathematics: Chapter 2 - Inverse Trigonometric Functions

### Part 1: Foundational Prerequisites

#### 1. Why Radians?

Radians are the preferred unit for angles in calculus and advanced mathematics. This is because using radians **simplifies calculus formulas**; for instance, the derivative of $\sin x$ is $\cos x$, but this elegant formula only holds if $x$ is in radians. If $x$ were in degrees, the derivative would introduce a cumbersome constant factor, $\pi/180$. Furthermore, a radian is defined as a ratio of arc length to radius ($\theta = s/r$), making it a **unitless** or dimensionless quantity, which is useful in physics and engineering. Angles measured in radians can also be **directly treated as real numbers**.

#### 2. Conversions and Fundamental Values

The absolute core prerequisite is comfort with basic trigonometry, including conversions and standard values.

|Angle ($\theta$)|Degrees|Radians|$\sin \theta$|$\cos \theta$|$\tan \theta$|
|:-:|:-:|:-:|:-:|:-:|:-:|
||$0^{\circ}$|$0$|$0$|$1$|$0$|
||$30^{\circ}$|$\pi/6$|$1/2$|$\sqrt{3}/2$|$1/\sqrt{3}$|
||$45^{\circ}$|$\pi/4$|$1/\sqrt{2}$|$1/\sqrt{2}$|$1$|
||$60^{\circ}$|$\pi/3$|$\sqrt{3}/2$|$1/2$|$\sqrt{3}$|
||$90^{\circ}$|$\pi/2$|$1$|$0$|Undefined|

(Note: The reciprocals, $\csc \theta = 1/\sin \theta$, $\sec \theta = 1/\cos \theta$, and $\cot \theta = 1/\tan \theta$, must also be known).

### Part 2: Core Concepts of Inverse Functions

#### 1. Definition and Principal Value Branch (PVB)

- **Inverse Function Definition:** If $\sin y = x$, then $y = \sin^{-1} x$. This means **$y$ is the angle whose sine is $x$**.
- **Existence:** The inverse of a function $f$ (denoted $f^{-1}$) exists only if $f$ is **one-one and onto** (bijective).
- **Restriction:** Trigonometric functions are periodic and thus not one-to-one over their entire domain. To define a unique inverse, the domain of the original function must be restricted.
- **PVB:** The range of the inverse function is this restricted domain, which is called the **Principal Value Branch**. When no branch is mentioned, the principal value branch is assumed.

#### 2. Domain and Range (Principal Value Branch)

This table is **CRITICAL** for finding principal values correctly.

|Inverse Function|Domain (Allowed $x$ values)|Range (Principal Value Branch - Output Angle $y$)|Group|
|:-:|:-:|:-:|:-:|
|$y = \sin^{-1} x$|$[-1, 1]$|$[-\pi/2, \pi/2]$|Q4/Q1|
|$y = \cos^{-1} x$|$[-1, 1]$|$[0, \pi]$|Q1/Q2|
|$y = \tan^{-1} x$|$R$|$(-\pi/2, \pi/2)$|Q4/Q1|
|$y = \csc^{-1} x$|$(-\infty, -1] \cup [1, \infty)$|$[-\pi/2, \pi/2] - {0}$|Q4/Q1|
|$y = \sec^{-1} x$|$(-\infty, -1] \cup [1, \infty)$|$[0, \pi] - {\pi/2}$|Q1/Q2|
|$y = \cot^{-1} x$|$R$|$(0, \pi)$|Q1/Q2|

**Note:** $\sin^{-1} x$ should not be confused with $(\sin x)^{-1}$, which equals $1/\sin x$.

### Part 3: Properties of Inverse Trigonometric Functions

#### a) Inverse Identity Properties (The "Undo" Properties)

These properties require that the input value or angle falls within specified ranges/domains.

- **Trig(Inv($x$)) = $x$:** This holds if the input value $x$ is in the **domain** of the inverse function.
    - $\sin(\sin^{-1} x) = x$, if $x \in [-1, 1]$.
    - $\cos(\cos^{-1} x) = x$, if $x \in [-1, 1]$.
    - $\tan(\tan^{-1} x) = x$, if $x \in R$.
- **Inv(Trig($x$)) = $x$:** This holds if the input angle $x$ is in the **range (PVB)** of the inverse function.
    - $\sin^{-1}(\sin x) = x$, if $x \in [-\pi/2, \pi/2]$.
    - $\cos^{-1}(\cos x) = x$, if $x \in [0, \pi]$.
    - $\tan^{-1}(\tan x) = x$, if $x \in (-\pi/2, \pi/2)$.

#### b) Negative Arguments Properties

These define how to handle negative inputs based on the PVB range.

| Group 1 (Q4/Q1 range; Odd Functions) |  Group 2 (Q1/Q2 range; uses $\pi$)  |
| :----------------------------------: | :---------------------------------: |
|    $\sin^{-1}(-x) = -\sin^{-1} x$    | $\cos^{-1}(-x) = \pi - \cos^{-1} x$ |
|    $\tan^{-1}(-x) = -\tan^{-1} x$    | $\sec^{-1}(-x) = \pi - \sec^{-1} x$ |
|    $\csc^{-1}(-x) = -\csc^{-1} x$    | $\cot^{-1}(-x) = \pi - \cot^{-1} x$ |
|                                      |                                     |

#### c) Reciprocal Identities

- $\sin^{-1} x = \csc^{-1} (1/x)$
- $\cos^{-1} x = \sec^{-1} (1/x)$
- $\tan^{-1} x = \cot^{-1} (1/x)$, for $x > 0$

#### d) Complementary Angle Properties (Sums to $\pi/2$)

These apply only for suitable values of $x$ in the domain:

- $\sin^{-1} x + \cos^{-1} x = \pi/2$
- $\tan^{-1} x + \cot^{-1} x = \pi/2$
- $\csc^{-1} x + \sec^{-1} x = \pi/2$

#### e) Sum/Difference & Double Angle Formulas (especially for $\tan^{-1}$)

- **Sum/Difference:**
    - $\tan^{-1} x + \tan^{-1} y = \tan^{-1} \left( \frac{x+y}{1-xy} \right)$, if $xy < 1$.
    - $\tan^{-1} x - \tan^{-1} y = \tan^{-1} \left( \frac{x-y}{1+xy} \right)$, if $xy > -1$.
- **Double Angle (2 $\tan^{-1} x$ formulas):** These are particularly versatile. They link to the double angle formulas of $\sin 2\theta$, $\cos 2\theta$, and $\tan 2\theta$ when expressed in terms of $\tan \theta$.
    - $2 \tan^{-1} x = \tan^{-1} \left( \frac{2x}{1-x^2} \right)$, if $|x| < 1$.
    - $2 \tan^{-1} x = \sin^{-1} \left( \frac{2x}{1+x^2} \right)$, if $|x| \leq 1$.
    - $2 \tan^{-1} x = \cos^{-1} \left( \frac{1-x^2}{1+x^2} \right)$, if $x \geq 0$.

### Part 4: Essential Trigonometric Identities for Proofs

These standard identities are crucial for solving problems involving simplification and proofs (like those in Exercise 2.2).

|Identity Type|Formula|Memorization Tip/Usage|
|:-:|:-:|:-:|
|**Pythagorean**|$\sin^2 \theta + \cos^2 \theta = 1$|Relates sine and cosine.|
|**Half-Angle Manipulations**|$1 - \cos \theta = 2 \sin^2 (\theta/2)$|"1 minus cosine means 2 sine squared (half angle)". Used to simplify $\sqrt{(1-\cos x)/(1+\cos x)}$.|
||$1 + \cos \theta = 2 \cos^2 (\theta/2)$|"1 plus cosine means 2 cosine squared (half angle)".|
|**Double Angle (General)**|$\sin 2\theta = 2 \sin \theta \cos \theta$||
||$\cos 2\theta = \cos^2 \theta - \sin^2 \theta$|Also $= 2 \cos^2 \theta - 1$ and $= 1 - 2 \sin^2 \theta$.|
|**Double Angle (in terms of $\tan \theta$)**|$\sin 2\theta = \frac{2 \tan \theta}{1+\tan^2 \theta}$|Used with $2 \tan^{-1} x = \sin^{-1} (\dots)$.|
||$\cos 2\theta = \frac{1-\tan^2 \theta}{1+\tan^2 \theta}$|Used with $2 \tan^{-1} x = \cos^{-1} (\dots)$.|
||$\tan 2\theta = \frac{2 \tan \theta}{1-\tan^2 \theta}$|Used with $2 \tan^{-1} x = \tan^{-1} (\dots)$.|
|**Triple Angle (CRITICAL)**|$\sin 3\theta = 3 \sin \theta - 4 \sin^3 \theta$|**"34 pattern."** Crucial for proving $3 \sin^{-1} x$ formulas.|
||$\cos 3\theta = 4 \cos^3 \theta - 3 \cos \theta$|**"43 pattern."** Crucial for proving $3 \cos^{-1} x$ formulas.|

### Part 5: How to Approach Problems

#### Scenario 1: Finding Principal Values (PV)

1. **Identify the Function and Value:** For example, given $\sin^{-1}(1/2)$ or $\cos^{-1}(-\sqrt{3}/2)$.
2. **Recall the PVB Range:** Know the restricted range for the function (e.g., $\sin^{-1}$ must be in $[-\pi/2, \pi/2]$).
3. **Basic Trig Knowledge (Ignore Negative for now):** Find the angle ($\theta$) whose positive value matches the input (using your memorized table).
4. **Apply Negative Argument Property (if needed):**
    - For **Group 1 ($\sin^{-1}, \tan^{-1}, \csc^{-1}$):** Use $-\theta$. _Example:_ $\sin^{-1}(-1/2) = -\sin^{-1}(1/2) = -\pi/6$.
    - For **Group 2 ($\cos^{-1}, \sec^{-1}, \cot^{-1}$):** Use $\pi - \theta$. _Example:_ $\cos^{-1}(-1/2) = \pi - \cos^{-1}(1/2) = \pi - \pi/3 = 2\pi/3$.
5. **Verify the Range:** Ensure the final angle is within the specified PVB.

#### Scenario 2: Simplifying Expressions and Proofs

The systematic approach involves recognizing patterns, substituting, applying identities, and checking conditions.

1. **Look for Algebraic Patterns:** Scan the expression inside the inverse function for structures like $3x - 4x^3$, $2x/(1-x^2)$, or $\sqrt{1-x^2}$.
2. **Connect to Trigonometric Identities:**
    - If you see $3x - 4x^3$, think $\sin 3\theta$, suggesting the substitution $x = \sin \theta$.
    - If you see $4x^3 - 3x$, think $\cos 3\theta$, suggesting $x = \cos \theta$.
    - If you see $2x/(1-x^2)$, think $\tan 2\theta$, suggesting $x = \tan \theta$.
3. **Make the Substitution:** Replace $x$ with the appropriate trigonometric function of $\theta$ (e.g., $x = \sin \theta$, which implies $\theta = \sin^{-1} x$).
4. **Simplify:** Use the trigonometric identity to simplify the expression inside the inverse function (e.g., $3x - 4x^3 \rightarrow 3 \sin \theta - 4 \sin^3 \theta \rightarrow \sin 3\theta$).
5. **Apply Inverse Property (with Domain Check):** Apply $\sin^{-1}(\sin A) = A$, but you **must** verify that the angle $A$ (in this case, $3\theta$) falls within the PVB of the outer inverse function (e.g., $[-\pi/2, \pi/2]$ for $\sin^{-1}$). The domain given for $x$ in the problem (e.g., $x \in [-1/2, 1/2]$) must be used to prove that the resulting angle is valid.
6. **Substitute Back:** Replace $\theta$ with its inverse form in $x$ (e.g., $3\theta \rightarrow 3 \sin^{-1} x$).

### Part 6: General Memorization Strategies

To master this chapter, the properties must be memorized and understood deeply. Effective strategies include:

- **Active Recall:** Test yourself by covering up definitions and trying to write them from memory, perhaps using flashcards for individual properties.
- **Spaced Repetition:** Review the material multiple times over increasing intervals (e.g., 1 hour, 1 day, 3 days, 1 week).
- **Practice Problems:** The absolute best way to memorize properties is to use them by working through every example and exercise.
- **Identify Connections:** Understand _why_ the properties are structured as they are (e.g., how $2 \tan^{-1} x$ relates to double angle formulas) to reduce rote memorization.
- **Visualize:** Draw graphs or the Cartesian plane (for the ASTC rule) to visualize domains and ranges.
- **Teaching/Explaining:** Explain concepts out loud to someone else (or an imaginary student) to organize thoughts and identify gaps.
- **Summary Sheet Creation:** Create your own concise summary sheet from memory after studying the detailed guides.
- **Don't Fear the Proofs:** Proofs demonstrate how properties are derived and build a deeper understanding. For example, the triple angle formulas can be understood by knowing their derivation from $\sin(2\theta + \theta)$.