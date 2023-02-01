---
title: "Exploring Mode Connectivity for Pre-trained Language Models"
collection: publications
permalink: /publication/2022-10-25-Connectivity
excerpt: 'The paper analytically and empirically investigates the mode connectivity of pre-trained language models'
date: 2022-10-25
venue: 'EMNLP 2022'
paperurl: 'https://arxiv.org/pdf/2210.14102.pdf'
citation: '@misc{https://doi.org/10.48550/arxiv.2210.14102, doi = {10.48550/ARXIV.2210.14102}, url = {https://arxiv.org/abs/2210.14102}, uthor = {Qin, Yujia and Qian, Cheng and Yi, Jing and Chen, Weize and Lin, Yankai and Han, Xu and Liu, Zhiyuan and Sun, Maosong and Zhou, Jie}, keywords = {Computation and Language (cs.CL), Artificial Intelligence (cs.AI), FOS: Computer and information sciences, FOS: Computer and information sciences}, title = {Exploring Mode Connectivity for Pre-trained Language Models}, ublisher = {arXiv}, year = {2022}, copyright = {arXiv.org perpetual, non-exclusive license} }'
---

Recent years have witnessed the prevalent application of pre-trained language models (PLMs) in NLP. From the perspective of parameter space, PLMs provide generic initialization, starting from which high-performance minima could be found. Although plenty of works have studied how to effectively and efficiently adapt PLMs to high-performance minima, little is known about the connection of various minima reached under different adaptation configurations. In this paper, we investigate the geometric connections of different minima through the lens of mode connectivity, which measures whether two minima can be connected with a low-loss path. We conduct empirical analyses to investigate three questions: (1) how could hyperparameters, specific tuning methods, and training data affect PLM's mode connectivity? (2) How does mode connectivity change during pre-training? (3) How does the PLM's task knowledge change along the path connecting two minima? In general, exploring the mode connectivity of PLMs conduces to understanding the geometric connection of different minima, which may help us fathom the inner workings of PLM downstream adaptation.

[Download paper here](https://arxiv.org/pdf/2210.14102.pdf)

