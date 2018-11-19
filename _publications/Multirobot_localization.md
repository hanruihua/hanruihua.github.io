---
title: "Decentralized Cooperative Multi-Robot Localization with EKF"
collection: publications
permalink: /publications/CoT
venue: "ArXiv 2018"
date: 2018-11-19
citation: '<b>Ruihua Han</b>, Shengduo Chen, Yasheng Bu, Zhijun Lyu and Qi Hao. <i>submitted to ICRA 2019.</i>'
---


## Abstract
Multi-robot localization has been a critical problem for robots performing complex tasks cooperatively. In this paper, we propose a decentralized approach to localize a group of robots in a large featureless environment. The proposed approach only requires that at least one robot remains stationary as a temporary landmark during a certain period of time. The novelty of our approach is threefold: (1) developing a decentralized scheme that each robot calculates their own state and only stores the latest one to reduce storage and computational cost; (2) developing an efficient localization algorithm through the extended Kalman filter (EKF) that only uses observations of relative pose to estimate the robot positions; (3) developing a scheme has less requirements on landmarks and more robustness against insufficient observations. Various simulations and experiments using five robots equipped with relative pose-measurement sensors are performed to validate the superior performance of our approach.