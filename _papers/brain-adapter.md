---
title: "Brain-Adapter: A Dual-Stream Vision-Language MIL Framework for Comprehensive 3D CT Diagnosis of Acute Intracranial Pathologies"
venue: "MICCAI 2026"
authors:
  - name: "Zhenyu Yi"
    note: "first"
  - name: "Zhiyun Song"
  - name: "Yusong Sun"
  - name: "Zelin Liu"
  - name: "Manman Fei"
  - name: "Zhenhao Li"
  - name: "Jiaxuan Zhao"
  - name: "Xu Han"
  - name: "Lichi Zhang"
author_note: "* denotes first author"
image: "images/brain-adapter.png"
tldr: "A dual-stream vision-language MIL framework for comprehensive 3D CT diagnosis of acute intracranial pathologies."
abstract: >-
  Automated diagnosis of 3D brain CT scans is essential for critical care, yet it remains challenging due to the heavy reliance on manual annotations and the limited semantic understanding of conventional models. While 2D foundation vision-language models (VLMs) have shown remarkable generalization, effectively transferring their representational power to 3D volumes remains an open problem. In this paper, we propose Brain-Adapter, a novel dual-stream multiple instance learning (MIL) framework that leverages pre-trained 2D biomedical VLMs and raw diagnostic reports for robust scan-level multi-label classification. Specifically, we introduce a Text-Conditioned Attention (TCA) mechanism, utilizing raw diagnostic sentences as semantic queries to dynamically align visual cues with specific disease concepts. Concurrently, a parallel visual MIL stream captures global scan characteristics, supervised by structured labels extracted via a Large Language Model (LLM). To ensure representation coherence, a consistency constraint enforces synergy between the two streams. During inference, an Uncertainty-Aware Refinement (UAR) module dynamically calibrates and fuses these dual-stream predictions to resolve ambiguous cases. Extensive experiments demonstrate that our method significantly outperforms state-of-the-art 3D models and standard MIL approaches. By eliminating the reliance on dense annotations, Brain-Adapter provides a highly scalable and clinically viable solution for 3D acute intracranial pathology analysis.
links:
  arxiv: "https://arxiv.org/abs/2606.23494"
  pdf: "https://arxiv.org/pdf/2606.23494"
  code: "https://github.com/Scatteredrain/Brain-Adapter"
bibtex: |
  @inproceedings{yi2026brainadapter,
    title     = {Brain-Adapter: A Dual-Stream Vision-Language MIL Framework for Comprehensive 3D CT Diagnosis of Acute Intracranial Pathologies},
    author    = {Yi, Zhenyu and Song, Zhiyun and Sun, Yusong and Liu, Zelin and Fei, Manman and Li, Zhenhao and Zhao, Jiaxuan and Han, Xu and Zhang, Lichi},
    booktitle = {International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)},
    year      = {2026}
  }
---
