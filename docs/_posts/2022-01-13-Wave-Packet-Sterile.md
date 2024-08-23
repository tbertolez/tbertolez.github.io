---
date: 2022-01-13
title: Impact of wave packet separation in low-energy sterile neutrino searches
categories:
  - Neutrino oscillations
  - Reactor neutrinos
  - Sterile neutrinos
author_staff_member: C. A. Argüelles, TBM, J. Salvadó
ref: Phys.Rev.D 107 (2023) 3, 036004
image: "/images/wpdaya.png"
arxiv: https://arxiv.org/abs/2201.05108
usemathjax: true
---

<!-- Check this for adding captions to images https://stackoverflow.com/questions/19331362/using-an-image-caption-in-markdown-jekyll 
Also to change the size of images: https://stackoverflow.com/questions/14675913/changing-image-size-in-markdown
-->

In the usual formulation of neutrino oscillations, the probability of conversion from a flavor $$ \alpha $$ to a flavor $$ \beta $$ is given by

$$
P_{\alpha\beta} = \sum_{i=1}^n |U_{\alpha i}|^2|U_{\beta i}|^2 + 2\text{Re} \sum_{j>i}U_{\alpha i}U_{\alpha j}^*U_{\beta i}^*U_{\beta j}\exp\left\{-2\pi i\frac{L}{L_{\mathrm{osc}}^{ij}}\right\},
$$

where $$U_{\alpha i}$$ is the mixing matrix, $$L$$ is the baseline of the experiment, and the oscillation length $$L_{\mathrm{osc}}^{ij}$$ is given by

$$
L_{\mathrm{osc}}^{ij} = \frac{4\pi E}{\Delta m^2_{ji}}\, .
$$

Here $E$ is the energy of the neutrino and $$\Delta m^2_{ji} = m_j^2-m_i^2$$ is the squared-mass difference between neutrino mass eigenstates. $$L_{\mathrm{osc}}^{ij}$$ is the characteristic length in which the oscillation between flavours takes place.

This expression is obtained under the assumption that neutrinos are plane waves. That is, they have definite momentum and completely undetermined position. This approximation is correct in the case of standard neutrino oscillations, however it might not be the case if BSM physics happen. 

If one takes into account the wave packet nature of neutrinos (a superposition of momenta, and localized in space), then the probability of conversion becomes

$$
P_{\alpha\beta} = \sum_{i=1}^n |U_{\alpha i}|^2|U_{\beta i}|^2 + 2\text{Re} \sum_{j>i}U_{\alpha i}U_{\alpha j}^*U_{\beta i}^*U_{\beta j}\exp\left\{-2\pi i\frac{L}{L_{\mathrm{osc}}^{ij}} - \left(\frac{L}{L_{\mathrm{coh}}^{ij}}\right)^2\right\}\, .
$$

The new term introduces an exponential damping in the oscillation amplitude, described by 

$$
L_{\mathrm{coh}}^{ij} = \frac{4\sqrt{2}E^2\sigma_x}{\Delta m^2_{ji}}\, ,
$$

where $$\sigma_x$$ is the width in position space of the neutrino wave packet. This new term can be understood as the separation of the mass eigenstates wave packets, as they have different velocities. Since the packets separate they cannot interfere anymore. Then, $$ L_{\mathrm{coh}}^{ij}$$ can be understood as the characteristic length where mass eigenstate $$i$$ and $$j$$ become separate.

The wave packet width is an unknown variable, and the most tightening experimental bound is $$\sigma_x > 2.1\times 10^{-4}\,\mathrm{nm}$$ [1]. This bound is such that it does not affect standard oscillations, but can affect low-energy sterile neutrino searches. 

![Experiments affected by wave packet formalism]({{site.url}}/images/wp-experiments.png)

In this paper we study how does the neutrino wave packet formalism affect $$\mathcal{O}(\mathrm{eV})$$ sterile neutrino searches in reactor experiments (DayaBay, NEOS, PROSPECT) and gallium experiments (BEST). We find that bounds from nuclear reactor experiments are reduced by a factor up to 5, and the allowed region from BEST expands slightly. 

![Bounds with and without the wave packet formalism]({{site.url}}/images/wpdaya.png)

Therefore, we conclude that the wave packet formalism must be checked in experimental analysis when looking for sterile neutrinos. Interestingly, this formalism helps erasing the tension between reactor and gallium experiments. However, still a stronger tension remains with solar neutrinos, which this formalism cannot address. 

---

[1] This paper has sparked a lot of [discussion](https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=refersto%3Arecid%3A2010385&ui-citation-summary=true) on what is the expected size of the neutrino wave packet, whether if it should be of atomic or nucleic size. Indeed, a wave packet the size of an atom would produce an effect not observable by present experiments, and would render the plane wave formula correct for sterile analysis too. While several estimations exist (see [Akhmedov, Smirnov](https://arxiv.org/abs/2208.03736); or [Jones et al.](https://arxiv.org/abs/2211.00026)), the most recent measurements by [Smolsky et al.](https://arxiv.org/abs/2404.03102) find $$\sigma_x > 6.2\times 10^{-3}\, \mathrm{nm}$$. However, this measurement is done through electron-capture experiments, not inverse beta decay. 

In any case, I am quite happy (even if at the start I was frightened) with the discussion this paper has sparked!
