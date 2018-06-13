+++
title = "Bayesian On-line Changepoint Detection 2.0"

date = 2018-05-07
lastmod = 2018-05-07
draft = false

#tags = [""]
summary = "Research on the next generation of Bayesian On-line Changepoint Detection algorithms. Amongst other things, the resulting inference procedure produces robust and spatio-temporal inference with on-line prediction, model selection and changepoint detection. The method scales and has constant run-time per observation. It is applicable to a wide variety of data streams, covering univariate, multivariate and spatially structured problems. As part of this project, I have also written reusable software that received the [Alan Turing Institute's Reproducible Research award](https://github.com/alan-turing-institute/ReproducibleResearchResources)."

+++

**Bayesian On-line Changepoint Detection (BOCPD)** is a discrete-time inference framework introduced in the statistics and machine learning community independently by [Fearnhead & Liu (2007)](http://eprints.lancs.ac.uk/745/1/online_chpt4.pdf) and [Adams & MacKay (2007)](https://arxiv.org/abs/0710.3742). Taken together, both papers have generated in excess of 500 citations and inspired more research in this area. The method is popular because it is efficient and runs in constant time per observation processed. Me and my collaborators are working on extending the inference paradigm in several ways:

- [x] Unifiying Fearnhead & Liu (2007) and Adams & MacKay (2007)¹
- [x] Multivariate analysis¹
- [x] Robust analysis²
- [ ] Continuous-time models 
- [ ] Point processes 

The software written as part of this ongoing project received the [Alan Turing Institute's Reproducible Research award](https://github.com/alan-turing-institute/ReproducibleResearchResources), and will be linked here via my github repo once it failsafe to use.

¹Jeremias Knoblauch, Theodoros Damoulas. [Spatio-temporal Bayesian On-line Changepoint Detection]({{< relref "publication/STBOCPDMS.md" >}}), *International Conference on Machine Learning* (2018). 

²
Jeremias Knoblauch, Jack Jewson, Theodoros Damoulas. [Doubly Robust Bayesian Inference for Non-Stationary Streaming Data with β-Divergences]({{< relref "publication/RobustBOCPD.md" >}}), *arXiv:1806.02261* (2018). 


