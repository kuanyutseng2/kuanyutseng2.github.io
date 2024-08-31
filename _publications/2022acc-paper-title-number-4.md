---
title: "Low-Fidelity Gradient Updates for High-Fidelity Reprogrammable Iterative Learning Control"
collection: publications
permalink: /publication/2022acc
excerpt: "Extended abstract also published in NeurIPS 2021 Workshop on Deployable Decision Making in Embodied Systems (DDM)\
<br/><img src='/images/2022acc.png'>"
date: 2022-06-08
venue: '2022 American Control Conference (ACC)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.23919/ACC53348.2022.9867601'
authors: <b>Kuan-Yu Tseng</b>, Jeff S. Shamma, Geir E. Dullerud

---
\[[Paper](https://doi.org/10.23919/ACC53348.2022.9867601)\] \
\
Extended abstract "GRILC: Gradient-based Reprogrammable Iterative Learning Control for Autonomous Systems",
 published in NeurIPS 2021 Workshop on Deployable Decision Making in Embodied Systems (DDM)
\[[Paper](http://kuanyut2.github.io/files/NeurIPS_2021_Workshop_on_DDM__revised_cameraReady1_.pdf)\]

## Abstract

We propose a novel gradient-based reprogrammable iterative learning control (GRILC) framework for autonomous systems. Performance of trajectory following in autonomous systems is often limited by mismatch between a complex actual model and a simplifed nominal model used in controller design. To overcome this issue, we develop the GRILC framework with offline optimization using the information of the nominal model and the actual trajectory, and online system implementation. In addition, a reprogrammable learning strategy is introduced which incorporates directly the learned primitives stored into a library, for future motion planning. The proposed method is applied to the autonomous time-trialing example. The simulation and experimental results illustrate the effectiveness and robustness of the proposed approach.


![2022acc](/images/2022acc.png)

## Citation: 
@inproceedings{tseng2022low,\
  title={Low-Fidelity Gradient Updates for High-Fidelity Reprogrammable Iterative Learning Control},\
  author={Tseng, Kuan-Yu and Shamma, Jeff S and Dullerud, Geir E},\
  booktitle={2022 American Control Conference (ACC)},\
  pages={4772--4777},\
  year={2022},\
  organization={IEEE}\
}