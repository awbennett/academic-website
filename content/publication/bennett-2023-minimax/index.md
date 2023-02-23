---
title: Provable Safe Reinforcement Learning with Binary Feedback
date: '2023-02-10'
draft: false
publishDate: '2023-02-10T05:42:43.351259Z'
authors:
- Andrew Bennett
- Nathan Kallus
- Xiaojie Mao
- Whitney Newey
- Vasilis Syrgkanis
- Masatoshi Uehara
publication_types:
- 3
abstract: '''
    In this paper, we study nonparametric estimation of instrumental variable
    (IV) regressions. Recently, many flexible machine learning methods have
    been developed for instrumental variable estimation. However, these
    methods have at least one of the following limitations: (1) restricting
    the IV regression to be uniquely identified; (2) only obtaining
    estimation error rates in terms of pseudometrics (e.g. projected
    norm) rather than valid metrics (e.g.  norm); or (3) imposing
    the so-called closedness condition that requires a certain conditional
    expectation operator to be sufficiently smooth. In this paper, we present
    the first method and analysis that can avoid all three limitations,
    while still permitting general function approximation. Specifically, we
    propose a new penalized minimax estimator that can converge to a fixed
    IV solution even when there are multiple solutions, and we derive a
    strong error rate for our estimator under lax conditions. Notably, this
    guarantee only needs a widely-used source condition and realizability
    assumptions, but not the so-called closedness condition. We argue that
    the source condition and the closedness condition are inherently
    conflicting, so relaxing the latter significantly improves upon the
    existing literature that requires both conditions. Our estimator can
    achieve this improvement because it builds on a novel formulation of the
    IV estimation problem as a constrained optimization problem.'''
featured: false
publication: '*arXiv Preprint*'
url_pdf: https://arxiv.org/pdf/2302.05404.pdf

---
