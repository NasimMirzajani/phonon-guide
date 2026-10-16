---
layout: default
lesson_number: 3
title: "Acoustic and optical phonons: What actually makes a lattice vibration couple to light?"
short_title: "Acoustic and optical phonons"
section: "Week 1 · Essential solid-state foundations"
read_time: "8–10 min"
permalink: /lessons/03-acoustic-optical/
---

# Morning Physics Briefing 03
### Acoustic and optical phonons: What actually makes a lattice vibration couple to light?

**Thursday, October 15, 2026 · Week 1: Solid-state foundations**  
**Reading time:** 8–10 minutes  
**Research focus:** Twisted and multilayer van der Waals heterostructures

**Today's central idea:** The distinction between acoustic and optical phonons is fundamentally about collective displacement patterns and their frequencies near the Brillouin-zone center. It is not a distinction between vibrations that do and do not interact with light.

For twisted heterostructures, this matters enormously. Adding layers introduces new vibrational modes; twisting modifies their coupling and symmetry; but only particular modes generate the electric polarization necessary for strong infrared light–matter coupling.

Today we'll connect three concepts that are often introduced separately: phonon branches, two-dimensional lattice dynamics, and infrared-active optical phonons.

---

## 1. Why crystals have acoustic and optical phonons

Recall from yesterday that lattice vibrations are eigenvectors of the dynamical matrix.

Suppose a primitive unit cell contains \\(N\\)atoms.

Each atom can move in three spatial directions, so the crystal has \\(3N\) phonon branches.

Three of these are acoustic branches. The remaining \\(3N-3\) are optical branches.

Why three acoustic branches?

Because translating an entire free crystal rigidly in any of the three spatial directions costs no elastic energy.

These rigid translations correspond to zero-frequency normal modes at the Brillouin-zone center, Γ.

At small but nonzero wavevectors, they become propagating or flexural acoustic vibrations.

Optical modes, by contrast, involve internal relative displacements within the primitive unit cell and generally have finite frequencies at Γ.

Consider a simple diatomic chain.

In its long-wavelength acoustic mode, the two atomic species move approximately together.

In its optical mode, they move relative to one another.

This gives us a useful intuition:

**Acoustic modes describe long-wavelength collective deformation. Optical modes describe internal motion within the basis of the crystal.**

However, the distinction becomes less visually obvious in complex multilayer structures, where optical modes may involve entire atomic layers moving against one another.

### Example: Monolayer MoS₂

A primitive unit cell of monolayer MoS₂ contains three atoms: one molybdenum and two sulfur atoms.

It therefore has nine phonon branches:

| Branch type | Number | Physical character |
|---|---:|---|
| Acoustic | 3 | Long-wavelength collective motion |
| Optical | 6 | Relative motion of atoms within the MoS₂ unit cell |

The optical branches include in-plane and out-of-plane vibrations.

Some are Raman-active, some infrared-active, and their selection rules depend on the symmetry of the crystal.

This distinction will become especially important when we compare monolayer and multilayer spectra.

---

## 2. The unusual acoustic phonons of two-dimensional materials

An ideal free-standing two-dimensional crystal has three acoustic branches.

Two involve in-plane displacements:

**LA — Longitudinal acoustic.** Atomic motion is parallel to the in-plane phonon wavevector.

**TA — Transverse acoustic.** Atomic motion is perpendicular to the in-plane wavevector but remains within the plane.

The third is distinctive:

**ZA — Flexural acoustic.** Atomic motion is perpendicular to the atomic plane.

The name ZA reflects the conventional designation of the out-of-plane direction as \\(z\).

### Why ZA phonons are special

For an ideal, free-standing, tensionless membrane with rotational invariance, the long-wavelength flexural dispersion is quadratic:

<div class="equation">
\[
\boxed{\omega_{\mathrm{ZA}}(q)\approx
\sqrt{\frac{\kappa}{\rho_{2D}}}\,q^2}
\]
</div>

Here, \\(\kappa\) is the bending rigidity, \\(\rho_{2D}\) is the areal mass density, and \\(q\) is the magnitude of the in-plane wavevector.

By contrast, ordinary in-plane acoustic phonons have approximately linear dispersion near Γ.

The physical reason is illuminating.

Stretching a membrane costs energy associated with in-plane strain.

Bending an ideal membrane costs energy associated with curvature.

At long wavelengths, curvature decreases more rapidly with wavelength than ordinary strain, producing the quadratic flexural dispersion.

This has significant consequences for low-frequency phonon populations, thermal transport, and anharmonic interactions.

### What happens in a multilayer?

When two sheets are coupled, their out-of-plane displacements are no longer independent.

One collective motion corresponds to the sheets bending together. Another involves relative out-of-plane motion.

The latter is the origin of the layer-breathing mode discussed yesterday.

In a free-standing bilayer, the common flexural acoustic mode remains gapless. The relative-layer breathing mode has a finite frequency at Γ because changing the layer separation costs interlayer interaction energy.

Substrates, applied tension, and structural reconstruction can modify these simple limiting behaviors.

**Important distinction:** The ZA mode and the layer-breathing mode both involve out-of-plane motion, but they are not the same excitation.

The ZA mode is acoustic; the relative-layer breathing mode is an optical branch of the bilayer.

---

## 3. Optical does not mean optically active

This is probably the most important conceptual correction for today.

The term *optical phonon* is a classification of a lattice normal mode.

It does not guarantee that the mode couples to electromagnetic radiation.

To understand optical activity, we must consider what happens to the electrical polarization when atoms move.

Imagine an optical vibration in which positively and negatively charged sublattices move against one another.

The displacement may generate an oscillating dipole moment.

That oscillating polarization can interact with an electromagnetic field.

However, a vibration can also involve internal atomic motion without producing a net oscillating dipole.

Such a mode may be infrared-inactive even though it is classified as optical.

### Born effective charges

In a crystal, the relationship between atomic displacement and macroscopic polarization is characterized by the *Born effective charge tensor*.

This is not simply the nominal ionic charge.

It describes how the electronic and ionic polarization responds when an atom is displaced.

For a phonon, the contributions from the different atoms must be combined using the phonon eigenvector.

A schematic expression for the mode-induced polarization is

<div class="equation">
\[
\Delta\mathbf P \propto
\sum_{\kappa}\mathbf Z_\kappa^*
\mathbf u_\kappa
\]
</div>

where \\(\mathbf Z_\kappa^*\) is the Born effective charge tensor and \\(\mathbf u_\kappa\) is the displacement of atom \\(\kappa\). The appropriate normalization depends on whether polarization is expressed per unit volume or area.

The central point is that **the displacement pattern and the effective charges together determine whether a phonon creates a macroscopic electric polarization**.

Two modes can have similar frequencies and involve similar atomic species, yet possess very different infrared oscillator strengths.

This is why phonon eigenvectors are indispensable when interpreting infrared spectra.

---

## 4. Raman-active versus infrared-active phonons

Infrared and Raman spectroscopy probe different aspects of the interaction between lattice vibrations and electromagnetic fields.

**Infrared absorption** couples, in the electric-dipole approximation, to vibrations that change the macroscopic dipole moment or polarization.

**Raman scattering** couples to vibrations that change the electronic polarizability tensor.

These are different response functions.

Consequently, a mode can be Raman-active without being infrared-active, infrared-active without being Raman-active, or active in both, depending on crystal symmetry.

For centrosymmetric crystals, first-order electric-dipole Raman and infrared activities obey a mutual-exclusion rule for modes of definite inversion parity.

In noncentrosymmetric crystals, that restriction generally does not apply.

### Why this matters for stacking

Consider two identical monolayers.

The symmetry of the bilayer depends on how the sheets are stacked.

Some stacking arrangements possess inversion symmetry, while others do not.

Twisting can reduce the symmetry further.

Therefore, stacking and twist can modify optical selection rules even if the underlying atomic displacement patterns remain qualitatively similar.

A phonon that is weak or symmetry-forbidden in one configuration may become optically accessible in another.

This is one reason polarization-resolved Raman and infrared measurements are powerful probes of multilayer structure.

But there is an important caveat: a mode becoming optically allowed does not necessarily imply that its frequency has changed substantially.

Selection rules and mechanical restoring forces are distinct aspects of the phonon problem.

---

## 5. The surprising behavior of phonons in multilayer MoS₂

A useful experimental and theoretical example comes from the thickness dependence of the familiar Raman modes of MoS₂.

Two prominent modes are:

- The out-of-plane \\(A_{1g}\) mode in bulk-like notation, corresponding to \\(A_1'\) in an isolated monolayer.
- The in-plane \\(E_{2g}^{1}\) mode in bulk-like notation, corresponding to \\(E'\) in an isolated monolayer.

As the number of layers increases, the out-of-plane mode generally shifts toward higher frequency.

This is reasonably intuitive: neighboring layers introduce additional restoring forces for the sulfur displacements.

But the in-plane mode shifts toward lower frequency.

At first glance, this seems contradictory.

Why would adding mechanically coupled layers soften an optical vibration?

The explanation involves the competition between short-range interatomic forces and long-range Coulomb interactions.

Adding layers increases dielectric screening. This changes the long-range electrostatic contribution to the restoring forces.

For the in-plane mode, the screening-induced softening can outweigh the additional short-range mechanical stiffening.

Molina-Sánchez and Wirtz demonstrated this mechanism in their 2011 first-principles study of MoS₂ and WS₂. citeturn0search0

**The lesson:** A phonon frequency is not determined solely by mechanical bonding stiffness. In polar and partially ionic materials, electrostatic interactions and dielectric screening can be equally important.

This is especially relevant for van der Waals heterostructures because their dielectric environments can be modified without substantially changing the intralayer chemical bonds.

---

## 6. From optical phonons to phonon polaritons

We can now make the connection to the central topic of this series.

An infrared-active optical phonon produces a polarization response.

When that polarization interacts self-consistently with an electromagnetic field, the combined system can support phonon polaritons.

The polariton is not merely a phonon that happens to absorb light.

It is an eigenmode of the coupled electromagnetic and lattice system.

This distinction becomes particularly important in hBN.

In bulk-like hBN, strongly infrared-active optical phonons generate pronounced resonances in the dielectric response.

Because hBN is anisotropic, its in-plane and out-of-plane dielectric tensor components behave differently.

Over particular infrared frequency intervals, these components can have opposite signs in their real parts.

That condition supports hyperbolic phonon polaritons, whose propagation differs dramatically from that of ordinary electromagnetic waves.

We will study the underlying dielectric response and polariton dispersion in Week 3.

For now, retain the conceptual sequence:

**Atomic displacement pattern → oscillating polarization → frequency-dependent dielectric response → coupled electromagnetic–lattice modes.**

Each stage contains physics that cannot be inferred from the phonon frequency alone.

---

## 7. A particularly important subtlety: LO–TO splitting in 2D

In bulk polar crystals, longitudinal optical (LO) and transverse optical (TO) phonons can have different frequencies as the wavevector approaches zero.

The physical origin is the long-range electric field generated by a longitudinal polar vibration.

But the electrostatics changes in two dimensions.

For an ideal isolated polar monolayer, the in-plane LO and TO frequencies become degenerate exactly at Γ.

Nevertheless, the longitudinal mode develops a characteristic nonzero slope as the in-plane wavevector moves away from Γ.

This is a fundamentally different long-wavelength behavior from the conventional three-dimensional case.

Sohier and colleagues established this result using analytical electrostatic models and first-principles calculations.

They also showed that the LO slope depends on the Born effective charges and the dielectric environment, and that the long-wavelength behavior changes with the number of layers. citeturn0search2

### Why this is directly relevant to heterostructures

Consider hBN encapsulated by other two-dimensional materials.

The surrounding layers modify the electrostatic screening.

Even if the intrinsic atomic force constants of hBN remain approximately unchanged, its long-wavelength polar optical phonon dispersion can be modified.

This provides a direct connection between heterostructure engineering and polar lattice excitations.

It also introduces an important distinction between the ideal two-dimensional limit and finite-thickness or bulk-like polar crystals.

**Do not automatically apply bulk LO–TO splitting formulas to an isolated monolayer.**

The dimensionality and electrostatic boundary conditions matter.

---

## 8. What twisting changes—and what it doesn't

Let's apply today's concepts to a twisted hBN heterostructure.

Twist can modify the vibrational problem through several mechanisms.

First, it changes the spatial distribution of stacking registries and therefore the interlayer force constants.

Second, it changes the translational and point-group symmetries of the combined structure, potentially modifying phonon selection rules.

Third, moiré periodicity can couple phonon components with different wavevectors, producing folding and hybridization.

Fourth, structural reconstruction can create domains with different local stacking configurations.

Finally, the dielectric environment and electromagnetic coupling of the layers can change the observed polaritonic modes.

These mechanisms should not be conflated.

For example, observing an additional Raman feature in twisted hBN does not automatically establish the existence of a new infrared-active phonon.

Likewise, a change in polariton propagation does not necessarily imply that the underlying optical phonon frequency has shifted.

The electromagnetic coupling between anisotropic layers may be sufficient to modify the polariton dispersion.

This distinction will be central when we study twisted α-MoO₃ and hBN-based polaritonic heterostructures.

---

## 9. Two papers to read today

### Paper 1 — The solid-state foundation

**Molina-Sánchez and Wirtz (2011)**  
*Phonons in single-layer and few-layer MoS₂ and WS₂*  
*Physical Review B* **84**, 155413.

[Read the paper](https://doi.org/10.1103/PhysRevB.84.155413)

**Why read it:** It connects phonon dispersion, atomic displacement patterns, layer number, dielectric screening, and experimentally observed Raman shifts.

Concentrate on the phonon-dispersion figures and the physical explanation for the opposite thickness trends of the in-plane and out-of-plane Raman modes. The detailed first-principles methodology can wait. citeturn0search0

### Paper 2 — The bridge to polaritons

**Sohier et al. (2017)**  
*Breakdown of Optical Phonons' Splitting in Two-Dimensional Materials*  
*Nano Letters* **17**, 3758–3763.

[Read the paper](https://doi.org/10.1021/acs.nanolett.7b01090)

**Why read it:** This is a particularly valuable paper for understanding why polar phonons behave differently in two-dimensional materials and how electrostatic screening from adjacent layers changes their dispersion.

Focus on the distinction between the LO–TO frequency splitting in three dimensions and the momentum-dependent behavior in two dimensions.

Pay particular attention to the discussion of boron nitride–graphene heterostructures. citeturn0search3

---

## 10. Three questions to test your understanding

**1. Why is a layer-breathing mode considered optical, even though it occurs at a very low frequency?**

Because the classification is based on the displacement pattern and its behavior at Γ, not on the absolute frequency. In the breathing mode, layers move relative to one another, producing a finite restoring force and nonzero frequency.

**2. Can an optical phonon be Raman-active but infrared-inactive?**

Yes. Raman activity depends on changes in polarizability, while infrared activity depends on changes in electric polarization. Their selection rules are different.

**3. Why can adding a layer soften an in-plane optical phonon even though it increases mechanical coupling?**

Because the additional layer can increase dielectric screening, reducing the long-range electrostatic contribution to the restoring force. The net frequency shift reflects competing mechanical and electrostatic effects.

---

## The one idea to remember

**A phonon's frequency tells you how rapidly a normal mode oscillates. Its eigenvector tells you how the atoms move. Its symmetry and effective charges tell you how it interacts with light.**

These are three different pieces of information.

For twisted and multilayer heterostructures, all three can change independently.

That is why a proper interpretation of Raman, infrared, or near-field spectra requires more than assigning peaks to phonon frequencies.

**Next briefing — Crystal symmetry and phonon selection rules.** We'll examine inversion symmetry, point groups, Raman tensors, and how stacking or twist can activate, suppress, or split vibrational modes.
