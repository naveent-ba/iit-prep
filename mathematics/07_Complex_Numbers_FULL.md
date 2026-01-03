---
title: Complex Numbers
parent: Mathematics
nav_order: 7
---

# Chapter 7 — COMPLEX NUMBERS
## Rotation, Algebra in 2D, and Completeness

---

## PAGE 1 — Why Complex Numbers Exist (Mindset Reset)

Most students think:

> “Complex numbers are imaginary. They are about √(-1).”

That is a terrible name and a misleading view.

### Complex Numbers answer questions like:
- How do we solve equations that have no real solution ($x^2 + 1 = 0$)?
- How can we do algebra in **two dimensions** at once?
- How do we describe **rotation** mathematically?
- How do we compute alternating currents and waves?

> **Complex numbers are not imaginary. They are rotational.**

This is why they appear in:
- electrical engineering (AC circuits)
- quantum mechanics
- fluid dynamics
- signal processing

Complex numbers are **algebra that can rotate**.

---

## PAGE 2 — The Core Idea (Anchor Page)

### The Core Idea of Complex Numbers

> **A complex number is a point (or vector) in a 2D plane.**

In Real numbers:
- Multiplication by $-1$ is a **180° flip**.

In Complex numbers:
- Multiplication by $i$ is a **90° rotation**.
- Multiplication by $i^2$ is two 90° rotations = 180° flip ($-1$).

> **$i$ is an operator that rotates a number by 90°.**

---

## PAGE 3 — What Changes vs What Remains Invariant

| Aspect | Changes | Remains Invariant |
|------|--------|-------------------|
| Coordinates ($x, y$) | ✅ | ❌ |
| Argument (Angle) | ✅ | ❌ |
| Modulus (Distance from origin) | ❌ | ✅ (under rotation) |
| Structure ($z \cdot \bar{z} = |z|^2$) | ❌ | ✅ |

> **JEE problems often hide geometry inside complex algebra.**
> If you see $|z - z_0| = r$, do not solve algebraically.
> **See the Circle.**

---

## PAGE 4 — Forms of Representation (The Toolbox)

You must be fluent in switching forms.

### 1. Cartesian Form ($z = x + iy$)
- Good for: Addition, Subtraction.
- Bad for: Multiplication, Powers, Roots.

### 2. Polar Form ($z = r(\cos\theta + i\sin\theta)$)
- Good for: Visualization.
- Connects directly to **Trigonometry**.

### 3. Euler’s Form ($z = re^{i\theta}$) — **THE SUPERPOWER**
- The most powerful tool in JEE.
- Multiplication becomes addition of angles.
- Roots become division of angles.

> **If the problem involves high powers ($z^{20}$) or rotation, ALWAYS use Euler’s form.**

---

## PAGE 5 — The Geometry of Modulus and Argument

### Modulus ($|z|$)
> **$|z|$ is the distance from the origin.**
> **$|z_1 - z_2|$ is the distance between two points.**

### Argument ($\arg z$)
> **$\arg z$ is the direction (angle with positive real axis).**

### Example:
Equation: $|z - 3| = |z - 5|$
- **Algebraic way:** Put $z = x + iy$, square both sides, solve. (Slow)
- **Geometric way:** Distance from 3 equals distance from 5.
- **Result:** Perpendicular bisector of the line joining 3 and 5. (Instant)

> **Geometry beats Algebra in Complex Numbers.**

---

## PAGE 6 — Rotation Theorem (Coni Method)

This is a specific JEE Advanced favorite.

To rotate a vector $z_1$ to $z_2$ by angle $\alpha$:

(Final Vector) = (Initial Vector) × e^(iα)

This relates three things:
1. Lengths
2. Angles
3. Coordinates

> **Rotation is multiplication by $e^{i\theta}$.**

---

## PAGE 7 — Cube Roots and $n$-th Roots of Unity

Roots of unity are not just numbers.
They are **vertices of a regular polygon**.

### Cube Roots ($1, \omega, \omega^2$)
- Form an equilateral triangle on the unit circle.
- $1 + \omega + \omega^2 = 0$ (Centroid is at origin).

### $n$-th Roots
- Form a regular $n$-sided polygon.
- Sum of all roots = 0.

> **Whenever you see $\omega$, think "Rotation by 120°".**

---

## PAGE 8 — What JEE Is REALLY Testing in Complex Numbers

### JEE Main Tests:
- basic algebra ($i$ powers, rationalizing)
- finding modulus and argument
- simple loci (circle equations)

### JEE Advanced Tests:
- **Geometry translation**: interpreting algebraic equations as shapes.
- **Rotation**: using $e^{i\theta}$ to solve triangle/square problems.
- **Inequalities**: Using Triangle Inequality $|z_1 + z_2| \leq |z_1| + |z_2|$.
- **Roots of Unity**: Series summation using geometric progression.

> **Advanced problems punish those who use $z = x+iy$ for everything.**

---

## PAGE 9 — Skill-Based Examples (What Is Being Tested)

### Example 1 — Locus Identification
Identify the locus:

|z - 2i| = 3

Skill tested:
- Recognition of circle equation (Center $2i$, Radius 3).
- No calculation needed.

---

### Example 2 — Minimum Value (Geometry)
Find minimum of $|z - 1| + |z - 3i|$.
Skill tested:
- Triangle inequality.
- Shortest distance between two points is a straight line.

---

### Example 3 — Rotational Logic
If $z_1, z_2, z_3$ form an equilateral triangle...
Skill tested:
- Rotation theorem ($z_3 - z_1 = (z_2 - z_1)e^{i\pi/3}$).
- Relationship between vertices.

---

## PAGE 10 — Common Complex Number Traps (Exam Killers)

- assuming $\sqrt{a} \sqrt{b} = \sqrt{ab}$ when $a,b$ are negative (FALSE).
- forgetting that Inequalities ($z_1 < z_2$) **do not exist** in complex numbers.
- blindly substituting $x+iy$ into tedious equations.
- ignoring the "Principal Argument" range ($-\pi < \theta \leq \pi$).

> **You cannot compare complex numbers. You can only compare their magnitudes.**

---

## PAGE 11 — Mental Checklist (Before Solving)

Before solving a Complex Number problem, ask:

1. Is this actually a **Geometry** problem (distance/circle)?
2. Can I use **Euler’s form** ($re^{i\theta}$) to simplify multiplication?
3. Is **Rotation** involved?
4. Are **Roots of Unity** ($\omega$) hiding here?
5. Should I vectorize ($z_2 - z_1$)?

This checklist saves **massive calculation time**.

---

## PAGE 12 — Why Complex Numbers Are the "Complete" Number System

Real numbers are a line.
Complex numbers are a plane.

Complex numbers are "algebraically closed":
- Every polynomial of degree $n$ has exactly $n$ roots.
- No more "no solution."

> **Complex numbers complete the logic of Algebra.**

---

## PAGE 13 — Forward Connections

Complex Numbers feed directly into:
- Vectors (2D vectors behave like complex numbers)
- Coordinate Geometry (Rotation of axes)
- Calculus (Integration techniques)
- Physics (Alternating Current, Optics)

> **If Algebra is structure, Complex Numbers are Algebra with direction.**