---
layout: default
lesson_number: 8
title: "Interlayer Shear and Breathing Modes: Measuring the Mechanical Coupling Between Atomic Layers"
short_title: "Interlayer Shear and Breathing Modes"
section: "Week 2 · Multilayer and twist physics"
read_time: "9–10 min"
permalink: /lessons/08-interlayer-shear-and-breathing-modes/
---

# Morning Physics Briefing 06
## Interlayer Shear and Breathing Modes: Measuring the Mechanical Coupling Between Atomic Layers

**Tuesday, 20 October 2026 | Week 2 — Multilayer and Twist Physics | Reading time: 9–10 minutes**

**Today's central question:** How can two low-frequency vibrations reveal the strength, directionality, and spatial uniformity of the forces holding a van der Waals heterostructure together?

Yesterday, we completed our solid-state foundations by examining dielectric response, LO–TO splitting, and the electrodynamic origin of Reststrahlen bands.

Today, we begin the physics of multilayer structures.

Our first objective is to understand two particularly informative collective vibrations: **interlayer shear modes and layer-breathing modes**.

Unlike the familiar optical phonons of an individual monolayer, these vibrations involve the relative displacement of entire atomic layers. Their frequencies are often only a few tens of inverse centimeters, yet they contain remarkably detailed information about interlayer force constants, stacking configurations, twist angles, and structural relaxation.

The central physical idea is that shear and breathing vibrations probe different curvatures of the interlayer interaction potential.

This distinction will become essential when we investigate moiré reconstruction, interlayer phonon hybridization, and interface modes later this week.

---

## 1. Why interlayer vibrations are unusually informative

Consider an isolated monolayer of MoS₂.

Its conventional optical phonons involve relative motion of molybdenum and sulfur atoms within the layer.

The restoring forces are primarily determined by strong intralayer chemical bonding.

Now place a second MoS₂ monolayer nearby.

The system acquires additional vibrational degrees of freedom.

The two layers can move together, but they can also move relative to one another.

There are three particularly simple relative translations: two in-plane directions and one out-of-plane direction.

The in-plane motions correspond to interlayer shear vibrations.

The out-of-plane motion corresponds to an interlayer breathing vibration.

Because these motions deform the comparatively weak interlayer interaction rather than the strong intralayer bonds, their frequencies are generally much lower than those of intralayer optical phonons.

For many transition-metal dichalcogenide multilayers, the relevant spectral features lie below approximately 50 cm⁻¹.

This makes them experimentally challenging but physically valuable.

A small change in the interlayer potential may produce a measurable change in these low-frequency modes while leaving high-frequency intralayer phonons comparatively unaffected.

**Low-frequency interlayer phonons are therefore sensitive probes of the interface itself, rather than primarily of the chemical bonding within each layer.**

Experiments on few-layer MoS₂ and WSe₂ established that shear and breathing frequencies evolve systematically with layer number and can often be described using a simple nearest-neighbor mechanical model. [Zhao et al. (2013)](https://doi.org/10.1021/nl304169w)

---

## 2. The interlayer potential has different curvatures in different directions

Imagine two atomically flat layers separated by their equilibrium distance.

We can describe their relative configuration using three coordinates: two lateral displacements and one interlayer separation.

The interlayer energy depends on all three.

### Lateral displacement: Shear

Suppose we translate the upper layer slightly along the lower layer.

As the upper layer moves, the relative atomic registry changes.

Sulfur atoms may move toward or away from particular atomic sites in the neighboring layer.

The resulting interaction energy generally varies with lateral displacement.

Near a mechanically stable stacking configuration, the curvature of this energy landscape determines the shear restoring force.

A steep energy minimum produces a relatively high shear frequency.

A shallow energy minimum produces a softer shear vibration.

The shear mode therefore probes the **local resistance to relative sliding**.

This is related to interfacial friction, but the two quantities are not identical.

A phonon frequency measures a small-amplitude, approximately harmonic restoring force.

Macroscopic friction additionally involves dissipation, defects, contact geometry, temperature, and potentially large-amplitude motion across multiple energy barriers.

Consequently, measuring a shear phonon does not directly determine a macroscopic friction coefficient.

### Out-of-plane displacement: Breathing

Now move the layers toward and away from one another.

The interlayer energy changes because attractive interactions compete with short-range repulsion.

Near equilibrium, the curvature of this energy profile determines the breathing restoring force.

A relatively large curvature corresponds to a high breathing frequency.

A smaller curvature corresponds to a softer breathing vibration.

The breathing mode therefore probes the **local stiffness against changes in interlayer separation**.

This is distinct from the total binding energy.

Two interfaces can possess similar binding energies but different curvatures near their equilibrium separations.

Conversely, interfaces with similar breathing frequencies need not have identical binding energies.

### The essential distinction

The shear and breathing modes measure different aspects of the same interlayer interaction.

An interface can resist compression relatively strongly while allowing easy lateral sliding.

This is particularly relevant to twisted structures, where the lateral corrugation of the interaction energy may be strongly reduced even though the layers remain mechanically bound.

---

## 3. A quantitative model for a bilayer

The simplest useful approximation treats each monolayer as a rigid sheet.

We assign each sheet a mass per unit area and connect the two sheets with an effective harmonic spring.

For a heterobilayer, the relative-motion frequency is

<div class="equation">
\[
\boxed{
\omega_{\mathrm{S,B}}^{2}
=
K_{\mathrm{S,B}}
\left(
\frac{1}{\mu_1}
+
\frac{1}{\mu_2}
\right)
}
\]
</div>

Here:

- \\(\omega_{\mathrm{S,B}}\\) is the angular frequency of the shear or breathing vibration.
- \\(K_{\mathrm{S,B}}\\) is the effective interlayer restoring-force constant per unit area for the relevant displacement direction.
- \\(\mu_1\\) and \\(\mu_2\\) are the masses per unit area of the two monolayers.
- The subscripts S and B distinguish shear and breathing motion.

For identical layers, the expression reduces to the familiar result in which the squared frequency is twice the interlayer force constant divided by the mass per unit area of one layer.

The important feature is the separation between **inertia** and **restoring force**.

The measured frequency depends on both.

### A useful thought experiment

Imagine two otherwise comparable bilayers.

In the second sample, the effective shear force constant is 21% larger, while the layer masses are unchanged.

The shear frequency increases by 10%.

Thus, a relatively modest frequency shift can indicate a larger relative change in the corresponding force constant.

However, this inference is valid only if the two measurements correspond to the same vibrational branch and the effective masses are correctly accounted for.

That qualification becomes important when comparing different materials.

---

## 4. Why a MoS₂/WSe₂ heterobilayer is different from MoS₂/MoS₂

Consider a heterobilayer containing one MoS₂ layer and one WSe₂ layer.

The two layers have different atomic masses and different intralayer bonding.

Their masses per unit area are therefore unequal.

In the rigid-layer approximation, the relative vibration is no longer a perfectly symmetric motion in which the two layers have equal displacement amplitudes.

Instead, the lighter layer undergoes a larger displacement amplitude than the heavier layer.

The center of mass remains stationary for the internal relative-motion eigenmode.

This means that even if the interlayer restoring force were identical to that of a MoS₂ homobilayer, the vibrational frequency would generally differ because the effective inertia has changed.

**A lower breathing frequency in one heterostructure does not automatically imply weaker interlayer bonding.**

One must first separate the mass effect from the force-constant effect.

There is an additional complication.

The rigid-layer approximation assumes that the internal atomic structure of each monolayer does not deform during the vibration.

This is often reasonable for low-frequency interlayer modes.

However, if an interlayer vibration approaches the frequency of another phonon with compatible symmetry, the modes can hybridize.

The resulting eigenvectors may contain both rigid-layer motion and internal atomic deformation.

At that point, assigning a single effective interlayer spring constant becomes less straightforward.

This provides our first connection to the phonon-hybridization problem that we will study later in Week 2.

---

## 5. What changes when we add more layers?

A bilayer has one relative shear branch for each independent in-plane polarization and one breathing branch.

A multilayer supports more complicated patterns of collective motion.

Consider four identical layers.

One vibration may involve the upper two layers moving together against the lower two.

Another may involve neighboring layers moving in alternating directions.

A third may contain a more complicated sequence of relative displacements.

Each displacement pattern experiences a different effective restoring force.

Consequently, the multilayer possesses several interlayer vibrational branches.

For a stack of \\(N\\) identical rigid layers with free surfaces and nearest-neighbor coupling, the nonzero frequencies are

<div class="equation">
\[
\boxed{
\omega_{p,\mathrm{S,B}}
=
2\sqrt{\frac{K_{\mathrm{S,B}}}{\mu}}
\sin\left(\frac{p\pi}{2N}\right),
\qquad
p=1,\ldots,N-1
}
\]
</div>

Here:

- \\(N\\) is the number of layers.
- \\(p\\) labels the relative-motion branches.
- \\(\mu\\) is the mass per unit area of one layer.
- \\(K_{\mathrm{S,B}}\\) is the nearest-neighbor shear or breathing force constant per unit area.
- \\(\omega_{p,\mathrm{S,B}}\\) is the corresponding angular frequency.

The model contains \\(N-1\\) nonzero breathing frequencies and \\(N-1\\) shear frequencies for each independent in-plane polarization.

For an in-plane isotropic stack, the two shear polarizations can be degenerate.

Not every branch is necessarily Raman-active.

The optical selection rules depend on crystal symmetry and the displacement pattern.

### What the model predicts

As the number of layers increases, additional interlayer branches appear.

The highest-frequency branches generally approach finite bulk limits.

The lowest-frequency branches become progressively softer as the stack becomes thicker.

This behavior follows directly from the allowed collective displacement patterns.

Some modes involve neighboring layers moving strongly against each other.

Others involve long-wavelength distortions extending across the entire multilayer.

The latter require relatively little restoring energy and therefore have lower frequencies.

The linear-chain model is surprisingly successful for several layered materials.

Zhao and colleagues demonstrated that low-frequency shear and breathing modes in few-layer MoS₂ and WSe₂ could be described using nearest-neighbor force constants that remained approximately consistent across different thicknesses. [Zhao et al. (2013)](https://doi.org/10.1021/nl304169w)

This is a useful result because it allows experimentally measured frequencies to be converted into effective interlayer mechanical parameters.

Nevertheless, the approximation should be tested rather than assumed for strongly reconstructed, strained, or chemically dissimilar interfaces.

---

## 6. Stacking registry changes the mechanical response

We now introduce a structural variable that is central to twisted heterostructures: stacking registry.

Consider two MoS₂ layers with the same relative crystallographic orientation but different lateral translations.

Although their chemical compositions are identical, their interlayer interaction energies can differ.

The equilibrium separation may change slightly.

The lateral energy corrugation may also change.

Consequently, both shear and breathing force constants can depend on stacking.

But they need not respond in the same way.

A change in registry may substantially modify the curvature of the lateral potential while only weakly modifying the curvature with respect to layer separation.

The opposite is also possible.

This is why measuring both modes is more informative than measuring either alone.

### Mechanical coupling versus Raman intensity

There is another important complication.

Changing the stacking registry also changes crystal symmetry.

That modifies the Raman tensors of the interlayer vibrations.

A mode may become much stronger or weaker in Raman spectroscopy without undergoing a correspondingly large frequency shift.

For example, conventional 2H and 3R stacking arrangements of MoS₂ differ in inversion symmetry.

Their vibrational modes therefore obey different optical selection rules.

The observed Raman spectrum reflects both the mechanical eigenfrequencies and the optical coupling to those eigenmodes.

This distinction becomes particularly important in multilayers containing several closely spaced shear branches.

The strongest Raman peak is not necessarily the highest-frequency mode, nor does it necessarily correspond to the mechanically stiffest displacement pattern.

We will examine stacking-dependent selection rules in detail tomorrow.

---

## 7. What twisting does to the shear mode

Now consider a twisted MoS₂ bilayer.

One layer is rotated relative to the other.

The local atomic registry varies across the interface.

At sufficiently large twist angles, a large sample contains many different local stacking environments.

This can reduce the average lateral corrugation of the interlayer interaction energy.

To understand the consequence, imagine translating one layer uniformly across the other.

In an aligned, commensurate bilayer, the entire interface may respond coherently to the translation.

In an incommensurate structure, energy increases in some regions may be partially compensated by decreases elsewhere.

The net restoring force for uniform sliding can become very small.

The coherent shear vibration can therefore soften dramatically.

This connects the physics of interlayer phonons to the concept of structural superlubricity.

However, the analogy has limits.

A real twisted bilayer may undergo atomic reconstruction.

Local regions can relax toward energetically favorable stacking configurations.

Domain walls, defects, finite boundaries, and substrate interactions can pin relative motion.

The effective shear stiffness is therefore not determined by twist angle alone.

**Twist angle controls the geometric registry pattern, but relaxation and pinning determine how that pattern responds mechanically.**

---

## 8. What twisting does to the breathing mode

The breathing mode generally behaves differently.

Even if the lateral registry varies across the interface, the two layers still experience attractive and repulsive forces that determine their equilibrium separation.

The out-of-plane restoring force therefore remains finite.

This means that a twisted bilayer can exhibit a relatively robust breathing vibration even when its coherent shear vibration becomes extremely soft.

This contrast was demonstrated experimentally in twisted bilayer MoS₂.

Huang and colleagues measured low-frequency Raman spectra and compared them with first-principles calculations.

They found strong twist sensitivity near relative orientations of 0° and 60°.

In their samples, phonon frequencies varied by up to approximately 8 cm⁻¹, and Raman intensities varied by factors approaching five.

For intermediate angles around 20°–40°, the low-frequency response was comparatively insensitive to further twisting.

The shear mode became particularly soft in this intermediate-angle regime, while the breathing response remained observable.

Some samples exhibited multiple breathing features, consistent with nonuniform interlayer coupling. [Huang et al. (2016)](https://doi.org/10.1021/acs.nanolett.5b05015)

The important result is not simply that twisting shifts phonon frequencies.

It is that **twisting can affect lateral and out-of-plane interlayer restoring forces very differently**.

This provides a direct experimental signature of the anisotropic mechanical response of a twisted interface.

---

## 9. Connection to moiré reconstruction

At small twist angles, the spatial variation of stacking registry occurs over a relatively long length scale.

The resulting moiré superlattice can produce regions with different local interlayer energies.

If the energetic benefit of favorable stacking exceeds the relevant elastic cost, the layers may reconstruct.

Instead of a smoothly varying registry everywhere, the system can form domains separated by relatively narrow domain walls.

This changes how we should think about interlayer phonons.

A uniform bilayer model assigns one effective shear force constant and one breathing force constant to the interface.

A reconstructed moiré structure may instead possess spatially varying force constants.

The resulting vibrational eigenmodes can involve coherent motion across many domains, relative displacement within particular regions, or motion concentrated near domain walls.

These possibilities are not adequately described by a single rigid-layer spring.

The full dynamical matrix of the relaxed moiré structure may be required.

There is also an important reciprocal-space consequence.

The enlarged moiré unit cell produces a reduced Brillouin zone.

Phonon branches can be folded into this smaller zone, potentially generating additional low-frequency modes.

But **a new Raman peak in a twisted sample is not automatically a moiré-folded phonon**.

It may instead arise from changes in selection rules, local stacking, strain, or interlayer mode hybridization.

We will develop the reciprocal-space description of these effects later this week.

---

## 10. How should the modes be measured?

The most direct experimental technique for many transition-metal dichalcogenide multilayers is ultralow-frequency Raman scattering.

The challenge is that the relevant vibrational frequencies lie very close to the laser line.

Specialized optical filters or spectrometer configurations are therefore needed to suppress elastically scattered light while retaining sensitivity to small Raman shifts.

A useful experiment should record more than peak positions.

**Frequency** provides information about effective restoring forces.

**Intensity and polarization dependence** help identify mode symmetry and Raman activity.

**Linewidth** provides information about damping, disorder, and possible inhomogeneous broadening, although these contributions must be distinguished.

**Spatial mapping** can reveal variations associated with strain, local stacking, bubbles, and structural reconstruction.

**Temperature dependence** can help separate anharmonic effects from static structural inhomogeneity.

For twisted heterostructures, spatial resolution is especially important.

A conventional Raman spot may average over many moiré unit cells.

Consequently, the measured spectrum may represent an effective response rather than the vibrational properties of a single local stacking configuration.

For sufficiently large reconstructed domains, spatially resolved spectroscopy can provide more direct structural information.

For smaller domains, comparison with microscopic calculations becomes particularly important.

---

## 11. Today's principal interpretive pitfall

### Misconception: A missing shear Raman peak proves that the layers are mechanically decoupled.

This conclusion is generally unjustified.

A missing peak may have several explanations.

The shear vibration may have softened below the instrument's accessible frequency range.

Its Raman tensor may have become very small because of the stacking symmetry.

The mode may be broadened by disorder or spatially varying coupling.

Or the vibration may have hybridized with other modes, redistributing its Raman intensity.

Furthermore, a weak lateral restoring force does not imply weak out-of-plane binding.

A twisted interface can remain mechanically stable against separation while offering very little resistance to coherent sliding.

The correct experimental question is therefore not simply whether the shear peak exists.

It is whether the complete set of observations supports a change in lateral stiffness, Raman selection rules, damping, or some combination of these mechanisms.

---

## 12. Research exercise: Interpret an unfamiliar heterobilayer

Imagine that you fabricate a MoS₂/WSe₂ heterobilayer and compare it with a MoS₂ homobilayer.

You observe a breathing-mode frequency lower than that of the homobilayer.

The shear peak is weak.

After changing the relative twist angle, the breathing frequency changes slightly, but its intensity changes substantially.

### Question 1: Does the lower breathing frequency prove weaker interlayer coupling?

**Answer:** No.

The two layers have different masses per unit area.

The breathing frequency depends on both the effective interlayer force constant and the inertia of the relative motion.

You must account for the unequal layer masses before inferring a change in mechanical stiffness.

A suitable calculation should also verify that the observed mode is predominantly a rigid-layer breathing vibration.

### Question 2: Why might the shear peak be weak even if the interface remains bound?

**Answer:** The effective lateral restoring force may be small because the two lattices are mismatched or twisted.

Alternatively, the shear vibration may have a weak Raman matrix element in the measurement geometry.

Disorder, pinning, and linewidth broadening can further reduce the observable signal.

The presence of a breathing mode demonstrates finite out-of-plane restoring stiffness, but does not uniquely determine the lateral stiffness.

### Question 3: What does a large intensity change accompanied by a small frequency shift suggest?

**Answer:** It suggests that the optical coupling to the mode may have changed more strongly than its mechanical restoring force.

Changes in stacking symmetry, electronic resonance conditions, or Raman tensor components can modify intensity without producing an equally large frequency shift.

Polarization-resolved measurements and calculations of the Raman tensor would help test this interpretation.

A change in intensity alone should not be interpreted as a proportional change in interlayer coupling.

---

## 13. Two papers for today's briefing

### Paper 1 — Foundational measurements of interlayer force constants

**Zhao et al., “Interlayer Breathing and Shear Modes in Few-Trilayer MoS₂ and WSe₂.”**

*Nano Letters* **13**, 1007–1015 (2013).

Published online: 4 March 2013.

[Read the paper — DOI: 10.1021/nl304169w](https://doi.org/10.1021/nl304169w)

**Why this paper is relevant**

This study establishes the experimental and theoretical foundation for using low-frequency Raman spectroscopy to characterize interlayer mechanical coupling.

The authors investigate shear and breathing modes in few-layer MoS₂ and WSe₂ using Raman spectroscopy and first-principles calculations.

They demonstrate that a simple nearest-neighbor linear-chain model can reproduce the principal layer-number trends.

This allows effective in-plane and out-of-plane interlayer force constants to be extracted from measured phonon frequencies.

When reading the paper, focus on how the authors identify different vibrational branches and distinguish the effects of layer number from changes in the interlayer interaction itself.

Also examine the assumptions underlying the linear-chain approximation.

**Research question:** Under what conditions can the interlayer force constants extracted from a homomultilayer be transferred to a heterostructure?

### Paper 2 — Twist-dependent shear and breathing modes

**Huang et al., “Low-Frequency Interlayer Raman Modes to Probe Interface of Twisted Bilayer MoS₂.”**

*Nano Letters* **16**, 1435–1444 (2016).

Published online: 26 January 2016.

[Read the paper — DOI: 10.1021/acs.nanolett.5b05015](https://doi.org/10.1021/acs.nanolett.5b05015)

**Why this paper is relevant**

This study extends the analysis of interlayer vibrations from conventional multilayers to twisted bilayers.

The authors combine low-frequency Raman spectroscopy with first-principles calculations to examine how the shear and breathing responses depend on twist angle.

The contrast between the strong softening of the shear mode and the persistence of the breathing mode provides a particularly clear illustration of the directional dependence of interlayer mechanical coupling.

The paper also shows that twist-angle dependence need not be monotonic.

Different angular regimes can exhibit qualitatively different sensitivities to local stacking.

Pay particular attention to the distinction between the experimentally measured Raman intensity and the calculated vibrational frequency.

**Research question:** How would you distinguish a genuine reduction in lateral restoring force from a twist-induced suppression of the shear-mode Raman tensor?

---

## 14. What you should retain

Today's central result is that interlayer shear and breathing modes provide complementary measurements of the mechanical interaction between neighboring atomic layers.

Shear modes probe the local curvature of the interlayer potential with respect to lateral displacement.

Breathing modes probe its curvature with respect to changes in layer separation.

Their frequencies depend on both restoring forces and effective masses.

In multilayers, additional collective displacement patterns generate multiple branches whose frequencies can often be understood using a linear-chain model.

Stacking registry affects the interlayer force constants and the optical selection rules.

Twisting can strongly reduce the effective lateral restoring force while preserving a finite out-of-plane restoring force.

At small twist angles, structural reconstruction can produce spatially varying force constants and vibrational modes that extend beyond the rigid-layer approximation.

**The most important principle is that interlayer phonons probe the local mechanical curvature of an interface, while Raman spectroscopy measures those vibrations through symmetry-dependent optical matrix elements.**

Both ingredients are needed to interpret the experiment.

---

## Next briefing — Wednesday, 21 October 2026

### Morning Physics Briefing 07: Stacking Registry, Symmetry, and the Interlayer Energy Landscape

Our next question will be:

**Why can two multilayer crystals with identical chemical compositions and similar interlayer force constants exhibit strikingly different Raman spectra?**

We will compare 2H and 3R stacking in MoS₂, examine how lateral translations modify interlayer energy landscapes, and connect stacking symmetry to the Raman activity of shear and breathing branches.

We will then introduce the competition between stacking energy and intralayer elasticity that drives structural reconstruction in small-angle twisted bilayers.

This will prepare us for the moiré reciprocal lattice, zone folding, and interlayer phonon hybridization in the remaining Week 2 briefings.
