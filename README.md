# Adversarial Attack 
### CNN(Convolutional Neural Network) 모델 대상 Adversarial Attack을 통한 인식영역의 오류 도출 PoC

## Author: Tackhyun Jung

## Status: 완료

![1](https://user-images.githubusercontent.com/41291493/109090196-f1590280-7755-11eb-9aea-49d36318bc96.png)

![2](https://user-images.githubusercontent.com/41291493/109090200-f322c600-7755-11eb-9257-c1ce9b70baeb.png)

### 핵심목표
1) CNN 모델에 기 학습된 데이터(이미지넷)를 활용하여 이미지 분류모델 구축 (완료)
2) Adversarial Attack code를 통한 CNN 모델의 인식영역에 오류 도출 (완료)

---

### 사용된 기술
* CNN(Convolutional Neural Network)
* Adversarial Attack

---

### Requirement
* Python 3x
* numpy
* keras
* PIL

---

### Usage

```
# Prediction
> python CNN.py

# Adversarial Attack
> python hacked.py
```

---
