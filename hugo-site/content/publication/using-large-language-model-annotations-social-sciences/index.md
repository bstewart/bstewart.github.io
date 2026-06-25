---
title: 'Using Large Language Model Annotations for the Social Sciences: A General Framework of Using Predicted Variables in Downstream Analyses'
date: '2026-01-01'
authors:
- Naoki Egami
- Musashi Hinck
- Brandon M. Stewart
- Hanying Wei
publication_types:
- journal_article
publication: Conditionally accepted at American Journal of Political Science.
abstract: >-
  Social scientists use automated annotation methods, such as supervised machine learning and, more recently, large language models (LLMs), that can predict labels and generate text-based variables. While such predicted text-based variables are often analyzed as if they were observed without errors, we show that ignoring prediction errors in the automated annotation step leads to substantial bias and invalid confidence intervals in downstream analyses, even if the accuracy of the automated annotations is high, e.g., above 90%. We propose a framework of design-based supervised learning (DSL) that can provide valid statistical estimates, even when predicted variables contain non-random prediction errors. DSL employs a doubly robust procedure to combine predicted labels and a smaller number of expert annotations. DSL allows scholars to apply advances in LLMs to social science research while maintaining statistical validity. We illustrate its general applicability using two applications where the outcome and independent variables are text-based.
citation: 'Naoki Egami, Musashi Hinck, Brandon M. Stewart, Hanying Wei. Using Large Language Model Annotations for the Social Sciences: A General Framework of Using Predicted Variables in Downstream Analyses. Conditionally accepted at American Journal of Political Science.'
bibtex: |
  @unpublished{egami2026llmannotations,
    title = {Using Large Language Model Annotations for the Social Sciences: A General Framework of Using Predicted Variables in Downstream Analyses},
    author = {Egami, Naoki and Hinck, Musashi and Stewart, Brandon M. and Wei, Hanying},
    note = {Conditionally accepted at American Journal of Political Science},
    year = {2026}
  }
image_alt: "Figure 4 from Using Large Language Model Annotations for the Social Sciences comparing bias, coverage, and RMSE when ignoring prediction errors versus using design-based supervised learning."
links:
- name: Preprint
  url: https://naokiegami.com/paper/dsl_ss.pdf
- name: Software
  url: https://naokiegami.com/dsl/
tags:
- "AI Annotation & Predicted Variables"
- "Causal Inference with Text"
- "Generative AI & LLMs"
slug: using-large-language-model-annotations-social-sciences
url: /publication/using-large-language-model-annotations-social-sciences/
---
