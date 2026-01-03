---
title: Electromagnetism
parent: Physics
nav_order: 3
---

# Chapter 3 — ELECTROMAGNETISM
## Fields, Forces, and Flux

---

## PAGE 1 — Why Electromagnetism Exists (Mindset Reset)

Most students think:

> "Electromagnetism is about memorizing formulas for fields and circuits."

That is **not** its real purpose.

### Electromagnetism answers questions like:
- How do charges interact without touching?
- What carries force across empty space?
- How are electricity and magnetism connected?
- What is light?

> **Electromagnetism is the physics of fields — invisible structures that fill space.**

This is why electromagnetism governs:
- All electronic devices
- Light and all EM radiation
- Chemical bonding
- Virtually all everyday phenomena (except gravity)

---

## PAGE 2 — The Core Idea (Anchor Page)

### The Core Idea of Electromagnetism

> **Charges create fields. Fields exert forces.**

The field is the messenger between charges.
- Charge A creates a field everywhere in space
- Charge B feels the field at its location
- No instantaneous action at a distance

### The Two Fields

| Field | Created by | Acts on | Force |
|-------|-----------|---------|-------|
| Electric ($\vec{E}$) | Charges | Charges | $\vec{F} = q\vec{E}$ |
| Magnetic ($\vec{B}$) | Moving charges (currents) | Moving charges | $\vec{F} = q\vec{v} \times \vec{B}$ |

### The Deep Unity (Maxwell's Insight)

Electricity and magnetism are not separate phenomena.
They are two aspects of ONE thing: the electromagnetic field.

- A changing magnetic field creates an electric field (Faraday's Law)
- A changing electric field creates a magnetic field (Ampere-Maxwell Law)
- Light is an electromagnetic wave

> **This unity is why we can generate electricity from spinning magnets.**

---

## PAGE 3 — What Changes vs What Remains Invariant

| Aspect | Changes | Remains Invariant |
|--------|---------|-------------------|
| Field strength (with distance) | ✅ | ❌ |
| Potential (with position) | ✅ | ❌ |
| Current distribution | ✅ | ❌ |
| **Total Charge** | ❌ | ✅ |
| **Flux through closed surface** (Gauss) | ❌ | ✅ |
| **EMF = −dΦ/dt** (Faraday) | ❌ | ✅ |
| **Kirchhoff's Laws** (energy & charge) | ❌ | ✅ |

> **Conservation laws are your shortcuts in electromagnetism too.**

---

## PAGE 4 — Electrostatics: Charges at Rest

### Coulomb's Law: The Starting Point

$$\vec{F} = \frac{1}{4\pi\varepsilon_0}\frac{q_1 q_2}{r^2}\hat{r}$$

This is an inverse-square law, just like gravity.

Key constant: $k = \frac{1}{4\pi\varepsilon_0} = 9 \times 10^9$ N·m²/C²

### Electric Field

$$\vec{E} = \frac{\vec{F}}{q} = \frac{1}{4\pi\varepsilon_0}\frac{Q}{r^2}\hat{r}$$

Field due to point charge:
- Points radially outward (positive charge)
- Points radially inward (negative charge)
- Magnitude decreases as $1/r^2$

### Superposition Principle

Fields add as vectors:
$$\vec{E}_{total} = \vec{E}_1 + \vec{E}_2 + \vec{E}_3 + ...$$

> **This is the most powerful tool for complex charge distributions.**

---

## PAGE 5 — Gauss's Law: The Shortcut for Symmetry

### The Statement

$$\oint \vec{E} \cdot d\vec{A} = \frac{q_{enclosed}}{\varepsilon_0}$$

**In words:** Electric flux through any closed surface = (enclosed charge) / ε₀

### When to Use Gauss's Law

ONLY when symmetry makes $\vec{E}$ constant on a Gaussian surface:

| Symmetry | Gaussian Surface | Example |
|----------|-----------------|---------|
| Spherical | Sphere | Point charge, charged sphere |
| Cylindrical | Cylinder | Infinite line charge, wire |
| Planar | Pillbox | Infinite charged plane |

### Key Results from Gauss's Law

**Point charge / Outside sphere:** $E = \frac{1}{4\pi\varepsilon_0}\frac{Q}{r^2}$

**Infinite line charge:** $E = \frac{\lambda}{2\pi\varepsilon_0 r}$

**Infinite plane:** $E = \frac{\sigma}{2\varepsilon_0}$ (constant! doesn't depend on distance)

**Inside a conductor:** $E = 0$ (charges reside on surface)

> **Gauss's Law is the "Accountant Mode" for electrostatics.**

### The Cavity Superposition Trick

Problem: Find the field inside a spherical cavity within a uniformly charged solid sphere (density $\rho$).

Solution: Treat the hole as **Solid Sphere ($+\rho$) + Negative Sphere ($-\rho$)**.

```
Original sphere     =    Full sphere    +    "Negative" cavity
with cavity              (no hole)           (opposite charge)

   ╭───────╮            ╭───────╮            ╭───╮
   │   ○   │      =     │ ● ● ● │      +     │ ○ │
   │       │            │ ● ● ● │            ╰───╯
   ╰───────╯            ╰───────╯
```

**Result:**
Inside a spherical cavity, the Electric Field is **UNIFORM**:
$$\vec{E} = \frac{\rho \vec{d}}{3\varepsilon_0}$$

Where $\vec{d}$ is the vector from the sphere's center to the cavity's center.

> **A complicated integral becomes a constant vector. This works for gravity too!**

---

## PAGE 6 — Electric Potential: Energy per Charge

### What Potential Really Is

$$V = \frac{U}{q} = \frac{W_{ext}}{q}$$

Potential is the work done to bring unit positive charge from infinity.

### Potential vs Field

$$\vec{E} = -\nabla V = -\frac{dV}{dr}\hat{r}$$ (for radial symmetry)

$$V = -\int \vec{E} \cdot d\vec{r}$$

> **Field is the slope of potential. Steep slope = strong field.**

### Potential Due to Point Charge

$$V = \frac{1}{4\pi\varepsilon_0}\frac{Q}{r}$$

Note: Potential falls as $1/r$, not $1/r^2$.

### The "Method of Images" (The Mirror Trick)

Problem: A point charge $+q$ is placed at distance $d$ from a grounded infinite conducting plane.

**The Trick:** Replace the conductor with a "mirror image" charge $-q$ at distance $d$ on the other side.

```
Real charge        Grounded          Image charge
    +q             conductor             -q
     ●────────────────|────────────────●
    ←───d───→         |         ←───d───→
```

**Results:**
- **Force on real charge:** $F = \frac{1}{4\pi\varepsilon_0}\frac{q^2}{(2d)^2}$ (attractive)
- **Potential/Field:** Calculate using the pair $(+q, -q)$
- **Valid region:** Only on the side of the real charge

**For a charge near a grounded sphere (radius R):**
- Image charge: $q' = -\frac{R}{d}q$
- Image location: $d' = \frac{R^2}{d}$ from center

> **Never integrate induced charges. Just place the mirror image.**

### Equipotential Surfaces

- Surfaces where $V$ = constant
- Always perpendicular to field lines
- No work done moving charge along equipotential

### Potential Energy

$$U = qV = \frac{1}{4\pi\varepsilon_0}\frac{q_1 q_2}{r}$$

For a system of charges: sum over all pairs.

---

## PAGE 7 — Capacitors: Storing Charge and Energy

### Capacitance Definition

$$C = \frac{Q}{V}$$

Unit: Farad (F) = Coulomb/Volt

### Parallel Plate Capacitor

$$C = \frac{\varepsilon_0 A}{d}$$

With dielectric: $C = \frac{\kappa \varepsilon_0 A}{d}$

### Energy Stored

$$U = \frac{1}{2}CV^2 = \frac{1}{2}\frac{Q^2}{C} = \frac{1}{2}QV$$

### Capacitors in Circuits

**Series:**
$$\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + ...$$
(Same charge, voltage divides)

**Parallel:**
$$C_{eq} = C_1 + C_2 + ...$$
(Same voltage, charge divides)

> **Series for capacitors is like parallel for resistors. Opposite behavior.**

---

## PAGE 8 — Current Electricity: Charges in Motion

### Current and Current Density

$$I = \frac{dQ}{dt}$$

$$\vec{J} = \frac{I}{A}\hat{n} = nev_d$$

Where $v_d$ is drift velocity.

### Ohm's Law

**Microscopic:** $\vec{J} = \sigma\vec{E}$

**Macroscopic:** $V = IR$

Resistance: $R = \frac{\rho L}{A}$

### Temperature Dependence

$$\rho(T) = \rho_0[1 + \alpha(T - T_0)]$$

Metals: $\alpha > 0$ (resistance increases with temperature)
Semiconductors: $\alpha < 0$ (resistance decreases with temperature)

---

## PAGE 9 — Kirchhoff's Laws: Conservation in Circuits

### Junction Rule (KCL) — Conservation of Charge

$$\sum I_{in} = \sum I_{out}$$

Charge cannot accumulate at a junction.

### Loop Rule (KVL) — Conservation of Energy

$$\sum V = 0 \text{ around any closed loop}$$

Energy gained = Energy lost in one complete loop.

### Sign Conventions

Traversing a component in a loop:
- Resistor: Going with current → $-IR$; Against → $+IR$
- EMF: Going from − to + → $+\mathcal{E}$; From + to − → $-\mathcal{E}$

> **KVL is the First Law of Thermodynamics applied to circuits.**

---

## PAGE 10 — Circuit Analysis Techniques

### Equivalent Resistance

**Series:** $R_{eq} = R_1 + R_2 + ...$ (currents same)

**Parallel:** $\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + ...$ (voltages same)

### Symmetry Tricks

- If two points are at same potential by symmetry → no current flows between them
- Can remove or short-circuit that branch

### Wheatstone Bridge

When balanced: $\frac{R_1}{R_2} = \frac{R_3}{R_4}$

Current through galvanometer = 0 (null method)

### Power in Circuits

$$P = IV = I^2R = \frac{V^2}{R}$$

Maximum power transfer: When load resistance = source internal resistance.

---

## PAGE 11 — RC Circuits: Time-Dependent Behavior

### Charging a Capacitor

$$Q(t) = Q_0(1 - e^{-t/RC})$$
$$I(t) = I_0 e^{-t/RC}$$

Time constant: $\tau = RC$

After time $\tau$: Charge reaches 63% of final value.

### Discharging

$$Q(t) = Q_0 e^{-t/RC}$$
$$I(t) = -I_0 e^{-t/RC}$$

> **The time constant tells you how "fast" the circuit responds.**

---

## PAGE 12 — Magnetic Fields: Created by Moving Charges

### The Biot-Savart Law

$$d\vec{B} = \frac{\mu_0}{4\pi}\frac{I \, d\vec{l} \times \hat{r}}{r^2}$$

This is the magnetic analog of Coulomb's law.

### Magnetic Field Due to Common Sources

**Long straight wire:** $B = \frac{\mu_0 I}{2\pi r}$ (concentric circles)

**Center of circular loop:** $B = \frac{\mu_0 I}{2R}$

**On axis of loop:** $B = \frac{\mu_0 I R^2}{2(R^2 + x^2)^{3/2}}$

**Inside solenoid:** $B = \mu_0 n I$ (uniform, $n$ = turns per unit length)

**Inside toroid:** $B = \frac{\mu_0 NI}{2\pi r}$

### Ampere's Law

$$\oint \vec{B} \cdot d\vec{l} = \mu_0 I_{enclosed}$$

Use when there's symmetry (like Gauss's Law for E-fields).

---

## PAGE 13 — Force on Moving Charges and Currents

### Lorentz Force

$$\vec{F} = q(\vec{E} + \vec{v} \times \vec{B})$$

The magnetic part: $\vec{F} = q\vec{v} \times \vec{B}$

Key properties:
- Force perpendicular to both $\vec{v}$ and $\vec{B}$
- Magnetic force does NO work (perpendicular to displacement)
- Can change direction but not speed

### Motion in Magnetic Field

Charged particle in uniform B-field:
- Circular motion perpendicular to $\vec{B}$
- Radius: $r = \frac{mv}{qB}$
- Period: $T = \frac{2\pi m}{qB}$ (independent of velocity!)

If $\vec{v}$ has component parallel to $\vec{B}$: Helical motion.

### Force on Current-Carrying Wire

$$\vec{F} = I\vec{L} \times \vec{B}$$

For straight wire in uniform field: $F = BIL\sin\theta$

### Force Between Parallel Wires

$$\frac{F}{L} = \frac{\mu_0 I_1 I_2}{2\pi d}$$

- Parallel currents: Attract
- Antiparallel currents: Repel

> **This defines the Ampere: 1 A produces 2×10⁻⁷ N/m between wires 1 m apart.**

---

## PAGE 14 — Electromagnetic Induction: The Dynamic Connection

### Faraday's Law

$$\mathcal{E} = -\frac{d\Phi_B}{dt}$$

Magnetic flux: $\Phi_B = \int \vec{B} \cdot d\vec{A}$

For uniform field: $\Phi_B = BA\cos\theta$

### Lenz's Law (The Minus Sign)

> **The induced current opposes the change that causes it.**

This is energy conservation in action:
- If induced current aided the change → runaway process → infinite energy
- Nature prevents this

### Ways to Change Flux

1. Change B (varying field strength)
2. Change A (expanding/contracting loop)
3. Change θ (rotating loop)
4. Move loop in/out of field region

### Motional EMF

For a rod of length L moving with velocity v perpendicular to B:
$$\mathcal{E} = BLv$$

This is Faraday's Law in action: flux through circuit changes as rod moves.

### Rotating Rod EMF

For a rod of length $L$ rotating with angular velocity $\omega$ about one end in a uniform magnetic field $B$:

```
      ω ↺
       \
        \  L
         \
          ● pivot
```

Velocity varies along the rod: $v(r) = \omega r$

$$\mathcal{E} = \int_0^L B \cdot (\omega r) \, dr = \frac{1}{2}B\omega L^2$$

**Alternative form:** $\mathcal{E} = \frac{1}{2}BL \cdot v_{tip}$ where $v_{tip} = \omega L$

**The Faraday Disk (Rim to Axle):**
If a metal disk (or a spoke) of radius $R$ rotates with angular velocity $\omega$:
The EMF is generated between the **Center (Axle)** and the **Rim**.

$$\mathcal{E} = \frac{1}{2} B \omega R^2$$

> **Note:** If a rod rotates about its center, the potential difference between the two ends is **ZERO** (symmetry — both halves push electrons the same way). The potential difference between Center and End is $\frac{1}{8} B \omega L_{total}^2$.

> **The $\frac{1}{2}$ factor appears because velocity varies linearly. Compare to $KE = \frac{1}{2}mv^2$.**

---

## PAGE 15 — Inductors: Storing Energy in Magnetic Fields

### Self-Inductance

$$\mathcal{E} = -L\frac{dI}{dt}$$

Inductance of solenoid: $L = \mu_0 n^2 V = \frac{\mu_0 N^2 A}{l}$

### Energy Stored

$$U = \frac{1}{2}LI^2$$

Compare: Capacitor stores $\frac{1}{2}CV^2$ (energy in E-field)
Inductor stores $\frac{1}{2}LI^2$ (energy in B-field)

### LR Circuits

**Growth of current:**
$$I(t) = I_0(1 - e^{-Rt/L})$$

**Decay:**
$$I(t) = I_0 e^{-Rt/L}$$

Time constant: $\tau = L/R$

### LC Oscillations

$$\omega = \frac{1}{\sqrt{LC}}$$

Energy oscillates between capacitor (E-field) and inductor (B-field).
This is the electrical analog of mass-spring system.

---

## PAGE 16 — Alternating Current Circuits

### AC Voltage and Current

$$V = V_0 \sin(\omega t)$$
$$I = I_0 \sin(\omega t + \phi)$$

### Phasors: The Complex Number Trick

Represent AC quantities as rotating vectors.
- Voltage and current may not be in phase
- Phase difference $\phi$ determines power

### Impedance of Circuit Elements

| Element | Impedance | Phase of I relative to V |
|---------|-----------|-------------------------|
| Resistor | $R$ | In phase (φ = 0) |
| Capacitor | $X_C = \frac{1}{\omega C}$ | I leads V by 90° |
| Inductor | $X_L = \omega L$ | I lags V by 90° |

### Series LCR Circuit

$$Z = \sqrt{R^2 + (X_L - X_C)^2}$$

$$\tan\phi = \frac{X_L - X_C}{R}$$

### Resonance

At $\omega_0 = \frac{1}{\sqrt{LC}}$:
- $X_L = X_C$
- Impedance is minimum ($Z = R$)
- Current is maximum
- Power factor = 1

### Power in AC Circuits

$$P_{avg} = V_{rms} I_{rms} \cos\phi$$

Power factor = $\cos\phi$

For pure L or C: $\cos\phi = 0$ → No average power consumed.

---

## PAGE 17 — Electromagnetic Waves (Preview)

### Maxwell's Equations (The Complete Picture)

1. Gauss's Law (E): $\nabla \cdot \vec{E} = \rho/\varepsilon_0$
2. Gauss's Law (B): $\nabla \cdot \vec{B} = 0$ (no magnetic monopoles)
3. Faraday's Law: $\nabla \times \vec{E} = -\partial\vec{B}/\partial t$
4. Ampere-Maxwell: $\nabla \times \vec{B} = \mu_0\vec{J} + \mu_0\varepsilon_0\partial\vec{E}/\partial t$

### The Wave Equation

Maxwell showed: Changing E creates B, changing B creates E.
Result: Self-propagating electromagnetic wave.

Speed: $c = \frac{1}{\sqrt{\mu_0 \varepsilon_0}} = 3 \times 10^8$ m/s

> **Light is an electromagnetic wave. Maxwell unified optics with electromagnetism.**

---

## PAGE 18 — What JEE Is REALLY Testing

### JEE Main Tests:
- Direct application of formulas
- Simple circuit analysis
- Basic field calculations
- Single-concept problems

### JEE Advanced Tests:
- Gauss's Law for non-trivial geometries
- Complex circuit analysis (symmetry, delta-star)
- Induced EMF with changing geometry
- Combining electrostatics with mechanics
- LCR circuit analysis

> **Advanced problems often require recognizing when to use conservation (Gauss, Kirchhoff) vs direct calculation.**

---

## PAGE 19 — Skill-Based Examples (What Is Being Tested)

### Example 1 — Gauss's Law

A non-conducting sphere has charge density $\rho = kr$. Find E inside.

Using Gauss: $E \cdot 4\pi r^2 = \frac{1}{\varepsilon_0}\int_0^r \rho \cdot 4\pi r^2 dr$

Skill tested: Setting up Gaussian surface, correct integration

---

### Example 2 — Kirchhoff's Laws

Three loops, three unknowns. Write loop equations, solve simultaneously.

Skill tested: Systematic application of KVL, sign conventions

---

### Example 3 — Induced EMF

A square loop moves with velocity v through a region where B changes linearly with x.
Find induced EMF.

Skill tested: Flux calculation, differentiation

---

## PAGE 20 — Common Electromagnetism Traps (Exam Killers)

### Electrostatics Traps
- Using Gauss's Law without symmetry
- Confusing field (vector) with potential (scalar)
- Forgetting E = 0 inside conductor

### Circuit Traps
- Wrong sign convention in Kirchhoff loops
- Confusing series/parallel for R vs C
- Forgetting internal resistance of battery

### Magnetic Field Traps
- Wrong right-hand rule application
- Forgetting magnetic force is perpendicular (no work)
- Using Ampere's Law without enclosed current

### Induction Traps
- Forgetting the minus sign (Lenz's Law)
- Not identifying what's changing in flux
- Confusing EMF with potential difference

> **Most errors come from not checking the physical situation before applying formulas.**

---

## PAGE 21 — Mental Checklist (Before Solving)

Before solving an electromagnetism problem, ask:

1. **Electrostatics or current?** (Static charges vs moving charges)
2. **Is there symmetry?** (Use Gauss's Law or Ampere's Law)
3. **What's the field source?** (Point charge, wire, loop, plane)
4. **Is flux changing?** (Faraday's Law applies)
5. **What's conserved?** (Charge at junctions, energy in loops)
6. **Vector or scalar?** (Fields are vectors, potentials are scalars)

> **Identify the physics first. Then choose the tool.**

---

## PAGE 22 — Forward Connections

Electromagnetism connects to:
- **Mechanics:** Charged particle motion, Lorentz force
- **Waves:** EM waves, light
- **Modern Physics:** Photoelectric effect, atomic spectra
- **Chemistry:** Bonding, electrochemistry
- **Engineering:** All electronics, power systems, communications

> **Electromagnetism is the foundation of modern technology.**
