# **[Reconstruction of frequency-localized functions from pointwise samples via least squares and deep learning**

This repository contains notebooks to reproduce the data and figures from [Reconstruction of frequency-localized functions from pointwise samples via least squares and deep learning]](https://arxiv.org/html/2502.09794v1) by A. Martina Neuman, Andrés Felipe Lerma-Pineda, Jason J. Bramburger, and Simone Brugiapaglia (2025).

## **Paper Abstract**
Recovering frequency-localized functions from pointwise data is a fundamental task in signal processing. We examine this problem from an approximation-theoretic perspective, focusing on least squares and deep learning-based methods. First, we establish a novel recovery theorem for least squares approximations using the Slepian basis from uniform random samples in low dimensions, explicitly tracking the dependence of the bandwidth on the sampling complexity. Building on these results, we then present a recovery guarantee for approximating bandlimited functions via deep learning from pointwise data. This result, framed as a practical existence theorem, provides conditions on the network architecture, training procedure, and data acquisition sufficient for accurate approximation. To complement our theoretical findings, we perform numerical comparisons between least squares and deep learning for approximating one- and two-dimensional functions. We conclude with a discussion of the theoretical limitations and the practical gaps between theory and implementation.

## **Repository Contents**
This repository contains five notebooks.
- [**PSWF Functions**]: This folder contains a Jupyter notebook to reproduce Figure 1 from the manuscript.
The notebook generates Prolate Spheroidal Wave Functions (PSWFs) of different orders over the interval [-1, 1].
The resulting functions are grouped by even and odd symmetry for visualization purposes.
- [**1D case**]: This folder contains notebooks that implement the reconstruction of a 1D frequency-localized function via least squares approximation and deep learning as presented in Section 4 and visualized in Figure 2.
- [**2D case**]:This folder contains notebooks that implement the reconstruction of a 2D frequency-localized function via least squares approximation and deep learning as presented in Section 4 and visualized in Figure 3.

## **Required Libraries**
All scripts and notebooks use Numpy and Tensorflow. MatPlotLib is used to plot data and results. Computations were performed using python version 3.8.3.
