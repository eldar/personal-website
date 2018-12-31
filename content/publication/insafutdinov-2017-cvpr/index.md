+++
title = "ArtTrack: Articulated Multi-Person Tracking in the Wild"
date = 2017-07-26
authors = ["Eldar Insafutdinov", "Mykhaylo Andriluka", "Leonid Pishchulin", "Siyu Tang", "Evgeny Levinkov", "Bjoern Andres", "Bernt Schiele"]
publication_types = ["1"]
shortname = "insafutdinov2017cvpr"
abstract = "In this paper we propose an approach for articulated tracking of multiple people in unconstrained videos. Our starting point is a model that resembles existing architectures for single-frame pose estimation but is substantially faster. We achieve this in two ways: (1) by simplifying and sparsifying the body-part relationship graph and leveraging recent methods for faster inference, and (2) by offloading a substantial share of computation onto a feed-forward convolutional architecture that is able to detect and associate body joints of the same person even in clutter. We use this model to generate proposals for body joint locations and formulate articulated tracking as spatio-temporal grouping of such proposals. This allows to jointly solve the association problem for all people in the scene by propagating evidence from strong detections through time and enforcing constraints that each proposal can be assigned to one person only. We report results on a public “MPII Human Pose” benchmark and on a new “MPII Video Pose” dataset of image sequences with multiple people. We demonstrate that our model achieves state-of-the-art results while using only a fraction of time and is able to leverage temporal information to improve state-of-the-art for crowded scenes"
selected = false
publication = "*30th IEEE Conference on Computer Vision and Pattern Recognition (CVPR 2017)*"
venue = "CVPR, 2017 (**oral presentation**)"
url_project = "https://pose.mpi-inf.mpg.de/art-track/"
url_pdf = "https://arxiv.org/pdf/1612.01465"
url_video = "https://www.youtube.com/watch?v=TClSwDRIJUQ"
url_code = "https://github.com/eldar/pose-tensorflow"
+++

