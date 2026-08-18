# prismPYP Reproduction

Reproduction and exploration of:

**He, L. & Bartesaghi, A. (2026).  
prismPYP: Power-spectrum and image domain learning for self-supervised micrograph evaluation.  
Structure 34, 988–999.**

## Motivation

This project explores self-supervised representation learning for
quality assessment of cryo-EM micrographs without requiring manual
image-quality labels.

## Original Method

prismPYP uses two representation-learning branches:

1. Real-domain micrographs
2. Fourier-domain power spectra

The learned representations are visualized and clustered to identify
high-quality micrographs, followed by consensus filtering across the
two domains.

## Reproduction Goals

- [x] Understand the cryo-EM image-quality problem
- [x] Understand real-domain self-supervised representation learning
- [ ] Reproduce real-domain representation learning
- [ ] Reproduce Fourier-domain representation learning
- [ ] Reproduce embedding visualization and clustering
- [ ] Reproduce consensus filtering
- [ ] Compare reproduced results with the paper
- [ ] Explore a small extension motivated by the paper

## Status

Work in progress.