# Gaussian Boson Sampling Experiments

This code simulates linear optical networks through two methods: Quantum Mechanics, which uses permanants to calculate transition amplitudes, and Stochastic Mechanics, a classical theory which uses Jones vectors to represent light.
The goal of this project is to see whether some recent "quantum advantage" experiments can be classically spoofed with high fidelity.

This repository was made by Ronak Ramachandran with help from Dr. Brian La Cour at UT Austin's [Applied Research Laboratories (ARL)](https://www.arlut.utexas.edu/) in 2022-2023.

## Quick Start Guide

First clone the repo to your local machine.

Before running anything, you will need conda. It's usually a good idea to get the entire [Anaconda toolset](https://docs.anaconda.com/anaconda/install/index.html), although it is a large installation.

Once conda is installed, you'll be able to run the following three commands in the root directory of this repo to set up your local environment:
```
conda env create -f environment.yml
conda activate arl-gbs
jupyter-notebook
```
The first of these commands can take a long time (5-10 minutes).

After running the third command, you will be provided with a link to follow. Copy-paste that link into your favorite browser, and you should be able to view and run this code in a jupyter notebook!

## Adding dependencies

If you need to install a new package to add new functionality to the codebase, you'll want to update environment.yaml so future users of this code will automatically install that package when they create the arl-gbs conda environment. 
