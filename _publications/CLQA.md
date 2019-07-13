---
title: "Cross-Lingual Transfer Learning for Question Answering"
collection: publications
permalink: /publication/CLQA
excerpt: 
date: 2019-06-03
%venue: 'North American Chapter of the Association for Computational
Linguistics(ACL) [Under Review]'
paperurl: 
---
**Chia-Hsuan Lee**, Hung-Yi Lee [[PDF]]()

## Abstract
Deep learning based question answering (QA) on English documents has achieved success because there is a large amount of English training examples.However, for most languages, training examples for high-quality QA models are not available. In this paper, we explore the problem of cross-lingual transfer learning for QA, where a source language (English) task with plentiful annotations is utilized to improve the performance of a QA model on a target language (Chinese) task with limited available annotations. We examine two different approaches. A machine translation (MT) based approach translates the source language into the target language, or vice versa. Although the MT-based approach brings improvement, it assumes the availability of a sentence-level translation system. A GAN-based approach incorporates a language discriminator to learn language-universal feature representations, and consequentially transfer knowledge from the source language. The GAN-based approach rivals the performance of the MT-based approach with fewer linguistic resources and achieves the state of the art on a Chinese question-answering dataset, outperforming the previous best model by over 30% (F1 score).
