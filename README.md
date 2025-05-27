# When Light Strikes Copper: Unleashing Bright Ultra-fast Electron Bunches
Lee-Teng intern project -- Summer 2025

## Abstract

In June 2025, a significant upgrade to the Advanced Photon Source (APS) will unfold with the installation of a state-of-the-art ultrafast laser system. This enhancement will power a new era of bright electron generation via photoemission, enabling the production and injection of high-brightness and high-charge electron bunches into the APS complex.

This research project centers on the characterization of the new laser system—expected to produce pulses on the order of 100 femtoseconds—and its interaction with a copper photocathode. Key goals include:

- Measuring pulse duration, transverse beam size, and overall beam quality.
- Investigating the dependence of photoemission properties on laser pulse parameters.
- Optimizing conditions for maximum brightness and charge extraction.

At the crossroads of ultrafast optics, quantum mechanics, and classical electrodynamics, this hands-on project presents a rare opportunity to bridge theory and practice. Participants will:

- Conduct experiments in a state-of-the-art laboratory setting.
- Develop and apply Python-based tools for data acquisition, analysis, and automation.
- Contribute to the foundational understanding necessary for future upgrades of the APS injection system.

The outcomes of this work will not only advance the performance of the APS but also build critical skills in experimental physics, scientific computing, and accelerator technology.

## Goal 1: Measuring, Transverse Beam Size, Pulse Duration, and Overall Beam Quality of the infrared beam (week 1 to week 6)

The performance of the upgraded ultrafast laser system hinges on a thorough understanding of three critical parameters: pulse duration, transverse beam size, and beam quality. These properties not only determine the efficiency and brightness of the electron bunches generated via photoemission but also influence the stability and reproducibility of the entire injector system.

### Transverse Beam Size

Beam quality refers to the spatial coherence, stability, and mode structure of the laser beam—key factors in delivering consistent energy to the photocathode and producing high-brightness electron bunches. A central metric for quantifying beam quality is the **M² factor**, which compares the divergence of the actual beam to that of an ideal Gaussian beam (M² = 1). Values close to unity indicate a beam that can be tightly focused with minimal aberrations, critical for achieving high field intensities at the cathode surface.

Evaluation of beam quality will include:

- **Near- and far-field imaging** to observe beam shape and evolution: we will use a simple CCD camera likley a USB CCD called firefly from FLIR
- **M² measurements** using a beam propagation method: knife-edge or camera-based profiling across a known focal length; see [Siegman paper 1](https://opg.optica.org/abstract.cfm?URI=DLAI-1998-MQ1), [Siegman paper #2](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/1868/1/Defining-measuring-and-optimizing-laser-beam-quality/10.1117/12.150601.full?SSO=1), also an excellent (and free!) source is the optics textbook by [Justin Peatross and Michael Ware](https://optics.byu.edu/docs/opticsBook.pdf) 
- **Pointing stability analysis** over extended time periods: the CCD measurement can be used to extract the centroid of the beam (in addition to its size) and long term-measurement provide an assessment of beam stability. Likewise the total intensity can be used to measure the total laser energy. 
- **advanced topic: Zernicke-polynomial decomposition** to assess spatial frequency content and coherence.

Maintaining a low M² (ideally < 1.3) will help ensure reproducible photoemission conditions and optimal coupling between the laser and the photocathode. This, in turn, improves the quality and stability of the resulting electron bunches.

### Pulse Duration 

Accurate measurement of the laser pulse duration is essential for understanding the temporal structure of the emitted electron bunches. Techniques such as autocorrelation, frequency-resolved optical gating (FROG), or cross-correlation with a reference signal may be employed. A sub-100 femtosecond pulse enables generation of ultrashort electron bunches, vital for applications in time-resolved science and advanced accelerator concepts. In June we expect to receive an autocorrelator from APE; see description from the [APE website](https://www.ape-berlin.de/en/autocorrelator/pulsecheck/)

## Goal 2: Generating ultraviolet light (week 6 to week 8)
To drive photoemission from the copper photocathode, the laser system must produce light in the ultraviolet (UV) range—typically around 260–270 nm for efficient electron extraction. This is achieved through nonlinear optical processes such as second-harmonic generation (SHG) and third-harmonic generation (THG). Starting with an ultrafast infrared (IR) or visible laser (e.g., 800 nm), frequency conversion crystals such as beta barium borate (BBO) are used to generate the required harmonics. Careful alignment, phase matching, and temporal synchronization are essential to maintain high conversion efficiency and preserve pulse duration. The resulting UV pulses must retain high beam quality and short duration to ensure localized, high-field excitation of the photocathode surface.

## Goal 3: Beam on virtual photocathode plane (week 9)

## Stretch Goal 4: Understanding Photoemission Mechanisms (stretched goal week 9 if realistic pending schedule)
