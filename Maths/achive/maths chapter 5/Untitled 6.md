# 📚 NCERT Class 12 Mathematics: Chapter 5 - Continuity and Differentiability (Bilkul Shuru Se!)

## 🙏 Introduction: Aao Milkar Seekhen!

Namaste dobara! Jab koi naya chapter shuru karte hain, khaaskar Calculus jaisa, toh thoda mushkil lagna normal hai. Puraani classes ke kuch concepts agar thode weak hon toh aur bhi lag sakta hai. Magar bilkul chinta mat karo! Hum ek-ek kadam aage badhenge, bilkul basic se shuru karenge, aur tumhari understanding build karenge. Mujhe apna guide samjho.

Hum sabse pehle **Limits** ki baat karenge, jo continuity aur differentiability ki foundation hai. Jab tumhe limits samajh aa jayegi, toh baaki sab apne aap easy lagne lagega.

Yeh rahi tumhare liye revised lesson, Obsidian Markdown format mein, jo fundamental concepts par focus karti hai:

---

## 🏗️ 0. Foundation: Limits Ko Samjho (Class 11 se Yaad Karen)

Chapter 5 mein jaane se pehle, chalo jaldi se "Limits" ko revise karte hain, kyunki continuity aur differentiability poori tarah se isi idea par based hain.

### 🚶 Limit Kya Hai? (Ek Example Se Samjho)

Imagine karo tum ek raaste par ek khaas point ki taraf chal rahe ho.

*   **Tum left side se us point ki taraf chal rahe ho.** Jab tum us point tak pahunchoge, toh tum *kahaan hone ki ummeed* kar rahe ho? Yeh hai tumhara **Left-Hand Limit (LHL)**.
*   **Tum right side se usi point ki taraf chal rahe ho.** Ab tum *kahaan hone ki ummeed* kar rahe ho? Yeh hai tumhara **Right-Hand Limit (RHL)**.
*   **Limit Tab Exist Karti Hai** jab, tum chahe left se aao ya right se (LHL ho ya RHL), tum *ek hi expected spot* ki taraf jaa rahe ho. Isse farak nahi padta ki tum us spot par actually pahunche ya wahaan koi hole hai; bas yeh matter karta hai ki tum *kahaan jaa rahe ho*.

Mathematically, ek function $f(x)$ ke liye, $x$ jab $c$ ko approach karta hai, toh limit ($\lim_{x \to c} f(x)$ likhte hain) tabhi exist karti hai agar:
$$ \lim_{x \to c^-} f(x) = \lim_{x \to c^+} f(x) $$
Jahaan $x \to c^-$ ka matlab hai $c$ se chhoti values se $c$ ki taraf aana, aur $x \to c^+$ ka matlab hai $c$ se badi values se $c$ ki taraf aana.

### 💡 Simple Example:

Function $f(x) = x+2$ ko dekho.
Chalo dekhte hain jab $x$, $3$ ko approach karta hai.

*   **Left side se ($x \to 3^-$):**
    *   Agar $x=2.9$ hai, toh $f(x) = 2.9+2 = 4.9$
    *   Agar $x=2.99$ hai, toh $f(x) = 2.99+2 = 4.99$
    *   Agar $x=2.999$ hai, toh $f(x) = 2.999+2 = 4.999$
    Lag raha hai ki hum $5$ ki taraf jaa rahe hain. Toh, $\lim_{x \to 3^-} (x+2) = 5$.

*   **Right side se ($x \to 3^+$):**
    *   Agar $x=3.1$ hai, toh $f(x) = 3.1+2 = 5.1$
    *   Agar $x=3.01$ hai, toh $f(x) = 3.01+2 = 5.01$
    *   Agar $x=3.001$ hai, toh $f(x) = 3.001+2 = 5.001$
    Yeh bhi lag raha hai ki hum $5$ ki taraf jaa rahe hain. Toh, $\lim_{x \to 3^+} (x+2) = 5$.

Kyunki LHL aur RHL dono $5$ hain, hum kehte hain $\lim_{x \to 3} (x+2) = 5$.

---

## 🔗 1. Continuity: "Kahin Toot-phoot Na Ho, Uchhal-kood Na Ho, Ched Na Ho"

Ab jab humein limits samajh aa gayi hain, toh hum Continuity ki baat kar sakte hain. Yahaan tumhari 'pen-on-paper' wali analogy kaam aayegi!

### 📝 Ek function continuous kab hota hai?

Ek function **ek point par continuous** tab hota hai agar uske graph ko us point se bina pen uthaye draw kiya jaa sake. Us khaas point par **na koi break hona chahiye, na koi jump, aur na hi koi hole**.

Mathematically, agar $f(x)$ function $x=c$ point par continuous hai, toh uske liye **teen conditions** poori honi chahiye:

1.  **Function us point par define hona chahiye:** $f(c)$ defined ho. (Us point par koi hole na ho).
2.  **Limit us point par exist karni chahiye:** $\lim_{x \to c} f(x)$ exist kare. (LHL aur RHL dono ek hi expected value par jaayen, matlab koi jump ya break na ho jahaan parts meet na kar rahe hon).
3.  **Limit ki value function ki value ke barabar honi chahiye:** $\lim_{x \to c} f(x) = f(c)$. (Expected value hi actual value ho, iska matlab na hole ho aur na jump).

Agar in teenon mein se koi bhi condition fail ho jaati hai, toh function $x=c$ par **discontinuous** hai.

### 💡 Example 1: Ek Continuous Function (Ex 5.1, Q1 se) [1]

Chalo, ek bilkul simple function lete hain: $f(x) = 5x - 3$. Hamein check karna hai ki kya yeh $x = 0$ par continuous hai.

**_Solution:_**
Chalo $x=0$ ke liye teen conditions check karte hain:

1.  **Kya $f(0)$ defined hai?**
    $f(0) = 5(0) - 3 = -3$. Haan, defined hai.

2.  **Kya $\lim_{x \to 0} f(x)$ exist karti hai?**
    Kyunki $f(x) = 5x-3$ ek simple straight line (polynomial) hai, iski limit direct value daal kar mil jaati hai:
    $\lim_{x \to 0} (5x - 3) = 5(0) - 3 = -3$. Haan, exist karti hai.

3.  **Kya $\lim_{x \to 0} f(x) = f(0)$ hai?**
    (2) se, $\lim_{x \to 0} f(x) = -3$.
    (1) se, $f(0) = -3$.
    Kyunki $-3 = -3$, haan, barabar hain!

Tino conditions poori ho gayi hain. Toh, $f(x) = 5x - 3$ **$x = 0$ par continuous hai**.

Tum is line ko $x=0$ se bina pen uthaye draw kar sakte ho.

### 💡 Example 2: Ek Discontinuous Function (Ex 5.1, Q5 se) [1]

Chalo ek function dekhte hain jo apna rule badalta hai:
$f(x) = \begin{cases} x, & \text{agar } x \le 1 \\ 5, & \text{agar } x > 1 \end{cases}$

Hamein check karna hai ki kya yeh $x = 1$ par continuous hai. Yeh "critical point" hai jahaan function ki definition badalti hai.

**_Solution:_**
Chalo $x=1$ ke liye teen conditions check karte hain:

1.  **Kya $f(1)$ defined hai?**
    Jab $x=1$ hai, toh pehla rule apply hota hai ($x \le 1$), toh $f(x)=x$.
    $f(1) = 1$. Haan, defined hai.

2.  **Kya $\lim_{x \to 1} f(x)$ exist karti hai?**
    Critical points par limits ke liye, humein LHL aur RHL alag se check karna padta hai.
    *   **LHL ($\lim_{x \to 1^-} f(x)$):** Hum $x=1$ ko *1 se chhoti values* se approach kar rahe hain. Toh, hum $f(x) = x$ wala rule use karenge.
        $\lim_{x \to 1^-} x = 1$.
    *   **RHL ($\lim_{x \to 1^+} f(x)$):** Hum $x=1$ ko *1 se badi values* se approach kar rahe hain. Toh, hum $f(x) = 5$ wala rule use karenge.
        $\lim_{x \to 1^+} 5 = 5$.

    Kyunki LHL ($1$) $\neq$ RHL ($5$), toh limit $\lim_{x \to 1} f(x)$ **exist nahi karti**.

Kyunki doosri condition fail ho gayi, humein teesri check karne ki zaroorat hi nahi hai! Function $f(x)$ **$x=1$ par continuous nahi hai**. Graph mein $x=1$ par ek "jump" hai.

---

## 📈 2. Differentiability: "Smoothness" (Chiknapan)

Ab, differentiability par chalte hain. Yeh concept continuity se closely related hai, par yeh ek aur layer add karta hai: **smoothness** (chiknapan).

### 📝 Ek function differentiable kab hota hai?

Ek function **ek point par differentiable** tab hota hai agar us point par uski graph ki *ek well-defined aur unique tangent line* ho.

Isko aise samjho:
*   **Continuous** ka matlab hai ki tum bina pen uthaye draw kar sakte ho.
*   **Differentiable** ka matlab hai ki tum bina pen uthaye draw kar sakte ho *aur* usmein koi sharp corners (nokile kone) ya kinks (mod) nahi hain. Yeh smooth hai!

Agar graph mein koi sharp corner hai (jaise pahad ki choti, ya absolute value function $f(x)=|x|$ ka point $x=0$ par), toh tum wahaan par *ek hi, unique* tangent line nahi bana sakte. Tum wahaan kai lines draw kar sakte ho jo us point ko touch karengi. Isliye, us sharp corner par function differentiable nahi hota.

### ↔️ Bada Rishta: Continuity aur Differentiability Ke Beech

Yeh ek bahut important rule hai:

**Agar ek function ek point par differentiable hai, toh woh us point par continuous BHI hoga.**
(Agar woh smooth hai, toh usmein breaks ya jumps toh honge hi nahi!)

**Lekin, iska ulta SACH nahi hai!**
Ek function continuous ho sakta hai par ek point par differentiable NAHI.
(Usko bina pen uthaye draw kiya jaa sakta hai, par ho sakta hai usmein koi sharp corner ho, jiske karan woh smooth na ho).

**Example:** Function $f(x) = |x|$ $x=0$ par continuous hai (tum usko bina pen uthaye draw kar sakte ho). Lekin $x=0$ par, usmein ek sharp corner hai, isliye woh $x=0$ par **differentiable nahi hai**.

### 📝 "Derivative" Kaise Nikalte Hain?

"Derivative" (jisko $f'(x)$ ya $\frac{dy}{dx}$ se denote karte hain) function ke graph par kisi bhi point $x$ par **tangent line ki slope** ko represent karta hai. Yeh humein function ke instantaneous rate of change (tatkaalik badlav ki dar) ke baare mein batata hai.

Class 11 mein tumne kuch basic differentiation formulas seekhe the. Chalo jaldi se power rule ko yaad karte hain, jo bahut common hai:
Agar $f(x) = x^n$ hai, toh $f'(x) = n x^{n-1}$.

**Example:** Agar $f(x) = x^2$ hai, toh $f'(x) = 2x^{2-1} = 2x$.
Iska matlab hai ki kisi bhi point $x$ par, $y=x^2$ ki tangent ki slope $2x$ hai.

### ⚙️ Differentiation Rules (Jaldi se Yaad Karen)

*   **Constant Rule:** $\frac{d}{dx}(c) = 0$ (jaise, $\frac{d}{dx}(5)=0$)
*   **Power Rule:** $\frac{d}{dx}(x^n) = nx^{n-1}$ (jaise, $\frac{d}{dx}(x^3)=3x^2$)
*   **Constant Multiple Rule:** $\frac{d}{dx}(cf(x)) = c \frac{d}{dx}(f(x))$ (jaise, $\frac{d}{dx}(3x^2)=3(2x)=6x$)
*   **Sum/Difference Rule:** $\frac{d}{dx}(f(x) \pm g(x)) = \frac{d}{dx}(f(x)) \pm \frac{d}{dx}(g(x))$ (jaise, $\frac{d}{dx}(x^2+x)=2x+1$)
*   **Basic Trig Functions ke Derivatives:**
    *   $\frac{d}{dx}(\sin x) = \cos x$
    *   $\frac{d}{dx}(\cos x) = -\sin x$
    *   $\frac{d}{dx}(\tan x) = \sec^2 x$

#### 🎯 Exercise 5.2 Questions (Selected) [1]

Chalo, ek bahut basic derivative problem try karte hain.

#### Question 1. Is function ko $x$ ke respect mein differentiate karo: $\sin(x^2 + 5)$ [1]

**_Explanation:_** Yeh thoda complex function hai. Yeh ek "function ke andar function" hai. Yahin par **Chain Rule** kaam aata hai.

**Chain Rule Analogy:** Russian doll (Matryoshka doll) imagine karo. Usko kholne ke liye, pehle sabse bahar wali doll ko kholte ho, fir uske andar wali ko, aur aise hi.
Vaise hi, $f(g(x))$ ke liye, pehle *outer* function $f$ ko differentiate karte ho, *inner* function $g(x)$ ko waise hi rakhte ho. Fir, usko *inner* function $g(x)$ ke derivative se multiply karte ho.

Formula: Agar $y = f(g(x))$, toh $\frac{dy}{dx} = f'(g(x)) \cdot g'(x)$.

**_Solution:_**
Maana $y = \sin(x^2 + 5)$.
Yahaan, **outer function** hai $\sin(\text{kuchh})$, aur **inner function** hai $\text{kuchh} = x^2 + 5$.

1.  **Outer function ko differentiate karo:** $\sin(\text{stuff})$ ka derivative $\cos(\text{stuff})$ hota hai.
    Toh, $\frac{d}{d(\text{inner})}(\sin(\text{inner})) = \cos(\text{inner}) = \cos(x^2 + 5)$.

2.  **Inner function ko differentiate karo:** $(x^2 + 5)$ ka $x$ ke respect mein derivative hai:
    $\frac{d}{dx}(x^2 + 5) = 2x + 0 = 2x$.

3.  **Results ko multiply karo:**
    $\frac{dy}{dx} = \cos(x^2 + 5) \cdot (2x)$
    $\frac{dy}{dx} = 2x \cos(x^2 + 5)$

Yeh hai Chain Rule kaam karte hue! Yeh is chapter mein sabse important differentiation rules mein se ek hai.

---

## 🚀 Aage Badhte Hain: Apni Skills Banayen

Humne abhi bas shuru kiya hai, par yeh critical initial steps hain.

**Abhi tumhe in baaton par focus karna chahiye:**

1.  **Limits ko dobara dekho:** Sure ho jao ki tumhe left aur right se kisi point ko approach karne ka idea clear hai.
2.  **Continuity conditions practice karo:** Simple functions (polynomials, piecewise) lo aur specific points par continuity ki teen conditions check karo. Samjho ki koi function discontinuous *kyun* ho sakta hai (hole, jump, break).
3.  **Differentiability ko conceptually samjho:** "Smoothness" aur "unique tangent line". Yeh link yaad rakho: Differentiable $\implies$ Continuous.
4.  **Basic Derivatives practice karo:** Sure ho jao ki tum simple polynomials aur trigonometric functions ko differentiate kar sakte ho.
5.  **Chain Rule ko samjho:** Yeh tumhari pehli major nayi differentiation technique hai. Ise alag-alag function combinations ke saath practice karo.

Ek saath sab kuch yaad karne ki koshish mat karo. Pehle continuity aur differentiability ka *matlab* samajhne par focus karo. Fir hum dheere-dheere implicit functions, logarithmic differentiation, parametric forms, aur higher-order derivatives ko tackle karenge.

**Tumhara agla step hona chahiye Exercise 5.1 aur 5.2 se kuch aur questions ko try karna, continuity ki conditions check karne aur chain rule apply karne par focus karte hue.**

Kaisa laga yeh? Kya yeh foundational explanations cheezein thoda aur clear karne mein help kar rahi hain? Please batao kya abhi bhi confusing lag raha hai, aur hum use kisi aur tareeke se samjhenge! Tumne clarify karne ko kaha, bahut acchi baat hai.

# 📚 NCERT Class 12 Mathematics: Chapter 5 - Continuity and Differentiability (Part 2)

## 🙏 Recapturing: Pichle Session Ki Yaadein

Pichle session mein humne dekha:
*   **Limits:** Kahaan jaa rahe hain jab kisi point ko approach karte hain. LHL = RHL hona chahiye.
*   **Continuity:** Bina pen uthaye graph banana. 3 conditions: $f(c)$ defined ho, limit exist kare, aur dono barabar hon.
*   **Differentiability:** Smooth graph, sharp corners (nokile kone) na hon. Agar differentiable hai toh continuous zaroor hoga.
*   **Chain Rule:** Function ke andar function ko differentiate karna. Pehle bahar wala, fir andar wala, aur multiply karo.

Ab, hum kuch aur zaroori differentiation techniques seekhenge jo tumhe bade aur complex functions ko solve karne mein help karengi.

---

## 👻 2.3. Derivatives of Implicit Functions (Chupe Hue Functions Ka Derivative)

**Implicit Function kya hota hai?**
Abhi tak humne jo functions dekhe, unmein $y$ ko $x$ ki terms mein clear cut likha hota tha, jaise $y = x^2 + \sin x$. Isko **Explicit Function** kehte hain.
Lekin, kuch functions aise hote hain jahaan $y$ ko seedhe-seedhe $x$ ki terms mein alag karke nahi likha jaa sakta, jaise $x^2 + y^2 = 25$ (yeh circle ki equation hai). Yahaan $y$ aur $x$ aapas mein "ghule-mile" hain. Aise functions ko **Implicit Functions** kehte hain.

**Kaise differentiate karte hain?**
Implicit functions ko differentiate karne ke liye, hum equation ke dono sides ko $x$ ke respect mein differentiate karte hain. Jab bhi hum $y$ wale term ko differentiate karte hain, toh yaad rakho ki $y$ bhi $x$ ka function hai. Isliye, Chain Rule lagana padta hai aur $\frac{dy}{dx}$ ko multiply karna padta hai.

**Steps:**
1.  Equation ke dono sides ko $x$ ke respect mein differentiate karo.
2.  Har $y$ term ko differentiate karte waqt, $\frac{dy}{dx}$ multiply karna mat bhoolna. (Jaise $\frac{d}{dx}(y^2) = 2y \cdot \frac{dy}{dx}$).
3.  Saare terms jinmein $\frac{dy}{dx}$ hai, unhein ek side le aao aur baakiyon ko doosri side.
4.  $\frac{dy}{dx}$ common lo aur uski value nikaalo.

#### 🎯 Exercise 5.3 Questions (Selected) [1]

#### Question 1. $\frac{dy}{dx}$ nikalo: $2x + 3y = \sin x$ [1]

**_Explanation:_** Yahaan $y$ seedhe $x$ ke terms mein nahi hai, toh yeh ek implicit function hai. Hum har term ko differentiate karenge.

**_Solution:_**
Hamein diya gaya hai $2x + 3y = \sin x$.
Dono sides ko $x$ ke respect mein differentiate karte hain:
$\frac{d}{dx}(2x) + \frac{d}{dx}(3y) = \frac{d}{dx}(\sin x)$

Term-by-term solve karte hain:
*   $\frac{d}{dx}(2x) = 2 \cdot \frac{d}{dx}(x) = 2 \cdot 1 = 2$.
*   $\frac{d}{dx}(3y) = 3 \cdot \frac{d}{dx}(y)$. Kyunki $y$, $x$ ka function hai, iska derivative $3 \frac{dy}{dx}$ hoga.
*   $\frac{d}{dx}(\sin x) = \cos x$.

Toh equation ban jaayegi:
$2 + 3 \frac{dy}{dx} = \cos x$

Ab, $\frac{dy}{dx}$ wale term ko ek taraf rakho aur baakiyon ko doosri taraf:
$3 \frac{dy}{dx} = \cos x - 2$

Aur finally, $\frac{dy}{dx}$ ki value:
$\frac{dy}{dx} = \frac{\cos x - 2}{3}$

Easy tha na? Bas Chain Rule yaad rakhna hai jab $y$ ko differentiate kar rahe ho.

---

## 🔄 2.4. Derivatives of Inverse Trigonometric Functions (Inverse Trig Functions Ke Derivatives)

Inverse Trigonometric functions jaise $\sin^{-1} x$, $\cos^{-1} x$, $\tan^{-1} x$, etc. ke derivatives bhi hote hain. Inke formulas ko yaad rakhna bahut zaroori hai.

**Basic Formulas (Remember These!):**
*   $\frac{d}{dx}(\sin^{-1} x) = \frac{1}{\sqrt{1-x^2}}$
*   $\frac{d}{dx}(\cos^{-1} x) = -\frac{1}{\sqrt{1-x^2}}$
*   $\frac{d}{dx}(\tan^{-1} x) = \frac{1}{1+x^2}$
*   $\frac{d}{dx}(\cot^{-1} x) = -\frac{1}{1+x^2}$
*   $\frac{d}{dx}(\sec^{-1} x) = \frac{1}{|x|\sqrt{x^2-1}}$
*   $\frac{d}{dx}(\csc^{-1} x) = -\frac{1}{|x|\sqrt{x^2-1}}$

Jab complex inverse trigonometric functions aayein, toh unhein seedhe differentiate karne ki jagah, **substitution (प्रतिस्थापन)** use karke simplify karna smarter approach hai. Isse differentiation bahut easy ho jaata hai.

#### 🎯 Exercise 5.3 Questions (Selected) [1]

#### Question 9. $\frac{dy}{dx}$ nikalo: $y = \sin^{-1} \left(\frac{2x}{1+x^2}\right)$ [1]

**_Explanation:_** Agar hum isko seedhe differentiate karenge toh Chain Rule bahut mushkil ho jaayega. $\sin^{-1}(\text{stuff})$ ka derivative toh $\frac{1}{\sqrt{1-(\text{stuff})^2}} \cdot \frac{d}{dx}(\text{stuff})$ hoga. "Stuff" yahaan $\frac{2x}{1+x^2}$ hai, jiska derivative nikalna complicated hai.

Toh, hum yahaan **trigonometric substitution** use karenge. Expression $\frac{2x}{1+x^2}$ ko dekho, yeh trigonometry ke kisi formula jaisa lag raha hai. Yaad karo:
$\sin(2\theta) = \frac{2 \tan \theta}{1+\tan^2 \theta}$
Agar hum $x = \tan \theta$ rakhein, toh yeh simplify ho jaayega!

**_Solution:_**
Hamein diya gaya hai $y = \sin^{-1} \left(\frac{2x}{1+x^2}\right)$.
Let's assume (मानो) $x = \tan \theta$.
Toh, $\theta = \tan^{-1} x$ (yeh baad mein kaam aayega).

Ab $x = \tan \theta$ ko $y$ ke expression mein daalte hain:
$y = \sin^{-1} \left(\frac{2 \tan \theta}{1+\tan^2 \theta}\right)$

Trigonometry ka formula use karte hue, hum jaante hain ki $\frac{2 \tan \theta}{1+\tan^2 \theta} = \sin(2\theta)$.
Toh, $y = \sin^{-1}(\sin(2\theta))$
$\sin^{-1}(\sin A) = A$ hota hai.
So, $y = 2\theta$

Ab, $\theta$ ki value wapas $x$ ki terms mein daalte hain: $\theta = \tan^{-1} x$.
$y = 2 \tan^{-1} x$

Dekha, kitna simple function ban gaya? Ab differentiate karna bahut easy hai:
$\frac{dy}{dx} = \frac{d}{dx}(2 \tan^{-1} x)$
Constant $2$ bahar aa jaayega:
$\frac{dy}{dx} = 2 \cdot \frac{d}{dx}(\tan^{-1} x)$
$\frac{dy}{dx} = 2 \cdot \frac{1}{1+x^2}$
$\frac{dy}{dx} = \frac{2}{1+x^2}$

Substitution ne is problem ko kitna easy bana diya!

---

### 🌲 2.5. Exponential aur Logarithmic Functions Ke Derivatives

Yeh functions bhi bahut common hain, aur inke derivatives bhi yaad hone chahiye:

**Basic Formulas:**
*   $\frac{d}{dx}(e^x) = e^x$ (Sabse easy! $e^x$ ka derivative $e^x$ hi hota hai)
*   $\frac{d}{dx}(a^x) = a^x \log a$ (Jahaan $a$ koi positive constant hai, jaise $2^x$)
*   $\frac{d}{dx}(\log x) = \frac{1}{x}$ (Jahaan $\log x$ ka matlab natural logarithm, i.e., $\ln x$ hai)
*   $\frac{d}{dx}(\log_a x) = \frac{1}{x \log a}$ (Agar base $a$ ho, toh $\log_a x = \frac{\log x}{\log a}$)

Jab bhi division ya multiplication mein functions hon, toh **Quotient Rule** ya **Product Rule** yaad karo.

*   **Product Rule:** If $y = u \cdot v$, then $\frac{dy}{dx} = u \frac{dv}{dx} + v \frac{du}{dx}$.
*   **Quotient Rule:** If $y = \frac{u}{v}$, then $\frac{dy}{dx} = \frac{v \frac{du}{dx} - u \frac{dv}{dx}}{v^2}$.

#### 🎯 Exercise 5.4 Questions (Selected) [1]

#### Question 1. Differentiate karo $x$ ke respect mein: $\frac{e^x}{\sin x}$ [1]

**_Explanation:_** Yahaan do functions division mein hain ($e^x$ aur $\sin x$), toh hum **Quotient Rule** use karenge.
Let $u = e^x$ (numerator) aur $v = \sin x$ (denominator).

**_Solution:_**
Hamein diya gaya hai $y = \frac{e^x}{\sin x}$.
Let $u = e^x$ and $v = \sin x$.

Pehle $u$ aur $v$ ke derivatives nikaalte hain:
*   $\frac{du}{dx} = \frac{d}{dx}(e^x) = e^x$.
*   $\frac{dv}{dx} = \frac{d}{dx}(\sin x) = \cos x$.

Ab Quotient Rule ka formula use karte hain:
$\frac{dy}{dx} = \frac{v \frac{du}{dx} - u \frac{dv}{dx}}{v^2}$

Values put karte hain:
$\frac{dy}{dx} = \frac{(\sin x) \cdot (e^x) - (e^x) \cdot (\cos x)}{(\sin x)^2}$

Numerator se $e^x$ common le sakte hain:
$\frac{dy}{dx} = \frac{e^x (\sin x - \cos x)}{\sin^2 x}$

Yeh ho gaya differentiate!

---

### 📝 2.6. Logarithmic Differentiation (Logarithm Use Karke Differentiation)

Logarithmic Differentiation ek bahut powerful technique hai jab function bahut complex ho, khaaskar jab:
1.  Function **bahut saare terms ke product ya quotient** mein ho.
2.  Function **ek function ki power mein doosra function** ho ($[f(x)]^{g(x)}$ form mein), jaise $x^x$ ya $(\sin x)^x$.

**Ismein karte kya hain?**
Hum equation ke dono sides par natural logarithm ($\log$ ya $\ln$) lete hain. Isse product, quotient, aur power terms add/subtract/multiply mein convert ho jaate hain, jinko differentiate karna easy hota hai. Fir implicit differentiation use karte hain.

**Steps:**
1.  Function ko $y$ ke barabar maan lo: $y = f(x)$.
2.  Dono sides par $\log$ (natural logarithm) lo.
3.  Logarithm ki properties use karke expression ko simplify karo:
    *   $\log(ab) = \log a + \log b$
    *   $\log(a/b) = \log a - \log b$
    *   $\log(a^b) = b \log a$
4.  Ab, dono sides ko $x$ ke respect mein differentiate karo (left side par $\frac{1}{y} \frac{dy}{dx}$ aayega).
5.  $\frac{dy}{dx}$ ki value nikaal lo, $y$ ki original value wapas daal kar.

#### 🎯 Exercise 5.5 Questions (Selected) [1]

#### Question 1. Is function ko $x$ ke respect mein differentiate karo: $\cos x \cdot \cos 2x \cdot \cos 3x$ [1]

**_Explanation:_** Yeh teen functions ka product hai. Product Rule do functions ke liye toh theek hai, par teen ke liye thoda lamba ho jaayega. Logarithmic differentiation yahaan sabse easy tareeka hai.

**_Solution:_**
Maana $y = \cos x \cdot \cos 2x \cdot \cos 3x$.
Dono sides par natural logarithm lete hain:
$\log y = \log(\cos x \cdot \cos 2x \cdot \cos 3x)$

Logarithm property $\log(abc) = \log a + \log b + \log c$ use karte hain:
$\log y = \log(\cos x) + \log(\cos 2x) + \log(\cos 3x)$

Ab, dono sides ko $x$ ke respect mein differentiate karte hain:
$\frac{d}{dx}(\log y) = \frac{d}{dx}(\log(\cos x)) + \frac{d}{dx}(\log(\cos 2x)) + \frac{d}{dx}(\log(\cos 3x))$

Left side par, $\frac{d}{dx}(\log y) = \frac{1}{y} \frac{dy}{dx}$ (Chain Rule).
Right side par, $\frac{d}{dx}(\log f(x)) = \frac{1}{f(x)} \cdot f'(x)$ (Chain Rule).

*   $\frac{d}{dx}(\log(\cos x)) = \frac{1}{\cos x} \cdot (-\sin x) = -\tan x$.
*   $\frac{d}{dx}(\log(\cos 2x)) = \frac{1}{\cos 2x} \cdot (-\sin 2x \cdot 2) = -2\tan 2x$. (Yahaan $2x$ ka bhi derivative $2$ multiply kiya).
*   $\frac{d}{dx}(\log(\cos 3x)) = \frac{1}{\cos 3x} \cdot (-\sin 3x \cdot 3) = -3\tan 3x$. (Yahaan $3x$ ka bhi derivative $3$ multiply kiya).

Sabko combine karte hain:
$\frac{1}{y} \frac{dy}{dx} = -\tan x - 2\tan 2x - 3\tan 3x$

Ab $\frac{dy}{dx}$ nikaalne ke liye, $y$ ko right side par multiply karo:
$\frac{dy}{dx} = y (-\tan x - 2\tan 2x - 3\tan 3x)$

Finally, $y$ ki original value wapas daal do:
$\frac{dy}{dx} = -(\cos x \cdot \cos 2x \cdot \cos 3x)(\tan x + 2\tan 2x + 3\tan 3x)$

Aasan ho gaya na? Logarithm ne bade product ko sums mein badal diya!

---

## 📝 Key Takeaways for Today

*   **Implicit Differentiation:** Jab $y$ aur $x$ mix hon. Differentiate both sides, aur har $y$ term ke derivative ke saath $\frac{dy}{dx}$ multiply karna.
*   **Inverse Trig Derivatives:** Inke formulas yaad rakho. Complex expressions ko simplify karne ke liye **substitution (प्रतिस्थापन)**, khaaskar $x=\tan\theta$, $x=\sin\theta$, etc., bahut useful hai.
*   **Exponential/Log Derivatives:** Inke bhi formulas yaad rakho.
*   **Quotient/Product Rule:** Jab functions multiply ya divide ho rahe hon.
*   **Logarithmic Differentiation:** Jaadui tareeka! Jab bahut saare functions multiply ho rahe hon, ya $f(x)^{g(x)}$ type ka function ho, toh $\log$ lekar simplify karo.

---

Kaisa raha yeh session? Kya ab yeh topics thode clear ho rahe hain? Abhi bhi kuch confusion hai toh poocho, hum phir se samjhenge! Yeh saari techniques practice se hi aati hain, toh NCERT ke questions zaroor try karna. Keep up the good work!