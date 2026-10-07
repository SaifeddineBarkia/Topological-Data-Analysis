# Topological Autoencoders (paper presentation)

> MVA (ENS Paris-Saclay) · Topological Data Analysis (2021)
> **Team:** **Saifeddine Barkia**, Siwar Mhadhbi, Eya Ghamgui

Study and presentation of [*Topological Autoencoders*](https://arxiv.org/abs/1906.00722) (Moor et al., ICML 2020), which adds a loss to autoencoders that **preserves the topological structure** of the input data in the latent space.

## Contents

- **Background:** simplicial vs **persistent homology**, and why persistence is needed when the underlying manifold is unknown and sampled discretely.
- **Method:** build **Vietoris–Rips complexes** on the input and latent point clouds, compute persistence diagrams and pairings, and map the selected pairings back to edge distances (0-dimensional features, i.e. minimum-spanning-tree edges) to get a differentiable **topological loss**.
- **Experiments and results:** the paper's comparison with standard autoencoders and classic dimensionality-reduction methods.

📊 Slides: [`Paper presentation.pptx`](./Paper%20presentation.pptx)

**Topics:** topological data analysis · persistent homology · representation learning
