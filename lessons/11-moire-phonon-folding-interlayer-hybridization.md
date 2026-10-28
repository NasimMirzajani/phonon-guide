---
layout: default
lesson_number: 11
title: "Moiré Phonon Folding and Interlayer Hybridization: When New Vibrational Modes Emerge"
short_title: "Moiré Phonon Folding and Hybridization"
section: "Week 2 — Multilayer and Twist Physics"
read_time: "9–10 min"
date: 2026-10-23
permalink: /lessons/11-moire-phonon-folding-interlayer-hybridization/
---

# Morning Physics Briefing 09
## Moiré Phonon Folding and Interlayer Hybridization: When New Vibrational Modes Emerge

**Friday, 23 October 2026 | Week 2 — Multilayer and Twist Physics | Reading time: 9–10 minutes**

**Today's central question:** When two phonon branches are brought to the same wavevector by a moiré superlattice, what determines whether they remain independent, hybridize, or develop spatially structured vibrational eigenmodes?

Yesterday, we established how twist generates a moiré reciprocal lattice and how the corresponding reduction of the Brillouin zone allows finite-wavevector phonons to appear near the moiré-zone center.

Today, we examine what happens when those folded phonon branches interact.

The central concept is **phonon hybridization**: the mixing of two or more vibrational eigenstates through a coupling in the lattice dynamical matrix.

In twisted van der Waals heterostructures, this coupling depends on the local stacking registry, interlayer force constants, and atomic reconstruction. It can redistribute vibrational motion between layers, change phonon frequencies, and produce eigenmodes with spatial structure on the moiré length scale.

These effects are particularly important for low-energy shear and breathing vibrations, whose restoring forces depend strongly on the interlayer interaction.

We will use twisted MoS₂ and MoSe₂/WSe₂ heterobilayers to understand the underlying physics.

---


![Original schematic: Moiré Phonon Folding and Interlayer Hybridization: When New Vibrational Modes Emerge]({{ '/assets/briefing11/folding-and-hybridization.svg' | relative_url }})

*Figure: Original conceptual illustration; not reproduced from a source paper.*

## 1. Begin with two independent phonon modes

Consider two isolated monolayers.

Each has a set of phonon eigenmodes obtained by diagonalizing its dynamical matrix.

For a particular wavevector, every mode has a frequency and an eigenvector describing the relative motion of the atoms.

Now bring the layers together.

The interlayer interaction introduces additional restoring forces.

An atomic displacement in one layer can exert a force on atoms in the other.

Consequently, the vibrations of the two layers become coupled.

This is already familiar from the interlayer shear and breathing modes of an ordinary bilayer.

For example, the breathing vibration involves the two layers moving in opposite out-of-plane directions.

The interlayer interaction provides the restoring force.

But a twisted bilayer introduces an additional complication.

The local stacking registry varies across the interface, so the interlayer force constants become spatially modulated.

This allows the interlayer interaction to couple vibrational patterns with different wavevectors in the original monolayer description.

The moiré reciprocal lattice determines which wavevector differences are compatible with that coupling.

---

## 2. How the moiré structure couples phonon wavevectors

Recall that the dynamical matrix contains the mass-weighted force constants of the crystal.

Its eigenvalues determine the squared phonon frequencies, while its eigenvectors describe the corresponding atomic displacements.

In a twisted bilayer, the interlayer force constants depend on the local stacking configuration.

We can describe their spatial modulation using a Fourier expansion:

<div class="equation">

\[
\boxed{
\delta D(\mathbf r)
=
\sum_{\mathbf G_{\mathrm m}}
\delta D_{\mathbf G_{\mathrm m}}
e^{i\mathbf G_{\mathrm m}\cdot\mathbf r}
}
\]

</div>

Here:

- \\(\delta D(\mathbf r)\\) is the spatially varying contribution to the dynamical matrix.
- \\(\mathbf r\\) is the in-plane position.
- \\(\mathbf G_{\mathrm m}\\) is a reciprocal lattice vector of the moiré superlattice.
- \\(\delta D_{\mathbf G_{\mathrm m}}\\) is the Fourier coefficient describing the strength and atomic-displacement structure of the modulation at that wavevector.

This expression assumes a periodic moiré description, as appropriate for a commensurate structure or a periodic continuum approximation.

### What does this mean physically?

Imagine a phonon whose displacement varies sinusoidally across the sample.

Now imagine that the restoring force acting on that displacement also varies periodically.

Multiplying the displacement pattern by the spatially varying force constant produces new spatial frequencies.

These frequencies differ from the original phonon wavevector by moiré reciprocal vectors.

Therefore, the spatial modulation can scatter a phonon from one wavevector to another.

This is analogous to the way a periodic optical grating scatters electromagnetic waves between diffraction orders.

The difference is that the periodic modulation now acts on the atomic displacement field through the force constants.

**The Fourier components of the interlayer force constants determine which phonon wavevectors can couple and how strongly.**

This is the microscopic origin of moiré-induced phonon mixing.

---

## 3. When does coupling produce strong hybridization?

Suppose two phonon states are folded to the same moiré wavevector.

One originates from a phonon branch at wavevector \\(\mathbf q\\).

The other originates from a branch at \\(\mathbf q+\mathbf G_{\mathrm m}\\).

The spatially modulated dynamical matrix may couple them.

If we retain only these two states, the vibrational problem can be represented by

<div class="equation">

\[
\boxed{
\begin{pmatrix}
\omega_1^2 & \Lambda \\
\Lambda^* & \omega_2^2
\end{pmatrix}
\begin{pmatrix}
c_1\\
c_2
\end{pmatrix}
=
\Omega^2
\begin{pmatrix}
c_1\\
c_2
\end{pmatrix}
}
\]

</div>

Here:

- \\(\omega_1\\) and \\(\omega_2\\) are the uncoupled phonon angular frequencies.
- \\(\Lambda\\) is the coupling matrix element, with units of angular frequency squared.
- \\(c_1\\) and \\(c_2\\) describe the contributions of the original phonon states to a hybridized eigenmode.
- \\(\Omega\\) is the angular frequency of the resulting eigenmode.
- The complex conjugate \\(\Lambda^*\\) ensures that the dynamical matrix is Hermitian.

This is a standard coupled-mode problem.

Its physical consequences are particularly important.

### Weak coupling

When the difference between the squared uncoupled frequencies is much larger than the coupling magnitude, each eigenmode retains predominantly its original character.

The frequency shifts are relatively small.

### Strong mixing

When the uncoupled frequencies approach one another, the eigenmodes can become substantial mixtures of the two original vibrations.

Near exact degeneracy, both states contribute equally in this ideal two-mode model, provided the coupling is nonzero.

The eigenfrequencies separate.

If the uncoupled frequencies would cross as a parameter changes, the coupling produces an **avoided crossing**.

This is one of the clearest signatures of hybridization.

However, the coupling matrix element must be nonzero.

Two modes can have identical frequencies and remain independent if symmetry forbids their interaction.

---

## 4. Why symmetry determines which modes can hybridize

Consider two phonon branches with similar frequencies.

One involves predominantly out-of-plane atomic displacement.

The other involves predominantly in-plane displacement.

Can they hybridize?

The answer depends on the symmetry of the combined structure.

If a crystal symmetry distinguishes the two displacement patterns, the corresponding off-diagonal coupling matrix element may vanish.

For example, a mirror symmetry can prevent mixing between modes that transform with opposite parity under that mirror operation.

If the symmetry is broken, the coupling may become allowed.

Twisting and atomic reconstruction can lower the symmetry of a multilayer.

This can activate coupling terms that vanish in a higher-symmetry reference structure.

### A subtle point about shear and breathing modes

In a high-symmetry bilayer, shear and breathing vibrations often belong to different symmetry representations.

Their mixing may therefore be forbidden.

In a lower-symmetry local stacking configuration, coupling between lateral and vertical displacements can become allowed.

This provides a mechanism for shear-like and breathing-like motion to mix.

However, symmetry permission alone does not guarantee substantial hybridization.

The modes must also have sufficient frequency proximity and a significant coupling matrix element.

**Strong hybridization requires compatible symmetry, appreciable coupling, and sufficiently close uncoupled frequencies.**

All three conditions matter.

---

## 5. What changes in a twisted MoS₂ bilayer?

Now consider two MoS₂ monolayers rotated relative to one another.

At a large twist angle, the interface samples many different stacking configurations over relatively short distances.

The effective interlayer shear restoring force can be strongly reduced compared with a well-aligned bilayer.

At smaller twist angles, the moiré wavelength increases.

The layers can relax toward favorable local stacking configurations.

Eventually, atomic reconstruction may produce extended stacking domains separated by domain walls.

These changes modify the vibrational problem in two related ways.

First, the local interlayer force constants change as the atomic structure relaxes.

Second, the spatial pattern of the force constants changes.

Consequently, both the frequencies and eigenvectors of the phonons can evolve strongly with twist angle.

This behavior was demonstrated experimentally and theoretically by Quan and colleagues in twisted bilayer MoS₂.

They found that phonon spectra evolve rapidly over a range of small twist angles, with the changes arising from strong coupling between vibrational modes and atomic reconstruction.

Their continuum model reproduced essential features of the experimental Raman spectra and connected the spectral changes to nanoscale lattice distortions. [Nature](https://www.nature.com/articles/s41563-021-00960-1)

### Why is this result significant?

The nominal twist angle determines the geometrical moiré periodicity.

But the actual phonon spectrum depends on the relaxed atomic structure.

Two theoretical calculations with the same twist angle can therefore produce different phonon spectra if one includes atomic reconstruction and the other assumes rigid layers.

This is especially important at small twist angles, where reconstruction becomes energetically favorable.

---

## 6. How can reconstruction change a phonon eigenvector?

Consider the interlayer breathing mode of an ordinary, uniformly stacked bilayer.

Its displacement pattern is straightforward.

The two layers move in opposite out-of-plane directions.

Within each layer, the displacement is approximately uniform for the zone-center rigid-layer breathing mode.

Now consider a reconstructed twisted bilayer.

Different regions have different local stacking configurations and interlayer stiffnesses.

A collective breathing-like vibration may no longer have uniform amplitude across the moiré unit cell.

Some regions may move more strongly than others.

The displacement may also acquire in-plane components.

The resulting eigenvector can become spatially structured on the moiré length scale.

### Extended versus spatially concentrated modes

Several possibilities exist.

**Extended moiré modes:** The displacement pattern extends throughout the moiré supercell, with an amplitude that varies periodically.

**Domain-concentrated modes:** The vibrational amplitude is largest within particular stacking domains.

**Domain-wall-concentrated modes:** The vibrational amplitude is strongest near the boundaries separating reconstructed domains.

These categories describe the spatial distribution of vibrational motion.

For an ideal periodic moiré crystal, the normal modes can still be classified as Bloch modes of the superlattice.

A mode with amplitude concentrated near periodically repeated domain walls is therefore not necessarily localized to one isolated wall.

It may form an extended Bloch state whose displacement is concentrated within the domain-wall network.

This distinction matters when interpreting calculations and spatially resolved measurements.

---

## 7. A new class of low-energy vibrations: Collective stacking motion

There is another consequence of allowing the layers to relax.

The reconstructed stacking pattern itself can undergo collective motion.

Imagine a boundary separating two favorable stacking domains.

If the boundary shifts slightly, the relative areas occupied by the domains change.

Such motion can involve collective lateral displacements of atoms across many unit cells.

These excitations are related to fluctuations of the relative stacking-displacement field.

They are often discussed in connection with **phasons** and stacking-soliton vibrations.

### Why can these modes be soft?

The restoring force depends on the energy required to shift the stacking pattern.

In an ideal incommensurate continuum system, uniform translations of the moiré pattern may have very little or no restoring force.

This can produce very low-energy collective modes.

Real samples introduce additional effects.

Atomic-scale commensurability, defects, strain, substrate interactions, and boundaries can pin the stacking pattern.

Pinning can give these collective modes a finite frequency.

### How do they differ from ordinary shear modes?

A conventional bilayer shear mode describes approximately rigid relative translation of the two layers.

A moiré collective mode can involve a spatially varying displacement field.

Different regions of the moiré cell may move in different directions or with different amplitudes.

The displacement can be concentrated near domain walls.

Thus, the characteristic motion may involve deformation or translation of the reconstructed stacking pattern.

This creates additional low-energy degrees of freedom beyond those captured by a simple two-mass model of a uniformly stacked bilayer.

---

## 8. A concrete heterobilayer example: MoSe₂/WSe₂

Consider a heterobilayer formed from monolayer MoSe₂ and monolayer WSe₂.

The two materials have similar crystal structures but different atomic masses and interatomic force constants.

Their phonon dispersions therefore differ.

When the layers are combined, the interlayer interaction couples their vibrations.

The lattice mismatch and relative twist create a moiré modulation of the local stacking registry.

This introduces additional spatial structure into the coupling.

### What happens to the low-energy phonons?

The system supports collective interlayer vibrations, including shear-like and breathing-like motion.

Because the layers have different masses, the displacement amplitudes need not be equal.

The relative motion is determined by the mass distribution and interlayer force constants.

As the twist angle changes, the local stacking environment and the moiré modulation change.

The low-energy eigenmodes can therefore evolve in frequency and spatial structure.

Lu and colleagues developed a continuum approach for calculating low-energy phonons in twisted van der Waals bilayers.

They applied it to bilayer graphene, bilayer MoS₂, and MoSe₂/WSe₂ heterobilayers.

Their calculations showed that decreasing twist angle can reorder low-energy phonon frequencies and produce displacement patterns with pronounced moiré-scale spatial structure. [APS Journals](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.106.144305)

### Why is the heterobilayer especially interesting?

In a homobilayer, the constituent layers have identical isolated-layer phonon dispersions.

In a heterobilayer, the dispersions differ.

This provides additional opportunities for branches belonging predominantly to different layers to approach one another in frequency.

When the moiré reciprocal lattice connects their wavevectors, interlayer coupling can produce mixed vibrational states.

The resulting modes may contain different proportions of motion from the two materials.

Their character can change as twist angle, strain, or interlayer separation is varied.

This creates a route to engineering the spatial and layer-resolved character of lattice vibrations.

---

## 9. How should we interpret an avoided crossing?

Suppose a calculation predicts two phonon branches that approach each other as the twist angle changes.

At a particular angle, the frequencies become close.

Instead of crossing, the branches repel.

This is consistent with hybridization.

But the most convincing evidence comes from examining the eigenvectors.

Imagine labeling the original modes A and B.

Before the avoided crossing, the lower-frequency branch is predominantly A-like.

The upper-frequency branch is predominantly B-like.

As the branches approach, their eigenvectors become mixtures of A and B.

After passing through the avoided crossing, the lower-frequency branch becomes predominantly B-like, while the upper-frequency branch becomes predominantly A-like.

**The exchange of mode character is a central signature of hybridization.**

The frequency repulsion and eigenvector mixing are two manifestations of the same coupling.

### What about experimental Raman spectra?

An avoided crossing may be accompanied by a redistribution of Raman intensity.

If one parent mode has a strong Raman tensor and the other is weak, their hybridization can transfer Raman spectral weight between the branches.

However, Raman intensity depends on the optical matrix elements.

It can also change because of electronic resonance effects or symmetry changes.

Therefore, a convincing experimental assignment should combine frequency evolution with mode identification and, where possible, polarization-dependent measurements.

---

## 10. How does this appear in Raman spectroscopy?

Consider a twisted MoS₂ bilayer with several low-frequency Raman peaks.

A new peak may originate from several different physical mechanisms.

| Mechanism | Physical origin | Expected evidence |
|---|---|---|
| Moiré zone folding | Finite-wavevector phonon becomes equivalent to the moiré-zone center | Twist-dependent frequency following a parent phonon dispersion |
| Interlayer hybridization | Coupling mixes two vibrational eigenstates | Frequency repulsion and exchange of eigenvector character |
| Atomic reconstruction | Relaxation modifies local force constants and displacement patterns | Strong small-angle dependence and agreement with relaxed-structure calculations |
| Symmetry-induced Raman activation | Structural symmetry permits an additional Raman tensor component | Polarization dependence consistent with the relevant symmetry |
| Domain-wall vibration | Collective motion concentrated near stacking boundaries | Calculated displacement amplitude concentrated near domain walls |

These mechanisms can coexist.

For example, a folded phonon may hybridize with another branch and acquire Raman intensity because the mixed eigenvector has a nonzero optical matrix element.

Reconstruction can modify all three effects.

This is why assigning every additional Raman peak to zone folding is insufficient.

### Why polarization-resolved Raman is valuable

Different vibrational symmetries produce different Raman tensors.

Changing the incident and detected polarization can therefore alter the relative intensities of different modes.

A calculation by Klein, Liang, and Meunier in 2024 illustrates this point.

They investigated low-frequency Raman-active vibrations in twisted bilayer MoS₂ using a force-field model and a parameterized bond-polarizability approach.

Their results showed that atomic relaxation and soliton-network formation generate additional vibrational modes, with some appearing in different Raman polarization configurations. [PubMed](https://pubmed.ncbi.nlm.nih.gov/38788746/)

This highlights the value of combining vibrational eigenvector calculations with experimentally accessible polarization selection rules.

---

## 11. Why phonon minibands can become narrow

The moiré superlattice introduces a long spatial length scale.

Consequently, the corresponding Brillouin zone is small.

A phonon branch represented within this reduced zone spans a relatively narrow range of wavevectors.

If the underlying dispersion is weak over that range, the corresponding miniband may have a small bandwidth.

Interlayer coupling can further reshape the minibands.

Under suitable conditions, some branches may become particularly flat.

### What is the physical significance of a flat phonon band?

The group velocity of a phonon is determined by the slope of its dispersion.

A flat band has a small group velocity.

This can affect how vibrational energy propagates through the structure.

A narrow phonon band can also produce a large vibrational density of states over a restricted frequency interval.

However, flat dispersion and real-space localization are distinct properties.

A narrow band can arise from weak coupling between spatially concentrated vibrational states.

It can also arise from other features of the dynamical matrix.

To establish real-space localization, we must examine the displacement eigenvectors.

To understand energy transport, we must additionally consider phonon lifetimes and scattering.

**A flat phonon miniband does not automatically imply a long-lived or strongly localized vibration.**

---

## 12. Connection to interface phonons and phonon polaritons

We can now connect the lattice-dynamical picture to the electromagnetic response.

A polar optical phonon carries an oscillating electric polarization.

Its coupling to the electromagnetic field depends on the mode-effective charge, frequency, and displacement pattern.

When two polar vibrational modes hybridize, their oscillator strengths can be redistributed.

A mode that was weakly infrared-active may acquire additional infrared oscillator strength through mixing with another mode.

Conversely, interference between contributions to the polarization can suppress the net dipole moment of a hybridized vibration.

This affects the dielectric response.

### What changes in a heterostructure?

An interface can support vibrations whose displacement patterns differ from those of either isolated material.

If these modes possess an oscillating dipole moment, they can contribute to the infrared response.

They may also couple to electromagnetic fields to form interface-related polaritonic excitations.

However, two distinct calculations are required.

The phonon dynamical matrix determines the vibrational eigenfrequencies and atomic displacement patterns.

The electromagnetic problem determines how the frequency-dependent dielectric response supports propagating or confined polaritonic modes.

A localized phonon eigenvector does not guarantee a localized polariton.

Similarly, an electromagnetic field concentrated near an interface does not necessarily indicate a new interface-localized atomic vibration.

### Why this matters for twisted hBN

In hBN, infrared-active optical phonons contribute strongly to the anisotropic dielectric response.

The material supports hyperbolic phonon polaritons within its Reststrahlen bands.

If stacking or twist modifies the vibrational eigenmodes and their infrared oscillator strengths, the dielectric response may change.

Those changes can influence polariton dispersion and confinement.

The magnitude of the effect depends on the microscopic coupling and the relevant electromagnetic boundary conditions.

This provides an important bridge between moiré phonon physics and the polaritonic phenomena we will examine in Week 3.

---

## 13. Today's principal interpretive pitfall

### Misconception: An additional Raman peak proves that a new vibrational mode has been created by interlayer hybridization.

An additional Raman peak establishes that the measured scattering spectrum contains an additional resolvable contribution.

Its microscopic origin requires further analysis.

A pre-existing finite-wavevector phonon may become Raman-accessible through moiré folding.

A symmetry change may activate a previously weak or forbidden transition.

Two existing phonon branches may hybridize and redistribute their Raman intensities.

Atomic reconstruction may modify the vibrational eigenvectors or introduce additional collective degrees of freedom.

These mechanisms have different physical implications.

A convincing hybridization assignment should identify the interacting parent modes, demonstrate a symmetry-allowed coupling, and establish changes in eigenvector character.

An avoided crossing provides strong supporting evidence when the relevant branches can be tracked.

A new peak alone is insufficient.

---

## 14. Research exercise: Three Raman observations

Imagine measuring a series of twisted MoS₂ bilayers with progressively smaller twist angles.

### Observation A

An additional Raman peak changes frequency smoothly with twist angle.

Its frequency agrees with the monolayer phonon dispersion evaluated at a wavevector corresponding to a moiré reciprocal vector.

**Question:** What is the leading interpretation?

**Answer:** Moiré-induced zone folding.

The twist-dependent moiré reciprocal lattice selects different finite-wavevector phonons.

Agreement with the parent monolayer dispersion supports this assignment.

Further analysis of the Raman matrix element is needed to explain the observed intensity.

### Observation B

Two peaks approach one another as twist angle changes, exhibit a minimum frequency separation, and exchange their polarization-dependent Raman intensities.

**Question:** What additional mechanism should be considered?

**Answer:** Phonon hybridization.

The frequency repulsion is consistent with coupling between the modes.

The redistribution of polarization-dependent intensity may reflect changes in their eigenvector character.

A coupled-mode calculation and analysis of the Raman tensors would strengthen the interpretation.

### Observation C

Below a small twist angle, several new low-frequency features emerge abruptly.

A rigid-lattice calculation fails to reproduce them, while a relaxed-structure calculation predicts strong domain formation and spatially structured displacement eigenvectors.

**Question:** What is the likely role of reconstruction?

**Answer:** Atomic reconstruction has substantially modified the dynamical matrix.

The formation of stacking domains and domain walls changes the spatial distribution of interlayer force constants.

This can shift existing modes, produce additional collective vibrations, and redistribute their optical activity.

The comparison between rigid and relaxed calculations provides evidence that structural relaxation is essential to the observed spectrum.

---

## 15. Two papers for today's briefing

### Paper 1 — Experimental phonon renormalization in reconstructed moiré structures

**Quan et al., “Phonon renormalization in reconstructed MoS₂ moiré superlattices.”**

*Nature Materials* **20**, 1100–1105 (2021).

[Read the paper — DOI: 10.1038/s41563-021-00960-1](https://www.nature.com/articles/s41563-021-00960-1)

[Open-access preprint](https://arxiv.org/abs/2009.10650)

**Why this paper matters**

This study combines Raman spectroscopy with a continuum phonon model to investigate the evolution of vibrational modes in twisted bilayer MoS₂.

The authors demonstrate that small-angle phonon spectra are strongly affected by atomic reconstruction and coupling between vibrational modes.

Their model captures the essential experimental trends without requiring a full first-principles calculation of every atom in a very large moiré supercell.

For today's briefing, focus on the calculated phonon eigenvectors and their evolution with twist angle.

Examine how the authors distinguish changes in the relaxed atomic structure from changes in vibrational coupling.

**Research question:** Which spectral features can be explained by geometrical folding, and which require reconstruction and dynamical mode coupling?

### Paper 2 — Low-energy phonons in twisted homo- and heterobilayers

**Lu, Zhu, Angeli, Larson, and Kaxiras, “Low-energy moiré phonons in twisted bilayer van der Waals heterostructures.”**

*Physical Review B* **106**, 144305 (2022).

[Read the paper — DOI: 10.1103/PhysRevB.106.144305](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.106.144305)

[Open-access preprint](https://arxiv.org/abs/2207.04965)

**Why this paper matters**

The authors develop a configuration-space continuum approach for calculating low-energy phonons in twisted bilayers.

Their method uses interatomic force constants obtained from first-principles calculations of different local stacking configurations.

They apply the framework to bilayer graphene, MoS₂, and MoSe₂/WSe₂.

The results demonstrate how twist angle modifies interlayer shear and breathing vibrations, changes the ordering of low-energy modes, and produces moiré-scale structure in the vibrational eigenvectors.

This paper is particularly useful for connecting the local stacking-dependent force constants discussed earlier this week with the collective phonon spectrum of an extended moiré structure.

**Research question:** How does the spatial dependence of the interlayer force constants determine whether a low-energy vibration resembles a conventional rigid-layer mode or a collective moiré displacement pattern?

---

## 16. What you should retain

The moiré reciprocal lattice determines which phonon wavevectors can be connected by the spatial modulation of the interlayer force constants.

When two phonon states are brought into the same reduced Brillouin zone, their interaction depends on the off-diagonal elements of the dynamical matrix.

Modes with compatible symmetry and sufficiently close frequencies can hybridize.

Hybridization changes their eigenfrequencies and redistributes their vibrational character.

Atomic reconstruction modifies the local force constants and the spatial pattern of interlayer coupling.

This can produce phonon eigenvectors with pronounced moiré-scale structure, including displacement concentrated within stacking domains or near domain walls.

The resulting vibrational spectrum may contain folded phonons, hybridized branches, reconstruction-induced frequency shifts, and collective stacking-related excitations.

Raman spectroscopy probes these modes through their optical matrix elements.

Polarization-dependent measurements and comparisons with calculated eigenvectors are particularly valuable for distinguishing the underlying mechanisms.

For polar materials, changes in phonon eigenvectors and oscillator strengths can also modify the infrared dielectric response, providing a route from moiré lattice dynamics to phonon-polariton engineering.

**The central principle is that the moiré geometry determines which phonon states can interact, while symmetry and the microscopic interlayer force constants determine the strength and consequences of that interaction.**

---

## Weekend application — Saturday, 24 October 2026

### From Moiré Phonons to Experimental Spectra: Designing a Raman and Infrared Study of a Twisted Heterostructure

Tomorrow we will apply the concepts from Week 2 to an experimental problem.

Suppose you have a twisted MoS₂/WSe₂ heterobilayer with an uncertain twist angle and possible atomic reconstruction.

You can measure polarization-dependent Raman spectra, infrared response, and spatially resolved optical signals.

**How would you distinguish changes in stacking registry, interlayer mechanical coupling, moiré folding, and phonon hybridization?**

We will develop a measurement and interpretation strategy, identifying which observables constrain each physical mechanism and which ambiguities require complementary measurements.

This will consolidate the multilayer and twist physics of Week 2 before we begin Week 3: dielectric anisotropy, Reststrahlen bands, and hyperbolic phonon polaritons.
