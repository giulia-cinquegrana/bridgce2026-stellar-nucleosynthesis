# Observed abundances

## `decastro2016_bastars.csv`

Homogeneous photospheric abundances for 182 barium giants and candidates from

> de Castro, D.B., Pereira, C.B., Roig, F., Jilinski, E., Drake, N.A., Chavero, C.,
> Sales Silva, J.V. (2016), *Chemical abundances and kinematics of barium stars*,
> MNRAS 459, 4299. CDS catalogue `J/MNRAS/459/4299`.

Compiled here from the CDS machine-readable tables:

| column | source table | notes |
|---|---|---|
| `Teff`, `logg`, `FeH`, `e_FeH` | table3 | `FeH` = [Fe I/H] |
| `Na Mg Al Si Ca Ti Cr Ni`      | table7 | [X/Fe] |
| `Y Zr La Ce Nd`, `sFe`, `hsls` | table8 | [X/Fe]; `sFe` = mean of the five s-elements; `hsls` = [hs/ls] |
| `Mass_dC16`, `logL`            | table12 | de Castro et al. spectroscopic mass & luminosity |

Blank cells = not measured for that star. LTE, Kurucz atmospheres, MOOG.
There is no per-star, per-element error table in the paper; the lab uses
representative 1-sigma errors (~0.10-0.20 dex) from their error analysis (sect. 4.4).

Used by `../../lab_agb_masstransfer.ipynb`. Four stars are hard-coded in that
notebook; the rest of the sample is here for extensions.
