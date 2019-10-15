---
layout: page
title: Research
permalink: /research/
---
### Star formation

Dense filaments within molecular clouds are known to be sites of star formation, but the formation of the filaments themselves and their subsequent collapse are not well understood. I'm currently running magnetohydrodynamical (MHD) simulations of cylindrical converging flows of gas, and investigating how the magnetic field strength and aligment alters the resulting filament and its subsequent collapse into cores. At some point I'll also be looking at how the chemistry changes (if at all) between the different cases, in an attempt to find observational signatures of the collapse mechanism. This is conveniently similar to my master's thesis and subsequent work (Priestley, Viti & Williams 2018; Priestley, Wurster & Viti 2019), which did the same sort of thing but for prestellar cores. Our conclusions there were that wildly different models of star formation lead to essentially identical predictions for most observable quantities, although line profiles might be a more promising (and currently untested) direction.

![Magnetised filament](https://raw.githubusercontent.com/fpriestley/fpriestley.github.io/master/bfield_0069.png)

### Dust in supernovae and supernova remnants

Core collapse supernovae (CCSNe) were originally suggested as a source of dust to explain the large dust masses seen in some high redshift galaxies. While it's now fairly uncontroversial that ~0.1 solar masses of dust can be formed in typical SNe based on far-infrared (IR) observations of supernova remnants (SNRs), there is disagreement about how much can survive destruction by the reverse shock. I wrote a [new code](https://fpriestley.github.io/dinamo/) to model dust emission in SNRs (although it works for virtually any environment), and reanalysed a bunch of existing far-IR data to try and extract additional information besides the dust masses. So far this has revealed that about 50% of the clumped dust in Cassiopeia A has survived the reverse shock (Priestley, Barlow & De Looze 2019), a higher fraction than often assumed, and that micron-sized dust grains, expected to be highly resistant to destruction by sputtering, make up nearly all the dust mass in a sample of five relatively nearby SNRs (Priestley et al., submitted). I'm currently attempting to use near-IR observations of SNe shortly (a few years) after explosion to resolve arguments about when the majority of the dust is formed.

![Cas A dust SED fit](https://raw.githubusercontent.com/fpriestley/fpriestley.github.io/master/casAdust.png)

### Molecules in ionized nebulae

I previously worked on modelling molecular emission from a variety of ionized nebulae using [UCL_PDR](https://fpriestley.github.io/uclpdr/), a code I didn't write but am now in charge of. This was motivated by the discovery of ArH+ in the Crab Nebula (Barlow et al. 2013), which turns out to be highly sensitive to the charged particle ionization rate - line ratios allowed us to confirm this is 10^7 times greater than the typical interstellar value, and rule out other suggested heating sources for the molecular-emitting gas (which is actually mostly atomic; Priestley, Barlow & Viti 2017). Using a similar approach on planetary nebulae, we found that the ionizing ultraviolet radiation, which is often assumed to be fully absorbed in molecular regions, is actually vital for reproducing the observed emission line strengths (Priestley & Barlow 2018).
