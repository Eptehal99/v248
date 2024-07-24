---
title: Multiple Instance Learning with Absolute Position Information
abstract: 'Most past work in multiple instance learning (MIL), which maps a group
  or bag of instances to a classification label, has focused on settings in which
  the order of instances does not contain information. In this paper, we define MIL
  with \textit{absolute} position information: tasks in which instances of importance
  remain in similar positions across bags. Such problems arise, for example, in MIL
  with medical images in which there exists a common global alignment across images
  (e.g., in chest x-rays the heart is in a similar location). We also evaluate the
  performance of existing MIL methods on a set of new benchmark tasks and two real
  data tasks with varying amounts of absolute position information. We find that,
  despite being less computationally efficient than other approaches, transformer-based
  MIL methods are more accurate at classifying tasks with absolute position information.
  Thus, we investigate the ability of positional encodings, a mechanism typically
  only used in transformers, to improve the accuracy of other MIL approaches. Applied
  to the task of identifying pathological findings in chest x-rays, when augmented
  with positional encodings, standard MIL approaches perform significantly better
  than without (AUROC of 0.799, 95% CI: [0.791, 0.806] vs. 0.782, 95% CI: [0.774,
  0.789]) and on-par with transformer-based methods (AUROC of 0.797, 95% CI: [0.790,
  0.804]) while being 10 times faster. Our results suggest that one can efficiently
  and accurately classify MIL data with absolute position information using standard
  approaches by simply including positional encodings.'
year: '2024'
volume: '248'
publisher: PMLR
series: Proceedings of Machine Learning Research
software: https://github.com/MLD3/MILwAPI
layout: inproceedings
issn: 2640-3498
id: krishnamoorthy24a
month: 0
tex_title: Multiple Instance Learning with Absolute Position Information
firstpage: 88
lastpage: 104
page: 88-104
order: 88
cycles: false
bibtex_author: Krishnamoorthy, Meera and Wiens, Jenna
author:
- given: Meera
  family: Krishnamoorthy
- given: Jenna
  family: Wiens
date: 2024-07-24
address:
container-title: Proceedings of the fifth Conference on Health, Inference, and Learning
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 7
  - 24
pdf: https://raw.githubusercontent.com/mlresearch/v248/main/assets/krishnamoorthy24a/krishnamoorthy24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
