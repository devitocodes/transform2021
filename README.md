# Seismic Synthetics with Devito and GemPy
## Transform 2021 workshop Thursday, April 22 (09:00 - 11:00 BST):

* Presented by: Edward Caunt, Imperial College London
* Conference website: https://softwareunderground.org/events/transform-2021

[Devito](https://www.devitoproject.org/) is a domain specific language (DSL) and compiler for finite difference schemes, with a primary user base among the geophysics community for use in seismic modelling and processing applications. This workshop will provide attendees with an introduction to using GemPy (an open-source 3D geological modelling package) to create synthetic seismic models, which can then be used for wave propagation in Devito. The intention is to highlight the possibilites of creating sharable, editable, and reproducable models for seismic modelling experiments using freely-available tools. A breakdown of the agenda is as follows:
*Creating a geological model in GemPy with seismic properties assigned to each unit
*Bridging the geological model data to Devito
*Forward acoustic propagation using Devito
*Wavefield visualisation in 3D using PyVista

Attendees who would like a more hands-on experience with Devito can follow along on their own local machine, ideally using Andaconda. Installation instructions for Devito can be found [here](https://www.devitoproject.org/devito/download.html), however, the notebook contains the required `pip` commands for installing any non-standard modules, so simply make sure you have a fresh conda environment called `transform2021` with an ipython kernel installed. If you have issues installing into a Conda environment, one alternative is a Python `venv`. Note that you can alternatively follow along using [Google Colab](https://colab.research.google.com). However, trying to make any 3D plots with GemPy or PyVista will cause a crash, so bear this in mind.

## Workshop prerequisites:
* Basic Python programming knowledge
* Basic knowledge of finite differences
* A Google account (if using Colab)

To access the workshop material, simply open the notebook titled `creating_synthetics.ipynb` in a new Conda environment. All necessary installations are contained within the notebook.
