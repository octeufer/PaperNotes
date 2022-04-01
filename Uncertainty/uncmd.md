# [Second opinion needed: communicating uncertainty in medical machine learning](https://www.nature.com/articles/s41746-020-00367-3)

### Introduction
The quantification and communication of uncertainty for individual predictions is often neglected even though uncertainty estimates could lead to more principled decision-making and enable machine learning models to automatically or semi-automatically abstain on samples for which there is high uncertainty.

Diagnostic and prognostic classification models estimate the same statistical quantity, diagnosis and prognosis differ greatly in their interpretation and use cases.

### Details

Dataset shift is an important component of predictive uncertainty in practice.

Predictive uncertainty in this case would be the size of the conformal set.

MC dropout and ensembling can be summarized by calculating the standard deviation from the collection of predictions.

Gaussian processes are an alternative Bayesian method that have natural predictive uncertainty estimates built in.

### Conclusion
The uncertainty-equipped models will be able to improve patient care, engender physician trust, and guard against dataset shift or adversarial attacks.