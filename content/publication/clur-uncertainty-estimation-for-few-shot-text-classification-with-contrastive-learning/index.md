---
title: "CLUR: Uncertainty Estimation for Few-Shot Text Classification with
  Contrastive Learning"
publication_types:
  - "1"
authors:
  - Jianfeng He
  - Xuchao Zhang
  - Shuo Lei
  - admin
  - Fanglan Chen
  - Bei Xiao
  - Chang-Tien Lu
doi: https://doi.org/10.1145/3580305.3599276
publication: Proceedings of the 29th ACM SIGKDD Conference on Knowledge
  Discovery and Data Mining
publication_short: in "ACM SIGKDD 2023"
abstract: Few-shot text classification has extensive application where the
  sample collection is expensive or complicated. When the penalty for
  classification errors is high, such as early threat event detection with
  scarce data, we expect to know "whether we should trust the classification
  results or reexamine them.'' This paper investigates the Uncertainty
  Estimation for Few-shot Text Classification (UEFTC), an unexplored research
  area. Given limited samples, a UEFTC model predicts an uncertainty score for a
  classification result, which is the likelihood that the classification result
  is false. However, many traditional uncertainty estimation models in text
  classification are unsuitable for implementing a UEFTC model. These models
  require numerous training samples, whereas the few-shot setting in UEFTC only
  provides a few or just one support sample for each class in an episode. We
  propose Contrastive Learning from Uncertainty Relations (CLUR) to address
  UEFTC. CLUR can be trained with only one support sample for each class with
  the help of pseudo uncertainty scores. Unlike previous works that manually set
  the pseudo uncertainty scores, CLUR self-adaptively learns them using our
  proposed uncertainty relations. Specifically, we explore four model structures
  in CLUR to investigate the performance of three common-used contrastive
  learning components in UEFTC and find that two of the components are
  effective. Experiment results prove that CLUR outperforms six baselines on
  four datasets, including an improvement of 4.52% AUPR on an RCV1 dataset in a
  5-way 1-shot setting. Our code and data split for UEFTC are in
  https://github.com/he159ok/CLUR_UncertaintyEst_FewShot_TextCls.
draft: false
featured: false
url_video: https://dl.acm.org/action/downloadSupplement?doi=10.1145%2F3580305.3599276&file=rtfp0242-2min-promo.mp4
image:
  filename: clur.jpg
  focal_point: Smart
  preview_only: false
date: 2023-08-24T17:16:54.101Z
---
