---
title: "Transfer learning for radioactive particle tracking"
collection: publications
permalink: /publication/
excerpt: 'keywords: transfer learning, domain adaptation, meta-learning, few-shot learning'
date: 2022-02-02
venue: 'Chemical Engineering Science'
paperurl: 
---
Radioactive particle tracking (RPT) is a non-invasive technique used to monitor opaque multiphase flow systems. Achieving highly accurate particle tracing is challenging and time-consuming because of the need to build a new RPT model from calibration data each time the experimental conditions change. This paper aims to examine if RPT calibration data under previous conditions can be leveraged with the help of transfer learning (TL) when creating an RPT model for a new condition.  
The results show that when it is impractical to collect a lot of calibration data, TL is often superior to training an RPT model only on new data. Moreover, when new calibration data collection is not feasible, an RPT model trained on historical data can be very accurate if sufficiently similar to the historical conditions.

Under the scenario of distinct data distribution between source and target data, we investigated the applicability of meta-learning techniques (MAML, Reptile, Meta-SGD), it is shown the results are comparable with simply fine-tuning a pretrained FNN model. 

<a href="https://github.com/sai-shi/sai-shi.github.io/blob/master/files/sai_shi_CV.pdf" target="_blank">Download paper.</a>

Recommended citation: Guilherme Lindner, Sai Shi, Slobodan Vučetić, Sanja Mišković. (2022). "Transfer learning for radioactive particle tracking" <i>Chemical Engineering Science</i>. Volume 248, Part B, 117190, ISSN 0009-2509.

---

