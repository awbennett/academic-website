---
title: The Variational Method of Moments
date: '2020-28-05'
draft: false
publishDate: '2020-28-05T05:42:43.351259Z'
authors:
- Andrew Bennett
- Nathan Kallus
publication_types:
- 3
abstract: '''
    The conditional moment problem is a powerful formulation for describing
    structural causal parameters in terms of observables, a prominent example
    being instrumental variable regression. A standard approach is to reduce
    the problem to a finite set of marginal moment conditions and apply the
    optimally weighted generalized method of moments (OWGMM), but this requires
    we know a finite set of identifying moments, can still be inefficient even
    if identifying, or can be theoretically efficient but practically unwieldy
    if we use a growing sieve of moment conditions. Motivated by a variational
    minimax reformulation of OWGMM, we define a very general class of
    estimators for the conditional moment problem, which we term the
    variational method of moments (VMM) and which naturally enables controlling
    infinitely-many moments. We provide a detailed theoretical analysis of
    multiple VMM estimators, including ones based on kernel methods and neural
    nets, and provide appropriate conditions under which these estimators
    are consistent, asymptotically normal, and semiparametrically efficient
    in the full conditional moment model. This is in contrast to other
    recently proposed methods for solving conditional moment problems based
    on adversarial machine learning, which do not incorporate optimal
    weighting, do not establish asymptotic normality, and are not
    semiparametrically efficient. In addition, we provide corresponding
    inference algorithms based on the same kind of variational reformulations,
    both for kernel- and neural net-based varieties. Finally, we demonstrate
    the strong performance of our proposed estimation and inference algorithms
    in a detailed series of synthetic experiments.'''
featured: false
publication: '*arXiv preprint arXiv:2012.09422*'
url_pdf: https://arxiv.org/pdf/2012.09422.pdf

---
