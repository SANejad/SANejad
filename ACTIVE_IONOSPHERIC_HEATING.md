<p align="center">
  <img alt="status" src="https://img.shields.io/badge/status-active%20research-7B61FF?style=for-the-badge">
  <img alt="scope" src="https://img.shields.io/badge/public%20repo-no%20source%20code-0B7285?style=for-the-badge">
  <img alt="domain" src="https://img.shields.io/badge/domain-active%20ionosphere%20modeling-1C7ED6?style=for-the-badge">
</p>

# Active Ionospheric Heating Simulation Platform

> **A numerical research platform for studying how controlled high-frequency heating modifies the ionosphere.**

[← Back to main profile](README.md)

This project develops a simulation framework for investigating active ionospheric modification experiments using physics-based numerical modeling. The goal is to study how controlled radio-frequency heating of a localized ionospheric region can produce measurable changes in plasma density, electron temperature, conductivity, electrodynamic structure, current closure, and wave–plasma interaction conditions.

Active ionospheric modification experiments provide a rare opportunity to perturb near-Earth plasma under controlled conditions, but the resulting response is governed by a strongly coupled system. Background plasma density, magnetic-field geometry, solar and geomagnetic activity, heating altitude, deposited energy, modulation pattern, conductivity structure, and current closure all influence how the ionosphere evolves. A dedicated numerical platform is therefore needed to examine these dependencies systematically, evaluate experimental scenarios before transmission, and interpretation of observed responses.



> The core idea is that active ionospheric heating can be studied as a controlled perturbation to a coupled plasma-electrodynamic system, with its effects traced through the evolution of plasma density, electron and ion temperature, conductivity, electric fields, currents, and transport processes. In this framework, experimental heating procedures are translated into physically constrained numerical scenarios, allowing different heating geometries, background conditions, and modulation strategies to be evaluated in terms of how they shape the ionospheric response.

---

## HAARP Facility

<p align="center">
  <img src="https://www.uaf.edu/news/images/HAARParray.jpeg" alt="HAARP antenna array, UAF/GI photo by JR Ancheta" width="85%">
</p>

<p align="center"><sub>HAARP antenna array. Public UAF/GI image; photo credit: JR Ancheta. Used here only as facility context.</sub></p>

**HAARP**, the High-frequency Active Auroral Research Program, is a scientific facility operated by the University of Alaska Fairbanks for studying the ionosphere using a high-power HF phased-array transmitter and supporting diagnostics. The public purpose of this project is to develop a numerical modeling pathway that can help interpret, design, and pre-evaluate ionospheric heating procedures.


---

## What problem this project addresses

Active ionospheric experiments are scientifically powerful, but their outcomes are difficult to predict or interpret from observations alone because the plasma response depends on background density, altitude, conductivity, geomagnetic conditions, source geometry, and diagnostic coverage. This project develops a numerical workbench for translating planned heating procedures into physics-based simulation scenarios, allowing expected ionospheric responses to be explored before an experiment and compared with observations afterward.

## Scientific vision

The project follows a closed research loop: define an active-experiment concept, translate it into a numerical scenario, simulate the ionospheric response, diagnose observable signatures, and use the results to refine experiment design or interpret measurements.

---
## Platform concept

The platform is organized around five layers:

| Platform layer | Purpose |
|---|---|
| **Experimental objective** | Defines the scientific objective of an active heating procedure, including the intended perturbation, target region, and expected physical response. |
| **Background ionosphere** | Specifies the modeled plasma environment, including density, temperature, altitude structure, magnetic geometry, solar and geomagnetic activity, and location. |
| **Heating representation** | Converts active heating concepts into controlled numerical perturbations or drivers suitable for model studies. |
| **Model response** | Follows the evolution of density, temperature, conductivity, electric fields, currents, and plasma transport after the imposed perturbation. |
| **Diagnostics and interpretation** | Converts the simulated response into quantities that can be compared with expected observational signatures and physical constraints. |

The implementation is intentionally not published here.

---

## Current status

This project is active and under development.

At this stage, the public repository is meant to describe the research direction, not to release the working implementation. The main effort now is to build and test a numerical workflow for representing active ionospheric heating procedures inside a physics-based ionosphere model.

Current work includes:

- defining how the background ionosphere should be specified for each run;
- representing localized heating as a controlled perturbation to the plasma;
- testing how the modeled ionosphere responds under different heating conditions;
- developing diagnostics for density, temperature, conductivity, currents, and electrodynamic structure;
- comparing simulated signatures with what could be measured during an active experiment.

The code, tuned parameters, and internal scenario workflow are not public at this stage. Simulation figures and case studies will be added when the runs are tested and the results are ready to be shown.

---
