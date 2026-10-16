# Morning Physics Briefing 04
## Crystal Symmetry and Phonon Selection Rules: Why Stacking Changes What We Can Observe

**Friday, 16 October 2026 · Week 1 — Solid-State Foundations · Reading time: 9–10 minutes**

**Today's central question:** Two crystals can have nearly identical phonon frequencies but strikingly different Raman and infrared spectra. How can the arrangement of atoms determine whether a vibration is optically visible?

This is particularly important for twisted and multilayer van der Waals heterostructures. Changing the stacking registry or twist angle does not merely modify the interlayer force constants. It can change the crystal's symmetry, which determines which vibrational modes couple to light.

Today we will establish the symmetry framework needed to interpret those effects.

---

### 1. Why symmetry matters for phonons

In Briefing 03, we distinguished acoustic and optical phonons by their displacement patterns and their behavior near the Brillouin-zone center.

However, knowing the frequency and displacement pattern of a phonon is not sufficient to predict whether it will appear in a Raman or infrared experiment.

Consider two optical phonons with nearly identical frequencies.

One might produce a strong Raman peak, while the other is completely absent.

This does not necessarily mean that the second phonon does not exist.

Instead, the two modes may transform differently under the symmetry operations of the crystal.

**The essential principle is that a phonon can couple to a particular optical probe only if the corresponding interaction is allowed by symmetry.**

This is the origin of phonon selection rules.

The consequences become especially interesting in layered materials because stacking and twisting can change the symmetry without changing the chemical composition.

### 2. Crystal symmetry and the point group

A crystal possesses a collection of symmetry operations that leave its atomic arrangement unchanged.

These can include rotations, reflections, inversion, and translations.

For optical phonons near the Brillouin-zone center, the relevant classification is usually obtained from the crystal's point group.

The point group describes the rotational, reflection, and inversion symmetries of the crystal.

Each phonon normal mode transforms according to an irreducible representation of that group.

You will encounter labels such as A₁g, E₂g, E₁u, and A₂u.

These labels are not arbitrary names for different vibrations. They encode how the displacement pattern transforms under symmetry operations.

For example, an A-type mode is nondegenerate, whereas an E-type mode is generally twofold degenerate in the crystal point groups relevant here.

The subscripts g and u refer to inversion parity.

A gerade (g) mode is unchanged under inversion, while an ungerade (u) mode changes sign.

This distinction becomes central when determining Raman and infrared activity.

### 3. Inversion symmetry and the Raman–IR mutual exclusion rule

Consider a crystal with inversion symmetry.

Under inversion, every spatial coordinate is transformed into its negative.

The electric dipole moment is a polar vector and therefore changes sign under inversion.

The electric polarizability, however, is a second-rank tensor that remains unchanged.

This leads to a fundamental result for zone-center phonons in centrosymmetric crystals:

**A phonon that is Raman-active cannot simultaneously be electric-dipole infrared-active.**

This is known as the mutual exclusion rule.

The physical reason is that the two optical processes probe different properties of the vibrating crystal.

Raman scattering measures how a phonon modulates the electronic polarizability.

Infrared absorption measures how a phonon produces an oscillating electric dipole.

In a centrosymmetric crystal, these quantities have opposite inversion parity.

Consequently, a gerade phonon can be Raman-active, while an ungerade phonon can be infrared-active.

The important qualification is that symmetry determines whether coupling is permitted, not whether it must be strong.

Some symmetry-allowed modes can have extremely weak oscillator strengths.

The mutual exclusion rule also assumes an ideal centrosymmetric structure and the usual first-order Raman and electric-dipole infrared processes. Higher-order optical processes, disorder, and symmetry breaking can modify what is experimentally observed.

### 4. The Raman selection rule

The intensity of a first-order Raman mode depends on the Raman tensor associated with that phonon.

<div class="equation">
\[
I_\nu^{\mathrm{Raman}}
\propto
\left|
\mathbf e_{\mathrm{out}}^{\mathsf T}
\mathbf R_\nu
\mathbf e_{\mathrm{in}}
\right|^2,
\qquad
\mathbf R_\nu =
\frac{\partial\boldsymbol{\alpha}}{\partial Q_\nu}
\]
</div>

Here:

- \\(I_\nu^{\mathrm{Raman}}\\) is the Raman intensity of phonon mode ν.
- \\(\mathbf e_{\mathrm{in}}\\) and \\(\mathbf e_{\mathrm{out}}\\) are the incident and scattered light polarization vectors.
- \\(\mathbf R_\nu\\) is the Raman tensor of mode ν.
- \\(\boldsymbol{\alpha}\\) is the electronic polarizability tensor.
- \\(Q_\nu\\) is the normal-mode coordinate.

The equation expresses a simple physical idea.

A phonon produces Raman scattering when its displacement changes the electronic polarizability in a way that couples the incident and scattered optical polarizations.

If the corresponding Raman tensor is zero by symmetry, the mode is forbidden in first-order Raman scattering.

Even when the tensor is nonzero, a particular polarization configuration can suppress the signal.

For example, a mode may be visible with parallel incident and scattered polarizations but disappear in a crossed-polarization measurement.

This is why polarization-resolved Raman spectroscopy can identify phonon symmetries rather than merely measure phonon frequencies.

In multilayer materials, this technique becomes particularly useful for distinguishing interlayer shear and breathing modes.

### 5. The infrared selection rule

Infrared spectroscopy probes a different property.

A phonon is electric-dipole infrared-active when its motion changes the macroscopic electric polarization.

Its oscillator strength is related to

<div class="equation">
\[
f_\nu^{\mathrm{IR}}
\propto
\left|
\mathbf e_{\mathrm{IR}}\cdot
\frac{\partial\mathbf P}{\partial Q_\nu}
\right|^2
\]
</div>

Here, \\(f_\nu^{\mathrm{IR}}\\) denotes the mode's infrared oscillator strength up to normalization factors, \\(\mathbf P\\) is the macroscopic polarization, and \\(\mathbf e_{\mathrm{IR}}\\) specifies the electric-field polarization of the incident infrared light.

The normal coordinate \\(Q_\nu\\) describes the phonon displacement.

The crucial quantity is the change in polarization produced by that displacement.

A vibration can therefore be infrared-inactive even when atoms move significantly.

What matters is whether the collective displacement generates an oscillating dipole moment.

In polar crystals such as hexagonal boron nitride, infrared-active optical phonons can interact strongly with electromagnetic fields.

This interaction ultimately produces phonon polaritons.

We will develop that connection when we reach dielectric response, LO–TO splitting, and Reststrahlen bands.

For now, the important distinction is:

**Raman activity probes polarizability modulation; infrared activity probes dipole modulation.**

---

### 6. Concrete example: Monolayer and bilayer MoS₂

Consider a monolayer of molybdenum disulfide, MoS₂.

Its structure consists of a molybdenum atomic plane between two sulfur planes.

The ideal monolayer belongs to the D₃h point group.

Importantly, it does not possess inversion symmetry.

Now stack two identical monolayers in the conventional 2H configuration.

The second layer is rotated by 180° relative to the first, producing a centrosymmetric bilayer with point group D₃d.

This is a remarkable structural transformation.

The chemical composition has not changed.

The individual monolayers have not changed their internal bonding.

Yet the bilayer now possesses an inversion center that was absent in either isolated monolayer.

As a result, the phonon selection rules change.

The bilayer vibrational modes can be classified by inversion parity, and the Raman–IR mutual exclusion rule applies to the ideal structure.

The bilayer also possesses additional low-frequency vibrations that do not exist in the isolated monolayer.

These are the interlayer shear and breathing modes.

In the shear mode, the two layers move laterally relative to one another.

In the breathing mode, the layers move toward and away from each other.

For ideal 2H bilayer MoS₂, the interlayer shear mode transforms as E_g, while the breathing mode transforms as A₁g.

Both are Raman-active.

Their frequencies are governed primarily by the weak interlayer restoring forces, making them useful probes of interlayer mechanical coupling.

Zhang and colleagues demonstrated that the frequencies and Raman selection rules of these modes evolve systematically with the number of layers. Their analysis combined polarization measurements, symmetry classification, and a simple linear-chain description. [Source: Zhang et al.](https://doi.org/10.1103/PhysRevB.87.115413)

### 7. What changes when we change the stacking?

Now consider a different arrangement of the same material.

Instead of conventional 2H stacking, suppose the layers adopt the rhombohedral 3R stacking configuration.

In 3R stacking, adjacent layers retain the same crystallographic orientation but are laterally displaced.

The resulting ideal bilayer lacks inversion symmetry.

Its point group is C₃v.

The change from 2H to 3R stacking therefore changes the symmetry classification of the vibrational modes.

This has important consequences.

First, the mutual exclusion rule no longer applies in its centrosymmetric form.

A phonon can, in principle, be both Raman-active and infrared-active.

Second, the Raman tensors and the way the polarizability changes during interlayer motion can differ between the two stacking configurations.

Third, the interlayer force constants can change because the atomic registry modifies the local interlayer interaction potential.

The phonon frequencies and Raman intensities therefore carry complementary information.

The frequency tells us about the restoring force associated with a vibration.

The Raman intensity tells us about how that vibration modulates the optical polarizability.

These are related but fundamentally different quantities.

This distinction is demonstrated particularly clearly by experiments on 2H and 3R MoS₂.

Van Baren and colleagues investigated the shear and breathing modes in multilayer crystals with the two stacking sequences.

They found that the strongest shear-mode Raman signal belongs to the highest-frequency shear branch in 2H multilayers but to the lowest-frequency branch in 3R multilayers.

They also found systematically higher breathing-mode frequencies in 2H than in 3R MoS₂, indicating somewhat stronger interlayer lattice coupling in the former.

The striking difference in shear-mode intensities cannot be explained by frequencies alone.

It requires considering how the bond polarizability contributions from different layers combine during the vibration. [Source: Van Baren et al.](https://doi.org/10.1088/2053-1583/ab0196)

**This is an important result for twisted heterostructures: phonon intensity can be a fingerprint of stacking registry, not merely phonon frequency.**

---

### 8. From stacking symmetry to twisted bilayers

Now imagine rotating one layer relative to another by a small angle.

In a perfectly aligned bilayer, the atomic registry can be uniform throughout the sample.

With a finite twist angle, the local registry varies spatially.

Different regions of the interface resemble different high-symmetry stacking configurations.

At sufficiently small twist angles, atomic relaxation may further reorganize these regions into reconstructed domains separated by domain walls.

The structure can therefore contain spatially varying local environments, each with different interlayer forces and local symmetry.

This has several consequences for phonons.

First, the local restoring forces can vary across the moiré superlattice.

Second, modes that would be distinct in a uniform high-symmetry structure can mix when the symmetry is reduced.

Third, a commensurate moiré superlattice introduces a new, smaller Brillouin zone.

Phonons that originally occupied finite wavevectors in the constituent-layer Brillouin zones can be folded toward the moiré-zone center.

Such folded modes may acquire optical visibility, provided that the relevant coupling and selection rules allow it.

However, folding a phonon to the moiré-zone center does not automatically guarantee a measurable Raman peak.

Its intensity still depends on the symmetry of the folded eigenmode, the associated Raman tensor, and the experimental excitation conditions.

For incommensurate structures, the description is more subtle because there may be no exact finite moiré unit cell.

In that situation, approximate supercell descriptions and spatially varying interlayer coupling are often more useful than a strict zone-folding picture.

This distinction will become important when we study moiré phonons in Week 2.

### 9. Connection to phonon polaritons

Why does this matter for phonon polaritons?

A phonon polariton is a hybrid excitation involving an electromagnetic field and a lattice vibration.

The electromagnetic field couples most directly to phonons that generate a polarization response.

Consequently, infrared oscillator strengths and polarization selection rules determine which optical phonons contribute to the dielectric response.

The crystal symmetry also constrains the dielectric tensor.

In a uniaxial material such as hBN, the in-plane and out-of-plane dielectric responses are different.

Different infrared-active phonons contribute to these tensor components.

This produces frequency intervals in which the real parts of the in-plane and out-of-plane dielectric functions can have opposite signs.

Such intervals support hyperbolic phonon polaritons.

When two anisotropic polar crystals are stacked and rotated relative to one another, their optical axes and electromagnetic boundary conditions become essential.

The resulting polaritonic modes can depend strongly on relative orientation.

However, there is an important distinction between twisting an intrinsically in-plane anisotropic material and twisting a uniaxial crystal with rotationally equivalent in-plane directions.

For example, rotating two ideal hBN layers about their common out-of-plane axis does not, by itself, rotate distinct in-plane principal dielectric axes in the way that twisting two α-MoO₃ layers does.

Twisted hBN can nevertheless exhibit stacking- and moiré-dependent phononic and polaritonic effects through changes in interlayer coupling, local symmetry, and structural relaxation.

The broader lesson is that symmetry influences polaritons through both the available phonon excitations and the electromagnetic response of the material.

### 10. An important interpretive pitfall

Suppose you measure two bilayer samples and find that a particular Raman peak is much stronger in one sample than in the other.

It is tempting to conclude that the stronger peak indicates stronger interlayer coupling.

That conclusion is not generally justified.

Raman intensity depends on several factors, including the Raman tensor, excitation energy, optical interference, polarization geometry, and possible excitonic resonance enhancement.

A change in intensity may therefore reflect a change in optical selection rules rather than a change in the mechanical restoring force.

Conversely, a frequency shift may indicate altered force constants, but strain, doping, temperature, and dielectric screening can also influence phonon frequencies.

A reliable interpretation should distinguish three questions:

**Is the mode symmetry-allowed?** This is primarily a group-theoretical question.

**How strongly does it couple to the optical probe?** This requires evaluating the Raman tensor or infrared oscillator strength.

**What determines its frequency?** This requires understanding the dynamical matrix and the relevant force constants.

These questions are connected, but they are not interchangeable.

---

## 11. Three questions to test your understanding

**Question 1 — Why can a phonon be Raman-active but infrared-inactive in a centrosymmetric crystal?**

**Answer:** Raman scattering and infrared absorption couple to different physical quantities.

Raman scattering probes the derivative of the electronic polarizability tensor with respect to the phonon coordinate.

Infrared absorption probes the derivative of the macroscopic polarization.

In a centrosymmetric crystal, the polarizability tensor is even under inversion, while the polarization vector is odd.

A zone-center phonon therefore cannot satisfy both parity requirements simultaneously in the usual first-order Raman and electric-dipole infrared approximations.

This gives rise to the mutual exclusion rule.

**Question 2 — Two multilayer MoS₂ samples have similar shear-mode frequencies but different Raman intensities. Does this necessarily mean their interlayer force constants differ?**

**Answer:** No.

Similar frequencies can indicate similar restoring forces, while the difference in Raman intensity may arise from different stacking-dependent Raman tensors.

The atomic registry controls how the electronic polarizability changes during relative layer motion.

Different layers can contribute constructively or destructively to the total Raman response.

Consequently, two structures with comparable interlayer mechanical stiffness can exhibit very different Raman spectra.

This is one reason polarization-dependent low-frequency Raman spectroscopy is valuable for identifying stacking configurations.

**Question 3 — If twisting a bilayer reduces its symmetry, should every previously forbidden phonon become Raman-active?**

**Answer:** No.

Reducing symmetry can relax certain selection rules, but it does not guarantee that every phonon acquires a measurable Raman response.

The resulting mode must still have a nonzero Raman tensor in the actual structure and measurement geometry.

Its intensity can also be extremely weak.

Furthermore, a twisted bilayer may retain some symmetries, depending on its twist angle and atomic configuration.

A careful prediction requires determining the symmetry of the twisted structure and the transformation properties of its phonon eigenvectors.

---

## 12. Research papers for today

### Paper 1 — Foundational experimental study

**Zhang et al., “Raman spectroscopy of shear and layer breathing modes in multilayer MoS₂.”**

*Physical Review B* **87**, 115413 (2013).

[Read the paper — DOI: 10.1103/PhysRevB.87.115413](https://doi.org/10.1103/PhysRevB.87.115413)

**Why this paper is relevant**

This paper establishes how interlayer shear and breathing vibrations can be identified through low-frequency Raman spectroscopy.

The authors use polarization measurements and symmetry analysis to distinguish the modes and investigate their dependence on layer number.

They also demonstrate how a relatively simple mechanical model can explain the evolution of the phonon frequencies.

It provides an excellent foundation for understanding why interlayer phonons are sensitive probes of multilayer structure.

When reading it, pay particular attention to how the authors separate symmetry information from frequency information.

### Paper 2 — Direct connection to stacking registry

**Van Baren et al., “Stacking-dependent interlayer phonons in 3R and 2H MoS₂.”**

*2D Materials* **6**, 025022 (2019).

[Read the paper — DOI: 10.1088/2053-1583/ab0196](https://doi.org/10.1088/2053-1583/ab0196)

[Open-access preprint](https://arxiv.org/abs/1901.11230)

**Why this paper is relevant**

This study directly addresses one of the central problems in multilayer van der Waals physics: how changing the stacking registry affects interlayer vibrations.

By comparing 2H and 3R MoS₂, the authors show that shear-mode Raman intensities are highly sensitive to stacking configuration.

Their analysis combines group theory, an effective bond-polarizability model, and first-principles calculations.

The important result is that the observed Raman response depends not only on phonon eigenfrequencies but also on the symmetry and spatial distribution of the associated polarizability changes.

This is particularly relevant when interpreting phonon spectra from twisted bilayers, where different local stacking configurations may coexist within the same moiré superlattice.

---

## 13. What you should retain from today's briefing

The most important conceptual advance is that **a phonon spectrum contains two distinct types of information: the eigenfrequencies of the lattice and the optical selection rules governing how those eigenmodes are observed.**

The dynamical matrix determines the vibrational eigenfrequencies and eigenvectors.

Crystal symmetry constrains how those eigenvectors couple to light.

Stacking registry can affect both.

This distinction becomes essential in twisted and multilayer materials, where changes in local symmetry, interlayer coupling, and moiré periodicity can produce complex vibrational spectra.

When interpreting Raman or infrared data, always distinguish a phonon becoming physically modified from a phonon becoming optically visible.

### Next briefing — 05: Dielectric Response and the Connection Between Phonons and Electromagnetic Fields

We will move from lattice vibrations to the frequency-dependent dielectric response.

The central question will be:

**How does an oscillating ionic lattice produce a frequency-dependent dielectric function, and why can that function become negative near an optical phonon resonance?**

This will establish the electrodynamic foundation for understanding Reststrahlen bands, LO–TO splitting, and phonon polaritons in anisotropic layered materials.
