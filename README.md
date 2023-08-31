# MAF

MSIT AI Fair(MAF)는 과학기술정보통신부 “인공지능 모델과 학습데이터의 편향성 분석-탐지-완화-제거 지원 프레임워크 개발(2019-2022)” 국가과제의 일환으로 개발된 프레임워크로 인공지능(AI)의 공정성을 진단하고 편향성을 교정하는 진단 시스템입니다.

MAF는 데이터 편향성과 알고리즘 편향성을 측정 및 완화하는 것을 목표로 합니다. MAF는 IBM에서 공개한 AI Fairness 360(AIF360)의 브랜치로 시작하여 AIF360의 기본 기능을 담고 있으며, 과제 수행 기간 중 컨소시엄 내에서 개발된 편향성 완화 알고리즘의 추가, 지원 데이터 형식 추가, CPU 환경 지원 추가 등의 기능을 계속 확장하고 있습니다.

MAF 패키지는 python 환경에서 사용할 수 있습니다.


MAF 패키지에는 다음이 포함됩니다
1. 편향성을 테스트할 데이터 세트
2. 모델에 대한 메트릭 세트 및 메트릭에 대한 설명
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
2. (추가할 알고리즘 작성 예정)
3. 
4. 

# Supported fairness metrics
* Pre-Processing Bias Mitigation : Disparate_Impact_Remover, Learning_Fair_Representation, Reweighing
* In-Processing Bias Mitigation : Gerry_Fair_Classifier, Meta_Fair_Classifier, Prejudice_Remover
* Post-Processing Bias Mitigation : Calibrated_EqOdds, EqualizedOdds, RejectOption
* Sota : FairBatch, FairFeatureDistillation(Image only), FairnessVAE(Image only), KernelDensityEstimator, LearningFromFairness(Image only)


# Setup
Supported Python Configurations:

| OS      | Python version |
| ------- | -------------- |
| macOS   | 3.8 – 3.11     |
| Ubuntu  | 3.8 – 3.11     |
| Windows | 3.8 – 3.11     |

### (Optional) Create a virtual environment

MAF에는 시스템의 다른 프로젝트와 충돌할 수 있는 많은 Python 패키지의 특정 버전이 필요합니다. 종속성이 안전하게 설치되도록 하려면 anaconda 가상 환경을 사용하는 것이 좋습니다.

### Install with pip
PyPI에서 최신 버전을 설치하려면 다음을 실행하세요.

```bash
pip install maf
```

### Install with pip
이 저장소의 최신 버전을 복제합니다.
```bash
git clone https://github.com/.../maf
```

### Using MAF
예제 디렉터리에는 MAF를 다양한 방식으로 사용하는 다양한 jupyter 노트북이 포함되어 있습니다. 

