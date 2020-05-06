
<img align="right" heignt = "250" width = "250" src="images/nmr_hex.png">

# nmrrr

This script is designed for batch processing and analysis of **NMR
r**esults in **R** (nmrrr).

Use this script for:  
(a) plotting spectra  
(b) calculating relative abundance of functional groups  
(c) peak assignments

Before using this script, NMR spectra must be processed in MestreNova
(phase corrected, baseline corrected, deconvoluted, peak picked,
normalized).

-----

Example spectra:  
spectra processed in MestreNova, with automated Global Spectral
Deconvolution.  
Water peak removed during processing. Avoid using DMSO and water regions
for further analyses.

### spectra plot version 1: with banded regions for bins

This is good for visualization, not necessarily ideal for manuscripts.

![gg\_nmr1](images/spectra_1.png)

### spectra plot version 2: with bracketed regions for bins

Preferred for manuscripts.

![gg\_nmr2](images/spectra_2.png)

These bins were obtained from [Mitchell et al. 2018, *Soil
Systems*](https://doi.org/10.3390/soils2010008).  
(1) aliphatic polymethylene and methyl groups (0.6-1.3 ppm); (2) N- and
O-substituted aliphatic (1.3–2.9 ppm); (3) O-alkyl (2.9–4.1 ppm); (4)
α-proton of peptides (4.1–4.8 ppm); (5) anomeric proton of
carbohydrates (4.8–5.2 ppm); (6) aromatic and phenolic (6.2–7.8 ppm);
and (7) amide (7.8–8.4 ppm). The peak at 2.50 ppm arises from the
solvent (DMSO-d6).
