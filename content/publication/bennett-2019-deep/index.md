---
title: Deep Generalized Method of Moments for Instrumental Variable Analysis
date: '2019-12-10'
draft: false 
publishDate: '2020-08-26T05:42:43.262457Z'
authors:
- Andrew Bennett
- Nathan Kallus
- Tobias Schnabel
publication_types:
- 1
abstract: '''
    Instrumental variable analysis is a powerful tool for estimating
    causal effects when randomization or full control of confounders
    is not possible. The application of standard methods such as 2SLS,
    GMM, and more recent variants are significantly impeded when the
    causal effects are complex, the instruments are high-dimensional,
    and/or the treatment is high-dimensional. In this paper,
    we propose the DeepGMM algorithm to overcome this. Our algorithm
    is based on a new variational reformulation of GMM with optimal
    inverse-covariance weighting that allows us to efficiently
    control very many moment conditions. We further develop practical
    techniques for optimization and model selection that make it
    particularly successful in practice. Our algorithm is also
    computationally tractable and can handle large-scale datasets.
    Numerical results show our algorithm matches the performance
    of the best tuned methods in standard settings and continues
    to work in high-dimensional settings where even recent methods
    break.
'''

featured: false
publication: '*Advances in Neural Information Processing Systems*'
url_pdf: https://papers.nips.cc/paper/8615-deep-generalized-method-of-moments-for-instrumental-variable-analysis.pdf
---

