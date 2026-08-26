# Nucleosynthesis in Asymptotic Giant Branch Stars

## Introduction [2 mins]

Asymptotic Giant Branch stars are important sites for galactic chemical evolution for several reasons.

- *There are many of them.* The AGB is the evolutionary endpoint of a large fraction of stars in the Universe, so AGB stars make a significant cumulative contribution to the chemical enrichment of galaxies.
- *They provide extended timescales for nucleosynthesis.* Lower-mass stars evolve more slowly than massive stars, and their conditions are particularly well suited to the production of heavy elements through slow and intermediate neutron-capture nucleosynthesis.
- *They couple nucleosynthesis and mixing.* Nuclear burning and mixing occur in different regions of the star, allowing material produced in the interior to eventually reach the surface.
- *They experience their strongest mass loss during the AGB.* Their expanded envelopes are progressively removed through powerful stellar winds, returning processed material to the interstellar medium on relatively short timescales.
- *Their nucleosynthesis is highly sensitive to stellar properties.* Initial mass and metallicity strongly influence the stellar structure, temperatures, mixing, neutron sources, and resulting abundance patterns. Surface abundances can therefore provide clues about the properties of individual stars and stellar populations.

So, over the next 30 or so minutes, we'll follow the journey of material through an AGB star: where it is produced, how it is transported to the surface, and how it is ultimately returned to the interstellar medium. Along the way, we'll see how changing mass and metallicity can move a star between very different nucleosynthetic regimes, and how we translate these stellar models into the yields used in chemical-evolution models.

## What is an AGB star?

So, what actually is an AGB star?

The AGB is one of the last active burning stages in the evolution of low- and intermediate-mass stars. Broadly, we're talking about stars with initial masses between roughly 1 and 8Msun, although that range depends on metallicity and other aspects of the stellar physics.

By the time a star reaches the AGB, it has exhausted its central reserves of hydrogen and helium, leaving behind a carbon–oxygen core. As the core contracts, it moves toward the next stage of nuclear burning, but in low- and intermediate-mass stars it never reaches the conditions required for central carbon ignition. Instead, helium burning ignites in a shell surrounding the C–O core, while hydrogen burning continues in another shell further out.

The result is the characteristic double-shell structure of the AGB: an inactive, degenerate carbon–oxygen core, surrounded by a helium-burning shell and a hydrogen-burning shell. Outside these burning shells is a large, convective envelope. By this stage, the star has expanded enormously, with a cool, extended envelope surrounding the compact core.

$$
\text{Convective envelope}
\;|\;
\text{H-burning shell}
\;|\;
\text{He-burning shell}
\;|\;
\text{Degenerate C--O core}
$$
	​
This gives us the basic architecture we need: distinct nuclear-burning sites surrounded by a large convective envelope. The star also undergoes increasingly strong mass loss during this phase, progressively eroding the envelope and eventually exposing the compact remnant. The loss of the envelope marks the end of the AGB phase.

But this picture is still static. The key question is what happens to these burning shells as the star evolves *along the AGB*. 

## The Thermally Pulsing AGB Engine

The defining feature of the AGB is that the two burning shells do not operate in a steady state. Instead, the helium-burning shell becomes thermally unstable, producing a series of **thermal pulses**. The star spends most of its time in a relatively quiescent phase, with energy production dominated by the hydrogen-burning shell. As hydrogen burning converts hydrogen into helium, helium accumulates in the intershell region above the core.

Eventually, the temperature and density in the helium-rich layer become high enough for helium burning to become unstable. The helium shell rapidly ignites through the triple-(\alpha) reaction,

[
3,^4\mathrm{He}\rightarrow{}^{12}\mathrm{C},
]

producing a large increase in the energy generation rate. This is the **helium-shell flash**, or thermal pulse. The resulting energy release drives convection through the helium-burning region, creating a temporary **pulse-driven convective zone** in the intershell.

An important consequence is that the hydrogen-burning shell is temporarily extinguished. The star then expands and cools, and the helium-burning luminosity declines. Once the pulse subsides, the structure contracts again, hydrogen burning is re-established, and the star returns to its quiescent state.

But the pulse does more than simply produce energy. It changes the composition and structure of the layers between the two shells. After the pulse, the convective envelope can penetrate into the previously processed intershell region, bringing newly synthesised material toward the surface. This is the **third dredge-up**.

The cycle therefore looks roughly like:

[
\text{H-shell burning}
\rightarrow
\text{He accumulation}
\rightarrow
\text{He-shell flash}
\rightarrow
\text{pulse-driven convection}
\rightarrow
\text{third dredge-up}
\rightarrow
\text{H-shell burning}.
]

The important point is that this cycle repeats. An AGB star can experience many thermal pulses during its lifetime, and each pulse provides another opportunity to modify the composition of the envelope.

The composition of the intershell itself is also changing from pulse to pulse. Helium burning produces large amounts of (^{12}\mathrm C), while subsequent processing can produce (^{16}\mathrm O) and other species. The intershell is therefore the site where much of the material that will eventually be dredged to the surface is produced.

This gives us the basic **engine of AGB nucleosynthesis**:

[
\boxed{
\text{nuclear burning}
\rightarrow
\text{mixing}
\rightarrow
\text{surface enrichment}
\rightarrow
\text{mass loss}
}
]

The details of this cycle—particularly how efficiently material is dredged up, how hot the burning regions become, and how rapidly the envelope is lost—depend strongly on the star's initial mass and metallicity. Those dependencies are what will ultimately determine which nucleosynthetic processes dominate.

## The AGB Nucleosynthesis Toolkit

Yes. For this section I would **keep it as a toolkit rather than a mini nucleosynthesis lecture**. The audience needs the vocabulary and physical mechanisms that you'll invoke in the mass–metallicity sections later.

One important correction: I would be careful with saying the **second dredge-up is simply "CNO-burning products."** It brings material processed by H burning to the surface, including enhanced He and (^{14}\mathrm N), and reduced (^{12}\mathrm C) and (^{13}\mathrm C); the detailed abundance changes depend on mass and metallicity.

I would cover **five mechanisms**:

1. First dredge-up
2. Second dredge-up
3. Third dredge-up
4. Hot-bottom burning
5. Extra mixing / proton ingestion as a brief "beyond standard convection" concept

I would **not yet explain the s-, i-, or neutron-capture processes here**. Just establish that third dredge-up can expose neutron-capture products and that HBB activates proton-capture nucleosynthesis. Those get properly unpacked later.

## The AGB Nucleosynthesis Toolkit

Before we look at how mass and metallicity change AGB nucleosynthesis, it is useful to introduce a few of the physical processes that we will keep coming back to.

The first is **dredge-up**. As a star evolves, its convective envelope can penetrate into layers that have previously undergone nuclear processing, bringing that material to the surface. There are three classical episodes of dredge-up.

The **first dredge-up** occurs as a star ascends the red giant branch, before it reaches the AGB. As the convective envelope deepens, it mixes material that has been processed by hydrogen burning into the stellar atmosphere. The main signature is the appearance of CNO-cycle products at the surface: (^{12}\mathrm C) is depleted, (^{14}\mathrm N) is enhanced, and the (^{12}\mathrm C/^{13}\mathrm C) ratio decreases. The first dredge-up therefore establishes part of the surface composition with which the star enters the AGB.

The **second dredge-up** occurs in more massive stars after core helium burning. The convective envelope penetrates deeper into the star and again exposes material processed by hydrogen burning. It generally increases the surface helium and nitrogen abundances while reducing the carbon abundance. Whether and how strongly the second dredge-up occurs depends strongly on stellar mass and metallicity, so it will become particularly relevant when we compare low- and intermediate-mass AGB stars.

The **third dredge-up** is different. It occurs after a thermal pulse, when the convective envelope penetrates into the helium-intershell. This brings material produced by helium burning—and, importantly for us, material affected by neutron-capture nucleosynthesis—to the surface. Repeated third dredge-up episodes can therefore transform an initially oxygen-rich star into a carbon star and can progressively enrich the envelope in heavy elements.

We can characterise the efficiency of the third dredge-up with

[
\lambda =
\frac{\Delta M_{\rm dredge}}
{\Delta M_{\rm core}},
]

where (\Delta M_{\rm dredge}) is the mass mixed into the envelope following a pulse and (\Delta M_{\rm core}) is the increase in core mass during the preceding interpulse period.

The second major mechanism we need is **hot-bottom burning**, or HBB. In sufficiently massive AGB stars, the base of the convective envelope becomes hot enough for hydrogen burning to occur within the envelope itself. Because convection operates on a short timescale, material can be repeatedly transported between the hot base of the envelope and the cooler surface.

This opens up proton-capture reactions that are not important in lower-mass AGB stars. The CNO cycles can efficiently convert carbon into nitrogen, while the Ne–Na and Mg–Al chains can modify the abundances of Na, Mg and Al. HBB can therefore prevent a star from becoming carbon-rich even when third dredge-up is bringing (^{12}\mathrm C) to the surface.

There is also a broader category of **extra mixing** that goes beyond the classical convective picture. Processes such as convective-boundary mixing, rotation, thermohaline mixing, and other proposed mechanisms can transport material across otherwise stable boundaries. These processes are particularly important because they can determine whether protons reach regions where they alter the subsequent nucleosynthesis.

This becomes especially interesting when we consider the formation of a (^{13}\mathrm C) pocket, or when proton ingestion occurs in very metal-poor stars. We will return to both of these later.

So the basic toolkit we need is:

[
\boxed{
\begin{array}{c}
\text{Dredge-up} \
\text{Hot-bottom burning} \
\text{Extra mixing} \
\text{Mass loss}
\end{array}
}
]

These processes determine **what material is exposed at the surface, what nuclear reactions can operate, and ultimately what material is returned to the interstellar medium**. The balance between them changes dramatically with stellar mass and metallicity, which is where we go next.


## How Mass and Metallicity Shape AGB Nucleosynthesis

So far, we've described the basic AGB structure and the processes that can alter its composition. But an AGB star is not a single nucleosynthetic site. **The nucleosynthesis depends strongly on the initial mass and metallicity of the star.**

These two quantities influence the structure of the star throughout its evolution: they affect the core mass, the temperatures reached in the burning shells, the strength of the thermal pulses, the efficiency of dredge-up, and whether hydrogen burning can occur at the base of the convective envelope. Ultimately, they determine which nucleosynthetic processes operate and how efficiently they contribute to the stellar yields. This is one of the central results of the model grid presented in my work. 

Let's first consider **mass**. As the initial mass increases, the core mass and the temperatures reached during AGB evolution generally increase. This changes the dominant sources of nucleosynthesis. In lower-mass AGB stars, the temperatures are sufficient for helium-shell burning and for neutron production through the (^{13}\mathrm C(\alpha,n)^{16}\mathrm O) reaction, making these stars important sites for the production of carbon and heavy (s)-process elements. In more massive AGB stars, the thermal pulses become hotter and the (^{22}\mathrm{Ne}(\alpha,n)^{25}\mathrm{Mg}) reaction becomes increasingly important. At still higher masses, the base of the convective envelope becomes hot enough for **hot-bottom burning**, allowing proton-capture nucleosynthesis to occur directly within the envelope. 

Metallicity introduces another, quite different, lever. It affects the stellar structure and therefore the temperatures and pulse properties, but it also changes the initial abundance of the nuclei that act as seeds for neutron-capture nucleosynthesis. In our models, decreasing metallicity produces **hotter interiors, stronger thermal pulses, and more efficient third dredge-up**. The consequence is enhanced production of carbon and heavy (s)-process elements. As the metallicity increases, the pulses become weaker and dredge-up is increasingly suppressed, reducing the contribution of AGB stars to heavy-element production. 

So there are really two effects happening at once. **Mass changes the physical conditions inside the star**, determining which burning and mixing processes are available. **Metallicity changes both those physical conditions and the composition of the material being processed.**

We can therefore think of AGB nucleosynthesis as occupying a landscape in **mass–metallicity space**. At one end, we have low-mass, metal-rich stars where dredge-up and neutron-capture production can be relatively weak. Moving toward lower metallicity, we encounter stronger pulses, more efficient dredge-up, and increasingly important heavy-element production. Moving toward higher mass instead takes us toward hotter thermal pulses, the (^{22}\mathrm{Ne}) neutron source, and eventually hot-bottom burning.

And this is the landscape that we'll explore for the rest of the lecture: **how changing mass and metallicity moves an AGB star between different nucleosynthetic regimes.**


## Metal-Rich AGB Stars: 13C and 22Ne Neutron Sources

## Metal-poor Low and Intermediate Mass AGBs: From the s-Process to the i-Process

## Metal-free Low and Intermediate Mass AGBs: The First AGB Stars

## Super AGBs: The High-Mass Limit

## The AGB Nucleosynthesis Landscape: Mass x Metallicity

## From Stellar Models to Nucleosynthetic Yields