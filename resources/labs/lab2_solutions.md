# Solutions

**Exercise 1(b).** Read off which branch point(s) are open (f_n >~ 0.5, capture wins) vs closed (f_n <~ 0.5, decay wins) at each mechanism's density:

- **13C pocket** (n_n=1e7) -- preferentially feeds **134Ba and 136Ba** directly. Both branch points are closed (f_n(Cs134)=0.028, f_n(Cs136)=0.0006), so almost everything decays straight through; 136Ba gets the biggest pile-up.
- **22Ne burst, low end** (n_n=3e8) -- still preferentially feeds **136Ba** (f_n(Cs136)=0.016, still closed), but branch point 1 is now roughly half-open (f_n(Cs134)=0.47), so 134Ba production is already partly suppressed relative to the 13C-pocket case.
- **22Ne burst, high end** (n_n=1e11) -- preferentially feeds **135Ba and 137Ba**. Both branch points are now mostly/fully open (f_n(Cs134)=0.997, f_n(Cs136)=0.85): 134Ba's direct-decay channel is essentially shut off, and material has started reaching 137Cs --> 137Ba in bulk for the first time.
- **PIE / i-process** (n_n=4.3e14) -- preferentially feeds **135Ba and 137Ba** completely (f_n(Cs134)=1.000, f_n(Cs136)=1.000). Direct decay-feeding of 134Ba and 136Ba is fully shut off (though, as Exercise 2 shows, 136Ba still ends up enhanced overall -- via onward capture flow through the chain, not via direct branch-point decay).

**Exercise 1(c).** Ranking by how open the 136Cs branch point is (f_n(Cs136), ascending): 13C pocket (0.0006, essentially closed) < 22Ne burst, low (0.016, still closed) < 22Ne burst, high (0.848, mostly open) < PIE/i-process (1.000, fully open).

The s-process/i-process boundary is a **continuum**, not a sharp line. f_n(Cs136) rises smoothly and monotonically across many orders of magnitude in n_n, with no discontinuity. It's a gradual transition (in log n_n) sitting somewhere between the two 22Ne-burst densities. 

**Discussion Q1.** The first bypass stage (134Ba/135Ba) peaks around n_n~2-3x10^8 (just past the 22Ne-burst-low marker) then collapses toward its floor by n_n~10^12-10^13. The second stage (137Ba pulling away) is smoother: 137Ba/138Ba climbs past where 134Ba/135Ba/138Ba are already declining starting around n_n~10^9-10^10.

At the 13C-pocket marker, 134Ba/135Ba haven't yet peaked and 136Ba dominates (25x Ba138). At 22Ne-burst-low, 134Ba/135Ba sit right at their peak (7.1, 8.9) -- transitional, but still recognisably s-process-like (136Ba still dominant, 39x). By 22Ne-burst-high (n_n=1e11), though, 134Ba/135Ba have collapsed essentially to their high-density floor (1.81, 1.86), and 137Ba (10.02) is already ~99% of its final saturated value (10.09). The PIE/i-process marker (4.3e14) gives 134Ba=1.75, 135Ba=1.80, 137Ba=10.09, similiar to the 22Ne-burst-high values.

So yes, the PIE/i-process marker sits clearly past where 137Ba/138Ba has turned on but so does 22Ne-burst-high. A star with a large 137Ba/138Ba enhancement points you to the n_n column of the Section 1 table, specifically any mechanism reaching n_n >~ 10^11. 137Ba/138Ba alone can't cleanly separate extreme normal AGB from true i-process progenitor here, you'd need other evidence (e.g. the accompanying C or heavier s-process abundance level, or the isotope diagnostics in Q3/Q5) to break that degeneracy.

**Discussion Q2.** Yes, qualitatively: 137Ba/138Ba climbs monotonically and only pulls decisively away from the declining 134Ba/135Ba/138Ba curves once n_n exceeds ~10^9-10^10 past ordinary s-process densities (13C pocket ~1e7, 22Ne burst ~1e8-3e8) in i-process territory. But the exact turn-on density, and the fact that this toy model can't separate 22Ne-burst-high from PIE/i-process (Q1), are model artifacts, not literal literature predictions. At least two real simplifications behind that:

1. **Single-zone, fixed total fluence.** Real AGB s-/i-process nucleosynthesis builds up over many separate, much smaller-exposure pulses with dilution/mixing in between; Section 4 notes the literature main-s fluence (tau_0~0.3 mb^-1) is ~30x larger than what this toy model uses and would drive everything except Ba138 to complete depletion. A genuine multi-pulse calculation would spread the Ba pattern out differently than one single large-fluence irradiation.
2. **No competing capture channel for 137Cs.** The code never gives 137Cs a capture pathway, it can only decay to 137Ba. A genuine third branch-point competition at 137Cs, if included, could shift exactly where the 137Ba pile-up saturates.
3. **Temperature-independent decay rates.** Real stellar beta-decay rates for these Cs isotopes are known to be enhanced at typical He-burning/i-process temperatures relative to their lab (terrestrial) values, an effect Section 2 ignores. Using lab half-lives everywhere shifts exactly which n_n each branch point opens at.

**Discussion Q3.** From Section 3's table, Ba134 and Ba136 are *s-only*; Ba135, Ba137 and Ba138 are *mixed s+r*. AGB-sourced enrichment should show up concentrated in the s-only isotopes, 134Ba and 136Ba, in proportions consistent with the model. A GCE model can therefore check: does the 137Ba/138Ba enrichment come *with* a matching 134Ba/136Ba enhancement (implying genuine s/i-process production alongside it -- AGB origin), or does it appear without any accompanying 134Ba/136Ba enhancement (which an AGB process cannot produce on its own). 

**Discussion Q4.** A few diagnostics beyond the Cs-Ba chain modelled here:

- **85Kr/86Kr** (and the related 87Rb/86Sr): 85Kr (t1/2~10.8 yr) is a classic branch point near the first s-process peak, sensitive to neutron density in essentially the same way as the Cs-Ba chain here.
- **96Zr**: only reached via a branch point at 95Zr that opens at higher densities; its presence in presolar SiC grains is a well-established high-density (i-process-leaning) indicator, directly analogous to 137Ba/138Ba in this lab.
- **Pb isotopic ratios** (206Pb/207Pb/208Pb) at the third s-process peak: sensitive to the total neutron exposure rather than the density alone.
- **176Lu/176Hf**: a well-known branch point that is primarily *temperature*-sensitive rather than density-sensitive, useful as a cross-check against density-only diagnostics like the ones used here.
- **Eu isotopes/abundance**: when considered in relation to barium (i.e., the s-process CAN make significant amounts of Eu, but that Eu will be < Ba)