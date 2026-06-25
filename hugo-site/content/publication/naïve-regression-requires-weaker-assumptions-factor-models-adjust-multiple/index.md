---
title: Naive Regression Requires Weaker Assumptions than Factor Models to Adjust for Multiple Cause Confounding
date: '2023-01-01'
authors:
- Justin Grimmer
- Dean Knox
- Brandon M. Stewart
publication_types:
- journal_article
publication: 'Journal of Machine Learning Research 24(182): 1-70, 2023.'
abstract: 'The empirical practice of using factor models to adjust for shared, unobserved confounders, Z, in observational settings with multiple treatments, A, is widespread in fields including genetics, networks, medicine, and politics. Wang and Blei (2019, WB) formalizes these procedures and develops the "deconfounder," a causal inference method using factor models of A to estimate "substitute confounders," Ẑ , then estimating treatment effects by regressing the outcome, Y, on part of A while adjusting for Ẑ . WB claim the deconfounder is unbiased when there are no single-cause confounders and Ẑ is "pinpointed." We clarify pinpointing requires each confounder to affect infinitely many treatments. We prove under these assumptions, a naïve semiparametric regression of Y on A is asymptotically unbiased. Deconfounder variants nesting this regression are therefore also asymptotically unbiased, but variants using Ẑ and subsets of causes require further untestable assumptions. We replicate
  every deconfounder analysis with available data and find it fails to consistently outperform naïve regression. In practice, the deconfounder produces implausible estimates in WB''s case study to movie earnings: estimates suggest comic author Stan Lee''s cameo appearances causally contributed $15.5 billion, most of Marvel movie revenue. We conclude neither approach is a viable substitute for careful research design in real-world applications.'
citation: 'Justin Grimmer, Dean Knox, Brandon M. Stewart. Naive Regression Requires Weaker Assumptions than Factor Models to Adjust for Multiple Cause Confounding. Journal of Machine Learning Research 24(182): 1-70, 2023.'
bibtex: |
  @article{grimmer2023naive,
    title = {Naive Regression Requires Weaker Assumptions than Factor Models to Adjust for Multiple Cause Confounding},
    author = {Grimmer, Justin and Knox, Dean and Stewart, Brandon M.},
    journal = {Journal of Machine Learning Research},
    volume = {24},
    number = {182},
    pages = {1--70},
    year = {2023}
  }
tags:
- "Research Design & Valid Inference"
slug: naïve-regression-requires-weaker-assumptions-factor-models-adjust-multiple
url: /publication/naïve-regression-requires-weaker-assumptions-factor-models-adjust-multiple/
---

