**PCA and Online Learning (Oja's Rule) Implementation**

This repository contains a comprehensive practical analysis and implementation of Principal Component Analysis (PCA), data preprocessing techniques, and online gradient-based learning via Oja's Rule. The project explores how dimensionality reduction and unsupervised weight updates capture the dominant variance in statistical datasets over time.

Key Features & Explorations

Batch PCA & Outlier Preprocessing: Investigated the sensitivity of PCA to anomalies. Implemented automated heuristics (such as standard deviation thresholds) to detect and purge outliers, restoring the orthogonal alignment of principal components.

Data Sphering & Whitening: Applied whitening transformations to eliminate pairwise correlations and normalize variances across dimensions, verifying the transformation matrices via covariance heatmaps.

Mathematical Derivation of Oja's Rule: Included a first-order Taylor expansion proof demonstrating how Oja's rule approximates explicit constraint normalization for small learning rates to prevent Hebbian weight divergence.

Online PCA Simulation: Simulated real-time, online learning by streaming data blocks sequentially. Analyzed the tracking performance and stability of weight vector trajectories under varying learning rates against a unit circle constraint.

Repository Structure

Sheet02Themostprinciplecomponent.pdf: The full academic report containing comprehensive mathematical proofs, experimental results, and analytical plots.

Jupyter Notebook: Step-by-step executable Python pipeline implementing the data cleaning, visualization, batch PCA, and Oja's neural network updates.

Note: For the full mathematical derivations, detailed performance discussions, and complete visualization charts, please refer directly to the attached PDF report.
