# Guidelines for SemEval System Papers

This document is intended for participants in any of the [SemEval](http://semeval.github.io) shared tasks.
It offers a template for how you, the author, can structure your system description paper to be as clear and complete as possible.

NOTES: 

1. Be sure to use the official stylesheet and follow its instructions.
2. Your paper should stand on its own. Don’t assume that your reader is familiar with the task. 
3. This document is just a guideline for structuring your paper. You can feel free to use a different structure if it makes more sense.
4. Some example system description papers from previous years that you can use as inspiration:
   - <https://www.aclweb.org/anthology/S16-1181>
   - <https://www.aclweb.org/anthology/S14-2030>
   - <https://www.aclweb.org/anthology/S18-1008>
   - <https://www.aclweb.org/anthology/S07-1044> [multiple tasks]
   - Best paper awardees at SemEval-2020: <https://semeval.github.io/semeval2020-awards.html>
5. We would like to emphasize the importance of analysis of your system’s behavior beyond the overall scores. There will be a best paper award to recognize system papers with strong analysis.

## Abstract

- A few sentences summarizing the paper.

## Introduction

- What is the task about and why is it important? Be sure to mention the language(s) covered and cite the task overview paper. ~1 paragraph

- What is the main strategy your system uses? ~1 paragraph

- What did you discover by participating in this task? Key quantitative and qualitative results, such as how you ranked relative to other teams and what your system struggles with. ~1 paragraph

- Have you released your code? Give a URL

## Background

- In your own words, summarize important details about the task setup: kind of input and output (give an example if possible); what datasets were used, including language, genre, and size. If there were multiple tracks, say which you participated in.

- Here or in other sections, cite related work that will help the reader to understand your contribution and what aspects of it are novel.

## System overview

- Key algorithms and modeling decisions in your system; resources used beyond the provided training data; challenging aspects of the task and how your system addresses them. This may require multiple pages and several subsections, and should allow the reader to mostly reimplement your system’s algorithms.

- Use equations and pseudocode if they help convey your original design decisions, as well as explaining them in English. If you are using a widely popular model/algorithm like logistic regression, an LSTM, or stochastic gradient descent, a citation will suffice—you do not need to spell out all the mathematical details.

- Give an example if possible to describe concretely the stages of your algorithm.

- If you have multiple systems/configurations, delineate them clearly.

- This is likely to be the longest section of your paper.

## Experimental setup

- How data splits (train/dev/test) are used.

- Key details about preprocessing, hyperparameter tuning, etc. that a reader would need to know to replicate your experiments. If space is limited, some of the details can go in an Appendix. 

- External tools/libraries used, preferably with version number and URL in a footnote.

- Summarize the evaluation measures used in the task.

- You do not need to devote much—if any—space to discussing the organization of your code or file formats.

## Results

- Main quantitative findings: How well did your system perform at the task according to official metrics? How does it rank in the competition?

- Quantitative analysis: Ablations or other comparisons of different design decisions to better understand what works best. Indicate which data split is used for the analyses (e.g. in table captions). If you modify your system subsequent to the official submission, clearly indicate which results are from the modified system.

- Error analysis: Look at some of your system predictions to get a feel for the kinds of mistakes it makes. If appropriate to the task, consider including a confusion matrix or other analysis of error subtypes—you may need to manually tag a small sample for this.

## Conclusion

- A few summary sentences about your system, results, and ideas for future work.

## Acknowledgments

- Anyone you wish to thank who is not an author, which may include grants and anonymous reviewers.

## Appendix

- Any low-level implementation details—rules and pre-/post-processing steps, features, hyperparameters, etc.—that would help the reader to replicate your system and experiments, but are not necessary to understand major design points of the system and experiments.

- Any figures or results that aren’t crucial to the main points in your paper but might help an interested reader delve deeper.
