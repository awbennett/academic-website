---
title: Future-Dependent Value-Based Off-Policy Evaluation in POMDPs
date: '2023-12-13'
draft: false
publishDate: '2023-12-13T05:42:43.351259Z'
authors:
- Masatoshi Uehara
- Haruka Kiyohara
- Andrew Bennett
- Victor Chernozhukov
- Nan Jiang
- Nathan Kallus
- Chengchun Shi
- Wen Sun
publication_types:
- 1
abstract: '''
    We study off-policy evaluation (OPE) for partially observable MDPs (POMDPs)
    with general function approximation. Existing methods such as sequential
    importance sampling estimators and fitted-Q evaluation suffer from the
    curse of horizon in POMDPs. To circumvent this problem, we develop a novel
    model-free OPE method by introducing future-dependent value functions that
    take future proxies as inputs. Future-dependent value functions play
    similar roles as classical value functions in fully-observable MDPs. We
    derive a new Bellman equation for future-dependent value functions as
    conditional moment equations that use history proxies as instrumental
    variables. We further propose a minimax learning method to learn
    future-dependent value functions using the new Bellman equation. We
    obtain the PAC result, which implies our OPE estimator is consistent
    as long as futures and histories contain sufficient information about
    latent states, and the Bellman completeness. Finally, we extend our
    methods to learning of dynamics and establish the connection between our
    approach and the well-known spectral learning methods in POMDPs.'''
featured: false
publication: '*International Conference on Neural Information Processing Systems (NeurIPS)*'
url_pdf: https://proceedings.neurips.cc/paper_files/paper/2023/file/3380e8116452e0efbf36f35d95e88c94-Paper-Conference.pdf

---
