---
title: Automated BIM-to-scan point cloud semantic segmentation using a domain adaptation network with hybrid attention and whitening (DawNet)
authors:
- Difeng Hu
- Vincent J. L. Gan
- Ruoming Zhai
date: '2024-01-01'
publishDate: '2024-05-18T04:56:48.356230Z'
publication_types:
- article-journal
publication: '*Automation in Construction*'
doi: https://doi.org/10.1016/j.autcon.2024.105473
abstract: Deep learning-based point cloud semantic segmentation facilitates scene understanding and BIM modelling, but its success requires vast amount of labelled point clouds, which is laborious and time-consuming. To reduce point cloud annotation cost, researchers attempt to leverage synthetic point clouds, but the domain gap between synthetic and real point clouds deteriorates the segmentation accuracy. To address this issue, this study develops a BIM-to-Scan point cloud semantic segmentation approach to mitigate the domain gap between BIM and real point clouds, improving the segmentation performance on real point clouds. To this end, this study starts by proposing a BIM-based point cloud generation method, which uses FME and BIM models to automatically generate and label synthetic point clouds, decreasing the annotation cost. To fill the domain gap, a DawNet is invented by integrating a domain adaptation network with ZCA whitening operation and hybrid attention mechanism. Specifically, ResPointNet++ is used to extract geometric features and execute the segmentation task, which is then combined with a domain discriminator to perform domain adversarial learning, aligning the data distribution of BIM and real point clouds. To improve the performance of the DawNet, a residual learning block with whitening and a hybrid attention module are designed. These two modules help extract and exploit domain-invariant features to boost the generalisation and segmentation performance of the DawNet. Finally comprehensive experiments show that the proposed BIM-based method spends 0.5 person-hours to generate 0.45 billion labelled BIM point clouds, and that the developed DawNet achieves 17% and 11% more mIoU than ResPointNet++ and DANN. The ablation study also confirms the effectiveness of the hybrid attention module and ZCA whitening operation..
tags:
- Domain adaptation
- BIM-to-scan semantic segmentation
- Hybrid attention
- Automatic point cloud labelling
- Deep learning
links:
- name: URL
  url: https://www-sciencedirect-com.libproxy1.nus.edu.sg/science/article/pii/S0926580524002097
---
