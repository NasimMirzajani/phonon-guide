---
layout: default
lesson_number: 9
title: "Stacking Registry, Symmetry, and the Interlayer Energy Landscape"
short_title: "Stacking Registry, Symmetry, and Interlayer Energy"
section: "Week 2 · Multilayer and twist physics"
read_time: "9–10 min"
permalink: /lessons/09-stacking-registry-symmetry-interlayer-energy/
---

# Morning Physics Briefing 07
## Stacking Registry, Symmetry, and the Interlayer Energy Landscape

**Wednesday, 21 October 2026 | Week 2 — Multilayer and Twist Physics | Reading time: 9–10 minutes**

**Today's central question:** Why can two multilayer crystals with identical chemical compositions and nearly identical interlayer force constants exhibit dramatically different Raman spectra—and how does the same stacking physics drive atomic reconstruction in twisted bilayers?

Yesterday, we established that interlayer shear and breathing modes probe different curvatures of the interaction potential between neighboring atomic layers.

Today, we examine what determines those curvatures.

The central variable is **stacking registry**: the relative atomic positions of adjacent layers.

In a van der Waals heterostructure, stacking is not merely a geometrical label. It determines the interlayer energy, the local mechanical stiffness, the symmetry of the combined crystal, and the optical activity of its vibrational modes.

When the layers are twisted, the registry becomes position-dependent. The resulting competition between interlayer stacking energy and intralayer elasticity can cause the atoms to reorganize into domains separated by narrow boundaries.

This provides the microscopic foundation for understanding moiré reconstruction, phonon folding, and interface-localized vibrations.

---

## 1. What exactly is stacking registry?

Consider two identical monolayers of MoS₂.

Each monolayer consists of a plane of molybdenum atoms sandwiched between two planes of sulfur atoms.

The individual monolayers have strong intralayer covalent bonding.

When two monolayers are stacked, their relative configuration depends on three variables:

1. Their relative crystallographic orientation.
2. Their lateral translation.
3. Their vertical separation.

The first two determine which atoms in one layer lie above particular atomic sites in the other.

The third determines how closely the layers approach each other.

These variables jointly determine the interlayer interaction energy.

Imagine holding the lower layer fixed while translating the upper layer laterally.

At some positions, the arrangement is energetically favorable.

At others, the electronic charge distributions and atomic cores interact less favorably.

The resulting energy is periodic under translations by lattice vectors.

This periodic energy landscape is sometimes called the *generalized stacking-fault energy surface* or *interlayer sliding potential*.

Its shape contains more information than the equilibrium stacking configuration alone.

The depth of a minimum describes its energetic preference relative to other configurations.

The curvature around that minimum determines the restoring force for small displacements.

The energy barriers between minima determine the energetic cost of larger sliding motions.

**A stacking configuration can be energetically favorable without being exceptionally resistant to small lateral displacements.**

This distinction between energy and curvature is fundamental.

---

## 2. The connection between stacking energy and phonon frequencies

Suppose the layers occupy a mechanically stable stacking configuration.

We now displace one layer slightly relative to the other.

For sufficiently small displacements, the interlayer energy can be approximated by a quadratic expansion:

<div class="equation">

\[
\boxed{
V(\mathbf{u},z)
\simeq
V_0
+
\frac{1}{2}\mathbf{u}^{T}
\mathbf{K}_{\parallel}\mathbf{u}
+
\frac{1}{2}K_{\perp}(z-z_0)^2
}
\]

</div>

Here:

- \\(V(\mathbf{u},z)\\) is the interlayer interaction energy per unit area.
- \\(\mathbf{u}\\) is the small lateral displacement from the equilibrium stacking registry.
- \\(z\\) is the interlayer separation.
- \\(z_0\\) is the equilibrium separation.
- \\(V_0\\) is the equilibrium interlayer energy per unit area.
- \\(\mathbf{K}_{\parallel}\\) is the matrix of lateral interlayer force constants per unit area.
- \\(K_{\perp}\\) is the out-of-plane force constant per unit area.

This expression assumes that the equilibrium configuration is stable and that the leading coupling between lateral and vertical displacements can be neglected. Such coupling is symmetry-forbidden at some high-symmetry registries but need not vanish in a general interface.

The eigenvalues of the lateral force-constant matrix determine the restoring forces associated with the two shear polarizations.

The out-of-plane force constant determines the restoring force associated with the breathing vibration.

This immediately reveals an important consequence.

Two stacking configurations may have similar equilibrium interlayer energies but different shear frequencies.

Conversely, they may have different energies but similar local force constants.

The shear mode measures the curvature of the energy landscape, not its absolute depth.

### What if the lateral stiffness is anisotropic?

In a high-symmetry hexagonal bilayer, the two in-plane shear polarizations may be degenerate.

But if the stacking configuration lowers the rotational symmetry, the lateral force-constant matrix need not have equal eigenvalues.

The shear degeneracy can then be lifted.

This can produce two distinct shear frequencies.

Such splitting provides information about the anisotropy of the interlayer potential.

However, a measured splitting could also arise from strain or other symmetry-breaking perturbations.

The frequency difference alone does not uniquely identify the stacking configuration.

---

## 3. Two important stacking families: 2H and 3R MoS₂

We now consider two well-established stacking arrangements of multilayer MoS₂.

### 2H stacking

In conventional 2H stacking, adjacent monolayers have alternating crystallographic orientations.

An ideal 2H bilayer possesses inversion symmetry.

This is important because an isolated monolayer of 2H-phase MoS₂ does not possess inversion symmetry.

Stacking a second layer in the conventional 2H arrangement therefore restores a symmetry absent in the monolayer.

For thicker 2H structures, inversion symmetry depends on layer number: ideal even-layer stacks are centrosymmetric, whereas ideal odd-layer stacks are not.

### 3R stacking

In 3R stacking, successive monolayers have a different relative orientation and lateral translation.

The ideal 3R structure lacks inversion symmetry.

This remains true for its conventional multilayer stacking sequence.

The two polytypes therefore differ in symmetry even though their constituent monolayers have essentially the same chemical bonding.

The differences can be summarized as follows:

| Property | Conventional 2H MoS₂ | Conventional 3R MoS₂ |
|---|---|---|
| Chemical composition | MoS₂ | MoS₂ |
| Relative layer arrangement | Alternating orientation | Parallel-orientation stacking sequence |
| Inversion symmetry in an ideal bilayer | Present | Absent |
| Interlayer shear and breathing modes | Present | Present |
| Raman selection rules | Governed by centrosymmetric bilayer symmetry | Governed by noncentrosymmetric bilayer symmetry |
| Typical interlayer force constants | Comparable to 3R, with measurable differences | Comparable to 2H, with measurable differences |

The central question is whether these structural differences primarily change the phonon frequencies or the optical visibility of the phonons.

The answer is that both effects occur, but they can have very different magnitudes.

---

## 4. Why stacking symmetry changes Raman spectra

Recall that [Raman scattering](https://en.wikipedia.org/wiki/Raman_scattering) probes the change in electronic polarizability produced by a vibrational displacement.

A phonon is Raman-active only if its symmetry allows the corresponding polarizability response.

The relevant Raman tensor depends on the vibrational eigenvector and the symmetry of the crystal.

This is why two mechanically similar modes can produce very different Raman intensities.

### Inversion symmetry and optical selection rules

In a centrosymmetric crystal, zone-center vibrational modes can be classified according to their parity under inversion.

Within the usual electric-dipole approximation, Raman-active modes have even parity, whereas infrared-active modes have odd parity.

This leads to the familiar mutual-exclusion rule for centrosymmetric crystals.

The situation changes when inversion symmetry is absent.

Modes are no longer classified by inversion parity, and some vibrations can be both Raman-active and infrared-active.

This is relevant when comparing ideal 2H and 3R MoS₂ bilayers.

However, **the absence of inversion symmetry does not mean that every phonon becomes optically active**.

Other point-group symmetries still constrain the Raman and infrared matrix elements.

The measurement geometry and light polarization also matter.

### A deeper point: Symmetry does not determine intensity by itself

Group theory tells us whether a Raman matrix element is allowed.

It does not generally determine how large that matrix element will be.

A symmetry-allowed vibration may still produce a very weak signal.

To predict intensity, we must understand how the electronic polarizability changes as the atoms move.

This brings us to the effective bond-polarizability model.

---

## 5. Why different shear branches dominate in 2H and 3R multilayers

Consider a multilayer containing more than two MoS₂ layers.

As we learned yesterday, the system supports several interlayer shear branches.

Each branch has a different pattern of relative layer displacement.

For example, one mode may involve neighboring layers moving strongly against each other.

Another may involve groups of layers moving more coherently.

The Raman intensity depends on how the polarizability changes across all the interfaces during the vibration.

These contributions can reinforce or cancel one another.

### The role of stacking

In 2H stacking, the orientation of adjacent layers produces a particular pattern of interlayer polarizability changes.

In 3R stacking, that pattern differs.

Consequently, the same general class of shear vibrations can produce very different interference among the Raman contributions from different interfaces.

The experimentally important result is striking.

Van Baren and colleagues investigated 2H and 3R MoS₂ multilayers using polarization-dependent ultralow-frequency Raman spectroscopy.

They found that the strongest shear-mode Raman signal occurs on the **highest-frequency shear branch in 2H stacking**, but on the **lowest-frequency shear branch in 3R stacking**.

Meanwhile, the breathing modes exhibit broadly similar Raman-activity trends in the two polytypes, although the measured breathing frequencies are consistently several inverse centimeters higher in 2H structures. 

This is an exceptionally useful experimental result.

It shows that stacking can strongly redistribute Raman intensity among existing phonon branches without requiring a similarly dramatic change in the underlying mechanical force constants.

The authors explained the observations by combining group theory, a linear-chain model, an effective bond-polarizability model, and first-principles calculations.

**Important qualification:** An ideal bilayer possesses only one nonzero rigid-layer shear frequency, with two potentially degenerate in-plane polarizations. The distinction between highest- and lowest-frequency shear branches becomes meaningful for thicker multilayers.

---

## 6. What does a Raman spectrum actually tell us about stacking?

Suppose we measure a five-layer MoS₂ crystal.

The spectrum contains several low-frequency Raman peaks.

One shear branch is particularly strong.

Can we determine whether the structure has 2H or 3R stacking?

Potentially, yes—but not from peak intensity alone.

A robust assignment should consider several observables.

First, the frequencies should be compared with the expected shear and breathing branches for the measured layer number.

Second, polarization-resolved Raman spectroscopy should be used to identify the relevant mode symmetries.

Third, the relative intensities of different branches should be compared with a model of the Raman tensors.

Fourth, the structural assignment should ideally be checked using an independent technique.

Electron diffraction, second-harmonic generation, and suitable scanning probe methods can provide complementary information.

For example, second-harmonic generation is sensitive to inversion symmetry within the electric-dipole approximation.

An ideal centrosymmetric 2H bilayer has a strongly suppressed bulk electric-dipole second-harmonic response.

An ideal noncentrosymmetric 3R bilayer can support a substantial response.

However, surfaces, substrates, defects, and higher-order optical processes can complicate this comparison.

Thus, Raman and nonlinear optical measurements are powerful structural probes, but their interpretation remains model-dependent.

---

## 7. From uniform stacking to a twisted interface

We now introduce a relative twist angle.

Imagine rotating one MoS₂ layer by a small angle relative to the other.

The two atomic lattices no longer share a single uniform stacking registry across the sample.

Instead, the local relative displacement varies gradually with position.

Different regions of the interface resemble different local stacking configurations.

This produces a [Moiré superlattice](https://en.wikipedia.org/wiki/Moir%C3%A9_pattern).

For two identical hexagonal lattices with a small relative twist angle, the moiré wavelength becomes large as the twist angle approaches zero.

The important consequence is that the interlayer energy is now position-dependent.

Some local registries are energetically favorable.

Others are less favorable.

If the layers remained perfectly rigid, the moiré pattern would simply represent the geometrical variation of registry.

But real atomic layers can deform.

That introduces a new competition.

---

## 8. The competition between stacking energy and intralayer elasticity

Suppose the layers could move laterally without any elastic penalty.

They would tend to rearrange locally toward the most favorable stacking configurations.

However, changing the local atomic positions strains the individual layers.

The strong intralayer bonds resist such deformation.

The actual relaxed structure therefore minimizes a combination of interlayer stacking energy and intralayer elastic energy.

A simplified continuum description is

<div class="equation">

\[
\boxed{
E[\mathbf{u}]
=
\int d^2r
\left[
\frac{1}{2}
C_{ijkl}\epsilon_{ij}\epsilon_{kl}
+
V_{\mathrm{stack}}
\bigl(\boldsymbol{\delta}_0(\mathbf{r})+\mathbf{u}(\mathbf{r})\bigr)
\right]
}
\]

</div>

Here:

- \\(E[\mathbf{u}]\\) is the total energy functional of the relaxed relative-displacement field.
- \\(\mathbf{r}\\) is the in-plane position.
- \\(\mathbf{u}(\mathbf{r})\\) describes the local relative in-plane relaxation of the two layers.
- \\(\boldsymbol{\delta}_0(\mathbf{r})\\) is the local stacking registry predicted by the unrelaxed twisted geometry.
- \\(V_{\mathrm{stack}}\\) is the stacking-dependent interlayer energy per unit area.
- \\(C_{ijkl}\\) is an effective in-plane elastic tensor appropriate to the relative-displacement field.
- \\(\epsilon_{ij}\\) is the corresponding in-plane strain tensor.

This is a simplified model with the interlayer separation held fixed or treated implicitly. A more complete treatment can include separate displacement fields for each layer, out-of-plane relaxation, and coupling between vertical separation and stacking registry.

The physical meaning is straightforward.

The elastic term penalizes spatially varying atomic displacement.

The stacking-energy term rewards locally favorable registry.

The relaxed structure is determined by their competition.

### What happens at relatively large twist angles?

The moiré wavelength is comparatively short.

Rearranging the atoms enough to produce large favorable domains may require substantial strain.

The elastic penalty can therefore prevent strong reconstruction.

The local registry varies relatively smoothly across the interface.

### What happens at very small twist angles?

The moiré wavelength becomes large.

The system has more spatial room to accommodate favorable stacking regions.

It can become energetically advantageous to form extended domains of low-energy registry.

The mismatch between neighboring domains becomes concentrated into narrow boundaries.

These boundaries are often described as stacking solitons or dislocations.

**The moiré pattern is therefore not necessarily the same as the relaxed atomic structure.**

At sufficiently small twist angles, a smooth geometrical moiré modulation can transform into a network of domains and domain walls.

---

## 9. Experimental evidence for atomic reconstruction

A particularly important demonstration was provided by Weston and colleagues.

Using atomic-resolution transmission electron microscopy, they studied twisted bilayers of MoS₂ and WS₂.

They directly observed atomic reconstruction at small twist angles.

The resulting structures depended strongly on whether the relative layer orientation was close to the 3R or 2H stacking family.

### Near 3R alignment

For twisted bilayers close to 3R stacking, the researchers observed triangular domains with symmetry-related stacking configurations.

These domains were separated by networks of partial dislocations.

The reconstruction became pronounced for twist angles below approximately 2°.

### Near 2H alignment

The behavior was different for bilayers close to 2H stacking.

Energetically favorable 2H domains occupied much of the structure.

Metastable regions and dislocation networks formed a different spatial pattern.

The observed domain topology evolved with twist angle.

These results demonstrated that the stacking-energy landscape determines not only local atomic registry but also the large-scale geometry of the reconstructed moiré structure.

This distinction between 2H-like and 3R-like reconstruction is particularly important.

A twist angle by itself is not enough to specify the structural state.

We must also know the relative orientation family and the stacking-energy landscape.

---

## 10. Why reconstruction matters for phonons

Consider a twisted bilayer before substantial reconstruction.

The local interlayer force constants vary across the moiré pattern.

Now allow the structure to reconstruct.

Large regions develop approximately uniform favorable stacking.

The domain walls accommodate much of the relative displacement between neighboring regions.

The vibrational problem has changed.

Instead of a nearly uniform spatial modulation, we now have domains with distinct mechanical environments connected by relatively narrow boundaries.

This can affect phonons in several ways.

### Local shear stiffness

Within a reconstructed domain, the interlayer shear restoring force reflects the curvature of the stacking-energy minimum associated with that domain.

The effective shear stiffness near a domain wall may be different because the local registry varies rapidly.

### Low-energy collective motion

Domain walls may possess collective displacement modes.

These can involve motion of the boundary itself rather than uniform translation of an entire layer.

Such excitations are conceptually distinct from the rigid-layer shear mode of a conventional bilayer.

### Phonon localization

A spatial variation in the force constants can create regions where particular vibrational modes are energetically favored.

Under suitable conditions, vibrations may become concentrated near domains or domain walls.

However, localization must be established from the phonon eigenvectors or a suitable spatially resolved measurement.

A new spectral peak alone is insufficient.

### Raman selection rules

The local symmetry differs between domains and domain walls.

Consequently, their Raman tensors may differ.

A vibration that is weak in a uniform reference structure may acquire optical intensity in a reconstructed moiré structure.

This is one mechanism by which twisting can activate additional spectral features.

But it is not the same as zone folding.

We will separate these mechanisms explicitly in the next two briefings.

---

## 11. A connection to phonon polaritons

Why should a researcher interested in phonon polaritons care about stacking reconstruction?

Because stacking can modify both the mechanical and electromagnetic properties of an interface.

For a polar material, local symmetry determines which vibrations carry an oscillating electric dipole.

Reconstruction may therefore alter the spatial distribution of infrared-active lattice response.

A domain wall may also modify local strain, interlayer separation, or dielectric screening.

These changes can influence electromagnetic mode propagation.

However, the interpretation requires care.

A spatially localized infrared near-field signal does not automatically demonstrate a localized phonon eigenmode.

The signal may instead arise from a local change in dielectric function, electromagnetic boundary conditions, or polariton scattering.

This is particularly important in twisted polar heterostructures, where structural and electromagnetic inhomogeneity can occur simultaneously.

For example, a reconstructed twisted hBN bilayer could exhibit spatial variations in local stacking and symmetry.

Those variations may affect its vibrational and infrared response.

But to establish a new interface-localized phonon, one would need evidence that the atomic displacement eigenvector itself is localized near the relevant structural feature.

To establish a localized polaritonic mode, one would instead examine electromagnetic field profiles and dispersion.

The two possibilities are related but physically distinct.

---

## 12. Today's principal interpretive pitfall

### Misconception: If two stacking configurations have nearly identical phonon frequencies, their interlayer physics must be nearly identical.

This is incorrect.

Similar phonon frequencies indicate similar effective restoring forces for the measured vibrational modes.

They do not imply identical stacking energies.

They do not imply identical inversion symmetry.

They do not imply identical Raman tensors.

And they do not imply identical reconstruction behavior under twisting.

The 2H and 3R polytypes of MoS₂ provide an instructive example.

Their interlayer breathing frequencies are relatively similar, although experimentally distinguishable.

Yet their shear-mode Raman intensities can exhibit strikingly different branch dependence.

The differences arise from the combination of mechanical coupling, stacking geometry, and optical selection rules.

The same principle applies to twisted heterostructures.

A small frequency shift accompanied by a large intensity change may indicate that symmetry and optical matrix elements have changed more strongly than the local restoring force.

Conversely, a strongly softened mode may indicate a genuine mechanical change even if its Raman intensity remains substantial.

**Frequency, intensity, and symmetry must be interpreted as separate observables before being combined into a structural conclusion.**

---

## 13. Research exercise: A stacking-dependent Raman experiment

Imagine that you have fabricated three five-layer MoS₂ samples.

Sample A is identified structurally as conventional 2H stacking.

Sample B is identified as 3R stacking.

Sample C is a small-angle twisted multilayer that has undergone partial atomic reconstruction.

You measure ultralow-frequency Raman spectra under identical conditions.

### Observation 1

Samples A and B exhibit similar breathing-mode frequencies, but the dominant shear-mode Raman peaks belong to different branches.

**Question:** Does this prove that the shear force constants are dramatically different?

**Answer:** No.

The dominant Raman branch depends on the optical matrix elements.

Different stacking symmetries can redistribute Raman intensity among shear modes without requiring comparably large differences in their frequencies.

A meaningful mechanical comparison requires identifying the corresponding vibrational branches and comparing their frequencies, not merely comparing the strongest peaks.

### Observation 2

Sample C exhibits additional low-frequency Raman features that are absent in Samples A and B.

**Question:** Can you immediately identify them as moiré-folded phonons?

**Answer:** No.

Possible explanations include zone folding, symmetry-induced activation, localized domain-wall vibrations, strain-related modes, and hybridization among existing branches.

A convincing zone-folding assignment requires identifying the parent phonon branch and the moiré reciprocal vectors responsible for the folding.

A domain-wall interpretation requires evidence that the vibrational eigenvectors are spatially concentrated near those boundaries.

### Observation 3

Spatial Raman mapping of Sample C reveals regions with different peak intensities but nearly identical peak frequencies.

**Question:** What physical interpretation should be considered first?

**Answer:** The local optical coupling may vary more strongly than the mechanical restoring forces.

Different local stacking symmetries or polarization-selection rules can change Raman intensity while leaving the mode frequencies nearly unchanged.

However, optical interference, thickness variations, and resonance effects should also be considered.

Independent structural mapping would help establish whether the intensity variations correlate with reconstructed domains.

### Observation 4

A first-principles calculation finds that one stacking configuration has a lower total energy than another, but the two have nearly identical shear frequencies.

**Question:** Is this inconsistent?

**Answer:** No.

The total-energy difference measures the relative stability of the two stacking configurations.

The shear frequency depends on the local curvature of the energy surface around each equilibrium configuration.

Two minima can have different depths but similar curvatures.

This is precisely why stacking energetics and interlayer phonon spectroscopy provide complementary information.

---

## 14. Two papers for today's briefing

### Paper 1 — Stacking-dependent interlayer phonons

**Van Baren et al., “Stacking-dependent interlayer phonons in 3R and 2H MoS₂.”**

*2D Materials* **6**, 025022 (2019).

[Read the paper — DOI: 10.1088/2053-1583/ab0196](https://doi.org/10.1088/2053-1583/ab0196)

[Open-access preprint](https://arxiv.org/abs/1901.11230)

**Why this paper is relevant**

This study directly addresses the relationship between stacking registry, interlayer force constants, and Raman selection rules.

The authors compare pure 2H and 3R MoS₂ multilayers using polarization-dependent ultralow-frequency Raman spectroscopy.

They show that the breathing-mode frequencies are consistently slightly higher in 2H structures, indicating a modest difference in interlayer mechanical coupling.

The more striking result is the reversal of which shear branch carries the strongest Raman intensity.

The paper explains this behavior using group theory, a linear-chain model, effective bond polarizability, and first-principles calculations.

For today's briefing, focus on how the authors separate the mechanical properties of the vibrational modes from their Raman activity.

**Research question:** How can the stacking sequence alter the Raman intensity of a shear branch without producing an equally large change in its frequency?

### Paper 2 — Atomic reconstruction in twisted TMD bilayers

**Weston et al., “Atomic reconstruction in twisted bilayers of transition metal dichalcogenides.”**

*Nature Nanotechnology* **15**, 592–597 (2020).

Published online: 25 May 2020.

[Read the paper — DOI: 10.1038/s41565-020-0682-9](https://doi.org/10.1038/s41565-020-0682-9)

[Open-access preprint](https://arxiv.org/abs/1911.12664)

**Why this paper is relevant**

This study demonstrates that the atomic structures of small-angle twisted bilayers cannot always be understood as rigidly rotated lattices.

Using atomic-resolution transmission electron microscopy, the authors reveal reconstructed domains and dislocation networks in twisted MoS₂ and WS₂ bilayers.

The results show that the domain patterns depend strongly on whether the layers are close to 2H or 3R alignment.

This provides direct experimental evidence for the competition between interlayer stacking energy and intralayer elasticity.

The paper is especially important for interpreting phonons in moiré systems because the relaxed structure determines the spatial distribution of local force constants.

When reading it, examine how the authors distinguish the geometrical moiré pattern from the reconstructed atomic configuration.

**Research question:** How would the phonon spectrum differ between a rigid twisted bilayer and a reconstructed bilayer with the same nominal twist angle?

---

## 15. What you should retain

Today's central result is that stacking registry controls several distinct but interconnected properties of a multilayer crystal.

The interlayer energy landscape determines which atomic arrangements are energetically favorable.

Its local curvature determines the restoring forces associated with shear and breathing vibrations.

The symmetry of the stacking arrangement determines which vibrational modes are allowed to couple to Raman and infrared fields.

The optical matrix elements determine how strongly those allowed modes appear in a measured spectrum.

Twisting makes the stacking registry spatially dependent.

At sufficiently small angles, the competition between stacking energy and intralayer elasticity can drive atomic reconstruction into domains and domain walls.

These reconstructed structures create spatial variations in mechanical stiffness, symmetry, and potentially infrared dielectric response.

The resulting vibrational spectrum may contain contributions from conventional interlayer modes, folded phonons, hybridized branches, and vibrations associated with reconstructed structural features.

**The most important principle is that stacking energy, phonon frequency, and Raman intensity are different physical quantities. They are related, but none uniquely determines the others.**

A convincing interpretation of twisted multilayer spectroscopy must distinguish all three.

---

## Next briefing — Thursday, 22 October 2026

### Morning Physics Briefing 08: Moiré Reciprocal Lattices — How Twist Creates New Phonon Wavevectors

Our next central question will be:

**How does a small relative rotation transform the reciprocal-space description of two atomic lattices, and why does that transformation matter for phonon spectroscopy?**

We will construct the moiré reciprocal lattice, distinguish atomic and moiré Brillouin zones, and examine how the reduced translational symmetry changes the labeling of phonon wavevectors.

We will then explain the difference between geometric zone folding and genuine dynamical hybridization.

The concrete examples will include twisted MoS₂ bilayers and lattice-mismatched MoS₂/WSe₂ heterostructures.

This will prepare us for the following briefing on moiré phonon folding, interlayer hybridization, and the interpretation of additional Raman peaks.
