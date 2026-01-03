---
title: Trigonometry
parent: Mathematics
nav_order: 3
---

# Chapter 3 — TRIGONOMETRY
## Direction and Proportion

---

## PAGE 1 — Why Trigonometry Exists (Mindset Reset)

Most students think:

> "Trigonometry is about memorizing sine–cosine formulas."

That is **not** its real purpose.

### Trigonometry answers questions like:
- How does *direction* control proportion?
- If I move in a certain direction, how much is horizontal vs vertical?
- How can the same shape behave identically at different sizes?
- How do angles encode geometry numerically?

> **Trigonometry converts direction into numbers.**

This is why trigonometry appears in:
- heights and distances
- coordinate geometry
- vectors
- calculus
- waves and oscillations
- physics

Trigonometry is **geometry without size**.

---

## PAGE 2 — The Core Idea (Anchor Page)

### The Core Idea of Trigonometry

> **Trigonometry studies ratios that remain invariant under scaling.**

If two triangles have the same angles:
- their sizes may differ
- but their side ratios are identical

These ratios depend **only on the angle**, not on length.

> **Angles control proportion, not size.**

---

## PAGE 3 — What Changes vs What Remains Invariant

| Aspect | Changes | Remains Invariant |
|--------|---------|-------------------|
| Triangle size | ✅ | ❌ |
| Side lengths | ✅ | ❌ |
| Angle | ❌ | ✅ |
| sinθ, cosθ, tanθ | ❌ | ✅ |

> **JEE problems often hide ratios inside changing lengths.**
Find the invariant angle.

---

## PAGE 4 — Meaning of sin, cos, tan (Before Formulas)

Forget formulas for a moment.

Think in terms of **effect**:

- **sinθ** → vertical component of a direction
- **cosθ** → horizontal component of a direction
- **tanθ** → steepness (rise / run)

This explains:
- why sin²θ + cos²θ = 1
- why tanθ blows up at 90°
- why tanθ = sinθ / cosθ

> **Trigonometric identities are structural truths.**

---

## PAGE 5 — Similarity: The Real Foundation

All trigonometric ratios come from **similar triangles**.

Scaling a triangle:
- changes lengths
- does not change ratios

This single fact explains:
- why trigonometry works
- why ratios depend only on θ

> **Similarity is the backbone of trigonometry.**

---

## PAGE 6 — The Unit Circle (The Big Leap)

Triangles are just a teaching tool.

The real power comes from the **unit circle**.

- Fix radius = 1
- Rotate a point through angle θ

Now:
- cosθ = x-coordinate
- sinθ = y-coordinate

This removes:
- size dependence
- right-angle restriction

> **Trigonometry becomes geometry + motion.**

---

## PAGE 7 — The ASTC Rule: Your Sign Map (Visualization Tool)

### The Problem

As θ moves around the circle, sin, cos, tan change signs.
Memorizing each case is error-prone.

### The Solution: ASTC

Visualize the four quadrants:

```
            90°
             |
     Q2      |      Q1
   (S only)  |  (All positive)
    Sin+     |   Sin+ Cos+ Tan+
             |
180° --------+-------- 0°/360°
             |
     Q3      |      Q4
   (T only)  |   (C only)
    Tan+     |    Cos+
             |
            270°
```

**Memory aid:** "**A**ll **S**tudents **T**ake **C**offee" or "**A**ll **S**in **T**an **C**os"

Starting from Q1 and going anti-clockwise: **A-S-T-C**

### Why This Works

- **Q1 (0° to 90°)**: x > 0, y > 0 → cos+, sin+ → All positive
- **Q2 (90° to 180°)**: x < 0, y > 0 → cos−, sin+ → only Sin positive
- **Q3 (180° to 270°)**: x < 0, y < 0 → cos−, sin− → only Tan positive (−/− = +)
- **Q4 (270° to 360°)**: x > 0, y < 0 → cos+, sin− → only Cos positive

### Using ASTC Instantly

To find sin(150°):
1. 150° is in Q2
2. Q2 → only Sin positive → sin(150°) is positive
3. Reference angle = 180° − 150° = 30°
4. sin(150°) = +sin(30°) = 1/2

To find cos(240°):
1. 240° is in Q3
2. Q3 → only Tan positive → cos(240°) is negative
3. Reference angle = 240° − 180° = 60°
4. cos(240°) = −cos(60°) = −1/2

> **ASTC + Reference Angle = Instant answer. No formula needed.**

---

## PAGE 8 — Allied Angles: The Complete Sign Table

### The Pattern

Instead of memorizing formulas, see the pattern:

| Angle | sin | cos | tan |
|-------|-----|-----|-----|
| θ | sinθ | cosθ | tanθ |
| 90° − θ | cosθ | sinθ | cotθ |
| 90° + θ | cosθ | −sinθ | −cotθ |
| 180° − θ | sinθ | −cosθ | −tanθ |
| 180° + θ | −sinθ | −cosθ | tanθ |
| 270° − θ | −cosθ | −sinθ | cotθ |
| 270° + θ | −cosθ | sinθ | −cotθ |
| 360° − θ | −sinθ | cosθ | −tanθ |

### The Rule (Don't Memorize, Derive)

**Step 1: Does the function change?**
- Angles with 90° or 270° → function CHANGES (sin ↔ cos, tan ↔ cot)
- Angles with 180° or 360° → function STAYS same

**Step 2: What's the sign?**
- Use ASTC: check which quadrant the final angle lands in
- Apply the sign for that function in that quadrant

### Example: sin(270° + θ)

1. 270° involved → function changes → becomes cosθ
2. If θ is small and positive, 270° + θ is in Q4
3. Q4 → Sin negative → answer is −cosθ

> **Two steps: (1) Does it flip? (2) What's the sign from ASTC?**

---

## PAGE 9 — Graph Transformations (Visualization Tool)

### The Base Graphs

```
y = sin x : starts at 0, peaks at π/2, back to 0 at π, minimum at 3π/2
y = cos x : starts at 1, zeros at π/2, minimum at π, back to 1 at 2π
y = tan x : vertical asymptotes at ±π/2, passes through origin
```

### The Transformation Framework

For y = A sin(Bx + C) + D:

| Parameter | Effect | How to Find |
|-----------|--------|-------------|
| A | **Amplitude** (vertical stretch) | Height = \|A\| |
| B | **Period** change | Period = 2π/\|B\| |
| C/B | **Phase shift** (horizontal) | Shift = −C/B |
| D | **Vertical shift** | Midline at y = D |

### Visual Intuition

**Amplitude (A):**
- A = 2 → graph stretches vertically, peaks at 2 and −2
- A = 1/2 → graph compresses vertically, peaks at 0.5 and −0.5
- A < 0 → graph flips upside down

**Period (B):**
- B = 2 → graph completes cycle in π (faster oscillation)
- B = 1/2 → graph completes cycle in 4π (slower oscillation)

**Phase Shift (−C/B):**
- Positive C → shift LEFT
- Negative C → shift RIGHT
- Think: sin(x + π/2) = cos(x) — shifted left by π/2

**Vertical Shift (D):**
- D = 3 → entire graph moves up by 3
- D = −2 → entire graph moves down by 2

### Quick Example

y = 3 sin(2x − π) + 1

- Amplitude = 3
- Period = 2π/2 = π
- Phase shift = −(−π)/2 = π/2 (shift RIGHT by π/2)
- Vertical shift = 1 (midline at y = 1)
- Range: [1−3, 1+3] = [−2, 4]

> **For range questions: Range = [D − |A|, D + |A|]**

---

## PAGE 10 — Trigonometric Equations: Visual Approach

### The Core Insight

> **A trig equation has infinitely many solutions. Your job is to express them all.**

### Solving sin θ = k (Visual Method)

**Step 1:** Find the principal solution α where sin α = k and α ∈ [−π/2, π/2]

**Step 2:** Visualize on unit circle:
- sin θ = k means y-coordinate = k
- Draw horizontal line y = k
- It intersects the circle at TWO points per cycle

**Step 3:** The two solutions in [0, 2π]:
- First solution: α (in Q1 if k > 0)
- Second solution: π − α (in Q2 if k > 0)

**Step 4:** General solution:
- All solutions: α, π − α, 2π + α, 2π + (π − α), ...
- Pattern: θ = nπ + (−1)ⁿα

### Solving cos θ = k (Visual Method)

**Step 1:** Find principal solution α where cos α = k and α ∈ [0, π]

**Step 2:** Visualize:
- cos θ = k means x-coordinate = k
- Draw vertical line x = k
- Intersects at α (Q1) and −α (Q4)

**Step 3:** General solution:
- θ = 2nπ ± α

### Solving tan θ = k (Visual Method)

**Step 1:** Find principal solution α where tan α = k and α ∈ (−π/2, π/2)

**Step 2:** Visualize:
- tan repeats every π (not 2π)
- Only ONE solution per π interval

**Step 3:** General solution:
- θ = nπ + α

### Summary Table (Reference, Not Memory)

| Equation | General Solution | Why |
|----------|------------------|-----|
| sin θ = sin α | θ = nπ + (−1)ⁿα | Two solutions per 2π, alternating |
| cos θ = cos α | θ = 2nπ ± α | Two solutions per 2π, symmetric about 0 |
| tan θ = tan α | θ = nπ + α | One solution per π |

> **Derive from the circle, don't memorize the formula.**

---

## PAGE 11 — Trigonometric Equations: Strategy

### Step 1: Simplify to Single Trig Function

Convert everything to sin and cos if needed.

### Step 2: Find Principal Solution

Use ASTC + reference angle to get the principal value.

### Step 3: Write General Solution

Use the visual method from PAGE 10.

### Step 4: Apply Constraints

If the problem restricts θ to an interval (e.g., [0, 2π]), substitute integer values of n to find specific solutions.

### Common Equation Types

| Type | Strategy |
|------|----------|
| a sin θ + b cos θ = c | Convert to R sin(θ + φ) form where R = √(a² + b²) |
| sin θ = k where \|k\| > 1 | No solution (sin range is [−1, 1]) |
| Multiple angles (sin 2θ, cos 3θ) | Let u = 2θ, solve for u, then find θ |
| sin θ = cos α | Use sin θ = sin(π/2 − α), then apply formula |

### The R-Formula (Important Tool)

To solve a sin θ + b cos θ = c:

1. Rewrite as R sin(θ + φ) where:
   - R = √(a² + b²)
   - tan φ = b/a

2. Now solve R sin(θ + φ) = c
   - This has solutions only if |c| ≤ R

> **The maximum value of a sin θ + b cos θ is √(a² + b²)**

---

## PAGE 12 — Inverse Trigonometric Functions: Running Backwards

### The Core Insight

> **Inverse trig asks: "What angle gives this ratio?"**

Forward: angle → ratio (sin 30° = 0.5)
Inverse: ratio → angle (sin⁻¹ 0.5 = 30°)

### The Problem: Infinite Angles

sin θ = 0.5 has infinitely many solutions: 30°, 150°, 390°, ...

So which one does sin⁻¹(0.5) return?

### The Solution: Principal Value

> **Inverse trig functions return ONE specific angle from a restricted range.**

| Function | Domain | Range (Principal Value) |
|----------|--------|-------------------------|
| sin⁻¹ x | [−1, 1] | [−π/2, π/2] |
| cos⁻¹ x | [−1, 1] | [0, π] |
| tan⁻¹ x | ℝ | (−π/2, π/2) |
| cot⁻¹ x | ℝ | (0, π) |
| sec⁻¹ x | \|x\| ≥ 1 | [0, π], excluding π/2 |
| cosec⁻¹ x | \|x\| ≥ 1 | [−π/2, π/2], excluding 0 |

> **The range is the invariant. It never changes.**

---

## PAGE 13 — Inverse Trig: Key Properties

### Property 1: Composition with Same Function

```
sin(sin⁻¹ x) = x       for x ∈ [−1, 1]
sin⁻¹(sin θ) = θ       only if θ ∈ [−π/2, π/2]
```

> **The second one is the trap. If θ is outside the principal range, you must adjust.**

### Property 2: Negative Arguments

```
sin⁻¹(−x) = −sin⁻¹(x)     (odd function)
cos⁻¹(−x) = π − cos⁻¹(x)   (not odd!)
tan⁻¹(−x) = −tan⁻¹(x)     (odd function)
```

### Property 3: Complementary Relationships

```
sin⁻¹ x + cos⁻¹ x = π/2
tan⁻¹ x + cot⁻¹ x = π/2
sec⁻¹ x + cosec⁻¹ x = π/2
```

> **These follow from complementary angles in a right triangle.**

### Property 4: Sum Formulas

```
tan⁻¹ x + tan⁻¹ y = tan⁻¹[(x + y)/(1 − xy)]    when xy < 1
```

When xy > 1, add or subtract π depending on signs.

---

## PAGE 14 — Inverse Trig: The Graphical View

### Why Graphs Matter

The graph of y = sin⁻¹ x is the reflection of y = sin x across y = x, but only for the principal branch.

### Key Graph Features

| Function | Shape | Key Points |
|----------|-------|------------|
| sin⁻¹ x | S-curve from (−1, −π/2) to (1, π/2) | Passes through origin |
| cos⁻¹ x | Decreasing curve from (−1, π) to (1, 0) | Never negative |
| tan⁻¹ x | S-curve with horizontal asymptotes at ±π/2 | Passes through origin |

### JEE Insight

When asked about range of a composite function like f(x) = sin⁻¹(2x − 1):
1. Find domain: −1 ≤ 2x − 1 ≤ 1 → 0 ≤ x ≤ 1
2. Range is always [−π/2, π/2] for sin⁻¹ (the output range is fixed)

---

## PAGE 15 — Solution of Triangles: The Complete Toolkit

### The Core Insight

> **In any triangle, if you know 3 elements (with at least one side), you can find all 6.**

The 6 elements: 3 sides (a, b, c) and 3 angles (A, B, C).

### The Sine Rule

```
a/sin A = b/sin B = c/sin C = 2R
```

Where R = circumradius.

> **Sine rule connects opposite side-angle pairs.**

**When to use:**
- Given 2 angles and 1 side (AAS)
- Given 2 sides and angle opposite to one (SSA — ambiguous case!)

### The Cosine Rule

```
a² = b² + c² − 2bc cos A
```

(and cyclic variations)

> **Cosine rule is Pythagoras with a correction term.**

**When to use:**
- Given 3 sides (SSS)
- Given 2 sides and included angle (SAS)

### The Projection Formula (Hidden Gem)

Any side is just the **shadow** of the other two sides.

```
a = b cos C + c cos B
b = c cos A + a cos C
c = a cos B + b cos A
```

> **Why use this?**
> It connects sides and angles **linearly** (no squares!).
> If a problem involves sums of cosines, **think Projection Formula.**

**When to use:**
- When cosine rule feels too heavy (avoiding squares)
- When you see expressions like b cos C + c cos B in a problem
- Quick verification of triangle relationships

---

## PAGE 16 — Solution of Triangles: Area and Special Points

### Area Formulas

| Formula | When to Use |
|---------|-------------|
| (1/2) × base × height | Height is known or easy to find |
| (1/2) ab sin C | Two sides and included angle |
| √[s(s−a)(s−b)(s−c)] | Three sides (Heron's formula) |
| rs | Inradius and semi-perimeter |
| abc / 4R | Circumradius known |

Where s = (a + b + c)/2 is the semi-perimeter.

### The Circumradius (R)

```
R = a / (2 sin A) = abc / (4 × Area)
```

> **R is the radius of the circle passing through all three vertices.**

### The Inradius (r)

```
r = Area / s = (s − a) tan(A/2)
```

> **r is the radius of the circle touching all three sides from inside.**

### JEE Insight

Many problems give relationships between R, r, and sides. The key connections:

```
Area = rs = abc / 4R
```

This links all the major quantities.

---

## PAGE 17 — What JEE Is REALLY Testing in Trigonometry

### JEE Main Tests:
- Standard identities
- Basic equations
- Direct evaluation using ASTC
- Simple inverse trig calculations
- Direct sine/cosine rule application

### JEE Advanced Tests:
- ASTC + reference angle for quick evaluation
- Graph transformations and range finding
- Inverse trig compositions and domain issues
- General solutions with constraints
- Solution of triangles with optimization
- Trigonometry + calculus combinations

> **Advanced problems punish identity memorization and reward structural thinking.**

---

## PAGE 18 — Skill-Based Examples (What Is Being Tested)

### Example 1 — ASTC Application
Find cos(225°).

1. 225° is in Q3 (between 180° and 270°)
2. Q3 → only Tan positive → cos is negative
3. Reference angle = 225° − 180° = 45°
4. cos(225°) = −cos(45°) = −1/√2

Skill tested: ASTC + reference angle (instant, no formula)

---

### Example 2 — Graph Transformation
Find the range of y = 2 sin(3x + π/4) − 1.

- Amplitude = 2, Vertical shift = −1
- Range = [−1 − 2, −1 + 2] = [−3, 1]

Skill tested: Direct application of [D − |A|, D + |A|]

---

### Example 3 — General Solution (Visual)
Solve: sin θ = 1/2

1. Principal solution: α = π/6 (sin π/6 = 1/2)
2. On unit circle: y = 1/2 intersects at π/6 and π − π/6 = 5π/6
3. General solution: θ = nπ + (−1)ⁿ(π/6)

Skill tested: Deriving from circle, not memorizing

---

### Example 4 — Inverse Trig Composition
Find: sin⁻¹(sin 5)

1. **Check Range:** 5 radians ≈ 5 × 57° = 285° (Quadrant IV)
2. **Target:** We need an angle in [−π/2, π/2] (Quadrant I or IV)
3. **Shift:** Subtract 2π to get into the principal range
   5 − 2π ≈ 5 − 6.28 = −1.28
4. **Verify:** −1.28 is in [−π/2, π/2] ✓

**Answer:** 5 − 2π

Skill tested: Check → Target → Shift → Verify method

---

### Example 5 — Solution of Triangle
In triangle ABC, a = 5, b = 7, C = 60°. Find c.

Using cosine rule (SAS case):
c² = a² + b² − 2ab cos C
c² = 25 + 49 − 2(5)(7)(1/2) = 74 − 35 = 39
c = √39

Skill tested: Recognizing SAS → cosine rule

---

### Example 6 — R-Formula
Find maximum of 3 sin x + 4 cos x.

Maximum = √(3² + 4²) = √25 = 5

Skill tested: Direct application of R = √(a² + b²)

---

## PAGE 19 — Common Trigonometry Traps (Exam Killers)

### Basic Trig Traps
- Forgetting ASTC (getting sign wrong)
- Mixing degrees and radians
- Wrong reference angle calculation
- Ignoring graph transformation parameters

### Equation Traps
- Forgetting to check for extraneous solutions
- Missing solutions when dividing by sin θ or cos θ (might be zero!)
- Wrong general solution pattern
- Not converting to principal solution first

### Inverse Trig Traps
- Assuming sin⁻¹(sin θ) = θ always (only true in principal range)
- Forgetting that cos⁻¹(−x) = π − cos⁻¹(x), not −cos⁻¹(x)
- Wrong domain for sec⁻¹ and cosec⁻¹

### Triangle Traps
- Using sine rule in SSA case without checking ambiguous case
- Forgetting that cosine rule always works for finding angles from sides
- Confusing R (circumradius) with r (inradius)

> **Most trig mistakes are thinking mistakes, not calculation mistakes.**

---

## PAGE 20 — Mental Checklist (Before Solving)

Before solving a trigonometry problem, ask:

1. Can **ASTC + reference angle** give me the answer directly?
2. Is this a **graph transformation** question? (Use A, B, C, D parameters)
3. For equations: Am I finding **all solutions** or just principal ones?
4. For inverse trig: Is the input in the **principal range**?
5. For triangles: Which rule applies — **sine or cosine**?
6. Is the **R-formula** useful? (max of a sin x + b cos x = √(a² + b²))
7. Can I **visualize on the unit circle** instead of using a formula?

This checklist saves **time and marks**.

---

## PAGE 21 — Why Trigonometry Appears Everywhere

Trigonometry appears everywhere because:
- Geometry needs ratios
- Vectors need projections
- Calculus needs periodic functions
- Physics needs oscillations and waves
- Navigation and astronomy need angle measurement

> **Trigonometry translates geometry into algebra.**

---

## PAGE 22 — Forward Connections

Trigonometry feeds directly into:
- **Calculus**: derivatives of sin & cos, integration techniques
- **Vectors**: components & projections
- **Complex Numbers**: Euler's formula, rotation
- **Coordinate Geometry**: polar coordinates, rotation of axes
- **Physics**: waves, oscillations, projectile motion

> **If algebra is structure and geometry is shape, trigonometry is direction.**
