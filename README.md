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


# Set up

Supported Python Configurations:

| OS      | Python version |
| ------- | -------------- |
| macOS   | 3.7 – 3.10     |
| Ubuntu  | 3.7 – 3.10     |
| Windows | 3.7 – 3.10     |

### (Optional) Create a virtual environment

AIF360 requires specific versions of many Python packages which may conflict
with other projects on your system. A virtual environment manager is strongly
recommended to ensure dependencies may be installed safely. If you have trouble
installing AIF360, try this first.

#### Conda

Conda is recommended for all configurations though Virtualenv is generally
interchangeable for our purposes. [Miniconda](https://conda.io/miniconda.html)
is sufficient (see [the difference between Anaconda and
Miniconda](https://conda.io/docs/user-guide/install/download.html#anaconda-or-miniconda)
if you are curious) if you do not already have conda installed.

Then, to create a new Python 3.7 environment, run:

```bash
conda create --name aif360 python=3.7
conda activate aif360
```

The shell should now look like `(aif360) $`. To deactivate the environment, run:

```bash
(aif360)$ conda deactivate
```

The prompt will return to `$ `.

Note: Older versions of conda may use `source activate aif360` and `source
deactivate` (`activate aif360` and `deactivate` on Windows).

### Install with `pip`

To install the latest stable version from PyPI, run:

```bash
pip install aif360
```

Note: Some algorithms require additional dependencies (although the metrics will
all work out-of-the-box). To install with certain algorithm dependencies
included, run, e.g.:

```bash
pip install 'aif360[LFR,OptimPreproc]'
```

or, for complete functionality, run:

```bash
pip install 'aif360[all]'
```

The options for available extras are: `OptimPreproc, LFR, AdversarialDebiasing,
DisparateImpactRemover, LIME, ART, Reductions, FairAdapt, inFairness,
LawSchoolGPA, notebooks, tests, docs, all`

If you encounter any errors, try the [Troubleshooting](#troubleshooting) steps.


# Setup


# Using MAF

