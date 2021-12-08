[Welcome](/index) | [Research](/research) | [Services](/services) | [Publications](https://scholar.google.com/citations?user=itO_fw8AAAAJ&hl=en) | [eBook]()

# Research

## Theoretical Foundation of Statistical Inference

The research is to develop new methodologies with in mind the foundational principles of statistical inference, in particular, using the concept of confidence distribution. A confidence distribtion can been loosely referred to as a distribution function on the parameter space that can represent confidence intervals of all levels for a parameter of interest. It is no different from a point estimator or an interval estimator (confidence interval), but it uses a sample-dependent distribution function on the parameter space (instead of a point or an interval) to estimate the parameter of interest. Some recent developments have highlighted the promising potentials of the CD concept, as an effective inferential tool






 it encompasses and unifies a wide range of examples, from regular parametric cases (including most examples of the classical development of Fisher's fiducial distribution) to bootstrap distributions, p-value functions,[5] normalized likelihood functions and, in some cases, Bayesian priors and Bayesian posteriors.[6]





The [Bayesian, Fiducial, and Frequentist (BFF) community](http://bff-stat.org/) began in 2014 as a means to facilitate scientific exchange among statisticians and scholars in related fields that  The community encourages and promotes research activities , 



The research proposes a general framework for prediction in which a prediction is presented in the form of a distribution function, called *predictive distribution function*. This predictive distribution function is well suited for the notion of confidence subscribed in the frequentist interpretation, and it can provide meaningful answers for questions related to prediction. 

A general approach under this framework is formulated and illustrated by using the so-called confidence distributions (CDs). This CD-based prediction approach inherits many desirable properties of CD, including its capacity for serving as a common platform for connecting and unifying the existing procedures of predictive inference in Bayesian, fiducial and frequentist paradigms. The theory underlying the CD-based predictive distribution is developed and some related efficiency and optimality issues are addressed. Moreover, a simple yet broadly applicable Monte Carlo algorithm is proposed for the implementation of the proposed approach. This concrete algorithm together with the proposed definition and associated theoretical development produce a comprehensive statistical inference framework for prediction. 

### Working papers and publications
- **J Shen**, M Xie, and R Liu. (2020). [*i*Fusion: Individualized fusion learning](https://amstat.tandfonline.com/doi/abs/10.1080/01621459.2019.1672557#.XciGbJJKg6U). *Journal of the American Statistical Association*, **115**, 1251-1267.
- **J Shen**, M Xie, and R Liu. (2019). [Prediction with confidence - A general framework for predictive inference](https://www.sciencedirect.com/science/article/abs/pii/S0378375817301696). *Journal of Statistical Planing and Inference*, **195**: 126-140.
- V Vovk, **J Shen**, V Manokhin, M Xie, and R Liu. (2019). [Nonparametric predictive distributions based on conformal prediction](https://link.springer.com/article/10.1007/s10994-018-5755-8). *Machine Learning*, **108**: 445-474. 
- **J Shen** and C Li. Meta-analysis of correlation coefficients using confidence distributions. Manuscript.

---

## Statistical Methods for Personalized Inference

Inferences from different data sources can often be fused together, a process referred to as “fusion learning,” to yield more powerful findings than those from individual data sources alone. Effective fusion learning approaches are in growing demand as increasing number of data sources have become easily available in this big data era. 

This research proposes a new fusion learning approach, called “*i*Fusion,” for drawing efficient individualized inference by fusing learnings from relevant data sources. Specifically, *i*Fusion:	

1. summarizes inferences from individual data sources as individual confidence distributions (CDs); 
2. forms a clique of individuals that bear relevance to the target individual and then combines the CDs from those relevant individuals; 
3. draws inference for the target individual from the combined CD. 

In essence, iFusion strategically “borrows strength” from relevant individuals to enhance the efficiency of the target individual inference while preserving its validity. The research focuses on the setting where each individual study has a number of observations but its inference can be further improved by incorporating additional information from similar studies that is referred to as its clique. Under the setting, iFusion is shown to achieve oracle property under suitable conditions. It is also shown to be flexible and robust in handling heterogeneity arising from diverse data sources. The development is ideally suited for goal-directed applications. Computationally, iFusion is parallel in nature and scales up easily for big data. An efficient scalable algorithm is provided for implementation. 

<img src="images/idea.png?raw=true" width="600"/>

### Working papers and publications
- **J Shen**, M Xie, and R Liu. (2019). [*i*Fusion: Individualized Fusion Learning](https://amstat.tandfonline.com/doi/abs/10.1080/01621459.2019.1672557#.XciGbJJKg6U). *Journal of the American Statistical Association*, to appear.

---

## Predictive Customer Lifetime Value

<img src="images/clv.jpeg?raw=true" width="600"/>

Customer lifetime value (CLV) measures the worth of a customer to a firm. It is the net present value of future
cash flow from the customer’s relationship to the firm. CLV has been studied in academia for decades and has been
gaining growing interest and routinely used by firms to develop customer-centric strategies. There are numerous values offered by CLV. One of the primary uses is by marketers to “determine the ideal target audience for promotional offers, personalized customer messaging, exclusive deals, rewards programs” [Vanderveld et al., 2016], and to optimize their marketing spend for optimal return on investment. In addition to its huge marketing value, CLV can be used as a general performance metric in all areas of business, with a focus on the profitable growth in the long term [Vanderveld et al., 2016], as opposed to many metrics that values customers only over the short term. Last but not definitely not the least, CLV can help financial planning and tie the firm’s overall financial valuation to its customer base in an explicit way [McCarthy and Fader, 2018]. For more examples of using CLV to develop actionable customer-centric strategies see Kumar [2008], Fader and Toms [2018].

A study of modern approaches to predicting customer lifetime value and how to use it to develop customer-centric strategies. 


### Working papers and publications
- **J Shen**. Predictive customer lifetime value - a survey. To be available at arXiv.org.

---

## Machine Learning Applications in U.S. Treasury Market

<img src="images/ust.jpeg?raw=true" width="600"/>

The research topic is to apply machine learning methods in predicting the U.S. Treasury market, for different types of prediction targets including Treasury yield curve, yield spread, bond future price, and bond risk premia, at various timescales from intraday to yearly. 

### Working papers and publications
- **J Shen**. A survey of machine learning applications in forecasting Treasury market. To be available at arXiv.org.

<!---

### Manuscripts

- **J Shen** and C Li. Meta-analysis of correlation coefficients using confidence distributions. 
- **J Shen** and M Xie. Discrepant posterior phenomenon: what can we learn from it?
- T Yan, **J Shen**, and Y Yang. Fast algorithm for grouping genotype combinations with application to multiple-locus association analyses.
- **J Shen**, and J Shi. Forecasting soccer game results using ordinal logistic regression models and a gambling strategy.
-->
