---
title: Learning Auxiliary Monocular Contexts Helps Monocular 3D Object Detection
publication_types:
  - "1"
authors:
  - admin
  - Nan Xue
  - Tianfu Wu
publication: "36th AAAI Conference on Artificial Intelligence (acceptance rate:
  1349/9020, 15%)"
publication_short: "AAAI 2022 (acceptance rate: 1349/9020, 15%)"
abstract: >-
  Monocular 3D object detection that aims to localize 3D bounding boxes in an
  input single 2D image is a highly challenging problem and remains open,
  especially when no extra information (e.g., depth, lidar and/or multi-frames)
  can be leveraged. 


  This paper proposes a simple yet effective formulation for monocular 3D object detection without exploiting any extra information. It presents the MonoCon method which learns auxiliary Monocular Contexts, as auxiliary tasks in training, to help monocular 3D object detection. 


  The key idea is that with the annotated 3D bounding boxes of objects in an image, there are rich well-posed projected 2D supervision signals available in training, such as the projected corner keypoints and their associated offset vectors with respect to the center of 2D bounding box. They should be exploited in training. Thus, the proposed MonoCon method treats those 2D contexts as auxiliary tasks in training. In implementation, it utilizes a very simple end-to-end design to justify the effectiveness of learning more monocular contexts, which consists of three components: a Deep Neural Network(DNN) based feature backbone, a number of regression head branches for learning the essential parameters used in the 3D bounding box prediction, and a number of regression head branches for learning auxiliary contexts. After training, the auxiliary context regression branches are discarded. 


  In experiments, the proposed MonoCon is tested in the KITTI monocular 3D object detection benchmark (car, pedestrian and cyclist), outperforming prior arts (including methods that use lidar, depth or multi-frame extra information) in the leaderboard by large margins on car by the time of this submission and obtaining comparable performance on pedestrian and cyclist in terms of accuracy. Thanks to the simple design, the proposed MonoCon obtains the fastest speed with 38.7 fps in comparisons. A high-level (possible) explanation of why the MonoCon performs better is provided based on the Cram`er–Wold theorem in measure theory.
draft: false
featured: true
projects:
  - monocon
slides: ""
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
summary: ""
date: 2021-12-03T15:12:14.730Z
---
