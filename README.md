# Full Waveform Inversion (FWI) for Brain Imaging

This repository contains an open-source implementation of Full Waveform Inversion (FWI) for neuroimaging and breast imaging applications. FWI is a powerful computational technique that uses acoustic wave data to reconstruct detailed internal structures. Our primary goal is to create an accessible, scalable FWI solution for research in neurotechnology and cancer detection.

## Project Overview

FWI is traditionally used in geophysical exploration, but its high-resolution capabilities also hold promise in medical imaging. We applied FWI to model MNI152 NIfTI brain (MNI152 T1 template from nilearn). We start with a known skull model. This allows us to refine imaging accuracy and performance in a simpler anatomical model before advancing to skull imaging. 

## Tech Stack
- **j-Wave**: Differentiable acoustic simulation framework.
- **JAX**: High-performance numerical computing with function tracing and Autodiff.
- **NFTIT Model**: Professional-grade 3D numerical head template for ultrasound research.

Please feel free to refine or develop new code! 

