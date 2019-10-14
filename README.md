# Must-read papers and resources on {Causal}∩{ML}

Contribtions are welcome. Inspired by [GNNpapers](https://github.com/thunlp/GNNPapers).

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Surveys</a></td></tr> 
<tr><td colspan="2"><a href="#counterfactual-prediction">2. Counterfactual prediction</a></td></tr>
<tr><td colspan="2"><a href="#representation-learning">3. Representation learning / domain adaptation</a></td></tr>
<tr><td colspan="2"><a href="#text">4. Covariate adjustment / dimensionality reduction</a></td></tr>
<tr><td colspan="2"><a href="#heterogeneous-treatment-effects">5. Heterogeneous treatment effects</a></td></tr>
<tr><td colspan="2"><a href="#causal-discovery">6. Causal discovery</a></td></tr>
<tr><td colspan="2"><a href="#semiparametric-inference">7. Semiparametric inference</a></td></tr>
<tr><td colspan="2"><a href="#counterfactual-learning">8. Counterfactual learning</a></td></tr>
<tr><td colspan="2"><a href="#applications">9. Applications</a></td></tr> 
<tr>
    <td>&emsp;<a href="social-sciences">9.1. Social Sciences</a></td>
    <td>&ensp;<a href="#text">9.2. Text</a></td>
</tr> 
<tr><td colspan="2"><a href="#resources">10. Resources</a></td></tr> 
<tr>
    <td>&emsp;<a href="#workshops">10.1. Workshops</a></td>
    <td>&emsp;<a href="#proceedings">10.2. Proceedings</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#code-libraries">10.3. Code libraries</a></td>
    <td>&emsp;<a href="#benchmark-datasets">10.4. Benchmark datasets</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#courses">10.5. Courses</a></td>
</tr> 
</table>

## [Survey papers](#content)
1. **Machine learning and causal inference for policy evaluation**, *KDD*, 2015. [paper](https://dl.acm.org/citation.cfm?id=2785466)
    
    Susan Athey.

## [Counterfactual prediction](#content)  

1. **Robust Synthetic Control**, *JMLR*, 2019. [paper](http://www.jmlr.org/papers/volume19/17-777.pdf)
    
    Muhammad Amjad, Devavrat Shah, Dennis Shen.

1. **Deep IV: A Flexible Approach for Counterfactual Prediction**, *PMLR*, 2017. [paper](http://proceedings.mlr.press/v70/hartford17a.html)
    
    Uri Shalit, Fredrik D. Johansson, David Sontag.

1. **Forecasting Treatment Responses Over Time Using Recurrent Marginal Structural Networks**, *NIPS*, 2018. [paper](http://proceedings.mlr.press/v70/hartford17a.html)
    
    Bryan Lim, Ahmed Alaa, Mihaela van der Schaar.

1. **Causal Effect Inference with Deep Latent-Variable Models**, *arXiv*, 2017. [paper](https://arxiv.org/abs/1705.08821)
    
    Christos Louizos, Uri Shalit, Joris Mooij, David Sontag, Richard Zemel, Max Welling

1. **GANITE: Estimation of Individualized Treatment Effects using Generative Adversarial Nets**, *ICLR*, 2018. [paper](https://openreview.net/pdf?id=ByKWUeWA-)
    
    Jinsung Yoon, James Jordon, Mihaela van der Schaar.

1. **Counterfactual Policy Optimization Using Domain-Adversarial Neural Networks**, *ICML*, 2018. [paper](http://medianetlab.ee.ucla.edu/papers/cf_treat_v5)
    
    Onur Atan, William R. Zame, Mihaela van der Schaar.

1. **Estimation of Individual Treatment Effect in Latent Confounder Models via Adversarial Learning**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1811.08943)
    
    Changhee Lee, Nicholas Mastronarde, Mihaela van der Schaar.

## [Representation learning / domain adaptation](#content)   

1. **Learning Representations for Counterfactual Inference**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1605.03661) 
    
    Fredrik D. Johansson, Uri Shalit, David Sontag.

1. **Representation Learning for Treatment Effect Estimation from Observational Data**, *NeurIPS*, 2019. [paper](https://papers.nips.cc/paper/7529-representation-learning-for-treatment-effect-estimation-from-observational-data.pdf) 
    
    Yao et al.

1. **Estimating individual treatment effect: generalization bounds and algorithms**, *PMLR*, 2017. [paper](http://proceedings.mlr.press/v70/shalit17a.html)
    
    Uri Shalit, Fredrik D. Johansson, David Sontag.

1. **Recommendations as Treatments: Debiasing Learning and Evaluation**, *PMLR*, 2016. [paper](http://proceedings.mlr.press/v48/schnabel16.html)
    
    Tobias Schnabel, Adith Swaminathan, Ashudeep Singh, Navin Chandak, Thorsten Joachims.

1. **Collaborative Prediction and Ranking with Non-Random Missing Data**, *RecSys*, 2009. [paper](http://www.cs.toronto.edu/~zemel/documents/acmrec2009-MarlinZemel.pdf)
    
    Benjamin M. Marlin, Richard S. Zemel.

## [Covariate adjustment / dimensionality reduction](#content)  

1. **Lasso adjustments of treatment effect estimates in randomized experiments**, *PNAS*, 2016. [paper](https://www.pnas.org/content/113/27/7383.short)
    
    Adam Bloniarz, Hanzhong Liu, Cun-Hui Zhang, Jasjeet S. Sekhon, Bin Yu.

## [Heterogeneous treatment effects](#content)  

1. **Estimating treatment effect heterogeneity in randomized program evaluation**, *Annals of Applied Statistics*, 2013. [paper](https://projecteuclid.org/euclid.aoas/1365527206)
    
    Kosuke Imai, Marc Ratkovic.

1. **Recursive partitioning for heterogeneous causal effects**, *PNAS*, 2016. [paper](https://www.pnas.org/content/113/27/7353)
    
    Susan Athey, Guido Imbens.

1. **Estimation and Inference of Heterogeneous Treatment Effects using Random Forests**, *JASA*, 2018. [paper](https://amstat.tandfonline.com/doi/full/10.1080/01621459.2017.1319839#.XaPLBeZKhhE)
    
    Stefan Wager, Susan Athey.

1. **Limits of Estimating Heterogeneous Treatment Effects: Guidelines for Practical Algorithm Design**, *PMLR*, 2018. [paper](http://proceedings.mlr.press/v80/alaa18a.html)
    
    Ahmed Alaa, Mihaela Schaar.

1. **Machine Learning Estimation of Heterogeneous Treatment Effects with Instruments**, *NeurIPS*, 2019. [paper](https://arxiv.org/abs/1905.10176)
    
    Vasilis Syrgkanis, Victor Lei, Miruna Oprescu, Maggie Hei, Keith Battocchi, Greg Lewis.

1. **Orthogonal Random Forest for Causal Inference**, *PMLR*, 2019. [paper](http://proceedings.mlr.press/v97/oprescu19a.html)

    Miruna Oprescu, Vasilis Syrgkanis, Zhiwei Steven Wu.

1. **Meta-learners for Estimating Heterogeneous Treatment Effects using Machine Learning**, *PNAS*, 2019. [paper](https://arxiv.org/abs/1706.03461)

    Miruna Oprescu, Vasilis Syrgkanis, Zhiwei Steven Wu.

1. **Transfer Learning for Estimating Causal Effects using Neural Networks**, *arXiv*, 2018. [paper](https://arxiv.org/abs/1808.07804)

    Sören R. Künzel, Bradly C. Stadie, Nikita Vemuri, Varsha Ramakrishnan, Jasjeet S. Sekhon, Pieter Abbeel.

## [Causal discovery](#content)  

1. **Learning Neural Causal Models from Unknown Interventions**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1910.01075)
    
    Nan Rosemary Ke, Olexa Bilaniuk, Anirudh Goyal, Stefan Bauer, Hugo Larochelle, Chris Pal, Yoshua Bengio.

## [Semiparametric inference](#content)  

1. **Double/Debiased Machine Learning for Treatment and Causal Parameters**, *arXiv*, 2017. [paper](https://arxiv.org/abs/1608.00060)
    
    Victor Chernozhukov, Denis Chetverikov, Mert Demirer, Esther Duflo, Christian Hansen, Whitney Newey, James Robins.

1. **Doubly Robust Policy Evaluation and Optimization**, *Statistical Science*, 2014. [paper](https://arxiv.org/abs/1503.02834)
    
    Miroslav Dudík, Dumitru Erhan, John Langford, Lihong Li.

## [Counterfactual learning](#content)  

1. **The Blessings of Multiple Causes**, *arXiv*, 2019. [paper](https://arxiv.org/abs/1805.06826)
    
    Yixin Wang, David M. Blei.

1. **Causal Bandits: Learning Good Interventions via Causal Inference**, *NIPS*, 2016. [paper](https://papers.nips.cc/paper/6195-causal-bandits-learning-good-interventions-via-causal-inference)
    
    Finnian Lattimore, Tor Lattimore, Mark D. Reid.

1. **Counterfactual Risk Minimization: Learning from Logged Bandit Feedback**, *arXiv*, 2015. [paper](https://arxiv.org/pdf/1502.02362.pdf)
    
    Adith Swaminathan, Thorsten Joachims.

## [Applications](#content)

### [Social sciences](#content)
1. **Retrospective Causal Inference with Machine Learning Ensembles: An Application to Anti-recidivism Policies in Colombia**, *Political Analysis*, 2016. [paper](https://arxiv.org/abs/1607.03026)
    
    Cyrus Samii, Laura Paler, Sarah Zukerman Daly 

### [Text](#content)

1. **Counterfactual Story Reasoning and Generation**, *arXIv*, 2019. [paper](https://arxiv.org/abs/1909.04076)
    
    Lianhui Qin, Antoine Bosselut, Ari Holtzman, Chandra Bhagavatula, Elizabeth Clark, Yejin Choi

## [Resources](#content)

### [Workshops](#content)

1. **NeurIPS 2019 Workshop** [link](http://tripods.cis.cornell.edu/neurips19_causalml/)

1. **NIPS 2017 Workshop** [link](https://sites.google.com/view/causalnips2017)

1. **NIPS 2013 Workshop** [link](http://clopinet.com/isabelle/Projects/NIPS2013/)

### [Proceedings](#content)

1. **PMLR, Volume 6: Causality: Objectives and Assessment, 12 December 2008, Whistler, Canada** [link](http://proceedings.mlr.press/v6/)

### [Code libraries](#content)

1. **EconML: A Python Package for ML-Based Heterogeneous Treatment Effects Estimation** [link](https://github.com/microsoft/EconML)

1. **Uplift modeling and causal inference with machine learning algorithms** [link](https://github.com/uber/causalml)

### [Benchmark datasets](#content)

1. **Causality workbench** [link](http://www.causality.inf.ethz.ch/repository.php?page=data)

1. **Causal Inference** [link](https://paperswithcode.com/task/causal-inference)

### [Courses](#content)

1. **CS7792 - Counterfactual Machine Learning** [link](http://www.cs.cornell.edu/courses/cs7792/2016fa/)