---
published: false # 暂时下线，日后大改后再打开
layout: page
title: Multimodal 3D representation learning
description: The representation learning the other two threads are built on.
img: assets/img/research/geometric-learning.png
importance: 3
category: work
related_publications: true
---
<div class="row justify-content-sm-center mt-3 mb-4">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/research/geometric-learning.png" class="img-fluid rounded" %}
  </div>
</div>

**The problem.** Scientific data is structured, sparse, expensive to label and captured through several complementary sensors or assays at once. Learning useful representations from it means confronting all four properties together, whether the object is a molecule or a street.

**What I build.** Methods for learning from structured 3D data under weak supervision. {% cite yin2022proposalcontrast %} pre-trains detectors on unlabelled point clouds by contrasting region proposals; {% cite yin2022proficient %} and {% cite wang2023ssda3d %} push the same objective into the semi-supervised and domain-adaptive settings, where labels exist but not for the distribution you care about; {% cite li2023lwsis %} supervises segmentation from cheaper modalities instead of dense masks. On the multimodal side, {% cite yin2024isfusion %} fuses camera and LiDAR at both the instance and the scene level, and {% cite yin2023tpami %} models temporal structure with graph message passing and spatiotemporal attention.

**Where it is going.** These techniques were developed for perception, and the transfer to molecular systems is direct: pre-training when labels are scarce, adapting across distributions, and fusing modalities that each see part of the object. That transfer is what made the move into protein design a continuation rather than a restart.
