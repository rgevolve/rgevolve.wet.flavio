# rgevolve.wet.flavio

Package providing Renormalization Group Evolution matrices for the
**WET** in the **flavio** basis, following the
[wcxf](https://wcxf.github.io/) conventions for Wilson coefficient
bases.

It is a sub-package of the **rgevolve** ecosystem — a set of Python
namespace packages for fast renormalization group evolution of Wilson
coefficients in the SMEFT and the WET using the evolution matrix
formalism. See the [rgevolve organization](https://github.com/rgevolve)
for the full ecosystem and the
[`rgevolve` meta-package](https://github.com/rgevolve/rgevolve) for
installation in lockstep with the core and all companions.

<!-- BEGIN: auto-generated from data.h5 by .github/scripts/generate-readme.py — do not edit by hand -->

## Contents

This distribution bundles RG evolution matrices precomputed at
**13 scales** between **2** and
**91.1876** GeV:

| scale (GeV) |
| ----------- |
| 2 |
| 4.2 |
| 4.8 |
| 5 |
| 5.91248 |
| 8.32321 |
| 11.7169 |
| 16.4942 |
| 23.2195 |
| 32.6869 |
| 46.0145 |
| 64.7761 |
| 91.1876 |

Matrices are organised into **125 sectors** covering a total
of **3127 Wilson coefficients** (counting the real and imaginary
parts of complex coefficients separately):

| sector | # Wilson coefficients |
| ------ | --------------------- |
| `cbenue` | 10 |
| `cbenumu` | 10 |
| `cbenutau` | 10 |
| `cbmunue` | 10 |
| `cbmunumu` | 10 |
| `cbmunutau` | 10 |
| `cbtaunue` | 10 |
| `cbtaunumu` | 10 |
| `cbtaunutau` | 10 |
| `cdenue` | 10 |
| `cdenumu` | 10 |
| `cdenutau` | 10 |
| `cdmunue` | 10 |
| `cdmunumu` | 10 |
| `cdmunutau` | 10 |
| `cdtaunue` | 10 |
| `cdtaunumu` | 10 |
| `cdtaunutau` | 10 |
| `csenue` | 10 |
| `csenumu` | 10 |
| `csenutau` | 10 |
| `csmunue` | 10 |
| `csmunumu` | 10 |
| `csmunutau` | 10 |
| `cstaunue` | 10 |
| `cstaunumu` | 10 |
| `cstaunutau` | 10 |
| `cu` | 216 |
| `cucu` | 16 |
| `dF=0` | 463 |
| `db` | 216 |
| `dbcu` | 40 |
| `dbdb` | 16 |
| `dbemu` | 16 |
| `dbetau` | 16 |
| `dbmue` | 16 |
| `dbmutau` | 16 |
| `dbnuinui` | 12 |
| `dbnumunue` | 8 |
| `dbnumunutau` | 8 |
| `dbnutaunue` | 8 |
| `dbtaue` | 16 |
| `dbtaumu` | 16 |
| `etauemu` | 12 |
| `ffnuinui` | 48 |
| `ffnumunue` | 32 |
| `ffnumunutau` | 32 |
| `ffnutaunue` | 32 |
| `mue` | 148 |
| `muemutau` | 12 |
| `muenuenumu` | 4 |
| `muenuenutau` | 4 |
| `muenuinui` | 12 |
| `muenumunue` | 4 |
| `muenumunutau` | 4 |
| `muenutaunue` | 4 |
| `muenutaunumu` | 4 |
| `mutau` | 148 |
| `mutaunuenumu` | 4 |
| `mutaunuenutau` | 4 |
| `mutaunuinui` | 12 |
| `mutaunumunue` | 4 |
| `mutaunumunutau` | 4 |
| `mutaunutaunue` | 4 |
| `mutaunutaunumu` | 4 |
| `sb` | 216 |
| `sbcu` | 40 |
| `sbemu` | 16 |
| `sbetau` | 16 |
| `sbmue` | 16 |
| `sbmutau` | 16 |
| `sbnuinui` | 12 |
| `sbnumunue` | 8 |
| `sbnumunutau` | 8 |
| `sbnutaunue` | 8 |
| `sbsb` | 16 |
| `sbtaue` | 16 |
| `sbtaumu` | 16 |
| `sd` | 216 |
| `sdemu` | 16 |
| `sdetau` | 16 |
| `sdmue` | 16 |
| `sdmutau` | 16 |
| `sdnuinui` | 12 |
| `sdnumunue` | 8 |
| `sdnumunutau` | 8 |
| `sdnutaunue` | 8 |
| `sdsd` | 16 |
| `sdtaue` | 16 |
| `sdtaumu` | 16 |
| `taue` | 148 |
| `tauenuenumu` | 4 |
| `tauenuenutau` | 4 |
| `tauenuinui` | 12 |
| `tauenumunue` | 4 |
| `tauenumunutau` | 4 |
| `tauenutaunue` | 4 |
| `tauenutaunumu` | 4 |
| `ubenue` | 10 |
| `ubenumu` | 10 |
| `ubenutau` | 10 |
| `ubmunue` | 10 |
| `ubmunumu` | 10 |
| `ubmunutau` | 10 |
| `ubtaunue` | 10 |
| `ubtaunumu` | 10 |
| `ubtaunutau` | 10 |
| `udenue` | 10 |
| `udenumu` | 10 |
| `udenutau` | 10 |
| `udmunue` | 10 |
| `udmunumu` | 10 |
| `udmunutau` | 10 |
| `udtaunue` | 10 |
| `udtaunumu` | 10 |
| `udtaunutau` | 10 |
| `usenue` | 10 |
| `usenumu` | 10 |
| `usenutau` | 10 |
| `usmunue` | 10 |
| `usmunumu` | 10 |
| `usmunutau` | 10 |
| `ustaunue` | 10 |
| `ustaunumu` | 10 |
| `ustaunutau` | 10 |

<!-- END: auto-generated -->

## Installation

```bash
pip install rgevolve.wet.flavio
```

To install the core package together with all available EFT/basis
companion packages at once, use the meta-package:

```bash
pip install rgevolve
```

## License

`rgevolve.wet.flavio` is licensed under the MIT License — see [`LICENSE`](LICENSE).
