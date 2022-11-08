---
title: Unsupervised All-words Sense Distribution Learning
date: '2016-06-01'
draft: false
publishDate: '2016-06-01T05:42:43.351259Z'
authors:
- Andrew Bennett
publication_types:
- 7
abstract: '''
    There has recently been significant interest in unsupervised methods for learning word sense distributions, or most frequent sense information, in particular for applications where sense distinctions are needed. In addition to their direct application to word sense disambiguation (WSD), particularly where domain adaptation is required,these methods have successfully been applied to diverse problems such as novel sense detection or lexical simplification. Furthermore, they could be used to supplement or replace existing sources of sense frequencies, such as SemCor, which have many significant flaws. However, a major gap in the past work on sense distribution learning is that it has never been optimised for large-scale application to the entire vocabularies of a languages, as would be required to replace sense frequency resources such as SemCor.
    
    In this thesis, we develop an unsupervised method for all-words sense distribution learning, which is suitable for language-wide application. We first optimise and extend HDP-WSI, an existing state-of-the-art sense distribution learning method based on HDP topic modelling. This is mostly achieved by replacing HDP with the more efficient HCA topic modelling algorithm in order to create HCA-WSI, which is over an order of magnitude faster than HDP-WSIand more robust. We then apply HCA-WSI across the vocabularies of several languages to create LexSemTM, which is a multilingual sense frequency resource of unprecedented size. Of note, LexSemTM contains sense frequencies for approximately 88% of polysemous lemmas in PrincetonWordNet, compared to only 39% forSemCor, and the quality of data in each is shown to be roughly equivalent. Finally, we extend our sense distribution learning methodology to multiword expressions (MWEs), which to the best of our knowledge is a novel task (as is applying any kind of general-purpose WSD methods to MWEs). We demonstrate that sense distribution learning for MWEs is comparable to that for simplex lemmas in all important respects, and we expand LexSemTM with MWE sense frequency data.
'''
featured: false
publication: '*Masters Thesis*'
url_pdf: https://rest.neptune-prod.its.unimelb.edu.au/server/api/core/bitstreams/4b9c0a97-d35c-5b24-af7c-1e7598b546d6/content

---
