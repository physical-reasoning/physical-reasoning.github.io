---
# Determines which paper appears first (lowest number (0) appears first)
sequence_id: 3

# Paper title
title: TorchDyn - Implicit Models and Neural Numerical Methods in PyTorch

# Paper authors
authors: Michael Poli, Stefano Massaroli, Atsushi Yamashita, Hajime Asama, Jinkyoo Park, Stefano Ermon

# Link to the paper's pdf (place in the `assets/pdf/papers` directory)
pdf: 03.pdf

# # Link to a representative image for the paper (place in the `assets/img/papers` directory)
# img: default.png

# Abstract for the papers
abstract: Computation in traditional deep learning models is determined by the explicit linking of select primitives e.g. layers or blocks arranged in a computational graph. Implicit neural models follow instead a declarative approach. First, a desiderata relating inputs and outputs of a neural network is encoded into constraints; then, a numerical method is applied to solve the resulting optimization problem as part of the inference pass. Existing open-source software frameworks focus on explicit models and do not offer implementations of the numerical routines required to study and benchmark this new class of models. We introduce TorchDyn, a PyTorch library dedicated to implicit learning. TorchDyn provides a standardized implementation of implicit models and the underlying numerical methods, designed to serve as stable baselines. Beyond models and numerics, the library further offers a collection of step-by-step tutorials and benchmarks designed to accelerate research and improve the robustness of experimental evaluations.
---
