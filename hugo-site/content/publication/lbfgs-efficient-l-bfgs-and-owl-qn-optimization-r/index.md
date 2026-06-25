---
title: 'lbfgs: Efficient L-BFGS and OWL-QN Optimization in R'
date: '2014-01-01'
authors:
- Antonio Coppola
- Brandon M. Stewart
publication_types:
- report
publication: R package vignette, 2014.
abstract: This vignette introduces the lbfgs package for R, which consists of a wrapper built around the libLBFGS optimization library written by Naoaki Okazaki. The lbfgs package implements both the Limited-memory Broyden-Fletcher-Goldfarb-Shanno (L-BFGS) and the Orthant-Wise Limited-memory Quasi-Newton (OWL-QN) optimization algorithms. The L-BFGS algorithm solves the problem of minimizing an objective, given its gradient, by iteratively computing approximations of the inverse Hessian matrix. The OWL-QN algorithm finds the optimum of an objective plus the L1 norm of the problem’s parameters. The package offers a fast and memory-efficient implementation of these optimization routines, which is particularly suited for high-dimensional problems. The lbfgs package compares favorably with other optimization packages for R in microbenchmark tests.
citation: 'Antonio Coppola and Brandon M. Stewart. lbfgs: Efficient L-BFGS and OWL-QN Optimization in R. R package vignette, 2014.'
links:
- name: Vignette
  url: /files/research/lbfgsvignette.pdf
tags:
- "software"
slug: lbfgs-efficient-l-bfgs-and-owl-qn-optimization-r
url: /publication/lbfgs-efficient-l-bfgs-and-owl-qn-optimization-r/
bibtex: |
  @manual{coppola2014lbfgs,
    title = {lbfgs: Efficient L-BFGS and OWL-QN Optimization in R},
    author = {Coppola, Antonio and Stewart, Brandon M.},
    year = {2014},
    note = {R package vignette}
  }
---
