---
title: Physical Chemistry
parent: Chemistry
nav_order: 1
---

# PHYSICAL CHEMISTRY
## The Laws of Balance — Applied Physics with Molecules

---

## PAGE 1 — The Core Insight

Physical Chemistry is **Physics in disguise**.

Every topic follows conservation laws:
- **Mole Concept:** Conservation of atoms (mass balance)
- **Thermodynamics:** Conservation of energy
- **Equilibrium:** Balance of rates
- **Electrochemistry:** Conservation of charge
- **Kinetics:** Energy barriers determine speed

> **If you can solve Physics, you can solve Physical Chemistry.**

### The Strategy

1. Write the balanced equation first
2. Identify what is conserved
3. Set up the constraint equation
4. Solve

---

## PAGE 2 — Mole Concept: The Unit Conversion Game

### The Central Idea

The mole is just a **counting unit** — like "dozen" but for atoms.

$$1 \text{ mole} = 6.022 \times 10^{23} \text{ particles} = N_A$$

### The Conversion Map

```
                    ÷ Molar Mass
        GRAMS ─────────────────────→ MOLES
          ↑                            ↓
          │                            │ × Nₐ
    × Molar Mass                       ↓
          │                        PARTICLES
          │                            │
        MOLES ←────────────────────────┘
                    ÷ Nₐ
```

### The Master Equations

| Conversion | Formula |
|:-----------|:--------|
| Mass → Moles | $n = \frac{m}{M}$ |
| Moles → Particles | $N = n \times N_A$ |
| Gas Volume (STP) → Moles | $n = \frac{V}{22.4}$ |
| Molarity | $M = \frac{n}{V_{liters}}$ |

### The Trap

Confusing **molarity** (moles per liter of solution) with **molality** (moles per kg of solvent).

---

## PAGE 3 — Stoichiometry: The Accounting

### The Invariant

> **Atoms are conserved. Moles react in fixed ratios.**

### The Method

1. Write balanced equation
2. Identify the **limiting reagent** (the one that runs out first)
3. Use mole ratios to find products

### Limiting Reagent Logic

Given reactants A and B:
$$\text{Compare: } \frac{\text{moles of A}}{\text{coefficient of A}} \text{ vs } \frac{\text{moles of B}}{\text{coefficient of B}}$$

**Smaller value = Limiting reagent**

### Percentage Yield

$$\% \text{ Yield} = \frac{\text{Actual yield}}{\text{Theoretical yield}} \times 100$$

---

## PAGE 4 — Concentration Terms (The Dictionary)

| Term | Formula | Key Feature |
|:-----|:--------|:------------|
| **Molarity (M)** | $\frac{\text{moles of solute}}{\text{liters of solution}}$ | Changes with temperature |
| **Molality (m)** | $\frac{\text{moles of solute}}{\text{kg of solvent}}$ | Independent of temperature |
| **Mole Fraction (χ)** | $\frac{n_i}{\sum n}$ | Dimensionless, sums to 1 |
| **Mass %** | $\frac{\text{mass of solute}}{\text{mass of solution}} \times 100$ | Simple but crude |
| **ppm** | $\frac{\text{mass of solute}}{\text{mass of solution}} \times 10^6$ | For trace quantities |

### The Conversion Trick

$$\text{Molarity} = \frac{\text{Molality} \times \text{Density} \times 1000}{1000 + \text{Molality} \times M_{\text{solute}}}$$

> **For dilute solutions:** Molarity ≈ Molality × Density

---

## PAGE 5 — Thermodynamics: Energy Accounting

### The First Law (Conservation of Energy)

$$\Delta U = q + W$$

or equivalently:

$$\Delta U = q - P\Delta V$$ (for expansion work)

| Sign | Meaning |
|:-----|:--------|
| q > 0 | Heat absorbed by system |
| W > 0 | Work done on system |
| ΔU > 0 | Internal energy increases |

### Enthalpy (The "Useful" Energy)

$$H = U + PV$$

$$\Delta H = q_p$$ (heat at constant pressure)

### The Process Table

| Process | Condition | Result |
|:--------|:----------|:-------|
| Isothermal | T = constant | ΔU = 0, q = -W |
| Adiabatic | q = 0 | ΔU = W |
| Isochoric | V = constant | W = 0, ΔU = q |
| Isobaric | P = constant | W = PΔV, ΔH = q |

---

## PAGE 6 — Thermodynamics: The Formulas

### Heat Capacities

$$C_p - C_v = R$$ (for ideal gas)

$$\gamma = \frac{C_p}{C_v}$$

| Gas Type | $C_v$ | $C_p$ | γ |
|:---------|:------|:------|:--|
| Monoatomic | $\frac{3}{2}R$ | $\frac{5}{2}R$ | 1.67 |
| Diatomic | $\frac{5}{2}R$ | $\frac{7}{2}R$ | 1.4 |
| Polyatomic | $3R$ | $4R$ | 1.33 |

### Work Done by Gas

| Process | Work Formula |
|:--------|:-------------|
| Isobaric | $W = P\Delta V = nR\Delta T$ |
| Isothermal | $W = nRT \ln\frac{V_2}{V_1} = nRT \ln\frac{P_1}{P_2}$ |
| Adiabatic | $W = \frac{P_1V_1 - P_2V_2}{\gamma - 1} = \frac{nR(T_1 - T_2)}{\gamma - 1}$ |
| Isochoric | $W = 0$ |

### Adiabatic Relations

$$TV^{\gamma-1} = \text{constant}$$
$$PV^{\gamma} = \text{constant}$$
$$TP^{\frac{1-\gamma}{\gamma}} = \text{constant}$$

---

## PAGE 7 — Thermochemistry: Heat of Reactions

### Hess's Law (The Shortcut)

> **Enthalpy is a state function. The path doesn't matter.**

$$\Delta H_{reaction} = \sum \Delta H_f(\text{products}) - \sum \Delta H_f(\text{reactants})$$

### Bond Enthalpy Method

$$\Delta H = \sum(\text{Bonds broken}) - \sum(\text{Bonds formed})$$

> **Breaking bonds = Endothermic (+)**
> **Forming bonds = Exothermic (−)**

### Standard Enthalpies to Know

| Process | Symbol | Sign |
|:--------|:-------|:-----|
| Formation | $\Delta H_f$ | Usually − for stable compounds |
| Combustion | $\Delta H_c$ | Always − (exothermic) |
| Neutralization | $\Delta H_n$ | −57 kJ/mol (strong acid + strong base) |
| Atomization | $\Delta H_{atom}$ | Always + (endothermic) |

---

## PAGE 8 — Entropy and Gibbs Energy

### The Second Law

> **Entropy of the universe always increases.**

$$\Delta S_{universe} = \Delta S_{system} + \Delta S_{surroundings} \geq 0$$

### Entropy Changes

$$\Delta S = \frac{q_{rev}}{T}$$

$$\Delta S = nC_p \ln\frac{T_2}{T_1}$$ (at constant P)

$$\Delta S = nR \ln\frac{V_2}{V_1}$$ (isothermal expansion)

### Gibbs Free Energy (The Decision Maker)

$$\Delta G = \Delta H - T\Delta S$$

| ΔG | Reaction |
|:---|:---------|
| ΔG < 0 | Spontaneous (forward favored) |
| ΔG > 0 | Non-spontaneous (reverse favored) |
| ΔG = 0 | Equilibrium |

### The Four Cases

| ΔH | ΔS | Spontaneous? |
|:---|:---|:-------------|
| − | + | Always (ΔG always −) |
| + | − | Never (ΔG always +) |
| − | − | At low T |
| + | + | At high T |

---

## PAGE 9 — Chemical Equilibrium: The Balance Point

### The Invariant

> **At equilibrium, forward rate = backward rate.**

### The Equilibrium Constant

For: $aA + bB \rightleftharpoons cC + dD$

$$K_c = \frac{[C]^c[D]^d}{[A]^a[B]^b}$$

$$K_p = \frac{(P_C)^c(P_D)^d}{(P_A)^a(P_B)^b}$$

### The Relationship

$$K_p = K_c(RT)^{\Delta n_g}$$

where $\Delta n_g$ = (moles of gaseous products) − (moles of gaseous reactants)

### The Gibbs-Equilibrium Connection

$$\Delta G° = -RT \ln K$$

$$\Delta G = \Delta G° + RT \ln Q$$

At equilibrium: Q = K, so ΔG = 0.

---

## PAGE 10 — Le Chatelier's Principle (The Response)

### The Rule

> **A system at equilibrium resists change.**

When stressed, equilibrium shifts to **oppose** the stress.

### The Response Table

| Stress | System Response |
|:-------|:----------------|
| Add reactant | Shift → Products |
| Add product | Shift → Reactants |
| Increase P (for gases) | Shift toward fewer moles |
| Increase T | Shift toward endothermic direction |
| Add catalyst | NO shift (speeds both directions equally) |

### Temperature Effect on K

| Reaction Type | Increase T → | K changes |
|:--------------|:-------------|:----------|
| Exothermic (ΔH < 0) | Shift left | K decreases |
| Endothermic (ΔH > 0) | Shift right | K increases |

### Van't Hoff Equation

$$\ln\frac{K_2}{K_1} = \frac{\Delta H°}{R}\left(\frac{1}{T_1} - \frac{1}{T_2}\right)$$

---

## PAGE 11 — Ionic Equilibrium: Acids & Bases

### The Definitions

| Theory | Acid | Base |
|:-------|:-----|:-----|
| Arrhenius | Gives H⁺ | Gives OH⁻ |
| Brønsted-Lowry | Proton donor | Proton acceptor |
| Lewis | Electron pair acceptor | Electron pair donor |

### The Water Equilibrium

$$K_w = [H^+][OH^-] = 10^{-14}$$ at 25°C

$$pH + pOH = 14$$

### Weak Acid/Base Equilibria

For weak acid HA:
$$K_a = \frac{[H^+][A^-]}{[HA]}$$

For weak base B:
$$K_b = \frac{[BH^+][OH^-]}{[B]}$$

**The Relationship:**
$$K_a \times K_b = K_w$$

### The Approximation (for weak acids/bases)

If $K_a << C$ (concentration):
$$[H^+] \approx \sqrt{K_a \times C}$$

$$pH = \frac{1}{2}(pK_a - \log C)$$

### Salt Hydrolysis (The "Reverse" Neutralization)

When salts react with water to change pH.

| Salt Type | Nature | pH Formula |
|:----------|:-------|:-----------|
| **Strong Acid + Strong Base** (NaCl) | Neutral | pH = 7 |
| **Weak Acid + Strong Base** (CH₃COONa) | Basic | $pH = 7 + \frac{1}{2}(pK_a + \log C)$ |
| **Strong Acid + Weak Base** (NH₄Cl) | Acidic | $pH = 7 - \frac{1}{2}(pK_b + \log C)$ |
| **Weak Acid + Weak Base** (CH₃COONH₄) | Depends | $pH = 7 + \frac{1}{2}(pK_a - pK_b)$ |

> **Note:** For WA+WB, pH is independent of concentration!

---

## PAGE 12 — Buffer Solutions

### The Definition

A buffer resists pH change when small amounts of acid/base are added.

### Types

| Buffer Type | Components | Example |
|:------------|:-----------|:--------|
| Acidic buffer | Weak acid + its salt | CH₃COOH + CH₃COONa |
| Basic buffer | Weak base + its salt | NH₃ + NH₄Cl |

### Henderson-Hasselbalch Equation

**Acidic buffer:**
$$pH = pK_a + \log\frac{[\text{Salt}]}{[\text{Acid}]}$$

**Basic buffer:**
$$pOH = pK_b + \log\frac{[\text{Salt}]}{[\text{Base}]}$$

### Buffer Capacity

Maximum when [Acid] = [Salt], i.e., pH = pKa

> **The buffer is most effective within pH = pKa ± 1**

---

## PAGE 13 — Solubility Equilibrium

### Solubility Product

For salt $A_xB_y$:
$$K_{sp} = [A^{y+}]^x[B^{x-}]^y$$

### Solubility Calculation

If solubility = s:
- For AB: $K_{sp} = s^2$, so $s = \sqrt{K_{sp}}$
- For AB₂: $K_{sp} = 4s^3$, so $s = \sqrt[3]{\frac{K_{sp}}{4}}$
- For A₂B₃: $K_{sp} = 108s^5$

### Precipitation Condition

**Ionic Product (Q) vs Ksp:**
- Q > Ksp → Precipitation occurs
- Q < Ksp → Unsaturated (no precipitation)
- Q = Ksp → Saturated (equilibrium)

### Common Ion Effect

Adding a common ion **decreases** solubility.

Example: Adding NaCl to AgCl solution decreases AgCl solubility.

---

## PAGE 14 — Chemical Kinetics: Speed of Reactions

### The Rate Expression

For: $aA + bB \to \text{Products}$

$$\text{Rate} = -\frac{1}{a}\frac{d[A]}{dt} = -\frac{1}{b}\frac{d[B]}{dt}$$

### Rate Law

$$\text{Rate} = k[A]^m[B]^n$$

- m, n = orders (determined experimentally)
- m + n = overall order
- k = rate constant

### Integrated Rate Laws

| Order | Rate Law | Integrated Form | Half-life | Units of k |
|:------|:---------|:----------------|:----------|:-----------|
| 0 | Rate = k | $[A] = [A]_0 - kt$ | $\frac{[A]_0}{2k}$ | mol L⁻¹ s⁻¹ |
| 1 | Rate = k[A] | $\ln[A] = \ln[A]_0 - kt$ | $\frac{0.693}{k}$ | s⁻¹ |
| 2 | Rate = k[A]² | $\frac{1}{[A]} = \frac{1}{[A]_0} + kt$ | $\frac{1}{k[A]_0}$ | L mol⁻¹ s⁻¹ |

### The Key Insight

> **First-order half-life is constant. Zero-order half-life depends on initial concentration.**

### Parallel First-Order Reactions

If A decomposes into B ($k_1$) and C ($k_2$) simultaneously:

$$A \xrightarrow{k_1} B$$
$$A \xrightarrow{k_2} C$$

1. **Effective Rate Constant:** $k_{eff} = k_1 + k_2$
2. **Effective Half-Life:** $T_{eff} = \frac{0.693}{k_1 + k_2}$
3. **Yield % of B:** $\frac{k_1}{k_1 + k_2} \times 100$

> **It works exactly like parallel decay in Nuclear Physics.**

---

## PAGE 15 — Arrhenius Equation (Temperature Dependence)

### The Equation

$$k = A e^{-E_a/RT}$$

**Logarithmic form:**
$$\ln k = \ln A - \frac{E_a}{RT}$$

### Two-Temperature Form

$$\ln\frac{k_2}{k_1} = \frac{E_a}{R}\left(\frac{1}{T_1} - \frac{1}{T_2}\right)$$

### The Physical Meaning

| Term | Meaning |
|:-----|:--------|
| A | Pre-exponential factor (collision frequency) |
| Ea | Activation energy (energy barrier) |
| $e^{-E_a/RT}$ | Fraction of molecules with sufficient energy |

### Catalyst Effect

A catalyst **lowers Ea** → k increases → reaction faster.

> **Catalyst changes the path, not the destination (ΔH unchanged).**

---

## PAGE 16 — Electrochemistry: Charge Conservation

### The Invariant

> **Electrons lost = Electrons gained (always)**

### Oxidation & Reduction

| Process | Electron Change | Oxidation Number |
|:--------|:----------------|:-----------------|
| Oxidation | Loses electrons | Increases |
| Reduction | Gains electrons | Decreases |

> **OIL RIG:** Oxidation Is Loss, Reduction Is Gain

### Electrochemical Cells

| Cell Type | ΔG | E°cell | Spontaneous? |
|:----------|:---|:-------|:-------------|
| Galvanic | < 0 | > 0 | Yes |
| Electrolytic | > 0 | < 0 | No (needs external power) |

### Cell Potential

$$E°_{cell} = E°_{cathode} - E°_{anode}$$

> **Cathode = Reduction. Anode = Oxidation.**

---

## PAGE 17 — Nernst Equation

### The Equation

$$E = E° - \frac{RT}{nF}\ln Q$$

At 25°C:
$$E = E° - \frac{0.059}{n}\log Q$$

### At Equilibrium

E = 0, Q = K

$$E° = \frac{0.059}{n}\log K$$

### Gibbs-Electrochemistry Connection

$$\Delta G° = -nFE°$$

| If E° > 0 | ΔG° < 0 | Spontaneous |
| If E° < 0 | ΔG° > 0 | Non-spontaneous |

### Concentration Cell

Same electrodes, different concentrations:
$$E = \frac{0.059}{n}\log\frac{[C_1]}{[C_2]}$$

---

## PAGE 18 — Conductance & Electrolysis

### Conductance (The Flow of Ions)

- **Conductivity ($\kappa$):** Conductance of 1 cm³ solution. $\kappa = \frac{1}{R} \times \text{Cell Constant}$
- **Molar Conductivity ($\Lambda_m$):** $\Lambda_m = \frac{\kappa \times 1000}{\text{Molarity}}$

### Kohlrausch's Law (Independent Migration)

At infinite dilution ($\infty$), ions move independently.

$$\Lambda_m^\infty (A_xB_y) = x\lambda^\infty_{A^+} + y\lambda^\infty_{B^-}$$

> **Application:** Find $\Lambda^\infty$ for weak acid (CH₃COOH) using strong salts:
> $$\Lambda^\infty_{CH_3COOH} = \Lambda^\infty_{CH_3COONa} + \Lambda^\infty_{HCl} - \Lambda^\infty_{NaCl}$$

### Degree of Dissociation from Conductance

$$\alpha = \frac{\Lambda_m}{\Lambda_m^\infty}$$

### Faraday's Laws

#### First Law

$$m = ZIt = \frac{MIt}{nF}$$

Where:
- m = mass deposited
- M = molar mass
- n = electrons transferred per ion
- F = 96500 C/mol
- I = current (A)
- t = time (s)

### Second Law

When same charge passes through different electrolytes:
$$\frac{m_1}{m_2} = \frac{E_1}{E_2}$$

where E = equivalent weight = M/n

### Practical Applications

| At Cathode | At Anode |
|:-----------|:---------|
| Metal deposits | Metal dissolves |
| H₂ evolves (from water) | O₂ evolves (from water) |
| Reduction | Oxidation |

---

## PAGE 19 — Solutions: Colligative Properties

### The Key Insight

> **Colligative properties depend on NUMBER of particles, not their identity.**

### The Four Properties

| Property | Formula | Depends On |
|:---------|:--------|:-----------|
| Relative lowering of VP | $\frac{P° - P}{P°} = \chi_{solute}$ | Mole fraction |
| Elevation of BP | $\Delta T_b = K_b \times m \times i$ | Molality |
| Depression of FP | $\Delta T_f = K_f \times m \times i$ | Molality |
| Osmotic pressure | $\pi = iCRT$ | Molarity |

### Van't Hoff Factor (i)

For electrolytes that dissociate:
$$i = 1 + \alpha(n - 1)$$

Where:
- α = degree of dissociation
- n = number of ions per formula unit

| Solute | i (complete dissociation) |
|:-------|:--------------------------|
| Glucose | 1 |
| NaCl | 2 |
| CaCl₂ | 3 |
| AlCl₃ | 4 |

### Ideal vs Non-Ideal Solutions (Raoult's Law Deviations)

| Type | Interaction (A-B vs A-A) | $\Delta H_{mix}$ | $\Delta V_{mix}$ | Deviation | Example |
|:-----|:-------------------------|:-----------------|:-----------------|:----------|:--------|
| **Ideal** | A-B ≈ A-A | 0 | 0 | None | Benzene + Toluene |
| **Positive Deviation** | A-B < A-A (Hates mixing) | > 0 (Endo) | > 0 (Expands) | $P_{vap} > P_{ideal}$ | Ethanol + Acetone |
| **Negative Deviation** | A-B > A-A (Loves mixing) | < 0 (Exo) | < 0 (Shrinks) | $P_{vap} < P_{ideal}$ | CHCl₃ + Acetone |

> **Azeotropes:** Constant boiling mixtures formed by non-ideal solutions.
> - **Minimum boiling azeotrope:** Positive deviation (e.g., Ethanol-Water at 95.6%)
> - **Maximum boiling azeotrope:** Negative deviation (e.g., HCl-Water)

---

## PAGE 20 — Solid State: Crystal Geometry

### The Unit Cells

| Type | Atoms per unit cell | Packing efficiency | Examples |
|:-----|:--------------------|:-------------------|:---------|
| Simple cubic (SC) | 1 | 52% | Po |
| Body-centered cubic (BCC) | 2 | 68% | Na, K, Fe |
| Face-centered cubic (FCC) | 4 | 74% | Cu, Ag, Au |
| Hexagonal close-packed (HCP) | 6 | 74% | Mg, Zn |

### Relationship: Edge length (a) and Radius (r)

| Type | Relation |
|:-----|:---------|
| SC | $a = 2r$ |
| BCC | $a = \frac{4r}{\sqrt{3}}$ |
| FCC | $a = 2\sqrt{2}r$ |

### Density Formula

$$\rho = \frac{Z \times M}{a^3 \times N_A}$$

Where Z = atoms per unit cell

### Voids in Close Packing

| Void Type | Location | Radius ratio |
|:----------|:---------|:-------------|
| Tetrahedral | Between 4 atoms | r/R = 0.225 |
| Octahedral | Between 6 atoms | r/R = 0.414 |

In FCC/HCP: 8 tetrahedral voids, 4 octahedral voids per unit cell

---

## PAGE 21 — Common Traps and Fixes

### Mole Concept Traps

| Trap | Fix |
|:-----|:----|
| Using molecular mass for ionic compounds | Use formula mass |
| Forgetting to balance equation first | ALWAYS balance first |
| Mixing up molarity and molality | Molarity = per liter solution, Molality = per kg solvent |

### Thermodynamics Traps

| Trap | Fix |
|:-----|:----|
| Wrong sign for work | Expansion by gas: W = −PΔV (work done BY gas is negative for system) |
| Using ΔH for ΔU | ΔH = ΔU + PΔV (they're different for gases) |
| Applying ΔG = ΔH − TΔS at non-standard conditions | Use ΔG = ΔG° + RT ln Q |

### Equilibrium Traps

| Trap | Fix |
|:-----|:----|
| Thinking catalyst shifts equilibrium | Catalyst speeds both directions equally—no shift |
| Adding inert gas at constant V shifts equilibrium | No effect (partial pressures unchanged) |
| Confusing Q and K | Q = current ratio, K = equilibrium ratio |

### Electrochemistry Traps

| Trap | Fix |
|:-----|:----|
| Wrong cell notation | Anode on left, cathode on right |
| Sign confusion in Nernst equation | E = E° − (0.059/n) log Q |
| Forgetting n in calculations | n = electrons transferred in balanced half-reaction |

---

## PAGE 22 — The Physical Chemistry Algorithm

When you see a Physical Chemistry problem:

```
1. IDENTIFY the conserved quantity
   ├── Mass? → Stoichiometry
   ├── Energy? → Thermodynamics
   ├── Charge? → Electrochemistry
   └── Concentration? → Equilibrium

2. WRITE the balanced equation

3. SET UP the constraint
   ├── ICE table for equilibrium
   ├── Energy balance for thermo
   └── Electron balance for electrochemistry

4. SOLVE using algebra (same as Physics)
```

> **Physical Chemistry = Physics with molecules. Solve it the same way.**

---

## PAGE 23 — Quick Reference: Must-Know Values

### Constants

| Constant | Value |
|:---------|:------|
| R (gas constant) | 8.314 J mol⁻¹ K⁻¹ = 0.0821 L atm mol⁻¹ K⁻¹ |
| F (Faraday) | 96500 C mol⁻¹ |
| NA (Avogadro) | 6.022 × 10²³ mol⁻¹ |
| Molar volume at STP | 22.4 L mol⁻¹ |

### Key Numbers

| Quantity | Value |
|:---------|:------|
| pH of neutral water (25°C) | 7 |
| Kw at 25°C | 10⁻¹⁴ |
| ΔHneutralization (strong acid + strong base) | −57 kJ/mol |
| 0.059 V | RT/F × 2.303 at 25°C |

### Quick Conversions

| From | To | Multiply by |
|:-----|:---|:------------|
| cal | J | 4.184 |
| atm | Pa | 101325 |
| eV | J | 1.6 × 10⁻¹⁹ |
| °C | K | +273 |
