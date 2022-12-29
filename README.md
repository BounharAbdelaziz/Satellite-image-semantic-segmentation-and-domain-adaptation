# Introduction

This work is done in the context of the [FLAIR](https://codalab.lisn.upsaclay.fr/competitions/8769 ) challenge which consist on building an efficient neural network capable of doing semantic segmentation of satellite imagery. By efficient we mean that we seek for an architecture that is resilient to domain shift, i.e. change of the camera lens, the period of the year, etc.

<img src="./for_readme/example.png"/>

# Dataset 

The FLAIR-one dataset consists of 77,412 high resolution (0.2 m spatial resolution) patches with 13 semantic classes (19 original classes remapped to 13, see the associated [paper](https://arxiv.org/pdf/2211.12979.pdf) for more details). The dataset covers a total of approximatly 800 km², with patches that have been sampled accross the entire metropolitan French territory to be illustrating the different climate and landscapes (spatial domains). The aerial images included in the dataset were acquired during different months and years (temporal domains).

<img src="./for_readme/FR_ortho_and_dataset.png"/>

# Suggested papers to read

# Trained architectures

A table summarizing the mean Intersection over Union (mIoU) scores of each experiment
