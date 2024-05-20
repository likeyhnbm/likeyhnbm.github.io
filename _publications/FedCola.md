---
title: "Towards Multi-modal Transformers in Federated Learning"
collection: publications
permalink: /publication/fedcola
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
---
# Towards Multi-modal Transformers in Federated Learning

[[Paper](https://arxiv.org/abs/2404.12467)]


## Abstract
Multi-modal transformers mark significant progress in different domains, but siloed high-quality data hinders their further improvement. To remedy this, federated learning (FL) has emerged as a promising privacy-preserving paradigm for training models without direct access to the raw data held by different clients. Despite its potential, a considerable research direction regarding the unpaired uni-modal clients and the transformer architecture in FL remains unexplored. To fill this gap, this paper explores a transfer multi-modal federated learning (MFL) scenario within the vision-language domain, where clients possess data of various modalities distributed across different datasets. We systematically evaluate the performance of existing methods when a transformer architecture is utilized and introduce a novel framework called Federated modality complementary and collaboration (FedCola) by addressing the in-modality and cross-modality gaps among clients. Through extensive experiments across various FL settings, FedCola demonstrates superior performance over previous approaches, offering new perspectives on future federated training of multi-modal transformers.

## Citation
```
@misc{sun2024multimodal,
      title={Towards Multi-modal Transformers in Federated Learning}, 
      author={Guangyu Sun and Matias Mendieta and Aritra Dutta and Xin Li and Chen Chen},
      year={2024},
      eprint={2404.12467},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
  ```