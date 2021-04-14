# Seismic Synthetics with Devito and GemPy
## Transform 2021 workshop Thursday, April 22 (09:00 - 11:00 BST):

* Presented by: Edward Caunt, Imperial College London
* Conference website: https://softwareunderground.org/events/transform-2021

[Devito](https://www.devitoproject.org/) is a domain specific language (DSL) and compiler for finite difference schemes, with a primary user base among the geophysics community for use in seismic modelling and processing applications. This workshop will provide attendees with an introduction to using GemPy (an open-source 3D geological modelling package) to create synthetic seismic models, which can then be used for wave propagation in Devito. The intention is to highlight the possibilites of creating sharable, editable, and reproducable models for seismic modelling experiments using freely-available tools. A breakdown of the agenda is as follows:
*Creating a geological model in GemPy with seismic properties assigned to each unit
*Bridging the geological model data to Devito
*Forward acoustic propagation using Devito
*Wavefield visualisation in 3D using PyVista

Attendees who would like a more hands-on experience with Devito can follow along using [Google Colab](https://colab.research.google.com), or on their own local machine. If the latter is preferred, installation instructionsfor Devito can be found [here](https://www.devitoproject.org/devito/download.html).

## Workshop prerequisites:
* Basic Python programming knowledge
* Basic knowledge of finite differences
* A Google account (if using Colab)

To access the workshop material:
* If using Google Colab:
    * Go to...
* If using your own device:
    * After installing Devito, in a separeate directory run `git clone https://github.com/devitocodes/transform2021.git`
    * With the `Devito` environment activated, run `jupyter notebook` and open the tutorial notebook
