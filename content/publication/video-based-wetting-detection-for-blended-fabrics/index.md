---
title: Video-Based Wetting Detection For Blended Fabrics
publication_types:
  - "1"
authors:
  - admin
  - Chau-Wai Wong
publication: 2019 53rd Asilomar Conference on Signals, Systems, and Computers
abstract: Textile scientists are seeking for automated ways to understand the
  wicking phenomenon of blended fabrics from recorded videos at the pixel level.
  In response to such need, we design a video-based method for detecting pixels
  that will become wet and for estimating the timestamps of wetting events,
  which is the first step toward characterizing the wicking phenomenon. Since
  the wicking behaviors of the blended fabrics can be very different from one
  yarn to another within a small spatial region, simple frame-level thresholding
  with morphological preprocessing steps does not fit this application scenario.
  In this paper, we analyze for each pixel the color variation along the time
  for the wetting event detection. We develop an iterative merging algorithm
  rooted from the likelihood ratio test to obtain a coarse-level timestamp. The
  timestamp is then refined using a parametric curve fitted to a small
  neighborhood. Experimental results show that our automated method can achieve
  satisfactory wetting detection performance when the generated binary
  wetting-event video is compared with the raw wicking video.
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2019-11-01T17:35:03.569Z
---
Poster and demos can be found via this [link](https://people.engr.ncsu.edu/cwong9/docs/2019_asilomar_wick_poster.pdf).