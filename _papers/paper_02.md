---
# Determines which paper appears first (lowest number (0) appears first)
sequence_id: 2

# Paper title
title: Playful Interactions for Representation Learning

# Accepted for oral presentation?
oral: 1

# Paper authors
authors: Sarah Young, Jyotish Pari, Pieter Abbeel, Lerrel Pinto

# Link to the paper's pdf (place in the `assets/pdf/papers` directory)
pdf: 02.pdf

# # Link to a representative image for the paper (place in the `assets/img/papers` directory)
# img: default.png

# Abstract for the papers
abstract: One of the key challenges in visual imitation learning is collecting large amounts of expert demonstrations for a given task. While methods for collecting human demonstrations are becoming easier with teleoperation methods and the use of low-cost assistive tools, we often still require 100-1000 demonstrations for every task to learn a visual representation and policy. To address this, we turn to an alternate form of data that does not require task-specific demonstrations -- play. Playing is a fundamental method children use to learn a set of skills and behaviors and visual representations in early learning. Importantly, play data is diverse, task-agnostic, and relatively cheap to obtain. In this work, we propose to use playful interactions in a self-supervised manner to learn visual representations for downstream tasks. We collect 2 hours of playful data in 19 diverse environments and use self-predictive learning to extract visual representations. Given these representations, we train policies using imitation learning for two downstream tasks; Pushing and Stacking. Our representations, which are trained from scratch, compare favorably against ImageNet pretrained representations. Finally, we provide an experimental analysis on the effects of different pretraining modes on downstream task learning.
---
