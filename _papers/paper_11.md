---
# Determines which paper appears first (lowest number (0) appears first)
sequence_id: 11

# Paper title
title: 3D-OES -- Viewpoint-Invariant Object-FactorizedEnvironment Simulators

# Paper authors
authors: Hsiao-Yu Tung, Zhou Xian, Mihir Prabhudesai, Shamit Lal, Katerina Fragkiadaki

# Link to the paper's pdf (place in the `assets/pdf/papers` directory)
pdf: 11.pdf

# # Link to a representative image for the paper (place in the `assets/img/papers` directory)
# img: default.png

# Abstract for the papers
abstract: We propose an action-conditioned dynamics model that predicts scene changes caused by object and agent interactions in a viewpoint-invariant 3D neural scene representation space, inferred from RGB-D videos. In this 3D feature space, objects do not interfere with one another and their appearance persists over time and across viewpoints. This permits our model to predict future scenes long in the future by simply “moving" 3D object features based on cumulative object motion predictions. Object motion predictions are computed by a graph neural network that operates over the object features extracted from the 3D neural scene representation. Our model generalizes well across varying number and appearances of interacting objects as well as across camera viewpoints, outperforming existing 2D and 3D dynamics models, and enables successful sim-to-real transfer.
---
