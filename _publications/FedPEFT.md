---
title: "Conquering the Communication Constraints to Enable Large Pre-Trained Models in Federated Learning"
collection: publications
permalink: /publication/fedpeft
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
---
# Conquering the Communication Constraints to Enable Large Pre-Trained Models in Federated Learning

[[Paper](https://arxiv.org/pdf/2210.01708.pdf)]


## Abstract
Federated learning (FL) has emerged as a promising paradigm for enabling the collaborative training of models without centralized access to the raw data on local devices. In the typical FL paradigm (e.g., FedAvg), model weights are sent to and from the server each round to participating clients. 
Recently, the use of small pre-trained models has been shown effective in federated learning optimization and improving convergence.
However, recent state-of-the-art pre-trained models are getting more capable but also have more parameters.
In conventional FL, sharing the enormous model weights can quickly put a massive communication burden on the system, especially if more capable models are employed. 
Can we find a solution to enable those strong and readily-available pre-trained models in FL to achieve excellent performance while simultaneously reducing the communication burden?
To this end, we investigate the use of parameter-efficient fine-tuning in federated learning and thus introduce a new framework: FedPEFT. Specifically, we systemically evaluate the performance of FedPEFT across a variety of client stability, data distribution, and differential privacy settings. By only locally tuning and globally sharing a small portion of the model weights, significant reductions in the total communication overhead can be achieved while maintaining competitive or even better performance in a wide range of federated learning scenarios, providing insight into a new paradigm for practical and effective federated systems.

## Citation
```
@misc{sun2022conquering,
      title={Conquering the Communication Constraints to Enable Large Pre-Trained Models in Federated Learning}, 
      author={Guangyu Sun and Matias Mendieta and Taojiannan Yang and Chen Chen},
      year={2022},
      eprint={2210.01708},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
  ```