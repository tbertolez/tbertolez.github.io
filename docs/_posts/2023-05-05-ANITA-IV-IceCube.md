---
date: 2023-05-05
title: IceCube and the origin of ANITA-IV events
categories:
  - Ultra-high-energy neutrinos
  - Neutrino telescopes
author_staff_member: TBM, C. A. Argüelles, I. Esteban, J. Lopez-Pavon, I. Martinez-Soler, J. Salvado
ref: JHEP 07 (2023) 005
arxiv: https://arxiv.org/abs/2305.03746
image: "/images/anita-cover.png"
usemathjax: true
---

<!-- I need to write an extract! -->

---

The ANITA-IV experiment was a balloon flying over Antarctica during December 2016. In such time, it observed four events with energies $$\sim 1\, \mathrm{EeV}$$ and incident directions $$\sim 1^\circ$$ below the horizon, with a significance $$\sim 3\sigma$$. Such events can be explained by an ultra-high-energy tau neutrino which, only through Standard Model processes, produces a tau lepton which later decays on-air.

<img src="{{site.url}}/images/sm-process-anita.png" alt="SM process"/>
*A SM origin of the ANITA anomalous events. Here, a $$\nu_\tau$$ produce a $$\tau$$ lepton that decays in-air.*

However, after ~9 years of observation, the IceCube experiment (and neither the Auger experiment) has found no signal of such events. This raises a large tension for the SM interpretation if one assumes that the flux is isotropic and not extremely centered around the ANITA-IV time of observation. 

In this paper we try to solve the tension introducing a BSM class of models which mimic the SM process, with three free parameters: the primary particle cross-section with a nucleus, $$\sigma$$, the secondary particle lifetime, $$\tau$$, and the original flux normalisation, $$\Phi$$.

<img src="{{site.url}}/images/bsm-process-anita.png" alt="BSM process"/>
*A BSM origin of the ANITA anomalous events. We parametrize a class of BSM models by incoming particles that produce, with cross section $${\sigma}$$, long-lived particles that decay with lifetime $${\tau}$$.*

First, we try to constrain this class of models from the ANITA-IV observations alone. Even if $$\Phi$$ can always be adjusted to exactly match the total number of events, their spatial distribution can constrain the parameter space. That is, if events are focused close to the horizon, this won't favor small cross-sections, which would procude a more isotropic event distribution. If we draw the ANITA-IV constraints in the parameter space, we find that ANITA-IV constrains the cross-section to be around $$\sigma 10^{-32}\, \mathrm{cm}^2$$, but it does not constraint the lifetime.

<img src="{{site.url}}/images/anita-only.png" alt="Bounds obtained from ANITA-IV only"/>
*Allowed BSM parameters from ANITA data under the diffuse-flux hypothesis, together with the required incoming N flux.*

In order to constrain the lifetime, we incorporate the absence of events in IceCube during its full time of observation. That is, which points of the parameter space can explain the 4 events of ANITA-IV, while also explaining the absence of observations of IceCube. This question constrains the parameter space to a smaller region of parameters, with $$\tau \sim 10^{-3}\, \mathrm{s}$$ and $$\Phi \sim 2\, \mathrm{km}^{-2}\mathrm{day}^{-1}$$.

<img src="{{site.url}}/images/anita-icecube.png" alt="Bounds obtained from the ANITA-IV+IceCube analysis"/>
*Allowed BSM parameters the combination of ANITA and IceCube (blue) under the diffuse-flux hypothesis, together with the required incoming particle flux. The best fit predicts 1.2 events after 9 years of IceCube operation. Although the SM-like scenario is excluded at $$\sim 3\sigma$$, BSM models may explain the ANITA anomalous events, and signals would be observable in IceCube-Gen2.*

These parameters then point towards a BSM model. For instance, one could produce a flux of particles from an ultra-heavy dark matter decay. The primary and secondary particles in the process are two fermions which constitute what is usually called _inelastic dark matter_. Finally, the portal to the SM is realized with a kinetic mixing with a dark boson.

---

I believe the interest of this paper lays on the fact that the ANITA experiment is just the first of many ultra-high-energy neutrino experiments to come. The analysis shown here is a proof-of-concept that the constraining power is real even with scarce statistics, and shows the importance of the interplay between different experiments in order to break degeneracies. Future experiments such as PUEO, GRAND or IceCube-Gen2 will shed a lot of information on these kind of events!

<!-- On December 2016, the ANITA experiment observed 4 neutrinos with energy $$\mathcal{O}(1)\, \mathrm{EeV}$$. Why IceCube saw nothing? We study BSM process in a model-independent way. -->