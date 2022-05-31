# [Explaining the Black-box Smoothly A counterfactual Approach](https://arxiv.org/abs/2101.04230)

### Important Notes

- Rather than location information, what features, how these features can be modified to change the classifier decision.
- Using an additional variable $\delta$ to control how far the generated images are from the original image. Align this distance with the outcome of the model from the original class.
- Gradually transform the input image to the counterfactual, following three properties: data consistency, classification model consistency, and context aware self-consistency.
- Using two clinical metrics (cardiothoracic ratio CTR, normal Costophrenic recess SCP) to demonstrate the clinical relevance of explanations.
- Metrics to compare counterfactual explanations: Frechet Inception Distance (FID) score to assess visual quality, counterfactual validity (CV) score to quantify compatibility with the classifier, and foreign object preservation (FOP) score to evaluate the retention of patient-specific information in the explanations.