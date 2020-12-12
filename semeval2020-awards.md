---
title: SemEval-2020 Awards
---

# SemEval 2020: Best Task, Best Paper!!

[SemEval-2020](http://alt.qcri.org/semeval2020) features two overall awards, one for organizers of a task and one for a team participating in a task.

We are very pleased to announce the winners of these awards for SemEval-2020!

## Best Task Award

The Best Task award, for organizers of an individual shared task, recognizes a task
that stands out for making an important intellectual contribution to empirical computational
semantics, as demonstrated by a creative, interesting, and scientifically rigorous dataset 
and evaluation design, and a well-written task overview paper.

### :sparkles: :star2: [Best Task 2020: Task 7, Assessing Humor in Edited News Headlines](https://www.aclweb.org/anthology/2020.semeval-1.98/):star2::sparkles:
### _Nabil Hossain, John Krumm, Michael Gamon, and Henry Kautz_

The set-up for this computational humor task combines cleverness and simplicity, 
resulting in a challenging yet accessible task. The dataset consists of headlines 
which have been edited for potentially humorous results—in each case, one word in 
the headline has been replaced—as well as funniness ratings acquired by crowdsourcing. 
Task participants could participate in either of two subtasks: 1) assign a funniness score
to edited headlines, 2) identify the funniest of two edited versions of the same headline. 
The task description paper is well-written and includes insightful analysis both 
of the performance of participating systems and of interesting aspects of the task. 

#### :sparkles:[Honorable Mention: Task 4, Commonsense Validation and Explanation](https://www.aclweb.org/anthology/2020.semeval-1.39/):sparkles:
#### _Cunxiang Wang, Shuailong Liang, Yili Jin, Yilong Wang, Xiaodan Zhu, and Yue Zhang_

This task addresses the important task of distinguishing between natural language utterances that make sense (according to commonsense knowledge)
and those that do not. The dataset combines natural language statements with explanations. More specifically, each instance consists of two 
similarly-worded statements (with one making more sense than the other), three candidate explanations for why the less-reasonable statement 
doesn’t make sense, one identified best explanation (selected from the candidates), and two alternate phrasings of the best explanation. 
This dataset can be extremely useful for future work on commonsense reasoning. Three subtasks were available to participants: 1) selecting 
the more sensible of the two statements, 2) choosing the best explanation from the three candidates, and 3) generating an explanation. The 
paper provides thorough explanations of the task, the dataset and its construction, and the evaluation metrics, as well as detailed analysis of the dataset. 
It concludes with an overview of the systems participating in the task.

#### :sparkles:[Honorable Mention: Task 11, Detection of Propaganda Techniques in News Articles](https://www.aclweb.org/anthology/2020.semeval-1.186/):sparkles:
#### _Giovanni Da San Martino, Alberto Barrón-Cedeño, Henning Wachsmuth, Rostislav Petrov, and Preslav Nakov_

This task addresses the very important and very difficult challenge of identifying propagandistic techniques as used in news articles. 
Following a complex interdisciplinary literature on methods of propaganda, the task organizers devise an inventory of 14 propaganda types 
and create a dataset in which news articles are labeled for text spans containing at least one propaganda technique. Each span is then 
labeled with the particular technique used in the span. The structure of the dataset parallels the two subtasks of span identification and 
technique classification. The paper provides a very detailed analysis of the different types of 
systems developed by participants, as well as their respective performance on the two subtasks.

## Best Paper Award

The Best Paper award, for task participants, recognizes a system description paper that advances our understanding of a problem and 
available solutions with respect to a task. It need not be the highest-scoring system in the task, but it must have a strong analysis 
component in the evaluation, as well as a clear and reproducible description of the problem, algorithms, and methodology.

### :sparkles: :star2:[Best Paper 2020: ApplicaAI at SemEval-2020 Task 11: On RoBERTa-CRF, Span CLS and Whether Self-Training Helps Them](https://www.aclweb.org/anthology/2020.semeval-1.187/) :star2::sparkles:
### _Dawid Jurkiewicz, Łukasz Borchmann, Izabela Kosmala, and Filip Graliński_

This paper approaches the task of propaganda detection and classification, successfully combining modern neural models (Transformers) 
with more traditional machine learning models (Conditional Random Fields) and methods (self-training). The presentation of the results 
is exemplary, reporting variance from random seeds, and an ablation study of the most important model components. The error analysis is 
insightful, identifying which classes are most often confused and which linguistic features correlate with model errors. 
Overall, there are clear conclusions for future researchers looking at this task, or looking to apply these techniques to other tasks.

#### :sparkles:[Honorable Mention: SESAM at SemEval-2020 Task 8: Investigating the relationship between image and text in sentiment analysis of memes](https://www.aclweb.org/anthology/2020.semeval-1.102/):sparkles:
#### _Lisa Bonheme and Marek Grzes_

This paper approaches the task of sentiment analysis of memes, with a careful consideration of how to combine features from the text 
and the image. Although the results could be seen as negative, because the multimodal models overall performed no better than text-only 
or image-only models, the clear presentation of the results highlights the challenges of dealing with multimodal data. 
The results are supported by an analysis of the dataset using Canonical Correlation Analysis.
