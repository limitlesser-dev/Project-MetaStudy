This chapter on Inverse Trigonometric Functions covers the definitions, domains, and ranges of the six inverse trigonometric functions, focusing on their principal value branches. It also discusses their graphical representations and introduces some fundamental properties. To complete the chapter, here are the solutions to the exercises and miscellaneous problems presented.

---

### Exercise 2.1

**1. Find the principal value of sin⁻¹(1/√2)**
Let $y = \sin^{-1}\left(\frac{1}{\sqrt{2}}\right)$.
Then $\sin y = \frac{1}{\sqrt{2}}$.
We know that the range of the principal value branch of $\sin^{-1}x$ is $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.
Since $\sin\left(\frac{\pi}{4}\right) = \frac{1}{\sqrt{2}}$ and $\frac{\pi}{4} \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$, the principal value of $\sin^{-1}\left(\frac{1}{\sqrt{2}}\right)$ is $\frac{\pi}{4}$.

**2. Find the principal value of cos⁻¹(√3/2)**
Let $y = \cos^{-1}\left(\frac{\sqrt{3}}{2}\right)$.
Then $\cos y = \frac{\sqrt{3}}{2}$.
We know that the range of the principal value branch of $\cos^{-1}x$ is $[0, \pi]$.
Since $\cos\left(\frac{\pi}{6}\right) = \frac{\sqrt{3}}{2}$ and $\frac{\pi}{6} \in [0, \pi]$, the principal value of $\cos^{-1}\left(\frac{\sqrt{3}}{2}\right)$ is $\frac{\pi}{6}$.

**3. Find the principal value of cosec⁻¹(2)**
Let $y = \text{cosec}^{-1}(2)$.
Then $\text{cosec } y = 2$.
We know that the range of the principal value branch of $\text{cosec}^{-1}x$ is $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right] - \{0\}$.
Since $\text{cosec}\left(\frac{\pi}{6}\right) = 2$ and $\frac{\pi}{6} \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] - \{0\}$, the principal value of $\text{cosec}^{-1}(2)$ is $\frac{\pi}{6}$.

**4. Find the principal value of tan⁻¹(-√3)**
Let $y = \tan^{-1}(-\sqrt{3})$.
Then $\tan y = -\sqrt{3}$.
We know that the range of the principal value branch of $\tan^{-1}x$ is $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$.
Since $\tan\left(-\frac{\pi}{3}\right) = -\sqrt{3}$ and $-\frac{\pi}{3} \in \left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$, the principal value of $\tan^{-1}(-\sqrt{3})$ is $-\frac{\pi}{3}$.

**5. Find the principal value of cos⁻¹(-1/2)**
Let $y = \cos^{-1}\left(-\frac{1}{2}\right)$.
Then $\cos y = -\frac{1}{2}$.
We know that the range of the principal value branch of $\cos^{-1}x$ is $[0, \pi]$.
Since $\cos\left(\frac{2\pi}{3}\right) = \cos\left(\pi - \frac{\pi}{3}\right) = -\cos\left(\frac{\pi}{3}\right) = -\frac{1}{2}$ and $\frac{2\pi}{3} \in [0, \pi]$, the principal value of $\cos^{-1}\left(-\frac{1}{2}\right)$ is $\frac{2\pi}{3}$.

**6. Find the principal value of tan⁻¹(-1)**
Let $y = \tan^{-1}(-1)$.
Then $\tan y = -1$.
We know that the range of the principal value branch of $\tan^{-1}x$ is $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$.
Since $\tan\left(-\frac{\pi}{4}\right) = -1$ and $-\frac{\pi}{4} \in \left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$, the principal value of $\tan^{-1}(-1)$ is $-\frac{\pi}{4}$.

---

### Exercise 2.2

**Prove the following:**

**1. $3\sin^{-1}x = \sin^{-1}(3x - 4x^3)$, $x \in \left[-\frac{1}{2}, \frac{1}{2}\right]$**
Let $x = \sin\theta$. Then $\theta = \sin^{-1}x$.
Since $x \in \left[-\frac{1}{2}, \frac{1}{2}\right]$, we have $\theta \in \left[-\frac{\pi}{6}, \frac{\pi}{6}\right]$.
Therefore, $3\theta \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.
RHS = $\sin^{-1}(3\sin\theta - 4\sin^3\theta)$
We know that $\sin(3\theta) = 3\sin\theta - 4\sin^3\theta$.
So, RHS = $\sin^{-1}(\sin(3\theta))$
Since $3\theta \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$, we have $\sin^{-1}(\sin(3\theta)) = 3\theta$.
RHS = $3\theta = 3\sin^{-1}x$ = LHS.
Hence, $3\sin^{-1}x = \sin^{-1}(3x - 4x^3)$ is proved.

**2. $3\cos^{-1}x = \cos^{-1}(4x^3 - 3x)$, $x \in \left[\frac{1}{2}, 1\right]$**
Let $x = \cos\theta$. Then $\theta = \cos^{-1}x$.
Since $x \in \left[\frac{1}{2}, 1\right]$, we have $\theta \in \left[0, \frac{\pi}{3}\right]$.
Therefore, $3\theta \in [0, \pi]$.
RHS = $\cos^{-1}(4\cos^3\theta - 3\cos\theta)$
We know that $\cos(3\theta) = 4\cos^3\theta - 3\cos\theta$.
So, RHS = $\cos^{-1}(\cos(3\theta))$
Since $3\theta \in [0, \pi]$, we have $\cos^{-1}(\cos(3\theta)) = 3\theta$.
RHS = $3\theta = 3\cos^{-1}x$ = LHS.
Hence, $3\cos^{-1}x = \cos^{-1}(4x^3 - 3x)$ is proved.

**Write the following functions in the simplest form:**

**3. $\tan^{-1}\left(\frac{\sqrt{1+x^2}-1}{x}\right)$, $x \neq 0$**
Let $x = \tan\theta$. Then $\theta = \tan^{-1}x$.
$\tan^{-1}\left(\frac{\sqrt{1+\tan^2\theta}-1}{\tan\theta}\right)$
$= \tan^{-1}\left(\frac{\sqrt{\sec^2\theta}-1}{\tan\theta}\right)$
$= \tan^{-1}\left(\frac{|\sec\theta|-1}{\tan\theta}\right)$
Assuming $\theta \in (-\pi/2, \pi/2)$ for the principal value, $\sec\theta > 0$, so $|\sec\theta| = \sec\theta$.
$= \tan^{-1}\left(\frac{\sec\theta-1}{\tan\theta}\right)$
$= \tan^{-1}\left(\frac{\frac{1}{\cos\theta}-1}{\frac{\sin\theta}{\cos\theta}}\right)$
$= \tan^{-1}\left(\frac{1-\cos\theta}{\sin\theta}\right)$
Using the identities $1-\cos\theta = 2\sin^2\left(\frac{\theta}{2}\right)$ and $\sin\theta = 2\sin\left(\frac{\theta}{2}\right)\cos\left(\frac{\theta}{2}\right)$.
$= \tan^{-1}\left(\frac{2\sin^2\left(\frac{\theta}{2}\right)}{2\sin\left(\frac{\theta}{2}\right)\cos\left(\frac{\theta}{2}\right)}\right)$
$= \tan^{-1}\left(\tan\left(\frac{\theta}{2}\right)\right)$
$= \frac{\theta}{2}$
Substitute back $\theta = \tan^{-1}x$.
So, the simplest form is $\frac{1}{2}\tan^{-1}x$.

**4. $\tan^{-1}\left(\sqrt{\frac{1-\cos x}{1+\cos x}}\right)$, $0 < x < \pi$**
We know that $1-\cos x = 2\sin^2\left(\frac{x}{2}\right)$ and $1+\cos x = 2\cos^2\left(\frac{x}{2}\right)$.
$\tan^{-1}\left(\sqrt{\frac{2\sin^2\left(\frac{x}{2}\right)}{2\cos^2\left(\frac{x}{2}\right)}}\right)$
$= \tan^{-1}\left(\sqrt{\tan^2\left(\frac{x}{2}\right)}\right)$
$= \tan^{-1}\left(\left|\tan\left(\frac{x}{2}\right)\right|\right)$
Since $0 < x < \pi$, we have $0 < \frac{x}{2} < \frac{\pi}{2}$. In this interval, $\tan\left(\frac{x}{2}\right) > 0$.
$= \tan^{-1}\left(\tan\left(\frac{x}{2}\right)\right)$
$= \frac{x}{2}$
So, the simplest form is $\frac{x}{2}$.

**5. $\tan^{-1}\left(\frac{\cos x - \sin x}{\cos x + \sin x}\right)$, $-\frac{\pi}{4} < x < \frac{3\pi}{4}$**
Divide the numerator and denominator by $\cos x$.
$\tan^{-1}\left(\frac{\frac{\cos x}{\cos x} - \frac{\sin x}{\cos x}}{\frac{\cos x}{\cos x} + \frac{\sin x}{\cos x}}\right)$
$= \tan^{-1}\left(\frac{1 - \tan x}{1 + \tan x}\right)$
We know that $\tan\left(\frac{\pi}{4}\right) = 1$.
$= \tan^{-1}\left(\frac{\tan\left(\frac{\pi}{4}\right) - \tan x}{1 + \tan\left(\frac{\pi}{4}\right)\tan x}\right)$
This is the formula for $\tan(A-B) = \frac{\tan A - \tan B}{1 + \tan A \tan B}$.
$= \tan^{-1}\left(\tan\left(\frac{\pi}{4} - x\right)\right)$
Since $-\frac{\pi}{4} < x < \frac{3\pi}{4}$, we have $-\frac{3\pi}{4} < -x < \frac{\pi}{4}$.
Adding $\frac{\pi}{4}$ to the inequality:
$-\frac{3\pi}{4} + \frac{\pi}{4} < \frac{\pi}{4} - x < \frac{\pi}{4} + \frac{\pi}{4}$
$-\frac{\pi}{2} < \frac{\pi}{4} - x < \frac{\pi}{2}$.
Since $\left(\frac{\pi}{4} - x\right)$ lies within the principal value branch of $\tan^{-1}x$,
$= \frac{\pi}{4} - x$.
So, the simplest form is $\frac{\pi}{4} - x$.

**6. $\tan^{-1}\left(\frac{x}{\sqrt{a^2-x^2}}\right)$, $|x| < a$**
Let $x = a\sin\theta$. Then $\sin\theta = \frac{x}{a}$, and $\theta = \sin^{-1}\left(\frac{x}{a}\right)$.
Since $|x| < a$, we have $-a < x < a$, which means $-1 < \frac{x}{a} < 1$.
So, $-\frac{\pi}{2} < \theta < \frac{\pi}{2}$.
$\tan^{-1}\left(\frac{a\sin\theta}{\sqrt{a^2 - (a\sin\theta)^2}}\right)$
$= \tan^{-1}\left(\frac{a\sin\theta}{\sqrt{a^2 - a^2\sin^2\theta}}\right)$
$= \tan^{-1}\left(\frac{a\sin\theta}{\sqrt{a^2(1-\sin^2\theta)}}\right)$
$= \tan^{-1}\left(\frac{a\sin\theta}{\sqrt{a^2\cos^2\theta}}\right)$
$= \tan^{-1}\left(\frac{a\sin\theta}{|a\cos\theta|}\right)$
Assuming $a > 0$. Since $-\frac{\pi}{2} < \theta < \frac{\pi}{2}$, $\cos\theta > 0$, so $|a\cos\theta| = a\cos\theta$.
$= \tan^{-1}\left(\frac{a\sin\theta}{a\cos\theta}\right)$
$= \tan^{-1}(\tan\theta)$
$= \theta$
Substitute back $\theta = \sin^{-1}\left(\frac{x}{a}\right)$.
So, the simplest form is $\sin^{-1}\left(\frac{x}{a}\right)$.

**7. $\tan^{-1}\left(\frac{3a^2x - x^3}{a^3 - 3ax^2}\right)$, $a > 0; -\frac{a}{\sqrt{3}} < x < \frac{a}{\sqrt{3}}$**
Let $x = a\tan\theta$. Then $\tan\theta = \frac{x}{a}$, and $\theta = \tan^{-1}\left(\frac{x}{a}\right)$.
Given $-\frac{a}{\sqrt{3}} < x < \frac{a}{\sqrt{3}}$.
Dividing by $a$: $-\frac{1}{\sqrt{3}} < \frac{x}{a} < \frac{1}{\sqrt{3}}$.
So, $-\frac{1}{\sqrt{3}} < \tan\theta < \frac{1}{\sqrt{3}}$.
This implies $-\frac{\pi}{6} < \theta < \frac{\pi}{6}$.
$\tan^{-1}\left(\frac{3a^2(a\tan\theta) - (a\tan\theta)^3}{a^3 - 3a(a\tan\theta)^2}\right)$
$= \tan^{-1}\left(\frac{3a^3\tan\theta - a^3\tan^3\theta}{a^3 - 3a^3\tan^2\theta}\right)$
Factor out $a^3$ from numerator and denominator:
$= \tan^{-1}\left(\frac{a^3(3\tan\theta - \tan^3\theta)}{a^3(1 - 3\tan^2\theta)}\right)$
$= \tan^{-1}\left(\frac{3\tan\theta - \tan^3\theta}{1 - 3\tan^2\theta}\right)$
We know that $\tan(3\theta) = \frac{3\tan\theta - \tan^3\theta}{1 - 3\tan^2\theta}$.
$= \tan^{-1}(\tan(3\theta))$
Since $-\frac{\pi}{6} < \theta < \frac{\pi}{6}$, we have $-\frac{\pi}{2} < 3\theta < \frac{\pi}{2}$.
Thus, $\tan^{-1}(\tan(3\theta)) = 3\theta$.
Substitute back $\theta = \tan^{-1}\left(\frac{x}{a}\right)$.
So, the simplest form is $3\tan^{-1}\left(\frac{x}{a}\right)$.

**Find the values of each of the following:**

**8. $\tan\left[2\cos\left(2\sin^{-1}\frac{1}{2}\right)\right]$**
First, evaluate $\sin^{-1}\frac{1}{2}$.
Let $\alpha = \sin^{-1}\frac{1}{2}$. Then $\sin\alpha = \frac{1}{2}$.
The principal value is $\alpha = \frac{\pi}{6}$.
Now substitute this back:
$\tan\left[2\cos\left(2 \cdot \frac{\pi}{6}\right)\right]$
$= \tan\left[2\cos\left(\frac{\pi}{3}\right)\right]$
We know $\cos\left(\frac{\pi}{3}\right) = \frac{1}{2}$.
$= \tan\left[2 \cdot \frac{1}{2}\right]$
$= \tan(1)$
The value is $\tan(1)$. (Note: 1 is in radians).

**9. $\tan\frac{1}{2}\left[\sin^{-1}\left(\frac{2x}{1+x^2}\right) + \cos^{-1}\left(\frac{1-y^2}{1+y^2}\right)\right]$, $|x| < 1, y > 0 \text{ and } xy < 1$**
We know the formulas:
$\sin^{-1}\left(\frac{2x}{1+x^2}\right) = 2\tan^{-1}x$ (for $|x| \le 1$)
$\cos^{-1}\left(\frac{1-y^2}{1+y^2}\right) = 2\tan^{-1}y$ (for $y \ge 0$)
Substitute these into the expression:
$\tan\frac{1}{2}[2\tan^{-1}x + 2\tan^{-1}y]$
$= \tan\frac{1}{2}[2(\tan^{-1}x + \tan^{-1}y)]$
$= \tan[\tan^{-1}x + \tan^{-1}y]$
We use the formula $\tan^{-1}x + \tan^{-1}y = \tan^{-1}\left(\frac{x+y}{1-xy}\right)$ (for $xy < 1$).
Given $xy < 1$, this formula is applicable.
$= \tan\left[\tan^{-1}\left(\frac{x+y}{1-xy}\right)\right]$
$= \frac{x+y}{1-xy}$
The value is $\frac{x+y}{1-xy}$.

---

### Miscellaneous Examples (from the section before Exercise 2.1)

**Example 1: Find the principal value of sin⁻¹(1/√2)**
This is the same as Exercise 2.1, Q1. The solution is $\frac{\pi}{4}$.

**Example 2: Find the principal value of cot⁻¹(-1/√3)**
Let $y = \cot^{-1}\left(-\frac{1}{\sqrt{3}}\right)$.
Then $\cot y = -\frac{1}{\sqrt{3}}$.
We know that the range of the principal value branch of $\cot^{-1}x$ is $(0, \pi)$.
Since $\cot\left(\frac{\pi}{3}\right) = \frac{1}{\sqrt{3}}$, we have $\cot\left(\pi - \frac{\pi}{3}\right) = -\cot\left(\frac{\pi}{3}\right) = -\frac{1}{\sqrt{3}}$.
So, $\cot\left(\frac{2\pi}{3}\right) = -\frac{1}{\sqrt{3}}$.
Since $\frac{2\pi}{3} \in (0, \pi)$, the principal value of $\cot^{-1}\left(-\frac{1}{\sqrt{3}}\right)$ is $\frac{2\pi}{3}$.

---

### Example 6 (from page 30)

**Find the value of $\sin^{-1}\left(\sin\frac{3\pi}{5}\right)$**
We know that $\sin^{-1}(\sin x) = x$ if $x \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.
Here $x = \frac{3\pi}{5}$. This value is not in the principal value branch $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ because $\frac{3\pi}{5} > \frac{\pi}{2}$.
However, we know that $\sin(\pi - \theta) = \sin\theta$.
So, $\sin\left(\frac{3\pi}{5}\right) = \sin\left(\pi - \frac{3\pi}{5}\right) = \sin\left(\frac{5\pi - 3\pi}{5}\right) = \sin\left(\frac{2\pi}{5}\right)$.
Now, $\frac{2\pi}{5}$ lies in the principal value branch $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ because $-\frac{\pi}{2} \le \frac{2\pi}{5} \le \frac{\pi}{2}$ (i.e., $-0.5\pi \le 0.4\pi \le 0.5\pi$).
Therefore, $\sin^{-1}\left(\sin\frac{3\pi}{5}\right) = \sin^{-1}\left(\sin\frac{2\pi}{5}\right) = \frac{2\pi}{5}$.
The value is $\frac{2\pi}{5}$.

---

### Exercises 10-12 (from page 27)

**Find the values of the following:**

**10. $\sin\left(\sin^{-1}\frac{2\pi}{3}\right)$**
This seems to be a typo in the original document, it should be $\sin^{-1}\left(\sin\left(\frac{2\pi}{3}\right)\right)$ or $\sin\left(\sin^{-1}\left(\frac{2}{3}\right)\right)$. Assuming it means $\sin^{-1}\left(\sin\left(\frac{2\pi}{3}\right)\right)$.
We know that $\sin^{-1}(\sin x) = x$ if $x \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.
Here $x = \frac{2\pi}{3}$. This value is not in the principal value branch $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$ because $\frac{2\pi}{3} > \frac{\pi}{2}$.
We have $\sin\left(\frac{2\pi}{3}\right) = \sin\left(\pi - \frac{\pi}{3}\right) = \sin\left(\frac{\pi}{3}\right)$.
Since $\frac{\pi}{3} \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$,
$\sin^{-1}\left(\sin\frac{2\pi}{3}\right) = \sin^{-1}\left(\sin\frac{\pi}{3}\right) = \frac{\pi}{3}$.
The value is $\frac{\pi}{3}$.

**11. $\tan^{-1}\left(\tan\frac{3\pi}{4}\right)$**
We know that $\tan^{-1}(\tan x) = x$ if $x \in \left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$.
Here $x = \frac{3\pi}{4}$. This value is not in the principal value branch $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$ because $\frac{3\pi}{4} > \frac{\pi}{2}$.
We have $\tan\left(\frac{3\pi}{4}\right) = \tan\left(\pi - \frac{\pi}{4}\right) = -\tan\left(\frac{\pi}{4}\right) = -1$.
We also know that $\tan\left(-\frac{\pi}{4}\right) = -1$.
Since $-\frac{\pi}{4} \in \left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$,
$\tan^{-1}\left(\tan\frac{3\pi}{4}\right) = \tan^{-1}(-1) = -\frac{\pi}{4}$.
The value is $-\frac{\pi}{4}$.

**12. $\tan\left(\sin^{-1}\frac{3}{5} + \cot^{-1}\frac{3}{2}\right)$**
Let $\alpha = \sin^{-1}\frac{3}{5}$ and $\beta = \cot^{-1}\frac{3}{2}$.
For $\alpha = \sin^{-1}\frac{3}{5}$, $\sin\alpha = \frac{3}{5}$. We can form a right triangle with opposite side 3 and hypotenuse 5, so the adjacent side is $\sqrt{5^2 - 3^2} = \sqrt{25-9} = \sqrt{16} = 4$.
Thus, $\tan\alpha = \frac{3}{4}$.
For $\beta = \cot^{-1}\frac{3}{2}$, $\cot\beta = \frac{3}{2}$. So, $\tan\beta = \frac{2}{3}$.
Now the expression becomes $\tan(\alpha + \beta)$.
Using the formula $\tan(A+B) = \frac{\tan A + \tan B}{1 - \tan A \tan B}$:
$\tan(\alpha + \beta) = \frac{\tan\alpha + \tan\beta}{1 - \tan\alpha \tan\beta}$
$= \frac{\frac{3}{4} + \frac{2}{3}}{1 - \frac{3}{4} \cdot \frac{2}{3}}$
$= \frac{\frac{9+8}{12}}{1 - \frac{6}{12}}$
$= \frac{\frac{17}{12}}{1 - \frac{1}{2}}$
$= \frac{\frac{17}{12}}{\frac{1}{2}}$
$= \frac{17}{12} \times 2 = \frac{17}{6}$.
The value is $\frac{17}{6}$.

---

### Exercises 13-15 (from page 30)

**13. If $\sin^{-1} x = y$, then**
The range of the principal value branch of $\sin^{-1}x$ is $\left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.
So, if $\sin^{-1}x = y$, then $y \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right]$.
The correct option is (B) $-\frac{\pi}{2} \le y \le \frac{\pi}{2}$.

**14. $\tan^{-1}\sqrt{3} - \sec^{-1}(-2)$ is equal to**
First, evaluate $\tan^{-1}\sqrt{3}$.
Let $\alpha = \tan^{-1}\sqrt{3}$. Then $\tan\alpha = \sqrt{3}$.
The principal value is $\alpha = \frac{\pi}{3}$.
Next, evaluate $\sec^{-1}(-2)$.
Let $\beta = \sec^{-1}(-2)$. Then $\sec\beta = -2$.
We know that the range of the principal value branch of $\sec^{-1}x$ is $[0, \pi] - \left\{\frac{\pi}{2}\right\}$.
Since $\sec\left(\frac{\pi}{3}\right) = 2$, we have $\sec\left(\pi - \frac{\pi}{3}\right) = -\sec\left(\frac{\pi}{3}\right) = -2$.
So, $\sec\left(\frac{2\pi}{3}\right) = -2$.
Since $\frac{2\pi}{3} \in [0, \pi] - \left\{\frac{\pi}{2}\right\}$, the principal value is $\beta = \frac{2\pi}{3}$.
Now, calculate the expression:
$\tan^{-1}\sqrt{3} - \sec^{-1}(-2) = \frac{\pi}{3} - \frac{2\pi}{3} = -\frac{\pi}{3}$.
The correct option is (B) $-\frac{\pi}{3}$.

**15. $\sin\left(\frac{\pi}{3} - \sin^{-1}\left(-\frac{1}{2}\right)\right)$ is equal to**
First, evaluate $\sin^{-1}\left(-\frac{1}{2}\right)$.
Let $\alpha = \sin^{-1}\left(-\frac{1}{2}\right)$. Then $\sin\alpha = -\frac{1}{2}$.
The principal value is $\alpha = -\frac{\pi}{6}$.
Now substitute this back into the expression:
$\sin\left(\frac{\pi}{3} - \left(-\frac{\pi}{6}\right)\right)$
$= \sin\left(\frac{\pi}{3} + \frac{\pi}{6}\right)$
$= \sin\left(\frac{2\pi}{6} + \frac{\pi}{6}\right)$
$= \sin\left(\frac{3\pi}{6}\right)$
$= \sin\left(\frac{\pi}{2}\right)$
$= 1$.
The correct option is (D) 1.

---

### Miscellaneous Exercise on Chapter 2

**Find the value of the following:**

**1. $\cos^{-1}\left(\cos\frac{13\pi}{6}\right)$**
We know that $\cos^{-1}(\cos x) = x$ if $x \in [0, \pi]$.
Here $x = \frac{13\pi}{6}$. This value is not in the principal value branch $[0, \pi]$ because $\frac{13\pi}{6} = 2\pi + \frac{\pi}{6} > \pi$.
We have $\cos\left(\frac{13\pi}{6}\right) = \cos\left(2\pi + \frac{\pi}{6}\right) = \cos\left(\frac{\pi}{6}\right)$.
Since $\frac{\pi}{6} \in [0, \pi]$,
$\cos^{-1}\left(\cos\frac{13\pi}{6}\right) = \cos^{-1}\left(\cos\frac{\pi}{6}\right) = \frac{\pi}{6}$.
The value is $\frac{\pi}{6}$.

**2. $\tan^{-1}\left(\tan\frac{7\pi}{6}\right)$**
We know that $\tan^{-1}(\tan x) = x$ if $x \in \left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$.
Here $x = \frac{7\pi}{6}$. This value is not in the principal value branch $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$ because $\frac{7\pi}{6} > \frac{\pi}{2}$.
We have $\tan\left(\frac{7\pi}{6}\right) = \tan\left(\pi + \frac{\pi}{6}\right) = \tan\left(\frac{\pi}{6}\right)$.
Since $\frac{\pi}{6} \in \left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$,
$\tan^{-1}\left(\tan\frac{7\pi}{6}\right) = \tan^{-1}\left(\tan\frac{\pi}{6}\right) = \frac{\pi}{6}$.
The value is $\frac{\pi}{6}$.

**Prove that:**

**3. $2\sin^{-1}\frac{3}{5} = \tan^{-1}\frac{24}{7}$**
Let $\sin^{-1}\frac{3}{5} = \theta$. Then $\sin\theta = \frac{3}{5}$.
Since $\sin\theta = \frac{3}{5}$, for a right triangle, opposite side = 3, hypotenuse = 5.
Adjacent side = $\sqrt{5^2 - 3^2} = 4$.
So, $\tan\theta = \frac{3}{4}$.
The LHS is $2\theta$. We want to show $2\theta = \tan^{-1}\frac{24}{7}$, or $\tan(2\theta) = \frac{24}{7}$.
Using the double angle formula for tangent, $\tan(2\theta) = \frac{2\tan\theta}{1-\tan^2\theta}$.
$\tan(2\theta) = \frac{2\left(\frac{3}{4}\right)}{1-\left(\frac{3}{4}\right)^2} = \frac{\frac{3}{2}}{1-\frac{9}{16}} = \frac{\frac{3}{2}}{\frac{16-9}{16}} = \frac{\frac{3}{2}}{\frac{7}{16}} = \frac{3}{2} \times \frac{16}{7} = \frac{24}{7}$.
So, $2\theta = \tan^{-1}\frac{24}{7}$.
Hence, $2\sin^{-1}\frac{3}{5} = \tan^{-1}\frac{24}{7}$ is proved.

**4. $\sin^{-1}\frac{8}{17} + \sin^{-1}\frac{3}{5} = \tan^{-1}\frac{77}{36}$**
Let $\sin^{-1}\frac{8}{17} = A$. Then $\sin A = \frac{8}{17}$. So $\cos A = \sqrt{1 - \left(\frac{8}{17}\right)^2} = \sqrt{1 - \frac{64}{289}} = \sqrt{\frac{225}{289}} = \frac{15}{17}$.
Let $\sin^{-1}\frac{3}{5} = B$. Then $\sin B = \frac{3}{5}$. So $\cos B = \sqrt{1 - \left(\frac{3}{5}\right)^2} = \sqrt{1 - \frac{9}{25}} = \sqrt{\frac{16}{25}} = \frac{4}{5}$.
Using the formula $\sin(A+B) = \sin A \cos B + \cos A \sin B$:
$\sin(A+B) = \left(\frac{8}{17}\right)\left(\frac{4}{5}\right) + \left(\frac{15}{17}\right)\left(\frac{3}{5}\right)$
$= \frac{32}{85} + \frac{45}{85} = \frac{77}{85}$.
So, $A+B = \sin^{-1}\frac{77}{85}$.
Now we need to convert $\sin^{-1}\frac{77}{85}$ to $\tan^{-1}$.
If $\sin C = \frac{77}{85}$, then for a right triangle, opposite side = 77, hypotenuse = 85.
Adjacent side = $\sqrt{85^2 - 77^2} = \sqrt{(85-77)(85+77)} = \sqrt{8 \times 162} = \sqrt{1296} = 36$.
So, $\tan C = \frac{77}{36}$.
Therefore, $A+B = \tan^{-1}\frac{77}{36}$.
Hence, $\sin^{-1}\frac{8}{17} + \sin^{-1}\frac{3}{5} = \tan^{-1}\frac{77}{36}$ is proved.

**5. $\cos^{-1}\frac{4}{5} + \cos^{-1}\frac{12}{13} = \cos^{-1}\frac{33}{65}$**
Let $\cos^{-1}\frac{4}{5} = A$. Then $\cos A = \frac{4}{5}$. So $\sin A = \sqrt{1 - \left(\frac{4}{5}\right)^2} = \sqrt{1 - \frac{16}{25}} = \sqrt{\frac{9}{25}} = \frac{3}{5}$.
Let $\cos^{-1}\frac{12}{13} = B$. Then $\cos B = \frac{12}{13}$. So $\sin B = \sqrt{1 - \left(\frac{12}{13}\right)^2} = \sqrt{1 - \frac{144}{169}} = \sqrt{\frac{25}{169}} = \frac{5}{13}$.
Using the formula $\cos(A+B) = \cos A \cos B - \sin A \sin B$:
$\cos(A+B) = \left(\frac{4}{5}\right)\left(\frac{12}{13}\right) - \left(\frac{3}{5}\right)\left(\frac{5}{13}\right)$
$= \frac{48}{65} - \frac{15}{65} = \frac{33}{65}$.
So, $A+B = \cos^{-1}\frac{33}{65}$.
Hence, $\cos^{-1}\frac{4}{5} + \cos^{-1}\frac{12}{13} = \cos^{-1}\frac{33}{65}$ is proved.

**6. $\cos^{-1}\frac{12}{13} + \sin^{-1}\frac{3}{5} = \sin^{-1}\frac{56}{65}$**
Let $\cos^{-1}\frac{12}{13} = A$. Then $\cos A = \frac{12}{13}$. So $\sin A = \sqrt{1 - \left(\frac{12}{13}\right)^2} = \frac{5}{13}$.
Let $\sin^{-1}\frac{3}{5} = B$. Then $\sin B = \frac{3}{5}$. So $\cos B = \sqrt{1 - \left(\frac{3}{5}\right)^2} = \frac{4}{5}$.
Using the formula $\sin(A+B) = \sin A \cos B + \cos A \sin B$:
$\sin(A+B) = \left(\frac{5}{13}\right)\left(\frac{4}{5}\right) + \left(\frac{12}{13}\right)\left(\frac{3}{5}\right)$
$= \frac{20}{65} + \frac{36}{65} = \frac{56}{65}$.
So, $A+B = \sin^{-1}\frac{56}{65}$.
Hence, $\cos^{-1}\frac{12}{13} + \sin^{-1}\frac{3}{5} = \sin^{-1}\frac{56}{65}$ is proved.

**7. $\tan^{-1}\frac{63}{16} = \sin^{-1}\frac{5}{13} + \cos^{-1}\frac{3}{5}$**
Let RHS = $\sin^{-1}\frac{5}{13} + \cos^{-1}\frac{3}{5}$.
Let $\sin^{-1}\frac{5}{13} = A$. Then $\sin A = \frac{5}{13}$. So $\cos A = \sqrt{1 - \left(\frac{5}{13}\right)^2} = \frac{12}{13}$.
Therefore, $\tan A = \frac{5/13}{12/13} = \frac{5}{12}$.
Let $\cos^{-1}\frac{3}{5} = B$. Then $\cos B = \frac{3}{5}$. So $\sin B = \sqrt{1 - \left(\frac{3}{5}\right)^2} = \frac{4}{5}$.
Therefore, $\tan B = \frac{4/5}{3/5} = \frac{4}{3}$.
Now, $A+B = \tan^{-1}\left(\frac{\tan A + \tan B}{1 - \tan A \tan B}\right)$
$= \tan^{-1}\left(\frac{\frac{5}{12} + \frac{4}{3}}{1 - \frac{5}{12} \cdot \frac{4}{3}}\right)$
$= \tan^{-1}\left(\frac{\frac{5+16}{12}}{1 - \frac{20}{36}}\right)$
$= \tan^{-1}\left(\frac{\frac{21}{12}}{\frac{36-20}{36}}\right)$
$= \tan^{-1}\left(\frac{\frac{7}{4}}{\frac{16}{36}}\right)$
$= \tan^{-1}\left(\frac{\frac{7}{4}}{\frac{4}{9}}\right)$
$= \tan^{-1}\left(\frac{7}{4} \times \frac{9}{4}\right)$
$= \tan^{-1}\left(\frac{63}{16}\right)$ = LHS.
Hence, $\tan^{-1}\frac{63}{16} = \sin^{-1}\frac{5}{13} + \cos^{-1}\frac{3}{5}$ is proved.

**Prove that:**

**8. $\tan^{-1}\sqrt{x} = \frac{1}{2}\cos^{-1}\left(\frac{1-x}{1+x}\right)$, $x \in$**
Let $\sqrt{x} = \tan\theta$. Then $x = \tan^2\theta$. So $\theta = \tan^{-1}\sqrt{x}$.
RHS = $\frac{1}{2}\cos^{-1}\left(\frac{1-\tan^2\theta}{1+\tan^2\theta}\right)$.
We know that $\cos(2\theta) = \frac{1-\tan^2\theta}{1+\tan^2\theta}$.
RHS = $\frac{1}{2}\cos^{-1}(\cos(2\theta))$.
Since $x \in$, $\sqrt{x} \in$. So $\tan\theta \in$.
This means $\theta \in \left[0, \frac{\pi}{4}\right]$.
Therefore, $2\theta \in \left[0, \frac{\pi}{2}\right]$.
Since $2\theta$ is in the principal value branch of $\cos^{-1}$, $\cos^{-1}(\cos(2\theta)) = 2\theta$.
RHS = $\frac{1}{2}(2\theta) = \theta$.
Substitute back $\theta = \tan^{-1}\sqrt{x}$.
RHS = $\tan^{-1}\sqrt{x}$ = LHS.
Hence, $\tan^{-1}\sqrt{x} = \frac{1}{2}\cos^{-1}\left(\frac{1-x}{1+x}\right)$ is proved.

**9. $\cot^{-1}\left(\frac{\sqrt{1+\sin x} + \sqrt{1-\sin x}}{\sqrt{1+\sin x} - \sqrt{1-\sin x}}\right)$, $x \in \left(0, \frac{\pi}{4}\right)$**
We know that $1+\sin x = \left(\cos\frac{x}{2} + \sin\frac{x}{2}\right)^2$ and $1-\sin x = \left(\cos\frac{x}{2} - \sin\frac{x}{2}\right)^2$.
So, $\sqrt{1+\sin x} = \left|\cos\frac{x}{2} + \sin\frac{x}{2}\right|$ and $\sqrt{1-\sin x} = \left|\cos\frac{x}{2} - \sin\frac{x}{2}\right|$.
Since $x \in \left(0, \frac{\pi}{4}\right)$, we have $\frac{x}{2} \in \left(0, \frac{\pi}{8}\right)$.
In this interval, $\cos\frac{x}{2} > \sin\frac{x}{2} > 0$.
So, $\sqrt{1+\sin x} = \cos\frac{x}{2} + \sin\frac{x}{2}$ and $\sqrt{1-\sin x} = \cos\frac{x}{2} - \sin\frac{x}{2}$.
Substitute these into the expression:
$\cot^{-1}\left(\frac{(\cos\frac{x}{2} + \sin\frac{x}{2}) + (\cos\frac{x}{2} - \sin\frac{x}{2})}{(\cos\frac{x}{2} + \sin\frac{x}{2}) - (\cos\frac{x}{2} - \sin\frac{x}{2})}\right)$
$= \cot^{-1}\left(\frac{2\cos\frac{x}{2}}{2\sin\frac{x}{2}}\right)$
$= \cot^{-1}\left(\cot\frac{x}{2}\right)$.
Since $\frac{x}{2} \in \left(0, \frac{\pi}{8}\right)$, which is in the principal value branch of $\cot^{-1}x$,
$= \frac{x}{2}$.
The value of the expression is $\frac{x}{2}$.

**10. $\tan^{-1}\left(\frac{\sqrt{1+x} - \sqrt{1-x}}{\sqrt{1+x} + \sqrt{1-x}}\right) = \frac{\pi}{4} - \frac{1}{2}\cos^{-1}x$, $\frac{1}{\sqrt{2}} \le x \le 1$**
Let $x = \cos(2\theta)$. Then $2\theta = \cos^{-1}x$, so $\theta = \frac{1}{2}\cos^{-1}x$.
Since $\frac{1}{\sqrt{2}} \le x \le 1$, we have $\frac{1}{\sqrt{2}} \le \cos(2\theta) \le 1$.
This implies $0 \le 2\theta \le \frac{\pi}{4}$, so $0 \le \theta \le \frac{\pi}{8}$.
LHS = $\tan^{-1}\left(\frac{\sqrt{1+\cos(2\theta)} - \sqrt{1-\cos(2\theta)}}{\sqrt{1+\cos(2\theta)} + \sqrt{1-\cos(2\theta)}}\right)$
We know $1+\cos(2\theta) = 2\cos^2\theta$ and $1-\cos(2\theta) = 2\sin^2\theta$.
LHS = $\tan^{-1}\left(\frac{\sqrt{2\cos^2\theta} - \sqrt{2\sin^2\theta}}{\sqrt{2\cos^2\theta} + \sqrt{2\sin^2\theta}}\right)$
$= \tan^{-1}\left(\frac{\sqrt{2}|\cos\theta| - \sqrt{2}|\sin\theta|}{\sqrt{2}|\cos\theta| + \sqrt{2}|\sin\theta|}\right)$
Since $0 \le \theta \le \frac{\pi}{8}$, both $\sin\theta$ and $\cos\theta$ are positive.
$= \tan^{-1}\left(\frac{\sqrt{2}\cos\theta - \sqrt{2}\sin\theta}{\sqrt{2}\cos\theta + \sqrt{2}\sin\theta}\right)$
$= \tan^{-1}\left(\frac{\cos\theta - \sin\theta}{\cos\theta + \sin\theta}\right)$
Divide numerator and denominator by $\cos\theta$:
$= \tan^{-1}\left(\frac{1 - \tan\theta}{1 + \tan\theta}\right)$
$= \tan^{-1}\left(\tan\left(\frac{\pi}{4} - \theta\right)\right)$.
Since $0 \le \theta \le \frac{\pi}{8}$, we have $-\frac{\pi}{8} \le -\theta \le 0$.
So, $\frac{\pi}{4} - \frac{\pi}{8} \le \frac{\pi}{4} - \theta \le \frac{\pi}{4} - 0$.
$\frac{\pi}{8} \le \frac{\pi}{4} - \theta \le \frac{\pi}{4}$.
This interval is within $\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)$, the principal value branch for $\tan^{-1}$.
So, LHS = $\frac{\pi}{4} - \theta$.
Substitute back $\theta = \frac{1}{2}\cos^{-1}x$.
LHS = $\frac{\pi}{4} - \frac{1}{2}\cos^{-1}x$ = RHS.
Hence, the identity is proved.

**Solve the following equations:**

**11. $2\tan^{-1}(\cos x) = \tan^{-1}(2\text{cosec } x)$**
Using the formula $2\tan^{-1}A = \tan^{-1}\left(\frac{2A}{1-A^2}\right)$:
$\tan^{-1}\left(\frac{2\cos x}{1-\cos^2 x}\right) = \tan^{-1}(2\text{cosec } x)$
$\tan^{-1}\left(\frac{2\cos x}{\sin^2 x}\right) = \tan^{-1}(2\text{cosec } x)$
Since the $\tan^{-1}$ function is one-to-one, we can equate the arguments:
$\frac{2\cos x}{\sin^2 x} = 2\text{cosec } x$
$\frac{2\cos x}{\sin^2 x} = \frac{2}{\sin x}$
Assuming $\sin x \neq 0$, we can divide by $\frac{2}{\sin x}$:
$\frac{\cos x}{\sin x} = 1$
$\cot x = 1$.
The principal value for $x$ is $\frac{\pi}{4}$.
In general, $x = n\pi + \frac{\pi}{4}$, where $n \in Z$.

**12. $\tan^{-1}\left(\frac{1-x}{1+x}\right) = \frac{1}{2}\tan^{-1}x$, $x > 0$**
Using the formula $\tan^{-1}A - \tan^{-1}B = \tan^{-1}\left(\frac{A-B}{1+AB}\right)$, we can see that $\tan^{-1}\left(\frac{1-x}{1+x}\right) = \tan^{-1}1 - \tan^{-1}x$.
So, $\tan^{-1}1 - \tan^{-1}x = \frac{1}{2}\tan^{-1}x$
$\frac{\pi}{4} - \tan^{-1}x = \frac{1}{2}\tan^{-1}x$
$\frac{\pi}{4} = \frac{1}{2}\tan^{-1}x + \tan^{-1}x$
$\frac{\pi}{4} = \frac{3}{2}\tan^{-1}x$
$\tan^{-1}x = \frac{\pi}{4} \times \frac{2}{3} = \frac{\pi}{6}$
$x = \tan\left(\frac{\pi}{6}\right)$
$x = \frac{1}{\sqrt{3}}$.

**Multiple Choice Questions:**

**13. $\sin(\tan^{-1}x)$, $|x|<1$ is equal to**
Let $\tan^{-1}x = \theta$. Then $\tan\theta = x$.
We want to find $\sin\theta$.
Form a right triangle: opposite side = $x$, adjacent side = $1$.
Hypotenuse = $\sqrt{x^2+1^2} = \sqrt{1+x^2}$.
So, $\sin\theta = \frac{\text{opposite}}{\text{hypotenuse}} = \frac{x}{\sqrt{1+x^2}}$.
The correct option is (D) $\frac{x}{\sqrt{1+x^2}}$.

**14. If $\sin^{-1}(1-x) - 2\sin^{-1}x = \frac{\pi}{2}$, then $x$ is equal to**
Given $\sin^{-1}(1-x) = \frac{\pi}{2} + 2\sin^{-1}x$.
Let $\sin^{-1}x = \theta$. Then $x = \sin\theta$.
Also, $1-x = \sin\left(\frac{\pi}{2} + 2\theta\right)$
$1-x = \cos(2\theta)$
We know $\cos(2\theta) = 1 - 2\sin^2\theta$.
So, $1-x = 1 - 2x^2$.
$0 = -x + 2x^2$
$0 = x(2x - 1)$.
This gives $x=0$ or $x=\frac{1}{2}$.
Let's check these values in the original equation:
If $x=0$:
$\sin^{-1}(1-0) - 2\sin^{-1}(0) = \sin^{-1}(1) - 2(0) = \frac{\pi}{2} - 0 = \frac{\pi}{2}$.
So $x=0$ is a solution.
If $x=\frac{1}{2}$:
$\sin^{-1}\left(1-\frac{1}{2}\right) - 2\sin^{-1}\left(\frac{1}{2}\right) = \sin^{-1}\left(\frac{1}{2}\right) - 2\sin^{-1}\left(\frac{1}{2}\right)$
$= -\sin^{-1}\left(\frac{1}{2}\right) = -\frac{\pi}{6}$.
This is not equal to $\frac{\pi}{2}$.
So $x=\frac{1}{2}$ is not a solution.
The correct option is (A) 0.

---