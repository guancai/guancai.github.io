---
title: Metrics for evaluating PEC performance
tags: PC-PEC
author: Guancai Xie
---

&emsp;By definition, the efficiency for any process that converts energy from one form to another is the ratio of the total power output to the total power input. For PEC systems, the **solar-to-hydrogen (STH) efficiency** is the single value by which all PEC devices can be reliably ranked against one another, which can be directly determined by analysis of the hydrogen formed under solar AM 1.5G illumination <u>in the absence of an applied bias</u>. For a correct STH efficiency measurement, the working electrode (WE) and counter electrode (CE) should be short-circuited, which infers that STH is <u>measured in a 2-electrode system</u>. Besides, one must have both the WE and CE immersed in the same pH solution. In addition, <u>the electrolyte should not contain any sacrificial donors or acceptors</u>. <!--more-->

STH can be calculated from the product of the rate of hydrogen production $r_\textrm{H$_2$}$ (mmol/s) and the gain in Gibbs energy $\Delta G$ (237 kJ mol$^{−1}$).

​                                                  

where $P_\textrm{total}$ is the energy flux of the sunlight (mW/cm$^2$) and *S* is the illuminated photoelectrode area (cm$^2$). Or, it can be calculated from the product of voltage, current, and the **faradaic efficiency** for hydrogen evolution $\eta _F$.

   

where$ J_\textrm{SC}$ is the short-circuit photocurrent density (mA/cm$^2$) normalized to the illuminated electrode area.

 

&emsp;For PEC systems that require an external bias to split water, $\eta_\textrm{STH}$ is zero. However, other metrics are invaluable scientifically and can be employed to provide insight into the functionality and limitations of a PEC device. These metrics including applied-bias photon-to-current efficiency (ABPE), half-cell solar-to-hydrogen efficiency (HC-STH), external quantum efficiency (EQE) = incident photon-to-current efficiency (IPCE), and internal quantum efficiency (IQE) = absorbed photon-to-current efficiency (APCE) are called diagnostic efficiencies.

 

&emsp;**ABPE** measures the net chemical output power (rate of production of free energy of products less the input electrical power) of a system in units of incident solar power, and it represents the fraction of the energy stored in the chemical products that can be assigned to the photovoltage provided by the input solar illumination. It is frequently used for two-electrode measurements when an external voltage is applied to PEC systems as the electrical energy has to be subtracted from the energy gain. As with STH, ABPE measurements also require that both the WE and CE should be immersed in the same pH solution and the electrolyte should not contain any sacrificial donors or acceptors. ABPE is the difference of the power output in chemical fuel and any added electrical input power, divided by the solar power input.

   

where Jph (mA/cm$^2$) is the photocurrent density obtained under an applied bias Vb (V).

 

&emsp;For a photoanode (photocathode) measured in the three-electrode configuration, the product of the potential gain and the photocurrent could be regarded as the hypothetical **HC-STH**. The gain in potential by PEC water splitting could be approximated by the difference of the potential of a photoanode (photocathode) from the oxygen (hydrogen) equilibrium potential:

   

where Eb is the applied potential (*vs.* RHE). *E*O2/H2O and *E*H+/H2 stand for the equilibrium potentials of oxygen evolution (+1.23 V *vs.* RHE) and hydrogen evolution (0 V *vs.* RHE), respectively. Provided that *η*F of PEC water splitting is unity and that a counter electrode drives the counter reaction without any overpotential, HC-STH is a convenient estimate of maximum ABPE of a half-cell independent of properties of a counter electrode. In reality, however, the potential of a counter electrode is not equilibrated with the potential of the redox reaction on the counter electrode as mentioned in the previous section. Therefore, HC-STH should not be regarded as ABPE.

 

&emsp;**IPCE** describes the photocurrent collected per incident photon flux as a function of illumination wavelength. The researcher can ideally integrate the IPCE data over the solar spectrum to estimate the maximum possible STH efficiency for that device, but only for the IPCE data collected under zero bias (2-electrode, short-circuit) conditions. IPCE under an applied bias is not considered a valid estimate for STH, but it is still a useful diagnostic tool that gives insight into the PEC material properties because it yields device efficiency in terms of “electrons out per photons in”. IPCE takes into account efficiencies for three fundamental processes involved in PEC: photon absorptance, defined as the fraction of electron-hole pairs generated per incident photon flux (ηe­-/h+), charge transport to the solid-liquid interface (ηcharge separation), and the efficiency of interfacial charge transfer (ηcharge injection). This method assumes that the counter electrode is not limiting current flowing through the circuit.

   

where 

   

where A is the absorbance of a sample defined as the logarithmic ratio of the measured output light intensity (I) versus the initial input light intensity (I0).

  IPCE is usually obtained from a chronoamperometry (potentiostatic) measurement. In this system, a bias can be applied between the sample/working electrode versus a counter electrode (2-electrode experiment) or a reference electrode (3-electrode experiment) while measuring the current that arises from subjecting the PEC electrode to monochromatic light at various wavelengths. The difference between the steady-state current under monochromatic illumination and the steady-state background current is the photocurrent that arises due to redox reactions occurring at the surface of the working and counter electrodes. 

   

where Pmono is the calibrated and monochromated illumination power intensity (mW/cm$^2$), and λ (nm) is the wavelength at which this illumination power is measured. Besides, the integration of IPCE over the entire solar spectrum can provide an estimation of the maximum possible STH, if (and only if) no applied bias is used in the IPCE measurement.

 

 &emsp; **APCE** describes the photocurrent collected per incident photon absorbed. This value is a particularly useful quantity to measure when studying thin films, because it helps to determine the optimum balance between maximal path length for photon absorption versus minimal effective carrier transport distance within the material.

   

By combining the equations for determining IPCE and ηe­-/h+ experimentally, we can derive APCE as follows:

   

 

Reference:

1. Chen Z, et al. Accelerating materials development for photoelectrochemical hydrogen production: Standards for methods, definitions, and reporting protocols. J. Mater. Res., 2010, 25(01): 3-16.

2. Hisatomi T, et al. Recent advances in semiconductors for photocatalytic and photoelectrochemical water splitting. Chem. Soc. Rev., 2014, 43(22): 7520-7535.