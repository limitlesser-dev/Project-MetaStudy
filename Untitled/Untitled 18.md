These notes provide a detailed explanation of the key concepts, definitions, and methods related to Relations and Functions based on the provided video transcript.

---

## Detailed Explainer Notes: Relations and Functions (Class 12)

This material covers the core Class 12 topics of Types of Relations and Types of Functions, including methods for proving and disproving these properties, drawing on prerequisites from Class 11.

### I. Prerequisites: Relations Basics

A strong understanding of relations and functions from Class 11 is essential; failure to master this prerequisite material can make the Class 12 chapter difficult.

#### 1. Cartesian Product

The Cartesian Product of two sets A and B, denoted $A \times B$, is the set of all ordered pairs $(a, b)$ where the first element ($a$) belongs to the first set (A), and the second element ($b$) belongs to the second set (B).

- **Elements:** The number of elements in $A \times B$ is the product of the number of elements in A and B ($|A| \times |B|$).

#### 2. Relation

A relation establishes a connection between two sets (A to B) defined by a specific rule.

- **Definition:** Any relation $R$ from A to B is a **subset** of the Cartesian product $A \times B$.
- **Terminology:** In an ordered pair $(a, b)$: $a$ is the **pre-image** (or first element), and $b$ is the **image** (or second element).
- **Domain, Range, and Co-domain:**
    - **Domain:** The set of all pre-images in the relation.
    - **Range:** The set of all images in the relation.
    - **Co-domain:** The entire destination set (the second set, B, in a relation from A to B). The range is always a subset of the co-domain.

### II. Types of Relations (The Core Curriculum)

The primary focus of the Class 12 curriculum is on the types of relations. Relations are typically defined from a set A to itself ($A \to A$).

|Type of Relation|Definition|Condition|
|:--|:--|:--|
|**Reflexive**|Every element must be related to itself.|$\mathbf{(a, a) \in R}$ for **all** $a \in A$.|
|**Symmetric**|If a pair exists, its inverse must also exist.|If $\mathbf{(a, b) \in R}$, then $\mathbf{(b, a) \in R}$.|
|**Transitive**|If a chain exists, the shortcut must exist.|If $\mathbf{(a, b) \in R}$ and $\mathbf{(b, c) \in R}$, then $\mathbf{(a, c) \in R}$.|
|**Equivalence**|A relation that is simultaneously Reflexive, Symmetric, and Transitive.|Must satisfy all three conditions.|

**Important Distinctions:**

- **Identity vs. Reflexive:** The Identity relation requires _only_ the doubles (e.g., $(1, 1), (2, 2)$) and _no_ other elements. The Reflexive relation requires _all_ doubles for all elements in A, but allows for other pairs (e.g., $(1, 2)$).
- **Transitivity Default:** If a pair $(a, b)$ is present, but no element starts with $b$ (i.e., no $(b, c)$ is present), the relation is considered **transitively true by default**.

#### Proof Methods for Relations

The presentation style is critical for showing whether a relation holds:

1. **If the relation _is_ true (e.g., is reflexive or symmetric):** Use a **general method** (algebraic proof) that applies to all elements, especially for infinite sets like integers ($Z$) or real numbers ($R$).
2. **If the relation _is not_ true (e.g., not transitive or not symmetric):** Provide **one counterexample** (a "dam example") to disprove it.

#### Equivalence Class

If a relation is an Equivalence Relation, an **Equivalence Class** can be found for any element 'a'.

- The equivalence class of an element 'a' (often denoted $[a]$) is the set of all elements in the domain that are related to 'a' according to the defined relation.

### III. Types of Functions

A function is a specialized type of relation where the domain does not repeat (one input yields one output).

|Type of Function|Other Name|Definition|
|:--|:--|:--|
|**One-One**|**Injective**|Every distinct pre-image has a distinct image.|
|**Many-One**||Two or more different inputs yield the same output.|
|**Onto**|**Surjective**|Every element in the Co-domain is the image of at least one element in the Domain. The Range equals the Co-domain.|
|**Bijective**||A function that is both One-One and Onto.|

#### Proof Methods for Functions

The domain and co-domain (e.g., $N \to N$, $Z \to Z$, $R \to R$) are crucial as they affect whether a function is One-One or Onto.

1. **Proving One-One (Injective):**
    
    - **Method:** Assume $x_1$ and $x_2$ are distinct arbitrary elements. Set $f(x_1) = f(x_2)$.
    - If this assumption implies that $x_1 = x_2$ (and considering the constraints of the domain, such as avoiding $\pm$ solutions if the domain is natural numbers), the function is One-One.
2. **Disproving One-One:**
    
    - **Method:** Find a single counterexample where two different inputs ($x_1 \neq x_2$) produce the same output ($f(x_1) = f(x_2)$).
3. **Proving Onto (Surjective):**
    
    - **Method:**
        1. Set $f(x) = y$ (since $f(x)$ and $y$ are equivalent).
        2. Solve the resulting equation to express **$x$ in terms of $y$**.
        3. Substitute this expression for $x$ back into the original function $f(x)$.
        4. If the result is $f(x) = y$, the function is Onto.
4. **Disproving Onto:**
    
    - **Method:** Identify an element in the co-domain (Y set) that cannot be produced by any input from the domain (X set). This element is "free" (वेला).
    - _Example:_ For $f(x) = x^2$ on integers ($Z \to Z$), negative integers in the co-domain are never reached, so it is not Onto.

#### Invertible Functions (Extra Topic)

A function is **invertible** if and only if it is **bijective** (both One-One and Onto). The formula derived for $x$ in terms of $y$ during the Onto proof process, after replacing $y$ with $x$, yields the function's inverse.

### IV. Counting Formulas (MCQ Focus)

These formulas are used to quickly solve objective questions concerning the maximum number of relations or functions that satisfy certain conditions. Let $|A| = m$ (or $n$) and $|B| = n$ (or $q$).

| Count Type              | Set Conditions | Formula | Citation |
| :---------------------- | :------------- | :------ | :------- |
| **Total Relations**     | $A \to B$, $   | A       | =P,      |
| **Reflexive Relations** | $A \to A$, $   | A       | =n$      |
| **Symmetric Relations** | $A \to A$, $   | A       | =n$      |
| **One-One Functions**   | $A \to B$, $   | A       | =m,      |
| **One-One Functions**   | $A \to B$, $   | A       | =m,      |
| **Onto Functions**      | $A \to A$, $   | A       | =n$      |
| **Bijective Functions** | $A \to A$, $   | A       | =        |