---
layout: default
lesson_number: 12
title: "Designing a Raman and Infrared Study of a Twisted MoS₂/WSe₂ Heterostructure"
short_title: "Raman and Infrared Study of a Twisted Heterobilayer"
section: "Week 2 — Multilayer and Twist Physics"
read_time: "9–10 min"
date: 2026-10-24
permalink: /lessons/12-raman-infrared-twisted-mos2-wse2/
---

# Weekend Physics Application 02
## Designing a Raman and Infrared Study of a Twisted MoS₂/WSe₂ Heterostructure

**Saturday, 24 October 2026 | Week 2 — Multilayer and Twist Physics | Reading time: 9–10 minutes**

**Today's central question:** You have fabricated a MoS₂/WSe₂ heterobilayer with an uncertain twist angle. Its Raman spectrum contains additional peaks, several vibrational frequencies have shifted, and the Raman intensity varies across the sample. How can you determine which observations arise from interlayer coupling, stacking registry, moiré phonon folding, atomic reconstruction, or phonon hybridization?

During Week 2, we developed the physics of interlayer shear and breathing modes, stacking-dependent force constants, moiré reciprocal lattices, and vibrational hybridization.

Today, we will apply those concepts to a realistic experimental problem.

Our goal is to design a sequence of measurements that progressively constrains the structure and vibrational dynamics of a twisted heterobilayer.

The central experimental principle is to distinguish three quantities:

1. **Phonon frequency**, which depends on the eigenvalues of the dynamical matrix.
2. **Phonon eigenvector**, which describes how the atoms move.
3. **Optical activity**, which determines how strongly a vibration couples to Raman or infrared fields.

These quantities respond differently to stacking, strain, reconstruction, and interlayer coupling.

Understanding their relationship allows us to extract considerably more information from vibrational spectroscopy.

---


![Original schematic: Designing a Raman and Infrared Study of a Twisted MoS₂/WSe₂ Heterostructure]({{ '/assets/briefing12/spectroscopy-workflow.svg' | relative_url }})

*Figure: Original conceptual illustration; not reproduced from a source paper.*

## 1. The sample: A twisted MoS₂/WSe₂ heterobilayer

Consider a sample consisting of one monolayer of MoS₂ stacked on one monolayer of WSe₂.

The two materials have similar hexagonal crystal structures but different lattice constants.

Representative values are approximately:

- MoS₂: 0.316 nm.
- WSe₂: 0.328 nm.

The lattice mismatch is approximately 3.8%.

Even when the crystallographic orientations are aligned, this mismatch generates a spatial variation in local stacking registry.

The resulting Moiré superlattice has a period of approximately 8.6 nm for an ideal aligned, unstrained heterobilayer.

This value was experimentally observed by Zhang and colleagues using scanning tunneling microscopy on MoS₂/WSe₂ heterobilayers. Their work also demonstrated that the local electronic structure varies substantially between different stacking registries. [DOI](https://doi.org/10.1126/SCIADV.1601459)

If we introduce a relative twist angle, the moiré period changes.

For small lattice mismatch and small twist angle, the approximate relationship is

<div class="equation">

\[
\boxed{
L_{\mathrm m}
\simeq
\frac{\sqrt{a_1a_2}}
{\sqrt{\delta^2+\theta^2}},
\qquad
\delta=\frac{a_2-a_1}{\sqrt{a_1a_2}}
}
\]

</div>

Here:

- \\(L_{\mathrm m}\\) is the geometrical moiré period.
- \\(a_1\\) and \\(a_2\\) are the lattice constants of the two monolayers.
- \\(\delta\\) is their fractional lattice mismatch, using the geometric-mean lattice constant.
- \\(\theta\\) is their relative twist angle in radians, measured from an aligned orientation.

This expression assumes small mismatch, small twist, and approximately rigid lattices.

It is particularly useful because it reveals a fundamental distinction between homobilayers and heterobilayers.

In an identical-layer homobilayer, the geometrical moiré period becomes arbitrarily large as the twist angle approaches zero.

In a lattice-mismatched heterobilayer, the moiré period remains finite at zero twist.

For our MoS₂/WSe₂ sample, the mismatch already establishes a substantial moiré reciprocal-space momentum.

Twisting modifies that momentum.

**Our first experimental objective is therefore to determine the relative crystallographic orientation and distinguish it from the local stacking configuration.**

---

## 2. Measurement 1: Determine the relative crystallographic orientation

Suppose the two monolayers were transferred manually.

The nominal twist angle is 2°, but the transfer alignment has an uncertainty of several degrees.

How can we determine the actual orientation?

### Polarization-resolved second-harmonic generation

Monolayer MoS₂ and WSe₂ possess threefold rotational symmetry and lack inversion symmetry.

Their electric-dipole second-harmonic responses therefore depend on the orientation of the crystal axes.

In a typical polarization-resolved SHG experiment, rotating the incident linear polarization produces a characteristic six-lobed intensity pattern.

The orientation of this pattern provides information about the crystallographic axes.

By measuring isolated regions of each monolayer, we can determine their relative orientations.

This is particularly useful when the heterobilayer contains exposed regions of both constituent materials.

### What are the limitations?

The six-lobed SHG intensity pattern has a 60° periodicity.

Consequently, intensity-only polarization measurements generally determine crystallographic orientation modulo 60°.

Additional information is required to distinguish configurations related by 60° when their atomic stacking family matters.

In overlapping regions, the SHG fields generated by the two layers can interfere coherently.

The resulting signal depends on their relative phases, amplitudes, and optical environment.

A phase-sensitive SHG measurement can therefore provide information beyond the intensity pattern.

However, interference from the two layers complicates the interpretation if their individual contributions are unknown.

**Experimental recommendation:** Determine the crystallographic orientation from exposed monolayer regions whenever possible, then use the heterobilayer SHG response as a complementary structural observable.

This gives us an initial estimate of the twist angle and its uncertainty.

---

## 3. Measurement 2: Establish the Raman spectrum of each constituent monolayer

Before interpreting the heterobilayer spectrum, we need reference measurements.

Measure Raman spectra from isolated MoS₂ and WSe₂ regions under identical experimental conditions.

Ideally, the reference regions should be on the same substrate and experience similar optical environments.

Why?

Because Raman frequencies and intensities depend on several factors beyond stacking.

These include strain, temperature, doping, dielectric screening, optical interference, and electronic resonance.

If the heterobilayer spectrum differs from the monolayer spectra, we need to determine which differences arise from the formation of the interface.

### What should we record?

For each monolayer, measure the frequencies, linewidths, and intensities of the prominent intralayer optical phonons.

Record spectra in parallel and crossed polarization configurations.

Repeat the measurements at several excitation wavelengths if possible.

For example, 532 nm, 633 nm, and 785 nm excitation can sample different electronic resonance conditions.

The precise choice should be informed by the excitonic absorption spectra of the constituent materials.

### Why is excitation wavelength important?

Raman scattering involves an optical matrix element that can be strongly enhanced near electronic resonances.

In transition-metal dichalcogenides, excitonic resonances are particularly important.

The Raman intensity can change substantially with laser wavelength even when the phonon frequency remains essentially unchanged.

This becomes crucial when interpreting weak moiré-related Raman peaks.

An additional peak may be prominent under one excitation condition and nearly invisible under another.

Its disappearance does not establish that the corresponding vibration has disappeared.

---

## 4. Measurement 3: Identify interlayer shear and breathing vibrations

Now turn to the low-frequency Raman spectrum.

In a bilayer, the interlayer shear and breathing vibrations provide direct information about the mechanical coupling between the layers.

### Shear mode

The shear mode involves relative lateral displacement of the two monolayers.

Its restoring force is determined by the curvature of the interlayer sliding-energy landscape.

Consequently, the shear frequency is particularly sensitive to stacking registry.

In a twisted heterobilayer, the local lateral restoring forces vary across the moiré pattern.

The collective shear-like eigenmodes may therefore differ substantially from those of a uniformly stacked reference bilayer.

### Breathing mode

The breathing mode involves relative displacement perpendicular to the layers.

Its restoring force depends primarily on the curvature of the interlayer interaction with respect to separation.

Breathing frequencies are sensitive to the interlayer separation, mechanical coupling, and local environment.

In many layered systems, the breathing mode remains relatively robust as the stacking configuration changes, although its frequency can shift.

### A practical challenge: Spectral access

Interlayer modes typically lie at very low Raman shifts, often within a few tens of inverse centimeters of the laser line.

Measuring them requires an ultralow-frequency Raman configuration with sufficient laser rejection.

A conventional Raman spectrometer with a cutoff near 100 cm⁻¹ may miss the entire relevant spectral region.

Volume Bragg gratings, suitable notch-filter arrangements, or specialized low-frequency Raman systems can provide access to these modes.

For our heterobilayer, we should aim to measure as close to the laser line as the instrument permits.

### What if the shear mode is weak or absent?

Several explanations are possible.

The lateral restoring force may be weak.

The relevant eigenmode may have a small Raman matrix element.

The vibration may be broadened by structural inhomogeneity.

The mode may also be shifted into a spectral region inaccessible to the instrument.

**A weak shear Raman peak is insufficient evidence for weak mechanical coupling.**

We must distinguish the mechanical frequency from the optical intensity.

---

## 5. Measurement 4: Use polarization to constrain phonon symmetry

Suppose the heterobilayer spectrum contains three additional peaks.

One appears only in parallel polarization.

Another is visible in both parallel and crossed polarization.

The third is weak in both configurations.

What can we conclude?

The polarization dependence provides information about the Raman tensors of the corresponding vibrational modes.

For a particular mode, the Raman intensity depends approximately on

<div class="equation">

\[
\boxed{
I_\nu
\propto
\left|
\mathbf e_{\mathrm{out}}^{T}
\mathbf R_\nu(\omega_{\mathrm L})
\mathbf e_{\mathrm{in}}
\right|^2
}
\]

</div>

Here:

- \\(I_\nu\\) is the Raman intensity associated with phonon mode \\(\nu\\), apart from other spectral and experimental prefactors.
- \\(\mathbf e_{\mathrm{in}}\\) is the incident polarization vector.
- \\(\mathbf e_{\mathrm{out}}\\) is the analyzed scattered-light polarization vector.
- \\(\mathbf R_\nu\\) is the Raman tensor of the mode.
- \\(\omega_{\mathrm L}\\) is the laser angular frequency.

The Raman tensor can be complex and strongly frequency-dependent near electronic resonances.

This expression provides a useful conceptual separation.

The phonon eigenvector determines the atomic displacement pattern.

The Raman tensor describes how that displacement changes the optical response.

Crystal symmetry constrains the allowed tensor components.

### What changes in a twisted heterobilayer?

The combined structure generally has lower symmetry than either isolated monolayer.

This can allow Raman tensor components that are forbidden in a higher-symmetry reference structure.

Consequently, a phonon that is weak or inactive in one configuration may become observable in another.

However, a polarization-dependent intensity change can also arise from resonance effects or mixing between vibrational modes.

**Experimental recommendation:** Measure the full polarization dependence of the additional peaks rather than relying only on parallel and crossed spectra.

The angular dependence provides stronger constraints on the effective Raman tensors.

---

## 6. Measurement 5: Test whether the additional peaks are moiré-folded phonons

We now reach the central problem of this week's lessons.

Suppose an additional Raman peak appears in the heterobilayer but is absent from the isolated monolayers.

Could it be a moiré-folded phonon?

Yes.

The moiré reciprocal lattice introduces additional spatial periodicities into the interlayer force constants.

These can couple phonon states whose wavevectors differ by moiré reciprocal vectors.

In a commensurate supercell description, phonons at finite wavevectors in the original monolayer Brillouin zones can fold toward the moiré-zone center.

Under suitable conditions, these modes become Raman-active.

### How would we test this interpretation?

First, determine the moiré reciprocal vectors from the estimated twist angle and lattice mismatch.

Second, calculate or obtain the phonon dispersions of isolated MoS₂ and WSe₂.

Third, identify phonon branches at wavevectors related to the relevant moiré reciprocal vectors.

Fourth, compare their predicted frequencies with the additional Raman peaks.

If the peak frequencies agree with the expected folded branches, this supports a zone-folding interpretation.

### What would provide stronger evidence?

Measure a series of heterobilayers with different twist angles.

As the twist angle changes, the moiré reciprocal vectors change.

Consequently, the phonon wavevectors selected by folding also change.

If the additional peak frequencies systematically follow the corresponding monolayer phonon dispersions, the assignment becomes considerably stronger.

### An important limitation

A folded phonon may remain Raman-weak.

Its visibility depends on the modulation of the force constants, the phonon eigenvector, and the Raman matrix element.

Thus, a calculation of folded frequencies should ideally be accompanied by a calculation of Raman activity.

---

## 7. Measurement 6: Distinguish phonon folding from hybridization

Suppose the additional Raman peaks do not agree with the expected folded monolayer frequencies.

One possible explanation is interlayer phonon hybridization.

The spatially modulated interlayer interaction can couple different vibrational states.

If two states have compatible symmetry and similar frequencies, their eigenvectors may mix strongly.

The resulting eigenfrequencies can shift away from their uncoupled values.

### What would constitute evidence for hybridization?

Ideally, we would identify two parent phonon branches and follow their evolution as a parameter changes.

The relevant parameter could be twist angle, strain, or interlayer separation.

If the branches approach and exhibit an avoided crossing, that supports the presence of coupling.

An accompanying exchange of eigenvector character provides stronger evidence.

In Raman spectroscopy, hybridization may also redistribute spectral intensity between the branches.

But intensity transfer alone is ambiguous because electronic resonance effects can produce similar behavior.

### What should we calculate?

For the heterobilayer, calculate the phonon eigenvectors and their projections onto the vibrational modes of the isolated constituent layers.

This allows us to determine whether a particular mode is predominantly MoS₂-like, WSe₂-like, or a substantial mixture.

For a reconstructed moiré structure, we should additionally examine the spatial distribution of the displacement amplitudes.

The resulting eigenvectors can reveal whether the vibration is extended across the moiré cell or concentrated in particular stacking environments.

---

## 8. Measurement 7: Determine whether atomic reconstruction is important

We now consider the structural relaxation of the heterobilayer.

The geometrical moiré pattern describes how the stacking registry varies when two rigid lattices are superimposed.

In a real heterostructure, the atoms can relax.

The resulting structure minimizes the competition between interlayer stacking energy and intralayer elasticity.

For sufficiently favorable conditions, this can produce reconstructed domains separated by narrow boundaries.

### How would reconstruction affect Raman spectroscopy?

Reconstruction modifies the local interlayer force constants.

It can therefore shift phonon frequencies.

It also changes the spatial modulation of the dynamical matrix.

This can alter phonon hybridization and redistribute vibrational amplitudes across the moiré cell.

Finally, reconstruction can change local symmetry and Raman activity.

These effects can generate pronounced spectral changes even when the reconstructed domains are much smaller than the optical diffraction limit.

### What would be convincing evidence?

Compare Raman measurements with phonon calculations for both rigid and relaxed heterobilayer structures.

If the rigid calculation fails to reproduce the observed frequencies while the relaxed calculation succeeds, reconstruction becomes a plausible explanation.

Independent structural evidence would strengthen the conclusion.

Depending on the sample and available instrumentation, scanning transmission electron microscopy, scanning probe microscopy, or diffraction-based methods may provide information about the atomic registry and reconstruction.

For an individual heterobilayer, it is also important to account for local strain and contamination.

These can change the interlayer separation and the effective mechanical coupling.

### Why this matters

Quan and colleagues demonstrated in twisted MoS₂ homobilayers that Raman spectra can reveal strong phonon renormalization associated with atomic reconstruction.

Their work provides a useful framework for interpreting the vibrational spectra of reconstructed moiré systems. [Nature](https://www.nature.com/articles/s41563-021-00960-1)

However, the reconstruction behavior of a MoS₂/WSe₂ heterobilayer must be evaluated using its own stacking-energy landscape and elastic properties.

The lattice mismatch changes the energetic competition relative to an identical-layer bilayer.

---

## 9. Measurement 8: What additional information can infrared spectroscopy provide?

Raman spectroscopy probes changes in electronic polarizability.

Infrared spectroscopy probes vibrations that produce an oscillating electric dipole moment.

The two techniques therefore provide complementary information about phonon symmetry and optical activity.

### Intralayer optical phonons

Both MoS₂ and WSe₂ possess optical phonons with infrared-active components.

Their frequencies and oscillator strengths depend on the atomic displacement patterns and effective charges.

The heterobilayer can modify these vibrations through interlayer coupling, dielectric screening, strain, and symmetry changes.

Infrared spectroscopy may therefore provide additional constraints on the vibrational eigenmodes.

### Interlayer shear and breathing vibrations

These modes lie at much lower frequencies than most intralayer optical phonons.

Their characteristic energies often fall in the far-infrared or terahertz region.

Accessing them requires instrumentation appropriate to those frequencies.

Their infrared activity also depends on symmetry and the mode-effective dipole moment.

For an ultrathin heterobilayer, the absolute absorption signal may be weak.

A suitable substrate, differential measurement strategy, and careful optical modeling are therefore important.

### What about nano-IR and s-SNOM?

Scattering-type scanning near-field optical microscopy, or s-SNOM, uses a sharp probe to generate and detect strongly confined electromagnetic fields.

It can provide nanoscale information about the local optical response.

However, conventional mid-infrared s-SNOM instrumentation may not access the very low frequencies associated with interlayer shear and breathing modes.

Terahertz near-field techniques may be more appropriate for those vibrations.

The relevant signal strength also depends on the oscillator strength and electromagnetic environment.

For our MoS₂/WSe₂ sample, infrared measurements would be particularly valuable if they reveal a vibrational feature whose activity changes with stacking or symmetry.

A spatially varying infrared signal could also indicate local changes in dielectric response.

But assigning such a signal to a localized phonon requires additional evidence about the vibrational eigenvector.

**The distinction between a local dielectric contrast and a localized vibrational eigenmode will become especially important when we study phonon polaritons.**

---

## 10. A practical experimental sequence

Suppose you have access to polarization-resolved Raman microscopy, SHG microscopy, and infrared spectroscopy.

How should you organize the measurements?

| Stage | Measurement | Primary information | Important ambiguity |
|---|---|---|---|
| 1 | Optical microscopy and AFM | Sample morphology, overlap region, contamination, bubbles | Optical contrast does not establish atomic registry |
| 2 | Polarization-resolved SHG | Relative crystallographic orientation | Intensity patterns have rotational ambiguities |
| 3 | Monolayer Raman references | Constituent phonon frequencies and Raman tensors | Substrate, strain, and resonance effects |
| 4 | Ultralow-frequency Raman | Interlayer shear and breathing vibrations | Raman intensity depends on optical matrix elements |
| 5 | Excitation-dependent Raman | Resonance enhancement and mode visibility | Intensity changes can occur without phonon renormalization |
| 6 | Twist-dependent Raman | Evidence for moiré folding and mode evolution | Folding, hybridization, and reconstruction can coexist |
| 7 | Infrared spectroscopy | Infrared-active phonons and dielectric response | Weak absorption and limited spectral access |
| 8 | Structural characterization and modeling | Registry, reconstruction, and vibrational eigenvectors | Model dependence and sample-specific disorder |

The order is deliberate.

We first establish the sample structure and reference spectra.

We then identify the interlayer vibrations.

Next, we examine the additional spectral features and their dependence on polarization, excitation energy, and twist angle.

Finally, we use structural information and calculations to distinguish the possible microscopic mechanisms.

This approach reduces the number of unconstrained explanations at each stage.

---

## 11. A realistic complication: Spatially varying twist angle

Suppose Raman mapping reveals that an additional peak changes frequency across the heterobilayer.

One interpretation is that the local twist angle varies.

This would modify the moiré reciprocal vectors and therefore the frequencies of folded phonons.

However, other explanations are possible.

Local strain can shift phonon frequencies.

Variations in interlayer separation can modify mechanical coupling.

Contamination or trapped bubbles can weaken the local interface interaction.

Reconstruction can change the effective phonon eigenvectors.

Temperature variations can also shift and broaden vibrational peaks.

### How would we separate these effects?

A useful strategy is to compare several spectral observables simultaneously.

If intralayer optical phonons shift together with the additional peak, strain or temperature may contribute.

If the interlayer breathing mode changes strongly while the intralayer modes remain relatively stable, changes in interlayer separation or coupling become more plausible.

If the additional peak follows the expected twist-dependent folded-phonon dispersion, local variation in moiré momentum becomes a stronger candidate.

If Raman intensity changes without significant frequency shifts, changes in optical matrix elements should be considered.

The most convincing interpretation comes from correlated measurements.

For example, a map of the local SHG orientation can be compared with Raman frequency and intensity maps.

Where possible, structural measurements can then be used to test whether the optical variations correlate with changes in stacking registry or reconstruction.

### An important spatial-resolution consideration

A diffraction-limited Raman measurement averages over a region much larger than a typical moiré unit cell.

For an 8–10 nm moiré period, hundreds or thousands of moiré cells may contribute to one optical measurement.

The resulting spectrum can still be sensitive to the moiré structure because the vibrational eigenmodes depend on the nanoscale periodicity.

However, a spatial Raman map does not directly resolve individual moiré cells.

It maps the spatial variation of the measured vibrational response averaged over the optical resolution.

This distinction is essential when interpreting claims of nanoscale reconstruction from far-field spectroscopy.

---

## 12. Today's principal interpretive pitfall

### Misconception: A spatially varying Raman intensity map directly images stacking domains.

A Raman intensity map measures the spatial distribution of an optical scattering signal.

That signal depends on the phonon eigenvectors, Raman tensors, excitation resonance, collection geometry, and local optical environment.

Changes in stacking registry can modify the signal through several of these mechanisms.

However, the optical resolution determines the spatial averaging of the measurement.

For moiré domains much smaller than the diffraction limit, the map generally reflects an averaged response.

A strong intensity contrast may also arise from strain, thickness variations, contamination, or electronic resonance effects.

Therefore, a Raman intensity map can provide evidence for spatially varying structural or vibrational properties.

Assigning individual atomic stacking domains requires a spatial-resolution argument and, ideally, independent structural validation.

**The most reliable interpretation combines spectral frequency, polarization dependence, excitation-energy dependence, and structural information.**

---

## 13. Research exercise: Four observations from one heterobilayer

Consider the following experimental results.

### Observation A

The interlayer breathing frequency decreases in one region of the sample.

The intralayer optical phonon frequencies remain nearly unchanged.

**Question:** What should you investigate first?

**Answer:** A change in interlayer mechanical coupling.

The breathing mode is directly sensitive to the out-of-plane restoring force between the layers.

Local changes in separation, contamination, or stacking-dependent interlayer interactions may reduce that restoring force.

The relatively stable intralayer frequencies suggest that the dominant change may involve the interface.

However, the result alone does not uniquely identify its cause.

### Observation B

An additional Raman peak shifts systematically with the measured twist angle.

Its frequency agrees with the monolayer phonon dispersion evaluated at the appropriate moiré reciprocal wavevector.

**Question:** What is the leading interpretation?

**Answer:** Moiré-induced phonon folding.

The twist-dependent moiré reciprocal lattice selects finite-wavevector phonons that can become optically accessible.

Agreement with the parent phonon dispersion supports the assignment.

The Raman intensity should still be analyzed separately.

### Observation C

Two Raman peaks approach one another as twist angle changes, exhibit a minimum frequency separation, and exchange their polarization-dependent intensities.

**Question:** What mechanism should be tested?

**Answer:** Phonon hybridization.

The frequency repulsion is consistent with coupling between two vibrational states.

The intensity redistribution may reflect changes in their eigenvector character.

A calculation of the coupled eigenvectors and Raman tensors would provide stronger evidence.

### Observation D

A new Raman peak appears only under 633 nm excitation.

Its frequency is unchanged when the laser is switched to 532 nm, but its intensity becomes too weak to resolve.

**Question:** Has the phonon disappeared?

**Answer:** The observation is consistent with resonance-dependent Raman visibility.

The optical matrix element can vary strongly with excitation energy.

The vibration may remain present while its Raman intensity falls below the detection threshold.

Excitation-dependent measurements should therefore be incorporated into the interpretation of weak moiré-related features.

---

## 14. Two papers for today's application

### Paper 1 — Direct structural characterization of MoS₂/WSe₂ moiré heterobilayers

**Zhang et al., “Interlayer couplings, Moiré patterns, and 2D electronic superlattices in MoS₂/WSe₂ hetero-bilayers.”**

*Science Advances* **3**, e1601459 (2017).

[Read the paper — DOI: 10.1126/sciadv.1601459](https://doi.org/10.1126/SCIADV.1601459)

**Why this paper matters**

The authors investigate rotationally aligned MoS₂/WSe₂ heterobilayers using scanning tunneling microscopy, scanning tunneling spectroscopy, electron microscopy, and first-principles calculations.

They observe a moiré period of approximately 8.7 nm, generated by the lattice mismatch between the constituent monolayers.

Their measurements reveal how the local electronic structure changes with atomic stacking registry.

Although the paper focuses primarily on electronic properties, it provides an experimentally grounded picture of the spatially varying interface environment.

For today's application, focus on how the authors determine the local stacking configurations and correlate them with measured properties.

**Research question:** If the local electronic structure changes strongly with stacking registry, which aspects of the interlayer force-constant matrix would you expect to vary across the same moiré pattern?

### Paper 2 — Raman identification of moiré phonons in a related heterobilayer

**Lim et al., “Modulation of Phonons and Excitons Due to Moiré Potentials in Twisted Bilayer of WSe₂/MoSe₂.”**

*ACS Nano* **17**, 13938–13947 (2023).

[Read the paper — DOI: 10.1021/acsnano.3c03883](https://pubs.acs.org/doi/10.1021/acsnano.3c03883)

**Why this paper matters**

This study examines a closely related TMD heterobilayer using Raman spectroscopy, photoluminescence, and first-principles calculations.

The authors investigate the twist-angle dependence of interlayer vibrational modes, moiré phonons, and interlayer excitonic states.

They identify distinct behavior near 0° and 60° alignment and examine the role of the interlayer interaction.

The paper provides a particularly useful example of combining vibrational and electronic optical measurements to constrain the structure of a twisted heterobilayer.

For today's application, examine how the authors distinguish different twist-angle regimes and identify the additional Raman features.

Also consider how the interpretation would change if only one excitation wavelength or polarization configuration were available.

**Research question:** Which conclusions in this paper follow directly from measured phonon frequencies, and which require additional assumptions about stacking, resonance enhancement, or structural relaxation?

---

## 15. What you should retain

This week's central concepts can now be assembled into an experimental interpretation framework.

Stacking registry determines the local interlayer interaction energy.

The curvature of that energy landscape determines the restoring forces associated with interlayer shear and breathing vibrations.

Crystal symmetry constrains the optical activity of the vibrational modes.

Twist and lattice mismatch create a moiré modulation of the local stacking registry.

The corresponding reciprocal vectors determine which finite-wavevector phonons can become coupled or folded into the reduced Brillouin zone.

Interlayer coupling can hybridize vibrational states with compatible symmetry and similar frequencies.

Atomic reconstruction modifies the local force constants and can produce spatially structured vibrational eigenvectors.

Raman spectroscopy probes these modes through changes in electronic polarizability.

Infrared spectroscopy provides complementary information about vibrations carrying oscillating electric dipole moments.

Each measurement constrains a different part of the physical problem.

**The strongest experimental conclusions emerge when frequency shifts, optical selection rules, spatial variation, and structural information support the same microscopic interpretation.**

This principle will remain important throughout our study of phonon polaritons.

---

## Next application — Sunday, 25 October 2026

### From Vibrational Eigenmodes to Dielectric Response: Which Phonons Can Form Polaritons?

Tomorrow we will connect the lattice dynamics of Week 2 to the electromagnetic response of polar layered materials.

Our central question will be:

**Given a calculated phonon eigenvector and its frequency, how can we determine whether that vibration contributes to the infrared dielectric response and can couple to an electromagnetic field?**

We will examine mode-effective charges, infrared oscillator strength, longitudinal and transverse optical character, and the relationship between phonon eigenvectors and dielectric resonances.

The concrete examples will include hBN and layered TMD heterostructures.

This will prepare us for Week 3, where we will develop the dielectric-tensor description of anisotropic phonon polaritons, Reststrahlen bands, and hyperbolic propagation.
