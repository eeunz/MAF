# MAF

MSIT AI Fair(MAF)는 편향 완화 프레임워크입니다. MAF는 정형 데이터뿐만 아니라 비정형 데이터의 편향을 완화하는 것을 목표로 합니다. MAF는 Aif360을 기반으로 AIF360의 기본 특징을 담고 있으며, 우리는 컨소시엄에서 개발한 편향 완화 알고리즘을 추가하여 확장하고 있습니다. MAF 패키지는 파이썬에서 사용할 수 있습니다.

MAF 패키지에는 다음이 포함됩니다
1. 편향성을 테스트할 데이터 세트 및 모델에 대한 메트릭 세트,
2. 이러한 메트릭에 대한 설명
3. 데이터 세트 및 모델의 편향을 완화하는 알고리즘. 연구소의 알고리즘 연구를 음성, 언어, 금융, 의뢰 시스템, 의료, 채용, 치안, 광고, 법률, 문화, 방송 등 광범위한 분야에서 활용하기 위해 설계되었습니다. 

우리는 확장성을 염두에 두고 패키지를 개발했습니다. 이 라이브러리는 개발 진행중입니다.

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

MAF에는 시스템의 다른 프로젝트와 충돌할 수 있는 많은 Python 패키지의 특정 버전이 필요합니다. 종속성이 안전하게 설치되도록 하려면 가상 환경 관리자를 사용하는 것이 좋습니다. MAF를 설치하는 데 문제가 있으면 먼저 이것을 시도하십시오.

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
example.ipynb는 MAF를 다양한 방식으로 사용할 수 있는 예입니다.
