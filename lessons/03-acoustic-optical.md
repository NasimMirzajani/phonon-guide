---
layout: default
lesson_number: 3
title: "Acoustic and optical phonons: what actually couples to light?"
short_title: "Acoustic vs optical"
section: "Week 1 · Essential solid-state foundations"
read_time: "8–10 min"
permalink: /lessons/03-acoustic-optical/
---

**Central idea.** “Optical phonon” describes a normal-mode classification, not a guarantee that the vibration absorbs infrared radiation. IR activity requires a nonzero dynamic polarization; Raman activity involves changes in polarizability.

## 1. Acoustic and optical branches

A three-dimensional crystal with \(N\) atoms in its primitive unit cell has \(3N\) phonon branches: three acoustic and \(3N-3\) optical. Acoustic frequencies approach zero at Γ because uniform translation costs no energy. Optical modes involve internal relative displacement and generally remain finite in frequency at Γ.

A monolayer MoS₂ unit cell has three atoms, therefore nine branches: three acoustic and six optical. “Optical” does not mean “high frequency” and “acoustic” does not mean “Raman invisible.” Relative-layer shear and breathing vibrations in multilayers are low-frequency optical branches of the larger unit cell.

## 2. The special flexural mode in two dimensions

A free-standing monolayer has longitudinal (LA), transverse in-plane (TA), and flexural out-of-plane (ZA) acoustic modes. In an ideal tensionless, rotation-invariant membrane, bending energy produces a long-wavelength quadratic ZA dispersion:

<div class="equation">\[\omega_{\rm ZA}(q)\approx\sqrt{\frac{\kappa}{\rho_{2D}}}\,q^2\]</div>

Here \(\kappa\) is bending rigidity, \(ho_{2D}\) is areal mass density, and \(q\) is in-plane wavevector. Tension, substrates and interlayer interactions can modify this ideal behavior. A bilayer's in-phase flexural motion is acoustic; its relative out-of-plane layer-breathing motion is optical.

## 3. What creates infrared activity?

A lattice displacement can produce a dynamic dipole via Born effective charges. In schematic form,

<div class="equation">\[\Delta\mathbf P\propto\sum_\kappa\mathbf Z_\kappa^*\mathbf u_\kappa\]</div>

where \(\mathbf Z_\kappa^*\) is the Born effective-charge tensor and \(\mathbf u_\kappa\) the atomic displacement. The correct normalization depends on whether polarization is defined per volume or per area. Only appropriately polarized modes with nonzero mode-effective charge couple strongly through electric-dipole infrared absorption.

Raman activity instead requires a change in the polarizability tensor. The two selection rules differ; inversion symmetry can create a mutual-exclusion rule for first-order electric-dipole Raman and infrared processes.

## 4. Why layering may soften rather than stiffen

In MoS₂, the out-of-plane Raman mode typically hardens with thickness, while a prominent in-plane mode softens. Increased dielectric screening can reduce the long-range electrostatic contribution to the restoring force, competing with short-range mechanical stiffening. Frequency shifts cannot be interpreted from covalent bonding alone.

## 5. The 2D LO–TO subtlety

In bulk polar crystals, long-range electrostatic fields can generate finite LO–TO frequency splitting at Γ. In an ideal isolated 2D polar monolayer, the in-plane LO and TO frequencies coincide exactly at Γ, but the LO branch has a distinctive slope away from Γ that depends on effective charges and dielectric screening. Stacking and encapsulation can change that electrostatic environment substantially.

## 6. Why this matters for twisted polaritons

A polar optical phonon supplies an infrared dielectric resonance. Coupling that response self-consistently to the electromagnetic field gives a phonon polariton. Twist can alter lattice eigenmodes and selection rules, *or* simply change the coupled electromagnetic modes of anisotropic layers. These are separate effects and should not be conflated.

## Interpretive pitfall

**A Raman-active optical phonon need not be infrared-active, and a new Raman line need not correspond to a new polariton.** Establish symmetry, effective charge, dielectric response and geometry before drawing conclusions.

## Read next

<div class="paper"><a href="https://doi.org/10.1103/PhysRevB.84.155413">Molina-Sánchez & Wirtz, “Phonons in single-layer and few-layer MoS₂ and WS₂” (Physical Review B, 2011)</a><br>Strong physical treatment of layer-dependent phonons and screening.</div>
<div class="paper"><a href="https://doi.org/10.1021/acs.nanolett.7b01090">Sohier et al., “Breakdown of Optical Phonons' Splitting in Two-Dimensional Materials” (Nano Letters, 2017)</a><br>Essential for 2D polar optical modes and dielectric-environment effects.</div>

**Self-check:** Why is an LBM an optical branch? Why does an optical mode sometimes have zero IR oscillator strength?
