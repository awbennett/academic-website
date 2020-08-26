---
title: Policy Evaluation with Latent Confounders via Optimal Balance
date: '2019-12-10'
draft: false
publishDate: '2020-08-26T05:42:43.262457Z'
authors:
- Andrew Bennett
- Nathan Kallus
publication_types:
- 1
abstract: '''
    Evaluating novel contextual bandit policies using logged data is
    crucial in applications where exploration is costly, such as
    medicine. But it usually relies on the assumption of no
    unobserved confounders, which is bound to fail in practice.
    We study the question of policy evaluation when we instead have
    proxies for the latent confounders and develop an importance
    weighting method that avoids fitting a latent outcome regression
    model. Surprisingly, we show that there exist no single set
    of weights that give unbiased evaluation regardless of
    outcome model, unlike the case with no unobserved confounders
    where density ratios are sufficient. Instead, we propose an
    adversarial objective and weights that minimize it, ensuring
    sufficient balance in the latent confounders regardless of
    outcome model. We develop theory characterizing the consistency
    of our method and tractable algorithms for it. Empirical results
    validate the power of our method when confounders are latent.
'''
featured: false
publication: '*Advances in Neural Information Processing Systems*'
url_pdf: https://papers.nips.cc/paper/8729-policy-evaluation-with-latent-confounders-via-optimal-balance.pdf
---

