---
abstract: >-
  Eye gaze estimation has been increasingly demanded by recent intelligent systems to accomplish a range of interaction-related tasks, by using simple eye images as input. However, learning the highly complex regression between eye images and gaze directions is nontrivial, and thus the problem is yet to be solved efficiently. In this paper, we propose the Asymmetric Regression-Evaluation Network (ARE-Net), and try to improve the gaze estimation performance to its full extent. At the core of our method is the notion of ``two eye asymmetry'' observed during gaze estimation for the left and right eyes. Inspired by this, we design the multi-stream ARE-Net; one asymmetric regression network (AR-Net) predicts 3D gaze directions for both eyes with a novel asymmetric strategy, and the evaluation network (E-Net) adaptively adjusts the strategy by evaluating the two eyes in terms of their performance during optimization. By training the whole network, our method achieves promising results and surpasses the state-of-the-art methods on multiple public datasets.
publication_types:
  - "1"
authors:
  - Yihua Cheng
  - Feng Lu
  - Xucong Zhang
publication: Proceedings of the European Conference on Computer Vision
summary: "Acceptted by ECCV. "
publication_short: ECCV
title: Appearance-Based Gaze Estimation via Evaluation-Guided Asymmetric Regression
featured: false
image:
  caption: ""
  focal_point: smart
  preview_only: false
  filename: network.png
date: 2020-07-01T00:00:00Z
links:
  - icon: ""
    icon_pack: fab
    name: PDF
    url: https://openaccess.thecvf.com/content_ECCV_2018/html/Yihua_Cheng_Appearance-Based_Gaze_Estimation_ECCV_2018_paper.html
---