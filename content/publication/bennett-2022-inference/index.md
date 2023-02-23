---
title: Provable Safe Reinforcement Learning with Binary Feedback
date: '2022-12-26'
draft: false
publishDate: '2022-12-26T05:42:43.351259Z'
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
    In a variety of applications, including nonparametric instrumental variable
    (NPIV) analysis, proximal causal inference under unmeasured confounding,
    and missing-not-at-random data with shadow variables, we are interested
    in inference on a continuous linear functional (e.g., average causal
    effects) of nuisance function (e.g., NPIV regression) defined by
    conditional moment restrictions. These nuisance functions are generally
    weakly identified, in that the conditional moment restrictions can be
    severely ill-posed as well as admit multiple solutions. This is sometimes
    resolved by imposing strong conditions that imply the function can be
    estimated at rates that make inference on the functional possible. In
    this paper, we study a novel condition for the functional to be strongly
    identified even when the nuisance function is not; that is, the functional
    is amenable to asymptotically-normal estimation at sqrt(n)-rates. The
    condition implies the existence of debiasing nuisance functions, and we
    propose penalized minimax estimators for both the primary and debiasing
    nuisance functions. The proposed nuisance estimators can accommodate
    flexible function classes, and importantly they can converge to fixed
    limits determined by the penalization regardless of the identifiability
    of the nuisances. We use the penalized nuisance estimators to form a
    debiased estimator for the functional of interest and prove its
    asymptotic normality under generic high-level conditions, which provide
    for asymptotically valid confidence intervals. We also illustrate our
    method in a novel partially linear proximal causal inference problem and
    a partially linear instrumental variable regression problem.'''
featured: false
publication: '*arXiv Preprint*'
url_pdf: https://arxiv.org/pdf/2208.08291.pdf

---
