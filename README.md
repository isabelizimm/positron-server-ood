# Positron Server OpenOnDemand

An example [Open OnDemand (OOD)](https://openondemand.org/) interactive app setup for launching [Positron](https://github.com/posit-dev/positron) on an HPC cluster through your web browser.

## Overview
 
This app integrates Positron Server into an Open OnDemand portal, letting users launch a full Positron session on HPC compute nodes without any local installation. Once launched, Positron is accessible directly from your browser.
 
Positron is a data science IDE built on Code OSS with first-class support for R and Python, including a console, variable inspector, data explorer, and plot viewer.

Positron Server is available for [free for educational use cases](https://positron.posit.co/education.html).
To receive a free license, please contact academic-licenses@posit.co.
 
## Prerequisites
 
- An HPC cluster running [Open OnDemand](https://openondemand.org/) (v2.0+)
- Positron Server installed or available as a module on your cluster
- OOD system administrator access to deploy custom interactive apps

 
## Related Projects
 
- [Positron](https://github.com/posit-dev/positron) — the IDE this app serves
- [Open OnDemand](https://github.com/OSC/ondemand) — the HPC web portal framework
- [jupyter-positron-server](https://github.com/posit-dev/jupyter-positron-server) — Positron Server integration for JupyterHub


