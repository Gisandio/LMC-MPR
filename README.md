# Entropy-Complexity Plane: Comparing MPR vs. LMC Complexity Using Bandt-Pompe and Histograms  

This repository provides code for computing and visualizing the **entropy-complexity plane**, leveraging both **LMC complexity** (López-Ruiz, Mancini, and Calbet) and **MPR complexity** (Martin, Plastino, and Rosso). The probability distributions are estimated using **histograms** and the **Bandt-Pompe (BP) method**, allowing direct comparisons between different approaches.  

The implementation is based on the **ordpy** library, which provides efficient tools for ordinal pattern analysis:  
[ordpy: A Python package for data analysis with permutation entropy and ordinal network methods](https://arthurpessa.github.io/ordpy/_build/html/index.html).  

(A. A. B. Pessa, H. V. Ribeiro, *Chaos* **31**, 063110 (2021). [arXiv:2102.06786](https://arxiv.org/abs/2102.06786))  

## Features  
- **Computation of statistical complexity measures**: Scripts to calculate **MPR complexity** (via Jensen-Shannon divergence) and **LMC complexity** (via Euclidean distance).  
- **Entropy-complexity plane generation**: Tools for visualizing different dynamical systems.  
- **Complexity bounds**: Computation of theoretical **maximum and minimum complexity curves**.  
- **Reproducible figures**: Scripts to generate key plots used in analysis.  

## Supported Systems  
- **Logistic Map** (\( r \)-parameterized)  
- **Hénon Map** (\( a, b \)-parameterized)  
- **Schuster Map** (with parameter \( q \))  
- **White and correlated noise** (for various \( D \))  

Figures illustrate the entropy-complexity plane for **BP with embedding dimension \( D \)** and **histograms with \( D! \) bins**, enabling a detailed characterization of dynamical behavior.  
