---
title: "Intro to Laplacian paradigm 2.0"
time: 08:40 -- 9:10
author: Richard Peng
draft: true
---

Spectral algorithms originated with the use of eigenvalues and eigenvectors to analyze graphs, and have wide applications in machine learning, image processing, and network science. Over the past decade, the synergy of spectral algorithms with tools from scientific computing and combinatorial graph theory has led to the Laplacian paradigm for designing graph algorithms. For a wide range of fundamental graph problems such as max-flow, stationary distributions of random walks, or even shortest paths with general weights, the current best algorithms on sparse graphs utilize ideas related to graph Laplacians.
A common theme among algorithms usually described as ‘spectral algorithms’ – including foundational algorithms in the Laplacian paradigm – has been a clear transition between combinatorial and numerical components. This delineation is exemplified by spectral graph partitioning, which first computes eigenvectors of the graph Laplacian numerically, then clusters them using geometry and combinatorics.
On the other hand, a hallmark of recent progresses in linear systems, optimization, and numerical problems broadly related to graph Laplacians is a tighter, more fine-grained integration of combinatorial and numerical components. These algorithms are built on deeper understanding of concepts introduced by earlier works in the Laplacian paradigm, such as effective resistances of edges, Schur complements, and graph (re)sparsification.
This workshop will survey the recent progress, with a focus on the rich connections exposed by the new ways of combining algorithmic constructs. The morning and afternoon sessions will focus on two overarching themes in these algorithms: the use of effective resistances in place of combinatorial graph theory, and the study of elimination-based algorithms on structured matrices.


