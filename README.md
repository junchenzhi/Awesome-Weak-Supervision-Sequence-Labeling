# Awesome-Weak-Supervision-Sequence-Labeling (Awesome-WSSL)


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>


A curated list of awesome Weak-Supervision-Sequence-Labeling (WSSL) papers, methods & resources.  
Inspired by [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning), [awesome-weak-supervision](https://github.com/JieyuZ2/Awesome-Weak-Supervision), 
[awesome-semi-supervised-learning](https://github.com/yassouali/awesome-semi-supervised-learning/tree/master).

- Note that: Please help contribute this list by contacting [me](zhijunchen@buaa.edu.cn) or add [pull request](https://github.com/junchenzhi/Awesome-Weak-Supervision-Sequence-Labeling/pulls).
- Note that: 
We aim to concentrate solely on the resources within this repository that exhibit the highest relevance to Weak-Supervision-Sequence-Labeling (WSSL).


---

- [Contents](#Awesome-Weak-Supervision-Sequence-Labeling)
  - 1 [Surveys and Benchmarks](#1-surveys-and-benchmarks)
    - 1.1 [Surveys](#11-surveys)
    - 1.2 [Benchmarks](#12-benchmarks)
  - 2 [Papers](#2-papers)  
    - 2.1 [Schematic of Categorization](#21-schematic-of-categorization)
    - 2.2 [List of Papers](#22-list-of-papers)
      - 2.2.A [Probabilistic Graphical Model](#22a-probabilistic-graphical-model)
      - 2.2.B [Deep Learning Model](#22b-deep-learning-model)
      - 2.2.C [Neural Graphical Model](#22c-neural-graphical-model)
  - 3 [Personal Recommendation](#3--personal-recommendation)
  - 4 [Other Resources](#4-other-resources)


---


# 1. Surveys and Benchmarks
## 1.1 Surveys
| Year |  Venue  |                                                                               Title                                                                               |                Implementation                 | 
|:----:|:-------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------:|
| 2019 |   N/A   |              [Sequence Labeling with Multiple Noisy Annotators](http://ink-ron.usc.edu/xiangren/ml4know19spring/public/surveys/Ouyu_Lan_Survey.pdf)               |                       -                       |
| 2021 | NeurIPS |                                    [WRENCH: A Comprehensive Benchmark for Weak Supervision](https://arxiv.org/abs/2109.11377)                                     | [Official](https://github.com/JieyuZ2/wrench) |
| 2022 |  ArXiv  |                                                           [A Survey on Programmatic Weak Supervision](https://arxiv.org/abs/2202.05433)                                                           |                       -                       |


## 1.2 Benchmarks
| Year |  Venue  |                                                                                                Title                                                                                                |                         Implementation                          | 
|:----:|:-------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------:|
| 2021 | NeurIPS |                                                     [WRENCH: A Comprehensive Benchmark for Weak Supervision](https://arxiv.org/abs/2109.11377)                                                      |          [Official](https://github.com/JieyuZ2/wrench)          |
| 2022 |  NAACL  |                                     [WALNUT: A Benchmark on Semi-weakly Supervised Learning for Natural Language Understanding](https://arxiv.org/abs/2108.12603)                                   |          [Official](https://github.com/microsoft/WALNUT)        |


# 2. Papers

## 2.1 Schematic of Categorization
- TBD. Please stay tuned.

## 2.2 List of Papers

### 2.2.A Probabilistic Graphical Model


| Year | Venue |                                                                                                                                                                                          Title                                                                                                                                                                                          |                                         Implementation                                         | 
|:----:|:-----:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|
| 2012 | AAAI  |                                                                                                                               [Sembler: Ensembling Crowd Sequential Labeling for Improved Quality](https://ojs.aaai.org/index.php/AAAI/article/view/8351)                                                                                                                               |                                               -                                                |
| 2014 |  MLJ  |                                                                                                                            [Sequence labeling with multiple annotators](https://fprodrigues.com/publications/sequence-labeling-with-multiple-annotators-2/)                                                                                                                             | [Official](https://fprodrigues.com/publications/sequence-labeling-with-multiple-annotators-2/) |
| 2017 |  ACL  |                                                                                                                                         [Aggregating and predicting sequence labels from crowd annotations](https://aclanthology.org/P17-1028/)                                                                                                                                         |                     [Official](https://github.com/thanhan/seqcrowd-acl17)                      |
| 2019 | EMNLP |                                                                                                                                                [A Bayesian Approach for Sequence Tagging with Crowds](https://arxiv.org/abs/1811.00780)                                                                                                                                                 |               [Official](https://github.com/UKPLab/arxiv2018-bayesian-ensembles)               |
| 2020 |  ACL  |                                                                                                                                     [Named Entity Recognition without Labelled Data: A Weak Supervision Approach](https://arxiv.org/abs/2004.14723)                                                                                                                                     |           [Official](https://github.com/NorskRegnesentral/weak-supervision-for-NER)            |
| 2020 | AAAI  |                                                                                                                                      [Weakly Supervised Sequence Tagging from Noisy Rules](https://ojs.aaai.org/index.php/AAAI/article/view/6009)                                                                                                                                       |               [Official](https://github.com/BatsResearch/safranchik-aaai20-code)               |
| 2021 |  ACL  |                                                                                                                                                                     [ skweak: Weak Supevision Made Easy for NLP](https://arxiv.org/abs/2104.09683)                                                                                                                                                                      |                    [Official](https://github.com/NorskRegnesentral/skweak)                     |


### 2.2.B Deep Learning Model



| Year |     Venue      |                                                                                                                             Title                                                                                                                              |                       Implementation                       | 
|:----:|:--------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------:|
| 2017 |      ACL       |                                                                                             [Aggregating and predicting sequence labels from crowd annotations](https://aclanthology.org/P17-1028/)                                                                                              |   [Official](https://github.com/thanhan/seqcrowd-acl17)    |
| 2018 |      AAAI      |                                                                                                 [Deep learning from crowds](https://arxiv.org/abs/1709.01779)                                                                                                  |       [Official](https://github.com/fmpr/CrowdLayer)       |
| 2020 |      ACL       |                                                                     [Learning to contextually aggregate multi-source supervision for sequence labeling](https://arxiv.org/abs/1910.04289)                                                                      |       [Official](https://github.com/INK-USC/ConNet)        |
| 2020 | EMNLP Findings |                                                                  [OptSLA: an Optimization-Based Approach for Sequential Label Aggregation](https://aclanthology.org/2020.findings-emnlp.119/)                                                                  |       [Official](https://github.com/NasimISU/OptSLA)       |
| 2021 |      ICDM      |                                                                                       [Truth Discovery in Sequence Labels from Crowds](https://arxiv.org/abs/2109.04470)                                                                                       |                        [Official](https://github.com/NasimISU/Truth-Discovery-in-Sequence-Labels-from-Crowds)                        |
| 2021 |      ACL       |                                                                   [Crowdsourcing Learning as Domain Adaptation: A Case Study on Named Entity Recognition](https://arxiv.org/abs/2105.14980)                                                                    |         [Official](https://github.com/izhx/CLasDA)         |
| 2023 |      ICDE      |                                                                                        [Learning from Noisy Crowd Labels with Logics](https://arxiv.org/abs/2302.06337)                                                                                        |    [Official](https://github.com/junchenzhi/Logic-LNCL)    |


### 2.3.C Neural Graphical Model


| Year | Venue |                                                                                                                                                                                                                                                                                                                                    Title                                                                                                                                                                                                                                                                                                                                    |                     Implementation                 | 
|:----:|:-----:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------:|
| 2021 |  ACL  |                                                                                                                                                                                                                                                                      [BERTifyingthe Hidden Markov Model for Multi-Source Weakly Supervised Named Entity Recognition](https://arxiv.org/abs/2105.12848)                                                                                                                                                                                                                                                                      |                      [Official](https://github.com/Yinghao-Li/CHMM-ALT)                  |
| 2022 |  KDD  |                                                                                                                                                                                                                                                                          [Sparse Conditional Hidden Markov Model for Weakly Supervised Named Entity Recognition](https://arxiv.org/abs/2205.14228)                                                                                                                                                                                                                                                                          | [Official](https://github.com/Yinghao-Li/Sparse-CHMM) |
| 2023 |  KDD  |                                                                                                                                                                                                                                                                                                           [Neural-Hidden-CRF: A Robust Weakly-Supervised Sequence Labele](https://dl.acm.org/doi/abs/10.1145/3580305.3599445)                                                                                                                                                                                                                                                                                                            | [Official](https://github.com/junchenzhi/Neural-Hidden-CRF)     


# 3  Personal Recommendation
- Recent great weak-supervision benchmark called Wrench (NeuIPS-2021):  [WRENCH: A Comprehensive Benchmark for Weak Supervision](https://arxiv.org/abs/2109.11377) ([Code](https://github.com/JieyuZ2/wrench))                    
# 4 Other Resources

- Awesome-Weak-Supervision: https://github.com/JieyuZ2/Awesome-Weak-Supervision
- Awesome-Learning-with-Label-Noise: https://github.com/subeeshvasu/Awesome-Learning-with-Label-Noise
- Awesome-Noisy-Labels: https://github.com/songhwanjun/Awesome-Noisy-Labels
- A survey on crowdsourcing learning: [Knowledge Learning with Crowdsourcing: A Brief Review and Systematic Perspective](https://arxiv.org/abs/2206.09315)

