---
layout: post
title:  Impact Evaluations III - Non-experimental Methods
date: 2016-06-29 10:32:36
published: false
categories: [harvard]
tags: [continuing-eduction]
---



## Preparation for...

- DATE: Wednesday, June 29
- TIME: 9:00 – 10:30 pm
- CLASS: Impact Evaluations III - Non-experimental Methods
- FACULTY: Dan Levy
- CASE: "Essential Reading: Designing Impact Evaluations: Assessing Jamaica’s PATH Program", HKS Case 1903.0
- READING: [Impact Evaluation in Practice - Pages 81-86 (Regression Discontinuity), Pages 95-102 (Differences in Differences) and Pages 107-115 (Matching)](https://www.dropbox.com/s/x1bsfxlesqzw9eh/Reading%20-%20Levy_Impact_Evaluation_in_Practice_Pages%2081-86_95-102_107-115.pdf?dl=0)

## Study Questions
**Q1:** Discussion Question #1 in Case Study:
Imagine yourself in the role of the Director of the Social and Manpower Planning Division. Create a table or list in which you assess the strengths and weaknesses of each design. Be sure to consider:

a. The scientific quality of the design, i.e. its ability to estimate the true impact of PATH on the key outcomes of interest.

- Design 1 is a matching approach and this does not allow us to state that the comparison group is equivalent to the treatment group with regards to *unobservable* chracteristics. Since the participation group is randomly selected it will have fair external validity but since the control group is matched there is lack of internal validity. Design 1 also lacks adequate statistical power because the sample size available is less then the suggested sample size of 2,500 for each treatment and control group.
- Design 2 is an RDD approach which can estimate the impact near the cutoff mark but is not robust to individuals at the lower part of the index - lacks external validity. Only generalizes to the *marginal* PATH participants. 
- Design 3 is most appropriate as it is most representative of RCTs. Good internal validity. 

b. The political and administrative feasibility of implementing the design

- Design 3 is both political and administrative feasibile because it provides the best indication of the true impact plus it does not have moral impacts since both samples are taken just above the cutoff. **Class note:** lots of debate regarding whether design 3 is politically feasible.
- Design 1 & 2 are harder to sell politically because they do not provide a robust estimate of the *true* impact

c. The logistical implications of the design, in terms of ensuring that findings from the evaluation are available in a timely manner for policymakers.

- Design 1 would be the quickest since it has existing data. So if leadership needed a "fair" estimate as quick as possible design 1 is an option but if we have the extra time then design 3 is going to provide a much more true impact.

d. The financial implications of the design, in particular if it involves more resources than those already budgeted.

- Design 1 will likely have lower cost since the control group baseline data has already been collected


**Q2:** Which evaluation design would you choose? Provide your justification for your selection in one paragraph.



## Notes

Statistical Power:

- the decision maker needs to have an impact level of their program that they believe is meaningful
- once the impact is decided then we can back into the power / sample size required
- its important to consider the level of impact desired for each metric/output the decision maker wants to track; we should develop the power/sample size required for each output and then aggregate this to a total sample size required


### Regression Discontinuity Design (RDD)
The regression discontinuity design (RDD) is an impact evaluation method that can be used for programs that have a continuous eligibility index with a clearly defined cutoff score to determine who is eligible and who is not

To apply a regression discontinuity design, two main conditions are needed:

1. A continuous eligibility index
2. Clearly defined cutoff score

Downfalls:

- The estimated impact is only valid in the neighborhood around the eligibility cutoff score


### Difference-in-Differences

- Offers the evaluator an additional set of tools that can be applied in situations in which the program assignment rules are less clear or in which randomization or RDD is not feasible
- Requires the existence of baseline data
- Requires stronger assumptions than randomized selection methods
- Compares the changes in outcomes over time between a population that is enrolled in a program (the treatment group) and a population that is not (the comparison group)
- Does not require us to specify the rules by which the treatment is assigned
- We are canceling out (or control- ling for) not only the e ect of observed time-invariant characteristics but also the e ect of unobserved time-invariant characteristics such as those mentioned above.

Simple approach:

- The difference in the before-and-after outcomes for the enrolled group—the first difference—controls for factors that are constant over time in that group, since we are comparing the same group to itself
- Then measure the before-and-after change in outcomes for a group that did not enroll in the program but was exposed to the same set of environmental conditions—the second difference
- Subtract the control difference from the treatment difference


Downfalls:

- difference-in-differences allows us to take care of di erences between the treatment and the comparison group that are constant over time, it will not help us eliminate the di erences between the treatment and comparison groups that change over time
- we must *assume* that, in the absence of the program, the outcome in the treatment group would have moved in tandem with the outcome in the comparison group.
- A good validity check is to compare changes in outcomes for the treatment and comparison groups before the program is implemented


### Matching

- enables you to identify the set of nonenrolled households that look most similar to the treatment households, based on the characteristics that you have available in your data set
- Since propensity score matching is not a real randomized assignment method, but tries to imitate one, it belongs to the category of quasi-experimental methods
- the program’s impact is estimated by comparing the average outcomes of a treatment or enrolled group and the average outcome among a statistically matched subgroup of units, the match being based on observed characteristics available in the data at hand
- In practice, matching methods are typically used when randomized selection, regression discontinuity design, and difference-in-differences options are not possible


Downfalls:

- If the list of relevant observed characteristics is very large, or if each characteristic takes on many values, it may be hard to identify a match for each of the units in the treatment group
- he curse of dimensionality can be quite easily solved using a method called “propensity score matching” (Rosenbaum and Rubin 1983) -- computes the probability that a unit will enroll in the program based on the observed values of its characteristics, the so-called propensity score
- It may happen that for some enrolled units, no units in the pool of nonenrollees have similar propensity scores
- they require extensive data sets on large samples of units
- matching can only be performed based on observed characteristics; by defi- nition, we cannot incorporate unobserved characteristics in the calculation of the propensity score










