Explaining Deep Learning-Based Representations of Resting State Functional Connectivity Data: Focusing on Interpreting Nonlinear Patterns in Autism Spectrum Disorder 
=====================================

This repository provides python implementation for the paper ``Explaining Deep Learning-Based Representations of Resting State Functional Connectivity Data: Focusing on Interpreting Nonlinear Patterns in Autism Spectrum Disorder''. The code is written in python with dependency in pytorch.

![figure2](figures/figure2.jpg)

![figure3](figures/figure3.jpg)

## 1. Tutorial
### 1.1. Data preparation
Please place the processed rs-fMRI files in the ``data`` folder. The directory structure and names of the processed data should be as follows:

data
- autism_age.npy
- autism_labels.npy
- autism_qc.npy
- autism_sex.npy
- autism_site.npy
- fmri_power_2011_cor.npy
- fmri_power_2011_cor_adj.npy

### 1.2. Experimental results
We provide implementation codes for training VAEs and generating main figures and results at ``train.ipynb`` and ``visualization.ipynb``, respectively. We provide pre-trained model at ``vae_nets/power_2011_combat_h80_l5_r10_ep1000``.


## 2. Package dependencies
- matplotlib=3.5.1
- nilearn=0.10.1
- numpy=1.21.5
- pandas=1.3.5
- python=3.10.12
- seaborn=0.12.2
- scipy=1.8.0
- torch=2.0.1
- torchvision=0.15.1
- tqdm=4.40.0

