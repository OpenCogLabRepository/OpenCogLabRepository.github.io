---
title: RTfMRI Neurofeedback
layout: experiment
authors: Cameron Craddock, Jonathan Lisinski, Stephen M. LaConte
repository: https://github.com/OpenCogLabRepository/RTfMRI-neurofeedback
environment: VisionEgg
category: neurofeedback
version: 1.0
published: 2013
license: MIT
dependencies: afni real time plugin, RT-functor, visionegg
imgurl: https://raw.githubusercontent.com/OpenCogLabRepository/RTfMRI-neurofeedback/master/analog_meter_half.png
bibtex: https://raw.githubusercontent.com/OpenCogLabRepository/RTfMRI-neurofeedback/master/RTfMRIneurofeedback.bib
download: https://zenodo.org/record/61454/files/RTfMRI-neurofeedback-v1.0.1.zip
---
[![DOI](https://zenodo.org/badge/9342/OpenCogLabRepository/RTfMRI-neurofeedback.svg)](https://zenodo.org/badge/latestdoi/9342/OpenCogLabRepository/RTfMRI-neurofeedback)

This stimulus was developed for conducting real-time fMRI based default mode network neurofeedback experiments (Craddock et al. 2012, LaConte et al. 2011).

The Neurofeedback task stimulus is implemented in Python using the [VisionEGG](http://visionegg.org/) library. The script displays the current level of activity, received from a TCP connection, of a brain area or network using an analog meter. On the meter, zero is straight up and down, and negative and positive values are on either side. The left and right side of the scale are labeled with strings that describe a behavior that is associated with the level of activity. For example, in the default mode network (DMN) example, low activity is referred to as "Focused" and high activity is "Wandering". The current task instruction is centered beneath the meter in a large font.

See the [repository README](https://github.com/OpenCogLabRepository/RTfMRI-neurofeedback) for more information.
