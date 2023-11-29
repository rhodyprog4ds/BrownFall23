
# Assignment 12: Fake News

## Quick Facts
- [accept the assignment](https://classroom.github.com/a/QRTv4_g_)
- __first: 2023-11-29__
- __final: 2023-12-07__

```{note}
there are 2 deadlines for this instead of an assignment 13. This means that we will review whatever you have done by the 29th on 11/30 and give you personalized feedback in order to finish the assignment.  
```
<!-- - First feedback: {{ early }}
__Final due date: {{ date }}__ -->


## Related notes

- [representing text](../notes/2023-11-21)
<!-- - [more text representations](../notes/2023-11-28) -->

## Assessment

Eligible skills: (links to checklists)
- **first chance** representation [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#representation-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#representation-level2) 
- **first chance** workflow [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#workflow-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#workflow-level2) psuedo code and explanation is enough for this
- compare [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#compare-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#compare-level2)
- optimization [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#optimization-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#optimization-level2)
- clustering [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#clustering-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#clustering-level2)
- classification [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#classification-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#classification-level2)
- evaluate (must use extra metrics to earn this here) [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#evaluate-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#evaluate-level2)
- summarize [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#summarize-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#summarize-level2)
- visualize [1](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#visualize-level1) and [2](https://rhodyprog4ds.github.io/BrownFall23/syllabus/achievements.html#visualize-level2)


## Instructions

Use the dataset in the assignment template repo to answer the following questions.

1. Is the text or the title of an article more predictive of whether it is real or fake?
1. Are titles of real or fake news more similar to one another?

The data includes variables:
- ‘text’: contents of an article
- ‘label’: whether it is real or fake news
- 'title': title of the article

Include narrative around the code required to answer these and interpret the results to give an actual answer. 
- Provide context on your answer and consider how strong it is based on what differences you can have in how you represent the data and how that might impact your model performance. 
- Consider if the analysis you have done is enough evidence answer the question from the analysis you have completed or could something else chang the answer. 
- Use summary statistics and visualizations appropriately in order to explain your results.

```{hint}
The data set contains a large number of articles (takes a long time to train), you can downsample this to something like a 1,000 articles or so in order to speed up training and evaluation (hint: use shuffle).

```
