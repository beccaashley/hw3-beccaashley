[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/UCB-stat-159-f25/hw3-beccaashley/main)

# LIGO Gravitational Wave Analysis - HW3

## About:

This assignment extended the LIGO Gravitational Wave Detection tutorial into a fully reproducible research package. The goal was to transform a single exploratory notebook into a structured, testable, and deployable Python project.

## Binder Link:

[![launch binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/UCB-stat-159-f25/hw3-beccaashley/main)

## MyST Link:

[https://ucb-stat-159-f25.github.io/hw3-beccaashley/](https://ucb-stat-159-f25.github.io/hw3-beccaashley/)

---

## Project Contents

This project reproduces parts of the LIGO Gravitational Wave Event tutorial, including:

- Implementation of `whiten`, `write_wavfile`, `reqshift`, and `plot_spectrogram` utilities
- Modularization of code into `ligotools/utils.py`
- Testing of these functions with Pytest
- A full MyST website built from Jupyter Notebooks
- Automated deployment via GitHub Actions

## Repository Structure

- `LOSC_Event_tutorial.ipynb`: main notebook demonstrating the workflow
- `ligotools/`: package containing reusable code
- `tests/`: unit tests for utilities
- `myst.yml`: configuration file for the MyST site
- `Makefile`: automation for environment setup and builds
