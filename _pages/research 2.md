---
title: "OpAL Lab - Research"
layout: textlay
excerpt: "OpAL Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

Our goal in OpAL is to develop and implement new optimization formulations and algorithms for graph-based machine learning problems. We like to view graph-based problems and procedures from an optimization perspective, although they might not always be posed that way. We are equally interested in theory and in practice.

Questions of interest include: (i) what is the worst-case running time of an optimization algorithm?, (ii) what is the worst-case iteration complexity of an optimization algorithm? (iii) what are the prediction guarantees of a graph-model? 
(iv)  how do we parallelize optimization algorithms for graph-based learning in a communication efficient way? 

![]({{ site.url }}{{ site.baseurl }}/images/respic/sbm-example-louvian.pdf){: style="width: 300px; float: right; border: 10px"}

Currently, we pay special attention to local properties of the graph structure. Our goal is to exploit small- and meso-scale information from the graph to find tiny communities in huge graphs with provable guarantees and running time that depends on the size of the output instead of the size of the whole graph. Furthermore, we are interested in graph neural networks from a theoretical learning perspective and in particular our goal is to understand their inductive biases.

Moreover, we are currently working with the Waterloo-Huawei Joint Innovation Lab to develop parallel and communication efficient optimization algorithms for training graph neural networks that utilize attribute information in addition to the graph. The new methods will allow us to further speed-up applications such as node classification, link-prediction, community detection, graph classification and graph generation. We are also working in parallelizing classical (non-neural network) methods such spectral and combinatorial diffusion algorithms.

![]({{ site.url }}{{ site.baseurl }}/images/respic/usroads-flow-embed-u01-permute.png){: style="width: 300px; float: left; border: 10px"}

In the past we have worked on inexpensive higher-order methods for regression and classification problems in signal processing and machine learning. 
We developed new Newton-type and Interior-Point Methods and we focused on developing preconditioners for linear systems that arise in higher-order optimization methods.
Higher-order methods are especially efficient on ill-conditioned problems where first-order methods might perform poorly or even stagnate far away from a local or global minimizer.
We worked on worst-case iteration complexity results for our methods as well as guarantees of the preconditioners that we developed.

Although our application focus changes depending on academic needs and industrial needs of our scientific community, the principles and the tools (optimization, linear algebra, statistics and computing) based on which we conduct research remain the same.
