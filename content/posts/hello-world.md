+++
date = '2025-06-08T22:05:24-05:00'
draft = false
title = 'Hello World'
+++

Sparsity-based blind source separation (BSS) algorithms in the short time–frequency (TF) domain have received a
lot of attention due to their versatility and noise reduction capabilities. In most of these algorithms, the estimation of the BSS filters
relies on the accurate association of each time–frequency bin to the
dominant source at that bin. The TF bin associations are then used
to estimate the statistics of the source signals, and BSS is achieved
by optimal spatial filters computed using the estimated statistics.
The main objective of this paper is to apply such a framework
to scenarios with an unknown number of moving sources. While
state-of-the-art approaches employ online clustering algorithms to
solve the problem for moving sources, we propose an approximate
Bayesian tracker and perform the association of each TF bin to
the dominant source using the tracker’s measurement-to-source
association probabilities. Therefore, the choice of the underlying
narrowband models and measurements for the tracker as well as
the resulting tracking algorithm constitute the main contributions
of this paper. The TF bin associations obtained from the tracker
are then used to estimate the statistics of the source signals. The
performance of the resulting BSS filters is compared to the performance of state-of-the-art sparsity-based and independent vector
analysis-based BSS algorithms. Our proposed approach targets
scenarios with at least two spatially separated microphone arrays,
with known microphone positions and relative orientations. The
framework also allows for efficient management of a time-varying
number of sources
