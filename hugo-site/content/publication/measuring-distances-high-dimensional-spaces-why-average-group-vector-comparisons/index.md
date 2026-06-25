---
title: 'Measuring Distances in High-Dimensional Spaces: Why Average Group Vector Comparisons Exhibit Bias, and What to Do About It'
date: '2025-01-01'
authors:
- Breanna Green
- William Hobbs
- Sofia Avila
- Pedro L. Rodriguez
- Arthur Spirling
- Brandon M. Stewart
publication_types:
- journal_article
publication: 'Political Analysis 33(3): 266-273, 2025.'
abstract: >-
  Analysts often seek to compare representations in high-dimensional space, e.g., embedding vectors of the same word across groups. We show that the distance measures calculated in such cases can exhibit considerable statistical bias, that stems from uncertainty in the estimation of the elements of those vectors. This problem applies to Euclidean distance, cosine similarity, and other similar measures. After illustrating the severity of this problem for text-as-data applications, we provide and validate a bias correction for the squared Euclidean distance. This same correction also substantially reduces bias in ordinary Euclidean distance and cosine similarity estimates, but corrections for these measures are not quite unbiased and are (non-intuitively) bimodal when distances are close to zero. The estimators require obtaining the variance of the latent positions. We (will) implement the estimator in free software, and we offer recommendations for related work.
citation: 'Breanna Green, William Hobbs, Sofia Avila, Pedro L. Rodriguez, Arthur Spirling, Brandon M. Stewart. Measuring Distances in High-Dimensional Spaces: Why Average Group Vector Comparisons Exhibit Bias, and What to Do About It. Political Analysis 33(3): 266-273, 2025.'
doi: 10.1017/pan.2024.22
bibtex: |
  @article{Green_2025, title={Measuring Distances in High Dimensional Spaces: Why Average Group Vector Comparisons Exhibit Bias, And What to Do about it}, volume={33}, ISSN={1476-4989}, url={https://doi.org/10.1017/pan.2024.22}, DOI={10.1017/pan.2024.22}, number={3}, journal={Political Analysis}, publisher={Cambridge University Press (CUP)}, author={Green, Breanna and Hobbs, William and Avila, Sofia and Rodriguez, Pedro L. and Spirling, Arthur and Stewart, Brandon M.}, year={2025}, month=Jan, pages={266–273} }
image_alt: "Figure 2 from Measuring Distances in High-Dimensional Spaces showing simulation results for corrected and uncorrected norm squared estimates across sample sizes, true values, and group imbalances."
links:
- name: Publisher's Version
  url: https://doi.org/10.1017/pan.2024.22
- name: Software
  url: https://cran.r-project.org/web/packages/conText/index.html
tags:
- "Embeddings & Semantic Representation"
- "Research Design & Valid Inference"
slug: measuring-distances-high-dimensional-spaces-why-average-group-vector-comparisons
url: /publication/measuring-distances-high-dimensional-spaces-why-average-group-vector-comparisons/
---
