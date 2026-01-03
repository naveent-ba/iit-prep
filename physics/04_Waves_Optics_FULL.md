---
title: Waves & Optics
parent: Physics
nav_order: 4
---

# Chapter 4 — WAVES & OPTICS
## Oscillation, Propagation, and Light

---

## PAGE 1 — Why Waves Exist (Mindset Reset)

Most students think:

> "Waves are about memorizing formulas for interference and lens equations."

That is **not** their real purpose.

### Waves answer questions like:
- How does disturbance travel without matter traveling?
- What happens when multiple disturbances meet?
- How does light bend, split, and interfere?
- Why do musical instruments produce specific notes?

> **Waves are energy in motion — without matter in motion.**

---

## PAGE 2 — The Core Idea (Anchor Page)

### The Core Idea of Waves

> **A wave is a disturbance that carries energy, not matter.**

When you shake one end of a rope:
- The shake travels down the rope
- The rope itself doesn't travel
- Energy moves; matter oscillates in place

### The One Rule That Solves Many Problems

> **Frequency NEVER changes when a wave enters a new medium.**

Speed changes. Wavelength changes. Frequency stays the same.

Why? Because the source determines frequency, and the source doesn't change when the wave enters a new medium.

---

## PAGE 3 — Simple Harmonic Motion: The Foundation

### What SHM Really Is

> **SHM = Motion where the restoring force is proportional to displacement.**

$$F = -kx \implies a = -\omega^2 x$$

The minus sign is crucial: force always points TOWARD equilibrium.

### Visualizing SHM: The Circle Connection

```
Imagine a point moving in a circle at constant speed.

        * ← point on circle
       /|
      / |
     /  | ← vertical projection = SHM!
    /   |
   ●----+---- center

The shadow of circular motion on a wall IS simple harmonic motion.
```

This is why SHM uses sin and cos — they come from circular motion!

### The Phase Confusion: Solved

**What is phase (φ)?**

Phase tells you: "Where in the cycle is the particle at t = 0?"

```
Phase = 0:        Starts at equilibrium, moving right
Phase = π/2:      Starts at +A (maximum), about to move left
Phase = π:        Starts at equilibrium, moving left
Phase = 3π/2:     Starts at -A (minimum), about to move right
```

### Sin vs Cos: Which One?

| Starting condition at t=0 | Use this |
|---------------------------|----------|
| At equilibrium (x = 0), moving toward +A | $x = A\sin(\omega t)$ |
| At maximum (x = +A) | $x = A\cos(\omega t)$ |
| At equilibrium (x = 0), moving toward −A | $x = -A\sin(\omega t)$ or $x = A\sin(\omega t + \pi)$ |
| At minimum (x = −A) | $x = -A\cos(\omega t)$ or $x = A\cos(\omega t + \pi)$ |

> **Draw the starting position. Then pick sin or cos to match.**

---

## PAGE 4 — SHM Formulas and Energy

### The Core Equations

| Quantity | Formula |
|----------|---------|
| Position | $x = A\cos(\omega t + \phi)$ |
| Velocity | $v = -A\omega\sin(\omega t + \phi)$ |
| Acceleration | $a = -A\omega^2\cos(\omega t + \phi) = -\omega^2 x$ |
| Max velocity | $v_{max} = A\omega$ (at equilibrium) |
| Max acceleration | $a_{max} = A\omega^2$ (at extremes) |

### The Velocity-Position Relationship (No Time Needed)

$$v = \omega\sqrt{A^2 - x^2}$$

This is extremely useful when you know position but not time.

### Energy in SHM: The Seesaw

```
At x = 0 (equilibrium):     All KE, zero PE
At x = ±A (extremes):       Zero KE, all PE

Energy flows back and forth, but TOTAL stays constant.

KE ████████░░░░░░░░ PE
   ↑ at center

KE ░░░░░░░░████████ PE
              ↑ at extreme
```

$$E_{total} = \frac{1}{2}kA^2 = \frac{1}{2}m\omega^2 A^2$$

### Quick Result: Where is KE = PE?

At $x = \frac{A}{\sqrt{2}} \approx 0.707A$

(This is a common JEE question.)

---

## PAGE 5 — Common SHM Systems: Decision Tree

### Which Formula for Period?

```
Is it a SPRING system?
├── YES → T = 2π√(m/k)
│         └── Find effective k for series/parallel springs
│
└── NO → Is it a PENDULUM?
         ├── Simple pendulum → T = 2π√(L/g)
         │   (point mass, massless string)
         │
         └── Physical pendulum → T = 2π√(I/mgd)
             (extended body, I about pivot, d = pivot to COM)
```

### Springs in Series vs Parallel

| Configuration | Equivalent k | Physical meaning |
|--------------|--------------|------------------|
| **Series** (one after another) | $\frac{1}{k_{eq}} = \frac{1}{k_1} + \frac{1}{k_2}$ | Softer (easier to stretch) |
| **Parallel** (side by side) | $k_{eq} = k_1 + k_2$ | Stiffer (harder to stretch) |

> **Series springs are like resistors in series for conductance (1/R).**
> **Parallel springs are like resistors in parallel for conductance.**

Wait — that's backwards from resistors! Use this memory trick:
- Springs in **S**eries → **S**ofter → **S**maller k
- Springs in **P**arallel → **P**owerful → **P**lus the k values

### Damped Oscillations (Real World SHM)

When energy is lost to friction/air drag, amplitude decays exponentially:

$$A(t) = A_0 e^{-bt/2m}$$

Where $b$ = damping constant.

**Energy decay:** $E \propto A^2 \propto e^{-bt/m}$

**Common JEE question:** "After how much time does amplitude become half?"

$$\frac{A_0}{2} = A_0 e^{-bt/2m} \implies t = \frac{2m \ln 2}{b}$$

> **Damping doesn't change frequency (for light damping), only amplitude.**

---

## PAGE 6 — Traveling Waves: Direction and Equation

### The Wave Equation

$$y(x,t) = A\sin(kx - \omega t)$$

### Which Way Is It Going? (The Big Confusion)

**Memory trick: The "Racing" Method**

Look at what's inside the parentheses: $(kx - \omega t)$

Ask: "For the phase to stay constant, if t increases, what must x do?"

$kx - \omega t = \text{constant}$

If t ↑, then x must ↑ to keep the difference constant.

So $(kx - \omega t)$ → wave moves in **+x direction**

Similarly:
- $(kx + \omega t)$ → wave moves in **−x direction**
- $(\omega t - kx)$ → same as $-(kx - \omega t)$ → **+x direction**

### Visual Check

```
Wave equation: y = A sin(kx - ωt)

At t = 0:     ∿∿∿∿∿ (wave shape)
At t = small: ∿∿∿∿∿ shifted RIGHT

The wave moves in +x direction.
```

> **Minus sign between kx and ωt → wave goes in +x direction.**

---

## PAGE 7 — Wave Parameters: What Each One Means

### The Complete Picture

```
y
↑      λ (one wavelength)
│    ←──────→
│    ╭──╮    ╭──╮
A ──│   │    │   │── amplitude
│   │    │  │    │
────┼────┼──┼────┼──→ x
│   │    │  │    │
-A ─│   ╰──╯    ╰──
```

| Parameter | Symbol | What it means | Formula |
|-----------|--------|---------------|---------|
| Amplitude | A | Max displacement from equilibrium | Given |
| Wavelength | λ | Distance for one complete wave | Measured |
| Wave number | k | "Spatial frequency" | $k = 2\pi/\lambda$ |
| Frequency | f | Oscillations per second | $f = 1/T$ |
| Angular frequency | ω | Radians per second | $\omega = 2\pi f$ |
| Wave speed | v | How fast the pattern moves | $v = f\lambda = \omega/k$ |

### The Fundamental Relationship

$$v = f\lambda$$

This connects TIME behavior (f) to SPACE behavior (λ).

---

## PAGE 8 — Wave Speed: What Determines It?

### The Rule

> **Wave speed depends on the MEDIUM, not on frequency or amplitude.**

### Wave Speed Formulas

| Wave type | Speed formula | Variables |
|-----------|--------------|-----------|
| String | $v = \sqrt{T/\mu}$ | T = tension, μ = mass/length |
| Sound in gas | $v = \sqrt{\gamma RT/M}$ | γ = Cp/Cv, M = molar mass |
| Sound in solid | $v = \sqrt{Y/\rho}$ | Y = Young's modulus |

### What Happens at a Boundary?

When a wave enters a new medium:

| Quantity | Changes? | Why? |
|----------|----------|------|
| Speed (v) | YES | Medium properties change |
| Wavelength (λ) | YES | Must change because v = fλ |
| Frequency (f) | **NO** | Determined by source, not medium |

> **This is the key insight for refraction problems!**

---

## PAGE 9 — Superposition and Interference

### The Principle

> **When waves meet, displacements ADD.**

$$y_{total} = y_1 + y_2$$

Waves pass through each other unchanged after meeting.

### Path Difference vs Phase Difference

These are DIFFERENT quantities. Don't confuse them!

| Quantity | Symbol | Unit | Meaning |
|----------|--------|------|---------|
| Path difference | Δx | meters | Extra distance one wave travels |
| Phase difference | Δφ | radians | How "out of step" the waves are |

**The connection:**
$$\Delta\phi = \frac{2\pi}{\lambda} \times \Delta x = k \times \Delta x$$

### Constructive vs Destructive: The Table

| Condition | Path Difference | Phase Difference | Result |
|-----------|-----------------|------------------|--------|
| **Constructive** (max) | $0, \lambda, 2\lambda, ...$ | $0, 2\pi, 4\pi, ...$ | Amplitude adds |
| **Destructive** (min) | $\frac{\lambda}{2}, \frac{3\lambda}{2}, ...$ | $\pi, 3\pi, 5\pi, ...$ | Amplitude cancels |

**Memory trick:**
- Constructive = "Complete" wavelengths = nλ
- Destructive = "Dis" = "Half" off = (n + ½)λ

---

## PAGE 10 — Standing Waves: The Trapped Pattern

### How They Form

Two identical waves traveling in OPPOSITE directions:

$$y = 2A\sin(kx)\cos(\omega t)$$

This is NOT traveling — it's standing still and vibrating.

### Nodes and Antinodes: Visual

```
Antinode     Node     Antinode     Node     Antinode
   ↓          ↓          ↓          ↓          ↓
   ╭──────────╮          ╭──────────╮
   │          │          │          │
───┼──────────┼──────────┼──────────┼──────────
   │          │          │          │
   ╰──────────╯          ╰──────────╯

← λ/2 →
```

- **Nodes:** Always at rest (amplitude = 0)
- **Antinodes:** Maximum vibration
- Distance between adjacent nodes = λ/2

### Standing Waves: The Decision Tree

```
What are the BOUNDARY CONDITIONS?

BOTH ENDS FIXED (string, closed pipe)?
├── Nodes at both ends
├── Allowed: λ = 2L/n (n = 1, 2, 3, ...)
└── Frequencies: f = nv/2L (ALL harmonics)

ONE END FIXED, ONE END FREE (closed pipe)?
├── Node at closed end, Antinode at open end
├── Allowed: λ = 4L/(2n-1) (n = 1, 2, 3, ...)
└── Frequencies: f = (2n-1)v/4L (ODD harmonics only)

BOTH ENDS FREE (open pipe)?
├── Antinodes at both ends
├── Allowed: λ = 2L/n
└── Frequencies: f = nv/2L (ALL harmonics)
```

### Quick Comparison Table

| System | Boundary | Harmonics | Fundamental |
|--------|----------|-----------|-------------|
| String (both fixed) | N---N | All (1,2,3...) | $f_1 = v/2L$ |
| Closed pipe | N---A | Odd only (1,3,5...) | $f_1 = v/4L$ |
| Open pipe | A---A | All (1,2,3...) | $f_1 = v/2L$ |

> **Closed pipe has lowest fundamental for same length (and only odd harmonics).**

---

## PAGE 11 — Doppler Effect: Demystified

### The Concept

When source or observer moves, the received frequency differs from emitted frequency.

**Moving TOWARD → Higher frequency (blue shift)**
**Moving AWAY → Lower frequency (red shift)**

### The Formula (With Memory System)

$$f' = f \cdot \frac{v \pm v_o}{v \mp v_s}$$

**The STOP Method:**
- **S**ource in denominator
- **T**op has observer
- **O**pposite signs (if + on top, − on bottom)
- **P**ositive for approaching

### Decision Tree for Signs

```
Is OBSERVER moving TOWARD source?
├── YES → Add v_o in numerator: (v + v_o)
└── NO (away) → Subtract: (v - v_o)

Is SOURCE moving TOWARD observer?
├── YES → Subtract v_s in denominator: (v - v_s)
└── NO (away) → Add: (v + v_s)
```

### Why This Makes Sense

**Observer toward source:** "Running into" more waves → higher frequency → ADD to numerator (increases f')

**Source toward observer:** Waves get "bunched up" → shorter wavelength → smaller denominator → higher f' → SUBTRACT from denominator

### Example Patterns

| Situation | Formula |
|-----------|---------|
| Source toward stationary observer | $f' = f \cdot \frac{v}{v - v_s}$ |
| Observer toward stationary source | $f' = f \cdot \frac{v + v_o}{v}$ |
| Both approaching | $f' = f \cdot \frac{v + v_o}{v - v_s}$ |
| Both receding | $f' = f \cdot \frac{v - v_o}{v + v_s}$ |

---

## PAGE 12 — Geometrical Optics: The Ray Model

### When to Use Ray Optics

Ray optics works when:
- Objects/apertures >> wavelength
- We can ignore interference and diffraction

### The One Sign Convention (Stick to This!)

**Cartesian Convention:**
1. Light travels LEFT → RIGHT
2. Measure all distances from pole/optical center
3. Distances in direction of light: POSITIVE
4. Distances opposite to light: NEGATIVE
5. Heights above axis: POSITIVE
6. Heights below axis: NEGATIVE

```
          ↑ (+)
          │
(−) ──────┼────── (+) → (light direction)
          │
          ↓ (−)
```

---

## PAGE 13 — Reflection: Mirrors

### Laws of Reflection

1. Angle of incidence = Angle of reflection
2. Incident ray, normal, and reflected ray are coplanar

### Mirror Equation

$$\frac{1}{v} + \frac{1}{u} = \frac{1}{f} = \frac{2}{R}$$

### Magnification

$$m = -\frac{v}{u} = \frac{h_i}{h_o}$$

### The Mirror Table (Memorize This Pattern)

| Mirror | f | Object beyond C | Object at C | Object between C and F | Object at F | Object between F and P |
|--------|---|-----------------|-------------|----------------------|-------------|----------------------|
| **Concave** | + | Real, inverted, diminished | Real, inverted, same size | Real, inverted, enlarged | At infinity | Virtual, erect, enlarged |
| **Convex** | − | — | — | — | — | Always virtual, erect, diminished |

> **Concave = Converging = Can form real images**
> **Convex = Diverging = Always virtual, diminished**

---

## PAGE 14 — Refraction: Lenses

### Snell's Law

$$n_1 \sin\theta_1 = n_2 \sin\theta_2$$

### Lens Formula

$$\frac{1}{v} - \frac{1}{u} = \frac{1}{f}$$

Note: Different from mirror formula! (minus sign)

### Lens Maker's Equation

$$\frac{1}{f} = (n-1)\left(\frac{1}{R_1} - \frac{1}{R_2}\right)$$

### Magnification

$$m = \frac{v}{u} = \frac{h_i}{h_o}$$

### Mirror vs Lens: The Comparison

| Property | Mirror | Lens |
|----------|--------|------|
| Formula | $\frac{1}{v} + \frac{1}{u} = \frac{1}{f}$ | $\frac{1}{v} - \frac{1}{u} = \frac{1}{f}$ |
| Magnification | $m = -v/u$ | $m = v/u$ |
| Concave/Convex → f | Concave: +, Convex: − | Convex: +, Concave: − |

> **Converging device (concave mirror, convex lens) has positive f.**

### Silvered Lens (Lens + Mirror Combo)

If you paint one side of a lens with silver, it acts like a **combined lens-mirror system**.

**The Power Rule:**
Light goes through lens → hits mirror → goes back through lens.
So the lens power counts TWICE.

$$P_{equivalent} = 2P_{Lens} + P_{Mirror}$$

Since $P_{mirror} = -1/f_m$ (sign from mirror convention):
$$\frac{1}{F_{eq}} = \frac{2}{f_L} + \frac{1}{f_m}$$

**Example:** Convex lens ($f_L = +20$ cm) silvered on one side ($f_m = \infty$ for plane mirror):
$$\frac{1}{F_{eq}} = \frac{2}{20} + 0 = \frac{1}{10} \implies F_{eq} = 10 \text{ cm}$$

> **The silvered lens always acts as a concave mirror (converging).**

---

## PAGE 15 — The Prism: Geometry of Light

### The Prism Geometry

A ray enters at angle $i$, refracts inside the prism (angle $A$), and emerges at angle $e$.

```
         A (apex angle)
        /\
       /  \
      /    \
   i →     → e
    ─────────
```

**The Two Invariants:**
1. $r_1 + r_2 = A$ (angles inside prism add to apex angle)
2. $\delta = (i - r_1) + (e - r_2) = i + e - A$ (total deviation)

### Minimum Deviation ($\delta_{min}$)

Occurs when light passes **symmetrically** through the prism:
- $i = e$
- $r_1 = r_2 = A/2$

**The Prism Formula:**
$$n = \frac{\sin\left(\frac{A + \delta_{min}}{2}\right)}{\sin\left(\frac{A}{2}\right)}$$

### Thin Prism Approximation ($A < 10°$)

For small angles:
$$\delta = (n-1)A$$

> **JEE Trap:** For thin prisms, deviation does NOT depend on angle of incidence!

### Dispersion (Splitting of White Light)

Different colors have different refractive indices: $n_V > n_R$

Therefore: Violet bends more than Red.

**Angular Dispersion:** $\theta = \delta_V - \delta_R = (n_V - n_R)A$

**Dispersive Power:** $\omega = \frac{\theta}{\delta_{mean}} = \frac{n_V - n_R}{n_Y - 1}$

**Achromatic Prism Combination:** To get deviation without dispersion:
$$\omega_1 \delta_1 + \omega_2 \delta_2 = 0$$

---

## PAGE 16 — Critical Angle and TIR

### Total Internal Reflection

Happens when:
1. Light goes from DENSER to RARER medium
2. Angle of incidence > Critical angle

$$\sin\theta_c = \frac{n_2}{n_1} = \frac{n_{rarer}}{n_{denser}}$$

### Visual Understanding

```
From glass (n=1.5) to air (n=1):

θ < θc:        θ = θc:         θ > θc:
   ↗ (refracted)   → (along surface)   No refraction!
  /                                     ↘ (all reflected)
 /                  ─────────────        \
─────────────      ─────────────      ─────────────
 \                  \                    \
  ↘                  ↘                    ↘
(some reflected)   (some reflected)    (TOTAL reflection)
```

> **TIR is how fiber optics and diamonds work!**

---

## PAGE 17 — Optical Instruments (The Magnifiers)

### Visual Angle ($\theta$)

Optical instruments don't just increase size — they increase the **angle** subtended at the eye.

**Magnifying Power:** $M = \frac{\beta}{\alpha}$ (Angle with instrument / Angle with naked eye at near point)

### 1. Simple Microscope (Magnifying Glass)

| Condition | Magnifying Power |
|-----------|------------------|
| Image at Infinity (Relaxed eye) | $M = \frac{D}{f}$ |
| Image at Near Point (Strained eye) | $M = 1 + \frac{D}{f}$ |

Where $D = 25$ cm (least distance of distinct vision)

### 2. Compound Microscope

Two lenses: Objective ($f_o$, small) and Eyepiece ($f_e$).

$$M = m_{objective} \times m_{eyepiece} = -\frac{L}{f_o} \times \frac{D}{f_e}$$

Where $L$ = tube length (distance between lenses) $\approx v_o + f_e$

**For greater magnification:** Use smaller $f_o$ and smaller $f_e$.

### 3. Astronomical Telescope

Two lenses: Objective ($f_o$, large) and Eyepiece ($f_e$, small).

$$M = -\frac{f_o}{f_e}$$

**Tube length (Normal adjustment):** $L = f_o + f_e$

**For greater magnification:** Use larger $f_o$ and smaller $f_e$.

### The Key Difference

| Instrument | To see... | Objective $f_o$ should be... |
|------------|-----------|------------------------------|
| Microscope | Small things | Small |
| Telescope | Far things | Large |

> **Microscope: Small $f_o$ to magnify. Telescope: Large $f_o$ to gather light.**

---

## PAGE 18 — Wave Optics: When Rays Fail

### When to Use Wave Optics

Use wave optics when:
- Aperture size ≈ wavelength
- Question asks about interference or diffraction
- Intensity distribution is needed

### Coherence: The Essential Requirement

For interference pattern to form:
1. Same frequency
2. Constant phase difference

> **Two bulbs don't create interference — they're incoherent.**

---

## PAGE 19 — Young's Double Slit: The Classic

### The Setup

```
     S₁ ●────────────────────── Screen
         \                    │
          \   d              │ y
           \                 │
     S₂ ●───\────────────────│─
              \              │
               \  ←───D────→ │
```

### Path Difference

$$\Delta = d\sin\theta \approx \frac{yd}{D}$$ (for small angles)

### Fringe Positions

**Bright fringes:** $y_n = \frac{n\lambda D}{d}$ (n = 0, 1, 2, ...)

**Dark fringes:** $y_n = \frac{(2n+1)\lambda D}{2d}$ (n = 0, 1, 2, ...)

### Fringe Width

$$\beta = \frac{\lambda D}{d}$$

**What affects fringe width?**

| Change | Effect on β |
|--------|-------------|
| ↑ wavelength (λ) | ↑ wider fringes |
| ↑ screen distance (D) | ↑ wider fringes |
| ↑ slit separation (d) | ↓ narrower fringes |

---

## PAGE 20 — Single Slit Diffraction: Different Pattern!

### The Key Difference

| | Double Slit | Single Slit |
|---|-------------|-------------|
| Central maximum | Same width as others | TWICE as wide |
| Pattern | Uniform fringes | Central bright, then fading |
| Minima condition | $d\sin\theta = (n+\frac{1}{2})\lambda$ | $a\sin\theta = n\lambda$ |

### Single Slit Minima

$$a\sin\theta = n\lambda$$ (n = 1, 2, 3, ...)

Where a = slit width

**WARNING:** This formula gives MINIMA (dark), not maxima!

### Visual Comparison

```
DOUBLE SLIT:
│ │ │ │ │ │ │ │ │ │ │ (uniform spacing)
    all same width

SINGLE SLIT:
     │   │ │ │ │ │   │   (central maximum wider)
     ←2β→ ←β→
```

---

## PAGE 21 — The Ultimate Comparison Table

### Interference Formulas: Single vs Double Slit

| Quantity | Double Slit (separation d) | Single Slit (width a) |
|----------|---------------------------|----------------------|
| **Maxima (bright)** | $d\sin\theta = n\lambda$ | Central max at θ=0; Secondary maxima ≈ $(n+\frac{1}{2})\frac{\lambda}{a}$ |
| **Minima (dark)** | $d\sin\theta = (n+\frac{1}{2})\lambda$ | $a\sin\theta = n\lambda$ |
| Central fringe | Same as others | Twice as wide |
| Angular width of central max | N/A | $2\lambda/a$ |

> **TRAP ALERT:** For single slit, the formula $a\sin\theta = n\lambda$ gives MINIMA!
> Don't confuse with double slit where $d\sin\theta = n\lambda$ gives MAXIMA!

---

## PAGE 22 — Phase Changes at Reflection

### The Hidden π

When light reflects from a DENSER medium, it gains a phase shift of π (or path shift of λ/2).

### When Does This Matter?

**Thin film interference:**

```
Air (n=1)     ↓ incident
─────────────────────────  ← reflection 1 (π shift if n_film > n_air)
Film (n=1.5)
─────────────────────────  ← reflection 2 (π shift if n_below > n_film)
Glass (n=1.6)
```

**Counting phase shifts:**
- 0 shifts or 2 shifts → No net change
- 1 shift → Net π change (affects constructive/destructive conditions)

### Lloyd's Mirror

One ray goes directly, one reflects off mirror.
Reflected ray gets π shift → Central fringe is DARK (not bright).

---

## PAGE 23 — Optical Path: The Unifying Concept

### Definition

$$\text{Optical Path} = n \times \text{Geometric Path}$$

### Why It Matters

When light travels through a medium of thickness t and refractive index n:
- Geometric path = t
- Optical path = nt
- Extra optical path compared to air = (n-1)t

### Application: Inserting a Glass Slab

If a thin glass plate (thickness t, refractive index n) is placed in front of one slit:

**Fringe shift** = $\frac{(n-1)t}{\lambda} \times \beta$ fringes

> **Fringes shift TOWARD the side with the glass plate.**

---

## PAGE 24 — Polarization

### What It Means

Light is a transverse wave — E-field oscillates perpendicular to direction of travel.

**Unpolarized:** E-field vibrates in all perpendicular directions
**Polarized:** E-field vibrates in only ONE plane

### Malus's Law

When polarized light (intensity I₀) passes through analyzer at angle θ:

$$I = I_0 \cos^2\theta$$

### Key Results

| Angle between polarizer and analyzer | Transmitted intensity |
|-------------------------------------|----------------------|
| 0° (parallel) | I₀ (maximum) |
| 45° | I₀/2 |
| 90° (crossed) | 0 (no light) |

### Brewster's Angle

When reflected and refracted rays are perpendicular:

$$\tan\theta_B = n$$

At this angle, reflected light is completely polarized.

---

## PAGE 25 — The Master Decision Tree for Optics

```
OPTICS PROBLEM
│
├── Is wavelength/interference/diffraction mentioned?
│   ├── YES → WAVE OPTICS
│   │         ├── Two sources/slits? → Young's double slit formulas
│   │         ├── Single aperture? → Single slit diffraction
│   │         ├── Thin film? → Count phase shifts, use optical path
│   │         └── Polarization? → Malus's law
│   │
│   └── NO → RAY OPTICS
│            ├── Mirror? → Use 1/v + 1/u = 1/f
│            ├── Lens? → Use 1/v - 1/u = 1/f
│            ├── Refraction? → Snell's law
│            └── Multiple surfaces? → Apply formulas step by step
│
└── For ANY optical problem:
    └── Check: Is sign convention consistent throughout?
```

---

## PAGE 26 — What JEE Is REALLY Testing

### JEE Main Tests:
- Direct formula application
- Basic SHM problems
- Simple interference calculations
- Standard mirror/lens problems

### JEE Advanced Tests:
- Combining SHM with mechanics/electromagnetism
- Multiple slit interference
- Thin film with phase shifts
- Optical path in different media
- Non-standard setups requiring first-principles thinking

> **Advanced problems test whether you UNDERSTAND the physics, not just memorized formulas.**

---

## PAGE 27 — Common Traps (Exam Killers)

### SHM Traps
| Trap | Fix |
|------|-----|
| Using wrong trig function | Draw starting position, pick sin/cos to match |
| Forgetting ω vs f | ω = 2πf. Check units! |
| Mixing up extreme vs equilibrium | Extreme: max PE, zero KE. Equilibrium: opposite |

### Wave Traps
| Trap | Fix |
|------|-----|
| Thinking frequency changes at interface | FREQUENCY NEVER CHANGES. Speed and λ do. |
| Wrong wave direction from equation | (kx - ωt) → +x direction. Memorize this! |
| Confusing path and phase difference | Path = physical distance. Phase = 2π/λ × path |

### Optics Traps
| Trap | Fix |
|------|-----|
| Wrong sign convention | Pick ONE convention, stick to it |
| Single vs double slit formula swap | Single: nλ = minima. Double: nλ = maxima |
| Forgetting phase shift at reflection | Always check: denser medium reflection → π shift |

---

## PAGE 28 — Mental Checklist (Before Solving)

### For SHM:
1. Is restoring force ∝ displacement? (Confirm it's SHM)
2. What's the starting condition? (Determines phase)
3. What quantity is asked? (Position, velocity, energy?)

### For Waves:
1. What type of wave? (Transverse/longitudinal, traveling/standing)
2. What are the boundary conditions? (Nodes/antinodes at ends)
3. Does the wave change medium? (Frequency stays same!)

### For Optics:
1. Ray optics or wave optics?
2. What sign convention am I using?
3. Are there phase shifts at reflections?
4. What's the path difference/optical path?

> **Ask these questions BEFORE you write any formula.**

---

## PAGE 29 — Forward Connections

Waves and Optics connect to:
- **Modern Physics:** Light as photons, matter waves
- **Electromagnetism:** Light as EM wave
- **Quantum Mechanics:** Wave-particle duality, uncertainty principle
- **Engineering:** Fiber optics, lasers, acoustics, imaging

> **Understanding waves is essential for understanding the quantum world.**
