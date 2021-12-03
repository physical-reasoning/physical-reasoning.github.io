---
# Determines which paper appears first (lowest number (0) appears first)
sequence_id: 7

# Paper title
title: Physics-guided Learning-based Adaptive Control on the SE(3) Manifold

# Paper authors
authors: Thai P Duong, Nikolay A Atanasov

# Link to the paper's pdf (place in the `assets/pdf/papers` directory)
pdf: 07.pdf

# # Link to a representative image for the paper (place in the `assets/img/papers` directory)
# img: default.png

# Abstract for the papers
abstract: In real-world robotics applications, accurate models of robot dynamics are critical for safe and stable control in rapidly changing operational conditions. This motivates the use of machine learning techniques to approximate robot dynamics and their disturbances over a training set of state-control trajectories. This paper demonstrates that inductive biases arising from physics laws can be used to improve the data efficiency and accuracy of the approximated dynamics model. For example, the dynamics of many robots, including ground, aerial, and underwater vehicles, are described using their $SE(3)$ pose and satisfy conservation of energy principles. We design a physically plausible model of the robot dynamics by imposing the structure of Hamilton's equations of motion in the design of a neural ordinary differential equation (ODE) network. The Hamiltonian structure guarantees satisfaction of $SE(3)$ kinematic constraints and energy conservation by construction. It also allows us to derive an energy-based adaptive controller that achieves trajectory tracking while compensating for disturbances. Our learning-based adaptive controller is verified on an under-actuated quadrotor robot.
---
