---
# Determines which paper appears first (lowest number (0) appears first)
sequence_id: 5

# Paper title
title: 3D Neural Scene Representations for Visuomotor Control

# Paper authors
authors: Yunzhu Li, Shuang Li, Vincent Sitzmann, Pulkit Agrawal, Antonio Torralba

# Link to the paper's pdf (place in the `assets/pdf/papers` directory)
pdf: 05.pdf

# # Link to a representative image for the paper (place in the `assets/img/papers` directory)
# img: default.png

# Abstract for the papers
abstract: Humans have a strong intuitive understanding of the 3D environment around us. The mental model of the physics in our brain applies to objects of different materials and enables us to perform a wide range of manipulation tasks that are far beyond the reach of current robots. In this work, we desire to learn models for dynamic 3D scenes purely from 2D visual observations. Our model combines Neural Radiance Fields (NeRF) and time contrastive learning with an autoencoding framework, which learns viewpoint-invariant 3D-aware scene representations. We show that a dynamics model, constructed over the learned representation space, enables visuomotor control for challenging manipulation tasks involving both rigid bodies and fluids, where the target is specified in a viewpoint different from what the robot operates on. When coupled with an auto-decoding framework, it can even support goal specification from camera viewpoints that are outside the training distribution. We further demonstrate the richness of the learned 3D dynamics model by performing future prediction and novel view synthesis. Finally, we provide detailed ablation studies regarding different system designs and qualitative analysis of the learned representations.
---
