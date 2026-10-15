---
layout: default
lesson_number: 1
title: "Reciprocal space and the new momentum scale of moiré lattices"
short_title: "Reciprocal space"
section: "Week 1 · Essential solid-state foundations"
read_time: "8–10 min"
permalink: /lessons/01-reciprocal-space/
---

**Central idea.** A small twist introduces a new, large real-space period and therefore a much smaller reciprocal-space momentum scale. This can modify which lattice excitations couple to one another.

## 1. Why reciprocal space?

A crystal has discrete translation symmetry. Reciprocal space is the natural language for describing the phases of electrons, lattice vibrations, and electromagnetic excitations in that periodic environment.

For a normal-mode displacement in unit cell \(l\), the complex representation is

<div class="equation">\[\mathbf u_{l\kappa}(t)=\mathbf e_\kappa(\mathbf q)e^{i(\mathbf q\cdot\mathbf R_l-\omega t)}\]</div>

Here \(\mathbf q\) is the phonon wavevector, \(\omega\) its angular frequency, and \(\mathbf e_\kappa\) the atomic displacement pattern within a cell. The physical displacement is the real part. Equivalent wavevectors differ by reciprocal lattice vectors.

A **Brillouin zone** is a convenient primitive region of reciprocal space, not a physical wall. In hexagonal materials, phonon papers typically plot selected paths Γ–M–K–Γ through that zone.

## 2. Why twisting changes the scale

For two identical, unstrained lattices rotated by angle \(	heta\), the geometrical moiré period is

<div class="equation">\[L_m=\frac{a}{2\sin(\theta/2)}\]</div>

where \(a\) is the atomic lattice constant. At small angles, \(L_m\) becomes much larger than \(a\). For graphene (\(approx0.246\) nm), a 1° twist gives a moiré period of about 14 nm. Lattice mismatch and relaxation modify the story for real heterostructures.

The moiré reciprocal vectors arise from differences between nearly aligned reciprocal lattice vectors. They provide new momentum transfers, smaller than the original atomic reciprocal lattice vectors.

## 3. What does this do to phonons?

- **Zone folding:** A phonon originally at finite atomic momentum may be represented within a smaller moiré Brillouin zone. Folding alone changes labels, not eigenfrequencies.
- **Mode coupling:** Spatial modulation of the interlayer force constants can couple vibrational components separated by moiré reciprocal vectors; real mixing can shift frequencies and form avoided crossings.
- **Optical access:** Moiré periodicity, altered symmetry, or resonance can make some finite-momentum excitations detectable in Raman-like processes. Visibility is not proof of a new eigenmode.
- **Structural relaxation:** Small-angle heterostructures can form locally preferred stacking domains; reconstruction changes the actual vibrational system beyond geometrical folding.

## 4. Connection to polaritons

A confined phonon polariton carries a large in-plane momentum compared with a photon in free space. Periodicity and anisotropic interfaces can modify the electromagnetic boundary-value problem, while changes to lattice modes can independently change the dielectric response. These mechanisms should be disentangled when interpreting twisted hBN and α-MoO₃ stacks.

## Interpretive pitfall

**A new Raman peak is not automatically a newly created phonon.** Check whether it represents a folded pre-existing mode, a genuinely hybridized eigenstate, a symmetry change, or a reconstruction-induced feature. Compare twist dependence, selection rules, resonance, and mode-eigenvector calculations.

## Read next

<div class="paper"><a href="https://doi.org/10.1073/pnas.1108174108">Bistritzer & MacDonald, “Moiré bands in twisted double-layer graphene” (PNAS, 2011)</a><br>Electronic example that clearly introduces the moiré momentum-coupling picture.</div>

**Self-check:** Why does reducing the twist angle increase moiré wavelength? Why does zone folding not necessarily change a frequency?
