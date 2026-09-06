---
title: "Learning from Limited Phenotype-Level Annotations for Promoting Multiple Instance Learning in Endoscopic Helicobacter pylori Infection Diagnosis"
venue: "Medical Image Analysis (MedIA)"
venue_note: "2026"
authors:
  - name: "Zhenyu Yi"
    note: "co-first"
  - name: "Jianwei Xu"
    note: "co-first"
  - name: "Yue Hu"
    note: "co-first"
  - name: "Liang Huang"
  - name: "Zhilin Zheng"
  - name: "Haifeng Jin"
  - name: "Panpan Ma"
  - name: "Tanzhou Chen"
  - name: "Jie Pan"
  - name: "Xiaoyun Ding"
  - name: "Fangfang Zhang"
  - name: "Jiang Liu"
  - name: "Xiaoteng Wang"
  - name: "Yingda Xia"
  - name: "Bin Lv"
  - name: "Ling Zhang"
author_note: "* denotes co-first author (equal contribution)"
image: "images/phenomil.png"
tldr: "A phenotype-aware MIL framework for endoscopic H. pylori infection diagnosis with limited fine-grained annotations."
abstract: >-
  Helicobacter pylori (H. pylori) infection is a major risk factor for gastric carcinogenesis, requiring holistic endoscopic assessment of distributed mucosal abnormalities. While patient-level diagnostic labels are accessible, obtaining large-scale fine-grained annotations is constrained due to high inter-observer variability and the labor-intensive nature of the process. This naturally formulates the task as a multiple instance learning (MIL) problem. Existing image-level approaches often rely on noisy supervisory signals without modeling sequence context, while standard embedding-based MIL methods suffer from suboptimal feature representations and insufficient integration of H. pylori-specific phenotypes. To address these challenges, we propose PhenoMIL, a two-stage framework emulating clinical hierarchical reasoning. First, the Fine-grained Phenotype-level Semi-Supervised Learning (FPS-SL) stage uses multi-label supervised contrastive learning and prototype-based pseudo-label generation to acquire phenotype-specific knowledge and learn transferable representation from limited instance-level annotations. Subsequently, the Clinically Informed MIL (CIMIL) stage performs holistic bag-level diagnosis using Consensus-aware Feature Modulation (CFM) to exploit latent neighborhood structures, and Phenotype-guided Attention Aggregation (PAA) to align instance weighting with diagnostic priors. Extensive evaluation on a large-scale multi-center dataset (303,910 images from 6388 patients) demonstrates PhenoMIL's superiority in both multi-label phenotype classification and H. pylori infection diagnosis. Notably, in a real-world reader study, PhenoMIL achieved 81.63% sensitivity and 87.84% specificity, outperforming both junior and senior endoscopists.
links:
  pdf: "https://www.sciencedirect.com/science/article/pii/S1361841526003361"
  code: "https://github.com/Scatteredrain/PhenoMIL"
bibtex: |
  @article{yi2026phenomil,
    title   = {Learning from Limited Phenotype-Level Annotations for Promoting Multiple Instance Learning in Endoscopic Helicobacter pylori Infection Diagnosis},
    author  = {Yi, Zhenyu and Xu, Jianwei and Hu, Yue and Huang, Liang and Zheng, Zhilin and Jin, Haifeng and Ma, Panpan and Chen, Tanzhou and Pan, Jie and Ding, Xiaoyun and Zhang, Fangfang and Liu, Jiang and Wang, Xiaoteng and Xia, Yingda and Lv, Bin and Zhang, Ling},
    journal = {Medical Image Analysis},
    year    = {2026}
  }
---
