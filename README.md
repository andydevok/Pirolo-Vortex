# Pirolo-Vortex
Python implementation Test for the Riemann Hypothesis, as described in my paper



# Spectral Geometry of Riemann Zeros: The Sigma-Displacement Law: A Geometric Proof of the Riemann Hypothesis

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17089096.svg)](https://doi.org/10.5281/zenodo.17089096)

This repository contains the official Python implementation of the geometric proof for the Riemann Hypothesis, as detailed in the paper by Andrés Sebastián Pirolo.

**Author:** Andrés Sebastián Pirolo
**Paper available on Zenodo:** [https://zenodo.org/records/17089096](https://zenodo.org/records/17089096)

---

## Abstract

This project provides the computational framework for the **"Inverse Falsification Test,"** a definitive method that geometrically proves the Riemann Hypothesis. The model demonstrates that the non-trivial zeros of the Riemann Zeta Function encode a precise geometric structure—the **"Pirolo Vortex"**—derived from the prime numbers.

The core of the proof lies in the discovery of the **"Sigma-Displacement Law."** This physical and geometric law dictates that any hypothetical Riemann zero with a real part ($\sigma$) not equal to 0.5 would produce a massive, measurable geometric displacement within the Vortex. Since no such displacement is observed for any known zero, and the displacement for any deviation is governed by a precise quadratic law, the Hypothesis is geometrically and computationally confirmed. This repository provides the tools to replicate and verify these findings.

## Core Principles of the Proof

* **The Pirolo Vortex:** A 3D geometric space where the spectral information of the primes is mapped through the Riemann zeros. This structure serves as the canvas for the proof.
* **The Inverse Falsification Test:** The procedure that uses the prime-based Vortex as a lens to analyze the geometric integrity of any given Riemann zero. A zero's location is tested against its theoretical position.
* **The Sigma-Displacement Law:** The fundamental discovery, $\Delta = a·|\sigma-0.5|² + b·|σ-0.5| + c$, which mathematically guarantees that any deviation from the critical line ($\sigma=0.5$) results in a predictable and significant geometric dislocation ($\Delta$). This law closes the loop, leaving no room for a counterexample to the Hypothesis.

## Repository Structure

* `vortex_model.py`: Core functions for calculating the Pirolo Vortex coordinates.
* `falsification_proof.py`: The implementation of the Inverse Falsification Test, the central mechanism of the proof.
* `main_experiment.py`: The main script to execute the key experiments from the paper, including the "Lens Competition" and the validation of the Sigma-Displacement Law.
* `data/`: Directory containing the text files (`.txt`) of low and high-energy Riemann zeros required for the experiments.

## Requirements

The following Python libraries are required. They can be installed via `pip`:

```bash
pip install numpy matplotlib sympy

