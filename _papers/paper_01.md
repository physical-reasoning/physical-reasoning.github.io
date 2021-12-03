---
# Determines which paper appears first (lowest number (0) appears first)
sequence_id: 1

# Paper title
title: Vision-based system identification and 3D keypoint discovery using dynamics constraints

# Accepted for oral presentation?
oral: 1

# Paper authors
authors: Miguel Jaques, Martin Asenov, Michael Burke, Timothy Hospedales

# Link to the paper's pdf (place in the `assets/pdf/papers` directory)
pdf: 01.pdf

# # Link to a representative image for the paper (place in the `assets/img/papers` directory)
# img: 00.png

# Abstract for the papers
abstract: This paper introduces V-SysId, a novel method that enables simultaneous keypoint discovery, 3D system identification, and extrinsic camera calibration from an unlabeled video taken from a static camera, using only the family of equations of motion of the object of interest as weak supervision. V-SysId takes keypoint trajectory proposals and alternates between maximum likelihood parameter estimation and extrinsic camera calibration, before applying a suitable selection criterion to identify the track of interest. This is then used to train a keypoint tracking model using supervised learning. Results on a range of settings (robotics, physics, physiology) highlight the utility of this approach.
---
