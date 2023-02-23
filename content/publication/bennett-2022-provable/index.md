---
title: Provable Safe Reinforcement Learning with Binary Feedback
date: '2022-10-26'
draft: false
publishDate: '2022-10-26T05:42:43.351259Z'
authors:
- Andrew Bennett
- Dipendra Misra
- Nathan Kallus
publication_types:
- 3
abstract: '''
    Safety is a crucial necessity in many applications of reinforcement
    learning (RL), whether robotic, automotive, or medical. Many existing
    approaches to safe RL rely on receiving numeric safety feedback, but in
    many cases this feedback can only take binary values; that is, whether
    an action in a given state is safe or unsafe. This is particularly true
    when feedback comes from human experts. We therefore consider the problem
    of provable safe RL when given access to an offline oracle providing
    binary feedback on the safety of state, action pairs. We provide a novel
    meta algorithm, SABRE, which can be applied to any MDP setting given
    access to a blackbox PAC RL algorithm for that setting. SABRE applies
    concepts from active learning to reinforcement learning to provably
    control the number of queries to the safety oracle. SABRE works by
    iteratively exploring the state space to find regions where the agent is
    currently uncertain about safety. Our main theoretical results shows that,
    under appropriate technical assumptions, SABRE never takes unsafe actions
    during training, and is guaranteed to return a near-optimal safe policy
    with high probability. We provide a discussion of how our meta-algorithm
    may be applied to various settings studied in both theoretical and
    empirical frameworks.'''
featured: false
publication: '*accepted at AISTATS*'
url_pdf: https://arxiv.org/pdf/2210.14492.pdf

---
