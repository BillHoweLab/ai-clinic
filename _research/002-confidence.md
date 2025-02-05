---
title: 'Mitigating Overconfidence in LLMs'
layout: research
persons: 'Bingbing Wen, Chenjun Xu, Bin Han, Robert Wolfe, Lucy Lu Wang, and Bill Howe'
conference: 'NeurIPS 2024 Workshop on Behavioral ML'
date: 'December 2024'
code: ''
paper: 'https://openreview.net/pdf?id=y9UdO5cmHs'
thumbnail: 'confidence-model.png'
summary: 'Introduces the Answer-Free Confidence Estimation (AFCE) method for calibrating LLM verbalized confidence assessments.'
---

Confidence estimation is a crucial area in machine learning, particularly with large language models (LLMs), which are prone to overconfidence, leading to inaccurate predictions, hallucinations, and impaired decision-making. As LLMs are increasingly integrated into real-world applications, overconfidence poses challenges for effective human-machine collaboration. We examine LLM overconfidence through the lens of human behavior, proposing a mechanism for understanding of how models exhibit overconfidence and how to mitigate its effects to improve LLM interpretability and calibration. Drawing on models of human overconfidence in cognitive and psychological research, we consider whether LLMs mirror human overconfidence patterns related to perceived task difficulty and comparisons with others. Our findings indicate that LLMs exhibit varied confidence patterns. Larger models, similar to humans, tend to overestimate their performance on challenging tasks and underestimate it on simpler ones, while small models display consistent overconfidence across all task levels. However, LLMs’ self-assessments are generally less sensitive to task difficulty than human estimates. We propose Answer-Free Confidence Estimation (AFCE), a method that reduces overconfidence by asking models for confidence scores on question sets without providing answers. This approach decouples confidence estimation from answer generation, significantly lowering overconfidence, particularly on challenging tasks. We then consider how LLMs’ self-assessment compares to their assessment of experts and laymen, providing insight into how LLMs place their own abilities, even though the actual accuracies between the two groups remains comparable. We aim to motivate psychology-grounded research for better confidence calibration in LLMs.