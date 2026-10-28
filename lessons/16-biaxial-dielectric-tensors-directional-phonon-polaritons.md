---
lesson_number: 16
title: "Biaxial Dielectric Tensors and Directional Phonon Polaritons: How Twist Controls Light Propagation"
short_title: "Biaxial Dielectric Tensors and Directional Polaritons"
section: "Week 3 — Polaritons in Anisotropic Layered Media"
read_time: "9–10 min"
date: 2026-10-28
permalink: /lessons/16-biaxial-dielectric-tensors-directional-phonon-polaritons/
---

# Morning Physics Briefing 12
## Biaxial Dielectric Tensors and Directional Phonon Polaritons: How Twist Controls Light Propagation

*Wednesday, 28 October 2026 · Week 3 — Polaritons in Anisotropic Layered Media · Reading time: 9–10 minutes*

**Today's central question:** How can rotating one van der Waals crystal relative to another transform phonon-polariton propagation from strongly directional hyperbolic waves into nearly diffractionless beams, even when the optical phonon frequencies of the individual crystals remain essentially unchanged?

Yesterday, we examined how the finite thickness of hBN determines the allowed guided polariton branches. Today, we introduce a second means of engineering polariton dispersion: rotating the dielectric principal axes of two anisotropic layers relative to one another.

Our primary example is α-MoO₃, an orthorhombic van der Waals crystal whose infrared dielectric response differs strongly along its two in-plane crystallographic directions.

The central physics involves three steps:

1. Anisotropic optical phonons produce direction-dependent dielectric response.
2. The dielectric tensor produces anisotropic polariton isofrequency contours.
3. Rotating and electromagnetically coupling two layers can change the topology of those contours, thereby controlling the direction of energy propagation.

This provides an important distinction between **atomic moiré engineering** and **electromagnetic twist engineering**.

---

## 1. From uniaxial hBN to biaxial α-MoO₃

Recall that hBN is approximately isotropic within its basal plane.

Its in-plane dielectric response is essentially the same along any azimuthal direction.

Consequently, an ideal, laterally homogeneous hBN slab supports polariton dispersion that is rotationally symmetric within the plane.

The out-of-plane response differs, producing hyperbolicity involving the in-plane and out-of-plane wavevector components.

Now consider α-MoO₃.

**α-MoO₃ has three distinct principal dielectric responses.** Its orthorhombic crystal structure contains strongly anisotropic Mo–O bonding arrangements. The frequencies and oscillator strengths of infrared-active optical phonons therefore depend on their polarization directions.

For the commonly studied (010) surface, the two in-plane axes are [100] and [001], while [010] is the surface normal.

In its crystallographic principal-axis system, the dielectric tensor is diagonal, with distinct components along all three axes.

At certain mid-infrared frequencies, one in-plane component has a negative real part while the other remains positive.

This produces strongly directional phonon-polariton propagation within the atomic plane.

### Why is this possible?

The infrared-active optical phonons polarized along [100] and [001] have different resonance frequencies.

Each contributes primarily to the dielectric response along its associated direction.

As the excitation frequency passes through these resonances, the real parts of the two dielectric components can change sign at different frequencies.

Consequently, the electromagnetic response can be metallic-like along one crystallographic direction and dielectric-like along the perpendicular direction.

This anisotropy creates the conditions for in-plane hyperbolic phonon polaritons.

---

## 2. The most useful concept: The isofrequency contour

To understand directional propagation, imagine plotting the allowed in-plane polariton wavevectors at one fixed frequency.

The resulting curve in reciprocal space is called an **isofrequency contour**, or IFC.

For a polariton propagating in a thin film, we describe its in-plane momentum by the vector \\(\mathbf q=(q_x,q_y)\\).

Different points on the IFC correspond to different propagation wavevectors at the same frequency.

![Schematic of closed elliptical and open hyperbolic isofrequency contours]({{ '/assets/briefing12/isofrequency-contours.svg' | relative_url }})

*Figure: Schematic reciprocal-space isofrequency contours. The precise shape of a thin-film polariton contour follows from the electromagnetic boundary conditions, including film thickness and substrate response.*

### Closed contours

If the IFC is approximately circular, polariton propagation is nearly isotropic.

An elliptical contour indicates anisotropy: the allowed wavevector magnitude depends on direction.

However, the contour remains closed.

### Open contours

A hyperbolic IFC consists of open branches.

The allowed polariton momenta become very large along particular asymptotic directions in the ideal local, low-loss approximation.

This produces strong angular restrictions on propagation and can lead to highly directional polariton energy transport.

Ma and colleagues directly observed elliptical and hyperbolic in-plane phonon-polariton behavior in α-MoO₃ using infrared near-field microscopy. [Ma et al., *Nature* (2018)](https://doi.org/10.1038/s41586-018-0618-9).

---

## 3. Why the wavevector direction differs from the energy-flow direction

This is one of the most important conceptual points in anisotropic polariton physics.

The wavevector describes the direction of phase variation.

The group velocity describes the motion of a narrowband wavepacket.

For a lossless polariton branch, the group velocity is

<div class="equation">
\\[
\\boxed{
\mathbf v_{\mathrm g}
=
\nabla_{\mathbf q}\omega(\mathbf q)
}
\\]
</div>

Here, \\(\omega(\mathbf q)\\) is the polariton angular frequency as a function of in-plane wavevector, and \\(\nabla_{\mathbf q}\\) is the gradient with respect to the two in-plane wavevector components.

The gradient points normal to the isofrequency contour.

Therefore, **the group velocity is perpendicular to the IFC**, whereas the wavevector points from the origin toward a point on that contour.

For an isotropic circular IFC, the two directions coincide.

For an anisotropic elliptical IFC, they generally differ.

For a hyperbolic IFC, they can differ substantially.

![Schematic distinguishing phase wavevector and group velocity]({{ '/assets/briefing12/group-velocity.svg' | relative_url }})

### Physical intuition

Imagine exciting a polariton at a particular point on the hyperbolic contour.

Its phase oscillates along the direction of its wavevector.

However, the energy associated with a narrow wavepacket propagates approximately along the group-velocity direction.

A localized source excites a broad distribution of wavevectors.

If the IFC is strongly hyperbolic, the corresponding group velocities can become concentrated into a restricted set of directions.

The resulting real-space field can form narrow polaritonic rays.

In a low-loss medium, group velocity and energy velocity are closely related. In a lossy system, the precise energy-flow direction is obtained from the electromagnetic Poynting vector.

### Why this matters experimentally

When you observe directional fringes in an s-SNOM image, you must distinguish the phase-front orientation from the energy-propagation direction.

The fringe wavevector is normal to the phase fronts.

The energy flow follows the appropriate polariton group-velocity direction.

These directions can differ significantly in α-MoO₃.

---

## 4. What happens when we rotate the crystal?

Suppose we rotate an α-MoO₃ flake by an in-plane angle \\(\theta\\).

Its intrinsic dielectric properties remain tied to the crystal axes.

But the tensor components expressed in the laboratory coordinate system change.

For a rotation about the surface normal, the laboratory-frame dielectric tensor is

<div class="equation">
\\[
\\boxed{
\boldsymbol{\varepsilon}_{\mathrm{lab}}(\omega,\theta)
=
\mathbf R(\theta)
\boldsymbol{\varepsilon}_{\mathrm{crystal}}(\omega)
\mathbf R^{T}(\theta)
}
\\]
</div>

Here, \\(\boldsymbol{\varepsilon}_{\mathrm{crystal}}\\) is the dielectric tensor in the crystallographic principal-axis frame, and \\(\mathbf R(\theta)\\) is the three-dimensional rotation matrix for an angle \\(\theta\\) about the surface normal. The superscript \\(T\\) denotes matrix transpose.

The tensor is generally no longer diagonal in the laboratory xy coordinates.

Off-diagonal in-plane components appear.

These components describe how an electric field along one laboratory direction can induce a displacement response with a component along the perpendicular laboratory direction.

### Does rotating a single flake change its polariton physics?

In an otherwise rotationally symmetric environment, rotating the entire flake rotates its polariton IFC and corresponding real-space propagation pattern.

The intrinsic dispersion relative to the crystal axes remains unchanged.

Now imagine stacking two flakes with different orientations.

The two dielectric tensors are rotated relative to one another.

Their polaritonic fields overlap and interact.

The combined system can support new hybrid electromagnetic eigenmodes whose dispersion depends on the relative twist angle.

This is where the physics becomes particularly interesting.

---

## 5. Twisted α-MoO₃: Coupling two anisotropic polariton systems

Consider two α-MoO₃ slabs.

Each supports in-plane hyperbolic phonon polaritons at a selected infrared frequency.

When separated, their polariton modes are independent.

When brought close together, their electromagnetic fields overlap.

A polariton associated predominantly with the upper slab can interact with a polariton associated predominantly with the lower slab.

The strength of this interaction depends on the spatial overlap of their fields, their polarization, and their frequency and momentum matching.

### What changes with twist?

At zero relative twist, the principal dielectric axes are aligned.

The individual IFCs have the same orientation.

The electromagnetic coupling produces hybridized branches with dispersion determined by the combined thickness and dielectric environment.

At a finite twist angle, the individual IFCs are rotated relative to one another.

Their wavevector-dependent resonances can approach or intersect at different locations in reciprocal space.

Where compatible modes become nearly degenerate, electromagnetic coupling can produce avoided crossings.

As the angle changes, these avoided crossings reshape the hybrid IFCs.

At particular angles and frequencies, the contour topology can change from open to closed.

This is the physical basis of the twist-induced polaritonic topological transitions observed in α-MoO₃ bilayers.

![Rotated individual IFCs and illustrative hybrid contour]({{ '/assets/briefing12/twist-ifc.svg' | relative_url }})

---

## 6. What does a topological transition mean here?

In this context, topology describes a global geometrical property of the polariton isofrequency contour.

A hyperbolic contour is open.

An elliptical contour is closed.

Changing continuously from one to the other requires a qualitative change in the contour's connectivity.

This is a **Lifshitz-like transition in momentum-space dispersion**.

It is distinct from the topological band phenomena associated with Berry curvature, Chern numbers, or protected edge states.

The relevant property here is the global shape and connectivity of the allowed polariton wavevectors.

### Why can twist change that topology?

Each layer contributes an anisotropic electromagnetic response.

Their relative rotation changes how the individual directional polariton branches interact.

The resulting hybrid modes can reorganize their momentum-space dispersion.

The angle at which a particular transition occurs depends on the excitation frequency, the dielectric tensor, the thicknesses of both slabs, and the surrounding environment.

This is why the transition angle is not a universal property of α-MoO₃.

Hu and colleagues experimentally demonstrated twist-controlled transitions between open and closed polariton IFCs in α-MoO₃ bilayers. [Hu et al., *Nature* (2020)](https://doi.org/10.1038/s41586-020-2359-9).

---

## 7. Photonic magic angles and polariton canalization

One of the most striking consequences of the transition occurs when the polariton IFC develops an extended, nearly flat segment.

Recall that the group velocity points normal to the IFC.

If many different wavevectors lie along a nearly straight segment of the contour, their group velocities point in approximately the same direction.

A localized excitation can therefore launch a distribution of polariton wavevectors whose energy flows together along a narrow path.

This produces **polariton canalization**.

### Why is this useful?

In ordinary diffraction, a spatially confined wavepacket contains a range of transverse wavevectors.

Different wavevector components generally propagate in different directions.

The wavepacket spreads.

Under canalization conditions, a broad set of wavevector components can have nearly parallel group velocities.

Their transverse spreading is strongly reduced.

The result is highly directional, weakly diffracting energy transport.

### What does the magic angle represent?

In the work of Hu and colleagues, a photonic magic twist angle refers to a relative orientation at which the coupled polariton dispersion undergoes a topological transition and supports strong canalization.

The authors demonstrated propagation with subwavelength spatial resolution below one-fortieth of the free-space wavelength. [Hu et al., *Nature* (2020)](https://doi.org/10.1038/s41586-020-2359-9).

The analogy with electronic magic-angle physics is useful because both involve twist-dependent changes in dispersion.

However, the mechanisms differ.

In twisted bilayer graphene, moiré-modified electronic hopping and band interference can generate narrow electronic bands.

In twisted α-MoO₃ slabs, the experimentally demonstrated polariton transition is governed primarily by the electromagnetic coupling of rotated anisotropic polariton modes.

---

## 8. Does this require an atomic moiré superlattice?

This question connects today's material to the previous two weeks.

When two crystalline layers are twisted, an atomic moiré pattern generally arises from the mismatch between their lattice orientations.

Such a pattern can modulate interlayer force constants and influence phonon eigenmodes.

However, the polariton engineering demonstrated in twisted α-MoO₃ slabs can be described through the electromagnetic coupling of two anisotropic layers using their macroscopic dielectric tensors.

The polariton wavelength is typically much larger than the atomic lattice constant.

The electromagnetic field therefore samples an effective dielectric response rather than resolving every atomic registry.

### Two mechanisms of twist control

| Atomic moiré phonon physics | Electromagnetic twist polaritonics |
|---|---|
| Spatially varying interlayer force constants | Rotated anisotropic dielectric tensors |
| Coupling between atomic displacement modes | Coupling between electromagnetic polariton modes |
| Moiré reciprocal vectors connect phonon wavevectors | In-plane momentum and field overlap govern polariton hybridization |
| Reconstruction may modify phonon eigenvectors | Thickness, twist, and dielectric environment modify IFCs |
| Probed by Raman, IR, and lattice dynamics | Probed by s-SNOM, nano-IR, and electromagnetic modeling |

The two mechanisms can coexist in sufficiently thin or strongly reconstructed heterostructures.

Their relative importance depends on the length scales, frequencies, and interlayer interactions.

For the α-MoO₃ slab experiments discussed today, electromagnetic coupling provides the established explanation for the twist-dependent polariton topology.

---

## 9. How would you observe the transition experimentally?

Consider an s-SNOM experiment on a twisted α-MoO₃ bilayer.

You illuminate a metallic AFM tip with infrared light.

The tip supplies the large in-plane momenta needed to excite confined polaritons.

The launched polaritons propagate through the coupled bilayer.

Their interference with scattered or reflected fields produces spatial structure in the detected near-field amplitude and phase.

### What would you expect at different twist angles?

![Conceptual hyperbolic ray, canalized, and elliptical polariton patterns]({{ '/assets/briefing12/polariton-patterns.svg' | relative_url }})

*Figure: Representative schematic near-field polariton patterns: hyperbolic directional rays, canalization, and elliptical wavefronts. Actual images depend on launching geometry, sample thickness, frequency, and scattering boundaries.*

**Hyperbolic regime:** Directional polariton propagation associated with open IFCs.

**Canalization regime:** Concentrated energy propagation along selected directions.

**Elliptical regime:** More broadly distributed propagation directions associated with closed IFCs.

### How would you extract the dispersion?

A two-dimensional Fourier transform of the complex near-field image can reveal the dominant spatial wavevectors.

By repeating the measurement at several frequencies, you can reconstruct the frequency dependence of the IFC.

This is more informative than extracting a single fringe spacing along one direction.

In a strongly anisotropic material, the full two-dimensional momentum distribution is essential for distinguishing open and closed contours.

### An important experimental complication

The observed near-field intensity is weighted by the excitation and detection efficiencies.

A weak signal along a particular direction does not necessarily indicate that no polariton mode exists there.

A rigorous comparison should use a calculated momentum-dependent electromagnetic response, together with a model of the near-field excitation and detection geometry.

---

## 10. Today's interpretive pitfall

### Misconception: A narrow polariton beam proves that the dispersion is flat and that the system is operating at a magic angle.

A narrow near-field beam can result from several mechanisms.

A hyperbolic IFC can concentrate group velocities along preferred directions.

A patterned structure can provide geometric focusing.

An edge or defect can selectively launch particular wavevectors.

A nearly flat IFC can produce canalization by making a broad range of group velocities nearly parallel.

These mechanisms may generate similar real-space intensity distributions.

To establish a photonic magic-angle transition, one should demonstrate the evolution of the polariton dispersion with twist angle and identify the associated change in IFC topology.

The strongest evidence combines spatial near-field imaging with momentum-space analysis and electromagnetic calculations.

**The distinction between directional launching, hyperbolic ray propagation, and canalization is essential when evaluating claims of diffractionless polariton transport.**

---

## 11. Research exercise: Interpreting a twisted α-MoO₃ experiment

Imagine that you fabricate three α-MoO₃ bilayers with different relative orientations.

All have the same individual slab thicknesses and are measured at the same infrared frequency.

### Sample A: Aligned principal axes

The near-field pattern shows strong directional propagation.

A calculation reveals open IFCs.

What is the likely physical regime?

The coupled structure supports hyperbolic polariton modes. The aligned dielectric axes preserve a common set of preferred in-plane directions, although coupling can modify the branches relative to those of isolated slabs.

### Sample B: Intermediate twist angle

The near-field image reveals a narrow beam propagating over a substantial distance.

The calculated IFC contains an extended nearly straight segment.

What mechanism explains the narrow beam?

Polariton canalization. A broad set of wavevectors along the flat IFC segment has nearly parallel group velocities, reducing angular spreading.

### Sample C: Larger twist angle

The near-field pattern becomes more broadly distributed in azimuth.

The calculated IFC is closed.

What has changed?

The hybridized polariton dispersion has undergone a topological transition from an open to a closed contour. The allowed momentum directions and corresponding group velocities have been reorganized by the electromagnetic coupling of the rotated anisotropic layers.

### Additional question

Suppose the Raman-active optical phonon frequencies of the individual layers remain essentially unchanged across all three samples.

Is this consistent with the observed polariton transition?

Yes. The transition can arise through changes in the electromagnetic coupling and boundary conditions of the bilayer. The intrinsic phonon resonances provide the dielectric response, while the relative orientation determines the coupled polariton dispersion.

---

## 12. Two papers for today's briefing

### Paper 1 — Ma et al.

**Ma et al. — “In-plane anisotropic and ultra-low-loss polaritons in a natural van der Waals crystal.”**

*Nature* **562**, 557–562 (2018).

This foundational experiment establishes the strongly anisotropic phonon-polariton response of α-MoO₃. The authors visualize elliptical and hyperbolic propagation using infrared nano-imaging and demonstrate strong confinement and long-lived polaritonic excitations.

[DOI: 10.1038/s41586-018-0618-9](https://doi.org/10.1038/s41586-018-0618-9)

### Paper 2 — Hu et al.

**Hu et al. — “Topological polaritons and photonic magic angles in twisted α-MoO₃ bilayers.”**

*Nature* **582**, 209–213 (2020).

The authors demonstrate twist-dependent transitions between hyperbolic and elliptical polariton IFCs, accompanied by polariton canalization near photonic magic angles. The work directly connects relative dielectric-axis rotation, polariton hybridization, and experimentally observed propagation patterns.

[DOI: 10.1038/s41586-020-2359-9](https://doi.org/10.1038/s41586-020-2359-9) · [Open-access preprint](https://arxiv.org/abs/2004.14217)

For the first paper, focus on the relationship between the dielectric principal axes and the measured near-field propagation directions.

For the second, examine the evolution of the IFC with twist angle. Identify which changes are caused by the rotation of the individual anisotropic responses and which require electromagnetic coupling between the slabs.

---

## 13. What you should retain

Biaxial crystals have different dielectric responses along all three principal crystallographic axes.

In α-MoO₃, the two in-plane components can have opposite signs within particular infrared frequency regions.

This produces strongly anisotropic phonon-polariton dispersion, including open hyperbolic isofrequency contours.

The group velocity is normal to the IFC in the lossless approximation, so the direction of polariton energy transport can differ substantially from its wavevector direction.

Rotating an α-MoO₃ slab rotates its dielectric tensor relative to the laboratory axes.

Stacking two differently oriented slabs allows their polariton modes to couple electromagnetically.

The resulting hybrid dispersion can change topology from open to closed as the twist angle varies.

Near a transition, an extended flat segment of the IFC can produce polariton canalization, allowing a narrow electromagnetic beam to propagate with reduced diffraction.

**The central principle is that twist changes the relative orientation of the dielectric tensors, which changes the electromagnetic coupling and therefore the allowed polariton wavevectors and energy-flow directions.**

This is a powerful form of twist engineering because it can operate through macroscopic electromagnetic interactions, without requiring the microscopic phonon eigenvectors to change substantially.

---

## Next briefing — Thursday, 29 October 2026

### Morning Physics Briefing 13: Interface Phonon Polaritons and Hybrid Modes in van der Waals Heterostructures

Tomorrow we will examine how electromagnetic fields couple across interfaces between different polar materials.

Our central question will be:

**When two materials with different optical phonon resonances are placed in contact, what determines whether their surface and guided polariton modes remain distinct or hybridize?**

We will examine surface phonon polaritons, interface boundary conditions, avoided crossings, field confinement, and oscillator-strength redistribution.

Our concrete examples will include graphene/hBN and heterostructures containing multiple polar dielectric layers.

This will prepare us to distinguish mechanical phonon hybridization from electromagnetic polariton hybridization in multilayer and twisted van der Waals systems.
