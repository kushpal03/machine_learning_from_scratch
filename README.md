# Machine Learning Algorithms From Scratch

**Author:** Kush Pal

## Overview
This repository is a centralized portfolio of core machine learning algorithms implemented entirely from first principles. The primary objective is to translate the mathematical theories and statistical models—heavily inspired by *An Introduction to Statistical Learning* (ISLP)—into highly optimized, pure Python and NumPy code. 

By avoiding high-level abstractions and "black-box" libraries like `scikit-learn`, these implementations demonstrate a rigorous understanding of the underlying calculus, linear algebra, and continuous optimization techniques that power modern data science.

## Repository Structure
This is a growing monorepo. Each folder represents a specific algorithm or family of models, containing a standalone Jupyter Notebook with detailed mathematical derivations (LaTeX), code engines, and visual proofs.

### 1. [Linear Regression](./Linear_Regression/Simple_Linear_Regression.ipynb)
A pure Python implementation of Simple Linear Regression tested against synthetically generated datasets.
* **Method 1: Ordinary Least Squares (OLS)** - A closed-form, vectorized analytical solution to minimize the Residual Sum of Squares (RSS). *(Completed)*
* **Method 2: Gradient Descent** - An iterative numerical optimization approach to traverse the cost function. *(Coming Soon)*

## Tech Stack
* **Python 3**
* **NumPy:** For computationally efficient, vectorized mathematical operations.
* **Matplotlib:** For visualizing the mathematical signal (Model Estimate) versus the noise (True Population Line).
* **Jupyter Notebooks:** For combining narrative documentation, LaTeX equations, and execution cells in a professional format.

## Methodology
Every algorithm in this repository follows a strict scientific validation process:
1. **Mathematical Foundation:** The core cost functions and derivatives are explicitly defined.
2. **Engine Construction:** The math is translated into loop-free Python code.
3. **Synthetic Data Generation:** A test dataset is generated with known "true" population parameters and injected Gaussian noise.
4. **Evaluation & Visual Proof:** The algorithm is benchmarked to prove it can reliably extract the true mathematical signal from the synthetic noise.
