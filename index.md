# Introduction
Here's a list of papers on machine learning for causal inference. This is not an exhaustive list but rather a snapshot of recent recent work that I've found interesting and useful in my job as a data scientist.

In the future, I may add some commentary on the papers to help anyone who is interested to navigate this rapidly progressing field.

# Machine learning for causal inference

## Overviews
* Athey, Susan. n.d. “The Impact of Machine Learning on Economics.” Accessed December 18, 2018. https://www.nber.org/chapters/c14009.pdf.

* Burkett, John P. n.d. “A Bibliographic Guide to Methods for Causal Inference: Theory, Software, and Applications.” https://web.uri.edu/ssirep/files/BGMCI.pdf

## Heterogeneous treatment effect estimation

### Lasso based methods
* Chernozhukov, Victor, Mert Demirer, Esther Duflo, and Ivan Fernandez-Val. 2017. “Generic Machine Learning Inference on Heterogenous Treatment Effects in Randomized Experiments.” arXiv [stat.ML]. arXiv. http://arxiv.org/abs/1712.04802.

* Imai, Kosuke, and Marc Ratkovic. 2013. “Estimating Treatment Effect Heterogeneity in Randomized Program Evaluation.” arXiv [stat.AP]. arXiv. https://doi.org/10.1214/12-AOAS593.

### Tree based methods
* Athey, Susan, and Guido Imbens. 2015. “Recursive Partitioning for Heterogeneous Causal Effects.” arXiv [stat.ML]. arXiv. http://arxiv.org/abs/1504.01132.

* Athey, Susan, Julie Tibshirani, and Stefan Wager. 2016. “Generalized Random Forests.” arXiv [stat.ME]. arXiv. http://arxiv.org/abs/1610.01271.

* Friedberg, Rina, Julie Tibshirani, Susan Athey, and Stefan Wager. 2018. “Local Linear Forests.” arXiv [stat.ML]. arXiv. http://arxiv.org/abs/1807.11408.

* Grimmer, Justin, Solomon Messing, and Sean J. Westwood. 2017. “Estimating Heterogeneous Treatment Effects and the Effects of Heterogeneous Treatments with Ensemble Methods.” Political Analysis: An Annual Publication of the Methodology Section of the American Political Science Association 25 (4): 413–34. https://doi.org/10.1017/pan.2017.15.

* Oprescu, Miruna, Vasilis Syrgkanis, and Zhiwei Steven Wu. 2018. “Orthogonal Random Forest for Heterogeneous Treatment Effect Estimation.” arXiv [cs.LG]. arXiv. http://arxiv.org/abs/1806.03467.

* Wager, Stefan, and Susan Athey. 2015. “Estimation and Inference of Heterogeneous Treatment Effects Using Random Forests.” arXiv [stat.ME]. arXiv. http://arxiv.org/abs/1510.04342.

### Bayesian methods
* Shiraito, Yuki. n.d. “Uncovering Heterogeneous Treatment Effects.” https://scholar.princeton.edu/shiraito/publications/uncovering-variety-causality-bayesian-nonparametric-approach-treatment

* Richard Hahn, P., Jared S. Murray, and Carlos Carvalho. 2017. “Bayesian Regression Tree Models for Causal Inference: Regularization, Confounding, and Heterogeneous Effects.” arXiv [stat.ME]. arXiv. http://arxiv.org/abs/1706.09523.

### Neural networks based methods
* Pham, Thai T. n.d. “The Supervised Learning Approach To Estimating Heterogeneous Causal Regime E Ects.”

* Pham, Thai T., and Yuanyuan Shen. 2017. “A Deep Causal Inference Approach to Measuring the Effects of Forming Group Loans in Online Non-Profit Microfinance Platform.” arXiv [stat.ML]. arXiv. http://arxiv.org/abs/1706.02795.

* Shalit, Uri, Fredrik D. Johansson, and David Sontag. 2016. “Estimating Individual Treatment Effect: Generalization Bounds and Algorithms.” arXiv [stat.ML]. arXiv. http://arxiv.org/abs/1606.03976.

### Meta-learners
* Künzel, Sören R., Jasjeet S. Sekhon, Peter J. Bickel, and Bin Yu. 2017. “Meta-Learners for Estimating Heterogeneous Treatment Effects Using Machine Learning.” arXiv [math.ST]. arXiv. http://arxiv.org/abs/1706.03461.

* Künzel, Sören R., Bradly C. Stadie, Nikita Vemuri, Varsha Ramakrishnan, Jasjeet S. Sekhon, and Pieter Abbeel. 2018. “Transfer Learning for Estimating Causal Effects Using Neural Networks.” arXiv [stat.ML]. arXiv. http://arxiv.org/abs/1808.07804.

* Stadie, Bradly C., Sören R. Künzel, Nikita Vemuri, and Jasjeet S. Sekhon. 2018. “Estimating Heterogeneous Treatment Effects Using Neural Networks With The Y-Learner,” September. https://openreview.net/forum?id=ryxnDoRcK7.

### K-nearest neighbours

* Zhou X, Kosorok MR. Causal nearest neighbor rules for optimal treatment regimes [Internet]. arXiv [stat.ML]. 2017. Available: http://arxiv.org/abs/1711.08451

### Uplift modeling

* Guelman, Leo, Montserrat Guillén, and Ana M. Pérez-Marín. 2012. “Random Forests for Uplift Modeling: An Insurance Customer Retention Case.” In Modeling and Simulation in Engineering, Economics and Management, 123–33. Springer Berlin Heidelberg. https://doi.org/10.1007/978-3-642-30433-0_13.

* ———. 2015. “Uplift Random Forests.” Cybernetics and Systems 46 (3-4): 230–48. https://doi.org/10.1080/01969722.2015.1012892.

* Gutierrez, Pierre, and Jean-Yves Gerardy. n.d. “Causal Inference and Uplift Modeling A Review of the Literature.”

* Nie, Xinkun, and Stefan Wager. 2017. “Quasi-Oracle Estimation of Heterogeneous Treatment Effects.” arXiv [stat.ML]. arXiv. http://arxiv.org/abs/1712.04912.

* Rzepakowski, Piotr, and Szymon Jaroszewicz. 2012. “Decision Trees for Uplift Modeling with Single and Multiple Treatments.” Knowledge and Information Systems 32 (2): 303–27. https://doi.org/10.1007/s10115-011-0434-0.

* Zhao, Yan, Xiao Fang, and David Simchi-Levi. 2017. “Uplift Modeling with Multiple Treatments and General Response Types.” arXiv [cs.AI]. arXiv. http://arxiv.org/abs/1705.08492.

## Regression discontinuity design
* Herlands, William, and Edward Mc Fowland III. n.d. “Automated Local Regression Discontinuity Design Discovery.” https://doi.org/10.1145/3219819.3219982.

## Double-robustness
* DiazOrdaz, Karla, Rhian Daniel, and Noemi Kreif. 2018. “Data-Adaptive Doubly Robust Instrumental Variable Methods for Treatment Effect Heterogeneity.” arXiv [stat.ME]. arXiv. http://arxiv.org/abs/1802.02821.

## Directed acyclic graphs
* Pearl, Judea. 2018a. “The Seven Tools of Causal Inference with Reflections on Machine Learning.” Communications of Association for Computing Machinery. https://doi.org/10.1145/nnnnnnn.nnnnnnn.

* ———. 2018b. “Theoretical Impediments to Machine Learning With Seven Sparks from the Causal Revolution.” UCLA. http://ftp.cs.ucla.edu/pub/stat_ser/r475.pdf.

* Pearl, Judea, and Elias Bareinboim. 2015. “External Validity: From Do-Calculus to Transportability Across Populations.” arXiv [stat.ME]. arXiv. https://doi.org/10.1214/14-STS486.

## Applied

### Policy interventions
* Davis, Jonathan M. V., and Sara B. Heller. 2017. “Using Causal Forests to Predict Treatment Heterogeneity: An Application to Summer Jobs.” The American Economic Review 107 (5): 546–50. https://doi.org/10.1257/aer.p20171000.

* Davis, Jonathan M. V., and Sara B. Heller. 2017. “Rethinking the Benefits of Youth Employment Programs: The Heterogeneous Effects of Summer Jobs.” Working Paper Series. National Bureau of Economic Research. https://doi.org/10.3386/w23443.

* Miller, Steve. 2017. “Tree-Based Estimation of Heterogeneous Dynamic Policy Effects.” https://doi.org/10.2139/ssrn.3049044.

### Advertisement
* Lewis, Randall A., and Jeffrey Wong. 2018. “Incrementality Bidding & Attribution,” February. https://doi.org/10.2139/ssrn.3129350.

* Gordon, Brett R., and Florian Zettelmeyer. n.d. “A Comparison of Approaches to Advertising Measurement: Evidence from Big Field Experiments at Facebook∗.”
