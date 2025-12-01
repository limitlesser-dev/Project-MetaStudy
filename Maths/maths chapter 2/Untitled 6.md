That's a great choice. Problem 3 is a classic simplification problem that uses one of the substitution techniques we listed.

Here is the problem:

#### Problem 3: Write $\tan^{-1} \left(\frac{\sqrt{1+x^2} - 1}{x}\right)$, $x \neq 0$ in the simplest form.

**Goal:** Simplify the expression inside the $\tan^{-1}$ function into a single tangent term, $\tan(\theta)$, so that the final answer is $\theta$.

---

### Guided Solution

**Step 1: Choose the correct Substitution.**

Look at the term inside the square root: **$\sqrt{1+x^2}$**.
*   We need a trigonometric identity that looks like **$1 + (\text{trig function})^2 = (\text{another trig function})^2$**.
*   The Pythagorean identity $1 + \mathbf{\tan^2 \theta} = \mathbf{\sec^2 \theta}$ is the perfect match.

Therefore, we substitute:
$$\text{Let } x = \tan \theta$$
$$\text{This means } \theta = \tan^{-1} x$$

**Step 2: Substitute $x = \tan \theta$ into the expression.**

$$\text{Expression} = \tan^{-1} \left(\frac{\sqrt{1+\tan^2\theta} - 1}{\tan\theta}\right)$$

**Step 3: Simplify the Square Root using the Pythagorean Identity.**

*   Replace $1 + \tan^2\theta$ with $\sec^2\theta$:
$$\text{Expression} = \tan^{-1} \left(\frac{\sqrt{\sec^2\theta} - 1}{\tan\theta}\right)$$

*   The square root cancels the square: $\sqrt{\sec^2\theta} = \sec\theta$:
$$\text{Expression} = \tan^{-1} \left(\frac{\sec\theta - 1}{\tan\theta}\right)$$

**Step 4: Convert to Sine and Cosine (The "S/C" Trick).**

To simplify a complex expression involving $\sec\theta$ and $\tan\theta$, it's usually best to convert everything back to the fundamental $\sin\theta$ and $\cos\theta$ using the reciprocal and quotient identities:
*   $\sec\theta = \frac{1}{\cos\theta}$
*   $\tan\theta = \frac{\sin\theta}{\cos\theta}$

$$\text{Expression} = \tan^{-1} \left(\frac{\frac{1}{\cos\theta} - 1}{\frac{\sin\theta}{\cos\theta}}\right)$$

**Step 5: Simplify the Numerator.**

*   Combine the terms in the numerator by finding a common denominator: $\frac{1}{\cos\theta} - 1 = \frac{1 - \cos\theta}{\cos\theta}$.

$$\text{Expression} = \tan^{-1} \left(\frac{\frac{1 - \cos\theta}{\cos\theta}}{\frac{\sin\theta}{\cos\theta}}\right)$$

**Step 6: Cancel Common Denominators.**

*   The $\cos\theta$ in the denominator of the numerator and the denominator of the denominator cancel out:
$$\text{Expression} = \tan^{-1} \left(\frac{1 - \cos\theta}{\sin\theta}\right)$$

**Step 7: Apply Half-Angle Identities (The crucial step from our list).**

*   Recall the identities that deal with $1 - \cos\theta$ and $\sin\theta$:
    *   $1 - \cos\theta = 2\sin^2\left(\frac{\theta}{2}\right)$
    *   $\sin\theta = 2\sin\left(\frac{\theta}{2}\right)\cos\left(\frac{\theta}{2}\right)$

$$\text{Expression} = \tan^{-1} \left(\frac{2\sin^2(\frac{\theta}{2})}{2\sin(\frac{\theta}{2})\cos(\frac{\theta}{2})}\right)$$

**Step 8: Final Simplification.**

*   Cancel the $2$s.
*   Cancel one $\sin(\frac{\theta}{2})$ term from the numerator and denominator:

$$\text{Expression} = \tan^{-1} \left(\frac{\sin(\frac{\theta}{2})}{\cos(\frac{\theta}{2})}\right)$$

*   Using the definition $\frac{\sin A}{\cos A} = \tan A$:

$$\text{Expression} = \tan^{-1} \left(\tan\left(\frac{\theta}{2}\right)\right)$$

**Step 9: Apply the Inverse Property and Substitute Back.**

*   $\tan^{-1}(\tan A) = A$:
$$\text{Expression} = \frac{\theta}{2}$$

*   Substitute $\theta = \tan^{-1} x$:
$$\text{Final Answer} = \frac{1}{2}\tan^{-1} x$$

---
### Summary of the Method

The solution was a chain reaction:

$$\sqrt{1+x^2} \xrightarrow{x=\tan\theta} \sqrt{\sec^2\theta} \xrightarrow{\text{S/C Trick}} \frac{1-\cos\theta}{\sin\theta} \xrightarrow{\text{Half-Angle}} \frac{\sin(\frac{\theta}{2})}{\cos(\frac{\theta}{2})} \xrightarrow{\text{Definition}} \tan\left(\frac{\theta}{2}\right)$$