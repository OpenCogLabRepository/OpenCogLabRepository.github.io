---
title: RTfMRI Neurofeedback
layout: experiment
authors: Cameron Craddock
repository: https://github.com/OpenCogLabRepository/RTfMRI-neurofeedback
environment: VisionEgg
category: modulation of DMN, neurofeedback
version: 1.0
published: 2013
license: MIT
dependencies: afni real time plugin, RT-functor, python
imgurl: https://avatars2.githubusercontent.com/u/10687121?v=3&s=200
bibtex: RTfMRIneurofeedback.bib
download: https://github.com/OpenCogLabRepository/RTfMRI-neurofeedback/archive/master.zip
---

In the real-time Neurofeedback (RT-NFB) task, fMRI data are processed as they are being collected, allowing the experimenter to provide visual feedback of brain activity during the course of the experiment. The RT-NFB task in the NFB protocol was developed in such a way to examine individual participant’s ability to either increase or decrease DMN activity in response to instructions, accompanied by real-time feedback of activity from their own DMN. Participants first undergo a short, “training” scan, during which they are giving traditional ‘resting state’ instructions. The resting state fMRI data was analyzed, using a spatial template, which identifies a canonical DMN region26, along with a support vector regression (SVR) method that permits participant-specific weighting of activation in pre-defined regions from the template27. The result is a DMN map that is tailored to the individual participant, based on pre-existing expectations about DMN anatomy and function.
During the RT-NFB task, participants are shown an analog meter (with Wander at one end and Focus at the other), along with an indicator of their current performance. The fixation point is equally between the two poles. Participants are instructed at the beginning of each of several blocks to either attempt to focus their attention (Focus) or let their mind wander (Wander).