---
title: "SIREN<sup>+</sup>: Robust Federated Learning with Proactive Alarming and Differential Privacy"
collection: publications
permalink: /publication/Siren+
excerpt: '**Hanxi Guo**, Hao Wang, Tao Song, Yang Hua, Ruhui Ma, Xiulang Jin, Zhengui Xue, and Haibing Guan.'
date: 2024-02-06
venue: 'IEEE Transactions on Dependable and Secure Computing'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10423198'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Federated learning (FL), an emerging machine learning paradigm that trains a global model across distributed clients without violating data privacy, has recently attracted significant attention. However, FL's distributed nature and iterative training extensively increase the attacking surface for Byzantine and inference attacks. Existing FL defense methods can hardly protect FL from both Byzantine and inference attacks due to their fundamental conflicts. The noise injected to defend against inference attacks interferes with model weights and training data, obscuring model analysis that Byzantine-robust methods utilize to detect attacks. Besides, the practicability of existing Byzantine-robust methods is limited since they heavily rely on model analysis. In this paper, we present SIREN<sup>+</sup> , a new robust FL system that defends against a wide spectrum of Byzantine attacks and inference attacks by jointly utilizing a proactive alarming mechanism and local differential privacy (LDP). The proactive alarming mechanism orchestrates clients and the FL server to collaboratively detect attacks using distributed alarms, which is free from the noise interference injected by LDP. Compared with the state-of-the-art defense methods, SIREN<sup>+</sup> can protect FL from Byzantine and inference attacks from a higher proportion of malicious clients in the system while keeping the global model performing normally. Extensive experiments with diverse settings and attacks on real-world datasets show that SIREN<sup>+</sup> outperforms existing defense methods when attacked by Byzantine and inference attacks.

[Download paper here](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10423198)
[Github Repo](https://github.com/AISIGSJTU/Siren-Plus)