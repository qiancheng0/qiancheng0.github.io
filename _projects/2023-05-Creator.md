---
title: "CREATOR: Disentangling Abstract and Concrete Reasonings of Large Language Models through Tool Creation"
excerpt: "Submitted to EMNLP 2023, under review <br/><img src='/images/QC/Creator.pdf'>"
collection: projects
date: 2023-04-17
---

## CREATOR: Disentangling Abstract and Concrete Reasonings of Large Language Models through Tool Creation, THUNLP Lab Survey Paper
Background:

* Large Language Models (LLMs) have demonstrated significant progress in utilizing external APIs as tools for various tasks.
* However, their tool-using ability is limited by the availability of suitable APIs and the instability of implicit reasoning, particularly when simultaneously engaging in reasoning about plans and actual calculations.


Contributions:

* We propose CREATOR, a novel framework that empowers LLMs to create their own tools through documentation and code realization.
* We leverage CREATOR and disentangle the LLM's ability into two distinct phases: abstract tool creation and concrete decision execution, which results in improved LLM performance.
* We evaluate CREATOR on two established benchmarks: MATH and TabMWP, and prove CREATOR significantly outperforms existing chain-of-thought (CoT), program-of-thought (PoT), and tool-using baselines.
* We present a new dataset, Creation Challenge, comprising 2K diverse questions, to highlight the necessity and benefits of LLMs' tool creation ability in effectively addressing these problems.
* We  reveal that leveraging LLMs as tool creators facilitates knowledge transfer, and LLMs exhibit varying levels of tool creation abilities, enabling them to flexibly tackle diverse situations.
