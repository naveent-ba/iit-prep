---
title: Mechanics
parent: Physics
nav_order: 1
---

# Chapter 1 — MECHANICS
## Motion, Force, and Conservation

---

## PAGE 1 — Why Mechanics Exists (Mindset Reset)

Most students think:

> "Mechanics is about applying formulas to pulleys and inclined planes."

That is **not** its real purpose.

### Mechanics answers questions like:
- Why do objects move the way they do?
- What makes motion change?
- What quantities remain constant during motion?
- How can we predict where something will be?

> **Mechanics is the grammar of motion.**

This is why mechanics dominates:
- JEE Physics (35-40% of the paper)
- Engineering design
- Space exploration
- Every physical system that moves

Mechanics is not a chapter. It is the **foundation** of all physics.

---

## PAGE 2 — The Core Idea (Anchor Page)

### The Core Idea of Mechanics

> **Motion changes only when forced to change.**

This is Newton's insight: Objects don't "want" to stop. They don't "want" to move.
They simply continue whatever they're doing unless something intervenes.

### The Three Levels of Mechanics

| Level | Question | Tool |
|-------|----------|------|
| **Kinematics** | Where is it? How fast? | Position, velocity, acceleration |
| **Dynamics** | Why does it move that way? | Force, Newton's Laws |
| **Conservation** | What remains unchanged? | Energy, Momentum, Angular Momentum |

> **JEE rewards those who operate at Level 3 (Conservation) instead of Level 2 (Forces).**

---

## PAGE 3 — What Changes vs What Remains Invariant

| Aspect | Changes | Remains Invariant |
|--------|---------|-------------------|
| Position | ✅ | ❌ |
| Velocity | ✅ | ❌ |
| Acceleration | ✅ | ❌ |
| Force | ✅ | ❌ |
| **Total Energy** (closed system) | ❌ | ✅ |
| **Total Momentum** (no external force) | ❌ | ✅ |
| **Angular Momentum** (no external torque) | ❌ | ✅ |

> **Everything observable changes. The conserved quantities are hidden — and powerful.**

---

## PAGE 4 — Kinematics: Describing Motion (Before Explaining It)

### What Kinematics Really Is

> **Kinematics describes motion without asking "why."**

It answers:
- Where is the object? → Position
- How fast is it moving? → Velocity
- How fast is velocity changing? → Acceleration

### The Calculus Connection (Critical for JEE Advanced)

```
Position x(t)
    ↓ derivative
Velocity v = dx/dt
    ↓ derivative
Acceleration a = dv/dt = d²x/dt²
```

Going backwards (integration):
```
Acceleration a(t)
    ↓ integrate
Velocity v = ∫a dt
    ↓ integrate
Position x = ∫v dt
```

### The SUVAT Equations (Only When a = constant)

These are shortcuts derived from calculus. Use ONLY when acceleration is constant:

| Equation | Missing Variable |
|----------|------------------|
| $v = u + at$ | $s$ |
| $s = ut + \frac{1}{2}at^2$ | $v$ |
| $v^2 = u^2 + 2as$ | $t$ |
| $s = \frac{(u+v)}{2}t$ | $a$ |

> **If acceleration varies, you MUST use calculus. SUVAT will give wrong answers.**

### Projectile Motion: Two Independent Worlds

A projectile is NOT one motion. It is TWO separate motions:

| Direction | Acceleration | What happens |
|-----------|--------------|--------------|
| Horizontal | 0 | Constant velocity |
| Vertical | g (downward) | Free fall |

> **The horizontal and vertical motions don't talk to each other.**

This is why time is the bridge: both motions share the same $t$.

### Relative Motion: Changing the Observer

Velocity depends on who's watching.

**The Rule:**
$$\vec{v}_{A/B} = \vec{v}_A - \vec{v}_B$$

"Velocity of A relative to B" = "Velocity of A" minus "Velocity of B"

**The Rain Problem Pattern:**
- Rain falls vertically (velocity $\vec{v}_r$)
- You move horizontally (velocity $\vec{v}_m$)
- Rain appears to come at angle: $\vec{v}_{rain/you} = \vec{v}_r - \vec{v}_m$

> **Change your reference frame to simplify the problem.**

---

## PAGE 5 — Newton's Laws: The "Why" of Motion

### First Law: The Default State

> **An object continues in its state of motion unless acted upon by a net force.**

This defines what force IS: the thing that changes motion.

### Second Law: The Quantitative Rule

$$\vec{F}_{net} = m\vec{a}$$

This is a VECTOR equation. It means:
- Forces in x-direction affect only x-acceleration
- Forces in y-direction affect only y-acceleration

### Third Law: The Interaction Rule

> **Forces come in pairs. Always.**

If A pushes B, then B pushes A with equal magnitude, opposite direction.

> **The Third Law is about two DIFFERENT objects, not the same object.**

### Pseudo Force (The Correction Factor)

Newton's Laws fail in accelerating (non-inertial) frames.
To fix them, you must add a **"Ghost Force"**.

$$\vec{F}_{pseudo} = -m \vec{a}_{frame}$$

**Direction:** Opposite to the acceleration of the observer.
**Magnitude:** Mass of object × Acceleration of observer.

**When to use:**
- Pendulum in accelerating car → Add $ma$ horizontally backward
- Block on accelerating wedge → Add $ma$ opposite to wedge acceleration
- Object in rotating frame → Add centrifugal force $m\omega^2 r$ outward

> **Use this for pendulums in cars, blocks on accelerating wedges, and centrifugal force.**

### The Free Body Diagram (FBD): Your Essential Tool

**The Rules:**
1. Isolate ONE object
2. Draw ALL forces acting ON that object
3. Do NOT include forces that object exerts on others
4. Choose coordinates aligned with motion

**Common Forces:**

| Force | Symbol | Direction | When it appears |
|-------|--------|-----------|-----------------|
| Weight | $mg$ | Downward | Always (near Earth) |
| Normal | $N$ | Perpendicular to surface | Contact with surface |
| Tension | $T$ | Along string, away from object | String attached |
| Friction | $f$ | Opposite to motion/tendency | Rough surface |
| Spring | $kx$ | Toward equilibrium | Spring attached |

### Friction: The Force That Resists

**Static Friction** (not moving yet):
- $f_s \leq \mu_s N$
- Adjusts to prevent motion
- Maximum value = $\mu_s N$

**Kinetic Friction** (already moving):
- $f_k = \mu_k N$
- Constant value (doesn't depend on speed)
- Usually $\mu_k < \mu_s$

> **Static friction is variable. Kinetic friction is fixed.**

---

## PAGE 6 — Constraint Motion: When Objects Are Connected

### The Principle

> **Constraints reduce freedom. Use them to relate motions.**

### String Constraints

**Inextensible string:** Length is constant → Velocities at ends are related.

**Pulley Rule:** If string length is constant:
$$\sum (\text{lengths on each side}) = \text{constant}$$
$$\Rightarrow \sum (\text{velocity components along string}) = 0$$

### The "Virtual Work" Trick (Power Method)

Instead of writing lengths, use this invariant:

> **Net power delivered by internal tension is ZERO.**

$$\sum \vec{T} \cdot \vec{v} = 0 \quad \text{and} \quad \sum \vec{T} \cdot \vec{a} = 0$$

**How to use:**
1. Draw Tensions on all blocks.
2. If T and v are in same direction: $+Tv$
3. If T and v are in opposite directions: $-Tv$
4. Sum = 0. Solve for unknown.

**Example:** Two blocks connected over pulley. Block 1 (mass m) goes down with velocity v₁, Block 2 (mass 2m) goes up with velocity v₂.

$T \cdot v_1 - T \cdot v_2 = 0 \Rightarrow v_1 = v_2$

> **This solves complex multi-pulley problems in one line.**

### Wedge Constraints

When a block slides on a wedge:
- Block has velocity relative to wedge
- Wedge may have velocity relative to ground
- Components perpendicular to wedge surface must match (no separation)

> **Write the constraint equation FIRST. Then apply Newton's laws.**

---

## PAGE 7 — Work and Energy: The Accountant's First Tool

### What Work Really Is

> **Work is energy transfer via force.**

$$W = \vec{F} \cdot \vec{d} = Fd\cos\theta$$

Key insight: Only the force component ALONG the displacement does work.

| Angle | $\cos\theta$ | Work |
|-------|--------------|------|
| 0° (same direction) | +1 | Positive (energy in) |
| 90° (perpendicular) | 0 | Zero |
| 180° (opposite) | −1 | Negative (energy out) |

### The Work-Energy Theorem

$$W_{total} = \Delta KE = \frac{1}{2}mv_f^2 - \frac{1}{2}mv_i^2$$

> **This works even when forces vary. It's the bridge between force and energy.**

### Conservative vs Non-Conservative Forces

| Conservative | Non-Conservative |
|--------------|------------------|
| Gravity, Spring, Electrostatic | Friction, Air resistance, Applied force |
| Work depends only on endpoints | Work depends on path |
| Can define Potential Energy | Cannot define Potential Energy |
| Mechanical energy conserved | Mechanical energy not conserved |

### Potential Energy: Stored Work

$$U = -W_{conservative}$$

**Common Potential Energies:**
- Gravitational: $U = mgh$ (near Earth)
- Gravitational: $U = -\frac{GMm}{r}$ (general)
- Spring: $U = \frac{1}{2}kx^2$

### Conservation of Mechanical Energy

If ONLY conservative forces do work:
$$KE_i + PE_i = KE_f + PE_f$$

> **This is the fastest way to solve most mechanics problems.**

---

## PAGE 8 — Power: Rate of Energy Transfer

$$P = \frac{dW}{dt} = \vec{F} \cdot \vec{v}$$

For constant force along velocity:
$$P = Fv$$

### The Car on Hill Problem

At constant speed up a hill:
- Engine force = $mg\sin\theta + f$ (balances gravity + friction)
- Power = Force × velocity
- Maximum speed at full power: $v_{max} = \frac{P_{max}}{F}$

---

## PAGE 9 — Momentum: The Accountant's Second Tool

### What Momentum Really Is

> **Momentum is "quantity of motion" — mass in motion.**

$$\vec{p} = m\vec{v}$$

### Newton's Second Law (General Form)

$$\vec{F}_{net} = \frac{d\vec{p}}{dt}$$

When mass is constant, this becomes $F = ma$.
When mass varies (rockets, conveyor belts), use this form.

### Conservation of Linear Momentum

If $\vec{F}_{ext} = 0$:
$$\vec{p}_{initial} = \vec{p}_{final}$$

> **This works even when internal forces are huge (explosions, collisions).**

### Impulse: When Forces Are Brief

$$\vec{J} = \int \vec{F} \, dt = \Delta \vec{p}$$

For collisions:
- Force is huge but acts briefly
- We don't know $F(t)$, but we know the impulse

---

## PAGE 10 — Collisions: Conservation in Action

### The Two Conservation Questions

1. **Is momentum conserved?**
   - Yes, if no external force (always true for collisions)

2. **Is kinetic energy conserved?**
   - Elastic: Yes
   - Inelastic: No

### Types of Collisions

| Type | Momentum | Kinetic Energy | Example |
|------|----------|----------------|---------|
| Elastic | Conserved | Conserved | Billiard balls (ideal) |
| Inelastic | Conserved | NOT conserved | Car crash |
| Perfectly Inelastic | Conserved | Maximum loss | Objects stick together |

### The 1D Elastic Collision Formula

For two objects colliding elastically:
$$v_1' = \frac{(m_1-m_2)v_1 + 2m_2 v_2}{m_1+m_2}$$
$$v_2' = \frac{(m_2-m_1)v_2 + 2m_1 v_1}{m_1+m_2}$$

**Special Cases:**
- Equal masses: Velocities exchange
- Heavy hits light (at rest): Light moves at 2× heavy's velocity
- Light hits heavy (at rest): Light bounces back, heavy barely moves

### Coefficient of Restitution

$$e = \frac{\text{velocity of separation}}{\text{velocity of approach}} = \frac{v_2' - v_1'}{v_1 - v_2}$$

- $e = 1$: Perfectly elastic
- $e = 0$: Perfectly inelastic
- $0 < e < 1$: Real collisions

### Oblique Collisions (2D)

When objects collide at an angle, split the universe into two directions:

```
            Common Tangent
                 ↑
                 │
    ○ ──────────●──────────→ Line of Impact (LOI)
                 │            (Common Normal)
                 │
```

1. **Line of Impact (LOI):** The common normal at contact point.
   - Momentum changes here.
   - Apply $e$ (restitution) here: $v_{sep} = e \cdot v_{app}$

2. **Common Tangent:** Perpendicular to LOI.
   - **Momentum is CONSERVED here** (no force along tangent for smooth surfaces).
   - Velocity component unchanged.

**The Method:**
1. Resolve velocities into LOI and tangent components
2. Apply collision formulas ONLY along LOI
3. Tangent components remain unchanged
4. Recombine to get final velocities

> **Solve the two directions independently, then recombine.**

---

## PAGE 11 — Center of Mass: The System's Representative Point

### What COM Really Is

> **The center of mass moves as if all mass were concentrated there.**

$$\vec{r}_{cm} = \frac{\sum m_i \vec{r}_i}{\sum m_i}$$

### The Key Property

$$\vec{F}_{ext} = M_{total} \vec{a}_{cm}$$

The COM of a system accelerates based on EXTERNAL forces only.
Internal forces cannot move the COM.

### Applications

**Rocket propulsion:** COM stays fixed (or moves uniformly) if no external force.
- Rocket goes one way, exhaust goes the other
- Momentum is conserved

**Finding COM by symmetry:**
- Uniform objects: COM at geometric center
- Composite objects: Weighted average of component COMs

---

## PAGE 12 — Rotational Motion: Angular Analogs

### The Translation-Rotation Dictionary

| Linear | Angular | Relation |
|--------|---------|----------|
| Position $x$ | Angle $\theta$ | $x = r\theta$ |
| Velocity $v$ | Angular velocity $\omega$ | $v = r\omega$ |
| Acceleration $a$ | Angular acceleration $\alpha$ | $a_t = r\alpha$ |
| Mass $m$ | Moment of Inertia $I$ | $I = \sum m_i r_i^2$ |
| Force $F$ | Torque $\tau$ | $\tau = r \times F$ |
| Momentum $p$ | Angular Momentum $L$ | $L = I\omega$ or $L = r \times p$ |
| $F = ma$ | $\tau = I\alpha$ | — |

> **Every linear concept has a rotational twin.**

### Moment of Inertia: Rotational Mass

$$I = \int r^2 \, dm$$

It measures resistance to angular acceleration.

**Common Moments of Inertia:**

| Object | Axis | $I$ |
|--------|------|-----|
| Solid cylinder/disk | Through center | $\frac{1}{2}MR^2$ |
| Hollow cylinder | Through center | $MR^2$ |
| Solid sphere | Through center | $\frac{2}{5}MR^2$ |
| Hollow sphere | Through center | $\frac{2}{3}MR^2$ |
| Rod | Through center | $\frac{1}{12}ML^2$ |
| Rod | Through end | $\frac{1}{3}ML^2$ |

### Parallel and Perpendicular Axis Theorems

**Parallel Axis:**
$$I = I_{cm} + Md^2$$

**Perpendicular Axis (for flat objects in xy-plane):**
$$I_z = I_x + I_y$$

---

## PAGE 13 — Torque and Angular Momentum

### Torque: The Rotational Force

$$\vec{\tau} = \vec{r} \times \vec{F}$$

Magnitude: $\tau = rF\sin\theta = r_\perp F = r F_\perp$

> **Torque depends on WHERE the force is applied, not just how strong it is.**

### Angular Momentum

For a particle: $\vec{L} = \vec{r} \times \vec{p}$

For a rigid body: $L = I\omega$

### Conservation of Angular Momentum

If $\vec{\tau}_{ext} = 0$:
$$\vec{L}_i = \vec{L}_f$$

**The Ice Skater Effect:**
- Arms out: Large $I$, small $\omega$
- Arms in: Small $I$, large $\omega$
- $L = I\omega$ stays constant

---

## PAGE 14 — Rolling Motion: Rotation + Translation

### Pure Rolling Condition

$$v_{cm} = R\omega$$

No slipping means the contact point has zero velocity relative to ground.

### Kinetic Energy of Rolling Object

$$KE = \frac{1}{2}mv_{cm}^2 + \frac{1}{2}I\omega^2 = \frac{1}{2}mv_{cm}^2\left(1 + \frac{I}{mR^2}\right)$$

### Rolling Down an Incline

Using energy conservation:
$$mgh = \frac{1}{2}mv^2\left(1 + \frac{I}{mR^2}\right)$$

Objects with smaller $I/mR^2$ roll faster.

**Race down the incline:**
1. Sliding block (no rotation): Fastest
2. Solid sphere ($I/mR^2 = 2/5$): Faster
3. Solid cylinder ($I/mR^2 = 1/2$): Medium
4. Hollow sphere ($I/mR^2 = 2/3$): Slower
5. Hollow cylinder ($I/mR^2 = 1$): Slowest

---

## PAGE 15 — Gravitation: The Universal Force

### Newton's Law of Gravitation

$$F = \frac{GMm}{r^2}$$

This is an inverse-square law, like Coulomb's law.

### Gravitational Field and Potential

Field: $\vec{g} = -\frac{GM}{r^2}\hat{r}$ (points toward mass)

Potential: $V = -\frac{GM}{r}$ (negative, zero at infinity)

Potential Energy: $U = -\frac{GMm}{r}$

> **Negative potential energy means the system is bound.**

### Orbital Motion

**Orbital velocity:** $v_o = \sqrt{\frac{GM}{r}}$

**Escape velocity:** $v_e = \sqrt{\frac{2GM}{r}} = \sqrt{2} \cdot v_o$

**Total energy in orbit:** $E = -\frac{GMm}{2r}$ (negative = bound)

### Kepler's Laws (Conservation in Disguise)

1. **Elliptical orbits:** Planets orbit in ellipses with Sun at focus
2. **Equal areas in equal times:** Angular momentum is conserved
3. **$T^2 \propto r^3$:** Period squared proportional to semi-major axis cubed

> **Kepler's 2nd Law is angular momentum conservation for central forces.**

---

## PAGE 16 — What JEE Is REALLY Testing

### JEE Main Tests:
- Direct formula application
- Single-concept problems
- Standard FBD situations
- Basic conservation problems

### JEE Advanced Tests:
- Multi-concept integration (energy + momentum)
- Constraint motion in complex systems
- Rotational + translational combination
- Variable mass systems (rockets)
- Non-standard reference frames

> **Advanced problems combine 2-3 concepts in one question.**

---

## PAGE 17 — Skill-Based Examples (What Is Being Tested)

### Example 1 — Energy vs Force Method

A block slides down a frictionless incline from height $h$. Find its speed at the bottom.

**Force method:** Draw FBD, find acceleration, use kinematics. (5+ steps)

**Energy method:** $mgh = \frac{1}{2}mv^2 \Rightarrow v = \sqrt{2gh}$ (1 step)

Skill tested: Choosing the right approach

---

### Example 2 — Momentum Conservation

Two blocks ($m$ and $2m$) on a frictionless surface are connected by a compressed spring. Released from rest. Find their velocities.

- No external horizontal force → momentum conserved
- Initial momentum = 0 → Final momentum = 0
- $mv_1 = 2mv_2$ in opposite directions

Skill tested: Recognizing when to use conservation

---

### Example 3 — Rolling Motion

A solid sphere rolls down an incline of height $h$. Find its speed at the bottom.

$$mgh = \frac{1}{2}mv^2 + \frac{1}{2}I\omega^2 = \frac{1}{2}mv^2 + \frac{1}{2}\cdot\frac{2}{5}mR^2\cdot\frac{v^2}{R^2}$$
$$mgh = \frac{7}{10}mv^2$$
$$v = \sqrt{\frac{10gh}{7}}$$

Skill tested: Combined rotation and translation

---

## PAGE 18 — Common Mechanics Traps (Exam Killers)

### Force/FBD Traps
- Forgetting normal force changes on inclines
- Including forces the object exerts (instead of forces ON it)
- Assuming tension is same when pulley has mass

### Energy Traps
- Using $mgh$ when $h$ is not vertical height
- Forgetting rotational kinetic energy
- Applying conservation when friction is present

### Momentum Traps
- Forgetting momentum is a vector
- Applying conservation when external force exists
- Confusing elastic and inelastic

### Rotation Traps
- Using wrong axis for moment of inertia
- Forgetting parallel axis theorem
- Confusing $\omega$ and $v$ in rolling

> **Most errors come from applying formulas without checking conditions.**

---

## PAGE 19 — Mental Checklist (Before Solving)

Before solving a mechanics problem, ask:

1. **Can I use energy conservation?** (Check: no friction, no inelastic collision)
2. **Can I use momentum conservation?** (Check: no external force)
3. **Can I use angular momentum conservation?** (Check: no external torque)
4. **Is there a constraint?** (String, surface, hinge)
5. **Is rotation involved?** (Don't forget rotational KE and angular momentum)
6. **What is my reference frame?** (Ground? Moving object?)

> **Run this checklist before writing $F = ma$.**

---

## PAGE 20 — Forward Connections

Mechanics feeds directly into:
- **Thermodynamics:** Work, energy, and the First Law
- **Electromagnetism:** Charged particle motion, Lorentz force
- **Waves:** SHM as foundation for all wave motion
- **Modern Physics:** Relativistic mechanics, quantum angular momentum

> **Mechanics is not one chapter. It is the foundation of all physics.**
