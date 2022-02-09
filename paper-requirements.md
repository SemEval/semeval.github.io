# Paper Submission Requirements

This page describes requirements for papers submitted to and published in [SemEval](https://semeval.github.io/). For other questions about SemEval, see [the FAQ](faq.html).

There are two kinds of papers: **system description papers**, which every team participating in a task has the option to submit; 
and **task description papers** written by each set of task organizers. 
Papers accepted following peer review will be part of the official SemEval proceedings, and eligible for presentation at the workshop.

For your paper to be accepted and published, it must conform to the following guidelines. Contact your task organizers if you have questions about the guidelines.

## Year-Specific Logistics

### Dates, Submission Site

See the homepage for a detailed schedule with the submission deadline, acceptance notification date, and camera-ready submission deadline, 
as well as the link to the submission form.

### Style Files

To write your paper, please use LaTeX style files issued by the conference SemEval is colocated with. 
The files contain details on the required page layout and formatting. 
Make sure to follow all those instructions—except the parts for which SemEval has separate requirements, specified below.

## Length

### Submissions for review

System paper submissions for a single task can be up to **5 pages**.

Some teams participating in multiple related (sub)tasks choose to publish a single system paper. In this case the limit is **8 pages**.

Task description papers (written by task organizers) can be up to **9 pages**.

Acknowledgments, references, and appendices do NOT count toward page limits.

### Camera-ready versions

Once accepted, your final paper may have an additional page so you can address reviewer feedback. 
Thus: 6 pages for a single-task system, 9 pages for multiple (sub)tasks, 10 pages for task descriptions (not counting acknowledgments/references/appendices).

## Title

SemEval paper titles follow a fixed template, where YYYY represents the year and N represents the task number:

* System description papers for one task (any number of subtasks) are titled "Team Name at SemEval-YYYY Task N: Descriptive Title" 
  * Note "at", not "@"
  * Note that "SemEval" and the year are separated by a hyphen and no spaces, e.g. "SemEval-2020"
  * Note that the task number is followed by a colon, not a dash
  * Note that the colon has a space after it but not before it
  * Authors are free to choose the Descriptive Title as they would a normal paper title; it may mention a particular question addressed, method used, or finding discussed in the paper
* System description papers for *multiple* tasks are titled "Team Name at SemEval-YYYY Tasks N1 and N2: Descriptive Title" (2 tasks) or "Team Name at SemEval-YYYY Tasks N1, N2, and N3: Descriptive Title" (3 or more tasks)
* (UPDATED) Task description papers are titled "SemEval-YYYY Task N: Task Name"

## Authors

At SemEval, papers are not anonymous when submitted for review
(for both system description papers and task description papers).
Enter your names and affiliations on the paper.

## Contents

System description papers should focus on:

* **Replicability:** present all details that will allow someone else to replicate your system
* **Analysis:** focus more on results and analysis and less on discussing rankings; report results on several runs of the system (even beyond the official submissions); present ablation experiments showing usefulness of different features and techniques; show comparisons with baselines.
* **Duplication:** cite the task description paper; you can avoid repeating details of the task and data, however, briefly outlining the task and relevant aspects of the data is a good idea. (The official BibTeX citations for papers will not be released until the camera-ready submission period, so during the initial submission, please use some sort of placeholder citation.)

For a detailed outline, as well as links to some past system description papers, see [these guidelines](https://semeval.github.io/system-paper-template.html).

Task description papers should focus on:

* **Replicability:** present all details that will allow someone else to replicate the data creation process and evaluation.
* **Analysis:** focus more on results and analysis and less on discussing rankings
* **Summary of systems:** Summarize the techniques, features, and resources used. Highlight what tended to work and what did not, across the systems.

## Paper awards

Two overall awards are given to papers—one for organizers of a task and one for a team participating in a task. The awards are:

* **Best Task (task organizers):** This award recognizes a task that stands out for making an important intellectual contribution to empirical computational semantics, as demonstrated by a creative, interesting, and scientifically rigorous dataset and evaluation design, and a well-written task overview paper.
* **Best Paper (task participants):** This award recognizes a system description paper that advances our understanding of a problem and available solutions with respect to a task. It need not be the highest-scoring system in the task, but it must have a strong analysis component in the evaluation, as well as a clear and reproducible description of the problem, algorithms, and methodology.

SemEval-2020 winners: <https://semeval.github.io/semeval2020-awards>
SemEval-2021 winners: <https://semeval.github.io/SemEval2021/awards>

## Reminders for final version

* Ensure that **author names** are properly capitalized in START metadata and appear in the same order/spelling/capitalization as the PDF
* Ensure that you have mentioned the language(s) of data used in the paper
* If you are releasing code or data, include the URL in the paper
* If the research raises ethical considerations (e.g. potential for misuse), these should be discussed in the paper
* If a system paper, make sure to **cite the task description paper**
