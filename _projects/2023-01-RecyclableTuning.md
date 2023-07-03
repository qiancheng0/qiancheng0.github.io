---
title: "Recyclable Tuning for Continual Pre-training"
excerpt: "ACL 2023 Findings, main figure <br/><img src='/images/poster/recyclable_tuning.png'>"
collection: projects
date: 2023-01-20
---

## Recyclable Tuning for Continual Pre-training, THUNLP Lab Project
Background:

* Continual pre-training is the paradigm where pre-trained language models (PLMs) continually acquire fresh knowledge from growing data and gradually get upgraded. Before an upgraded PLM is released, we may have tuned the original PLM for various tasks and stored the adapted weights.
* However, when tuning the upgraded PLM, these outdated adapted weights will typically be ignored and discarded, causing a potential waste of resources.


Pilot Studies:

* We demonstrate that after adapting both the upgraded PLM and the original PLM to the same task, linearly interpolating the parameters of both adapted models could produce a series of checkpoints with high task performance (low loss). Such a property indicates a close parametric connection of both PLMs in the loss landscape.
* After adapting both PLMs to the same task, we observe that their corresponding attention heads exhibit similar patterns given the same input. Such representational proximity implies that both PLMs own similar functionalities during text processing.


Methods:

* we propose two methods for recyclable tuning: (1) Initialization-based method, which leverages the adapted weights of the original PLM as the initialization for the upgraded PLM. (2) Distillation-based method, which distills the knowledge from the adapted weights of the original PLM to the upgraded PLM.


Contributions:

* We formulate the task of recyclable tuning for continual pre-training.
* We conduct empirical analyses for this task through the lens of model compatibility, linear mode connectivity, and functional similarity.
* We explore the practical benefits of recyclable tuning through parameter initialization and knowledge distillation.
* We also envision our setup to serve as the testbed for other topics, e.g., cross-model knowledge transfer and continual learning.