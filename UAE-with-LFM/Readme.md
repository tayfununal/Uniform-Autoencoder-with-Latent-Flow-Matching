# Latent Flow Model (LFM)

This directory contains the implementation of the **Latent Flow Model (LFM)**, which serves as the core mechanism for the generative phase of the proposed framework.

## Overview
The LFM is designed to operate within the **latent space** constructed by the Uniform Autoencoder (UAE). By learning the distribution of the latent representations, this model facilitates the generation of high-fidelity samples.

### Key Components
* **Training:** Optimization of the flow model on the pre-trained UAE latent embeddings.
* **Generation:** Sampling mechanism used to synthesize new data points from the learned distribution.
