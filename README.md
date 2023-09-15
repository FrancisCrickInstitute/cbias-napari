# Introduction to Napari
Introduction to Napari training course, run as part of the Crick Bioimage Analysis Symposium 2023

## Course slides
https://docs.google.com/presentation/d/1XMpOllcfKLbBjMX4CYpHhNL0ldemzSqWyqyY85_n-sk/edit?usp=sharing

## Creating the conda environment
To install the example conda environment run this in a terminal. If you don't have conda installed, you can obtain it here with miniconda.

`conda env create -f cbias_napari_env.yml`

This will build a conda environment with the plugins used in the demonstration. You only need to do this once, and the environment will be stored on your system ready to be activated whenever you need it. This step can take a while, so be patient!

This conda environment can be activated in a terminal by

`conda activate cbias_napari_env`

and from here you can simply type napari in the command line terminal to launch the viewer (it can take a little while first time).
