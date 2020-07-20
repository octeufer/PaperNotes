# Quantifying Causal Contribution via Structure Preserving Interventions


This paper introduce  **Causal Information Contribution** (CIC) and **Causal Variance Contribution** (CVC) to quantify the influence of each variable in a causal diagram on the targets of interest. The cascade causal effects are introduced by *Functional Causal Model* (FCM), in which the term of random noises recursively leads to Markovian influence. *Structure preserving interventions* are introduced to represent the interventions on unobserved noise variables only. The total uncertainty of a target variable can be attributed to the information from each noise tern via Shapley values.

- Influence in the sense of contribution. 
    + Each author contributed his/her section respectively.
    + $S_A, S_B and S_C$ are independent.
    + $D_A := S_A; Contribution(A) := I(S_A : D_C) = H(S_A)$.
- Influence in the sense of options for actions. 
    + Measure the information that each author has seen and could therefore have changed.
    + This is also called *options to change*, or *potential influence*. 
    + $Opt(A) := I(D_A : D_C) = H(S_A)$.
    + $Opt(B) := I(D_B : D_C) = H(S_A) + H(S_B)$.
- Structure preserving interventions.
    + Do not remove $f_j$ in the equation and change to $X_j := x_j$.
    + Instead, it only acts on noises.
