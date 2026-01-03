---
title: Thermodynamics
parent: Physics
nav_order: 2
---

# Chapter 2 — THERMODYNAMICS
## Heat, Work, and Entropy

---

## PAGE 1 — Why Thermodynamics Exists (Mindset Reset)

Most students think:

> "Thermodynamics is about memorizing PV diagrams and formulas for different processes."

That is **not** its real purpose.

### Thermodynamics answers questions like:
- How does heat flow and transform into work?
- Why can't we build a perpetual motion machine?
- What determines which processes are possible?
- How do billions of particles create predictable behavior?

> **Thermodynamics is the physics of the irreversible.**

This is why thermodynamics governs:
- Engines and refrigerators
- Chemical reactions
- Stars and black holes
- The arrow of time itself

---

## PAGE 2 — The Core Idea (Anchor Page)

### The Core Idea of Thermodynamics

> **Energy is conserved, but not all energy is equally useful.**

The First Law says: Energy cannot be created or destroyed.
The Second Law says: But you can't convert it all to work.

This is the tragedy of thermodynamics:
- Heat flows spontaneously from hot to cold
- Never the reverse
- Every engine wastes some energy

### The Two Laws as Constraints

| Law | What it says | What it forbids |
|-----|--------------|-----------------|
| First Law | Energy is conserved | Perpetual motion of the first kind |
| Second Law | Entropy never decreases | Perpetual motion of the second kind |

> **The First Law is about accounting. The Second Law is about direction.**

---

## PAGE 3 — What Changes vs What Remains Invariant

| Aspect | Changes | Remains Invariant |
|--------|---------|-------------------|
| Pressure | ✅ | ❌ |
| Volume | ✅ | ❌ |
| Temperature | ✅ | ❌ |
| Internal Energy | ✅ | ❌ |
| **Total Energy** (system + surroundings) | ❌ | ✅ |
| **Entropy Direction** (always increases) | ❌ | ✅ |

> **State variables change. Conservation laws and entropy direction don't.**

---

## PAGE 4 — Temperature and Heat: The Basics

### What Temperature Really Is

> **Temperature measures average kinetic energy of molecules.**

For an ideal gas:
$$\frac{1}{2}m\langle v^2 \rangle = \frac{3}{2}k_B T$$

Temperature is NOT heat. Temperature is the "quality" of thermal energy.

### What Heat Really Is

> **Heat is energy transfer due to temperature difference.**

Heat flows from hot to cold — never spontaneously the other way.

Symbol: $Q$
- $Q > 0$: Heat enters the system
- $Q < 0$: Heat leaves the system

### Specific Heat and Calorimetry

$$Q = mc\Delta T$$

**The Conservation Principle:**
In an isolated system, heat lost = heat gained.

$$m_1 c_1 (T_f - T_1) + m_2 c_2 (T_f - T_2) = 0$$

---

## PAGE 5 — Kinetic Theory of Gases: Molecules in Motion

### The Ideal Gas Model

Assumptions:
1. Gas = many tiny particles in random motion
2. No intermolecular forces (except during collisions)
3. Collisions are elastic
4. Volume of molecules << volume of container

### The Ideal Gas Law

$$PV = nRT = Nk_BT$$

Where:
- $n$ = number of moles
- $R = 8.314$ J/mol·K
- $N$ = number of molecules
- $k_B = 1.38 \times 10^{-23}$ J/K

### Pressure from Molecular Collisions

$$P = \frac{1}{3}\rho \langle v^2 \rangle = \frac{1}{3}\frac{Nm\langle v^2 \rangle}{V}$$

### Molecular Speeds

| Speed | Formula | Meaning |
|-------|---------|---------|
| RMS speed | $v_{rms} = \sqrt{\frac{3RT}{M}} = \sqrt{\frac{3k_BT}{m}}$ | Root mean square |
| Average speed | $v_{avg} = \sqrt{\frac{8RT}{\pi M}}$ | Mean of distribution |
| Most probable | $v_{mp} = \sqrt{\frac{2RT}{M}}$ | Peak of distribution |

Relation: $v_{mp} < v_{avg} < v_{rms}$

### Degrees of Freedom and Internal Energy

| Gas Type | Degrees of Freedom ($f$) | Examples |
|----------|-------------------------|----------|
| Monatomic | 3 (translation only) | He, Ar, Ne |
| Diatomic | 5 (3 trans + 2 rot) | H₂, O₂, N₂ |
| Polyatomic | 6 (3 trans + 3 rot) | CO₂, H₂O |

Internal Energy:
$$U = \frac{f}{2}nRT$$

> **Internal energy depends ONLY on temperature for ideal gases.**

---

## PAGE 6 — The First Law: Energy Accounting

### The Statement

$$\Delta U = Q - W$$

Or equivalently: $Q = \Delta U + W$

Where:
- $\Delta U$ = change in internal energy
- $Q$ = heat added to system
- $W$ = work done BY the system

### Work Done by Gas

$$W = \int P \, dV$$

- Expansion ($dV > 0$): Work is positive (system does work)
- Compression ($dV < 0$): Work is negative (work done on system)

### The PV Diagram: Your Visual Tool

Work = Area under the curve on a PV diagram.

```
P
|  ____
| /    \
|/______\_____ V

Work = shaded area (positive for clockwise cycle)
```

> **Clockwise cycle = heat engine (net work output)**
> **Counterclockwise cycle = refrigerator (net work input)**

---

## PAGE 7 — Thermodynamic Processes: The Big Four

### 1. Isothermal Process (Constant T)

$$T = \text{constant} \implies PV = \text{constant}$$

- $\Delta U = 0$ (temperature doesn't change)
- $Q = W$ (all heat becomes work)
- $W = nRT \ln\frac{V_f}{V_i}$

### 2. Adiabatic Process (No Heat Exchange)

$$Q = 0 \implies \Delta U = -W$$

The gas heats up when compressed, cools when expanded.

$$PV^\gamma = \text{constant}$$
$$TV^{\gamma-1} = \text{constant}$$

Where $\gamma = C_P/C_V = 1 + 2/f$

### 3. Isobaric Process (Constant P)

$$P = \text{constant}$$

- $W = P\Delta V$
- $Q = nC_P\Delta T$

### 4. Isochoric Process (Constant V)

$$V = \text{constant} \implies W = 0$$

- $\Delta U = Q$
- $Q = nC_V\Delta T$

### Comparison Table

| Process | Constant | Work ($W$) | Heat ($Q$) | $\Delta U$ |
|---------|----------|------------|------------|------------|
| Isothermal | $T$ | $nRT\ln(V_f/V_i)$ | $W$ | $0$ |
| Adiabatic | $Q = 0$ | $-\Delta U$ | $0$ | $nC_V\Delta T$ |
| Isobaric | $P$ | $P\Delta V$ | $nC_P\Delta T$ | $nC_V\Delta T$ |
| Isochoric | $V$ | $0$ | $nC_V\Delta T$ | $Q$ |

### The "Master Key": Polytropic Process ($PV^x = \text{constant}$)

Most JEE Advanced problems involve processes that are NOT the standard four.
They follow the form $PV^x = C$.

**Work Done:**
$$W = \frac{P_1 V_1 - P_2 V_2}{x - 1} = \frac{nR(T_1 - T_2)}{x - 1}$$

**Molar Heat Capacity (The Killer Formula):**
$$C = C_V + \frac{R}{1-x}$$

**Special Cases:**

| Process | Value of x | C |
|---------|-----------|---|
| Isobaric | 0 | $C_V + R = C_P$ |
| Isothermal | 1 | $\infty$ (all heat → work) |
| Adiabatic | $\gamma$ | 0 (no heat exchange) |
| Isochoric | $\infty$ | $C_V$ |

> **Use this for ANY process. The Big Four are just special cases.**

---

## PAGE 8 — Specific Heat Capacities: Cp and Cv

### Definitions

$$C_V = \frac{Q}{n\Delta T}\bigg|_V = \frac{f}{2}R$$

$$C_P = \frac{Q}{n\Delta T}\bigg|_P = C_V + R = \frac{f+2}{2}R$$

### Why Cp > Cv

At constant pressure, some heat goes into expansion work.
At constant volume, all heat goes into raising temperature.

$$C_P - C_V = R$$ (Mayer's relation)

### The Gamma Ratio

$$\gamma = \frac{C_P}{C_V} = 1 + \frac{2}{f}$$

| Gas Type | $f$ | $\gamma$ |
|----------|-----|----------|
| Monatomic | 3 | 5/3 = 1.67 |
| Diatomic | 5 | 7/5 = 1.4 |
| Polyatomic | 6 | 4/3 = 1.33 |

### Gas Mixtures (The Weighted Average)

When non-reacting gases mix, Energy and Moles are conserved.

**Internal Energy:** $U_{mix} = U_1 + U_2$

**Heat Capacities (mole-weighted average):**
$$C_{V, mix} = \frac{n_1 C_{V1} + n_2 C_{V2}}{n_1 + n_2}$$
$$C_{P, mix} = \frac{n_1 C_{P1} + n_2 C_{P2}}{n_1 + n_2}$$

**Gamma of Mixture:**
$$\gamma_{mix} = \frac{C_{P, mix}}{C_{V, mix}}$$

**Example:** 2 moles He + 3 moles O₂
- He: $C_V = \frac{3}{2}R$, O₂: $C_V = \frac{5}{2}R$
- $C_{V,mix} = \frac{2 \times \frac{3}{2}R + 3 \times \frac{5}{2}R}{5} = \frac{3R + 7.5R}{5} = 2.1R$

> **Warning: You cannot just average the gammas! Average the C's first, then find γ.**

---

## PAGE 9 — The Second Law: The Arrow of Time

### The Two Equivalent Statements

**Kelvin-Planck:** No heat engine can convert all heat to work.

**Clausius:** Heat cannot spontaneously flow from cold to hot.

> **Both statements are equivalent. Violating one violates the other.**

### Entropy: The Measure of Disorder

$$\Delta S = \int \frac{dQ_{rev}}{T}$$

For a reversible process:
$$\Delta S_{universe} = 0$$

For an irreversible process:
$$\Delta S_{universe} > 0$$

> **Entropy of the universe always increases. This IS the arrow of time.**

### Entropy Changes in Common Processes

| Process | $\Delta S$ |
|---------|------------|
| Isothermal expansion | $nR\ln(V_f/V_i)$ |
| Heating at constant V | $nC_V\ln(T_f/T_i)$ |
| Heating at constant P | $nC_P\ln(T_f/T_i)$ |
| Adiabatic reversible | $0$ |
| Free expansion | $nR\ln(V_f/V_i)$ (irreversible!) |

---

## PAGE 10 — Heat Engines: Converting Heat to Work

### The Concept

A heat engine:
1. Absorbs heat $Q_H$ from hot reservoir
2. Does work $W$
3. Rejects heat $Q_C$ to cold reservoir

$$Q_H = W + Q_C$$

### Efficiency

$$\eta = \frac{W}{Q_H} = \frac{Q_H - Q_C}{Q_H} = 1 - \frac{Q_C}{Q_H}$$

### Carnot Engine: The Ideal Limit

The Carnot cycle (two isothermals + two adiabatics) achieves maximum efficiency:

$$\eta_{Carnot} = 1 - \frac{T_C}{T_H}$$

Where temperatures are in Kelvin.

> **No engine operating between $T_H$ and $T_C$ can be more efficient than Carnot.**

### The Carnot Cycle

1. Isothermal expansion at $T_H$ (absorb $Q_H$)
2. Adiabatic expansion ($T_H \to T_C$)
3. Isothermal compression at $T_C$ (reject $Q_C$)
4. Adiabatic compression ($T_C \to T_H$)

---

## PAGE 11 — Refrigerators and Heat Pumps

### Refrigerator

A refrigerator moves heat from cold to hot using work.

$$Q_H = Q_C + W$$

**Coefficient of Performance (COP):**
$$\text{COP} = \frac{Q_C}{W} = \frac{Q_C}{Q_H - Q_C}$$

For Carnot refrigerator:
$$\text{COP}_{Carnot} = \frac{T_C}{T_H - T_C}$$

### Heat Pump

Same as refrigerator, but we want to heat the hot reservoir.

$$\text{COP}_{heat pump} = \frac{Q_H}{W} = \frac{T_H}{T_H - T_C}$$

> **A heat pump is more efficient than direct heating (COP > 1).**

---

## PAGE 12 — Thermal Expansion

### Linear Expansion

$$\Delta L = L_0 \alpha \Delta T$$
$$L = L_0(1 + \alpha \Delta T)$$

### Area and Volume Expansion

$$\Delta A = A_0 (2\alpha) \Delta T = A_0 \beta_{area} \Delta T$$
$$\Delta V = V_0 (3\alpha) \Delta T = V_0 \gamma \Delta T$$

For isotropic solids: $\beta = 2\alpha$, $\gamma = 3\alpha$

### Thermal Stress

If expansion is prevented:
$$\text{Stress} = Y \alpha \Delta T$$

Where $Y$ is Young's modulus.

---

## PAGE 13 — Heat Transfer: Conduction, Convection, Radiation

### Conduction

$$\frac{dQ}{dt} = -KA\frac{dT}{dx}$$

In steady state (one dimension):
$$\frac{Q}{t} = \frac{KA(T_1 - T_2)}{L}$$

**Thermal Resistance:**
$$R = \frac{L}{KA}$$

Resistances in series: $R_{total} = R_1 + R_2 + ...$
Resistances in parallel: $\frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + ...$

### Radiation

Stefan-Boltzmann Law:
$$P = \sigma A T^4$$

For a black body at temperature $T$ in surroundings at $T_0$:
$$P_{net} = \sigma A (T^4 - T_0^4)$$

Wien's Displacement Law:
$$\lambda_{max} T = b = 2.9 \times 10^{-3} \text{ m·K}$$

> **Hotter objects emit at shorter wavelengths.**

### Newton's Law of Cooling (The Approximation)

For small temperature differences, cooling rate is proportional to temperature difference.

$$\frac{dT}{dt} = -k(T - T_{surr})$$

**Solution:** $T(t) = T_{surr} + (T_0 - T_{surr})e^{-kt}$

**The Exam Formula (Average Form):**
For a body cooling from $T_1$ to $T_2$ in time $t$:
$$\frac{T_1 - T_2}{t} = K \left( \frac{T_1 + T_2}{2} - T_{surr} \right)$$

**When to use:**
- Temperature difference ≲ 40°C from surroundings
- For larger differences, must use Stefan-Boltzmann ($T^4$)

> **This is the "coffee cooling" formula. Use when $\Delta T$ is small.**

---

## PAGE 14 — What JEE Is REALLY Testing

### JEE Main Tests:
- Direct application of formulas
- Single-process calculations
- Basic efficiency problems
- Kinetic theory formulas

### JEE Advanced Tests:
- Multi-process cycles
- Combining First and Second Laws
- Entropy calculations
- Non-ideal processes
- Connecting thermodynamics to mechanics

> **Advanced questions often give a complete cycle and ask about net work, efficiency, or entropy change.**

---

## PAGE 15 — Skill-Based Examples (What Is Being Tested)

### Example 1 — Work in a Cycle

A gas undergoes a cycle: A → B (isobaric) → C (isochoric) → A (isothermal).
Find net work done.

Skill tested:
- Work = Area enclosed by cycle
- Decomposing into known processes

---

### Example 2 — Carnot Efficiency

An engine operates between 500 K and 300 K. What is maximum efficiency?

$$\eta = 1 - \frac{300}{500} = 0.4 = 40\%$$

Skill tested: Carnot limit sets the upper bound

---

### Example 3 — First Law Application

2 moles of diatomic gas expand isobarically. $\Delta T = 100$ K. Find $Q$, $W$, and $\Delta U$.

- $\Delta U = nC_V\Delta T = 2 \times \frac{5}{2}R \times 100 = 500R$
- $W = P\Delta V = nR\Delta T = 200R$
- $Q = \Delta U + W = 700R$

Or directly: $Q = nC_P\Delta T = 2 \times \frac{7}{2}R \times 100 = 700R$ ✓

Skill tested: First Law accounting

---

## PAGE 16 — Common Thermodynamics Traps (Exam Killers)

### Sign Convention Traps
- Confusing work done BY vs ON the system
- Forgetting $Q$ is positive when heat enters

### Process Traps
- Using isothermal formula for adiabatic process
- Forgetting $\Delta U = 0$ for isothermal ideal gas
- Confusing $C_P$ and $C_V$

### Cycle Traps
- Calculating work for open path (not cycle)
- Forgetting work = area ONLY for closed cycle on PV diagram

### Entropy Traps
- Calculating entropy change using irreversible path
- Forgetting entropy is a state function (path independent)

> **Always check: What's constant? What's the process?**

---

## PAGE 17 — Mental Checklist (Before Solving)

Before solving a thermodynamics problem, ask:

1. **What type of process?** (Isothermal, adiabatic, isobaric, isochoric)
2. **What's the system?** (Gas, surroundings, or universe)
3. **Is it a cycle?** (Net work = enclosed area)
4. **Which law applies?** (First Law for energy, Second for direction)
5. **What are the constraints?** (Ideal gas? Reversible?)
6. **Sign convention?** ($Q$ into system positive, $W$ by system positive)

> **Identify the process first. Then apply the right equations.**

---

## PAGE 18 — Forward Connections

Thermodynamics connects to:
- **Mechanics:** Work-energy theorem is a special case
- **Chemistry:** Reaction spontaneity, equilibrium (Gibbs free energy)
- **Statistical Mechanics:** Entropy as $S = k_B \ln W$
- **Engineering:** All engines, refrigerators, power plants

> **Thermodynamics sets limits on what's possible in the physical world.**
