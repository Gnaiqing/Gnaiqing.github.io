---
title: "WeShap: Weak Supervision Source Evaluation with Shapley Values"
collection: publications
category: conferences
permalink: /publication/2025-weshap
date: 2025-09-01
venue: 'the 51st International Conference on Very Large Databases (VLDB)'
paperurl: 'https://arxiv.org/pdf/2406.11010'
---
**Evaluating the utility of weak supervision sources with Shapley values for efficient data annotation.**

Efficient data annotation stands as a significant bottleneck in training contemporary machine learning models. The Programmatic Weak Supervision (PWS) pipeline presents a solution by utilizing multiple weak supervision sources to automatically label data, thereby expediting the annotation process. Given the varied contributions of these weak supervision sources to the accuracy of PWS, it is imperative to employ a robust and efficient metric for their evaluation. This is crucial not only for understanding the behavior and performance of the PWS pipeline but also for facilitating corrective measures.

In our study, we introduce WeShap values as an evaluation metric, which quantifies the average contribution of weak supervision sources within a proxy PWS pipeline, leveraging the theoretical underpinnings of Shapley values. We demonstrate efficient computation of WeShap values using dynamic programming, achieving quadratic computational complexity relative to the number of weak supervision sources.

Our experiments demonstrate the versatility of WeShap values across various applications, including the identification of beneficial or detrimental labeling functions, refinement of the PWS pipeline, and rectification of mislabeled data. Furthermore, WeShap values aid in comprehending the behavior of the PWS pipeline and scrutinizing specific instances of mislabeled data. Although initially derived from a specific proxy PWS pipeline, we empirically demonstrate the generalizability of WeShap values to other PWS pipeline configurations.

Our findings indicate a noteworthy average improvement of 5.0 points in downstream model accuracy through the revision of the PWS pipeline compared to previous state-of-the-art methods, underscoring the efficacy of WeShap values in enhancing data quality for training machine learning models.