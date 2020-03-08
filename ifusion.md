## Individualized Fusion Learning (*i*Fusion)

Inferences from different data sources can often be fused together, a process referred to as “fusion learning,” to yield more powerful findings than those from individual data sources alone. Effective fusion learning approaches are in growing demand as increasing number of data sources have become easily available in this big data era. This article proposes a new fusion learning approach, called “*i*Fusion,” for drawing efficient individualized inference by fusing learnings from relevant data sources. Specifically, iFusion (i) summarizes inferences from individual data sources as individual confidence distributions (CDs); (ii) forms a clique of individuals that bear relevance to the target individual and then combines the CDs from those relevant individuals; and, finally, (iii) draws inference for the target individual from the combined CD. In essence, iFusion strategically “borrows strength” from relevant individuals to enhance the efficiency of the target individual inference while preserving its validity. This article focuses on the setting where each individual study has a number of observations but its inference can be further improved by incorporating additional information from similar studies that is referred to as its clique. Under the setting, iFusion is shown to achieve oracle property under suitable conditions. It is also shown to be flexible and robust in handling heterogeneity arising from diverse data sources. The development is ideally suited for goal-directed applications. Computationally, iFusion is parallel in nature and scales up easily for big data. An efficient scalable algorithm is provided for implementation. Simulation studies and a real application in financial forecasting are presented. In effect, this article covers methodology, theory, computation, and application for individualized inference by iFusion.


*i*Fusion as a trade-off between bias and variance

<img src="images/idea.png?raw=true" width="600"/>

Why *i*Fusion?

<img src="images/pros.png?raw=true" width="600"/>

*i*Fusion vs classical fusion learning/meta analysis

<img src="images/flow.png?raw=true" width="600"/>


---

### Links
- [Full article]- **J Shen**, M Xie, and R Liu. (2019). [*i*Fusion: Individualized Fusion Learning](https://amstat.tandfonline.com/doi/abs/10.1080/01621459.2019.1672557#.XciGbJJKg6U). *Journal of the American Statistical Association*, to appear.
- [Review article on confidence distribution](https://www.stat.rutgers.edu/home/mxie/RCPapers/insr.12000.pdf): M Xie, K Singh. (2013). Confidence distribution, the frequentist distribution estimator of a parameter: A review. *International Statistical Review*, **81**, 3–39.