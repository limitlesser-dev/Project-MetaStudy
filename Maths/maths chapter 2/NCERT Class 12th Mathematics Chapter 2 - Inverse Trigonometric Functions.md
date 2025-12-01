# 📚 NCERT Class 12th Mathematics: Chapter 2 - Inverse Trigonometric Functions
## 🧠 Your Ultimate Memorization Sheet & Explanations!

This sheet is designed not just to list what you need to know, but to help you understand *why* it's important and *how* to effectively memorize it. Break this down into smaller chunks, and don't try to cram it all at once!

---

## Part 1: Pre-requisite Foundation (Must be rock solid!)

Before inverse functions, you *must* be comfortable with basic trigonometry. If this part feels shaky, review your Class 10/11 notes!

### 1.1 Conversions: Degrees vs. Radians

*   **The Big Conversion:** $\pi \text{ radians} = 180^\circ$
*   **Key Conversions to Memorize (because they appear constantly):**
    *   $0^\circ = 0 \text{ rad}$
    *   $30^\circ = \frac{\pi}{6} \text{ rad}$
    *   $45^\circ = \frac{\pi}{4} \text{ rad}$
    *   $60^\circ = \frac{\pi}{3} \text{ rad}$
    *   $90^\circ = \frac{\pi}{2} \text{ rad}$
    *   $180^\circ = \pi \text{ rad}$
    *   $270^\circ = \frac{3\pi}{2} \text{ rad}$
    *   $360^\circ = 2\pi \text{ rad}$

*   **Memorization Tip:** Notice the pattern for $\pi/6, \pi/4, \pi/3$. As the denominator gets smaller, the angle gets larger (since $\pi$ is divided into fewer parts).

### 1.2 Fundamental Trigonometric Values (for standard angles)

This is the ABSOLUTE core. Make a table, draw it repeatedly, use flashcards, sing a song – whatever it takes!

| Angle   | 0°  | 30°  | 45°  | 60°  | 90° |
| ------- | --- | ---- | ---- | ---- | --- |
| Radians | 0   | π/6  | π/4  | π/3  | π/2 |
| sin θ   | 0   | 1/2  | 1/√2 | √3/2 | 1   |
| cos θ   | 1   | √3/2 | 1/√2 | 1/2  | 0   |
| tan θ   | 0   | 1/√3 | 1    | √3   | ∞   |
| cot θ   | ∞   | √3   | 1    | 1/√3 | 0   |
| cosec θ | ∞   | 2    | √2   | 2/√3 | 1   |
| sec θ   | 1   | 2/√3 | √2   | 2    | ∞   |

*   **Memorization Tip:**
* 
    *   **Sine (0 to 1):** Starts at 0, increases to 1 at $90^\circ$. Values are $\frac{\sqrt{0}}{2}, \frac{\sqrt{1}}{2}, \frac{\sqrt{2}}{2}, \frac{\sqrt{3}}{2}, \frac{\sqrt{4}}{2}$ (which simplify to the table values).
    *   **Cosine (1 to 0):** Is the reverse of sine. Starts at 1, decreases to 0 at $90^\circ$.
    *   **Tangent ($\tan \theta = \frac{\sin \theta}{\cos \theta}$):** Calculate it from sine and cosine.
    *   **The other three:** $\csc \theta = \frac{1}{\sin \theta}$, $\sec \theta = \frac{1}{\cos \theta}$, $\cot \theta = \frac{1}{\tan \theta}$. If you know sin, cos, tan, you know these too!

### 1.3 Quadrant Rules and Signs of Trigonometric Functions

Crucial for understanding why principal values are chosen and how negative inputs work.

*   **"All Students Take Coffee" (ASTC) Rule:**
    *   **A**ll are positive in Quadrant I ($0 \text{ to } \frac{\pi}{2}$)
    *   **S**ine (and Cosecant) are positive in Quadrant II ($\frac{\pi}{2} \text{ to } \pi$)
    *   **T**angent (and Cotangent) are positive in Quadrant III ($\pi \text{ to } \frac{3\pi}{2}$)
    *   **C**osine (and Secant) are positive in Quadrant IV ($\frac{3\pi}{2} \text{ to } 2\pi$)

*   **Memorization Tip:** Draw the Cartesian plane and label the quadrants with ASTC. Practice finding the sign of, say, $\sin(2\pi/3)$ (Q2, so positive).

---

## Part 2: Inverse Trigonometric Functions - The Core Chapter Content

### 2.1 Understanding Inverse Functions (The "What Does it Mean?")

*   **Definition:** If $\sin y = x$, then $y = \sin^{-1} x$. This means $y$ is the angle whose sine is $x$.
    *   *Example:* If $\sin 30^\circ = \frac{1}{2}$, then $\sin^{-1}\left(\frac{1}{2}\right) = 30^\circ$ (or $\frac{\pi}{6}$ radians).
*   **Key Concept: The Principal Value Branch:** Because trigonometric functions are periodic (their values repeat), they are not "one-to-one" over their entire domain. To define a unique inverse, we restrict the domain of the original trig function. The *range* of the inverse function is this restricted domain, and it's called the Principal Value Branch. You *must* ensure your answers fall within these ranges.

### 2.2 Domain and Range (Principal Value Branch) of Inverse Trigonometric Functions

This is **THE MOST IMPORTANT TABLE** to memorize for finding principal values.

| Inverse Function  | Domain (Allowed $x$ values)      | Range (Principal Value Branch - Output Angle $y$) | Why this range?                                                                                                                      |
| :---------------- | :------------------------------- | :------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------- |
| $y = \sin^{-1} x$ | $[-1, 1]$                        | $[-\frac{\pi}{2}, \frac{\pi}{2}]$ (Q4 & Q1)       | Contains all unique sine values from -1 to 1. Extends from negative $90^\circ$ to positive $90^\circ$.                               |
| $y = \cos^{-1} x$ | $[-1, 1]$                        | $[0, \pi]$ (Q1 & Q2)                              | Contains all unique cosine values from -1 to 1. Extends from $0^\circ$ to $180^\circ$.                                               |
| $y = \tan^{-1} x$ | $\mathbb{R}$                     | $(-\frac{\pi}{2}, \frac{\pi}{2})$ (Q4 & Q1)       | Contains all unique tangent values from $-\infty$ to $\infty$. Excludes the endpoints because $\tan(\pm\frac{\pi}{2})$ is undefined. |
| $y = \csc^{-1} x$ | $(-\infty, -1] \cup [1, \infty)$ | $[-\frac{\pi}{2}, \frac{\pi}{2}] - \{0\}$         | Same as $\sin^{-1} x$ but excludes 0 because $\csc 0$ is undefined.                                                                  |
| $y = \sec^{-1} x$ | $(-\infty, -1] \cup [1, \infty)$ | $[0, \pi] - \{\frac{\pi}{2}\}$                    | Same as $\cos^{-1} x$ but excludes $\frac{\pi}{2}$ because $\sec(\frac{\pi}{2})$ is undefined.                                       |
| $y = \cot^{-1} x$ | $\mathbb{R}$                     | $(0, \pi)$                                        | Similar to $\cos^{-1} x$ but excludes endpoints because $\cot(0)$ and $\cot(\pi)$ are undefined.                                     |

*   **Memorization Tip:**
    *   **Group 1 (Q4/Q1):** $\sin^{-1}x$, $\tan^{-1}x$, $\csc^{-1}x$ all have ranges centered around 0, going from negative to positive. ($\sin^{-1}$ and $\tan^{-1}$ are odd functions).
    *   **Group 2 (Q1/Q2):** $\cos^{-1}x$, $\cot^{-1}x$, $\sec^{-1}x$ all have ranges starting from 0, going up to $\pi$. (They relate to $\pi - \cos^{-1}x$ for negative values).
    *   Remember the exclusions: `0` for $\csc^{-1}$, `pi/2` for $\sec^{-1}$, `0` and `pi` for $\cot^{-1}$ (where the original functions are undefined).
    *   The domain is determined by the range of the original trigonometric function (e.g., sine goes from -1 to 1, so $\sin^{-1}$'s input $x$ must be in $[-1, 1]$).

### 2.3 Properties of Inverse Trigonometric Functions

These are your problem-solving tools. Understand each one.

#### a) Inverse Identity Properties (The "Undo" Properties)

*   **Explanation:** These functions "undo" each other, but only if the input angle `x` (for $\sin^{-1}(\sin x)$) or value `x` (for $\sin(\sin^{-1} x)$) is within the specified valid range/domain. **The conditions are vital!**

    1.  $\sin^{-1} (\sin x) = x$, **if $x \in [-\frac{\pi}{2}, \frac{\pi}{2}]$**
    2.  $\cos^{-1} (\cos x) = x$, **if $x \in [0, \pi]$**
    3.  $\tan^{-1} (\tan x) = x$, **if $x \in (-\frac{\pi}{2}, \frac{\pi}{2})$**
        *(Similarly for $\csc^{-1}, \sec^{-1}, \cot^{-1}$ with their respective ranges)*

    4.  $\sin (\sin^{-1} x) = x$, **if $x \in [-1, 1]$**
    5.  $\cos (\cos^{-1} x) = x$, **if $x \in [-1, 1]$**
    6.  $\tan (\tan^{-1} x) = x$, **if $x \in \mathbb{R}$**
        *(Similarly for $\csc, \sec, \cot$ with their respective domains)*

*   **Memorization Tip:** The condition for $\text{Inv}(\text{Trig}(x))=x$ is the *range of the inverse function*. The condition for $\text{Trig}(\text{Inv}(x))=x$ is the *domain of the inverse function*.

#### b) Negative Argument Properties (How to handle negative inputs efficiently)

*   **Explanation:** These tell you how to deal with negative values inside the inverse functions. Notice the two groups.

    **Group 1 (Odd Functions - Just pull out the negative):**
    1.  $\sin^{-1} (-x) = -\sin^{-1} x$, for $x \in [-1, 1]$
    2.  $\tan^{-1} (-x) = -\tan^{-1} x$, for $x \in \mathbb{R}$
    3.  $\csc^{-1} (-x) = -\csc^{-1} x$, for $|x| \ge 1$

    **Group 2 (Uses $\pi$ because their principal range is $[0, \pi]$):**
    4.  $\cos^{-1} (-x) = \pi - \cos^{-1} x$, for $x \in [-1, 1]$
    5.  $\sec^{-1} (-x) = \pi - \sec^{-1} x$, for $|x| \ge 1$
    6.  $\cot^{-1} (-x) = \pi - \cot^{-1} x$, for $x \in \mathbb{R}$

*   **Memorization Tip:** Functions whose principal value branches include negative angles ($\sin^{-1}$, $\tan^{-1}$, $\csc^{-1}$) simply pull out the negative sign. Functions whose principal value branches are entirely non-negative ($\cos^{-1}$, $\sec^{-1}$, $\cot^{-1}$) use the $\pi - \dots$ form.

#### c) Reciprocal Identities (Converting between reciprocal functions)

*   **Explanation:** These help you switch between an inverse function and its reciprocal's inverse.

    1.  $\sin^{-1} x = \csc^{-1} \left(\frac{1}{x}\right)$, if $x \in (0, 1]$ or $[-1, 0)$
    2.  $\cos^{-1} x = \sec^{-1} \left(\frac{1}{x}\right)$, if $x \in (0, 1]$ or $[-1, 0)$
    3.  $\tan^{-1} x = \cot^{-1} \left(\frac{1}{x}\right)$, if $x > 0$
        *(For $x < 0$, $\tan^{-1} x = \cot^{-1} (\frac{1}{x}) - \pi$)*

*   **Memorization Tip:** The "$\frac{1}{x}$" is intuitive. Be mindful of the conditions, especially for $\tan^{-1}/\cot^{-1}$ when $x$ is negative. For most basic problems, $x>0$ is assumed.

#### d) Complementary Angle Properties (Sums to $\frac{\pi}{2}$)

*   **Explanation:** These are analogous to complementary angles in basic trigonometry ($\sin(90^\circ - \theta) = \cos \theta$).

    1.  $\sin^{-1} x + \cos^{-1} x = \frac{\pi}{2}$, if $x \in [-1, 1]$
    2.  $\tan^{-1} x + \cot^{-1} x = \frac{\pi}{2}$, if $x \in \mathbb{R}$
    3.  $\csc^{-1} x + \sec^{-1} x = \frac{\pi}{2}$, if $|x| \ge 1$

*   **Memorization Tip:** Just remember the pairs: (sin, cos), (tan, cot), (csc, sec) sum to $\pi/2$.

#### e) Sum/Difference & Double Angle Formulas (Especially for $\tan^{-1}$)

*   **Explanation:** These are some of the most frequently used formulas for simplifying and solving equations. The $2\tan^{-1}x$ formulas are particularly versatile.

    1.  $\tan^{-1} x + \tan^{-1} y = \tan^{-1} \left(\frac{x+y}{1-xy}\right)$, if $xy < 1$
    2.  $\tan^{-1} x - \tan^{-1} y = \tan^{-1} \left(\frac{x-y}{1+xy}\right)$, if $xy > -1$
    3.  $2\tan^{-1} x = \tan^{-1} \left(\frac{2x}{1-x^2}\right)$, if $|x| < 1$
    4.  $2\tan^{-1} x = \sin^{-1} \left(\frac{2x}{1+x^2}\right)$, if $|x| \le 1$
    5.  $2\tan^{-1} x = \cos^{-1} \left(\frac{1-x^2}{1+x^2}\right)$, if $x \ge 0$

*   **Memorization Tip:**
    *   Notice the similarity of $\tan^{-1} x + \tan^{-1} y$ to the $\tan(A+B)$ formula: $\tan(A+B) = \frac{\tan A + \tan B}{1 - \tan A \tan B}$. Just replace $\tan A$ with $x$, $\tan B$ with $y$, and put $\tan^{-1}$ around the whole expression.
    *   The $2\tan^{-1}x$ formulas are linked to the double angle formulas for $\tan 2\theta$, $\sin 2\theta$, and $\cos 2\theta$ when expressed in terms of $\tan\theta$. (e.g., $\sin 2\theta = \frac{2\tan\theta}{1+\tan^2\theta}$). If you let $x = \tan\theta$, these pop out. Understanding this connection makes memorization easier.

---

## Part 3: Essential Trigonometric Identities for Proofs/Simplification

These are from your previous classes but are indispensable for Chapter 2 problems (like the ones with $3x - 4x^3$).

1.  $\sin^2 \theta + \cos^2 \theta = 1$
2.  $1 + \tan^2 \theta = \sec^2 \theta$
3.  $1 + \cot^2 \theta = \csc^2 \theta$
4.  $\sin 2\theta = 2\sin\theta\cos\theta$
5.  $\cos 2\theta = \cos^2\theta - \sin^2\theta = 2\cos^2\theta - 1 = 1 - 2\sin^2\theta$
6.  $\tan 2\theta = \frac{2\tan\theta}{1-\tan^2\theta}$
7.  **Critical for this chapter:**
    *   $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$
    *   $\cos 3\theta = 4\cos^3\theta - 3\cos\theta$
    *   $\tan 3\theta = \frac{3\tan\theta - \tan^3\theta}{1-3\tan^2\theta}$

*   **Memorization Tip:** The $3\theta$ formulas are less intuitive. Write them down repeatedly. For $\sin 3\theta$, think "3 sine, 4 sine cubed" (34 pattern). For $\cos 3\theta$, think "4 cosine cubed, 3 cosine" (43 pattern).

---

## Part 4: How to Approach Problems and "Think" Which Value to Use

### 1. **Finding Principal Values (e.g., $\sin^{-1}(-\frac{1}{2})$)**

*   **Step 1: Understand the Goal.** You're finding an *angle*.
*   **Step 2: Ignore the negative (for a moment).** "What angle has a sine of $\frac{1}{2}$?" (From your memorized table: $\frac{\pi}{6}$ or $30^\circ$).
*   **Step 3: Check the Principal Value Range for the specific function.** For $\sin^{-1}$, it's $[-\frac{\pi}{2}, \frac{\pi}{2}]$.
*   **Step 4: Apply the Negative Argument Property (if needed).**
    *   For $\sin^{-1}$, $\tan^{-1}$, $\csc^{-1}$: If input is negative, just put a negative sign in front of the angle you found in Step 2.
        *   Example: $\sin^{-1}(-\frac{1}{2}) = -\sin^{-1}(\frac{1}{2}) = -\frac{\pi}{6}$. Check: $-\frac{\pi}{6}$ is in $[-\frac{\pi}{2}, \frac{\pi}{2}]$. Correct!
    *   For $\cos^{-1}$, $\sec^{-1}$, $\cot^{-1}$: If input is negative, use the $\pi - (\text{angle from Step 2})$ rule.
        *   Example: $\cos^{-1}(-\frac{1}{2})$. Angle for $+\frac{1}{2}$ is $\frac{\pi}{3}$. So, $\cos^{-1}(-\frac{1}{2}) = \pi - \cos^{-1}(\frac{1}{2}) = \pi - \frac{\pi}{3} = \frac{2\pi}{3}$. Check: $\frac{2\pi}{3}$ is in $[0, \pi]$. Correct!
*   **Step 5: ALWAYS Verify.** Does your final angle fall within the specified Principal Value Branch for that inverse function?

### 2. **Simplifying Expressions / Proofs (e.g., $3 \sin^{-1} x = \sin^{-1} (3x - 4x^3)$)**

*   **Step 1: Look at the algebraic structure inside the inverse function.** Do you see patterns like $2x/(1-x^2)$, $3x-4x^3$, $4x^3-3x$?
*   **Step 2: Connect to the (non-inverse) trigonometric identities.**
    *   If you see $3x-4x^3$, think $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$. This suggests a substitution $x = \sin\theta$.
    *   If you see $4x^3-3x$, think $\cos 3\theta = 4\cos^3\theta - 3\cos\theta$. This suggests $x = \cos\theta$.
    *   If you see $2x/(1-x^2)$, think $\tan 2\theta = 2\tan\theta / (1-\tan^2\theta)$. This suggests $x = \tan\theta$.
    *   If you see $\sqrt{1-x^2}$ or similar radicals, think of Pythagorean identities, which might suggest $x=\sin\theta$ or $x=\cos\theta$ (e.g., $\sqrt{1-\sin^2\theta} = \cos\theta$).
*   **Step 3: Make the substitution.** Let $x$ equal the appropriate trig function of $\theta$. This means $\theta$ will be an inverse trig function of $x$.
*   **Step 4: Simplify the expression using trigonometric identities.**
*   **Step 5: Apply the Inverse Identity Property (e.g., $\sin^{-1}(\sin A) = A$).** **Crucially, check the condition for this property to be valid.** This usually involves ensuring the angle ($A$) is within the principal value branch for the outer inverse function. The problem statement will often provide a domain for $x$ that ensures this.
*   **Step 6: Substitute back.** Replace $\theta$ with its inverse trig function equivalent in terms of $x$.

---

## 🚀 General Memorization Strategies:

1.  **Active Recall:** Don't just re-read. Test yourself. Cover up definitions/properties and try to write them from memory. Use flashcards for individual properties.
2.  **Spaced Repetition:** Review the material multiple times over increasing intervals (e.g., after 1 hour, then 1 day, then 3 days, then a week).
3.  **Practice Problems:** The absolute best way to memorize properties is to *use them*. Work through every example and exercise in your NCERT textbook. When you get stuck, look at the property, then try again.
4.  **Teach Someone Else (or yourself!):** Explaining a concept out loud to an imaginary student (or a real one!) forces you to organize your thoughts and identify gaps in your understanding.
5.  **Visualize:** Draw graphs (even rough sketches) of the inverse functions to see their domains and ranges. Visualize the ASTC rule.
6.  **Create a "Summary" Sheet:** After you've studied this detailed one, try to create your own, more concise summary sheet from memory. This acts as a powerful review tool.
7.  **Identify Connections:** Understand *why* properties are what they are (e.g., how $2\tan^{-1}x$ relates to double angle formulas). This reduces pure rote memorization.
8.  **Don't Fear the Proofs:** Proofs are fantastic for showing how properties are derived and used. They build deeper understanding.

You have a clear path now. Take it one step at a time. You are fully capable of mastering this! Good luck with your exam!