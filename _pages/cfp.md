---
layout: page
permalink: /call-for-papers/
title: Call for Papers
description:
nav: true
nav_order: 1
---

We welcome researchers working in the field of time series analysis to submit their latest work to the ICLR 2026 workshop on **Time Series in the Age of Large Models**.

## Key Dates

All deadlines are 11:59 pm AoE.

- Submission deadline: **February 14, 2026**
- Acceptance notification: March 1, 2026
- Camera ready deadline: TBD

Submission link: **[OpenReview](https://openreview.net/group?id=ICLR.cc/2026/Workshop/TSALM)**

## Submission Tracks

We welcome submissions across two tracks:

### Research Track (max 4 pages)

We invite research papers presenting novel theoretical insights, methodological advances, or empirical findings related to time series foundation models.

### Industry & Applications Track (max 2 pages)

Recognizing that significant innovation occurs beyond academic settings, we welcome submissions from industry practitioners, open-source contributors, and applied researchers. This track prioritizes practical impact and real-world insights over strict novelty requirements. Submissions may include (a) implementation and evaluation of simple but unpublished ideas, (b) self-contained theoretical results or proofs-of-concept, (c) follow-up experiments or re-analyses of existing work, (d) critiques or novel interpretations of published research, (e) real-world deployment experiences and lessons learned, (f) open-source tools, libraries, datasets, and frameworks, and (g) large-scale applications and production systems.

## Submission Instructions

Submissions should take the form of a short paper of up to 2 or 4 pages. Additional pages containing references and appendices are allowed but reviewers are _not obliged_ to refer to the appendices. Submissions should be made on **OpenReview** in a single `.pdf` file using **[this LaTeX style template](../assets/latex/tsalm-iclr2026-workshop-template.zip)**. The review process is _double-blind_, so please ensure that your submission is properly anonymized. Papers that exceed the page limit or have not been properly anonymized will be desk-rejected without review.

All accepted submissions will be accompanied by a poster presentation. Selected submissions will be invited for oral talks.

**Dual submission policy**: This workshop is **non-archival**; even though all accepted papers will be available on OpenReview, there are no formally-published proceedings. If a paper is currently under review at another venue, it can still be submitted to this workshop. If a paper has previously appeared at a venue, it should be reasonably extended in order to be accepted at this workshop.

**Author LLM Use Policy**: Please refer to [ICLR 2026's LLM use policy for authors](https://iclr.cc/Conferences/2026/ReviewerGuide). 

## Scope and Topics

We invite submissions related to the theme of time series in the age of large models. Key topics include, but are not limited to:

- **Context-informed foundation models for time series:** Most prior work has focused on univariate forecasting, but practical scenarios often require additional context. We welcome contributions on multivariate forecasting, forecasting with static and dynamic exogenous variables, and multimodal forecasting where context comes from other modalities such as text or images. We particularly encourage context-informed models for anomaly detection and classification.

- **Reasoning and time series ML agents:** LLM-powered agents have the potential to democratize ML by enabling domain experts to seamlessly integrate foundation models with classical methods. We welcome submissions on novel agents and scaffolds for time series modeling, benchmarks for evaluating agent performance, and work exploring when agents with time series tools are preferable to tailored foundation models. We also encourage work on reasoning capabilities in time series models, both explicit (e.g., ReAct, CodeAct) and implicit.

- **Benchmarks, datasets, and tools:** We welcome contributions proposing unified benchmarking frameworks, diverse large-scale datasets reflecting real-world complexity, and "live" benchmarks that mitigate memorization concerns. We also encourage work on synthetic data generation for pretraining and open-source tools for large-scale pretraining and inference.

- **Interpretability of large time series models:** As these models are deployed in high-stakes domains, understanding their inner workings becomes critical. We seek methods providing transparency into predictions, including attention analysis, feature attribution, symbolic distillation, and causal interpretability. We also welcome work examining how interpretability methods scale with model size and differ across architectures.

- **Evaluation and real-world applications:** We invite contributions on improved metrics for probabilistic prediction, domain-specific evaluation setups, and work bridging forecasting and downstream decision-making. We also welcome applications in domains such as dynamical systems, finance, human mobility, weather, and healthcare.

## Call for Reviewers

We are looking for reviewers for the workshop. If you would like to serve as a reviewer, please fill out this [Google form](https://forms.gle/33Qz2QjEy6w3sTtG7).

## Reviewer Guidelines

Reviewers should follow these guidelines when evaluating a paper. These guidelines are based on the [reviewer guidelines for TMLR](https://jmlr.org/tmlr/acceptance-criteria.html). 

The acceptance decision for a submission is based on the answers to the following questions:

**Are the claims made in the submission supported by accurate, convincing and clear evidence?**   

This is the most important criterion. This implies assessing the technical soundness as well as the clarity of the narrative and arguments presented. Papers with large gaps between claims and evidence must be rejected. 

- Papers presenting a new method/model with a reasonable proof of concept should be seen as satisfying this criterion. 
- Papers solely presenting empirical analysis should present rigorous comparisons before making general claims. 

**Would at least some individuals in this workshop’s audience be interested in knowing the findings of this paper?**    

This is arguably the most subjective criterion, and therefore needs to be treated carefully. Generally, a reviewer that is unsure as to whether a submission satisfies this criterion should assume that it does. Crucially, it should not be used as a reason to reject work that isn't considered “significant” or “impactful” because it isn't achieving a new state-of-the-art on some benchmark. Nor should it form the basis for rejecting work on a method considered not “novel enough”, as novelty of the studied method is not a necessary criteria for acceptance. We explicitly avoid these terms (“significant”, “impactful”, “novel”), and focus instead on the notion of “interest”. If the authors make it clear that there is something to be learned by some researchers in their area from their work, then the criterion of interest is considered satisfied.

Papers should be accepted if they meet these criteria, even if the contribution or significance of the work is modest. 

Papers that should not be accepted include 
- papers that make bold statements unsupported by empirical or rigorous evidence,
- papers that aren’t clearly written,
- papers that incorrectly claim novelty over existing published work, and
- papers that merely re-implement an idea that has already been reproduced before.

**Reviewer LLM Use Policy**: Please refer to [ICLR 2026's LLM use policy for reviewers](https://iclr.cc/Conferences/2026/ReviewerGuide). 

### Review Format

A review should have the following content.

**Summary of contributions**: Brief description, in the reviewer's words, of the contributions and new knowledge presented by the submission.      
**Strengths and weaknesses**: List of the strong aspects of the submission as well as weaker elements (if any) that you think require attention from the authors.     
**Suggestions**: Any suggestions to improve the paper for future versions.

## Contact

If you have questions about this workshop or are not sure if your paper's topic is suitable for submission, please feel free to contact the organizers at [tsalm-workshop@googlegroups.com](mailto:tsalm-workshop@googlegroups.com).
