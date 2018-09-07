---
layout: page
title: Basics
---
The many-body wavefunction mapping goes from $$\mathbb{R}^{6} \rightarrow \mathbb{C}$$:

$$
\Psi : (\mathbb{R}^{3})^{N} \rightarrow \mathbb{C} : (\ldots, \vec{r}_{i}, \ldots) \mapsto \Psi(\ldots, \vec{r}_{i}, \ldots), \mathrm{where}\;n = 2,
$$

but the electron density mapping goes from $$\mathbb{R}^{3} \rightarrow \mathbb{R}$$, which is a significant reduction in complexity.  But the electron density functional contains as much information about the state of the system as does the many-body wavefunction, which is everything.

So, DFT simplifies the Constant Annoyance of exchange-correlation (XC) contributions by providing a universal "generator" XC functional, which is used to derive the XC field for a given system.  The XC field is considered to be an external potential, and the electrons are considered to be non-interacting (with each other), only with the nuclei.