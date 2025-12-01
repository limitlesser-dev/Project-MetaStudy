This comprehensive guide details the concepts of Relations and Functions, drawing exclusively from the provided source material, including prerequisite knowledge, types of relations, types of functions, proof techniques, and related formulas.

---

## Detailed Explainer Notes on Relations and Functions

This chapter is **100% related** to the 11th Standard material on Relations and Functions. Previously, the chapter included Relation, Function, Binary Operation, and Inverse of a Function, but Binary Operation and Inverse of a Function have largely been removed from the current curriculum.

### I. Prerequisites and 11th Grade Review

#### A. Cartesian Product and Relation Definition

1. **Cartesian Product ($A \times B$):** This is the multiplication of two sets. It is defined as the set of all **ordered pairs** $(a, b)$, where the first element ($a$) belongs to the first set (A) and the second element ($b$) belongs to the second set (B).
2. **Definition of a Relation:** A relationship requires two entities ("kiska rishta kiske saath") and a specific definition for the relationship ("wo rishta kya kehlata hai"). A relation ($R$) from set A to set B is defined by a specific condition on the ordered pairs $(x, y)$.
3. **Relation and Cartesian Product:** Any relation ($R$) defined from set A to set B will always be a **subset** of the Cartesian product $A \times B$.

#### B. Domain, Range, and Codomain

1. **Domain:** The set of all **pre-images** (the first element of every ordered pair in the relation).
2. **Range:** The set of all **images** (the second element of every ordered pair in the relation).
3. **Codomain:** The entire set (the second set, B, in a relation from A to B) from which the range is derived. The Range is always a **subset** of the Codomain.

### II. Types of Relations

The core focus of the current curriculum is on the types of relations and functions.

#### A. Proof Techniques

When proving characteristics of relations (Reflexive, Symmetric, Transitive):

- **To Prove It Exists (It _is_ R, S, or T):** Use a **general method** rather than specific examples, especially when dealing with infinite sets like integers (Z) or real numbers (R).
- **To Disprove It Exists (It is _not_ R, S, or T):** Provide only **one counter-example**.

#### B. Basic Relations (Not always in syllabus)

1. **Null/Empty/Void Relation:** A relation that contains **no elements** and cannot possibly happen based on the given condition ($\phi$).
2. **Identity Relation:** Contains **only** doublets $(a, a)$, where $a$ belongs to set $A$. No element other than doublets are allowed.

#### C. Core Types of Relations

1. **Reflexive Relation:**
    
    - **Condition:** $(a, a)$ must belong to the relation $R$ **for all** elements $a$ belonging to the set $A$.
    - **Detail:** All doublets corresponding to the elements in $A$ must be present. Extra ordered pairs ($a, b$) are allowed. If any doublet is missing, it is not reflexive.
    - **Example Proof:** $x - x = 0$, and 0 is an integer (or divisible by any number), proving $(x, x)$ belongs to the relation $R$ generally.
2. **Symmetric Relation:**
    
    - **Condition:** If $(a, b)$ is in $R$, then $(b, a)$ **must** also be in $R$.
    - **Detail:** If $(a, b)$ is present, you must find its reverse. If $(a, b)$ is not present, you do not need to check anything.
    - **Example Disproof:** If $(1, 2)$ is present but $(2, 1)$ is not, it is **not symmetric**. Example: If $x$ is exactly 7cm taller than $y$, then $y$ cannot be 7cm taller than $x$.
3. **Transitive Relation (Most Complicated):**
    
    - **Condition:** If $(a, b)$ is in $R$ **AND** $(b, c)$ is in $R$, **THEN** $(a, c)$ must be in $R$.
    - **Default Transitive Rule:** If $(a, b)$ is found, but no ordered pair starts with $b$ (i.e., $(b, c)$ is missing), the relation is **by default** Transitive.
    - **Example Disproof:** If $(1, 2)$ and $(2, 3)$ are present, but $(1, 3)$ is missing, it is **not transitive**.
4. **Equivalence Relation:**
    
    - A relation that is simultaneously **Reflexive, Symmetric, and Transitive**.
    - _The Smallest Equivalence Relation_ is the set containing only the doublets required for reflexivity.
    - _The Longest/Largest Equivalence Relation_ is the entire $A \times A$.

#### D. Equivalence Class

The **Equivalence Class of an element $x$** (often written as $[x]$) is the set of all elements in the given set that are related to $x$ under the equivalence relation. To find the equivalence class of 2, you find which elements, when paired with 2, fulfill the relation's definition (e.g., $2-y$ is divisible by 4).

### III. Types of Functions

A function is a machine that works on input (domain) and output (range). A key property is that the **domain should not repeat** (the same input cannot give two different outputs).

#### A. Classification by Mapping

1. **One-One Function (Injective):**
    
    - **Definition:** Every distinct pre-image (input) maps to a distinct image (output).
    - **Proof Technique:** Let $x_1$ and $x_2$ be two distinct arbitrary elements. Set $f(x_1) = f(x_2)$ and show that this equation implies $x_1 = x_2$.
2. **Many-One Function:**
    
    - **Definition:** Multiple domain elements map to the same range element.
    - **Disproof Technique (Not One-One):** Provide one counter-example where $x_1 \neq x_2$ but $f(x_1) = f(x_2)$ (e.g., $f(x)=x^2$ where $f(-1) = f(1) = 1$).
3. **Onto Function (Surjective):**
    
    - **Definition:** Every element in the codomain (Y) must be the image of at least one element in the domain (X). No element in the codomain side should be "free".
    - **Proof Technique (General Method):** (1) Set $f(x) = y$. (2) Solve this equation to find $x$ in terms of $y$. (3) Substitute this expression for $x$ back into the original function $f(x)$. (4) If the result $f(x)$ simplifies to $y$, the function is Onto.
    - **Disproof Technique (Not Onto):** Provide a single example of an element $y$ in the codomain that cannot be obtained as $f(x)$. Example: In $f(x)=x^2$ from $\mathbb{Z} \to \mathbb{Z}$, negative integers can never be outputs, so it is not Onto.
4. **Bijective Function:**
    
    - A function that is both **One-One and Onto**.

#### B. Invertible Functions (Advanced/Other Boards)

A function is **invertible** if and only if it is a **Bijective function** (both One-One and Onto). The inverse function $f^{-1}(x)$ is the expression for $x$ in terms of $y$ derived during the Onto proof.

### IV. Formulas for Counting Relations and Functions (MCQ Focus)

These formulas are used to quickly solve objective questions concerning the number of relations or functions possible between two sets.

|Scenario|Condition|Formula|Citation|
|:--|:--|:--|:--|
|**Total Relations**|Set A has P elements, Set B has Q elements (A to B)|$2^{P \times Q}$||
|**Reflexive Relations**|Set A has $n$ elements (A to A)|$2^{n^2 - n}$||
|**Symmetric Relations**|Set A has $n$ elements (A to A)|$2^{\frac{n^2 + n}{2}}$ (As $2^{n+1 / 2}$)||
|**Onto Functions**|Set A has $n$ elements (A to A)|$n!$||
|**One-One Functions**|Set A has $m$ elements, Set B has $n$ elements (A to B)|If $m = n$, $n!$ (factorial). If $m < n$, ${}^{n}P_m$. If $m > n$, 0.||