# [Knowledge-Gradient Methods for Statistical Learning](https://people.orie.cornell.edu/pfrazier/pub/FrazierDissertation.pdf)

### Introduction, Information Collection Problem

One makes decisions about how much and of what type of information to collect about some unknown.

E.g.  At each patient visit, the doctor collects information about the effectiveness of the currently prescribed medications and decides which mix of drugs and dosages the patient should take until the next visit, and when this visit should occur.

In making information collection decisions one implicitly trades the cost of collecting the
information, against the benefit of the information obtained, which is the ability to make better decisions in the future.

The literature from which the work in this thesis originates is the ranking and selection
(R&S) literature.

Our goal in R&S is to allocate these measurements as efficiently as possible across the alternatives in order to be able to accurately choose which alternative is best with as few measurements as possible.

### Examples

#### Stopping decisions
Information collection decision is a stopping time that adaptively chooses how much information to collect

Early warning systems, Group sequential clinical trials, Drug recall

#### Decisions from a finite set
Screening of shipping containers, Collaborative filtering.

#### Continuous univariate decisions
Information collection decisions is chosen from a one-dimensional continuous or discrete space.

Product pricing, Sequential planning, Drug dosing

#### Continuous multivariate decisions
Information collection decisions is chosen from a multidimensional continuous space.

Model calibration.

