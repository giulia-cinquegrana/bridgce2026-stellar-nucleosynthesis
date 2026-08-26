![](../.bridgce.png)

# Nucleosynthesis in Asymptotic Giant Branch Stars

Asymptotic Giant Branch stars are important sites for galactic chemical evolution for several reasons.

- **There are many of them:** The AGB is the evolutionary endpoint of a large fraction of stars in the Universe, so AGB stars make a significant cumulative contribution to the chemical enrichment of galaxies.
- **Low and intermediate mass stars have more time to process material:** Their longer evolutionary timescales allow nucleosynthesis to operate over extended periods, with material repeatedly processed and mixed before it is ultimately returned to the interstellar medium.
- **AGBs couple nucleosynthesis and mixing:** Nuclear burning and mixing occur in different regions of the star, allowing material produced in the interior to eventually reach the surface.
- **Low and intermediate mass stars experience their strongest mass loss during the AGB:** Their expanded envelopes are progressively removed through powerful stellar winds, returning processed material to the interstellar medium on relatively short timescales.
- **AGB nucleosynthesis is highly sensitive to stellar properties:** Initial mass and metallicity strongly influence the stellar structure, temperatures, mixing, neutron sources, and resulting abundance patterns. Surface abundances can therefore provide clues about the properties of individual stars and stellar populations.

This afternoon we will follow the journey of material through an AGB star: where it is produced, how it is transported to the surface, and how it is ultimately returned to the interstellar medium. Along the way, we'll see how changing mass and metallicity can move a star between very different nucleosynthetic regimes, and how we translate these stellar models into the yields used in chemical-evolution models.

---

## What is an AGB star?

The AGB is one of the last major stages of nuclear burning in the evolution of low- and intermediate-mass stars ($\approx 1 - 8\, \rm M_\odot$; the exact mass range depends on metallicity). 

<p align="center">
  <img src="../.agb_dawesreview.png" width="600">
  <br>
  <em>AGB structure, based on Figure 14 from Karakas & Lattanzio (2014).</em>
</p>

Stars enter the early AGB after exhausting their central helium. They are left with a degenerate carbon–oxygen core that, despite continued contraction, never reaches the conditions required for central carbon ignition. Instead, helium burning shifts to a shell surrounding the C–O core, while hydrogen burning continues in a shell further out. The star has expanded into a cool giant by this stage, with a large convective envelope surrounding the burning shells. The extended envelope is only weakly bound to the core, and stellar winds progressively erode it until the compact remnant is eventually exposed.

For sufficiently massive AGB stars, the helium-burning shell eventually becomes thermally unstable. This marks the transition from the early AGB to the thermally pulsing AGB (TP-AGB), characterised by periodic thermonuclear runaway events in the helium-burning shell.

---

## The Thermally Pulsing AGB Engine

The TP-AGB is not a steady-burning phase. Instead, the star undergoes repeated cycles of **He-shell instability, thermal pulses, envelope expansion, dredge-up, and renewed shell burning**.

### The Early AGB

While the He-burning shell is established after core He exhaustion, the H-burning shell continues to deposit ash onto the layer above it, progressively increasing the pressure on the He-burning shell. As the He shell burns through this material and becomes geometrically thinner, it becomes increasingly susceptible to the thin-shell instability. The shell cannot expand sufficiently to provide the usual stabilising feedback—a drop in temperature—so the nuclear energy generation rate continues to rise. This eventually triggers a thermonuclear runaway, or thermal pulse.

### The Thermal Pulse 

As the He-burning shell becomes unstable, its temperature rises rapidly. The triple-$\alpha$ reaction is extremely temperature sensitive, so even a modest increase in temperature produces a sharp increase in the helium-burning rate and hence the energy generation. This rapid energy release drives a **pulse-driven convective zone** throughout the He-intershell, rapidly mixing and homogenising the material accumulated there. The energy released by the pulse also temporarily extinguishes the H-burning shell.

### Third Dredge-Up 

As the pulse subsides, the energy released by the He flash drives the envelope outward. The resulting expansion and cooling allow the convective envelope to move inwards into material processed during the pulse. Material from the He-intershell, including newly synthesised $^{12}\mathrm{C}$, $^{16}\mathrm{O}$, and products of neutron-capture nucleosynthesis, is then mixed into the envelope and transported to the stellar surface. The **third dredge-up** therefore provides the principal link between nucleosynthesis in the interior and the abundance patterns observed at the surface.

- **$^{13}\mathrm{C}$ pocket**: Following third dredge-up, partial mixing of protons into the $^{12}\mathrm{C}$-rich intershell can produce a $^{13}\mathrm{C}$-rich layer through $^{12}\mathrm{C}(p,\gamma)^{13}\mathrm{N} \rightarrow ^{13}\mathrm{C}$. This $^{13}\mathrm{C}$ pocket can subsequently act as a neutron source through $^{13}\mathrm{C}(\alpha,n)^{16}\mathrm{O}$. Its formation and structure depends sensitively on the treatment of mixing at the convective boundary and represents an important uncertainty in AGB nucleosynthesis models.

### Interpulse Phase

After the thermal pulse, the star relaxes back toward its quiescent configuration. The convective envelope retreats, the H-burning shell is re-established, and the star enters the **interpulse phase**. This is the longest part of the TP-AGB cycle. Hydrogen burns steadily, depositing fresh helium onto the intershell. As the He-rich layer grows, the pressure and temperature at its base increase until the thin-shell instability is triggered again.

- **Hot-Bottom Burning**: There is one additional process that becomes important toward the higher-mass end of the AGB. In sufficiently massive stars, the base of the convective envelope can become hot enough for hydrogen burning to occur *within the convective envelope itself*. The material at the base of the envelope is repeatedly cycled through this hot region, allowing proton-capture reactions to modify the envelope composition. Depending on the temperature, this can activate the CNO cycles and, at higher temperatures, the Ne--Na and Mg--Al chains. HBB can therefore strongly enhance nitrogen and alter the abundances of Na, Mg, and Al, while simultaneously preventing the envelope from becoming carbon-rich despite continued third dredge-up events.

### Summary 

Importantly, *the cycle is not identical from pulse to pulse*. The core mass, envelope mass, temperature, composition, and mass-loss rate all evolve throughout the TP-AGB. One of the key features of this whole process is that **these cycles repeat many times**. The number of pulses a star experiences, the strength of those pulses, the efficiency of third dredge-up, whether a \(^{13}\mathrm{C}\) pocket forms, and whether HBB operates all depend on the stellar properties. At the same time, the envelope is being progressively removed by stellar winds. The nucleosynthetic products are therefore being *processed, mixed, and ejected repeatedly throughout the AGB*, rather than only at the very end of the star's life. The next question is, *how do initial mass and metallicity determine which of these processes dominates?*

---

## How Mass and Metallicity Shape AGB Nucleosynthesis

So far, we've looked at the AGB star as a physical system: a degenerate core, two burning shells, a convective envelope, and a sequence of thermal pulses and mixing episodes. But this picture is not the same for every AGB star. What actually comes out of an AGB star can be very different depending on where the star sits in initial mass and metallicity space. These parameters determine the stellar structure and evolutionary timescales, which in turn determine the temperatures and densities reached in the burning regions, the efficiency of mixing, and how long the star has to lose its envelope.

### Mass

Initial mass provides the other major axis of the AGB nucleosynthesis landscape. The most important consequence of increasing mass is that the star develops a more massive core and reaches higher temperatures in its interior. This changes which nuclear-burning regimes become accessible. A more massive star has a stronger gravitational potential and develops higher pressures and temperatures in its interior. This means that increasing the initial mass can move the star across thresholds for different nuclear reactions.

For AGB stars, this is particularly important for the temperature at the base of the convective envelope. As the stellar mass increases, the base of the envelope becomes progressively hotter, eventually reaching the temperatures required for **hot-bottom burning**. At solar metallicity, HBB typically begins around the intermediate-mass regime, although the precise mass threshold is model dependent. At a fixed mass, decreasing metallicity generally produces higher temperatures at the base of the envelope and therefore makes HBB easier to activate. Once HBB is operating, the nucleosynthetic regime changes fundamentally. Instead of relying primarily on material being transported from the He-intershell to the surface, nuclear processing occurs directly at the base of the convective envelope. Depending on the temperature, this can activate the CNO cycles and the Ne--Na and Mg--Al chains, strongly affecting the abundances of C, N, O, Na, Mg and Al.

Mass also affects the efficiency of third dredge-up. In general, TDU becomes more efficient with increasing stellar mass and decreasing metallicity, although the precise behaviour depends on the stellar evolution model and its treatment of convective boundaries. This gives us a useful first-order picture:

$$
\boxed{
\begin{array}{ccc}
\text{Low mass}
&\longrightarrow&
\text{cooler envelopes, TDU, }^{13}\mathrm C\text{ neutron source}
\\[0.5em]
\text{Intermediate mass}
&\longrightarrow&
\text{hotter envelopes, HBB, }^{22}\mathrm{Ne}\text{ neutron source}
\end{array}}
$$

with metallicity shifting the boundaries between these regimes. This is why there is no single nucleosynthetic signature for an AGB star. *Mass and metallicity determine which physical processes are available, how efficiently they operate, and whether their products ultimately reach the surface and are ejected.* And this gives us the framework for the rest of the lecture: rather than treating all AGB stars as one nucleosynthetic site, we can now move through the mass--metallicity plane and ask which processes dominate in each regime.

### Metallicity

Metallicity affects AGB nucleosynthesis in two distinct ways. First, it changes the **structure of the star** through quantities such as opacity and mean molecular weight. Second, it changes the **composition of the material being processed**, including the abundance of CNO nuclei and the number of neutron-capture seed nuclei.

- **Opacity ($\kappa$)**: $\kappa$ sources in low- and intermediate-mass stars tend to comprise of metal-dependent transitions (bound free and free absorption). Metal-rich material therefore interacts more strongly with radiation, making it harder for energy to escape through the stellar envelope. The radiative temperature gradient is, 

    $\nabla_{\rm rad} = \frac{3\kappa P L}{16\pi a c G m T^4},$ 

    where $\kappa$ is the opacity. Increasing the opacity increases the radiative temperature gradient required to transport the stellar luminosity. At a given mass and luminosity, metal-rich stars consequently tend to have more extended, less compact envelopes and cooler surface temperatures than their metal-poor counterparts. This structural difference then feeds directly into the AGB nucleosynthesis: the envelope structure determines the temperatures reached at its base, the efficiency of mixing, and ultimately whether processes such as hot-bottom burning can operate.

- **Mean molecular weight**: Metallicity is also accompanied by changes in the initial helium abundance, and therefore in the **mean molecular weight** of the stellar gas. For an ideal gas,

    $P \propto \frac{\rho T}{\mu}.$

    So increasing the mean molecular weight changes the temperature required to provide pressure support. In our very metal-rich models, the increase in $\mu$ can become sufficiently important that it offsets some of the structural effects of increasing opacity, producing hotter and more luminous main-sequence models at the highest metallicities ($\rm [Fe/H] > +0.5$). This has an important consequence: metallicity does not produce a simple monotonic change in every stellar property. Opacity and mean molecular weight act in opposite directions, and their relative importance changes across the metallicity range.

- **Mass loss**: The structural changes caused by metallicity also affect the star's mass-loss history. Mass loss is particularly important on the AGB because the envelope is the reservoir that connects the interior nucleosynthesis to the interstellar medium. Increasing the mass-loss rate removes the envelope more rapidly, reducing both the duration of the TP-AGB and the number of thermal pulses and dredge-up episodes that can occur. At very high metallicity, this effect can become extreme. In our models, sufficiently strong early-AGB mass loss can remove the envelope before the star even reaches the thermally pulsing phase. For models that do reach the TP-AGB, increasing metallicity generally results in fewer thermal pulses and less efficient mixing. 

- **H-burning lifetimes**: Metallicity changes the timescale over which the star evolves. The effect is mediated in part through the mean molecular weight and the resulting luminosity. At very high metallicity, the increased mean molecular weight can produce hotter, more luminous main-sequence stars, while the initial hydrogen abundance is also reduced. The combination leads to significantly shorter hydrogen-burning lifetimes at the highest metallicities. In our \(Z=0.10\) models, the main-sequence lifetime is approximately half that of the corresponding solar-metallicity model. The exact lifetime is not itself a nucleosynthetic process, but it determines when a population begins returning AGB material to the interstellar medium and therefore matters for chemical-evolution timescales.

- **Composition of the nuclear-burning material**: Finally, metallicity changes the *starting composition of the nuclear reactions themselves*. At higher metallicity, the star begins with larger abundances of CNO nuclei and other heavy elements. This matters particularly for proton-capture nucleosynthesis, where many of the nuclei being processed are already present in the initial composition. For example, the CNO nuclei act largely as catalysts in the CNO cycle, but their increasing initial abundance means that the resulting abundance changes can be strongly metallicity dependent. In our metal-rich models, this contributes to enhanced production of secondary species such as \(^{14}\mathrm N\), while some initially abundant CNO isotopes experience greater destruction. Metallicity is also fundamental to neutron-capture nucleosynthesis because it changes the abundance of the seed nuclei onto which neutrons are captured. Combined with the metallicity dependence of the neutron sources and dredge-up, this is one reason why the heavy-element nucleosynthesis of AGB stars changes so strongly across the metallicity range.

---

Okay, lets take X different examples of the mass and metallicity range to look at in detail. 

## Low-Mass AGB Stars

Low-mass AGB stars are characterised by efficient third dredge-up and relatively cool thermal pulses. Their nucleosynthesis is dominated by the production of **carbon and heavy s-process elements**, with the potential to produce substantial enhancements extending to the third s-process peak.

### Metal-Free to Metal-Poor

- Efficient third dredge-up brings primary \(^{12}\mathrm{C}\) to the surface.
- At low metallicity, the high neutron-to-seed ratio favours production of heavy s-process elements.
- Strong carbon enhancement can therefore accompany large enhancements in Ba--Pb.
- At sufficiently low metallicity, proton-ingestion events can occur, producing primary nitrogen and potentially opening the **i-process**.
- The nucleosynthesis can therefore transition from classical s-process behaviour to proton-ingestion/i-process behaviour as metallicity decreases.

### Metal-Rich to Super-Metal-Rich

- Increasing metallicity reduces the efficiency of third dredge-up.
- The larger abundance of Fe-peak seed nuclei also reduces the neutron-to-seed ratio, shifting the s-process distribution toward lighter nuclei.
- At sufficiently high metallicity, strong mass loss can limit the number of thermal pulses and dredge-up episodes.
- Consequently, carbon and heavy s-process enrichment become progressively weaker.
- At the highest metallicities, AGB yields can become dominated by material processed through H burning rather than newly synthesised primary carbon and heavy elements.

## Intermediate-Mass AGB Stars

Intermediate-mass AGB stars reach substantially higher temperatures than their low-mass counterparts. Their nucleosynthesis is therefore increasingly dominated by **hot-bottom burning**, rather than by the \(^{13}\mathrm{C}\) neutron source.

Characteristic products include enhanced **\(^{14}\mathrm{N}\), Na, Al and Mg**, as well as \(^{7}\mathrm{Li}\) under suitable conditions. Their s-process production is generally weaker and is more strongly influenced by the \(^{22}\mathrm{Ne}\) neutron source, favouring production around the first s-process peak.

### Metal-Poor

- Lower metallicity allows higher temperatures to be reached at the base of the convective envelope.
- HBB therefore becomes stronger and can activate the CNO, Ne--Na and Mg--Al cycles.
- Efficient HBB converts dredged-up carbon into primary \(^{14}\mathrm{N}\).
- Depending on the temperature, Na and Al can be enhanced while O and Mg can be depleted.
- The \(^{22}\mathrm{Ne}(\alpha,n)^{25}\mathrm{Mg}\) neutron source becomes increasingly important during thermal pulses.
- Higher neutron densities but shorter exposures favour production toward the **first s-process peak**, rather than the heavy-s-process distribution characteristic of low-mass AGB stars.
- At sufficiently low metallicity, proton-ingestion behaviour can again introduce qualitatively different nucleosynthesis.

### Metal-Rich

- Higher opacity produces a more extended envelope and generally lowers the temperature at its base.
- HBB is therefore weaker and requires a higher initial stellar mass to activate.
- Increasing metallicity also raises the initial abundance of CNO nuclei, making the resulting N production increasingly secondary.
- Stronger mass loss can shorten the TP-AGB and reduce the number of thermal pulses and dredge-up episodes.
- At very high metallicity, third dredge-up can become inefficient or disappear entirely, strongly reducing the production of primary carbon and heavy s-process elements.
- If HBB does operate, the yields can instead be dominated by secondary N and proton-capture products.

## Super-AGB Stars

Super-AGB stars occupy the transition between intermediate-mass stars that end their lives as white dwarfs and massive stars that undergo core-collapse.

- Their initial masses are high enough to ignite carbon burning, but they develop partially degenerate cores.
- They therefore experience both advanced core burning and an AGB-like thermally pulsing phase.
- Carbon burning can occur in a partially degenerate core and may proceed through carbon-burning shells.
- Their high core masses and high envelope temperatures make them particularly important sites for HBB and proton-capture nucleosynthesis.
- The high temperatures also allow the \(^{22}\mathrm{Ne}\) neutron source to operate efficiently.
- Their yields can therefore be rich in **N, Na, Al and Mg**, with a different neutron-capture signature from low-mass AGB stars.
- Strong mass loss is crucial: depending on the competition between envelope loss and core growth, a super-AGB star may end as an ONe white dwarf or proceed to an electron-capture or core-collapse supernova.

## AGBs in Binaries

So far, we've treated AGB stars as isolated stars. But this is an important simplification: a large fraction of low- and intermediate-mass stars have companions, and binary interactions can substantially alter the evolution of the AGB star and therefore its nucleosynthetic yields. :contentReference[oaicite:0]{index=0}

The important point is that the companion does not simply provide another source of material. **Binary interactions can change the mass, core-to-envelope ratio, lifetime, and evolutionary pathway of the AGB star itself.**

### How can a companion change an AGB star?

There are several possible interactions:

- **Mass transfer:** one star can transfer material to its companion, changing the companion's total mass and composition.
- **Wind accretion:** the companion can accrete material from the AGB wind.
- **Roche-lobe overflow:** if the AGB star expands sufficiently, it can transfer mass directly to its companion.
- **Common-envelope evolution:** in sufficiently close systems, the companion can enter the AGB envelope, rapidly removing it and potentially terminating the AGB phase.
- **Mergers:** the two stars can ultimately merge, producing an evolutionary pathway that cannot be represented by a single-star model.

All of these processes can change how long the star remains on the TP-AGB and how many thermal pulses and dredge-up episodes it experiences.

### Changing the TP-AGB lifetime

One particularly interesting result from Osborn et al. is that binary evolution can sometimes **increase** the duration of the TP-AGB.

If a star gains envelope mass after core-He burning, it can enter the TP-AGB with a relatively small core-to-total-mass ratio. These stars can remain on the TP-AGB for much longer than single stars of the same initial mass.

This has a direct nucleosynthetic consequence: a longer TP-AGB lifetime means more thermal pulses, more opportunities for third dredge-up, and more time for H-burning processes such as HBB to operate.

This effect is particularly striking for \(^{26}\mathrm{Al}\). Osborn et al. find that binary systems can produce stars with substantially enhanced \(^{26}\mathrm{Al}\) because of these unusually long TP-AGB lifetimes. For a population with a binary fraction of \(0.75\), the population-weighted \(^{26}\mathrm{Al}\) yield was approximately \(25\%\) higher than for a population of single stars. :contentReference[oaicite:1]{index=1}

So binary evolution does not necessarily mean **less** nucleosynthesis. In some evolutionary pathways, it can actually extend the time available for nucleosynthesis and increase specific yields.

### But binaries can also suppress AGB nucleosynthesis

The opposite can happen if binary interaction removes the envelope.

If mass transfer or a common-envelope phase strips the AGB envelope before the star has completed its normal TP-AGB evolution, the star experiences fewer thermal pulses and less third dredge-up.

This can substantially reduce the amount of carbon and s-process material that is ultimately ejected.

Osborn et al.'s population-synthesis calculations at solar metallicity find that a population with a binary fraction of \(0.7\) ejects approximately **20--25\% less carbon and s-process material** than an equivalent population of only single stars, while the total N and O yields change much less. :contentReference[oaicite:2]{index=2}

At low metallicity, the effect can be even larger. At \(Z=0.0001\), binary populations were predicted to contain approximately **37\% fewer TP-AGB stars**, resulting in roughly **40\% less ejected carbon** and **35--40\% less material produced by the s-process** compared with single-star populations. :contentReference[oaicite:3]{index=3}

### The important consequence for chemical evolution

This means that the usual approach of taking a grid of **single-star AGB yields** and integrating them over an initial-mass function is incomplete if binary evolution is important.

Schematically, instead of

$$
\text{initial mass}
\rightarrow
\text{single-star AGB}
\rightarrow
\text{yield},
$$

we should really have

$$
\boxed{
\text{initial mass + binary properties}
\rightarrow
\text{binary evolution}
\rightarrow
\text{modified AGB evolution}
\rightarrow
\text{yield}
}
$$

The binary parameters introduce another dimension to the AGB nucleosynthesis landscape: **mass, metallicity, and binary configuration**.

And importantly, the effect is not necessarily a simple reduction in the yield. Binary interactions can either **truncate the AGB and suppress nucleosynthesis**, or **alter the stellar structure in a way that extends the TP-AGB and enhances particular products**.

This is why binary population synthesis is important for translating individual stellar models into realistic chemical yields for stellar populations.

## The AGB Nucleosynthesis Landscape: Mass x Metallicity

## From Stellar Models to Nucleosynthetic Yields