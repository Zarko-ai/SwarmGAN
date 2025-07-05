# DFO-GAN
# Implementation of the Dispersive Flies Optimization (DFO) algorithm with the Generative Adversarial Network (GAN).

We have provided the full implementation of the Dispersive Flies Optimization (DFO) algorithm integrated with the Generative Adversarial Network (GAN). This implementation is available in this repository, where you will find three main files:

- **GAN-DFO**: This file contains the implementation of the DFO algorithm applied to the GAN, specifically designed to optimize the selection of the latent vector ($z$) values. By leveraging DFO, we aim to identify the most suitable $z$ values that contribute to generating higher-quality images.

- **GAN-Test**: This file includes the architecture of the GAN and is responsible for generating images using the optimized $z$ values produced by the **GAN-DFO** file. The primary objective of this file is to validate and compare the image quality generated with and without the optimized latent vectors.

- **DFO-Implementation**: This file contains the standalone implementation of the DFO algorithm, separate from the GAN. It serves as a reference for understanding how the optimization process is carried out independently before being applied to the GAN framework.

