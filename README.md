# Seismic Synthetics with Devito and GemPy
## Transform 2021 workshop Thursday, April 22 (09:00 - 11:00 BST):

* Presented by: Edward Caunt, Imperial College London
* Conference website: https://softwareunderground.org/events/transform-2021

[Devito](https://www.devitoproject.org/) is a domain specific language (DSL) and compiler for finite difference schemes and other stencil computations, with a primary user base among the geophysics community for use in seismic modelling and processing applications. This workshop will provide attendees with an introduction to using [GemPy](https://www.gempy.org/) (an open-source 3D geological modelling package) to create synthetic seismic models, which can then be used for wave propagation in Devito. The intention is to highlight the possibilites of creating sharable, editable, and reproducable models for seismic modelling experiments using freely-available tools. A breakdown of the agenda is as follows:
* Creating a geological model in GemPy with seismic properties assigned to each unit
* Bridging the geological model data to Devito
* Forward acoustic propagation using Devito
* Wavefield visualisation in 3D using PyVista

Attendees who would like a more hands-on experience with Devito can follow along on their own local machine. Installation instructions for Devito can be found [here](https://www.devitoproject.org/devito/download.html), however, the notebook contains the required `pip` commands for installing any non-standard modules, so you should be able to simply have have a fresh python environment called `transform2021_devito` with an ipython kernel installed.

You can alternatively follow along using [Google Colab](https://colab.research.google.com) (recommended for Windows users). Note that you will need to uncomment and run a couple of additional cells to make the 3D visualisations work, and prevent the notebook crashing.

## Workshop prerequisites:

* Basic Python programming knowledge
* Basic geological background
* Basic knowledge of finite differences
* A Google account (if using Colab)

To access the workshop material, simply open the notebook titled `creating_synthetics.ipynb` in a new Conda environment or in Google Colab. All necessary installations are contained within the notebook.

## Python environment setup:

* In a bash terminal, create the virtual environment with `python3 -m venv $PATH_TO_DIR/transform2021_devito` where `$PATH_TO_DIR` is the path to the directory where you want to put your python environment.
* Now activate the environment with `source $PATH_TO_DIR/transform2021_devito/bin/activate`
* Update `pip` with `pip install --upgrade pip`
* Install `ipykernel` with `pip install ipykernel`
* Install the kernel into the `venv` with `ipython kernel install --user --name='transform2021_devito'`
* Start the notebook with `jupyter notebook`
