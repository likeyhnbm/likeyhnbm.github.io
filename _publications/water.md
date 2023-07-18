---
title: "Assessing environmental oil spill based on fluorescence images of water samples and deep learning"
collection: publications
permalink: /publication/water
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
---
# Assessing environmental oil spill based on fluorescence images of water samples and deep learning
[[Paper](https://doi.org/10.3808/jei.202300491)]


## Abstract
Measuring oil concentration in the aquatic environment is important for determining the potential exposure, risk, or injury for oil spill response and natural resource damage assessment. Conventional analytical chemistry methods that are currently used require samples to be collected in the field, shipped, and processed in the laboratory. While these conventional laboratory approaches are desirable for their established reliability, accuracy, and precision, they are also rather time-consuming, laborious, and costly.  For rapid field response immediately after a spill, there is a need for methods to estimate the concentration of oil in near real time. To make the oil analysis more portable, rapid, and cost effective, we developed a plug-and-play device and a deep learning model to assess oil levels in water using fluorescent images of water samples. We constructed a 3D printed device to collect fluorescent images of solvent extracted water samples using a consumer iPhone. We prepared approximately 1300 samples of oil at different concentrations that were used to train and test the deep learning model. The model is composed of a convolutional neural network and a novel module of histogram bottleneck block with an attention mechanism to exploit the spectral features found in low-contrast images. This model predicts the oil concentration in weight per volume based on image fluorescence. To provide a confidence assessment of our results, we devised a confidence interval estimator by combining gradient boosting and polymodal regressor. Our model achieved sufficient accuracy to predict relevant oil levels for most environmental applications. We plan to further develop the device and iPhone application as a near real-time tool for oil spill responders to measure oil in water.

## Citation
```
@article{JEI202300491,
	author = {D. P. Liu and M. Liu and G. Y. Sun and Z. Q. Zhou and D. L. Wang and F. He and J. X. Li and J. C. Xie and R. Gettler and E. Brunson and J. Steevens and D. Xu},
	title = {Assessing Environmental Oil Spill Based on Fluorescence Images of Water Samples and Deep Learning},
	journal = {JOURNAL OF ENVIRONMENTAL INFORMATICS},
	volume = {42},
	number = {1},
	year = {2023},
	keywords = {},
	issn = {1684-8799}
}
  ```