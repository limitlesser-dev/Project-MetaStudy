# 📚 NCERT Class 12th Mathematics: Chapter 2 - Inverse Trigonometric Functions
## 🧠 Aapki Ultimate Memorization Sheet & Explanations! (Examples ke saath)

Yeh sheet sirf aapko yeh batane ke liye nahi hai ki kya padhna hai, balki yeh aapko yeh samjhne mein help karegi ki *kyu* yeh important hai aur *kaise* ise effectively memorize karein. Isko small chunks mein divide karo, aur ek saath poora cram karne ki koshish mat karna!

---

## Part 1: Pre-requisite Foundation (Yeh rock solid hona chahiye!)

Inverse functions se pehle, aapko basic trigonometry mein comfortable hona *bahut zaruri* hai. Agar yeh part thoda shaky lag raha hai, toh apni Class 10/11 ki notes review karo!

### 1.1 Conversions: Degrees vs. Radians

*   **The Big Conversion:** $\pi \text{ radians} = 180^\circ$
*   **Key Conversions jo memorize karni hai (kyuki yeh constantly appear hoti hain):**
    *   $0^\circ = 0 \text{ rad}$
    *   $30^\circ = \frac{\pi}{6} \text{ rad}$
    *   $45^\circ = \frac{\pi}{4} \text{ rad}$
    *   $60^\circ = \frac{\pi}{3} \text{ rad}$
    *   $90^\circ = \frac{\pi}{2} \text{ rad}$
    *   $180^\circ = \pi \text{ rad}$
    *   $270^\circ = \frac{3\pi}{2} \text{ rad}$
    *   $360^\circ = 2\pi \text{ rad}$

*   **Memorization Tip:** $\pi/6, \pi/4, \pi/3$ ka pattern dekho. Jaise jaise denominator chhota hota hai, angle bada hota jata hai (kyuki $\pi$ ko kam parts mein divide kiya ja raha hai).

### 1.2 Fundamental Trigonometric Values (standard angles ke liye)

Yeh ABSOLUTE core hai. Ek table banao, use baar-baar draw karo, flashcards use karo, gaana gao – jo bhi lagta hai karo!

| Angle ($\theta$) | $0^\circ (0)$ | $30^\circ (\frac{\pi}{6})$ | $45^\circ (\frac{\pi}{4})$ | $60^\circ (\frac{\pi}{3})$ | $90^\circ (\frac{\pi}{2})$ | $180^\circ (\pi)$ |
| :--------------- | :------------ | :------------------------- | :------------------------- | :------------------------- | :------------------------- | :---------------- |
| $\sin \theta$    | 0             | $\frac{1}{2}$              | $\frac{1}{\sqrt{2}}$       | $\frac{\sqrt{3}}{2}$       | 1                          | 0                 |
| $\cos \theta$    | 1             | $\frac{\sqrt{3}}{2}$       | $\frac{1}{\sqrt{2}}$       | $\frac{1}{2}$              | 0                          | -1                |
| $\tan \theta$    | 0             | $\frac{1}{\sqrt{3}}$       | 1                          | $\sqrt{3}$                 | Undefined (UD)             | 0                 |

*   **Memorization Tip:**
    *   **Sine (0 se 1 tak):** 0 se start hota hai, $90^\circ$ par 1 tak badhta hai. Values hain $\frac{\sqrt{0}}{2}, \frac{\sqrt{1}}{2}, \frac{\sqrt{2}}{2}, \frac{\sqrt{3}}{2}, \frac{\sqrt{4}}{2}$ (jo table values mein simplify ho jaati hain).
    *   **Cosine (1 se 0 tak):** Sine ka reverse hai. 1 se start hota hai, $90^\circ$ par 0 tak ghatta hai.
    *   **Tangent ($\tan \theta = \frac{\sin \theta}{\cos \theta}$):** Ise sine aur cosine se calculate karo.
    *   **Baaki teen:** $\csc \theta = \frac{1}{\sin \theta}$, $\sec \theta = \frac{1}{\cos \theta}$, $\cot \theta = \frac{1}{\tan \theta}$. Agar aapko sin, cos, tan pata hai, toh yeh bhi pata hain!

### 1.3 Quadrant Rules aur Trigonometric Functions ke Signs

Yeh samajhne ke liye bahut crucial hai ki principal values kyu choose ki jaati hain aur negative inputs kaise work karte hain.

*   **"All Students Take Coffee" (ASTC) Rule:**
    *   **A**ll (sab) Quadrant I ($0 \text{ se } \frac{\pi}{2}$) mein positive hote hain.
    *   **S**ine (aur Cosecant) Quadrant II ($\frac{\pi}{2} \text{ se } \pi$) mein positive hote hain.
    *   **T**angent (aur Cotangent) Quadrant III ($\pi \text{ se } \frac{3\pi}{2}$) mein positive hote hain.
    *   **C**osine (aur Secant) Quadrant IV ($\frac{3\pi}{2} \text{ se } 2\pi$) mein positive hote hain.

*   **Memorization Tip:** Cartesian plane draw karo aur quadrants ko ASTC se label karo. Practice karo $\sin(2\pi/3)$ jaise values ka sign find karna (Q2, toh positive).

---

## Part 2: Inverse Trigonometric Functions - Chapter ka Core Content

### 2.1 Inverse Functions ko samajhna (Matlab "Iska Kya Matlab Hai?")

*   **Definition:** Agar $\sin y = x$, toh $y = \sin^{-1} x$. Iska matlab hai ki $y$ woh angle hai jiska sine $x$ hai.
    *   *Example:* Agar $\sin 30^\circ = \frac{1}{2}$, toh $\sin^{-1}\left(\frac{1}{2}\right) = 30^\circ$ (ya $\frac{\pi}{6}$ radians).
*   **Key Concept: The Principal Value Branch:** Kyuki trigonometric functions periodic hote hain (unki values repeat hoti hain), woh apne entire domain par "one-to-one" nahi hote. Ek unique inverse define karne ke liye, hum original trig function ke domain ko restrict karte hain. Inverse function ki *range* yeh restricted domain hoti hai, aur ise Principal Value Branch kehte hain. Aapko *ensure* karna hoga ki aapke answers in ranges ke andar hi fall karein.

### 2.2 Domain aur Range (Principal Value Branch) of Inverse Trigonometric Functions

Principal values find karne ke liye yeh **SABSE IMPORTANT TABLE** hai jo memorize karni hai.

| Inverse Function | Domain (Allowed $x$ values) | Range (Principal Value Branch - Output Angle $y$) | Why this range? |
| :--------------- | :-------------------------- | :------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------- |
| $y = \sin^{-1} x$ | $[-1, 1]$                   | $[-\frac{\pi}{2}, \frac{\pi}{2}]$ (Q4 & Q1)         | Saare unique sine values -1 se 1 tak contain karta hai. Negative $90^\circ$ se positive $90^\circ$ tak extend karta hai. |
| $y = \cos^{-1} x$ | $[-1, 1]$                   | $[0, \pi]$ (Q1 & Q2)                            | Saare unique cosine values -1 se 1 tak contain karta hai. $0^\circ$ se $180^\circ$ tak extend karta hai. |
| $y = \tan^{-1} x$ | $\mathbb{R}$                | $(-\frac{\pi}{2}, \frac{\pi}{2})$ (Q4 & Q1)         | Saare unique tangent values $-\infty$ se $\infty$ tak contain karta hai. Endpoints ko exclude karta hai kyuki $\tan(\pm\frac{\pi}{2})$ undefined hai. |
| $y = \csc^{-1} x$ | $(-\infty, -1] \cup [1, \infty)$ | $[-\frac{\pi}{2}, \frac{\pi}{2}] - \{0\}$           | $\sin^{-1} x$ jaisa hi hai but 0 ko exclude karta hai kyuki $\csc 0$ undefined hai. |
| $y = \sec^{-1} x$ | $(-\infty, -1] \cup [1, \infty)$ | $[0, \pi] - \{\frac{\pi}{2}\}$                  | $\cos^{-1} x$ jaisa hi hai but $\frac{\pi}{2}$ ko exclude karta hai kyuki $\sec(\frac{\pi}{2})$ undefined hai. |
| $y = \cot^{-1} x$ | $\mathbb{R}$                | $(0, \pi)$                                        | $\cos^{-1} x$ jaisa hi hai but endpoints ko exclude karta hai kyuki $\cot(0)$ aur $\cot(\pi)$ undefined hain. |

*   **Memorization Tip:**
    *   **Group 1 (Q4/Q1):** $\sin^{-1}x$, $\tan^{-1}x$, $\csc^{-1}x$ sabki ranges 0 ke around centered hoti hain, negative se positive tak. ($\sin^{-1}$ aur $\tan^{-1}$ odd functions hain).
    *   **Group 2 (Q1/Q2):** $\cos^{-1}x$, $\cot^{-1}x$, $\sec^{-1}x$ sabki ranges 0 se start hoti hain, $\pi$ tak jaati hain. (Yeh negative values ke liye $\pi - \cos^{-1}x$ se relate karti hain).
    *   Exclusions yaad rakho: $\csc^{-1}$ ke liye `0`, $\sec^{-1}$ ke liye `pi/2`, $\cot^{-1}$ ke liye `0` aur `pi` (jahan original functions undefined hote hain).
    *   Domain original trigonometric function ki range se determine hota hai (jaise, sine -1 se 1 tak jaata hai, toh $\sin^{-1}$ ka input $x$ $[-1, 1]$ mein hona chahiye).

### 2.3 Properties of Inverse Trigonometric Functions

Yeh aapke problem-solving tools hain. Har ek ko samjho.

#### a) Inverse Identity Properties (The "Undo" Properties)

*   **Explanation:** Yeh functions ek doosre ko "undo" karte hain, but sirf tab jab input angle `x` (for $\sin^{-1}(\sin x)$) ya value `x` (for $\sin(\sin^{-1} x)$) specified valid range/domain ke andar ho. **Conditions bahut important hain!**

    1.  $\sin^{-1} (\sin x) = x$, **agar $x \in [-\frac{\pi}{2}, \frac{\pi}{2}]$**
        *   **Example:** $\sin^{-1}\left(\sin \frac{\pi}{4}\right) = \frac{\pi}{4}$ (kyuki $\frac{\pi}{4} \in [-\frac{\pi}{2}, \frac{\pi}{2}]$).
        *   **Counter-example:** $\sin^{-1}\left(\sin \frac{3\pi}{4}\right) \neq \frac{3\pi}{4}$ kyuki $\frac{3\pi}{4}$ $[-\frac{\pi}{2}, \frac{\pi}{2}]$ mein nahi hai. Instead, $\sin \frac{3\pi}{4} = \sin (\pi - \frac{\pi}{4}) = \sin \frac{\pi}{4}$. Toh, $\sin^{-1}\left(\sin \frac{3\pi}{4}\right) = \sin^{-1}\left(\sin \frac{\pi}{4}\right) = \frac{\pi}{4}$.
    2.  $\cos^{-1} (\cos x) = x$, **agar $x \in [0, \pi]$**
        *   **Example:** $\cos^{-1}\left(\cos \frac{2\pi}{3}\right) = \frac{2\pi}{3}$ (kyuki $\frac{2\pi}{3} \in [0, \pi]$).
    3.  $\tan^{-1} (\tan x) = x$, **agar $x \in (-\frac{\pi}{2}, \frac{\pi}{2})$**
        *   **Example:** $\tan^{-1}\left(\tan (-\frac{\pi}{6})\right) = -\frac{\pi}{6}$ (kyuki $-\frac{\pi}{6} \in (-\frac{\pi}{2}, \frac{\pi}{2})$).
        *(Similar for $\csc^{-1}, \sec^{-1}, \cot^{-1}$ with their respective ranges)*

    4.  $\sin (\sin^{-1} x) = x$, **agar $x \in [-1, 1]$**
        *   **Example:** $\sin\left(\sin^{-1} \frac{1}{2}\right) = \frac{1}{2}$ (kyuki $\frac{1}{2} \in [-1, 1]$).
    5.  $\cos (\cos^{-1} x) = x$, **agar $x \in [-1, 1]$**
        *   **Example:** $\cos\left(\cos^{-1} (-0.8)\right) = -0.8$ (kyuki $-0.8 \in [-1, 1]$).
    6.  $\tan (\tan^{-1} x) = x$, **agar $x \in \mathbb{R}$**
        *   **Example:** $\tan\left(\tan^{-1} 5\right) = 5$ (kyuki $5 \in \mathbb{R}$).
        *(Similar for $\csc, \sec, \cot$ with their respective domains)*

*   **Memorization Tip:** $\text{Inv}(\text{Trig}(x))=x$ ke liye condition *inverse function ki range* hai. $\text{Trig}(\text{Inv}(x))=x$ ke liye condition *inverse function ka domain* hai.

#### b) Negative Argument Properties (Negative inputs ko efficiently handle kaise karein)

*   **Explanation:** Yeh batate hain ki inverse functions ke andar negative values se kaise deal karna hai. Do groups notice karo.

    **Group 1 (Odd Functions - Bas negative ko bahar nikal lo):**
    1.  $\sin^{-1} (-x) = -\sin^{-1} x$, for $x \in [-1, 1]$
        *   **Example:** $\sin^{-1}\left(-\frac{1}{2}\right) = -\sin^{-1}\left(\frac{1}{2}\right) = -\frac{\pi}{6}$.
    2.  $\tan^{-1} (-x) = -\tan^{-1} x$, for $x \in \mathbb{R}$
        *   **Example:** $\tan^{-1}(-\sqrt{3}) = -\tan^{-1}(\sqrt{3}) = -\frac{\pi}{3}$.
    3.  $\csc^{-1} (-x) = -\csc^{-1} x$, for $|x| \ge 1$
        *   **Example:** $\csc^{-1}(-2) = -\csc^{-1}(2) = -\frac{\pi}{6}$.

    **Group 2 ($\pi$ use karta hai kyuki unki principal range $[0, \pi]$ hai):**
    4.  $\cos^{-1} (-x) = \pi - \cos^{-1} x$, for $x \in [-1, 1]$
        *   **Example:** $\cos^{-1}\left(-\frac{1}{2}\right) = \pi - \cos^{-1}\left(\frac{1}{2}\right) = \pi - \frac{\pi}{3} = \frac{2\pi}{3}$.
    5.  $\sec^{-1} (-x) = \pi - \sec^{-1} x$, for $|x| \ge 1$
        *   **Example:** $\sec^{-1}(-2) = \pi - \sec^{-1}(2) = \pi - \frac{\pi}{3} = \frac{2\pi}{3}$.
    6.  $\cot^{-1} (-x) = \pi - \cot^{-1} x$, for $x \in \mathbb{R}$
        *   **Example:** $\cot^{-1}(-1) = \pi - \cot^{-1}(1) = \pi - \frac{\pi}{4} = \frac{3\pi}{4}$.

*   **Memorization Tip:** Woh functions jinki principal value branches mein negative angles shamil hote hain ($\sin^{-1}$, $\tan^{-1}$, $\csc^{-1}$) simply negative sign ko bahar nikal dete hain. Woh functions jinki principal value branches poori tarah non-negative hoti hain ($\cos^{-1}$, $\sec^{-1}$, $\cot^{-1}$) $\pi - \dots$ form use karte hain.

#### c) Reciprocal Identities (Reciprocal functions ke beech convert karna)

*   **Explanation:** Yeh aapko inverse function aur uske reciprocal ke inverse ke beech switch karne mein help karte hain.

    1.  $\sin^{-1} x = \csc^{-1} \left(\frac{1}{x}\right)$, if $x \in (0, 1]$ or $[-1, 0)$
        *   **Example:** $\sin^{-1}\left(\frac{1}{2}\right) = \csc^{-1}(2) = \frac{\pi}{6}$.
    2.  $\cos^{-1} x = \sec^{-1} \left(\frac{1}{x}\right)$, if $x \in (0, 1]$ or $[-1, 0)$
        *   **Example:** $\cos^{-1}\left(\frac{\sqrt{3}}{2}\right) = \sec^{-1}\left(\frac{2}{\sqrt{3}}\right) = \frac{\pi}{6}$.
    3.  $\tan^{-1} x = \cot^{-1} \left(\frac{1}{x}\right)$, if $x > 0$
        *   **Example:** $\tan^{-1}(\sqrt{3}) = \cot^{-1}\left(\frac{1}{\sqrt{3}}\right) = \frac{\pi}{3}$.
        *(For $x < 0$, $\tan^{-1} x = \cot^{-1} (\frac{1}{x}) - \pi$)*

*   **Memorization Tip:** "$\frac{1}{x}$" intuitive hai. Conditions ka dhyaan rakho, especially $\tan^{-1}/\cot^{-1}$ ke liye jab $x$ negative ho. Zyada tar basic problems ke liye, $x>0$ assume kiya jaata hai.

#### d) Complementary Angle Properties ($\frac{\pi}{2}$ mein sum hota hai)

*   **Explanation:** Yeh basic trigonometry mein complementary angles ($sin(90^\circ - \theta) = \cos \theta$) ke analogous hain.

    1.  $\sin^{-1} x + \cos^{-1} x = \frac{\pi}{2}$, if $x \in [-1, 1]$
        *   **Example:** $\sin^{-1}\left(\frac{1}{2}\right) + \cos^{-1}\left(\frac{1}{2}\right) = \frac{\pi}{6} + \frac{\pi}{3} = \frac{3\pi}{6} = \frac{\pi}{2}$.
    2.  $\tan^{-1} x + \cot^{-1} x = \frac{\pi}{2}$, if $x \in \mathbb{R}$
        *   **Example:** $\tan^{-1}(1) + \cot^{-1}(1) = \frac{\pi}{4} + \frac{\pi}{4} = \frac{2\pi}{4} = \frac{\pi}{2}$.
    3.  $\csc^{-1} x + \sec^{-1} x = \frac{\pi}{2}$, if $|x| \ge 1$
        *   **Example:** $\csc^{-1}(2) + \sec^{-1}(2) = \frac{\pi}{6} + \frac{\pi}{3} = \frac{3\pi}{6} = \frac{\pi}{2}$.

*   **Memorization Tip:** Bas pairs yaad rakho: (sin, cos), (tan, cot), (csc, sec) ka sum $\pi/2$ hota hai.

#### e) Sum/Difference & Double Angle Formulas (Especially for $\tan^{-1}$)

*   **Explanation:** Yeh kuch sabse zyada use hone wale formulas hain simplification aur equations solve karne ke liye. $2\tan^{-1}x$ formulas particularly versatile hain.

    1.  $\tan^{-1} x + \tan^{-1} y = \tan^{-1} \left(\frac{x+y}{1-xy}\right)$, if $xy < 1$
        *   **Example:** $\tan^{-1}\left(\frac{1}{2}\right) + \tan^{-1}\left(\frac{1}{3}\right) = \tan^{-1}\left(\frac{\frac{1}{2}+\frac{1}{3}}{1-\frac{1}{2}\cdot\frac{1}{3}}\right) = \tan^{-1}\left(\frac{\frac{5}{6}}{1-\frac{1}{6}}\right) = \tan^{-1}\left(\frac{\frac{5}{6}}{\frac{5}{6}}\right) = \tan^{-1}(1) = \frac{\pi}{4}$.
    2.  $\tan^{-1} x - \tan^{-1} y = \tan^{-1} \left(\frac{x-y}{1+xy}\right)$, if $xy > -1$
        *   **Example:** $\tan^{-1}(1) - \tan^{-1}\left(\frac{1}{2}\right) = \tan^{-1}\left(\frac{1-\frac{1}{2}}{1+1\cdot\frac{1}{2}}\right) = \tan^{-1}\left(\frac{\frac{1}{2}}{\frac{3}{2}}\right) = \tan^{-1}\left(\frac{1}{3}\right)$.
    3.  $2\tan^{-1} x = \tan^{-1} \left(\frac{2x}{1-x^2}\right)$, if $|x| < 1$
        *   **Example:** $2\tan^{-1}\left(\frac{1}{3}\right) = \tan^{-1}\left(\frac{2(\frac{1}{3})}{1-(\frac{1}{3})^2}\right) = \tan^{-1}\left(\frac{\frac{2}{3}}{1-\frac{1}{9}}\right) = \tan^{-1}\left(\frac{\frac{2}{3}}{\frac{8}{9}}\right) = \tan^{-1}\left(\frac{2}{3} \times \frac{9}{8}\right) = \tan^{-1}\left(\frac{3}{4}\right)$.
    4.  $2\tan^{-1} x = \sin^{-1} \left(\frac{2x}{1+x^2}\right)$, if $|x| \le 1$
        *   **Example:** $2\tan^{-1}(1) = \sin^{-1}\left(\frac{2(1)}{1+1^2}\right) = \sin^{-1}\left(\frac{2}{2}\right) = \sin^{-1}(1) = \frac{\pi}{2}$. (Also $2\tan^{-1}(1) = 2 \times \frac{\pi}{4} = \frac{\pi}{2}$).
    5.  $2\tan^{-1} x = \cos^{-1} \left(\frac{1-x^2}{1+x^2}\right)$, if $x \ge 0$
        *   **Example:** $2\tan^{-1}(1) = \cos^{-1}\left(\frac{1-1^2}{1+1^2}\right) = \cos^{-1}\left(\frac{0}{2}\right) = \cos^{-1}(0) = \frac{\pi}{2}$. (Previous example se match karta hai).

*   **Memorization Tip:**
    *   $\tan^{-1} x + \tan^{-1} y$ ki similarity $\tan(A+B)$ formula se notice karo: $\tan(A+B) = \frac{\tan A + \tan B}{1 - \tan A \tan B}$. Bas $\tan A$ ko $x$, $\tan B$ ko $y$ se replace karo, aur poore expression ke around $\tan^{-1}$ laga do.
    *   $2\tan^{-1}x$ formulas $\tan 2\theta$, $\sin 2\theta$, aur $\cos 2\theta$ ke double angle formulas se link karte hain jab unhe $\tan\theta$ ke terms mein express kiya jaata hai. (e.g., $\sin 2\theta = \frac{2\tan\theta}{1+\tan^2\theta}$). Agar aap $x = \tan\theta$ lete ho, toh yeh nikal aate hain. Is connection ko samajhne se memorization easy ho jaati hai.

---

## Part 3: Proofs/Simplification ke liye Essential Trigonometric Identities

Yeh aapki previous classes se hain but Chapter 2 problems (jaise $3x - 4x^3$ wale) ke liye indispensable hain.

1.  $\sin^2 \theta + \cos^2 \theta = 1$
2.  $1 + \tan^2 \theta = \sec^2 \theta$
3.  $1 + \cot^2 \theta = \csc^2 \theta$
4.  $\sin 2\theta = 2\sin\theta\cos\theta$
5.  $\cos 2\theta = \cos^2\theta - \sin^2\theta = 2\cos^2\theta - 1 = 1 - 2\sin^2\theta$
6.  $\tan 2\theta = \frac{2\tan\theta}{1-\tan^2\theta}$
7.  **Is chapter ke liye Critical:**
    *   $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$
    *   $\cos 3\theta = 4\cos^3\theta - 3\cos\theta$
    *   $\tan 3\theta = \frac{3\tan\theta - \tan^3\theta}{1-3\tan^2\theta}$

*   **Memorization Tip:** $3\theta$ formulas thode kam intuitive hain. Inhe baar-baar likho. $\sin 3\theta$ ke liye, "3 sine, 4 sine cubed" (34 pattern) socho. $\cos 3\theta$ ke liye, "4 cosine cubed, 3 cosine" (43 pattern) socho.

---

## Part 4: Problems ko Approach kaise karein aur "Socho" konsi Value use karni hai

### 1. **Principal Values find karna (e.g., $\sin^{-1}(-\frac{1}{2})$)**

*   **Step 1: Goal samjho.** Aap ek *angle* find kar rahe ho.
*   **Step 2: Negative ko ignore karo (ek moment ke liye).** "Kis angle ka sine $\frac{1}{2}$ hota hai?" (Apni memorized table se: $\frac{\pi}{6}$ ya $30^\circ$).
*   **Step 3: Specific function ke liye Principal Value Range check karo.** $\sin^{-1}$ ke liye, yeh $[-\frac{\pi}{2}, \frac{\pi}{2}]$ hai.
*   **Step 4: Negative Argument Property apply karo (agar zarurat ho).**
    *   $\sin^{-1}$, $\tan^{-1}$, $\csc^{-1}$ ke liye: Agar input negative hai, toh bas Step 2 mein jo angle mila hai uske saamne negative sign laga do.
        *   Example: $\sin^{-1}(-\frac{1}{2}) = -\sin^{-1}(\frac{1}{2}) = -\frac{\pi}{6}$. Check: $-\frac{\pi}{6}$ $[-\frac{\pi}{2}, \frac{\pi}{2}]$ mein hai. Correct!
    *   $\cos^{-1}$, $\sec^{-1}$, $\cot^{-1}$ ke liye: Agar input negative hai, toh $\pi - (\text{angle from Step 2})$ rule use karo.
        *   Example: $\cos^{-1}(-\frac{1}{2})$. $+\frac{1}{2}$ ke liye angle $\frac{\pi}{3}$ hai. Toh, $\cos^{-1}(-\frac{1}{2}) = \pi - \cos^{-1}(\frac{1}{2}) = \pi - \frac{\pi}{3} = \frac{2\pi}{3}$. Check: $\frac{2\pi}{3}$ $[0, \pi]$ mein hai. Correct!
*   **Step 5: HAMESHA Verify karo.** Kya aapka final angle us inverse function ki specified Principal Value Branch mein aata hai?

### 2. **Expressions ko simplify karna / Proofs (e.g., $3 \sin^{-1} x = \sin^{-1} (3x - 4x^3)$)**

*   **Step 1: Inverse function ke andar algebraic structure dekho.** Kya aapko $2x/(1-x^2)$, $3x-4x^3$, $4x^3-3x$ jaise patterns dikhte hain?
*   **Step 2: (Non-inverse) trigonometric identities se connect karo.**
    *   Agar aapko $3x-4x^3$ dikhta hai, toh $\sin 3\theta = 3\sin\theta - 4\sin^3\theta$ socho. Isse suggest hota hai ki $x = \sin\theta$ substitution karein.
    *   Agar aapko $4x^3-3x$ dikhta hai, toh $\cos 3\theta = 4\cos^3\theta - 3\cos\theta$ socho. Isse suggest hota hai ki $x = \cos\theta$.
    *   Agar aapko $2x/(1-x^2)$ dikhta hai, toh $\tan 2\theta = 2\tan\theta / (1-\tan^2\theta)$ socho. Isse suggest hota hai ki $x = \tan\theta$.
    *   Agar aapko $\sqrt{1-x^2}$ ya similar radicals dikhte hain, toh Pythagorean identities ke baare mein socho, jo $x=\sin\theta$ ya $x=\cos\theta$ suggest kar sakte hain (e.g., $\sqrt{1-\sin^2\theta} = \cos\theta$).
*   **Step 3: Substitution karo.** $x$ ko $\theta$ ke appropriate trig function ke equal mano. Iska matlab $\theta$ $x$ ka inverse trig function hoga.
*   **Step 4: Trigonometric identities use karke expression ko simplify karo.**
*   **Step 5: Inverse Identity Property apply karo (e.g., $\sin^{-1}(\sin A) = A$).** **Critically, is property ke valid hone ki condition check karo.** Isme usually yeh ensure karna hota hai ki angle ($A$) outer inverse function ki principal value branch mein ho. Problem statement often $x$ ke liye ek domain provide karega jo isse ensure karega.
*   **Step 6: Wapas substitute karo.** $\theta$ ko uske inverse trig function equivalent terms of $x$ se replace karo.

---

## 🚀 General Memorization Strategies:

1.  **Active Recall:** Sirf dobara mat padho. Khud ko test karo. Definitions/properties ko cover karke memory se likhne ki koshish karo. Individual properties ke liye flashcards use karo.
2.  **Spaced Repetition:** Material ko multiple times, badhte hue intervals par review karo (jaise, 1 ghante baad, phir 1 din baad, phir 3 din baad, phir ek week baad).
3.  **Practice Problems:** Properties ko memorize karne ka sabse achha tarika hai unhe *use karna*. Apni NCERT textbook ke har example aur exercise ko solve karo. Jab अटक जाओ, property dekho, phir dobara try karo.
4.  **Kisi Aur Ko Padhao (ya khud ko!):** Ek imaginary student (ya real one!) ko concept bol kar samjhane se aapke thoughts organize hote hain aur aap apni understanding mein gaps identify kar paate ho.
5.  **Visualize:** Inverse functions ke graphs draw karo (even rough sketches) unke domains aur ranges dekhne ke liye. ASTC rule ko visualize karo.
6.  **Ek "Summary" Sheet banao:** Is detailed sheet ko study karne ke baad, apni khud ki, zyada concise summary sheet memory se banane ki koshish karo. Yeh ek powerful review tool ka kaam karegi.
7.  **Connections Identify karo:** Samjho ki properties *kyu* aisi hain (jaise, $2\tan^{-1}x$ double angle formulas se kaise relate karta hai). Yeh pure rote memorization ko kam karta hai.
8.  **Proofs se mat daro:** Proofs fantastic hote hain yeh dikhane ke liye ki properties kaise derive aur use ki jaati hain. Woh deeper understanding build karte hain.

Ab aapke paas ek clear path hai. Ek-ek step lo. Aap is chapter mein master kar sakte ho! All the best for your exam!Ab aapke paas ek clear path hai. Ek-ek step lo. Aap is chapter mein master kar sakte ho! All the best for your exam!