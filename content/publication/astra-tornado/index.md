---
title: 'ASTRA: Architectural inSights for post-ToRnado damAge recognition'
authors:
- Umeike, R.
- Dao, T.
- Crawford, S.
- van de Lindt, J.
- Johnston, B.
- Wang, W. (Lisa)
- Do, T.
- Mofikoya, A.
- Banjara, S.
- admin
date: '2026-08-06'
publication_types:
- article-journal
publication: '*Expert Systems with Applications*, 333, 133915 (2027).'
publication_short: Expert Systems with Applications
summary: A large-scale evaluation of deep learning approaches to post-tornado building damage recognition.
tags:
- Tornado Damage
- Computer Vision
- Deep Learning
- Natural Hazards
publishDate: '2026-08-06'
hugoblox:
  ids:
    doi: 10.1016/j.eswa.2026.133915
links:
- type: Publisher
  url: https://www.sciencedirect.com/science/article/pii/S0957417426028228?via%3Dihub
---

### Abstract

Rapid and accurate building damage assessment after tornadoes is critical for emergency response and recovery, yet automated methods struggle with the visual complexity of tornado-induced wreckage, primarily due to severe domain shift and extreme class imbalance. We introduce ASTRA, a large-scale framework evaluating 79 open-source models (67 CNNs and 12 Transformers-based architectures) across 2,420 experiments on an expertly curated Quad-State Tornado Damage (QSTD) benchmark of 5,517 street-view images annotated under the IN-CORE engineering taxonomy. We find that achieving strong performance hinges on the interaction among architecture, optimization, and pre-training source, not on architecture alone. Attention-based models were acutely optimization-sensitive: although bottom-tier under the default configuration, they recovered by +25 to +38 Macro-F1-points once optimization was corrected, either by switching from Adam to SGD or, equivalently, lowering the learning rate. A controlled ablation attributes this swing primarily to the learning rate, with a smaller optimizer effect specific to Vision Transformers; CNNs showed no comparable reversal. Furthermore, we uncover a counterintuitive behavior in which scene-centric Places365 pre-training did not surpass object-centric ImageNet after optimization, despite its closer semantic proximity to building and streetscape scenes and its competitive zero-shot performance. In a strict zero-shot test on the held-out Tuscaloosa-Moore Tornado Damage dataset of 2,393 images, naive baselines failed to transfer, while QSTD-optimized models achieved substantially better performance. The champion model, ConvNeXt-Base, achieved a +34.6 Macro-F1-point gain over its baseline, despite temporal, sensor, and geographic shifts. Consequently, ASTRA offers practical optimization guidelines and a rigorously validated, open-source foundation for automated tornado-damage assessment. Project Website: https://crumeike.github.io/astra-page.'
