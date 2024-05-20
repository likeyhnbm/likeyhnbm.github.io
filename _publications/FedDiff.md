---
title: "Navigating Heterogeneity and Privacy in One-Shot Federated Learning with Diffusion Models"
collection: publications
permalink: /publication/feddiff
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
---
# Navigating Heterogeneity and Privacy in One-Shot Federated Learning with Diffusion Models

[[Paper](https://arxiv.org/abs/2405.01494)]


## Abstract
Federated learning (FL) enables multiple clients to train models collectively while preserving data privacy. However, FL faces challenges in terms of communication cost and data heterogeneity. One-shot federated learning has emerged as a solution by reducing communication rounds, improving efficiency, and providing better security against eavesdropping attacks. Nevertheless, data heterogeneity remains a significant challenge, impacting performance. This work explores the effectiveness of diffusion models in one-shot FL, demonstrating their applicability in addressing data heterogeneity and improving FL performance. Additionally, we investigate the utility of our diffusion model approach, FedDiff, compared to other one-shot FL methods under differential privacy (DP). Furthermore, to improve generated sample quality under DP settings, we propose a pragmatic Fourier Magnitude Filtering (FMF) method, enhancing the effectiveness of generated data for global model training.

## Citation
```
@misc{mendieta2024navigating,
      title={Navigating Heterogeneity and Privacy in One-Shot Federated Learning with Diffusion Models}, 
      author={Matias Mendieta and Guangyu Sun and Chen Chen},
      year={2024},
      eprint={2405.01494},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
  ```