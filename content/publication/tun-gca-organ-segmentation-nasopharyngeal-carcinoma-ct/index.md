---
title: "TUN-GCA: A Novel Approach for Organ Segmentation in Nasopharyngeal Carcinoma CT Images"
subtitle: ""
publication_types:
  - "1"
authors:
  - Wenxin Che
  - admin
  - Rihan Huang
  - Quanying Liu
  - Youzhi Qu
  - Ziyuan Ye
author_notes:
  - Equal contribution
  - Equal contribution
  - Equal contribution
doi: 10.1007/978-981-96-4001-0_26
publication: In *Human Brain and Artificial Intelligence (HBAI 2024)*, Communications in Computer and Information Science, vol. 2438, pp. 368–381
publication_short: HBAI 2024
abstract: >-
  Nasopharyngeal cancer (NPC) is a highly prevalent malignant tumor. Effective radiation therapy planning for NPC requires precise segmentation of nasopharyngeal structures and adjacent organs that may be affected by radiation, based on CT imaging. However, it is challenging to segment the nasopharynx and surrounding organs because they are relatively small and exhibit intricate patterns in CT images. In this work, we introduce a novel three-stage framework, termed TransUNet with Gradually Converging Attention (TUN-GCA), to address this problem. Our framework utilizes a TransUNet model pretrained on 3D surrogate labels, allowing the model to initially focus on a small region that encompasses all organs of interest, similar to how human doctors look for anatomical landmarks. Subsequently, the model is trained with actual labels to precisely segment these organs. Finally, DBSCAN clustering is employed to explore multiple organs and eliminate potential voxel outliers, enhancing overall robustness. We evaluated the proposed framework using a dataset of 99 subjects with CT images from nasopharyngeal cancer patients, comprising both left and right parotid and submandibular glands. The extensive experimental results demonstrate that our proposed model substantially outperforms other competitive baselines in terms of accuracy and efficiency.

draft: false
featured: false
tags:
  - Nasopharyngeal Carcinoma
  - Computed Tomography
  - Medical Image Segmentation
  - Deep Learning
  - TransUNet
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2025-01-01T00:00:00.000Z
---
