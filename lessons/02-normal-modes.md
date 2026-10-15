---
layout: default
lesson_number: 2
title: "Normal modes, dynamical matrices, and interlayer vibrations"
short_title: "Normal modes"
section: "Week 1 · Essential solid-state foundations"
read_time: "8–10 min"
permalink: /lessons/02-normal-modes/
---

**Central idea.** Phonons are collective eigenvectors determined by masses and restoring-force curvatures. In multilayers, whole sheets can move against one another, producing low-frequency shear and layer-breathing modes.

## 1. What is the dynamical matrix?

Displace an atom slightly and the neighboring atoms experience forces. Linearizing these forces creates a matrix of force constants; Fourier transforming and mass weighting gives the **dynamical matrix**.

<div class="equation">\[D(\mathbf q)\mathbf e_\nu(\mathbf q)=\omega_\nu^2(\mathbf q)\mathbf e_\nu(\mathbf q)\]</div>

The eigenvalue gives squared phonon frequency and the eigenvector gives relative atomic motion. Frequency alone cannot tell you whether a spectral feature is a shear, breathing, intralayer, or mixed mode.

## 2. Shear versus breathing

- **Shear (C):** Sheets slide laterally against each other. Restoring stiffness depends strongly on the lateral corrugation of the interlayer potential and hence stacking registry.
- **Layer-breathing (LBM):** Sheets move toward and away from each other. The stiffness reflects the local curvature of the binding energy versus interlayer separation.

For rigid sheets with areal mass densities \(\mu_1,\mu_2\) and a harmonic interlayer spring constant per area \(K\), the nonzero relative-motion frequency is

<div class="equation">\[\omega_{\rm rel}^{2}=K\left(\frac{1}{\mu_1}+\frac{1}{\mu_2}\right)\]</div>

Choose lateral or out-of-plane \(K\) for shear or breathing, respectively. This is a local-curvature result, **not** a formula based on total adhesion energy.

## 3. What changes with layer number?

An \(N\)-layer rigid-sheet stack has \(N-1\) relative-layer branches per independent displacement polarization. Modes form families of different displacement patterns. Some are Raman-visible, some IR-visible, and some silent, depending on symmetry and light coupling. The mere existence of a mechanical normal mode does not guarantee a Raman line.

## 4. Why twist is subtle

Twist makes local registry vary across a moiré cell. Shear and breathing probe different directions of the interlayer potential and therefore need not respond similarly. A weakening or disappearance of a *Raman peak* may be a selection-rule or resonance effect rather than disappearance of the underlying eigenmode.

In a dissimilar heterobilayer such as MoS₂/WSe₂, the different layer masses lead to unequal amplitudes in a relative-layer mode. Substrates, reconstruction, and strain can further modify the observed normal modes.

## 5. Bridge to polaritons

Normal-mode displacement vectors and effective charges determine the dielectric oscillator strengths. To obtain a propagating polariton, you must additionally solve Maxwell's equations with the layer dielectric response and boundary conditions. A low-frequency breathing vibration need not support a strong infrared polariton.

## Interpretive pitfall

**A Raman shift is not a direct spring-constant readout.** Mode eigenvectors, masses, optical matrix elements, and spatial inhomogeneity can all affect what you measure.

## Read next

<div class="paper"><a href="https://doi.org/10.1021/acsnano.0c10672">Pizzi et al., “Shear and Breathing Modes of Layered Materials” (ACS Nano, 2021)</a><br>Read the mode illustrations and symmetry/selection-rule discussion.</div>
<div class="paper"><a href="https://doi.org/10.1021/acsnano.5b02502">Wu et al., “Interface Coupling in Twisted Multilayer Graphene by Resonant Raman Spectroscopy of Layer Breathing Modes” (ACS Nano, 2015)</a><br>A concrete twisted-multilayer case study.</div>

**Self-check:** Why can shear soften while breathing remains comparatively unchanged? Can a missing Raman peak establish that a phonon no longer exists?
