# Introduction
Here's a list of papers on machine learning for causal inference. This is not an exhaustive list but rather a snapshot of recent recent work that I've found interesting and useful in my job as a data scientist.

In the future, I may add some commentary on the papers to help anyone who is interested to navigate this rapidly progressing field.

# Machine learning for causal inference

## Overviews
* [The Impact of Machine Learning on Economics](http://www.nber.org/chapters/c14009.pdf) [Athey 2018]
* [A Bibliographic Guide to Methods for Causal Inference: Theory, Software, and Applications](https://web.uri.edu/ssirep/files/BGMCI6752.pdf) [Burkett 2017]

## Heterogeneous treatment effect estimation

### Lasso based methods
* [Generic Machine Learning Inference on Heterogenous Treatment Effects in Randomized Experiments](https://arxiv.org/abs/1712.04802?context=econ) [Chernozhukov et al 2018]
* [Estimating treatment effect heterogeneity in randomized program evaluation](https://imai.princeton.edu/research/files/svm.pdf) [Imai and Ratkovic 2013]

### Tree based methods
* [Some methods for heterogeneous treatment effect estimation in high dimensions](http://doi.wiley.com/10.1002/sim.7623) [Powers et al 2017]
* [Recursive Partitioning for Heterogeneous Causal Eﬀects](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4941430/) [Athey and Imbens 2016]
* [Generalized Random Forests](https://arxiv.org/abs/1610.01271) [Athey et al 2017]
* [Estimation and Inference of Heterogeneous Treatment Effects using Random Forests](https://arxiv.org/abs/1510.04342) [Wager and Athey 2017]
* [Estimating Individual Treatment Effect in Observational Data Using Random Forest Methods](https://arxiv.org/abs/1701.05306) [Lu et al 2017]
* [Estimating Heterogeneous Treatment Effects and the Effects of Heterogeneous Treatments with Ensemble Methods](https://www.cambridge.org/core/product/identifier/S1047198717000158/type/journal_article) [Grimmer et al 2017]

### Bayesian methods
* [Uncovering Heterogeneous Treatment Eﬀects](http://www.princeton.edu/~shiraito/research/dp4hetero.pdf) [Shiraito 2016]
* [Bayesian Regression Tree Models for Causal Inference: Regularization, Confounding, and Heterogeneous Effects](https://arxiv.org/abs/1706.09523) [Hahn et al 2017]

### Neural networks based methods
* [The Supervised Learning Approach To Estimating Heterogeneous Causal Regime Effects](http://web.stanford.edu/~thaipham/papers/Heterogeneous_Regime_Effects.pdf) [Pham 2016]
* [Estimating individual treatment effect: generalization bounds and algorithms](https://arxiv.org/pdf/1606.03976.pdf) [Shalit et al 2017]

### Meta-learners
* [Meta-learners for Estimating Heterogeneous Treatment Eﬀects using Machine Learning](https://arxiv.org/abs/1706.03461) [Künzel et al 2017]
* [Learning Objectives for Treatment Eﬀect Estimation](https://arxiv.org/abs/1712.04912) [Nie and Wager 2018]

### K-nearest neighbours
* [Causal nearest neighbor rules for optimal treatment regimes](https://arxiv.org/abs/1711.08451) [Zhou and Kosorok 2017]

### Applied

#### Policy interventions
* [Using Causal Forests to Predict Treatment Heterogeneity: An Application to Summer Jobs](http://pubs.aeaweb.org/doi/10.1257/aer.p20171000) [Davis and Heller 2017]
* [Tree-Based Estimation of Heterogeneous Dynamic Policy Effects](https://www.ssrn.com/abstract=3049044) [Miller 2017]
* [Rethinking the Beneﬁts of Youth Employment Programs: The Heterogeneous Effects of Summer Jobs](http://www.nber.org/papers/w23443) [Davis and Heller 2017]

#### Advertisement
* [Incrementality Bidding & Attribution](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3129350) [Lewis and Wong 2018]

## Propensity scores
* [A Comparison of Approaches to Advertising Measurement: Evidence from Big Field Experiments at Facebook](https://www.kellogg.northwestern.edu/faculty/gordon_b/files/fb_comparison.pdf) [Gordon et al 2018]

## Interrupted time series analysis

## Double-robustness
* [Data-adaptive doubly robust instrumental variable methods for treatment eﬀect heterogeneity](https://arxiv.org/abs/1802.02821) [DiazOrdaz et al 2018]

## Directed acyclic graphs
* [Theoretical Impediments to Machine Learning With Seven Sparks from the Causal Revolution](http://ftp.cs.ucla.edu/pub/stat_ser/r475.pdf) [Pearl 2018]
* [The Seven Pillars of Causal Reasoning with Reflections on Machine Learning](http://ftp.cs.ucla.edu/pub/stat_ser/r481.pdf) [Pearl 2018]
