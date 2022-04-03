# [Occam`s Razor](https://papers.nips.cc/paper/2000/file/0950ca92a4dcf426067cfd2246bb5ff3-Paper.pdf)

### Introduction
Occam`s Razor influences scientific thinking in general and in problems of statistical inference in particular. In this paper the authors review its consequences for Bayesian statistical models, where its behaviour can be easily demonstrated and quantified.

This paper focuses on complex models with large numbers of parameters which are often referred to as non-parametric. 

Inference is not primarily targeted at the parameters themselves, but rather at the predictions made by the models.

Typically an estimator of the generalization error or an independent validation set is used to control the model complexity.

Question: Should we use Occam`s Razor to determine the optimal number of hidden units in a neural network or should we simply use as many hidden units as possible computationally?

#### View 1: Model size selection
One of the central quantities in Bayesian learning is the evidence, the probability of the data given the model $P(Y|M_i)$.

The evidence discourages overcomplex models, and can be used to select the most probable model.

#### View 2: Large models
It makes sense to use large models (no matter how much data you have) and pursue the infinite limit if you can.

We don`t need or want to use Occam`s Razor to limit the number of parameters in our model.

### Discussion
Depending on the scaling properties of the prior over parameters, both the Occam`s Razor view and the large models view can seem appropriate.

### Conclusion
While not necessarily penalizing the number of parameters, this process is active in terms of the complexity of functions.

We don`t seriously believe that the "true" generative process can be implemented exactly with a small model. Whichever view we take, Occam`s Razor is always at work discouraging overcomplex models.