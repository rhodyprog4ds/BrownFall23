# Assignment 9: Linear Regression

## Quick Facts
- [accept the assignment](https://classroom.github.com/a/HlXVb4Ll)
- __Due: 2023-11-06__


## Assessment

Eligible skills: (links to checklists)


- **first chance** regression [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#regression-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#regression-level2)
- process [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#process-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#process-level2)
- evaluate [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#evaluate-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#evaluate-level2)
- summarize [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#summarize-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#summarize-level2)
- visualize [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#visualize-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#visualize-level2)



## Related notes

- [](../notes/2023-03-28)
- [](../notes/2023-03-30)


## Instructions

Find a dataset suitable for regression. We recommend a dataset from the UCI repository. Remember that you can use the filters to choose a dataset that is well-suited for regression. 

### Linear Regression Basics

TLDR: Fit a linear regression model, measure the fit with two metrics, and make a plot that helps visualize the result.

1. Include a basic description of the data(what the features are, units, size of dataset, etc)
2. Write  your own description of what the prediction task it, why regression is appropriate.
3. Fit a linear model on all numerical features with 75% training data.
4. Test it on 25% held out test data and measure the fit with two metrics and one plot
5. Inspect the model to answer:

    - What to the coefficients tell you?
    - What to the residuals tell you?
6. Repeat the split, train, and test steps 5 times.

    - Is the performance consistent enough you trust it?
7. Interpret the model and its performance in terms of the application. Some questions you might want to answer in order to do this include:

  - do you think this model is good enough to use for real?
  - is this a model you would trust?
  - do you think that a more complex model should be used?
  - do you think that maybe this task cannot be done with machine learning?
1. Try fitting the model only on one feature. Justify your choice of feature based on the results above.  Plot this result.



```{hint}
For python level 2, summarize level 2 or visualize level 2 expand the "Repeat the split test and train" step a little.  


- Use a loop to vary a variable of the analysis, repeat more times, or similar. 
- Answer a question about regression and when it works, by putting all of the results into a dataframe
```