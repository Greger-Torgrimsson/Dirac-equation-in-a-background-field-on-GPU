# Scattered-wave-function (SWF) approach for strong-field QFT in curved spacetimes and electromagnetic fields

JAX implementations of scattered-wave-function methods for strong-field-QFT processes in curved spacetimes and electromagnetic background fields.

**Author:** Greger Torgrimsson


## Contents

### jaxGRandQED.ipynb

Computes the probability of pair production in general curved spacetimes and/or electromagnetic background fields, assuming trivial holonomy.
Used in [3].

### jaxGR.ipynb 

Computes the probability of pair production in curved spacetimes with metrics of the inflation or Gullstrand-Painlevé form.
Allows for metrics with nontrivial holonomy.
Used in [3].

### jaxBWplaneWaveGH.ipynb 

Computes the probability of nonlinear Breit-Wheeler pair production in 1+1 dimensions.
"planeWave" refers to the high-energy photon, not the background field.
Used in [2].

### jaxSchwingerGH.ipynb 

Computes probability of Schwinger pair production. (This is an updated code that is much faster than DiracGPU.ipynb.)
Used in [2].


## References

The underlying SWF methods were developed in:

1. Greger Torgrimsson,\
**Momentum correlation in pair production by spacetime-dependent fields from scattered wave functions**\
Phys. Rev. D **112**, 116011 (2025)


2. Greger Torgrimsson,\
**Solving the Dirac equation on a GPU for strong-field processes in multidimensional background fields**\
arXiv:2512.16889 [hep-ph]

3. P. Semren and G. Torgrimsson,\
**Scattered wave functions and worldline instantons for particle production in curved spacetime**\
(to appear)
