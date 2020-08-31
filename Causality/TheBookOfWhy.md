# The Book of Why

### Chapter 1

P5, the statistics focused exclusively on how to summarize data, not on how to interpret it.

**The calculus of causation consists of two languages: causal diagrams, to express what we know, and a symbolic language, resembling algebra, to express what we want to know.** 

P8, language of knowledge and language of queries, e.g. $P(L|do(D))$.

P9, seeing the barometer fall increases the probability of the storm, while forcing it to fall does not affect this probability. *Conditional probability and intervention*.

### Chapter 2

- Galton board

*Central Limit Theorem*, *Laplace Theorem*.
The random process that amounts to a sum of large number of coin flips lead to the same probability distribution, normal distribution.

- Regression toward the mean

When Galton study the distribution of populations across generations or between two variables, he found the phenomenon of *regression toward the mean*.
- The model of success.
 $Success = talent + luck$.
 $Great success = big talent + a lot of luck$.
 Galton`s model consider luck as inheritable, which is not correct. Talent is inheritable and replace success.

- Person`s correlation coefficient.

 Person and Galton found the leap from mathematics to biology and economy. The *correlation* between two variables, expressed by the data. The *two variables* can be chronological or tabular.
 When doing study on correlations, Person also found *Spurious correlations* and the phenomenon of *Simpson paradox*.
 While both of them ignored *Causation* from statistics.

- Genetics, heredity, and path *diagrams*. 

 Sewall Wright developed a mathematical method for answering causal questions from data. 
 Path diagrams are the tool that bridge rung one and rung two. Two languages are included in Wright`s work: one is diagram, another is data. 
 Causal analysis is not to prove that $X$ is cause of $Y$; It is representing causal knowledge in some mathematic language (e.g. diagram), combining it with data, and answering causal queries.

- E PUR SI MUOVE (and yet it moves).

 Path diagrams developed into structural equation models. Sometimes patterns from aggregated data cannot reflect true causal quantities, because of the bias. Causal model can help us disentangle the bias from data, and recover the true quantities of causal queries.

- Bayesian connection: from objectivity to subjectivity.

 Prior belief + new evidence = revised belief. The prior belief provides space for human subjectivity, which distinguish Bayesian methods from orthodox statistical methods. However, the prior belief is still not causal model because it is only based on probability language, not diagrams.  

### Chapter 3

- Bayes`s rule

  Bayes`s rule offers a general solution to the inverse-probability problem.
  The most important role of Baye`s rule in statistics is: we can estimate the conditional probability directly in one direction, for which our judgment is more reliable, and use mathematics to derive the conditional probability in the other direction, for which our judgment is rather hazy.

  Bayes`s rule offers an empirical claim to faithfully represent the English expression "given that I know".

- Objections
  
  The philosophical objection stems from the interpretation of probabilities as a degree of belief.

  The language of probability, expressed in symbols like $P(S)$, was intended to capture the concept of frequencies in games of chance. But the expression "given that I know" is epistemological and should be governed by logic of knowledge, not that of frequencies and proportions.

- Robustness
  
  The inverse probability e.g. $P(disease|test)$ is not the same for everyone; it is context dependent. The forward probability does not depend on whether you are high risk or not. It is "robust" to such variations. It remains relatively invariant to the reasons for the disease (epidemic, diet, hygiene, socioeconomic, status, family history). The inverse probability is sensitive to these conditions.
