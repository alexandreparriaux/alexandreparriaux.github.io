---
layout: archive
title: "Quantum Cascade Lasers"
permalink: /research/QCL/
author_profile: true
toc: true
---

Since I arrived at the Laboratoire Temps-Fréquence, I have been working on different possibilities to characterize and stabilize quantum cascade lasers (QCL). The lasers I have been using were developed by ETH Zurich, so these works are in collaboration with people from the Quantum Optoelectronics Group.


## Control by illumination of the front facet

One major work to control frequency combs based on QCLs was to study a novel actuator based on a NIR light illuminating the front facet of the QCL-chip. A full characterization of this actuator has been made and we demonstrated a tight locking of a QCL-comb line on a DFB-QCL with a 10-fold improvement of the residual phase noise [[APL-23]](#APL-23). This actuator was then used to design a master-follower dual-comb setup to study noise properties of stabilization schemes, which is difficult to perform in the MIR with other techniques [[APR-24]](#APR-24).

<p style="text-align: center;">
<img src="../lock_fnQCL_DFB.png" width="950"/>
</p>
<p style="text-align: justify;" markdown="1">
**Figure:** **(Left)** Phase noise PSD and **(Right)** RF spectrum of the beating between one QCL-comb line and a DFB-QCL depending on the stabilization method used. Adding the optical actuator results in nice improvements [[APL-23]](#APL-23).
</p>


We also demonstrated that the NIR light could be used for injection locking of the repetition frequency of a QCL-comb with enhanced performance compared to the usual electrical approach [[APL-25]](#APL-25). For this, we modulated a NIR laser using a RF generator at a frequency close to the repetition frequency of the QCL, and we illuminated the front facet. Our results are in good agreement with Adler's law of coupled oscillators.

<p style="text-align: center;">
<img src="../ORFIL.png" width="450"/>
</p>
<p style="text-align: justify;" markdown="1">
**Figure:** Set of RF spectra obtained at the electrical extraction channel of a QCL-comb when sweeping the frequency of the generator (diagonal line) to observe the bandwidth Δf where the locking occurs [[APL-25]](#APL-25).
</p>


## References

<a id="APL-25">[APL-25]</a> 
Alexandre Parriaux, Kenichi N. Komagata, Mathieu Bertrand, Mattias Beck, Valentin J. Wittwer, Jérôme Faist, and Thomas Südmeyer, *"Non-resonant optical injection locking in quantum cascade laser frequency combs,"* **APL Photonics** 10.6, 066113 (2025).
<br> DOI: [10.1063/5.0253292](https://doi.org/10.1063/5.0253292)

<a id="APR-24">[APR-24]</a> 
Alexandre Parriaux, Kenichi N. Komagata, Mathieu Bertrand, Valentin J. Wittwer, Jérôme Faist, and Thomas Südmeyer, *"Dual-Comb Interferometry for Coherence Analysis of Tightly Locked Mid-Infrared Quantum Cascade Laser Frequency Combs,"* **Advanced Photonics Research** 2024, 5, 2400006 (2024).
<br> DOI: [10.1002/adpr.202400006](https://doi.org/10.1002/adpr.202400006)

<a id="APL-23">[APL-23]</a> 
Kenichi N. Komagata, Alexandre Parriaux, Mathieu Bertrand, Johannes Hillbrand, Mattias Beck, Valentin J. Wittwer, Jérôme Faist, and Thomas Südmeyer, *"Coherent control of mid-infrared frequency comb by optical injection of near-infrared light,"* **APL Photonics** 8.8, 086110 (2023).
<br> DOI: [10.1063/5.0156861](https://doi.org/10.1063/5.0156861)








