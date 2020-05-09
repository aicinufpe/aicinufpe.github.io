---
layout: paper
title: "Real-Time Exploration of Large Spatiotemporal Datasets based on Order Statistics"
date: 2019-05-06
member_handle: [nivan]
year: 2019
journal: "IEEE Transactions on Visualization and Computer Graphics"
volume:
issue:
pages: 1-1
authors: ""
doi: "10.1109/TVCG.2019.2914446"
image: nivan-qds-2019.png
description: We propose the Quantile Datacube Structure (QDS) that supports interactive visual exploration based on order statistics.
arxiv: 
eprint:   
github:
category: paper
published: true
embargo: false
peerreview: true
review: false
tags: [Data visualization, Spatiotemporal phenomena , Real-time systems , Data structures]
project:
bibtex: >
  @ARTICLE{pahins2019real, 
       author={C. A. {de Lara Pahins} and N. {Ferreira} and J. {Comba}}, 
       journal={IEEE Transactions on Visualization and Computer Graphics}, 
       title={Real-Time Exploration of Large Spatiotemporal Datasets based on Order Statistics}, 
       year={2019}, 
       volume={}, 
       number={}, 
       pages={1-1}
  }
highlight: 1
---


# Abstract

In recent years sophisticated data structures based on datacubes have been proposed to perform interactive visual exploration of large datasets. While powerful, these approaches overlook the important fact that aggregations used to produce datacubes do not represent the actual distribution of the data being analyzed. As a result, these methods might produce biased results as well as hide important features in the data. In this paper, we introduce the Quantile Datacube Structure (QDS) that bridges this gap by supporting interactive visual exploration based on order statistics. To achieve this, QDS makes use of an efficient non-parametric distribution approximation scheme called p-digest and employs a novel datacube indexing scheme that reduces the memory usage of previous datacube methods. This enables interactive slicing and dicing while accurately approximating the distribution of quantitative variables of interest. We present two case studies that illustrate the ability of QDS to not only build order statistics based visualizations interactively but also to perform event detection on very large datasets. Finally, we present extensive experimental results that validate the effectiveness of QDS regarding memory usage and accuracy in the approximation of order statistics for real-world datasets.
