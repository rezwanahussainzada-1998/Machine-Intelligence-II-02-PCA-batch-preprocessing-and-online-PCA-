# PCA and Online Learning (Oja's Rule) Implementation

[cite_start]This repository contains a comprehensive practical analysis and implementation of **Principal Component Analysis (PCA)**, data preprocessing techniques, and online gradient-based learning via **Oja's Rule**[cite: 545]. [cite_start]The project explores how dimensionality reduction and unsupervised weight updates capture the dominant variance in statistical datasets over time[cite: 517, 545].

## Key Features & Explorations

* [cite_start]**Batch PCA & Outlier Preprocessing:** Investigated the sensitivity of PCA to anomalies[cite: 547]. [cite_start]Implemented automated heuristics (such as standard deviation thresholds) to detect and purge outliers, restoring the orthogonal alignment of principal components[cite: 493, 496].
* [cite_start]**Data Sphering & Whitening:** Applied whitening transformations to eliminate pairwise correlations and normalize variances across dimensions, verifying the transformation matrices via covariance heatmaps[cite: 501, 507].
* [cite_start]**Mathematical Derivation of Oja's Rule:** Included a first-order Taylor expansion proof demonstrating how Oja's rule approximates explicit constraint normalization for small learning rates to prevent Hebbian weight divergence[cite: 518, 519, 521].
* [cite_start]**Online PCA Simulation:** Simulated real-time, online learning by streaming data blocks sequentially[cite: 524, 530]. [cite_start]Analyzed the tracking performance and stability of weight vector trajectories under varying learning rates ($\epsilon \in \{0.002, 0.04, 0.45\}$) against a unit circle constraint[cite: 529, 538].

## Repository Structure

* [cite_start]`Sheet02Themostprinciplecomponent.pdf`: The full academic report containing comprehensive mathematical proofs, experimental results, and analytical plots.
* [cite_start]`*.ipynb` (Jupyter Notebook): Step-by-step executable Python pipeline implementing the data cleaning, visualization, batch PCA, and Oja's neural network updates[cite: 528, 534].

---
*Note: For the full mathematical derivations, detailed performance discussions, and complete visualization charts, please refer directly to the attached PDF report.*
