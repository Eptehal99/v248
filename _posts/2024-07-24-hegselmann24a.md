---
title: A Data-Centric Approach To Generate Faithful and High Quality Patient Summaries
  with Large Language Models
abstract: Patients often face difficulties in understanding their hospitalizations,
  while healthcare workers have limited resources to provide explanations. In this
  work, we investigate the potential of large language models to generate patient
  summaries based on doctors’ notes and study the effect of training data on the faithfulness
  and quality of the generated summaries. To this end, we release (i) a rigorous labeling
  protocol for errors in medical texts and (ii) a publicly available dataset of annotated
  hallucinations in 100 doctor-written and 100 generated summaries. We show that fine-tuning
  on hallucination-free data effectively reduces hallucinations from 2.60 to 1.55
  per summary for Llama 2, while preserving relevant information. We observe a similar
  effect on GPT-4 (0.70 to 0.40), when the few-shot examples are hallucination-free.
  We also conduct a qualitative evaluation using hallucination-free and improved training
  data. We find that common quantitative metrics do not correlate well with faithfulness
  and quality. Finally, we test GPT-4 for automatic hallucination detection, which
  clearly outperforms common baselines.
year: '2024'
volume: '248'
publisher: PMLR
series: Proceedings of Machine Learning Research
software: https://github.com/stefanhgm/patient_summaries_with_llms
layout: inproceedings
issn: 2640-3498
id: hegselmann24a
month: 0
tex_title: A Data-Centric Approach To Generate Faithful and High Quality Patient Summaries
  with Large Language Models
firstpage: 339
lastpage: 379
page: 339-379
order: 339
cycles: false
bibtex_author: Hegselmann, Stefan and Shen, Zejiang and Gierse, Florian and Agrawal,
  Monica and Sontag, David and Jiang, Xiaoyi
author:
- given: Stefan
  family: Hegselmann
- given: Zejiang
  family: Shen
- given: Florian
  family: Gierse
- given: Monica
  family: Agrawal
- given: David
  family: Sontag
- given: Xiaoyi
  family: Jiang
date: 2024-07-24
address:
container-title: Proceedings of the fifth Conference on Health, Inference, and Learning
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 7
  - 24
pdf: https://raw.githubusercontent.com/mlresearch/v248/main/assets/hegselmann24a/hegselmann24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
