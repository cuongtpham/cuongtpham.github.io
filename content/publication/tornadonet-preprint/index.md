---
title: 'TornadoNet: Real-Time Building Damage Detection with Ordinal Supervision'
authors:
- Umeike, R.
- admin
- Hausen, R.
- Dao, T.
- Crawford, S.
- Brown-Giammanco, T.
- Lemson, G.
- van de Lindt, J. W.
- Johnston, B.
- Mitschang, A.
- Do, T.
date: '2026-03-01'
publication_types:
- manuscript
publication: '*arXiv preprint*, arXiv:2603.11557 (2026).'
publication_short: arXiv preprint
summary: An arXiv preprint benchmarking real-time post-tornado damage detection with ordinal-aware supervision.
tags:
- Preprint
- Tornado Damage
- Deep Learning
- Computer Vision
links:
- type: Preprint
  url: https://arxiv.org/abs/2603.11557
---
### Abstract
 We present TornadoNet, a comprehensive benchmark for automated street-level building damage assessment evaluating how modern real-time object detection architectures and ordinal-aware supervision strategies perform under realistic post-disaster conditions. TornadoNet provides the first controlled benchmark demonstrating how architectural design and loss formulation jointly influence multi-level damage detection from street-view imagery, delivering methodological insights and deployable tools for disaster response. Using 3,333 high-resolution geotagged images and 8,890 annotated building instances from the 2021 Midwest tornado outbreak, we systematically compare CNN-based detectors from the YOLO family against transformer-based models (RT-DETR) for multi-level damage detection. Models are trained under standardized protocols using a five-level damage classification framework based on IN-CORE damage states, validated through expert cross-annotation. Baseline experiments reveal complementary architectural strengths. CNN-based YOLO models achieve highest detection accuracy and throughput, with larger variants reaching 46.05% mAP@0.5 at 66-276 FPS on A100 GPUs. Transformer-based RT-DETR models exhibit stronger ordinal consistency, achieving 88.13% Ordinal Top-1 Accuracy and MAOE of 0.65, indicating more reliable severity grading despite lower baseline mAP. To align supervision with the ordered nature of damage severity, we introduce soft ordinal classification targets and evaluate explicit ordinal-distance penalties. RT-DETR trained with calibrated ordinal supervision achieves 44.70% mAP@0.5, a 4.8 percentage-point improvement, with gains in ordinal metrics (91.15% Ordinal Top-1 Accuracy, MAOE = 0.56). These findings establish that ordinal-aware supervision improves damage severity estimation when aligned with detector architecture.