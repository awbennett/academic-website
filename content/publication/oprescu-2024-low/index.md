---
title: Low-rank MDPs with Continuous Action Spaces
date: '2024-05-03'
draft: false
publishDate: '2024-05-03T05:42:43.351259Z'
authors:
- Miruna Oprescu
- Andrew Bennett
- Nathan Kallus
publication_types:
- 1
abstract: '''
    Low-Rank Markov Decision Processes (MDPs) have recently emerged as a
    promising framework within the domain of reinforcement learning (RL), as
    they allow for provably approximately correct (PAC) learning guarantees
    while also incorporating ML algorithms for representation learning.
    However, current methods for low-rank MDPs are limited in that they only
    consider finite action spaces, and give vacuous bounds as
    action space size increases to infinity, which greatly limits their
    applicability. In this work, we study the
    problem of extending such methods to settings with continuous
    actions, and explore multiple concrete approaches for performing this
    extension. As a case study, we consider the seminal FLAMBE algorithm
    (Agarwal et al., 2020), which is a reward-agnostic method for PAC RL with
    low-rank MDPs. We show that, without any modifications to the algorithm,
    we obtain a similar PAC bound when actions are allowed to be continuous.
    Specifically, when the model for transition functions satisfies a Hölder
    smoothness condition w.r.t. actions, and either the policy class has a
    uniformly bounded minimum density or the reward function is also Hölder
    smooth, we obtain a polynomial PAC bound that depends on the order of
    smoothness.'''
featured: false
publication: '*International Conference on Artificial Intelligence and Statistics (AISTATS)*'
url_pdf: https://proceedings.mlr.press/v206/bennett23a/bennett23a.pdf

---
