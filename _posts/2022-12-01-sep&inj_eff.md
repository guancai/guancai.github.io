---
title: Measurement of the charge separation and injection yields
tags: PC-PEC
author: Guancai Xie
---

&emsp;The water splitting photocurrent ($J^\textrm{H2O} _\textrm{photocurrent}$) is a product of the rate of photon absorption expressed as a current density ($J _\textrm{absorbed}$), the charge separation yield of the photogenerated carriers ($\eta _\textrm{charge separation}$), and charge injection yield to the electrolyte ($\eta _\textrm{charge injection}$): 
<!--more-->

$$J ^\textrm{H2O} _\textrm{photocurrent} = J _\textrm{absorbed} \times \eta _\textrm{charge separation} \times \eta _\textrm{charge injection}$$ 

Where $\eta_\textrm{charge separation}$ is the yield of the photogenerated electrons/holes that reach the electrode/electrolyte interface or, in other words, the fraction of photogenerated electrons/holes that does not recombine with holes/electrons in the bulk of photoelectrodes. $\eta _\textrm{charge injection}$ is the yield of those electrons/holes that have reached the electrode/electrolyte interface and that are injected into the electrolyte to reduce/oxidize the water, or in other words, do not recombine with holes/electrons at surface traps. $J _\textrm{absorbed}$ is the current density converted from the absorbed photons when assuming that the absorbed photons are completely converted into electrons (APCE=100%), and it can be calculated by using the equation:

$$J_\textrm{absorbed} = e\times\int\limits_{\lambda_a}^{\lambda_b}\frac{P(\lambda)}{\frac{hc}{\lambda}}A(\lambda)d\lambda = \frac{e}{hc}\times \int\limits_{\lambda_a}^{\lambda_b} P(\lambda)A(\lambda) \lambda d\lambda ​$$

where $ \lambda_a$ is the shortest wavelength of the light emitted by the light source, $ \lambda_b$ is the wavelength of the absorption edge of the photoelectrode. $P$,$\lambda$, $h$, $c$, $e$, and $A$ are the power of incident photons, the wavelength of the incident monochromatic light, the Planck constant, the light speed, the charge of single electron, and the absorbance of the photoelectrode, respectively.  

&emsp;On the other hand, $\eta_\textrm{charge separation}$ is assumed to become 100% ($\eta_\textrm{charge injection} = 1$) in the presence of electron scavenger (usually ascorbic acid) or hole scavenger (usually H$_2$O$_2$ or Na$_2$SO$ _3$) in the electrolyte, then the photocurrent measured with scavenger in the electrolyte ($J^\textrm{scavenger} _\textrm{photocurrent}$) is a product of $J _\textrm{absorbed}$ and $\eta _\textrm{charge separation}$ only:

$$J^\textrm{scavenger} _\textrm{photocurrent}=J _\textrm{absorbed}\times\eta _\textrm{charge separation}​$$

So, the $\eta_\textrm{charge separation}$ and $\eta_\textrm{charge injection}$ can be calculated by

$$ \eta _\textrm{charge separation}= J^\textrm{scavenger} _\textrm{photocurrent} /J _\textrm{absorbed} $$

$$\eta _\textrm{charge injection}=J^\textrm{H2O} _\textrm{photocurrent}/J^\textrm{scavenger} _\textrm{photocurrent}$$



**Notes:**

1. The scavenger used should be transparent to visible and UV light, does not corrode the photoelectrode, and importantly the injection barrier is removed and the surface recombination is suppressed. (No transient photocurrent in the chopped light J-t measurement)
2. The band bending should remain the same in both electrolyte solution (with and without the scavenger), namely, the flat band potential should be the same from Mott-Schottky measurement.
3. The C program used to process the charge separation and injection yields can be downloaded from [to be added]().

 **Example:**













**Reference:**

1. Dotan, H. et al. Probing the Photoelectrochemical Properties of Hematite (α-Fe$_2$O$_3$) Electrodes Using Hydrogen Peroxide as a Hole Scavenger. *Energy Environ. Sci.* **2011**, *4* (3), 958. 

2. Li, J, et al. Superior Visible Light Hydrogen Evolution of Janus Bilayer Junctions via Atomic-Level Charge Flow Steering. *Nat. Commun.* **2016**, *7*, 11480.