---
title: "Towards Scalable Automatic Modulation Classification via Meta-Learning"
collection: publications
category: International Conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper presents a scalable automatic modulation classification (AMC) scheme based on meta-learning and few-shot learning, enabling flexible recognition of unseen modulations with minimal data.'
date: 2023-10-30
venue: 'MILCOM 2023-2023 IEEE Military Communications Conference (MILCOM)'
paperurl: '../files/publications/International Conferences/Towards_Scalable_Automatic_Modulation_Classification_via_Meta-Learning.pdf'
author: 'Jungik Jang, <b>Jisung Pyo</b>, Young-Il Yoon, Sang Yong Seo, Eun Jae Lee, Gyeong Hun Jung, Jaehyuk Choi'
---

Driven by recent technological breakthroughs in deep learning (DL), many recent automatic modulation classification (AMC) methods utilize deep networks to classify the type of modulation in the incoming signal at the receiver. However, existing DL-based approaches suffer from limited scalability, especially for unseen modulations or input signals from new environments not used in training the DL model, thus not ready for real-world systems such as software defined radio devices. In this paper, we introduce a scalable AMC scheme that provides flexibility for new modulations and adaptability to input signals with diverse configurations. We propose a meta-learning framework based on few-shot learning (FSL) to acquire general knowledge and a learning method for AMC tasks. This approach allows the model to recognize new unseen modulations by learning with only a very small number of samples, without requiring the entire model to be retrained. Additionally, we enhance the scalability of the classifier by leveraging a transformer-based encoder, enabling efficient processing of input signals with varying configurations. Extensive evaluations demonstrate that the proposed AMC method outperforms existing techniques across all signal-to-noise ratios (SNRs) on RadioML2018.01A dataset.
