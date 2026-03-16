# DynFlowDrive
> Xiaolu Liu, Yicong Li, Song Wang, Junbo Chen, Angela Yao, Jianke Zhu

This is the code implementation of **DynFlowDrive: Flow-Based Dynamic World
Modeling for Autonomous Driving** (arXiv 2026)  [[Paper](https://arxiv.org/abs/xxxx.xxxxx)] 

## Abstract
Recently, world models have been incorporated into the autonomous driving systems to improve the planning reliability. Existing approaches typically predict future states through appearance generation or deterministic regression, which limits their ability to capture trajectory-conditioned scene evolution and leads to unreliable action planning. To address this, we propose DynFlowDrive, a latent world model that leverages flow-based dynamics to model the transition of world states under different driving actions. By adopting the rectifiedflow formulation, the model learns a velocity field that describes how the scene state changes under different driving actions, enabling progressive prediction of future latent states. Building upon this, we further introduce a stability-aware multi-mode trajectory selection strategy that evaluates candidate trajectories according to the stability of the induced
scene transitions. Extensive experiments on the nuScenes and NavSim benchmarks demonstrate consistent improvements across diverse driving frameworks without introducing additional inference overhead.

<p align="center"> <a><img src="figs/teaser_github.png" width="90%"></a> </p>
