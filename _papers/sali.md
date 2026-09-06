---
title: "SALI: Short-Term Alignment and Long-Term Interaction Network for Colonoscopy Video Polyp Segmentation"
venue: "MICCAI 2024"
venue_note: "Oral (<3%)"
authors:
  - name: "Qiang Hu"
    note: "co-first"
  - name: "Zhenyu Yi"
    note: "co-first"
  - name: "Ying Zhou"
  - name: "Fang Peng"
  - name: "Mei Liu"
  - name: "Qiang Li"
  - name: "Zhiwei Wang"
author_note: "* denotes co-first author (equal contribution)"
image: "images/sali.png"
tldr: "A hybrid temporal interaction network for colonoscopy video polyp segmentation."
abstract: >-
  Colonoscopy videos provide richer information in polyp segmentation for rectal cancer diagnosis. However, the endoscope's fast moving and close-up observing make the current methods suffer from large spatial incoherence and continuous low-quality frames, and thus yield limited segmentation accuracy. In this context, we focus on robust video polyp segmentation by enhancing the adjacent feature consistency and rebuilding the reliable polyp representation. To achieve this goal, we in this paper propose SALI network, a hybrid of Short-term Alignment Module (SAM) and Long-term Interaction Module (LIM). The SAM learns spatial-aligned features of adjacent frames via deformable convolution and further harmonizes them to capture more stable short-term polyp representation. In case of low-quality frames, the LIM stores the historical polyp representations as a long-term memory bank, and explores the retrospective relations to interactively rebuild more reliable polyp features for the current segmentation. Combing SAM and LIM, the SALI network of video segmentation shows a great robustness to the spatial variations and low-visual cues. Benchmark on the large-scale SUNSEG verifies the superiority of SALI over the current state-of-the-arts by improving Dice by 2.1%, 2.5%, 4.1% and 1.9%, for the four test sub-sets, respectively.
links:
  pdf: "https://link.springer.com/chapter/10.1007/978-3-031-72089-5_50"
  arxiv: "https://arxiv.org/abs/2406.13532"
  code: "https://github.com/Scatteredrain/SALI"
bibtex: |
  @inproceedings{hu2024sali,
    title     = {SALI: Short-Term Alignment and Long-Term Interaction Network for Colonoscopy Video Polyp Segmentation},
    author    = {Hu, Qiang and Yi, Zhenyu and Zhou, Ying and Peng, Fang and Liu, Mei and Li, Qiang and Wang, Zhiwei},
    booktitle = {International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)},
    year      = {2024},
    note      = {Oral presentation}
  }
---
