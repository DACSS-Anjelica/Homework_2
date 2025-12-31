# **Homework 2 – Network Analysis of Actor Collaborations**

This repository contains my submission for Homework 2, which focuses on analyzing a small social network using R. The network represents actors, where nodes are actors and edges indicate whether two actors have appeared in a movie together. Edge weights reflect how many times actors have worked together.

## **Contents**

* `homework-2.Rmd` – R Markdown file containing all code, analysis, and explanations

* `index.html` – Rendered HTML output published with GitHub Pages

* `hollywood.graphml` – Network data file used for the analysis


## **Methods**

In this assignment, I:

* Loaded and visualized an undirected, weighted network using igraph and ggraph

* Computed node-level centrality measures (eigenvector, closeness, betweenness)

* Examined correlations among centrality measures

* Evaluated the possible presence of communities using transitivity and modularity

* Applied Girvan–Newman and Louvain community detection algorithms

* Visualized the resulting communities

* Centrality measures were computed without using edge weights, meaning all co-acting relationships were treated equally.

## **Results**

The analysis suggests that actors tend to cluster into collaboration groups rather than forming a fully random network. Community detection methods identified two main groups of actors, with Girvan–Newman producing slightly higher modularity than Louvain for this dataset.

## **Published output**

The rendered HTML version of this assignment is available here:
https://dacss-anjelica.github.io/Homework_2/
