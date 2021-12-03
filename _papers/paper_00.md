---
# Determines which paper appears first (lowest number (0) appears first)
sequence_id: 0

# Paper title
title: Efficient and Interpretable Robot Manipulation with Graph Neural Networks

# Accepted for oral presentation?
oral: 1

# Paper authors
authors: Yixin Lin, Austin S Wang, Eric Undersander, Akshara Rai

# Link to the paper's pdf (place in the `assets/pdf/papers` directory)
pdf: 00.pdf

# # Link to a representative image for the paper (place in the `assets/img/papers` directory)
# img: 00.png

# Abstract for the papers
abstract: Manipulation tasks like loading a dishwasher can be seen as a sequence of spatial constraints and relationships between different objects. We aim to discover these rules from demonstrations by posing manipulation as a classification problem over a graph, whose nodes represent task-relevant entities like objects and goals. In our experiments, a single GNN policy trained using imitation learning (IL) on 20 expert demonstrations can solve blockstacking and rearrangement tasks in both simulation and on hardware, generalizing over the number of objects and goal configurations. These experiments show that graphical IL can solve complex long-horizon manipulation problems without requiring detailed task descriptions.
---
