---
title: "Anomaly Crossing: New Horizons for Video Anomaly Detection as Cross-domain Few-shot Learning"
collection: publications
permalink: /publication/water
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
---
# Anomaly Crossing: New Horizons for Video Anomaly Detection as Cross-domain Few-shot Learning


[[Paper](https://arxiv.org/abs/2112.06320)]
[[Code](https://github.com/likeyhnbm/AnomalyCrossing)]


## Abstract
Video anomaly detection aims to identify abnormal events that occurred in videos. Since anomalous events are relatively rare, it is not feasible to collect a balanced dataset and train a binary classifier to solve the task. Thus, most previous approaches learn only from normal videos using unsupervised or semi-supervised methods. Obviously, they are limited in capturing and utilizing discriminative abnormal characteristics, which leads to compromised anomaly detection performance. In this paper, to address this issue, we propose a new learning paradigm by making full use of both normal and abnormal videos for video anomaly detection. In particular, we formulate a new learning task: cross-domain few-shot anomaly detection, which can transfer knowledge learned from numerous videos in the source domain to help solve few-shot abnormality detection in the target domain. Concretely, we leverage self-supervised training on the target normal videos to reduce the domain gap and devise a meta context perception module to explore the video context of the event in the few-shot setting. Our experiments show that our method significantly outperforms baseline methods on DoTA and UCF-Crime datasets, and the new task contributes to a more practical training paradigm for anomaly detection.

## Citation
```
@misc{sun2022anomaly,
      title={Anomaly Crossing: New Horizons for Video Anomaly Detection as Cross-domain Few-shot Learning}, 
      author={Guangyu Sun and Zhang Liu and Lianggong Wen and Jing Shi and Chenliang Xu},
      year={2022},
      eprint={2112.06320},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
  ```