# [Generalization and Invariances in the Presence of Unobserved Confounding](https://arxiv.org/abs/2007.10653)

### Task:
The ability of extrapolate, from observed to new related environments.

### Problem:
Most methods fail when moving beyond i.i.d data.

### Reasons:
1) Ignoring causal structure.
2) Unobserved data, such as hidden confounders.

### Arguments:
1) Generalization with respect to a broader class of distribution shifts, observed, unobserved, or target variables.
2) Explicit notion of generalization to certain new environments.
3) Formulate a general objective pairing with gradient-based learning algorithm, that has a causal interpretation.

### Questions:
1) Why there is no statistical test for confounding, why many think there is, and why they are almost right.
2) Unobserved confounders represent a structural limitation for the reliability of prediction algorithms.

### Contribution:
Approaching the "right" set $\mathcal{P}$ by learning the "structure" of $P$ from heterogeneous data, which is an affine combination of heterogeneous data sources, with solutions admitting a causal interpretation under certain conditions.