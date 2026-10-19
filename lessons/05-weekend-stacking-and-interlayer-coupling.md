---
layout: default
lesson_number: 5
title: "From Crystal Symmetry to Interlayer Coupling: Reading the Phonon Spectrum of a Twisted Bilayer"
short_title: "Stacking and Interlayer Coupling"
section: "Week 1 · Weekend applications"
read_time: "9–10 min"
permalink: /lessons/05-weekend-stacking-and-interlayer-coupling/
---

# Morning Physics Briefing — Weekend Research Application
## 
From Crystal Symmetry to Interlayer Coupling: Reading the Phonon Spectrum of a Twisted Bilayer

Saturday, 17 October 2026 | Week 1 — Consolidation and Application | Reading time: 9–10 minutes

**Today's central question:**

*You receive Raman spectra from three bilayer MoS*₂* samples with different stacking configurations. How much can you infer about their interlayer coupling, atomic registry, and symmetry from the phonon frequencies and intensities alone?*

This weekend, rather than introducing the next curriculum topic, we will connect the concepts developed in the first four briefings and apply them to a realistic research problem.

The objective is to develop a systematic way of interpreting phonon measurements in multilayer and twisted van der Waals structures.

## 1. Four concepts that must be considered together

Our first four briefings established four complementary descriptions of lattice vibrations.

**Reciprocal space** tells us which phonon wavevectors are involved in an experiment.

**Normal-mode analysis** tells us the frequencies and displacement patterns of the lattice vibrations.

**Acoustic and optical classifications** describe how different atomic degrees of freedom participate in collective motion.

**Crystal symmetry** determines which of these vibrations can couple to a particular experimental probe.

These descriptions answer different questions.

For example, a phonon may exist as a perfectly legitimate eigenmode of the dynamical matrix but be invisible in a particular Raman geometry.

Conversely, a previously weak Raman feature may become intense after changing the stacking configuration, even if the corresponding phonon frequency barely changes.

This distinction is fundamental in twisted multilayer systems.

Twisting changes the spatial relationship between neighboring layers. That modification can affect the interlayer force constants, the symmetry of the vibrational eigenvectors, and their coupling to light.

**The experimental spectrum is therefore not simply a map of phonon frequencies. It is a symmetry- and coupling-weighted representation of the available vibrational states.**

Understanding that distinction is essential before attempting to identify moiré phonons or twist-induced mode hybridization.

## 2. A concrete research problem: Three MoS₂ bilayers

Imagine that your laboratory has prepared three bilayer MoS₂ samples.

**Sample A: Conventional 2H stacking**

The two monolayers have the relative orientation and translation associated with the conventional 2H structure.

The ideal bilayer possesses inversion symmetry.

**Sample B: 3R stacking**

The layers have the relative orientation and lateral displacement associated with rhombohedral stacking.

The ideal bilayer lacks inversion symmetry.

**Sample C: A twisted bilayer**

One layer is rotated by approximately 25° relative to the other.

The resulting structure has spatially varying atomic registry rather than a single uniform stacking configuration.

All three samples contain the same number of Mo and S atoms per unit area, apart from small differences associated with lattice relaxation.

Their individual monolayers have essentially the same intralayer bonding.

Yet their low-frequency Raman spectra need not be identical.

Why?

Because the low-frequency modes probe the relative motion of entire layers.

Their restoring forces are particularly sensitive to the interlayer interaction potential.

## 3. Shear and breathing modes measure different parts of the interlayer potential

Consider the potential-energy landscape experienced when one layer moves relative to another.

There are two particularly important displacement directions.

**Lateral displacement: The shear mode**

Imagine translating the upper layer slightly along the plane of the lower layer.

The energy changes because the relative positions of sulfur and molybdenum atoms across the interface change.

Near a stable stacking configuration, the curvature of this energy landscape determines the restoring force for small lateral displacements.

The corresponding vibration is an interlayer shear mode.

A relatively steep lateral energy landscape produces a relatively high shear frequency.

A nearly flat landscape produces a soft shear mode.

**Out-of-plane displacement: The breathing mode**

Now imagine moving the layers toward and away from each other.

This changes their separation.

The resulting restoring force depends on the balance between attractive interlayer interactions and short-range repulsion.

The corresponding vibration is the interlayer breathing mode.

Its frequency probes the curvature of the interlayer potential with respect to layer separation.

These two curvatures are not necessarily correlated.

A bilayer can resist changes in interlayer separation relatively strongly while allowing comparatively easy lateral sliding.

This is one reason shear and breathing modes provide complementary information about interlayer coupling.

**A useful mechanical approximation**

For two identical, rigid layers coupled by a harmonic interlayer interaction, the nonzero relative-motion frequency is

<div class="equation">
\[
\boxed{ \omega_{\mathrm{S,B}} = \sqrt{\frac{2K_{\mathrm{S,B}}}{\mu}} }
\]
</div>

Here:

||
||
||

<table>
<tbody>
<tr class="odd">
<td><ul>
<li><p>\\(\omega_{\mathrm{S,B}}\\) is the angular frequency of the shear or breathing mode.</p></li>
<li><p>\\(K_{\mathrm{S,B}}\\) is the corresponding interlayer restoring-force constant per unit area, defined through the quadratic energy cost of relative displacement.</p></li>
<li><p>\\(\mu\\) is the mass per unit area of one monolayer.<br />
The factor of two arises because both layers participate in the relative vibration.<br />
This model neglects internal layer deformation, anharmonicity, substrate interactions, and coupling to other phonon branches.<br />
Nevertheless, it provides a useful physical interpretation.<br />
<strong>A frequency shift reflects a change in effective restoring force only after the relevant mode identity and effective mass have been established.</strong><br />
That qualification matters when comparing different stacking configurations or strongly hybridized modes.<br />
<br />
<strong>4. What should happen in the three samples?</strong><br />
Let's begin with Sample A, the conventional 2H bilayer.<br />
Its low-frequency spectrum contains interlayer shear and breathing vibrations.<br />
For the ideal structure, these can be classified according to the irreducible representations of the D₃d point group.<br />
The shear vibration is doubly degenerate in the absence of symmetry-breaking perturbations.<br />
The breathing vibration is nondegenerate.<br />
Both can be Raman-active, but their Raman tensors differ.<br />
Consequently, polarization-resolved Raman measurements can help distinguish them.<br />
Now consider Sample B, the 3R bilayer.<br />
The absence of inversion symmetry changes the selection rules.<br />
However, the mechanical differences between 2H and 3R stacking are not necessarily dramatic.<br />
The interlayer separation and restoring forces can remain comparable.<br />
The Raman intensities, on the other hand, may change substantially because the electronic polarizability responds differently to the atomic displacements.<br />
This distinction was demonstrated experimentally by van Baren and colleagues.<br />
Their study of 2H and 3R multilayer MoS₂ found that the strongest Raman-active shear branch depends strongly on stacking order.<br />
For multilayers supporting several shear branches, the strongest shear response occurs on the highest-frequency branch in 2H stacking but on the lowest-frequency branch in 3R stacking.<br />
They also observed slightly higher breathing frequencies in 2H than in 3R structures.<br />
The results demonstrate that stacking affects both mechanical coupling and Raman selection rules, but not necessarily in the same way. <u><a href="https://scixplorer.org/abs/2019TDM.....6b5022V/abstract?utm_source=chatgpt.com">SciXplorer</a></u><br />
<strong>Important distinction:</strong> A bilayer has only one interlayer shear frequency in the ideal rigid-layer approximation, although the mode is twofold degenerate. The comparison of different shear branches becomes especially informative in thicker multilayers.<br />
<br />
<strong>5. Now introduce the twist angle</strong><br />
Sample C is rotated by approximately 25°.<br />
What changes physically?<br />
The first effect is that the interlayer atomic registry is no longer uniform.<br />
Different regions of the interface sample different relative atomic arrangements.<br />
For an idealized rigid, sufficiently large, incommensurate bilayer, the spatial average of the lateral interlayer potential can become relatively insensitive to uniform sliding.<br />
This can strongly reduce the effective restoring force for coherent relative lateral motion.<br />
The breathing mode behaves differently.<br />
Even when the lateral registry varies, the two layers still experience an attractive interaction that maintains a finite equilibrium separation.<br />
Consequently, the breathing vibration can remain relatively robust while the coherent shear vibration becomes very soft or difficult to observe.<br />
This is a central physical distinction.<br />
<strong>Twisting can reduce the effective resistance to lateral sliding without eliminating the restoring force against layer separation.</strong><br />
In a real sample, the outcome depends on structural relaxation, commensurability, finite-size effects, pinning, and the substrate.<br />
A nominally twisted bilayer should therefore not automatically be treated as a freely sliding, perfectly rigid system.<br />
<strong>Experimental evidence</strong><br />
Huang and colleagues studied low-frequency Raman modes in twisted bilayer MoS₂.<br />
They found that the interlayer vibrational spectra are particularly sensitive to twist angles near 0° and 60°.<br />
In their samples, phonon frequencies varied by as much as approximately 8 cm⁻¹, while Raman intensities varied by factors approaching five.<br />
For intermediate twist angles between approximately 20° and 40°, the measured low-frequency response was comparatively insensitive to angle.<br />
Their study also found that high-frequency intralayer phonons were substantially less sensitive to twisting than the interlayer modes. <u><a href="https://pubs.acs.org/doi/abs/10.1021/acs.nanolett.5b05015?utm_source=chatgpt.com">ACS Publications</a></u><br />
This result provides a useful experimental lesson.<br />
When investigating twist-dependent interlayer coupling, low-frequency Raman spectroscopy may be much more informative than conventional high-frequency Raman measurements alone.<br />
<br />
<strong>6. Why an absent Raman peak does not prove that a phonon has disappeared</strong><br />
Suppose the shear-mode peak becomes undetectable in Sample C.<br />
There are several possible explanations.<br />
The effective lateral restoring force may have decreased sufficiently that the mode frequency approaches the low-frequency limit of the spectrometer.<br />
The phonon may remain at a finite frequency but acquire a much smaller Raman tensor.<br />
The mode may become broadened by structural disorder, spatially varying interlayer coupling, or anharmonic interactions.<br />
Alternatively, the experimental polarization geometry may suppress its Raman response.<br />
These mechanisms have different physical interpretations.<br />
A mechanically softened phonon corresponds to a change in the lattice dynamics.<br />
A symmetry-forbidden or optically weak phonon corresponds to a change in the measurement coupling.<br />
A broadened phonon may indicate reduced lifetime, inhomogeneity, or unresolved mode mixing.<br />
A missing spectral feature alone cannot distinguish these possibilities.<br />
<strong>This is today's principal interpretive pitfall: Raman visibility is not equivalent to phonon existence.</strong><br />
For twisted structures, the problem becomes more complicated because the measured signal can average over different local stacking configurations.<br />
A single spectrum may therefore contain contributions from several local environments.<br />
<br />
<strong>7. How would you distinguish the possible mechanisms experimentally?</strong><br />
Imagine that the shear peak is strong in Sample A, weaker in Sample B, and absent in Sample C.<br />
A convincing analysis should combine several independent observations.<br />
<strong>First: Measure both shear and breathing frequencies</strong><br />
If the shear mode softens substantially while the breathing frequency changes only slightly, the result suggests that twisting has affected the lateral restoring force more strongly than the out-of-plane restoring force.<br />
This is physically plausible because lateral sliding and layer separation probe different directions of the interlayer potential.<br />
However, it is not yet proof of a specific microscopic stacking configuration.<br />
<strong>Second: Perform polarization-resolved Raman spectroscopy</strong><br />
Changing the incident and detected polarizations provides information about the Raman tensor.<br />
A peak that disappears in one polarization configuration but reappears in another may reflect a selection rule rather than a loss of mechanical stiffness.<br />
Polarization dependence can also help identify mode symmetry.<br />
<strong>Third: Map the spectrum spatially</strong><br />
A twisted sample may contain reconstructed domains, local strain, bubbles, or variations in interlayer separation.<br />
A spatially averaged spectrum can conceal this heterogeneity.<br />
Raman mapping can reveal whether different regions exhibit different frequencies, linewidths, or intensities.<br />
The interpretation must account for the optical spot size relative to the structural length scales.<br />
<strong>Fourth: Establish the stacking geometry independently</strong><br />
Electron diffraction, scanning probe measurements, or suitable structural microscopy can provide information about the relative crystallographic orientation and local registry.<br />
Raman spectroscopy is a powerful indirect structural probe, but it is not generally a unique structural determination.<br />
<strong>Fifth: Compare against a dynamical model</strong><br />
First-principles calculations or an appropriately parameterized interlayer force-constant model can test whether the measured frequencies are consistent with a proposed stacking structure.<br />
The calculated eigenvectors are particularly important.<br />
Without them, it is easy to confuse a mode shift with a change in which mode carries the strongest Raman intensity.<br />
The strongest analysis combines structural information, mode frequencies, eigenvectors, and optical selection rules.<br />
<br />
<strong>8. Where reciprocal space enters the problem</strong><br />
So far, we have discussed the interlayer vibrations primarily in real space.<br />
But the reciprocal-space picture is equally important.<br />
In conventional first-order Raman scattering, the momentum transferred by visible photons is very small compared with the dimensions of a typical crystal Brillouin zone.<br />
The experiment therefore predominantly probes phonons close to the zone center.<br />
For a periodic multilayer, these phonons can be classified using the reciprocal lattice of the complete structure.<br />
When a bilayer is twisted into a commensurate moiré superlattice, the enlarged real-space unit cell corresponds to a smaller reciprocal-space Brillouin zone.<br />
Phonon branches can consequently be folded into this reduced zone.<br />
Some vibrations that occur at finite wavevectors in the original layer description can appear near the moiré-zone center.<br />
However, two distinct effects must be separated.<br />
<strong>Zone folding changes the wavevector labeling of a mode.</strong><br />
<strong>Interlayer coupling and symmetry determine whether that mode mixes with other vibrations and becomes optically observable.</strong><br />
A folded phonon does not automatically produce a strong Raman peak.<br />
Its intensity depends on the actual eigenvector, the Raman matrix element, and the structure's remaining symmetries.<br />
This is an important foundation for the moiré-phonon discussions coming in Week 2.<br />
<br />
<strong>9. Connection to phonon polaritons</strong><br />
There is a deeper reason to care about phonon selection rules.<br />
The same lattice eigenmodes that appear in Raman spectroscopy can also influence the dielectric response.<br />
However, Raman activity and infrared activity are different properties.<br />
Raman scattering probes changes in electronic polarizability.<br />
Infrared absorption probes the electric polarization generated by lattice motion.<br />
A vibration can therefore be Raman-active but infrared-inactive.<br />
For phonon polaritons, the infrared response is particularly important.<br />
A polar optical phonon can couple to an electromagnetic field through its oscillating electric dipole.<br />
In anisotropic crystals, the coupling depends on the direction of the electric field relative to the crystal axes.<br />
This directional dependence ultimately becomes central to hyperbolic phonon polaritons.<br />
For example, hexagonal boron nitride has different in-plane and out-of-plane dielectric responses.<br />
In contrast, α-MoO₃ exhibits strong in-plane dielectric anisotropy.<br />
The distinction becomes especially important when layers are rotated relative to one another.<br />
In twisted anisotropic polar crystals, the electromagnetic response can depend on the relative orientation of their dielectric principal axes.<br />
But the lesson from today's Raman problem remains relevant:<br />
<strong>Changing the observed optical response does not necessarily imply that the underlying phonon frequencies have changed by the same amount.</strong><br />
The optical response depends on both the vibrational spectrum and the coupling between those vibrations and the electromagnetic field.<br />
This is the conceptual bridge between phonon spectroscopy and phonon-polariton physics.<br />
<br />
<strong>10. Research exercise: Interpret an unfamiliar spectrum</strong><br />
Consider the following hypothetical observations.<br />
Three bilayer MoS₂ samples are measured under otherwise identical conditions.</p></li>
</ul>
<p><strong>Observation</strong></p></td>
<td><p>Sample A</p></td>
<td><p>Sample B</p></td>
<td><p>Sample C</p></td>
</tr>
<tr class="even">
<td><p>Structure</p></td>
<td><p>2H</p></td>
<td><p>3R</p></td>
<td><p>Twisted</p></td>
</tr>
<tr class="odd">
<td><p>Breathing-mode frequency</p></td>
<td><p>Relatively high</p></td>
<td><p>Slightly lower</p></td>
<td><p>Similar to B</p></td>
</tr>
<tr class="even">
<td><p>Shear-mode Raman intensity</p></td>
<td><p>Strong</p></td>
<td><p>Different polarization response</p></td>
<td><p>Very weak</p></td>
</tr>
<tr class="odd">
<td><p>High-frequency intralayer modes</p></td>
<td><p>Clearly visible</p></td>
<td><p>Clearly visible</p></td>
<td><p>Clearly visible</p></td>
</tr>
<tr class="even">
<td><p>Spatial uniformity</p></td>
<td><p>High</p></td>
<td><p>High</p></td>
<td><p>Variable</p></td>
</tr>
</tbody>
</table>

**Question 1: Can you conclude that Sample C has negligible interlayer coupling?**

No.

The persistence of the breathing mode indicates that a finite out-of-plane restoring force remains.

The weak shear signal may reflect reduced lateral stiffness, altered Raman coupling, or both.

**Question 2: Does the difference between Samples A and B prove that one has a much larger interlayer binding energy?**

No.

Phonon frequencies probe the local curvature of the interlayer potential near equilibrium.

Binding energy concerns the overall energetic stabilization of the bound structure relative to separated layers.

Two systems can have similar binding energies but different local force constants, or vice versa.

**Question 3: If Sample C exhibits several nearby breathing peaks, what would you investigate?**

One possibility is spatially varying interlayer coupling associated with different local stacking environments.

Other possibilities include strain, structural inhomogeneity, or additional coupled vibrational modes.

Spatially resolved measurements and calculations would help distinguish these explanations.

**Question 4: If a new Raman peak appears only after twisting, is it necessarily a moiré-folded phonon?**

No.

It might arise from symmetry breaking, disorder-assisted scattering, a previously weak mode becoming optically active, or genuine moiré-induced zone folding.

To establish the latter interpretation, one should identify the proposed parent phonon branch, determine the relevant moiré reciprocal vectors, and test whether the observed frequency and intensity behavior agree with the model.

This distinction will become particularly important when evaluating experimental claims of moiré phonons.

## 11. Two papers for today's application

Paper 1 — Stacking-dependent interlayer vibrations

Van Baren et al., “Stacking-dependent interlayer phonons in 3R and 2H MoS₂.”

*2D Materials* **6**, 025022 (2019).

<u>[Read the paper ](https://doi.org/10.1088/2053-1583/ab0196?utm_source=chatgpt.com)[—](https://doi.org/10.1088/2053-1583/ab0196?utm_source=chatgpt.com)[ DOI: 10.1088/2053-1583/ab0196](https://doi.org/10.1088/2053-1583/ab0196?utm_source=chatgpt.com)</u>

<u>[Open-access preprint](https://arxiv.org/abs/1901.11230?utm_source=chatgpt.com)</u>

**Why this paper is relevant**

This paper demonstrates that interlayer phonon spectra depend on both the mechanical coupling between layers and the symmetry of their stacking arrangement.

The comparison between 2H and 3R structures is particularly useful because it isolates the effects of stacking while retaining the same chemical composition.

The authors combine Raman spectroscopy, group theory, an effective bond-polarizability model, and first-principles calculations.

Pay particular attention to the distinction between the frequency of a shear branch and its Raman intensity.

The paper provides a practical framework for understanding why different stacking sequences can produce very different spectra even when their interlayer mechanical properties are broadly comparable.

**Paper 2 — Direct experimental study of twisted bilayers**

Huang et al., “Low-Frequency Interlayer Raman Modes to Probe Interface of Twisted Bilayer MoS₂.”

*Nano Letters* **16**, 1435–1444 (2016).

<u>[Read the paper ](https://doi.org/10.1021/acs.nanolett.5b05015?utm_source=chatgpt.com)[—](https://doi.org/10.1021/acs.nanolett.5b05015?utm_source=chatgpt.com)[ DOI: 10.1021/acs.nanolett.5b05015](https://doi.org/10.1021/acs.nanolett.5b05015?utm_source=chatgpt.com)</u>

**Why this paper is relevant**

This study directly connects twist angle, stacking registry, and interlayer phonon spectroscopy.

The authors combine low-frequency Raman measurements with first-principles calculations to investigate how the shear and breathing modes evolve with relative layer orientation.

One particularly important observation is that low-frequency interlayer modes are substantially more sensitive to twisting than many high-frequency intralayer modes.

The study also demonstrates that twist-angle dependence is not necessarily monotonic.

Near certain orientations, small changes in twist or lateral translation can substantially alter the interlayer vibrational response.

At other orientations, the measured response may be comparatively insensitive to further twisting.

When reading the paper, consider which observations establish changes in mechanical coupling and which depend on changes in Raman intensity.

That distinction is essential for interpreting more complicated moiré systems.

## 12. What you should retain

The central conclusion of today's application is that a phonon spectrum reflects three interconnected but distinct aspects of a layered structure.

**The vibrational frequencies** provide information about the local curvature of the interatomic potential.

**The phonon eigenvectors** determine how atoms and layers move relative to one another.

**The optical matrix elements** determine which vibrations appear in Raman or infrared measurements and with what intensity.

Twisting can modify all three.

For interlayer shear and breathing modes, the distinction is particularly revealing because the two vibrations probe different directions of the interlayer potential.

This gives low-frequency Raman spectroscopy unusual sensitivity to stacking registry, interlayer coupling, and structural relaxation.

At the same time, symmetry breaking and changes in optical coupling can complicate interpretation.

The most reliable experimental conclusions come from combining frequencies, intensities, polarization dependence, spatial mapping, and microscopic modeling.

**Looking ahead**

Sunday — Week 1 consolidation: A short research application connecting lattice vibrations, symmetry, and the first physical ideas behind dielectric response.

**Monday, 19 October — Morning Physics Briefing 05: Dielectric Response and the Origin of Phonon–Photon Coupling.**

We will examine how an oscillating ionic lattice produces a frequency-dependent dielectric response and why polar optical phonons can cause the real part of the dielectric function to become negative.

This will complete the essential solid-state foundations before we move into multilayer coupling, stacking, and moiré physics in Week 2.
