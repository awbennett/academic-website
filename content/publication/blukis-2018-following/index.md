---
title: Following High-level Navigation Instructions on a Simulated Quadcopter with Imitation Learning
date: '2018-06-28'
draft: false
publishDate: '2018-06-28T05:42:43.351259Z'
authors:
- Valts Blukis
- Nataly Brukhim
- Andrew Bennett
- Ross Knepper
- Yoav Artzi
publication_types:
- 1
abstract: '''
    We introduce a method for following high-level navigation instructions by mapping directly from images, instructions and pose estimates to continuous low-level velocity commands for real-time control. The Grounded Semantic Mapping Network (GSMN) is a fully-differentiable neural network architecture that builds an explicit semantic map in the world reference frame by incorporating a pinhole camera projection model within the network. The information stored in the map is learned from experience, while the local-to-world transformation is computed explicitly. We train the model using DAggerFM, a modified variant of DAgger that trades tabular convergence guarantees for improved training speed and memory use. We test GSMN in virtual environments on a realistic quadcopter simulator and show that incorporating an explicit mapping and grounding modules allows GSMN to outperform strong neural baselines and almost reach an expert policy performance. Finally, we analyze the learned map representations and show that using an explicit map leads to an interpretable instruction-following model.
'''
featured: false
publication: '*Robotics: Science and Systems (RSS)*'
url_pdf: http://www.roboticsproceedings.org/rss14/p66.pdf

---


