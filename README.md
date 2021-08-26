# EMAtutorial
This repository contains a set of .ipynb files to walk-through the use of EMAWorkbench to do exploratory modeling.
These files can be run using Google Colab.

SEIR.ipynb: Show simulation of SEIR epidemic dynamics modeling using scipy's odeint

EMA-SEIRBase.ipynb: Designed to teach you the basic capabilities and steps in using EMA: define the EMA wrapper for the simulation by specifying the parameter uncertainties; perform experiments and visualisation of results. Uses a SEIR model.

EMA-SEIRPolicy.ipynb: Designed to teach you to do analysis using EMA workbench: define policy levers in addition to parameter uncertainties; perform experiments, and do feature scoring and scenario discovery. Use a SEIQR model.

EMA-VensimPySD.ipynb: Designed to teach how to import a Vensim model using PySD, and then call that using EMA.  Uses a DMC-OptClass.mdl.

"EMAWorkbench" is an open source python package that helps perform exploratory modeling with models developed in various modelling packages and environments such as Python, Vensim, Excel, etc.
