![](../.bridgce.png)

# Nucleosynthesis in Asymptotic Giant Branch Stars

## Introduction

Asymptotic Giant Branch stars are important sites for galactic chemical evolution for several reasons.

- **There are many of them:** The AGB is the evolutionary endpoint of a large fraction of stars in the Universe, so AGB stars make a significant cumulative contribution to the chemical enrichment of galaxies.
- **Low and intermediate mass stars have more time to process material:** Their longer evolutionary timescales allow nucleosynthesis to operate over extended periods, with material repeatedly processed and mixed before it is ultimately returned to the interstellar medium.
- **AGBs couple nucleosynthesis and mixing:** Nuclear burning and mixing occur in different regions of the star, allowing material produced in the interior to eventually reach the surface.
- **Low and intermediate mass stars experience their strongest mass loss during the AGB:** Their expanded envelopes are progressively removed through powerful stellar winds, returning processed material to the interstellar medium on relatively short timescales.
- **AGB nucleosynthesis is highly sensitive to stellar properties:** Initial mass and metallicity strongly influence the stellar structure, temperatures, mixing, neutron sources, and resulting abundance patterns. Surface abundances can therefore provide clues about the properties of individual stars and stellar populations.

This afternoon we will follow the journey of material through an AGB star: where it is produced, how it is transported to the surface, and how it is ultimately returned to the interstellar medium. Along the way, we'll see how changing mass and metallicity can move a star between very different nucleosynthetic regimes, and how we translate these stellar models into the yields used in chemical-evolution models.

## What is an AGB star?

The AGB is one of the last active burning stages in the evolution of low- and intermediate-mass stars. Broadly, we are talking about stars with initial masses between roughly 1 and $8\,\rm M_\odot$, although that range depends on metallicity and other aspects of the stellar physics.

By the time a star reaches the AGB, it has exhausted its central reserves of hydrogen and helium, leaving behind a carbon–oxygen core. As the core contracts, it moves toward the next stage of nuclear burning, but in low- and intermediate-mass stars it never reaches the conditions required for central carbon ignition. Instead, helium burning ignites in a shell surrounding the C–O core, while hydrogen burning continues in another shell further out.

The result is the characteristic double-shell structure of the AGB; an inactive, degenerate carbon–oxygen core, surrounded by a helium-burning shell and a hydrogen-burning shell. Between the two burning shells is the He-intershell, a thin region whose composition will become particularly important for the nucleosynthesis we discuss later. Outside the burning shells is a large, convective envelope. By this stage, the star has expanded enormously, with a cool, extended envelope surrounding the compact core.

![](../.agb_dawesreview.png)
	​
This gives us the basic architecture we need: multiple nuclear-burning sites, a chemically important intershell region, and a large convective envelope surrounding them. The star also undergoes increasingly strong mass loss during this phase, progressively eroding the envelope and eventually exposing the compact remnant. The loss of the envelope marks the end of the AGB, leaving behind a C–O white dwarf in the case of stars that do not proceed to more advanced burning.

But this picture is still static. As the star evolves along the AGB, the structure of these burning regions changes, and with it the conditions under which nucleosynthesis occurs. So what drives this changing structure, and how does it lead to the repeated episodes of nucleosynthesis that characterise the AGB?

## The Thermally Pulsing AGB Engine

The defining feature of the thermally pulsing AGB is that the two burning shells do not operate in a steady state. Instead, the star undergoes repeated cycles of **He-shell instability, thermal pulses, envelope expansion, dredge-up, and renewed shell burning**.

- **The early AGB**: After helium-shell burning is established on the early AGB, the H-burning shell continues to deposit helium ash onto the He-burning shell. The He-rich layer therefore becomes progressively more massive and compressed. As the He-burning shell becomes geometrically thinner, it becomes increasingly susceptible to the *thin-shell instability* (see derivation *here*). In a sufficiently thin shell, expansion does not provide the usual stabilising feedback: the shell cannot expand enough to reduce its temperature and hence its nuclear energy generation. The result is a thermonuclear runaway, or *thermal pulse*.

- **The thermal pulse**: The temperature in the He-burning shell rises rapidly, causing the helium-burning rate to increase sharply through the triple-α reaction,

$$
3\,^4\mathrm{He}\rightarrow{}^{12}\mathrm{C}.
$$

The enormous increase in energy generation drives a *pulse-driven convective zone* through the He-intershell, between the He- and H-burning shells. This region becomes strongly mixed, homogenising the material that has accumulated and been processed in the intershell. The pulse temporarily extinguishes the H-burning shell.

- **Expansion and third dredge-up**: As the pulse subsides, the energy released by the He flash drives the envelope outward. The expansion and cooling of the outer layers eventually allow the convective envelope to penetrate inward into material that has been processed during the pulse. This is known as the *third dredge-up*. Material from the He-intershell—including newly synthesised \(^{12}\mathrm{C}\), \(^{16}\mathrm{O}\), and products of neutron-capture nucleosynthesis—is transported into the convective envelope and can subsequently appear at the stellar surface. The third dredge-up therefore provides the critical connection between nucleosynthesis in the interior and observable surface abundances.

    - There is also an important connection to the **\(^{13}\mathrm{C}\) pocket**. Following dredge-up, partial mixing of protons into the \(^{12}\mathrm{C}\)-rich intershell can produce a \(^{13}\mathrm{C}\)-rich layer,

    $$
    ^{12}\mathrm{C}(p,\gamma)^{13}\mathrm{N}
    \rightarrow
    ^{13}\mathrm{C},
    $$

    which can subsequently act as a neutron source through

    $$
    ^{13}\mathrm{C}(\alpha,n)^{16}\mathrm{O}.
    $$

    The formation and structure of this pocket depend on how mixing is treated at the convective boundary. In sufficiently massive AGB stars, the base of the envelope can become hot enough that protons are burned during dredge-up itself—so-called **hot dredge-up**—which can inhibit the formation of a \(^{13}\mathrm{C}\) pocket.

- **The interpulse phase**: After the thermal pulse, the star relaxes back toward its quiescent configuration. The convective envelope retreats, the H-burning shell is re-established, and the star enters the **interpulse phase**. This is the longest part of the TP-AGB cycle. Hydrogen burns steadily, depositing fresh helium onto the intershell. As the He-rich layer grows, the pressure and temperature at its base increase until the thin-shell instability is triggered again.

- There is one additional process that becomes important toward the higher-mass end of the AGB. In sufficiently massive stars, the base of the convective envelope becomes hot enough for hydrogen burning to occur *within the convective envelope itself*. This is **hot-bottom burning** (HBB). The material at the base of the envelope is repeatedly cycled through this hot region, allowing proton-capture reactions to modify the envelope composition. Depending on the temperature, this can activate the CNO cycles and, at higher temperatures, the Ne--Na and Mg--Al chains. HBB can therefore strongly enhance nitrogen and alter the abundances of Na, Mg, and Al, while simultaneously preventing the envelope from becoming carbon-rich despite continued third dredge-up.

The cycle therefore becomes:

$$
\boxed{
\begin{array}{c}
\text{H-shell burning}\\
\downarrow\\
\text{He accumulation}\\
\downarrow\\
\text{He-shell instability}\\
\downarrow\\
\text{thermal pulse}\\
\downarrow\\
\text{pulse-driven convection}\\
\downarrow\\
\text{third dredge-up}\\
\downarrow\\
\text{interpulse H burning}\\
\downarrow\\
\text{repeat}
\end{array}
}
$$

Importantly, *the cycle is not identical from pulse to pulse*. The core mass, envelope mass, temperature, composition, and mass-loss rate all evolve throughout the TP-AGB. One of the key features of this whole process is that **these cycles repeat many times**. The number of pulses a star experiences, the strength of those pulses, the efficiency of third dredge-up, whether a \(^{13}\mathrm{C}\) pocket forms, and whether HBB operates all depend on the stellar properties. At the same time, the envelope is being progressively removed by stellar winds. The nucleosynthetic products are therefore being *processed, mixed, and ejected repeatedly throughout the AGB*, rather than only at the very end of the star's life.

The next question is, *how do initial mass and metallicity determine which of these processes dominates?*

## How Mass and Metallicity Shape AGB Nucleosynthesis

So far, we've looked at the AGB star as a physical system: a degenerate core, two burning shells, a convective envelope, and a sequence of thermal pulses and mixing episodes. But this picture is not the same for every AGB star. What actually comes out of an AGB star can be very different depending on where the star sits in *initial mass and metallicity* space. These parameters determine the stellar structure and evolutionary timescales, which in turn determine the temperatures and densities reached in the burning regions, the efficiency of mixing, and how long the star has to lose its envelope.

There is therefore a chain connecting the initial properties of the star to its nucleosynthetic output:

$$
(M, Z)
\rightarrow
\text{stellar structure}
\rightarrow
(T,\rho,\text{mixing, mass loss})
\rightarrow
\text{nuclear burning}
\rightarrow
\text{surface abundances and yields}.
$$

Let's first consider metallicity.

### Metallicity

Metallicity affects AGB nucleosynthesis in two distinct ways. First, it changes the **structure of the star** through quantities such as opacity and mean molecular weight. Second, it changes the **composition of the material being processed**, including the abundance of CNO nuclei and the number of neutron-capture seed nuclei.

#### Opacity

The opacity of stellar material depends strongly on its composition. As metallicity increases, the opacity of the stellar gas generally increases.

Higher opacity changes the way energy is transported through the star, leading to lower effective temperatures and, in the relevant AGB models, lower densities and temperatures at the base of the convective envelope. These structural differences are particularly important for intermediate-mass stars because they can suppress **hot-bottom burning**.

This means that metallicity does not simply change the amount of material available for nucleosynthesis; it changes the physical conditions under which the nucleosynthesis takes place. In our very metal-rich models, for example, the temperature at the base of the convective envelope decreases substantially with increasing metallicity, delaying or suppressing HBB. :contentReference[oaicite:1]{index=1}

#### Mean molecular weight

Metallicity is also accompanied by changes in the initial helium abundance, and therefore in the **mean molecular weight** of the stellar gas.

For an ideal gas,

$$
P \propto \frac{\rho T}{\mu},
$$

so increasing the mean molecular weight changes the temperature required to provide pressure support. In our very metal-rich models, the increase in \(\mu\) can become sufficiently important that it offsets some of the structural effects of increasing opacity, producing hotter and more luminous main-sequence models at the highest metallicities.

This has an important consequence: metallicity does not produce a simple monotonic change in every stellar property. Opacity and mean molecular weight act in opposite directions, and their relative importance changes across the metallicity range. :contentReference[oaicite:2]{index=2}

#### Mass loss

The structural changes caused by metallicity also affect the star's mass-loss history.

Mass loss is particularly important on the AGB because the envelope is the reservoir that connects the interior nucleosynthesis to the interstellar medium. Increasing the mass-loss rate removes the envelope more rapidly, reducing both the duration of the TP-AGB and the number of thermal pulses and dredge-up episodes that can occur.

At very high metallicity, this effect can become extreme. In our models, sufficiently strong early-AGB mass loss can remove the envelope before the star even reaches the thermally pulsing phase. For models that do reach the TP-AGB, increasing metallicity generally results in fewer thermal pulses and less efficient mixing. :contentReference[oaicite:3]{index=3}

This is important because a nucleosynthetic product only contributes to the stellar yield if it is both **produced and ejected**. A star can therefore undergo nucleosynthesis internally without making a large contribution to the chemical enrichment of the surrounding medium.

#### H-burning lifetimes

Metallicity also changes the timescale over which the star evolves.

The effect is mediated in part through the mean molecular weight and the resulting luminosity. At very high metallicity, the increased mean molecular weight can produce hotter, more luminous main-sequence stars, while the initial hydrogen abundance is also reduced. The combination leads to significantly shorter hydrogen-burning lifetimes at the highest metallicities. In our \(Z=0.10\) models, the main-sequence lifetime is approximately half that of the corresponding solar-metallicity model. :contentReference[oaicite:4]{index=4}

The exact lifetime is not itself a nucleosynthetic process, but it determines when a population begins returning AGB material to the interstellar medium and therefore matters for chemical-evolution timescales.

#### Composition of the nuclear-burning material

Finally, metallicity changes the **starting composition of the nuclear reactions themselves**.

At higher metallicity, the star begins with larger abundances of CNO nuclei and other heavy elements. This matters particularly for proton-capture nucleosynthesis, where many of the nuclei being processed are already present in the initial composition.

For example, the CNO nuclei act largely as catalysts in the CNO cycle, but their increasing initial abundance means that the resulting abundance changes can be strongly metallicity dependent. In our metal-rich models, this contributes to enhanced production of secondary species such as \(^{14}\mathrm N\), while some initially abundant CNO isotopes experience greater destruction. :contentReference[oaicite:5]{index=5}

Metallicity is also fundamental to neutron-capture nucleosynthesis because it changes the abundance of the seed nuclei onto which neutrons are captured. Combined with the metallicity dependence of the neutron sources and dredge-up, this is one reason why the heavy-element nucleosynthesis of AGB stars changes so strongly across the metallicity range.

So metallicity affects AGB nucleosynthesis through both **the physics of the star** and **the composition of the material being processed**.

### Mass

Initial mass provides the other major axis of the AGB nucleosynthesis landscape.

The most important consequence of increasing mass is that the star develops a more massive core and reaches higher temperatures in its interior. This changes which nuclear-burning regimes become accessible.

#### Pressure and central temperature

A more massive star has a stronger gravitational potential and develops higher pressures and temperatures in its interior. This means that increasing the initial mass can move the star across thresholds for different nuclear reactions.

For AGB stars, this is particularly important for the temperature at the base of the convective envelope. As the stellar mass increases, the base of the envelope becomes progressively hotter, eventually reaching the temperatures required for **hot-bottom burning**.

At solar metallicity, HBB typically begins around the intermediate-mass regime, although the precise mass threshold is model dependent. At a fixed mass, decreasing metallicity generally produces higher temperatures at the base of the envelope and therefore makes HBB easier to activate. :contentReference[oaicite:6]{index=6}

Once HBB is operating, the nucleosynthetic regime changes fundamentally. Instead of relying primarily on material being transported from the He-intershell to the surface, nuclear processing occurs directly at the base of the convective envelope. Depending on the temperature, this can activate the CNO cycles and the Ne--Na and Mg--Al chains, strongly affecting the abundances of C, N, O, Na, Mg and Al.

Mass also affects the efficiency of third dredge-up. In general, TDU becomes more efficient with increasing stellar mass and decreasing metallicity, although the precise behaviour depends on the stellar evolution model and its treatment of convective boundaries. :contentReference[oaicite:7]{index=7}

This gives us a useful first-order picture:

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

with metallicity shifting the boundaries between these regimes.

This is why there is no single nucleosynthetic signature for an AGB star. *Mass and metallicity determine which physical processes are available, how efficiently they operate, and whether their products ultimately reach the surface and are ejected.* And this gives us the framework for the rest of the lecture: rather than treating all AGB stars as one nucleosynthetic site, we can now move through the mass--metallicity plane and ask which processes dominate in each regime.





## Metal-Rich AGB Stars: 13C and 22Ne Neutron Sources

## Metal-poor Low and Intermediate Mass AGBs: From the s-Process to the i-Process

## Metal-free Low and Intermediate Mass AGBs: The First AGB Stars

## Super AGBs: The High-Mass Limit

## AGBs in Binaries

## The AGB Nucleosynthesis Landscape: Mass x Metallicity

## From Stellar Models to Nucleosynthetic Yields