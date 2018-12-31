+++
title = "Unsupervised Learning of Shape and Pose with Differentiable Point Clouds"
date = 2018-12-02
authors = ["Eldar Insafutdinov", "Alexey Dosovitskiy"]
publication_types = ["1"]
selected = false
shortname = "insafutdinov2018neurips"
abstract = "We address the problem of learning accurate 3D shape and camera pose from a collection of unlabeled category-specific images. We train a convolutional network to predict both the shape and the pose from a single image by minimizing the reprojection error: given several views of an object, the projections of the predicted shapes to the predicted camera poses should match the provided views. To deal with pose ambiguity, we introduce an ensemble of pose predictors that we then distill it to a single “student” model. To allow for efficient learning of high-fidelity shapes, we represent the shapes by point clouds and devise a formulation allowing for differentiable projection of these. Our experiments show that the distilled ensemble of pose predictors learns to estimate the pose accurately, while the point cloud representation allows to predict detailed shape models."
publication = "*Advances in Neural Information Processing Systems 31 (NIPS 2018)*"
url_pdf = "https://arxiv.org/pdf/1810.09381"
url_project = "https://eldar.github.io/PointClouds/"
url_code = "https://github.com/eldar/differentiable-point-clouds"
url_video = "https://www.youtube.com/watch?v=LuIGovKeo60"
venue = "NeurIPS, 2018"
+++

