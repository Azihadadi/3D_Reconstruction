# 3D Reconstruction from Stereo Images

## Overview
This project implements a 3D reconstruction pipeline from stereo images using feature matching, triangulation, and bundle adjustment.

## Methods
- Feature detection and matching (SIFT/SURF/Harris)
- Epipolar geometry estimation
- Sparse 3D reconstruction via triangulation
- Dense reconstruction using multi-view integration
- Optimization using Levenberg–Marquardt (bundle adjustment)

## Key Idea
Sparse reconstruction from limited views is progressively refined into dense 3D structure using multi-image constraints.

## Results
Sparse reconstruction vs dense reconstruction comparison (qualitative improvement in surface detail and completeness).

## Requirements
- MATLAB R2017a or compatible version

## How to run
Step-by-step instructions to run main script

## Reference
Based on classical Structure-from-Motion literature
