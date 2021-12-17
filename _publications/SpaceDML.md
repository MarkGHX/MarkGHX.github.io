---
title: "SpaceDML: Enabling Distributed Machine Learning in Space Information Networks"
collection: publications
permalink: /publication/SpaceDML
excerpt: 'Space information networks (SINs) have become a rapidly growing global infrastructure service. Massive volumes of high-resolution images and videos captured by low-orbit satellites and unmanned aerial vehicles have provided a rich training data source for machine learning applications. However, SIN devices' limited communication and computation resources make it challenging to perform machine learning efficiently with a swarm of SIN devices. In this article, we propose SpaceDML, a distributed machine learning system for SIN platforms that applies dynamic model compression techniques to adapt distributed machine learning training to SINs' limited bandwidth and unstable connectivity. SpaceDML has two key algorithm:s adaptive loss-aware quantization, which compresses models without sacrificing their quality, and partial weight averaging, which selectively averages active clients' partial model updates …'
date: 2021-08-20
venue: 'IEEE Network'
paperurl: 'https://ieeexplore.ieee.org/iel7/65/9520333/09520325.pdf?casa_token=AZlLE0r2RRwAAAAA:Ekwt9YAF_VD8jwMPKfZzWCgrFOzO-4MnHGZ8sS0Zoz-AvJyOa3oVHeP2lt4-UR49VvhFxF3ojw'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Space information networks (SINs) have become a rapidly growing global infrastructure service. Massive volumes of high-resolution images and videos captured by low-orbit satellites and unmanned aerial vehicles have provided a rich training data source for machine learning applications. However, SIN devices' limited communication and computation resources make it challenging to perform machine learning efficiently with a swarm of SIN devices. In this article, we propose SpaceDML, a distributed machine learning system for SIN platforms that applies dynamic model compression techniques to adapt distributed machine learning training to SINs' limited bandwidth and unstable connectivity. SpaceDML has two key algorithm:s adaptive loss-aware quantization, which compresses models without sacrificing their quality, and partial weight averaging, which selectively averages active clients' partial model updates. These algorithms jointly improve communication efficiency and enhance the scalability of distributed machine learning with SIN devices. We evaluate SpaceDML by training a LeNet-S model on the MNIST dataset. The experimental results show that SpaceDML can increase model accuracy by 2-3 percent and reduce communication bandwidth consumption by up to 60 percent compared to the baseline algorithm.

[Download paper here](https://ieeexplore.ieee.org/iel7/65/9520333/09520325.pdf?casa_token=AZlLE0r2RRwAAAAA:Ekwt9YAF_VD8jwMPKfZzWCgrFOzO-4MnHGZ8sS0Zoz-AvJyOa3oVHeP2lt4-UR49VvhFxF3ojw)

Recommended citation:
'''
@article{guo2021spacedml,
  title={SpaceDML: Enabling Distributed Machine Learning in Space Information Networks},
  author={Guo, Hanxi and Yang, Qing and Wang, Hao and Hua, Yang and Song, Tao and Ma, Ruhui and Guan, Haibing},
  journal={IEEE Network},
  volume={35},
  number={4},
  pages={82--87},
  year={2021},
  publisher={IEEE}
}
'''