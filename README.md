# 📌 PyTorch 기반 CNN 모델 구현 및 CIFAR 데이터셋 실험

## 📂 프로젝트 소개
이 저장소는 **PyTorch**를 활용하여 **CNN(Convolutional Neural Networks)** 모델을 직접 구현하고,  
**CIFAR-10 & CIFAR-100 데이터셋**을 이용해 학습 및 실험을 수행하는 프로젝트입니다.

✔ 다양한 CNN 모델(VGGNet, ResNet, MobileNet, Custom CNN) 구현  
✔ **PyTorch**를 활용한 학습 및 평가 코드 제공  
✔ **CIFAR-10 / CIFAR-100**을 활용한 모델 비교 실험  
✔ `Jupyter Notebook` 기반으로 직접 실행하며 실험 가능  

---

## 📂 프로젝트 구조
```
CNN-Implementations/
│── data/                     # 데이터셋 (자동 다운로드 또는 직접 다운로드 가능)
│   ├── cifar-10-python.tar.gz   # CIFAR-10 데이터셋 (압축 파일)
│   ├── cifar-100-python.tar.gz  # CIFAR-100 데이터셋 (압축 파일)
│── models/                   # PyTorch 기반 CNN 모델 구현 (Jupyter Notebook)
│   ├── cnn_models.ipynb       # 모든 CNN 모델 정리 및 비교
│   ├── custom.ipynb           # Custom CNN 모델 구현 및 학습
│   ├── MLP.ipynb              # MLP(다층 퍼셉트론) 실험 코드
│   ├── MobileNet-V1.ipynb     # MobileNet-V1 구현 및 학습
│   ├── ResNet.ipynb           # ResNet 구현
│   ├── ResNet18.ipynb         # ResNet18 구현 및 CIFAR 학습
│   ├── Vgg.ipynb              # VGGNet 구현 및 학습
│── README.md                  # 프로젝트 설명
```

---

## 📥 데이터셋 다운로드 방법
이 프로젝트는 **CIFAR-10 및 CIFAR-100 데이터셋**을 사용합니다.  
데이터는 `data/` 폴더 내 `tar.gz` 형태로 포함되어 있으며, 아래 두 가지 방법 중 하나를 선택할 수 있습니다.

### ✅ **1. 자동 다운로드 (추천)**
각 Jupyter Notebook을 실행하면 데이터셋이 자동으로 다운로드됩니다.

### ✅ **2. 직접 다운로드**
- **[CIFAR-10 다운로드](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)**
- **[CIFAR-100 다운로드](https://www.cs.toronto.edu/~kriz/cifar-100-python.tar.gz)**

다운로드한 파일을 `data/` 폴더에 넣고 실행하세요.

---

## 🔥 모델 설명 (PyTorch 구현)
이 저장소에는 **PyTorch로 구현한 CNN 모델**이 포함되어 있으며, 다양한 네트워크를 실험할 수 있습니다.

| 파일명 | 설명 |
|--------|-------------------------------|
| `custom.ipynb` | Custom CNN 모델 (직접 설계) |
| `Vgg.ipynb` | VGGNet 구현 |
| `ResNet.ipynb` | ResNet 구현 |
| `ResNet18.ipynb` | ResNet18 구현 |
| `MobileNet-V1.ipynb` | MobileNet-V1 구현 |
| `cnn_models.ipynb` | ResNet18, MobileNet, Custom 모델을 비교 및 분석 |
| `MLP.ipynb` | 다층 퍼셉트론(MLP) 실험 |

각 모델을 실행하면 **CIFAR-10 및 CIFAR-100 데이터셋을 이용해 학습 및 평가**할 수 있습니다.

---

## 📊 학습 결과 예제
학습 후 모델의 성능을 평가한 예제 결과입니다.

| 모델 | 데이터셋 | 최종 정확도 (Top-1) |
|------|---------|-----------------|
| Custom CNN | CIFAR-10 | 93.68% |
| VGG-16 | CIFAR-10 | 90.71% |
| ResNet-18 | CIFAR-10 | 94.7% |
| MobileNet-V1 | CIFAR-10 | 90.47% |

---

## 📌 참고 자료
- [PyTorch 공식 문서](https://pytorch.org)
- [CIFAR 데이터셋 설명](https://www.cs.toronto.edu/~kriz/cifar.html)

---
