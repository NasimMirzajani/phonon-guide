---
layout: default
lesson_number: 14
title: "The Dielectric Tensor and Reststrahlen Bands: From Optical Phonons to Hyperbolic Dispersion"
short_title: "Dielectric Tensor and Hyperbolic Dispersion"
section: "Week 3 — Polaritons in Anisotropic Layered Media"
read_time: "9–10 min"
date: 2026-10-26
permalink: /lessons/14-dielectric-tensor-reststrahlen-hyperbolic-dispersion/
---

# Morning Physics Briefing 10
## The Dielectric Tensor and Reststrahlen Bands: From Optical Phonons to Hyperbolic Dispersion

**Monday, 26 October 2026 | Week 3 — Polaritons in Anisotropic Layered Media | Reading time: 9–10 minutes**

**Today's central question:** Why can an electromagnetic wave propagate through a crystal along one direction while becoming evanescent along another, and how can the same material support polaritons with wavelengths tens of times smaller than the free-space infrared wavelength?

Last week, we established how stacking, twist, and interlayer coupling modify phonon eigenvectors and frequencies. Yesterday, we connected those vibrations to the infrared dielectric response through Born effective charges and oscillator strengths.

Today, we examine how that dielectric response determines electromagnetic propagation.

Our primary example is hexagonal boron nitride (hBN), which supports two distinct hyperbolic phonon-polariton bands. We will then introduce α-MoO₃, whose strong in-plane anisotropy provides an additional degree of control over polariton propagation.

The central connection is:

**Optical phonon resonance → frequency-dependent dielectric tensor → anisotropic electromagnetic dispersion → confined phonon polaritons.**

---


![Original schematic: The Dielectric Tensor and Reststrahlen Bands: From Optical Phonons to Hyperbolic Dispersion]({{ '/assets/briefing14/hyperbolic-types.svg' | relative_url }})

*Figure: Original conceptual illustration; not reproduced from a source paper.*

## 1. What does the dielectric tensor physically describe?

Consider an electromagnetic field propagating through a crystal.

The electric field drives the electronic charge distribution and, at infrared frequencies, can also drive ionic displacements.

These responses generate an electric polarization.

The dielectric tensor describes how the polarization and electric displacement respond to an applied electric field.

In an isotropic material, the response is identical along every direction.

In an anisotropic crystal, the response depends on the direction of the electric field relative to the crystal axes.

For example, consider a layered material with strong covalent bonding within each atomic plane and weaker interactions between planes.

The restoring forces associated with in-plane atomic motion differ from those associated with out-of-plane motion.

Consequently, the corresponding optical phonons have different frequencies.

Their induced polarizations also point along different directions.

The dielectric response therefore contains different resonances for in-plane and out-of-plane electric fields.

### The dielectric tensor of hBN

Bulk hBN is approximately isotropic within its basal plane.

Its crystallographic c axis is perpendicular to those planes.

In the principal-axis coordinate system, the dielectric tensor has the form

<div class="equation">

\[
\boldsymbol{\varepsilon}(\omega)=
\begin{pmatrix}
\varepsilon_{\parallel}(\omega)&0&0\\
0&\varepsilon_{\parallel}(\omega)&0\\
0&0&\varepsilon_{\perp}(\omega)
\end{pmatrix}.
\]

</div>

Here, \\(\varepsilon_{\parallel}\\) describes the in-plane dielectric response, while \\(\varepsilon_{\perp}\\) describes the response along the c axis.

Each component is complex and frequency-dependent.

The real part governs much of the wave propagation and phase response.

The imaginary part describes absorption and dissipation.

The important feature is that the two components can have opposite signs at particular infrared frequencies.

We will see that this produces hyperbolic dispersion.

---

## 2. Why optical phonons produce strong dielectric dispersion

Recall that an infrared-active phonon carries an oscillating electric dipole moment.

When an infrared electric field drives the vibration near its natural frequency, the ionic displacement becomes large.

The induced polarization therefore changes rapidly with excitation frequency.

For a principal dielectric component, a simplified multi-oscillator model is

<div class="equation">

\[
\boxed{
\varepsilon_j(\omega)
=
\varepsilon_{\infty,j}
+
\sum_{\nu}
\frac{
S_{j\nu}
}{
\omega_{\mathrm{TO},\nu}^{2}
-\omega^{2}
-i\gamma_{\nu}\omega
}
}
\]

</div>

Here:

- \\(\varepsilon_j(\omega)\\) is the complex relative dielectric function along principal direction \\(j\\).
- \\(\varepsilon_{\infty,j}\\) is the background electronic dielectric response.
- \\(\nu\\) labels infrared-active optical phonons.
- \\(S_{j\nu}\\) is the oscillator-strength parameter for mode \\(\nu\\) along direction \\(j\\), with units of angular frequency squared.
- \\(\omega_{\mathrm{TO},\nu}\\) is the transverse optical phonon angular frequency.
- \\(\gamma_\nu\\) is the damping rate.
- \\(\omega\\) is the driving angular frequency.

The oscillator strength is determined by the mode-effective charge, which we discussed yesterday.

### What happens as the excitation frequency increases?

At frequencies substantially below a phonon resonance, the ions respond approximately in phase with the electric field.

Near resonance, the ionic response becomes large and develops a substantial phase lag.

Above resonance, the displacement becomes increasingly out of phase with the driving field.

The resulting ionic polarization can oppose the applied field strongly enough that the real part of the dielectric function becomes negative.

This produces a Reststrahlen band.

### Why is the Reststrahlen band associated with LO and TO phonons?

In a simple, low-loss bulk polar dielectric, the transverse optical frequency corresponds to a pole of the dielectric response.

The longitudinal optical frequency corresponds to a zero of the relevant dielectric function.

Between these frequencies, its real part is negative.

The longitudinal optical frequency is higher because a longitudinal ionic displacement generates a macroscopic electric field that contributes an additional restoring force.

This is the electrostatic origin of LO–TO splitting.

For a material with multiple infrared-active modes, the dielectric function may contain several resonances and zero crossings. Damping also shifts the precise boundaries of the frequency intervals where its real part is negative.

---

## 3. Why a negative dielectric function changes electromagnetic propagation

Consider a plane electromagnetic wave in a homogeneous dielectric.

Its allowed wavevector depends on the material's dielectric response.

In an ordinary transparent dielectric, the real part of the permittivity is positive.

The material supports propagating electromagnetic waves with real wavevectors.

Now suppose the relevant dielectric component becomes negative.

The corresponding electromagnetic wave may acquire an imaginary wavevector component.

Its amplitude then decays exponentially in that direction.

This is the origin of evanescent electromagnetic fields.

### The connection to infrared reflection

A bulk polar crystal can exhibit strong reflection within a Reststrahlen band.

The incident electromagnetic field drives the ionic polarization, but the resulting dielectric response prevents the corresponding propagating bulk wave from carrying energy into the material in the usual way.

The field is largely reflected, apart from absorption and possible coupling to other allowed modes.

This is the physical origin of the characteristic high-reflectivity Reststrahlen region.

### What happens at an interface?

An interface between a material with negative permittivity and a surrounding dielectric with positive permittivity can support a surface-bound electromagnetic mode.

Its field decays away from the interface.

When the negative dielectric response originates from an optical phonon, the resulting mode is a surface phonon polariton.

This is closely analogous to a surface plasmon polariton, except that the resonant polarization is primarily ionic rather than electronic.

The existence and dispersion of the surface mode depend on the dielectric functions and boundary conditions.

Anisotropic materials introduce additional possibilities because different field components experience different dielectric responses.

---

## 4. How anisotropy produces hyperbolic dispersion

Consider hBN with its c axis along the laboratory z direction.

For an extraordinary electromagnetic wave propagating in a homogeneous uniaxial medium, the dispersion relation is

<div class="equation">

\[
\boxed{
\frac{k_x^2+k_y^2}{\varepsilon_{\perp}(\omega)}
+
\frac{k_z^2}{\varepsilon_{\parallel}(\omega)}
=
\frac{\omega^2}{c^2}
}
\]

</div>

Here:

- \\(k_x\\) and \\(k_y\\) are the in-plane wavevector components.
- \\(k_z\\) is the out-of-plane wavevector component.
- \\(\varepsilon_{\parallel}\\) is the in-plane dielectric function.
- \\(\varepsilon_{\perp}\\) is the out-of-plane dielectric function.
- \\(\omega\\) is the electromagnetic angular frequency.
- \\(c\\) is the speed of light in vacuum.

For the following geometrical discussion, we neglect absorption and treat the permittivities as real.

This relation describes the allowed wavevectors of the extraordinary wave in the bulk medium.

### Case A: Both dielectric components are positive

Suppose both the in-plane and out-of-plane dielectric functions are positive.

The constant-frequency surface in wavevector space is an ellipsoid.

The electromagnetic wave can propagate along different directions, with direction-dependent phase velocities.

The anisotropy changes the shape of the surface but leaves it closed.

### Case B: The dielectric components have opposite signs

Now suppose the in-plane dielectric function is positive while the out-of-plane component is negative.

The two wavevector terms have opposite signs.

The constant-frequency surface becomes a hyperboloid.

It is an open surface.

This means that the ideal local electromagnetic dispersion permits wavevectors much larger than the free-space photon wavevector.

This is the origin of **hyperbolic dispersion**.

The ability to support large wavevectors is especially important because large wavevectors correspond to short spatial wavelengths.

Thus, hyperbolic materials can support deeply subwavelength electromagnetic excitations.

In real materials, damping, nonlocality, and microscopic structure limit the physically accessible wavevectors.

---

## 5. Type-I and type-II hyperbolic dispersion

There are two possible sign combinations for a uniaxial material.

### Type-I hyperbolic response

The in-plane permittivity is positive, and the out-of-plane permittivity is negative.

This produces a two-sheet hyperboloid in the ideal bulk dispersion.

### Type-II hyperbolic response

The in-plane permittivity is negative, and the out-of-plane permittivity is positive.

This produces a one-sheet hyperboloid.

Both cases support high-wavevector extraordinary electromagnetic modes.

Their propagation characteristics differ because the signs of the dielectric components are reversed.

### hBN supports both types

This is one of the most useful properties of hBN.

| Property | Lower Reststrahlen band | Upper Reststrahlen band |
|---|---|---|
| Approximate frequency range | 760–825 cm⁻¹ | 1360–1610 cm⁻¹ |
| Dominant optical phonon | Out-of-plane | In-plane |
| In-plane permittivity | Positive | Negative |
| Out-of-plane permittivity | Negative | Positive |
| Hyperbolic classification | Type I | Type II |

The frequency boundaries depend on the sample and dielectric parameters.

The two bands arise from different atomic displacement directions.

The lower-frequency band is associated with the out-of-plane infrared-active phonon.

The upper-frequency band is associated with the in-plane infrared-active phonon.

**The hyperbolic classification is determined by which principal dielectric component becomes negative.**

Caldwell and colleagues experimentally demonstrated both types of hyperbolic response in hBN nanostructures in 2014. [Nature](https://www.nature.com/articles/ncomms6221)

---

## 6. Why hyperbolic materials support large wavevectors

This is worth understanding geometrically.

For a conventional isotropic dielectric, the constant-frequency surface is a sphere.

At a fixed frequency, the allowed wavevector magnitude is fixed by the refractive index.

For an anisotropic dielectric with positive principal permittivities, the corresponding surface is an ellipsoid.

Its extent remains finite.

For a hyperbolic material, the constant-frequency surface is open.

Increasing one wavevector component can be accompanied by an increase in another component while preserving the dispersion relation.

This permits large wavevector magnitudes at a fixed frequency.

### A concrete numerical example

Consider infrared light with a free-space wavelength of approximately 6.7 µm, corresponding to a wavenumber near 1500 cm⁻¹.

Suppose a confined phonon polariton in an hBN structure has an in-plane wavelength of 200 nm.

Its in-plane wavevector is approximately 33 times larger than the free-space photon wavevector.

This is a confinement factor of approximately 33.

The precise value depends on the material thickness, dielectric environment, frequency, and polariton branch.

### Why does the wavelength become so small?

The electromagnetic field is strongly coupled to the resonant ionic polarization.

The resulting collective excitation has a dispersion substantially different from the free-space light line.

Within a hyperbolic band, the anisotropic dielectric response permits solutions with large in-plane momentum.

The polariton can therefore accumulate phase much more rapidly across the sample than a free-space photon of the same frequency.

This is the physical basis of subdiffractional phonon-polariton propagation.

---

## 7. Phase propagation and energy propagation can point in different directions

There is another important consequence of hyperbolic dispersion.

In an isotropic material, the wavevector and energy-flow direction are parallel.

In an anisotropic material, they generally differ.

The wavevector is perpendicular to surfaces of constant phase.

The group velocity is determined by the gradient of the dispersion relation with respect to wavevector.

In a low-loss medium, the group-velocity direction is closely related to the direction of electromagnetic energy transport.

### Visualizing the difference

Imagine a constant-frequency surface in wavevector space.

The wavevector identifies a point on that surface.

The group velocity points normal to the surface at that point.

For a spherical surface, the normal is radial.

For a hyperbolic surface, the normal can point in a substantially different direction from the wavevector.

This produces highly directional energy propagation.

In real space, hyperbolic polaritons can therefore form narrow, ray-like propagation patterns.

Their propagation directions depend on the dielectric anisotropy and excitation frequency.

### Why does this matter experimentally?

Suppose a near-field tip launches a broad distribution of in-plane wavevectors.

In a strongly anisotropic material, the energy associated with those wavevectors may preferentially propagate along particular directions.

The resulting near-field image can exhibit directional interference fringes or ray-like patterns.

The orientation of these patterns provides information about the polariton dispersion.

However, the direction of energy flow and the direction of the phase wavevector must be distinguished when interpreting the images.

---

## 8. From bulk hyperbolic waves to polaritons in thin hBN flakes

The bulk dispersion relation describes electromagnetic propagation in a homogeneous, effectively infinite material.

A thin hBN flake introduces interfaces at its upper and lower surfaces.

The electromagnetic field must satisfy boundary conditions at both interfaces.

These conditions restrict the allowed field distributions.

The resulting modes are guided or confined polaritonic branches.

### What does thickness do?

Consider an hBN slab surrounded by dielectric media.

The electromagnetic field can reflect internally between the upper and lower interfaces.

Only particular combinations of frequency, in-plane wavevector, and out-of-plane field profile satisfy the boundary conditions.

The slab therefore supports discrete guided-mode branches.

The number and dispersion of these branches depend on thickness.

Thicker flakes can support more branches over a given spectral range.

Thinner flakes generally modify the allowed in-plane wavevectors and field confinement.

The exact trends depend on the hyperbolic band and the mode order.

### A useful analogy

Imagine a waveguide in which the field must reproduce itself after repeated propagation and reflection between boundaries.

The allowed transverse field patterns become quantized.

For hyperbolic hBN, the unusual bulk dispersion allows these guided modes to possess very large in-plane wavevectors.

This produces strongly confined phonon polaritons.

### What does the surrounding environment change?

The substrate and superstrate determine the electromagnetic boundary conditions.

Changing the substrate dielectric function can therefore modify the polariton dispersion.

This can occur even when the intrinsic hBN phonon frequencies remain nearly unchanged.

This distinction will become important when comparing bare hBN with graphene/hBN and other heterostructures.

---

## 9. How are hyperbolic phonon polaritons measured?

The large wavevector of a confined phonon polariton creates an experimental challenge.

A free-space infrared photon has much less in-plane momentum than a strongly confined polariton at the same frequency.

Efficient excitation therefore requires a mechanism that supplies additional momentum.

### Near-field excitation

A sharp metallic tip can generate a highly localized electromagnetic field.

Spatial localization produces a broad wavevector distribution.

The tip can therefore excite polaritons with in-plane momenta much larger than those accessible through direct far-field illumination.

This is the basis of Scattering-type scanning near-field optical microscopy, or s-SNOM.

### What appears in the image?

A tip-launched polariton propagates across the sample.

When it reaches an edge or another scattering feature, part of the field can reflect.

The reflected polariton interferes with the field associated with the tip and the incident excitation.

As the tip scans, the detected near-field amplitude and phase vary spatially.

This produces interference fringes.

For a simple tip-launched, edge-reflected geometry, the fringe spacing is approximately half the polariton wavelength.

Other launching and detection geometries can produce different fringe periodicities.

### What can we extract?

From frequency-resolved near-field images, we can estimate the polariton wavevector.

Repeating the measurement at different infrared frequencies allows us to reconstruct a dispersion relation.

The decay of the fringes provides information about propagation losses, although extracting an intrinsic damping rate requires accounting for the launching and detection geometry.

This is how an optical microscope can provide information about electromagnetic modes with wavelengths far below the diffraction limit.

---

## 10. Introducing α-MoO₃: Hyperbolicity within the atomic plane

hBN is a uniaxial material.

Its two in-plane principal dielectric components are approximately equal.

Now consider α-MoO₃.

Its orthorhombic crystal structure produces different dielectric responses along its three principal crystallographic directions.

It is therefore a biaxial material.

Importantly, the two in-plane dielectric components are different.

### Why is this significant?

At certain infrared frequencies, one in-plane dielectric component can be negative while the other is positive.

This produces strongly anisotropic in-plane polariton propagation.

The corresponding in-plane polariton isofrequency contours can become hyperbolic.

As a result, polariton energy propagates preferentially along particular crystallographic directions.

### What would an s-SNOM image look like?

In an approximately isotropic in-plane material, a localized source can launch polaritons with similar propagation characteristics in different azimuthal directions.

The resulting wavefronts may appear approximately circular.

In α-MoO₃, the polariton dispersion depends strongly on the in-plane propagation direction.

The resulting wavefronts can be highly elongated or exhibit directional ray-like propagation.

Ma and colleagues experimentally demonstrated this behavior using infrared nano-imaging and nano-spectroscopy.

They observed both elliptical and hyperbolic in-plane polariton dispersion in α-MoO₃, with polariton wavelengths up to approximately 60 times smaller than the free-space wavelength. [Nature](https://www.nature.com/articles/s41586-018-0618-9)

### Why is this important for twisted heterostructures?

Imagine stacking two α-MoO₃ flakes.

Each has its own in-plane dielectric principal axes.

Now rotate one flake relative to the other.

The two dielectric tensors have different orientations in the laboratory frame.

The electromagnetic fields supported by the layers can couple across their interface.

Their combined dispersion depends on the relative angle between the principal axes.

This provides a direct mechanism for twist-dependent polariton propagation.

The situation differs from twisted hBN, whose macroscopic in-plane dielectric response is approximately rotationally symmetric.

In twisted α-MoO₃, the relative rotation directly changes the orientation of the dielectric anisotropy.

This will be central to our later discussion of twist-tunable polaritonic modes.

---

## 11. Today's principal interpretive pitfall

### Misconception: A hyperbolic dielectric tensor guarantees an experimentally observable, long-lived, highly confined polariton.

The opposite signs of the principal permittivities establish hyperbolic bulk dispersion within the local, low-loss approximation.

The experimentally accessible polariton modes also depend on material geometry, interfaces, and damping.

For example, a thin film supports guided branches whose dispersion is determined by electromagnetic boundary conditions.

A mode may possess a large wavevector but experience substantial damping.

Its propagation length may therefore be short.

Conversely, a less strongly confined mode may propagate farther.

### Three quantities to keep separate

**Confinement:** How much larger is the polariton wavevector than the free-space photon wavevector?

**Propagation length:** Over what distance does the polariton amplitude or intensity decay?

**Lifetime:** Over what time scale does the polariton excitation lose coherence or energy?

These quantities are related through the mode dispersion and damping.

However, they are distinct experimental observables.

A large wavevector does not automatically imply a long lifetime.

A narrow resonance does not uniquely determine the spatial propagation length without information about the dispersion.

This distinction becomes particularly important when comparing different materials or evaluating claims of unusually low-loss polaritons.

---

## 12. Research exercise: Interpreting two infrared measurements

Imagine that you have an hBN flake on a SiO₂ substrate.

You measure its infrared response in two spectral regions.

### Observation A

At 780 cm⁻¹, the out-of-plane dielectric component is negative, while the in-plane component is positive.

**Question:** What type of hyperbolic response should the material exhibit?

**Answer:** Type I.

The negative out-of-plane dielectric response produces a two-sheet hyperbolic isofrequency surface in the ideal bulk approximation.

The relevant infrared resonance originates primarily from the out-of-plane optical phonon.

### Observation B

At 1500 cm⁻¹, the in-plane dielectric component is negative, while the out-of-plane component is positive.

**Question:** What changes?

**Answer:** The material exhibits type-II hyperbolic response.

The corresponding isofrequency surface has a different geometry.

The dominant dielectric resonance originates from the in-plane optical phonon.

### Observation C

An s-SNOM experiment at 1500 cm⁻¹ reveals interference fringes with a spacing of approximately 100 nm.

**Question:** What polariton wavelength would you initially infer?

**Answer:** Approximately 200 nm, assuming the fringes arise from interference between a tip-launched polariton and its reflection from an edge.

This would correspond to a confinement factor of approximately 33 relative to the free-space wavelength at 1500 cm⁻¹.

The assignment should be checked against the launching geometry and the calculated polariton dispersion.

### Observation D

You replace the SiO₂ substrate with a different dielectric.

The near-field fringe spacing changes, but the principal infrared phonon resonance of hBN remains nearly unchanged.

**Question:** What is the most likely explanation?

**Answer:** The electromagnetic boundary conditions have changed.

The substrate modifies the guided polariton dispersion.

The underlying optical phonon frequency can remain approximately constant while the polariton wavevector changes.

This provides a useful experimental way to distinguish changes in intrinsic lattice dynamics from changes in electromagnetic confinement.

---

## 13. Two papers for today's briefing

### Paper 1 — Experimental demonstration of hyperbolic polaritons in hBN

**Caldwell et al., “Sub-diffractional volume-confined polaritons in the natural hyperbolic material hexagonal boron nitride.”**

*Nature Communications* **5**, 5221 (2014).

[Read the paper — DOI: 10.1038/ncomms6221](https://www.nature.com/articles/ncomms6221)

**Why this paper matters**

This paper provides an experimental demonstration of both type-I and type-II hyperbolic phonon-polariton resonances in hBN.

The authors fabricate hBN nanocones and measure their infrared resonances.

They identify multiple confined polaritonic modes in both Reststrahlen bands.

The observed dependence of the resonances on nanocone geometry, polarization, and excitation conditions supports the hyperbolic-mode interpretation.

The paper is particularly useful for understanding how the sign of the dielectric anisotropy changes the electromagnetic mode structure.

**Research question:** Why does reversing the signs of the in-plane and out-of-plane permittivities change the relationship between polariton resonance frequency and mode order?

### Paper 2 — In-plane hyperbolic polaritons in α-MoO₃

**Ma et al., “In-plane anisotropic and ultra-low-loss polaritons in a natural van der Waals crystal.”**

*Nature* **562**, 557–562 (2018).

[Read the paper — DOI: 10.1038/s41586-018-0618-9](https://www.nature.com/articles/s41586-018-0618-9)

**Why this paper matters**

This study demonstrates highly anisotropic phonon-polariton propagation in α-MoO₃.

The authors use infrared near-field microscopy and spectroscopy to visualize confined polaritons.

They identify both elliptical and hyperbolic in-plane dispersion and measure strong confinement and relatively long polariton lifetimes.

The results establish α-MoO₃ as a platform for directional infrared nanophotonics.

For today's briefing, focus on the relationship between the crystal's in-plane dielectric tensor and the propagation directions observed in the near-field images.

**Research question:** How does the in-plane polariton propagation pattern change as the excitation frequency crosses from an elliptic to a hyperbolic dispersion regime?

---

## 14. What you should retain

The dielectric tensor connects the microscopic polarization response of a crystal to the propagation of electromagnetic fields.

Infrared-active optical phonons produce resonances in the dielectric tensor.

Near these resonances, the real part of a dielectric component can become negative.

In an anisotropic material, different principal components can have opposite signs.

This produces hyperbolic electromagnetic dispersion.

The open isofrequency surfaces permit large wavevectors at a fixed frequency, providing a mechanism for strongly confined phonon polaritons.

In hBN, the out-of-plane and in-plane optical phonons generate two distinct Reststrahlen bands.

The lower band supports type-I hyperbolic response.

The upper band supports type-II hyperbolic response.

The electromagnetic modes of thin hBN flakes depend additionally on thickness, substrate, and boundary conditions.

Near-field microscopy can access their large momenta and reveal their dispersion through spatial interference patterns.

In α-MoO₃, the dielectric response is strongly anisotropic within the atomic plane.

This produces directional in-plane polariton propagation and creates opportunities for controlling electromagnetic modes through relative layer rotation.

**The central principle is that the phonons determine the frequency-dependent dielectric tensor, while the dielectric tensor and electromagnetic boundary conditions determine the polariton dispersion.**

---

## Next briefing — Tuesday, 27 October 2026

### Morning Physics Briefing 11: Phonon-Polariton Dispersion in Thin Films — Why Thickness Changes the Wavelength

Tomorrow we will examine how electromagnetic boundary conditions convert the bulk hyperbolic dispersion into discrete polariton branches in thin van der Waals crystals.

Our central question will be:

**Why does changing the thickness of an hBN flake modify the polariton wavelength, even when its optical phonon frequencies remain essentially unchanged?**

We will examine guided-mode quantization, polariton momentum, confinement, group velocity, and damping.

We will also discuss how substrate dielectric screening modifies the dispersion and how near-field interference measurements can distinguish different polariton branches.

This will prepare us for the subsequent briefing on biaxial dielectric tensors, directional propagation, and twist-tunable hyperbolic polaritons.
