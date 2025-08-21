---
permalink: /research/
title: "Research"
author_profile: true
---

{% include toc %}
{% include base_path %}

## Abstract

This study investigates the connections between the emission line spectra of galaxies and their morphological properties. We utilize recent JWST NIRSpec spectroscopic data in three bands to create emission line ratio diagrams. We examine two BPT diagrams showing the relationship between the $[OIII]\lambda 5007 / H\beta$ emission line ratio and the $[NII]\lambda 6584/H\alpha$ and $[SII]\lambda 6718 + 6731/H\alpha$ line ratios, respectively. We also examine two more emission line relationships: first, between the $[OIII]\lambda 5007/[OII]\lambda 3729$ and the $[SIII]\lambda 9531/[SII]\lambda 6717,6731$ emission line ratios, and the relationship between the $[OIII]\lambda 5007/[OII]\lambda 3729$ and the $[([OIII]\lambda 5007+[OII]\lambda 3729)/H\beta$ emission line ratios. We study the connections between these emission line ratios with several morphological properties: the effective radius $R_{eff}$, a measure of how compact/extended a galaxy we define as $\Delta log(R_{eff})$, each galaxy's S\'ersic index, and with the electron density of each galaxy. We find that there is a negative relationship between electron density and $\Delta log(R_{eff})$, along with a possible positive relationship between $\Delta log(R_{eff})$ and the S32 line ratio. 

## Introduction

A galaxy's spectrum is created by studying the galaxy's light after it has been dispersed into its component wavelengths. The emission lines present in a spectrum tell us incredible amounts of information about the physical processes within a galaxy, such as the rates of star formation within the galaxy, the galaxy's temperature and density, the amount and types of gas and dust in the galaxy, and more. Many of the strong lines we see in galaxy spectra come from HII regions, which are regions of space where hydrogen gas has been ionized by nearby stars. By taking flux ratios of emission line pairs close in wavelength, we can minimize the effects of dust extinction. Dust extinction is the phenomenon that occurs when light from distant objects is dimmed and reddened due to the light's interaction with dust particles in either the intergalactic and/or the interstellar medium. This effect can negatively impact our ability to analyze galaxy spectra, meaning minimizing its effects is extremely helpful to this field of study. 

The purpose of this study is to compare the results of these emission line diagnostics to morphological measurements of these galaxies. We examine the relationships between the aforementioned emission line ratios with several morphological properties: the effective radius $R_{eff}$, which is the radius of a galaxy that contains half of its light (M. Vika et al. 2015), a measure of how compact/extended a galaxy is, each galaxy's S\'ersic index, and with the electron density of each galaxy. 

The data used for this study was sourced from the Dawn James Webb Space Telescope (JWST) Archive, which is a repository of public JWST galaxy data  (A. de Graaff et al. 2025) (K. E. Heintz et al. 2024). The spectroscopic data was gathered by JWST's Near-Infrared Spectrograph (NIRSpec)  (P. Jakobsen et al. 2022).

To determine the significance of these connections, we utilized Spearman tests. These tests provide two results: first, a correlation coefficient, which is a number between $-1$ and $1$ that shows the strength of the relationship between two variables, and second, a p-value, which is a number between $0$ and $1$ that quantifies the probability of observing this result, assuming there is no relationship between the two variables. 

## Presentations & Publication

I presented initial results as a poster at the 209th Meeting of the American Astronomical Society: [Poster 156.02](https://ui.adsabs.harvard.edu/abs/2006AAS...20915602J/abstract).

I completed additional analysis as part of an undergraduate honors thesis and presented the following poster at the 2007 Colby College Undergraduate Research Symposium:

![2007 M82 PNe Research Poster]({{ base_path }}/images/m82pne_poster.png)

Download: [PDF]({{ base_path }}/files/m82pne_poster.pdf)

I published these results in [Johnson et al. 2009, ApJ, 697, 1138](https://dx.doi.org/10.1088/0004-637X/697/2/1138).

## Acknowledgements

(Some of) The data products presented herein were retrieved from the Dawn JWST Archive (DJA). DJA is an initiative of the Cosmic Dawn Center (DAWN), which is funded by the Danish National Research Foundation under grant DNRF140.

This material is based upon work supported by the National Science Foundation (NSF) under Grant Numbers AST-2149425 and AST-2446392. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the NSF.

## References

Baldwin, J. A., Phillips, M. M., & Terlevich, R. 1981, PASP, 93, 5, doi: [10.1086/130766](https://iopscience.iop.org/article/10.1086/130766)
de Graaff, A., Brammer, G., Weibel, A., et al. 2025, A&A, 697, A189, doi: [10.1051/0004-6361/202452186](https://www.aanda.org/articles/aa/full_html/2025/05/aa52186-24/aa52186-24.html)
Heintz, K. E., Watson, D., Brammer, G., et al. 2024, Science, 384, 890, doi: [10.1126/science.adj0343](https://www.science.org/doi/10.1126/science.adj0343)
Jakobsen, P., Herruit, P., Alves de Oliveira, C., et al. 2022, A&A, 661, A80, doi: [10.1051/0004-6361/202142663](https://www.aanda.org/articles/aa/full_html/2022/05/aa42663-21/aa42663-21.html)
Luridiana, V., Morisset, C., & Shaw, R. A. 2015, A&A, 573, A42, doi: [10.1051/0004-6361/201323152](https://www.aanda.org/articles/aa/full_html/2015/01/aa23152-13/aa23152-13.html)
Maiolino, R., & Mannucci, F. 2019, A&A Rv, 27, 3, doi: [10.1007/s00159-018-0112-2](https://link.springer.com/article/10.1007/s00159-018-0112-2)
Pasha, I., & Miller, T. B. 2023, Journal of Open Source Software, 8, 5703, doi: [10.21105/joss.05703](https://joss.theoj.org/papers/10.21105/joss.05703)
Sersic, J. L. 1968, Atlas de Galaxias Australes
Strom, A. L., Steidel, C. C., Rudie, G. C., et al. 2017, ApJ, 836, 164, doi: [10.3847/1538-4357/836/2/164](https://iopscience.iop.org/article/10.3847/1538-4357/836/2/164)
Vika, M., Vulcani, B., Bamford, S. P., Haubler, B., & Rojas, A. L. 2015, A&A, 577, A97, doi: [10.1051/0004-6361/201425174](https://www.aanda.org/10.1051/0004-6361/201425174)
Virtanen, P., Gommers, R., Oliphant, T. E., et al. 2020, Nature Methods, 17, 261, doi: [10.1038/s41592-019-0686-2](https://www.nature.com/articles/s41592-019-0686-2)
