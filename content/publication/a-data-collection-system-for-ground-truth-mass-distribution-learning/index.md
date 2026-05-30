---
title: A Data Collection System for Ground-Truth Mass Distribution Learning
publication_types:
  - "7"
authors:
  - Michele Morisco
publication: MSc Degree
abstract: >-
  Extended Reality, including Virtual Reality, Augmented Reality, and Mixed
  Reality, enables immersive interaction but still lacks realistic physical
  behavior in virtual objects, such as mass and weight. In particular, current
  virtual environments cannot largely represent and simulate intrinsic physical
  properties such as mass distribution and weight, which are essential for
  achieving truly immersive and physically consistent experiences. This thesis,
  developed to assist with some objectives of the EU-funded Social and
  Human-centered XR project, proposes a system for estimating mass distribution
  to generate high-quality ground-truth data for learning-based applications.
  The proposed system integrates both hardware and software components to enable
  scalable, accurate, and repeatable data acquisition.
      The hardware setup consists of a multi-camera acquisition box with four calibrated cameras, a passive hand-shaped gripper equipped with force sensors, and a modular 3D-printed object with configurable internal mass distributions. These components are coordinated through a central control unit. The software framework is divided into two modules: a synchronized data acquisition module and a computer vision module. The following performs camera calibration, object pose estimation, and gripper fingertip tracking using fiducial markers, producing precise affine transformation matrices. The system is designed to automate data acquisition for estimating inertial properties, with a focus on accuracy and scalability. Experimental results demonstrate an acceptable baseline of the proposed approach in estimating object and gripper poses and highlight the system’s potential to support learning-based models that incorporate physical properties into virtual environments. This work contributes a solid baseline for data acquisition in XR applications and lays the basis for future research on embedding realistic physical behavior into virtual objects.
draft: false
featured: false
tags:
  - Thesis
  - XR
  - Computer Vision
  - OpenCV
  - "2026"
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: The proposed system in a frame.
summary: MSc thesis proposes a system for estimating mass distribution to
  generate high-quality ground-truth data for learning-based applications.
date: 2026-05-30T15:14:13.545Z
url_slides: /uploads/MSc Thesis/Thesis_Presentation.pdf
url_code: "https://github.com/michisco/SUN-Tool"
---
