---
# Determines which paper appears first (lowest number (0) appears first)
sequence_id: 6

# Paper title
title: Learning Graph Search Heuristics

# Paper authors
authors: Michal Pandy, Rex Ying, Gabriele Corso, Petar Veličković, Jure Leskovec, Pietro Liò

# Link to the paper's pdf (place in the `assets/pdf/papers` directory)
pdf: 06.pdf

# # Link to a representative image for the paper (place in the `assets/img/papers` directory)
# img: default.png

# Abstract for the papers
abstract: Searching for a path between two nodes in a graph is one of the most well-studied and fundamental problems in computer science. In numerous domains such as robotics, AI, or biology, practitioners develop search heuristics to accelerate their pathfinding algorithms. However, it is a laborious and complex process to hand-design heuristics based on the problem and the structure of a given use case. Here we present PHIL (Path Heuristic with Imitation Learning), a novel neural architecture and a training algorithm for discovering graph search and navigation heuristics from data by leveraging recent advances in imitation learning and graph representation learning. At training time, we aggregate datasets of search trajectories and ground-truth shortest path distances, which we use to train a specialized graph neural network-based heuristic function using backpropagation through steps of the pathfinding process. Our heuristic function learns graph embeddings useful for inferring node distances, runs in constant time independent of graph sizes, and can be easily incorporated in an algorithm such as A* at test time. Experiments show that PHIL reduces the number of explored nodes compared to state-of-the-art methods on benchmark datasets by 40.8% on average and allows for fast planning in time-critical robotics domains.
---
