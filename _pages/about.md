---
permalink: /
title: "?"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently doing a MSc in Computer Science (Artificial Intelligence Major) at University of Galway.

My research interests span across AI Safety, Bayesian Models of Cognition and Program Syntheis.


## Current Work

### MSc Thesis
*expected August 2026*
A combination between AI Debate, Human-AI complementarity and computational modelling.

### [Investigating the limits of free-form debate as a scalable oversight strategy](https://openreview.net/pdf?id=vRCGzuAhOM) *Accepted to TMLR!* 
Abstract: Debate is a scalable oversight method involving two copies of a strong model trained to defend alternative responses to a question, with a judge with less task-relevant information, time, or domain-specific capability evaluating which answer is better supported. We repli- cate and extend a result from prior work demonstrating that training Llama3-8B-Instruct- 262k as a debater led to increased performance of a GPT-4-class judge model on QuALITY, a question-answering task that grants the debaters a capability advantage via information asymmetry. When replicating the original setup as closely as possible, we confirm that training debater models in free-form, multi-round debate increased judge accuracy. How- ever, this finding did not generalize across alternative tasks or models, and did not replicate consistently under our closest approximation to the original setting. These results suggest that the effectiveness of free-text debate as a scalable oversight method is sensitive to task structure, model pairing, and training conditions, and highlight the need for greater under- standing of when and why debate improves judge accuracy. We identify several factors that may influence debate’s success and outline directions for future work aimed at characterizing the conditions under which debate strengthens oversight reliably.
------

### [Toward Human-AI Complementarity Across Diverse Tasks](https://arxiv.org/abs/2605.04070)
*Preprint (arXiv); under review*
------
Abstract: Human-AI complementarity, the idea that combining human and AI judgments can outperform either alone, offers a promising pathway toward robust oversight of advanced AI systems. However, whether human-AI complementarity can be achieved on realistic tasks remains an open question. We investigate this through two approaches: hybridization and two AI assistance methods (top-2 assistance and subtask delegation), evaluated on a multi-domain dataset of 1,886 samples spanning knowledge, factuality, long-context reasoning, and deception detection. We find only modest complementarity gains. Baseline hybridization yields just +0.4 percentage points (pp) over AI alone (69.3% vs 68.9%), limited both by a small complementarity region (only 8.9% of items where AI errs but humans do not) and the inability of confidence-based routing to identify it, since the model's confidence is similarly distributed across correct and incorrect predictions. Applied when AI has low confidence, top-2 assistance increases human accuracy from 28.4% to 38.3%, surpassing AI alone (37.7%) -- but primarily because humans adopt correct AI suggestions, not because they successfully override AI errors. These findings suggest that the primary bottleneck is not human task accuracy per se, but the ability to route decisions to humans when it matters and to design assistance methods that enable humans to catch AI mistakes. Our quantitative and qualitative analyses pinpoint where and why each method succeeds or fails, offering concrete targets for future work. We will release our dataset and code upon request to support progress toward more effective human-AI collaboration for AI oversight.

### Human-Mediated Sensing for AI Decision-Making Under Uncertanty - Waiting on conference acceptance.
*under review*
