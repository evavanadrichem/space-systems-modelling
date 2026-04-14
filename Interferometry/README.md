# Interferometric Image Reconstruction

## Overview
This project simulates image reconstruction from partial Fourier sampling, modelling the behaviour of a multi-element interferometric system.

## Key Features
- 2D Fourier transform analysis of image data  
- Construction of uv-plane sampling for a 128-element interferometer  
- Reconstruction of images from incomplete frequency information  

## Approach
The spatial frequency content of a lunar image is analysed using a Fourier transform. A simulated interferometer samples a subset of the frequency domain, and the image is reconstructed using inverse transforms.

## Outcome
The project demonstrates how incomplete sampling leads to reconstruction artefacts and loss of detail, highlighting the importance of baseline distribution and frequency coverage.

See the main notebook for full simulation and results.
