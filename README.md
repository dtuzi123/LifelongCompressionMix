
# Lifelong Compression Mixture Model via Knowledge Relationship Graph

>📋 This is the implementation of Lifelong Compression Mixture Model via Knowledge Relationship Graph

>📋 Accepted by AAAI 2023

# Title : Lifelong Compression Mixture Model via Knowledge Relationship Graph

# Paper link : 


# Abstract
Task-Free Continual Learning (TFCL) represents a challenging scenario for lifelong learning because it does not access any task information. The Dynamic Expansion Model (DEM) has shown promising results in this scenario due to its scalability and generalisation power. However, existing work from DEM focuses only on addressing forgetting and ignores model compression, which is hardly deployed in practical systems. In this work, we aim to simultaneously address network forgetting and model compression by developing the Lifelong Compression Mixture Model (LGMM) equipped with the maximum mean discrepancy (MMD) based expansion criterion for model expansion. A diversity-aware sample selection approach is proposed to selectively store a variety of samples to promote information diversity among the components of the LGMM, which allows more knowledge to be captured with an appropriate model size. Since we can not access the past data and task information in TFCL, it is challenging to apply the existing compression technologies in LCMM. Inspired by this, we propose a data-free component discarding mechanism that evaluates a knowledge relation graph matrix describing the relevance between each pair of components. A greedy selection procedure is proposed to statistically select  overlapping components and remove them from the LGMM. The proposed discarding mechanism can be performed during or after the training. Experiments on different datasets show that LGMM achieves the best performance for TFCL.

# Environment

1. Tensorflow 2.1
2. Python 3.6

# Training and evaluation

>📋 Python xxx.py, the model will be automatically trained and then report the results after the training.

>📋 Different parameter settings of OCM would lead different results and we also provide different settings used in our experiments.

# BibTex
>📋 If you use our code, please cite our paper as:


