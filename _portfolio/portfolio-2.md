---
title: "HiDe-prompt"
excerpt: "Hierarchical Decomposition of Prompt-Based Continual Learning <br/><img src='/images/portfolio2.png'>"
collection: portfolio
---

Prompt-based continual learning is an emerging direction in leveraging pre-trained
knowledge for downstream continual learning, and has almost reached the performance pinnacle under supervised pre-training.
However, our empirical research reveals that the current strategies fall short of their full potential under the more
realistic self-supervised pre-training, which is essential for handling vast quantities
of unlabeled data in practice. This is largely due to the difficulty of task-specific
knowledge being incorporated into instructed representations via prompt parameters and predicted by uninstructed representations at test time. 
To overcome the exposed sub-optimality, we conduct a theoretical analysis of the continual learning objective in the context of pre-training,
and decompose it into hierarchical components: within-task prediction, task-identity inference, and task-adaptive
prediction. Following these empirical and theoretical insights, we propose Hierarchical Decomposition (HiDe-)Prompt, 
an innovative approach that explicitly optimizes the hierarchical components with an ensemble of task-specific prompts
and statistics of both uninstructed and instructed representations, further with the coordination of a contrastive regularization strategy. 
Our extensive experiments demonstrate the superior performance of HiDe-Prompt and its robustness to pretraining paradigms in continual learning (e.g., up to 15.01% and 9.61% lead on
Split CIFAR-100 and Split ImageNet-R, respectively). Our code is available at [code](https://github.com/thu-ml/HiDe-Prompt).

