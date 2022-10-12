# Awesome Data Valuation

<img src="https://imgur.com/wkCjCds.png" alt="data market problem" width="400"/>

💱 A curated list of data valuation (DV) to design your next data marketplace. DV aims to understand the value of a data point for a given machine learning task and is an essential primitive in the design of data marketplaces and explainable AI.

### Legend
💻 Code available

🎥 Talk / Slides


## What is your data worth?

### Shapley Value & Cooperative Game Theory

[Towards Efficient Data Valuation Based on the Shapley Value](http://proceedings.mlr.press/v89/jia19a.html), Ruoxi Jia & David Dao, Boxin Wang, Frances Ann Hubis, Nick Hynes, Nezihe Merve Gürel, Bo Li, Ce Zhang, Dawn Song, Costas J. Spanos, 2019, [💻](https://github.com/sunblaze-ucb/data-valuation)

<details>
  <summary>Summary</summary>
Jia et al. (2019) contribute theoretical and practical results for efficient methods for approximating the Shapley value (SV). They show that methods with a sublinear amount of model evaluations are possible and further reductions can be made for sparse SVs. Lastly, they introduce two practical SV estimation methods for ML tasks, one for uniformly stable learning algorithms and one for smooth loss functions.
</details>

<details>
  <summary>Bibtex</summary>
  
```
@inproceedings{jia2019towards,
  title={Towards efficient data valuation based on the shapley value},
  author={Jia, Ruoxi and Dao, David and Wang, Boxin and Hubis, Frances Ann and Hynes, Nick and G{\"u}rel, Nezihe Merve and Li, Bo and Zhang, Ce and Song, Dawn and Spanos, Costas J},
  booktitle={The 22nd International Conference on Artificial Intelligence and Statistics},
  pages={1167--1176},
  year={2019},
  organization={PMLR}
}
```
 
</details>

[Data Shapley: Equitable Valuation of Data for Machine Learning](http://proceedings.mlr.press/v97/ghorbani19c.html), Amirata Ghorbani, James Zou, 2019, [💻](https://github.com/amiratag/DataShapley)

<details>
  <summary>Summary</summary>
Ghorbani & Zou (2019) introduce (data) Shapley value to equitably measure the value of each training point to a supervised learners performance. They further outline several benefits of the Shapley value, e.g. being able to capture outliers or inform what new data to acquire, as well as develop Monte Carlo and gradient-based methods for its efficient estimation.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{ghorbani2019data,
  title={Data shapley: Equitable valuation of data for machine learning},
  author={Ghorbani, Amirata and Zou, James},
  booktitle={International Conference on Machine Learning},
  pages={2242--2251},
  year={2019},
  organization={PMLR}
}
```
 
</details>

[A Distributional Framework for Data Valuation](https://arxiv.org/abs/2002.12334), Amirata Ghorbani, Michael P. Kim, James Zou, 2020, [💻](https://github.com/amiratag/DistributionalShapley)

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{ghorbani2020distributional,
  title={A Distributional Framework for Data Valuation},
  author={Ghorbani, Amirata, P. Kim, Michael and Zou, James},
  booktitle={International Conference on Machine Learning},
  year={2020}
}
```
 
</details>

[Asymmetric Shapley values: incorporating causal knowledge into model-agnostic explainability](https://proceedings.neurips.cc//paper/2020/hash/0d770c496aa3da6d2c3f2bd19e7b9d6b-Abstract.html), Christopher Frye, Colin Rowat, Ilya Feige, 2020, [🎥](https://www.youtube.com/watch?v=7d13f4UaAn0)

<details>
  <summary>Bibtex</summary>
  
```
@article{frye2020asymmetric,
  title={Asymmetric Shapley values: incorporating causal knowledge into model-agnostic explainability},
  author={Frye, Christopher and Rowat, Colin and Feige, Ilya},
  journal={Advances in Neural Information Processing Systems},
  volume={33},
  year={2020}
}
```
 
</details>

[Collaborative Machine Learning with Incentive-Aware Model Rewards](https://arxiv.org/abs/2010.12797), Rachael Hwee Ling Sim, Yehong Zhang, Mun Choon Chan, Bryan Kian Hsiang Low, 2020

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{sim2020collaborative,
  title={Collaborative machine learning with incentive-aware model rewards},
  author={Sim, Rachael Hwee Ling and Zhang, Yehong and Chan, Mun Choon and Low, Bryan Kian Hsiang},
  booktitle={International Conference on Machine Learning},
  pages={8927--8936},
  year={2020},
  organization={PMLR}
}
```
 
</details>

[Validation free and replication robust volume-based data valuation](https://proceedings.neurips.cc/paper/2021/hash/59a3adea76fadcb6dd9e54c96fc155d1-Abstract.html), Xinyi Xu, Zhaoxuan Wu, Chuan Sheng Foo, Bryan Kian Hsiang Low, 2021, [💻](https://github.com/ZhaoxuanWu/VolumeBased-DataValuation)

<details>
  <summary>Summary</summary>
Xu et al. (2021) propose using data diversity via robust volume for measuring the value of data. This removes the need for a validation set and allows for guarantees on replication robustness but suffers from the curse of dimensionality and may ignore useful information in the validation set.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@article{xu2021validation,
  title={Validation free and replication robust volume-based data valuation},
  author={Xu, Xinyi and Wu, Zhaoxuan and Foo, Chuan Sheng and Low, Bryan Kian Hsiang},
  journal={Advances in Neural Information Processing Systems},
  volume={34},
  year={2021}
}
```
 
</details>

[Beta Shapley: a Unified and Noise-reduced Data Valuation Framework for Machine Learning](https://arxiv.org/abs/2110.14049), Yongchan Kwon, James Zou, 2021

<details>
  <summary>Bibtex</summary>
  
  ```
@article{kwon2021beta,
  title={Beta Shapley: a Unified and Noise-reduced Data Valuation Framework for Machine Learning},
  author={Kwon, Yongchan and Zou, James},
  journal={arXiv preprint arXiv:2110.14049},
  year={2021}
}
```
 
</details>

[Gradient-Driven Rewards to Guarantee Fairness in Collaborative Machine Learning](https://proceedings.neurips.cc/paper/2021/hash/8682cc30db9c025ecd3fee433f8ab54c-Abstract.html), Xinyi Xu, Lingjuan Lyu, Xingjun Ma, Chenglin Miao, Chuan Sheng Foo, Bryan Kian Hsiang Low, 2021

<details>
  <summary>Summary</summary>
Xu et al. (2021) propose cosine gradient Shapley value to fairly evaluate the expected contribution of each agent's update in the federated learning setting removing the need for an auxiliary validation dataset. They further introduce a novel training-time gradient reward mechanism with a fairness guarantee.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@article{xu2021gradient,
  title={Gradient driven rewards to guarantee fairness in collaborative machine learning},
  author={Xu, Xinyi and Lyu, Lingjuan and Ma, Xingjun and Miao, Chenglin and Foo, Chuan Sheng and Low, Bryan Kian Hsiang},
  journal={Advances in Neural Information Processing Systems},
  volume={34},
  pages={16104--16117},
  year={2021}
}
```

</details>

[Improving Cooperative Game Theory-based Data Valuation via Data Utility Learning](https://arxiv.org/abs/2107.06336), Tianhao Wang, Yu Yang, Ruoxi Jia, 2022

<details>
  <summary>Summary</summary>
Wang et al. (2022) propose a general framework to improve effectiveness of sampling-based Shapley value (SV) or Least core (LC) estimation heuristics. They propose learning to predict the performance of a learning algorithm (denoted data utility learning) and using this predictor to estimate learning performance without retraining for cheaper SV and LC estimation.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@article{wang2021improving,
  title={Improving cooperative game theory-based data valuation via data utility learning},
  author={Wang, Tianhao and Yang, Yu and Jia, Ruoxi},
  journal={arXiv preprint arXiv:2107.06336},
  year={2021}
}
```

</details>

#### Efficient algorithms

[Efficient Task-Specific Data Valuation for Nearest Neighbor Algorithms](https://arxiv.org/abs/1908.08619), Ruoxi Jia, David Dao, Boxin Wang, Frances Ann Hubis, Nezihe Merve Gurel, Bo Li, Ce Zhang, Costas J. Spanos, Dawn Song, 2019, [💻](https://github.com/easeml/datascope)

<details>
  <summary>Summary</summary>
Jia et al. (2019) present algorithms to compute the Shapley value exactly in quasi-linear time and approximations in sublinear time for k-nearest-neighbor models. They empirically evaluate their algorithms at scale and extend them to several other settings.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@article{jia12efficient,
  title={Efficient Task-Specific Data Valuation for Nearest Neighbor Algorithms},
  author={Jia, Ruoxi and Dao, David and Wang, Boxin and Hubis, Frances Ann and Gurel, Nezihe Merve and Zhang, Bo Li4 Ce and Song, Costas Spanos1 Dawn},
  journal={Proceedings of the VLDB Endowment},
  volume={12},
  number={11}
}
```
 
</details>

[Efficient computation and analysis of distributional Shapley values](https://arxiv.org/abs/2007.01357), Yongchan Kwon, Manuel A. Rivas, James Zou, 2021, [💻](https://github.com/ykwon0407/fast_dist_shapley)

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{kwon2021efficient,
  title={Efficient computation and analysis of distributional Shapley values},
  author={Kwon, Yongchan and Rivas, Manuel A and Zou, James},
  booktitle={International Conference on Artificial Intelligence and Statistics},
  pages={793--801},
  year={2021},
  organization={PMLR}
}
```
 
</details>

#### Benchmarks, Criticism & Relaxations

[Scalability vs. Utility: Do We Have to Sacrifice One for the Other in Data Importance Quantification?](https://arxiv.org/abs/1911.07128), Ruoxi Jia, Fan Wu, Xuehui Sun, Jiacen Xu, David Dao, Bhavya Kailkhura, Ce Zhang, Bo Li, Dawn Song, 2021, [💻](https://github.com/AI-secure/Shapley-Study)

<details>
  <summary>Bibtex</summary>
  
  ```
@misc{jia2021scalability,
      title={Scalability vs. Utility: Do We Have to Sacrifice One for the Other in Data Importance Quantification?}, 
      author={Ruoxi Jia and Fan Wu and Xuehui Sun and Jiacen Xu and David Dao and Bhavya Kailkhura and Ce Zhang and Bo Li and Dawn Song},
      year={2021},
      eprint={1911.07128},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
 
</details>

[Shapley values for feature selection: The good, the bad, and the axioms](https://arxiv.org/abs/2102.10936), Daniel Fryer, Inga Strümke, Hien Nguyen, 2021

<details>
  <summary>Bibtex</summary>
 
  ```
@misc{fryer2021shapley,
      title={Shapley values for feature selection: The good, the bad, and the axioms}, 
      author={Daniel Fryer and Inga Strümke and Hien Nguyen},
      year={2021},
      eprint={2102.10936},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
  
</details>

### Influence functions & LOO

[Understanding Black-box Predictions via Influence Functions](http://proceedings.mlr.press/v70/koh17a), Pang Wei Koh, Percy Liang, 2017, [💻](https://bit.ly/gt-influence), [🎥](https://drive.google.com/open?id=1ZLY_9Wsk9MA0kXAoJDd6o1gbLvHhyPAn)

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{koh2017understanding,
  title={Understanding black-box predictions via influence functions},
  author={Koh, Pang Wei and Liang, Percy},
  booktitle={International Conference on Machine Learning},
  pages={1885--1894},
  year={2017},
  organization={PMLR}
}
```
 
</details>

[On the accuracy of influence functions for measuring group effects](https://arxiv.org/abs/1905.13289), Pang Wei Koh*, Kai-Siang Ang*, Hubert H. K. Teo*, and Percy Liang, 2019, [💻](https://github.com/kohpangwei/group-influence-release), [🎥](https://drive.google.com/open?id=1ZLY_9Wsk9MA0kXAoJDd6o1gbLvHhyPAn)

<details>
  <summary>Bibtex</summary>
  
  ```
@article{koh2019accuracy,
  title={On the accuracy of influence functions for measuring group effects},
  author={Koh, Pang Wei and Ang, Kai-Siang and Teo, Hubert HK and Liang, Percy},
  journal={arXiv preprint arXiv:1905.13289},
  year={2019}
}
```
 
</details>

### Reinforcement Learning

[Data Valuation using Reinforcement Learning](https://proceedings.mlr.press/v119/yoon20a.html), Jinsung Yoon Sercan Arik Tomas Pfister, 2020, [💻](https://github.com/google-research/google-research/tree/master/dvrl), [🎥](https://icml.cc/media/icml-2020/Slides/6276.pdf)

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{49189,
title	= {Data Valuation using Reinforcement Learning},
author	= {Jinsung Yoon and Sercan Arik and Tomas Pfister},
year	= {2020}
}
```
 
</details>

### Deep Neural Networks

[DAVINZ: Data Valuation using Deep Neural Networks at Initialization](https://proceedings.mlr.press/v162/wu22j.html), Zhaoxuan Wu, Yao Shu, Bryan Kian Hsiang Low, 2022, [🎥](https://icml.cc/media/icml-2022/Slides/17500.pdf)

<details>
  <summary>Summary</summary>
Wu et al. (2022) introduce a validation-based and training-free method for efficient data valuation with large and complex deep neural networks (DNNs). They derive and exploit a domain-aware generalization bound for DNNs to characterize their performance without training and uses this bound as the scoring function while keeping conventional techniques such as Shapley values as the valuation function.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{wu2022davinz,
  title={DAVINZ: Data Valuation using Deep Neural Networks at Initialization},
  author={Wu, Zhaoxuan and Shu, Yao and Low, Bryan Kian Hsiang},
  booktitle={International Conference on Machine Learning},
  pages={24150--24176},
  year={2022},
  organization={PMLR}
}
```
 
</details>

### Surveys

[Data Valuation in Machine Learning: “Ingredients”, Strategies, and Open Challenges](https://www.ijcai.org/proceedings/2022/782), Rachael Hwee Ling Sim*, Xinyi Xu*, Bryan Kian Hsiang Low, 2022, [🎥](https://xinyi-xu.com/ijcai_slides.pdf)

<details>
  <summary>Summary</summary>
Sim et al. (2022) present a technical survey of data valuation and its "ingredients" and properties. The paper outlines common desiderata as well as some open research challenges.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{sim2022data,
  title={Data valuation in machine learning:“ingredients”, strategies, and open challenges},
  author={Sim, Rachael Hwee Ling and Xu, Xinyi and Low, Bryan Kian Hsiang},
  booktitle={Proc. IJCAI},
  year={2022}
}
```
 
</details>


## Designing data marketplaces

### Data market system designs

[A demonstration of sterling: a privacy-preserving data marketplace](http://www.vldb.org/pvldb/vol11/p2086-hynes.pdf), Nick Hynes, David Dao, David Yan, Raymond Cheng, Dawn Song, 2018

<details>
  <summary>Bibtex</summary>
  
  ```
@article{hynes2018demonstration,
  title={A Demonstration of Sterling: A Privacy-Preserving Data Marketplace},
  author={Hynes, Nick and Dao, David and Yan, David and Cheng, Raymond and Song, Dawn},
  journal={Proceedings of the VLDB Endowment},
  volume={11},
  number={12},
  year={2018}
}
```
 
</details>


[DataBright: Towards a Global Exchange for Decentralized Data Ownership and Trusted Computation](https://arxiv.org/abs/1802.04780), David Dao, Dan Alistarh, Claudiu Musat, Ce Zhang, 2018

<details>
  <summary>Bibtex</summary>
  
  ```
@article{dao2018databright,
  title={Databright: Towards a global exchange for decentralized data ownership and trusted computation},
  author={Dao, David and Alistarh, Dan and Musat, Claudiu and Zhang, Ce},
  journal={arXiv preprint arXiv:1802.04780},
  year={2018}
}
```
 
</details>


[A Marketplace for Data: An Algorithmic Solution](https://arxiv.org/abs/1805.08125), Anish Agarwal, Munther Dahleh, Tuhin Sarkar, 2019

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{agarwal2019marketplace,
  title={A marketplace for data: An algorithmic solution},
  author={Agarwal, Anish and Dahleh, Munther and Sarkar, Tuhin},
  booktitle={Proceedings of the 2019 ACM Conference on Economics and Computation},
  pages={701--726},
  year={2019}
}
```
 
</details>


[Computing a Data Dividend](https://arxiv.org/abs/1905.01805), Eric Bax, 2019

<details>
  <summary>Bibtex</summary>
  
```
@misc{bax2019computing,
      title={Computing a Data Dividend}, 
      author={Eric Bax},
      year={2019},
      eprint={1905.01805},
      archivePrefix={arXiv},
      primaryClass={cs.GT}
}
```
 
</details>


[Incentivizing Collaboration in Machine Learning via Synthetic Data Rewards](https://arxiv.org/pdf/2112.09327.pdf), Sebastian Shenghong Tay, Xinyi Xu, Chuan Sheng Foo, Bryan Kian Hsiang Low, 2021

<details>
  <summary>Bibtex</summary>
  
```
@article{tay2021incentivizing,
  title={Incentivizing Collaboration in Machine Learning via Synthetic Data Rewards},
  author={Tay, Sebastian Shenghong and Xu, Xinyi and Foo, Chuan Sheng and Low, Bryan Kian Hsiang},
  journal={arXiv preprint arXiv:2112.09327},
  year={2021}
}
```
 
</details>

### Automatic data compliance

[Data Capsule: A New Paradigm for Automatic Compliance with Data Privacy Regulations
](https://arxiv.org/abs/1909.00077), Lun Wang, Joseph P. Near, Neel Somani, Peng Gao, Andrew Low, David Dao, Dawn Song, 2019, [💻](https://github.com/sunblaze-ucb/Data-Capsule)

<details>
  <summary>Bibtex</summary>
  
  ```
@misc{wang2019data,
      title={Data Capsule: A New Paradigm for Automatic Compliance with Data Privacy Regulations}, 
      author={Lun Wang and Joseph P. Near and Neel Somani and Peng Gao and Andrew Low and David Dao and Dawn Song},
      year={2019},
      eprint={1909.00077},
      archivePrefix={arXiv},
      primaryClass={cs.CY}
}
```
 
</details>

### Data valuation applications

[A Principled Approach to Data Valuation for Federated Learning](https://arxiv.org/abs/2009.06192), Tianhao Wang, Johannes Rausch, Ce Zhang, Ruoxi Jia, Dawn Song, 2020

<details>
  <summary>Bibtex</summary>
 
  ```
@misc{wang2020principled,
      title={A Principled Approach to Data Valuation for Federated Learning}, 
      author={Tianhao Wang and Johannes Rausch and Ce Zhang and Ruoxi Jia and Dawn Song},
      year={2020},
      eprint={2009.06192},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
  
</details>

[Data valuation for medical imaging using Shapley value and application to a large-scale chest X-ray dataset
](https://www.nature.com/articles/s41598-021-87762-2), Siyi Tang, Amirata Ghorbani, Rikiya Yamashita, Sameer Rehman, Jared A Dunnmon, James Zou, Daniel L Rubin, 2021

<details>
  <summary>Bibtex</summary>
 
  ```
@article{tang2021data,
  title={Data valuation for medical imaging using Shapley value and application to a large-scale chest X-ray dataset},
  author={Tang, Siyi and Ghorbani, Amirata and Yamashita, Rikiya and Rehman, Sameer and Dunnmon, Jared A and Zou, James and Rubin, Daniel L},
  journal={Scientific reports},
  volume={11},
  number={1},
  pages={1--9},
  year={2021},
  publisher={Nature Publishing Group}
}
```
  
</details>


## Data markets and society

### Economics of Data

[Nonrivalry and the Economics of Data](https://www.gsb.stanford.edu/faculty-research/working-papers/nonrivalry-economics-data), Charles I. Jones, Christopher Tonetti, 2019

<details>
  <summary>Bibtex</summary>
 
  ```
@article{10.1257/aer.20191330,
Author = {Jones, Charles I. and Tonetti, Christopher},
Title = {Nonrivalry and the Economics of Data},
Journal = {American Economic Review},
Volume = {110},
Number = {9},
Year = {2020},
Month = {September},
Pages = {2819-58},
DOI = {10.1257/aer.20191330},
URL = {https://www.aeaweb.org/articles?id=10.1257/aer.20191330}}
```
  
</details>


### Data Dignity

[Chapter 5: Data as Labor, Radical Markets](https://www.degruyter.com/document/doi/10.1515/9780691196978/html), Eric A. Posner and E Glen Weyl, 2019

<details>
  <summary>Bibtex</summary>
  
```
@book{posner2019radical,
  title={Radical Markets},
  author={Posner, Eric A and Weyl, E Glen},
  year={2019},
  publisher={Princeton University Press}
}
```
 
</details>


[Should We Treat Data as Labor? Moving beyond "Free"](https://www.aeaweb.org/articles?id=10.1257/pandp.20181003) Imanol Arrieta-Ibarra, Leonard Goff, Diego Jiménez-Hernández, Jaron Lanier, E. Glen Weyl, 2018

<details>
  <summary>Bibtex</summary>
  
 ```
@article{10.1257/pandp.20181003,
Author = {Arrieta-Ibarra, Imanol and Goff, Leonard and Jiménez-Hernández, Diego and Lanier, Jaron and Weyl, E. Glen},
Title = {Should We Treat Data as Labor? Moving beyond "Free"},
Journal = {AEA Papers and Proceedings},
Volume = {108},
Year = {2018},
Month = {May},
Pages = {38-42},
DOI = {10.1257/pandp.20181003},
URL = {https://www.aeaweb.org/articles?id=10.1257/pandp.20181003}}
```
  
</details>


## Strategic adaptation

### Performative prediction

[Performative Prediction](https://proceedings.mlr.press/v119/perdomo20a.html), Juan Perdomo, Tijana Zrnic, Celestine Mendler-Dünner, Moritz Hardt, 2020

<details>
  <summary>Summary</summary>
Perdomo et al. (2020) introduce the concept of "performative prediction" dealing with predictions that influence the target they aim to predict, e.g. through taking actions based on the predictions, causing a distribution shift. The authors develop a risk minimization framework for performative prediction and introduce the equilibrium notion of performative stability where predictions are calibrated against future outcomes that manifest from acting on the prediction.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{perdomo2020performative,
  title={Performative prediction},
  author={Perdomo, Juan and Zrnic, Tijana and Mendler-D{\"u}nner, Celestine and Hardt, Moritz},
  booktitle={International Conference on Machine Learning},
  pages={7599--7609},
  year={2020},
  organization={PMLR}
}
```

</details>

[Stochastic Optimization for Performative Prediction](https://papers.nips.cc/paper/2020/hash/33e75ff09dd601bbe69f351039152189-Abstract.html), Celestine Mendler-Dünner, Juan Perdomo, Tijana Zrnic, Moritz Hardt, 2020

<details>
  <summary>Summary</summary>
Mendler-Dünner et al. (2020) look at stochastic optimization for performative prediction and prove convergence rates for greedily deploying models after each stochastic update (which may cause distribution shift affecting convergence to a stability point) or lazily deploying the model after several updates.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@article{mendler2020stochastic,
  title={Stochastic optimization for performative prediction},
  author={Mendler-D{\"u}nner, Celestine and Perdomo, Juan and Zrnic, Tijana and Hardt, Moritz},
  journal={Advances in Neural Information Processing Systems},
  volume={33},
  pages={4929--4939},
  year={2020}
}
```

</details>

### Strategic classification

[Strategic Classification is Causal Modeling in Disguise](http://proceedings.mlr.press/v119/miller20b), John Miller, Smitha Milli, Moritz Hardt, 2020

<details>
  <summary>Summary</summary>
Miller et al. (2020) argue that strategic classification involves causal modelling and designing incentives for improvement requires solving a non-trivial causal inference problem. The authors provide a distinction between gaming and improvement as well as provide a causal framework for strategic adaptation.
</details>

<details>
  <summary>Bibtex</summary>
  
  ```
@inproceedings{miller2020strategic,
  title={Strategic classification is causal modeling in disguise},
  author={Miller, John and Milli, Smitha and Hardt, Moritz},
  booktitle={International Conference on Machine Learning},
  pages={6917--6926},
  year={2020},
  organization={PMLR}
}
```

</details>
