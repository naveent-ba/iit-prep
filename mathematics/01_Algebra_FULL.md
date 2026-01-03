---
title: Algebra
parent: Mathematics
nav_order: 1
---

# Chapter 1 — ALGEBRA
## Structure, Balance, and Constraints

---

## PAGE 1 — Why Algebra Exists (Mindset Reset)

Most students think:

> "Algebra is about solving for x."

That is **not** its real purpose.

### Algebra answers questions like:
- What relationships must always be true?
- What constraints bind quantities together?
- What can change — and what must not?
- How can we reason *before* knowing exact numbers?

> **Algebra is reasoning without numbers.**

This is why algebra appears everywhere:
- equations
- inequalities
- functions
- sequences
- coordinate geometry
- probability
- calculus

Algebra is not just a chapter.
It is the **language of structure**.

---

## PAGE 2 — The Core Idea (Anchor Page)

### The Core Idea of Algebra

> **Algebra is the mathematics of structure and balance.**

An algebraic statement is a **truth claim**.

When you write:
```
x + 5 = 12
```
You are not "finding x".

You are saying:
> "There exists a value that balances this relationship."

> **Algebra preserves truth while changing form.**

---

## PAGE 3 — Equations Are Balance Laws (Very Important)

An equation behaves like a **physical balance scale**.

- Left side = Right side
- Truth must be preserved

This is why:
- adding
- subtracting
- multiplying
- dividing

are valid **only if done symmetrically**.

### JEE Insight
Most algebra mistakes happen when students:
- violate balance
- divide by zero unknowingly
- manipulate expressions without checking validity

---

## PAGE 4 — What Changes vs What Remains Invariant

| Aspect | Changes | Remains Invariant |
|--------|---------|-------------------|
| Numerical values | ✅ | ❌ |
| Expression form (expanded / factorised) | ✅ | ❌ |
| Representation (equation, graph, words) | ✅ | ❌ |
| Truth of the relationship | ❌ | ✅ |
| Constraints / domain | ❌ | ✅ |

> **JEE problems deliberately change form to hide invariants.**
Your job is to *protect* them.

---

## PAGE 5 — Variables Are Not Ignorance (Critical Shift)

A common misunderstanding:

> "x means I don't know."

Correct view:

> **x means the structure is known, the value may vary.**

Example:
```
ax + b > 0
```
This already encodes:
- inequality structure
- domain constraints
- relationships between quantities

Algebra is **information-dense**, not vague.

---

## PAGE 6 — Functions: The True Language of Algebra

A function is **not** a formula.

> **A function describes dependence.**

From:
```
f(x) = x² − 4x + 3
```
You should infer:
- shape (parabola)
- symmetry
- minimum value
- roots
- behavior as x → ±∞

Even before calculation.

> **JEE Advanced tests function behavior, not substitution.**

---

## PAGE 7 — Representations (Same Idea, Different Forms)

One algebraic idea can appear as:
- an equation
- an inequality
- a graph
- a word problem

Example:
```
x² − 5x + 6 ≥ 0
```

Equivalent to:
- sign analysis
- interval reasoning
- a parabola above the x-axis

> **Advanced problems often switch representations mid-question.**

---

## PAGE 8 — Quadratic Equations: The Discriminant Decides Everything

### The Core Insight

A quadratic equation ax² + bx + c = 0 has one invariant that tells you everything:

> **Δ = b² − 4ac (The Discriminant)**

| Condition | Nature of Roots |
|-----------|-----------------|
| Δ > 0 | Two distinct real roots |
| Δ = 0 | Two equal real roots (one repeated) |
| Δ < 0 | No real roots (complex conjugate pair) |

### Vieta's Formulas: Roots ↔ Coefficients

For ax² + bx + c = 0 with roots α and β:

```
α + β = −b/a     (sum of roots)
αβ = c/a        (product of roots)
```

> **You can reason about roots without finding them.**

This is powerful: many JEE problems ask about roots indirectly.

### The Quadratic as a Function

```
f(x) = ax² + bx + c
```

- If a > 0: parabola opens upward (minimum exists)
- If a < 0: parabola opens downward (maximum exists)
- Vertex at x = −b/2a

> **The sign of 'a' and the discriminant together determine the entire graph.**

---

## PAGE 9 — Polynomials: Structure Beyond Quadratics

### The Fundamental Truth

> **A polynomial of degree n has exactly n roots (counting multiplicity and complex roots).**

### Factor Theorem

If f(a) = 0, then (x − a) is a factor of f(x).

> **Every root gives you a factor. Every factor gives you a root.**

### Remainder Theorem

When f(x) is divided by (x − a), the remainder is f(a).

> **To find the remainder, just substitute.**

### Vieta's Formulas (General)

For polynomial: xⁿ + a₁xⁿ⁻¹ + a₂xⁿ⁻² + ... + aₙ = 0

- Sum of roots = −a₁
- Sum of products taken two at a time = a₂
- Product of all roots = (−1)ⁿ aₙ

> **The coefficients encode symmetric functions of roots.**

### JEE Insight

When a problem gives you roots and asks about coefficients (or vice versa), don't solve — use Vieta's formulas directly.

---

## PAGE 10 — Logarithms: Multiplication Becomes Addition

### The Core Insight

> **Logarithm converts multiplication into addition.**

```
log(ab) = log(a) + log(b)
log(a/b) = log(a) − log(b)
log(aⁿ) = n·log(a)
```

This is why logarithms were invented — to simplify computation.

### The Invariant: Change of Base

```
logₐ(x) = logᵦ(x) / logᵦ(a)
```

> **The base is just a scaling factor. The relationship is invariant.**

### Domain Constraints (Critical for JEE)

For log_a(x) to exist:
- x > 0 (argument must be positive)
- a > 0, a ≠ 1 (base must be positive and not 1)

> **Most logarithm errors come from ignoring domain.**

### Logarithmic Equations: The Trap

When solving log equations:
1. Solve the equation
2. **Check that solutions satisfy domain constraints**

Many "solutions" are extraneous because they violate x > 0.

---

## PAGE 11 — Sequences: Algebra Over Position

### The Core Insight

> **A sequence is a function whose domain is natural numbers.**

Instead of f(x), think f(n) where n = 1, 2, 3, ...

### Arithmetic Progression (AP)

The **invariant** is the common difference d.

```
aₙ = a + (n−1)d
Sₙ = n/2 [2a + (n−1)d] = n/2 [first + last]
```

Key insight: In an AP, the average equals the middle term.

### Geometric Progression (GP)

The **invariant** is the common ratio r.

```
aₙ = arⁿ⁻¹
Sₙ = a(rⁿ − 1)/(r − 1)  when r ≠ 1
S∞ = a/(1 − r)          when |r| < 1
```

Key insight: Each term is a fixed multiple of the previous.

### Harmonic Progression (HP)

If a, b, c are in HP, then 1/a, 1/b, 1/c are in AP.

> **HP problems are AP problems in disguise.**

### AM-GM-HM Inequality

For positive numbers a and b:

```
AM ≥ GM ≥ HM
(a+b)/2 ≥ √(ab) ≥ 2ab/(a+b)
```

Equality holds when a = b.

> **This inequality appears everywhere in optimization problems.**

---

## PAGE 12 — Binomial Theorem: Controlled Expansion

### The Core Structure

```
(x + y)ⁿ = Σ ⁿCᵣ · xⁿ⁻ʳ · yʳ    (r goes from 0 to n)
```

### The General Term

```
Tᵣ₊₁ = ⁿCᵣ · xⁿ⁻ʳ · yʳ
```

> **The (r+1)th term has r factors of y.**

### Key Properties (Structure, Not Memory)

| Property | Why It's True |
|----------|---------------|
| Sum of coefficients = 2ⁿ | Put x = y = 1 |
| Sum of odd position coeffs = Sum of even position coeffs | Put x = 1, y = −1 |
| ⁿC₀ + ⁿC₁ + ... + ⁿCₙ = 2ⁿ | Same as first property |
| ⁿCᵣ = ⁿCₙ₋ᵣ | Symmetry of Pascal's triangle |

### Finding Specific Terms

**Middle term:**
- If n is even: one middle term at position (n/2 + 1)
- If n is odd: two middle terms at positions (n+1)/2 and (n+3)/2

**Term independent of x:**
Set the power of x to zero and solve for r.

**Greatest coefficient:**
Occurs at middle term(s).

### JEE Insight

Most binomial problems are about:
1. Finding a specific term (use general term formula)
2. Finding coefficient of xᵏ (set power = k, solve for r)
3. Sum of coefficients (substitute x = 1)

---

## PAGE 13 — What JEE Is REALLY Testing in Algebra

### JEE Main Tests:
- Direct manipulation and solving
- Standard identities
- Routine AP/GP sums
- Basic binomial expansion
- Logarithm simplification

### JEE Advanced Tests:
- Hidden constraints and domain awareness
- Symmetry exploitation
- Vieta's formulas for indirect root reasoning
- Sequences with non-standard patterns
- Binomial with constraints (divisibility, greatest term)
- Function behavior without explicit solving

> **Mechanical algebra fails at Advanced level.**

---

## PAGE 14 — Skill-Based Examples (What Is Being Tested)

### Example 1 — Constraint Awareness
Expression:
```
√(x − 1) + √(3 − x)
```
Skill tested:
- Domain intersection: 1 ≤ x ≤ 3
- Inequality logic

---

### Example 2 — Structural Thinking (The Wavy Curve)
Solve:
$$(x − 1)(x − 2)(x − 5) \ge 0$$

Use the **Sign Scheme (Wavy Curve)**:
1. **Critical Points:** 1, 2, 5
2. **The Wave:** Starts positive from the right
3. **The Switch:** Sign changes at each simple root

> **Visualizing the sign change is faster than calculating it.**

---

### Example 3 — Vieta's Formulas
If α and β are roots of x² − 5x + 6 = 0, find α² + β².

Don't solve for α and β. Use:
```
α² + β² = (α + β)² − 2αβ = 25 − 12 = 13
```

Skill tested:
- Reasoning about roots without finding them

---

### Example 4 — Logarithm Domain
Solve: log₂(x − 3) + log₂(x + 1) = 3

Steps:
1. Combine: log₂[(x−3)(x+1)] = 3
2. Solve: (x−3)(x+1) = 8 → x² − 2x − 11 = 0
3. Check: x > 3 (for both logs to exist)

Skill tested:
- Domain verification after solving

---

### Example 5 — Sequence Insight
In a GP, the 4th term is 24 and 7th term is 192. Find the 10th term.

Don't find a and r separately.
```
a₇/a₄ = r³ = 192/24 = 8 → r³ = 8
a₁₀ = a₇ · r³ = 192 · 8 = 1536
```

Skill tested:
- Using ratio structure directly

---

### Example 6 — Binomial Coefficient
Find the term independent of x in (x² + 1/x)⁹.

General term: ⁹Cᵣ · (x²)⁹⁻ʳ · (1/x)ʳ = ⁹Cᵣ · x^(18−3r)

For independence: 18 − 3r = 0 → r = 6

Term: ⁹C₆ = 84

Skill tested:
- Setting up and solving power equation

---

## PAGE 15 — Common Algebra Traps (Exam Killers)

### General Traps
- Dividing by expressions that may be zero
- Ignoring domain of radicals and logarithms
- Treating inequalities like equations
- Illegal cancellation

### Quadratic Traps
- Forgetting that Δ < 0 means no real roots
- Using sum/product formulas without checking if roots exist
- Confusing "roots are real" with "roots are positive"

### Logarithm Traps
- Forgetting log argument must be positive
- Forgetting log base must be positive and ≠ 1
- Not checking extraneous solutions

### Sequence Traps
- Confusing nth term with sum of n terms
- Using GP sum formula when r = 1
- Forgetting |r| < 1 condition for infinite GP sum

### Binomial Traps
- Off-by-one errors: Tᵣ₊₁ (not Tᵣ) has r as the power of y
- Forgetting negative signs when y is negative
- Wrong middle term count for odd vs even n

> **Most algebra mistakes are logical, not computational.**

---

## PAGE 16 — Mental Checklist (Before Solving)

Before solving any algebra problem, ask:

1. What are the **constraints**? (domain, positivity, existence)
2. Is the domain **restricted**? (radicals, logarithms, denominators)
3. Is **symmetry** present? (Vieta's, substitution, pattern)
4. Is this better seen as a **function**? (graph behavior, extrema)
5. Am I preserving **balance** at every step?
6. For sequences: What is the **invariant**? (d for AP, r for GP)
7. For polynomials: Can I use **Vieta's formulas** instead of solving?

This checklist alone saves **many marks**.

---

## PAGE 17 — Why Algebra Appears Everywhere

Algebra appears everywhere because:
- Geometry needs equations
- Trigonometry needs identities
- Calculus needs functions
- Probability needs constraints
- Sequences model growth and patterns

> **Algebra is the skeleton of mathematics.**

If geometry is shape
and calculus is change,
**algebra is structure**.

---

## PAGE 18 — Forward Connections

Algebra feeds directly into:
- **Trigonometry**: identities, equations
- **Calculus**: limits, derivatives, optimization
- **Probability**: constraints, counting
- **Coordinate Geometry**: equations as shapes
- **Matrices**: systems of equations
- **Complex Numbers**: algebraic operations in 2D

> **Strong algebra reduces difficulty everywhere else.**
