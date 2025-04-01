---
title: "Meta-transformer: A meta-learning framework for scalable automatic modulation classification"
collection: publications
category: International Journals
permalink: /publication/2024-01-11-Meta-transformer:%20A%20meta-learning%20framework%20for%20scalable%20automatic%20modulation%20classification
date: 2024-01-11
excerpt: 'This paper proposes Meta-Transformer, a meta-learning-based AMC framework using few-shot learning and transformer-based encoders to achieve high performance and scalability with unseen modulations.'
venue: 'IEEE Access'
IF : '(IF=3.4 / Q2)'
paperurl: '../files/publications/International Journals/Meta-Transformer_A_Meta-Learning_Framework_for_Scalable_Automatic_Modulation_Classification.pdf'
author: 'Jungik Jang, <b>Jisung Pyo</b>, Young-Il Yoon, Jaehyuk Choi'
---

Recent advances in deep learning (DL) have led many contemporary automatic modulation classification (AMC) techniques to use deep networks in classifying the modulation type of incoming signals at the receiver. However, current DL-based methods face scalability challenges, particularly when encountering unseen modulations or input signals from environments not present during model training, making them less suitable for real-world applications like software-defined radio devices. In this paper, we introduce a scalable AMC scheme that provides flexibility for new modulations and adaptability to input signals with diverse configurations. We propose the Meta-Transformer, a meta-learning framework based on few-shot learning (FSL) to acquire general knowledge and a learning method for AMC tasks. This approach empowers the model to identify new unseen modulations using only a very small number of samples, eliminating the need for complete model retraining. Furthermore, we enhance the scalability of the classifier by leveraging main-sub transformer-based encoders, enabling efficient processing of input signals with diverse setups. Extensive evaluations demonstrate that the proposed AMC method outperforms existing techniques across all signal-to-noise ratios (SNRs) on RadioML2018.01A.