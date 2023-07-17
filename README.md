# MAF

MSIT AI Fair (MAF) is a bias mitigation framework based on aif360 that can detect and mitigate biases in machine learning models. It contains the basic features of AIF360, and it is being expanded by adding a bias mitigation algorithm developed by the consortium. The MAF package is available in Python.

# MAF package includes
1. ddf
2. dfsd
3. f4sfds


We developed the package with scalability in mind. This library is still under development. We recommend contributions from metrics, descriptors, and deflection elimination algorithms.

# Supported bias mitigation algorithms
1. Fairness VAE
2. Fair feature distillation
3. Learning from fairness
4. Kernel density estimation
5. FairBatch

# Algorithms to add
1.  Classifier-projection regularization
2.  GAN2GAN
3.  FBI-Denoiser
4.  Manifold-PCA


# Supported fairness metrics
* Error rate	
* Average odds difference
* Average abs odds difference
* Selection rate	
* Disparate impact
* Statistical parity difference
* Generalized entropy index
* Theil index
* Equal opportunity difference


# Setup
Supported Python Configurations:

| OS      | Python version |
| ------- | -------------- |
| macOS   | 3.7 – 3.10     |
| Ubuntu  | 3.7 – 3.10     |
| Windows | 3.7 – 3.10     |

### (Optional) Create a virtual environment

MAF requires specific versions of many Python packages which may conflict
with other projects on your system. A virtual environment manager is strongly
recommended to ensure dependencies may be installed safely. If you have trouble
installing MAF, try this first.


# Using MAF
The example directory contains a collection of different jupyter notebooks that use MAF in different ways. Both the tutorial and the demo show the code that works using MAF. Tutorials provide additional discussions that guide you through various steps in your notebook.
