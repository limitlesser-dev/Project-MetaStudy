## 🛠 Your Essential Trigonometric Identities "Toolbox" for Chapter 2 Proofs

These are the absolute must-know identities that frequently appear in inverse trigonometric function proofs. Commit these to memory!

### 1. **Basic Pythagorean Identities:**
These relate sine, cosine, and tangent.
*   $\sin^2 \theta + \cos^2 \theta = 1$
*   $1 + \tan^2 \theta = \sec^2 \theta$
*   $1 + \cot^2 \theta = \csc^2 \theta$

### 2. **Half-Angle / Double Angle Manipulation Forms (Crucial for expressions like $\frac{1-\cos x}{1+\cos x}$):**
These come directly from the $\cos 2\theta$ formulas but are used very often to simplify $1 \pm \cos x$.
*   $1 - \cos \theta = 2\sin^2 \left(\frac{\theta}{2}\right)$
    *   *Think:* "1 minus cosine means 2 sine squared (half angle)."
*   $1 + \cos \theta = 2\cos^2 \left(\frac{\theta}{2}\right)$
    *   *Think:* "1 plus cosine means 2 cosine squared (half angle)."
*   $\sin \theta = 2\sin \left(\frac{\theta}{2}\right) \cos \left(\frac{\theta}{2}\right)$
    *   *This is just the $\sin 2A$ formula with $A=\theta/2$.*

### 3. **Double Angle Formulas (Very Important for $2\tan^{-1}x$ type questions):**
These express $\sin 2\theta$, $\cos 2\theta$, $\tan 2\theta$ in terms of $\tan \theta$.
*   $\sin 2\theta = \frac{2\tan\theta}{1+\tan^2\theta}$
*   $\cos 2\theta = \frac{1-\tan^2\theta}{1+\tan^2\theta}$
*   $\tan 2\theta = \frac{2\tan\theta}{1-\tan^2\theta}$

### 4. **Triple Angle Formulas (ABSOLUTELY ESSENTIAL for $3\sin^{-1}x$, $3\cos^{-1}x$ proofs):**
These are the ones you asked about specifically!
*   $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$
    *   **Memorization Tip:** Think "34". Three times sine, minus four times sine cubed. Starts with 3, ends with 4.
*   $\cos 3\theta = 4\cos^3\theta - 3\cos\theta$
    *   **Memorization Tip:** Think "43". Four times cosine cubed, minus three times cosine. Starts with 4, ends with 3. (Notice it's the reverse pattern of $\sin 3\theta$).
*   $\tan 3\theta = \frac{3\tan\theta - \tan^3\theta}{1-3\tan^2\theta}$

---

## 💡 How to Memorize These Identities Effectively:

1.  **Understand the Derivation (Don't just rote learn):** While you need to recall them quickly, knowing *where they come from* can help if you get stuck. For example:
    *   $\sin 3\theta = \sin(2\theta + \theta) = \sin 2\theta \cos\theta + \cos 2\theta \sin\theta$
        *   Then substitute $\sin 2\theta = 2\sin\theta\cos\theta$ and $\cos 2\theta = 1-2\sin^2\theta$.
        *   $= (2\sin\theta\cos\theta)\cos\theta + (1-2\sin^2\theta)\sin\theta$
        *   $= 2\sin\theta\cos^2\theta + \sin\theta - 2\sin^3\theta$
        *   $= 2\sin\theta(1-\sin^2\theta) + \sin\theta - 2\sin^3\theta$ (using $\cos^2\theta = 1-\sin^2\theta$)
        *   $= 2\sin\theta - 2\sin^3\theta + \sin\theta - 2\sin^3\theta$
        *   $= 3\sin\theta - 4\sin^3\theta$.
    *   Similarly for $\cos 3\theta = \cos(2\theta + \theta)$, use $\cos 2\theta = 2\cos^2\theta - 1$.

2.  **Write Them Down Repeatedly:** Just the act of physically writing them helps engrain them in your memory.
3.  **Flashcards:** Put the left side ($\sin 3\theta$) on one side, and the right side ($3\sin\theta - 4\sin^3\theta$) on the other. Test yourself!
4.  **Practice Problems (Crucial!):** Every time you do a proof, you're actively recalling and using these identities. This is the best form of long-term memorization. The more you use them, the more natural they become.
5.  **Look for Patterns:** Like the "34" and "43" for triple angles, or how the double angle formulas for $\sin 2\theta$ and $\cos 2\theta$ in terms of $\tan\theta$ involve $2\tan\theta$ and $1\pm\tan^2\theta$.

---

## 🚶‍♂️ Let's Re-walk a Proof (with the Identities in Mind)

Let's revisit **Question 1 from Exercise 2.2**:
**Prove $3 \sin^{-1} x = \sin^{-1} (3x - 4x^3)$, $x \in [-\frac{1}{2}, \frac{1}{2}]$**

**This time, with the explicit use of the identity:**

**Thought Process (Step-by-Step with Identity Focus):**

1.  **Analyze the Target (RHS):** The expression inside the $\sin^{-1}$ is $(3x - 4x^3)$.
2.  **Scan your Identity Toolbox:** Immediately, $(3x - 4x^3)$ should trigger the memory of the **Triple Angle Identity for Sine**:
    *   $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$
3.  **Identify the Substitution:** Comparing $(3x - 4x^3)$ with $(3\sin\theta - 4\sin^3\theta)$, it's clear that if we let $x = \sin\theta$, the algebraic expression will transform into the trigonometric identity.
4.  **Perform the Substitution:**
    *   Let $x = \sin\theta$.
    *   This implies $\theta = \sin^{-1}x$. (This is the LHS we want to arrive at!)
5.  **Substitute into the RHS:**
    *   RHS = $\sin^{-1} (3x - 4x^3)$
    *   Substitute $x = \sin\theta$:
    *   RHS = $\sin^{-1} (3\sin\theta - 4\sin^3\theta)$
6.  **Apply the Identity:** Now that it perfectly matches the triple angle identity:
    *   RHS = $\sin^{-1} (\sin 3\theta)$
7.  **Apply the Inverse Property (with careful domain check!):**
    *   We know that $\sin^{-1}(\sin A) = A$, *but only if $A$ is in the principal value branch of $\sin^{-1}$, which is $[-\frac{\pi}{2}, \frac{\pi}{2}]$*.
    *   In our case, $A = 3\theta$. We need to ensure $3\theta \in [-\frac{\pi}{2}, \frac{\pi}{2}]$.
    *   The problem gives us the domain for $x$: $x \in [-\frac{1}{2}, \frac{1}{2}]$.
    *   Since $x = \sin\theta$, this means $\sin\theta \in [-\frac{1}{2}, \frac{1}{2}]$.
    *   For $\theta = \sin^{-1}x$ in its principal branch, this means $\theta \in [-\frac{\pi}{6}, \frac{\pi}{6}]$.
        *   (Because $\sin(-\frac{\pi}{6}) = -\frac{1}{2}$ and $\sin(\frac{\pi}{6}) = \frac{1}{2}$)
    *   Now, check $3\theta$:
        *   Multiply the interval by 3: $3 \times (-\frac{\pi}{6}) \le 3\theta \le 3 \times (\frac{\pi}{6})$
        *   $-\frac{\pi}{2} \le 3\theta \le \frac{\pi}{2}$.
    *   This confirms that $3\theta$ *is* within the required range.
    *   So, $\sin^{-1}(\sin 3\theta) = 3\theta$.
8.  **Substitute back to original variable:**
    *   We know $\theta = \sin^{-1}x$.
    *   Therefore, RHS = $3\sin^{-1}x$.
9.  **Conclusion:** This matches the LHS. Hence, the proof is complete.

---

**Key Takeaway for You:**

The proofs are essentially a two-step process:

1.  **Algebraic Expression $\xrightarrow{\text{Substitution + Identity}}$ Simple Trigonometric Function:** Use a substitution ($x=\sin\theta$, $x=\tan\theta$, etc.) to transform the complex algebraic expression inside the inverse function into a simpler trigonometric form like $\sin(n\theta)$, $\tan(n\theta)$, etc., using one of your memorized identities.
2.  **Inverse Function $\xrightarrow{\text{Inverse Property + Range Check}}$ Angle:** Apply the property $\text{Inv}(\text{Trig}(A)) = A$, always, always, always verifying that the angle $A$ falls within the principal value branch of the outer inverse function.

Start by focusing intensely on those triple angle and double angle identities in terms of $\tan\theta$. Once they click, these proof questions will feel like a puzzle you now have the solution for!