# Awesome GFlowNets   [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of resources about generative flow networks (GFlowNets).

## Table of Contents
- [Monograph \& Tutorial](#monograph)
- [Paper](#paper)
- [Workshop paper \& Note](#workshop)

<a name="monograph" />

## Monograph \& Tutorial
[GFlowNet Foundations](https://arxiv.org/abs/2111.09266) [theoretical framework]  
Yoshua Bengio, et al.

[GFlowNets for AI-Driven Scientific Discovery](https://arxiv.org/abs/2302.00615) [review paper]  
Moksh Jain, et al.

[The GFlowNet Tutorial](https://milayb.notion.site/The-GFlowNet-Tutorial-95434ef0e2d94c24aab90e69b30be9b3) [high level introduction]  
Yoshua Bengio. 

[GFlowNet Tutorial](https://colab.research.google.com/drive/1fUMwgu2OhYpQagpzU5mhe9_Esib3Q2VR) [PRACTICAL colab notebook]  
Emmanuel Bengio.

<a name="paper" />

## Paper

<!-- ### Modeling \& training -->

[Multi-Fidelity Active Learning with GFlowNets](https://arxiv.org/abs/2306.11715)  
Alex Hernandez-Garcia, et al. [[code](https://github.com/nikita-0209/mf-al-gfn)] 

[Joint Bayesian Inference of Graphical Structure and Parameters with a Single Generative Flow Network](https://arxiv.org/abs/2305.19366)  
Tristan Deleu, et al. NeurIPS 2023. [[code](https://github.com/tristandeleu/jax-jsp-gfn)]  

[Let the Flows Tell: Solving Graph Combinatorial Optimization Problems with GFlowNets](http://arxiv.org/abs/2305.17010)   
Dinghuai Zhang, et al. NeurIPS 2023 spotlight. [[code](https://github.com/zdhNarsil/GFlowNet-CombOpt)]

[DynGFN: Bayesian Dynamic Causal Discovery using Generative Flow Networks](https://arxiv.org/abs/2302.04178) [GFlowNet for Bayesian dynamical causal discovery]  
Lazar Atanackovic, et al. NeurIPS 2023. [[code](https://github.com/lazaratan/dyn-gfn)]  

[Stochastic Generative Flow Networks](https://arxiv.org/abs/2302.09465) [model-based GFlowNets for stochastic transitions]  
Ling Pan, et al. UAI 2023 spotlight. [[code](https://github.com/ling-pan/Stochastic-GFN)]  

[GFlowNet-EM for Learning Compositional Latent Variable Models](https://arxiv.org/abs/2302.06576) [GFlowNet for latent posterior]  
Edward Hu, et al. ICML 2023.   [[code](https://github.com/GFNOrg/GFlowNet-EM)]  

[Distributional GFlowNets with Quantile Flows](https://arxiv.org/abs/2302.05793) [distributional GFlowNets for stochastic rewards]  
Dinghuai Zhang, et al. [[code](https://github.com/zdhNarsil/Distributional-GFlowNets)]   

[Better Training of GFlowNets with
Local Credit and Incomplete Trajectories](http://arxiv.org/abs/2302.01687) [forward-looking GFlowNet]  
Ling Pan, et al. ICML 2023. [[code](https://github.com/ling-pan/FL-GFN)]  

[Unifying Generative Models with GFlowNets and Beyond](https://arxiv.org/abs/2209.02606)  
Dinghuai Zhang, et al. ICML 2022 Beyond Bayes workshop.

[A theory of continuous generative flow networks](https://arxiv.org/abs/2301.12594) [GFlowNet on continuous space]  
Salem Lahlou, et al. ICML 2023. [[code]](https://github.com/saleml/continuous-gfn)

[Multi-Objective GFlowNets](https://arxiv.org/abs/2210.12765)  
Moksh Jain, et al. ICML 2023.  [[code]](https://github.com/GFNOrg/multi-objective-gfn)    

[Learning GFlowNets from partial episodes for improved convergence and stability](https://arxiv.org/abs/2209.12782) [SubTB criterion]  
Kanika Madan, et al. ICML 2023 oral. [[code]](https://github.com/GFNOrg/gflownet/tree/subtb) 

[GFlowOut: Dropout with Generative Flow Networks](https://arxiv.org/abs/2210.12928)  
Dianbo Liu, et al. ICML 2023.  

[Generative Augmented Flow Networks](https://arxiv.org/abs/2210.03308) [enabling intermediate rewards]  
Ling Pan, et al. ICLR 2023 spotlight. [[code]](https://github.com/ling-pan/GAFN)  

[GFlowNets and variational inference](https://arxiv.org/abs/2210.00580)  
Nikolay Malkin, et al. ICLR 2023. [[code]](https://github.com/GFNOrg/GFN_vs_HVI)  

[Trajectory Balance: Improved Credit Assignment in GFlowNets](https://arxiv.org/abs/2201.13259)  [trajectory balance (TB) criterion]  
Nikolay Malkin, et al. NeurIPS 2022. [[code]](https://github.com/GFNOrg/gflownet/tree/trajectory_balance)

[Bayesian Structure Learning with Generative Flow Networks](https://arxiv.org/abs/2202.13903) [causal graph Bayesian posterior]  
Tristan Deleu, et al. UAI 2022. [[code]](https://github.com/tristandeleu/jax-dag-gflownet)

[Generative Flow Networks for Discrete Probabilistic Modeling](https://arxiv.org/abs/2202.01361) [energy-based GFlowNet]    
Dinghuai Zhang, et al. ICML 2022. [[code]](https://github.com/zdhnarsil/EB_GFN)

[Biological Sequence Design with GFlowNets](https://arxiv.org/abs/2203.04115)  
Moksh Jain, et al. ICML 2022. [[code]](https://github.com/MJ10/BioSeq-GFN-AL)

[Flow Network based Generative Models for Non-Iterative Diverse Candidate Generation](https://arxiv.org/abs/2106.04399)  [first GFlowNet paper]    
Emmanuel Bengio, et al. NeurIPS 2021. [[blog post]](http://folinoid.com/w/gflownet) [[code]](https://github.com/GFNOrg/gflownet)

<a name="workshop" />

## Workshop paper \& Note

[An Empirical Study of the Effectiveness of Using a Replay Buffer on Mode Discovery in GFlowNets](https://arxiv.org/abs/2307.07674)  
Nikhil Vemgal, et al. ICML 2023 SPIGM workshop.

[Generative Flow Networks: a Markov Chain Perspective](https://arxiv.org/abs/2307.01422) [merge the initial and the terminal states]  
Tristan Deleu, et al.

[Thompson sampling for improved exploration in GFlowNets](https://arxiv.org/abs/2306.17693)  
Jarrid Rector-Brooks, et al. ICML 2023 SPIGM workshop.

[BatchGFN: Generative Flow Networks for Batch Active Learning](https://arxiv.org/abs/2306.15058)  
Shreshth A. Malik, et al. ICML 2023 SPIGM workshop. [[code](https://github.com/s-a-malik/batchgfn)]

[Goal-conditioned GFlowNets for Controllable Multi-Objective Molecular Design](https://arxiv.org/abs/2306.04620)   
Julien Roy, et al.

[Bayesian learning of Causal Structure and Mechanisms
with GFlowNets and Variational Bayes](https://arxiv.org/abs/2211.02763)  [DAG-GFlowNet with parameters]  
Mizu Nishikawa-Toomey, et al.  

[Evaluating Generalization in GFlowNets for Molecule Design](https://openreview.net/forum?id=JFSaHKNZ35b)  
Andrei Cristian Nica, et al. ICML 2022 MLDD workshop.

## Contact
If you have any suggestion or want to add your own work, please feel free to drop a message to [dinghuai.zhang@mila.quebec](mailto:dinghuai.zhang@mila.quebec).
