# [Causality Lecture Notes](http://web.math.ku.dk/~peters/jonas_files/scriptChapter1-4.pdf)

## Introduction

### Motivation

Correlation vs Causation, from the view of two different distributions.

- Observations due to the confounding.
- Simpson paradox.
    + Maybe caused by an unknown common cause.
- Where statistical test does not work.
    + When applying statistical test on both groups, the differences of recovery rates for both treatments are not significant.
    + When multiply each factor by 10, the results are significant, which means it is highly influenced by the amount of the population.
    + Here it also means that the causal effect, is not directly related to the amount of the data.
- Combine observational and intervention data.
- More complex changes, parameter setting in policy.

### Graph

## Structural Equation Models

### Definition
- A set of equations associated with a graph, and a topological order.
- The set of equations define the joint distribution of X, both for observational and interventional.
- With or without a causal order at hand is important, because finding a causal order from observations is difficult.
- Model class in the equations can be different, for simplicity one can assume linear equations.
- SEM is a tuple, S represents equations and N represents the independent random noises.

### Intervention
- Construct a distribution \tilde{P}^x from the observed distribution P^x.
- For intentional distributions we replace some equations with new ones.
- Several different kinds of 'changes': atomic, soft/stochastic.
- Whether (or not) exists (total) causal effect: independence test after do intervention on 'causes'.
- Similar to Randomized Controlled Trials, randomly assigning treatments.
- The changes of distribution of 'Parents' by doing intervention on 'Descendants' or conditioning on 'Descendants' are different. 
