# [Exchanging Lessons Between Algorithmic Fairness and Domain Generalization](https://arxiv.org/abs/2010.07249)

### Problem
This paper discusses some common goals in domain generalization and algorithmic fairness. It tries to draw connections between the two areas and suggests lessons can be both learned from each other.

Specifically, this paper studies the problem of domain generalization with unknown environment information. This problem also can be linked to the problem of algorithmic fairness without knowing sensitive information.

### Solution
This paper draws inspiration from fairness methods that optimize worst-case performance without access to demographic information. Specifically they propose a bi-level optimization: 1) fix the classifier and infer the environment assignments; 2) fix the environments and optimize the classifier.

### Some insights
This paper argues that a representation map based on spurious feature will maximally violates the Environments Invariant Principle and suggests learning correct causal features.