+++
title = "SNeS: Learning Probably Symmetric Neural Surfaces from Incomplete Data"
date = 2022-10-01
authors = ["Eldar Insafutdinov", "Dylan Campbell", "João F. Henriques", "Andrea Vedaldi"]
publication_types = ["1"]
selected = false
shortname = "insafutdinov2022eccv"
abstract = "We present a method for the accurate 3D reconstruction of partly-symmetric objects. We build on the strengths of recent advances in neural reconstruction and rendering such as Neural Radiance Fields (NeRF). A major shortcoming of such approaches is that they fail to reconstruct any part of the object which is not clearly visible in the training image, which is often the case for in-the-wild images and videos. When evidence is lacking, structural priors such as symmetry can be used to complete the missing information. However, exploiting such priors in neural rendering is highly non-trivial: while geometry and non-reflective materials may be symmetric, shadows and reflections from the ambient scene are not symmetric in general. To address this, we apply a soft symmetry constraint to the 3D geometry and material properties, having factored appearance into lighting, albedo colour and reflectivity. We evaluate our method on the recently introduced CO3D dataset, focusing on the car category due to the challenge of reconstructing highly-reflective materials. We show that it can reconstruct unobserved regions with high fidelity and render high-quality novel view images."
publication = "*European Conference on Computer Vision (ECCV 2022)*"
venue = "ECCV, 2022"
url_pdf = "https://arxiv.org/pdf/2206.06340"
url_project = "https://www.robots.ox.ac.uk/~vgg/research/snes/"
url_code = "https://github.com/eldar/snes"
+++
