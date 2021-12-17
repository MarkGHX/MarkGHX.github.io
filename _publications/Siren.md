---
title: "Siren: Byzantine-robust Federated Learning via Proactive Alarming"
collection: publications
permalink: /publication/Siren
excerpt: 'With the popularity of machine learning on many applications, data privacy has become a severe issue when machine learning is applied in the real world. Federated learning (FL), an emerging paradigm in machine learning, aims to train a centralized model while distributing training data among a large number of clients in order to avoid data privacy leaking, which has attracted great attention recently. However, the distributed training scheme in FL is susceptible to different kinds of attacks. Existing defense systems mainly utilize model weight analysis to identify malicious clients with many limitations. For example, some defense systems must know the exact number of malicious clients beforehand, which can be easily bypassed by well-designed attack methods and become impractical for real-world scenarios...'
date: 2021-11-01
venue: 'ACM Symposium on Cloud Computing'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3472883.3486990'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
With the popularity of machine learning on many applications, data privacy has become a severe issue when machine learning is applied in the real world. Federated learning (FL), an emerging paradigm in machine learning, aims to train a centralized model while distributing training data among a large number of clients in order to avoid data privacy leaking, which has attracted great attention recently. However, the distributed training scheme in FL is susceptible to different kinds of attacks. Existing defense systems mainly utilize model weight analysis to identify malicious clients with many limitations. For example, some defense systems must know the exact number of malicious clients beforehand, which can be easily bypassed by well-designed attack methods and become impractical for real-world scenarios.

This paper presents Siren, a Byzantine-robust federated learning system via a proactive alarming mechanism. Compared with current Byzantine-robust aggregation rules, Siren can defend against attacks from a higher proportion of malicious clients in the system while keeping the global model performing normally. Extensive experiments against different attack methods are conducted under diverse settings on both independent and identically distributed (IID) and non-IID data. The experimental results illustrate the effectiveness of Siren comparing with several state-of-the-art defense methods.

[Download paper here](https://dl.acm.org/doi/pdf/10.1145/3472883.3486990?casa_token=nXd8gc3VjSMAAAAA:mEcPNuaLTiiLponIsuK7P3JCDxKgt1cb_tZlAati74SWcmyvJGZmvVzBZvVchAk6g-j_XSeFn9KxxQ)

Recommended citation:
'''
@inproceedings{guo2021siren,
  title={Siren: Byzantine-robust Federated Learning via Proactive Alarming},
  author={Guo, Hanxi and Wang, Hao and Song, Tao and Hua, Yang and Lv, Zhangcheng and Jin, Xiulang and Xue, Zhengui and Ma, Ruhui and Guan, Haibing},
  booktitle={Proceedings of the ACM Symposium on Cloud Computing},
  pages={47--60},
  year={2021}
}
'''