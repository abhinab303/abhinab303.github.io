---
layout: post
title: "Selection in Deep Learning"
tags: [research]
---

Lately, I’ve been increasingly fascinated by a simple but powerful idea in Deep Learning: *selection*. In this post, I want to highlight several research directions where selection plays a central role.

**Selecting Layers for Robust Finetuning:**

Instead of finetuning all layers for adversarial robustness, recent work shows that adapting only a small set of critical layers can lead to better robustness and more stable optimization.
[Paper](https://openaccess.thecvf.com/content/ICCV2025/papers/Gopal_SAFER_Sharpness_Aware_layer-selective_Finetuning_for_Enhanced_Robustness_in_vision_ICCV_2025_paper.pdf)

**Selecting Tokens for Video Understanding:**

Transformers have built-in attention, but recent video models show that explicitly removing irrelevant tokens is efficient and can sometimes outperform attention alone. Pruning noisy visual patches helps the model focus on what truly matters.
[Paper](https://openreview.net/pdf/0f034cec09015c31c9ffe918643cb9066d29da68.pdf)

**Selecting Clients in Federated Learning:**

In federated learning, filtering out harmful or low-quality clients before updating the global model is essential and is one of the fundamental challenges.
[Paper](https://openreview.net/pdf?id=sYNWqQYJhz)

**Selecting Replay Samples in Continual Learning:**

In real-world systems, models must be continually updated. Key questions include when to refresh old knowledge and which past samples to replay. 
[Paper](https://arxiv.org/abs/2209.08660)

**Subset Selection:**

My interest in this topic began when I came across the ICML 2021 workshop “Subset Selection in Machine Learning: From Theory to Applications,” where Prof. Baharan Mirzasoleiman emphasized a key insight: as data grows, selection becomes essential for both efficiency and learning quality. This resonated deeply with me and eventually led to my ICML 2024 paper, which proposed a novel data selection strategy showing that carefully chosen subsets can perform equal to or better than using the full dataset.
[Paper](https://proceedings.mlr.press/v235/acharya24a.html)

**A Unifying Pattern:**

Across these diverse problem areas, a common theme emerges: deep learning advances not only by learning more, but by choosing what matters.
