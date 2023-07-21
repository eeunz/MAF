# MAF

MAF is  a bias mitigation framework in AI algorithms.  MAF aims to mitigate the bias of unstructured data as well as structured data. MAF compares and analyzes the original and relaxed values to represent them in charts. We are expanding by adding a bias mitigation algorithm developed by the consortium, and the MAF package is available on Python. MSIT AI Fair (MAF) is a bias mitigation framework based on aif360 that can detect and mitigate biases in machine learning models. It contains the basic features of AIF360, and it is being expanded by adding a bias mitigation algorithm developed by the consortium. The MAF package is available in Python.

# MAF package includes
## 1. Pre-Processing Bias Mitigation
Pre-processing techniques for deflection mitigation are very important. Certain characteristics of the training data can directly cause problems in the learned model. For this reason, many techniques for preprocessing focus on modifying training sets to overcome dataset imbalance versions. This can be achieved in a variety of ways, including resampling data rows, rebalancing data rows, inverting class labels between groups, and omitting critical variables or proxies. By modifying the training data in this way, the output of the learned classifier will be less biased.
## 2. In-Processing Bias Mitigation
~~
## 3. Post-Processing Bias Mitigation
~~

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
## 1. Pre-Processing Bias Mitigation : Disparate_Impact_Remover, Learning_Fair_Representation, Reweighing
## 2. In-Processing Bias Mitigation : Gerry_Fair_Classifier, Meta_Fair_Classifier, Prejudice_Remover
## 3. Post-Processing Bias Mitigation : Calibrated_EqOdds, EqualizedOdds, RejectOption
## 4. Sota : FairBatch, FairFeatureDistillation, FairnessVAE, KernelDensityEstimator, LearningFromFairness


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
