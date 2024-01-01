---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Math and Applied Mathematics, College of Sciences, Shanghai University, 2018-2022.
* M.S. in Applied Mathematics, Institute of Science and Technology for Brain-Inspired Intelligence, Fudan University, 2022-Present.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Research Experience
======
* A Biological Interpretable One-shot Pruning Framework for Spiking Neural Networks, 2023.3-2023.8
  * Fudan University
  * Supervisor: Professor, Yuguo Yu
  * Summary: In this research, we develop a biologically interpretable magnitude-based pruning approach for Spiking Neural Networks (SNNs). Experimentally, it can be found that after removing some weak neurons with relatively small weight sum, the test accuracy of SNNs on the MNIST dataset is slightly improved. In addition, through visualizing the feature maps of the middle layers of the SNNs by the t-SNE algorithm, it can be found that the representation ability of the network is not significantly affected by the removal of weak neurons. However, after removing the mid and hub neurons, the feature extraction ability of the network decreases significantly. At the same time, the image recognition accuracy of the model dropped as well.

* Multi-scan Point Cloud Segmentation, 2022.10-2023.1
  * Fudan University
  * Supervisor: Young Researcher, Jian Pu
  * Summary: The semantic analysis of 3D scenes is a crucial step for autonomous driving systems. Lidar point cloud segmentation can help autonomous vehicles recognize objects in the surrounding environment, thus bringing better priors for path planning and decision control in downstream tasks. However, the recognition of moving objects is not included in the traditional single frame point cloud segmentation task, and the temporal information possessed by the continuous multi-frame point cloud is not fully utilized. Therefore, in this study, we examine three different fusion strategies for temporal and spatial information fusion on range-based point cloud inputs. They are input layer fusion, cross-attention-based fusion, and concatenation fusion, respectively. and conduct experiments on the SemanticKITTI multi-frame segmentation basis. The experimental results show that the concatenation fusion has the best performance among the above three fusion schemes, reaching 47.8% of the mIoU value, and can achieve a competitive result in the SemantcKITTI multi-frame segmentation task list (currently ranked fifteenth). At the same time, the segmentation performance for moving objects (such as moving vehicles, moving cyclists, etc.) is significantly improved compared with some previous methods.

Misc
======
* Reviewer in NeurIPS2023.
