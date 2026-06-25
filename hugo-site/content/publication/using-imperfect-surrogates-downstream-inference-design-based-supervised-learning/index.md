---
title: 'Using Imperfect Surrogates for Downstream Inference: Design-Based Supervised Learning for Social Science Applications of Large Language Models'
date: '2023-12-01'
authors:
- Naoki Egami
- Musashi Hinck
- Brandon M. Stewart
- Hanying Wei
publication_types:
- conference_paper
publication: Advances in Neural Information Processing Systems, 2023.
abstract: In computational social science (CSS), researchers analyze documents to explain social and political phenomena. In most scenarios, CSS researchers first obtain labels for documents and then explain labels using interpretable regression analyses in the second step. One increasingly common way to annotate documents cheaply at scale is through large language models (LLMs). However, like other scalable ways of producing annotations, such surrogate labels are often imperfect and biased. We present a new algorithm for using imperfect annotation surrogates for downstream statistical analyses while guaranteeing statistical properties -- like asymptotic unbiasedness and proper uncertainty quantification -- which are fundamental to CSS research. We show that direct use of surrogate labels in downstream statistical analyses leads to substantial bias and invalid confidence intervals, even with high surrogate accuracy of 80--90\%. To address this, we build on debiased machine learning to propose
  the design-based supervised learning (DSL) estimator. DSL employs a doubly-robust procedure to combine surrogate labels with a smaller number of high-quality, gold-standard labels. Our approach guarantees valid inference for downstream statistical analyses, even when surrogates are arbitrarily biased and without requiring stringent assumptions, by controlling the probability of sampling documents for gold-standard labeling. Both our theoretical analysis and experimental results show that DSL provides valid statistical inference while achieving root mean squared errors comparable to existing alternatives that focus only on prediction without inferential guarantees.
citation: 'Naoki Egami, Musashi Hinck, Brandon M. Stewart, Hanying Wei. Using Imperfect Surrogates for Downstream Inference: Design-Based Supervised Learning for Social Science Applications of Large Language Models. Advances in Neural Information Processing Systems, 2023.'
doi: 10.52202/075280-3000
bibtex: |
  @inproceedings{Egami_2023, series={NeurIPS 2023}, title={Using Imperfect Surrogates for Downstream Inference: Design-based Supervised Learning for Social Science Applications of Large Language Models}, url={https://doi.org/10.52202/075280-3000}, DOI={10.52202/075280-3000}, booktitle={Advances in Neural Information Processing Systems 36}, publisher={Neural Information Processing Systems Foundation, Inc. (NeurIPS)}, author={Egami, Naoki and Hinck, Musashi and Stewart, Brandon and Wei, Hanying}, year={2023}, pages={68589–68601}, collection={NeurIPS 2023} }
links:
- name: Publisher's Version
  url: https://doi.org/10.52202/075280-3000
tags:
- "AI Annotation & Predicted Variables"
- "Causal Inference with Text"
slug: using-imperfect-surrogates-downstream-inference-design-based-supervised-learning
url: /publication/using-imperfect-surrogates-downstream-inference-design-based-supervised-learning/
---
