---
title: The Variational Method of Moments
date: '2023-04-27'
draft: false
publishDate: '2023-04-27T05:42:43.351259Z'
authors:
- Andrew Bennett
- Nathan Kallus
publication_types:
- 2
abstract: '''
    The conditional moment problem is a powerful formulation for describing
    structural causal parameters in terms of observables, a prominent example
    being instrumental variable regression. A standard approach reduces the
    problem to a finite set of marginal moment conditions and applies the
    optimally weighted generalized method of moments (OWGMM), but this
    requires we know a finite set of identifying moments, can still be
    inefficient even if identifying, or can be theoretically efficient but
    practically unwieldy if we use a growing sieve of moment conditions.
    Motivated by a variational minimax reformulation of OWGMM, we define a
    very general class of estimators for the conditional moment problem, which
    we term the variational method of moments (VMM) and which naturally enables
    controlling infinitely-many moments. We provide a detailed theoretical
    analysis of multiple VMM estimators, including ones based on kernel
    methods and neural nets, and provide conditions under which these are
    consistent, asymptotically normal, and semiparametrically efficient in
    the full conditional moment model. We additionally provide algorithms
    for valid statistical inference based on the same kind of variational
    reformulations, both for kernel- and neural-net-based varieties. Finally,
    we demonstrate the strong performance of our proposed estimation and
    inference algorithms in a detailed series of synthetic experiments.'''
featured: false
publication: '*Journal of the Royal Statistical Society Series B: Statistical Methodology (JRSS:B)*'
url_pdf: https://academic.oup.com/jrsssb/article-pdf/85/3/810/50859763/qkad025.pdf
---
