---
title: "DataSculpt: Cost-Efficient Label Function Design via Prompting Large Language Models"
collection: publications
category: conferences
permalink: /publication/2025-datasculpt
date: 2025-03-28
venue: 'EDBT 2025'
paperurl: 'https://openproceedings.org/2025/conf/edbt/paper-73.pdf'
---
Programmatic weak supervision methodologies expedite the labeling of extensive datasets using label functions (LFs) that encapsulate heuristic data sources. Nonetheless, the creation of precise
LFs necessitates domain expertise and substantial endeavors. Recent advances in large language models (LLMs) have exhibited
substantial potential across diverse tasks, including synthesizing
LFs automatically. However, previous works either fall short of
creating accurate LFs due to a lack of specificity or require a
substantial monetary budget for exhaustive querying.

In this research, we propose a novel framework, DataSculpt,
that harnesses LLMs for automated LF generation. DataSculpt
leverages few-shot learning in an iterative PWS framework, creating a massive and diverse LF set with a single prompt template.
We evaluated DataSculpt on six real-world datasets. Our results
show that DataSculpt can generate accurate LFs and significantly
reduce costs. For instance, using GPT-3.5, DataSculpt achieved
downstream model accuracy comparable to exhaustive querying
methods at only a fraction of the cost, with total expenses around
$0.06 compared to over $250 for exhaustive querying. DataSculpt
demonstrates that efficient LF generation with high accuracy
is achievable, making it a practical solution for large-scale data
labeling.
