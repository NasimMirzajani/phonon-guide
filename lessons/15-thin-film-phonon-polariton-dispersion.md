---
layout: default
lesson_number: 15
title: "Phonon-Polariton Dispersion in Thin Films: Why Thickness Changes the Wavelength"
short_title: "Thin-Film Phonon-Polariton Dispersion"
section: "Week 3 — Polaritons in Anisotropic Layered Media"
read_time: "9–10 min"
date: 2026-10-27
permalink: /lessons/15-thin-film-phonon-polariton-dispersion/
---

# Morning Physics Briefing 11

## Phonon-Polariton Dispersion in Thin Films: Why Thickness Changes the Wavelength

Tuesday, 27 October 2026 · Week 3 — Polaritons in Anisotropic Layered Media · Reading time: 9–10 minutes

**Today's central question:** Why can two hBN flakes with identical optical phonon frequencies support phonon polaritons with dramatically different wavelengths, simply because one flake is thinner?

Yesterday, we established how the dielectric tensor determines the allowed electromagnetic wavevectors in anisotropic materials. Within the Reststrahlen bands of hBN, the in-plane and out-of-plane permittivities have opposite signs, producing hyperbolic dispersion.

Today, we introduce finite thickness. The upper and lower interfaces of a flake impose electromagnetic boundary conditions that select discrete polariton branches from the bulk hyperbolic dispersion.

This leads to a powerful result: the polariton wavelength can scale approximately linearly with flake thickness, even when the underlying optical phonon resonance remains unchanged.

We will connect this result to guided-mode quantization, group velocity, damping, and near-field measurements, using hBN and graphene/hBN as examples.


![Original schematic: Phonon-Polariton Dispersion in Thin Films: Why Thickness Changes the Wavelength]({{ '/assets/briefing15/slab-thickness-guided-modes.svg' | relative_url }})

*Figure: Original conceptual illustration; not reproduced from a source paper.*

## 1. Start with the bulk dispersion

Consider a homogeneous hBN crystal with its atomic layers in the xy plane and its crystallographic c axis along z.

For an extraordinary electromagnetic wave, the bulk dispersion relation is

<div class="equation">

\[
\boxed{ \frac{q^2}{\varepsilon\_\perp(\omega)} + \frac{k_z^2}{\varepsilon\_\parallel(\omega)} = \frac{\omega^2}{c^2} }
\]

</div>

Here, \\(q\\) is the magnitude of the in-plane wavevector, \\(k_z\\) is the out-of-plane wavevector, \\(\varepsilon\_\parallel\\) and \\(\varepsilon\_\perp\\) are the relative in-plane and out-of-plane permittivities, \\(\omega\\) is the electromagnetic angular frequency, and \\(c\\) is the vacuum speed of light.

Within a hyperbolic band, the two permittivities have opposite signs.

This allows both \\(q\\) and \\(k_z\\) to become large while still satisfying the dispersion relation.

At a fixed frequency, the bulk crystal therefore supports a continuous range of allowed wavevector combinations.

### What happens when the crystal has finite thickness?

Imagine cutting a slab of thickness \\(d\\) from this bulk crystal.

The material now has an upper and a lower interface.

An electromagnetic wave propagating inside the slab encounters these boundaries and can undergo reflection.

The upward- and downward-propagating field components interfere.

Only particular field distributions satisfy the electromagnetic boundary conditions at both surfaces.

The continuous bulk solutions become a set of discrete guided-mode branches, each with a different field profile across the slab.

This is the origin of thickness-dependent phonon-polariton dispersion.

## 2. Guided-mode quantization: The physical picture

Conceptual ray representation of a hyperbolic guided mode. The field accumulates phase as it travels between the upper and lower interfaces. The actual mode is a coherent electromagnetic field distribution, with reflections and interference selecting the allowed wavevectors.

Imagine following one electromagnetic field component as it propagates through the slab.

It accumulates phase while traveling from one interface to the other.

Reflection at each interface adds another phase shift.

For a self-consistent guided mode, the field must reproduce its phase after a complete round trip.

In the lossless ray approximation, this condition can be expressed as

<div class="equation">

\[
\boxed{ 2k_zd+\phi\_{\mathrm t}+\phi\_{\mathrm b}=2\pi m }
\]

</div>

Here, \\(d\\) is the slab thickness, \\(\phi\_{\mathrm t}\\) and \\(\phi\_{\mathrm b}\\) are the reflection phase shifts at the top and bottom interfaces for the internal wave, and \\(m\\) is an integer labeling the allowed phase orders.

The reflection phases depend on the permittivities of the slab and surrounding media, as well as frequency and wavevector. The exact guided modes are obtained by solving Maxwell's boundary conditions, including field continuity and evanescent decay outside the slab.

### Why does this quantize the polariton wavevector?

For a particular frequency, the dielectric tensor fixes the relationship between the in-plane and out-of-plane wavevector components.

The boundary condition then selects particular values of \\(k_z\\).

Because \\(k_z\\) and \\(q\\) are linked through the bulk dispersion, selecting \\(k_z\\) also selects \\(q\\).

The result is a discrete set of allowed in-plane polariton wavevectors at each frequency.

Each allowed solution corresponds to a guided polariton branch.

## 3. Why thinner flakes produce shorter polariton wavelengths

Now consider the strongly confined regime, where the in-plane polariton wavevector is much larger than the free-space photon wavevector.

In this regime, the bulk dispersion approximately fixes the ratio between the in-plane and out-of-plane wavevector components at a given frequency.

Meanwhile, the guided-mode condition requires the out-of-plane phase accumulation to remain compatible with the slab thickness.

If we decrease the thickness while retaining the same mode order and approximately the same reflection phases, the required out-of-plane wavevector increases.

The in-plane wavevector increases with it.

Since wavelength is inversely proportional to wavevector, the in-plane polariton wavelength decreases.

This gives the approximate scaling: at fixed frequency and branch, polariton wavelength is proportional to slab thickness.

Illustrative thickness scaling at fixed frequency

hBN slab thickness

## 30 nm

Polariton wavelength

# 314 nm

In-plane wavevector

# 20.0 µm⁻¹

Idealized inverse-thickness scaling, normalized to q = 20 µm⁻¹ at d = 30 nm. This demonstrates the scaling mechanism, rather than a calculated dispersion for a specific hBN frequency or substrate.

The experimental importance of this result was demonstrated by Dai and colleagues in 2014.

Using infrared nanoimaging, they measured phonon polaritons in hBN flakes of different thicknesses and established a thickness-dependent dispersion scaling that persisted down to a few atomic layers.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://dspace.mit.edu\&sz=32)

MIT Open Scholarship



### Where does the approximation break down?

The scaling is most reliable when the dielectric response is approximately bulk-like, the mode is strongly confined, and the reflection phases do not vary substantially over the thickness range being compared.

At monolayer thicknesses, changes in intrinsic phonon frequencies and two-dimensional screening can become important. The appropriate electromagnetic description may also be more naturally expressed through a sheet susceptibility than a bulk dielectric slab.

## 4. Why several polariton branches can exist at the same frequency

Return to the guided-mode condition.

Different integers \\(m\\) correspond to different possible phase accumulations across the slab.

Each solution has a different out-of-plane field distribution and a corresponding in-plane wavevector.

This produces a family of polariton branches.

The lowest-order branch typically has the simplest transverse field profile.

Higher-order branches contain additional oscillations across the thickness.

### How does this relate to ordinary optical waveguides?

In a conventional dielectric waveguide, guided modes also have different transverse field distributions.

Their propagation constants differ because the boundary conditions select different allowed transverse wavevectors.

The same general wave mechanics applies to hyperbolic slabs.

The difference is the underlying anisotropic dispersion.

In a hyperbolic medium, large in-plane and out-of-plane wavevectors can coexist at a fixed frequency, allowing guided branches with extremely short in-plane wavelengths.

### What would multiple branches look like experimentally?

Suppose an infrared near-field tip excites two polariton branches at the same frequency.

Each branch has a different in-plane wavelength.

The detected near-field signal may therefore contain multiple spatial oscillation periods.

If the branches are sufficiently separated in momentum, a spatial Fourier transform can reveal multiple peaks.

This is particularly useful because the relative excitation strengths depend on the tip field distribution and the electromagnetic mode profiles.

Some guided branches may exist but couple very weakly to the experimental excitation.

Dai and colleagues demonstrated multimode waveguiding and polaritonic focusing in hBN using near-field imaging in 2015.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://epub.ub.uni-muenchen.de\&sz=32)

Open Access LMU



## 5. How the substrate changes the dispersion

Now consider two hBN flakes of identical thickness.

One is suspended in air.

The other lies on a SiO₂ substrate.

The intrinsic hBN dielectric tensor may be nearly identical in the two cases, but the electromagnetic boundary conditions differ.

At the lower interface, the reflected field depends on the substrate permittivity.

Changing that permittivity changes the reflection phase and the field distribution outside the slab.

The guided-mode condition is consequently modified.

The allowed in-plane polariton wavevector can shift.

### What if the substrate has its own infrared phonons?

SiO₂ has infrared-active optical phonons and corresponding dielectric resonances.

Near those resonances, its dielectric function can vary strongly with frequency.

The electromagnetic fields associated with an hBN polariton may then interact with substrate-supported surface phonon-polariton excitations.

If the modes have compatible polarization and momentum, the coupled system can develop hybridized electromagnetic branches.

This can generate avoided crossings or pronounced changes in polariton dispersion.

### Connection to graphene/hBN

A graphene sheet provides another way to modify the electromagnetic boundary conditions.

Graphene supports a carrier-density-dependent optical conductivity.

When its plasmonic response overlaps the phonon-polariton response of hBN, the coupled structure can support hybrid plasmon–phonon polaritons.

Changing graphene's carrier density can therefore tune the polariton dispersion electrically.

This is an important distinction between mechanical phonon hybridization and electromagnetic mode hybridization.

In the latter case, the polariton wavevector can change substantially while the atomic phonon eigenvectors remain approximately unchanged.

## 6. Phase velocity, group velocity, and propagation length

We now have a family of guided polariton branches.

Each branch describes the relationship between electromagnetic frequency and in-plane wavevector.

Three different properties become important.

### Phase velocity

The phase velocity describes how a constant-phase surface moves along the propagation direction.

For a strongly confined polariton, the in-plane wavevector is large compared with the free-space photon wavevector.

Its in-plane phase velocity is therefore small compared with the vacuum speed of light.

This corresponds to rapid spatial phase accumulation.

### Group velocity

The group velocity is determined by the slope of the dispersion relation.

It describes the motion of a narrowband wavepacket in the lossless approximation.

In a dispersive polaritonic system, the group velocity depends on how rapidly the frequency changes with wavevector.

A branch can possess a large wavevector and a small group velocity.

However, large momentum alone does not determine the group velocity. The dispersion slope must be evaluated.

Near an optical phonon resonance, strong dielectric dispersion can produce slow polaritonic modes.

### Propagation length

A real polariton experiences damping.

At a fixed real excitation frequency, its in-plane wavevector is generally complex.

The real part controls the spatial phase oscillation.

The positive imaginary part controls the exponential amplitude decay along the propagation direction.

For an amplitude proportional to an exponentially damped traveling wave, the amplitude decay length is the inverse of the imaginary wavevector component.

The intensity decay length is half that value.

### Why these distinctions matter

A mode with a very short wavelength can also have a short propagation length.

A slow group velocity may increase the time the excitation spends traversing a given distance, making dissipation particularly consequential.

The polariton's propagation performance therefore depends on both its dispersion and its damping.

This is why experimental studies often report the polariton wavelength together with a propagation length or a dimensionless propagation quality factor.

## 7. What exactly does s-SNOM measure?

Consider a near-field experiment on an hBN flake.

A metallic tip is illuminated by infrared light.

The tip generates a localized electromagnetic field containing a broad distribution of in-plane wavevectors.

These high-momentum components can excite confined polaritons.

The polaritons propagate away from the tip and may scatter from sample edges, defects, or patterned structures.

The scattered electromagnetic field can return to the tip, where it modifies the detected near-field signal.

Schematic of tip-launched polaritons propagating along an hBN flake. Reflections from an edge or other scatterer can generate interference patterns detected by the scanning tip.

### How does fringe spacing relate to polariton wavelength?

For a tip-launched polariton that reflects from a straight edge and returns to the tip, moving the tip by a distance \\(x\\) changes the polariton's round-trip propagation distance by approximately \\(2x\\).

The accumulated phase therefore changes twice as rapidly with tip position as it would for a one-way propagating wave.

This produces fringes with a spacing of approximately half the polariton wavelength.

Other launching geometries can give different relationships.

For example, an edge-launched polariton interfering with a nearly uniform incident optical field can produce a different spatial period.

The experimental geometry must therefore be considered before converting fringe spacing into polariton momentum.

## 8. A quantitative near-field example

Suppose you measure an hBN flake at an infrared wavenumber of 1500 cm⁻¹, within its upper Reststrahlen band.

The corresponding free-space wavelength is approximately 6.67 µm.

You observe near-field fringes separated by 100 nm near a straight sample edge.

Assume the fringes arise from tip-launched, edge-reflected polaritons.

The inferred polariton wavelength is then approximately 200 nm.

The polariton wavevector is approximately 31.4 µm⁻¹, compared with a free-space photon wavevector of approximately 0.94 µm⁻¹.

The confinement factor is therefore about 33.

Free-space wavelength

## 6.67 µm

Polariton wavelength

## 200 nm

Polariton wavevector

## 31.4 µm⁻¹

Confinement factor

## 33×

Illustrative calculation from a hypothetical near-field measurement, assuming a tip-launched, edge-reflected geometry.

Now suppose you measure a second flake that is twice as thick.

In the approximate inverse-thickness regime, the polariton wavevector for the same branch would decrease by a factor of two.

The polariton wavelength would increase by a factor of two.

The fringe spacing would also approximately double.

All of this can occur at the same infrared excitation frequency.

The thickness changes the electromagnetic mode dispersion through its boundary conditions.

## 9. What can go wrong when interpreting a measured dispersion?

Suppose you collect near-field images at ten infrared frequencies.

For each image, you extract a dominant fringe period and convert it into a polariton wavevector.

You then plot frequency against wavevector.

This gives an experimental dispersion curve.

But several complications deserve attention.

First, the dominant excited mode can change with frequency. A tip may couple efficiently to one guided branch at one frequency and to another branch elsewhere.

Second, the fringe pattern can contain contributions from multiple launchers, reflected waves, and guided branches.

Third, the substrate may have strong dielectric dispersion of its own.

Fourth, the finite spatial scan length and limited fringe visibility constrain momentum resolution.

Finally, the observed spatial decay includes geometric spreading, reflection efficiency, and tip-coupling effects as well as intrinsic polariton damping.

### A more rigorous analysis

A useful approach is to calculate the electromagnetic response of the actual layered structure, using the frequency-dependent dielectric tensors and the measured thicknesses.

For planar structures, a transfer-matrix or electromagnetic reflection-coefficient calculation can identify the guided-mode branches.

The polariton modes appear as poles or resonant features of the appropriate momentum-dependent response.

The calculated dispersion can then be compared with the wavevectors extracted from near-field measurements.

For a strongly anisotropic material, the calculation must retain the relevant tensor components.

This is especially important when moving from hBN to biaxial materials such as α-MoO₃.

## 10. Today's interpretive pitfall

### Misconception: A shift in polariton wavelength proves that the underlying optical phonon frequency has changed.

A polariton is an electromagnetic eigenmode of the combined material and its environment.

Its dispersion depends on the dielectric response, thickness, interfaces, and surrounding media.

Changing any of these can modify the polariton wavevector at a fixed frequency.

For example, thinning an hBN slab changes its guided-mode boundary conditions.

Replacing the substrate changes the electromagnetic reflection phase.

Adding graphene introduces a tunable sheet conductivity.

All three can shift the polariton wavelength while leaving the principal hBN optical phonon resonance approximately unchanged.

A useful experimental distinction is to compare the polariton dispersion with independent measurements of the dielectric resonances.

Infrared spectroscopy or ellipsometry can constrain the phonon-related dielectric response.

Near-field microscopy can then determine how that response produces confined electromagnetic modes in the actual geometry.

## 11. Research exercise: Three changes to the same hBN sample

Consider an hBN flake with a thickness of 40 nm, supporting a guided polariton at 1500 cm⁻¹.

Scenario A — You reduce the thickness to 20 nm.

Assuming the same guided branch and the strong-confinement scaling regime, what happens to the polariton wavelength?

It decreases by approximately a factor of two. The out-of-plane phase condition requires a larger wavevector, which produces a larger in-plane momentum.

Scenario B — You retain the thickness but change the substrate.

What determines the resulting change in wavelength?

The substrate modifies the electromagnetic reflection phase and field distribution. The direction and magnitude of the wavelength shift depend on the substrate's complex dielectric function and the relevant guided branch.

Scenario C — You retain the thickness and substrate but add a doped graphene sheet.

What new physical mechanism becomes possible?

The electromagnetic response of graphene can couple to the hBN phonon-polariton field. If the graphene plasmon and hBN polariton branches approach one another in frequency and momentum, their coupling can produce hybridized modes and avoided crossings.

The strength of this interaction depends on carrier density, damping, field overlap, and the dielectric environment.

## 12. Two papers for today's briefing

[Real-space imaging of surface phonon polaritons on hBN. (A) Schematics.... | Download Scientific Diagram](https://images.openai.com/static-rsc-4/IfegvhupV9o2nltmOec3FSMdMQHptBhXbF5v-z-gXSlD6MDyS87c9MM4EOKFIWwL59gW-Ea1IXnoTy3OecXx0TpfTSO9wdoiOn7Mz1X0xmKPszDcoQscXppf7ogaUO4OFVaUZzPNO9btHSYWdOTPv3vdNhdqvWeJbQrcYpMq1jQ?purpose=inline)

Dai et al. — “Tunable Phonon Polaritons in Atomically Thin van der Waals Crystals of Boron Nitride.”

Science 343, 1125–1129 (2014)

The foundational thickness-scaling experiment. The authors use infrared nanoimaging to measure propagating phonon polaritons in hBN and demonstrate how their wavelength depends on the number of layers.

[DOI: 10.1126/science.1246833](https://doi.org/10.1126/science.1246833) · [Open manuscript](https://dspace.mit.edu/entities/publication/6ad9ae2c-27e6-4259-9c52-7051a3318cf2)

[Hyperbolic phonon-polaritons in boron nitride for near-field optical imaging and focusing | Nature Communications](https://images.openai.com/static-rsc-4/J84DLmiaX65mewq6x78VXH7CHftynmCtIrctoD_BqQ3I-GwwLsnEVdlmleO070H5ri3Nd9XIAcIXbzI4qBmrGKR7lQ8FhPSDPk0jelMaRjeRqGn2AUwGDHofDvzrthP1uC2cO5hJm3pPAB4Zx5vzHRg4uZz8RV7LcmrysoNFQkI?purpose=inline)

Dai et al. — “Subdiffractional focusing and guiding of polaritonic rays in a natural hyperbolic material.”

Nature Communications 6, 6963 (2015)

This study visualizes hyperbolic polariton propagation, focusing, and multimode waveguiding in hBN. It is especially useful for connecting the internal electromagnetic field distribution with experimentally measured near-field patterns.

[DOI: 10.1038/ncomms7963](https://doi.org/10.1038/ncomms7963) · [Open-access manuscript](https://epub.ub.uni-muenchen.de/34339/)

For the first paper, focus on the measured wavelength-versus-thickness relationship and its comparison with the electromagnetic model.

For the second, examine how multiple polariton branches contribute to near-field patterns and how the authors distinguish propagation from focusing effects.

## 13. What you should retain

The bulk dielectric tensor determines the relationship between the in-plane and out-of-plane electromagnetic wavevectors.

In a thin slab, the upper and lower interfaces impose boundary conditions that select discrete guided-mode branches.

Each branch has a characteristic out-of-plane field distribution and an associated in-plane polariton wavevector.

Within the strongly confined regime, reducing slab thickness generally increases the in-plane wavevector and decreases the polariton wavelength for a fixed branch and frequency.

The surrounding dielectric environment modifies the reflection phases and therefore the guided-mode dispersion.

Near-field microscopy can access these large wavevectors and reconstruct their frequency dependence from spatial interference patterns.

The measured propagation length depends on damping as well as the mode's electromagnetic field distribution and dispersion.

The central principle is that the optical phonons establish the dielectric response, while the slab geometry determines which polaritonic solutions of Maxwell's equations are supported.

## Next briefing — Wednesday, 28 October 2026

### Morning Physics Briefing 12: Biaxial Dielectric Tensors and Directional Phonon Polaritons

Tomorrow we will move from uniaxial hBN to biaxial α-MoO₃.

Our central question will be:

How does an in-plane anisotropic dielectric tensor produce directional polariton propagation, and what happens when two anisotropic layers are rotated relative to one another?

We will examine in-plane isofrequency contours, the distinction between phase and energy propagation, the rotation of dielectric principal axes, and the electromagnetic coupling of twisted α-MoO₃ layers.

This will establish the foundation for understanding twist-tunable hyperbolic polaritons and the optical consequences of rotating anisotropic van der Waals crystals.
