# A2VIS 
[[`arXiv`]()]
[[`Project Page`](https://uark-aicv.github.io/A2VIS/)]
[[`BibTex`](#citation)]


Handling occlusion remains a significant challenge for video instance-level tasks like Multiple Object Tracking (MOT) and Video Instance Segmentation (VIS). In this paper, we propose a novel framework, Amodal-Aware Video Instance Segmentation (A2VIS), which incorporates amodal representations to achieve a reliable and comprehensive understanding of both visible and occluded parts of objects in a video. The key intuition is that awareness of amodal segmentation through spatiotemporal dimension enables a stable stream of object information. In scenarios where objects are partially or completely hidden from view, amodal segmentation offers more consistency and less dramatic changes along the temporal axis compared to visible segmentation. Hence, both amodal and visible information from all clips can be integrated into one global instance prototype. To effectively address the challenge of video amodal segmentation, we introduce the spatiotemporal-prior Amodal Mask Head, which leverages visible information intra clips while extracting amodal characteristics inter clips. Through extensive experiments and ablation studies, we show that A2VIS excels in both MOT and VIS tasks in identifying and tracking object instances with a keen understanding of their full shape.


# Code

Code for "A2VIS" (coming soon!).

# <a name="citation"></a>Citing A2VIS

<!-- If you find this code helpful, please consider citing: -->

```BibTeX
comming soon!
```

# Acknowledgement
This material is based upon work supported by the National Science Foundation (NSF) under Award No OIA-1946391, NSF 2223793 EFRI BRAID and partly supported by Cobb Vantress Inc. 