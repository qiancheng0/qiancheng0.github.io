---
title: "Exploring Mode Connectivity for Pre-trained Language Models"
excerpt: "EMNLP 2022 Poster of the paper <br/><img src='/images/poster/connectivity_poster.png'>"
collection: projects
date: 2022-10-25
---

## Exploring Mode Connectiviy of Pre-trained Language Models, THUNLP Lab Project
Background:

* Pre-trained Language Models (PLMs) provide a generic initialization, from which high-performance minima could be found. However, little is known about the relationships of various minima reached under different conditions.
* We propose to dive deeper into the loss landscape, and explore various minima’s geometric connections through the lens of Mode Connectivity, which measures whether two different minima can be connected via a low-loss parametric path.

Questions to Investigate: 
* How could hyperparameters and training data affect PLM’s mode connectivity?
* How does mode connectivity change during pre-training?
* How does the PLM's task knowledge change along the path connecting two minima?

Contributions:

* Our findings can help design better weight averaging methods, including how to choose appropriate endpoints, how to combine the weights (linear / curve?), etc.
* Our discovery that pretraining implicitly pulls task boundaries closer may help explain why PLMs possess excellent cross-task transferability.
* Our investigation of knowledge variation along connected path may provide insights for knowledge distillation & knowledge transfer.