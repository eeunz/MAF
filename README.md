# MAF

MAF is  a bias mitigation framework in AI algorithms.  MAF aims to mitigate the bias of unstructured data as well as structured data. MAF compares and analyzes the original and relaxed values to represent them in charts. We are expanding by adding a bias mitigation algorithm developed by the consortium, and the MAF package is available on Python. MSIT AI Fair (MAF) is a bias mitigation framework based on aif360 that can detect and mitigate biases in machine learning models. It contains the basic features of AIF360, and it is being expanded by adding a bias mitigation algorithm developed by the consortium. The MAF package is available in Python.

The MAF package includes
1. a comprehensive set of metrics for the data set and model to test for bias,
2. Description of these metrics
3. Algorithms to mitigate bias in datasets and models. It is designed to translate the laboratory's algorithmic research into practical implementations in a wide range of areas such as voice, language, finance, referral systems, healthcare, recruitment, policing, advertising, law, culture, and broadcasting. We invite you to use it and improve it.

We developed the package with scalability in mind. This library is still under development. We recommend contributions from metrics, descriptors, and deflection elimination algorithms.

# Supported bias mitigation algorithms
1. Disparate_Impact_Remover
2. Learning_Fair_Representation
3. Reweighing
4. Gerry_Fair_Classifier
5. Meta_Fair_Classifier
6. Prejudice_Remover
7. FairBatch
8. FairFeatureDistillation(Image only)
9. FairnessVAE(Image only)
10. KernelDensityEstimator
11. LearningFromFairness(Image only)

# Algorithms to add
1. fair-manifold-pca
2. ~ 
3. ~
4. ~


# Supported fairness metrics
* Pre-Processing Bias Mitigation : Disparate_Impact_Remover, Learning_Fair_Representation, Reweighing
* In-Processing Bias Mitigation : Gerry_Fair_Classifier, Meta_Fair_Classifier, Prejudice_Remover
* Post-Processing Bias Mitigation : Calibrated_EqOdds, EqualizedOdds, RejectOption
* Sota : FairBatch, FairFeatureDistillation(Image only), FairnessVAE(Image only), KernelDensityEstimator, LearningFromFairness(Image only)


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

Then, to create a new Python 3.7 environment, run:

```bash
conda create --name MAF python=3.7
conda activate MAF
```

The shell should now look like `(MAF) $`. To deactivate the environment, run:

```bash
(MAF)$ conda deactivate
```

The prompt will return to `$ `.

Note: Older versions of conda may use `source activate MAF` and `source
deactivate` (`activate MAF` and `deactivate` on Windows).


### Install with `pip`

To install the latest stable version from PyPI, run:

```bash
pip install MAF
```

### Manual installation

Clone the latest version of this repository:

```bash
git clone https://github.com/konanaif/MAF.git
```



# Using MAF
example.ipynb is an example of how you can use MAF in different ways.
