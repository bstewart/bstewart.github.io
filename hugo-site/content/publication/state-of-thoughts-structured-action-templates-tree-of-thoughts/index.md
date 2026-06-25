---
title: 'STATe-of-Thoughts: Structured Action Templates for Tree-of-Thoughts'
date: '2026-02-01'
authors:
- Zachary Bamberger
- Till R. Saenger
- Gilad Morad
- Ofra Amir
- Brandon M. Stewart
- Amir Feder
publication_types:
- working_paper
publication: arXiv:2602.14265, 2026.
abstract: >-
  Inference-Time-Compute (ITC) methods like Best-of-N and Tree-of-Thoughts are meant to produce output candidates that are both high-quality and diverse, but their use of high-temperature sampling often fails to achieve meaningful output diversity. Moreover, existing ITC methods offer limited control over how to perform reasoning, which limits both their performance and explainability. We present STATe-of-Thoughts (STATe), an explainable ITC method that searches over high-level reasoning patterns. STATe replaces stochastic sampling with discrete and interpretable textual interventions: a controller selects actions encoding high-level reasoning choices, a generator produces reasoning steps conditioned on those choices, and an evaluator scores candidates to guide search. This structured approach yields four main advantages. First, action-guided textual interventions produce greater response diversity than temperature-based sampling. Second, when paired with reliable evaluation, STATe's diverse yet high-quality outputs surpass existing ITC methods on instruction following. Third, in a case study on argument generation, STATe's explicit action sequences capture interpretable features that are highly predictive of output quality. Fourth, estimating the association between performance and action choices allows us to identify promising yet unexplored regions of the action space and steer generation directly toward them. Together, these results establish STATe as a practical framework for generating high-quality, diverse, and interpretable text. Our framework is available at https://github.com/zbambergerNLP/dspy-reasoning.
citation: 'Zachary Bamberger, Till R. Saenger, Gilad Morad, Ofra Amir, Brandon M. Stewart, Amir Feder. STATe-of-Thoughts: Structured Action Templates for Tree-of-Thoughts. arXiv:2602.14265, 2026.'
bibtex: "@misc{bamberger2026stateofthoughtsstructuredactiontemplates,\n      title={STATe-of-Thoughts: Structured Action Templates for Tree-of-Thoughts}, \n      author={Zachary Bamberger and Till R. Saenger and Gilad Morad and Ofra Amir and Brandon M. Stewart and Amir Feder},\n      year={2026},\n      eprint={2602.14265},\n      archivePrefix={arXiv},\n      primaryClass={cs.CL},\n      url={https://arxiv.org/abs/2602.14265}, \n}\n"
image_alt: "Figure 1 workflow diagram for STATe-of-Thoughts showing action templates, output generation, and evaluation."
links:
- name: arXiv
  url: https://arxiv.org/abs/2602.14265
- name: Website
  url: https://github.com/zbambergerNLP/state-of-thoughts
tags:
- "Generative AI & LLMs"
slug: state-of-thoughts-structured-action-templates-tree-of-thoughts
url: /publication/state-of-thoughts-structured-action-templates-tree-of-thoughts/
---
