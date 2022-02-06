---
title: Lab 3 - Iris
weight: 0
description: Biometrics - iris segmentation, pupil segmentation, iris recognition.
---

# Iris recognition

Identifying the characteristics of the iris is a similar process to identifying it with the facial pattern and fingerprint. The system segments the image of the iris and then converts it into a pattern which is compared with the pattern. Iris readers often use an additional system to illuminate the eye with near-infrared light.

{{< youtube XI066IGEONw >}}

## Pre-read (Required)

- https://www.tensorflow.org/addons/tutorials/losses_triplet
- https://www.tensorflow.org/tensorboard/tensorboard_projector_plugin
- https://www.v7labs.com/blog/image-segmentation-guide

## Demo project

{{< include-html "content/docs/labs/iris/index.html" >}}

## Class content

- Introduction to the segmentation and related metrics (IoU, Dice score).
- Analysis of classic algorithms for automatic detection and segmentation of the iris (Geodesic Active Contours, SuperPixel Segmentation - SPS, Hough Transform).
- Construction of the U-NET network for iris segmentation on the CASIA V 4.0 set.
- Transformation of the iris image to the Cartesian coordinate system
- Extracting features with the Gabor filter. Analysis of the influence of light on the pattern.
- Use Hamming distance to calculate the distance between vectors
- Build iris embedding (a vector that represents the features extracted from the iris).
- Create Deep Neural Network that creates a mapping from iris images to a compact Euclidean space where distances directly represent iris similarity.
