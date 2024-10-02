---
title: 'VQ-TR: Vector Quantized Attention for Time Series Forecasting'
date: '2024-05-08'
draft: false
publishDate: '2024-05-08T05:42:43.351259Z'
authors:
- Kashif Rasul
- Andrew Bennett
- Pablo Vicente
- Umang Gupta
- Hena Ghonia
- Anderson Schneider
- Yuriy Nevmyvaka
publication_types:
- 1
abstract: '''
    Probabilistic time series forecasting is a challenging problem due to the
    long sequences involved, the large number of samples needed for accurate
    probabilistic inference, and the need for real-time inference in many
    applications. These challenges necessitate methods that are not only
    accurate but computationally efficient. Unfortunately, most current
    state-of-the-art methods for time series forecasting are based on
    Transformers, which scale poorly due to quadratic complexity in sequence
    length, and are therefore needlessly computationally inefficient.
    Moreover, with a few exceptions, these methods have only been evaluated for
    non-probabilistic point estimation. In this work, we address these two
    shortcomings. For the first, we introduce VQ-TR, which maps large sequences
    to a discrete set of latent representations as part of the Attention
    module. This not only allows us to attend over larger context windows with
    linear complexity in sequence length but also allows for effective
    regularization to avoid overfitting. For the second, we provide what is
    to the best of our knowledge the first systematic comparison of modern
    Transformer-based time series forecasting methods for probabilistic
    forecasting. In this comparison, we find that VQ-TR performs better or
    comparably to all other methods while being computationally
    efficient.'''
featured: false
publication: '*International Conference on Learning Representations (ICLR)*'
url_pdf: https://openreview.net/pdf?id=IxpTsFS7mh

---
