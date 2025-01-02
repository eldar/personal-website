+++
title = "Flash3D: Feed-Forward Generalisable 3D Scene Reconstruction from a Single Image"
date = 2024-08-01
authors = ["Stanislaw Szymanowicz", "Eldar Insafutdinov", "Chuanxia Zheng", "Dylan Campbell", "João F. Henriques", "Christian Rupprecht", "Andrea Vedaldi"]
publication_types = ["1"]
selected = false
shortname = "szymanowicz20253dv"
abstract = "In this paper, we propose Flash3D, a method for scene reconstruction and novel view synthesis from a single image which is both very generalisable and efficient. For generalisability, we start from a \"foundation\" model for monocular depth estimation and extend it to a full 3D shape and appearance reconstructor. For efficiency, we base this extension on feed-forward Gaussian Splatting. Specifically, we predict a first layer of 3D Gaussians at the predicted depth, and then add additional layers of Gaussians that are offset in space, allowing the model to complete the reconstruction behind occlusions and truncations. Flash3D is very efficient, trainable on a single GPU in a day, and thus accessible to most researchers. It achieves state-of-the-art results when trained and tested on RealEstate10k. When transferred to unseen datasets like NYU it outperforms competitors by a large margin. More impressively, when transferred to KITTI, Flash3D achieves better PSNR than methods trained specifically on that dataset. In some instances, it even outperforms recent methods that use multiple views as input."
publication = "* International Conference on 3D Vision  (3DV 2025)*"
venue = "to appear in 3DV, 2025"
url_pdf = "https://arxiv.org/pdf/2406.04343"
url_project = "https://www.robots.ox.ac.uk/~vgg/research/flash3d/"
url_code = "https://github.com/eldar/flash3d"
+++

