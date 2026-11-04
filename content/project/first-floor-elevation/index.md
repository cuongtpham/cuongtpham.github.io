
---
title: "AI-Based First-Floor Elevation Estimation"
date: 2026-11-03
summary: "Estimating building first-floor heights using street-view imagery, computer vision, and geometric projection."
tags:
  - Computer Vision
  - Deep Learning
  - Structural Engineering
  - Python
  - Natural Hazards
---

## Overview

This project develops a computer vision-based approach to estimate the first-floor height (FFH) of elevated residential buildings using street-view imagery.

The approach combines object detection and geometric projection to derive building elevation information that can support infrastructure inventory development and coastal flood risk assessment.

## Methodology

The workflow consists of three main components:

1. **Image analysis:** Detecting relevant building features, including doors and foundations, using YOLO-based object detection.
2. **Geometric estimation:** Estimating first-floor height from image measurements using geometric projection.
3. **Validation:** Comparing AI-derived estimates with reference measurements and evaluating prediction errors.

## Key Results

The method was evaluated using 96 elevated residential buildings in Dauphin Island, Alabama.

- Mean Absolute Error (MAE): **0.306 m**
- Root Mean Square Error (RMSE): **0.369 m**
- Normalized MAE: **9.5%**

## Applications

The estimated building elevations can be used to improve building inventory information and support community-scale coastal flood damage and economic loss assessments.

## Tools and Technologies

Python, YOLOv11, Deep Learning, Computer Vision, and Geometric Projection.
