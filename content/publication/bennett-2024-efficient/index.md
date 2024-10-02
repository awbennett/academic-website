---
title: Efficient and Sharp Off-Policy Evaluation in Robust Markov Decision Processes
date: '2024-09-25'
draft: false
publishDate: '2024-09-25T05:42:43.351259Z'
authors:
- Andrew Bennett
- Nathan Kallus
- Miruna Oprescu
- Wen Sun
- Kaiwen Wang
publication_types:
- 3
abstract: '''
    We study evaluating a policy under best- and worst-case perturbations to a
    Markov decision process (MDP), given transition observations from the
    original MDP, whether under the same or different policy. This is an
    important problem when there is the possibility of a shift between
    historical and future environments, due to e.g. unmeasured confounding,
    distributional shift, or an adversarial environment. We propose a
    perturbation model that can modify transition kernel densities up to a
    given multiplicative factor or its reciprocal, which extends the classic
    marginal sensitivity model (MSM) for single time step decision making to
    infinite-horizon RL. We characterize the sharp bounds on policy value
    under this model, that is, the tightest possible bounds given by the
    transition observations from the original MDP, and we study the estimation
    of these bounds from such transition observations. We develop an estimator
    with several appealing guarantees: it is semiparametrically efficient, and
    remains so even when certain necessary nuisance functions such as
    worst-case Q-functions are estimated at slow nonparametric rates. It is
    also asymptotically normal, enabling easy statistical inference using Wald
    confidence intervals. In addition, when certain nuisances are estimated
    inconsistently we still estimate a valid, albeit possibly not sharp bounds
    on the policy value. We validate these properties in numeric simulations.
    The combination of accounting for environment shifts from train to test
    (robustness), being insensitive to nuisance-function estimation
    (orthogonality), and accounting for having only finite samples to learn
    from (inference) together leads to credible and reliable policy evaluation.'''
featured: false
publication: '*accepted at NeurIPS*'
url_pdf: https://arxiv.org/pdf/2404.00099

---
